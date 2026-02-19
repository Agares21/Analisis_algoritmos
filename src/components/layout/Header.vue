<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header class="mi-header">
    <div class="logo">
      <router-link to="/">
        <img src="/img/LogoF.png" alt="Logo Personal" />
      </router-link>
      <h3>Analisis de Algoritmos</h3>
    </div>

    <nav>
      <RouterLink to="/" class="nav-link">Inicio</RouterLink>
      <RouterLink to="/algoritmo" class="nav-link">Algoritmo</RouterLink>
      <RouterLink to="editor" class="nav-link">Crea tu Grafo</RouterLink>
      <RouterLink to="/acerca" class="nav-link">Acerca de</RouterLink>
    </nav>
  </header>
</template>

<style scoped>
.mi-header {
  background-color: #1e293b; /* Color oscuro */
  color: white;
  display: flex;
  justify-content: space-between; /* Separa logo y menú */
  align-items: center;
  padding: 1rem 2rem;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.logo {
  display: flex;
  align-items: center;
  gap: 15px;
}

.logo h3 {
  margin: 0;
  color: #42b883; /* Verde Vue */
}
.logo img {
  max-height: 80px;
  transition: all 0.3s ease;
}

nav {
  display: flex;
  gap: 1.5rem; /* Espacio entre enlaces */
}

.nav-link {
  color: #cbd5e1;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

.nav-link:hover {
  color: white;
}

/* Esta clase se añade automática cuando estás en esa página */
.router-link-active {
  color: #42b883;
  border-bottom: 2px solid #42b883;
}
</style>
