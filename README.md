<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Una pregunta importante | Propuesta de relación</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700&family=Playfair+Display:wght@400;700&display=swap');
        
        :root {
            --primary: #6d28d9;
            --secondary: #f9a8d4;
            --dark: #1e293b;
            --light: #f8fafc;
        }
        
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
        }
        
        .heading {
            font-family: 'Playfair Display', serif;
        }
        
        .heart-animate {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        
        .world-icon {
            animation: rotate 20s linear infinite;
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .message-box {
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .message-box:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="min-h-screen bg-gradient-to-b from-purple-50 to-pink-50">
    <header class="relative overflow-hidden">
        <div class="absolute inset-0 bg-black opacity-40"></div>
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/a420441a-a17d-4260-a00b-4f6072473e79.png" alt="Atardecer en dos ciudades diferentes mostrando la distancia pero conectadas digitalmente con iconos de tecnología y corazones" class="w-full h-96 object-cover">
        <div class="absolute inset-0 flex items-center justify-center text-center px-4">
            <div class="max-w-4xl mx-auto">
                <h1 class="heading text-4xl md:text-6xl font-bold text-white mb-4">Tengo una pregunta importante para ti</h1>
                <p class="text-xl text-purple-100 mb-8">Aunque los kilómetros nos separan, nuestros corazones están conectados</p>
                <div class="heart-animate inline-block">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-red-500" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z" clip-rule="evenodd" />
                    </svg>
                </div>
            </div>
        </div>
    </header>

    <main class="container mx-auto px-4 py-16 max-w-5xl">
        <section class="mb-20">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-purple-900 mb-4">¿Por qué tomar esta decisión ahora?</h2>
                <div class="w-24 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="message-box bg-white p-8 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-100 p-3 rounded-full mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z" />
                            </svg>
                        </div>
                        <h3 class="heading text-xl font-semibold text-gray-800">Conectados digitalmente</h3>
                    </div>
                    <p class="text-gray-600">En esta era digital, la distancia es solo un número. Hemos demostrado que podemos mantener una conexión profunda sin importar la geografía, compartiendo nuestros días a través de pantallas pero con emociones reales.</p>
                </div>
                
                <div class="message-box bg-white p-8 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="bg-pink-100 p-3 rounded-full mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <h3 class="heading text-xl font-semibold text-gray-800">Plan a futuro</h3>
                    </div>
                    <p class="text-gray-600">Esta relación no es solo para hoy, sino con la visión de un mañana donde nuestra distancia se acorte. Tengo planes concretos y metas claras para que, con tiempo y esfuerzo, podamos reducir esa distancia físicamente.</p>
                </div>
                
                <div class="message-box bg-white p-8 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-100 p-3 rounded-full mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
                            </svg>
                        </div>
                        <h3 class="heading text-xl font-semibold text-gray-800">Confianza establecida</h3>
                    </div>
                    <p class="text-gray-600">Hemos construido unos cimientos de confianza, honestidad y comunicación que muchas relaciones cercanas físicamente envidiarían. Estos valores son los pilares que hacen que una relación a distancia funcione.</p>
                </div>
                
                <div class="message-box bg-white p-8 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="bg-pink-100 p-3 rounded-full mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                            </svg>
                        </div>
                        <h3 class="heading text-xl font-semibold text-gray-800">Visitas planificadas</h3>
                    </div>
                    <p class="text-gray-600">Ya estoy trabajando en organizar nuestras primeras visitas. La distancia es temporal, pero lo que sentimos es real y duradero. Cada vez que nos veamos será especial y valiosa.</p>
                </div>
            </div>
        </section>

        <section class="mb-20">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-purple-900 mb-4">Nosotros en algun momento</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Estos son algunas imagenes que demuestran mi amor por ti</p>
                <div class="w-24 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <img src="https://stickerly.pstatic.net/sticker_pack/GKxNn91GyJYvRhMszE6eOQ/E68GYA/21/741203845.png" alt="Descripción de la imagen 1" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <img src="https://stickerly.pstatic.net/sticker_pack/GKxNn91GyJYvRhMszE6eOQ/E68GYA/21/792858465.png" alt="Descripción de la imagen 2" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <img src="https://stickerly.pstatic.net/sticker_pack/GKxNn91GyJYvRhMszE6eOQ/E68GYA/21/1535343679.png" alt="Descripción de la imagen 3" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <img src="https://stickerly.pstatic.net/sticker_pack/GKxNn91GyJYvRhMszE6eOQ/E68GYA/21/763399966.png" alt="Descripción de la imagen 4" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <img src="https://stickerly.pstatic.net/sticker_pack/GKxNn91GyJYvRhMszE6eOQ/E68GYA/21/769829278.png" alt="Descripción de la imagen 5" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <img src="https://stickerly.pstatic.net/sticker_pack/GKxNn91GyJYvRhMszE6eOQ/E68GYA/21/850085151.png" alt="Descripción de la imagen 6" class="w-full h-48 object-cover hover:scale-105 transition duration-500">
                </div>
            </div>
        </section>

        <section class="mb-20 bg-white rounded-xl shadow-lg overflow-hidden">
            <div class="md:flex">
                <div class="md:w-1/2 p-8 md:p-12 bg-gradient-to-br from-purple-500 to-pink-500 text-white">
                    <h2 class="heading text-3xl font-bold mb-6">La pregunta</h2>
                    <div class="world-icon inline-block mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                        </svg>
                    </div>
                    <p class="text-xl mb-6">Aunque no estemos en el mismo lugar físico, he llegado a conocerte de una manera profunda y genuina. Nuestras conversaciones, nuestra conexión y lo que siento por ti son reales aunque no podamos tocarnos.</p>
                    <p class="text-xl font-medium">¿Aceptarías ser mi novia oficial, para construir algo serio y real a pesar de la distancia?</p>
                </div>
                <div class="md:w-1/2 p-8 md:p-12">
                    <h3 class="heading text-2xl font-semibold text-gray-800 mb-6">Tu respuesta</h3>
                    <form id="responseForm" class="space-y-6">
                        <div class="space-y-4">
                            <label class="flex items-center space-x-3 cursor-pointer">
                                <input type="radio" name="response" value="yes" class="h-6 w-6 text-purple-600 focus:ring-purple-500" checked>
                                <span class="text-gray-700">Sí, acepto ser tu novia y construir esto juntos</span>
                            </label>
                            <label class="flex items-center space-x-3 cursor-pointer">
                                <input type="radio" name="response" value="think" class="h-6 w-6 text-purple-600 focus:ring-purple-500">
                                <span class="text-gray-700">Necesito un poco más de tiempo para pensarlo</span>
                            </label>
                            <label class="flex items-center space-x-3 cursor-pointer">
                                <input type="radio" name="response" value="talk" class="h-6 w-6 text-purple-600 focus:ring-purple-500">
                                <span class="text-gray-700">Quiero hablar más sobre esto primero</span>
                            </label>
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Mensaje para mí (opcional)</label>
                            <textarea id="message" rows="3" class="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-purple-500 focus:border-purple-500" placeholder="Escribe lo que sientes..."></textarea>
                        </div>
                        <button type="submit" class="w-full flex justify-center py-3 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-purple-600 hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-purple-500 transition duration-200">
                            Enviar respuesta
                        </button>
                    </form>
                    <div id="thankYouMessage" class="hidden mt-6 p-4 bg-purple-50 rounded-lg text-purple-800">
                        <p class="font-medium">¡Gracias por tu respuesta! Significa mucho para mí. Hablaré contigo pronto sobre esto.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gradient-to-r from-purple-900 to-purple-700 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="text-center">
                <h3 class="heading text-2xl font-bold mb-4">Para mi persona especial</h3>
                <p class="max-w-2xl mx-auto mb-6">No importa la distancia cuando dos personas realmente se quieren. Esta es solo una parte de nuestro viaje juntos.</p>
                <div class="flex justify-center space-x-4">
                </div>
            </div>
        </div>
    </footer>

    <script>
        document.getElementById('responseForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Simular envío de formulario
            const selectedResponse = document.querySelector('input[name="response"]:checked').value;
            const message = document.getElementById('message').value;
            
            // Mostrar mensaje de agradecimiento
            document.getElementById('thankYouMessage').classList.remove('hidden');
            document.getElementById('responseForm').reset();
            
            // Scroll suave a mensaje
            setTimeout(() => {
                document.getElementById('thankYouMessage').scrollIntoView({ behavior: 'smooth' });
            }, 300);
            
            // Aquí normalmente enviarías los datos a un servidor
            console.log('Respuesta seleccionada:', selectedResponse);
            console.log('Mensaje adicional:', message);
        });
    </script>
</body>
</html>
