<script>
import AppTitle from './components/AppTitle.vue';

export default {
  data() {
    return {
      message: 'La mia prima App con Vite'
    };
  },
  components: {
    AppTitle
  }
}
</script>

<template>
  <AppTitle />
  <h2>{{ message }}</h2>
</template>

<style scoped>
h2 {
  color: gray;
}
</style>
