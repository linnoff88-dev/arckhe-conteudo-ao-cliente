# conteudo-ao-cliente

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

[![From content to client](guia/assets/banner-en.jpg)](https://linnoff88-dev.github.io/

## What it is

This page brings together five pieces that already exist separately across ARCKHÉ and shows how they fit together. There are four free tools that run in your computerâ€™s terminal with the help of Claude Code (an AI assistant that works there), plus a short course. Theyâ€™re for people who create contentâ€”on their own or at a small companyâ€”and lose track of things between choosing a topic, producing, publishing, and replying. Each piece handles one step: finding the topic of the day, seeing what has already worked on your channels, building a carousel, delivering the material to people who comment, and handing the rest of the routine to an agent. Each has its own guide and works on its own. You can use just one or all five together.

## ðŸ“– User guide

Full page (what each piece does + step-by-step instructions): **https://linnoff88-dev.github.io/

## The 5 pieces

| # | Piece | What it does | Guide |
|---|---|---|---|
| 1 | ðŸ“¡ radar-pautas | Reads ~20 AI news sites and returns the 6 hottest topics of the day, with verified links | [guide](https://linnoff88-dev.github.io/ |
| 2 | ðŸ“ˆ muse-canais | Finds recent videos on your YouTube channels that are 2Ã— above normal and suggests 8 ideas | [guide](https://linnoff88-dev.github.io/ |
| 3 | ðŸ–¼ï¸ carrossel-ARCKHÉ | Claude Code skill: cover, slides, â€œcomment WORD,â€ and 3 stories in the right dimensions | [guide](https://linnoff88-dev.github.io/ |
| 4 | ðŸ’¬ lead-comenta | Free resource page for people who comment, plus ready-to-use reply messages | [guide](https://linnoff88-dev.github.io/ |
| 5 | ðŸ§¹ Course | Hand the tedious work to an agent â€” 8 lessons, through chat or the terminal | [course](https://linnoff88-dev.github.io/ |

## The process, from start to finish

| Step | What | Command | Who does it |
|---|---|---|---|
| 1 | Find the topic of the day | `python3 radar.py --dry` (in radar-pautas) | âš™ï¸ script |
| 2 | See what has already worked | `python3 muse.py --ideias` (in muse-canais) | âš™ï¸ script + ðŸ¤– Claude Code |
| 3 | Make the carousel | Ask Claude Code with the carrossel-ARCKHÉ skill enabled | ðŸ¤– Claude Code |
| 4 | Check the slides | `python3 scripts/checa.py <pasta> <roteiro.json>` | âš™ï¸ script |
| 5 | Prepare the material for people who comment | `python3 lead.py nova PALAVRA --tema "..." --fonte <url>` | ðŸ¤– Claude Code |
| 6 | Approve and post | You review everything and publish | ðŸ§  you |
| 7 | Delegate the routine | Follow the trabalho-chato-ao-agente course | ðŸ§  you |

This repository contains only the page. Each toolâ€™s code is in its own repository.

---

[ARCKHÉ AI](https://ARCKHÉ AI)
