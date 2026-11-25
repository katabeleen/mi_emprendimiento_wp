# Análisis de Rendimiento con Lighthouse (Móvil)

* **URL analizada:** `https://kataatejidos.infinityfree.me/` (redirigida internamente a `https://kataatejidos.infinityfree.me/?i=2` durante la prueba)
* **Dispositivo:** Móvil (Mobile)
* **Fecha de medición:** 25 de noviembre de 2026

## 1. Resultados obtenidos
| Categoría | Puntaje |
|---|---|
| **Rendimiento (Performance)** | **85** / 100 |
| **Accesibilidad (Accessibility)** | **96** / 100 |
| **Buenas prácticas (Best Practices)** | **92** / 100 |
| **SEO** | **92** / 100 |

> *Nota del informe:* Lighthouse indicó que la URL de prueba (`?i=1`) fue redirigida a `https://kataatejidos.infinityfree.me/?i=2`, un comportamiento habitual de los servidores gratuitos de InfinityFree al validar el acceso del navegador.

*(Puedes agregar aquí tu captura de pantalla del informe de Lighthouse)*

## 2. Análisis de los resultados
* **Accesibilidad (96), Buenas prácticas (92) y SEO (92):** Se encuentran en rango verde con puntajes altos, lo que refleja una buena estructura semántica, legibilidad y configuración base adecuada en el sitio.
* **Rendimiento (85):** Es el puntaje más bajo de las cuatro categorías, principalmente por las limitaciones propias del hosting gratuito (tiempos de respuesta y redirección del servidor) y la carga de recursos del tema y fuentes/estilos. Aun así, mantenerse en 85 es un buen resultado para un entorno gratuito.

## 3. Mejoras aplicadas y propuestas
1. **Optimización de imágenes y textos alternativos:** Convertir las fotografías de tejidos y amigurumis a formatos livianos (como WebP), ajustar su tamaño al espacio real en pantalla y revisar que todas tengan texto alternativo (`alt`) descriptivo para reducir el peso de carga y sostener la accesibilidad.
2. **Reducción de carga del servidor y caché:** Al migrar a un hosting profesional en la Etapa 2 (evitando redirecciones y límites de recursos de hosting gratuito) y activar un plugin de caché, se puede mejorar el tiempo de respuesta inicial y acercar **Rendimiento** a la zona verde (90+).
