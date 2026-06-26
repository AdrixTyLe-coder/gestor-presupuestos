# 🛠️ Generador de Presupuestos Inteligente para Autónomos

Una aplicación web móvil-friendly, minimalista y auto-contenida diseñada específicamente para optimizar el flujo de trabajo de profesionales independientes en el sector de la construcción y reformas. 
Permite transformar estimaciones lógicas rápidas en documentos PDF corporativos de alta fidelidad listos para enviar al cliente a pie de obra.

---

## 🎯 Problema Real y Solución Ejecutada

Muchos autónomos pierden horas redactando presupuestos en hojas de cálculo complejas o enviando mensajes informales que restan profesionalidad, esta herramienta agiliza el proceso permitiendo añadir partidas dinámicas directamente desde el smartphone táctil en menos de 2 minutos.

### 💎 Características Clave:
- **Diseño Geométrico de Alta Fidelidad:** Interfaz limpia basada en una paleta corporativa (Teal & Black) que transmite máxima seriedad.
- **Efecto Acordeón Anti-rotura:** Algoritmo dinámico que reajusta los márgenes y tamaños de fuente según el volumen de líneas (máximo 15) para garantizar que el PDF ocupe siempre una única página A4 perfecta.
- **Persistencia de Datos Local (Local Storage):** Guarda los datos del profesional en el navegador del dispositivo de forma permanente para evitar reescribirlos en cada uso.
- **Cálculo Financiero Reactivo:** Automatización de desgloses de IVA (general o reducido del 10% para reformas particulares) y cálculo inmediato de la regla de adelanto (40% acopio / 60% entrega).
- **Escudo Legal Integrado:** Redacción automática en primera persona de cláusulas de protección contra vicios ocultos e imprevistos estructurales.

---

## 🛠️ Stack Tecnológico

- **Maquetación y UI:** HTML5 & CSS3 nativo (usando Clip-paths para bloques asimétricos).
- **Estilos Adaptativos:** Tailwind CSS (Optimizado con tamaños de fuente específicos para prevenir el zoom automático molesto en iOS/Android).
- **Lógica de Control:** JavaScript Puro (ES6+) reactivo orientado a eventos.
- **Motor de Renderizado:** `html2pdf.js` para la clonación e impresión directa en el cliente sin necesidad de servidores ni bases de datos.
