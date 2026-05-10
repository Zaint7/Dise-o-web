# Mi página personal — HTML5 semántico y accesible

## Propósito
Página de presentación personal para reclutadores y compañeros de universidad.

## Estructura de archivos
mi-pagina/
├── index.html
└── assets/
├── style.css
└── perfil.jpg
## Semántica aplicada
- `<header>` para el encabezado principal
- `<nav>` con `aria-label` para la navegación
- `<main>` como contenedor del contenido principal
- `<section>` para cada bloque temático con `aria-labelledby`
- `<article>` para cada proyecto (contenido independiente)
- `<aside>` para las habilidades secundarias
- `<footer>` para el pie de página

## Accesibilidad aplicada
- `lang="es"` en `<html>`
- `alt` descriptivo en todas las imágenes
- `<label>` vinculado a cada campo de formulario con `for`/`id`
- `aria-label` en navegación y botón
- Foco visible en todos los elementos interactivos (Tab)
- Contraste de color #003366 sobre #ffffff (ratio > 7:1)

## Validación
Código validado sin errores en https://validator.w3.org/