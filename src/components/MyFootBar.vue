<template>
<div class='container'>
  <div class="container-footbar">
        <div>
            <button><a href="#">SIGN-UP NOW!</a></button>
        </div>

        <div class="social">
            <h2>FOLLOW US</h2>
            <img src="../assets/footer-facebook.png" alt="">
            <img src="../assets/footer-periscope.png" alt="">
            <img src="../assets/footer-pinterest.png" alt="">
            <img src="../assets/footer-twitter.png" alt="">
            <img src="../assets/footer-youtube.png" alt="">
        </div>
  </div>
</div>
</template>

<script>
    export default {
        name:'MyFootbar'
    }
</script>

<style scoped lang="scss">
    .container{
        background-color: #303030;
    }
    .container-footbar{
        margin: 0 15%;
        padding:20px 0;
        display: flex;
        justify-content: space-between;

    }
    button{
        border: solid 2px #0282f9;
        background-color: #303030;
        color: white;
        padding: 10px;
       

         &:hover{
            scale: 1.2;
            }
        a{
            color: white;
            text-decoration: none;
        }
    }
    
    H2{
        color: #0282f9;
        display: inline;
        font-size: 16px;
        margin-right: 20px;
    }
    
    img{
        height: 20px;
        margin-right: 10px;
    }
    .social{
        display: flex;
        align-items: center;
    }
</style>