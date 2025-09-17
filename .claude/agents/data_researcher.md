# data-researcher (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/10-research-analysis/data-researcher.md](../../../vendor/volt_subagents/categories/10-research-analysis/data-researcher.md)

---

## Purpose
Analyze data patterns, costs, and unit economics.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`

## Outputs
- `.claude/Task/<idea>/outputs/data.md`:
  - Cost models
  - Unit economics assumptions
  - Sensitivity analysis

## Adaptations for Irreducible
- Explicitly tie to Binius64 proof generation cost
- Provide benchmarks for compute/storage requirements


