# betoo

AI-powered specialist workflows. Each `/betoo:command` activates a different mode.

## Skills

| Command | What it does |
|---------|-------------|
| `/betoo:review` | Pre-landing code review — structural bugs, race conditions, trust boundaries |
| `/betoo:ship` | One-command shipping — validate, sync, test, review, push, PR |
| `/betoo:qa` | QA testing with real browser — diff-aware, full, quick, regression modes |
| `/betoo:browse` | Headless Chromium (~100ms/command) — navigate, click, screenshot, assert |
| `/betoo:investigate` | Systematic debugger — investigate, analyze, hypothesize, implement |
| `/betoo:retro` | Weekly retrospective — commit analysis, per-person breakdown, trend tracking |
| `/betoo:founder` | Product thinking — challenge premises, expand scope, find the real product |
| `/betoo:plan-eng-review` | Architecture review — data flow, failure modes, test matrix |
| `/betoo:plan-design-review` | Designer's eye — rates dimensions 0-10, fixes to improve |
| `/betoo:design-consultation` | Design system creation — researches space, proposes aesthetic, writes DESIGN.md |
| `/betoo:design-review` | Visual QA — finds spacing issues, interaction problems, fixes with screenshots |
| `/betoo:autoplan` | Auto CEO + design + eng review pipeline |
| `/betoo:document-release` | Post-ship doc updater — cross-references diff against all .md files |
| `/betoo:codex` | OpenAI Codex CLI wrapper — review, challenge, consult modes |
| `/betoo:qa-only` | Report-only QA — finds bugs without fixing them |
| `/betoo:setup-browser-cookies` | Cookie import for authenticated browser testing |

## Data

- State: `${CLAUDE_PLUGIN_DATA}/projects/<slug>/`
- Project-local: `.betoo/` in repo root
