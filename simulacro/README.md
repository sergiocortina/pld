# Simulacro Certificación PLD/FT — CNBV 2026

**Publicado en:** https://sergiocortina.github.io/pld/simulacro/ (enlace también en la última slide de la [presentación del curso CANADEVI](../Curso_CANADEVI_Antilavado_2026.html)).

Simulacro de examen **en línea y para celular** de la Prueba de Conocimientos en Materia de Prevención de Lavado de Dinero y Financiamiento al Terrorismo de la CNBV. Mismo formato que describe la *Guía para el Sustentante*:

- Opción múltiple: **4 alternativas, 1 correcta**.
- **Sesión única de 4 horas** con cuenta regresiva.
- **Navegación libre**, mapa de preguntas, **marcar** y **modificar respuestas** antes de terminar (como en el examen real).
- **Calificación inmediata tras cada respuesta**: acierto/error, resaltado de la correcta y **la razón (argumentación)** con base en las fuentes.
- **Resultado final**: % global, **desglose por área** y repaso de las incorrectas.
- Funciona en el celular sin app y **continúa la sesión** si la cierras.

| Configuración | Examen (con calificación inmediata) | Resultados |
|---|---|---|
| ![config](docs/01_configuracion.png) | ![examen](docs/02_examen_feedback.png) | ![resultados](docs/03_resultados.png) |

## Modos

- **Simulacro · 100**: 100 preguntas al azar, equilibradas entre las 3 áreas del temario CNBV (33/33/34).
- **Banco completo · 180**: todas las preguntas (repaso exhaustivo).
- **Calificación inmediata** activada por defecto; puedes apagarla para un examen más fiel (sin ver resultados hasta el final).

## Aclaraciones importantes

- La CNBV **no publica** el número de reactivos ni un porcentaje aprobatorio: califica por **criterio de suficiencia**. Este simulacro usa **70% como referencia de estudio**, no como umbral oficial.
- Es **material de estudio no oficial**: banco de 180 preguntas (114 originales + 66 autoradas) contrastado con DCG, LFPID, GAFI, ENR y tipologías de la UIF. No sustituye al temario ni a la Guía Oficial.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | La app completa (autónoma, con las 180 preguntas embebidas; no necesita servidor) |
| `preguntas.json` | Las 180 preguntas en JSON (para revisar o editar) |
| `docs/*.png` | Capturas de las vistas |

Las fuentes de compilación (plantilla, parser del banco y scripts de validación/tests) viven en el proyecto de la certificación; para regenerar `index.html` se ejecuta el compilador correspondiente y se copia el resultado aquí.
