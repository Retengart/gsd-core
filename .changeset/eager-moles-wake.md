---
type: Changed
pr: 1570
---
**eval-auditor scoring moved into a deterministic `eval.score` query verb (LLM-playbook principle 10)** — coverage/infra/overall arithmetic and verdict banding are computed in code (`gsd-tools query eval.score`) instead of by the model. Based on arXiv 2504.00406 (VerifiAgent), 2508.15754 (TIR), 2510.15955.
