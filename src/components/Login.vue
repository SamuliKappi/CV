<script setup>
  import { ref } from 'vue'
  const emits = defineEmits(['login'])
  const username = ref()
  const password = ref()
  function onSubmit() {
    emits('login', username.value, password.value)
  }
  const view = ref(0)
</script>

<template>
  <form id="login" class="login" @submit.prevent="onSubmit">
    <label>Username</label><input v-model="username" type="text">
    <label>Password</label><input v-model="password" type="password">
    <button type="submit">Login</button>
  </form>
</template>