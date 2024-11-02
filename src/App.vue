<script setup>
import AnotherComponent from "./components/AnotherComponent.vue";
import MyEvent from "./components/MyEvent.vue";
const href = "https://www.youtube.com/watch?v=KAaUyVJoNAE"
const imgInfo ={
  src: 'https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=2864&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
  alt: "women wearing black crew neck shirt",
  width: 400,
}
</script>

<template>
  <!-- <a :href="href">Good Song</a>
  <img :="imgInfo" class="rounded-xl" /> -->
  <MyEvent />
</template>

<style scoped>
</style>
