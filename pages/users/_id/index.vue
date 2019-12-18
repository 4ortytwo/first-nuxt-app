<template>
  <div>
    <h1>A single user with ID: {{ $route.params.id }}</h1>
  </div>
</template>

<script>
export default {
  // created() {
  //   console.log('Router object', this.$router)
  // }
  validate(data) {
    console.log('nuxt validate data', data)

    return /^\d+$/.test(data.params.id)
  }
}
</script>
