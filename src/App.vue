<template>
  <div id="app">
    <Header>
    <Content/>
    <Jumbotron/>
    <Footer/>

  </div>
</template>

<script>


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
</style>
