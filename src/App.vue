<template>
  <div id="app">
    <!-- Goi component Header -->
    <Header></Header>
    <ListUser></ListUser>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/>  -->
    <!-- msg la prop cua component HelloWorld -->
    <Footer></Footer>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header'
import Footer from './components/Footer'
import ListUser from './components/ListUser'
export default {
  name: 'app',
  // Khai bao cac component
  components: {
    HelloWorld,
    Header,
    Footer,
    ListUser
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
