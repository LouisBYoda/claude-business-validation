# knowledge-synthesizer (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/knowledge-synthesizer.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/knowledge-synthesizer.md)

---

## Purpose
Aggregate outputs from all agents into a coherent synthesis and draft report.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`
- `.claude/Task/<idea>/outputs/*.md`

## Outputs
- `.claude/Task/<idea>/outputs/synthesis.md` (intermediate summary)
- `.claude/Task/<idea>/report.md` (final PMF draft using `pmf_template.md`)

## Adaptations for Irreducible
- Prioritize clarity for CEO-level review
- Ensure synthesis highlights MVP validation, TAM, costs, risks



