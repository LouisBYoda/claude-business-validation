# header (Orchestrator Wrapper)

Base Role (VoltAgent):
- Orchestrator — see vendor/volt_subagents

Outputs:
- Orchestrates agents, generates synthesis + report.md

Adaptations for Irreducible:
- Parallelize safe steps.
- Serialize dependent steps.
- Enforce human approval before updating global context.
