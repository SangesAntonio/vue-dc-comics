<template>
  <footer>
      <div class="container">
          <div class="lists">

          <div class="list">
            <h2>DC COMICS</h2>
            <ul>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">TV</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">News</a></li>
            </ul>
            <h2>SHOP</h2>
            <ul>
                <li><a href="">Shop DC</a></li>
                <li><a href="">Shop DC collectibles</a></li>
            </ul>
          </div>
          <div class="list">
            <h2>DC </h2>
            <ul>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">TV</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">News</a></li>
              <li><a href="">News</a></li>
              <li><a href="">News</a></li>
              <li><a href="">News</a></li>
              <li><a href="">News</a></li>
            </ul>
            
          </div>
          <div class="list">
             <h2>SITES</h2>
             <ul>
                <li><a href="">Characters</a></li>
                <li><a href="">Comics</a></li>
                <li><a href="">Movies</a></li>
                <li><a href="">TV</a></li>
             </ul>
          </div>

      </div>
      <div class="img-dc">
          
      </div>
    </div>
            
  </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scope>
footer{
    background-image: url(../assets/img/footer-bg.jpg);
}

.lists{
    display: flex;
    padding: 30px 0;
}
.list{
    padding: 0 20px;
}
.list ul li{
    list-style-type: none;
    padding: 3px 0;

}
.list ul li a{
    text-decoration: none;
    color: gray;
    font-size: 0.8rem;
    font-weight: normal;

}

h2{
    font-size: 1.2rem;
    color: white;
    margin: 5px 0;
}
.img-dc{
    content: '';
    widows: 100%;
    height: auto;
}

</style>