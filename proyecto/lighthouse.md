# Análisis de rendimiento con Lighthouse

**Sitio analizado:** https://kataatejidos.infinityfree.me/
**Herramienta:** Lighthouse en Chrome
**Dispositivo:** móvil
**Fecha del análisis:** 25 de noviembre de 2026

## 1. Resultados (1 pt)

| Categoría | Puntaje (0 a 100) |
|---|---|
| Rendimiento | 85 |
| Accesibilidad | 96 |
| Buenas prácticas | 92 |
| SEO | 92 |

**Evidencia:** Captura del informe de Lighthouse en Chrome (URL analizada `https://kataatejidos.infinityfree.me/?i=2` tras redirección de prueba).

## 2. Análisis (1 pt)

- **Qué significan mis puntajes:** Rendimiento (85) mide qué tan rápido carga y responde el sitio en móvil; Accesibilidad (96) evalúa qué tan fácil es leer y navegar el sitio para distintas personas; Buenas prácticas (92) revisa aspectos técnicos y de seguridad web; y SEO (92) indica qué tan bien preparada está la página para que los buscadores la entiendan e indexen. En general son puntajes altos y estables para un sitio en hosting gratuito.
- **Mi mejor categoría y por qué:** Accesibilidad (96), porque la estructura de la página, textos y contrastes se mantienen claros y legibles en el análisis.
- **Mi categoría más débil y por qué:** Rendimiento (85), principalmente por las limitaciones de velocidad y redirección interna (`?i=1` a `?i=2`) propias de InfinityFree como hosting gratuito, sumadas a la carga de estilos y recursos del tema en móvil.
- **Problemas que encontré en el informe:** El informe advirtió una redirección previa antes de cargar la página final y tiempos de carga influenciados por el servidor gratuito, además de oportunidades habituales de optimización de imágenes y recursos estáticos en móvil.

## 3. Mejoras (1 pt)

Al menos 2, propuestas o ya aplicadas.

| Mejora | Qué problema resuelve | ¿Aplicada o propuesta? | Resultado (si la aplicaste) |
|---|---|---|---|
| Optimización y compresión de imágenes (formato liviano y tamaño adecuado) | Reduce el peso de las fotografías de tejidos y amigurumis en móvil para acelerar la carga | Propuesta | Pendiente de aplicar en la siguiente iteración |
| Migración a hosting con mejor respuesta y caché en Etapa 2 | Disminuye latencia, redirecciones del servidor gratuito y tiempos de respuesta inicial | Propuesta | Planificada para la Etapa 2 |

> No se evalúa que saques un puntaje alto, sino que entiendas qué mide Lighthouse y qué harías para mejorar. Reconoce los límites del hosting gratuito si influyen en tu resultado.
