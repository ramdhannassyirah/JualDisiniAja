<script setup>
import AppNav from './components/AppNav.vue'
import AppHero from './components/AppHero.vue'
import AppFooter from './components/AppFooter.vue'
import HomeView from './views/HomeView.vue'
</script>
<template>
  <div class="id">
    <header>
      <AppNav />
      <AppHero />
    </header>
    <main>
      <HomeView />
    </main>
    <footer>
      <AppFooter />
    </footer>
  </div>
</template>
