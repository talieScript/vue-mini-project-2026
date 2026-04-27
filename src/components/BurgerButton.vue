<script setup lang="ts"></script>

<template>
  <button>
    <svg focusable="false" viewBox="0 0 24 24">
      <path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"></path>
    </svg>
  </button>
</template>

<style scoped>
button {
  padding: 12px;
  display: inline-block;
  border-radius: 50%;
  vertical-align: middle;
  overflow: hidden;
  cursor: pointer;
  background-color: transparent;
  border: none;
  display: flex;
  align-items: center;
  justify-content: center;
}
button:hover {
  background-color: rgba(0, 0, 0, 0.05);
}
button svg {
  fill: currentColor;
  color: black;
  width: 24px;
  height: 24px;
}
</style>
