<div align="center">

# Critical Evaluation

### Agent skill against **sycophancy** — truth over agreement

Challenge ideas and plans with structured skepticism: pre-mortem failure forecasts, devil’s advocacy, red team, first principles, and single-agent multi-lens council.

[![License: CC BY 4.0](https://img.shields.io/badge/docs-CC%20BY%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Skill](https://img.shields.io/badge/skill-v1.1.0-blue?style=flat-square)](skills/critical-evaluation/SKILL.md)

[Skill](skills/critical-evaluation/SKILL.md) · [Why models agree](skills/critical-evaluation/references/why-models-agree.md) · [Examples](examples/) · [Changelog](CHANGELOG.md)

</div>

---

## Why this exists

Assistants trained with human preference feedback often **match user beliefs**, abandon correct answers under mild pushback, and under-generate **how a plan fails**—even when the downside is obvious to a careful human. That pattern is called **sycophancy**. It is partly driven by raters and reward models preferring agreeable answers, then amplified by optimization (see research such as Sharma et al., arXiv:2310.13548).

This skill makes critical evaluation **default**: independent judgment, mandatory **pre-mortem**, hold-under-pushback, and explicit “do not proceed” as a valid verdict.

---

## Install

```bash
git clone https://github.com/vinimrdi/critical-evaluation.git
cp -R critical-evaluation/skills/critical-evaluation ~/.claude/skills/critical-evaluation
```

```bash
npx skills add vinimrdi/critical-evaluation --skill critical-evaluation
```

---

## Ask your agent

```text
Use critical-evaluation on this plan.
Independent take first. Mandatory pre-mortem (≥3 failure scenarios).
Do not agree out of courtesy. Hold under pushback without new evidence.
```

---

## Related

- [ux-laws-principles](https://github.com/vinimrdi/ux-laws-principles)  
- [optical-alignment-ui](https://github.com/vinimrdi/optical-alignment-ui)  
- Multi-model peer review: [karpathy/llm-council](https://github.com/karpathy/llm-council)  
