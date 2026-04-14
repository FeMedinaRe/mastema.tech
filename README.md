# Mastema Tech - Landing Page

Bienvenido al repositorio de la landing page de **Mastema Tech**, tu aliado tecnológico de confianza.

Este proyecto es una página web estática (HTML, CSS y JS) diseñada para mostrar los servicios de soporte técnico informático, incluyendo formateo, mejora de componentes y armado de computadores a la medida. Está construida enfocándose en una experiencia de usuario moderna (UX/UI), un modo oscuro (dark theme) muy profesional y compatibilidad con todos los dispositivos.

## Tecnologías Utilizadas

*   **HTML5**
*   **CSS3** (incluyendo **Bootstrap 5.1.3** precompilado en `styles.css` con variables personalizadas).
*   **JavaScript (Vanilla)** para efectos de la interfaz (Smooth Scroll y animaciones de la barra de navegación).
*   **Google Fonts** (Tipografía: *Inter*)
*   **Bootstrap Icons**

## Características Principales

*   **Tema Oscuro:** Diseño "Dark Mode" predeterminado (`#0f172a`), más atractivo para empresas tecnológicas y amigable a la vista.
*   **Diseño Responsivo:** Se adapta perfectamente a smartphones, tablets y computadoras de escritorio.
*   **Micro-interacciones:** Tarjetas de servicio con efectos de elevación (`hover lift`), sombras ajustadas, barra de navegación cristalina (efecto `backdrop-filter: blur`) que disminuye de tamaño al hacer scroll.
*   **Ligero y Rápido:** No requiere sistemas de construcción (como Webpack o Node.js) ni bases de datos para funcionar. 

## Cómo Ejecutar el Proyecto (Modo Desarrollo)

Puesto que este es un proyecto completamente estático, existen varias formas de previsualizarlo en tu entorno local:

### Opción 1: Abrir directamente (Sin servidor)
La forma más fácil es hacer doble clic en el archivo `index.html` ubicado en la carpeta principal. Tu navegador web predeterminado abrirá la página (`file:///ruta/hacia/index.html`).

### Opción 2: Servidor local HTTP (Recomendado)
Para evitar problemas técnicos vinculados a CORS o rutas de archivos en el futuro, se recomienda abrir un servidor local básico:

**Si usas Python 3:**
Abre tu terminal, sitúate en el directorio del proyecto y ejecuta:
```bash
python3 -m http.server 8000
```
Luego ve a `http://localhost:8000` en tu navegador.

**Si usas Node.js (npx):**
Abre tu terminal, sitúate en el directorio del proyecto y ejecuta:
```bash
npx serve
```
Luego ve a la dirección que te indique la terminal (por lo general `http://localhost:3000`).

## Estructura de Archivos

```text
/
├── index.html        # Página principal y estructura del contenido
├── css/
│   └── styles.css    # Código CSS de Bootstrap y reglas personalizadas (ubicadas al principio del archivo)
├── js/
│   └── scripts.js    # Scripts de animaciones y comportamiento interactivo
├── assets/           # Carpeta para iconos o imágenes (incluye favicon)
├── LICENSE           # Licencia original (MIT)
└── README.md         # Documentación del proyecto
```

## Cambios Futuros

*   **Estilos:** Si necesitas alterar colores corporativos o efectos de borde, edita directamente las variables o clases en la parte superior del archivo `css/styles.css`.
*   **Contenido:** Puedes añadir más `cards` a la cuadrícula de `#servicios` dentro de `index.html`. Asegúrate de usar los íconos correctos buscando en el [Directorio de Bootstrap Icons](https://icons.getbootstrap.com/).

---
© 2026 Mastema Tech. Todos los derechos reservados.
