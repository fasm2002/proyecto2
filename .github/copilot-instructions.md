# Instrucciones del proyecto «Fiesta Viva» para asistentes de IA

## Contexto
Sitio web de una empresa ficticia que organiza eventos festivos en Lima (Perú).
Curso: Desarrollo de aplicaciones web I · Semana 13.

## Tecnologías
- HTML5 semántico, CSS3 (Flexbox, Grid, variables) y JavaScript sin frameworks.
- Sin librerías externas ni CDN.
- Estructura: index.html, css/estilos.css, js/cotizador.js, js/app.js, img/.

## Reglas de código
- Textos visibles y comentarios en español; variables y funciones en camelCase.
- Diseño mobile-first con puntos de quiebre en 768 px y 1024 px.
- Accesibilidad WCAG 2.2 AA: label en cada campo, alt descriptivo, foco visible,
  botones de al menos 48 px de alto, aria-expanded en el menú.
- Imágenes con <picture> (WebP y JPG), width, height y loading="lazy" fuera del hero.
- Nunca usar innerHTML con datos del usuario: usar textContent o createElement.
- Precios en soles (PEN) con Intl.NumberFormat("es-PE").

## Prohibido
- Incluir datos personales reales, claves o tokens.
- Inventar clientes, testimonios o premios.
