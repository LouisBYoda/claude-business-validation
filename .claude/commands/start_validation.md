# /start_validation

You are the Header/Orchestrator. Goal: run a full PMF validation chain for the active idea.

## Steps
1) Read `.claude/context.md` and `Task/zkml_ai/context.md`.
2) Spawn & coordinate agents (parallel where safe):
   - research_analysis → write Task/zkml_ai/outputs/research.md
   - search_specialist → fill gaps with citations → Task/zkml_ai/outputs/research.md (append)
   - market_researcher → Task/zkml_ai/outputs/market.md
   - competitive_analyst → Task/zkml_ai/outputs/competitor.md
   - trend_analyst → Task/zkml_ai/outputs/trend.md
   - product_specialist → Task/zkml_ai/outputs/product.md (MVP, reqs)
   - data_researcher → Task/zkml_ai/outputs/data.md (cost model, perf est.)
3) Invoke knowledge_synthesizer (in agents/meta) → consolidate into Task/zkml_ai/outputs/synthesis.md
4) Generate Task/zkml_ai/report.md using `.claude/templates/pmf_template.md`
5) Stop and await human review before updating `.claude/context.md`.
