<script setup>
import { RouterView, RouterLink } from 'vue-router';
</script>

<template>
  <nav class="flex flex-row justify-between p-5 text-xl bg-cyan-950">
    <div class="bg-black p-4 rounded-full"></div>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/contact">Contact</RouterLink>
  </nav>
  <main>
    <RouterView />
  </main>
</template>