# LLM Debate Benchmark: Adversarial Multi-Turn Argument Under Opposition

This benchmark measures how well large language models perform in adversarial, multi-turn debates across a wide range of propositions. Strong performance is not just about producing a polished first answer. It requires broad knowledge, accurate use of relevant facts under pressure, strong rebuttal, and the ability to stay coherent, responsive, and defensible over several rounds.

Each evaluated matchup runs twice on the **same topic with sides swapped**. A three-model judge panel then decides winner and margin, and the published leaderboard is Bradley-Terry over completed side-swapped matchups.

---

![Bradley-Terry leaderboard](images/debate_bt_ratings__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

---

## How to read the main chart

- Each bar is one model’s current **Bradley-Terry rating**.
- Higher bars mean stronger judged debate performance.
- Bradley-Terry is a relative within-pool rating centered near `1500`; it is not an absolute capability score.
- The grey band behind each bar is the **95% robust confidence interval** for that model’s rating.
- The published order uses **Bradley-Terry**.

---

## Current Snapshot

- **22 rated models**
- **1,273 completed debate artifacts in the current debate scope**
- **653 side-swapped groups in the current status report before incomplete and excluded groups are removed**
- **620 rating-eligible side-swapped matchups in the clean aggregated slice**
- **1,240 clean rated debates and 3,718 parsed judgment rows in that slice**

One side-swapped matchup means two debates on the same motion with PRO and CON roles reversed. Under a complete three-judge panel, that normally produces six judge rows across the two debates; the current clean slice is two parsed judge rows short of that maximum after filtering.

The public transcript directory mirrors the clean completed debates that are safe to read directly. It currently has 1,253 transcript files because 20 completed judged debates are excluded from the public mirror after transcript-quality filtering.

The stored rating table currently has 22 rated models. Most public chart views show the 20 chart-visible models after report-time suppression and chart-specific metadata filters.

---

## Reader Paths

There are four useful ways to read this snapshot:

1. **Fast ranking check**: start with the Bradley-Terry chart, then use the [full leaderboard table](#current-full-leaderboard) to see coverage for each model.
2. **Design sanity check**: read the [pairwise heatmap](#pairwise-view), [judge sanity checks](#judge-sanity-checks), [cross-judge agreement heatmap](#cross-judge-agreement), [benchmark status](reports/debate_benchmark_status__judge_judge_active_20260321b__debate_placement_active_20260320f.md), [reliability diagnostics](#reliability-diagnostics), and [opinion-shift diagnostics](#opinion-shift-diagnostics) to see whether the headline ranking is being distorted by narrow matchups, judge disagreement, operational failures, or stance drift toward the side a model just argued.
3. **Transcript-level read**: jump to the [worked examples](#worked-examples), then use the [matchup judgment index](reports/debate_matchup_judgments__judge_judge_active_20260321b__debate_placement_active_20260320f.md), [model profiles](reports/debate_model_profiles__judge_judge_active_20260321b__debate_placement_active_20260320f.md), and [qualitative comparison layer](#qualitative-comparison-layer) for broader transcript-driven patterns.
4. **Quality/readability check**: use the [debate quality signal](#debate-quality-signal) and [entertainment report](reports/debate_entertainment_report__judge_judge_active_20260321b__debate_placement_active_20260320f.md) to see which models produce debates judges found readable or engaging. This is diagnostic only and does not affect ratings.

The chart bundle is meant to answer “who is ahead?” quickly. The worked examples and qualitative reports are meant to answer the more important follow-up: “what did the better debate actually look like?”

---

## Pairwise View

The pairwise heatmap shows how models perform against each other after aggregation across completed, side-swapped matchups. This is useful because a single scalar leaderboard always hides some structure. A model can be strong overall while still having a few specific bad matchups.

![Pairwise heatmap](images/debate_pair_margin_heatmap__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

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
| 1 | Claude Opus 4.7 (high reasoning) | 1718.8 | 55 |
| 2 | Claude Sonnet 4.6 (high reasoning) | 1612.4 | 83 |
| 3 | GPT-5.4 (high reasoning) | 1605.7 | 84 |
| 4 | Claude Opus 4.6 (high reasoning) | 1598.5 | 80 |
| 5 | Claude Sonnet 4.6 (no reasoning) | 1592.9 | 87 |
| 6 | Gemini 3.1 Pro Preview | 1590.4 | 68 |
| 7 | Claude Opus 4.6 (no reasoning) | 1579.3 | 81 |
| 8 | Kimi K2.5 Thinking | 1547.1 | 85 |
| 9 | GPT-5.4 (no reasoning) | 1543.7 | 96 |
| 10 | ByteDance Seed2.0 Pro | 1541.9 | 64 |
| 11 | GLM-5 | 1535.9 | 55 |
| 12 | MiniMax-M2.7 | 1519.0 | 55 |
| 13 | Grok 4.20 Beta 0309 (Reasoning) | 1511.5 | 52 |
| 14 | Qwen3.5-397B-A17B | 1502.3 | 48 |
| 15 | Grok 4.20 Beta 0309 (Non-Reasoning) | 1476.2 | 37 |
| 16 | Xiaomi MiMo V2 Pro | 1474.6 | 32 |
| 17 | DeepSeek V3.2 | 1464.6 | 41 |
| 18 | Gemini 3.1 Flash-Lite Preview | 1459.4 | 33 |
| 19 | GPT-OSS-120B | 1352.9 | 32 |
| 20 | Baidu Ernie 5.0 | 1346.0 | 16 |
| 21 | Mistral Large 3 | 1312.0 | 25 |
| 22 | Llama 4 Maverick | 1115.1 | 31 |

`BT` is the headline Bradley-Terry rating. `Matchups` is the number of completed side-swapped matchups for that model in the clean aggregated slice.

---


## What Stands Out

The current picture has one clear provisional leader, a still-crowded frontier just below it, family-dependent reasoning gains, and clearer separation in the lower half of the field than at the top.

- **Claude Opus 4.7 currently leads the published board, but on narrower coverage than the most-established active models.** It sits at 1718.8 BT across 55 completed side-swapped matchups. That is a strong result, but it should still be read as less settled than the heavily-tested active cluster below it.
- **The active-model frontier is still real and not fully settled.** The strongest active BT cluster is Claude Sonnet 4.6 (high reasoning), GPT-5.4 (high reasoning), Claude Opus 4.6 (high reasoning), Claude Sonnet 4.6 (no reasoning), and Gemini 3.1 Pro Preview. That group is still close enough that more data could reshuffle the middle.
- **Reasoning mode is helping, but the size of the gain depends heavily on the family.** In the current snapshot, GPT-5.4 high reasoning beats GPT-5.4 no reasoning by about `62.0` BT points, Grok reasoning beats Grok non-reasoning by about `35.3`, Claude Sonnet 4.6 high reasoning beats Claude Sonnet 4.6 no reasoning by about `19.5`, and Claude Opus 4.6 high reasoning beats Claude Opus 4.6 no reasoning by about `19.2`.
- **Judges are rewarding rebuttal quality and argument strength more than isolated style.** The top cluster is repeatedly described in the model profiles as disciplined, grounded, clash-driven, and responsive. Lower-ranked models often retain some mix of grounding, originality, or rhetorical effectiveness, but still lose because they underperform on rebuttal quality and argument strength.
- **The clearest current blowouts are mostly in the lower part of the field, not at the frontier.** The largest average pairwise edges are still concentrated against Llama 4 Maverick, with Claude Opus 4.6 (high reasoning) over Llama 4 Maverick at about `+3.1`, Kimi K2.5 Thinking over Llama 4 Maverick at about `+3.0`, and GPT-5.4 (high reasoning) over Llama 4 Maverick at about `+2.8`. That is another way of seeing that the bottom of the table is more separated than the top.

---

## Price vs. Performance

The price chart reads the same Bradley-Terry strength signal against shared standard API list prices. The x-axis is input plus output USD per 1M tokens, so it is a simple list-price comparison rather than measured cost for this exact debate prompt shape.

![Price versus performance](images/debate_price_vs_performance__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

Higher and further left is better on this view. Vertical grey bands show the same BT uncertainty interval as the main chart. Only models with price metadata are plotted.

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
- mean cross-judge winner agreement is 0.576, measured as the fraction of overlapping side-swapped matchup decisions where two judges picked the same winner
- mean absolute presented-side margin bias by judge is 0.109 on the signed margin scale
- the canonical parsed judgment table currently has 0 parse-warning rows
- the active judge pool for new rows includes Claude Sonnet 4.6 (high reasoning), GPT-5.4 (high reasoning), Gemini 3.1 Pro Preview, Grok 4.20 Beta 0309 (Reasoning), Qwen3.5-397B-A17B, and Kimi K2.5 Thinking
- the cumulative judge scope also contains carried-over historical rows from MiniMax-M2.7

This does not make the judges perfect. But it does mean the current snapshot is not obviously being driven by parser chaos or a huge systematic side-presentation artifact.
Panels are built from distinct model families and avoid same-family judges against the debaters when feasible.

---

## Cross-Judge Agreement

The judge-agreement data are also rendered directly as a heatmap so it is easier to see which evaluators tend to move together and which pairs diverge more often.

![Judge agreement heatmap](images/debate_judge_agreement_heatmap__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

Each off-diagonal cell is a judge-pair agreement rate; the number in parentheses is the count of overlapping side-swapped matchup groups. The diagonal cells are judge identifiers, not data cells. The heatmap uses the cumulative judge scope, so it includes carried-over MiniMax-M2.7 rows in addition to the current active judge pool.

This is a sanity-check view, not a second leaderboard. It is there to make evaluator consistency visible rather than bury it inside one summary statistic.

---

## Debate Quality Signal

The benchmark also tracks a judge-side entertainment/readability diagnostic as a secondary signal. It does not affect ratings, but it is useful for checking whether the benchmark produces debates that are merely formal or actually engaging to read.

- mean entertainment across complete side-swapped matchups: 7.11 / 10
- most entertaining current models by that signal include Claude Opus 4.7 (high reasoning), Claude Sonnet 4.6 (high reasoning), Claude Sonnet 4.6 (no reasoning), and Kimi K2.5 Thinking

High-entertainment matchup examples from the current scope:

- Claude Opus 4.7 (high reasoning) vs Kimi K2.5 Thinking on space tourism under climate change and global poverty
- Claude Opus 4.7 (high reasoning) vs Claude Sonnet 4.6 (no reasoning) on banning private cars from central city districts
- Claude Opus 4.7 (high reasoning) vs Kimi K2.5 Thinking on permanent asteroid-deflection infrastructure

This signal is diagnostic rather than decisive, but it helps show that the benchmark is producing debates judges generally find readable and engaging.
For the chart-visible model table and example matchups, see the [current entertainment report](reports/debate_entertainment_report__judge_judge_active_20260321b__debate_placement_active_20260320f.md). That report hides report-time suppressed models by default, so its visible-matchup mean can differ slightly from the all-clean-slice mean above.

![Strength versus entertainment](images/debate_strength_vs_entertainment__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

In the scatter, the x-axis is BT, the y-axis is mean entertainment/readability score, bubble size is rated matchup coverage, and grey horizontal bands show BT uncertainty.

Read against the main strength rating, this view separates three cases that a single leaderboard hides: models that are strong and lively, models that are strong but comparatively dry, and models that are readable or vivid without being top-tier debaters. Entertainment still stays diagnostic only; it does not feed the rating.

---

## Best Lines

The current transcript-highlights pass also surfaces lines that are worth quoting in their own right. A few of the strongest from the current scope:

This is an LLM-selected post-run highlight pass, not a rating input and not human curation.

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

Read the [full highlights report](reports/debate_highlights__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-low.md) for the longer ranked list and source debate links.

---

## Content Block Rate

Content blocks reflect a distinct moderation/content-fragility problem rather than simple latency, parser trouble, or blank outputs.
This is not an overall reliability or request-failure rate; blank outputs, parser failures, and request failures are tracked separately in the [current benchmark status](reports/debate_benchmark_status__judge_judge_active_20260321b__debate_placement_active_20260320f.md).

![Content block rate](images/debate_content_block_rate__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

In the broader seen-attempt denominator, including attempts that may not enter the clean rated slice, Xiaomi MiMo V2 Pro is still the clear outlier at 9.6% of seen debates ending in a content block (`10 / 104`). The next highest rates are Grok 4.20 Beta 0309 (Non-Reasoning) at 3.8%, Kimi K2.5 Thinking at 2.2%, and Qwen3.5-397B-A17B at 1.9%. Most of the highest-rated models are at or near zero on this specific measure, including both current GPT-5.4 variants, Claude Opus 4.6 (high reasoning), and ByteDance Seed2.0 Pro.

![Strength versus content blocks](images/debate_content_block_vs_strength__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

In the scatter, the x-axis is BT from the clean rated slice, while the y-axis is content-block share over broader seen debate attempts. Bubble size is rated side-swapped matchup coverage; grey horizontal bands show BT uncertainty.

The scatter is useful because it separates "strong but occasionally brittle" from "strong and operationally clean." Xiaomi MiMo V2 Pro is the clearest high-block-rate outlier. Kimi K2.5 Thinking and Grok 4.20 Beta 0309 (Non-Reasoning) also show visible content-block exposure, while most frontier models cluster in the lower-right with much lower block rates.

---

## Reliability Diagnostics

Content blocks are only one operational failure mode. The reliability views show the broader availability picture: completed debates, content blocks, blank outputs, validation failures, request failures, and other terminal errors over seen debate attempts.

![Strength versus reliability](images/debate_strength_vs_reliability__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

The dumbbell chart keeps raw BT as the headline quality score and shows how an availability-adjusted score would move when operational failures are penalized. Longer connectors mean a larger reliability penalty; they do not mean the completed debates were judged worse.

![Reliability breakdown](images/debate_reliability_breakdown__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

The stacked breakdown is the best view when the question is what kind of operational issue occurred. In the status table, content blocks are a subset of terminal errors, so content-block rates use the availability table's seen-attempt denominator rather than adding the content-block count a second time.

---

## Worked Examples

If you want to jump straight into transcript pairs that are especially worth reading:

- Frontier matchup: Claude Sonnet 4.6 (high reasoning) vs GPT-5.4 (high reasoning) on banning location-data sales. This is one of the best current top-tier matchups to read because the topic is strong, the execution is strong, and the side swap materially changes the picture. Mean entertainment across the pair: 7.83 / 10. Read [Debate A](transcripts/prop_0541__claude-sonnet-4-6-adaptive__gpt-5.4-high__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0541__gpt-5.4-high__claude-sonnet-4-6-adaptive__s1__tpl_placement_active_20260320f.md), and the [matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260321b__debate_placement_active_20260320f/matchup-judgment-prop_0541-claude-sonnet-4-6-adaptive-vs-gpt-5.4-high.md).
- Clear separation example: GPT-5.4 (high reasoning) vs Llama 4 Maverick on forced-sterilization redress. This is a cleaner blowout where the stronger debater stays better as PRO and as CON. Read [Debate A](transcripts/prop_0214__gpt-5.4-high__llama4-maverick__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0214__llama4-maverick__gpt-5.4-high__s1__tpl_placement_active_20260320f.md), and the [matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260321b__debate_placement_active_20260320f/matchup-judgment-prop_0214-gpt-5.4-high-vs-llama4-maverick.md).
- Most quotable current pair: MiniMax-M2.7 vs Qwen3.5-397B-A17B on algorithmic dynamic pricing. This is the sharpest current read if you want memorable lines rather than just benchmark hygiene, and it is essentially a dead heat. Read [Debate A](transcripts/prop_0041__minimax-m2.7__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md), [Debate B](transcripts/prop_0041__qwen3.5-397b-a17b__minimax-m2.7__s1__tpl_placement_active_20260320f.md), and the [matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260321b__debate_placement_active_20260320f/matchup-judgment-prop_0041-minimax-m2.7-vs-qwen3.5-397b-a17b.md).

<details>
<summary>Claude Sonnet 4.6 (high reasoning) vs GPT-5.4 (high reasoning) on banning location-data sales</summary>

Motion: Governments should prohibit data brokers from selling individuals’ precise location data without explicit, time-limited opt-in consent.

Full transcripts:

- [Debate A: Claude Sonnet 4.6 (high reasoning) as PRO, GPT-5.4 (high reasoning) as CON](transcripts/prop_0541__claude-sonnet-4-6-adaptive__gpt-5.4-high__s0__tpl_placement_active_20260320f.md)
- [Debate B: GPT-5.4 (high reasoning) as PRO, Claude Sonnet 4.6 (high reasoning) as CON](transcripts/prop_0541__gpt-5.4-high__claude-sonnet-4-6-adaptive__s1__tpl_placement_active_20260320f.md)
- [Matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260321b__debate_placement_active_20260320f/matchup-judgment-prop_0541-claude-sonnet-4-6-adaptive-vs-gpt-5.4-high.md)
- [Current rolling judgment rows (search for `prop_0541`)](judgments/judge_results__judge_active_20260321b.csv)

Judge panel on both side-swapped debates: Gemini 3.1 Pro Preview, Grok 4.20 Beta 0309 (Reasoning), and Qwen3.5-397B-A17B.

Judged result:

- Debate A (`Claude PRO / GPT CON`): split 2-1 for Claude Sonnet 4.6 (high reasoning), with judge entertainment scores `9`, `7`, and `8`
- Debate B (`GPT PRO / Claude CON`): 3-0 for GPT-5.4 (high reasoning), with judge entertainment scores `8`, `7`, and `8`
- Across both side assignments: GPT-5.4 (high reasoning) won 4 of 6 judge votes overall
- Mean entertainment across the full side-swapped pair: 7.83 / 10
- Average absolute judged margin across the six judge rows: 1.4

This is a good example of why the benchmark uses side-swapped relative judgments instead of a one-shot absolute score. One assignment was close and slightly favored Claude; the rematch, with roles reversed, favored GPT more clearly.

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
- [Matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260321b__debate_placement_active_20260320f/matchup-judgment-prop_0214-gpt-5.4-high-vs-llama4-maverick.md)
- [Current rolling judgment rows (search for `prop_0214`)](judgments/judge_results__judge_active_20260321b.csv)

Judge panel on both side-swapped debates: Claude Sonnet 4.6 (high reasoning), Kimi K2.5 Thinking, and Qwen3.5-397B-A17B.

Judged result:

- Debate A (`GPT PRO / Llama CON`): 3-0 for GPT-5.4 (high reasoning), with entertainment scores `5`, `6`, and `5`
- Debate B (`Llama PRO / GPT CON`): 3-0 for GPT-5.4 (high reasoning), with entertainment scores `6`, `7`, and `7`
- Across both side assignments: GPT-5.4 (high reasoning) won all 6 of 6 judge votes
- Mean entertainment across the full side-swapped pair: 6.0 / 10
- Average absolute judged margin across the six judge rows: 2.6

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
- [Matchup judgment report](reports/debate_matchup_judgments/judge_judge_active_20260321b__debate_placement_active_20260320f/matchup-judgment-prop_0041-minimax-m2.7-vs-qwen3.5-397b-a17b.md)
- [Current rolling judgment rows (search for `prop_0041`)](judgments/judge_results__judge_active_20260321b.csv)

Judged result:

- Debate A (`MiniMax PRO / Qwen CON`): split 2-1 for MiniMax-M2.7, with judge entertainment scores `7`, `8`, and `7`
- Debate B (`Qwen PRO / MiniMax CON`): split 2-1 for Qwen3.5-397B-A17B, with judge entertainment scores `7`, `8`, and `7`
- Across both side assignments: each model won 3 of 6 judge votes overall
- Mean entertainment across the full side-swapped pair: 7.33 / 10
- Mean signed normalized margin for MiniMax-M2.7: +0.06, effectively a dead heat

Why this one is worth reading:

- The same core clash appears from both sides: whether personalized pricing is vulnerability-based extraction or a way to discount for price-sensitive buyers.
- MiniMax's strongest PRO move is the distinction between transparent opt-in discounts and hidden profiling. It argues that revenue optimization is not a poverty program, even when some users receive lower prices.
- Qwen's strongest PRO move in the rematch is sharper and more compact: personalized pricing makes the public price private, so comparison shopping breaks at the exact moment consumers most need it.
- MiniMax's CON case is also more precise in the rematch. It argues that the real injury is non-consensual data profiling, not the price response itself, and that privacy and consumer-protection rules can target that harm without banning legitimate discounts.
- The result is a good example of a high-entertainment tie. Both models find live pressure points, both produce memorable lines, and neither side assignment fully settles the policy question.

</details>

---

## Method Summary

### Topics

The benchmark draws from a large proposition bank intended to be understandable to an informed generalist while still varied enough to expose real differences between models. Topics are not limited to the safest generic policy prompts; the set includes empirical, normative, geopolitical, technological, and social disputes.

The working bank is intentionally broad. That matters because debate performance can be very topic-sensitive, and a narrow prompt family would make it too easy for models to overfit to one style of argument.

The current curated keep bank contains 683 topics. The current debate scope has touched 653 distinct topics, and 620 of those are in the current clean rated slice after incomplete and quarantined side-swapped groups are excluded.

Top-level topic coverage in the current bank and evaluated slice:

| Domain | Curated bank | Topics seen in current debate scope | Topics in clean rated slice |
| --- | ---: | ---: | ---: |
| Law / regulation / courts | 135 | 130 | 122 |
| Labor / education / social policy | 122 | 114 | 108 |
| Media / culture / internet | 111 | 111 | 107 |
| Macro / trade / industrial policy | 108 | 100 | 93 |
| Health / bioethics | 65 | 64 | 61 |
| Energy / climate / infrastructure | 49 | 43 | 41 |
| Science / space / frontier tech | 34 | 34 | 33 |
| Geopolitics / defense / security | 24 | 24 | 23 |
| Business / antitrust / market structure | 28 | 26 | 26 |
| AI / tech policy | 7 | 7 | 6 |

Question-type coverage:

| Question type | Curated bank | Topics seen in current debate scope | Topics in clean rated slice |
| --- | ---: | ---: | ---: |
| mixed | 466 | 442 | 418 |
| normative | 151 | 148 | 140 |
| empirical | 66 | 63 | 62 |

### Debate execution

For a selected model pair and topic:

1. The two models debate the proposition in a multi-turn format.
2. The same pair then debates the same proposition again with the sides reversed.
3. Both full debate transcripts are stored.

Each debate uses a 10-turn structure: PRO opening, CON opening, PRO rebuttal 1, CON rebuttal 1, PRO pressure questions, CON pressure questions, PRO rebuttal 2, CON rebuttal 2, PRO closing, and CON closing.

### Judging

Each completed debate is intended to be judged by a three-model panel. The raw judge outputs are retained, then parsed into structured winner, margin, and diagnostic rubric fields. The rubric sub-scores are useful diagnostics, but the main published ranking comes from the final side-swapped matchup outcome, not from directly averaging rubric categories into the leaderboard.
Panels are constructed from three distinct model families and, when feasible, avoid same-family judges against the debaters.

The current judge roster in this snapshot is drawn from Claude Sonnet 4.6 (high reasoning), GPT-5.4 (high reasoning), Gemini 3.1 Pro Preview, Grok 4.20 Beta 0309 (Reasoning), Qwen3.5-397B-A17B, and Kimi K2.5 Thinking, with some earlier carried-over rows from MiniMax-M2.7 in the cumulative judge scope.

---

## Limits and caveats

- This is still a live benchmark, not a frozen final release.
- It uses LLM judges, not human judges, though the design reduces noise with side swaps, multiple judges, stored raw outputs, and agreement diagnostics.
- Some models are affected meaningfully by availability and content-filter behavior, which is why operational reliability is tracked alongside quality.
- Debate is only one capability slice. It is a rich one, but it is not the whole story about model usefulness.
- The current judge scope is cumulative and still evolving, and this published rolling snapshot spans a live judge-prompt refresh inside the same template scope. It should be read as a strong live snapshot rather than a frozen historical release.
- The current published snapshot is rebuilt from the clean filtered slice of that rolling judge scope, so the leaderboard and status counts intentionally differ from the cumulative raw judgment CSV linked below.

Taken together, this benchmark measures which models currently look strongest at **sustained, adversarial, multi-turn argumentation** under this setup.

---

## Qualitative Comparison Layer

The [qualitative-comparison layer](reports/qualitative_model_comparisons__judge_judge_active_20260321b__debate_placement_active_20260320f.md) adds a selected set of transcript-driven writeups on top of the scored results. It focuses on strong side-swapped head-to-head pairs, combining a deterministic transcript-and-judge report with [matchup summaries](reports/qualitative_model_comparison_summaries__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md) and a [cross-pair synthesis](reports/qualitative_model_comparison_synthesis__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md).

The current set covers 19 selected side-swapped groups, 38 debates, and 5 models. It is there to show how wins happen: recurring style differences, win conditions, pressure-round usage, and places where the transcripts are more nuanced than the topline result.
It is a deliberately selected qualitative sample, not a representative subset and not a second leaderboard; win/loss counts in that report describe only the selected comparison set.
Use this layer when the question is not just who won, but what transcript-level patterns produced the wins.

**Claude Opus 4.7** stands out in that set for repeatedly narrowing each debate to one clean decision point and then closing on it. Against GPT-5.4, Gemini, Grok, and Kimi, the recurring pattern is early hinge selection followed by strong pressure conversion: "commitment versus silence" on support-lifespan labeling, upstream influence versus reactive alternatives on worker board seats, EMTALA-style administrability on clinicians refusing care, and what actually counts as diversification in Gulf-state development. 

---

## Opinion-Shift Diagnostics

The [opinion-shift report](reports/debate_opinion_shift_report__judge_judge_active_20260321b__debate_placement_active_20260320f.md) is separate from the debate leaderboard. It uses fresh post-run stance probes of the participant model. "After arguing PRO/CON" means the model is shown the stored single-debate transcript in which it argued that side, then asked again for support on the motion.

The support scale is `0` for strongest opposition, `50` for neutral, and `100` for strongest support. These charts do not affect BT ratings.

Start with the magnitude-by-argued-side chart and the toward-own-argued-side chart:

![Opinion-shift magnitude by argued side](images/debate_opinion_shift_mean_abs_by_argued_side__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

![Opinion-shift movement toward own argued side](images/debate_opinion_shift_mean_toward_argued_side__judge_judge_active_20260321b__debate_placement_active_20260320f.png)

Use the mean-absolute charts to see how much a model moves, regardless of direction. Use the mean-signed and before-vs-after charts to see movement on the raw PRO-support scale. Signed drift should be read alongside before scores; because baseline support is often above neutral, negative drift can partly reflect movement back toward neutrality. Use the neutral-crossing charts to see how often a model crosses the neutral point. Use the toward-own-argued-side chart when the question is whether the model moved toward the side it personally argued; CON legs are sign-flipped there, so positive means movement toward the side the model argued, not necessarily higher PRO support.

Opinion-shift coverage is smaller than the main rated slice because it requires before/after stance probes: the report has 566 visible side-swapped groups with at least one parsed shift, while the public argued-side charts cover 564 visible groups and 1,128 debate-leg exposures rather than the full 620 clean rated matchups.

---

## Full Artifacts

- [Current leaderboard markdown](reports/debate_leaderboard__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current benchmark status](reports/debate_benchmark_status__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current model profiles](reports/debate_model_profiles__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current model dossiers](reports/debate_model_dossiers__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)
- [Current qualitative comparison report](reports/qualitative_model_comparisons__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current qualitative comparison summaries](reports/qualitative_model_comparison_summaries__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)
- [Current qualitative comparison synthesis](reports/qualitative_model_comparison_synthesis__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-medium.md)
- [Current entertainment report](reports/debate_entertainment_report__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current matchup judgment index](reports/debate_matchup_judgments__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current highlights report](reports/debate_highlights__judge_judge_active_20260321b__debate_placement_active_20260320f__gpt-5.4-low.md)
- [Current opinion-shift report](reports/debate_opinion_shift_report__judge_judge_active_20260321b__debate_placement_active_20260320f.md)
- [Current Bradley-Terry chart](images/debate_bt_ratings__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current content-block-rate chart](images/debate_content_block_rate__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current strength-vs-content-blocks chart](images/debate_content_block_vs_strength__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current strength-vs-reliability chart](images/debate_strength_vs_reliability__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current reliability-breakdown chart](images/debate_reliability_breakdown__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current price-vs-performance chart](images/debate_price_vs_performance__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current pairwise heatmap](images/debate_pair_margin_heatmap__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current judge-agreement heatmap](images/debate_judge_agreement_heatmap__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current strength-vs-entertainment chart](images/debate_strength_vs_entertainment__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-PRO mean-absolute chart](images/debate_opinion_shift_mean_abs_after_arguing_pro__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-PRO mean-signed chart](images/debate_opinion_shift_mean_signed_after_arguing_pro__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-PRO neutral-crossing chart](images/debate_opinion_shift_neutral_crossing_rate_after_arguing_pro__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-PRO before-vs-after chart](images/debate_opinion_shift_mean_support_before_after_after_arguing_pro__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-CON mean-absolute chart](images/debate_opinion_shift_mean_abs_after_arguing_con__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-CON mean-signed chart](images/debate_opinion_shift_mean_signed_after_arguing_con__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-CON neutral-crossing chart](images/debate_opinion_shift_neutral_crossing_rate_after_arguing_con__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift argued-CON before-vs-after chart](images/debate_opinion_shift_mean_support_before_after_after_arguing_con__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift magnitude by argued-side chart](images/debate_opinion_shift_mean_abs_by_argued_side__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift combined argued-side mean-signed chart](images/debate_opinion_shift_mean_signed_by_argued_side__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift combined argued-side neutral-crossing chart](images/debate_opinion_shift_neutral_crossing_rate_by_argued_side__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [Current opinion-shift toward-own-argued-side chart](images/debate_opinion_shift_mean_toward_argued_side__judge_judge_active_20260321b__debate_placement_active_20260320f.png)
- [All clean completed debate transcripts in the current judged scope](transcripts/)
- [Current rolling raw judgment table (CSV)](judgments/judge_results__judge_active_20260321b.csv)
- [Current rolling raw judgment rows (JSONL)](judgments/judge_results__judge_active_20260321b.jsonl)

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

- `2026-04-20`: Added Claude Opus 4.7 (high reasoning) to the published board, bringing the leaderboard to 22 rated models. Qualitative comparison layer added.
- `2026-03-22`: First release with 21 rated models: Claude Sonnet 4.6 (high reasoning), GPT-5.4 (high reasoning), Claude Opus 4.6 (high reasoning), Claude Sonnet 4.6 (no reasoning), Gemini 3.1 Pro Preview, GLM-5, Claude Opus 4.6 (no reasoning), Kimi K2.5 Thinking, GPT-5.4 (no reasoning), ByteDance Seed2.0 Pro, MiniMax-M2.7, Grok 4.20 Beta 0309 (Reasoning), Qwen3.5-397B-A17B, Grok 4.20 Beta 0309 (Non-Reasoning), Xiaomi MiMo V2 Pro, DeepSeek V3.2, Gemini 3.1 Flash-Lite Preview, GPT-OSS-120B, Baidu Ernie 5.0, Mistral Large 3, and Llama 4 Maverick.

---
