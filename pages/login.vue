<template>
<section>
  <form>
    <h1>Login</h1>
    <div class="form-group">
      <input type="text" class="form-control">
    </div>
    <p>
      <nuxt-link to="/">To home page</nuxt-link>
    </p>
    <button class="btn btn-primary" type="submit">Login</button>
  </form>
</section>
</template>

<script>
export default {
  name: "login"
}
</script>

<style scoped>
form{
  width: 500px;
  margin: 0 auto;
}
</style>
