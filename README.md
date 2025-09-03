<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Martín Eduardo Ancamilla Monsalve - Portafolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 40px rgba(0,0,0,0.1); }
        .skill-bar { transition: width 1s ease-in-out; }
        .animate-fade-in { animation: fadeIn 0.6s ease-in; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header/Hero Section -->
    <header class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 text-center">
            <div class="animate-fade-in">
                <div class="w-32 h-32 bg-white rounded-full mx-auto mb-6 flex items-center justify-center shadow-lg">
                    <i class="fas fa-shield-alt text-6xl text-indigo-600"></i>
                </div>
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Martín Eduardo Ancamilla Monsalve</h1>
                <p class="text-xl md:text-2xl mb-6 opacity-90">Especialista en Ciberseguridad & Telecomunicaciones</p>
                <div class="flex flex-wrap justify-center gap-6 text-lg">
                    <div class="flex items-center">
                        <i class="fas fa-phone mr-2"></i>
                        <span>+56 9 8673 3802</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-envelope mr-2"></i>
                        <span>martineduardouch@gmail.com</span>
                    </div>
                    <div class="flex items-center">
                        <i class="fas fa-map-marker-alt mr-2"></i>
                        <span>Temuco, Chile</span>
                    </div>
                </div>
                <div class="mt-6">
                    <a href="https://www.linkedin.com/in/martín-ancamilla-monsalve" target="_blank" 
                       class="inline-flex items-center bg-white text-indigo-600 px-6 py-3 rounded-full font-semibold hover:bg-gray-100 transition-colors">
                        <i class="fab fa-linkedin mr-2"></i>
                        LinkedIn
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Achievement Banner -->
    <section class="bg-yellow-50 border-l-4 border-yellow-400 py-4">
        <div class="container mx-auto px-6">
            <div class="flex items-center justify-center">
                <i class="fas fa-trophy text-yellow-600 text-2xl mr-3"></i>
                <span class="text-lg font-semibold text-gray-800">🏆 3° Lugar Mundial - Huawei ICT Competition (Network Track)</span>
            </div>
        </div>
    </section>

    <div class="container mx-auto px-6 py-12">
        <!-- Perfil Profesional -->
        <section class="mb-16 animate-fade-in">
            <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <i class="fas fa-user-tie text-indigo-600 mr-3"></i>
                    Perfil Profesional
                </h2>
                <p class="text-gray-700 text-lg leading-relaxed">
                    Ingeniero en Telecomunicaciones, Conectividad y Redes con formación sólida en tecnologías Cisco, Huawei y Fortinet. 
                    Destaco por mi desempeño internacional en la competencia Huawei ICT Competition (Top 3 mundial, Network Track), 
                    así como por mi experiencia práctica en configuración de redes empresariales, seguridad de red y servicios sobre Ubuntu Server. 
                    Busco integrarme a un equipo técnico donde pueda aportar conocimientos sólidos y seguir creciendo profesionalmente.
                </p>
            </div>
        </section>

        <!-- Experiencia y Educación -->
        <div class="grid md:grid-cols-2 gap-8 mb-16">
            <!-- Experiencia -->
            <section class="animate-fade-in">
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover h-full">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                        <i class="fas fa-briefcase text-indigo-600 mr-3"></i>
                        Experiencia
                    </h2>
                    <div class="border-l-4 border-indigo-200 pl-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Docente Especialidad Telecomunicaciones</h3>
                        <p class="text-indigo-600 font-medium mb-2">Liceo Politécnico Pueblo Nuevo</p>
                        <p class="text-gray-600 mb-4">2024 – 2025</p>
                        <ul class="text-gray-700 space-y-2">
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mr-2 mt-1"></i>
                                Impartición de contenidos en planta externa, redes, electrónica y servicios en servidores
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mr-2 mt-1"></i>
                                Aplicación de metodologías activas para enseñanza técnica
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mr-2 mt-1"></i>
                                Participación en proyectos formativos interdisciplinarios
                            </li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Educación -->
            <section class="animate-fade-in">
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover h-full">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                        <i class="fas fa-graduation-cap text-indigo-600 mr-3"></i>
                        Educación
                    </h2>
                    <div class="space-y-6">
                        <div class="border-l-4 border-indigo-200 pl-6">
                            <h3 class="text-xl font-semibold text-gray-800 mb-2">Ingeniería en Telecomunicaciones, Conectividad y Redes</h3>
                            <p class="text-indigo-600 font-medium mb-2">INACAP</p>
                            <p class="text-gray-600">2020 – 2024</p>
                        </div>
                        <div class="border-l-4 border-green-200 pl-6">
                            <h3 class="text-xl font-semibold text-gray-800 mb-2">Diplomado en Seguridad de Redes</h3>
                            <p class="text-green-600 font-medium mb-2">Desafío Latam</p>
                            <p class="text-gray-600">2025 – Actualidad</p>
                            <span class="inline-block bg-green-100 text-green-800 text-sm px-3 py-1 rounded-full mt-2">En Curso</span>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <!-- Certificaciones -->
        <section class="mb-16 animate-fade-in">
            <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                    <i class="fas fa-certificate text-indigo-600 mr-3"></i>
                    Certificaciones Técnicas
                </h2>
                <div class="grid md:grid-cols-3 gap-6">
                    <div class="bg-red-50 p-6 rounded-lg border border-red-200">
                        <div class="flex items-center mb-3">
                            <i class="fas fa-network-wired text-red-600 text-2xl mr-3"></i>
                            <h3 class="font-semibold text-gray-800">Huawei HCIA Datacom</h3>
                        </div>
                        <p class="text-gray-600">2023 – 2026</p>
                    </div>
                    <div class="bg-blue-50 p-6 rounded-lg border border-blue-200">
                        <div class="flex items-center mb-3">
                            <i class="fas fa-shield-alt text-blue-600 text-2xl mr-3"></i>
                            <h3 class="font-semibold text-gray-800">Fortinet NSE 1</h3>
                        </div>
                        <p class="text-gray-600">Certificación</p>
                    </div>
                    <div class="bg-green-50 p-6 rounded-lg border border-green-200">
                        <div class="flex items-center mb-3">
                            <i class="fas fa-chart-line text-green-600 text-2xl mr-3"></i>
                            <h3 class="font-semibold text-gray-800">Excel para Negocios</h3>
                        </div>
                        <p class="text-gray-600">Fundamentos</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Competencias Técnicas -->
        <section class="mb-16 animate-fade-in">
            <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                <h2 class="text-3xl font-bold text-gray-800 mb-8 flex items-center">
                    <i class="fas fa-cogs text-indigo-600 mr-3"></i>
                    Competencias Técnicas
                </h2>
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="space-y-6">
                        <div class="bg-gradient-to-r from-blue-50 to-blue-100 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3 flex items-center">
                                <i class="fas fa-network-wired text-blue-600 mr-2"></i>
                                Networking
                            </h3>
                            <ul class="text-gray-700 space-y-1 text-sm">
                                <li>• Ruteo estático y dinámico (OSPF multiarea, BGP)</li>
                                <li>• Configuración de redes VLSM</li>
                                <li>• Diseño de redes multisucursal, STP y QoS</li>
                            </ul>
                        </div>
                        <div class="bg-gradient-to-r from-red-50 to-red-100 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3 flex items-center">
                                <i class="fas fa-shield-alt text-red-600 mr-2"></i>
                                Seguridad
                            </h3>
                            <ul class="text-gray-700 space-y-1 text-sm">
                                <li>• Configuración de Firewall (Fortinet)</li>
                                <li>• Zonas DMZ, Trust/Untrust</li>
                                <li>• Análisis y mitigación de vulnerabilidades</li>
                            </ul>
                        </div>
                        <div class="bg-gradient-to-r from-purple-50 to-purple-100 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3 flex items-center">
                                <i class="fas fa-wifi text-purple-600 mr-2"></i>
                                Wireless LAN
                            </h3>
                            <ul class="text-gray-700 space-y-1 text-sm">
                                <li>• CAPWAP</li>
                                <li>• VLANs y VAPs</li>
                            </ul>
                        </div>
                    </div>
                    <div class="space-y-6">
                        <div class="bg-gradient-to-r from-green-50 to-green-100 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3 flex items-center">
                                <i class="fas fa-server text-green-600 mr-2"></i>
                                Servidores
                            </h3>
                            <ul class="text-gray-700 space-y-1 text-sm">
                                <li>• Ubuntu Server (Apache, DNS, DHCP)</li>
                                <li>• Instalación y configuración de servicios</li>
                            </ul>
                        </div>
                        <div class="bg-gradient-to-r from-yellow-50 to-yellow-100 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3 flex items-center">
                                <i class="fas fa-phone text-yellow-600 mr-2"></i>
                                Telefonía IP
                            </h3>
                            <ul class="text-gray-700 space-y-1 text-sm">
                                <li>• Protocolos SIP y H.323</li>
                                <li>• Issabel 7, anexos Zoiper y Grandstream</li>
                            </ul>
                        </div>
                        <div class="bg-gradient-to-r from-indigo-50 to-indigo-100 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3 flex items-center">
                                <i class="fas fa-microchip text-indigo-600 mr-2"></i>
                                Otros
                            </h3>
                            <ul class="text-gray-700 space-y-1 text-sm">
                                <li>• Fusión de fibra óptica, ADSL y FTTH</li>
                                <li>• Prototipado con Arduino R3</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Habilidades Blandas e Idiomas -->
        <div class="grid md:grid-cols-2 gap-8 mb-16">
            <section class="animate-fade-in">
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover h-full">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                        <i class="fas fa-users text-indigo-600 mr-3"></i>
                        Habilidades Blandas
                    </h2>
                    <div class="space-y-4">
                        <div class="flex items-center p-3 bg-gray-50 rounded-lg">
                            <i class="fas fa-comments text-blue-500 mr-3"></i>
                            <span class="text-gray-700">Comunicación efectiva en entornos TI</span>
                        </div>
                        <div class="flex items-center p-3 bg-gray-50 rounded-lg">
                            <i class="fas fa-handshake text-green-500 mr-3"></i>
                            <span class="text-gray-700">Trabajo colaborativo en equipos técnicos</span>
                        </div>
                        <div class="flex items-center p-3 bg-gray-50 rounded-lg">
                            <i class="fas fa-file-alt text-purple-500 mr-3"></i>
                            <span class="text-gray-700">Elaboración de reportes técnicos en ciberseguridad</span>
                        </div>
                        <div class="flex items-center p-3 bg-gray-50 rounded-lg">
                            <i class="fas fa-search text-red-500 mr-3"></i>
                            <span class="text-gray-700">Análisis y mitigación de vulnerabilidades</span>
                        </div>
                    </div>
                </div>
            </section>

            <section class="animate-fade-in">
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover h-full">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6 flex items-center">
                        <i class="fas fa-globe text-indigo-600 mr-3"></i>
                        Idiomas
                    </h2>
                    <div class="space-y-6">
                        <div>
                            <div class="flex justify-between items-center mb-2">
                                <span class="font-semibold text-gray-800">Español</span>
                                <span class="text-sm text-gray-600">Nativo</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-3">
                                <div class="bg-green-500 h-3 rounded-full skill-bar" style="width: 100%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between items-center mb-2">
                                <span class="font-semibold text-gray-800">Inglés</span>
                                <span class="text-sm text-gray-600">Intermedio (B1)</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-3">
                                <div class="bg-blue-500 h-3 rounded-full skill-bar" style="width: 70%"></div>
                            </div>
                            <p class="text-sm text-gray-600 mt-1">Oxford Online Placement Test</p>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </div>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p class="text-lg mb-4">¿Interesado en colaborar? ¡Conectemos!</p>
            <div class="flex justify-center space-x-6">
                <a href="mailto:martineduardouch@gmail.com" class="hover:text-yellow-300 transition-colors">
                    <i class="fas fa-envelope text-2xl"></i>
                </a>
                <a href="https://www.linkedin.com/in/martín-ancamilla-monsalve" target="_blank" class="hover:text-yellow-300 transition-colors">
                    <i class="fab fa-linkedin text-2xl"></i>
                </a>
                <a href="tel:+56986733802" class="hover:text-yellow-300 transition-colors">
                    <i class="fas fa-phone text-2xl"></i>
                </a>
            </div>
            <p class="mt-6 text-sm opacity-75">© 2025 Martín Eduardo Ancamilla Monsalve. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script>
        // Animación de entrada suave
        window.addEventListener('load', function() {
            const elements = document.querySelectorAll('.animate-fade-in');
            elements.forEach((el, index) => {
                setTimeout(() => {
                    el.style.opacity = '1';
                    el.style.transform = 'translateY(0)';
                }, index * 200);
            });
        });

        // Efecto de hover en las tarjetas
        document.querySelectorAll('.card-hover').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-5px)';
                this.style.boxShadow = '0 20px 40px rgba(0,0,0,0.1)';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0)';
                this.style.boxShadow = '0 4px 6px rgba(0,0,0,0.1)';
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97916a087621deab',t:'MTc1Njg2MjMxNy4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
