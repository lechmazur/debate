# Debate Benchmark Status

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 1866
- completed_debates: 1779
- incomplete_debates: 87
- terminal_error_debates: 59
- content_block_debates: 13
- judgment_rows: 3608
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 727
- rating_eligible_pair_groups: 701
- rated_models: 29
- mean_availability_score: 95.0
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.553
- mean absolute presented-side margin bias by judge: 0.157

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7-adaptive | 1 | 157 | 1 | 0 | 0 | 72 | 23 | 77 | 98.7 | 1710.6 | 1606.1 | 60.3 |
| gpt-5.4-high | 1 | 217 | 5 | 0 | 0 | 103 | 24 | 110 | 96.4 | 1625.4 | 1552.5 | 50.6 |
| gpt-5.5-high | 1 | 116 | 0 | 0 | 0 | 58 | 14 | 58 | 100.0 | 1574.4 | 1517.1 | 66.9 |
| glm-5.1 | 1 | 115 | 1 | 0 | 0 | 57 | 14 | 58 | 98.3 | 1573.4 | 1515.1 | 67.5 |
| kimi-k2.6 | 1 | 107 | 1 | 0 | 0 | 53 | 14 | 53 | 98.1 | 1567.7 | 1510.8 | 69.9 |
| mimo-v2.5-pro | 1 | 104 | 0 | 0 | 0 | 52 | 14 | 52 | 100.0 | 1553.4 | 1501.6 | 70.5 |
| gemini-3.1-pro-preview | 1 | 197 | 13 | 1 | 0 | 91 | 27 | 104 | 92.4 | 1551.2 | 1491.3 | 53.8 |
| qwen3.6-max-preview | 1 | 100 | 0 | 0 | 0 | 50 | 14 | 49 | 100.0 | 1534.5 | 1489.2 | 71.9 |
| kimi-k2.5 | 1 | 195 | 7 | 4 | 0 | 63 | 26 | 101 | 93.1 | 1519.7 | 1482.8 | 64.3 |
| deepseek-v4-pro | 1 | 80 | 0 | 0 | 0 | 40 | 14 | 40 | 100.0 | 1516.7 | 1478.8 | 79.9 |
| hy3-preview-high | 1 | 35 | 1 | 0 | 0 | 17 | 12 | 18 | 94.4 | 1480.8 | 1456.5 | 118.5 |
| qwen3.5-397b-a17b | 1 | 116 | 6 | 2 | 0 | 36 | 24 | 61 | 93.4 | 1466.5 | 1462.9 | 84.0 |
| grok-4.3 | 1 | 55 | 1 | 0 | 0 | 27 | 13 | 28 | 96.4 | 1419.0 | 1417.1 | 96.1 |
| mistral-medium-3.5-high | 1 | 40 | 0 | 0 | 0 | 20 | 13 | 20 | 100.0 | 1411.6 | 1423.8 | 110.2 |
| claude-opus-4-6-adaptive | 0 | 160 | 8 | 0 | 0 | 69 | 15 | 84 | 95.2 | 1632.9 | 1561.0 | 61.5 |
| claude-sonnet-4-6-adaptive | 0 | 170 | 12 | 1 | 0 | 68 | 18 | 91 | 91.2 | 1625.8 | 1531.0 | 62.0 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 71 | 18 | 92 | 94.6 | 1624.6 | 1546.7 | 60.7 |
| claude-opus-4-6-0K | 0 | 164 | 4 | 1 | 0 | 76 | 15 | 84 | 96.4 | 1611.2 | 1549.7 | 58.7 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 82 | 21 | 100 | 96.0 | 1568.7 | 1522.4 | 56.6 |
| minimax-m2.7 | 0 | 113 | 3 | 1 | 0 | 44 | 17 | 58 | 94.8 | 1522.5 | 1486.5 | 76.4 |
| seed-2.0-pro | 0 | 128 | 0 | 0 | 0 | 41 | 18 | 64 | 100.0 | 1519.7 | 1488.4 | 79.0 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 33 | 12 | 40 | 92.5 | 1485.6 | 1484.0 | 87.5 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 24 | 15 | 52 | 61.5 | 1459.3 | 1450.4 | 101.5 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 34 | 13 | 44 | 93.2 | 1438.4 | 1442.6 | 86.3 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 29 | 11 | 36 | 91.7 | 1425.7 | 1441.9 | 93.0 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 30 | 8 | 32 | 100.0 | 1349.6 | 1422.2 | 91.5 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 14 | 6 | 16 | 100.0 | 1330.1 | 1367.9 | 129.0 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 20 | 7 | 28 | 89.3 | 1299.2 | 1420.2 | 110.2 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 28 | 8 | 32 | 96.9 | 1098.2 | 1274.2 | 94.5 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 1273 | 0 | 1273 | 656 |
| qwen3.6-max-preview | 1 | 1262 | 0 | 1262 | 647 |
| gemini-3.1-pro-preview | 1 | 308 | 0 | 308 | 155 |
| claude-sonnet-4-6-adaptive | 1 | 277 | 0 | 277 | 139 |
| grok-4.3 | 1 | 266 | 0 | 266 | 133 |
| gpt-5.5-high | 1 | 222 | 0 | 222 | 112 |
