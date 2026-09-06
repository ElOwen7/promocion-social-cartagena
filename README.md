# Sitio web — I.E. Promoción Social de Cartagena

Sitio institucional estático construido únicamente con HTML, CSS y JavaScript.

## Abrir en Windows

Abre directamente el archivo `dist/index.html`. Los enlaces apuntan a archivos HTML concretos, por lo que funcionan incluso sin un servidor local.

## Estructura

- `dist/index.html`: página principal.
- `dist/eventos/index.html`: agenda y noticias.
- `dist/styles.css`: diseño, colores y adaptación para celulares.
- `dist/script.js`: menú móvil y animaciones.
- `dist/assets/`: fotografías, escudo, logo, QR y plan de actividades.

## Publicar gratis en Render

1. Sube el proyecto a GitHub.
2. En Render crea un **Static Site**.
3. Usa `dist` como **Publish Directory**.
4. El sitio no necesita comando de construcción.

También puedes usar el archivo `render.yaml` mediante la opción **Blueprint** de Render.

## Actualizar contenido

- Para cambiar fechas o actividades, edita `dist/index.html` y `dist/eventos/index.html`.
- Para reemplazar fotografías conserva el mismo nombre dentro de `dist/assets/`.
- Los colores institucionales están definidos al inicio de `dist/styles.css`.
