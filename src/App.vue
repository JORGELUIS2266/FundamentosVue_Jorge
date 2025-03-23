<script setup>
import CaruselCard from './components/Carusel-Card.vue';
import Container from './components/Container.vue';
import Footer from './components/Footer.vue';
import Navbar from './components/navbar.vue';
</script>

<template>
  <div class="d-flex flex-column min-vh-100">
    <Navbar />
    <main class="flex-grow-1 pt-5"> <!-- AÑADIR pt-5 para empujar contenido -->
      <router-view />
      <Container/>
       <CaruselCard/>  
    </main>
    <Footer/>
  </div>
</template>

<style scoped>
</style>
