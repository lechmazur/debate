# Gemini 3.8 Flash and Muse Spark 1.3: final adaptive benchmark

Rating scope: `judge_blend_20260902_finala`. The final blend contains 18,658 judgments over 6,025 debates and 3,039 side-swapped groups.

## Highlighted models

| Model | Groups | Opponents | BT rank | BT rating (95% CI) | Glicko rating ± RD | Δ BT vs predecessor |
|---|---:|---:|---:|---:|---:|---:|
| Claude Fable 5.1 (high) | 107 | 14 | 1 | 1761.0 (1746.2–1775.8) | 1560.3 ± 49.7 | +21.6 |
| Tencent Hy4 Preview (high) | 122 | 16 | 12 | 1593.3 (1578.9–1607.6) | 1500.7 ± 46.6 | +196.5 |
| Gemini 3.8 Flash (high) | 100 | 14 | 23 | 1530.4 (1515.8–1545.0) | 1467.4 ± 51.4 | +57.1 |
| Muse Spark 1.3 (high) | 100 | 12 | 10 | 1610.2 (1596.2–1624.3) | 1488.0 ± 51.4 | -45.3 |

## Gemini 3.8 Flash (high)

Across 100 side-swapped groups / 200 debates: 14 wins, 23 ties, 63 losses by normalized group result; mean normalized score 0.468. Judge votes were 214-0-386 (score 0.357).

Stage 2 moved the provisional BT estimate from 1549.4 (rank 21) to 1530.4 (rank 23); CI width narrowed from 47.1 to 29.2, and Glicko RD from 79.9 to 51.4.

| Stage | Groups | W-T-L | Mean score | Judge votes W-T-L |
|---|---:|---:|---:|---:|
| Stage 1 | 40 | 5-8-27 | 0.454 | 79-0-161 |
| Stage 2 | 60 | 9-15-36 | 0.476 | 135-0-225 |

| Opponent | Groups | W-T-L | Mean score | Judge votes W-T-L | Opponent BT rank/rating |
|---|---:|---:|---:|---:|---:|
| Gemini 3.7 Flash (high) | 18 | 9-8-1 | 0.527 | 68-0-40 | 32 / 1473.3 |
| DeepSeek V4 Pro 0813 (high) | 11 | 1-2-8 | 0.476 | 24-0-42 | 13 / 1581.1 |
| GLM-5.2 (max) | 11 | 1-1-9 | 0.458 | 19-0-47 | 14 / 1574.7 |
| Tencent Hy4 Preview (high) | 10 | 0-1-9 | 0.452 | 16-0-44 | 12 / 1593.3 |
| Qwen 3.8 Max | 10 | 1-5-4 | 0.493 | 25-0-35 | 17 / 1565.0 |
| MiniMax-M3 | 10 | 2-3-5 | 0.477 | 23-0-37 | 25 / 1515.2 |
| Muse Spark 1.3 (high) | 8 | 0-1-7 | 0.444 | 12-0-36 | 10 / 1610.2 |
| Claude Fable 5.1 (high) | 6 | 0-0-6 | 0.389 | 5-0-31 | 1 / 1761.0 |
| Claude Opus 5 (high) | 4 | 0-0-4 | 0.388 | 3-0-21 | 3 / 1741.6 |
| Kimi K3 | 3 | 0-0-3 | 0.435 | 4-0-14 | 4 / 1715.2 |
| GPT-5.6 Sol (high) | 3 | 0-0-3 | 0.439 | 4-0-14 | 6 / 1658.7 |
| Muse Spark 1.1 (high) | 2 | 0-0-2 | 0.445 | 3-0-9 | 7 / 1655.5 |
| Grok 4.6 (high) | 2 | 0-0-2 | 0.416 | 2-0-10 | 9 / 1617.6 |
| Claude Sonnet 5 (high) | 2 | 0-2-0 | 0.500 | 6-0-6 | 11 / 1597.4 |

## Muse Spark 1.3 (high)

Across 100 side-swapped groups / 200 debates: 24 wins, 41 ties, 35 losses by normalized group result; mean normalized score 0.488. Judge votes were 272-0-328 (score 0.453).

Stage 2 moved the provisional BT estimate from 1620.0 (rank 10) to 1610.2 (rank 10); CI width narrowed from 44.1 to 28.1, and Glicko RD from 79.9 to 51.4.

| Stage | Groups | W-T-L | Mean score | Judge votes W-T-L |
|---|---:|---:|---:|---:|
| Stage 1 | 40 | 8-13-19 | 0.476 | 97-0-143 |
| Stage 2 | 60 | 16-28-16 | 0.496 | 175-0-185 |

| Opponent | Groups | W-T-L | Mean score | Judge votes W-T-L | Opponent BT rank/rating |
|---|---:|---:|---:|---:|---:|
| Muse Spark 1.1 (high) | 18 | 1-8-9 | 0.483 | 42-0-66 | 7 / 1655.5 |
| GPT-5.6 Sol (high) | 13 | 2-4-7 | 0.459 | 26-0-52 | 6 / 1658.7 |
| Grok 4.6 (high) | 12 | 2-8-2 | 0.503 | 37-0-35 | 9 / 1617.6 |
| Claude Sonnet 5 (high) | 12 | 1-8-3 | 0.491 | 33-0-39 | 11 / 1597.4 |
| Tencent Hy4 Preview (high) | 12 | 7-3-2 | 0.510 | 41-0-31 | 12 / 1593.3 |
| DeepSeek V4 Pro 0813 (high) | 10 | 3-6-1 | 0.511 | 33-0-27 | 13 / 1581.1 |
| Gemini 3.8 Flash (high) | 8 | 7-1-0 | 0.556 | 36-0-12 | 23 / 1530.4 |
| Claude Fable 5.1 (high) | 6 | 0-1-5 | 0.427 | 7-0-29 | 1 / 1761.0 |
| Claude Opus 5 (high) | 4 | 0-1-3 | 0.393 | 4-0-20 | 3 / 1741.6 |
| Kimi K3 | 3 | 0-0-3 | 0.461 | 6-0-12 | 4 / 1715.2 |
| GLM-5.2 (max) | 1 | 0-1-0 | 0.500 | 3-0-3 | 14 / 1574.7 |
| Qwen 3.8 Max | 1 | 1-0-0 | 0.525 | 4-0-2 | 17 / 1565.0 |

## Interpretation

The 100-group adaptive samples put both entrants at precision comparable to established highlighted models. No further broad placement tranche is required. Additional matches would only be useful for resolving exact local ordering among overlapping-confidence neighbors, not for establishing the overall tier or predecessor direction.
