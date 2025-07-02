<script setup>
import { RouterView } from 'vue-router'
import HeaderPortfolio from './components/HeaderPortfolio.vue'
import FooterPortfolio from './components/FooterPortfolio.vue'
</script>

<template>
  <div class="app-wrapper">
    <HeaderPortfolio />
    <RouterView />
    <FooterPortfolio />
  </div>
</template>

