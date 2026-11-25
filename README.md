# conteudo-ao-cliente

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

[![Do conteêÂºdo ao cliente](guia/assets/banner.jpg)](https://linnoff88-dev.github.io/

## O que êÂ©

Esta pêÂ¡gina junta cinco peêÂ§as que jêÂ¡ existem separadas no ARCKHê e mostra como elas se encaixam. SêÂ£o quatro ferramentas gratuitas, que rodam no terminal do seu computador com a ajuda do Claude Code (um assistente de IA que trabalha ali), e um curso curto. Servem para quem cria conteêÂºdo (sozinho ou numa empresa pequena) e se perde entre escolher o assunto, produzir, publicar e responder. Cada peêÂ§a cuida de uma etapa: achar a pauta do dia, ver o que jêÂ¡ funcionou nos seus canais, montar o carrossel, entregar o material para quem comenta e passar o resto da rotina para um agente. Cada uma tem o seu guia e funciona sozinha. VocêÂª pode usar uma sêÂ³ ou as cinco juntas.

## ê°Å¸ââ Guia de uso

PêÂ¡gina completa (o que cada peêÂ§a faz + passo a passo): **https://linnoff88-dev.github.io/

## As 5 peêÂ§as

| # | PeêÂ§a | O que faz | Guia |
|---|---|---|---|
| 1 | ê°Å¸âÂ¡ radar-pautas | LêÂª ~20 sites de notêÂ­cias de IA e devolve as 6 pautas mais quentes do dia, com link conferido | [guia](https://linnoff88-dev.github.io/ |
| 2 | ê°Å¸âË muse-canais | Acha os vêÂ­deos recentes 2êâ acima do normal dos seus canais do YouTube e propêÂµe 8 ideias | [guia](https://linnoff88-dev.github.io/ |
| 3 | ê°Å¸âÂ¼ê¯Â¸Â carrossel-ARCKHê | Skill do Claude Code: capa, slides, "comenta PALAVRA" e 3 stories no tamanho certo | [guia](https://linnoff88-dev.github.io/ |
| 4 | ê°Å¸âÂ¬ lead-comenta | PêÂ¡gina do material grêÂ¡tis de quem comenta + textos de resposta prontos | [guia](https://linnoff88-dev.github.io/ |
| 5 | ê°Å¸Â§Â¹ Curso | Entregue o trabalho chato a um agente ê¢â¬â 8 aulas, pelo chat ou pelo terminal | [curso](https://linnoff88-dev.github.io/ |

## O processo, do inêÂ­cio ao fim

| Passo | O quêÂª | Comando | Quem faz |
|---|---|---|---|
| 1 | Achar a pauta do dia | `python3 radar.py --dry` (no radar-pautas) | ê¢Å¡â¢ê¯Â¸Â script |
| 2 | Ver o que jêÂ¡ funcionou | `python3 muse.py --ideias` (no muse-canais) | ê¢Å¡â¢ê¯Â¸Â script + ê°Å¸Â¤â Claude Code |
| 3 | Fazer o carrossel | pedir ao Claude Code com a skill carrossel-ARCKHê ligada | ê°Å¸Â¤â Claude Code |
| 4 | Conferir os slides | `python3 scripts/checa.py <pasta> <roteiro.json>` | ê¢Å¡â¢ê¯Â¸Â script |
| 5 | Preparar o material de quem comenta | `python3 lead.py nova PALAVRA --tema "..." --fonte <url>` | ê°Å¸Â¤â Claude Code |
| 6 | Aprovar e postar | vocêÂª olha tudo e publica | ê°Å¸Â§Â  vocêÂª |
| 7 | Delegar a rotina | seguir o curso trabalho-chato-ao-agente | ê°Å¸Â§Â  vocêÂª |

Este repositêÂ³rio tem sêÂ³ a pêÂ¡gina. O cêÂ³digo de cada ferramenta estêÂ¡ no repositêÂ³rio dela.

---

[ARCKHê AI](https://ARCKHê AI)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>