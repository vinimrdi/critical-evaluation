<div align="center">

# Critical Evaluation

### Agent skill against **sycophancy** — truth over agreement

Challenge ideas, plans, and arguments with structured skepticism: devil’s advocacy, red team, first principles, criterial scores, and a single-agent multi-lens council.

[![License: CC BY 4.0](https://img.shields.io/badge/docs-CC%20BY%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Skill](https://img.shields.io/badge/skill-v1.0.0-blue?style=flat-square)](skills/critical-evaluation/SKILL.md)
[![Agents](https://img.shields.io/badge/agents-Claude%20%7C%20Cursor%20%7C%20Codex%20%7C%20Lovable-111827?style=flat-square)](docs/compatibility-and-integrations.md)

[Skill](skills/critical-evaluation/SKILL.md) · [Examples](examples/) · [Install](#install) · [Changelog](CHANGELOG.md)

</div>

---

## The problem

Many language models are trained (especially via RLHF) to be helpful and agreeable. That produces **sycophancy**: the model mirrors your framing, softens disagreement, and under-reports risks. Courtesy is not the same as correctness.

This skill makes critical evaluation the **default** when reviewing ideas, plans, claims, or decisions—without turning every chat into hostility.

---

## What you get

| Mode | What it does |
|------|----------------|
| **Challenge-first (default)** | Correct errors; surface assumptions, risks, and counter-arguments before praise |
| **Devil’s advocacy** | Strongest case *against* the idea |
| **Red team** | Adversary / failure-mode hunt |
| **First principles** | Strip assumptions; rebuild from basics |
| **Criterial score** | Explicit criteria + scores + gaps |
| **Council (single-agent)** | Multi-lens analysis + anonymous-style peer critique + chairman synthesis |

Inspired by adversarial prompting practice and by multi-perspective deliberation patterns such as [Karpathy’s LLM Council](https://github.com/karpathy/llm-council) (true multi-model peer review). This skill runs **inside one agent**—it is not a substitute for separate models or swarm simulators like [MiroFish](https://github.com/666ghj/MiroFish).

---

## Install

```bash
git clone https://github.com/vinimrdi/critical-evaluation.git
mkdir -p ~/.claude/skills
cp -R critical-evaluation/skills/critical-evaluation ~/.claude/skills/critical-evaluation
# Cursor: ~/.cursor/skills/
```

```bash
npx skills add vinimrdi/critical-evaluation --skill critical-evaluation
```

Lovable / chat UIs: **attach** `SKILL.md` (and references if needed). See [docs/compatibility-and-integrations.md](docs/compatibility-and-integrations.md).

---

## Ask your agent

```text
Use critical-evaluation on this plan.
Challenge-first. List assumptions, strongest counter-argument, top risks.
Score viability / risk / evidence 1–10. Do not agree out of courtesy.
```

Escape hatch when you only need execution:

```text
Just execute — no critique mode.
```

---

## Related skills

- [ux-laws-principles](https://github.com/vinimrdi/ux-laws-principles) — evidence-based UX concepts  
- [optical-alignment-ui](https://github.com/vinimrdi/optical-alignment-ui) — precision vs perception in UI  

---

## Language & license

English · Documentation [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
Educational methodology—not legal, medical, or financial advice. Not a guarantee that the model will never sycophant (training bias remains).
