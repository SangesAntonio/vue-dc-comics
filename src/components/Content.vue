<template>
  <main>
      <div class=" cartoon-section">
          
      </div>
      <div class="container cards">
          <Programcard v-for='(program, index) in programs' 
          :key='index' 
          :programs='program'/>
      </div>

  </main>
</template>

<script>
import Programcard from './Programcard.vue'
export default {
    name: 'Content',
    components:{
        Programcard,
    },
    props:['programs'],
    
}
</script>

<style scoped lang="scss">
main{
    background-color: #1C1C1C;

    .cartoon-section{
        height: 500px;
        background-image: url(../assets/img/jumbotron.jpg);
        color: white;
    }

    .cards{
        display: flex;
        flex-wrap: wrap;
        padding-top: 50px;
        
    }
}
</style>