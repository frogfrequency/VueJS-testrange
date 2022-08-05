<template>
  <button @click="onClick()" :style="{ background: color}">
    {{ text }}
  </button>
</template>

<script>

export default {
  name: "Button",
  props: {
    text: String,
    color: String,
  },
  methods: {
    onClick() {
      this.$emit("btn-click")
    }
  }
};
</script>

<style>
button {
  background-color: green;
  border: none;
  font-family: inherit;
}
</style>