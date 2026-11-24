# 🧠 skills

[![Made with Claude, Codex and DeepSeek](https://img.shields.io/badge/Made_with-Claude_%C2%B7_Codex_%C2%B7_DeepSeek-D97757)](https://portfolio.tjakoen.com/notes/ten-times-zero)
[![License: Apache 2.0](https://img.shields.io/badge/license-Apache_2.0-blue)](LICENSE)
[![Generated](https://img.shields.io/badge/generated-from_portfolio_standards-2ea44f)](https://portfolio.tjakoen.com/skills)

The standards I work by, mounted as skills an agent loads when the task fits. A skill is a small
Markdown file with a line saying **when** to read it, so an agent reaches for the rule before the
work rather than after it.

This repo is generated. The canon is
[`standards/`](https://github.com/tjakoen/tjakoen.github.io/tree/main/standards) in the portfolio,
rendered at [portfolio.tjakoen.com/standards](https://portfolio.tjakoen.com/standards), and the index
is at [portfolio.tjakoen.com/skills](https://portfolio.tjakoen.com/skills).

## Install

```bash
npx skills@latest add tjakoen/skills
```

Pick the ones you want, or take the set. The three below are the way in; everything else is a rule
you reach when the task needs it.

| Skill | What it is for |
|---|---|
| `main-flow` | The seven stages of a piece of work, from orient to close, and what each one owes |
| `which-skill` | The router: from the task in front of you to the standard that governs it |
| `glossary` | The working vocabulary, one line per word |

## What is inside

| Area | Skills |
|---|---|
| **Working with AI** | `ai-development`, `ai-repo-standard`, `intake`, `brief`, `session-loop`, `loop-standard`, `decisions` |
| **Quality** | `audit-standard`, `conformance`, `hooks`, `models`, `models-verify`, `graph` |
| **Writing** | `voice`, `note-standard`, `figures`, `readme-standard`, `commit-standard`, `tour-standard` |
| **Building** | `design-standard`, `dashboard`, `tree`, `kickstart`, `claude-starter`, `local-ai-standard`, `prompt`, `glossary`, `which-skill`, `main-flow` |

`skills.json` is the machine-readable index: name, title, one-line description and path for every
skill in this repo.

## How this repo is made

1. A standard changes in the portfolio's `standards/` folder.
2. `pantry skills sync <portfolio> --out <this repo>/skills` materialises the mounts.
3. The publish step writes `skills.json`, and the same change regenerates the `/skills` page.

Nobody edits `skills/` by hand. The next publish overwrites it, which is the point: one source, two
projections, and a check that proves they agree.

## Licence

Apache 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

---

*The judgment is human. The typing, by design, is not. On this one, the rules are mine, and the
wording is mostly not.*
