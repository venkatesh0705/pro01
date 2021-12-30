<template>
  <div class="home">
    <div class="brand">
      <img alt="sample" />
    </div>
    <div class="menu">
      <div class="menu_items">
        <li class="items">item 01</li>
        <li class="items">item 02</li>
        <li class="items">item 03</li>
        <li class="items">item 04</li>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Index",
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.home {
  background-color: aquamarine;
  display: flex;
  justify-content: space-between;
  padding: 10px 0;
}
.menu {
  float: left;
}
.menu_items {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-direction: row;
  list-style-type: none;
}
.items {
  margin: 0 10px;
}
</style>
