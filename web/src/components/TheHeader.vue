<script setup lang="ts">
import TheNavbar from './TheNavbar.vue'
</script>

<template>
  <header class="flex flex-row items-center justify-between px-4 py-2 rounded-lg">
    <img src="@/assets/logo.svg" alt="vue_logo" width="75" height="75" />

    <div class="flex flex-row items-center gap-4">
      <TheNavbar />
    </div>
  </header>
</template>
