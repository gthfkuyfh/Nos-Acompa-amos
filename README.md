<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nos Acompañamos - Inclusión en Salud Mental</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;800&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        /* Simple animation for cards on hover */
        .feature-card:hover {
            transform: translateY(-5px);
            transition: transform 0.3s ease-in-out;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header -->
    <header class="bg-white/80 backdrop-blur-md shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-teal-600">Nos Acompañamos</a>
            <nav class="hidden md:flex space-x-8">
                <a href="#problema" class="text-gray-600 hover:text-teal-600 transition-colors">El Desafío</a>
                <a href="#solucion" class="text-gray-600 hover:text-teal-600 transition-colors">Nuestra Solución</a>
                <a href="#valor" class="text-gray-600 hover:text-teal-600 transition-colors">Valor Agregado</a>
                <a href="#contacto" class="bg-teal-500 text-white px-4 py-2 rounded-full hover:bg-teal-600 transition-colors">Contacto</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-gray-700 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <a href="#problema" class="block py-2 px-6 text-sm text-gray-700 hover:bg-gray-100">El Desafío</a>
            <a href="#solucion" class="block py-2 px-6 text-sm text-gray-700 hover:bg-gray-100">Nuestra Solución</a>
            <a href="#valor" class="block py-2 px-6 text-sm text-gray-700 hover:bg-gray-100">Valor Agregado</a>
            <a href="#contacto" class="block py-2 px-6 text-sm text-gray-700 hover:bg-gray-100">Contacto</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <section class="relative text-center py-20 md:py-32 px-6 bg-white">
            <div class="absolute inset-0 bg-teal-50 opacity-50"></div>
            <div class="container mx-auto relative">
                <h1 class="text-4xl md:text-6xl font-extrabold text-gray-900 leading-tight">
                    Transformando la exclusión <br class="hidden md:block"> en <span class="text-teal-600">participación</span>.
                </h1>
                <p class="mt-6 max-w-2xl mx-auto text-lg text-gray-600">
                    Un espacio para crecer, compartir y volver a sentirse incluido. Creamos un modelo de acompañamiento integral para personas con diagnósticos en salud mental.
                </p>
                <div class="mt-10">
                    <a href="#solucion" class="bg-teal-500 text-white px-8 py-3 rounded-full font-semibold text-lg hover:bg-teal-600 transition-transform transform hover:scale-105">Conoce Nuestra Propuesta</a>
                </div>
            </div>
        </section>

        <!-- Problem Section -->
        <section id="problema" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="text-3xl md:text-4xl font-bold text-gray-900">La Realidad del <span class="text-red-500">Aislamiento</span></h2>
                        <p class="mt-4 text-gray-600">
                            Vimos que muchas personas con diagnósticos psicológicos o psiquiátricos terminan aisladas, sin un lugar donde se sientan parte. A menudo enfrentan barreras como el estigma, el abandono de tratamientos y la sobrecarga familiar.
                        </p>
                        <div class="mt-8 bg-red-50 border-l-4 border-red-500 p-6 rounded-r-lg">
                            <p class="text-xl font-semibold text-red-700">
                                ¿Sabías que más del 60% de las personas con diagnóstico en salud mental no logra integrarse socialmente de forma estable?
                            </p>
                            <p class="mt-2 text-red-600">Nosotros queremos cambiar eso.</p>
                        </div>
                    </div>
                    <div>
                        <img src="https://placehold.co/600x400/f87171/ffffff?text=Comunidad+y+Apoyo" 
                             alt="Imagen conceptual de una persona sintiéndose aislada" 
                             class="rounded-lg shadow-xl"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x400';">
                    </div>
                </div>
            </div>
        </section>

        <!-- Solution Section -->
        <section id="solucion" class="py-16 md:py-24 bg-gray-50">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Un Nuevo Modelo de Inclusión y Bienestar</h2>
                <p class="mt-4 max-w-3xl mx-auto text-gray-600">
                    Nuestra propuesta combina lo mejor del contacto humano y la tecnología para ofrecer un acompañamiento continuo, personalizado y efectivo.
                </p>
                <div class="mt-12 grid md:grid-cols-3 gap-8">
                    <!-- Feature 1 -->
                    <div class="bg-white p-8 rounded-lg shadow-md feature-card">
                        <div class="bg-teal-100 text-teal-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto">
                           <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
                        </div>
                        <h3 class="mt-6 text-xl font-bold">Espacio Terapéutico Presencial</h3>
                        <p class="mt-2 text-gray-600">Un lugar seguro para socializar, realizar actividades y crecer junto a un equipo interdisciplinario.</p>
                    </div>
                    <!-- Feature 2 -->
                    <div class="bg-white p-8 rounded-lg shadow-md feature-card">
                        <div class="bg-teal-100 text-teal-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z" /></svg>
                        </div>
                        <h3 class="mt-6 text-xl font-bold">Aplicación Digital</h3>
                        <p class="mt-2 text-gray-600">Una herramienta para que los participantes y sus familias sigan el progreso y el acompañamiento desde casa.</p>
                    </div>
                    <!-- Feature 3 -->
                    <div class="bg-white p-8 rounded-lg shadow-md feature-card">
                        <div class="bg-teal-100 text-teal-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                        </div>
                        <h3 class="mt-6 text-xl font-bold">Actividades Recreativas</h3>
                        <p class="mt-2 text-gray-600">Fomentamos la integración y el desarrollo de habilidades con actividades grupales y personalizadas.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Value Proposition Section -->
        <section id="valor" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Más que un Tratamiento, <span class="text-teal-600">una Comunidad</span></h2>
                    <p class="mt-4 max-w-3xl mx-auto text-gray-600">
                        Cubrimos un vacío real en la oferta de servicios actual con un enfoque que genera confianza y resultados.
                    </p>
                </div>
                <div class="mt-12 max-w-4xl mx-auto grid md:grid-cols-2 gap-x-10 gap-y-8">
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-green-100 text-green-600 rounded-full h-10 w-10 flex items-center justify-center">✓</div>
                        <div>
                            <h4 class="font-semibold">Enfoque Integral</h4>
                            <p class="text-gray-600 text-sm">Abordamos terapia, desarrollo de habilidades e integración social.</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-green-100 text-green-600 rounded-full h-10 w-10 flex items-center justify-center">✓</div>
                        <div>
                            <h4 class="font-semibold">Relaciones Cercanas</h4>
                            <p class="text-gray-600 text-sm">Fomentamos la confianza y el compromiso con un trato personalizado.</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-green-100 text-green-600 rounded-full h-10 w-10 flex items-center justify-center">✓</div>
                        <div>
                            <h4 class="font-semibold">Segmento Específico</h4>
                            <p class="text-gray-600 text-sm">Nos centramos en un grupo que no dispone de un acompañamiento adecuado.</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-green-100 text-green-600 rounded-full h-10 w-10 flex items-center justify-center">✓</div>
                        <div>
                            <h4 class="font-semibold">Alto Impacto Social</h4>
                            <p class="text-gray-600 text-sm">Nuestro modelo es una propuesta viable, necesaria y validada.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Call to Action Section -->
        <section id="contacto" class="py-16 md:py-24 bg-teal-600">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold text-white">Súmate al Cambio</h2>
                <p class="mt-4 max-w-2xl mx-auto text-teal-100">
                    Si representas a una institución médica, obra social o quieres saber más sobre nuestro proyecto, nos encantaría conversar contigo.
                </p>
                <div class="mt-8">
                    <a href="https://wa.me/5492626550151" 
                       target="_blank" 
                       rel="noopener noreferrer"
                       class="inline-flex items-center justify-center bg-white text-teal-600 px-8 py-3 rounded-full font-semibold text-lg hover:bg-gray-100 transition-transform transform hover:scale-105">
                        <svg class="w-6 h-6 mr-3" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52s-.67-.816-.916-1.123c-.244-.306-.487-.262-.67-.268-.182-.006-.381-.012-.58-.012-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871-.118.571-.355 1.758-2.182 2.106-2.87.347-.688.347-1.274.247-1.422zM12 2.04c-5.523 0-10 4.477-10 10s4.477 10 10 10 10-4.477 10-10-4.477-10-10-10zM12 20.18c-4.498 0-8.14-3.642-8.14-8.14s3.642-8.14 8.14-8.14 8.14 3.642 8.14 8.14-3.642 8.14-8.14 8.14z"></path></svg>
                        Contáctanos por WhatsApp
                    </a>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-10 text-center">
            <div>
                <h3 class="text-xl font-bold text-white">Nos Acompañamos</h3>
                <p class="mt-2 text-gray-400 text-sm">Un proyecto de Julieta Alaniz, Eliana Lombardi y Martina Salinas.</p>
                <p class="mt-1 text-gray-400 text-sm">Una iniciativa en el marco del Instituto Tecnológico Universitario - Universidad Nacional de Cuyo.</p>
            </div>
            <div class="mt-8 border-t border-gray-700 pt-6 text-center text-sm text-gray-500">
                <p>&copy; 2024 Nos Acompañamos. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
    
    <script>
        // Script for mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
