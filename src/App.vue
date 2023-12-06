<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  data() {
    return {
      message: 'La mia prima App con Vite'
    };
  },
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <AppTitle />
  <AppHero />
  <h2>{{ message }}</h2>
</template>

<style scoped>
h2 {
  color: gray;
}
</style>
