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

        <div class="bg-gray-600 text-white text-base py-5 flex items-center justify-center w-full">

            <div class="inline-block text-center font-bold">
                <h3>🚀 Una plataforma de primera categoría para la consulta de antecedentes y terceros</h3>
            </div>

            <button class="bg-white text-gray-800 px-4 py-0.5 rounded ml-4 font-bold text-[0.7rem]">CONTÁCTANOS</button>

        </div>
        <div class="felx flex-col bg-white w-full justify-center items-center self-center">
            <h1 class="bg-transparent text-gray-600  text-2xl px-2 py-3 text-center mb-4 self-center font-bold">Consultar antecedentes y terceros es muy fácil con Tusdatos</h1>
            <p class="text-center text-[1.1rem] self-center text-gray-700">
                Las validaciones de antecedentes y de contrapartes son fundamentales para garantizar la seguridad y <br> confiabilidad en las empresas.
            </p>
            <p class="text-center text-[1.1rem] self-center text-gray-700 py-3">
                Al realizarlas, se cubren distintos aspectos según el tipo de consulta:
            </p>
            <div class="flex flex-col items-center justify-center">
                <div class="max-w-screen-xl mx-auto">
                    <div class="grid grid-cols-4 gap-0 max-w-4xl py-6">
                        <!-- Columna 1 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 1 -->
                            <div class="container mx-auto w-1/3 rounded-full py-4">
                                <img src="@/assets/camion.png" alt="vehiculo" class="object-scale-down">
                            </div>

                            
                            <h2 class = "text-center text-xl font-bold text-gray-600">Vehículos</h2>
                            <p class="text-justify text-[0.8rem] text-gray-500">La verificación de datos como propietario, historial de multas, robos y accidentes, permite tomar decisiones informadas al adquirir o contratar vehículos, minimizando riesgos y asegurando la tranquilidad en tus operaciones.</p>
                        </div>

                        <!-- Columna 2 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg  border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 2 -->
                            <div class="container mx-auto w-1/3 rounded-full py-4">
                                <img src="@/assets/persona_natural.png" alt="persona_natural">
                            </div>
                            <h2 class="text-center text-xl font-bold text-gray-600">Persona Natural</h2>
                            <p class="text-justify text-[0.8rem] text-gray-500">Conocer sus antecedentes permite tomar decisiones informadas en procesos de contratación y selección, mitigando riesgos, fraude y protegiendo la integridad de tu compañía.</p>

                        </div>

                        <!-- Columna 3 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                        <!-- Contenido de la columna 3 -->
                        <div class="container mx-auto w-1/3 rounded-full py-4">
                            <img src="@/assets/persona_juridica.png" alt="persona_juridica">
                        </div>
                        
                        <h2 class="text-center text-xl font-bold text-gray-600">Persona Jurídica</h2>
                        <p class="text-justify text-[0.8rem] text-gray-500">Verificar la legalidad, solidez  y cumplimiento tributario de empresas, sociedades o proveedores, asegura relaciones comerciales transparentes y fortalece la cadena de valor en tu negocio.</p>

                        </div>

                        <!-- Columna 4 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg h-80">
                        <!-- Contenido de la columna 4 -->
                        <div class="container mx-auto w-1/3 rounded-full py-4">
                            <img src="@/assets/persona_extranjera.png" alt="persona_extranjera">
                        </div>
                        
                        <h2 class="text-center text-xl font-bold text-gray-600">Persona Extranjera</h2>
                        <p class="text-justify text-[0.8rem] text-gray-500">Al validar antecedentes de ciudadanos extranjeros, se cumple con normativas locales e internacionales, y se garantiza la idoneidad de colaboradores, clientes o socios provenientes de otros países.</p>

                        </div>
                    </div>
                    <p class="max-w-4xl text-center py-5 text-gray-700 text-[1.1rem]">
                        Sólo debes ingresar el número de documento: sea cedula de ciudadanía (CC), Número de identificación tributario (NIT), Permiso de protección temporal (PPT), cedula de extranjería (CE) o pasaporte (PP) y encontrarás la información relevante para tus procesos de contratación y selección, en un clic y menos de un minuto.</p>

                </div>
                <div class="grid grid-cols-2 gap-4 max-w-5xl py-12">
                    <div class="col-span-1">
                        <div class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-1/4 text-center">
                            nuestra misión
                        </div>
                        <h2 class="align-left text-[1.5rem] font-semibold text-gray-800 py-2">
                            Tusdatos.co recolecta y <br> centraliza la información <br> requerida para brindar una <br> mayor tranquilidad y seguridad
                        </h2>
                        <div class="flex items-center py-3 ">
                            <!-- Imagen a la izquierda -->
                            <div class="w-16 h-16 mr-4 ">
                                <img src="@/assets/shz.png" alt="Imagen de la persona" class="w-full h-full rounded-full" />
                            </div>
                            <!-- Nombre y cargo a la derecha -->
                            <div>
                                <h2 class="text-[1.25rem] font-medium text-gray-800">Santiago Hernández Zambrano</h2>
                                <p class="py-2 uppercase text-[0.6rem] font-medium text-gray-400">ceo y fundador de tusdatos.co</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-span-1">
                        <iframe
                        width="500"
                        height="315"
                        :src="`https://www.youtube.com/watch?v=Bd76kqrl-pc&embeds_referring_euri=https%3A%2F%2Fwww.tusdatos.co%2F&source_ve_path=Mjg2NTksMjg2NjY&feature=emb_logo&ab_channel=Tusdatosco`"
                        title="Video player"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen
                        ></iframe>
                    </div>
                </div>
                <div class="items-center self-center w-1/2 py-8">
                    <img src="@/assets/tablet.png" alt="tablet">
                </div>
                <div class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-1/8 text-center">
                    EVIDENCIAS
                </div>
                <div class="grid grid-cols-2 gap-4 max-w-5xl py-12 pt-0">
                    <div class="col-span-1">
                        <img src="@/assets/imSlider1.jpg" alt="imSlider1">
                    </div>
                    <div class="col-span-1 px-8">
                        <h1 class="text-[1.5rem] text-left font-semibold">
                            Tus consultas quedan con <br> soportes de la fuente viva
                        </h1>
                        <p class="py-3 text-gray-700 text-[1rem]">
                            Deja atrás las bases de datos pre-cargadas para la realización de estudios de seguridad y debida diligencia. En Tusdatos.co las fuentes son consultadas en el momento que solicitas el estudio. <br>
                            Capturamos evidencias de las consultas realizadas donde se demuestra la fecha y hora en la que se ejecutó.
                            Pueden ser usadas como evidencia jurídica de la realización del proceso de debida diligencia.
                        </p>
                        <button class="uppercase bg-gray-700 text-white px-4 py-3 mt-4 rounded text-[0.7rem] font-bold w-1/2">
                            compra un paquete hoy
                        </button>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex flex-col bg-gray-600 w-full">

            <h1 class="bg-transparent text-white text-2xl px-2 py-2 text-center mb-4 self-center font-bold">
                Asociados
            </h1>

            <div class="bg-transparent grid grid-cols-6 grid-rows-1 gap-x-8 p-0 items-center">
                <img src="@/assets/fenalco.png" alt="fenalco" class="h-1/2 w-full object-down" />
                <img src="@/assets/woa_w.png" alt="woa" class="h-1/2 w-full object-scale-down" />
                <img src="@/assets/fintech_w.png" alt="fintech" class="h-1/2 w-full object-scale-down" />
                <img src="@/assets/andi.png" alt="andi" class="h-1/2 w-full object-scale-down" />
                <img src="@/assets/rockstar_w.svg" alt="rockstar" class="h-1/2 w-full object-scale-down" />
                <img src="@/assets/colombia_w.png" alt="colombia" class="h-1/2 w-full object-scale-down" />
            </div>

        </div>
        <div class="felx flex-col bg-white w-full justify-center items-center self-center">
            <div class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-1/8 text-center">
                PLANES
            </div>
            <h1 class="bg-transparent text-gray-600  text-2xl px-2 py-3 text-center mb-4 self-center font-bold">Planes simples y completos</h1>
            <p class="text-center text-[1.1rem] self-center text-gray-700">
                Precios transparentes en pesos y sin cargos ocultos, para que te puedas beneficiar inmediatamente. Los planes son activados de manera manual y requerimos documentación soporte para su activación. Al realizar una compra aceptas nuestros términos y condiciones.
            </p>
            <div class="flex flex-col items-center justify-center">
                <div class="max-w-screen-xl mx-auto">
                    <div class="grid grid-cols-3 gap-0 max-w-4xl py-6">
                        <!-- Columna 1 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 1 -->
                            <h1>PLAN Internet 100</h1>
                            <h1>$450.000</h1>
                            <p>VENCIMIENTO 24 MES</p>
                            <img src="@/assets/ePayco.png" alt="ePayco">
                        </div>

                        <!-- Columna 2 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg  border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 2 -->
                            <div class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-1/8 text-center">
                                POPULAR
                            </div>
                            <h1>PLAN BLindado 400</h1>
                            <br>
                            <div>
                                <hr>
                                100 consultas
                                <hr>
                                Antecedentes
                                <hr>
                                Listas restrictivas
                                <hr>
                                Capturas de pantalla
                                <hr>
                                Reportes en PDF
                                <hr>
                                Soporte vía email
                                <hr>
                                Relacionados
                                <hr>
                                Noticias reputacionales
                            </div>
                            <h1>$1'060.000</h1>
                            <p>VENCIMIENTO 24 MES</p>
                            <img src="@/assets/ePayco.png" alt="ePayco">
                        </div>

                        <!-- Columna 3 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 3 -->
                            <h1>PLAN BLindado 1000</h1>
                            <h1>$2'350.000</h1>
                            <p>VENCIMIENTO 24 MES</p>
                            <img src="@/assets/ePayco.png" alt="ePayco">
                        </div>

                    </div>
                    <p class="max-w-4xl text-center py-5 text-gray-700 text-[1.1rem]">
                        No dudes en contactarnos si tienes preguntas sobre nuestros planes. Estamos aquí para ayudarte. No olvides revisar nuestras preguntas frecuentes.    
                    </p>

                    <h1>📈✨ ¿Necesitas un mayor volumen de consultas?</h1>
                    <p>
                        No hay problema, contamos con planes corporativos de más de 100.000 consultas a precios altamente competitivos. ¡Impulsa tu negocio con nuestra oferta excepcional! 💼🌟
                    </p>
                    <button class="bg-white text-gray-800 px-4 py-0.5 rounded ml-4 font-bold text-[0.7rem]">CONTÁCTANOS</button>
                    <div class="grid grid-cols-3 gap-0 max-w-4xl py-6">
                        <!-- Columna 1 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 1 -->
                            <h1>+2'700.000</h1>
                            <p>reportes entregados</p>
                        </div>

                        <!-- Columna 2 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg  border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 2 -->
                            <h1>+5'500.000</h1>
                            <p>horas ahorradas</p>
                        </div>

                        <!-- Columna 3 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                            <!-- Contenido de la columna 3 -->
                            <h1>+4190</h1>
                            <p>usuarios felices</p>
                            
                        </div>
                    </div>

                </div>

            </div>
        </div>
        
        <div class="flex flex-col bg-gray-600 w-full p-4">

            <div class="bg-transparent text-white text-[1.75rem] px-2 py-1 rounded-md text-center mb-4 self-center font-base">
                📰 Tusdatos en la prensa 📰
            </div>

            <div class="bg-transparent grid grid-cols-6 grid-rows-1 p-0 max-w-6xl self-center gap-0">
                <img src="@/assets/forbes.png" alt="forbes" class="w-full h-1/2 object-contain" />
                <img src="@/assets/enter.png" alt="enter" class="w-full h-1/2 object-contain" />
                <img src="@/assets/referente.png" alt="referente" class="w-full h-1/2 object-contain" />
                <img src="@/assets/startups.png" alt="startups" class="w-full h-1/2 object-contain" />
                <img src="@/assets/dinero.png" alt="dinero" class="w-full h-1/2 object-contain" />
                <img src="@/assets/portafolio.png" alt="portafolio" class="w-full h-1/2 object-scale-down" />
            </div>

        </div>
        
        
        <div class="bg-gray-600 text-white text-base py-5 flex items-center justify-center w-full">

            <div class="inline-block text-center font-bold">
                <h3>🚀 Reduce hasta en un 80% el tiempo y costo en tus procesos de validación, optimizando recursos y mejorando la eficiencia de tu negocio. 💼⏱️💰</h3>
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