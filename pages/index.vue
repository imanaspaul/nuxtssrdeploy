<template>
  <div class="container m-auto">
    <nuxt-link to="/">Home</nuxt-link> /
    <nuxt-link to="/about">About</nuxt-link>
    <Tutorial />
    <p class="absolute bottom-0 right-20">
      &copy; {{ new Date().getFullYear() }} by manascode.com
    </p>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
