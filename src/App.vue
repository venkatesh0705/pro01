<template>
  <div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <index />
    <parent />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Index from "./components/index.vue";
import parent from "./components/parent.vue";
export default {
  name: "App",
  components: {
    Index,
    parent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
}
</style>
