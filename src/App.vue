<template>
  <div id="app">
    <Header/>
    <main></main>
    <section></section>
    <footer></footer>

  </div>
</template>

<script>
import Header from './components/Header.vue';


export default {
  name: 'App',
  components: {
    Header,
    
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
  width: 70%;
  margin: 0 auto;
}

.container{
  width: 70%;
  margin: 0 auto;
}
</style>
