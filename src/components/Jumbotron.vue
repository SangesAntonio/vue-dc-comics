<template>
 <section class="bg-blue">
     <div class="cards container">
         <div class="card">
             <img src="../assets/img/buy-comics-digital-comics.png" alt="Merch">
             <h4>DIGITAL COMICS</h4>
         </div>
         <div class="card">
             <img src="../assets/img/buy-comics-merchandise.png" alt="Merch">
             <h4>DC MERCHANDISE</h4>
         </div>
         <div class="card">
             <img src="../assets/img/buy-comics-subscriptions.png" alt="Merch">
             <h4>SUBSCRIPTIONS</h4>
         </div>
         <div class="card">
             <img src="../assets/img/buy-comics-shop-locator.png" alt="Merch">
             <h4>COMIC SHOP LOCATOR</h4>
         </div>
         <div class="card">
             <img src="../assets/img/buy-dc-power-visa.svg" alt="Merch">
             <h4>   DC POWER VISA</h4>
         </div>
         

     </div>
 </section>

</template>

<script>
export default {
    name: 'Jumbotron',
}
</script>

<style scoped>
.bg-blue{
    background-color: #0282F9;
}

.cards{
    padding: 40px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.card{
    color: white;
    display: flex;
    align-items: center;
    width: calc(100% / 5);
    margin: 20px;
    
}
.card img{
    width: 60px;
    padding-right: 5px;
}
h4{
    font-size: 0.8rem;
    font-weight: 300;
}
</style>