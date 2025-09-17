# multi-agent-coordinator (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/multi-agent-coordinator.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/multi-agent-coordinator.md)

---

## Purpose
Enable safe parallel execution and orchestrate dependent tasks.

## Inputs
- Task graph from `task-distributor`
- Progress signals from agents

## Outputs
- Execution schedule
- Progress updates to `performance-monitor`

## Behavior
- Run independent tasks in parallel; serialize dependent ones  
- Retry flaky steps with backoff  
- Report execution status and flag bottlenecks

