<script setup>
// Aquí iría tu lógica si la necesitas en el futuro
</script>

<template>
  <div class="acerca-page">
    <div class="profile-card">
      <div class="logo-container">
        <div class="logo-wrapper">
          <img src="/img/LogoF.png" alt="Logo AGP/AGAC" class="profile-logo" />
        </div>
      </div>

      <div class="card-content">
        <h1>Análisis de Algoritmos</h1>

        <p class="purpose">
          Esta plataforma web interactiva está diseñada para visualizar,
          aprender y experimentar con la teoría de grafos y algoritmos en tiempo
          real, facilitando la comprensión de estructuras de datos complejas.
        </p>

        <div class="info-section">
          <h2>Información del Proyecto</h2>
          <ul class="datos-lista">
            <li>
              <strong>Desarrollador:</strong> Alejandro Gabriel Arce Chiri
            </li>
            <li><strong>Materia:</strong> Análisis de Algoritmos - MAT361</li>
            <li><strong>Semestre:</strong> 1-2026</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* --- CONTENEDOR PRINCIPAL --- */
.acerca-page {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f8fafc;
  padding: 2rem;
  font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
}

/* --- TARJETA --- */
.profile-card {
  background: white;
  border-radius: 20px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.05);
  max-width: 650px;
  width: 100%;
  overflow: hidden;
  text-align: center;
  border: 1px solid rgba(0, 0, 0, 0.05);
}

/* --- ZONA DEL LOGO --- */
.logo-container {
  background: radial-gradient(circle at center, #764ba2 0%, #667eea 100%);
  padding: 3rem 0;
  display: flex;
  justify-content: center;
}

.logo-wrapper {
  background: rgb(15, 15, 15);
  width: 160px;
  height: 160px;
  border-radius: 80%;
  padding: 15px;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
  overflow: hidden;
}

.profile-logo {
  width: 100%;
  height: 100%;
  border-radius: 80%;
  object-fit: cover;
}

/* --- TEXTOS Y LISTA --- */
.card-content {
  padding: 3rem 2rem 2rem;
}

h1 {
  color: #1e293b;
  font-size: 2.2rem;
  margin: 0 0 1rem;
  font-weight: 800;
  letter-spacing: -0.5px;
}

.purpose {
  color: #64748b;
  font-size: 1.1rem;
  line-height: 1.6;
  margin: 0 auto 2.5rem;
  max-width: 90%;
}

.info-section h2 {
  color: #2563eb;
  font-size: 1rem;
  margin-bottom: 1.5rem;
  text-transform: uppercase;
  letter-spacing: 1.5px;
  font-weight: 700;
}

.datos-lista {
  list-style: none;
  padding: 1.5rem 2rem;
  margin: 0 auto 2.5rem;
  text-align: left;
  display: inline-block;
  background: #eff6ff;
  border-radius: 12px;
  color: #334155;
  border: 1px solid #dbeafe;
}

.datos-lista li {
  margin-bottom: 1rem;
  font-size: 1.1rem;
}

.datos-lista li:last-child {
  margin-bottom: 0;
}

.datos-lista strong {
  color: #1e293b;
  margin-right: 0.5rem;
}
</style>
