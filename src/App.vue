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
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

img{
  max-width: 100%;
  height: auto;
}

body{
  min-width: 100vh;
  font-family: 'Lato', sans-serif;

}

.container{
  width: 70%;
  margin: 0 auto;
}
</style>
