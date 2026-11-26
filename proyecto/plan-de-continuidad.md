# Plan de continuidad · Etapa 2 de mi sitio

**Emprendimiento:** kataatejidos
**Sitio de la etapa 1:** https://kataatejidos.infinityfree.me/
**Fecha:** 25 de noviembre de 2026

## 1. Qué quedó fuera de la etapa 1 y por qué (3 pts)

| Funcionalidad | Por qué quedó fuera (tiempo, recursos, costo, conocimientos) | Qué aporta a mi emprendimiento |
|---|---|---|
| Tienda online y carrito de compras con WooCommerce | Tiempo de alcance de la Etapa 1, configuración de pagos/envíos y priorización de una base informativa y de contacto primero | Permite vender tejidos y amigurumis de forma directa y automatizada en línea |
| Envío de correos confiable desde el formulario de contacto | Restricciones de envío de correo saliente en el hosting gratuito (InfinityFree), donde se muestra confirmación en pantalla pero no llega el correo a la bandeja | Asegura recibir consultas y pedidos de clientes sin perder mensajes |
| Catálogo detallado de productos y patrones con filtros | Tiempo de carga de imágenes y estructuración de fichas de productos en esta primera entrega | Facilita que los clientes comparen modelos, tallas o colores de tejidos |

## 2. Recursos que necesito (2 pts)

| Funcionalidad | Plugin o herramienta | Gratis o de pago | Costo aproximado | Qué tendría que aprender |
|---|---|---|---|---|
| Tienda online y gestión de pedidos | WooCommerce | Gratis (base) / complementos de pago opcionales | USD $0 base (posibles costos en pasarelas o extensiones) | Configurar productos, stock, envíos y métodos de pago en WordPress |
| Envío seguro de correos del formulario | Plugin SMTP (ej. WP Mail SMTP) + cuenta SMTP/correo del dominio | Gratis (versión base) / plan de correo o hosting | Bajo / según plan de hosting o correo | Conectar credenciales SMTP, remitente y revisar entrega sin caer en spam |
| Optimización de imágenes y caché | Plugin de caché/optimización (ej. LiteSpeed Cache o similar) y compresor de imágenes | Gratis (versión base) | USD $0 | Ajustar caché, compresión WebP y pruebas de velocidad sin romper estilos |

**Servidor:** Para la Etapa 2 necesitaría un hosting web de pago o plan más estable que el gratuito actual, con buen espacio en disco para fotografías de tejidos, versión de PHP compatible y actualizada con WordPress/WooCommerce, base de datos MySQL sin límites estrictos de conexiones, certificado SSL (HTTPS) activo y soporte para envío de correo/SMTP.

## 3. Priorización y cronograma (2 pts)

| Prioridad | Qué hago | Cuándo (mes o semana) | Resultado esperado |
|---|---|---|---|
| 1 | Resolver el envío real de correos del formulario (SMTP/correo) y respaldar el sitio con UpdraftPlus | Semana 1 | Consultas de contacto llegando de forma confiable y respaldo completo listo |
| 2 | Migrar a un servidor con SSL, buen rendimiento y base estable, optimizando imágenes | Semana 2 | Sitio más rápido, sin redirecciones de servidor gratuito y listo para crecer |
| 3 | Instalar y configurar WooCommerce, productos de *kataatejidos* y pruebas de compra | Semanas 3 y 4 | Tienda funcional operativa para recibir pedidos de la Etapa 2 |

## 4. Riesgos y mitigación (1 pt)

| Riesgo | Qué haría | Cuándo se activa |
|---|---|---|
| El correo del formulario sigue sin llegar o cae en spam por limitaciones del servidor gratuito | Configurar SMTP autenticado o migrar a un hosting con correo funcional y probar en bandeja de entrada y spam | Al probar formularios en producción o tras cambios de servidor |
| Un plugin o actualización de WooCommerce rompe el diseño del tema OceanWP o ralentiza el sitio | Hacer respaldo previo con UpdraftPlus, activar un plugin a la vez y revisar en vista móvil y escritorio | Al instalar o actualizar plugins y temas |
| El costo de hosting, dominio o complementos supera lo presupuestado para el emprendimiento | Comparar planes esenciales, partir con herramientas gratuitas base y priorizar solo lo indispensable para vender | Al contratar hosting/servicios de la Etapa 2 |
