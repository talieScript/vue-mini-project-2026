<script setup lang="ts">
import BurgerButton from '@/components/BurgerButton.vue'
</script>

<template>
  <header class="header">
    <BurgerButton />
    <h1>Tasks</h1>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  align-items: center;
  margin: 8px;
}

.header h1 {
  font-size: 22px;
  margin-left: 4px;
}
</style>
