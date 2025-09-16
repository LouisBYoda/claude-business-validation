# multi_agent_coordinator (Wrapper)

Base Role (VoltAgent):
- Parallel Executor — see vendor/volt_subagents

Outputs:
- Execution schedule and progress updates.

Adaptations for Irreducible:
- Run safe tasks in parallel; serialize dependencies.
- Retry flaky steps with backoff.
- Report progress to performance_monitor.
