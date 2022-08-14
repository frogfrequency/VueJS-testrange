<template>
  <div class="app">
    <Header title="MyTutti"></Header>
    <router-view></router-view>
    <div class="container">test</div>
    <Footer></Footer>
  </div>
</template>





<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";



export default {
  name: "App",
  components: {
    Header,
    Footer,
  },
};
</script>

<style>

  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap');

  body {
    font-family: 'Poppins', sans-serif;
    background-color: rgb(219, 221, 253);
  }

  .container {
    border: solid rgb(163, 163, 220);
    width: 100%;
    height: 400px;
  }

  
</style>
