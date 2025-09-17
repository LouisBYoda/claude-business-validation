# market-researcher (Wrapper)

Base Role (VoltAgent):  
[vendor/volt_subagents/categories/10-research-analysis/market-researcher.md](../../../vendor/volt_subagents/categories/10-research-analysis/market-researcher.md)

---

## Purpose
Analyze market size and demand for target opportunities.

## Inputs
- `.claude/context.md`
- `.claude/Task/<idea>/context.md`
- MCPs: `market_data.json`

## Outputs
- `.claude/Task/<idea>/outputs/market.md`:
  - TAM/SAM/SOM
  - Segments & ICPs
  - Buying criteria & adoption barriers
  - Pricing benchmarks

## Adaptations for Irreducible
- Highlight adoption constraints for ZK proofs
- Compare enterprise vs. consumer adoption paths





