<template>
    <footer>
        <button>Sign-up Now!</button>
        <div class="social-media">
            <span>Follow Us</span>
            <a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a>
            <a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a>
            <a href="#"><img src="../assets/img/footer-youtube.png" alt="YouTube"></a>
            <a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a>
            <a href="#"><img src="../assets/img/footer-periscope.png" alt="Periscope"></a>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style scoped lang="scss">
    footer{
        background-color: #303030;
        height: 120px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        button{
            color: white;
            text-transform: uppercase;
            background-color: transparent;
            border: 2px solid dodgerblue;
            border-radius: 0%;
            font-size: 17px;
            padding: 15px;
            cursor: pointer;
        }
        .social-media{
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 20%;
            span{
                font-size: 17px;
                color: dodgerblue;
                text-transform: uppercase;
            }
            img{
                height: 40px;
            }
        }
    }


</style>