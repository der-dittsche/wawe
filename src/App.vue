<template>
  <header>
    <NavbarTop />
  </header>

  <RouterView />
  <footer>
    <FooterView />
  </footer>
</template>
<script setup>
import { RouterView } from 'vue-router'
import NavbarTop from './components/NavbarTop.vue'
import FooterView from './components/FooterView.vue'
</script>
