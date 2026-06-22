---
type: Fixed
pr: 1570
---
**Gating critics now self-disconfirm their own verdict (LLM-playbook principles 5, 25)** — gsd-verifier, gsd-plan-checker and gsd-code-reviewer run a verdict self-check (false-PASS / strongest-counterargument) before finalizing, via a shared verdict-self-check reference. Based on arXiv 2507.11662 (Self-Grounded Verification — blind pass-criteria first), 2507.10124 (metacognitive self-check), 2507.02778 (self-correction blind spot). (GRP 2503.06139 dropped — no pairwise choice in a single-artifact gate.)
