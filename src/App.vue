<template>
  <div id="app">
    <Navbar />
    <div class="container app-container">
      <router-view />
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  name: 'app',
  components: {
    Navbar
  }
};
</script>

<style>
</style>
