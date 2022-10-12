<template>
<section>
  <Navbar/>
  <h1>
    Users
  </h1>
  <ul>
    <li v-for="user of 5" :key="user">
      <a href="#" @click.prevent="openUser(user)">User {{user}}</a>
    </li>
  </ul>
</section>
</template>

<script>
export default {
  methods: {
    openUser(user) {
      this.$router.push('/users/' + user)
    }
  },
  name: "index.vue"
}
</script>

<style scoped>

</style>
