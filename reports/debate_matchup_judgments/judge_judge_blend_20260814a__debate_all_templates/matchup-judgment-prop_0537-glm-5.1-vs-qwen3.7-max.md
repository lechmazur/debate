# Debate Matchup Judgment Report

**GLM-5.1** vs **Qwen 3.7 Max**

- Paired result: **GLM-5.1**
- Mean entertainment: `8.00 / 10`
- Judge decisions: `3` across two side-swapped debates

**Motion:** Governments should build sovereign AI compute capacity for critical public-interest uses rather than depend heavily on private cloud providers and foreign infrastructure.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0537__qwen3.7-max__glm-5.1__s1__tpl_placement_active_20260320f.md): PRO = **Qwen 3.7 Max**, CON = **GLM-5.1**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260814a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0537__qwen3.7-max__glm-5.1__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen 3.7 Max**, CON = **GLM-5.1**
- Judged result: Split `2-1` for **GLM-5.1**.
- Entertainment scores: `8`, `8`, `8`
- Mean signed raw margin (PRO+): `-0.57`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = GLM-5.1 (CON); B = Qwen 3.7 Max (PRO) | Qwen 3.7 Max | +1.0 | +1.07 | 8.0 |
| Gemini 3.1 Pro Preview | A = GLM-5.1 (CON); B = Qwen 3.7 Max (PRO) | GLM-5.1 | -1.2 | -1.00 | 8.0 |
| Kimi K2.6 | A = GLM-5.1 (CON); B = Qwen 3.7 Max (PRO) | GLM-5.1 | -1.5 | -1.50 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = GLM-5.1 (CON); B = Qwen 3.7 Max (PRO)): Side B won by keeping the debate centered on the motion's core risk: critical public uses need guaranteed physical compute when markets, foreign jurisdictions, or private incentives fail. Side A made strong points about obsolescence, procurement, diversification, and contracts, but some of those attacks over-narrowed sovereign compute into a single static cluster and did not fully answer why enforceable rights are less reliable than actual state-controlled capacity in a crisis. B's baseline-capacity framing made ownership look like resilience rather than vanity duplication.
  Most decisive rebuttal noted: B's most decisive exchange was answering A's export-control and procurement critique by arguing that future upgrade dependence does not erase the immediate value of already-installed chips, while contracts cannot create scarce compute during systemic shortages.
- **Gemini 3.1 Pro Preview** (A = GLM-5.1 (CON); B = Qwen 3.7 Max (PRO)): Side A won by effectively demonstrating that sovereign compute cannot escape dependency on the global semiconductor supply chain, while exposing the model as a fragile, stagnant single point of failure. Side B argued well for the necessity of physical control during a crisis, but failed to adequately overcome Side A's point that reserved commercial instances achieve baseline capacity without sacrificing continuous technological refresh.
  Most decisive rebuttal noted: Side A's second rebuttal, where they clarified that commercial contracts secure 'existing, operational hardware' via reserved instances, effectively neutralizing Side B's claim that contracts require vendors to manufacture unavailable chips.
- **Kimi K2.6** (A = GLM-5.1 (CON); B = Qwen 3.7 Max (PRO)): Side A won by exposing that Side B's concession—that critical AI workloads do not require frontier hardware—self-defeats the sovereignty rationale, since baseline capacity already exists commercially. Side A also showed that sovereign facilities still depend on foreign semiconductor supply chains, merely relocating rather than resolving dependency, while a single state-owned cluster introduces a vulnerable point of failure against diversified commercial capacity under domestic legal jurisdiction. Side B's vivid "paper guarantees" framing could not overcome the reality that physical ownership of aging chips does not create silicon independence, nor could Side B reconcile modest baseline needs with urgent national-survival rhetoric.
  Most decisive rebuttal noted: Side A's turn that Side B's claim that critical workloads do not need bleeding-edge hardware removes the entire rationale for sovereign buildout, since existing commercial infrastructure can already provide such baseline capacity.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260814a__debate_all_templates`
- Topic ID: `prop_0537`
- Side-swap group ID: `prop_0537__glm-5.1__qwen3.7-max__tpl_placement_active_20260320f`
- Raw paired winner: **GLM-5.1**
- Mean normalized margin for GLM-5.1: `+0.48`
- Complete side swap: `no`
- Included in ratings: `no`
