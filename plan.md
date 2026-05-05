# Plan de Redesign y Evolución de Mastema Tech Solutions

## 1. Objetivo General
Transformar el sitio web de **Mastema Tech** en la plataforma corporativa de **Mastema Tech Solutions**, destacando los servicios de:

- **Desarrollo de SaaS a medida**
- **Soporte TI externalizado**
- **Consultorías y auditorías de mantenimiento**
- **Traspaso y soporte en la nube**

## 2. Hallazgos Previos
- **Nombre actual**: Mastema Tech  
- **Meta description**: “Soluciones informáticas y soporte técnico para empresas y particulares. Formateo, mejora de componentes y armado de PC a pedido.”
- **Servicios mostrados**: Enfoque en reparación de hardware y armado de PCs.
- **Estructura**: Navbar, hero con título “Tu aliado tecnológico de confianza”, sección de servicios en cards, footer con contacto.

## 3. Cambios Propuestos

### 3.1. Estructura y Contenido (`index.html`)
| Área | Cambio |
|------|--------|
| **Título & Meta** | `title: Mastema Tech Solutions – Soluciones SaaS y Soporte IT` |
| **Meta description** | “Mastema Tech Solutions ofrece desarrollo de SaaS, soporte TI externalizado, consultorías y migración a la nube para empresas.” |
| **Nombre de la marca** | Cambiar “Mastema Tech” → **Mastema Tech Solutions** en todo el sitio (navbar, hero, footer). |
| **Eslogan Hero** | Reemplazar por **“Tu aliado tecnológico en la nube y transformación digital”**. |
| **Sección de Servicios** | Reemplazar los 3 cards actuales por: |
| | 1. **Soporte TI Externalizado** – icono `bi-headset` |
| | 2. **Consultorías & Auditorías** – icono `bi-search` o `bi-clipboard-check` |
| | 3. **Migración y Soporte en la Nube** – icono `bi-cloud` |
| **Hero Image** | Mantener imagen actual o actualizar a una visual que represente nube/transformación. |
| **Llamada a Acción** | Revisar texto del botón “Solicitar Soporte” y adaptar a “Solicitar Soporte IT”. |
| **Nueva Sección de Casos de Éxito** | Insertar un bloque de 3‑4 tarjetas con proyectos destacados (en construcción). |
| **Footer** | Actualizar con el nuevo eslogan y mantener datos de contacto (email). |

### 3.2. Estilos (`css/styles.css`)
- **Paleta de colores**: 
  - Azul corporativo: `#0d6efd` (primary)  
  - Gris oscuro: `#212529` (texto)  
  - Verde suave para elementos de éxito: `#198754`  
- **Actualizar variables** en `:root` para reflejar la nueva identidad visual.
- **Cards de servicios**: 
  - Ajustar fondo a `#ffffff` con borde sutil `#dee2e6`.
  - Estilos de ícono y tipografía alineados al nuevo enfoque.
- **Botones**: Aplicar estilo `btn-primary` con color de fondo `#0d6efd` y hover `#0a58ca`.
- **Sección de Casos de Éxito**: Definir grid de 3 columnas en pantallas ≥992px; responsive 1‑2 columnas en móviles.
- **Footer**: Fondo `#050505` con texto blanco, mantener borde superior ligero.

### 3.3. Interactividad (`js/scripts.js`)
- **Scroll suave** para enlaces del navbar que apunten a secciones internas.
- **Animaciones de entrada** (fade‑in) para los cards de la nueva sección de casos de éxito.
- **Validaciones de formulario** (si se agrega un formulario de contacto) utilizando Bootstrap 5 validation utilities.
- **Gestión de menú móvil**: asegurar que el toggler funcione y cierre el menú tras selección.

## 4. Implementación Paso a Paso
| Paso | Descripción | Estado |
|------|-----------|--------|
| 1 | Crear archivo `plan.md` | ✅ Completado |
| 2 | Actualizar `index.html` con cambios estructurales y de contenido | ✅ Completado |
| 3 | Modificar `css/styles.css` (variables, cards, botones, casos) | ✅ Completado |
| 4 | Editar `js/scripts.js` (scroll suave, animaciones, menú móvil) | ✅ Completado |
| 5 | Revisar y previsualizar el sitio en navegador | ⏳ Pendiente |
| 6 | Ajustar posibles inconsistencias de maquetado | ⏳ Pendiente |
| 7 | Finalizar y confirmar funcionamiendo de enlaces | ⏳ Pendiente |

## 5. Entregables
| Archivo | Estado |
|---------|--------|
| `index.html` | ✅ Completado |
| `css/styles.css` | ✅ Completado |
| `js/scripts.js` | ✅ Completado |
| `plan.md` | ✅ Actualizado |  

## 6. Plazos Estimados
| Etapa | Tiempo estimado |
|-------|-----------------|
| Preparación y revisión del plan | 0.5 día |
| Actualización de `index.html` | 1 día |
| Ajustes de estilos en `styles.css` | 1 día |
| Implementación de JS y pruebas | 0.5 día |
| Revisión final y ajustes | 0.5 día |
| **Total** | **≈ 3 días** |

## 7. Consideraciones Adicionales
- **SEO**: Incluir palabras clave relacionadas con “SaaS”, “soporte IT externalizado”, “consultoría tecnológica” en meta tags y contenido.  
- **Accesibilidad**: Garantizar contraste adecuado entre texto y fondo; usar `aria-label` en el navbar y botones.  
- **Rendimiento**: Optimizar imágenes del hero y de la sección de casos de éxito (formato WebP, dimensiones adecuadas).  

---  
*Este plan está listo para ser ejecutado una vez aprobado. Se procederá a la creación/actualización de los archivos según lo descrita.*