# Claude Code 2.0 en la práctica

[![Claude Code en la práctica](guia/assets/banner-es.jpg)](https://inematds.github.io/claude-code-2/guia/es/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## Qué es

Esta guía presenta, en lenguaje sencillo, las 13 novedades más útiles de Claude Code, el asistente de Anthropic que trabaja con tus archivos y tu computadora. Está dirigida a quienes crean contenido, enseñan o llevan un negocio y quieren usar la IA en el día a día sin saber programar. Cada novedad explica qué resuelve, dónde activarla, qué precaución tener y ofrece un prompt listo para copiar y pegar. Para usarla, basta con la app de Claude en Mac o Windows y un plan pago (Pro, Max o Ultra); algunas novedades todavía están en prueba o solo están disponibles en EE. UU., y la guía lo indica en cada caso.

## 📖 Guía de uso

Guía completa (las 13 novedades, cada una con un prompt listo): **https://inematds.github.io/claude-code-2/guia/es/**

Curso práctico, en 7 lecciones: **https://inematds.github.io/claude-code-2-na-pratica-v72/es/**

## Las 13 novedades

| # | Novedad | Qué hace |
|---|---|---|
| 1 | Secciones por proyecto | Conversaciones, archivos y tareas de cada trabajo en un solo lugar |
| 2 | Side chat | Haz una pregunta rápida al lado (Cmd/Ctrl + ; o `/btw`) sin ensuciar la conversación |
| 3 | Split view | Dos sesiones lado a lado |
| 4 | Ayudantes (subagentes) | Una conversación divide el trabajo y reúne el resultado |
| 5 | Computer use | Claude usa las apps de la computadora (vista previa, Pro/Max/Ultra) |
| 6 | Projects en la nube | El trabajo continúa aunque la computadora esté apagada (beta) |
| 7 | Remote Control | Sigue y aprueba desde el celular (`/remote-control`) |
| 8 | Navegador integrado | Claude usa sitios web por ti (Cmd/Ctrl + Shift + B) |
| 9 | Presentaciones, diseños y paneles | Claude Slides, Design, Dashboards y Motion |
| 10 | Documentos compartidos | Página dinámica que el equipo edita y comenta con @Claude |
| 11 | Comandos de barra | `/rewind`, `/context`, `/recap`, `/goal`, `/output-style` |
| 12 | Mods | Barras, avisos y comandos nuevos (versión 2.1.287+) |
| 13 | Claude Duet | Ayudante que trae las tareas (solo EE. UU., lista de espera) |

Los 13 prompts en texto sin formato, listos para copiar: [`prompts/`](prompts/) (PT, EN, ES).

«Claude Code 2.0» es el apodo del conjunto de novedades de las versiones 2.1.x. Datos verificados en la documentación oficial el 01/11/2026.

## El proceso, de principio a fin

Leyenda: 🧠 sesión con Nei · ⚙️ script/temporizador · 🤖 `claude -p` / subagente

1. 🧠 Pedido de Nei + contenido de origen (se queda solo en local, en `origem/`, fuera de git).
2. 🤖 Verificar cada afirmación en la documentación oficial → `longrun/2026-11-01-claude-code-2/FATOS.md` (repo wifi).
3. ⚙️ Portada y banners con Codex: `longrun/2026-11-01-claude-code-2/gera-imagens.sh`.
4. 🧠 Escribir la guía PT en `guia/index.html` (13 tarjetas reescritas, ejemplos propios, sin citar la fuente).
5. ⚙️ Traducir EN/ES por partes con el traductor central: `python3 -I longrun/2026-11-01-claude-code-2/tools/traduz_guia.py ~/projetos/claude-code-2 en` (y `es`).
6. ⚙️ Extraer los prompts: `python3 -I longrun/2026-11-01-claude-code-2/tools/extrai_prompts.py ~/projetos/claude-code-2`.
7. 🤖 Revisor independiente (agente nuevo) → corregir → calificación en `~/projetos/wifi/scripts/revisor-nota.py`.
8. ⚙️ Publicar: commit + push (autor inematds) → GitHub Pages mediante Actions (`.github/workflows/pages.yml`).
9. 🧠 Curso v7.2 (`claude-code-2-na-pratica-v72`), explicavideo 16:9 + 9:16, rtex 9:16 → lives4, INEMA.CCODE, metritds y portal inema.club.

## Licencia

Contenido abierto y gratuito · [INEMA.CLUB](https://inema.club)