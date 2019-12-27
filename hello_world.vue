<template>
  <div id="#hello_world">Hello, World!</div>
</template>

<script>
export default {
  mounted() {
    console.log("Hello, World!");
  }
};
</script>

<style scoped>
#hello_world {
  visibility: visible;
}
</style>
