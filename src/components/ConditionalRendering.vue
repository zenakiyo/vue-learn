<script setup>
  import { ref } from 'vue';
  const isLogged = ref(true);
</script>

<template>
  <div>
    <button class="border-blue-200 border-2 rounded-md m-5 pt-2 pb-2 w-24" @click="isLogged = !isLogged">{{ isLogged ? "Logout" : "LogIn" }}</button>
    <p class="ml-5 text-blue-600" v-show="isLogged">The user is logged IN</p>
  </div>
</template>
