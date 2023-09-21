<script setup lang="ts">
import { injectGlobal } from '@magister_zito/vue3-styled-components';
import Home from '../components/Home/Home.vue';

injectGlobal`
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: 'Noto Sans TC', sans-serif;
  }

  #__nuxt {
    min-height: 100vh;
    padding: 140px 0 115px;
    position: relative;

    @media screen and (max-width: 1279px) {
      padding: 102px 0 208px;
    }
  }
`;
</script>

<template>
  <Home />
</template>

<style scoped></style>
