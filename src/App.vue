
<template>
  <div id="app">
    <SiteHeader />
    <SiteBody />
    <SiteFooter />
  </div>
</template>

<script setup>
import SiteHeader from "./components/SiteHeader.vue";
import SiteBody from "./components/SiteBody.vue";
import SiteFooter from "./components/SiteFooter.vue";
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0f172a;
  color: white;
}

button, a {
  font: inherit;
}
</style>
