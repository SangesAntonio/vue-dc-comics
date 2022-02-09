<template>
  <ul>
    <li><a :href="link.url">{{link.text}}</a></li>
  </ul>
</template>

<script>
export default {
    name: 'headerNav',
    props:['link'],

}
</script>

<style lang='scss'>
nav {
  ul {
    display: flex;
    justify-content: center;
    
    li{
      list-style-type: none;

        a{
          text-decoration: none;
          color: rgb(56, 56, 56);
          margin: 0px 20px;
          font-size: 0.7rem;
          font-weight: bold;
      }
    }
  }
}

.right-nav{
  display: flex;
  align-items: center;
  width: calc(100 / 2);
}

</style>