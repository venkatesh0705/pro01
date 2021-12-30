<template>
  <div>
    <Index />
    <Test />
    <testing />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Index from "./components/index.vue";
import Test from "./components/test.vue";
import testing from "./components/testing.vue";

export default {
  name: "App",
  components: {
    Index,
    Test,
    testing,
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
