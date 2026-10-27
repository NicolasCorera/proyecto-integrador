# PROYECTO INTEGRADOR UTN - Landing Page de Perfumería

_Proyecto integrador de la Diplomatura en Programación Web Full Stack de la UTN_

Repositorio: [github.com/NicolasCorera/proyecto-integrador](https://github.com/NicolasCorera/proyecto-integrador)

## Descripción

Landing page de **AROMA**, una perfumería de lujo ficticia, con estética oscura y detalles dorados. Es un sitio estático hecho solo con HTML y CSS, sin JavaScript ni dependencias propias.


## Tecnologías

- HTML5
- CSS3 (variables CSS, Flexbox, Grid, transiciones)
- [Material Symbols Outlined](https://fonts.google.com/icons) (Google Fonts) para los íconos
- Íconos SVG de [SVG Repo](https://www.svgrepo.com/)
- Git y GitHub para el trabajo en equipo

## Estructura del proyecto

```
.
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── img/
│       ├── hero.webp
│       ├── banner.webp
│       ├── banner_2.webp
│       ├── banner_3.webp
│       ├── product_1.webp
│       ├── product_2.webp
│       ├── product_3.webp
│       ├── leaf-svgrepo-com.svg
│       ├── diamond-svgrepo-com.svg
│       ├── transport-svgrepo-com.svg
│       └── shield-check-svgrepo-com.svg
├── LICENSE.md
└── README.md
```

## Cómo ejecutarlo

1. Clonar el repositorio:

```bash
git clone https://github.com/NicolasCorera/proyecto-integrador.git
cd proyecto-integrador
```

2. Levantar un servidor local en la raíz del proyecto:

```bash
python3 -m http.server 8000
```

3. Abrir `http://localhost:8000` en el navegador.

> Las imágenes se cargan con rutas absolutas (`/assets/img/...`), por lo que el sitio tiene que servirse desde la raíz. Abriendo `index.html` directamente con doble clic las imágenes no se van a ver.

## Flujo de trabajo

El equipo trabaja con una rama `main` y una rama por integrante o funcionalidad, que se integran mediante Pull Requests.

| Rama | Uso |
| --- | --- |
| `main` | Rama principal |
| `feat/startWeb` | Primera parte del `index.html` |
| `feature/comienzo-de-css` | Estilos del hero, la navbar, los productos y las flechas del carrusel |
| `pedeflous-carlos-ananashei` | Estructura HTML de la sección 2 |
| `feature-daniproyecto`, `feature/Carlos`, `feature/eze`, `feature/pato`, `feature/tamara` | Ramas personales de cada colaborador |

## Estado actual

- El proyecto no tiene JavaScript: las flechas del carrusel de productos son solo visuales y los botones no ejecutan ninguna acción.
- Los links del menú, del footer y de las redes sociales son marcadores de posición.
- La sección de newsletter todavía no tiene formulario.
- Solo las secciones Hero, Colección y About us tienen estilos aplicados.
- No hay media queries: el diseño no está adaptado a pantallas chicas.

# Colaboradores

- 1 Patricio Gamarra
- 2 Carlos Pedeflous
- 3 Daniela Maracara
- 4 Ezequiel Gimenez
- 5 Tamara Rodas
- 6 Nicolás Corera

## Licencia 📄

Este proyecto está bajo la Licencia GNU GPL v3 - mira el archivo [LICENSE.md](LICENSE.md) para detalles