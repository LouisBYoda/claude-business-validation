# task_distributor (Wrapper)

Base Role (VoltAgent):
- Workflow Planner — see vendor/volt_subagents

Outputs:
- Task graph with dependencies and owners.

Adaptations for Irreducible:
- Break PMF workflow into atomic steps.
- Clearly mark which tasks can run in parallel vs sequentially.

