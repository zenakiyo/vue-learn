<script setup>
import { ref, computed } from "vue";
const number = 5;
</script>

<template>
  <h1>Original Number: {{ number }}</h1>
  <h2>
    Squared Number:
    {{
      computed(() => {
        return number * number;
      })
    }}
  </h2>
</template>
