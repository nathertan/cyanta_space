<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1>Nathanael Dihyan</h1>
    <h2>Cyanta</h2>
    <h3>
      A multi - interest student. Mostly self taught since Uni sucks. <br>
      “I want a dream that everlasts.”
    </h3>
    
  </div>
  
</template>

<style scoped>
h1 {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: 500;
  font-size: 40px; 
  color: white;
}

h2 {
  color:#A7FFFF;
  top: -5px;
  font-size: 32px;
  font-weight: 500;
}

h3 {
    color: white;
    font-size: 16px;
    font-weight: 100;
}

.greetings h1,

.greetings h2,
.greetings h3 {
  text-align: left;
}

@media (max-width: 1024px) {
  .greetings h1,

  .greetings h2,

  .greetings h3 {
    text-align: center;
  }
}
</style>
