
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Vue Props</h1>
    <Parent />
  </div>
</template>

<script>
import Parent from './components/Parent.vue'

export default {
  name: 'App',
  components: {
    Parent
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
