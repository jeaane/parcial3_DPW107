<template>
  <footer>
    <div class="footer-content">
      <section class="about">
        <h3>📘 Acerca de</h3>
        <p>Esta aplicación fue creada con amor y Vue 💖</p>
      </section>

      <section class="social">
        <h3>🔗 Redes Sociales</h3>
        <ul>
          <li><a href="https://twitter.com" target="_blank">🐦 Twitter</a></li>
          <li><a href="https://facebook.com" target="_blank">📘 Facebook</a></li>
          <li><a href="https://instagram.com" target="_blank">📸 Instagram</a></li>
        </ul>
      </section>

      <section class="copyright">
        <p>© 2025 Jean Corp. Todos los derechos reservados 🛡️</p>
      </section>
    </div>
  </footer>
</template>

<script setup>
// No se necesita lógica para este pie de página estático
</script>

<style scoped>
footer {
  background-color: #222;
  color: #fff;
  padding: 2rem;
  text-align: center;
}

.footer-content {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.about, .social, .copyright {
  margin-bottom: 1rem;
}

.social ul {
  list-style: none;
  padding: 0;
}

.social li {
  margin: 0.5rem 0;
}

a {
  color: #00aced;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
