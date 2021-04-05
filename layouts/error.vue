<template>
  <div class="container">
    <p class="error-text">404</p>
    <div>
      <span>Take me</span>
      <NuxtLink to="/">Home</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
.container {
  background: aqua;
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
