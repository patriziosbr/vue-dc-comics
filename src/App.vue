<template>
  <div id="app">
    
    <Header/>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
  * {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  }
  body {
    font-family: Arial, Helvetica, sans-serif;
  }
  


</style>
