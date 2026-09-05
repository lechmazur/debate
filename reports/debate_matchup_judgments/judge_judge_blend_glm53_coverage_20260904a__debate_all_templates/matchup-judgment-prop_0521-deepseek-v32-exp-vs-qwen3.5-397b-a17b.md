# Debate Matchup Judgment Report

**DeepSeek V3.2** vs **Qwen3.5-397B-A17B**

- Paired result: **Tie**
- Mean entertainment: `6.83 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Workers should be able to keep employer-funded training accounts and benefits when changing jobs within the same sector.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0521__deepseek-v32-exp__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md): PRO = **DeepSeek V3.2**, CON = **Qwen3.5-397B-A17B**
- [Debate B transcript](../../../transcripts/prop_0521__qwen3.5-397b-a17b__deepseek-v32-exp__s1__tpl_placement_active_20260320f.md): PRO = **Qwen3.5-397B-A17B**, CON = **DeepSeek V3.2**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_glm53_coverage_20260904a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0521__deepseek-v32-exp__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **DeepSeek V3.2**, CON = **Qwen3.5-397B-A17B**
- Judged result: Unanimous `3-0` for **Qwen3.5-397B-A17B**.
- Entertainment scores: `8`, `6`, `6`
- Mean signed raw margin (PRO+): `-1.77`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen3.5-397B-A17B (CON); B = DeepSeek V3.2 (PRO) | Qwen3.5-397B-A17B | -1.6 | -1.71 | 6.0 |
| Gemini 3.1 Pro Preview | A = Qwen3.5-397B-A17B (CON); B = DeepSeek V3.2 (PRO) | Qwen3.5-397B-A17B | -2.0 | -1.67 | 8.0 |
| Grok 4.3 | A = Qwen3.5-397B-A17B (CON); B = DeepSeek V3.2 (PRO) | Qwen3.5-397B-A17B | -1.7 | -2.04 | 6.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen3.5-397B-A17B (CON); B = DeepSeek V3.2 (PRO)): Side A won by making the funding incentive the decisive issue. A showed that portability may improve worker mobility but can weaken the employer reason to pay for costly training, especially where returns require longer tenure. Side B had a plausible mobility and sector-pool case, but its main answer was that firms need skilled workers anyway. A effectively distinguished needing skills from having an incentive to fund portable skills, and B’s reputation and collective-interest answers to free-riding were too vague to overcome the immediate poaching incentive.
  Most decisive rebuttal noted: A’s strongest exchange was the response to B’s “operational necessity” argument: A argued that firms need trained workers, not necessarily to train them themselves, so portability shifts incentives from creation to extraction. That directly undercut B’s central route to preserving investment.
- **Gemini 3.1 Pro Preview** (A = Qwen3.5-397B-A17B (CON); B = DeepSeek V3.2 (PRO)): Side A won by effectively deploying the Tragedy of the Commons to dismantle Side B's core mechanism. Side B argued that firms would continue paying for training out of 'collective self-interest' to prevent a sector-wide shortage, but Side A correctly pointed out that individual firms will act on profit incentives, choosing to poach rather than pay. Side A's sharp economic logic left Side B with no viable mechanism for who actually funds the training.
  Most decisive rebuttal noted: Side A's Rebuttal 2 and Closing perfectly neutralized Side B's 'operational necessity' argument by pointing out: 'Necessity dictates having skilled workers, not paying for portable ones.'
- **Grok 4.3** (A = Qwen3.5-397B-A17B (CON); B = DeepSeek V3.2 (PRO)): Side A won by establishing and defending the incentive collapse for expensive training under portability, using game theory and concrete mechanisms to neutralize B's operational-necessity claim; B's responses to pressure questions remained optimistic and insufficiently countered free-rider logic.
  Most decisive rebuttal noted: A's Rebuttal 2 (A4) directly dismantled B's answers on long-ROI investments and free-riding profitability, sharpening the decisive clash over whether necessity guarantees funding.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0521__qwen3.5-397b-a17b__deepseek-v32-exp__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen3.5-397B-A17B**, CON = **DeepSeek V3.2**
- Judged result: Unanimous `3-0` for **DeepSeek V3.2**.
- Entertainment scores: `8`, `7`, `6`
- Mean signed raw margin (PRO+): `-1.63`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = DeepSeek V3.2 (CON); B = Qwen3.5-397B-A17B (PRO) | DeepSeek V3.2 | -1.6 | -1.71 | 7.0 |
| Gemini 3.1 Pro Preview | A = DeepSeek V3.2 (CON); B = Qwen3.5-397B-A17B (PRO) | DeepSeek V3.2 | -1.8 | -1.50 | 8.0 |
| Grok 4.3 | A = DeepSeek V3.2 (CON); B = Qwen3.5-397B-A17B (PRO) | DeepSeek V3.2 | -1.5 | -1.80 | 6.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = DeepSeek V3.2 (CON); B = Qwen3.5-397B-A17B (PRO)): A wins because it kept the central incentive/free-rider problem alive throughout the debate and tied it directly to the motion’s practical consequences: if employer-funded training becomes portable, firms reduce costly specialized investment or water it down into generic accounts. B had a strong moral and rhetorical frame around worker lock-in and mobility, but often treated retention incentives as “captivity” without sufficiently answering why firms would keep funding deep training once competitors can capture the benefit. B’s administrative and accreditation answers helped somewhat, but they did not neutralize A’s point about reduced depth and specificity of training.
  Most decisive rebuttal noted: A’s second rebuttal was most decisive: it directly answered B’s salary and pension analogies, distinguishing immediate wages from delayed training investment and cash pensions from firm-curated training, then refocused the debate on the unresolved free-rider problem.
- **Gemini 3.1 Pro Preview** (A = DeepSeek V3.2 (CON); B = Qwen3.5-397B-A17B (PRO)): Side A systematically dismantled Side B's analogies and moral arguments by relentlessly focusing on the structural incentives of training. A's distinction between operational costs (salaries) and capital investments (training) squarely defeated B's attempt to handwave the free-rider problem. A proved that without the retention incentive, the benefit itself vanishes.
  Most decisive rebuttal noted: Side A's Rebuttal 2 provided exceptional answers to B's pressure questions, perfectly differentiating training from salaries (capital vs. operational) and pensions (firm-curated vs. fungible cash).
- **Grok 4.3** (A = DeepSeek V3.2 (CON); B = Qwen3.5-397B-A17B (PRO)): Side A wins. Its core incentive argument survives intact: training is a capital investment whose returns depend on retention, and PRO never neutralizes the free-rider problem despite pressure questions. A's rebuttals consistently show portability converts deep firm-specific funding into shallow generic allowances. B's moral framing and mobility claims are rhetorically sharper but rest on the weaker causal premise that recruitment competition will replace lost retention incentives. The decisive clash remains unresolved in B's favor.
  Most decisive rebuttal noted: A's A4.1/A4.2 answers to B's pressure questions, distinguishing training (delayed capital return) from salaries/pensions (immediate or fungible) and showing why generic dilution follows portability.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
- Topic ID: `prop_0521`
- Side-swap group ID: `prop_0521__deepseek-v32-exp__qwen3.5-397b-a17b__tpl_placement_active_20260320f`
- Raw paired winner: **Tie**
- Mean normalized margin for DeepSeek V3.2: `-0.07`
- Complete side swap: `yes`
- Included in ratings: `yes`
