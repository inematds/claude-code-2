# Claude Code 2.0 in Practice

[![Claude Code in Practice](guia/assets/banner-en.jpg)](https://inematds.github.io/claude-code-2/guia/en/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## What it is

This guide explains, in plain language, the 13 most useful new features in Claude Code, Anthropic’s assistant that works with your files and computer. It’s for people who create content, teach, or run a business and want to use AI in their day-to-day work without knowing how to code. Each feature explains what it does, where to turn it on, one thing to watch out for, and a ready-to-use prompt. All you need is the Claude app for Mac or Windows and a paid plan (Pro, Max, or Ultra). Some features are still being tested or are available only in the US; the guide notes this for each one.

## 📖 User guide

Complete guide (all 13 features, each with a ready-to-use prompt): **https://inematds.github.io/claude-code-2/guia/en/**

Course with hands-on practice, in 7 lessons: **https://inematds.github.io/claude-code-2-na-pratica-v72/** (EN/ES versions coming soon)

## The 13 new features

| # | Feature | What it does |
|---|---|---|
| 1 | Project sections | Conversations, files, and tasks for each project in one place |
| 2 | Side chat | Ask a quick question on the side (Cmd/Ctrl + ; or `/btw`) without cluttering the conversation |
| 3 | Split view | Two sessions side by side |
| 4 | Helpers (subagents) | One conversation splits up the work and brings the results together |
| 5 | Computer use | Claude uses your computer apps (preview, Pro/Max/Ultra) |
| 6 | Cloud Projects | Work continues while your computer is off (beta) |
| 7 | Remote Control | Follow along and approve from your phone (`/remote-control`) |
| 8 | Built-in browser | Claude uses websites for you (Cmd/Ctrl + Shift + B) |
| 9 | Slides, designs, and dashboards | Claude Slides, Design, Dashboards, and Motion |
| 10 | Shared docs | A living page the team can edit and comment on with @Claude |
| 11 | Slash commands | `/rewind`, `/context`, `/recap`, `/goal`, `/output-style` |
| 12 | Mods | Styles, notifications, and new commands (version 2.1.287+) |
| 13 | Claude Duet | An assistant that brings in tasks (US only, waitlist) |

The 13 prompts in plain text, ready to copy: [`prompts/`](prompts/) (PT, EN, ES).

“Claude Code 2.0” is the nickname for the bundle of new features in versions 2.1.x. Facts verified against the official documentation on 11/01/2026.

## The process, from start to finish

Key: 🧠 session with Nei · ⚙️ script/timer · 🤖 `claude -p` / subagent

1. 🧠 Nei’s request + source material (kept local only, in `origem/`, outside git).
2. 🤖 Check every claim against the official documentation → `longrun/2026-11-01-claude-code-2/FATOS.md` (wifi repo).
3. ⚙️ Cover and banners made with Codex: `longrun/2026-11-01-claude-code-2/gera-imagens.sh`.
4. 🧠 Write the PT guide in `guia/index.html` (13 rewritten cards, original examples, no source cited).
5. ⚙️ Translate EN/ES in chunks with the central translator: `python3 -I longrun/2026-11-01-claude-code-2/tools/traduz_guia.py ~/projetos/claude-code-2 en` (and `es`).
6. ⚙️ Extract the prompts: `python3 -I longrun/2026-11-01-claude-code-2/tools/extrai_prompts.py ~/projetos/claude-code-2`.
7. 🤖 Independent reviewer (new agent) → make corrections → score in `~/projetos/wifi/scripts/revisor-nota.py`.
8. ⚙️ Publish: commit + push (inematds author) → GitHub Pages via Actions (`.github/workflows/pages.yml`).
9. 🧠 v7.2 course (`claude-code-2-na-pratica-v72`), 16:9 + 9:16 explainer video, 9:16 rtex → lives4, INEMA.CCODE, metritds, and the inema.club portal.

## License

Open and free content · [INEMA.CLUB](https://inema.club)