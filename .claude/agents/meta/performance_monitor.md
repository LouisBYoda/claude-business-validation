# performance-monitor (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/performance-monitor.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/performance-monitor.md)

---

## Purpose
Track agent and workflow performance.

## Inputs
- Execution schedule from `multi-agent-coordinator`
- Agent outputs and timing logs

## Outputs
- Performance dashboard/logs
- Bottleneck reports

## Behavior
- Monitor throughput, latency, and agent utilization  
- Detect anomalies in workflow speed or quality  
- Feed metrics back into orchestration layer


