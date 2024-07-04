<script>
import MyComponent from './components/MyComponent.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppHero,
    MyComponent,

  }
}
</script>

<template>
  <AppHero />

  <MyComponent />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
