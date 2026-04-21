# Guía de Ruta y Restricciones de Cambios

Este documento resume la estrategia de diseño y las restricciones críticas para el desarrollo del Portafolio JGRD.

## 🚫 Restricciones Críticas (Inviolables)
1. **Integridad de la Información**: Bajo ninguna circunstancia se debe resumir, omitir o parafrasear la información contenida en el objeto `PORTFOLIO_DATA`. Cada palabra, título de investigación y viñeta de experiencia debe mantenerse literal.
2. **Cero Huecos (Densidad Visual)**: El diseño debe evitar espacios blancos innecesarios (huecos) que hagan sentir la página vacía. Se prioriza el uso de tarjetas de ancho completo y alineaciones eficientes.
3. **Stand-alone**: El proyecto debe seguir siendo funcional en un único archivo `index.html` (o archivos estáticos simples) que no requieran procesos de construcción (`npm install`, `vite build`, etc.) para su visualización local.

## 🛣️ Ruta de Cambios Implementada
1. **Layout de Línea de Tiempo**: 
   - Se eliminó el diseño de zig-zag alterno.
   - Se implementó una línea lateral izquierda para maximizar el ancho disponible para el texto.
2. **Estética "Premium Glass"**:
   - Uso de `backdrop-blur-md` y bordes con transparencia sutil.
   - Tipografía moderna: **Plus Jakarta Sans**.
   - Micro-animaciones de revelado (`reveal`) al hacer scroll.
3. **Barra de Contacto Clásica**:
   - Ubicación en la sección Hero con formato: `Teléfono | Email | Ubicación | LinkedIn | GitHub`.
4. **Galería Dinámica**:
   - Implementación de un "Mini Acordeón" para la sección de Adakademy que permite desplegar/ocultar fotos locales sin romper el layout.

## 📂 Estructura de Archivos
- `index.html`: Núcleo del proyecto (HTML/JS/CSS).
- `Public/`: Carpeta contenedora de activos locales (`Perfil.jpeg`, `Adakademy/`).

---
*Este documento sirve como referencia para mantener la consistencia en futuras actualizaciones.*
