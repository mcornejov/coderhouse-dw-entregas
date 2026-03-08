# Cafe Aurora

Sitio web de una cafeteria de especialidad, desarrollado como proyecto integrador del curso de **Desarrollo Web** en CoderHouse.

## Demo

[Ver sitio en vivo](https://mcornejov.github.io/coderhouse-dw-entregas/)

## Paginas

| Pagina | Descripcion |
|--------|-------------|
| `index.html` | Inicio: carousel hero, sobre nosotros, especialidades, experiencia, musica |
| `pages/menu.html` | Menu: cafes, pasteleria, origenes, maridajes, recomendados del barista |
| `pages/contacto.html` | Contacto: formulario, preguntas frecuentes, ubicacion y horarios |

## Tecnologias

- HTML5 semantico
- SASS/SCSS (arquitectura modular 7-1)
- CSS3 compilado desde SCSS
- Bootstrap 5.3 (CDN — navbar y carousel)
- Google Fonts (Playfair Display + Lato)
- Responsive design (mobile-first, media queries propias)

## Estructura

```
├── index.html
├── pages/
│   ├── menu.html
│   └── contacto.html
├── scss/
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _reset.scss
│   │   ├── _typography.scss
│   │   └── _utilities.scss
│   ├── components/
│   │   ├── _navbar.scss
│   │   ├── _buttons.scss
│   │   ├── _cards.scss
│   │   ├── _carousel.scss
│   │   ├── _forms.scss
│   │   ├── _accordion.scss
│   │   ├── _blockquote.scss
│   │   └── _tables.scss
│   ├── layout/
│   │   ├── _grid.scss
│   │   ├── _sections.scss
│   │   ├── _footer.scss
│   │   └── _aside.scss
│   ├── pages/
│   │   ├── _home.scss
│   │   ├── _menu.scss
│   │   └── _contacto.scss
│   ├── vendors/
│   │   └── _bootstrap-overrides.scss
│   └── main.scss
├── css/
│   └── styles.css          (compilado desde SCSS)
├── img/
│   ├── hero.jpg
│   ├── local.jpg
│   ├── logo.svg
│   ├── producto-1.jpg
│   ├── producto-2.jpg
│   └── ambiente.mp3
└── wireframes/
    ├── wireframe-desktop.svg
    └── wireframe-mobile.svg
```

## SCSS

El proyecto usa una arquitectura modular SASS con:

- **Variables**: paleta de colores, tipografia, breakpoints, spacing
- **Mixins**: `respond-to()`, `button-variant()`, `flex-center()`, `card-hover()`
- **Nesting** con `&` para BEM y pseudo-clases
- **@extend** con placeholders (`%btn-base`)
- **@each** para generar clases dinamicas de color
- **@if/@else** en mixins condicionales

## Creditos

- Imagenes: [Freepik](https://www.freepik.es/)
- Musica: "Autumn Is Coming (Piano)" — Monument_Music ([Pixabay](https://pixabay.com/music/))
