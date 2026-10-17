# LLM Debate Benchmark: Adversarial Multi-Turn Argument Under Opposition

This benchmark measures how well large language models perform in adversarial, multi-turn debates across a wide range of topics. Strong performance requires more than a polished opening: models need broad knowledge, accurate facts under pressure, strong rebuttal, and the ability to remain coherent and responsive over several rounds.

Each matchup runs twice on the **same motion with sides swapped**. A three-model judge panel decides each debate's winner and margin. The published leaderboard uses Bradley-Terry ratings built from complete side-swapped matchups.

---

![Bradley-Terry leaderboard: current models and highlighted predecessors](images/debate_bt_ratings_current_models__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

This chart shows **26 current models and highlighted-model predecessors**, including Muse Spark 1.3, Gemini 3.1 Pro Preview, and Mistral Large 3. The [full historical chart](images/debate_bt_ratings__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png) and leaderboard table below retain the broader public comparison set.

---

## How to read the chart

- Higher bars mean stronger judged debate performance.
- Bradley-Terry is a relative within-pool rating centered near `1500`, not an absolute capability score.
- The grey band spans the **95% robust confidence interval**; darker shading means greater relative density.
- The published order uses Bradley-Terry. Glicko-2 remains a secondary scheduling diagnostic.

## Current snapshot — October 15, 2026

- **62 rated model identities** in the complete stored graph; **59** shown publicly
- **4,223 complete side-swapped matchups**, comprising **8,446 debates**, used for ratings
- **25,896 judge decisions** behind the ratings
- **683 topics** represented in the rated corpus

Opus 5.5's coverage expansion adds **70 complete matchups (140 debates)**. It now also has at least **five fully judged, side-swapped topics against all 25 other displayed models**.

The earlier October 15 highlighted-model coverage expansion adds **192 complete matchups (384 debates)**. Each highlighted model now has at least **five fully judged, side-swapped topics against all 25 other displayed models**: 72 unique pairings, including the selected predecessors. Existing deeper comparisons remain intact. Gemini 3.1 Flash-Lite Preview is retired and no longer routable, so it remains in the historical leaderboard and is hidden from current-model charts.

The earlier October intakes added **Meta Muse Wonder 1.0 (high), Gemini 4 Argon (high), and Mistral Large 4 (high)**. Those two intakes completed **588 of 590 scheduled debates** and saved **1,763 judgments**. One MiMo blank response and one Qwen refusal left two debate directions unavailable. One Grok judgment remained unavailable after an exact retry; both directions of that matchup are excluded from ratings, while its five successful judgments remain archived.

A transcript audit also removed three historical matchups whose motion changed during generation. Their original transcripts and 20 judgments remain archived. Ratings and confidence intervals below use the corrected combined results.

One side-swapped matchup means two debates on the same motion with PRO and CON roles reversed.

### Model and data scopes

| View | Models | Matchups | Purpose |
| --- | ---: | ---: | --- |
| Complete stored rating graph | 62 | 4,298 represented; 4,223 rated | All retained historical and current results |
| Public leaderboard | 59 | 4,041 represented; 3,976 rated after report-time exclusions | Reader-facing ranking |
| September 24 qualitative analysis | 43 | 2,926 complete, or 5,852 debates | 42 public behavior cards and four newcomer dossiers |
| Current-focused comparison charts | 26; 25 with costs | — | Current models plus selected predecessors |

The published judge table contains 26,143 retained decisions; 25,896 belong to complete matchups used for ratings. Archived unavailable-panel and topic-drift results are outside this export. These scopes answer different questions, so their counts are not expected to match. The full leaderboard retains historical comparisons; current-focused charts hide superseded versions except selected predecessors. The September 5 and October 15 blind participant-judging studies are separate diagnostics and do not feed the leaderboard.

## Reader paths

1. **Ranking:** start with the chart above, the [full leaderboard report](reports/debate_leaderboard__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md), and the [Opus 5.5 coverage report](reports/opus55_coverage_20261015_final_analysis.md).
2. **Design checks:** inspect the [pairwise heatmap](#pairwise-view), [judge agreement](#judge-sanity-checks), and [status report](reports/debate_benchmark_status__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md).
3. **How models debate:** use the September 24 [behavior model cards](reports/debate_behavior_model_cards__judge_judge_blend_20260923_finala__debate_all_templates__gpt-5.6-medium.md) and [four September entrant dossiers](reports/debate_model_dossiers__judge_judge_blend_20260923_finala__debate_all_templates__gpt-5.6-medium__reviewed.md), plus the [quantitative model profiles](reports/debate_model_profiles__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md).
4. **Individual debates:** browse the [matchup results index](reports/debate_matchup_judgments__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md) and [published transcripts](transcripts/).
5. **Topic coverage:** see the [summaries by subject and question type](#topics).

## Pairwise view

![Pairwise heatmap: current models and highlighted predecessors](images/debate_pair_margin_heatmap_current_models__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

This heatmap uses the same **26 current models and highlighted-model predecessors** as the main leaderboard chart. All 72 pairings involving a highlighted model, plus all 25 Opus 5.5 pairings, have at least five complete topics. Other model pairs can still have sparse or missing coverage. Its coverage note counts only matchups between the displayed models. The [full historical heatmap](images/debate_pair_margin_heatmap__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png) remains available separately.

Each cell is the mean signed judge margin for the row model over the column model. Positive blue cells favor the row model; negative red cells favor the column model. The number in parentheses is the count of complete side-swapped matchups for that head-to-head. Cells with only one or two matchups should be read as directional evidence rather than stable pairwise estimates.

## Bradley-Terry leaderboard

| Rank | Model | BT | Matchups |
| ---: | --- | ---: | ---: |
| 1 | Claude Fable 5.1 (high) | 1733.5 | 212 |
| 2 | Claude Fable 5 (high) | 1722.4 | 205 |
| 3 | Claude Opus 5 (high) | 1720.1 | 207 |
| 4 | Kimi K3 | 1694.0 | 225 |
| 5 | Claude Opus 5.5 (high) | 1691.1 | 192 |
| 6 | Gemini 4 Argon (high) | 1672.7 | 175 |
| 7 | Muse Wonder 1.0 (high) | 1651.9 | 175 |
| 8 | Claude Opus 4.7 (high) | 1644.1 | 120 |
| 9 | GPT-5.6 Sol (high) | 1642.0 | 267 |
| 10 | GLM-5.3 (high) | 1637.7 | 143 |
| 11 | Muse Spark 1.1 (high) | 1633.9 | 189 |
| 12 | Claude Opus 4.8 (high) | 1626.7 | 165 |
| 13 | Grok 4.7 (high) | 1616.1 | 114 |
| 14 | GPT-6 Astra (high) | 1608.0 | 182 |
| 15 | Xiaomi MiMo V2.6 Pro (thinking) | 1604.6 | 108 |
| 16 | Grok 4.6 (high) | 1600.9 | 197 |
| 17 | Muse Spark 1.3 (high) | 1593.3 | 212 |
| 18 | Claude Sonnet 5 (high) | 1582.5 | 237 |
| 19 | DeepSeek V4.1 Flash (high) | 1578.5 | 115 |
| 20 | Tencent Hy4 Preview (high) | 1577.6 | 212 |
| 21 | DeepSeek V4 Pro 0813 (high) | 1567.2 | 193 |
| 22 | GLM-5.2 (max) | 1559.3 | 182 |
| 23 | Claude Sonnet 4.6 (high) | 1556.4 | 139 |
| 24 | Qwen 3.8 Max | 1549.3 | 183 |
| 25 | GPT-5.4 (high) | 1542.7 | 131 |
| 26 | Claude Sonnet 4.6 (no reasoning) | 1537.2 | 85 |
| 27 | GPT-5.5 (high) | 1523.4 | 126 |
| 28 | GLM-5.1 | 1514.4 | 99 |
| 29 | Gemini 3.8 Flash (high) | 1509.7 | 155 |
| 30 | Kimi K2.6 | 1506.8 | 131 |
| 31 | MiniMax-M3 | 1496.0 | 176 |
| 32 | GPT-5.4 (no reasoning) | 1490.3 | 93 |
| 33 | Grok 4.5 (high) | 1486.1 | 122 |
| 34 | Gemini 3.1 Pro Preview | 1485.2 | 250 |
| 35 | Xiaomi MiMo V2.5 Pro | 1480.0 | 187 |
| 36 | Qwen 3.6 Max Preview | 1470.4 | 84 |
| 37 | Gemini 3.7 Flash (high) | 1451.2 | 117 |
| 38 | Mistral Large 4 (high) | 1451.2 | 159 |
| 39 | Kimi K2.5 Thinking | 1448.7 | 73 |
| 40 | ByteDance Seed2.0 Pro | 1448.1 | 195 |
| 41 | DeepSeek V4 Pro Preview | 1443.6 | 128 |
| 42 | Qwen 3.7 Max | 1429.8 | 160 |
| 43 | MiniMax-M2.7 | 1429.0 | 89 |
| 44 | Grok 4.20 0309 (Reasoning) | 1406.7 | 49 |
| 45 | Gemini 3.5 Flash | 1402.8 | 129 |
| 46 | Grok 4.20 0309 (Non-Reasoning) | 1398.8 | 36 |
| 47 | Qwen3.5-397B-A17B | 1385.2 | 91 |
| 48 | Xiaomi MiMo V2 Pro | 1385.1 | 28 |
| 49 | Baidu Ernie 5.1 | 1383.0 | 188 |
| 50 | Tencent Hy3 Preview (high) | 1382.0 | 122 |
| 51 | Step 3.7 Flash (high) | 1377.0 | 180 |
| 52 | Grok 4.3 | 1366.2 | 88 |
| 53 | DeepSeek V3.2 | 1357.3 | 41 |
| 54 | Mistral Medium 3.5 (high) | 1336.6 | 142 |
| 55 | Gemini 3.1 Flash-Lite Preview | 1324.9 | 31 |
| 56 | GPT-OSS-120B | 1272.9 | 51 |
| 57 | Baidu Ernie 5.0 | 1241.6 | 16 |
| 58 | Mistral Large 3 | 1184.9 | 57 |
| 59 | Llama 4 Maverick | 1025.6 | 29 |

`BT` is the headline Bradley-Terry rating. `Matchups` counts complete side-swapped matchup groups.

### What stands out

- **Claude Opus 5.5 ranks #5 publicly** with 1691.1 BT (95% CI 1681.0–1701.1) across 192 complete matchups.
- **Gemini 4 Argon ranks #6 publicly** with 1672.7 BT (95% CI 1661.1–1684.2) across 175 complete matchups. Gemini 3.1 Pro Preview scores 1485.2.
- **Meta Muse Wonder ranks #7 publicly** with 1651.9 BT (95% CI 1641.5–1662.3) across 175 complete matchups. Muse Spark 1.3 scores 1593.3.
- **Mistral Large 4 ranks #38 publicly** with 1451.2 BT (95% CI 1437.6–1464.8) across 159 complete matchups. Mistral Large 3 scores 1184.9.
- **Claude Fable 5.1 (high) leads** at 1733.5. These ratings incorporate the broader opponent coverage and supersede the standalone intake estimates.

## Price vs. performance

![Price versus performance](images/debate_price_vs_performance__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

Higher and further left is better. The x-axis is average debater-side USD per completed, rating-eligible debate, calculated from recorded token usage and applicable prices or provider-reported request costs. It accounts for the number of input and output tokens actually used, including recorded reasoning tokens and cache or batch discounts. It covers accepted turns and excludes failed attempts and judging.

Cost coverage is reported per model; models without usable cost data are omitted. The current-focused view includes selected predecessors for comparison. DeepSeek Pro is a separate comparison variant, not a Flash predecessor.

DeepSeek V4.1 Flash averages **$0.01127 per debate (1.13¢)** across 230 debates with complete recorded token usage. Its estimate uses the full-week weighted average of the scheduled rates: **20.83% peak and 79.17% off-peak**, independent of when requests ran.

The recently expanded models have complete recorded-usage cost coverage for their rating-eligible debates:

| Model | Average debater cost per debate | Debates |
| --- | ---: | ---: |
| Claude Opus 5.5 (high) | $0.12418 | 384 |
| Gemini 4 Argon (high) | $0.19289 | 350 |
| Meta Muse Wonder 1.0 (high) | $0.25598 | 350 |
| Mistral Large 4 (high) | $0.09241 | 318 |

## Judge sanity checks

The rating graph is connected. After averaging the two debate directions within each matchup, mean cross-judge winner agreement is `0.634`. Decisive-only agreement is `0.938`: it considers only judge pairs where both selected a clear winner, excluding cases where either judge returned a tie or noise-level result. Mean absolute presented-side margin bias is `0.181` on the signed-margin scale. Panels use three distinct model families and avoid same-family judges against debaters when feasible.

The active judge pool is GPT-5.6 Sol (high), Claude Sonnet 5 (high), Gemini 3.1 Pro Preview, Qwen 3.7 Max, Grok 4.5 (high), Kimi K2.6, and Muse Spark 1.1 (high). The combined rating graph also retains judgments from earlier panels.

![All-bucket judge agreement heatmap](images/debate_judge_agreement_heatmap__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

![Decisive-only judge agreement heatmap](images/debate_judge_decisive_agreement_heatmap__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

The heatmaps compare judges on side-swapped matchups. The first includes either model winning and tie/noise buckets. The second asks the narrower question: when both judges chose a clear winner, how often did they choose the same winner? These are evaluator-consistency diagnostics, not a second leaderboard.

## How do models judge their own debates?

Each participant evaluates its own debates twice as a fresh judge, with anonymous A/B labels and display order reversed. Prompts omit model identities and do not disclose that the judge participated. Judgments include a winner, a 0–5 margin, and five 1–10 diagnostic scores.

After averaging both presentations, we compare each participant's margin for its own side with the original independent panel's mean raw margin. Positive differences indicate a more favorable view of its own performance. Brackets show 95% confidence intervals clustered by topic.

### October 15: Wonder, Argon, and Mistral Large 4

The three highlighted models judged **50 debates against one another**, covering all three pairings and 25 complete side-swapped matchups: **200 valid judgments**, with no missing responses. Every debate has three reference-panel judgments. Wonder and Argon each assessed 30 debates; Mistral assessed 40.

| Participant | Own minus panel margin, 95% CI | Panel-awarded losses acknowledged |
| --- | ---: | ---: |
| Muse Wonder 1.0 (high) | −0.32 [−0.46, −0.15] | 4/5 (80%) |
| Gemini 4 Argon (high) | +0.66 [+0.44, +0.88] | 1/4 (25%) |
| Mistral Large 4 (high) | +0.79 [+0.52, +1.03] | 29/39 (74%) |

![Highlighted participants' self-assessment relative to the panel](participant_judging/participant_blind_highlighted_20261015a/self_assessment_shift.png)

**Wonder judged its own performance more harshly than the panel on average; Argon and Mistral judged theirs more favorably.** Mistral nevertheless acknowledged 29 of its 39 panel-awarded losses. Argon's loss-acknowledgment percentage rests on only four panel losses.

Reversing presentation produced opposite winners in **16 of 100 participant–debate assessments**: Wonder 5/30, Argon 1/30, and Mistral 10/40. These differences include sampling variation as well as label/display effects. Each model faced only the other two participants; this smaller cohort has a different opponent mix from September and is not a controlled cross-cohort comparison. Self–panel differences may reflect scale use or rubric interpretation and do not establish conscious self-recognition.

See the [October report and per-model summaries](participant_judging/participant_blind_highlighted_20261015a/report.md), [order-sensitivity chart](participant_judging/participant_blind_highlighted_20261015a/presentation_effect.png), [opponent comparison chart](participant_judging/participant_blind_highlighted_20261015a/opponent_margins.png), and [individual judgments with explanations](participant_judging/participant_blind_highlighted_20261015a/examples.md). These participant judgments do not affect official ratings.

### September 5: the previous top-eight cohort

The eight highest-ranked latest-version models at selection time judged **450 debates against one another**, covering all 28 pairings and 225 side-swapped matchups: **1,800 valid judgments** under the same protocol.

| Participant | Own minus panel margin, 95% CI | Panel-awarded losses acknowledged |
| --- | ---: | ---: |
| Claude Fable 5.1 (high) | +0.02 [−0.13, +0.18] | 8/14 (57%) |
| Claude Opus 5 (high) | −0.03 [−0.21, +0.12] | 16/23 (70%) |
| Kimi K3 | +0.26 [+0.10, +0.42] | 21/37 (57%) |
| GLM-5.3 (high) | −0.02 [−0.23, +0.18] | 25/44 (57%) |
| GPT-6 Astra (high) | +2.33 [+2.13, +2.54] | 1/69 (1%) |
| Grok 4.6 (high) | +0.32 [+0.16, +0.48] | 47/73 (64%) |
| Muse Spark 1.3 (high) | +0.22 [−0.02, +0.47] | 31/52 (60%) |
| Claude Sonnet 5 (high) | +0.23 [+0.02, +0.43] | 40/60 (67%) |

![Participant self-assessment relative to the panel](participant_judging/participant_blind_top8_20260905a/self_assessment_shift.png)

**Astra is the clear outlier in this sample.** Against Fable 5.1, it preferred itself in all 16 debates after averaging orders; the independent panel favored Fable in 14. Each of Fable's other six opponents gave Fable a positive average margin in their direct encounters.

Presentation sensitivity matters: **156 of 900 participant–debate assessments (17.3%) picked opposite winners across the two presentations**. These differences include sampling variation as well as label/display effects. We average both orders and retain graded margins and ties. Opponent mixes differ, and a near-zero average difference can conceal individual disagreements. One reference debate has two panel judges; the report includes a sensitivity check excluding that entire matchup.

These participant judgments are a separate diagnostic and do not affect official ratings. See the [full report and per-model summaries](participant_judging/participant_blind_top8_20260905a/report.md), [order-sensitivity chart](participant_judging/participant_blind_top8_20260905a/presentation_effect.png), and [individual judgments with explanations](participant_judging/participant_blind_top8_20260905a/examples.md).

## Debate quality signal

The benchmark tracks an entertainment/readability score as a diagnostic only; it does not affect ratings. Across chart-visible complete matchups, the mean is `7.50 / 10`. The highest model averages include Claude Opus 5 (high), Claude Fable 5.1 (high), Grok 4.6 (high), Muse Spark 1.3 (high), and Grok 4.7 (high).

![Strength versus entertainment](images/debate_strength_vs_entertainment__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

See the [entertainment report](reports/debate_entertainment_report__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md) for model and matchup details.

## Qualitative behavior — September 24 study

The September 24 analysis covers every eligible complete side-swapped matchup within its 43-model comparison roster, including its four September entrants. This dated study does not include Wonder, Argon, or Mistral Large 4:

- **5,852 / 5,852 debates** with blinded transcript annotations and behavior-to-outcome linkage
- **2,926 / 2,926 side-swapped matchups** with paired behavior synthesis
- **42 public behavior model cards** with judge diagnostics and transcript evidence; report-suppressed models remain in the stored analysis
- **Four reviewed September dossiers:** Claude Opus 5.5 High, Grok 4.7 High, MiMo V2.6 Pro Thinking, and DeepSeek V4.1 Flash High

The dossiers describe recurring strengths, weaknesses, execution, and behavior across assigned sides. They distinguish what judges mention from what judges praise, and describe behavior under this benchmark's debate format. Earlier dossiers remain available as dated snapshots.

![Diagnostic subscores](images/debate_behavior_diagnostic_subscores__judge_judge_blend_20260923_finala__debate_all_templates__gpt-5.6-medium.png)

- [Behavior model cards](reports/debate_behavior_model_cards__judge_judge_blend_20260923_finala__debate_all_templates__gpt-5.6-medium.md)
- [Four newcomer dossiers](reports/debate_model_dossiers__judge_judge_blend_20260923_finala__debate_all_templates__gpt-5.6-medium__reviewed.md)
- [September 4 model dossiers](reports/debate_model_dossiers__judge_judge_blend_glm53_coverage_20260904a__debate_all_templates__gpt-5.6-medium__reviewed.md)
- [Deterministic qualitative audit](reports/debate_qualitative_behavior__judge_judge_blend_20260923_finala__debate_all_templates.md)
- [Current quantitative model profiles](reports/debate_model_profiles__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md)

### Historical qualitative readings

The March 2026 close readings remain available as a dated, deliberately selected sample. They show the arguments and judge reasoning behind individual results, rather than representative estimates of current model behavior:

- [Transcript evidence and judge notes](reports/qualitative_model_comparisons__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Debate-by-debate summaries](reports/qualitative_model_comparison_summaries__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)
- [Cross-model synthesis](reports/qualitative_model_comparison_synthesis__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)

## Reliability

Content blocks, blank outputs, formatting failures, and model-service failures are tracked separately from debate quality. The availability-adjusted view shows how reliability would change model strength if completion problems were penalized; it does not change how completed debates were judged.

![Content block rate](images/debate_content_block_rate__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

![Strength versus reliability](images/debate_strength_vs_reliability__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

![Reliability breakdown](images/debate_reliability_breakdown__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.png)

## Topics

The topic bank contains **683 motions**, spanning policy, empirical, and moral disputes intended to be understandable to an informed generalist. Every motion has completed debates and contributes to the stored ratings. The tables count distinct topics; individual models have different topic coverage.

| Theme | Topics |
| --- | ---: |
| Law / regulation / courts | 135 |
| Labor / education / social policy | 122 |
| Media / culture / internet | 111 |
| Macro / trade / industrial policy | 108 |
| Health / bioethics | 65 |
| Energy / climate / infrastructure | 49 |
| Science / space / frontier tech | 34 |
| Business / antitrust / market structure | 28 |
| Geopolitics / defense / security | 24 |
| AI / tech policy | 7 |
| **Total** | **683** |

| Question type | Topics |
| --- | ---: |
| Mixed | 466 |
| Normative | 151 |
| Empirical | 66 |
| **Total** | **683** |

## Worked examples

### September entrant examples

- **Claude Opus 5.5 vs Grok 4.7** on children’s digital wellbeing. Each won unanimously, 3–0, as CON, leaving the paired result tied. Both challenged whether sleep, boredom, and play adequately address product-specific harms such as grooming and unwanted purchases. Read [Debate A](transcripts/prop_0270__claude-opus-5-5-high__grok-4.7-high__s0__tpl_placement_active_20260813a.md), [Debate B](transcripts/prop_0270__grok-4.7-high__claude-opus-5-5-high__s1__tpl_placement_active_20260813a.md), and the [matchup report](reports/debate_matchup_judgments/judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates/matchup-judgment-prop_0270-claude-opus-5-5-high-vs-grok-4.7-high-df0a410a9f89.md).
- **DeepSeek V4.1 Flash vs MiMo V2.6 Pro Thinking** on whether the British economy would be stronger without Brexit. Each won unanimously, 3–0, as PRO, again producing a paired tie. The clash turns on the relevant counterfactual: whether avoiding Brexit's additional costs would improve an economy that still faces domestic structural problems. Read [Debate A](transcripts/prop_0030__deepseek-v4.1-flash-high__mimo-v2.6-pro-thinking__s0__tpl_placement_active_20260813a.md), [Debate B](transcripts/prop_0030__mimo-v2.6-pro-thinking__deepseek-v4.1-flash-high__s1__tpl_placement_active_20260813a.md), and the [matchup report](reports/debate_matchup_judgments/judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates/matchup-judgment-prop_0030-deepseek-v4.1-flash-high-vs-mimo-v2.6-pro-thinking-1e46e51726a9.md).

These pairs illustrate why a single debate direction can be misleading.

### Earlier model comparison

**Claude Opus 4.8 vs Claude Opus 5** on banning corporate political donations: Opus 4.8 won the first direction 2–1 as PRO; Opus 5 won the reverse direction 3–0 as PRO and won the paired result. Every judge rated both debates 9 / 10 for entertainment. Read [Debate A](transcripts/prop_0379__claude-opus-4-8-adaptive__claude-opus-5-high__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0379__claude-opus-5-high__claude-opus-4-8-adaptive__s1__tpl_placement_active_20260320f.md), and the [matchup report](reports/debate_matchup_judgments/judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates/matchup-judgment-prop_0379-claude-opus-4-8-adaptive-vs-claude-opus-5-high-4db31537c073.md).

## Best lines

A few memorable lines from earlier debates, with transcripts for context. These are examples of rhetoric, not inputs to the ratings.

> You cannot reject a trap you cannot see.

— **Qwen3.5-397B-A17B**, arguing for a ban on personalized algorithmic pricing. [Transcript](transcripts/prop_0041__qwen3.5-397b-a17b__minimax-m2.7__s1__tpl_placement_active_20260320f.md)

> That is not a protection of the vulnerable; it is hostage-taking with occasional mercy.

— **MiniMax-M2.7**, challenging the claim that personalized pricing protects low-income shoppers. [Transcript](transcripts/prop_0041__minimax-m2.7__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md)

> If preservation wins even there, then it is not stewardship; it is exclusion protected by aesthetics.

— **GPT-5.4 (high)**, arguing for housing density in historic districts. [Transcript](transcripts/prop_0003__gpt-5.4-high__minimax-m2.7__s0__tpl_placement_active_20260320f.md)

## Method summary

For each selected model pair and topic:

1. The two models debate the proposition in a ten-turn format.
2. They debate the same proposition again with PRO and CON reversed.
3. Full prompts, raw responses, parsed turns, and transcripts are retained.
4. A three-model judge panel selects a winner and margin for each debate.
5. Complete side-swapped groups feed Bradley-Terry; rubric subscores remain diagnostic.

The ten turns are PRO opening, CON opening, first rebuttals, pressure questions, second rebuttals, and closings. Output length is enforced by deterministic clipping, so the stored text—not a model's self-reported word count—is authoritative.

Bradley-Terry estimates relative strength from paired outcomes while accounting for opponent strength. This makes comparisons across uneven schedules more useful than a raw win rate or an average of rubric scores. Swapping sides reduces the influence of an easier position on a particular motion; multiple judges and confidence intervals help show the remaining uncertainty.

## Limits and caveats

- This is a live benchmark, not a frozen final release.
- It uses LLM judges rather than human judges, though side swaps, multiple judges, distinct judge families, and agreement diagnostics reduce some noise.
- Matchup schedules are intentionally non-uniform, so confidence intervals and the pairwise matrix matter.
- Qualitative tags and dossier prose come from GPT-5.6 Sol (medium), not human coders.
- Availability and content-filter behavior can materially affect coverage; reliability is reported separately.
- Debate is one capability slice, not a complete measure of model usefulness.

## Further reading and data

- [Opus 5.5 coverage report](reports/opus55_coverage_20261015_final_analysis.md)

- [Five-topic coverage report](reports/highlighted_coverage_20261015_stage1_final_analysis.md) — historical [leaderboard](reports/highlighted_coverage_20261015_leaderboard_snapshot.md), [profiles](reports/debate_model_profiles__judge_judge_blend_highlighted_coverage_20261015_finala__debate_all_templates.md), and [heatmap](images/debate_pair_margin_heatmap_current_models__judge_judge_blend_highlighted_coverage_20261015_finala__debate_all_templates.png).

- [Leaderboard report](reports/debate_leaderboard__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md)
- [Benchmark status](reports/debate_benchmark_status__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md)
- [Matchup results index](reports/debate_matchup_judgments__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md)
- [Wonder/Argon intake report](reports/frontier_expansion_20261014_final_analysis.md)
- [Mistral intake report](reports/frontier_expansion_mistral4_20261014_final_analysis.md)
- [Judge decision table](judgments/judge_results__judge_blend_opus55_coverage_20261015_finala.csv)
- [Full judge decision records (gzip-compressed JSONL)](judgments/judge_results__judge_blend_opus55_coverage_20261015_finala.jsonl.gz)
- [Completed public transcripts](transcripts/)

### Reproducibility checks

- [Proxy-error integrity audit](reports/debate_proxy_error_audit__judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates.md)
- Public judgment exports omit local prompt and raw-response filesystem paths; canonical raw artifacts remain retained in the benchmark data store.

## Related benchmarks

- [LLM Sycophancy Benchmark](https://github.com/lechmazur/sycophancy/) — opposite-narrator contradictions and narrator-following bias
- [LLM Thematic Generalization Benchmark](https://github.com/lechmazur/generalization/) — latent-category induction from examples and counterexamples
- [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing/) — short-story quality under fixed required elements
- [BAZAAR: Auction Market Benchmark](https://github.com/lechmazur/bazaar/) — strategic bidding in a competitive simulated market
- [Buyout Game Benchmark](https://github.com/lechmazur/buyout_game/) — multi-agent bargaining, transfers, and hostile takeovers
- [PACT](https://github.com/lechmazur/pact/) — multi-round buyer-seller bargaining with hidden values and public messages
- [LLM Persuasion Benchmark](https://github.com/lechmazur/persuasion/) — multi-turn persuasion measured by opinion movement
- [LLM Round-Trip Translation Benchmark](https://github.com/lechmazur/translation/) — meaning and voice retained after translation out of English and back
- [Step Race](https://github.com/lechmazur/step_game/) — collaboration and misdirection under pressure
- [Elimination Game](https://github.com/lechmazur/elimination_game/) — social reasoning, deception, and jury persuasion
- [Extended NYT Connections](https://github.com/lechmazur/nyt-connections/) — category induction with distractors

## Updates

- `2026-10-15`: Added Meta Muse Wonder 1.0 (high), Gemini 4 Argon (high), and Mistral Large 4 (high).
- `2026-09-24`: Added Opus 5.5 High, Grok 4.7 High, MiMo V2.6 Pro Thinking, and DeepSeek V4.1 Flash High.
- `2026-09-05`: Added blind participant judging among the current top eight: 450 debates, both presentation orders, graded margins, and per-model summaries.
- `2026-09-04`: Added GPT-6 Astra (high) and GLM-5.3 (high), expanded opponent coverage for highlighted models, completed six new qualitative profiles, and refreshed the cost chart using recorded token usage.

- `2026-09-03`: Added Claude Fable 5.1 (high), Tencent Hy4 Preview (high), Gemini 3.8 Flash (high), and Muse Spark 1.3 (high) after two-stage adaptive placement.
- `2026-08-14`: Added Grok 4.6 (high), Gemini 3.7 Flash (high). Added qualitative behavior coverage and current-model dossiers.
- `2026-08-04`: Added Qwen 3.8 Max.
- `2026-07-24`: Added Claude Opus 5 (high).
- `2026-07-17`: Added Kimi K3.
- `2026-07-13`: Added MiniMax-M3, Claude Sonnet 5 (high), Grok 4.5 (high), GPT-5.6 Sol (high), and Muse Spark 1.1 (high).
- `2026-06-20`: Added GLM-5.2 (max).
- `2026-06-10`: Added Claude Fable 5 (high).

---
