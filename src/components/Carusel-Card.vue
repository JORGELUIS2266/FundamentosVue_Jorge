<script setup>
import CardRow from './Card-Row.vue';
import Carrusel from './Carrusel.vue';
import Tabla from './tabla.vue';
</script>
<template>
    <div class="row">
      <!-- Inicio del col-md-6 para los juegos mas populares -->
      <div class="col-md-6">
        <div class="card mt">
          <div style="background-color: #E94560;" class="card-header">
            <h1 style="color: beige; font-size: 40px; font-family: 'Open Sans', sans-serif; text-transform: uppercase; letter-spacing: 3px; text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.5);">  
              VIDEOJUEGOS MÁS POPULARES  
            </h1>
          </div>
          <div class="card-body">
            <!-- inicio de carrusel de reproduccion automatico -->
            <Carrusel/>
          </div>
        </div>
        <!-- Inicio de la tabla principal -->
        <br>
        <Tabla/>
      </div>
      <!-- Fin del col-md-6 para los juegos mas populares -->
      <!-- Inicio del col-md-6 para la lista de Videojuegos-->
      <CardRow/>
      <!-- Fin del col-md-6 par la Lista de Videojuegos -->
    </div>
    <!-- Fin del row principal -->
  </template>
  
  <script>
  export default {
    name: 'VideojuegosComponent',
    // Aquí puedes agregar lógica de JavaScript si es necesario
  }
  </script>
  
  <style scoped>
  /* Estilos básicos */
  .card-header {
    background-color: #E94560;
  }
  
  h1, h2 {
    color: beige;
    font-size: 40px;
    font-family: 'Open Sans', sans-serif;
    text-transform: uppercase;
    letter-spacing: 3px;
    text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.5);
  }
  
  .btn {
    background-color: #E94560;
    color: white;
  }
  </style>