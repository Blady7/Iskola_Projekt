<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="container-fluid my-container my-border">
    <header>
      <div>
        <nav>
          <RouterLink to="/">Home</RouterLink> | 
          <RouterLink to="/kartyak">Kártyák</RouterLink>
        </nav>
      </div>
    </header>

    <RouterView />
  </div>
</template>

<style>
</style>
