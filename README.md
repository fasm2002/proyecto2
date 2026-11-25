# Fiesta Viva · Sitio web con cotizador de eventos

Proyecto del Laboratorio 13 de Desarrollo de aplicaciones web I.
Empresa ficticia creada con fines académicos.

## Cómo ejecutarlo
1. Abrir la carpeta en Visual Studio Code.
2. Clic derecho en `index.html` → «Open with Live Server».
3. Pruebas del cotizador: `node pruebas/cotizador.test.js`

## Estructura
- `index.html` · página principal
- `css/estilos.css` · estilos mobile-first
- `js/cotizador.js` · reglas de negocio (tarifas, validación y cálculo)
- `js/app.js` · menú, formulario y resumen
- `img/` · ilustraciones en JPG y WebP, logotipo y favicon
- `pruebas/` · pruebas automáticas del cotizador

## Uso de inteligencia artificial
- Asistente de código: estructura HTML, estilos y funciones del cotizador.
  Todo el código fue revisado, corregido y probado por el equipo.
- Corrección aplicada: la propuesta inicial del resumen usaba `innerHTML` con el
  nombre del cliente (riesgo de XSS); se reemplazó por `textContent` y `createElement`.
- Textos: borradores de servicios y descripción SEO revisados por el equipo.
- Imágenes: ilustraciones de referencia; no representan eventos reales.
