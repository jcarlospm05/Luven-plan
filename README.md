# LUVEN Plan · CRM + CMS modular v3.0

Aplicación web móvil para coordinar el lanzamiento de LUVEN, desplegada en GitHub Pages.

## Páginas
- ToDo · CRM: todas las tareas, búsqueda, filtros, estados, notas.
- Roadmap: fases de octubre y noviembre.
- Datasheet: ficha maestra y límites reales del proyecto.
- Estrategia: decisiones, canales, contenido y publicidad.
- Storytelling CMS: editar, previsualizar, guardar y copiar texto.
- Identidad gráfica: paleta, tipografías y ejemplos visuales de publicaciones.
- Fotografías: sección para botellas reales (archivos pendientes).
- Respaldo: exportar/importar JSON con estados, notas y storytelling.
- Páginas separadas por cada área del plan.

## Arquitectura
- `index.html`: shell.
- `css/styles.css`: diseño responsive y tipografía Playfair Display / DM Sans.
- `js/app.js`: navegación, CRM y CMS local.
- `data/site.json`: mapa de módulos.
- `data/plan-maestro.json`: datasheet, estrategia y roadmap.
- `data/story.json`: storytelling inicial.
- `data/*.json`: pasos por área.
- `assets/`: espacio para fotografías reales.

Agregar tareas requiere modificar solo el archivo JSON de su módulo. Al agregar un módulo nuevo, registrar el archivo en `data/site.json`. Mantener los identificadores de pasos para conservar el progreso local.

## Importante
El CMS y el CRM actuales almacenan cambios en **localStorage del navegador**, no en GitHub. Para compartirlos entre teléfonos, exportar e importar un respaldo JSON. Una próxima fase con autenticación y base de datos sería necesaria para sincronización multiusuario automática.

La web no es una tienda, no realiza cobros ni permite vender productos con alcohol. Los contenidos públicos y políticas comerciales deben cumplir las reglas correspondientes. El repositorio es público: nunca guardar información confidencial.

URL: https://jcarlospm05.github.io/Luven-plan/
