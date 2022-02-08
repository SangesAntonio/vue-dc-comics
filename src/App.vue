<template>
  <div id="app">
    <Header/>
    <Content/>
    <Jumbotron/>
    <Footer/>

  </div>
</template>

<script>
import Header from './components/Header.vue';
import Content from './components/Content.vue';
import Jumbotron from './components/Jumbotron.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: {
    Header,
    Content,
    Jumbotron,
    Footer,
    
  }
}
</script>

<style lang="scss">
@import './assets/sass/style.scss';
</style>
