<template>
  <div id="app">
    
    <Header />

    <div class="containerFullBlack">
      <Contents />
    </div>  

    <div class="containerFullBlue">
      <Bonus />
    </div>

    <div class="containerFooter">
      <Footer />
    </div>

    <div class="containerFollowUs">
      <FollowUs />
    </div>
  </div>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Contents from './components/Contents.vue'
import Bonus from './components/Bonus.vue'
import Footer from './components/Footer.vue'
import FollowUs from './components/FollowUs.vue'


export default {
  name: 'App',
  components: {
    Header,
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

  .containerFullBlack {
    background-color: black;
  }
  .containerFullBlue {
    background-color: #0C7CEC;
  }
  .containerFooter {
    background-image: url(./assets/img/dc-logo-bg.png), url(./assets/img/footer-bg.jpg);
    background-position: center right, center bottom;
    background-repeat: no-repeat;
  }
  .containerFollowUs {
    background-color: #303030;
  }
  


</style>
