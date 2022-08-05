<template>
  <div class="app">
    <Header title="MyTutti"></Header>
    <div class="container">test</div>
  </div>
</template>





<script>
import Header from "./components/Header.vue";



export default {
  name: "App",
  components: {
    Header,
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
