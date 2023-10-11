<template>
   <div class="flex items-center justify-center bg-gray-800">
        <div class="flex max-w-4xl bg-transparent rounded-md w-full overflow-hidden">
            <div class="flex-1 p-6 bg-transparent">
                <div class="bg-gray-600 bg-opacity-50 text-white uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-1/3">
                Conoce a TusDatos.co
                </div>
                <br>
                <h1 class="text-[2rem] text-white font-semibold mb-4">Consulta de antecedentes en un clic</h1>
                <p class="text-base mt-2 text-gray-500">
                    Valida datos de clientes, proveedores o colaboradores en segundos y en tiempo real para prevenir riesgos en tus procesos de selección o contratación
                </p>
                <br>
                <div class="grid grid-cols-2 grid-rows-3 gap-2">
                    <div>
                        <input type="text" id="nombre" name="nombre" class="px-4 py-3 border border-gray-400 block w-full mt-2 bg-gray-700 text-white rounded transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu nombre" />
                    </div>
                    <div>
                        <input type="text" id="apellido" name="apellido" class="px-4 py-3 border border-gray-400 block w-full mt-2 bg-gray-700 text-white rounded transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu apellido" />
                    </div>
                    <div>
                        <input type="text" id="email" name="email" class="px-4 py-3 border border-gray-400 block w-full mt-2 bg-gray-700 text-white rounded transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu correo corporativo" />
                    </div>
                    <div>
                        <input type="text" id="celular" name="celular" class="px-4 py-3 border border-gray-400 block w-full mt-2 bg-gray-700 text-white rounded transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu celular" />
                    </div>
                    <div>
                        <input type="text" id="empresa" name="empresa" class="px-4 py-3 border border-gray-400 block w-full mt-2 bg-gray-700 text-white rounded transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu empresa" />
                    </div>
                    <div>
                        <input type="text" id="cargo" name="cargo" class="px-4 py-3 border border-gray-400 block w-full mt-2 bg-gray-700 text-white rounded transition duration-300 ease-in-out focus:bg-white focus:placeholder-white focus:text-black" placeholder="Tu cargo"/>
                    </div>
                </div>
                <button class="bg-white text-gray-800 px-4 py-3 mt-4 rounded text-[0.75rem] font-bold">
                    ¡QUIERO QUE ME CONTACTEN!
                </button>
                <div class="text-gray-300 text-[0.58rem] py-5 px-1">
                    *Al completar el formulario <a class="link" href="#">autorizas</a> de forma expresa el tratamiento de tus datos personales            
                </div>
            </div>

            <!-- Columna de imagen con flexbox -->
            <div class="flex-1 p-6 bg-transparent">
                <img src="@/assets/robot.png" alt="Imagen" class="w-full h-auto" />
            </div>
        </div>
    </div>

    <div class="bg-white flex flex-col items-center justify-center ">

        <div class="flex flex-col max-w-4xl bg-transparent w-full p-4">

            <div class="bg-gray-200 text-gray-600 text-[0.65rem] px-2 py-1 rounded-md text-center mb-4 self-center font-bold">
                CONFÍAN EN NOSOTROS
            </div>

            <div class="grid grid-cols-4 grid-rows-2 gap-4 py-1">
                <img src="@/assets/superior.png" alt="superior" class="w-full h-1/2 object-scale-down" />
                <img src="@/assets/ifood.png" alt="ifood" class="w-full h-1/2 object-scale-down" />
                <img src="@/assets/puntored.png" alt="punto_red" class="w-full h-1/2 object-scale-down" />
                <img src="@/assets/khiron.png" alt="khiron" class="w-full h-1/2 object-scale-down" />

                <img src="@/assets/brinks.png" alt="brinks" class="w-full h-1/2 object-scale-down" />
                <img src="@/assets/feoracle.png" alt="feoracle" class="w-full h-1/2 object-scale-down" />
                <img src="@/assets/bold.png" alt="bold" class="w-full h-1/2 object-scale-down" />
                <img src="@/assets/ciac.png" alt="ciac" class="w-full h-1/2 object-scale-down" />
            </div>

        </div>

        <div class="bg-gray-600 text-white text-lg py-5 flex items-center justify-center w-full">

            <div class="inline-block text-center font-bold">
                <h3>🚀 Una plataforma de primera categoría para la consulta de antecedentes y terceros</h3>
            </div>

            <button class="bg-white text-gray-800 px-4 py-0.5 rounded ml-4 font-bold text-[0.7rem]">CONTÁCTANOS</button>

        </div>

    </div>

</template>

<style>
    ::placeholder, input{
        font-size: 0.75rem;
    }
</style>