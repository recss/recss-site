<template>
  <div id="app">
    <About msg=""/>
  </div>
</template>

<script>
import About from './components/About.vue'

export default {
  name: 'app',
  components: {
    About
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
