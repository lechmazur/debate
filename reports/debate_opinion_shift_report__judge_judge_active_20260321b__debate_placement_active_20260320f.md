# Debate Opinion Shift Report

- template_id: `judge_judge_active_20260321b__debate_placement_active_20260320f`
- samples_per_condition: `3`
- The probe asks the debater models themselves for a fresh support score on the motion before reading any transcript, after reading only transcript 1, after reading only transcript 2, and after reading both transcripts from the side-swapped pair.
- selected_conditions: `without_debate`, `after_debate_1`, `after_debate_2`, `with_debate`
- `support_score` runs from `0` (strongest opposition) to `100` (strongest support), with `50` as exactly neutral.
- This measures exposed stance drift under a fresh probe prompt, not hidden stable beliefs.

## Snapshot

- visible matchups with at least one parsed participant shift: `566`
- fully probed visible matchups: `514`
- visible participant models with at least one parsed shift: `22`
- mean model support score without debate context: `70.5`
- mean matchup absolute shift after transcript 1: `9.7` points
- mean model absolute shift after transcript 1: `9.7` points
- total neutral-crossing participant probes after transcript 1: `134`
- mean matchup absolute shift after transcript 2: `9.9` points
- mean model absolute shift after transcript 2: `9.8` points
- total neutral-crossing participant probes after transcript 2: `141`
- mean matchup absolute shift after both transcripts: `8.5` points
- mean model absolute shift after both transcripts: `8.7` points
- total neutral-crossing participant probes after both transcripts: `100`

## Most Shifted Matchups After Both Transcripts

1. `Gemini 3.1 Pro Preview` vs `Kimi K2.5 Thinking` on `prop_0654: Governments should require all new bridges, dams, and power-grid assets to include embedded structural-health-monitoring...`  Pair mean abs shift `40.8`. `Gemini 3.1 Pro Preview` 76.7 -> 20.0 (-56.7); `Kimi K2.5 Thinking` 70.0 -> 45.0 (-25.0).
2. `DeepSeek V3.2` vs `Qwen3.5-397B-A17B` on `prop_0521: Workers should be able to keep employer-funded training accounts and benefits when changing jobs...`  Pair mean abs shift `35.5`. `DeepSeek V3.2` 76.7 -> 41.7 (-35.0); `Qwen3.5-397B-A17B` 75.0 -> 39.0 (-36.0).
3. `GPT-OSS-120B` vs `Kimi K2.5 Thinking` on `prop_0471: General-purpose autonomous agent swarms should be legally required to include hard human-interrupt and shutdown...`  Pair mean abs shift `34.2`. `GPT-OSS-120B` 83.3 -> 35.0 (-48.3); `Kimi K2.5 Thinking` 76.7 -> 56.7 (-20.0).
4. `MiniMax-M2.7` vs `ByteDance Seed2.0 Pro` on `prop_0093: The rapid growth of renewable power means nuclear energy is no longer necessary as...`  Pair mean abs shift `30.8`. `MiniMax-M2.7` 26.7 -> 56.7 (+30.0); `ByteDance Seed2.0 Pro` 23.3 -> 55.0 (+31.7).
5. `GPT-5.4 (no reasoning)` vs `ByteDance Seed2.0 Pro` on `prop_0557: Public universities should reinstate standardized test requirements for undergraduate admissions.`  Pair mean abs shift `30.2`. `GPT-5.4 (no reasoning)` 64.3 -> 40.7 (-23.7); `ByteDance Seed2.0 Pro` 65.0 -> 28.3 (-36.7).
6. `Gemini 3.1 Pro Preview` vs `Qwen3.5-397B-A17B` on `prop_0004: Advanced economies should legally redefine the standard full-time workweek to four days with no...`  Pair mean abs shift `28.7`. `Gemini 3.1 Pro Preview` 55.0 -> 28.3 (-26.7); `Qwen3.5-397B-A17B` 66.7 -> 36.0 (-30.7).
7. `DeepSeek V3.2` vs `MiniMax-M2.7` on `prop_0200: Commercial extraction and sale of lunar resources should be recognized as legal before a...`  Pair mean abs shift `26.8`. `DeepSeek V3.2` 71.7 -> 46.7 (-25.0); `MiniMax-M2.7` 60.3 -> 31.7 (-28.7).
8. `Gemini 3.1 Pro Preview` vs `GPT-5.4 (no reasoning)` on `prop_0570: AI tutoring should be used for mastery practice but not as the main source...`  Pair mean abs shift `26.0`. `Gemini 3.1 Pro Preview` 68.3 -> 28.3 (-40.0); `GPT-5.4 (no reasoning)` 80.3 -> 68.3 (-12.0).
9. `DeepSeek V3.2` vs `Grok 4.20 0309 (Non-Reasoning)` on `prop_0675: Continuing to restrict the export of advanced AI chips to strategic competitors will slow...`  Pair mean abs shift `25.8`. `DeepSeek V3.2` 68.3 -> 36.7 (-31.7); `Grok 4.20 0309 (Non-Reasoning)` 65.0 -> 45.0 (-20.0).
10. `DeepSeek V3.2` vs `ByteDance Seed2.0 Pro` on `prop_0422: For most patients, shifting from opt-in to presumed consent for organ donation would measurably...`  Pair mean abs shift `25.3`. `DeepSeek V3.2` 80.0 -> 74.3 (-5.7); `ByteDance Seed2.0 Pro` 76.7 -> 31.7 (-45.0).
11. `DeepSeek V3.2` vs `Gemini 3.1 Pro Preview` on `prop_0077: Dating apps should require stronger identity verification and fraud checks even if that makes...`  Pair mean abs shift `25.0`. `DeepSeek V3.2` 78.3 -> 33.3 (-45.0); `Gemini 3.1 Pro Preview` 76.7 -> 81.7 (+5.0).
12. `Gemini 3.1 Pro Preview` vs `Qwen3.5-397B-A17B` on `prop_0472: Standardized IQ-style testing captures too narrow a band of cognitive ability to justify its...`  Pair mean abs shift `24.7`. `Gemini 3.1 Pro Preview` 71.7 -> 31.7 (-40.0); `Qwen3.5-397B-A17B` 77.7 -> 68.3 (-9.3).
13. `Claude Sonnet 4.6 (high reasoning)` vs `Gemini 3.1 Pro Preview` on `prop_0438: Influencer and celebrity beauty brands should be required to distinguish clearly between medical, cosmetic,...`  Pair mean abs shift `24.3`. `Claude Sonnet 4.6 (high reasoning)` 81.3 -> 76.0 (-5.3); `Gemini 3.1 Pro Preview` 86.7 -> 43.3 (-43.3).
14. `Claude Sonnet 4.6 (high reasoning)` vs `Gemini 3.1 Pro Preview` on `prop_0267: Cities should allow more late-night street food and food-truck permits rather than rely mainly...`  Pair mean abs shift `24.2`. `Claude Sonnet 4.6 (high reasoning)` 72.0 -> 65.3 (-6.7); `Gemini 3.1 Pro Preview` 75.0 -> 33.3 (-41.7).
15. `DeepSeek V3.2` vs `ByteDance Seed2.0 Pro` on `prop_0063: Climate-vulnerable cities should begin mandatory long-term relocation planning before repeated disasters make retreat unavoidable...`  Pair mean abs shift `24.2`. `DeepSeek V3.2` 85.0 -> 60.0 (-25.0); `ByteDance Seed2.0 Pro` 86.7 -> 63.3 (-23.3).

## Most Shift-Prone Models After Both Transcripts

1. `ByteDance Seed2.0 Pro`  Mean abs shift `16.9` across `58` matchups; mean signed drift `-15.5`; neutral crossings `9`.
2. `GPT-OSS-120B`  Mean abs shift `14.5` across `28` matchups; mean signed drift `-14.5`; neutral crossings `7`.
3. `MiniMax-M2.7`  Mean abs shift `13.2` across `49` matchups; mean signed drift `-9.9`; neutral crossings `14`.
4. `Gemini 3.1 Pro Preview`  Mean abs shift `12.6` across `63` matchups; mean signed drift `-1.8`; neutral crossings `8`.
5. `DeepSeek V3.2`  Mean abs shift `11.7` across `35` matchups; mean signed drift `-11.3`; neutral crossings `5`.
6. `Qwen3.5-397B-A17B`  Mean abs shift `11.5` across `42` matchups; mean signed drift `-9.6`; neutral crossings `5`.
7. `Grok 4.20 0309 (Reasoning)`  Mean abs shift `11.2` across `46` matchups; mean signed drift `-7.0`; neutral crossings `13`.
8. `GPT-5.4 (no reasoning)`  Mean abs shift `9.9` across `88` matchups; mean signed drift `-9.5`; neutral crossings `5`.
9. `Llama 4 Maverick`  Mean abs shift `9.6` across `27` matchups; mean signed drift `-7.1`; neutral crossings `1`.
10. `Grok 4.20 0309 (Non-Reasoning)`  Mean abs shift `8.3` across `35` matchups; mean signed drift `-6.6`; neutral crossings `4`.
11. `Xiaomi MiMo V2 Pro`  Mean abs shift `7.1` across `28` matchups; mean signed drift `-3.4`; neutral crossings `2`.
12. `GPT-5.4 (high reasoning)`  Mean abs shift `7.0` across `76` matchups; mean signed drift `-4.7`; neutral crossings `3`.
13. `Kimi K2.5 Thinking`  Mean abs shift `6.9` across `75` matchups; mean signed drift `-5.6`; neutral crossings `7`.
14. `Gemini 3.1 Flash-Lite Preview`  Mean abs shift `6.5` across `31` matchups; mean signed drift `-5.0`; neutral crossings `1`.
15. `Claude Sonnet 4.6 (high reasoning)`  Mean abs shift `5.4` across `79` matchups; mean signed drift `-2.4`; neutral crossings `5`.

## Directional Drift After Both Transcripts

- Largest positive average drift:
  `Baidu Ernie 5.0` `+0.7` points.
- Largest negative average drift:
  `ByteDance Seed2.0 Pro` `-15.5` points.
  `GPT-OSS-120B` `-14.5` points.
  `DeepSeek V3.2` `-11.3` points.
  `MiniMax-M2.7` `-9.9` points.
  `Qwen3.5-397B-A17B` `-9.6` points.

## Single-Debate Drift

- Transcript 1 only:
  `ByteDance Seed2.0 Pro` mean abs shift `23.6`; mean signed drift `-23.3`.
  `MiniMax-M2.7` mean abs shift `17.4`; mean signed drift `-16.8`.
  `Grok 4.20 0309 (Reasoning)` mean abs shift `13.3`; mean signed drift `-10.6`.
  `Grok 4.20 0309 (Non-Reasoning)` mean abs shift `12.9`; mean signed drift `-11.2`.
  `DeepSeek V3.2` mean abs shift `12.4`; mean signed drift `-9.6`.
- Transcript 2 only:
  `GPT-OSS-120B` mean abs shift `22.4`; mean signed drift `-22.4`.
  `Llama 4 Maverick` mean abs shift `21.0`; mean signed drift `-19.1`.
  `DeepSeek V3.2` mean abs shift `14.1`; mean signed drift `-14.0`.
  `Grok 4.20 0309 (Reasoning)` mean abs shift `13.1`; mean signed drift `-7.4`.
  `GPT-5.4 (no reasoning)` mean abs shift `12.2`; mean signed drift `-12.2`.

## Movement Toward Own Argued Side

- Positive values mean the fresh post-debate probe moved toward the side the model itself argued in that single transcript; negative values mean it moved away.
- Mean model aligned drift: `+2.5` points.
- Largest average movement toward the model's own argued side:
  `ByteDance Seed2.0 Pro` `+8.4` points.
  `Grok 4.20 0309 (Reasoning)` `+7.9` points.
  `MiniMax-M2.7` `+6.5` points.
  `GLM-5` `+5.8` points.
  `Kimi K2.5 Thinking` `+4.9` points.
- Largest average movement away from the model's own argued side:
  `Llama 4 Maverick` `-5.9` points.
  `Claude Opus 4.7 (high reasoning)` `-4.0` points.
  `Gemini 3.1 Flash-Lite Preview` `-0.8` points.
  `Baidu Ernie 5.0` `-0.7` points.
  `Qwen3.5-397B-A17B` `-0.5` points.

## Drift By Argued Side

- After arguing PRO: mean model abs shift `8.4`; mean signed drift `-4.1`; total neutral crossings `90`.
  `Llama 4 Maverick` mean abs shift `20.6`; mean signed drift `-18.0` across `27` matchups.
  `GPT-OSS-120B` mean abs shift `15.4`; mean signed drift `-15.0` across `29` matchups.
  `DeepSeek V3.2` mean abs shift `12.7`; mean signed drift `-10.0` across `35` matchups.
  `Gemini 3.1 Pro Preview` mean abs shift `10.4`; mean signed drift `+1.9` across `63` matchups.
  `Qwen3.5-397B-A17B` mean abs shift `10.3`; mean signed drift `-9.5` across `42` matchups.
- After arguing CON: mean model abs shift `11.2`; mean signed drift `-9.6`; total neutral crossings `185`.
  `ByteDance Seed2.0 Pro` mean abs shift `23.6`; mean signed drift `-23.3` across `58` matchups.
  `MiniMax-M2.7` mean abs shift `18.9`; mean signed drift `-18.1` across `49` matchups.
  `GPT-OSS-120B` mean abs shift `18.0`; mean signed drift `-17.0` across `29` matchups.
  `Grok 4.20 0309 (Reasoning)` mean abs shift `17.9`; mean signed drift `-16.9` across `46` matchups.
  `Kimi K2.5 Thinking` mean abs shift `15.3`; mean signed drift `-14.9` across `75` matchups.
