# conteudo-ao-cliente

**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

[![Del contenido al cliente](guia/assets/banner-es.jpg)](https://linnoff88-dev.github.io/

## QuêÂ© es

Esta pêÂ¡gina reêÂºne cinco piezas que ya existen por separado en ARCKHê y muestra cêÂ³mo encajan. Son cuatro herramientas gratuitas que funcionan en la terminal de tu computadora con la ayuda de Claude Code (un asistente de IA que trabaja allêÂ­), y un curso corto. Sirven para quienes crean contenido (a solas o en una empresa pequeêÂ±a) y se pierden entre elegir el tema, producir, publicar y responder. Cada pieza se ocupa de una etapa: encontrar el tema del dêÂ­a, ver quêÂ© ya funcionêÂ³ en tus canales, armar el carrusel, entregar el material a quienes comentan y delegar el resto de la rutina a un agente. Cada una tiene su guêÂ­a y funciona por separado. Puedes usar una sola o las cinco juntas.

## ê°Å¸ââ GuêÂ­a de uso

PêÂ¡gina completa (quêÂ© hace cada pieza + paso a paso): **https://linnoff88-dev.github.io/

## Las 5 piezas

| # | Pieza | QuêÂ© hace | GuêÂ­a |
|---|---|---|---|
| 1 | ê°Å¸âÂ¡ radar-pautas | Lee ~20 sitios de noticias sobre IA y devuelve los 6 temas mêÂ¡s relevantes del dêÂ­a, con el enlace verificado | [guêÂ­a](https://linnoff88-dev.github.io/ |
| 2 | ê°Å¸âË muse-canais | Encuentra los videos recientes de tus canales de YouTube que superan 2êâ su rendimiento habitual y propone 8 ideas | [guêÂ­a](https://linnoff88-dev.github.io/ |
| 3 | ê°Å¸âÂ¼ê¯Â¸Â carrossel-ARCKHê | Skill de Claude Code: portada, diapositivas, êÂ«comenta PALABRAêÂ» y 3 stories en el tamaêÂ±o correcto | [guêÂ­a](https://linnoff88-dev.github.io/ |
| 4 | ê°Å¸âÂ¬ lead-comenta | PêÂ¡gina del material gratuito para quienes comentan + textos de respuesta listos | [guêÂ­a](https://linnoff88-dev.github.io/ |
| 5 | ê°Å¸Â§Â¹ Curso | Delega el trabajo pesado a un agente: 8 clases, por chat o por terminal | [curso](https://linnoff88-dev.github.io/ |

## El proceso, de principio a fin

| Paso | QuêÂ© | Comando | QuiêÂ©n lo hace |
|---|---|---|---|
| 1 | Encontrar el tema del dêÂ­a | `python3 radar.py --dry` (en radar-pautas) | ê¢Å¡â¢ê¯Â¸Â script |
| 2 | Ver quêÂ© ya funcionêÂ³ | `python3 muse.py --ideias` (en muse-canais) | ê¢Å¡â¢ê¯Â¸Â script + ê°Å¸Â¤â Claude Code |
| 3 | Crear el carrusel | Pedirlo a Claude Code con la skill carrossel-ARCKHê activada | ê°Å¸Â¤â Claude Code |
| 4 | Revisar las diapositivas | `python3 scripts/checa.py <pasta> <roteiro.json>` | ê¢Å¡â¢ê¯Â¸Â script |
| 5 | Preparar el material para quienes comentan | `python3 lead.py nova PALAVRA --tema "..." --fonte <url>` | ê°Å¸Â¤â Claude Code |
| 6 | Aprobar y publicar | Revisas todo y lo publicas | ê°Å¸Â§Â  têÂº |
| 7 | Delegar la rutina | Seguir el curso trabalho-chato-ao-agente | ê°Å¸Â§Â  têÂº |

Este repositorio contiene solo la pêÂ¡gina. El cêÂ³digo de cada herramienta estêÂ¡ en su propio repositorio.

---

[ARCKHê AI](https://ARCKHê AI)
