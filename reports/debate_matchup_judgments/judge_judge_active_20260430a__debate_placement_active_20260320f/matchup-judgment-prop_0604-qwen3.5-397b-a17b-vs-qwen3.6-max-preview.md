# Debate Matchup Judgment Report

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- side_swap_group_id: `prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__tpl_placement_active_20260320f`
- topic_id: `prop_0604`
- matchup: **Qwen3.5-397B-A17B** vs **Qwen 3.6 Max Preview**
- overall judged result (normalized): **Qwen 3.6 Max Preview**
- overall judged result (raw): **Qwen 3.6 Max Preview**
- mean entertainment: `7.50 / 10`
- mean signed normalized margin for `Qwen3.5-397B-A17B`: `-0.74`
- judgment rows: `6`
- swap_complete: `1`
- rating_eligible: `1`

**Motion:** The European Union should move from “risk-based” AI regulation to mandatory licensing for frontier general-purpose AI models deployed in the EU market.

## Source Links

- [Debate A transcript](../../../transcripts/prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__s0__tpl_placement_active_20260320f.md): PRO = **Qwen3.5-397B-A17B**, CON = **Qwen 3.6 Max Preview**
- [Debate B transcript](../../../transcripts/prop_0604__qwen3.6-max-preview__qwen3.5-397b-a17b__s1__tpl_placement_active_20260320f.md): PRO = **Qwen 3.6 Max Preview**, CON = **Qwen3.5-397B-A17B**
- [Rolling judgment CSV](../../../judgments/judge_results__judge_active_20260430a.csv)
  Search for `side_swap_group_id=prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__tpl_placement_active_20260320f` or topic `prop_0604`.

## Debate A

- debate_id: `prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__s0__tpl_placement_active_20260320f`
- transcript: [read transcript](../../../transcripts/prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__s0__tpl_placement_active_20260320f.md)
- roles: PRO = **Qwen3.5-397B-A17B**, CON = **Qwen 3.6 Max Preview**
- judged result: Unanimous `3-0` for **Qwen 3.6 Max Preview**.
- entertainment scores: `8`, `7`, `7`
- mean signed raw margin (PRO+): `-1.77`

| Judge | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | Qwen 3.6 Max Preview | -1.5 | -1.61 | 7.0 |
| Gemini 3.1 Pro Preview | Qwen 3.6 Max Preview | -2.2 | -1.83 | 8.0 |
| Kimi K2.6 | Qwen 3.6 Max Preview | -1.6 | -1.60 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)**: Side A won because it made the central licensing mechanism look underinclusive, technically fragile, and costly: offshore APIs, open weights, distillation, and arbitrary compute thresholds meant the proposed gate would mainly burden compliant EU developers. Side B had a strong...
  Most decisive rebuttal noted: Side A's strongest exchange was answering the biosecurity pressure by shifting the focus from model permits to real chokepoints such as labs, cloud scale, critical infrastructure, and dual-use supply chains, which undercut Side B's claim that only upstream licensing can preven...
- **Gemini 3.1 Pro Preview**: Side A wins by demonstrating that mandatory licensing is easily bypassed via offshore models and distillation, while clarifying that risk-based regulation already applies ex-ante checks at the necessary physical and infrastructural chokepoints. Side B relied heavily on the pre...
  Most decisive rebuttal noted: Side A's A1 in Rebuttal 2, which neutralized Side B's biological weapons scenario by pointing out that the physical chokepoints (centrifuges, labs) are the true bottlenecks and are already covered by risk-based and dual-use regulations.
- **Kimi K2.6**: CON won by proving that mandatory licensing is unenforceable for digital base models—weights leak, offshore APIs bypass the regime, and distillation breaks compute thresholds—while risk-based application rules target actual harm at tangible chokepoints. PRO's gate metaphor cru...
  Most decisive rebuttal noted: CON's rebuttal to PRO's pressure questions and the distillation issue: showing that licensing the "teacher" fails once capabilities go global, and that catastrophic harm is better stopped at physical deployment chokepoints than at a digital tollbooth that only the lawful pay.

## Debate B

- debate_id: `prop_0604__qwen3.6-max-preview__qwen3.5-397b-a17b__s1__tpl_placement_active_20260320f`
- transcript: [read transcript](../../../transcripts/prop_0604__qwen3.6-max-preview__qwen3.5-397b-a17b__s1__tpl_placement_active_20260320f.md)
- roles: PRO = **Qwen 3.6 Max Preview**, CON = **Qwen3.5-397B-A17B**
- judged result: Split `2-1` for **Qwen3.5-397B-A17B**.
- entertainment scores: `8`, `7`, `8`
- mean signed raw margin (PRO+): `-0.33`

| Judge | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | Qwen 3.6 Max Preview | +1.7 | +1.82 | 7.0 |
| Gemini 3.1 Pro Preview | Qwen3.5-397B-A17B | -1.5 | -1.25 | 8.0 |
| Kimi K2.6 | Qwen3.5-397B-A17B | -1.2 | -1.20 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)**: Side B won by making the central clash about timing and market access: frontier general-purpose models create unpredictable systemic risks, so verification before commercial deployment is more credible than reacting to harmful applications afterward. Side A had real objections...
  Most decisive rebuttal noted: Best exchange was B's answer to the open-weights objection: licensing need not police every download because commercial scale depends on EU market access, legal certainty, cloud infrastructure, and payment rails. That undercut A's strongest enforceability route.
- **Gemini 3.1 Pro Preview**: Side A wins by cleanly dismantling Side B's mechanism. A successfully proves that B's 'commercial deployment' gate fails to stop the worst catastrophic risks (which B admits are out of scope for personal downloads of open weights) while simultaneously imposing massive complian...
  Most decisive rebuttal noted: Side A's A2 in Rebuttal 2 flawlessly catches Side B in a contradiction, using B's own rule that 'integrators bear the burden' to prove the policy acts as a massive compliance tax on every downstream European business.
- **Kimi K2.6**: Side A (CON) won because it exposed critical solvency and cost problems with mandatory licensing that Side B (PRO) never fully repaired. CON effectively turned PRO's open-weights defense into an economic liability: by conceding that downstream commercial integrators trigger li...
  Most decisive rebuttal noted: CON's second rebuttal (A4.1–A4.3), where it seized on PRO's admission that commercial integrators trigger the license to demonstrate that the regime imposes due-diligence costs on every downstream business, turning PRO's "targeted gate" argument into a broad compliance tax on...
