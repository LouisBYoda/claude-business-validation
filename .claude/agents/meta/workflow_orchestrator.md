# workflow-orchestrator (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/workflow-orchestrator.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/workflow-orchestrator.md)

---

## Purpose
Automate and enforce sequencing of complex workflows across agents.

## Inputs
- Validation workflow plan
- `.claude/context.md`

## Outputs
- Enforced step-by-step execution
- Logs stored in `.claude/Task/<idea>/outputs/synthesis.md`

## Adaptations for Irreducible
- Ensure execution always follows: Research → Product → Market → Competitor → Trends → Data → Synthesis
- Guarantee consistency across all idea validations
