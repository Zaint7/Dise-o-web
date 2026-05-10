# Mi página personal — HTML5 semántico y accesible

## Propósito
Página de presentación personal para reclutadores y compañeros de universidad.
Muestra información sobre el desarrollador, proyectos en curso, tecnologías manejadas y un formulario de contacto.

## Estructura de archivos
```
Diseño web/
├── index.html
└── assets/
    ├── style.css
    └── perfil.jpeg
```

## Cómo visualizar la página
Abre `index.html` con Live Server en VS Code, o visita el enlace de GitHub Pages una vez publicado.

## Semántica aplicada
- `<header>` para el encabezado principal de la página
- `<nav>` con `aria-label` para la barra de navegación
- `<main>` como contenedor del contenido principal (único en la página)
- `<section>` para cada bloque temático con `aria-labelledby` apuntando al `h2` correspondiente
- `<article>` para cada proyecto (contenido independiente y reutilizable)
- `<aside>` para las habilidades técnicas (contenido relacionado pero secundario)
- `<footer>` para el pie de página

## Accesibilidad aplicada
- `lang="es"` en `<html>` para que los lectores de pantalla usen el idioma correcto
- `alt` descriptivo en todas las imágenes
- `<label>` vinculado a cada campo del formulario mediante `for`/`id`
- `aria-label` en el `<nav>` y en el botón de envío
- Foco visible en todos los elementos interactivos (navegación por teclado con Tab)
- Contraste de color `#1b4332` sobre `#ffffff` (ratio superior a 7:1)
- `aria-labelledby` en cada `<section>` para asociarla a su título

## Validación
Código validado sin errores en https://validator.w3.org/