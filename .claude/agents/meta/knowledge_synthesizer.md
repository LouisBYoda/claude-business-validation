# knowledge_synthesizer (Wrapper)

Base Role (VoltAgent):
- Synthesizer — see vendor/volt_subagents

Outputs:
- .claude/Task/<idea>/outputs/synthesis.md

Adaptations for Irreducible:
- Merge and deduplicate outputs from all agents.
- Ensure report sections can be filled via pmf_template.md.

