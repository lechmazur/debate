# Debate Matchup Judgment Report

**Qwen 3.6 Max Preview** vs **Qwen 3.7 Max**

- Paired result: **Qwen 3.6 Max Preview**
- Mean entertainment: `7.33 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0621__qwen3.6-max-preview__qwen3.7-max__s0__tpl_placement_active_20260320f.md): PRO = **Qwen 3.6 Max Preview**, CON = **Qwen 3.7 Max**
- [Debate B transcript](../../../transcripts/prop_0621__qwen3.7-max__qwen3.6-max-preview__s1__tpl_placement_active_20260320f.md): PRO = **Qwen 3.7 Max**, CON = **Qwen 3.6 Max Preview**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_glm53_coverage_20260904a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0621__qwen3.6-max-preview__qwen3.7-max__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen 3.6 Max Preview**, CON = **Qwen 3.7 Max**
- Judged result: Unanimous `3-0` for **Qwen 3.6 Max Preview**.
- Entertainment scores: `8`, `7`, `7`
- Mean signed raw margin (PRO+): `+1.57`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen 3.6 Max Preview (PRO); B = Qwen 3.7 Max (CON) | Qwen 3.6 Max Preview | +1.4 | +1.50 | 7.0 |
| Gemini 3.1 Pro Preview | A = Qwen 3.7 Max (CON); B = Qwen 3.6 Max Preview (PRO) | Qwen 3.6 Max Preview | +1.5 | +1.25 | 8.0 |
| Grok 4.3 | A = Qwen 3.6 Max Preview (PRO); B = Qwen 3.7 Max (CON) | Qwen 3.6 Max Preview | +1.8 | +2.16 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen 3.6 Max Preview (PRO); B = Qwen 3.7 Max (CON)): Side A won because it kept the debate centered on the strongest point: when prosecutors use a risk score to restrict liberty, the defense must be able to test the tool's foundation. Side B raised serious practical concerns about costs, indigent defendants, trade secrets, and vendor exit, but relied on overconfident assertions that vendors would inevitably leave and that opaque tools reduce bias. Side A gave cleaner answers through protective orders, procurement conditions, subpoenas, inadmissibility if disclosure is unavailable, and disaggregated error rates. The due process and adversarial-testing frame outweighed Side B's administrative objections.
  Most decisive rebuttal noted: Side A's second rebuttal was decisive: it directly answered the ownership and error-rate pressure questions, then reframed Side B's vendor and delay arguments as attempts to outsource constitutional duties to private licensors.
- **Gemini 3.1 Pro Preview** (A = Qwen 3.7 Max (CON); B = Qwen 3.6 Max Preview (PRO)): Side B won by successfully framing the issue around fundamental due process and the right to test evidence, effectively using the mechanics of government procurement and protective orders to dismantle Side A's claim that vendors would flee the market. Side B's direct, substantive answers to the Pressure Questions neutralized Side A's strongest traps.
  Most decisive rebuttal noted: Side B's A2 in Rebuttal 2 dismantled Side A's trap about which error rate to use, specifying disaggregated false-positive and false-negative rates to expose bias, thereby strengthening their own case while answering the question.
- **Grok 4.3** (A = Qwen 3.6 Max Preview (PRO); B = Qwen 3.7 Max (CON)): Side A built the stronger case by establishing due process as the decisive burden and then directly neutralizing CON's practical objections (IP ownership, resource inequality, vendor flight) with contract mechanisms and shared auditing precedents. B's market-preservation and "advisory tool" framing was never fully reconciled with the reality of judicial anchoring, and B's answers to pressure questions remained evasive on cross-examination feasibility. A's later speeches narrowed and resolved the clash; B's repeated the same trade-off without advancing weighing.
  Most decisive rebuttal noted: A4 directly answers both B pressure questions with concrete legal mechanisms and disaggregated metrics, then uses those answers to flip the "two-tiered justice" argument back on secrecy itself.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0621__qwen3.7-max__qwen3.6-max-preview__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen 3.7 Max**, CON = **Qwen 3.6 Max Preview**
- Judged result: Unanimous `3-0` for **Qwen 3.6 Max Preview**.
- Entertainment scores: `8`, `7`, `7`
- Mean signed raw margin (PRO+): `-1.43`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen 3.7 Max (PRO); B = Qwen 3.6 Max Preview (CON) | Qwen 3.6 Max Preview | -1.3 | -1.39 | 7.0 |
| Gemini 3.1 Pro Preview | A = Qwen 3.6 Max Preview (CON); B = Qwen 3.7 Max (PRO) | Qwen 3.6 Max Preview | -1.5 | -1.25 | 8.0 |
| Grok 4.3 | A = Qwen 3.7 Max (PRO); B = Qwen 3.6 Max Preview (CON) | Qwen 3.6 Max Preview | -1.5 | -1.80 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen 3.7 Max (PRO); B = Qwen 3.6 Max Preview (CON)): Side B won a clear but competitive debate by making the mechanism of the mandate the central issue: prosecutors often lack control over proprietary code, disclosure would likely function as a ban, and the fallback is less auditable judicial discretion. Side A had a strong due-process framing and good answers on experts and protective orders, but conceded that discarding tools was acceptable and did not fully answer B’s alternative of independent validation, cohort error analysis, and input challenges. B also more effectively weighed functional fairness against performative transparency.
  Most decisive rebuttal noted: B’s second rebuttal was decisive: it directly answered the pressure questions, reframed verification as black-box statistical replication rather than source-code transfer, and turned A’s “feature, not a bug” concession into a practical harm to defendants.
- **Gemini 3.1 Pro Preview** (A = Qwen 3.6 Max Preview (CON); B = Qwen 3.7 Max (PRO)): Side A won by successfully shifting the debate from an abstract constitutional principle to the practical mechanics of machine learning and systemic fairness. By forcing Side B to concede that the mandate would essentially ban proprietary algorithms, Side A was able to weigh the flaws of unstructured judicial intuition against the benefits of statistically auditable algorithms. Side A's unrefuted point that source code syntax is functionally unreadable for bias—and that independent black-box testing is the actual method for detecting disparate impact—decisively neutralized Side B's main mechanism.
  Most decisive rebuttal noted: Side A's Rebuttal 1 argument that source code transparency does not help detect bias due to non-linear feature interactions, and that statistical validation is the true functional remedy.
- **Grok 4.3** (A = Qwen 3.7 Max (PRO); B = Qwen 3.6 Max Preview (CON)): CON won by establishing that prosecutors lack control over vendor IP, that disclosure would eliminate validated tools, and that existing audits plus input challenges already protect due process; PRO's concession that tool loss is a "feature" handed CON a decisive concession that human discretion is inferior was never rebutted.
  Most decisive rebuttal noted: B's Rebuttal 2 exploiting PRO's "feature not bug" admission while clarifying black-box verification methods answered live pressure more directly than PRO's responses.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
- Topic ID: `prop_0621`
- Side-swap group ID: `prop_0621__qwen3.6-max-preview__qwen3.7-max__tpl_placement_active_20260320f`
- Raw paired winner: **Qwen 3.6 Max Preview**
- Mean normalized margin for Qwen 3.6 Max Preview: `+1.56`
- Complete side swap: `yes`
- Included in ratings: `yes`
