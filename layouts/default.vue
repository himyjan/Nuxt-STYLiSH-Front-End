<script setup lang="ts">
import Header from '../components/Header/Header.vue';
import Footer from '../components/Footer/Footer.vue';
import { store } from '../store/store';
</script>

<template>
  <!-- <Header :cartItems="store.cartItems" /> -->
  <Header :cartItems="[]" />
  <slot />
  <Footer />
</template>

<style scoped></style>