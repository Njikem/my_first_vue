<template>
  <div id="footer">
    <h4>{{about}}</h4>
    <h4>{{contact}}</h4>
    <h4>{{phone_number}}</h4>

 
  </div>
</template>

<script>

export default {
  name: 'MyFooter',
  components: {
},
   data: function(){
        return{
            about: "About Us",
            contact: "Address:253 Enright Way",
            phone_number: "Number:780-230-2215"
        }
    }
}
</script>

<style>
 #footer{
    display: flex;
    justify-content: space-between;
 }
</style>
