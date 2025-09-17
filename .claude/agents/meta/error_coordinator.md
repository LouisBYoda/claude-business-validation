# error-coordinator (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/error-coordinator.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/error-coordinator.md)

---

## Purpose
Handle errors, retries, and graceful recovery.

## Inputs
- Error signals from agents
- Execution logs

## Outputs
- Recovery actions
- Escalation reports

## Behavior
- Retry transient failures with backoff  
- Escalate systemic issues to human reviewers  
- Ensure workflow continuity despite errors


