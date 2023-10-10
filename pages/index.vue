<template>
   <div class="flex items-center justify-center min-h-screen bg-gray-800">
        <!-- Contenedor principal con flexbox -->
        <div class="flex max-w-4xl bg-transparent rounded-md w-full overflow-hidden">
        <!-- Columna de campos del formulario con flexbox -->
        <div class="flex-1 p-6 bg-transparent">

            <!-- Label "Conoce a TusDatos.co" con fondo medio transparente -->
            <div class="bg-gray-600 bg-opacity-50 text-white uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-1/3">
            Conoce a TusDatos.co
            </div>
            <br>
            <!-- Título del formulario -->
            <h1 class="text-[2rem] text-white font-semibold mb-4">Consulta de antecedentes en un clic</h1>
            <p class="text-base mt-2 text-gray-500">
                Valida datos de clientes, proveedores o colaboradores en segundos y en tiempo real para prevenir riesgos en tus procesos de selección o contratación
            </p>
            <br>
            <!-- Campos de texto como celdas de la grilla -->
            <div class="grid grid-cols-2 grid-rows-3 gap-2">
            <!-- Campo 1: Nombre -->
                <div>
                    <input type="text" id="nombre" name="nombre" class=" border border-gray-400 block w-full mt-2 bg-gray-700 text-white p-2 rounded-md transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu nombre" />
                </div>
            <!-- Campo 2: Correo Electrónico -->
                <div>
                    <input type="text" id="apellido" name="apellido" class="border border-gray-400 block w-full mt-2 bg-gray-700 text-white p-2 rounded-md transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu apellido" />
                </div>
            <!-- Campo 3: Teléfono -->
                <div>
                    <input type="text" id="email" name="email" class="border border-gray-400 block w-full mt-2 bg-gray-700 text-white p-2 rounded-md transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu correo corporativo" />
                </div>
            <!-- Campo 4: Asunto -->
                <div>
                    <input type="text" id="celular" name="celular" class="border border-gray-400 block w-full mt-2 bg-gray-700 text-white p-2 rounded-md transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu celular" />
                </div>
            <!-- Campo 5: Mensaje -->
                <div>
                    <input type="text" id="empresa" name="empresa" class="border border-gray-400 block w-full mt-2 bg-gray-700 text-white p-2 rounded-md transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu empresa" />
                </div>
            <!-- Campo 6: Adjuntar Archivo -->
                <div>
                    <input type="text" id="cargo" name="cargo" class="border border-gray-400 block w-full mt-2 bg-gray-700 text-white p-2 rounded-md transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu cargo"/>
                </div>
            </div>

            <button class="bg-white text-gray-800 px-4 py-2 mt-4 rounded-md text-xs font-bold">
                ¡QUIERO QUE ME CONTACTEN!
            </button>

        </div>

        <!-- Columna de imagen con flexbox -->
        <div class="flex-1 p-6 bg-transparent">
            <img src="@/assets/robot.png" alt="Imagen" class="w-full h-auto" />
        </div>
        </div>
    </div>
</template>

<style>
    ::placeholder, input{
        font-size: small;
    }
</style>