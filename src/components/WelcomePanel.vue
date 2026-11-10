
<template>
  <section id="home" class="hero">
    <p class="tag">WELCOME TO SKYLINE HUB</p>
    <h1>Your Adventure Starts Here ✈</h1>
    <p>Explore destinations, discover new experiences,
      and see what's possible with Vue.js.</p>
    <a href="#explore" class="btn">Start Exploring</a>
  </section>
</template>

<style scoped>
.hero {
  text-align: center;
  padding: 105px 20px;
  background: linear-gradient(135deg, #1e3a8a, #312e81, #0f172a);
}

.tag {
  color: #c4b5fd;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 12px;
}

h1 {
  font-size: clamp(32px, 6vw, 52px);
  margin: 20px 0;
}

.hero p {
  max-width: 550px;
  margin: 20px auto 35px;
  line-height: 1.8;
  color: #e2e8f0;
}

.btn {
  display: inline-block;
  padding: 14px 28px;
  background: #6366f1;
  color: white;
  text-decoration: none;
  border-radius: 10px;
  font-weight: bold;
}

.btn:hover {
  background: #4f46e5;
}
</style>
