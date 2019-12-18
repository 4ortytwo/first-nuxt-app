<template>
  <div class="container">
    <!-- <a href="/users">Users</a> -->
    <nuxt-link to="/users">Users</nuxt-link>
    <!-- <router-link href="/users">Users</router-link> -->
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Header from '~/components/Header.vue'

export default {
  components: {
    Logo,
    Header
  }
}
</script>
