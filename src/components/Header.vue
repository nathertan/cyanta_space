<template>
  <div class="pic">
    <img alt="Profile" src="../assets/profile.png" class="picture" />
  </div>

  <div class="greetings">
    <h1>Nathanael Dihyan</h1>
    <h2>Cyanta</h2>
    <h3>
      A freshgrad. Mostly self taught since Uni sucks. <br />
      Hit me up for projects and fun ideas!
    </h3>
  </div>
  <div class="action-button">
    <form action="#content" style="display: flex; justify-content: center">
      <input
        type="submit"
        value="More About Me"
        style="
          background-color: #262626;
          border: none;
          color: #ababab;
          width: 70vw;
          height: 38px;
          border-radius: 10px;
          font-size: 16px;
        "
      />
    </form>
  </div>
</template>

<style scoped>
@media (max-width: 1024px) {
  .greetings {
    text-align: center;
    margin-top: 1vh;
  }

  .pic {
    display: flex;
    justify-content: center;
    justify-self: center;
    margin-top: 22vh;
  }

  .picture {
    display: flex;
    width: 18vh;
  }

  .action-button {
    margin-top: 4vh;
    margin-bottom: 30vh;
  }
}
</style>
