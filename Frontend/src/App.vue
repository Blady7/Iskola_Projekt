<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/kartyak">Kártyák</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>

</style>
