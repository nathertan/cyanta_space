<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import content from "./components/content.vue";
</script>

<template>
  <Header />

  <content />
  <Footer />
</template>

<style>
h1 {
  font-weight: 500;
  font-size: 40px;
  color: white;
}

h2 {
  color: #a7ffff;
  top: -5px;
  font-size: 32px;
  font-weight: 500;
}

h3 {
  color: white;
  font-size: 16px;
  font-weight: 100;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
  }

  .pic {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
  }
}
</style>
