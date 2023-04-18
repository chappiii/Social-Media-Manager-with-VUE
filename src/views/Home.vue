<script setup>
  import { RouterView } from 'vue-router';
  import LandingPage from '../components/LandingPage.vue';
  import Publish from '../components/Publish.vue';
  
</script>

<template>
    <div>
      <LandingPage />
      <Publish />
    </div>
</template>
<style scoped>
* {
  padding: 0;
  margin: 0;
}
</style>