# Debate Matchup Judgment Report

**Qwen3.5-397B-A17B** vs **Qwen 3.6 Max Preview**

- Paired result: **Qwen 3.6 Max Preview**
- Mean entertainment: `7.50 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** The European Union should move from “risk-based” AI regulation to mandatory licensing for frontier general-purpose AI models deployed in the EU market.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__s0__tpl_placement_active_20260320f.md): PRO = **Qwen3.5-397B-A17B**, CON = **Qwen 3.6 Max Preview**
- [Debate B transcript](../../../transcripts/prop_0604__qwen3.6-max-preview__qwen3.5-397b-a17b__s1__tpl_placement_active_20260320f.md): PRO = **Qwen 3.6 Max Preview**, CON = **Qwen3.5-397B-A17B**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260814a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen3.5-397B-A17B**, CON = **Qwen 3.6 Max Preview**
- Judged result: Unanimous `3-0` for **Qwen 3.6 Max Preview**.
- Entertainment scores: `8`, `7`, `7`
- Mean signed raw margin (PRO+): `-1.77`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen 3.6 Max Preview (CON); B = Qwen3.5-397B-A17B (PRO) | Qwen 3.6 Max Preview | -1.5 | -1.61 | 7.0 |
| Gemini 3.1 Pro Preview | A = Qwen 3.6 Max Preview (CON); B = Qwen3.5-397B-A17B (PRO) | Qwen 3.6 Max Preview | -2.2 | -1.83 | 8.0 |
| Kimi K2.6 | A = Qwen 3.6 Max Preview (CON); B = Qwen3.5-397B-A17B (PRO) | Qwen 3.6 Max Preview | -1.6 | -1.60 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen 3.6 Max Preview (CON); B = Qwen3.5-397B-A17B (PRO)): Side A won because it made the central licensing mechanism look underinclusive, technically fragile, and costly: offshore APIs, open weights, distillation, and arbitrary compute thresholds meant the proposed gate would mainly burden compliant EU developers. Side B had a strong precautionary case about catastrophic risk, but never fully proved that licensing could actually verify safety or stop the most dangerous pathways better than enforceable application and infrastructure controls.
  Most decisive rebuttal noted: Side A's strongest exchange was answering the biosecurity pressure by shifting the focus from model permits to real chokepoints such as labs, cloud scale, critical infrastructure, and dual-use supply chains, which undercut Side B's claim that only upstream licensing can prevent catastrophic harm.
- **Gemini 3.1 Pro Preview** (A = Qwen 3.6 Max Preview (CON); B = Qwen3.5-397B-A17B (PRO)): Side A wins by demonstrating that mandatory licensing is easily bypassed via offshore models and distillation, while clarifying that risk-based regulation already applies ex-ante checks at the necessary physical and infrastructural chokepoints. Side B relied heavily on the premise that risk-based regulation is purely post-hoc, which Side A decisively refuted.
  Most decisive rebuttal noted: Side A's A1 in Rebuttal 2, which neutralized Side B's biological weapons scenario by pointing out that the physical chokepoints (centrifuges, labs) are the true bottlenecks and are already covered by risk-based and dual-use regulations.
- **Kimi K2.6** (A = Qwen 3.6 Max Preview (CON); B = Qwen3.5-397B-A17B (PRO)): CON won by proving that mandatory licensing is unenforceable for digital base models—weights leak, offshore APIs bypass the regime, and distillation breaks compute thresholds—while risk-based application rules target actual harm at tangible chokepoints. PRO's gate metaphor crumbled under sustained pressure on evasion pathways and the teacher-student problem.
  Most decisive rebuttal noted: CON's rebuttal to PRO's pressure questions and the distillation issue: showing that licensing the "teacher" fails once capabilities go global, and that catastrophic harm is better stopped at physical deployment chokepoints than at a digital tollbooth that only the lawful pay.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0604__qwen3.6-max-preview__qwen3.5-397b-a17b__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen 3.6 Max Preview**, CON = **Qwen3.5-397B-A17B**
- Judged result: Split `2-1` for **Qwen3.5-397B-A17B**.
- Entertainment scores: `8`, `7`, `8`
- Mean signed raw margin (PRO+): `-0.33`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen3.5-397B-A17B (CON); B = Qwen 3.6 Max Preview (PRO) | Qwen 3.6 Max Preview | +1.7 | +1.82 | 7.0 |
| Gemini 3.1 Pro Preview | A = Qwen3.5-397B-A17B (CON); B = Qwen 3.6 Max Preview (PRO) | Qwen3.5-397B-A17B | -1.5 | -1.25 | 8.0 |
| Kimi K2.6 | A = Qwen3.5-397B-A17B (CON); B = Qwen 3.6 Max Preview (PRO) | Qwen3.5-397B-A17B | -1.2 | -1.20 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen3.5-397B-A17B (CON); B = Qwen 3.6 Max Preview (PRO)): Side B won by making the central clash about timing and market access: frontier general-purpose models create unpredictable systemic risks, so verification before commercial deployment is more credible than reacting to harmful applications afterward. Side A had real objections on open weights, compliance costs, and sovereignty, but B repeatedly narrowed licensing to commercial deployment and showed why that remains an enforceable choke point. A's alternative also drifted toward pre-deployment capability thresholds, making it less distinct from licensing, and the clipped closing hurt execution.
  Most decisive rebuttal noted: Best exchange was B's answer to the open-weights objection: licensing need not police every download because commercial scale depends on EU market access, legal certainty, cloud infrastructure, and payment rails. That undercut A's strongest enforceability route.
- **Gemini 3.1 Pro Preview** (A = Qwen3.5-397B-A17B (CON); B = Qwen 3.6 Max Preview (PRO)): Side A wins by cleanly dismantling Side B's mechanism. A successfully proves that B's 'commercial deployment' gate fails to stop the worst catastrophic risks (which B admits are out of scope for personal downloads of open weights) while simultaneously imposing massive compliance costs on downstream EU businesses (which B inadvertently conceded when discussing integrators).
  Most decisive rebuttal noted: Side A's A2 in Rebuttal 2 flawlessly catches Side B in a contradiction, using B's own rule that 'integrators bear the burden' to prove the policy acts as a massive compliance tax on every downstream European business.
- **Kimi K2.6** (A = Qwen3.5-397B-A17B (CON); B = Qwen 3.6 Max Preview (PRO)): Side A (CON) won because it exposed critical solvency and cost problems with mandatory licensing that Side B (PRO) never fully repaired. CON effectively turned PRO's open-weights defense into an economic liability: by conceding that downstream commercial integrators trigger licensing requirements, PRO validated CON's claim that the regime acts as a compliance tax on European SMEs and adopters, not merely a targeted gate on frontier developers. This undermined PRO's proportionality and competitiveness arguments. CON's sovereignty critique—that licensing drives frontier development offshore without stopping open-weight propagation—also remained largely unanswered across the final speeches. While PRO mounted a theoretically compelling case about unpredictable emergent capabilities and irreversible harms, CON showed that risk-based frameworks can incorporate capability thresholds and iterative pre-deployment testing without licensing's rigid, enforceability-fraught structure. By the close of the debate, CON had the cleaner path to victory: licensing fails the enforceability test (porous in an open-weight ecosystem), fails the economic test (integrator burdens stagnate adoption), and sacrifices EU digital sovereignty, whereas adaptive governance targets actual harms without these structural drawbacks.
  Most decisive rebuttal noted: CON's second rebuttal (A4.1–A4.3), where it seized on PRO's admission that commercial integrators trigger the license to demonstrate that the regime imposes due-diligence costs on every downstream business, turning PRO's "targeted gate" argument into a broad compliance tax on the EU economy.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260814a__debate_all_templates`
- Topic ID: `prop_0604`
- Side-swap group ID: `prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__tpl_placement_active_20260320f`
- Raw paired winner: **Qwen 3.6 Max Preview**
- Mean normalized margin for Qwen3.5-397B-A17B: `-0.74`
- Complete side swap: `yes`
- Included in ratings: `yes`
