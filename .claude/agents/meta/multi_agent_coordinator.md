# multi_agent_coordinator

Inputs: task graph from task_distributor
Outputs: execution schedule, progress updates

- Run safe tasks in parallel; serialize dependent ones.
- Retry flaky steps; backoff on repeated errors.
- Report status to performance_monitor.
