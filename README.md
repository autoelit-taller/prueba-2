# prueba-2
ahora agrega esto solo para el dominio y liga el siguiente numero como numero de taller +528115774422
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cotizador Rápido | Servicio Automotriz AutoElit</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#0f172a',
                            card: '#1e293b',
                            accent: '#3b82f6',
                            hover: '#2563eb'
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-950 text-slate-100 font-sans min-h-screen flex flex-col justify-between">

    <!-- Header / Navbar -->
    <header class="bg-brand-dark border-b border-slate-800 py-4 px-6 shadow-md">
        <div class="max-w-6xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
            <div class="flex items-center space-x-3">
                <div class="bg-brand-accent p-2 rounded-xl text-white font-bold text-xl tracking-wider">
                    AE
                </div>
                <div>
                    <h1 class="text-xl font-bold tracking-tight">Servicio Automotriz AutoElit</h1>
                    <p class="text-xs text-slate-400">autoelit.com — Cotizador Automático de Servicios</p>
                </div>
            </div>
            <div class="text-xs sm:text-sm bg-slate-900 border border-slate-700 px-3 py-1.5 rounded-full text-slate-300">
                🟢 Atención inmediata en mostrador y WhatsApp
            </div>
        </div>
    </header>

    <!-- Main Container -->
    <main class="max-w-6xl mx-auto px-4 py-8 w-full grid grid-cols-1 lg:grid-cols-3 gap-8">
        
        <!-- Columna Izquierda / Servicios (2 Spans) -->
        <div class="lg:col-span-2 space-y-6">
            <div class="bg-brand-card border border-slate-800 rounded-2xl p-6 shadow-xl">
                <h2 class="text-lg font-semibold text-brand-accent mb-4 flex items-center gap-2">
                    <span>1.</span> Selecciona los servicios requeridos
                </h2>
                
                <!-- Lista de Servicios Comunes -->
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4" id="services-container">
                    
                    <!-- Item 1 -->
                    <label class="service-card border border-slate-700 bg-slate-900/50 hover:border-brand-accent p-4 rounded-xl cursor-pointer transition flex items-start gap-3">
                        <input type="checkbox" name="service" value="Afinación Mayor / Menor" data-price="1200" class="mt-1 h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <div class="flex-1">
                            <span class="block font-medium text-sm">Afinación (Aceite, Bujías, Filtros)</span>
                            <span class="text-xs text-slate-400">Estimado: $1,200 MXN</span>
                        </div>
                    </label>

                    <!-- Item 2 -->
                    <label class="service-card border border-slate-700 bg-slate-900/50 hover:border-brand-accent p-4 rounded-xl cursor-pointer transition flex items-start gap-3">
                        <input type="checkbox" name="service" value="Cambio de Balatas (Frenos)" data-price="950" class="mt-1 h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <div class="flex-1">
                            <span class="block font-medium text-sm">Cambio de Balatas de Freno</span>
                            <span class="text-xs text-slate-400">Estimado: $950 MXN (Por eje)</span>
                        </div>
                    </label>

                    <!-- Item 3 -->
                    <label class="service-card border border-slate-700 bg-slate-900/50 hover:border-brand-accent p-4 rounded-xl cursor-pointer transition flex items-start gap-3">
                        <input type="checkbox" name="service" value="Diagnóstico Computarizado (Escáner)" data-price="500" class="mt-1 h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <div class="flex-1">
                            <span class="block font-medium text-sm">Diagnóstico Computarizado / Escáner</span>
                            <span class="text-xs text-slate-400">Estimado: $500 MXN</span>
                        </div>
                    </label>

                    <!-- Item 4 -->
                    <label class="service-card border border-slate-700 bg-slate-900/50 hover:border-brand-accent p-4 rounded-xl cursor-pointer transition flex items-start gap-3">
                        <input type="checkbox" name="service" value="Servicio de Suspensión y Amortiguadores" data-price="1500" class="mt-1 h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <div class="flex-1">
                            <span class="block font-medium text-sm">Suspensión y Amortiguadores</span>
                            <span class="text-xs text-slate-400">Mano de obra desde: $1,500 MXN</span>
                        </div>
                    </label>

                    <!-- Item 5 -->
                    <label class="service-card border border-slate-700 bg-slate-900/50 hover:border-brand-accent p-4 rounded-xl cursor-pointer transition flex items-start gap-3">
                        <input type="checkbox" name="service" value="Rotación, Alineación y Balanceo" data-price="450" class="mt-1 h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <div class="flex-1">
                            <span class="block font-medium text-sm">Alineación y Balanceo</span>
                            <span class="text-xs text-slate-400">Estimado: $450 MXN</span>
                        </div>
                    </label>

                    <!-- Item 6 -->
                    <label class="service-card border border-slate-700 bg-slate-900/50 hover:border-brand-accent p-4 rounded-xl cursor-pointer transition flex items-start gap-3">
                        <input type="checkbox" name="service" value="Cambio de Kit de Embrague / Clutch" data-price="2200" class="mt-1 h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <div class="flex-1">
                            <span class="block font-medium text-sm">Cambio de Kit de Embrague / Clutch</span>
                            <span class="text-xs text-slate-400">Mano de obra desde: $2,200 MXN</span>
                        </div>
                    </label>

                </div>

                <!-- Sección Dinámica: Otro / Falla Compleja -->
                <div class="mt-6 border-t border-slate-800 pt-4">
                    <label class="flex items-center gap-2 cursor-pointer mb-3">
                        <input type="checkbox" id="toggle-other" class="h-4 w-4 text-brand-accent focus:ring-brand-accent rounded border-slate-700 bg-slate-800">
                        <span class="font-medium text-sm text-slate-200">¿Otro servicio o falla compleja no listada? Especificar</span>
                    </label>
                    <div id="other-section" class="hidden space-y-3 bg-slate-900/80 p-4 rounded-xl border border-slate-700">
                        <div>
                            <label class="block text-xs text-slate-400 mb-1">Describe la falla o requerimiento específico:</label>
                            <textarea id="other-description" rows="2" placeholder="Ej. El motor vibra al acelerar en tercera velocidad..." class="w-full bg-slate-950 border border-slate-700 rounded-lg p-2.5 text-sm text-slate-100 focus:outline-none focus:border-brand-accent"></textarea>
                        </div>
                        <div>
                            <label class="block text-xs text-slate-400 mb-1">Tipo de Motor / Configuración (Opcional):</label>
                            <select id="engine-type" class="w-full bg-slate-950 border border-slate-700 rounded-lg p-2.5 text-sm text-slate-100 focus:outline-none focus:border-brand-accent">
                                <option value="">Selecciona tipo de motor...</option>
                                <option value="4 Cilindros">4 Cilindros</option>
                                <option value="6 Cilindros">6 Cilindros</option>
                                <option value="8 Cilindros (V8)">8 Cilindros (V8)</option>
                                <option value="Diesel">Diésel</option>
                                <option value="Desconocido">No lo sé / Otro</option>
                            </select>
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <!-- Columna Derecha / Resumen y Cotización (1 Span) -->
        <div class="space-y-6">
            <div class="bg-brand-card border border-slate-800 rounded-2xl p-6 shadow-xl sticky top-6">
                <h2 class="text-lg font-semibold text-brand-accent mb-4">
                    2. Resumen de Cotización
                </h2>

                <!-- Datos del Vehículo y Cliente -->
                <div class="space-y-3 mb-6">
                    <div>
                        <label class="block text-xs text-slate-400 mb-1">Nombre del Cliente *</label>
                        <input type="text" id="client-name" placeholder="Ej. Carlos Garza" class="w-full bg-slate-950 border border-slate-700 rounded-lg p-2.5 text-sm text-slate-100 focus:outline-none focus:border-brand-accent">
                    </div>
                    <div>
                        <label class="block text-xs text-slate-400 mb-1">Teléfono / WhatsApp *</label>
                        <input type="tel" id="client-phone" placeholder="Ej. 81 0000 0000" class="w-full bg-slate-950 border border-slate-700 rounded-lg p-2.5 text-sm text-slate-100 focus:outline-none focus:border-brand-accent">
                    </div>
                    <div>
                        <label class="block text-xs text-slate-400 mb-1">Vehículo (Marca, Modelo y Año) *</label>
                        <input type="text" id="car-model" placeholder="Ej. Nissan Versa 2021" class="w-full bg-slate-950 border border-slate-700 rounded-lg p-2.5 text-sm text-slate-100 focus:outline-none focus:border-brand-accent">
                    </div>
                </div>

                <!-- Desglose de Precios -->
                <div class="border-t border-slate-800 pt-4 mb-6 space-y-2">
                    <div class="flex justify-between text-sm text-slate-300">
                        <span>Servicios seleccionados:</span>
                        <span id="summary-count">0 items</span>
                    </div>
                    <div class="flex justify-between text-lg font-bold text-white pt-2 border-t border-slate-800">
                        <span>Total Estimado:</span>
                        <span id="total-price" class="text-brand-accent">$0 MXN</span>
                    </div>
                    <p class="text-[11px] text-slate-400 italic mt-1">
                        * Nota: El precio final puede variar tras la inspección física y diagnóstico en el taller AutoElit.
                    </p>
                </div>

                <!-- Botón de Envío -->
                <button id="send-whatsapp-btn" class="w-full bg-emerald-600 hover:bg-emerald-500 text-white font-medium py-3 px-4 rounded-xl transition shadow-lg flex items-center justify-center gap-2 cursor-pointer">
                    <span>📲 Enviar Cotización por WhatsApp</span>
                </button>
            </div>
        </div>

    </main>

    <!-- Footer -->
    <footer class="bg-brand-dark border-t border-slate-800 py-4 text-center text-xs text-slate-500 mt-12">
        &copy; 2026 Servicio Automotriz AutoElit (autoelit.com). Todos los derechos reservados.
    </footer>

    <!-- Script de Lógica Interactiva -->
    <script>
        const checkboxes = document.querySelectorAll('input[name="service"]');
        const toggleOther = document.getElementById('toggle-other');
        const otherSection = document.getElementById('other-section');
        const otherDescription = document.getElementById('other-description');
        const engineType = document.getElementById('engine-type');
        
        const summaryCount = document.getElementById('summary-count');
        const totalPrice = document.getElementById('total-price');
        const sendWhatsappBtn = document.getElementById('send-whatsapp-btn');

        // Mostrar u ocultar sección de falla compleja
        toggleOther.addEventListener('change', () => {
            if (toggleOther.checked) {
                otherSection.classList.remove('hidden');
            } else {
                otherSection.classList.add('hidden');
                otherDescription.value = '';
                engineType.value = '';
            }
            calculateTotal();
        });

        // Calcular totales dinámicamente
        function calculateTotal() {
            let total = 0;
            let count = 0;

            checkboxes.forEach(cb => {
                if (cb.checked) {
                    total += parseFloat(cb.dataset.price);
                    count++;
                }
            });

            if (toggleOther.checked) {
                count++; // Contamos el servicio complejo como 1 adicional (sujeto a cotizar)
            }

            summaryCount.textContent = `${count} ${count === 1 ? 'item' : 'items'}`;
            totalPrice.textContent = `$${total.toLocaleString('es-MX')} MXN`;
            if(toggleOther.checked && total === 0) {
                totalPrice.textContent = 'Por Cotizar (Falla Compleja)';
            }
        }

        checkboxes.forEach(cb => cb.addEventListener('change', calculateTotal));

        // Enviar a WhatsApp
        sendWhatsappBtn.addEventListener('click', () => {
            const clientName = document.getElementById('client-name').value.trim();
            const clientPhone = document.getElementById('client-phone').value.trim();
            const carModel = document.getElementById('car-model').value.trim();

            if (!clientName || !clientPhone || !carModel) {
                alert('Por favor completa tu Nombre, Teléfono y Modelo de Vehículo antes de enviar la cotización.');
                return;
            }

            let selectedServicesText = [];
            let totalCalc = 0;

            checkboxes.forEach(cb => {
                if (cb.checked) {
                    selectedServicesText.push(`- ${cb.value} ($${cb.dataset.price} MXN)`);
                    totalCalc += parseFloat(cb.dataset.price);
                }
            });

            if (toggleOther.checked) {
                const desc = otherDescription.value.trim() || 'No especificado';
                const engine = engineType.value ? `(Motor: ${engineType.value})` : '';
                selectedServicesText.push(`- Falla / Servicio Complejo: ${desc} ${engine}`);
            }

            if (selectedServicesText.length === 0) {
                alert('Por favor selecciona al menos un servicio o describe tu falla en la opción compleja.');
                return;
            }

            // Construir mensaje para WhatsApp
            let message = `*COTIZACIÓN WEB - AUTOELIT*\n\n`;
            message += `👤 *Cliente:* ${clientName}\n`;
            message += `📞 *Teléfono:* ${clientPhone}\n`;
            message += `🚗 *Vehículo:* ${carModel}\n\n`;
            message += `📋 *Servicios solicitados:*\n${selectedServicesText.join('\n')}\n\n`;
            message += `💰 *Total Estimado:* ${totalCalc > 0 ? '$' + totalCalc.toLocaleString('es-MX') + ' MXN' : 'Sujeto a revisión'}\n\n`;
            message += `_Enviado desde autoelit.com_`;

            // Número de WhatsApp del taller (reemplaza por el real)
            const workshopNumber = "528100000000"; 
            const encodedUrl = `https://wa.me/${workshopNumber}?text=${encodeURIComponent(message)}`;

            window.open(encodedUrl, '_blank');
        });
    </script>
</body>
</html>
