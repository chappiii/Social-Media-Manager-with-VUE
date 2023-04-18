<script setup>
  import { RouterView } from 'vue-router';
  import LandingPage from '../components/LandingPage.vue';
  import Publish from '../components/Publish.vue';
  import Aalyze from '../components/Analyze.vue';
  
</script>

<template>
    <div>
      <LandingPage />
      <Publish />
      <Aalyze />
    </div>
</template>
<style scoped>
* {
  padding: 0;
  margin: 0;
}
</style>