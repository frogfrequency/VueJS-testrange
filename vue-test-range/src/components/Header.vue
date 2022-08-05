<template>
  <header>
    <menu-icon />
    <h1 id="header-title">{{ title }}</h1>
    <account-icon />
    <!-- <Button @btn-click="myMethod()" text="favorite" color="yellow"> </Button> -->
  </header>
</template>


<script>
import Button from "./Button.vue";
import MenuIcon from 'vue-material-design-icons/Menu.vue';
import AccountIcon from 'vue-material-design-icons/Account.vue';


export default {
  name: "Header",
  props: {
    title: {
      type: String,
      default: "no title found",
    },
  },
  components: {
    Button,
    MenuIcon,
    AccountIcon,
  },
  methods: {
    myMethod() {
      console.log(`${this.title}`);
    },
  },
};
</script>

<style>
header {
  margin: 8px;
  padding: 8px 16px;
  /* background-color: rgb(120, 154, 224); */
  border-radius: px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
#header-title {
  margin: 4px 0px;
}
</style>