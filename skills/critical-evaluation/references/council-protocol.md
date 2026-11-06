# Council protocol (single-agent multi-lens)

Inspired by multi-stage deliberation systems such as [Karpathy’s LLM Council](https://github.com/karpathy/llm-council) (parallel models → anonymized peer ranking → chairman). **This skill implements the structure inside one model** using distinct lenses. It does **not** provide independent training distributions or true peer anonymity across vendors.

## When to use

High-stakes or ambiguous decisions: strategy pivots, major builds, “should we ship X,” conflicting goals.

## Stages

### 1. Frame

- Decision in one sentence  
- Stakes and constraints  
- What “success” means  
- What is out of scope  

If the question is too vague, ask **one** clarifying question—not a questionnaire.

### 2. Five lenses (produce all five)

| Lens | Job | Must end with |
|------|-----|----------------|
| **Contrarian** | Hunt fatal flaws | The question being avoided |
| **First principles** | Rebuild from basics | A redrawn decision |
| **Expansionist** | Upside and non-binary options | A ceiling-raising option |
| **Outsider** | Zero insider jargon | The confused-newcomer question |
| **Executor** | Operational reality | One Monday-morning step |

Keep each lens short (about 120–250 words). No lens may only praise.

### 3. Peer-style review

For the set of five:

- Strongest lens and why  
- Biggest blind spot across all five  
- Where lenses contradict  

### 4. Chairman synthesis

- Points of agreement  
- Real clashes (not fake balance)  
- Blind spots  
- Recommendation  
- **Single** next action  
- Confidence + what would change the recommendation  

## Limits

- Same model → correlated errors (persona collapse risk in multi-agent research).  
- For independent peer review, run multiple models (e.g. OpenRouter council apps).  
- Swarm products (e.g. MiroFish) optimize for simulated populations, not this critique workflow.
