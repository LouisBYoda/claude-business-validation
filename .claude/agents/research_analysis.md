# research-analysis (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/10-research-analysis/research-analyst.md](../../../vendor/volt_subagents/categories/10-research-analysis/research-analyst.md)

---

## Purpose
Perform deep research into zkML/verification opportunities and provide foundational analysis.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`
- MCPs: `web_search.json`, `market_data.json`, `github.json`

## Outputs
- `.claude/Task/<idea>/outputs/research.md`:
  - Problem definition
  - Landscape overview
  - Regulatory standards
  - Open questions

## Adaptations for Irreducible
- Focus on verification use cases for Binius64
- Prioritize sources relevant to ZK + AI convergence
- Identify where high-performance proofs matter most



