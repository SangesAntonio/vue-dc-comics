<template>
  <div>
    <div class="card">
      
        <img :src="program.thumb" alt="">
      
      <p>{{program.series}}</p>
    </div>
      
  </div>
</template>

<script>
export default {
  name: 'Programcard',
  props:['program']

}
</script>

<style scoped lang="scss">
.card{
  flex-basis: calc(100% / 6);
  padding: 15px;
  color: white;
  margin-bottom: 30px;
    
  .img{
    object-fit: cover;
    width: 170px;
    height: 170px;
    

  }
  
}
p{    
  font-size: 0.9rem;
  margin-top: 15px;

}

</style>