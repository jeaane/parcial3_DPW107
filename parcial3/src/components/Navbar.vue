<template>
  <nav>
    <ul>
      <li>
        <router-link to="/inicio">🏠 Inicio</router-link>
      </li>
      <li>
        <router-link to="/perfil">👤 Perfil</router-link>
      </li>
    </ul>
  </nav>
</template>

<script setup>
// No necesitas lógica aquí si solo estás mostrando enlaces
</script>

<style scoped>
nav {
  background-color: #f0f0f0;
  padding: 1rem;
}

ul {
  list-style: none;
  display: flex;
  gap: 1rem;
  padding: 0;
  margin: 0;
}

li {
  font-weight: bold;
}

router-link {
  text-decoration: none;
  color: #333;
}
</style>
