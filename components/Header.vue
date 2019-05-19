<template>
  <div class="header">
    <div class="title-logo">
      <Logo />
      <h1 class="title">
          artstream
      </h1>
    </div>
    <div class="menu">
      <nuxt-link to="/register">Register</nuxt-link>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.header {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  margin: 0 auto;
  padding-left: 15px;
  padding-right: 15px;
  max-width: 1000px;
}

.title-logo {
  display: flex;
  align-items: center;
  justify-content: center;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 30px;
  color: #35495e;
  letter-spacing: 1px;
}
</style>
