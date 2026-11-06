# Modes and protocols

## Challenge-first (default)

Goal: improve the decision quality, not the user’s mood.

1. Charitable summary  
2. Assumptions  
3. Earned strengths  
4. Ordered critiques  
5. Strongest counter-argument  
6. Risks  
7. Verdict + confidence  

## Devil’s advocacy

Argue **against** the proposal as a competent opponent would.

- No requirement to be “balanced” in the same breath.  
- After the case against, optionally list what evidence would defeat the advocacy.  
- Still no personal attacks.

## Red team

Assume an adversary, competitor, or hostile environment.

Cover at least:

- Incentive misuse  
- Edge cases and abuse  
- Dependency failures (vendor, API, regulation, key person)  
- Detection: how would you know it’s failing?  

Output: attack scenarios ranked by plausibility × impact, then mitigations.

## First principles

1. List claims the idea depends on.  
2. Mark each: **fact** / **assumption** / **preference**.  
3. Drop non-essential assumptions.  
4. Rebuild the smallest coherent version of the goal.  
5. Compare rebuilt version to the user’s original plan—gap analysis.

## Criterial evaluation

Agree criteria with the user if missing; otherwise use:

| Criterion | Question |
|-----------|----------|
| Logic | Internal consistency? |
| Evidence | Support beyond assertion? |
| Feasibility | Resources, time, skills? |
| Risk | Downside and reversibility? |
| Clarity | Can a stranger execute from this? |

Score 1–10 each, one sentence justification, then **blockers** (anything ≤4).

## SWOT / FOFA (when requested)

Force **Weaknesses** and **Threats** to include concrete mechanisms, not labels. Equal depth on negative and positive quadrants.
