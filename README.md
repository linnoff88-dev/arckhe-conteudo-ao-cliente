# conteudo-ao-cliente

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

[![Do conteÃºdo ao cliente](guia/assets/banner.jpg)](https://linnoff88-dev.github.io/

## O que Ã©

Esta pÃ¡gina junta cinco peÃ§as que jÃ¡ existem separadas no ARCKHÉ e mostra como elas se encaixam. SÃ£o quatro ferramentas gratuitas, que rodam no terminal do seu computador com a ajuda do Claude Code (um assistente de IA que trabalha ali), e um curso curto. Servem para quem cria conteÃºdo (sozinho ou numa empresa pequena) e se perde entre escolher o assunto, produzir, publicar e responder. Cada peÃ§a cuida de uma etapa: achar a pauta do dia, ver o que jÃ¡ funcionou nos seus canais, montar o carrossel, entregar o material para quem comenta e passar o resto da rotina para um agente. Cada uma tem o seu guia e funciona sozinha. VocÃª pode usar uma sÃ³ ou as cinco juntas.

## ðŸ“– Guia de uso

PÃ¡gina completa (o que cada peÃ§a faz + passo a passo): **https://linnoff88-dev.github.io/

## As 5 peÃ§as

| # | PeÃ§a | O que faz | Guia |
|---|---|---|---|
| 1 | ðŸ“¡ radar-pautas | LÃª ~20 sites de notÃ­cias de IA e devolve as 6 pautas mais quentes do dia, com link conferido | [guia](https://linnoff88-dev.github.io/ |
| 2 | ðŸ“ˆ muse-canais | Acha os vÃ­deos recentes 2Ã— acima do normal dos seus canais do YouTube e propÃµe 8 ideias | [guia](https://linnoff88-dev.github.io/ |
| 3 | ðŸ–¼ï¸ carrossel-ARCKHÉ | Skill do Claude Code: capa, slides, "comenta PALAVRA" e 3 stories no tamanho certo | [guia](https://linnoff88-dev.github.io/ |
| 4 | ðŸ’¬ lead-comenta | PÃ¡gina do material grÃ¡tis de quem comenta + textos de resposta prontos | [guia](https://linnoff88-dev.github.io/ |
| 5 | ðŸ§¹ Curso | Entregue o trabalho chato a um agente â€” 8 aulas, pelo chat ou pelo terminal | [curso](https://linnoff88-dev.github.io/ |

## O processo, do inÃ­cio ao fim

| Passo | O quÃª | Comando | Quem faz |
|---|---|---|---|
| 1 | Achar a pauta do dia | `python3 radar.py --dry` (no radar-pautas) | âš™ï¸ script |
| 2 | Ver o que jÃ¡ funcionou | `python3 muse.py --ideias` (no muse-canais) | âš™ï¸ script + ðŸ¤– Claude Code |
| 3 | Fazer o carrossel | pedir ao Claude Code com a skill carrossel-ARCKHÉ ligada | ðŸ¤– Claude Code |
| 4 | Conferir os slides | `python3 scripts/checa.py <pasta> <roteiro.json>` | âš™ï¸ script |
| 5 | Preparar o material de quem comenta | `python3 lead.py nova PALAVRA --tema "..." --fonte <url>` | ðŸ¤– Claude Code |
| 6 | Aprovar e postar | vocÃª olha tudo e publica | ðŸ§  vocÃª |
| 7 | Delegar a rotina | seguir o curso trabalho-chato-ao-agente | ðŸ§  vocÃª |

Este repositÃ³rio tem sÃ³ a pÃ¡gina. O cÃ³digo de cada ferramenta estÃ¡ no repositÃ³rio dela.

---

[ARCKHÉ AI](https://ARCKHÉ AI)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>