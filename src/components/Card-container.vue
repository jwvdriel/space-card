<script setup>
import Content from './Card-content.vue'
</script>

<template>
  <div class="card">
    <img src="/space-enjoy.jpg" alt="space-room" />
    <Content />
  </div>
</template>

<style scoped>
.card {
  width: 340px;
  display: flex;
  flex-direction: column;
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow:
    0px 1px 2px 0 rgb(0 0 0 / 0.06),
    0px 1px 3px 0 rgb(0 0 0 / 0.1);
}

img {
  align-self: stretch;
  height: 288px;
  object-fit: cover;
}
</style>
