<template>
  <header class="header">
    <div class="container">
      <img src="/logo.png" alt="DeshPay Logo" class="logo" />
      <nav class="nav">
        <!-- Navigation links will go here -->
        <a href="#" class="nav-link">Home</a>
        <a href="#" class="nav-link">About</a>
        <a href="#" class="nav-link">Services</a>
        <a href="#" class="nav-link">Contact</a>
      </nav>
    </div>
  </header>
</template>

<script setup>
// No logic yet
</script>

<style scoped>
.header {
  background: #fff;
  border-bottom: 1px solid #e2e8f0;
  padding: 0.75rem 0;
}
.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 1rem;
}
.logo {
  height: 40px;
}
.nav {
  display: flex;
  gap: 2rem;
}
.nav-link {
  color: #1a202c;
  text-decoration: none;
  font-weight: 500;
  font-size: 1rem;
  transition: color 0.2s;
}
.nav-link:hover {
  color: #3182ce;
}
</style>