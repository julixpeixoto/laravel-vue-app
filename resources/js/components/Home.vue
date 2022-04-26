<template>
      <div class="bg-white h-screen flex items-center justify-center">
          <div class=" text-center">
              <div class="font-medium max-w-xl text-xl">
                  <h1 class="text-3xl font-bold underline">Welcome to Laravel + Vue Project!</h1>
                  <h2>{{ devName }}</h2>
              </div>
          </div>
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
