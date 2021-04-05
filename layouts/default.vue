<template>
  <div>
    <nav>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink to="/">Home</NuxtLink>
    </nav>
    <Nuxt />
  </div>
</template>
<script>
export default {
  head: {
    title: 'Nuxt Mission',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'A mission to explore the Jamstack using Nuxt.',
      },
    ],
  },
}
</script>
