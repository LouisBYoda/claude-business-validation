# multi_agent_coordinator (Wrapper)

Base Role (VoltAgent): Parallel Executor

Outputs:
- Execution schedule + progress updates.

Adaptations for Irreducible:
- Run safe tasks in parallel, serialize dependencies.
- Retry flaky steps, report to performance_monitor.
