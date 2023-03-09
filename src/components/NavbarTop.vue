<template>
  <nav class="nav__top">
    <div class="nav__top-logo">WaWe</div>
    <div class="nav__menu">
      <ul class="nav__menu-list">
        <li class="nav__menu-item"><RouterLink to="/">Start</RouterLink></li>
        <li class="nav__menu-item"><RouterLink to="/date">Termine</RouterLink></li>
        <li class="nav__menu-item"><RouterLink to="/about">Über uns</RouterLink></li>
        <li class="nav__menu-item"><RouterLink to="/group">Gruppen</RouterLink></li>
        <li class="nav__menu-item"><RouterLink to="/blog">Blog</RouterLink></li>
        <li class="nav__menu-item"><RouterLink to="/contact">Kontakt</RouterLink></li>
      </ul>
    </div>
    <div class="nav__top-login">
      <button>Login</button>
    </div>
  </nav>
</template>
<script setup>
import { RouterLink } from 'vue-router'
</script>
<style scoped>
.nav__top {
  background-color: lightgreen;
  display: flex;
  gap: 2rem;
  box-shadow: 1px 1px 2px darkgreen;
}
.nav__top-logo {
  flex: 1;
  padding: 1rem;
}
.nav__menu {
  flex: 8;
}
.nav__menu-list {
  list-style: none;
  display: flex;
  gap: 1rem;
  width: 100%;
  justify-content: center;
}
.nav__menu-item {
  cursor: pointer;
  padding-inline: 2rem;
  padding-block: 1rem;
}
.nav__menu-item a {
  text-decoration: none;
}

.nav__top-login {
  width: 100%;
  flex: 1;
  display: flex;
  justify-content: flex-end;
  padding: 1rem;
}
</style>
