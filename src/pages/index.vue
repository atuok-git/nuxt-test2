<template>
  <div>
    <h1>Title</h1>
    <nuxt-link to="/about">about</nuxt-link>
    <nuxt-link to="/news/">news</nuxt-link>
    <nuxt-link to="/test">test</nuxt-link>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss" scoped>
h1 {
  color: $colorCorporateMain;
}
</style>
