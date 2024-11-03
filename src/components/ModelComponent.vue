<script setup>
import { reactive, ref } from 'vue';

  const formData = ref({username: '', email: '', password: ''})
</script>

<template>
  <form action="" @submit.prevent>
    <input type="text" name="" id="username" placeholder="your username" v-model="formData.username">
    <input type="email" name="" id="username" placeholder="your email" v-model="formData.email">
    <button type="submit">Submit</button>
  </form>
  <h1>{{ formData.username }}</h1>
    <h1>{{ formData.email }}</h1>
</template>
