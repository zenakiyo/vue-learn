<script setup>
import { ref } from "vue";
const peoples = ['abc', 'bcd', 'cde', 'def']
</script>

<template>
  <ul>
    <li class="ml-5 m-1 p-1 bg-slate-100" v-for="(people, index) in peoples" :key="index">{{ people }}</li>
  </ul>
</template>
