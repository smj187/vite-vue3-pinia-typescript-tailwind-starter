<script setup lang="ts">
  import Header from "@/components/Header.vue"
  import { RouterView } from "vue-router"
</script>

<template>
  <div class="relative">
    <Header />
    <main class="mt-16 p-9">
      <RouterView />
    </main>
  </div>
</template>

<style scoped lang="scss">
  .container {
    min-height: 100vh;
    background-color: #141414;
    color: #e8e8e8;
  }
</style>
