<template>
  <div id="app">
    
    <Header />

    <div class="containerFullBlack">
      <Contents />
    </div>  

    <div class="containerFullBlue">
      <Bonus />
    </div>


  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Contents from './components/Contents.vue'
import Bonus from './components/Bonus.vue'


export default {
  name: 'App',
  components: {
    Header,
    Contents,
    Bonus
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

  .containerFullBlack {
    background-color: black;
  }
  .containerFullBlue {
    background-color: #0C7CEC;
  }
  


</style>
