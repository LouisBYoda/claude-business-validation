# search-specialist (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/10-research-analysis/search-specialist.md](../../../vendor/volt_subagents/categories/10-research-analysis/search-specialist.md)

---

## Purpose
Fill gaps in outputs with precise fact-finding and citations.

## Inputs
- Agent outputs in `.claude/Task/<idea>/outputs/*.md`
- MCPs: `web_search.json`, `github.json`

## Outputs
- Appends inline citations to research, competitor, market, trend, or data files

## Adaptations for Irreducible
- Always validate critical assumptions (e.g. market sizing numbers, performance metrics)
- Cross-check claims against primary sources



