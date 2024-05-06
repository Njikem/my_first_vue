<template>

 <div class="header">
<img style="width:30px" v-bind:src="image_source"/>
<h2>{{contact}}</h2>
<h2>{{aboutus}}</h2>
<img  style="width:30px" v-bind:src="image"/>
  </div>
</template>

<script>

export default {
  name: 'MyHeader',
  components: {
    
},
data: function(){
    return{
       image_source: "https://cdn-icons-png.flaticon.com/128/15623/15623739.png",
        contact: "CONTACT",
        aboutus: "ABOUT US",
        image: "https://cdn-icons-png.flaticon.com/128/2976/2976215.png",
    }
}

}
</script>

<style>

.header{
    display: flex;
    justify-content: space-between;
}

</style>
