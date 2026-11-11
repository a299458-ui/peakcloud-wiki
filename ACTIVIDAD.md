# Herramientas gratuitas para crear y publicar una wiki o sitio web

**Materia:** Proyectos Profesionales 2  
**Proyecto:** PeakCloud  
**Estudiante:** Dania Cecilia Saldaña Robles  
**Universidad:** Universidad Autónoma de Chihuahua  
**Fecha de consulta:** 5 de noviembre de 2026

## Introducción

Para un proyecto de software, una wiki o sitio web sirve como punto de consulta para explicar qué problema atiende el sistema, qué módulos incluye y cómo va avanzando. También ayuda a compartir subproductos como cronogramas, diagramas, especificaciones y evidencia de pruebas. Para PeakCloud preparé un sitio estático de documentación con información tomada del segundo avance, cuyo corte es el 27 de octubre de 2026.

## Herramientas revisadas

| Herramienta | Qué ofrece | Ventajas para PeakCloud | Consideraciones |
|---|---|---|---|
| **GitHub Pages** | Publica sitios estáticos directamente desde un repositorio GitHub. El plan gratuito permite Pages para repositorios públicos. | El contenido vive junto al código; permite llevar historial de cambios y publicar documentación hecha en HTML, Markdown o generadores estáticos. | Hay que tener una cuenta y familiarizarse un poco con repositorios y configuración. Un sitio estático no ejecuta por sí mismo el sistema PeakCloud ni su base de datos. |
| **Google Sites** | Editor visual en navegador y publicación desde la opción “Publicar”. | Es fácil para empezar, permite armar páginas sin programar y compartirlas con otras personas. Puede servir para una presentación informativa. | La documentación queda en el editor de Sites, separada del historial del código; el diseño y estructura son más guiados. |
| **Notion Sites** | Permite publicar una página de Notion en la web y usar páginas enlazadas como una documentación tipo wiki. | Es cómodo para redactar, actualizar y enlazar notas y entregables sin escribir código. | La publicación depende de la cuenta y funciones disponibles de Notion; personalizar una web y versionar junto al código es menos directo. |

Las funciones y condiciones de los planes pueden cambiar; antes de publicar conviene revisar la documentación oficial enlazada en las referencias.

## Herramienta elegida: GitHub Pages

Elegí **GitHub Pages** para PeakCloud porque el proyecto es de desarrollo de software. La documentación puede vivir en el mismo repositorio del código, así el equipo puede revisar cambios, recuperar versiones anteriores y actualizar la wiki conforme cambien los módulos o las pruebas. Además, Pages publica archivos estáticos desde el repositorio y está disponible con GitHub Free cuando el repositorio es público (GitHub, s. f.-a; GitHub, s. f.-b).

El sitio que preparé usa HTML y CSS, no requiere instalar un sistema de gestión de contenidos y se adapta a celular y computadora. La página explica el propósito, módulos, entregables y estado del proyecto. **No es la aplicación PeakCloud en funcionamiento**: es documentación pública. Si se usa un repositorio público, antes de subirlo hay que quitar contraseñas, tokens, datos reales de clientes y cualquier información interna.

## Subproductos incluidos en la wiki

- **Resumen del producto:** sistema para apoyar la operación de un gimnasio.
- **Mapa de módulos:** clientes, membresías y pagos, asistencias, reservaciones, inventario y reportes. Se mencionan también las funciones complementarias de asistencia QR y consultas de nutrición y fisioterapia reportadas en el avance.
- **Resumen del avance:** el documento del 27 de octubre de 2026 reporta desarrollo e integración terminados, Inventario y Reportes al 100 %, pruebas iniciadas parcialmente y las etapas de implementación y cierre aún programadas.
- **Seguimiento de entregables:** planeación, integración, pruebas, implementación y cierre con etiquetas de estado tomadas del reporte.

Los estados se presentan como un resumen del segundo avance académico; no se agregaron resultados nuevos. El reporte indica que faltaba incluir evidencia directa de la ejecución de la prueba de registro de clientes, así que la wiki lo aclara en lugar de mostrarlo como evidencia ya adjunta.

## Pasos seguidos para preparar y publicar el sitio

1. **Revisé el segundo avance de PeakCloud** para identificar el objetivo del sistema, sus módulos, subproductos y el estado reportado al 27 de octubre de 2026.
2. **Comparé tres opciones gratuitas** —GitHub Pages, Google Sites y Notion Sites— tomando en cuenta facilidad, colaboración, publicación y relación con un proyecto de software.
3. **Elegí GitHub Pages** por su integración con el repositorio y el historial de cambios.
4. **Organicé la información en secciones**: presentación, descripción, módulos, entregables, estado, ficha y referencias.
5. **Preparé el sitio** como `index.html` con una hoja de estilos `styles.css`, diseño adaptable a móvil y enlaces de navegación.
6. **Revisé el contenido contra el avance** para no presentar como terminadas actividades que seguían pendientes ni inventar resultados de pruebas.
7. **Para publicarlo**, crea un repositorio nuevo en GitHub, sube `index.html` y `styles.css` a la raíz, abre **Settings → Pages**, elige la rama principal y la carpeta raíz como fuente, guarda y espera a que GitHub genere la URL. La guía oficial señala que la publicación inicial puede tardar varios minutos (GitHub, s. f.-a).
8. **Comparte el enlace publicado** y actualiza los archivos cuando haya nuevos avances. Antes de hacer público el repositorio, revisa que no incluya datos personales de clientes, claves o información confidencial.

Los pasos 1 a 6 corresponden a la preparación de los archivos incluidos en esta carpeta. Los pasos 7 y 8 son la guía para publicarlos en una cuenta de GitHub; la página todavía no está alojada en una URL pública.

## Conclusiones

Investigar estas herramientas ayudó a ver que una wiki no solo sirve para presentar bonito un proyecto: también puede mantener organizadas sus decisiones y avances. Google Sites y Notion Sites facilitan crear páginas sin programar; GitHub Pages requiere aprender un poco sobre repositorios, pero encaja mejor con PeakCloud porque el proyecto ya consiste en construir software y su documentación puede evolucionar junto con el código.

La wiki preparada resume con claridad qué busca resolver PeakCloud, qué módulos tiene y en qué punto estaba al corte del segundo avance. También deja visible que las pruebas, implementación y cierre seguían pendientes, por lo que el contenido debe actualizarse cuando se complete cada etapa. Tener esta información en un solo lugar puede facilitar la comunicación del equipo y la revisión del proyecto por parte de la docente.

## Referencias (formato APA 7.ª edición)

Google. (s. f.). *Crear, nombrar, eliminar o copiar un sitio*. Ayuda de Google Sites. https://support.google.com/sites/answer/98081?hl=es

GitHub. (s. f.-a). *Quickstart for GitHub Pages*. GitHub Docs. https://docs.github.com/en/pages/quickstart

GitHub. (s. f.-b). *What is GitHub Pages?* GitHub Docs. https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages

Notion. (s. f.-a). *Notion Sites availability & pricing*. Notion Help Center. https://www.notion.com/help/notion-sites-availability-and-pricing

Notion. (s. f.-b). *Publish a website with Notion Sites*. Notion Help Center. https://www.notion.com/help/public-pages-and-web-publishing

Saldaña Robles, D. C. (2026, 27 de octubre). *Segundo avance del desarrollo de PeakCloud* [Reporte académico de la materia Proyectos Profesionales 2]. Universidad Autónoma de Chihuahua.
