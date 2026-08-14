# Debate Matchup Judgment Report

**Baidu Ernie 5.1** vs **Qwen 3.7 Max**

- Paired result: **Qwen 3.7 Max**
- Mean entertainment: `7.33 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Employers should be legally required to disclose when hiring and firing decisions are meaningfully influenced by automated decision systems.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0677__ernie-5.1__qwen3.7-max__s0__tpl_placement_active_20260320f.md): PRO = **Baidu Ernie 5.1**, CON = **Qwen 3.7 Max**
- [Debate B transcript](../../../transcripts/prop_0677__qwen3.7-max__ernie-5.1__s1__tpl_placement_active_20260320f.md): PRO = **Qwen 3.7 Max**, CON = **Baidu Ernie 5.1**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260814a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0677__ernie-5.1__qwen3.7-max__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Baidu Ernie 5.1**, CON = **Qwen 3.7 Max**
- Judged result: Split `2-1` for **Baidu Ernie 5.1**.
- Entertainment scores: `8`, `7`, `7`
- Mean signed raw margin (PRO+): `+0.27`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen 3.7 Max (CON); B = Baidu Ernie 5.1 (PRO) | Baidu Ernie 5.1 | +1.6 | +1.71 | 7.0 |
| Gemini 3.1 Pro Preview | A = Baidu Ernie 5.1 (PRO); B = Qwen 3.7 Max (CON) | Qwen 3.7 Max | -2.0 | -1.67 | 8.0 |
| Grok 4.3 | A = Baidu Ernie 5.1 (PRO); B = Qwen 3.7 Max (CON) | Baidu Ernie 5.1 | +1.2 | +1.44 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen 3.7 Max (CON); B = Baidu Ernie 5.1 (PRO)): Side B won by making disclosure feel like the necessary gateway to audits, disparate-impact claims, and worker contestation, while keeping the mandate narrow enough to blunt trade-secret and cost objections. Side A’s strongest points were the ambiguity of “meaningfully influenced” in hybrid hiring workflows and the risk of boilerplate notices, but its abandonment/regression story remained more speculative than B’s transparency benefit. B also more effectively framed A’s outcome-only alternative as circular: workers often cannot challenge or investigate algorithmic bias if they do not know automation shaped the decision.
  Most decisive rebuttal noted: B’s answer that disclosure need not reveal proprietary code but can trigger existing discovery, protective orders, and audits was the decisive exchange; it neutralized A’s “receipt, not explanation” attack and preserved B’s core claim that minimal notice is still practically useful.
- **Gemini 3.1 Pro Preview** (A = Baidu Ernie 5.1 (PRO); B = Qwen 3.7 Max (CON)): Side B won by successfully differentiating the multi-stage, hybrid nature of modern hiring from Side A's primary analogy of credit scoring. Side B also cleanly shifted the focus of the compliance burden from the trivial cost of the notice itself to the unpredictable liability of litigating the "meaningfully influenced" threshold, making the regression argument highly plausible.
  Most decisive rebuttal noted: Side B's first and second rebuttals dismantling the credit scoring analogy by pointing out that hiring is a multi-stage funnel and hiring software is an auxiliary tool, unlike core banking models.
- **Grok 4.3** (A = Baidu Ernie 5.1 (PRO); B = Qwen 3.7 Max (CON)): Side A built the stronger path by directly answering Pressure Questions with existing legal tools (EEOC discovery, protective orders) that make disclosure functional without exposing IP, then crystallizing that outcome regulation is circular without first knowing an algorithm was used. Side B's regression and vagueness attacks were persistent but left unneutralized only on the margins; A's rebuttals materially damaged both while preserving the minimal-scope claim.
  Most decisive rebuttal noted: A's Rebuttal 2 A1/A2 exchange neutralized B's two live pressure questions with concrete mechanisms already operating in credit and Title VII law.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0677__qwen3.7-max__ernie-5.1__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen 3.7 Max**, CON = **Baidu Ernie 5.1**
- Judged result: Unanimous `3-0` for **Qwen 3.7 Max**.
- Entertainment scores: `8`, `7`, `7`
- Mean signed raw margin (PRO+): `+1.83`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Baidu Ernie 5.1 (CON); B = Qwen 3.7 Max (PRO) | Qwen 3.7 Max | +2.0 | +2.14 | 7.0 |
| Gemini 3.1 Pro Preview | A = Qwen 3.7 Max (PRO); B = Baidu Ernie 5.1 (CON) | Qwen 3.7 Max | +2.0 | +1.67 | 8.0 |
| Grok 4.3 | A = Qwen 3.7 Max (PRO); B = Baidu Ernie 5.1 (CON) | Qwen 3.7 Max | +1.5 | +1.80 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Baidu Ernie 5.1 (CON); B = Qwen 3.7 Max (PRO)): Side B won by making the central enforcement problem clearer: existing rights are weak if applicants never know an automated system meaningfully influenced the decision, so disclosure is a prerequisite to litigation, review, and regulation. Side A raised plausible concerns about vagueness, trade secrets, and chilling useful tools, but these were comparatively less developed and often rested on overconfident claims that discovery or targeted audits can work without initial notice. B's minimal-disclosure framing also blunted the trade-secret objection.
  Most decisive rebuttal noted: Side B's catch-22 rebuttal was decisive: discovery only helps after a lawsuit exists, but without disclosure a rejected applicant may lack the factual basis to sue. Side A repeatedly asserted discovery and audits as alternatives but never fully solved that threshold problem.
- **Gemini 3.1 Pro Preview** (A = Qwen 3.7 Max (PRO); B = Baidu Ernie 5.1 (CON)): Side A won by successfully exposing a procedural catch-22 in Side B's reliance on existing litigation and discovery. A demonstrated convincingly that without a disclosure mandate, applicants lack the initial factual basis required to file a lawsuit and reach the discovery phase, effectively neutralizing B's primary alternative.
  Most decisive rebuttal noted: Side A's Rebuttal 2 answers perfectly crystallized the "what vs. how" distinction on trade secrets and effectively weaponized the procedural reality of civil litigation against Side B's discovery claims.
- **Grok 4.3** (A = Qwen 3.7 Max (PRO); B = Baidu Ernie 5.1 (CON)): Side A wins because its catch-22 argument (disclosure needed to file suit and trigger discovery/audits) survived B's responses, exposed a real enforcement gap, and was crystallized cleanly in later rounds. B's alternatives remained abstract and did not neutralize the procedural barrier.
  Most decisive rebuttal noted: A's direct A1/A2 answers in Rebuttal 2, showing that generic rejections prevent reaching discovery or targeted audits.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260814a__debate_all_templates`
- Topic ID: `prop_0677`
- Side-swap group ID: `prop_0677__ernie-5.1__qwen3.7-max__tpl_placement_active_20260320f`
- Raw paired winner: **Qwen 3.7 Max**
- Mean normalized margin for Baidu Ernie 5.1: `-0.69`
- Complete side swap: `yes`
- Included in ratings: `yes`
