<script setup>
import {ref} from 'vue'
let count = ref(0);
</script>

<template>
  <h1>count: {{ count }}</h1>
  <button @click='count --'>Decremetn</button>
  <button @click='count ++'>Increment</button>
</template>
<style>
</style>
