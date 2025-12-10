[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5wZOCA16)
# Laboratorios de CSS. Proyecto de Curriculum Vitae

Este proyecto consiste en una serie de laboratorios prácticos donde crearás tu propio curriculum vitae utilizando HTML y CSS. A lo largo de tres laboratorios, irás aplicando diferentes conceptos y técnicas de CSS para mejorar progresivamente el diseño de tu CV.

## Estructura del Proyecto

El template base incluye las siguientes secciones:
- **Header**: Nombre completo y título profesional
- **Sobre Mí**: Descripción personal con foto de perfil
- **Habilidades**: Lista de competencias técnicas
- **Estudios**: Formación académica
- **Hobbies**: Intereses personales
- **Redes Sociales**: Enlaces a perfiles profesionales
- **Footer**: Copyright

### Estructura de Archivos Sugerida

```
lab4-css-template/
│
├── index.html              # Archivo HTML principal
├── readme.md               # Este archivo
│
├── css/
│   ├── styles.css         # Estilos principales (Lab 4)
│   ├── layout.css         # Estilos de posicionamiento y flexbox (Lab 5) - opcional
│   └── responsive.css     # Media queries (Lab 6) - opcional
│
├── assets/
│   ├── images/
│   │   ├── profile.jpg    # Tu foto de perfil
│   │   └── background.jpg # Imagen de fondo - opcional
│   │
│   └── icons/
│       ├── linkedin.png   # Icono de LinkedIn
│       ├── github.png     # Icono de GitHub
│       ├── twitter.png    # Icono de Twitter
│       └── instagram.png  # Icono de Instagram
│
└── docs/                  # Carpeta opcional para documentación adicional
    └── lab-notes.md       # Notas de cada laboratorio - opcional
```

**Nota:** Puedes mantener todos los estilos en un solo archivo `styles.css` o separarlos en múltiples archivos CSS según tu preferencia. Si utilizas múltiples archivos, recuerda enlazarlos todos en el `index.html`.

## Laboratorios

### Laboratorio 4: CSS - Tipografía, Fondos y Bordes
En este laboratorio aprenderás a:
- Aplicar diferentes fuentes tipográficas
- Establecer tamaños, pesos y estilos de texto
- Utilizar colores y gradientes de fondo
- Crear y personalizar bordes
- Dar estilo básico a las secciones del CV

**Entregables:**
- Archivo `css/styles.css` con estilos de tipografía, fondos y bordes
- Carpeta `assets/` con imágenes e iconos organizados
- CV con diseño visual básico

**Tips de propiedades CSS útiles:**
- **Tipografía:** `font-family`, `font-size`, `font-weight`, `font-style`, `line-height`, `text-align`, `text-transform`, `letter-spacing`, `color`
- **Fondos:** `background-color`, `background-image`, `background-size`, `background-position`, `background-repeat`, `background-gradient` (linear-gradient, radial-gradient)
- **Bordes:** `border`, `border-width`, `border-style`, `border-color`, `border-radius`, `box-shadow`
- **Espaciado:** `margin`, `padding`
- **Otros:** `opacity`, `text-decoration`, `list-style`

### Laboratorio 5: CSS - Posición, Fondos y Flexbox
En este laboratorio aprenderás a:
- Utilizar diferentes tipos de posicionamiento (relative, absolute, fixed)
- Aplicar fondos avanzados (imágenes, múltiples fondos)
- Implementar Flexbox para layouts
- Organizar elementos de forma flexible y responsive
- Mejorar la distribución de contenido en las secciones

**Entregables:**
- Archivo `css/layout.css` (opcional) o continuar en `css/styles.css`
- CV con layout estructurado usando Flexbox
- Elementos posicionados correctamente

**Tips de propiedades CSS útiles:**
- **Posicionamiento:** `position` (static, relative, absolute, fixed, sticky), `top`, `right`, `bottom`, `left`, `z-index`
- **Flexbox:** `display: flex`, `flex-direction`, `justify-content`, `align-items`, `align-content`, `flex-wrap`, `gap`, `flex-grow`, `flex-shrink`, `flex-basis`
- **Dimensiones:** `width`, `height`, `max-width`, `min-height`
- **Fondos avanzados:** `background-attachment`, múltiples `background-image`, `background-blend-mode`
- **Otros:** `overflow`, `display` (block, inline, inline-block)

### Laboratorio 6: CSS - Diseño Responsivo y Media Queries
En este laboratorio aprenderás a:
- Implementar media queries para diferentes tamaños de pantalla
- Crear un diseño adaptable (responsive design)
- Optimizar el CV para móviles, tablets y desktop
- Aplicar técnicas de diseño mobile-first
- Ajustar tipografía y espaciados según el dispositivo

**Entregables:**
- Archivo `css/responsive.css` (opcional) o continuar en `css/styles.css`
- CV completamente responsive
- Diseño optimizado para al menos 3 breakpoints diferentes (móvil, tablet, desktop)

**Tips de propiedades CSS útiles:**
- **Media Queries:** `@media` con condiciones como `min-width`, `max-width`, `orientation`
- **Breakpoints comunes:** 320px (móvil pequeño), 768px (tablet), 1024px (desktop), 1440px (desktop grande)
- **Unidades relativas:** `rem`, `em`, `%`, `vw`, `vh`
- **Flexbox responsive:** Ajustar `flex-direction`, `flex-wrap` según el tamaño de pantalla
- **Diseño adaptable:** `max-width` para contenedores, `width: 100%` para imágenes
- **Otros:** `display: none` / `display: block` para mostrar/ocultar elementos, ajustar `font-size` y `padding` según breakpoints

## Instrucciones Generales

1. **No modifiques** la estructura HTML base sin consultar con el instructor
2. **Crea la estructura de carpetas** siguiendo la sugerida arriba:
   - Carpeta `css/` para tus archivos de estilos
   - Carpeta `assets/images/` para tus imágenes (foto de perfil, fondos, etc.)
   - Carpeta `assets/icons/` para los iconos de redes sociales
3. **Agrega tus propios assets** organizados en las carpetas correspondientes:
   - `assets/images/profile.jpg` - Tu foto de perfil
   - `assets/icons/linkedin.png` - Icono de LinkedIn
   - `assets/icons/github.png` - Icono de GitHub
   - `assets/icons/twitter.png` - Icono de Twitter
   - `assets/icons/instagram.png` - Icono de Instagram
4. **Enlaza tu CSS** en el `index.html` usando rutas relativas: `<link rel="stylesheet" href="css/styles.css">`
5. **Personaliza el contenido** con tu información real
6. **Crea un archivo CSS** para cada laboratorio (`styles.css`, `layout.css`, `responsive.css`) o mantén uno solo con comentarios que separen cada sección
7. **Prueba tu diseño** en diferentes navegadores y tamaños de pantalla

## Comandos Git

### Clonar el repositorio por primera vez
```bash
# Clona el repositorio en tu máquina local
git clone [URL_DEL_REPOSITORIO]

# Navega a la carpeta del proyecto
cd lab4-css-template
```

### Sincronizar cambios del repositorio
```bash
# Antes de empezar a trabajar, obtén los últimos cambios
git pull origin main
```

### Guardar tus cambios
```bash
# Agregar todos los archivos modificados
git add .

# Crear un commit con un mensaje descriptivo
git commit -m "Descripción de los cambios realizados"

# Subir tus cambios al repositorio
git push origin main
```

**Recomendaciones:**
- Siempre haz `git pull` antes de empezar a trabajar
- Haz commits con mensajes claros como: "Completar Lab 4 - tipografía y fondos"
- Sube tus cambios con `git push` al finalizar tu sesión de trabajo

## Recursos Recomendados

- [MDN Web Docs - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Google Fonts](https://fonts.google.com/)
- [Can I Use](https://caniuse.com/) - Para verificar compatibilidad de propiedades CSS

## Evaluación

Cada laboratorio será evaluado según:
- Correcta aplicación de los conceptos de CSS enseñados
- Creatividad en el diseño
- Calidad del código (organización, comentarios)
- Funcionalidad y presentación final

¡Buena suerte con tus laboratorios! 🚀