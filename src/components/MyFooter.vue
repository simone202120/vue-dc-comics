<template>
<div class="container1">
    <div class="containerFoot">
        <div class="container-link">
            <div>
                <h4>DC COMICS</h4>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>

                <h4>SHOP</h4>
                <ul>
                    <li><a href="#">Shop</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>

                </ul>
            </div>

            <div>
                <h4>DC</h4>
                <ul>
                    <li><a href="#">Therms of use</a></li>
                    <li><a href="#">Privacy policy (new)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscription</a></li>
                    <li><a href="#">Taent Workshop</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact US</a></li>
                </ul>
            </div>

            <div>
                <h4>SITES</h4>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">Mad Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>

                </ul>
            </div>
            
        </div>
        <div class="logo-bg">
            <img id="footimg" src="../assets/dc-logo-bg.png" alt="">
        </div>
    </div>
</div>
</template>

<script>
export default {
    name:'MyFooter'
}
</script>

<style scoped lang="scss">
    .container1{
        background-image: url("../assets/footer-bg.jpg");
        height: 400px;
    }
    .containerFoot{
       margin: 0 15%;
       display: flex;
       justify-content: space-between;

    }

    #footimg{
        object-fit: cover;
        height: 100%;
        width: 100%;
    }

    .container-link{
        display: flex;
        margin-top: 40px;
        justify-content: space-between;
        width: 40%;

        h4{
            color:white;
            margin-bottom: 15px;
            margin-top:15px;
            font-size: 20px;
        }
    }

    li,a{
        color:gray;
        padding: 5px 0px;
        font-size: 12px;
        text-decoration: none;
        
        &:hover{
            color: white;
            font-weight: 500;
        }
    }

    .logo-bg{
         height: 400px;
       
    }
    


</style>