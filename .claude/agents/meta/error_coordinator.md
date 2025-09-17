# error-coordinator (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/error-coordinator.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/error-coordinator.md)

---

## Purpose
Handle agent or workflow errors gracefully.

## Inputs
- Error logs from orchestrator/agents

## Outputs
- Recovery steps
- Notes in `.claude/Task/<idea>/outputs/synthesis.md`

## Adaptations for Irreducible
- Retry critical tasks up to 3 times
- Escalate to human if validation data is missing or contradictory



