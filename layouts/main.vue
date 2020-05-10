<template>
<div>
  <nav>
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/signup">singup</nuxt-link>
    <nuxt-link to="/profile">profile</nuxt-link>
  </nav>
  <nuxt />
</div>
</template>

<script>
export default {

 head() {
   return {
     title: '메인레이아웃'
   }
 },
}
</script>

<style>

</style>