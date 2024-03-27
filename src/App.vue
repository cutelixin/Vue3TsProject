<template>
  <div class="box">
    <h1>我是app</h1>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
</script>

<style scoped>
.box {
  width: 600px;
  height: 400px;
  background-color: black;

  h1 {
    color: white;
  }
}
</style>
