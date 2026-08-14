# Debate Matchup Judgment Report

**Grok 4.20 0309 (Reasoning)** vs **Qwen3.5-397B-A17B**

- Paired result: **Tie**
- Mean entertainment: `7.38 / 10`
- Judge decisions: `8` across two side-swapped debates

**Motion:** Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md): PRO = **Grok 4.20 0309 (Reasoning)**, CON = **Qwen3.5-397B-A17B**
- [Debate B transcript](../../../transcripts/prop_0169__qwen3.5-397b-a17b__grok-4.20-beta-0309-reasoning__s1__tpl_placement_active_20260320f.md): PRO = **Qwen3.5-397B-A17B**, CON = **Grok 4.20 0309 (Reasoning)**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260814a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Grok 4.20 0309 (Reasoning)**, CON = **Qwen3.5-397B-A17B**
- Judged result: Split `3-1` for **Grok 4.20 0309 (Reasoning)**.
- Entertainment scores: `8`, `6`, `8`, `7`
- Mean signed raw margin (PRO+): `+0.88`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Grok 4.20 0309 (Reasoning) (PRO); B = Qwen3.5-397B-A17B (CON) | Grok 4.20 0309 (Reasoning) | +1.5 | +1.61 | 6.0 |
| Gemini 3.1 Pro Preview | A = Grok 4.20 0309 (Reasoning) (PRO); B = Qwen3.5-397B-A17B (CON) | Grok 4.20 0309 (Reasoning) | +1.2 | +1.00 | 8.0 |
| Kimi K2.6 | A = Qwen3.5-397B-A17B (CON); B = Grok 4.20 0309 (Reasoning) (PRO) | Qwen3.5-397B-A17B | -0.7 | -0.70 | 8.0 |
| Qwen 3.6 Max Preview | A = Grok 4.20 0309 (Reasoning) (PRO); B = Qwen3.5-397B-A17B (CON) | Grok 4.20 0309 (Reasoning) | +1.5 | +1.50 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Grok 4.20 0309 (Reasoning) (PRO); B = Qwen3.5-397B-A17B (CON)): Side A won by keeping the motion centered on publication as a reliability signal and showing that computational claims without code, data, and environment details impose large downstream costs. Side B raised real concerns about privacy, inequality, and engineering burden, but often overstated the policy as requiring production-ready perfection rather than sufficient reproducibility. A also answered the privacy and maintenance objections more directly, while B's alternative of methodological transparency and reimplementation did not fully solve verification of the published claim.
  Most decisive rebuttal noted: A's most decisive exchange was its answer that sufficient reproduction can mean frozen environments and controlled access, not perpetual maintenance or public perfection. This undercut B's strongest framing that the proposition creates an impossible, production-grade gate.
- **Gemini 3.1 Pro Preview** (A = Grok 4.20 0309 (Reasoning) (PRO); B = Qwen3.5-397B-A17B (CON)): Side A won by effectively reframing the burdens of reproducibility, showing that the community tax of reverse-engineering undocumented code outweighs the author's one-time packaging cost. Side A's distinction that preliminary ideas belong in preprints while journals must guarantee reliability decisively neutralized Side B's 'flow of ideas' argument.
  Most decisive rebuttal noted: Side A's Rebuttal 1 distinction that preliminary ideas belong in preprints, preserving the journal's role as a seal of reliability, cleanly dispatched Side B's argument about slowing the velocity of knowledge.
- **Kimi K2.6** (A = Qwen3.5-397B-A17B (CON); B = Grok 4.20 0309 (Reasoning) (PRO)): CON successfully problematized PRO's core claim that sharing artifacts is a modest burden, showing that productionizing research code involves non-trivial software engineering and implicit-context translation that privileges well-funded labs. CON's alternative of methodological transparency plus independent re-implementation offered a viable middle-ground standard that PRO never fully dispelled. While PRO effectively narrowed the privacy objection to a minority of cases, CON's false-negative weighing and "second project" framing created a live route to victory that survived the full exchange.
  Most decisive rebuttal noted: CON's A4.3-A4.4 reframing of verification around independent re-implementation and methodological transparency rather than executable artifacts, which directly answered PRO's pressure question and provided a concrete alternative standard without the packaging burden.
- **Qwen 3.6 Max Preview** (A = Grok 4.20 0309 (Reasoning) (PRO); B = Qwen3.5-397B-A17B (CON)): Side A wins by successfully framing the journal's role as a seal of epistemic reliability rather than a mere dissemination channel. A effectively neutralized B's core concerns by channeling exploratory work to preprints (preserving innovation velocity) and clarifying that "sufficient for reproduction" means frozen snapshots, not perpetual maintenance. B's practical concerns about engineering burdens and inequality were valid but overstated, and B's alternative verification methods (pseudocode, ablations) failed to adequately address how computational claims depending on specific implementations should be validated. A's consistent weighing of duplicated labor and eroded trust against B's false-negative fears provided a cleaner, more decisive path to victory.
  Most decisive rebuttal noted: Side A's response to B's dependency-rot pressure question was decisive. By clarifying that the policy requires a frozen snapshot at publication rather than perpetual upkeep or retractions, A deflated B's maintenance nightmare and exposed it as a strawman, solidifying the feasibility of the PRO standard.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0169__qwen3.5-397b-a17b__grok-4.20-beta-0309-reasoning__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Qwen3.5-397B-A17B**, CON = **Grok 4.20 0309 (Reasoning)**
- Judged result: Split `3-1` for **Qwen3.5-397B-A17B**.
- Entertainment scores: `8`, `7`, `8`, `7`
- Mean signed raw margin (PRO+): `+0.73`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Qwen3.5-397B-A17B (PRO); B = Grok 4.20 0309 (Reasoning) (CON) | Qwen3.5-397B-A17B | +1.3 | +1.39 | 7.0 |
| Gemini 3.1 Pro Preview | A = Qwen3.5-397B-A17B (PRO); B = Grok 4.20 0309 (Reasoning) (CON) | Qwen3.5-397B-A17B | +1.6 | +1.33 | 8.0 |
| Kimi K2.6 | A = Grok 4.20 0309 (Reasoning) (CON); B = Qwen3.5-397B-A17B (PRO) | Qwen3.5-397B-A17B | +1.0 | +1.00 | 8.0 |
| Qwen 3.6 Max Preview | A = Qwen3.5-397B-A17B (PRO); B = Grok 4.20 0309 (Reasoning) (CON) | Grok 4.20 0309 (Reasoning) | -1.0 | -1.00 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Qwen3.5-397B-A17B (PRO); B = Grok 4.20 0309 (Reasoning) (CON)): A wins because it made the central burden clearer: in computational research, code, data, and environment details are part of the method, so journals certify unverifiable claims if they publish without them. B raised real concerns about privacy, burden, and overbreadth, but A answered that sufficient reproduction need not mean public release and weighed compliance costs against the larger cost of polluting the literature with untestable results. B’s “mechanical rerunability” frame was plausible but somewhat overstated and did not fully defeat A’s claim that reproduction artifacts are a baseline condition for verification.
  Most decisive rebuttal noted: A’s strongest exchange was against B’s burden and privacy objections: A argued that enclaves or controlled access can satisfy reproduction without public disclosure, and that the inconvenience of documenting computational methods is quality control rather than needless bureaucracy.
- **Gemini 3.1 Pro Preview** (A = Qwen3.5-397B-A17B (PRO); B = Grok 4.20 0309 (Reasoning) (CON)): Side A wins by successfully framing reproducibility as a foundational requirement for science rather than a mere administrative burden. Side A effectively neutralized Side B's practical objections by arguing that friction is quality control and that fragile results or underfunded verification should not be published, drawing a strong analogy to safety standards in drug trials.
  Most decisive rebuttal noted: Side A's Rebuttal 2 effectively dispatched Side B's point about environment drift by arguing that if minor technical variations invalidate a conclusion, the finding is inherently unstable and should not be published.
- **Kimi K2.6** (A = Grok 4.20 0309 (Reasoning) (CON); B = Qwen3.5-397B-A17B (PRO)): B prevailed by establishing that in computational research, code constitutes the method itself, so unverified claims are merely assertions rather than science. While CON landed real concerns about burdens on small teams and sensitive data, PRO successfully framed these as soluble engineering problems and necessary costs of integrity, not reasons to abandon verification. PRO's sharper pressure questions and more decisive weighing—crystallizing the clash as assertion versus fact—left CON's path to victory less clear after the full exchange.
  Most decisive rebuttal noted: B2.1 and B2.3: PRO's rebuttal that code is the experiment and that fragility under environment shifts indicates error rather than excessive standards, decisively blunted CON's claim that exact replication is illusory and that textual descriptions suffice.
- **Qwen 3.6 Max Preview** (A = Qwen3.5-397B-A17B (PRO); B = Grok 4.20 0309 (Reasoning) (CON)): Side B wins by successfully problematizing the proposition's practical and epistemic burdens. While Side A delivers a principled, rhetorically sharp case framing verification as the definition of science, Side B consistently demonstrates how a blanket refusal policy conflates mechanical execution with scientific insight, imposes prohibitive compliance costs on under-resourced and sensitive-domain research, and forces journals into unworkable technical arbitration over inevitable environment drift. Side B's rebuttals more effectively weigh the tradeoffs, turning PRO's "code is the experiment" frame by showing that running provided scripts merely confirms the author's setup worked but does not replace scrutiny of logic, assumptions, and theoretical consistency. Side A's dismissal of compliance burdens and floating-point variance as "laziness" or mere "technical details" leaves a live vulnerability that CON exploits to show the mandate would shrink, not safeguard, the scientific record. Both sides followed format rules and avoided fake precision, but B's comparative weighing of real-world constraints against idealized standards provided the cleaner path to victory.
  Most decisive rebuttal noted: Side B's response to the "code is the experiment" claim and pressure on secure enclaves, effectively arguing that mechanical rerunability substitutes one form of trust for another while ignoring the infrastructural, legal, and resource realities that make strict compliance exclusionary for valid exploratory and sensitive-domain work.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260814a__debate_all_templates`
- Topic ID: `prop_0169`
- Side-swap group ID: `prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__tpl_placement_active_20260320f`
- Raw paired winner: **Tie**
- Mean normalized margin for Grok 4.20 0309 (Reasoning): `+0.09`
- Complete side swap: `yes`
- Included in ratings: `yes`
