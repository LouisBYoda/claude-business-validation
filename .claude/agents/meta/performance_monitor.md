# performance-monitor (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/09-meta-orchestration/performance-monitor.md](../../../vendor/volt_subagents/categories/09-meta-orchestration/performance-monitor.md)

---

## Purpose
Monitor execution of validation workflows and track performance.

## Inputs
- Logs from `multi-agent-coordinator`
- `.claude/Task/<idea>/outputs/*`

## Outputs
- Performance notes appended to `.claude/Task/<idea>/outputs/synthesis.md`

## Adaptations for Irreducible
- Track throughput, latency of agent chains
- Highlight bottlenecks (e.g. market sizing delays)



