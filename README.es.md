# conteudo-ao-cliente

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

[![Del contenido al cliente](guia/assets/banner-es.jpg)](https://linnoff88-dev.github.io/

## QuÃ© es

Esta pÃ¡gina reÃºne cinco piezas que ya existen por separado en ARCKHÉ y muestra cÃ³mo encajan. Son cuatro herramientas gratuitas que funcionan en la terminal de tu computadora con la ayuda de Claude Code (un asistente de IA que trabaja allÃ­), y un curso corto. Sirven para quienes crean contenido (a solas o en una empresa pequeÃ±a) y se pierden entre elegir el tema, producir, publicar y responder. Cada pieza se ocupa de una etapa: encontrar el tema del dÃ­a, ver quÃ© ya funcionÃ³ en tus canales, armar el carrusel, entregar el material a quienes comentan y delegar el resto de la rutina a un agente. Cada una tiene su guÃ­a y funciona por separado. Puedes usar una sola o las cinco juntas.

## ðŸ“– GuÃ­a de uso

PÃ¡gina completa (quÃ© hace cada pieza + paso a paso): **https://linnoff88-dev.github.io/

## Las 5 piezas

| # | Pieza | QuÃ© hace | GuÃ­a |
|---|---|---|---|
| 1 | ðŸ“¡ radar-pautas | Lee ~20 sitios de noticias sobre IA y devuelve los 6 temas mÃ¡s relevantes del dÃ­a, con el enlace verificado | [guÃ­a](https://linnoff88-dev.github.io/ |
| 2 | ðŸ“ˆ muse-canais | Encuentra los videos recientes de tus canales de YouTube que superan 2Ã— su rendimiento habitual y propone 8 ideas | [guÃ­a](https://linnoff88-dev.github.io/ |
| 3 | ðŸ–¼ï¸ carrossel-ARCKHÉ | Skill de Claude Code: portada, diapositivas, Â«comenta PALABRAÂ» y 3 stories en el tamaÃ±o correcto | [guÃ­a](https://linnoff88-dev.github.io/ |
| 4 | ðŸ’¬ lead-comenta | PÃ¡gina del material gratuito para quienes comentan + textos de respuesta listos | [guÃ­a](https://linnoff88-dev.github.io/ |
| 5 | ðŸ§¹ Curso | Delega el trabajo pesado a un agente: 8 clases, por chat o por terminal | [curso](https://linnoff88-dev.github.io/ |

## El proceso, de principio a fin

| Paso | QuÃ© | Comando | QuiÃ©n lo hace |
|---|---|---|---|
| 1 | Encontrar el tema del dÃ­a | `python3 radar.py --dry` (en radar-pautas) | âš™ï¸ script |
| 2 | Ver quÃ© ya funcionÃ³ | `python3 muse.py --ideias` (en muse-canais) | âš™ï¸ script + ðŸ¤– Claude Code |
| 3 | Crear el carrusel | Pedirlo a Claude Code con la skill carrossel-ARCKHÉ activada | ðŸ¤– Claude Code |
| 4 | Revisar las diapositivas | `python3 scripts/checa.py <pasta> <roteiro.json>` | âš™ï¸ script |
| 5 | Preparar el material para quienes comentan | `python3 lead.py nova PALAVRA --tema "..." --fonte <url>` | ðŸ¤– Claude Code |
| 6 | Aprobar y publicar | Revisas todo y lo publicas | ðŸ§  tÃº |
| 7 | Delegar la rutina | Seguir el curso trabalho-chato-ao-agente | ðŸ§  tÃº |

Este repositorio contiene solo la pÃ¡gina. El cÃ³digo de cada herramienta estÃ¡ en su propio repositorio.

---

[ARCKHÉ AI](https://ARCKHÉ AI)
