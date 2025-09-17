# competitive-analyst (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/10-research-analysis/competitive-analyst.md](../../../vendor/volt_subagents/categories/10-research-analysis/competitive-analyst.md)

---

## Purpose
Map competitor landscape and Irreducible’s differentiation.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`
- MCPs: `github.json`, `web_search.json`

## Outputs
- `.claude/Task/<idea>/outputs/competitor.md`:
  - Competitor table (approach, traction, gaps)
  - SWOT summary
  - Differentiation hypothesis

## Adaptations for Irreducible
- Always benchmark against performance, scalability, dev ergonomics
- Link competitive insights back to MVP feasibility


