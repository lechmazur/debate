# Debate Matchup Judgment Report

**GPT-5.4 (high)** vs **GPT-5.4 (no reasoning)**

- Paired result: **GPT-5.4 (high)**
- Mean entertainment: `7.62 / 10`
- Judge decisions: `8` across two side-swapped debates

**Motion:** Courts should recognize a limited “right to explanation” when automated systems significantly affect access to housing, credit, employment, or healthcare.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0517__gpt-5.4-high__gpt-5.4-none__s0__tpl_placement_active_20260320f.md): PRO = **GPT-5.4 (high)**, CON = **GPT-5.4 (no reasoning)**
- [Debate B transcript](../../../transcripts/prop_0517__gpt-5.4-none__gpt-5.4-high__s1__tpl_placement_active_20260320f.md): PRO = **GPT-5.4 (no reasoning)**, CON = **GPT-5.4 (high)**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_glm53_coverage_20260904a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0517__gpt-5.4-high__gpt-5.4-none__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **GPT-5.4 (high)**, CON = **GPT-5.4 (no reasoning)**
- Judged result: Unanimous `4-0` for **GPT-5.4 (high)**.
- Entertainment scores: `8`, `7`, `7`, `8`
- Mean signed raw margin (PRO+): `+1.50`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| Gemini 3.1 Pro Preview | A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO) | GPT-5.4 (high) | +2.0 | +1.67 | 8.0 |
| Grok 4.3 | A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO) | GPT-5.4 (high) | +1.5 | +1.80 | 7.0 |
| Kimi K2.6 | A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO) | GPT-5.4 (high) | +1.3 | +1.30 | 7.0 |
| Qwen 3.6 Max Preview | A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO) | GPT-5.4 (high) | +1.2 | +1.20 | 8.0 |

### Judge Notes

- **Gemini 3.1 Pro Preview** (A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO)): Side B won by successfully framing the 'right to explanation' as an indispensable gateway to existing legal remedies. Side B provided clear, concrete examples of how an explanation would work in practice, effectively neutralizing Side A's arguments about process inflation and the impossibility of explaining probabilistic models. Side A's reliance on existing statutory remedies for 'adverse action' ultimately undermined its own claim that algorithms are too complex to explain, and Side A suffered from repeated word-count clipping.
  Most decisive rebuttal noted: Side B's A1 and A2 in Rebuttal 2, which used concrete examples (delinquency records, triage tools) to prove that explaining hybrid probabilistic models is both possible and necessary to activate existing rights.
- **Grok 4.3** (A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO)): Side B won by establishing explanation as the necessary gateway that activates existing remedies, directly answering pressure questions with workable standards and concrete examples like wrong eviction records; Side A’s clipped speeches and failure to neutralize this comparison left its indeterminacy and hybrid-system arguments weaker after the full exchange.
  Most decisive rebuttal noted: B’s Rebuttal 2 (A1/A2 answers) that supplied principal-factors standards and showed how the eviction-record case activates data-correction tools without duplication.
- **Kimi K2.6** (A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO)): PRO successfully defended a limited gateway right by showing that without knowing the principal factors behind algorithmic denials, existing remedies for discrimination, data correction, and appeal are often unusable. CON mounted a serious administrability challenge, but PRO answered it with concrete, workable examples of hybrid-system explanations in lending, housing, and healthcare. CON’s failure to stay within word limits in three separate speeches—including a clipped final weighing in Rebuttal 2—is a material execution cost that compounded its inability to fully neutralize PRO’s gateway argument. PRO’s framing that imperfect accountability still beats zero accountability, and that opacity should disqualify systems from essential decisions, created the cleaner path to victory.
  Most decisive rebuttal noted: PRO’s Rebuttal 2 (B4), especially the direct answer to CON’s Q1: providing concrete examples of legally adequate explanations for hybrid lender and hospital decisions, and showing how the right activates rather than duplicates existing remedies.
- **Qwen 3.6 Max Preview** (A = GPT-5.4 (no reasoning) (CON); B = GPT-5.4 (high) (PRO)): Side B (PRO) wins by successfully framing the limited right to explanation as a necessary "gateway" that activates existing legal remedies, directly neutralizing CON's core claim that current law already covers these harms. When pressed on administrability and hybrid/probabilistic models, PRO provided concrete, workable examples of what a legally adequate explanation looks like (principal factors, data categories, workflow role), defusing CON's warning about boilerplate and forced oversimplification. CON's tradeoff argument (strict enforcement triggers litigation over wording; loose enforcement yields misleading summaries) was sharp but ultimately conceded that transparency is needed while disputing the legal vehicle. PRO's consistent narrowing of the scope and effective burden-flip on opacity ("if it cannot be explained, it should not govern essential goods") gave a cleaner, more decisive path to victory. CON's repeated clipping was a minor execution cost, but the substantive gap came from PRO's superior handling of the gateway clash and clearer operationalization of the standard under pressure.
  Most decisive rebuttal noted: Side B's Rebuttal 2 directly answered CON's pressure questions by operationalizing the explanation standard for hybrid systems (e.g., listing specific factors like debt-to-income ratio or prior utilization alongside human policy application) and demonstrating how the right activates, rather than duplicates, existing remedies. This turned CON's administrability offense and crystallized the practical necessity of the proposal.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0517__gpt-5.4-none__gpt-5.4-high__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **GPT-5.4 (no reasoning)**, CON = **GPT-5.4 (high)**
- Judged result: Split `3-1` for **GPT-5.4 (high)**.
- Entertainment scores: `8`, `7`, `8`, `8`
- Mean signed raw margin (PRO+): `-0.68`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| Gemini 3.1 Pro Preview | A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO) | GPT-5.4 (high) | -1.5 | -1.25 | 8.0 |
| Grok 4.3 | A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO) | GPT-5.4 (no reasoning) | +1.5 | +1.80 | 7.0 |
| Kimi K2.6 | A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO) | GPT-5.4 (high) | -1.5 | -1.50 | 8.0 |
| Qwen 3.6 Max Preview | A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO) | GPT-5.4 (high) | -1.2 | -1.20 | 8.0 |

### Judge Notes

- **Gemini 3.1 Pro Preview** (A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO)): Side A wins by successfully turning Side B's "limited right" constraint against them. Side A demonstrates that a limited, plain-language explanation of a complex model will inevitably result in "sanitized summaries" and "explainability theater" rather than exposing the proxy discrimination or errors Side B wants to catch.
  Most decisive rebuttal noted: Side A's Rebuttal 2 cleanly severs Side B's mechanism by explaining that a personalized list of 'main factors' is actually the worst detector for proxy discrimination in complex models, directly neutralizing Side B's core argument.
- **Grok 4.3** (A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO)): Side B built the stronger overall case by consistently showing that existing remedies require explanation to be usable, directly answered pressure questions, and crystallized the core clash in closing; Side A’s vagueness and theater critiques were solid but less decisive after exchange.
  Most decisive rebuttal noted: B2.1-B2.2 bridge response and B4.1-B4.2 answers to questions, which forced CON to defend concrete safeguards without the missing link.
- **Kimi K2.6** (A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO)): CON (Side A) won by showing that PRO's "limited" right to explanation collapses into either existing concrete safeguards—making it redundant—or into vague judicial grading of sanitized prose—making it misleading. CON's distinction between data access and model rationale, and the "explainability theater" frame, proved more durable across the exchange. PRO's bridge metaphor was powerful, but never fully answered how courts could verify the accuracy of post-hoc summaries in complex models, and their own description of the right ("principal reasons," "key data," "meaningful path") largely restated the record-access and review procedures CON already endorsed. Both sides argued skillfully, but CON left the decisive clash—concrete accountability versus performative explanation—cleaner and more intact.
  Most decisive rebuttal noted: CON's collapse in Rebuttal 1 and 2 of PRO's limited right into existing procedures: showing that PRO's test of "principal reasons," "key data categories," and a "meaningful path" either duplicated concrete record-access and review remedies or invited judges to litigate vague prose standards while real harms went unaddressed.
- **Qwen 3.6 Max Preview** (A = GPT-5.4 (high) (CON); B = GPT-5.4 (no reasoning) (PRO)): CON wins by successfully framing PRO’s “limited explanation” as explainability theater that invites sanitized, post-hoc summaries rather than genuine accountability. While PRO built a strong normative case that explanation is a necessary “bridge” to contest decisions, CON materially damaged that route by showing that in complex models, “main factors” often launder proxy discrimination and force judges to grade boilerplate prose. CON’s alternative—focusing on concrete record access, validation checks, anti-bias enforcement, and outcome-based challenges—proved more workable and directly targeted the harms without the procedural bloat. CON also handled pressure questions more cleanly, turning PRO’s vagueness on the legal test back against them. Both sides were rhetorically sharp, but CON’s comparative weighing on practical implementation was decisive.
  Most decisive rebuttal noted: CON’s consistent attack on PRO’s “limited explanation” as performative boilerplate (“grading prose” vs. “concrete accountability”), effectively arguing that sanitized factor lists hide interaction-based proxy discrimination while offering a cleaner, verification-focused alternative.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
- Topic ID: `prop_0517`
- Side-swap group ID: `prop_0517__gpt-5.4-high__gpt-5.4-none__tpl_placement_active_20260320f`
- Raw paired winner: **GPT-5.4 (high)**
- Mean normalized margin for GPT-5.4 (high): `+1.01`
- Complete side swap: `yes`
- Included in ratings: `yes`
