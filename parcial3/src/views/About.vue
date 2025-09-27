<template>
  <div class="contador">
    <h1>🧮 Página de contador</h1>
    <HelloWorld msg="¡Bienvenid@ al contador Vue! 🎉" />
    <router-link to="/">Go to Home</router-link>
  </div>
</template>

<script setup>
import HelloWorld from '../components/HelloWorld.vue'
</script>

<style scoped>
.contador {
  text-align: center;
  padding: 2rem;
  background-color: #eef;
  color: #333;
}

h1 {
  font-size: 2rem;
  margin-bottom: 1.5rem;
}
</style>
