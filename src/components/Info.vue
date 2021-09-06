<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <h3>DC Comics</h3>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <h3>Shop</h3>
                <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="col">
                <h3>DC</h3>
                <ul>
                    <li><a href="#">Terms of Use</a></li>
                    <li><a href="#">Privacy Policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshop</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div class="col">
                <h3>Sites</h3>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
        <img src="../assets/img/dc-logo-bg.png" alt="Logo">
    </div>
</template>

<script>
export default {
    name: "Info",
}
</script>

<style scoped>
    .container{
        height: 400px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;
        display: flex;
        align-items: center;
        justify-content: space-around;
    }

    .row{
        width: 30%;
        display: flex;
        justify-content: space-around;
        text-align: left;
    }

    h3{
        color: white;
        font-size: 20px;
        margin-top: 15px;
        margin-bottom: 10px;
    }

    a{
        color: #959595;
    }

    a:hover{
        color: white;
    }
</style>