<template>
  <div id="app">
    <Header/>
    <MainContent/>
    <Info/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import MainContent from './components/MainContent.vue'
import Info from './components/Info.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    MainContent,
    Info,
    Footer,
  },
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

ul{
  list-style-type: none;
}

a{
  text-decoration: none;
}
</style>
