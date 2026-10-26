# NAVAR | Arquitectura, Diseño y Construcción

## Descripción del proyecto

NAVAR es un proyecto web personal orientado a presentar servicios profesionales de arquitectura, diseño y construcción.

El sitio reúne información sobre mi perfil profesional, los servicios ofrecidos, los proyectos y los canales de contacto.

## Tecnologías utilizadas

- HTML5
- CSS3
- Sass (SCSS)
- Bootstrap 5
- Flexbox y CSS Grid
- Diseño responsive
- Git y GitHub

## Estructura del proyecto

- `index.html`: página principal.
- `pages/`: páginas de contacto, proyectos, servicios y sobre mí.
- `scss/`: archivos fuente SCSS organizados por responsabilidades.
- `scss/main.scss`: archivo principal que importa los módulos SCSS.
- `styles/styles.css`: hoja de estilos compilada utilizada por las páginas HTML.
- `img/`: recursos gráficos del sitio.

## Compilación de Sass

El proyecto utiliza Sass con sintaxis SCSS para organizar y mantener los estilos de forma modular.

Para compilar los archivos SCSS y generar la hoja de estilos CSS, se utiliza Sass desde la terminal, ubicado en la raíz del proyecto:

```powershell
sass.cmd --no-source-map scss/main.scss styles/styles.css
```

Este comando compila `scss/main.scss` y genera o actualiza `styles/styles.css`, archivo vinculado desde las páginas HTML.

Para que los cambios realizados en los archivos SCSS se reflejen en el sitio, es necesario volver a ejecutar el comando de compilación.

## Publicación

El sitio web está publicado mediante GitHub Pages.

**URL del sitio publicado:** https://eliastnavarro.github.io/navar-desarrollo-web/

## Autor

Elías Navarro

Proyecto desarrollado como parte de la carrera de Desarrollo Web de Coderhouse.