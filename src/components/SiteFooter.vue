
<template>
  <footer>
    <h3>✈ Skyline Hub</h3>
    <p>Explore the world. Discover something new.</p>
    <small>© {{ year }} Skyline Hub. Built with Vue.js.</small>
  </footer>
</template>

<script setup>
const year = new Date().getFullYear();
</script>

<style scoped>
footer {
  background: #1e293b;
  padding: 35px 20px;
  text-align: center;
}

h3 {
  color: #a5b4fc;
}

p {
  color: #cbd5e1;
}

small {
  color: #94a3b8;
}
</style>
