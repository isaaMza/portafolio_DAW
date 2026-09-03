# Documentación del portafolio

## Estructura del proyecto
- `index.html` — landing page (hero, sección libre, resumen "acerca de mí")
- `education.html` — historial académico, certificados y experiencia laboral
- `projects.html` — catálogo/galería de proyectos
- `navbar.html` — menú de navegación, incluido con `fetch()` en cada página
- `style.css` — hoja de estilos global (paleta, tipografía, layout)

## Herramientas y librerías usadas
- [Bootstrap 5.3.8](https://getbootstrap.com/) — componentes usados explícitamente:
  - `navbar` + `navbar-toggler` — menú responsivo
  - `container-fluid`, `row`, `col-*` — sistema de grid
  - `btn` / `btn-outline-dark` — botón de descarga de CV
  - `badge` — etiquetas de skills (`skill-badge` es una clase propia que se combina con `badge`)
  - `card`, `card-img-top`, `card-body`, `card-title`, `card-text` — tarjetas de la galería de proyectos
  - `list-inline`, `list-inline-item` — lista de hobbies
- [Google Fonts](https://fonts.google.com/) — tipografías Space Grotesk (encabezados) e IBM Plex Mono (etiquetas/mono)
- Patrón de inclusión de `navbar.html` con `fetch()` + `includeHTML()` — basado en el ejercicio de clase (about.html / index.html de referencia)

## Referencias de diseño
- Paleta blanco y negro minimalista definida a partir de la solicitud del proyecto
- Fondos de las tarjetas de proyectos (`thumb-1`, `thumb-2`, `thumb-3`) generados con gradientes CSS
  propios (`radial-gradient`, `repeating-linear-gradient`), sin imágenes externas
- Estructura de línea de tiempo (`.timeline`) para el historial académico, inspirada en patrones
  comunes de timelines de portafolios

## Contenido
Todo el contenido (nombre, carrera, historial académico, certificados, experiencia laboral y
proyectos) fue proporcionado directamente por Ana Isabel Meza Espinosa.

## Archivos adicionales
- `assets/CV_Ana_Isabel_Meza.pdf` — CV enlazado desde el botón "Descargar CV" en `index.html`
- `assets/bbvafoto.png`, `assets/bbvafoto2.png`, `assets/touchdesignerfoto.png`, `assets/pokemon.png` — fotos reales de los proyectos en `projects.html`

## Otros elementos agregados
- Segundo botón en el hero ("Ver más en ._sabel") que enlaza al otro portafolio (Framer): https://crowded-tool-223252.framer.app/
- Franja negra con frase (`statement-band`) inspirada en el estilo bold/minimal del portafolio en Framer
- Logo de la navbar cambiado a "._sabel"

## Inspiración de estos portafolios 
- https://lazyeight.design/
- https://bleed.com/work/skyfall
- https://www.seungmee-lee.com/