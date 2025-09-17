# knowledge-synthesizer (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/knowledge-synthesizer.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/knowledge-synthesizer.md)

---

## Purpose
Aggregate outputs into coherent synthesis and final PMF report.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`
- `.claude/Task/<idea>/outputs/*.md`

## Outputs
- `.claude/Task/<idea>/outputs/synthesis.md`
- `.claude/Task/<idea>/report.md` (via `.claude/templates/pmf_template.md`)


