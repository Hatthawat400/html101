<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

<div class="row">
  <div class="col-3"><Counter lable="ok"/></div>
  <div class="col-3"><Counter lable="ชอบ"/></div>
  <div class="col-3"><Counter lable="รัก"/></div>
  <div class="col-3"><Counter lable="เกลียด"/></div>
</div>
  
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Counter from './components/Counter'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Counter, 
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
