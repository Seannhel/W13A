
<template>
  <header class="header">
    <a href="#home" class="logo">✈ Skyline Hub</a>

    <nav>
      <a href="#home">Home</a>
      <a href="#explore">Explore</a>
      <a href="#developer">Developer</a>
    </nav>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 8%;
  background: #1e293b;
  gap: 20px;
  flex-wrap: wrap;
}

.logo {
  font-size: 23px;
  font-weight: bold;
  color: #a5b4fc;
  text-decoration: none;
}

nav {
  display: flex;
  gap: 22px;
}

nav a {
  color: white;
  text-decoration: none;
}

nav a:hover {
  color: #a5b4fc;
}
</style>
