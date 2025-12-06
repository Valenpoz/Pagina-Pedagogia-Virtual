# Documentación Diseño: Pedagogía Virtual

Esta documentación proporciona una visión general de la estructura, funcionalidad y estilos del sitio web de **Pedagogía Virtual**.

## Descripción General

El proyecto es una página de aterrizaje (landing page) moderna y responsiva diseñada para **Pedagogía Virtual**, una consultora en educación y tecnología. El sitio destaca sus plataformas, servicios y filosofía empresarial.

### Stack Tecnológico

*   **HTML5:** Estructura semántica del contenido.
*   **CSS3:** Estilos personalizados utilizando variables, Flexbox, Grid y animaciones CSS nativas.
*   **Diseño Responsivo:** Adaptable a dispositivos móviles mediante Media Queries.

## Estructura de Archivos

```
/pedagogia-virtual
├── index.html        # Archivo principal de la estructura de la página
├── style.css         # Hoja de estilos con diseño y animaciones
└── assets/           # Directorio para imágenes y recursos gráficos (logos, iconos)
```

## Componentes Principales ([index.html](file:///c:/Users/lyval/.gemini/antigravity/scratch/pedagogia-virtual/index.html))

La página se divide en las siguientes secciones semánticas:

### 1. Header (`.main-header`)
*   Barra de navegación fija (`sticky`) en la parte superior.
*   Contiene el logo y enlaces a las secciones principales: Plataformas, Quiénes Somos y Servicios.
*   Incluye una animación de entrada `slideDown`.

### 2. Hero Section (`.hero`)
*   Sección introductoria con un degradado llamativo.
*   Muestra el título principal y una breve descripción de la misión de la empresa.
*   Botón de llamada a la acción ("Conócenos").
*   Utiliza `clip-path` para un borde inferior inclinado dinámico.

### 3. Plataformas (`#plataformas`)
*   Presenta las herramientas digitales de la empresa:
    *   **Enlace Digital:** Plataforma de aprendizaje.
    *   **n8n:** Automatización inteligente.
    *   **Comunidad IA:** Comunidad docente sobre IA.
*   Utiliza un diseño de cuadrícula (`grid`) para las tarjetas.
*   Cada tarjeta tiene efectos `hover` que revelan un degradado y elevan el elemento.

### 4. Quiénes Somos (`#quienes-somos`)
*   Describe la naturaleza de la empresa (spin-off del grupo de investigación Virtus).
*   Detalla la misión y el enfoque en TIC.
*   Lista las líneas de investigación activas.

### 5. Servicios (`#servicios`)
*   Catálogo de servicios ofrecidos:
    *   Capacitación Docente, Plataformas Virtuales, Material Educativo, Desarrollo Web, Asesoría Educativa, Consultoría Empresarial.
*   Cada servicio se muestra en una tarjeta con un icono representativo y una descripción.
*   Las tarjetas tienen animaciones de entrada escalonadas (`staggered delay`).

### 6. Footer
*   Información de derechos de autor.

## Estilos y Diseño ([style.css](file:///c:/Users/lyval/.gemini/antigravity/scratch/pedagogia-virtual/style.css))

### Variables CSS (`:root`)
El sistema de diseño centraliza los colores y efectos:
*   `--primary-color`: `#D9202E` (Rojo principal)
*   `--secondary-color`: `#FFC60B` (Amarillo secundario)
*   `--primary-gradient`: Degradado de rojo a naranja.
*   `--dark-bg`: Fondo oscuro para secciones y tarjetas.
*   `--text-color`: Color de texto principal (claro).

### Animaciones
Se implementan animaciones clave frames para mejorar la experiencia de usuario:
*   `fadeInUp`: Aparición suave desde abajo (usado en textos y tarjetas).
*   `slideDown`: Deslizamiento desde arriba (usado en el header).

### Tipografía
Utiliza la fuente **Roboto** de Google Fonts en varios pesos (300, 400, 500, 700, 900).

## Cómo Ejecutar
Simplemente abre el archivo [index.html](file:///c:/Users/lyval/.gemini/antigravity/scratch/pedagogia-virtual/index.html) en cualquier navegador web moderno. No se requiere servidor de compilación ni dependencias externas más allá de la conexión a internet para cargar las fuentes de Google.
