# Install critical-evaluation

Copy **only** the skill folder so `SKILL.md` is at:

```text
~/.claude/skills/critical-evaluation/SKILL.md
```

Not nested as `.../critical-evaluation/skills/critical-evaluation/SKILL.md`.

## Claude Code (recommended)

```bash
npx skills add https://github.com/vinimrdi/critical-evaluation/tree/main/skills/critical-evaluation -g -a claude-code
```

Manual:

```bash
git clone --depth 1 https://github.com/vinimrdi/critical-evaluation.git /tmp/critical-evaluation
mkdir -p ~/.claude/skills
cp -R /tmp/critical-evaluation/skills/critical-evaluation ~/.claude/skills/critical-evaluation
# Cursor: ~/.cursor/skills/   ·  shared: ~/.agents/skills/   ·  project: .claude/skills/
```

Verify:

```bash
test -f ~/.claude/skills/critical-evaluation/SKILL.md && echo OK
```

## Claude.ai (web chat)

A GitHub link alone is not enough (page readers often return a summary).

1. **Review card** — paste the full contents of `skills/critical-evaluation/SKILL.md` and save the card, or  
2. **ZIP upload** — zip the `skills/critical-evaluation` directory so the archive root is `critical-evaluation/SKILL.md` (and optional `references/`).

```bash
git clone --depth 1 https://github.com/vinimrdi/critical-evaluation.git /tmp/critical-evaluation
cd /tmp/critical-evaluation/skills
zip -r ~/Desktop/critical-evaluation-skill.zip critical-evaluation
```

Upload that zip where the product asks for a skill package (`SKILL.md` at the **first level** of the folder).

## Other hosts

| Host | Path |
|------|------|
| Cursor | `~/.cursor/skills/critical-evaluation/` |
| Generic agents | `~/.agents/skills/critical-evaluation/` |
| Project-only | `.claude/skills/critical-evaluation/` inside the repo |

## Version

Skill version **1.2.0**. See [CHANGELOG.md](CHANGELOG.md).
