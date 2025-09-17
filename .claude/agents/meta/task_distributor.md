# task-distributor (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/task-distributor.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/task-distributor.md)

---

## Purpose
Distribute work across specialist agents efficiently.

## Inputs
- Task definition from Header/Orchestrator
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`

## Outputs
- Agent task assignments
- Updates to `.claude/Task/<idea>/outputs/*` (trigger downstream work)

## Behavior
- Split complex workflows into atomic subtasks  
- Assign to the correct specialist agent  
- Track completion and escalate failures to `error-coordinator`

