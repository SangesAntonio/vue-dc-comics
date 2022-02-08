<template>
   <footer>
     <div class="top-footer">

       
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
      </div>
     </div>
      <div class="bottom-footer">
        <div class="container bottom">
            <div class="left-bottom">
                <a href="#">SIGN UP NOW</a>
            </div>
            <div class="right-bottom">
                <ul>
                    <li class="text-social">FOLLOW US</li>
                    <li><a href=""><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                    <li><a href=""><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                    <li><a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                    <li><a href=""><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                    <li><a href=""><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                    
                </ul>
            </div>
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
.top-footer{
    background-image: url(../assets/img/footer-bg.jpg);
}
.bottom-footer{
    background-color: #303030;
}
.bottom{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 46px 0;
    
}
.lists{
    display: flex;
    padding: 30px 0;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right;
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
    margin-top: 5px;
}

.left-bottom a{
    width: 100px;
    height: 40px;
    padding: 10px 15px;
    text-decoration: none;
    border: 2px solid dodgerblue;
    color: white;
}

.right-bottom ul li{
  list-style-type: none;
  margin: 0 10px;
}
.right-bottom ul{
    display: flex;
    align-content: center;
}

.text-social{
    display: flex;
    align-items: center;
    color: dodgerblue;
}


</style>