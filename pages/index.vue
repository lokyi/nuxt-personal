<template>
  <section class="container">
    <div>
      <h1 class="title">
        Hello,
      </h1>
      <p class="intro">
        I'm Yi Yue, a full stack web developer, and a student in machine learning, electrical engineering, and wireless health technology.

        I'm originally from Shanghai, China but these days I live in Los Angeles, United States.
      </p>
      <div class="links">
        <nuxt-link to="/resume" class="button--grey">Résumé</nuxt-link>
      </div>
    </div>
  </section>
</template>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 50px;
  color: #35495e;
  letter-spacing: 1px;
  margin-bottom: 25px;
}

.intro {
  font-weight: 200;
  font-size: 21px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  width: 670px;
  margin: 0 auto 10px;
}

@media screen and (max-width: 600px) {
  .intro {
    width: 400px;
  }
}

.links {
  padding-top: 15px;
}
</style>
