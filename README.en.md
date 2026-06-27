# 🧩 Prompt Studio — v0.5 beta

[中文](README.md) · **English**

> Bilingual (中/EN) single-file prompt generator for LLMs, agents & image models · 88 templates + composable dictionary · runs locally, nothing uploaded

A prompt generator for multiple AI models and agents. A single static HTML file — **just open `index.html` in a browser**: no install, no network, nothing leaves your machine.

---

## Features

- **Six categories**: General LLM, 🎭 Role Library, Coding Agent, Automation Agent, Image/Multimodal, Prompt Engineering
- **88 bilingual templates**, adapted from top GitHub repos (including 38 mainstream roles)
- **Prompt dictionary**: clickable bilingual chips under each field (tone/length/format, image style·light·lens·params, coding dev/maintenance/testing rules…) — combine freely
- **One-click CN/EN switch**: UI, templates, dictionary, output, and usage notes are all bilingual
- **Three output levels**: Lite / Standard / Detailed
- **Import & customize**: paste natural language or a rough prompt → auto-parsed into a structured custom version; or generate a "refine instruction" to hand to any AI
- **My Templates**: save / favorite locally (localStorage), survives reload
- **Export engineering formats**: promptfoo YAML test config, DSPy code snippet
- Variable placeholders, scenario search, one-click copy, download .md, usage notes, version badge

---

## Quick Start

1. Unzip and open `index.html` in a modern browser.
2. Pick a target type → pick a scenario template (or use "Import & Customize") → combine chips under each field → fill `{variables}` → choose a level → generate.
3. Copy / download the result, or export to promptfoo / DSPy.

> The version badge next to the title shows the current version (should be **v0.5 beta**).

---

## Docs

- **`USAGE.md`** — detailed guide: global vs. project usage, and the dev/maintenance/testing rules to follow
- **`CHANGELOG.md`** — version changelog
- **`DEVLOG.md`** — development log (process, decisions, problems & fixes)
- **`NOTICE.md`** — copyright & attribution (originality statement, source licenses)
- **`LICENSE`** — MIT License

---

## Extending

All content lives in the `<script>` of `index.html`; extend by editing data, no logic changes needed:

- `CATS` — categories & field definitions
- `TPL` — scenario templates (grouped by category, each bilingual)
- `DICT` — prompt dictionary snippet library
- `SPECS` — per-category usage notes
- `I18N` — UI strings

---

## Sources

- f/awesome-chatgpt-prompts (prompt content, CC0) · CHENJIAMIAN/awesome-chatgpt-prompts-zh-CN · NeekChaw/awesome-prompt
- PatrickJS/awesome-cursorrules (CC0)
- langGPTai/LangGPT · stanfordnlp/DSPy · promptfoo · prompt-optimizer (structure/format only)
- altryne/awesome-ai-art-image-synthesis

See `NOTICE.md` for the full originality & license statement.

---

Static single file · data stays in your local browser, nothing is uploaded.
