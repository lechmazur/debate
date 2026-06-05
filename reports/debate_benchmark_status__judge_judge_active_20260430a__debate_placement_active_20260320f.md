# Debate Benchmark Status

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 3016
- completed_debates: 2910
- incomplete_debates: 106
- terminal_error_debates: 71
- content_block_debates: 13
- judgment_rows: 9038
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 1284
- rating_eligible_pair_groups: 1252
- rated_models: 33
- mean_availability_score: 95.5
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.574
- mean absolute presented-side margin bias by judge: 0.163

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7-adaptive | 1 | 208 | 2 | 0 | 0 | 101 | 28 | 102 | 98.1 | 1717.1 | 1615.3 | 51.1 |
| claude-opus-4-8-adaptive | 1 | 231 | 11 | 0 | 0 | 115 | 22 | 105 | 95.0 | 1696.6 | 1605.9 | 48.0 |
| gpt-5.4-high | 1 | 265 | 5 | 0 | 0 | 128 | 29 | 134 | 97.0 | 1619.3 | 1552.9 | 45.5 |
| gpt-5.5-high | 1 | 182 | 0 | 0 | 0 | 91 | 20 | 86 | 100.0 | 1590.5 | 1529.0 | 53.8 |
| glm-5.1 | 1 | 181 | 3 | 0 | 0 | 89 | 20 | 91 | 96.7 | 1584.1 | 1523.7 | 54.4 |
| kimi-k2.6 | 1 | 176 | 2 | 0 | 0 | 87 | 20 | 83 | 97.8 | 1579.3 | 1521.2 | 55.0 |
| gemini-3.1-pro-preview | 1 | 259 | 13 | 1 | 0 | 128 | 32 | 129 | 94.1 | 1558.6 | 1505.7 | 45.5 |
| mimo-v2.5-pro | 1 | 166 | 2 | 0 | 0 | 82 | 20 | 83 | 97.6 | 1557.0 | 1504.8 | 56.6 |
| qwen3.6-max-preview | 1 | 158 | 0 | 0 | 0 | 79 | 19 | 76 | 100.0 | 1540.4 | 1498.2 | 57.6 |
| deepseek-v4-pro | 1 | 146 | 0 | 0 | 0 | 73 | 20 | 71 | 100.0 | 1514.6 | 1480.7 | 59.9 |
| seed-2.0-pro | 1 | 184 | 0 | 0 | 0 | 90 | 23 | 89 | 100.0 | 1514.2 | 1491.1 | 54.1 |
| minimax-m2.7 | 1 | 165 | 3 | 1 | 2 | 81 | 22 | 84 | 94.2 | 1502.2 | 1481.5 | 56.9 |
| qwen3.7-max | 1 | 242 | 2 | 0 | 0 | 115 | 22 | 115 | 98.4 | 1499.4 | 1478.5 | 48.0 |
| gemini-3.5-flash | 1 | 159 | 1 | 0 | 0 | 79 | 18 | 76 | 98.8 | 1472.6 | 1460.8 | 57.6 |
| hy3-preview-high | 1 | 120 | 2 | 0 | 0 | 59 | 20 | 60 | 96.7 | 1471.0 | 1459.6 | 66.4 |
| qwen3.5-397b-a17b | 1 | 186 | 6 | 2 | 0 | 88 | 29 | 94 | 95.8 | 1457.5 | 1453.5 | 54.7 |
| step-3.7-flash-high | 1 | 228 | 2 | 0 | 0 | 108 | 22 | 115 | 98.3 | 1457.2 | 1451.8 | 49.5 |
| ernie-5.1 | 1 | 234 | 0 | 0 | 0 | 112 | 22 | 113 | 100.0 | 1447.1 | 1443.1 | 48.6 |
| grok-4.3 | 1 | 127 | 1 | 0 | 0 | 63 | 20 | 62 | 98.4 | 1435.7 | 1433.3 | 64.3 |
| mistral-medium-3.5-high | 1 | 118 | 0 | 0 | 0 | 59 | 20 | 57 | 100.0 | 1408.3 | 1418.7 | 66.4 |
| claude-sonnet-4-6-adaptive | 0 | 278 | 12 | 1 | 2 | 134 | 31 | 143 | 93.2 | 1629.0 | 1551.6 | 44.5 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1610.5 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1562.3 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 4 | 0 | 73 | 30 | 124 | 90.2 | 1520.9 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 51 | 16 | 54 | 96.3 | 1485.2 | 1458.8 | 71.2 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 37 | 12 | 40 | 92.5 | 1475.2 | 1482.4 | 82.9 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 31 | 15 | 52 | 61.5 | 1460.7 | 1450.0 | 90.1 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1430.7 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 33 | 11 | 36 | 91.7 | 1407.3 | 1435.4 | 87.5 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1335.7 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1310.6 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1284.2 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1099.7 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2028 | 0 | 2028 | 1030 |
| qwen3.6-max-preview | 1 | 1825 | 0 | 1825 | 930 |
| grok-4.3 | 1 | 1480 | 0 | 1480 | 748 |
| gemini-3.1-pro-preview | 1 | 1438 | 0 | 1438 | 729 |
| gpt-5.5-high | 1 | 1292 | 0 | 1292 | 658 |
| claude-sonnet-4-6-adaptive | 1 | 975 | 0 | 975 | 496 |
