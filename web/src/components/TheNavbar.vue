<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav class="flex flex-row mr-0 ml-auto gap-x-2 text-2xl">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/catalog">Catalog</RouterLink>
  </nav>
</template>
