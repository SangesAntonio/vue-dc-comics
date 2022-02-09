<template>
  <header class="">
      <nav class="navbar container">
        <div class="left-nav">
          <a href="#">
            <img src="../assets/img/dc-logo.png" alt="">
          </a>
        </div>
        <div class="right-nav">
          <ul>
            <HeaderNav v-for= "(link, index) in links" 
            :key="index"
            :link="link"/>
          </ul>
        </div>
      </nav>
  </header>
</template>

<script>
import HeaderNav from './HeaderNav.vue'
export default {
  name: 'Header',
  components:{
    HeaderNav,
  },
  props: ['links'],
  
}
</script>
<style scoped lang="scss">
header{
  height: 140px;
  padding: 30px 0;
}
.navbar{
  display: flex;
  background-color: white;
  justify-content: space-between;
}
</style>