<script setup>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import content from './components/content.vue';
</script>

<template>
  <div style="height: 25vh;"></div>
  <header style="margin-bottom: 21px;">
    <img style="margin-right: 50px;" alt="Profile" class="pic" src="./assets/profile.png" width="218" height="218" />

    <div class="wrapper" style="margin-top: 21px;">
      <Header/>
    </div>
  </header>
  <form action="#content" style="display: flex; justify-content: center;">
    <input type="submit" value="More About Me" style="background-color: #262626; border: none; color: #ABABAB;  width: 705px; height: 38px; border-radius: 10px; font-size: 16px;">
  </form>
  
  <div id="buffer" style="margin-bottom: 300px;"></div>

  <div id="content">
    <content/>

  </div>
    
  <footer>
    <Footer/>
    <div style="margin-bottom: 10vh;"></div>
  </footer>

  <footer>
    
  </footer>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.pic {
  display: block;
  margin: 0 auto 2rem;
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
