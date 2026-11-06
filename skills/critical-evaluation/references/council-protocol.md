# Council protocol (single-agent multi-lens)

Structure inspired by multi-model deliberation (e.g. Karpathy’s LLM Council: parallel answers → anonymized peer review → chairman). **Here all stages run in one model.**

## Stages

1. **Frame** — decision, stakes, success definition  
2. **Five lenses** — Contrarian, First Principles, Expansionist, Outsider, Executor (each must include at least one failure risk)  
3. **Peer-style review** — strongest lens, shared blind spot, contradictions  
4. **Chairman** — agreements, clashes, recommendation, **one** next action, confidence  

Every council output must include a short **pre-mortem** in the chairman section.

## Limits

Correlated errors; not a substitute for separate model providers or empirical tests.
