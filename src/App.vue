<template>
  <div id="app" class="bg-light">
    <!-- Aquí insertaremos el NavBar más adelante -->
    <Navbar />
    <header>
      <h1 class="text-center p-4 text-primary">Bienvenido a Cursos AlfaWeb</h1>
    </header>

    <!-- Contenido principal, donde podrían ir las vistas o componentes -->
    <main class="container mt-4">
      <!-- Ejemplo de contenido provisional -->
      <p>Contenido inicial de la aplicación</p>
    </main>

    <router-view></router-view>

    <!-- Aquí insertaremos el Footer más adelante -->
     <Footer />
  </div>
 
</template>

<script>
import Navbar from './components/AppNavbar.vue';
import Footer from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>
/* Opcional: Estilos locales o globales */
</style>