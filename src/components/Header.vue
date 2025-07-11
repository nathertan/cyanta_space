<template>
  <img
    style="justify-content: center; align-self: center"
    alt="Profile"
    class="pic"
    src="../assets/profile.png"
    width="218"
    height="218"
  />

  <div class="greetings">
    <h1>Nathanael Dihyan</h1>
    <h2>Cyanta</h2>
    <h3>
      A freshgrad. Mostly self taught since Uni sucks. <br />
      “I want a dream that everlasts.”
    </h3>
    <form action="#content" style="display: flex; justify-content: center">
      <input
        type="submit"
        value="More About Me"
        style="
          background-color: #262626;
          border: none;
          color: #ababab;
          width: 705px;
          height: 38px;
          border-radius: 10px;
          font-size: 16px;
        "
      />
    </form>
  </div>
</template>

<style scoped>
.pic {
  display: block;
  margin: 0 auto 2rem;
}

@media (max-width: 1024px) {
  .greetings h1,
  .greetings h2,
  .greetings h3 {
    text-align: center;
  }
}
</style>
