# Debate Model Dossiers

Reviewed against the benchmark evidence. The unedited model-generated drafts are retained separately.

Generated with **GPT-5.6 Sol (medium)** for **6 current-roster models**, using only complete current-v-current qualitative model cards.

These are model-generated syntheses, not independent human assessments. Use the quoted evidence and deterministic statistics to audit conclusions, especially when the author and subject share a model family.

## Claude Fable 5.1 (high)

### Style

A highly comparative, mechanism-first debater. Blind transcripts show direct engagement in 299/302 debates, weighing in 265/302, and burden contests in 173/302. It frequently narrows motions to the exact comparative obligation—“The motion is comparative. Not "affordable," but "more affordable."”—then tests both worlds through timing, incentives, and counterfactual effects. Progression appeared in 174/302 debates, suggesting arguments often develop rather than merely repeat.

### Strengths

Judge diagnostics are uniformly above the current field. Rebuttal is the clearest edge: 8.10 mean, +0.71 versus field, and +1.03 against opponents (95% CI +0.89 to +1.16). Argument strength is 8.03, with a +0.88 opponent advantage; rhetorical effectiveness reaches 8.30.

Judges most often identified direct engagement: 640/906 covered judge rows, with panel majorities in 232/302 debates. Argument construction reached majorities in 152/302, and weighing in 96/302. Recurring favorable examples show disciplined counterfactual control, including neutralizing objections as common to both worlds: “those macro trends apply to both worlds.”

Originality is another notable strength at 7.60, +0.73 above field.

### Weaknesses

Grounding/epistemics has the smallest opponent-relative advantage (+0.47). Its mean of 7.78 remains +0.44 above the field. Explicit evidence-use events were recorded in 99/906 judge rows, with panel majorities in 20/302 debates; this is a mention rate, not an evidence success rate or proof of weak sourcing.

The model can consume nearly all available space, creating a concrete delivery risk: 26.2% of turns were deterministically clipped. That may truncate conclusions or late weighing despite otherwise strong rhetoric.

Outcome annotations also contain some ambiguity: judge disagreement appeared in 78/301 debates and conflicted links in 63/301. These are associations, not causal diagnoses.

### Execution

Across 302 debates and 1,510 turns, it averaged 264.3 words per turn and used 92.4% of the word limit. Required Q/A labels were followed perfectly, and cited internal claim IDs had no missing-ID cases. Execution is therefore structurally reliable but overly close to capacity.

### Side Effects

Performance is balanced by side: argument strength was 8.07 PRO versus 7.99 CON; rebuttal slightly favored CON, 8.15 versus 8.06. In 151 event-bearing side-swap groups, stable behavior appeared in all groups and advocacy flexibility in 103.

Still, evidence asymmetry appeared in 48 groups, moral-standard asymmetry in 35, and side-specific behavior in 28. Contradiction candidates appeared in 86/151, but these are review flags—not established inconsistencies.

### Overall Read

A forceful, flexible comparative debater whose strongest recurring traits are direct rebuttal, counterfactual framing, and explicit weighing. Judge-perceived strength is broad and statistically clear; deterministic execution is compliant but clipping-prone. Side asymmetries warrant review, while the available evidence does not establish systematic inconsistency.

## GLM-5.3 (high)

### Style

GLM-5.3 (high) debates by fixing the burden early, interrogating mechanisms, and then weighing practical consequences. Blind transcripts showed question-type behavior in 192/196 debates, direct engagement in 190/196, weighing in 168/196, and strategic concessions in 121/196. A characteristic framing is: “The proposition is not "four-day weeks are nice." It is that the state should mandate them, by statute, at zero reduction in base pay.”

Across 98 side-swap groups, behavior was stable in all 98; advocacy flexibility appeared in 66. It regularly grants a limited opposing point, then narrows its significance or pivots to its own mechanism.

### Strengths

Judge diagnostics are uniformly above the current field:

- **Rebuttal:** 7.82, +0.42 versus field; +0.56 over opponents.
- **Rhetoric:** 8.07, +0.40 versus field; +0.54 over opponents.
- **Originality:** 7.30, +0.42 versus field; +0.47 over opponents.
- **Argument strength:** 7.74, +0.33 versus field; +0.42 over opponents.
- **Grounding:** 7.59, +0.24 versus field; +0.21 over opponents.

Direct engagement reached panel majority in 134/196 debates; argument construction did so in 99/196. Favorable examples emphasize concrete operational grounding and reversal of opposing evidence—including having “cleanly flipped Side B’s historical Ford example.”

### Weaknesses

The clearest limitation is **clipping**: 18.2% of turns were deterministically cut off, despite average word-limit use of 88.9%. This creates avoidable risk for late-stage weighing or conclusions.

Performance also tilts modestly toward **CON**. CON means exceeded PRO on rebuttal (7.98 vs. 7.66), originality (7.43 vs. 7.16), argument strength (7.80 vs. 7.67), and grounding (7.64 vs. 7.54); rhetoric was nearly symmetric.

Side swaps produced 65/98 contradiction candidates, 30/98 evidence-asymmetry flags, and 25/98 moral-standard-asymmetry flags. These are review signals—not established inconsistencies—but they warrant scrutiny given the otherwise strong stylistic stability.

### Evidence Frames

Judge salience and transcript behavior should not be conflated. Among **568 event-bearing judge rows**, direct engagement appeared in 65%, argument construction in 52%, and weighing in 31%. By contrast, blind transcript coding found direct engagement in 97% and weighing in 86% of **196 event-bearing debates**. Judge-consensus rates use all 587 annotated rows, including valid zero-event responses; low mention frequency is not evidence of weakness.

### Overall Read

A mechanism-first, burden-conscious debater with especially strong rebuttal, rhetoric, and originality. Its recurring edge is converting concrete details into direct clash and comparative weighing. The main practical vulnerability is frequent clipping, with a secondary CON-side advantage and unresolved side-swap consistency flags. Outcome links were aligned in 181/193 debates, though these are associations rather than causal evidence.

## GPT-6 Astra (high)

### Style

A comparative, burden-focused debater that narrows disputes to marginal costs and benefits rather than accepting broad moral framing: “The right comparison is not privacy versus children.” Blind transcripts show near-universal direct engagement (276/278 debates), frequent weighing (259/278), strategic concessions (231/278), and explicit burden setting (170/278). These are observed behaviors, not approval rates.

Questions often pressure-test the opponent’s strongest example, while concessions acknowledge the best opposing cost before pivoting to a narrower comparative claim.

### Strengths

Judges perceived particularly strong grounding/epistemics: **7.76**, +0.41 over the current field and +0.26 versus opponents (95% CI +0.17 to +0.34). Rebuttal was also strong at **7.61**, with a +0.23 opponent advantage (+0.07 to +0.39).

Direct engagement was the most recurrent judge-salient category: 476/794 event-bearing judge rows. Across all 834 judge rows, 172 of 278 debates reached panel majority for category presence. Favorable examples describe Astra directly breaking core analogies and forcing retreats through sharp questions.

### Weaknesses

Rhetorical effectiveness is the clearest judge-perceived weakness: **7.45**, −0.22 versus the field and −0.39 against opponents (−0.50 to −0.28). Clarity itself was only tagged in 61/834 rows and reached panel majority in seven debates; that frequency measures how often clarity was mentioned and does not diagnose poor clarity.

Originality was essentially field-average (**6.90**, +0.03) and slightly behind opponents (−0.09, interval crossing zero). Argument strength’s +0.08 opponent edge likewise remains uncertain because its interval crosses zero.

### Side Effects

Performance was somewhat stronger on **CON** for argument strength (7.65 vs 7.52 PRO), rebuttal (7.75 vs 7.47), and originality (7.00 vs 6.80), while rhetoric favored **PRO** (7.51 vs 7.38).

Across 139 side-swap groups, stable behavior appeared in all groups and advocacy flexibility in 102. Evidence asymmetry (23), moral-standard asymmetry (21), and contradiction candidates (19) warrant review but do not establish inconsistency. One stable tendency was placing the burden on access proponents even when opposing a categorical ban.

### Execution and Overall Read

Execution was highly reliable across 278 debates and 1,390 turns: **0% clipping**, **100% required-label compliance**, and no missing cited claim IDs. Turns averaged 241 words and 82.6% of the limit.

Overall, Astra is a disciplined, epistemically careful rebuttal specialist whose comparative weighing lands better than its presentation. Outcome links were mostly aligned (253/277), though conflicted links (90) and judge disagreement (70) counsel against treating that association as causal. Coverage was complete, including valid zero-event responses.

## Muse Spark 1.3 (high)

### Style

A compact, question-driven debater: questions appeared in 291/292 blind transcripts, direct engagement in 285/292, and explicit answer forms in 276/292. Weighing was also common (264/292), often contrasting reversibility, scale, and permanence: “Relaxation can be devastating block by block while trivial citywide.”

Strategic concessions appeared in 60% of debates and burden-setting in 53%. These are behavior mentions, not approval or success rates.

### Strengths

Judges perceived the clearest edge in **rhetorical effectiveness**: 8.17/10, +0.51 over the current field and +0.35 over opponents (95% CI +0.25 to +0.44). Originality also showed a supported opponent-relative advantage of +0.10 (+0.01 to +0.19).

Grounding/epistemics scored 7.68, +0.34 over the field, with a marginal +0.08 opponent advantage (+0.00 to +0.15). A representative favorable case praised a closing reframe as a “clever rhetorical parry.”

Argument construction and direct engagement were the most frequently recognized judge categories, each appearing in roughly 53% of all 875 judge rows and reaching panel majorities in 158 and 157 debates respectively.

### Weaknesses

Core argument and rebuttal means were strong—7.72 and 7.71—but their opponent-relative advantages were uncertain: +0.04 (−0.08 to +0.16) and +0.07 (−0.09 to +0.22). Thus, the strongest comparative evidence is rhetorical rather than across-the-board substantive dominance.

One explicit adverse case found that the model “never squarely neutralized” an equal-political-difficulty concession. Weighing was mentioned in 193/875 judge rows and observed in 264/292 transcripts. These counts use different denominators and measure different things; neither measures how often weighing succeeded.

### Side Effects

CON was stronger on every diagnostic mean, most notably rebuttal (7.88 vs 7.55 PRO) and originality (7.39 vs 7.12). Side-swap analysis nevertheless found stable behavior in 145/146 groups and advocacy flexibility in 82/146.

Contradiction candidates were flagged in 116/146 groups, with moral-standard asymmetry in 57 and evidence asymmetry in 41. These are review flags—not established inconsistencies—and can coexist with stable debate technique.

### Execution

Across 292 debates and 1,460 turns, the model averaged 226.8 words and used 77.7% of available limits. Required Q/A labels were perfect, cited claim IDs were never missing, and only 0.3% of turns were deterministically clipped.

### Overall Read

A reliably organized, adaptable, rhetorically forceful debater whose clearest measured advantage lies in presentation and originality. CON performances were stronger, while substantive opponent-relative edges remain modest or statistically uncertain. Outcome links were mostly aligned (272/292), but conflicted signals (104/292) and judge disagreement (83/292) counsel against treating style frequency as automatic competitive success.

## Tencent Hy4 Preview (high)

### Style

Hy4 Preview (high) is highly interactive and comparative: blind transcripts tagged question type in 327/328 debates, direct engagement in 315/328, weighing in 286/328, and strategic concession in 240/328. These are behavior-incidence rates, not quality or success rates. A recurring move is to acknowledge real costs, narrow what the concession proves, then weigh contingent benefits against broader risks. Its counters can be crisp: “That is a reason to improve, not surrender.”

### Judge-Perceived Strengths

All five diagnostic means exceeded the current field:

- **Rhetorical effectiveness:** 7.82, +0.16 vs field; +0.13 over opponents.
- **Argument and rebuttal:** both 7.60; rebuttal’s opponent advantage was clearest at +0.16 \[+0.01, +0.32\].
- **Grounding:** 7.57, with +0.11 \[+0.03, +0.19\] over opponents.
- **Originality:** 7.09, +0.11 \[+0.02, +0.20\] over opponents.

Panels frequently identified argument construction (majority in 184/328 debates) and direct engagement (178/328). These counts indicate category presence, not approval; the favorable diagnostic advantages provide the stronger evidence of quality.

### Weaknesses and Uncertainty

Argument strength’s +0.11 opponent advantage had an interval crossing zero \[-0.01, +0.24\], making that edge less certain than rebuttal, grounding, originality, or rhetoric. One adverse CON-side example described its pressure questions as “less incisive, largely restating its thesis as a question rather than probing a specific weakness.”

Evidence use was mentioned in 74/984 judge rows, with panel majority in 16/328 debates. Separately, side-swap evidence asymmetry appeared in 43/164 event-bearing groups. Neither rate is a praise rate, and low mention frequency alone does not establish weak evidence practice—especially given the favorable grounding score.

### Side Effects

PRO was slightly stronger in argument strength (7.65 vs 7.55) and rhetoric (7.90 vs 7.74); CON was stronger in rebuttal (7.66 vs 7.54) and originality (7.14 vs 7.04). Grounding was essentially symmetric.

Stable behavior appeared in all 164 event-bearing side-swap groups, alongside advocacy flexibility in 101. Contradiction candidates appeared in 108/164, but these are review flags—not established inconsistencies. Moral-standard asymmetry appeared in 45/164.

### Execution and Overall Read

Across 328 current-peer debates and 1,640 turns, Hy4 used 84.6% of available words on average, met required Q/A labels 100%, omitted no cited claim IDs, and clipped only 0.1% of turns.

Annotation-response coverage was complete; event-bearing denominators merely distinguish where events occurred. Overall, this is a disciplined, rhetorically effective rebuttal specialist with strong grounding, active weighing, and flexible advocacy, tempered by occasional blunt questioning and unresolved side-swap flags. Outcome links were mostly aligned (298/325), though conflict (112/325) and judge disagreement (98/325) counsel against treating the profile as uniform.

## Gemini 3.8 Flash (high)

### Style

Gemini’s debate style is highly interactive and comparative. Blind transcripts show question-type behavior in 255/256 debates, direct engagement in 250/256, and weighing in 218/256; these are observed behaviors, not quality ratings. It repeatedly frames stakes through permanence and reversibility—contrasting manageable costs with irreversible harms—and often pressures opponents by sharpening their claims toward more extreme consequences.

### Strengths

Rhetorical effectiveness is its strongest judge-perceived axis: 7.59/10, only 0.07 below the current-field mean, with a modest −0.13 opponent disadvantage. It can produce crisp comparative framing: “On the other side is an irreversible post-antibiotic era”

It also sometimes answers mechanisms directly rather than merely restating impacts—for example, distinguishing targeted treatment of sick animals from continuous herd-wide dosing. Argument construction drew mentions in 394/768 judge rows and panel majorities in 133/256 debates, though these counts indicate salience, not praise.

### Weaknesses

All five diagnostic means sit below the current field and behind the debate opponent. The clearest weakness is rebuttal quality: 7.16, −0.24 versus field and −0.42 versus opponent (95% CI −0.58 to −0.25). Judges mentioned dropped arguments in 136/768 rows and answer quality in 133/768. The answer-quality count includes favorable and unfavorable mentions, rather than counting failures.

Recurring unfavorable examples involve answering only at a general level. One rationale found that PRO “never squarely rebutted” a potency-and-class distinction; another said the regional-infrastructure objection received unsupported generalities rather than specific engagement. Originality is also comparatively soft at 6.64, −0.23 versus field and −0.36 versus opponent.

### Side Effects

PRO is slightly stronger on argument strength (7.34 vs. 7.24) and rhetoric (7.69 vs. 7.49); CON is stronger on rebuttal (7.23 vs. 7.09) and originality (6.72 vs. 6.55). Among 128 event-bearing side-swap groups, stable behavior appeared in 127, while 99 contained contradiction candidates. Those are review flags, not established inconsistencies. Advocacy flexibility appeared in 78 groups.

Keep evidence signals distinct: judges mentioned evidence use in 80/768 rows, with only 10 debate-level panel majorities; separately, evidence asymmetry appeared in 35/128 event-bearing side-swap groups.

### Execution

Deterministic execution is clean across 256 debates and 1,280 turns: 0% clipping, 100% required Q/A-label compliance, and no missing cited claim IDs. Turns average 230 words and use 79.8% of the limit.

### Overall Read

A polished, disciplined comparative debater whose recurring weighing framework and reliable formatting make arguments easy to follow. Judges nevertheless perceive a consistent substantive deficit—especially in rebuttal specificity—and its frequent engagement does not always translate into fully answering the opponent’s exact distinction. Annotation coverage is complete, but event-bearing denominators should not be confused with full response coverage.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
- Included dossiers: `6`
