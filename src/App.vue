<script setup>
import AppNav from './components/AppNav.vue'
import AppHero from './components/AppHero.vue'

import HomeView from './views/HomeView.vue'
</script>
<template>
  <div class="">
    <header>
      <AppNav />
      <AppHero />
    </header>
    <main>
      <HomeView />
    </main>
  </div>
</template>
