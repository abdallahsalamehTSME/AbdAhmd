<script setup lang="ts"></script>

<template>
  <div class="container">
    <slot></slot>
  </div>
</template>

<style scoped>
.container {
  height: 100vh;
  padding: 2% 10%;
  display: flex;
  justify-content: space-between;
}
</style>
