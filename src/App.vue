<script>

import Navbar from './components/Navbar.vue'

export default {
  name: "sidat",
  components: {
    Navbar
  },
  data() {
    return {
      title: "This is my first vue app",
    };
  },
  
};
</script>

<template>
  <Navbar />
</template>

<style>
    html{
      scroll-behavior: smooth;
    }
</style>
