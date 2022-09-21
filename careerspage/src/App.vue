<template>
  <MainNav/> 
  <main-nav/>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>{{myname}}</h1>
  <HelloWorld msg="Welcome"/>
 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainNav from './components/MainNav.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MainNav,
},

data() {
  return {
     myname : "Tichaona Zvidzayi"
  }
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
