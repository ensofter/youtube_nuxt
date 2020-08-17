<template>
  <section>
    <h1>Страница не найдена 404</h1>

    <nuxt-link to="/">Home</nuxt-link>
  </section>
</template>

<script>
export default {
  name: "error"
}
</script>

<style scoped>
  section {
    width: 500px;
    margin: auto;
    padding-top: 5rem;
  }
  h1 {
    color: red;
  }
</style>
