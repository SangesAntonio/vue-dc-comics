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
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
          </ul>
          
        </div>
      </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
header{
  height: 140px;
}
.navbar{
  padding-top: 30px;
  display: flex;
  background-color: white;
  justify-content: space-between;
}
nav ul li{
  list-style-type: none;
}
nav ul li a{
  text-decoration: none;
  color: rgb(56, 56, 56);
  margin: 0px 20px;
  font-size: 0.7rem;
  font-family: 'Lato', sans-serif;
  font-weight: bold;
}
nav ul {
  display: flex;
  justify-content: center;
}
.right-nav{
  display: flex;
  align-items: center;
  width: calc(100 / 2);
}




</style>