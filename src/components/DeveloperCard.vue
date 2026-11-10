
<template>
  <section id="developer" class="developer">
    <div class="profile">
      <div class="avatar">👨‍💻</div>
      <h2>Meet the Developer</h2>
      <h3>Student Web Developer</h3>
      <p>
        I'm learning HTML, CSS, JavaScript and Vue.js.
        This website demonstrates how reusable Vue
        components make web development easier!
      </p>

      <button @click="showSkills = !showSkills">
        {{ showSkills ? "Hide Skills" : "Show My Skills" }}
      </button>

      <p v-if="showSkills" class="skills">
        HTML • CSS • JavaScript • Vue.js
      </p>
    </div>
  </section>
</template>

<script setup>
import { ref } from "vue";

const showSkills = ref(false);
</script>

<style scoped>
.developer {
  padding: 60px 20px;
  background: #172238;
  text-align: center;
}

.profile {
  max-width: 550px;
  margin: auto;
}

.avatar {
  font-size: 65px;
}

h3 {
  color: #a5b4fc;
}

p {
  color: #cbd5e1;
  line-height: 1.8;
}

button {
  background: #6366f1;
  padding: 13px 25px;
  color: white;
  border: none;
  border-radius: 9px;
  cursor: pointer;
}

button:hover {
  background: #4f46e5;
}

.skills {
  color: #a5b4fc;
  font-weight: bold;
}
</style>
