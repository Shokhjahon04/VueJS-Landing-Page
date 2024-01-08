<script>
import { RouterLink, RouterView } from 'vue-router';
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer,
  }
}
</script>

<template>
  <Navbar />

  <main class="main">
    <RouterView />
  </main>

  <Footer />
</template>

<style scoped>

</style>