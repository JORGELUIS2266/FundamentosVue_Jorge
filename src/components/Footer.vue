<template>
    <footer class="bg-dark text-white mt-5">
      <div class="container py-4">
        <!-- Sección de descarga de la aplicación -->
        <div class="row">
          <div class="col-md-12 text-center">
            <h4>DESCARGA LA APLICACIÓN</h4>
            <h5>GAMES</h5>
  
            <!-- Iconos de redes sociales -->
            <div class="mt-3">
              <a href="#" class="text-white mx-3"><i class="bi bi-twitter" style="font-size: 1.5rem;"></i></a>
              <a href="#" class="text-white mx-3"><i class="bi bi-youtube" style="font-size: 1.5rem;"></i></a>
              <a href="#" class="text-white mx-3"><i class="bi bi-instagram" style="font-size: 1.5rem;"></i></a>
              <a href="#" class="text-white mx-3"><i class="bi bi-facebook" style="font-size: 1.5rem;"></i></a>
            </div>
  
            <p class="mt-3">© 2020-2025 GAMES, Inc. Compara, compra y disfruta de los videojuegos más populares. Todos los derechos reservados.</p>
          </div>
        </div>
  
        <!-- Sección de enlaces -->
        <div class="row mt-3">
          <div class="col-md-12 text-center">
            <h5>ENLACES</h5>
            <ul class="list-unstyled d-inline">
              <li class="d-inline mx-3"><a href="#" class="text-white">AVISO DE PRIVACIDAD</a></li>
              <li class="d-inline mx-3"><a href="#" class="text-white">TÉRMINOS DE SERVICIO</a></li>
              <li class="d-inline mx-3"><a href="#" class="text-white">PREFERENCIAS DE COOKIES</a></li>
            </ul>
          </div>
        </div>
  
        <!-- Sección de advertencias -->
        <div class="row mt-3">
          <div class="col-md-12 text-center">
            <p>Sangre | Lenguaje | Violencia | Interacción de usuarios | Compras dentro del juego</p>
          </div>
        </div>
  
        <!-- Sección de Contactos -->
        <div class="row mt-4">
          <div class="col-md-12 text-center">
            <h5>CONTACTO</h5>
            <div class="row justify-content-center">
              <!-- Columna 1: Correos electrónicos -->
              <div class="col-md-4">
                <ul class="list-unstyled">
                  <li><i class="bi bi-envelope"></i> <a href="mailto:Fernando08castellanos@gmail.com" class="text-white">Fernando08castellanos@gmail.com</a></li>
                  <li><i class="bi bi-envelope"></i> <a href="mailto:Valeria12alcantara@emailfalso.com" class="text-white">Valeria12alcantara@emailfalso.com</a></li>
                </ul>
              </div>
  
              <!-- Columna 2: Teléfonos -->
              <div class="col-md-4">
                <ul class="list-unstyled">
                  <li><i class="bi bi-telephone"></i> <a href="tel:+1234567890" class="text-white">+123 456 7890</a></li>
                  <li><i class="bi bi-telephone"></i> <a href="tel:+525598762103" class="text-white">+52 55 9876 2103</a></li>
                </ul>
              </div>
  
              <!-- Columna 3: Direcciones -->
              <div class="col-md-4">
                <ul class="list-unstyled">
                  <li><i class="bi bi-geo-alt"></i> Calle Siempre Viva #742, CDMX, México</li>
                  <li><i class="bi bi-geo-alt"></i> Avenida Magnolia #275, Colonia Altos del Bosque, CDMX, México</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: "AppFooter", // Nombre del componente
  };
  </script>
  
  <style scoped>
  /* Estilos específicos para este componente */
  .bg-dark {
    background-color: #343a40 !important;
  }
  
  .text-white {
    color: white !important;
  }
  
  .mt-5 {
    margin-top: 3rem !important;
  }
  
  .py-4 {
    padding-top: 1.5rem !important;
    padding-bottom: 1.5rem !important;
  }
  
  .mt-3 {
    margin-top: 1rem !important;
  }
  
  .mx-3 {
    margin-left: 1rem !important;
    margin-right: 1rem !important;
  }
  
  .d-inline {
    display: inline !important;
  }
  
  .list-unstyled {
    list-style: none;
    padding-left: 0;
  }
  
  .justify-content-center {
    justify-content: center !important;
  }
  
  .text-center {
    text-align: center !important;
  }
  </style>