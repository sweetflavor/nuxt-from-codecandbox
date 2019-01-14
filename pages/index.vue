<template>
  <section>
    <div>
      <div class="links">
        <img src="@/assets/codesandbox_icon.png" width="120" alt="" />
        <h1>Hola a Todos!</h1>
        <nuxt-link to="/about" class="button--grey">About</nuxt-link>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 100px;
  color: #526488;
  letter-spacing: 1px;
  font-size: 6em;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
