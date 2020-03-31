<template>
  <div class="container">
    <form>
      <label>Login</label>
      <input type="text" placeholder="username" value="linh" />
      <input type="password" value="123" />
      <nuxt-link to="/">Home</nuxt-link>
    </form>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend()
</script>
