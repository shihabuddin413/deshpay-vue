<script setup>
import Header from './components/Header.vue'
</script>

<template>
  <div class="app-container">
    <Header />
    <main class="main-content">
      <!-- Main homepage content will go here -->
      <section class="hero-section">
        <h1>DeshPay Digital Bhumi</h1>
        <p>Pixel-perfect clone homepage placeholder</p>
      </section>
    </main>
  </div>
</template>

<style scoped>
.app-container {
  min-height: 100vh;
  background: #f7f7f7;
  font-family: 'Inter', Arial, sans-serif;
}
.main-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 1rem;
}
.hero-section {
  text-align: center;
  margin-top: 4rem;
}
.hero-section h1 {
  font-size: 2.5rem;
  font-weight: 700;
  color: #1a202c;
}
.hero-section p {
  font-size: 1.25rem;
  color: #4a5568;
  margin-top: 1rem;
}
</style>
