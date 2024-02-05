<script setup>
import { RouterView } from 'vue-router'
import AppNav from './components/AppNav.vue'
</script>
<template>
  <div class="id">
    <header>
      <AppNav />
    </header>
    <main>
      <RouterView />
    </main>
    <footer></footer>
  </div>
</template>
