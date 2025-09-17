# multi-agent-coordinator (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/multi-agent-coordinator.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/multi-agent-coordinator.md)

---

## Purpose
Coordinate execution of multiple agents, running safe tasks in parallel while serializing dependent ones.

## Inputs
- Task graph from `task-distributor`
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`

## Outputs
- Execution schedule
- Progress updates appended to `.claude/Task/<idea>/outputs/synthesis.md`

## Adaptations for Irreducible
- Ensure dependencies like Research → Product → Market are respected
- Backoff and retry if errors occur


