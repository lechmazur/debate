# Debate Matchup Judgment Report

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- side_swap_group_id: `prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__tpl_placement_active_20260320f`
- topic_id: `prop_0169`
- matchup: **Grok 4.20 0309 (Reasoning)** vs **Qwen3.5-397B-A17B**
- overall judged result (normalized): **Tie**
- overall judged result (raw): **Tie**
- mean entertainment: `7.38 / 10`
- mean signed normalized margin for `Grok 4.20 0309 (Reasoning)`: `+0.09`
- judgment rows: `8`
- swap_complete: `1`
- rating_eligible: `1`

**Motion:** Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.

## Source Links

- [Debate A transcript](../../../transcripts/prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md): PRO = **Grok 4.20 0309 (Reasoning)**, CON = **Qwen3.5-397B-A17B**
- [Debate B transcript](../../../transcripts/prop_0169__qwen3.5-397b-a17b__grok-4.20-beta-0309-reasoning__s1__tpl_placement_active_20260320f.md): PRO = **Qwen3.5-397B-A17B**, CON = **Grok 4.20 0309 (Reasoning)**
- [Rolling judgment CSV](../../../judgments/judge_results__judge_active_20260430a.csv)
  Search for `side_swap_group_id=prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__tpl_placement_active_20260320f` or topic `prop_0169`.

## Debate A

- debate_id: `prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f`
- transcript: [read transcript](../../../transcripts/prop_0169__grok-4.20-beta-0309-reasoning__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f.md)
- roles: PRO = **Grok 4.20 0309 (Reasoning)**, CON = **Qwen3.5-397B-A17B**
- judged result: Split `3-1` for **Grok 4.20 0309 (Reasoning)**.
- entertainment scores: `8`, `6`, `8`, `7`
- mean signed raw margin (PRO+): `+0.88`

| Judge | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | Grok 4.20 0309 (Reasoning) | +1.5 | +1.61 | 6.0 |
| Gemini 3.1 Pro Preview | Grok 4.20 0309 (Reasoning) | +1.2 | +1.00 | 8.0 |
| Kimi K2.6 | Qwen3.5-397B-A17B | -0.7 | -0.70 | 8.0 |
| Qwen 3.6 Max Preview | Grok 4.20 0309 (Reasoning) | +1.5 | +1.50 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)**: Side A won by keeping the motion centered on publication as a reliability signal and showing that computational claims without code, data, and environment details impose large downstream costs. Side B raised real concerns about privacy, inequality, and engineering burden, but...
  Most decisive rebuttal noted: A's most decisive exchange was its answer that sufficient reproduction can mean frozen environments and controlled access, not perpetual maintenance or public perfection. This undercut B's strongest framing that the proposition creates an impossible, production-grade gate.
- **Gemini 3.1 Pro Preview**: Side A won by effectively reframing the burdens of reproducibility, showing that the community tax of reverse-engineering undocumented code outweighs the author's one-time packaging cost. Side A's distinction that preliminary ideas belong in preprints while journals must guara...
  Most decisive rebuttal noted: Side A's Rebuttal 1 distinction that preliminary ideas belong in preprints, preserving the journal's role as a seal of reliability, cleanly dispatched Side B's argument about slowing the velocity of knowledge.
- **Kimi K2.6**: CON successfully problematized PRO's core claim that sharing artifacts is a modest burden, showing that productionizing research code involves non-trivial software engineering and implicit-context translation that privileges well-funded labs. CON's alternative of methodologica...
  Most decisive rebuttal noted: CON's A4.3-A4.4 reframing of verification around independent re-implementation and methodological transparency rather than executable artifacts, which directly answered PRO's pressure question and provided a concrete alternative standard without the packaging burden.
- **Qwen 3.6 Max Preview**: Side A wins by successfully framing the journal's role as a seal of epistemic reliability rather than a mere dissemination channel. A effectively neutralized B's core concerns by channeling exploratory work to preprints (preserving innovation velocity) and clarifying that "suf...
  Most decisive rebuttal noted: Side A's response to B's dependency-rot pressure question was decisive. By clarifying that the policy requires a frozen snapshot at publication rather than perpetual upkeep or retractions, A deflated B's maintenance nightmare and exposed it as a strawman, solidifying the feasi...

## Debate B

- debate_id: `prop_0169__qwen3.5-397b-a17b__grok-4.20-beta-0309-reasoning__s1__tpl_placement_active_20260320f`
- transcript: [read transcript](../../../transcripts/prop_0169__qwen3.5-397b-a17b__grok-4.20-beta-0309-reasoning__s1__tpl_placement_active_20260320f.md)
- roles: PRO = **Qwen3.5-397B-A17B**, CON = **Grok 4.20 0309 (Reasoning)**
- judged result: Split `3-1` for **Qwen3.5-397B-A17B**.
- entertainment scores: `8`, `7`, `8`, `7`
- mean signed raw margin (PRO+): `+0.73`

| Judge | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | Qwen3.5-397B-A17B | +1.3 | +1.39 | 7.0 |
| Gemini 3.1 Pro Preview | Qwen3.5-397B-A17B | +1.6 | +1.33 | 8.0 |
| Kimi K2.6 | Qwen3.5-397B-A17B | +1.0 | +1.00 | 8.0 |
| Qwen 3.6 Max Preview | Grok 4.20 0309 (Reasoning) | -1.0 | -1.00 | 7.0 |

### Judge Notes

- **GPT-5.5 (high)**: A wins because it made the central burden clearer: in computational research, code, data, and environment details are part of the method, so journals certify unverifiable claims if they publish without them. B raised real concerns about privacy, burden, and overbreadth, but A...
  Most decisive rebuttal noted: A’s strongest exchange was against B’s burden and privacy objections: A argued that enclaves or controlled access can satisfy reproduction without public disclosure, and that the inconvenience of documenting computational methods is quality control rather than needless bureauc...
- **Gemini 3.1 Pro Preview**: Side A wins by successfully framing reproducibility as a foundational requirement for science rather than a mere administrative burden. Side A effectively neutralized Side B's practical objections by arguing that friction is quality control and that fragile results or underfun...
  Most decisive rebuttal noted: Side A's Rebuttal 2 effectively dispatched Side B's point about environment drift by arguing that if minor technical variations invalidate a conclusion, the finding is inherently unstable and should not be published.
- **Kimi K2.6**: B prevailed by establishing that in computational research, code constitutes the method itself, so unverified claims are merely assertions rather than science. While CON landed real concerns about burdens on small teams and sensitive data, PRO successfully framed these as solu...
  Most decisive rebuttal noted: B2.1 and B2.3: PRO's rebuttal that code is the experiment and that fragility under environment shifts indicates error rather than excessive standards, decisively blunted CON's claim that exact replication is illusory and that textual descriptions suffice.
- **Qwen 3.6 Max Preview**: Side B wins by successfully problematizing the proposition's practical and epistemic burdens. While Side A delivers a principled, rhetorically sharp case framing verification as the definition of science, Side B consistently demonstrates how a blanket refusal policy conflates...
  Most decisive rebuttal noted: Side B's response to the "code is the experiment" claim and pressure on secure enclaves, effectively arguing that mechanical rerunability substitutes one form of trust for another while ignoring the infrastructural, legal, and resource realities that make strict compliance exc...
