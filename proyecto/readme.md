# kataatejidos · Sitio WordPress

> **Este README es tuyo.** Complétalo mientras construyes tu sitio y borra las instrucciones entre paréntesis. Las instrucciones del proyecto están en [`indicaciones/README.md`](indicaciones/README.md).

- **Sitio en producción:** [https://kataatejidos.infinityfree.me/]
- **Prototipo en Stitch:** [https://stitch.google.com/projects/6254953640441361299]
- **Repo del Parcial 02:** [https://github.com/katabeleen/mi-emprendimiento.git]
- **Autor/a:** Katalina Alvarado · MKA1203

## Contexto de la web

*kataatejidos* es un emprendimiento enfocado en tejidos y creaciones artesanales (como tejidos y amigurumis) dirigido a personas que buscan piezas hechas a mano, cercanas y con identidad propia. El sitio web presenta el emprendimiento, muestra su propuesta y permite que las personas interesadas conozcan el proyecto y se pongan en contacto fácilmente. Al llegar al sitio, busco que la visita explore las secciones, entienda el valor de los tejidos y envíe consultas o solicitudes de contacto.

## Mi tema

- [ ] **Tema propio:** `(no aplica)`
- [x] **Tema descargado:** OceanWP · https://wordpress.org/themes/oceanwp/

## Instrucciones si uso un tema descargado

### Requisitos del tema

| Dato | Mi tema |
|---|---|
| Nombre y enlace a la ficha | OceanWP — https://wordpress.org/themes/oceanwp/ |
| Gratis o de pago | Gratis (versión base en WordPress.org, con extensiones opcionales de pago) |
| Tipo (clásico o de bloques) | Clásico |
| Versión de WordPress que requiere | WordPress 5.0 o superior (se recomienda versión actual) |
| Versión de PHP que requiere | PHP 7.4 o superior (se recomienda 8.x) |
| Plugins que necesita (si alguno) | Ocean Extra (recomendado para opciones del tema) y los plugins funcionales del sitio |
| Licencia | GPLv2 o posterior |

### Cómo llevar mi sitio de Local a producción

Para pasar el sitio desde el entorno local a producción en InfinityFree (`https://kataatejidos.infinityfree.me/`), se trabaja con un plugin de respaldo/migración o exportación de contenidos y configuración de WordPress:

- **Plugin de migración que uso:** (indica el plugin que usaste, ej. All-in-One WP Migration o UpdraftPlus, y su enlace en WordPress.org). Gratis o de pago: Gratis (versión base). Límites que tiene: puede tener límite de tamaño de subida o tiempo de ejecución en hosting gratuito.
- **Qué se exporta:** Entradas, páginas, imágenes, menús y configuración general del sitio.

Pasos:

1. **En Local:** Exportar el respaldo o paquete del sitio desde el panel de WordPress usando el plugin seleccionado.
2. **En producción:** Instalar WordPress en el servidor (InfinityFree), activar el tema OceanWP y los plugins necesarios.
3. **Importa:** Subir y restaurar/importar el respaldo en WordPress (o configurar páginas, menús, estilos y ajustes).
4. **Revisa:** Revisar enlaces permanentes, menú de navegación, página de inicio, carga de imágenes, pie de página y formulario de contacto.
5. **Problemas que tuve y cómo los resolví:** Se ajustó el ancho de los campos del formulario y la distribución del pie de página con CSS adicional, y se verificó que en el hosting gratuito el formulario muestra confirmación en pantalla aunque el correo de prueba no llega a la bandeja por restricciones del servidor gratuito.

---

## Respaldo y reinstalación en otro servidor

**Qué respaldar:**

- Los archivos de WordPress (tema OceanWP, plugins, imágenes subidas y CSS/ajustes).
- La base de datos (páginas, entradas, menús, formularios y configuración).

**Cómo respaldo mi sitio:** Generando respaldos periódicos de archivos y base de datos mediante plugin en WordPress (y/o descarga manual de respaldo), guardando una copia segura fuera del servidor antes de cambios importantes o actualizaciones.

**Cómo lo reinstalo en un servidor nuevo:**

1. **Requisitos del servidor:** Hosting con soporte para PHP actual, base de datos MySQL, certificado SSL (HTTPS), soporte de correo/SMTP y espacio suficiente para imágenes.
2. **Instalar WordPress limpio:** Instalar WordPress en el nuevo hosting y configurar la conexión a la base de datos.
3. **Restaurar el respaldo:** Instalar el plugin de respaldo/migración y restaurar el paquete o archivos y base de datos.
4. **Ajustar:** Actualizar URL del sitio si corresponde, guardar **Ajustes > Enlaces permanentes**, revisar menú principal, asignar portada y comprobar el tema OceanWP.
5. **Probar:** Verificar que carguen la portada, páginas, entradas e imágenes, y probar el formulario de contacto (incluyendo envío vía SMTP en el nuevo entorno).

**Problemas que tuve y cómo los resolví:** Las limitaciones del hosting gratuito (como redirecciones internas y restricción en el envío de correos salientes) se documentaron para abordarlas con configuración SMTP o un servidor con mejores prestaciones en la Etapa 2.

## Plugins instalados

| Plugin | Para qué lo uso | Gratis o de pago | Versión |
|---|---|---|---|
| Contact Form 7 | Formulario de contacto del sitio | Gratis | (revisa la versión en tu panel de WP) |
| (Plugin SEO si instalaste) | Optimización SEO básica en WordPress | Gratis | (revisa la versión en tu panel de WP) |
| (Plugin de respaldo/migración si usaste) | Respaldo y migración del sitio | Gratis | (revisa la versión en tu panel de WP) |

## Páginas y entradas

- **Páginas:** Inicio, Contacto (y las demás páginas de tu sitio de la Fase 1 — revísalas en *Páginas* de WordPress).
- **Entradas del blog:** (anota aquí los títulos exactos de tus 3 entradas publicadas).

## Cómo me organicé

Mi plan y mi plan B están en [`decisiones.md`](proyecto/decisiones.md). Se trabajó de forma incremental ajustando el diseño del tema OceanWP, el formulario y la documentación del repositorio para la entrega.

## Plan de continuidad y rendimiento

- **Plan de continuidad (etapa 2 de mi web):** [`plan-de-continuidad.md`](proyecto/plan-de-continuidad.md)
- **Análisis de rendimiento con Lighthouse:** [`lighthouse.md`](proyecto/lighthouse.md)

## Uso de IA

- **Asistente de IA:** Apoyo para estructurar la documentación en Markdown, interpretar los resultados de Lighthouse y el comportamiento del formulario en hosting gratuito, y ordenar los pasos para publicar y respaldar el sitio; revisé, ajusté y validé los contenidos con mi sitio y mi repositorio.
