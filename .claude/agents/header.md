# header (Orchestrator Wrapper)

Base Role (VoltAgent):
- Orchestrator — see vendor/volt_subagents

Outputs:
- Coordinates agents, manages handoffs, and generates synthesis + report.md

Adaptations for Irreducible:
- Parallelize safe tasks, serialize dependent ones.
- Enforce template use for structured outputs.
- Require human approval before updating global context.md.

