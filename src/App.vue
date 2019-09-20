<template>
  <div id="app">
    <!-- Goi component Header -->
    <Header v-bind:title="title"></Header>
    <ListUser></ListUser>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/>  -->
    <!-- msg la prop cua component HelloWorld -->
    <Footer></Footer>
  </div>
</template>

<script>
/*
  App
    Header
    ListUsers
    Footer
*/
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header";
import Footer from "./components/Footer";
import ListUser from "./components/ListUser";
export default {
  name: "app",
  // Khai bao cac component
  data(){
    return {
      title: 'Hello VueJS - Header',
      listUser : [
        {email: 'hoangducchien97@gmail.com', active: true},
        {email: 'chien.hoang@savvycomsoftware.com', active: false},
        {email: 'admin@gmail.com', active: true},
        {email: 'test@gmail.com', active: false},
      ]
    }
  },
  components: {
    HelloWorld,
    Header,
    Footer,
    ListUser
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
