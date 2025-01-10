<template>
  <div>
    <h1>LAB3 - 058ForFork</h1>
    <hr>
    <input type="text" name="userName" id="test" v-model="userName">
  </div>
</template>

<script setup>
import { ref } from 'vue'
const userName = ref('')
</script>
