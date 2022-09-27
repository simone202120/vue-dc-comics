<template>
  <div class="containerSection">
        <div class="icons">
            <div class="icon"><a href="#"><img src="../assets/buy-comics-digital-comics.png" alt="">Digital Comics</a></div>
            <div class="icon"><a href="#"><img src="../assets/buy-comics-merchandise.png" alt="">DC Merchandise</a></div>
            <div class="icon"><a href="#"><img src="../assets/buy-comics-shop-locator.png" alt="">Shop Locator</a></div>
            <div class="icon"><a href="#"><img src="../assets/buy-comics-subscriptions.png" alt="">Subscription</a></div>
            <div class="icon"><a href="#"><img src="../assets/buy-dc-power-visa.svg" alt="">DC Power Visa</a></div>
        </div>
  </div>
</template>

<script>
    export default {
        name: 'MySection',
        
    }
</script>

<style scoped lang="scss">
    .containerSection{
        background-color: #0282f9;
        height: 100px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .icons{
        display: flex;
        justify-content: center;


         img{
        height: 40px;
        margin-right: 10px;
         }
        
    }
    
    .icon a{
        display: flex;
        align-items: center;
        margin: 15px;
        color: white;
        font-size: 12px;
        text-decoration: none;

         &:hover{
            scale: 1.2;
        }
    }
</style>