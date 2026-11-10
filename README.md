<div align="center">

# Critical Evaluation

### Agent skill against **sycophancy** — calibrated honesty, not flattery

Verdict-first critique · mandatory pre-mortem · hold under pushback · multi-lens council with consensus attack.

[![Skill](https://img.shields.io/badge/skill-v1.2.0-blue?style=flat-square)](skills/critical-evaluation/SKILL.md)
[![License: CC BY 4.0](https://img.shields.io/badge/docs-CC%20BY%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

[Skill](skills/critical-evaluation/SKILL.md) · [Why models agree](skills/critical-evaluation/references/why-models-agree.md) · [Landscape](skills/critical-evaluation/references/competitive-landscape.md) · [Changelog](CHANGELOG.md)

</div>

---

## Install

Full guide: [INSTALL.md](INSTALL.md).

### Claude Code (one command)

```bash
npx skills add https://github.com/vinimrdi/critical-evaluation/tree/main/skills/critical-evaluation -g -a claude-code
```

### Manual

```bash
git clone --depth 1 https://github.com/vinimrdi/critical-evaluation.git /tmp/critical-evaluation
mkdir -p ~/.claude/skills
cp -R /tmp/critical-evaluation/skills/critical-evaluation ~/.claude/skills/critical-evaluation
```

`SKILL.md` must sit at `~/.claude/skills/critical-evaluation/SKILL.md`.

### Claude.ai (web)

Paste `skills/critical-evaluation/SKILL.md` into a skill review card, or upload a **flat ZIP** of that folder. A GitHub link alone is not enough.

---

## Ask

```text
Use critical-evaluation on this plan.
Verdict first. Pre-mortem ≥3 failures. Hold under pushback without new evidence.
```

---

## What v1.2 learned from peers

Process order from anti-sycophancy skills · calibrated honesty from ground-truth · confirmation reframes · decision-changing objections · council consensus attack · evidence tags — documented in [competitive-landscape.md](skills/critical-evaluation/references/competitive-landscape.md).
