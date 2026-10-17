# Portafolio web estático

Versión ligera del portafolio personal, hecha con HTML, CSS y JavaScript. No requiere Flask, Python, base de datos ni servidor propio y puede publicarse gratis con GitHub Pages.

## Publicación en GitHub Pages

El workflow `.github/workflows/pages.yml` configura GitHub Pages y publica el sitio automáticamente cuando se suben cambios a `main`. También se puede iniciar manualmente desde **Actions**. Si la organización o la cuenta restringe la activación automática de Pages, habilítalo en **Settings → Pages → Build and deployment → Source → GitHub Actions**.

Cuando termine la ejecución, abre la URL que muestra el workflow o **Settings → Pages**.

## Contenido

- `index.html`: contenido del sitio.
- `static/css/style.css`: estilos y diseño adaptable.
- `static/js/script.js`: menú móvil y año del pie de página.
- `static/`: fotografía y favicon.

Esta versión no incluye los formularios, comentarios ni chatbot del portafolio principal porque necesitan servicios de backend.
