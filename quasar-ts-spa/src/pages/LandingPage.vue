<template>
  <q-page class="flex flex-center column">
    <div class="text-h3 q-mb-lg">Welcome to Quasar SPA</div>
    <div class="text-subtitle1 q-mb-xl">Built with Vue 3 and TypeScript</div>
    <q-btn label="Get Started" color="primary" to="/demo" />
  </q-page>
</template>

<script setup lang="ts">
defineOptions({ name: 'LandingPage' })
</script>
