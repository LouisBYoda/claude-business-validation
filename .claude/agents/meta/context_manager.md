# context-manager (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/context-manager.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/context-manager.md)

---

## Purpose
Maintain `.claude/context.md` as a living memory across all opportunities.

## Inputs
- Task reports from `/Task/<idea>/report.md`
- Human-reviewed updates

## Outputs
- Summarized learnings into `.claude/context.md`

## Behavior
- Promote generalizable insights from task-specific reports  
- Keep context concise; link out to details in Task reports  
- Only update via `/update_context` command


