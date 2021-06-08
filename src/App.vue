<template>
  <div id="app">
    
    <Header />
    
    <Jumbotron />

    <Contents />
     
    <Bonus />
    
    <Footer />
 

    <FollowUs />
  </div>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Contents from './components/Contents.vue'
import Bonus from './components/Bonus.vue'
import Footer from './components/Footer.vue'
import FollowUs from './components/FollowUs.vue'
import Jumbotron from './components/Jumbotron.vue'


export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Contents,
    Bonus,
    Footer,
    FollowUs
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



  .containerFollowUs {
    background-color: #303030;
  }
  


</style>
