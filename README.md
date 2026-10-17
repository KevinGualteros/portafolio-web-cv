# Portafolio web estático

Versión ligera del portafolio personal, hecha con HTML, CSS y JavaScript. No requiere Flask, Python, base de datos ni servidor propio y puede publicarse gratis con GitHub Pages.

## Publicación en GitHub Pages

1. En el repositorio, abre **Settings → Pages**.
2. En **Build and deployment → Source**, selecciona **GitHub Actions** y guarda el cambio.
3. El workflow `.github/workflows/pages.yml` publicará el sitio automáticamente al subir cambios a `main`. También se puede iniciar manualmente desde **Actions**.
4. Cuando termine la ejecución, abre la URL que muestra el workflow o **Settings → Pages**.

## Contenido

- `index.html`: contenido del sitio.
- `static/css/style.css`: estilos y diseño adaptable.
- `static/js/script.js`: menú móvil y año del pie de página.
- `static/`: fotografía y favicon.

Esta versión no incluye los formularios, comentarios ni chatbot del portafolio principal porque necesitan servicios de backend.
