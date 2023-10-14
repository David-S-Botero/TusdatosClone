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

                        <div class="col-span-1 p-4 bg-white shadow-lg  border-r-2 border-gray h-80">
                            <div class="container mx-auto w-1/3 rounded-full py-4">
                                <img src="@/assets/persona_natural.png" alt="persona_natural">
                            </div>
                            <h2 class="text-center text-xl font-bold text-gray-600">Persona Natural</h2>
                            <p class="text-justify text-[0.8rem] text-gray-500">Conocer sus antecedentes permite tomar decisiones informadas en procesos de contratación y selección, mitigando riesgos, fraude y protegiendo la integridad de tu compañía.</p>

                        </div>

                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-80">
                        <div class="container mx-auto w-1/3 rounded-full py-4">
                            <img src="@/assets/persona_juridica.png" alt="persona_juridica">
                        </div>
                        
                        <h2 class="text-center text-xl font-bold text-gray-600">Persona Jurídica</h2>
                        <p class="text-justify text-[0.8rem] text-gray-500">Verificar la legalidad, solidez  y cumplimiento tributario de empresas, sociedades o proveedores, asegura relaciones comerciales transparentes y fortalece la cadena de valor en tu negocio.</p>

                        </div>

                        <div class="col-span-1 p-4 bg-white shadow-lg h-80">
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
                            <div class="w-16 h-16 mr-4 ">
                                <img src="@/assets/shz.png" alt="Imagen de la persona" class="w-full h-full rounded-full" />
                            </div>
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
        <div class="felx flex-col bg-white w-full justify-center items-center">
            <div class="flex justify-center pt-6">
                <p class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-16 text-center  self-center">
                    PLANES
                </p>
            </div>
            <h1 class="bg-transparent text-gray-600  text-2xl px-2 pb-0 text-center mb-4 self-center font-bold">Planes simples y completos</h1>
            <p class="text-center text-[0.9rem] self-center text-gray-700 self-center mb-4 px-2 pt-0">
                Precios transparentes en pesos y sin cargos ocultos, para que te puedas beneficiar <br> inmediatamente. Los planes son activados de manera manual y requerimos <br> documentación soporte para su activación. Al realizar una compra aceptas nuestros <br> <a href="#">términos y condiciones.</a> 
            </p>
            <div class="flex flex-col items-center justify-center">
                <div class="max-w-screen-xl mx-auto py-7">
                    
                    <div class="flex items-center justify-center max-w-full">
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-96 self-start w-1/3 h-auto">
                            <h1 class="text-center font-semibold">PLAN Internet 100</h1>
                            <br>
                            <div class="text-[0.9rem] p-4">
                                <hr>
                                <b>100</b> consultas
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
                           
                            <h1 class="text-center pt-3 text-[2rem] font-semibold">$450.000</h1>
                            <p class="text-center pb-3 text-[0.6rem] text-gray-400">VENCIMIENTO 24 MES</p>
                            <div class="ietms-center self-center">
                                <img src="@/assets/ePayco.png" alt="ePayco" class="object-scale-down justify-center w-full">
                            </div>
                        </div>
                        <div class=" flex grid col-span-1 p-4 bg-white shadow-lg bg-gray-700  border-r-2 border-gray h-96 w-1/3  h-auto justify-center">
                            <div class="flex justify-center pt-6">
                                <p class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 w-16 text-center  self-center">
                                    PLANES
                                </p>
                            </div>
                            <h1 class="text-center py-5 font-semibold">PLAN Blindado 400</h1>
                            <br>
                            <div class="text-[0.9rem] p-4">
                                <hr>
                                <b>400</b> consultas
                                <hr>
                                Antecedentes
                                <hr>
                                Listas restrictivas
                                <hr>
                                Capturas de pantalla
                                <hr>
                                Reportes en PDF
                                <hr>
                                Soporte vía email y teléfono
                                <hr>
                                <span class="text-gray-400">Relacionados</span>
                                <hr>
                                <span class="text-gray-400">Noticias reputacionales</span>
                            </div>
                            <h1 class="text-center pt-3 text-[2rem] font-semibold">$1'060.000</h1>
                            <p class="text-center pb-3 text-[0.6rem] text-gray-400">VENCIMIENTO 24 MES</p>
                            <div class="ietms-center self-center">
                                <img src="@/assets/ePayco.png" alt="ePayco" class="object-scale-down justify-center w-full">
                            </div>
                        </div>

                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 bg-gray-700 border-gray h-96 self-start w-1/3 h-auto">
                            <h1 class="text-center font-semibold">PLAN BLindado 1000</h1>
                            <br>
                        
                            <div class="text-[0.9rem] p-4">
                                <hr>
                                <b>1000 </b> consultas
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
                            
                            <h1 class="text-center pt-3 text-[2rem] font-semibold">$2'350.000</h1>
                            <p class="text-center pb-3 text-[0.6rem] text-gray-400">VENCIMIENTO 24 MES</p>
                            <div class="ietms-center self-center">
                                <img src="@/assets/ePayco.png" alt="ePayco" class="object-scale-down justify-center w-full">
                            </div>
                        </div>
                    </div>
                    <p class="max-w-4xl text-center py-5 text-gray-700 text-[0.55rem]">
                        No dudes en contactarnos si tienes preguntas sobre nuestros planes. Estamos aquí para ayudarte. No olvides revisar nuestras preguntas frecuentes.    
                    </p>

                    <h1 class="bg-transparent text-gray-600 text-[1rem] px-2 py-1 rounded-md text-center mb-4 self-center font-bold">
                        📈✨ ¿Necesitas un mayor volumen de consultas?
                    </h1>
                    <p class="text-center">
                        No hay problema, contamos con planes corporativos de más de 100.000 consultas a precios altamente <br> competitivos. ¡Impulsa tu negocio con nuestra oferta excepcional! 💼🌟
                    </p>
                    <div class="flex justify-center py-3">
                        <button class="bg-gray-700 text-white px-3 py-2 rounded ml-4 font-bold text-[0.7rem] self-center">
                            CONTÁCTANOS
                        </button>
                    </div>
                    <div class="flex grid grid-cols-3 gap-0 max-w-4xl py-6 items-center justify-center">
                        <!-- Columna 1 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-auto text-center">
                            <!-- Contenido de la columna 1 -->
                            <h1 class="text-center pt-3 text-[2rem] font-semibold" >+2'700.000</h1>
                            <p class="text-[0.8rem] text-gray-500">reportes entregados</p>
                        </div>

                        <!-- Columna 2 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg  border-r-2 border-gray h-auto text-center">
                            <!-- Contenido de la columna 2 -->
                            <h1 class="text-center pt-3 text-[2rem] font-semibold">+5'500.000</h1>
                            <p class="text-[0.8rem] text-gray-500">horas ahorradas</p>
                        </div>

                        <!-- Columna 3 -->
                        <div class="col-span-1 p-4 bg-white shadow-lg border-r-2 border-gray h-auto text-center">
                            <!-- Contenido de la columna 3 -->
                            <h1 class="text-center pt-3 text-[2rem] font-semibold">+4190</h1>
                            <p class="text-[0.8rem] text-gray-500">usuarios felices</p>
                            
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
        
        <div class="p-4 py-9">
            <div class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 px-2 rounded-md mb-2 text-center max-w-5xl w-1/4">
                Los mejores del mercado
            </div>

            <h2 class="text-2xl font-semibold py-4">¿Por qué elegir a Tusdatos.co?</h2>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-5 max-w-4xl">
                <div class="space-y-4">
                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                        <h1 class="text-[1.2rem] font-semibold">Toma de decisiones y debidas diligencias</h1>
                        <p class="text-[0.9rem] py-5 text-justify">
                            Ayudamos a la toma de decisiones con base en el perfil de riesgo de las personas y empresas según sus datos públicos, socio económicos y legales. Los procesos de AML (Anti Money laundering) y KYC (Know your customer) son vitales para todas las empresas.
                        </p>
                    </div>
                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                        <h1 class="text-[1.2rem] font-semibold">Mejora de procesos</h1>
                        <p class="text-[0.9rem] py-5 text-justify">
                            Mejoramos la efectividad en los procesos de selección, contratación y validación de terceros mediante un reporte íntegro y comprensivo. Para que puedas saber de forma inmediata si la persona o empresa tiene algún tipo de hallazgo que no te permita establecer una relación. ¡Un estudio de seguridad completo!
                        </p>
                    </div>
                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                        <h1 class="text-[1.2rem] font-semibold">
                            Tiempo real
                        </h1>
                    <p class="text-[0.9rem] py-5 text-justify">
                        Consultas en tiempo real directamente sobre sobre las fuentes. No usamos bases de datos precargadas, solo información al día. Vamos directamente a las fuentes en el momento que solicitas la consulta
                    </p>
                    </div>
                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                        <h1 class="text-[1.2rem] font-semibold">
                         Facilidad de uso
                        </h1>
                        <p class="text-[0.9rem] py-5 text-justify">
                            Las consultas se realizan en un solo clic, tambien es posible realizar cientos de consultas paralelas y en pocos minutos. La plataforma esta desarrollada para ser muy intuitiva y de fácil uso. Te acompañamos en tus procesos.
                        </p>
                    </div>
                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                        <h1 class="text-[1.2rem] font-semibold">
                         Planes a la medida
                        </h1>
                        <p class="text-[0.9rem] py-5 text-justify">
                            Contamos con planes para cumplir con cualquier necesidad, sin importa el tamaño de la empresa (PYMES hasta grandes empresas y corporaciones). El alcance de las consultas y los hallazgos se pueden configurar según el sector y la necesidad.
                        </p>
                    </div>
            
                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                    <h1 class="text-[1.2rem] font-semibold">
                        Evita riesgos y reduce el fraude
                    </h1>
                    <p class="text-[0.9rem] py-5 text-justify">
                        Entregamos el panorama de riesgo completo, no solo una alerta. Ingresas el número del documento y te entregamos un reporte de más de 20 páginas con todos los antecedentes. Evita la incertidumbre, cumplimos con los requisitos más estrictos de ley para la validación de terceros y cumplimiento de regulaciones de lavado de activos. No son listas, es cumplimiento 360.
                    </p>
                    </div>

                    <div class="p-4 w-96 h-auto bg-transparent border border-gay-700 rounded-md">
                    <h1 class="text-[1.2rem] font-semibold">
                        Vencimiento amigable
                    </h1>
                    <p class="text-[0.9rem] py-5 text-justify">
                        Tienes hasta 24 meses para consumir el paquete adquirido. El costo por validación siempre va a ser claro y no hay cargos escondidos. Lo mejor de todo, te cobramos en tu moneda local.
                    </p>
                    </div>
                    <button class="uppercase bg-gray-700 text-white px-4 py-3 mt-4 rounded text-[0.7rem] font-bold w-1/2">
                        ¡solicita una demo hoy!
                    </button>
                </div>

                <div class="w-80 px-6 h-96 bg-transparent">
                    <img src="@/assets/phone.png" alt="">
                </div>
            </div>
        </div>
        
        <div class="flex justify-center items-center content-center p-9 gap-x-40">
            <div class="rounded-full bg-gray-500 w-[30rem] h-[30rem] flex flex-col items-center place-content-center">
                <img src="@/assets/spreciado.jpeg" alt="Santiago_Preciado" class="w-16 h-16 rounded-full mt-4">
                <div class="w-3/4 py-7">
                    <p class="text-white text-center text-[0.8rem]">“Tusdatos.co  ha sido una herramienta de grandiosa ayuda para los procesos de pre-contratación de los que participo. Es una plataforma que te permite en tiempo real referenciar a tus candidatos, clientes y proveedores para así concretar relaciones laborales y comerciales basadas en una total confianza. De igual manera, el equipo ha aportado para que la organización multinacional para la que trabajo realice una automatización y digitalización de su procesos, lo que en nuestro contexto actual ha resultado ser lo más acertado”</p>
                </div>
                <button class="bg-gray-700 text-white px-4 py-2 mt-2 rounded-full text-[0.6rem] font-semibold ">SANTIAGO PRECIADO</button>
                <button class="bg-gray-700 text-white px-4 py-2 mt-2 rounded-full text-[0.6rem] font-semibold">ESPECIALISTA BIENESTAR SOCIAL EMPRESARIAL</button>
            </div>

            <div class="flex text-center justify-center">
            
                <div class="text-center">
                    <div class="mb-4">
                    <p class="bg-gray-600 bg-opacity-50 text-white font-bold uppercase text-[0.65rem] py-1 rounded-md w-[6rem]">testimonios</p>
                    <p class="text-sm text-gray-700 text-[1.6rem] font-bold py-5">+1050 clientes felices</p>
                    </div>
                </div>
                    
            </div>
        </div>

        <div class="bg-gray-600 text-white text-base py-5 flex items-center justify-center w-full">

            <div class="inline-block text-center font-bold">
                <h3>🚀 Reduce hasta en un 80% el tiempo y costo en tus procesos de validación, optimizando recursos y mejorando la eficiencia de tu negocio. 💼⏱️💰</h3>
            </div>

            <button class="bg-white text-gray-800 px-4 py-0.5 rounded ml-4 font-bold text-[0.7rem]">CONTÁCTANOS</button>

        </div>
        <div class="text-center p-4">

            <h1 class="text-2xl font-semibold py-1">Somos expertos en cumplimiento</h1>
            <p class="text-gray-500 text-center py-4 text-[0.8rem]">
                Te mantenemos actualizado con las últimas tendencias y novedades en gestión de <br> riesgos, prevención del lavado de activos y financiación del terrorismo, así como en la <br> lucha contra la proliferación de armas de destrucción masiva. Estamos aquí para <br> asegurarnos de que siempre estés un paso adelante en el cumplimiento normativo.
            </p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-8">
       
            <div class="text-center w-64 py-6">
                <img src="imagen1.jpg" alt="Imagen 1" class="w-32 h-32 mx-auto rounded-full">
                <p class="text-gray-500 mt-2 uppercase text-[0.7rem]">Cumplimiento</p>
                <h2 class="text-xl font-semibold mt-2">Evolución normativa <br>frente al LA/FT/FPADM</h2>
                <p class="text-gray-500 text-[0.8rem] text-justify py-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore quam molestias incidunt autem, enim voluptatum numquam voluptas impedit rem! Quis accusamus  delectus consectetur distinctio, officiis magni labore vero iure quasi.</p>
                <p class="text-sm text-gray-500 mt-2 text-[0.57rem]">Oct 4, 2022 by</p>
            </div>

            <!-- Columna 2 -->
            <div class="text-center w-64 py-6">
                <img src="imagen2.jpg" alt="Imagen 2" class="w-32 h-32 mx-auto rounded-full">
                <p class="text-gray-500 mt-2 uppercase text-[0.7rem]">Cumplimiento</p>
                <h2 class="text-xl font-semibold mt-2">¿Qué es el Siplaft y quiénes deben implementarlo?</h2>
                <p class="text-gray-500 text-[0.8rem] text-justify py-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ab quo, sit at magnam sint minus animi voluptate sed, qui aliquam nostrum! Cupiditate quibusdam quisquam nobis vero quos labore dolore ipsam?</p>
                <p class="text-sm text-gray-500 mt-2 text-[0.57rem]">Sep 22, 2022 by Lina Rocha</p>
            </div>

            <!-- Columna 3 -->
            <div class="text-center w-64 py-6">
                <img src="imagen3.jpg" alt="Imagen 3" class="w-32 h-32 mx-auto rounded-full">
                <p class="text-gray-500 mt-2 uppercase text-[0.7rem]">Cumplimiento</p>
                <h2 class="text-xl font-semibold mt-2">World Compliance Forum 2022</h2>
                <p class="text-gray-500 text-[0.8rem] text-justify py-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, ea? Omnis velit hic quisquam beatae reiciendis nisi cupiditate quae quos praesentium, nemo quod quaerat possimus recusandae. Natus ab similique eius?</p>
                <p class="text-sm text-gray-500 mt-2 text-[0.57rem]">Jun 30, 2022 by Diego Gonzales</p>
            </div>
            </div>
        </div>
        <div class="container mx-auto p-8">
        <div class="flex flex-col md:flex-row md:space-x-16 justify-center">
            <!-- Columna Izquierda -->
            <div class="w-full md:w-1/4 text-center">
                <h2 class="text-2xl font-semibold mb-4">Preguntas Frecuentes</h2>
                <p class="text-gray-500 text-sm">¿Tienes más dudas? Comunícate con nosotros
                </p>
            </div>

            <div class="w-full md:w-1/2 space-y-4">
                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿Qué es Tusdatos.co?</h3>
                        <p class="text-sm py-6 text-gray-600">Tusdatos.co ofrece validación de antecedentes,  conocimiento de terceros y validación de identidad sobre personas, empresas y vehículos en un clic y en menos de un minuto. Ayudamos a reducir los riesgos y el fraude en procesos de selección, contratación y cumplimiento, así como a volver las empresas más eficientes pasando los procesos de validación de días a segundos. Lo anterior, a través de la automatización de las consultas sobre las fuentes principales nacionales e internaciones de antecedentes, seguridad social, asociaciones profesionales, listas restrictivas y vinculantes, PEPS, y muchas muchas más. Cada consulta es realizada en tiempo real sobre las fuentes dejando las evidencias de los diferentes certificados de consulta con fecha y hora.</p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿Para qué puedo usar Tusdatos.co?</h3>
                        <p class="text-sm py-6 text-gray-600">Nuestro servicio lo puedes utilizar para: cumplimiento de normativas de lavado de activos y financiación de terrorismo (Sarlaft), cumplimiento normativa BASC, cumplimiento OEA, onboarding de usuarios, o simplemente para reducir los riesgos y el fraude en tu trato con terceros.</p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿Sólo se pueden hacer búsquedas de personas naturales?</h3>
                        <p class="text-sm py-6 text-gray-600">No, con Tusdatos.co también puedes hacer búsquedas de personas jurídicas tanto por NIT como por nombre o razón social y de vehículos.</p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿Solo puedo hacer validación de personas con cédula de ciudadanía?</h3>
                        <p class="text-sm py-6 text-gray-600">Las validaciones de personas naturales en Tusdatos.co las puedes realizar con diferentes documentos, como cédula de ciudadanía (CC), cédula de extranjería (CE), permiso de protección temporal (PPT), número de identificación tributario (NIT), pasaporte e incluso nombre.</p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿Puedo validar mis antecedentes o los de un conocido?</h3>
                        <p class="text-sm py-6 text-gray-600">Tusdatos.co es un servicio enfocado a las empresas, sin embargo en caso de que cumplas estrictos requisitos de protección de datos y confirmación de consentimiento de la búsqueda lo podemos realizar.</p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿A quién está dirigido Tusdatos.co?</h3>
                        <p class="text-sm py-6 text-gray-600">Empresas legalmente constituidas en Colombia, las cuales por su objeto, o por la normativa del país, deban realizar la búsqueda de antecedentes o listas restrictivas de sus públicos de relacionamiento, como clientes, proveedores, empleados, entre otros. </p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿Cuentan con planes de más consultas?</h3>
                        <p class="text-sm py-6 text-gray-600">¡Por supuesto! Tenemos paquetes de más 500 mil consultas, contáctanos para obtener más información de ellos.</p>
                    </div>
                </div>

                <div class="flex items-center">
                    <img src="@/assets/quest.svg" alt="Imagen 1" class="w-16 h-16 object-scale-down">
                    <div>
                        <h3 class="text-xl font-semibold">¿El servicio se paga mensualmente?</h3>
                        <p class="text-sm py-6 text-gray-600">No. Si compras un paquete de consultas se realiza un solo cobro. No te cobramos nada adicional al menos que desees hacer una re-compra. Si necesitas un paquete mensual también te lo podemos ofrecer.</p>
                    </div>
                </div>

            </div>
        </div>
    </div>
    </div>

</template>

<style>
    ::placeholder, input{
        font-size: 0.75rem;
    }

</style>