
<template>
  <section id="explore" class="explore">
    <h2>Explore Destinations 🌎</h2>
    <p>Find inspiration for your next adventure.</p>

    <div class="cards">
      <article v-for="place in places" :key="place.name" class="card">
        <div class="emoji">{{ place.emoji }}</div>
        <h3>{{ place.name }}</h3>
        <p>{{ place.description }}</p>
        <span>{{ place.country }}</span>
      </article>
    </div>
  </section>
</template>

<script setup>
const places = [
  {
    name: "Tokyo",
    country: "Japan",
    emoji: "🗼",
    description: "Discover amazing food, technology and culture."
  },
  {
    name: "Seoul",
    country: "South Korea",
    emoji: "🌆",
    description: "Explore exciting nightlife, history and city views."
  },
  {
    name: "Singapore",
    country: "Singapore",
    emoji: "🌴",
    description: "Enjoy beautiful gardens and futuristic architecture."
  }
];
</script>

<style scoped>
.explore {
  padding: 70px 8%;
  text-align: center;
}

.explore > p {
  color: #94a3b8;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
  gap: 20px;
  margin-top: 35px;
}

.card {
  padding: 30px 20px;
  background: #1e293b;
  border-radius: 16px;
  transition: transform 0.2s;
}

.card:hover {
  transform: translateY(-6px);
}

.emoji {
  font-size: 55px;
}

.card h3 {
  color: #c4b5fd;
}

.card p {
  color: #cbd5e1;
  line-height: 1.6;
}

.card span {
  color: #818cf8;
  font-weight: bold;
}
</style>
