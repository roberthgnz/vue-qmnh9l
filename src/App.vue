<script setup>
const input = ref('');
const output = ref('');
</script>

<template>
  <div id="app">
    <textarea v-model="input" rows="7" cols="32" />
    <pre>{{ output }}</pre>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
