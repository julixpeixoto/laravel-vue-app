<template>
  <div>
    <h1>Welcome to Laravel + Vue Project!</h1>
    <h2>{{ devName }}</h2>
  </div>
</template>

<script>
export default {
  setup: () => ({
    devName: "Julix",
  }),
};
</script>

<style scoped>
/* CSS Here! */
</style>