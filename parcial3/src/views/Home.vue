<template>
  <div class="home">
    <h1>📚 Parcial de Desarrollo Web</h1>
    <p>👤 Estudiante: Jean</p>
    <p>🆔 CI: 12345678</p>
    <p>🏫 Asignatura: Programación Web II</p>
    <p>📅 Fecha: 26 de septiembre de 2025</p>
    <p>🎉 ¡Bienvenid@ a tu aplicación Vue!</p>
    <router-link to="/about">Go to About</router-link>
  </div>
</template>

<script setup>
// No se necesita lógica para esta vista estática
</script>

<style scoped>
.home {
  text-align: center;
  padding: 3rem;
  background-color: #f9f9f9;
  color: #333;
  font-family: 'Segoe UI', sans-serif;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

p {
  font-size: 1.2rem;
  margin: 0.5rem 0;
}
</style>
