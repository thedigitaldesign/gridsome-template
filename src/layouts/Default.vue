<template>
  <div class="layout">
    <Navbar />

    <main class="container max-w-full">
      <slot />
    </main>

    <Footer />
  </div>
</template>

<script lang="ts">
// Components
import Footer from '../components/Footer.vue'
import Navbar from '../components/Navbar.vue'

export default {
  components: {
    Footer,
    Navbar
  }
}
</script>

<style></style>
