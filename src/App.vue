<template>
  <v-app id="app">
    <MainLayout></MainLayout>
  </v-app>
</template>

<script>
import MainLayout from './layouts/MainLayout.vue';
import './styles/main.sass'

export default {
  name: 'App',
  components: {
    MainLayout,
  }
}
</script>

<style>
#app {
  font-family: -apple-system,Helvetica, 'Inter', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
