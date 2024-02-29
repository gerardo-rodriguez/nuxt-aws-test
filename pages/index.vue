<script setup lang="ts">
console.log('Index page');
</script>

<template>
  <div>
    <h1>This is the index page at <code>/</code></h1>
    <HelloWorld />
    <NuxtLink to="/about">Go to the "about" page</NuxtLink>
  </div>
</template>

<style scoped>
h1 {
  color: green;
}
</style>
