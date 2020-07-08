<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <img alt="Vue logo" src="./assets/logo-novo2.png">
    <HelloWorld msg="Bem Vindo ao Curso do VueJS!!!"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
