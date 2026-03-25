# avad

Turn one AI assistant into a team of specialists. Each slash command activates a different mode — review, QA, shipping, design, debugging, and more.

## Install

```
claude plugin add agwacom/avad
```

## Skills

**Ship code:**
- `/avad:review` — Pre-landing code review with structural analysis
- `/avad:ship` — One-command shipping: validate → sync → test → review → push → PR
- `/avad:qa` — QA testing with real browser automation
- `/avad:investigate` — Systematic root-cause debugging

**Plan & design:**
- `/avad:plan-ceo-review` — Product thinking and scope analysis
- `/avad:plan-eng-review` — Architecture, data flow, and test coverage
- `/avad:plan-design-review` — Visual design scoring and improvement
- `/avad:design-consultation` — Create a design system from scratch
- `/avad:autoplan` — Run CEO + design + eng reviews automatically

**Build & maintain:**
- `/avad:browse` — Headless Chromium browser (~100ms/command)
- `/avad:design-review` — Visual QA with screenshot-based fix loop
- `/avad:retro` — Weekly engineering retrospective
- `/avad:document-release` — Post-ship documentation updater
- `/avad:codex` — OpenAI Codex CLI integration

## Requirements

- [Bun](https://bun.sh) or Node.js (for Playwright browser automation)
- Playwright Chromium (installed automatically by `setup`)

## Multi-model

avad skills are designed to work across AI coding assistants. Claude Code is the primary platform, with Codex CLI support planned.

## License

MIT — see [LICENSE](LICENSE)
