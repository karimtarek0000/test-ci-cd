<template>
  <div class="about">
    <h1>About Page testing</h1>
    <p>This page issdsdsdsd prefetched after the initial load.</p>
  </div>
</template>

<script setup>
  import { useHead } from '@vueuse/head';

  // Set page-specific metadata
  useHead({
    title: 'About',
  });
</script>

<style scoped>
  .about {
    padding: 20px;
  }
</style>
