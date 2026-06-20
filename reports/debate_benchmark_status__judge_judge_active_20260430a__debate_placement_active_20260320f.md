# Debate Benchmark Status

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 3386
- completed_debates: 3274
- incomplete_debates: 112
- terminal_error_debates: 75
- content_block_debates: 13
- judgment_rows: 10130
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 1465
- rating_eligible_pair_groups: 1431
- rated_models: 35
- mean_availability_score: 95.7
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.575
- mean absolute presented-side margin bias by judge: 0.156

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7-adaptive | 1 | 218 | 2 | 0 | 0 | 106 | 29 | 107 | 98.2 | 1703.9 | 1606.4 | 49.9 |
| claude-opus-4-8-adaptive | 1 | 251 | 11 | 0 | 0 | 125 | 24 | 109 | 95.4 | 1686.9 | 1597.9 | 46.0 |
| glm-5-2 | 1 | 159 | 0 | 0 | 1 | 79 | 16 | 80 | 98.8 | 1612.5 | 1565.6 | 57.6 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 133 | 30 | 139 | 97.1 | 1606.9 | 1546.0 | 44.7 |
| gpt-5.5-high | 1 | 202 | 0 | 0 | 0 | 101 | 22 | 91 | 100.0 | 1578.2 | 1518.1 | 51.1 |
| glm-5.1 | 1 | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1573.6 | 1514.0 | 51.6 |
| kimi-k2.6 | 1 | 196 | 2 | 0 | 0 | 97 | 22 | 91 | 98.0 | 1566.7 | 1509.8 | 52.1 |
| gemini-3.1-pro-preview | 1 | 279 | 13 | 1 | 0 | 138 | 34 | 139 | 94.5 | 1548.7 | 1499.3 | 43.9 |
| mimo-v2.5-pro | 1 | 185 | 2 | 0 | 1 | 91 | 22 | 92 | 96.8 | 1548.2 | 1496.1 | 53.8 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1530.0 | 1489.6 | 55.9 |
| deepseek-v4-pro | 1 | 166 | 0 | 0 | 0 | 83 | 22 | 81 | 100.0 | 1507.4 | 1471.3 | 56.3 |
| seed-2.0-pro | 1 | 204 | 0 | 0 | 0 | 100 | 25 | 97 | 100.0 | 1502.6 | 1479.7 | 51.4 |
| minimax-m2.7 | 1 | 183 | 5 | 1 | 2 | 90 | 24 | 94 | 93.8 | 1494.7 | 1473.5 | 54.1 |
| qwen3.7-max | 1 | 261 | 3 | 0 | 0 | 124 | 24 | 122 | 97.7 | 1490.8 | 1472.5 | 46.2 |
| gemini-3.5-flash | 1 | 179 | 1 | 0 | 0 | 89 | 20 | 86 | 98.9 | 1465.2 | 1451.3 | 54.4 |
| hy3-preview-high | 1 | 140 | 2 | 0 | 0 | 69 | 22 | 68 | 97.2 | 1453.4 | 1440.6 | 61.5 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 93 | 30 | 98 | 96.0 | 1448.0 | 1446.2 | 53.2 |
| step-3.7-flash-high | 1 | 248 | 2 | 0 | 0 | 118 | 24 | 124 | 98.4 | 1446.3 | 1442.8 | 47.4 |
| ernie-5.1 | 1 | 254 | 0 | 0 | 0 | 122 | 24 | 120 | 100.0 | 1435.5 | 1434.1 | 46.6 |
| grok-4.3 | 1 | 147 | 1 | 0 | 0 | 73 | 22 | 71 | 98.6 | 1430.2 | 1423.4 | 59.9 |
| mistral-medium-3.5-high | 1 | 138 | 0 | 0 | 0 | 69 | 22 | 67 | 100.0 | 1398.1 | 1404.9 | 61.5 |
| claude-fable-5-high | 0 | 205 | 5 | 0 | 0 | 102 | 21 | 102 | 97.1 | 1767.8 | 1650.6 | 50.9 |
| claude-sonnet-4-6-adaptive | 0 | 278 | 12 | 1 | 2 | 134 | 31 | 143 | 93.2 | 1618.4 | 1551.6 | 44.5 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1599.7 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1551.4 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 4 | 0 | 73 | 30 | 124 | 90.2 | 1510.1 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 51 | 16 | 54 | 96.3 | 1474.5 | 1458.8 | 71.2 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 37 | 12 | 40 | 92.5 | 1465.0 | 1482.4 | 82.9 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 31 | 15 | 52 | 61.5 | 1450.1 | 1450.0 | 90.1 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1420.1 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 33 | 11 | 36 | 91.7 | 1397.1 | 1435.4 | 87.5 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1324.6 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1299.6 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1273.0 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1088.5 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2257 | 0 | 2257 | 1145 |
| qwen3.6-max-preview | 1 | 2028 | 0 | 2028 | 1032 |
| grok-4.3 | 1 | 1682 | 0 | 1682 | 849 |
| gemini-3.1-pro-preview | 1 | 1615 | 0 | 1615 | 818 |
| gpt-5.5-high | 1 | 1498 | 0 | 1498 | 762 |
| claude-sonnet-4-6-adaptive | 1 | 1050 | 0 | 1050 | 534 |
