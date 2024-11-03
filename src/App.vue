<script setup>
import { ref } from "vue";
import FormComponent from "./components/FormComponent.vue";
const formHandler = (username, email, password) => {
  console.log(username)
}
</script>

<template>
  <FormComponent @userInfo="formHandler"/>
</template>

<style scoped></style>
