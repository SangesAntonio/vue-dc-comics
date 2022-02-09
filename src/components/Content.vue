<template>
  <main>
      <div class=" cartoon-section">
          <div class="banner-small">
              <h3>CURRENT SERIES</h3>
          </div>
      </div>
      <div class="container cards">
          <Programcard v-for='(program, index) in programs' 
          :key='index' 
          :program='program'/>
      </div>
      <div class="container button-blue">
          <p>LOAD MORE</p>
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
        height: 550px;
        background-image: url(../assets/img/jumbotron.jpg);
        color: white;
        position: relative;
    }

    .cards{
        display: flex;
        flex-wrap: wrap;
        padding-top: 50px;
    }
    .banner-small{
        width: 250px;
        height: 50px;
        background-color: dodgerblue;
        padding: 10px;
        color: white;
        position: relative;
        bottom: -475px;
        left: 250px;
        text-align: center;

        h3{
            
        }
    }
    .button-blue{
        width: 100px;
        height: 30px;
        background-color: dodgerblue;
        padding: 10px;
        color: white;
        

        p{
            font-size: 0.8rem;
        }
    }
}
</style>