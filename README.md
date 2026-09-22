# Portafolio Profesional — Ivan Palencia
### Data · Software · Analytics

Sitio web profesional y comercial diseñado para presentar capacidades técnicas, proyectos de analítica y desarrollo de software, experiencia profesional y oferta de servicios a reclutadores y clientes empresariales.

El proyecto está construido con una arquitectura **100% estática en HTML5 y CSS3 puro**, sin JavaScript, sin frameworks CSS ni dependencias complejas, optimizado para cargar a la máxima velocidad y desplegarse directamente en **GitHub Pages**.

---

## 🚀 Características Principales

- **Cero JavaScript**: Navegación responsive mediante toggle CSS accesible, sin dependencias externas ni scripts pesados.
- **Storytelling Técnico-Comercial**: Cada proyecto sigue el flujo `Problema → Solución → Tecnologías → Impacto / Resultado`.
- **Estructura Semántica y Accesible**: Cumple buenas prácticas de accesibilidad (WCAG), contraste de color, navegación por teclado y soporte para `@media (prefers-reduced-motion)`.
- **Optimizado para SEO**: Etiquetas Open Graph, meta descriptions estructuradas, URLs canónicas y jerarquía de encabezados limpia.
- **Fácilmente Personalizable**: Secciones claramente delimitadas por comentarios en mayúsculas (`<!-- EDITABLE SECTION -->`) para actualizar datos personales en minutos.

---

## 📁 Estructura del Proyecto

```text
ivanpalenciab.github.io/
├── index.html                           # Estructura semántica principal y contenido
├── css/
│   └── styles.css                       # Hoja de estilos en CSS3 puro (Design tokens, Grid, Flexbox)
├── assets/
│   ├── icons/
│   │   └── favicon.svg                  # Favicon vectorial con monograma IP
│   └── images/
│       ├── ivan.jpg                     # Fotografía profesional de perfil
│       ├── cirkucore-interfaz.png       # Captura de interfaz - Sistema de analítica para la circularidad
│       ├── project-enterprise-analytics.svg
│       ├── project-sustainability-analytics.svg
│       ├── project-predictive-models.svg
│       ├── project-data-apis.svg
│       └── project-agriculture-decision.svg
└── README.md                            # Documentación y guía de despliegue
```

---

## 🌐 Despliegue en GitHub Pages

Al encontrarse el repositorio en una cuenta con nombre de usuario coincidente (`ivanpalenciab/ivanpalenciab.github.io`), GitHub Pages publica automáticamente el sitio en la raíz de tu dominio:

### Pasos para activar el despliegue:

1. **Subir los cambios al repositorio remoto**:
   ```bash
   git add .
   git commit -m "feat: portafolio profesional en HTML5 y CSS3 puro"
   git push origin main
   ```
   *(Si tu rama principal se llama `master`, utiliza `git push origin master`)*.

2. **Configurar GitHub Pages en el repositorio**:
   - Ingresa a tu repositorio en GitHub: `https://github.com/ivanpalenciab/ivanpalenciab.github.io`.
   - Haz clic en la pestaña **Settings** (Configuración).
   - En el menú lateral izquierdo, haz clic en **Pages**.
   - En la sección **Build and deployment**:
     - **Source**: Selecciona `Deploy from a branch`.
     - **Branch**: Selecciona `main` (o `master`) y carpeta `/(root)`.
     - Haz clic en **Save**.

3. **Verificar el sitio en línea**:
   - En pocos segundos o minutos, tu sitio estará activo en:
     **`https://ivanpalenciab.github.io/`**

---

## ✏️ Guía de Personalización Rápida

Para modificar tu información, abre el archivo `index.html` y localiza los siguientes bloques comentados:

| Sección | Marcador en `index.html` | Qué puedes modificar |
| :--- | :--- | :--- |
| **Hero / Perfil** | `<!-- HERO SECTION -->` | Titular, subtítulo, estado de disponibilidad. |
| **Sobre mí** | `<!-- EDITABLE SECTION: SOBRE MÍ -->` | Narrativa profesional, años de experiencia y pilares. |
| **Proyectos** | `<!-- EDITABLE SECTION: PROJECTS -->` | Textos de Problema/Solución/Impacto, badges de tecnologías y enlaces. |
| **Habilidades** | `<!-- EDITABLE SECTION: SKILLS -->` | Agregar o reorganizar chips de herramientas y lenguajes. |
| **Experiencia** | `<!-- EDITABLE SECTION: EXPERIENCE -->` | Cargos, empresas, fechas y logros destacados. |
| **Servicios** | `<!-- EDITABLE SECTION: SERVICES -->` | Servicios ofrecidos y alcance de entregables. |
| **Contacto** | `<!-- EDITABLE SECTION: CONTACT -->` | Correo electrónico (`mailto:`), perfiles de LinkedIn y GitHub. |

### Cómo reemplazar o actualizar imágenes de proyectos:
Puedes sustituir cualquiera de los mockups vectoriales en `assets/images/` por capturas de pantalla reales en formato `.webp`, `.png` o `.jpg`. Simplemente cambia la ruta en el atributo `src` de la etiqueta `<img>` correspondiente dentro de `index.html`:
```html
<img src="assets/images/mi-captura-real.webp" alt="Descripción de la solución" class="project-image" loading="lazy">
```

---

## 🎨 Paleta de Colores

La paleta se encuentra centralizada en las variables CSS al inicio de `css/styles.css`:

- **Azul Primario (Navy)**: `#1e1b4b` / `#343265`
- **Acento Esmeralda**: `#2aa539` / `#15803d`
- **Fondo Principal**: `#f8fafc`
- **Superficie de Tarjetas**: `#ffffff`
- **Texto Principal**: `#0f172a`
- **Texto Secundario**: `#475569`

---

## 📄 Licencia

© 2026 Ivan Palencia. Todos los derechos reservados.
