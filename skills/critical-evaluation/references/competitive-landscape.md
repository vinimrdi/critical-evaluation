# Competitive landscape — what peer skills do well

Survey of public Agent Skills and related repos in the anti-sycophancy / critical evaluation / council line (2025–2026). Used to evolve this skill. Not an endorsement ranking by stars alone.

## Pattern clusters

### A. Minimal process anti-sycophancy

**Examples:** community `anti-sycophancy` skills (e.g. mskadu / sickn33 packs), **Frank** (huxleyli15/frank).

| Strength | Adoption here |
|----------|----------------|
| Extract claim → independent assess → **conclude first** | Core process steps 1–3 |
| Pushback = new evidence vs repeated opinion | Pushback table |
| Ban hollow praise openers | Banned empty moves |

### B. Calibrated honesty (not reflexive dissent)

**Examples:** **ground-truth** (glichtenthal/ground-truth).

| Strength | Adoption here |
|----------|----------------|
| Target = calibrated honesty | Stated in SKILL intro |
| Untested assumption before agree | Stance rule 5 |
| Stress-test before endorse | Stance rule 4 |
| Capitulation tell: reversal cites reaction not argument | why-models-agree + hold protocol |

### C. Structural “ask don’t tell”

**Examples:** **0xcjl/anti-sycophancy** (hook + skill + persistent rules; arXiv “Ask Don’t Tell” theme).

| Strength | Adoption here |
|----------|----------------|
| Confirmation questions → treat presupposition as the problem | Leading questions section |
| Changing *question structure* > “be objective” alone | Documented in why-models-agree |
| Multi-layer deploy (hook / skill / memory) | Noted as optional ops; skill stays portable |

### D. Multi-round self-challenge

**Examples:** **expert-insist** (3-round validation).

| Strength | Adoption here |
|----------|----------------|
| Form conclusion → challenge top assumption → resolve only if conflict | Optional in modes; mirrors independent take + falsifiers |

### E. Devil’s advocate craft

**Examples:** **wtfzambo/devils-advocate**, **the-fool** (Jeffallan/claude-skills).

| Strength | Adoption here |
|----------|----------------|
| Start with objection most likely to change the decision | Devil’s advocacy mode |
| Pre-mortem + second-order failure modes | Mandatory pre-mortem |
| Evidence falsification mode | Evidence audit mode |
| One consequential point at a time | Preferred under devil’s advocacy |

### F. Council / multi-lens

**Examples:** **okjpg/llm-council**, **evisoft/council**, **oliwoodman/llm-council-skill**, **tenfoldmarc**, **Paldom/llm-council-skills**, research-backed **DMAD** notes (ngmeyer-style).

| Strength | Adoption here |
|----------|----------------|
| Five tension lenses + mandatory peer step | Council protocol |
| Each lens ends with a sharp artifact (avoided question, redrawn decision, Monday step) | council-protocol.md |
| **Devil’s advocate vs emerging consensus** (not only early soft contrarian) | Council step 5 |
| Mandatory trigger phrases | description triggers |
| Word discipline per lens | Short lens guidance |
| Correlated-failure warning | Already stated multi-lens ≠ multi-model |

### G. Evidence hygiene

**Examples:** **ysskrishna critical-thinking**, **deep-mind-skill** (evidence gate).

| Strength | Adoption here |
|----------|----------------|
| [CITED] / [MISSING] on claims | Evidence audit mode |
| Split factual vs normative | Clarify in extract/claim |

### H. Domain packs + evals

**Examples:** **candor** (itsryanlenk) — core + work-mode personas + A/B evals; **badpowers** — think/audit/critique with failure registries.

| Strength | Adoption here |
|----------|----------------|
| Lead with disagreement + reason | Verdict-first |
| Failure mode registry | Pre-mortem structure |
| Published evals | Future work; not claimed without running them |

## What we deliberately did *not* copy

- Platform-only hooks that break portability (document as optional instead).  
- Therapy-adjacent “reflection” skills (out of scope).  
- Claims of eliminating sycophancy (instruction layer is partial).  
- Oversight-loosening directives (“always proceed without asking”).  

## Positioning of *this* skill

Combines: mechanism literacy (why RLHF agrees) + verdict-first process + mandatory pre-mortem + hold-under-pushback + council with **consensus attack** + evidence tags — in one portable English skill tree aligned with vinimrdi’s other agent skills.
