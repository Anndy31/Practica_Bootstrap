# PracticaBootstrap — Portafolio de Proyección Profesional

> **Anndy Tomalo** · Fundamentos Web · Universidad de las Fuerzas Armadas ESPE — Santo Domingo  
> Tercera etapa del proceso de aprendizaje: HTML → CSS → **Bootstrap 5**

---

## Descripción general

Sitio web personal de proyección académica y profesional desarrollado con **Bootstrap 5** y CSS personalizado. A diferencia de la práctica anterior (portafolio de quién soy y qué he hecho), esta versión responde a la pregunta: **¿hacia dónde me dirijo?**

El sitio presenta el perfil profesional futuro, metas académicas, habilidades por desarrollar, certificaciones planificadas y proyectos que se esperan construir entre 2026 y 2028.

---

## Tecnologías utilizadas

| Tecnología | Versión | Uso |
|---|---|---|
| HTML5 | — | Estructura semántica |
| Bootstrap 5 | 5.3.3 | Framework CSS principal |
| CSS3 propio | — | Personalización visual (`css/estilos.css`) |
| Font Awesome | 6.5.0 | Íconos |
| Bootstrap JS Bundle | 5.3.3 | Componentes interactivos (Modal, Carousel, Accordion) |

---

##  Estructura de carpetas

```
PracticaBootstrap/
│
├── index.html                  # Página principal del portafolio
│
├── pages/                      # Subpáginas internas
│   ├── proyeccion.html         # Proyección personal y profesional
│   ├── metas.html              # Metas académicas y personales
│   ├── contacto.html           # Formulario de contacto
│   ├── habilidades.html        # Habilidades detalladas
│   └── proyectos.html          # Proyectos futuros detallados
│
├── css/
│   └── estilos.css             # Estilos propios (650+ líneas)
│
├── img/
│   ├── espe/
│   │   └── imagenEjemploEspe.png
│   ├── proyecto1.jpg
│   ├── proyecto2.jpg
│   ├── proyecto3.jpg
│   └── mundito.ico
│
├── audio/
│   └── audioEjemploA7X.mp3
│
├── video/
│   └── videoEjemploDiagnostica.mp4
│
└── README.md
```

---

## 🧩 Componentes Bootstrap utilizados

| Componente | Dónde se aplica |
|---|---|
| **Navbar** responsiva con hamburguesa | Todas las páginas |
| **Container** + **Grid** (`col-12 col-md-X col-lg-X`) | Estructura general |
| **Cards** | Proyectos, habilidades, certificaciones, perfil |
| **Buttons** | Acciones principales y secundarias |
| **Alerts** | Bienvenida y avisos informativos |
| **Badges** | Tecnologías, estados y fechas |
| **Carousel** | Proyectos futuros y metas académicas |
| **Accordion** | Proyección futura (perfil, metas, área laboral) |
| **Modal** | Plan de mejora personal con formulario |
| **Progress bars** | Nivel de habilidades actuales |
| **List groups** | Intereses, tecnologías y áreas |
| **Tables** (responsive) | Resumen de conocimientos |
| **Forms** | Contacto y plan de mejora (dentro del modal) |
| **Images** (`img-fluid`, `figure`) | Hero, carrusel, proyectos |
| **Utilities** | Spacing, typography, flex, gap, text colors |

### 🔗 Combinaciones destacadas

- **Acordeón que contiene un carrusel**: dentro de "Metas Académicas" en el accordion, se embebe un carousel con las metas.
- **Modal con formulario**: el botón "Ver plan de mejora" abre un modal que contiene un form completo con validación.
- **Cards con badges + botones + imagen**: en la sección de proyectos futuros.
- **Table + Progress bars**: en la misma sección de habilidades, una tabla de conocimientos convive con las barras de progreso.
- **List groups + badges**: en tecnologías a aprender, cada ítem lleva su badge de prioridad o fecha.

---

##  Personalizaciones CSS

El archivo `css/estilos.css` agrega sobre Bootstrap:

- **Variables CSS** propias (`--color-primario`, `--color-dorado`, `--sombra-suave`, etc.)
- **Navbar** con fondo oscuro semitransparente y efectos hover
- **Hero section** con gradiente animado y texto con efecto fade-up
- **Cards personalizadas** con bordes, sombras y efecto lift al pasar el cursor
- **Progress bars** con color propio y animación de entrada
- **Badges** en dos estilos (`badge-tech` y `badge-meta`)
- **Animaciones**: `animate-fade-up`, `avatar-pulse`, `icon-spin`
- **Footer** con columnas, divisor y estilo propio
- **Formularios** con enfoque visual personalizado

---

##  Enfoque Mobile First

El diseño se revisó y verificó en los siguientes breakpoints:

| Pantalla | Comportamiento |
|---|---|
| **Móvil** (< 768px) | Navbar colapsada (hamburguesa), columnas apiladas (`col-12`), imágenes adaptadas |
| **Tablet** (768px–991px) | Grid de 2 columnas (`col-md-6`), navbar expandida |
| **Escritorio** (≥ 992px) | Grid completo (`col-lg-4`, `col-xl-4`), layout de 3 columnas |

Todos los componentes incluyen clases responsivas de Bootstrap. Las tablas usan `table-responsive` y las imágenes usan `img-fluid`.

---

##  Instrucciones para visualizar el sitio

**Opción 1 — Abrir localmente:**
1. Descarga o clona el repositorio.
2. Abre el archivo `index.html` en cualquier navegador moderno.
3. No requiere servidor local ni instalación adicional.

**Opción 2 — Clonar con Git:**
```bash
git clone https://github.com/TU_USUARIO/PracticaBootstrap.git
cd PracticaBootstrap
# Abre index.html en tu navegador
```

> **Nota:** Para que los componentes interactivos (Modal, Carousel, Accordion, Navbar) funcionen correctamente, se requiere conexión a internet la primera vez (Bootstrap y Font Awesome se cargan desde CDN).

---

## 👤 Autor

**Anndy Tomalo**  
Estudiante de Tecnologías de la Información  
Universidad de las Fuerzas Armadas ESPE — Santo Domingo  
Fundamentos Web · 2026
