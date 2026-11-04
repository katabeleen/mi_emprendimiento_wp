# Decisiones del sitio web

## 1. Plugins

| Funcionalidad | Plugin | Gratis / Pago | Versión de WP compatible | ¿Funciona con tema propio? | Enlace a ficha oficial |
|---|---|---|---|---|---|
| **SEO** (Optimización para motores de búsqueda) | Yoast SEO | Gratis (Versión Premium de pago ofrece actualizaciones o soporte comercial) | Probado hasta 7.1.4 | Sí | [Ficha en WordPress.org](https://wordpress.org/plugins/wordpress-seo/) |
| **Contacto** (Formulario de contacto) | WPForms | Gratis (Versión Lite gratuita, versión Pro de pago con funciones avanzadas) | Probado hasta 7.14 | Sí | [Ficha en WordPress.org](https://wordpress.org/plugins/contact-form-7/) |
| **Seguridad y Respaldos** | UpdraftPlus | Gratis (Versión Premium incluye almacenamiento en más nubes y migración) | Probado hasta 7.1.4 | Sí | [Ficha en WordPress.org](https://wordpress.org/plugins/updraftplus/) |
| **Anti-Spam** | Akismet Spam Protection | Gratis para uso personal (Planes de pago para empresas) | Probado hasta 7.1.4 | Sí | [Ficha en WordPress.org](https://wordpress.org/plugins/akismet/) |
| **Redes Sociales** | Smash Balloon Social Photo Feed | Gratis (Versión Pro agrega más estilos y soporta reels/historias) | Probado hasta 7.1.4 | Sí | [Ficha en WordPress.org](https://wordpress.org/plugins/instagram-feed/) |

---

## 2. Páginas de la Fase 1

### Páginas seleccionadas:
1. **Inicio (Home):** Elegida porque es la página principal que presenta la propuesta de valor de la marca a los visitantes.
2. **Contacto:** Elegida para brindar un canal directo donde los clientes puedan enviar mensajes o consultas a través del formulario.
3. **Nosotros:** Elegida para generar confianza informando la historia, misión y equipo detrás del emprendimiento.
4. **Servicios / Productos (Catálogo informativo):** Elegida para mostrar lo que se ofrece detalladamente sin incluir carro de compras aún.
5. **Preguntas Frecuentes (FAQ):** Elegida para responder rápidamente dudas recurrentes sobre tiempos de respuesta, despachos o atención.

> **Páginas diferidas para fases posteriores:** Carrito de Compras, Finalizar Compra (Checkout), Mi Cuenta y Políticas de Devolución.

---

## 3. Plan del Tema

* **Nombre del tema:** `kataatejidos`
* **Tipo de tema:** **Custom (Tema propio)**. Se eligió un tema propio para tener control total sobre el código, estilos en CSS y estructura sin exceso de código no utilizado.

### Carta Gantt (5 al 25 de Noviembre)

| Etapa | Fechas | Entregable / Hito |
|---|---|---|
| Identidad visual y estructura base de tema | 05 nov - 08 nov | Archivos `index.php`, `style.css` y paleta de colores lista |
| Maquetación de la Home e Inicio | 09 nov - 12 nov | Página de inicio maquetada y responsiva |
| Maquetación de páginas internas | 13 nov - 17 nov | Páginas de Contacto, Nosotros, Servicios y FAQ listas |
| **Checkpoint de revisión** | **Miércoles 18 nov** | **Revisión de avances y corrección de `decisiones.md`** |
| Instalación y configuración de Plugins | 19 nov - 21 nov | Formulario de contacto, SEO y Anti-Spam probados |
| Pruebas, ajustes de diseño e integración | 22 nov - 24 nov | Corrección de errores y prueba responsiva en móviles |
| **Entrega Final** | **Miércoles 25 nov** | **Sitio terminado y desplegado** |

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title Plan de Desarrollo del Sitio
    section Etapas
    Identidad Visual y Tema Base :2026-11-05, 4d
    Home y Maquetación           :2026-11-09, 4d
    Páginas Internas             :2026-11-13, 5d
    Checkpoint                   :milestone, 2026-11-18, 1d
    Configuración de Plugins     :2026-11-19, 3d
    Ajustes y Pruebas            :2026-11-22, 3d
    Entrega Final                :milestone, 2026-11-25, 1d

## 4. Plan B

| Riesgo | Qué hago para resolverlo | Cuándo se activa |
|---|---|---|
| Que los estilos de CSS en mi tema propio no se apliquen bien o se rompa el diseño en celulares. | Revisaré la estructura en el archivo style.css o usaré un plugin temporal de estilos CSS personalizados. | Si el diseño falla al revisar la vista móvil antes del 18 de noviembre. |
| Que el plugin de formulario de contacto falle o no entregue los avisos correctamente. | Instalaré otro plugin alternativo de contacto o configuraré un mensaje visual directo en pantalla para el usuario. | Si las pruebas de envío fallan durante la semana de pruebas. |
| Que me quede atascada con la programación o estructura PHP de las plantillas de WordPress. | Consultaré la guía del curso, pediré apoyo en la clase de taller o usaré una estructura base limpia de respaldo. | Si paso más de un día bloqueada con el código de un archivo. |
