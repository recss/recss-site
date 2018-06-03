<template>
  <div id="app">
    <!-- <img src="./assets/noun_38753_cc.svg"> -->
    <!-- <router-view/> -->
    <HelloWorld></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
*,
*::before,
*::after {
  box-sizing: border-box;
}

html,
body {
  height: 100%;
  width: 100%;
  margin: 0;
}

img {
  max-width: 100%;
  object-fit: contain;
}

#app {
  min-height: 100vh;
  border: 1em solid #333;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(245,245,245);
  display: grid;
    grid: 100% / repeat(12, 1fr);
    justify-content: center;
    justify-items: center;
}

#app > * {
  width: 100%;
  background-color: #fff;
  grid-column: 2 / span 10;
}

@media (min-width: 1000px) {
  #app > * {
    grid-column: 3 / span 8;
  }
}
</style>
