<template>
  <img alt="Medieval Scroll" src="./assets/medieval.png">
  <IndexMain msg="Welcome to Your Vue.js App"/>
</template>

<script>
import IndexMain from './components/Index.vue'

export default {
  name: 'App',
  components: {
    IndexMain
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
