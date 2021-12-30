<template>
  <div>
    <h1>sample text-child component</h1>
    {{ message }}
  </div>
</template>

<script>
export default {
  name: child,
  props: ["message"],
};
</script>
