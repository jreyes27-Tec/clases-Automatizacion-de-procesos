# Sitio académico – Dr. José Reyes Rosales

Plantilla profesional de blog / sitio web para publicar clases, proyectos y material de Ingeniería Mecatrónica.

## Estructura

```
blog_dr_reyes/
├── index.html              ← Página de inicio
├── acerca.html             ← Acerca del docente y del sitio
├── css/style.css           ← Estilos globales
├── assets/                 ← Logos institucionales
├── clases/
│   ├── index.html          ← Listado de clases
│   ├── 01-diseno-mecanico-cad.html
│   └── diagrama_automatizacion_interactivo.html
└── proyectos/
    └── index.html          ← Listado de proyectos (listo para ampliar)
```

## Cómo publicarlo en internet (gratis)

### Opción recomendada: GitHub Pages

1. Crea una cuenta en [github.com](https://github.com) (si no tienes).
2. Crea un repositorio nuevo (ej. `clases-mecatronica` o `dr-reyes-rosales`).
3. Sube **toda la carpeta** `blog_dr_reyes` (el contenido interno, no la carpeta en sí si quieres la raíz limpia).
4. En el repositorio: **Settings → Pages → Source: Deploy from a branch → main → / (root)**.
5. En unos minutos tendrás una URL tipo:  
   `https://tu-usuario.github.io/clases-mecatronica/`

### Otras opciones gratuitas

- **Netlify**: arrastra la carpeta a [netlify.com/drop](https://app.netlify.com/drop)
- **Vercel**: importa el repositorio desde vercel.com
- **Cloudflare Pages**

## Cómo agregar una nueva clase

1. Crea un archivo en `clases/`, por ejemplo `02-sistemas-control.html` (puedes copiar `01-diseno-mecanico-cad.html` y adaptarlo).
2. Agrega una tarjeta nueva en `clases/index.html` apuntando a ese archivo.
3. Si la clase tiene un HTML interactivo propio, colócalo también dentro de `clases/` y enlázalo.

## Cómo agregar un proyecto

1. Crea un archivo o carpeta dentro de `proyectos/`.
2. Agrega una tarjeta en `proyectos/index.html`.

## Personalización rápida

- **Nombre y cargos**: busca “José Reyes Rosales” en todos los HTML y actualiza.
- **Semblanza**: edita `acerca.html`.
- **Colores**: modifica las variables en `css/style.css` (`--navy`, `--accent`, etc.).

## Primera clase incluida

Ya está publicada la **Clase 01 – Diseño Mecánico y Modelado CAD / CAM / CAE** con el diagrama interactivo completo.
