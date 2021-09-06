<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="LOGO">
        <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
        </ul>
    </header>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style scoped>
    header{
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 125px;
        border-top: 25px solid black;
        padding-top: 25px;
    }

    img{
        height: 100%;
    }

    ul{
        flex-basis: 40%;
        display: flex;
        justify-content: space-around;
    }

    li a{
        color: black;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;    
        font-size: 15px;
        text-transform: uppercase;
        padding-bottom: 30px;
    }

    a:hover{
        color: dodgerblue;
        border-bottom: 5px solid dodgerblue;
    }

</style>