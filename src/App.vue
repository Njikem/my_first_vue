<template>
  <div id="app">
    <MyHeader/>
    <MyBody/>
    <MyFooter/>
 
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyBody from './components/MyBody.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyBody,
    MyFooter,
    MyHeader
},

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
