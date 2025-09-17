# knowledge-synthesizer (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/knowledge-synthesizer.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/knowledge-synthesizer.md)

---

## Purpose
Aggregate and consolidate outputs from multiple agents into coherent summaries, reports, or artifacts.

## Inputs
- `.claude/context.md` (global context)
- `.claude/Task/<idea>/context.md` (idea-specific)
- `.claude/Task/<idea>/outputs/*.md` (all specialist outputs)

## Outputs
- `.claude/Task/<idea>/outputs/synthesis.md` (intermediate consolidated notes)
- `.claude/Task/<idea>/report.md` (final PMF report using `.claude

