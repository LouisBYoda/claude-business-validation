# task-distributor (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/task-distributor.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/task-distributor.md)

---

## Purpose
Split complex validation workflows into manageable subtasks and assign them to specialist agents.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`
- Validation workflow plan from Header agent

## Outputs
- Execution map (which agent does what, in what order)
- Progress log stored in `.claude/Task/<idea>/outputs/synthesis.md`

## Adaptations for Irreducible
- Break down PMF validation into Research → Product → Market → Competitor → Trends → Data
- Support parallelization where dependencies are minimal


