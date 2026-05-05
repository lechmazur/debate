# LLM Debate Benchmark: Adversarial Multi-Turn Argument Under Opposition

This benchmark measures how well large language models perform in adversarial, multi-turn debates across a wide range of propositions. Strong performance is not just about producing a polished first answer. It requires broad knowledge, accurate use of relevant facts under pressure, strong rebuttal, and the ability to stay coherent, responsive, and defensible over several rounds.

Each evaluated matchup runs twice on the **same topic with sides swapped**. A three-model judge panel then decides winner and margin, and the published leaderboard is Bradley-Terry over completed side-swapped matchups.

---

![Bradley-Terry leaderboard](images/debate_bt_ratings__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

---

## How to read the main chart

- Each bar is one model’s current **Bradley-Terry rating**.
- Higher bars mean stronger judged debate performance.
- Bradley-Terry is a relative within-pool rating centered near `1500`; it is not an absolute capability score.
- The grey band behind each bar is the **95% robust confidence interval** for that model’s rating.
- The published order uses **Bradley-Terry**.

---

## Current Snapshot

- **29 rated models in the public chart slice**
- **1,779 completed debate artifacts in the current public snapshot**
- **727 side-swapped groups in the current status report before incomplete and excluded groups are removed**
- **701 rating-eligible side-swapped matchups in the current public ratings**
- **3,608 parsed judgment rows in the current public snapshot**

One side-swapped matchup means two debates on the same motion with PRO and CON roles reversed.

The public transcript directory mirrors clean completed debates that are safe to read directly. Transcript files with proxy-error turns or out-of-snapshot judgments are filtered from the public bundle.

The stored rating tables still retain historical models, but public markdown and charts focus on the current visible model set by default.

---

## Reader Paths

There are four useful ways to read this snapshot:

1. **Fast ranking check**: start with the Bradley-Terry chart, then use the [full leaderboard table](#current-full-leaderboard) to see coverage for each model.
2. **Design sanity check**: read the [pairwise heatmap](#pairwise-view), [judge sanity checks](#judge-sanity-checks), [cross-judge agreement heatmap](#cross-judge-agreement), [benchmark status](reports/debate_benchmark_status__judge_judge_active_20260430a__debate_placement_active_20260320f.md), and [reliability diagnostics](#reliability-diagnostics) to see whether the headline ranking is being distorted by narrow matchups, judge disagreement, or operational failures.
3. **Transcript-level read**: jump to the [worked examples](#worked-examples), then use the [matchup judgment index](reports/debate_matchup_judgments__judge_judge_active_20260430a__debate_placement_active_20260320f.md), [model profiles](reports/debate_model_profiles__judge_judge_active_20260430a__debate_placement_active_20260320f.md), and [model dossiers](reports/debate_model_dossiers__judge_judge_active_20260430a__debate_placement_active_20260320f__gpt-5.4-low.md) for broader transcript-driven patterns.
4. **Quality/readability check**: use the [debate quality signal](#debate-quality-signal) and [entertainment report](reports/debate_entertainment_report__judge_judge_active_20260430a__debate_placement_active_20260320f.md) to see which models produce debates judges found readable or engaging. This is diagnostic only and does not affect ratings.

The chart bundle is meant to answer “who is ahead?” quickly. The worked examples, matchup reports, model profiles, and model dossiers are meant to answer the more important follow-up: “what did the better debate actually look like?”

---

## Pairwise View

The pairwise heatmap shows how models perform against each other after aggregation across completed, side-swapped matchups. This is useful because a single scalar leaderboard always hides some structure. A model can be strong overall while still having a few specific bad matchups.

![Pairwise heatmap](images/debate_pair_margin_heatmap__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

Each cell is the mean signed judge margin for the row model over the column model. Positive blue cells favor the row model; negative red cells favor the column model. The number in parentheses is the count of completed side-swapped matchups for that head-to-head cell.

The heatmap is most useful as a quick read on where the field is decisively separated and where it still is not. In the current snapshot, the biggest clean edges are mostly against Llama 4 Maverick, while the top cluster remains much tighter.
Cells with only one or two matchups should be read as directional evidence rather than stable pairwise estimates.

---

## What this benchmark shows

Debate is harder than ordinary question answering because the model has to stay correct and coherent after the other side pushes back. That pressure exposes several different abilities at once:

- **Knowledge under stress**: can the model retrieve the right facts when challenged, not just in its opening statement?
- **Counterargument handling**: can it answer the strongest objection instead of repeating its own case?
- **Strategic coherence**: can it preserve a line of argument over multiple turns instead of drifting or contradicting itself?
- **Epistemic discipline**: can it make claims that remain defensible when the debate becomes adversarial?

In practice, this format does not reward openings alone. Some models look strong in a first pass but weaken once the other side attacks specifics, while others stay more stable across rebuttal and closing.

The side-swapped design matters too. Some propositions are easier to argue from one side than the other, so each pair debates the same motion twice with roles reversed. That makes the benchmark closer to a structured adversarial comparison than a one-shot preference test.

Another reason debate is useful is that it makes different failure modes visible at the same time. A model can know the facts but fail to organize them. It can produce elegant openings but weak rebuttals. It can sound persuasive while still collapsing under pressure. Debate compresses those distinctions into one adversarial format.

---

## Representative Motions

The benchmark is broad rather than narrowly optimized around one policy template. A few current motions give a good sense of the range:

- **Dating apps**: The dominant dating-app model makes relationship formation worse for most users than better.
- **School smartphones**: Schools should ban smartphones during the school day by default rather than leave phone rules to individual teachers.
- **Older-adult care**: Hospitals and care providers should not replace most human companionship with AI or robotic companions for older adults, even when staffing is tight.
- **Shrinkflation**: Supermarkets and food apps should be required to display shrinkflation and unit-price changes more clearly when package sizes fall without obvious headline price cuts.
- **Eurozone politics**: The eurozone's post-2010 crisis response deepened political distrust more than it preserved European solidarity.

This matters because debate ability can look very different on fiscal policy, civil liberties, technology governance, migration, labor, education, or historical-justice motions. A wide topic bank makes the leaderboard more meaningful.

---

## Bradley-Terry Leaderboard

### Current full leaderboard

| Rank | Model | BT | Matchups |
| ---: | --- | ---: | ---: |
| 1 | Claude Opus 4.7 (high reasoning) | 1710.6 | 72 |
| 2 | Claude Opus 4.6 (high reasoning) | 1632.9 | 69 |
| 3 | Claude Sonnet 4.6 (high reasoning) | 1625.8 | 68 |
| 4 | GPT-5.4 (high reasoning) | 1625.4 | 103 |
| 5 | Claude Sonnet 4.6 (no reasoning) | 1624.6 | 71 |
| 6 | Claude Opus 4.6 (no reasoning) | 1611.2 | 76 |
| 7 | GPT-5.5 (high reasoning) | 1574.4 | 58 |
| 8 | GLM-5.1 | 1573.4 | 57 |
| 9 | GPT-5.4 (no reasoning) | 1568.7 | 82 |
| 10 | Kimi K2.6 | 1567.7 | 53 |
| 11 | Xiaomi MiMo V2.5 Pro | 1553.4 | 52 |
| 12 | Gemini 3.1 Pro Preview | 1551.2 | 91 |
| 13 | Qwen 3.6 Max Preview | 1534.5 | 50 |
| 14 | MiniMax-M2.7 | 1522.5 | 44 |
| 15 | ByteDance Seed2.0 Pro | 1519.7 | 41 |
| 16 | Kimi K2.5 Thinking | 1519.7 | 63 |
| 17 | DeepSeek V4 Pro | 1516.7 | 40 |
| 18 | Grok 4.20 0309 (Non-Reasoning) | 1485.6 | 33 |
| 19 | Tencent Hy3 Preview (high reasoning) | 1480.8 | 17 |
| 20 | Qwen3.5-397B-A17B | 1466.5 | 36 |
| 21 | Xiaomi MiMo V2 Pro | 1459.3 | 24 |
| 22 | DeepSeek V3.2 | 1438.4 | 34 |
| 23 | Gemini 3.1 Flash-Lite Preview | 1425.7 | 29 |
| 24 | Grok 4.3 | 1419.0 | 27 |
| 25 | Mistral Medium 3.5 High Reasoning | 1411.6 | 20 |
| 26 | GPT-OSS-120B | 1349.6 | 30 |
| 27 | Baidu Ernie 5.0 | 1330.1 | 14 |
| 28 | Mistral Large 3 | 1299.2 | 20 |
| 29 | Llama 4 Maverick | 1098.2 | 28 |

`BT` is the headline Bradley-Terry rating. `Matchups` is the number of completed side-swapped matchup groups for that model in the current public ratings.

---


## What Stands Out

The current picture has one clear provisional leader, a crowded frontier just below it, GPT-5.5 now represented in the main public charts, and clearer separation in the lower half of the field than at the top.

- **Claude Opus 4.7 currently leads the published board.** It sits at 1710.6 BT across 72 completed side-swapped matchup groups.
- **The frontier is still tight below first place.** Claude Opus 4.6 (high reasoning), Claude Sonnet 4.6 (high reasoning), GPT-5.4 (high reasoning), Claude Sonnet 4.6 (no reasoning), and Claude Opus 4.6 (no reasoning) are separated by about 22 BT points.
- **GPT-5.5 is now in the current public ratings.** GPT-5.5 (high reasoning) ranks 7th at 1574.4 BT across 58 matchup groups, just ahead of GLM-5.1 and close to Kimi K2.6, GPT-5.4 (no reasoning), and Qwen 3.6 Max Preview.
- **The new frontier entrants are present but still narrower than the oldest anchors.** Kimi K2.6, Qwen 3.6 Max Preview, Grok 4.3, DeepSeek V4 Pro, Mistral Medium 3.5 High Reasoning, and Tencent Hy3 Preview are included, but several have fewer pair groups than GPT-5.4, Gemini, and the earlier Claude anchors.
- **Judges are rewarding rebuttal quality and argument strength more than isolated style.** The top cluster is repeatedly described in the model profiles as disciplined, grounded, clash-driven, and responsive. Lower-ranked models often retain some mix of grounding, originality, or rhetorical effectiveness, but still lose because they underperform on rebuttal quality and argument strength.

---

## Price vs. Performance

The price chart reads the same Bradley-Terry strength signal against debate cost estimates from router logs. The x-axis is debater-side USD per completed debate, excluding judge-panel cost. Exact router usage is used when present; legacy matched logs without usage counts use a text-token estimate from the saved full prompt and raw response artifacts. Non-USD provider pricing rows are excluded from USD cost recovery rather than converted or relabeled implicitly.

![Price versus performance](images/debate_price_vs_performance__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

Higher and further left is better on this view. The next render will omit the vertical BT uncertainty bands on this chart for readability. Only visible rated models with cost rows are plotted.

---

## Why Bradley-Terry And Side Swaps

This benchmark does not publish a simple “average judge score per debate” leaderboard as the main result. The primary table is Bradley-Terry over completed side-swapped matchups.

That matters for three reasons:

1. A single debate can be distorted by side advantage or topic-specific asymmetry.
2. Bradley-Terry uses the pairwise structure of the benchmark instead of treating every judged debate as an isolated score.
3. Relative judgments are a better fit for LLM judging than absolute score calibration. Asking which side did better on the same motion is usually more stable than asking whether a debate was, say, a `7.8` or an `8.3` on some global scale.

That last point matters in practice. Judges can differ in harshness, scale usage, and topic leniency. A relative decision on the same debate is less exposed to those calibration problems than an absolute score in isolation. For that reason, rubric fields are retained as diagnostics, but the public leaderboard is built from relative outcomes.

So the headline unit is not “one debate,” but “one completed side-swapped matchup on one topic.” That is a better fit for a benchmark meant to compare sustained adversarial performance rather than one-off wins.

---


## Judge Sanity Checks

The benchmark relies on LLM judges, so it is worth being explicit about the current sanity checks:

- the Bradley-Terry graph is connected
- mean cross-judge winner agreement is 0.553, measured as the fraction of overlapping side-swapped matchup decisions where two judges picked the same winner
- mean absolute presented-side margin bias by judge is 0.157 on the signed margin scale
- the canonical parsed judgment table currently has 0 parse-warning rows
- the current judge roster includes GPT-5.5 (high reasoning), Claude Sonnet 4.6 (high reasoning), Gemini 3.1 Pro Preview, Qwen 3.6 Max Preview, Grok 4.3, and Kimi K2.6
- the cross-judge agreement heatmap also includes historical overlap where available
- every active judge has parsed judgments in the current status report

This does not make the judges perfect. But it does mean the current snapshot is not obviously being driven by parser chaos or a huge systematic side-presentation artifact.
Panels are built from distinct model families and avoid same-family judges against the debaters when feasible.

---

## Cross-Judge Agreement

The judge-agreement data are also rendered directly as a heatmap so it is easier to see which evaluators tend to move together and which pairs diverge more often.

![Judge agreement heatmap](images/debate_judge_agreement_heatmap__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

Each off-diagonal cell is a judge-pair agreement rate; the number in parentheses is the count of overlapping side-swapped matchup groups. Judge identities are shown on the axes with names and brand logos; diagonal cells are intentionally left blank. The full symmetric matrix is shown, so upper-right and lower-left off-diagonal cells mirror each other where overlap exists.

This is a sanity-check view, not a second leaderboard. It is there to make evaluator consistency visible rather than bury it inside one summary statistic.

---

## Debate Quality Signal

The benchmark also tracks a judge-side entertainment/readability diagnostic as a secondary signal. It does not affect ratings, but it is useful for checking whether the benchmark produces debates that are merely formal or actually engaging to read.

- mean entertainment across chart-visible complete side-swapped matchups: 7.32 / 10
- most entertaining current models by that signal include Claude Opus 4.7 (high reasoning), Claude Sonnet 4.6 (high reasoning), Kimi K2.5 Thinking, Claude Sonnet 4.6 (no reasoning), Claude Opus 4.6 (high reasoning), Kimi K2.6, GLM-5.1, MiniMax-M2.7, and GPT-5.4 (high reasoning)

High-entertainment matchup examples from the current snapshot:

- Claude Opus 4.7 (high reasoning) vs Claude Sonnet 4.6 (no reasoning) on returning human remains to Indigenous and colonized peoples
- Claude Opus 4.6 (high reasoning) vs Claude Sonnet 4.6 (no reasoning) on electronic-waste exports
- Claude Opus 4.7 (high reasoning) vs GPT-5.5 (high reasoning) on public agencies suspending benefits, visas, or fraud claims solely because an AI system flags a case

This signal is diagnostic rather than decisive, but it helps show that the benchmark is producing debates judges generally find readable and engaging.
For the chart-visible model table and example matchups, see the [current entertainment report](reports/debate_entertainment_report__judge_judge_active_20260430a__debate_placement_active_20260320f.md). That report uses the same visible model set as the charts, so its visible-matchup mean can differ slightly from the all-clean-slice mean above.

![Strength versus entertainment](images/debate_strength_vs_entertainment__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

In the scatter, the x-axis is BT, the y-axis is mean entertainment/readability score, bubble size is rated matchup coverage, and grey horizontal bands show BT uncertainty.

Read against the main strength rating, this view separates three cases that a single leaderboard hides: models that are strong and lively, models that are strong but comparatively dry, and models that are readable or vivid without being top-tier debaters. Entertainment still stays diagnostic only; it does not feed the rating.

---

## Best Lines

An earlier transcript-highlights pass also surfaced lines that are worth quoting in their own right. This is an LLM-selected post-run highlight pass, not a rating input and not human curation.

1. Encryption backdoors, Claude Sonnet 4.6 (no reasoning): *"Children don't disappear in percentages. They disappear one at a time, in exactly these cases."*
2. Historic-district housing, GPT-5.4 (high reasoning): *"If preservation wins even there, then it is not stewardship; it is exclusion protected by aesthetics."*
3. Four-day workweek, Gemini 3.1 Pro Preview: *"We do not subsidize cheap goods with exhausted labor."*
4. Prescription-drug advertising, Claude Opus 4.6 (no reasoning): *"You don't build the bridge while the ferry company lobbies to keep its monopoly."*
5. Homelessness as housing vs policing, Claude Sonnet 4.6 (high reasoning): *"A city that clears the same encampment twelve times a year is not governing effectively; it is performing governance."*
6. Medical autonomy vs dignity, Claude Opus 4.6 (high reasoning): *"A conception of dignity that can be enforced against your will over your own body is just domination with better vocabulary."*
7. The euro and European solidarity, Qwen3.5-397B-A17B: *"Politically, the Euro is not glue; it is acid."*
8. NDAs and workplace abuse, GPT-5.4 (no reasoning): *"That is not a shield for victims. It is a shield against victims."*
9. Algorithmic dynamic pricing, Qwen3.5-397B-A17B: *"You cannot reject a trap you cannot see."*
10. Brexit and economic drag, GPT-5.4 (high reasoning): *"If two runners face the same storm and one is also carrying a backpack, the backpack still made him slower."*

The [full highlights report](reports/debate_highlights__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-low.md) has more examples from that pass.

---

## Content Block Rate

Content blocks reflect a distinct moderation/content-fragility problem rather than simple latency, parser trouble, or blank outputs.
This is not an overall reliability or request-failure rate; blank outputs, parser failures, and request failures are tracked separately in the [current benchmark status](reports/debate_benchmark_status__judge_judge_active_20260430a__debate_placement_active_20260320f.md).

![Content block rate](images/debate_content_block_rate__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

In the broader seen-attempt denominator, including attempts that may not enter the clean rated slice, Xiaomi MiMo V2 Pro remains the clear outlier with 10 content-block terminal errors across 104 seen debates. Kimi K2.5 Thinking, Qwen3.5-397B-A17B, Grok 4.20 0309 (Non-Reasoning), Gemini 3.1 Pro Preview, Gemini 3.1 Flash-Lite Preview, MiniMax-M2.7, Llama 4 Maverick, and the older Claude Sonnet/Opus no-reasoning rows show smaller content-block exposure. Current frontier-expansion models such as GPT-5.5, Kimi K2.6, Qwen 3.6 Max Preview, GLM-5.1, Grok 4.3, DeepSeek V4 Pro, Xiaomi MiMo V2.5 Pro, and Mistral Medium 3.5 High Reasoning show zero content blocks in the latest status report.

---

## Reliability Diagnostics

Content blocks are only one operational failure mode. The reliability views show the broader availability picture: completed debates, content blocks, blank outputs, validation failures, request failures, and other terminal errors over seen debate attempts.

![Strength versus reliability](images/debate_strength_vs_reliability__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

The dumbbell chart keeps raw BT as the headline quality score and shows how an availability-adjusted score would move when operational failures are penalized. Longer connectors mean a larger reliability penalty; they do not mean the completed debates were judged worse.

![Reliability breakdown](images/debate_reliability_breakdown__judge_judge_active_20260430a__debate_placement_active_20260320f.png)

The stacked breakdown is the best view when the question is what kind of operational issue occurred. In the status table, content blocks are a subset of terminal errors, so content-block rates use the availability table's seen-attempt denominator rather than adding the content-block count a second time.

---

## Worked Examples

If you want to jump straight into transcript pairs that are especially worth reading:

- Frontier matchup: Claude Sonnet 4.6 (high reasoning) vs GPT-5.4 (high reasoning) on banning location-data sales. This is one of the best current top-tier matchups to read because the topic is strong, the execution is strong, and the side swap materially changes the picture. Mean entertainment across the pair: 8.00 / 10. Read [Debate A](transcripts/prop_0541__claude-sonnet-4-6-adaptive__gpt-5.4-high__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0541__gpt-5.4-high__claude-sonnet-4-6-adaptive__s1__tpl_placement_active_20260320f.md), and the [matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260430a__debate_placement_active_20260320f/matchup-judgment-prop_0541-claude-sonnet-4-6-adaptive-vs-gpt-5.4-high.md).
- Clear separation example: GPT-5.4 (high reasoning) vs Llama 4 Maverick on forced-sterilization redress. This is a cleaner blowout where the stronger debater stays better as PRO and as CON. Mean entertainment across the pair: 6.25 / 10. Read [Debate A](transcripts/prop_0214__gpt-5.4-high__llama4-maverick__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0214__llama4-maverick__gpt-5.4-high__s1__tpl_placement_active_20260320f.md), and the [matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260430a__debate_placement_active_20260320f/matchup-judgment-prop_0214-gpt-5.4-high-vs-llama4-maverick.md).
- High-readability close clash: MiniMax-M2.7 vs Qwen3.5-397B-A17B on algorithmic dynamic pricing. MiniMax wins the current public version of this pair, but the side-swapped rematch is split and the transcript remains a sharp read. Mean entertainment across the pair: 7.75 / 10. Read [Debate A](transcripts/prop_0041__minimax-m2.7__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0041__qwen3.5-397b-a17b__minimax-m2.7__s1__tpl_placement_active_20260320f.md), and the [matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260430a__debate_placement_active_20260320f/matchup-judgment-prop_0041-minimax-m2.7-vs-qwen3.5-397b-a17b.md).

<details>
<summary>Claude Sonnet 4.6 (high reasoning) vs GPT-5.4 (high reasoning) on banning location-data sales</summary>

Motion: Governments should prohibit data brokers from selling individuals’ precise location data without explicit, time-limited opt-in consent.

Full transcripts:

- [Debate A: Claude Sonnet 4.6 (high reasoning) as PRO, GPT-5.4 (high reasoning) as CON](transcripts/prop_0541__claude-sonnet-4-6-adaptive__gpt-5.4-high__s0__tpl_placement_active_20260320f.md)
- [Debate B: GPT-5.4 (high reasoning) as PRO, Claude Sonnet 4.6 (high reasoning) as CON](transcripts/prop_0541__gpt-5.4-high__claude-sonnet-4-6-adaptive__s1__tpl_placement_active_20260320f.md)
- [Matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260430a__debate_placement_active_20260320f/matchup-judgment-prop_0541-claude-sonnet-4-6-adaptive-vs-gpt-5.4-high.md)
- [Raw judgment rows (search for `prop_0541`)](judgments/judge_results__judge_active_20260430a.csv)

Judge panel rows in this snapshot: Kimi K2.6 and Qwen 3.6 Max Preview.

Judged result:

- Debate A (`Claude PRO / GPT CON`): unanimous 2-0 for GPT-5.4 (high reasoning), with judge entertainment scores `8` and `8`
- Debate B (`GPT PRO / Claude CON`): unanimous 2-0 for GPT-5.4 (high reasoning), with judge entertainment scores `8` and `8`
- Across both side assignments: GPT-5.4 (high reasoning) won all 4 judge rows in this snapshot
- Mean entertainment across the full side-swapped pair: 8.00 / 10
- Average absolute judged margin across the four judge rows: 1.1

This is a good example of why the benchmark uses side-swapped relative judgments instead of a one-shot absolute score. The role reversal changes which argument is easiest to press, but GPT-5.4 carries the pair on both assignments in this snapshot.

Debate structure in this benchmark:

1. PRO opening
2. CON opening
3. PRO rebuttal 1
4. CON rebuttal 1
5. PRO pressure questions
6. CON pressure questions
7. PRO rebuttal 2
8. CON rebuttal 2
9. PRO closing
10. CON closing

Round-by-round sketch from Debate A (`Claude PRO / GPT CON`):

1. PRO opening: Claude frames precise location as uniquely intimate surveillance data and argues that broker resale turns private life into something strangers can buy.
2. CON opening: GPT accepts the privacy harm but attacks the mechanism, arguing that the real target should be abusive downstream use rather than consent paperwork.
3. PRO rebuttal 1: Claude tries to make enforceability central, claiming explicit consent creates a clear legal baseline while pure use-based restrictions push everything into after-the-fact reconstruction.
4. CON rebuttal 1: GPT’s strongest reply is that a captured click is not meaningful protection. Once the checkbox is obtained, the sale is lawful, so the harms Claude named can still occur.
5. PRO pressure questions: Claude presses on who would enforce use-based rules and why the answer to dark-patterned consent is not stronger consent law plus anti-bundling constraints.
6. CON pressure questions: GPT targets the motion’s weak point by asking whether “analytics intermediary” carve-outs still allow raw upstream transfers and what “time-limited” consent changes after a sale already happens.
7. PRO rebuttal 2: Claude answers that upstream transfers are still covered, the sale must state a specific purpose, and consent should be read as a floor rather than the whole privacy regime.
8. CON rebuttal 2: GPT argues those answers concede both porosity and redundancy: if broad labels like analytics are enough, the rule is easy to route around; if harmful-use bans are still needed, those bans are doing the real work.
9. PRO closing: Claude reduces the round to the default legal setting: under the proposition, resale is presumptively blocked unless a person explicitly says yes.
10. CON closing: GPT closes by reframing the motion as a paperwork-first rule that powerful interfaces can satisfy while the truly dangerous downstream buyers still require separate restrictions.

What changes in the side-swapped rematch (`GPT PRO / Claude CON`):

- GPT’s PRO case is cleaner when it gets to argue directly for the proposition rather than attack it. The rematch lets it frame the motion as a narrow default shift against invisible resale.
- Claude’s CON case becomes sharper on the idea that consent is a compliance ritual, not a real screen on buyer identity or downstream misuse.
- That role reversal is exactly why the second debate matters. Good models can often argue both sides coherently, but they do not do so equally well.

</details>

<details>
<summary>GPT-5.4 (high reasoning) vs Llama 4 Maverick on forced-sterilization redress</summary>

Motion: Countries should provide stronger compensation and archival access to survivors and descendants of forced-sterilization programs rather than treat those abuses as closed chapters.

Full transcripts:

- [Debate A: GPT-5.4 (high reasoning) as PRO, Llama 4 Maverick as CON](transcripts/prop_0214__gpt-5.4-high__llama4-maverick__s0__tpl_placement_active_20260320f.md)
- [Debate B: Llama 4 Maverick as PRO, GPT-5.4 (high reasoning) as CON](transcripts/prop_0214__llama4-maverick__gpt-5.4-high__s1__tpl_placement_active_20260320f.md)
- [Matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260430a__debate_placement_active_20260320f/matchup-judgment-prop_0214-gpt-5.4-high-vs-llama4-maverick.md)
- [Raw judgment rows (search for `prop_0214`)](judgments/judge_results__judge_active_20260430a.csv)

Judge panel rows in this snapshot: Kimi K2.6 and Qwen 3.6 Max Preview.

Judged result:

- Debate A (`GPT PRO / Llama CON`): unanimous 2-0 for GPT-5.4 (high reasoning), with entertainment scores `7` and `4`
- Debate B (`Llama PRO / GPT CON`): unanimous 2-0 for GPT-5.4 (high reasoning), with entertainment scores `7` and `7`
- Across both side assignments: GPT-5.4 (high reasoning) won all 4 judge rows
- Mean entertainment across the full side-swapped pair: 6.25 / 10
- Average absolute judged margin across the four judge rows: 3.3

This is a cleaner blowout than the location-data example above. The better debater stays better as PRO and as CON, which is what a real benchmark gap should look like.

Why this one was decisive:

- In Debate A, GPT's PRO case is concrete from the start: the injury is ongoing, compensation is redress rather than charity, and archival access is part of proving what happened rather than just symbolic acknowledgment.
- Llama's CON case is morally sympathetic but more diffuse. It leans on complexity, resource diversion, and re-traumatization concerns without landing an equally sharp mechanism for why compensation and archive access are the wrong response.
- In the rematch, Llama's PRO case is serviceable but generic. GPT's CON case is much more pointed: descendant compensation becomes open-ended, privacy harms from broader file access become concrete, and the administrative line-drawing problem stays central through rebuttal and closing.
- The side swap still matters, but it does not change the ranking. GPT wins both assignments unanimously, so this pair reads much more like a stable separation than a frontier toss-up.

Taken together, the two examples show why the benchmark runs each matchup twice. Sometimes side-swapping reveals a genuinely close contest between elite models. Sometimes it confirms that the stronger debater is simply stronger on either side of the motion.

</details>

<details>
<summary>MiniMax-M2.7 vs Qwen3.5-397B-A17B on personalized dynamic pricing</summary>

Motion: Retailers should be banned from using personalized algorithmic dynamic pricing based on a customer's perceived willingness or ability to pay.

Full transcripts:

- [Debate A: MiniMax-M2.7 as PRO, Qwen3.5-397B-A17B as CON](transcripts/prop_0041__minimax-m2.7__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md)
- [Debate B: Qwen3.5-397B-A17B as PRO, MiniMax-M2.7 as CON](transcripts/prop_0041__qwen3.5-397b-a17b__minimax-m2.7__s1__tpl_placement_active_20260320f.md)
- [Matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260430a__debate_placement_active_20260320f/matchup-judgment-prop_0041-minimax-m2.7-vs-qwen3.5-397b-a17b.md)
- [Raw judgment rows (search for `prop_0041`)](judgments/judge_results__judge_active_20260430a.csv)

Judged result:

- Debate A (`MiniMax PRO / Qwen CON`): unanimous 2-0 for MiniMax-M2.7, with judge entertainment scores `8` and `8`
- Debate B (`Qwen PRO / MiniMax CON`): split 1-1, with judge entertainment scores `7` and `8`
- Across both side assignments: MiniMax-M2.7 won 3 of 4 judge rows overall
- Mean entertainment across the full side-swapped pair: 7.75 / 10
- Mean signed normalized margin for MiniMax-M2.7: +0.90

Why this one is worth reading:

- The same core clash appears from both sides: whether personalized pricing is vulnerability-based extraction or a way to discount for price-sensitive buyers.
- MiniMax's strongest PRO move is the distinction between transparent opt-in discounts and hidden profiling. It argues that revenue optimization is not a poverty program, even when some users receive lower prices.
- Qwen's strongest PRO move in the rematch is sharper and more compact: personalized pricing makes the public price private, so comparison shopping breaks at the exact moment consumers most need it.
- MiniMax's CON case is also more precise in the rematch. It argues that the real injury is non-consensual data profiling, not the price response itself, and that privacy and consumer-protection rules can target that harm without banning legitimate discounts.
- The result is a good example of a high-entertainment clash where one side wins the aggregate but the losing model still finds live pressure points in the rematch.

</details>

---

## Method Summary

### Topics

The benchmark draws from a large proposition bank intended to be understandable to an informed generalist while still varied enough to expose real differences between models. Topics are not limited to the safest generic policy prompts; the set includes empirical, normative, geopolitical, technological, and social disputes.

The working bank is intentionally broad. That matters because debate performance can be very topic-sensitive, and a narrow prompt family would make it too easy for models to overfit to one style of argument.

The current curated keep bank contains 683 topics. The latest status report sees 727 side-swapped groups and 701 rating-eligible public groups after incomplete and excluded groups are removed. Those rating-eligible groups cover 659 distinct topics; the chart-visible entertainment slice has signal on 658 topics.

Top-level topic coverage:

| Theme | Curated bank | Topics with debate artifacts | Topics in rating-eligible groups |
| --- | ---: | ---: | ---: |
| Law / regulation / courts | 135 | 135 | 131 |
| Labor / education / social policy | 122 | 122 | 115 |
| Media / culture / internet | 111 | 111 | 108 |
| Macro / trade / industrial policy | 108 | 108 | 103 |
| Health / bioethics | 65 | 65 | 64 |
| Energy / climate / infrastructure | 49 | 49 | 48 |
| Science / space / frontier tech | 34 | 34 | 33 |
| Business / antitrust / market structure | 28 | 28 | 28 |
| Geopolitics / defense / security | 24 | 24 | 22 |
| AI / tech policy | 7 | 7 | 7 |

Question-type coverage:

| Question type | Curated bank | Topics with debate artifacts | Topics in rating-eligible groups |
| --- | ---: | ---: | ---: |
| mixed | 466 | 466 | 450 |
| normative | 151 | 151 | 145 |
| empirical | 66 | 66 | 64 |

### Debate execution

For a selected model pair and topic:

1. The two models debate the proposition in a multi-turn format.
2. The same pair then debates the same proposition again with the sides reversed.
3. Both full debate transcripts are stored.

Each debate uses a 10-turn structure: PRO opening, CON opening, PRO rebuttal 1, CON rebuttal 1, PRO pressure questions, CON pressure questions, PRO rebuttal 2, CON rebuttal 2, PRO closing, and CON closing.

### Judging

Each completed debate is intended to be judged by a three-model panel. The raw judge outputs are retained, then parsed into structured winner, margin, and diagnostic rubric fields. The rubric sub-scores are useful diagnostics, but the main published ranking comes from the final side-swapped matchup outcome, not from directly averaging rubric categories into the leaderboard.
Panels are constructed from three distinct model families and, when feasible, avoid same-family judges against the debaters.

The current judge roster in this snapshot is drawn from GPT-5.5 (high reasoning), Claude Sonnet 4.6 (high reasoning), Gemini 3.1 Pro Preview, Qwen 3.6 Max Preview, Grok 4.3, and Kimi K2.6.

---

## Limits and caveats

- This is still a live benchmark, not a frozen final release.
- It uses LLM judges, not human judges, though the design reduces noise with side swaps, multiple judges, stored raw outputs, and agreement diagnostics.
- Some models are affected meaningfully by availability and content-filter behavior, which is why operational reliability is tracked alongside quality.
- Debate is only one capability slice. It is a rich one, but it is not the whole story about model usefulness.
- The current published snapshot is rebuilt from a clean filtered slice, so leaderboard and status counts can differ from the cumulative raw judgment CSV linked below.

Taken together, this benchmark measures which models currently look strongest at **sustained, adversarial, multi-turn argumentation** under this setup.

---

## Qualitative Comparison Layer

The qualitative-comparison layer adds a curated set of transcript-driven writeups on top of the scored results. It focuses on strong side-swapped head-to-head pairs, combining a deterministic transcript-and-judge report with matchup summaries and a cross-pair synthesis.

The available set covers 19 selected side-swapped groups, 38 debates, and 5 models. It is there to show how wins happen: recurring style differences, win conditions, pressure-round usage, and places where the transcripts are more nuanced than the topline result.

**Claude Opus 4.7** stands out in that set for repeatedly narrowing each debate to one clean decision point and then closing on it. Against GPT-5.4, Gemini, Grok, and Kimi, the recurring pattern is early hinge selection followed by strong pressure conversion: "commitment versus silence" on support-lifespan labeling, upstream influence versus reactive alternatives on worker board seats, EMTALA-style administrability on clinicians refusing care, and what actually counts as diversification in Gulf-state development.

Read the [qualitative comparison report](reports/qualitative_model_comparisons__judge_judge_active_20260321b__debate_placement_active_20260320f.md), [matchup summaries](reports/qualitative_model_comparison_summaries__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md), and [cross-pair synthesis](reports/qualitative_model_comparison_synthesis__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md).

---

## Full Artifacts

- [Current leaderboard markdown](reports/debate_leaderboard__judge_judge_active_20260430a__debate_placement_active_20260320f.md)
- [Current benchmark status](reports/debate_benchmark_status__judge_judge_active_20260430a__debate_placement_active_20260320f.md)
- [Current model profiles](reports/debate_model_profiles__judge_judge_active_20260430a__debate_placement_active_20260320f.md)
- [Current model dossiers](reports/debate_model_dossiers__judge_judge_active_20260430a__debate_placement_active_20260320f__gpt-5.4-low.md)
- [Qualitative comparison report](reports/qualitative_model_comparisons__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Qualitative comparison summaries](reports/qualitative_model_comparison_summaries__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)
- [Qualitative comparison synthesis](reports/qualitative_model_comparison_synthesis__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)
- [Current entertainment report](reports/debate_entertainment_report__judge_judge_active_20260430a__debate_placement_active_20260320f.md)
- [Current matchup judgment index](reports/debate_matchup_judgments__judge_judge_active_20260430a__debate_placement_active_20260320f.md)
- [Highlights report](reports/debate_highlights__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-low.md)
- [Current Bradley-Terry chart](images/debate_bt_ratings__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current content-block-rate chart](images/debate_content_block_rate__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current strength-vs-reliability chart](images/debate_strength_vs_reliability__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current reliability-breakdown chart](images/debate_reliability_breakdown__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current price-vs-performance chart](images/debate_price_vs_performance__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current pairwise heatmap](images/debate_pair_margin_heatmap__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current judge-agreement heatmap](images/debate_judge_agreement_heatmap__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [Current strength-vs-entertainment chart](images/debate_strength_vs_entertainment__judge_judge_active_20260430a__debate_placement_active_20260320f.png)
- [All clean completed public debate transcripts](transcripts/)
- [Current raw judgment table (CSV)](judgments/judge_results__judge_active_20260430a.csv)
- [Current raw judgment rows (JSONL)](judgments/judge_results__judge_active_20260430a.jsonl)

## Related Benchmarks

This benchmark sits alongside other public LLM evaluations that probe different failure modes and capabilities:

- [LLM Sycophancy Benchmark](https://github.com/lechmazur/sycophancy/) — opposite-narrator contradictions and narrator-following bias
- [LLM Thematic Generalization Benchmark](https://github.com/lechmazur/generalization/) — latent-category induction from examples and counterexamples
- [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing/) — short-story quality under fixed required elements
- [BAZAAR: Auction Market Benchmark](https://github.com/lechmazur/bazaar/) — strategic bidding in a competitive simulated market
- [Buyout Game Benchmark](https://github.com/lechmazur/buyout_game/) — multi-agent bargaining, transfers, and hostile takeovers under explicit financial incentives
- [PACT](https://github.com/lechmazur/pact/) — multi-round buyer-seller bargaining with hidden values, public messages, and carried-forward bids and asks
- [LLM Persuasion Benchmark](https://github.com/lechmazur/persuasion/) — multi-turn persuasion measured by how much one model moves another model’s stated position
- [LLM Round-Trip Translation Benchmark](https://github.com/lechmazur/translation/) — meaning and voice retained after translating out of English and back
- [Step Race: Collaboration vs. Misdirection Under Pressure](https://github.com/lechmazur/step_game/) — multi-agent public conversation before private move selection
- [Elimination Game: Social Reasoning and Deception in Multi-Agent LLMs](https://github.com/lechmazur/elimination_game/) — alliance formation, deception, and jury persuasion
- [Extended NYT Connections](https://github.com/lechmazur/nyt-connections/) — harder category induction with extra distractor words

Debate is the one in this group most directly about adversarial reasoning with an active opponent.

---

## Updates

- `2026-05-04`: Updated the public ratings, bringing the leaderboard to 29 rated models with GPT-5.5, GLM-5.1, Kimi K2.6, Xiaomi MiMo V2.5 Pro, Qwen 3.6 Max Preview, DeepSeek V4 Pro, Tencent Hy3 Preview (high reasoning), Grok 4.3, and Mistral Medium 3.5 High Reasoning added to the visible board.
- `2026-04-20`: Added Claude Opus 4.7 (high reasoning) to the published board, bringing the leaderboard to 22 rated models. Qualitative comparison layer added.
- `2026-03-22`: First release with 21 rated models: Claude Sonnet 4.6 (high reasoning), GPT-5.4 (high reasoning), Claude Opus 4.6 (high reasoning), Claude Sonnet 4.6 (no reasoning), Gemini 3.1 Pro Preview, GLM-5, Claude Opus 4.6 (no reasoning), Kimi K2.5 Thinking, GPT-5.4 (no reasoning), ByteDance Seed2.0 Pro, MiniMax-M2.7, Grok 4.20 Beta 0309 (Reasoning), Qwen3.5-397B-A17B, Grok 4.20 Beta 0309 (Non-Reasoning), Xiaomi MiMo V2 Pro, DeepSeek V3.2, Gemini 3.1 Flash-Lite Preview, GPT-OSS-120B, Baidu Ernie 5.0, Mistral Large 3, and Llama 4 Maverick.

---
