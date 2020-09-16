<template>
  <div id="app">
    
   <page-header></page-header>
   <page-body></page-body>
   <page-footer></page-footer>
  </div>
</template>

<script>
import PageHeader from "./components/header.vue";
import PageBody from "./components/body.vue";
import PageFooter from "./components/footer.vue";
export default {
  name: 'App',
  components: {
    PageHeader, PageFooter, PageBody
  
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
