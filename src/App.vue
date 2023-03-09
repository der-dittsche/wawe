<template>
  <header>
    <NavbarTop />
  </header>
  <div class="container mx-auto pt-3">
    <RouterView />
  </div>
</template>
<script setup>
import { RouterView } from 'vue-router'
import NavbarTop from './components/NavbarTop.vue'
</script>
