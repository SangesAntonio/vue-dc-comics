<template>
  <div id="app">
    <Header/>
    <Content/>
    <section></section>
    <footer></footer>

  </div>
</template>

<script>
import Header from './components/Header.vue';
import Content from './components/Content.vue';


export default {
  name: 'App',
  components: {
    Header,
    Content,
    
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body{
  min-width: 100vh;

}

.container{
  width: 70%;
  margin: 0 auto;
}
</style>
