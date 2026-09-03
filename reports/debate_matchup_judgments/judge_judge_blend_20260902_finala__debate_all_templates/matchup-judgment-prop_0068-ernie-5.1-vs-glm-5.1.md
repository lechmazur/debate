# Debate Matchup Judgment Report

**Baidu Ernie 5.1** vs **GLM-5.1**

- Paired result: **GLM-5.1**
- Mean entertainment: `7.33 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Major platforms should be required to label not only AI-generated content but also AI-optimized persuasion campaigns targeted to specific users or micro-groups.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0068__ernie-5.1__glm-5.1__s0__tpl_placement_active_20260320f.md): PRO = **Baidu Ernie 5.1**, CON = **GLM-5.1**
- [Debate B transcript](../../../transcripts/prop_0068__glm-5.1__ernie-5.1__s1__tpl_placement_active_20260320f.md): PRO = **GLM-5.1**, CON = **Baidu Ernie 5.1**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260902_finala.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0068__ernie-5.1__glm-5.1__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Baidu Ernie 5.1**, CON = **GLM-5.1**
- Judged result: Unanimous `3-0` for **GLM-5.1**.
- Entertainment scores: `8`, `7`, `8`
- Mean signed raw margin (PRO+): `-1.77`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Baidu Ernie 5.1 (PRO); B = GLM-5.1 (CON) | GLM-5.1 | -1.8 | -1.93 | 7.0 |
| Gemini 3.1 Pro Preview | A = GLM-5.1 (CON); B = Baidu Ernie 5.1 (PRO) | GLM-5.1 | -2.0 | -1.67 | 8.0 |
| Qwen 3.6 Max Preview | A = GLM-5.1 (CON); B = Baidu Ernie 5.1 (PRO) | GLM-5.1 | -1.5 | -1.50 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Baidu Ernie 5.1 (PRO); B = GLM-5.1 (CON)): Side B won by making implementation the decisive clash. Side A established a real manipulation harm and a plausible transparency principle, but its case narrowed from AI-optimized persuasion to AI-generated personalized copy and leaned on overconfident claims about detectability. Side B consistently showed that the rule creates gray zones, requires process auditing rather than simple disclosure, can be gamed by human-in-the-loop workflows, and may create false confidence rather than useful transparency. A's imperfect-transparency weighing remained live, but B answered it more directly and comparatively.
  Most decisive rebuttal noted: Side B's first rebuttal was most decisive: it attacked A's technical line by explaining unreliable text detection, voluntary watermarking, local models, and messy human-AI workflows, undermining both enforceability and the claim that the label would be non-arbitrary.
- **Gemini 3.1 Pro Preview** (A = GLM-5.1 (CON); B = Baidu Ernie 5.1 (PRO)): Side A won by successfully dismantling Side B's enforcement mechanism, forcing Side B to concede that text detection is unreliable. When Side B pivoted to arguing that 'imperfect transparency is better than none,' Side A decisively countered with the 'broken compass' analogy, proving that performative transparency creates false confidence that is worse than the status quo.
  Most decisive rebuttal noted: Side A's Rebuttal 2 effectively contrasted the simple factual check of political ad funding with the intrusive audit regime required for AI generation, destroying Side B's core analogy.
- **Qwen 3.6 Max Preview** (A = GLM-5.1 (CON); B = Baidu Ernie 5.1 (PRO)): CON wins by successfully dismantling the feasibility and net benefit of the proposed labeling regime. While PRO built a strong normative case for informational symmetry, CON exposed critical technical and practical flaws: text-based AI detection is unreliable, watermarking is easily bypassed, and the line between AI-optimized and human-edited content is inherently gray. When PRO conceded imperfect enforcement and pivoted to "some awareness is better than none," CON effectively turned that concession into a liability, arguing that a broken label creates false confidence and performative transparency that is worse than the status quo. CON’s "broken compass" framing and sharper comparative weighing gave a cleaner reason to vote against the motion.
  Most decisive rebuttal noted: CON’s Rebuttal 2 sharply dismantled PRO’s concession of imperfect enforcement by introducing the "performative transparency" and "false confidence" framework. By explaining how a flawed label causes users to lower their guard for unlabeled (but still manipulated) content, CON turned PRO’s main weighing argument into a decisive net-harm claim, effectively closing off PRO’s path to victory.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0068__glm-5.1__ernie-5.1__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **GLM-5.1**, CON = **Baidu Ernie 5.1**
- Judged result: Unanimous `3-0` for **GLM-5.1**.
- Entertainment scores: `7`, `7`, `7`
- Mean signed raw margin (PRO+): `+1.60`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = GLM-5.1 (PRO); B = Baidu Ernie 5.1 (CON) | GLM-5.1 | +1.3 | +1.39 | 7.0 |
| Gemini 3.1 Pro Preview | A = Baidu Ernie 5.1 (CON); B = GLM-5.1 (PRO) | GLM-5.1 | +2.0 | +1.67 | 7.0 |
| Qwen 3.6 Max Preview | A = Baidu Ernie 5.1 (CON); B = GLM-5.1 (PRO) | GLM-5.1 | +1.5 | +1.50 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = GLM-5.1 (PRO); B = Baidu Ernie 5.1 (CON)): Side A won by making the central distinction clearer: labeling advanced AI-optimized persuasion is not the same as labeling every targeted ad. Side B’s strongest point was definitional overbreadth and label fatigue, but it repeatedly leaned on examples like nonprofits, shoe ads, and bakeries without proving that neutral disclosure would meaningfully punish them or that they fall within A’s narrower advanced-targeting category. A’s pricing/platform-capability response was somewhat asserted, but it gave a workable comparative answer: platforms already operationalize tiers of targeting, so disclosure can attach to those tools rather than advertiser intent. B’s intent objection was less decisive because the proposition concerns AI-optimized persuasion campaigns broadly, not only malicious manipulation.
  Most decisive rebuttal noted: A’s response that platforms need not read minds because they know which advanced AI targeting capabilities they sell and deploy was the most decisive exchange; it directly weakened B’s feasibility and overbreadth route.
- **Gemini 3.1 Pro Preview** (A = Baidu Ernie 5.1 (CON); B = GLM-5.1 (PRO)): Side B wins decisively by establishing a clear, enforceable mechanism for the label—the deployment of advanced, premium-priced psychographic targeting bundles. Side A relies heavily on the claim that platforms cannot determine the 'intent' (e.g., distinguishing a nonprofit from disinformation), but Side B successfully argues that the label targets the *mechanism* of vulnerability-mapping, making intent irrelevant. A's Turn 4 was also clipped for exceeding the word limit, slightly hindering their execution.
  Most decisive rebuttal noted: B4.1 and B4.2 effectively dismantled A's claim that no line exists between basic and advanced targeting by pointing out that platforms already operationalize and monetize this exact distinction through parameter stacking and premium pricing.
- **Qwen 3.6 Max Preview** (A = Baidu Ernie 5.1 (CON); B = GLM-5.1 (PRO)): PRO wins by successfully grounding the labeling trigger in observable platform commercial practices rather than advertiser intent. CON's core objection hinged on platforms being unable to discern "persuasion intent," arguing this would cause overlabeling and fatigue. PRO cleanly pivoted to labeling the use of advanced AI-optimization tiers themselves, noting platforms already distinguish these capabilities via premium pricing and parameter bundling. This made the proposal technically feasible and directly neutralized CON's definitional collapse argument. CON repeated the intent objection in later rounds but never adequately answered PRO's point that transparency should attach to the mechanism used, not the moral worth of the advertiser. PRO also turned the fatigue argument effectively and maintained sharper rhetorical focus on the asymmetry of algorithmic vulnerability targeting.
  Most decisive rebuttal noted: PRO's Rebuttal 2 answer to CON's pressure questions, where PRO distinguished basic single-parameter targeting from stacked psychographic/behavioral bundles and tied the labeling trigger to the commercial tiers platforms already sell. This directly resolved the feasibility clash and exposed CON's reliance on "intent" as a misplaced burden.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260902_finala__debate_all_templates`
- Topic ID: `prop_0068`
- Side-swap group ID: `prop_0068__ernie-5.1__glm-5.1__tpl_placement_active_20260320f`
- Raw paired winner: **GLM-5.1**
- Mean normalized margin for Baidu Ernie 5.1: `-1.61`
- Complete side swap: `yes`
- Included in ratings: `yes`
