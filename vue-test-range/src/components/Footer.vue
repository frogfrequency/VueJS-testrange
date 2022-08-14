<template>
  <div>
    <h4>Copyright &copy; 2022</h4>
    <router-link class="link" to="/about" >About</router-link>
    <!-- style="background-color: black" -->
  </div>
</template>


<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
* {
  text-align: center;
}


.link {
  text-decoration: none;
  color: inherit;
  font-weight: 600;
  font-size: 18px;
  /* font-size: px; */
  /* height: 100px; */
  /* border: solid; */
}

.link:hover {
  /* text-decoration: underline; */
  filter: contrast(0.6);
}

</style>