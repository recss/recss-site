<template>
  <div class="hello">
    <div id="logo-skew"></div>
    <section id="logo-container">
      <svg id="logo" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" x="0px" y="0px" viewBox="0 0 100 100" enable-background="new 0 0 100 100" xml:space="preserve">
        <path d="M85.228,58.529c-3.63-2.096-8.005-1.703-11.177,0.632L58.182,50l18.664-10.775l5.04-7.634l-9.131,0.548L54.091,42.914  V24.591c3.609-1.58,6.136-5.172,6.136-9.364C60.227,9.579,55.648,5,50,5S39.773,9.579,39.773,15.227  c0,4.192,2.527,7.784,6.136,9.364v18.323l-15.869-9.162c0.437-3.915-1.411-7.9-5.041-9.996c-4.892-2.824-11.147-1.148-13.971,3.744  c-2.824,4.892-1.148,11.146,3.744,13.971c3.63,2.096,8.005,1.703,11.177-0.632L41.818,50L23.155,60.775l-5.04,7.634l9.131-0.548  l18.664-10.775v18.323c-3.609,1.579-6.136,5.172-6.136,9.364C39.773,90.421,44.352,95,50,95s10.227-4.579,10.227-10.227  c0-4.192-2.527-7.785-6.136-9.364V57.086l15.869,9.162c-0.437,3.915,1.411,7.9,5.041,9.996c4.892,2.824,11.147,1.148,13.971-3.743  C91.795,67.608,90.119,61.353,85.228,58.529z"/>
      </svg>
    </section>

    <section id="content">
      <h1>Kevin K. Johnson, II</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Et netus et malesuada fames ac turpis egestas integer eget. Varius vel pharetra vel turpis nunc eget lorem dolor sed. Semper viverra nam libero justo laoreet sit amet cursus sit. Convallis aenean et tortor at risus viverra adipiscing at. Euismod in pellentesque massa placerat duis ultricies lacus sed turpis. Faucibus vitae aliquet nec ullamcorper sit amet risus nullam. Arcu ac tortor dignissim convallis. Gravida dictum fusce ut placerat orci nulla pellentesque dignissim enim. </p>

      <p>Dolor sit amet consectetur adipiscing. Commodo nulla facilisi nullam vehicula ipsum a arcu. Vitae et leo duis ut diam quam. Senectus et netus et malesuada fames. Mattis rhoncus urna neque viverra justo. Viverra nibh cras pulvinar mattis nunc. Lectus nulla at volutpat diam ut. Tortor at risus viverra adipiscing at in tellus. Molestie ac feugiat sed lectus vestibulum mattis.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#logo-container {
  padding-bottom: 1.25em;
  background-color: #333;
  transform: translateY(-100px);
}
#logo {
  max-width: 200px;
  padding: 1em;
  stroke: rgba(249,233,27,0.40);
  /* fill: rgba(255,255,255,0.05); */
  /* filter: drop-shadow(3px 3px rgba(255,255,255,0.15)); */
  transform: translateY(25px);
}
#logo-skew {
  height: 100px;
  /* border-bottom: 0.5em solid rgba(249,233,27,0.40); */
  background-color: #333;
  transform: skew(0, -3deg) translateY(160px);
}
#content {
  padding: 0 2em 1em;
  text-align: left;
  transform: translateY(-2em);
}
#content h1 {
  margin-top: 0;
}
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  border-bottom: 1px solid rgba(249,233,27,0.75);
  color: rgba(249,233,27,0.75);
  text-decoration: none;
  transition: 0.3s;
}

a:focus,
a:hover {
  color: rgba(249,233,27,0.40);
}

@media (min-width: 850px) {
  #content {
    transform: translateY(-1em);
  }
}
</style>
