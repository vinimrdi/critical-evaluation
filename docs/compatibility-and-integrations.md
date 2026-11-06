# Compatibility and integrations

## Agent Skills layout

```
skills/critical-evaluation/SKILL.md
skills/critical-evaluation/references/
```

| Environment | Typical path |
|-------------|--------------|
| Claude Code | `~/.claude/skills/critical-evaluation/` |
| Cursor | `~/.cursor/skills/critical-evaluation/` or project `.cursor/skills/` |
| Codex / generic | Path configured by the product; attach folder if discovery fails |
| Lovable / chat | **Attach** SKILL.md (+ references); do not assume auto-install |

## What “works” means

| Layer | Meaning |
|-------|---------|
| Format | Valid SKILL.md frontmatter |
| Discovery | Agent finds the skill by path or slash command |
| Behavior | Model follows challenge-first rules (varies by base model alignment) |

This skill **cannot** fully override strong sycophancy baked into a model; it raises the odds of critical output when the model complies with instructions.

## Multi-model council

For true multi-model peer review, run software such as [karpathy/llm-council](https://github.com/karpathy/llm-council) (OpenRouter). This skill’s **Council mode** simulates lenses inside **one** model.

## Swarm simulation

[MiroFish](https://github.com/666ghj/MiroFish) explores multi-agent social simulation from seed data. Different problem (forecast/sandbox), not a drop-in replacement for “critique my plan.”
