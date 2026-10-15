# LUVEN — Plan de lanzamiento modular v2.0

Web móvil estática: HTML, CSS, JavaScript y JSON por sección.

## Estructura

- `index.html`: punto de entrada y navegación por páginas.
- `css/styles.css`: estilos.
- `js/app.js`: navegación, checklist, búsqueda y respaldos.
- `data/site.json`: listado de módulos.
- `data/*.json`: tareas independientes por categoría y storytelling.
- `assets/`: fotografías del producto (pendientes de integrar).

Para agregar un módulo: crea su archivo JSON e incorpóralo a `data/site.json`. Para modificar tareas existentes edita solamente el JSON de su sección y conserva los identificadores de pasos: así no se pierde el progreso guardado.

## Publicación

GitHub Pages: rama `main`, carpeta `/(root)`.
URL prevista: https://jcarlospm05.github.io/Luven-plan/

## Advertencias

El progreso se guarda localmente en cada navegador. El respaldo JSON sirve para trasladarlo a otro teléfono. Esta web no es una tienda ni permite vender alcohol. No guardar contraseñas ni información personal de clientes en un repositorio público.

Fotos reales de las dos botellas: pendientes de agregar bajo `assets/botella-750.jpg` y `assets/botella-350.jpg`.
