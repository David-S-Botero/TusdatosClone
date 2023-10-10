<template>
    <div class="bg-pink-500 min-h-screen">
        <!-- Encabezado -->
        <header class="bg-transparent p-4">
        <div class="container mx-auto flex justify-between items-center">
            <!-- Logo y Nombre de la página -->
            <div class="flex items-center">
            <img src="@/assets/logo.png" alt="Logo" class="w-10 h-10 mr-2" />
            <h1 class="text-white text-2xl font-semibold">Tusdatos.co</h1>
            </div>
            <!-- Opciones de navegación -->
            <div class="hidden md:flex space-x-6">
            <!-- Router-Links con cambio de color de fondo en hover -->
            <router-link to="/" class="text-white hover:bg-pink-600 hover:text-white px-2 py-1 rounded">Home</router-link>
            <router-link to="/" class="text-white hover:bg-pink-600 hover:text-white px-2 py-1 rounded">Nosotros</router-link>
            <router-link to="/" class="text-white hover:bg-pink-600 hover:text-white px-2 py-1 rounded">Blog</router-link>
            <router-link to="/" class="text-white hover:bg-pink-600 hover:text-white px-2 py-1 rounded">Ecuador</router-link>
            <router-link to="/" class="text-white hover:bg-pink-600 hover:text-white px-2 py-1 rounded">Servicios</router-link>
            </div>
            <!-- Botones de inicio de sesión y contacto -->
            <div class="flex items-center space-x-4">
            <button class="bg-transparent border border-white text-white px-3 py-1 rounded-md text-sm">LOGIN</button>
            <button class="bg-white text-pink-500 px-3 py-1 rounded-md font-bold text-sm">CONTÁCTANOS</button>
            </div>
        </div>
        </header>
    </div>
    
    <slot />
  <footer class="bg-white text-white p-6 border-t border-gray-300">
    <div class="container mx-auto flex flex-col md:flex-row">
      <!-- Columna lateral sin contenido -->
      <div class="w-full md:w-1/12"></div>

      <!-- Cuatro columnas con contenido -->
      <div class="w-full md:w-5/6">
        <!-- Primera fila de cuatro mini columnas -->
        <div class="flex flex-wrap"> <!-- Mantenemos flex-wrap -->
          <!-- Mini columna 1 -->
          <div class="w-full md:w-1/4 bg-white p-4"> <!-- Cambiamos a md:w-1/4 y aplicamos bg-white -->
            <!-- Logo y Nombre de la página -->
            <div class="flex items-center mb-2">
              <img src="@/assets/logo.png" alt="Logo" class="w-10 h-10 mr-2" />
              <h2 class="text-xl font-semibold text-gray-800">Tusdatos.co</h2>
            </div>

            <h1 class="text-2xl text-gray-800 font-bold"><br>Contáctanos</h1>
            <!-- Párrafo -->
            <p class="text-gray-500  text-sm mt-2"><br>Cra 7 # 24 - 89 oficina 4401 <br><br>Bogotá, Colombia <br><br>+57 305 4082874 <br><br>info@tusdatos.co</p>
          </div>

          <!-- Mini columna 2 -->
          <div class="w-full md:w-1/4 bg-white p-4"> <!-- Cambiamos a md:w-1/4 y aplicamos bg-white -->
            <!-- Párrafo con texto aleatorio -->
            <p class="text-sm mt-2 text-gray-500">Tusdatos.co recolecta y centraliza la información requerida para brindar una mayor tranquilidad y seguridad.</p>


            <h2 class="text-xl text-gray-800 font-bold"><br>Redes Sociales</h2>
            <!-- Contactos por redes sociales en mini iconos -->
            <div class="flex mt-4">
                <a href="#" class="text-black  rounded-lg p-2 transition duration-300 ease-in-out border border-gray-300 mr-4">
                    <i class="fab fa-facebook font-bold">F</i>
                </a>
                <a href="#" class="text-black  rounded-lg p-2 transition duration-300 ease-in-out border border-gray-300 mr-4">
                    <i class="fab fa-twitter font-bold">T</i>
                </a>
                <a href="#" class="text-black  rounded-lg p-2 transition duration-300 ease-in-out border border-gray-300 mr-4">
                    <i class="fab fa-instagram font-bold">I</i>
                </a>
              <!-- Agrega más iconos y enlaces según tus necesidades -->
            </div>
          </div>

          <!-- Mini columna 3 -->
          <div class="w-full md:w-1/4 bg-white text-black p-4"> <!-- Cambiamos a md:w-1/4 y aplicamos bg-white y text-black -->
            <!-- Contenido aleatorio -->
            <h2 class="text-xl text-gray-800 font-bold">Mapa del sitio</h2>
            <p class="text-gray-500  text-sm mt-2">
                <br>
                Home<br><br>
                Contáctanos<br><br>
                Cumplimiento<br><br>
                Blog<br><br>
                Nosotros<br><br>
                Aviso de privacidad<br><br>
                Términos y condiciones<br><br>
                Política de tratamiento de datos<br><br>
            </p>
          </div>

          <div class="w-full md:w-1/4 bg-white p-4">
            <h2 class="text-xl text-gray-800 font-bold">Apoyados por</h2><br>
            <!-- Lista de imágenes -->
            <div class="grid grid-cols-2 gap-4">
              <img src="@/assets/colombia.png" alt="Imagen 1" class="w-full h-auto" /><br>
              <img src="@/assets/rockstar.svg" alt="Imagen 2" class="w-full h-auto" /><br>
              <img src="@/assets/eventure.png" alt="Imagen 3" class="w-full h-auto" /><br>
              <img src="@/assets/fintech.png" alt="Imagen 4" class="w-full h-auto" /><br>
              <img src="@/assets/woa.png" alt="Imagen 5" class="w-full h-auto" />
              <!-- Agrega más imágenes según sea necesario -->
            </div>
          </div>
        </div>

        <!-- Columna grande debajo estirada de lateral a lateral con borde superior -->
        <div class="border-t border-gray-300 bg-white mt-4  text-gray-500 text-xs">
          <!-- Contenido aleatorio -->
          <p class="p-4">© Tusdatos.co 2018 - 2022.</p>
        </div>
      </div>

      <!-- Columna lateral sin contenido -->
      <div class="w-full md:w-1/12"></div>
    </div>
  </footer>
</template>