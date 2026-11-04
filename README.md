# Claude Code 2.0 na prática

[![Claude Code na prática](guia/assets/banner.jpg)](https://inematds.github.io/claude-code-2/guia/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## O que é

Este guia mostra, em linguagem simples, as 13 novidades mais úteis do Claude Code, o assistente da Anthropic que trabalha nos seus arquivos e no seu computador. É para quem cria conteúdo, ensina ou toca um negócio e quer usar a IA no dia a dia sem saber programar. Cada novidade traz o que ela resolve, onde ligar, um cuidado e um prompt pronto para colar. Para usar, basta o app do Claude no Mac ou no Windows e um plano pago (Pro, Max ou Ultra); algumas novidades ainda estão em teste ou só nos EUA, e o guia avisa em cada uma.

## 📖 Guia de uso

Guia completo (as 13 novidades, com prompt pronto em cada uma): **https://inematds.github.io/claude-code-2/guia/**

Curso com prática, em 7 aulas: **https://inematds.github.io/claude-code-2-na-pratica-v72/**

## As 13 novidades

| # | Novidade | O que faz |
|---|---|---|
| 1 | Seções por projeto | Conversas, arquivos e tarefas de cada trabalho num lugar só |
| 2 | Side chat | Pergunta rápida do lado (Cmd/Ctrl + ; ou `/btw`) sem sujar a conversa |
| 3 | Split view | Duas sessões lado a lado |
| 4 | Ajudantes (subagentes) | Uma conversa divide o trabalho e junta o resultado |
| 5 | Computer use | O Claude usa os apps do computador (prévia, Pro/Max/Ultra) |
| 6 | Projects na nuvem | Trabalho continua com o computador desligado (beta) |
| 7 | Remote Control | Acompanhar e aprovar pelo celular (`/remote-control`) |
| 8 | Navegador embutido | O Claude usa sites por você (Cmd/Ctrl + Shift + B) |
| 9 | Slides, designs e painéis | Claude Slides, Design, Dashboards e Motion |
| 10 | Docs compartilhados | Página viva que a equipe edita e comenta com @Claude |
| 11 | Comandos de barra | `/rewind`, `/context`, `/recap`, `/goal`, `/output-style` |
| 12 | Mods | Faixas, avisos e comandos novos (versão 2.1.287+) |
| 13 | Claude Duet | Ajudante que traz as tarefas (só EUA, lista de espera) |

Os 13 prompts em texto puro, para copiar: [`prompts/`](prompts/) (PT, EN, ES).

"Claude Code 2.0" é o apelido do pacote de novidades das versões 2.1.x. Fatos conferidos na documentação oficial em 01/11/2026.

## O processo, do início ao fim

Legenda: 🧠 sessão com o Nei · ⚙️ script/timer · 🤖 `claude -p` / subagente

1. 🧠 Pedido do Nei + conteúdo de origem (fica só local, em `origem/`, fora do git).
2. 🤖 Conferir cada afirmação na documentação oficial → `longrun/2026-11-01-claude-code-2/FATOS.md` (repo wifi).
3. ⚙️ Capa e banners pelo Codex: `longrun/2026-11-01-claude-code-2/gera-imagens.sh`.
4. 🧠 Escrever o guia PT em `guia/index.html` (13 cartões reescritos, exemplos próprios, sem citar a fonte).
5. ⚙️ Traduzir EN/ES em pedaços pelo tradutor central: `python3 -I longrun/2026-11-01-claude-code-2/tools/traduz_guia.py ~/projetos/claude-code-2 en` (e `es`).
6. ⚙️ Extrair os prompts: `python3 -I longrun/2026-11-01-claude-code-2/tools/extrai_prompts.py ~/projetos/claude-code-2`.
7. 🤖 Revisor independente (agente novo) → corrigir → nota em `~/projetos/wifi/scripts/revisor-nota.py`.
8. ⚙️ Publicar: commit + push (autor inematds) → GitHub Pages por Actions (`.github/workflows/pages.yml`).
9. 🧠 Curso v7.2 (`claude-code-2-na-pratica-v72`), explicavideo 16:9 + 9:16, rtex 9:16 → lives4, INEMA.CCODE, metritds e portal inema.club.

## Licença

Conteúdo aberto e gratuito · [INEMA.CLUB](https://inema.club)
