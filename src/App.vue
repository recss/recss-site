<template>
  <div id="app">
    <div id="icon"></div>
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
#icon {
    height: 150px;
    width: 150px;
    margin: 0 auto 2em;
    border-radius: 75px;
    background-color: rgba(0,0,0,0.15);
    background-image: url('./assets/jacqui-icon.png');
    background-size: 100px;
    background-position: 27px 15px;
    background-repeat: no-repeat;
}
</style>
