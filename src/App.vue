<script setup>
import donunqConfigurator from './components/donunqConfigurator.vue'
import donunqViewport from './components/donunqViewport.vue'
</script>

<template>
  <donunqConfigurator />
  <donunqViewport />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
