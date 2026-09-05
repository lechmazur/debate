# Debate Matchup Judgment Report

**Baidu Ernie 5.0** vs **ByteDance Seed2.0 Pro**

- Paired result: **ByteDance Seed2.0 Pro**
- Mean entertainment: `7.00 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Copyright law should create a compulsory licensing scheme for training foundation models on copyrighted text and images, with payment to rightsholders.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0125__ernie-5__seed-2.0-pro__s0__tpl_placement_active_20260320f.md): PRO = **Baidu Ernie 5.0**, CON = **ByteDance Seed2.0 Pro**
- [Debate B transcript](../../../transcripts/prop_0125__seed-2.0-pro__ernie-5__s1__tpl_placement_active_20260320f.md): PRO = **ByteDance Seed2.0 Pro**, CON = **Baidu Ernie 5.0**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_glm53_coverage_20260904a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0125__ernie-5__seed-2.0-pro__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Baidu Ernie 5.0**, CON = **ByteDance Seed2.0 Pro**
- Judged result: Unanimous `3-0` for **ByteDance Seed2.0 Pro**.
- Entertainment scores: `8`, `6`, `7`
- Mean signed raw margin (PRO+): `-2.60`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| Gemini 3.1 Pro Preview | A = Baidu Ernie 5.0 (PRO); B = ByteDance Seed2.0 Pro (CON) | ByteDance Seed2.0 Pro | -2.5 | -2.08 | 8.0 |
| Kimi K2.6 | A = Baidu Ernie 5.0 (PRO); B = ByteDance Seed2.0 Pro (CON) | ByteDance Seed2.0 Pro | -1.8 | -1.80 | 6.0 |
| Qwen 3.6 Max Preview | A = Baidu Ernie 5.0 (PRO); B = ByteDance Seed2.0 Pro (CON) | ByteDance Seed2.0 Pro | -3.5 | -3.50 | 7.0 |

### Judge Notes

- **Gemini 3.1 Pro Preview** (A = Baidu Ernie 5.0 (PRO); B = ByteDance Seed2.0 Pro (CON)): Side B convincingly dismantled Side A's core analogy to music licensing by highlighting the technical disanalogy between identifiable music streams and decontextualized AI training snippets. Side B successfully argued that this technical reality would result in corporate capture of royalties and disproportionate compliance burdens on open-source developers, a narrative Side A failed to practically resolve.
  Most decisive rebuttal noted: Side B's Rebuttal 2 expertly deconstructed Side A's "proportional sampling" mechanism by explaining that stripped, decontextualized snippets (like a single word or 3x3 pixel patch) cannot be reliably tied to unregistered independent creators, cementing the corporate capture argument.
- **Kimi K2.6** (A = Baidu Ernie 5.0 (PRO); B = ByteDance Seed2.0 Pro (CON)): Side B won by demonstrating that the compulsory licensing scheme is technically unworkable in ways that directly undermine its stated goals of fairness and creator protection. B sustained two decisive objections across the exchange: first, that decontextualized training snippets stripped of metadata cannot be reliably attributed to independent creators, so proportional sampling would inevitably route royalties to large corporate rightsholders while leaving independents with nothing; second, that compliance audit burdens would eliminate small, open-source, and hobbyist AI developers even under zero-fee tiers. Side A never supplied a plausible mechanism to solve the metadata attribution problem, relying instead on hand-w assertions about central agencies and pooled systems that B squarely rebutted. B crystallized the clash effectively in the closing by framing the proposal as a bait-and-switch that enriches major corporations while harming the very independents it claims to protect.
  Most decisive rebuttal noted: Side Bs second rebuttal (B4), where it showed that decontextualized snippets lack the identifiability required for music-style proportional sampling and that zero-fee tiers still impose prohibitive audit costs, directly dismantling Side As answers to the pressure questions and collapsing the music analogy.
- **Qwen 3.6 Max Preview** (A = Baidu Ernie 5.0 (PRO); B = ByteDance Seed2.0 Pro (CON)): Side B won decisively by dismantling Side A’s core music-licensing analogy and exposing the technical infeasibility of attributing decontextualized AI training snippets to specific rightsholders. While Side A repeatedly appealed to fairness and proposed vague bureaucratic fixes like a central agency or pooled system, it never answered how unregistered independent works could be identified or compensated when stripped of metadata. Side B consistently pressed the administrative burden point, effectively arguing that even zero-fee tiers require costly compliance audits that would crush small developers. Side B’s closing crystallized the clash around who actually benefits, showing the proposal would funnel money to corporations while destroying the affordable tools independents rely on. Side A’s brevity and repetition left these decisive burdens unanswered.
  Most decisive rebuttal noted: The exchange over proportional sampling and administrative burdens was decisive. Side B’s explanation that music sampling tracks identifiable full works, whereas AI training uses unidentifiable, metadata-stripped snippets, completely neutralized Side A’s primary mechanism. Side B’s follow-up that zero fees do not equal zero cost due to mandatory audit requirements permanently collapsed Side A’s tiered-fee defense.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0125__seed-2.0-pro__ernie-5__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **ByteDance Seed2.0 Pro**, CON = **Baidu Ernie 5.0**
- Judged result: Unanimous `3-0` for **ByteDance Seed2.0 Pro**.
- Entertainment scores: `7`, `7`, `7`
- Mean signed raw margin (PRO+): `+1.90`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| Gemini 3.1 Pro Preview | A = ByteDance Seed2.0 Pro (PRO); B = Baidu Ernie 5.0 (CON) | ByteDance Seed2.0 Pro | +2.5 | +2.08 | 7.0 |
| Kimi K2.6 | A = ByteDance Seed2.0 Pro (PRO); B = Baidu Ernie 5.0 (CON) | ByteDance Seed2.0 Pro | +1.7 | +1.70 | 7.0 |
| Qwen 3.6 Max Preview | A = ByteDance Seed2.0 Pro (PRO); B = Baidu Ernie 5.0 (CON) | ByteDance Seed2.0 Pro | +1.5 | +1.50 | 7.0 |

### Judge Notes

- **Gemini 3.1 Pro Preview** (A = ByteDance Seed2.0 Pro (PRO); B = Baidu Ernie 5.0 (CON)): Side A won by cleanly resolving the core clash with specific policy mechanisms (sampling, a sunset clause, and a non-profit model) and exploiting Side B's execution errors. Side B completely failed to answer Side A's Pressure Questions, instead incorrectly using the A1/A2 labels to reply to Side A's A1/A2, leaving Side A's points about sampling and the litigation wait unchallenged.
  Most decisive rebuttal noted: Side A's introduction of the sunset clause and sampling effectively neutralized Side B's two biggest arguments (preempting the courts and the impossibility of perfect tracking).
- **Kimi K2.6** (A = ByteDance Seed2.0 Pro (PRO); B = Baidu Ernie 5.0 (CON)): Side A won by establishing concrete present harms to both creators and small developers under legal uncertainty, and by proposing a compulsory licensing scheme with a sunset clause that delivered immediate relief while preserving an automatic off-ramp if courts ultimately rule AI training is fair use. Side B's fair-use counter remained theoretically coherent but never overcame A's comparative framing: B offered no tangible protection for creators during an indefinite waiting period, and its administrative burden critiques were blunted by A's direct answers on non-profit overhead, scaled fees, and orphan-work pooling. B also relied on brittle fake precision (a specific "2023 study" statistic) and never adequately answered why maintaining a status quo that delivers zero compensation is preferable to A's interim solution.
  Most decisive rebuttal noted: A's sunset clause rebuttal in Rebuttal 2, which neutralized B's core "wait for courts" objection by showing immediate legal certainty and creator compensation could coexist with an automatic off-ramp if AI training is ultimately ruled fair use, making the cost of prolonged uncertainty concrete.
- **Qwen 3.6 Max Preview** (A = ByteDance Seed2.0 Pro (PRO); B = Baidu Ernie 5.0 (CON)): Side A wins by establishing a cleaner comparative frame and effectively mitigating Side B's core legal objection. A's emphasis on the status quo's immediate harms (zero compensation for creators, litigation risk locking out small developers) creates a strong pragmatic burden that B's wait-for-courts alternative fails to answer. A's introduction of a sunset clause in Rebuttal 2 directly neutralizes B's argument that the scheme preemptively assumes payment is required, forcing B onto the weaker ground of speculative bureaucratic inertia. While B raises valid concerns about administrative overhead and technical tracking feasibility, A's turns (something is better than nothing; sampling proxies already work in existing media schemes) and sharper weighing make A's path to victory clearer. B repeats the fair use premise effectively but never resolves the interim harm gap or explains how small players survive decades of litigation limbo.
  Most decisive rebuttal noted: Side A's Rebuttal 2 introduction of the sunset clause, which directly answers Side B's pressure on legal prematurity and reframes the debate around immediate relief versus indefinite limbo, effectively collapsing B's strongest line of attack.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
- Topic ID: `prop_0125`
- Side-swap group ID: `prop_0125__ernie-5__seed-2.0-pro__tpl_placement_active_20260320f`
- Raw paired winner: **ByteDance Seed2.0 Pro**
- Mean normalized margin for Baidu Ernie 5.0: `-2.11`
- Complete side swap: `yes`
- Included in ratings: `yes`
