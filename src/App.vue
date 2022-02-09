<template>
  <div id="app">
    <Header  :links="links"/>
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
  },
  data(){
    return{
      links:[
        {text:'CHARACTERS', url:'#'},
        {text:'COMICS', url:'#'},
        {text:'MOVIES', url:'#'},
        {text:'TV', url:'#'},
        {text:'GAMES', url:'#'},
        {text:'COLLECTIBLES', url:'#'},
        {text:'VIDEOS', url:'#'},
        {text:'FANS', url:'#'},
        {text:'NEWS', url:'#'},
        {text:'SHOP', url:'#'},
      ]
    };
  },
};
</script>

<style lang="scss">
@import './assets/sass/style.scss';
</style>
