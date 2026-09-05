# Debate Matchup Judgment Report

**Claude Opus 4.8 (high)** vs **Baidu Ernie 5.1**

- Paired result: **Claude Opus 4.8 (high)**
- Mean entertainment: `7.50 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Political campaigns should be prohibited from using behavioral micro-targeting based on inferred psychological or emotional profiles.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0033__claude-opus-4-8-adaptive__ernie-5.1__s0__tpl_placement_active_20260320f.md): PRO = **Claude Opus 4.8 (high)**, CON = **Baidu Ernie 5.1**
- [Debate B transcript](../../../transcripts/prop_0033__ernie-5.1__claude-opus-4-8-adaptive__s1__tpl_placement_active_20260320f.md): PRO = **Baidu Ernie 5.1**, CON = **Claude Opus 4.8 (high)**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_glm53_coverage_20260904a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0033__claude-opus-4-8-adaptive__ernie-5.1__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Claude Opus 4.8 (high)**, CON = **Baidu Ernie 5.1**
- Judged result: Unanimous `3-0` for **Claude Opus 4.8 (high)**.
- Entertainment scores: `8`, `7`, `7`
- Mean signed raw margin (PRO+): `+2.17`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Baidu Ernie 5.1 (CON); B = Claude Opus 4.8 (high) (PRO) | Claude Opus 4.8 (high) | +2.0 | +2.14 | 8.0 |
| Grok 4.3 | A = Baidu Ernie 5.1 (CON); B = Claude Opus 4.8 (high) (PRO) | Claude Opus 4.8 (high) | +2.5 | +3.00 | 7.0 |
| Qwen 3.6 Max Preview | A = Baidu Ernie 5.1 (CON); B = Claude Opus 4.8 (high) (PRO) | Claude Opus 4.8 (high) | +2.0 | +2.00 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Baidu Ernie 5.1 (CON); B = Claude Opus 4.8 (high) (PRO)): B won by keeping the motion narrowly focused on inferred psychological and emotional profiling rather than ordinary voter outreach. A’s early case leaned on examples like GOTV and ordinary segmentation, which B persuasively excluded from the ban. A’s strongest route was regulation over prohibition, but B effectively argued that if the practice is definable and auditable, the same evidence can support a ban, while A never established a legitimate democratic value for exploiting inferred vulnerability profiles.
  Most decisive rebuttal noted: B’s decisive rebuttal was the line-drawing turn: once A conceded inferred emotional profiles are concrete and auditable, B used that to collapse A’s vagueness objection and reframe the debate as whether an identifiable manipulation tool should be licensed or prohibited.
- **Grok 4.3** (A = Baidu Ernie 5.1 (CON); B = Claude Opus 4.8 (high) (PRO)): Side B wins because it maintained a clean distinction between psychological profiling and ordinary segmentation, forced and exploited A's concession that the line is auditable, answered pressure questions directly, and delivered sharper weighing on enforcement and deterrence across rounds.
  Most decisive rebuttal noted: B's Rebuttal 2 (B4) turning A's auditability concession into a clean enforcement comparison while neutralizing both pressure questions.
- **Qwen 3.6 Max Preview** (A = Baidu Ernie 5.1 (CON); B = Claude Opus 4.8 (high) (PRO)): Side B (PRO) won by forcing a decisive concession on enforceability. CON initially claimed the line between psychological profiling and ordinary segmentation was a "mirage," but under pressure admitted the inference step is a "concrete, auditable act." PRO expertly leveraged this in Rebuttal 2 and Closing: if the practice is auditable for CON's proposed regulation, it is equally prosecutable under a ban, neutralizing CON's core "drives underground" and "unenforceable" arguments. PRO's comparative weighing (ban turns the paper trail into a conviction rather than a paperwork scandal) was cleaner and logically airtight, while CON's case collapsed into internal contradiction.
  Most decisive rebuttal noted: Side B's Rebuttal 2, where it answered CON's pressure questions by clarifying the enforceable conduct (data contracts and model specs), then turned CON's own answers against them by showing that if the line is clear enough to regulate, it is clear enough to ban, completely undercutting CON's route to victory.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0033__ernie-5.1__claude-opus-4-8-adaptive__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Baidu Ernie 5.1**, CON = **Claude Opus 4.8 (high)**
- Judged result: Split `2-1` for **Claude Opus 4.8 (high)**.
- Entertainment scores: `8`, `7`, `8`
- Mean signed raw margin (PRO+): `-0.73`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Claude Opus 4.8 (high) (CON); B = Baidu Ernie 5.1 (PRO) | Baidu Ernie 5.1 | +0.8 | +0.86 | 8.0 |
| Grok 4.3 | A = Claude Opus 4.8 (high) (CON); B = Baidu Ernie 5.1 (PRO) | Claude Opus 4.8 (high) | -1.5 | -1.80 | 7.0 |
| Qwen 3.6 Max Preview | A = Claude Opus 4.8 (high) (CON); B = Baidu Ernie 5.1 (PRO) | Claude Opus 4.8 (high) | -1.5 | -1.50 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Claude Opus 4.8 (high) (CON); B = Baidu Ernie 5.1 (PRO)): Side B wins narrowly. Side A made the sharper rhetorical and enforcement attacks, especially pressing whether “worried” and “anxious” can be legally separated. But Side B preserved the more persuasive interpretation of the motion: the ban is not on emotion or all inference, but on covert behavioral micro-targeting using inferred psychological or emotional profiles. B gave an administrable enough distinction through hidden behavioral models, vendor contracts, and inferred mental-state labels, while A’s “all targeting is inference” argument overreached and did not fully answer the narrower category the proposition targets. B’s autonomy and consent harms therefore remained live.
  Most decisive rebuttal noted: Side B’s answer that the motion targets inferred mental-state profiles rather than ordinary demographic inference was the key rebuttal, though Side A’s “worried versus anxious” challenge made the round close.
- **Grok 4.3** (A = Claude Opus 4.8 (high) (CON); B = Baidu Ernie 5.1 (PRO)): Side A wins because it consistently showed the ban rests on an incoherent and unadministrable distinction between types of inference that cannot separate ordinary targeting from the prohibited activity, while Side B's line based on data source or "anxious vs worried" collapsed under pressure and enforcement claims lacked mechanism against offshore actors. Side A answered pressure questions directly and maintained the decisive comparison throughout.
  Most decisive rebuttal noted: Side A's Rebuttal 2 directly dismantled B's answers to the pressure questions by showing the "source of data" test and enforcement claims were circular and unenforceable.
- **Qwen 3.6 Max Preview** (A = Claude Opus 4.8 (high) (CON); B = Baidu Ernie 5.1 (PRO)): CON wins by successfully collapsing PRO’s core distinction between permissible demographic targeting and banned psychological profiling. CON demonstrated that all modern ad targeting inherently infers receptivity or emotional states from behavioral data, making PRO’s proposed legal boundary a semantic distinction (“worried” vs. “anxious”) rather than a workable rule. CON also won the enforcement clash by showing that a prohibition would primarily chill accountable domestic campaigns while doing little to stop already-opaque offshore actors, whereas PRO’s “sever market demand” argument lacked a concrete mechanism. CON’s sharper pressure questions, direct A1/A2 answers, and consistent comparative weighing (“performance, not protection”) provided a cleaner path to victory.
  Most decisive rebuttal noted: The exchange over the administrability of the ban’s boundary. PRO attempted to draw a line based on data source (observable vs. inferred psychological state), but CON’s Rebuttal 1 and 2 effectively showed that inference is inherent to all targeting, reducing PRO’s test to a “thesaurus, not a legal test.” CON’s closing point that browsing patterns are also observable behavioral exhaust definitively undercut PRO’s final attempt to salvage the line.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
- Topic ID: `prop_0033`
- Side-swap group ID: `prop_0033__claude-opus-4-8-adaptive__ernie-5.1__tpl_placement_active_20260320f`
- Raw paired winner: **Claude Opus 4.8 (high)**
- Mean normalized margin for Claude Opus 4.8 (high): `+1.60`
- Complete side swap: `yes`
- Included in ratings: `yes`
