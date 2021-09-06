<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="LOGO">
        <ul>
            <li v-for="(link, index) in links" :key="index"><a href="link.url">{{link.text}}</a></li>
        </ul>
    </header>
</template>

<script>
export default {
    name: "Header",
    data(){
        return {
            links: [
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
  {
    text: 'Shop',
    url: '#',
    current: false,
  },
],
        }
    }
}
</script>

<style scoped lang="scss">
    header{
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 125px;
        border-top: 25px solid #1C1C1C;
        padding-top: 5px;
        img{
            height: 80%;
        }
        ul{
            flex-basis: 40%;
            display: flex;
            justify-content: space-around;
            a{
                color: black;   
                font-size: 15px;
                text-transform: uppercase;
                padding-bottom: 33px;
                &:hover{
                    color: dodgerblue;
                    border-bottom: 5px solid dodgerblue;
                }
            }
        }
    }

</style>