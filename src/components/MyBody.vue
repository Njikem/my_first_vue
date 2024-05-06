<template>
  <div>
    <Article/>
    <meet-the-team></meet-the-team>
    <meet-the-developer></meet-the-developer>
    <p id="p_tag">{{body}}</P>
  </div>
</template>

<script>
import Article from './Article.vue'
import MeetTheTeam from './MeetTheTeam.vue' 
import MeetTheDeveloper from './MeetTheDeveloper.vue'


export default {
  name: 'MyBody',
  components: {
    Article,
    MeetTheTeam,
    MeetTheDeveloper
},
 
 data: function(){
  return{
    body: 'An apple is a round, edible fruit produced by an apple tree. Apple trees are cultivated worldwide and are the most widely grown species in the genus Malus. The tree originated in Central Asia, where its wild ancestor, Malus sieversii, is still found',
  }
 }
}
</script>

<style>

#p_tag{
  margin-top: 30px;
  width: 90%;
  padding-left: 60px;
}

</style>