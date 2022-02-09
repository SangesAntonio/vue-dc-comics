<template>
    <div class="card">
      <figure>

        <img :src="program.thumb" alt="">
      </figure>
      <p>{{program.series}}</p>
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
  width: calc(100% / 6);
  color: white;
  margin-bottom: 30px;
  padding: 15px;
  overflow: hidden;
    
  figure{
    width: 170px;
    height: 170px;
    
    img{
      width: 170px;
      height: 170px;
      object-fit: cover;
      object-position: top left;

    }

  }
  
}
p{    
  font-size: 0.9rem;
  margin-top: 15px;

}

</style>