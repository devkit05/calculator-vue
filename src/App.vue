<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Calculator></Calculator>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Calculator from "./components/CalComp.vue"
export default {
  name: 'App',
  components: {
    // HelloWorld,
    Calculator
  }
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
