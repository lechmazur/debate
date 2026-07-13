# Debate Benchmark Status

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 3536
- completed_debates: 3424
- incomplete_debates: 112
- terminal_error_debates: 75
- content_block_debates: 13
- judgment_rows: 10580
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 1540
- rating_eligible_pair_groups: 1506
- rated_models: 36
- mean_availability_score: 95.8
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.576
- mean absolute presented-side margin bias by judge: 0.154

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7-adaptive | 1 | 218 | 2 | 0 | 0 | 106 | 29 | 107 | 98.2 | 1702.2 | 1606.4 | 49.9 |
| claude-opus-4-8-adaptive | 1 | 261 | 11 | 0 | 0 | 130 | 25 | 114 | 95.6 | 1686.8 | 1598.3 | 45.2 |
| glm-5-2 | 1 | 169 | 0 | 0 | 1 | 84 | 17 | 84 | 98.8 | 1609.0 | 1562.6 | 55.9 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 133 | 30 | 139 | 97.1 | 1605.4 | 1546.0 | 44.7 |
| gpt-5.5-high | 1 | 212 | 0 | 0 | 0 | 106 | 23 | 96 | 100.0 | 1576.3 | 1517.8 | 49.9 |
| glm-5.1 | 1 | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1571.5 | 1514.0 | 51.6 |
| kimi-k2.6 | 1 | 206 | 2 | 0 | 0 | 102 | 23 | 96 | 98.1 | 1563.9 | 1508.9 | 50.9 |
| minimax-m3 | 1 | 150 | 0 | 0 | 0 | 75 | 15 | 74 | 100.0 | 1563.4 | 1533.9 | 59.1 |
| gemini-3.1-pro-preview | 1 | 289 | 13 | 1 | 0 | 143 | 35 | 144 | 94.7 | 1547.7 | 1499.4 | 43.1 |
| mimo-v2.5-pro | 1 | 195 | 2 | 0 | 1 | 96 | 23 | 96 | 97.0 | 1546.2 | 1495.8 | 52.4 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1528.0 | 1489.6 | 55.9 |
| deepseek-v4-pro | 1 | 176 | 0 | 0 | 0 | 88 | 23 | 85 | 100.0 | 1503.9 | 1469.9 | 54.7 |
| seed-2.0-pro | 1 | 214 | 0 | 0 | 0 | 105 | 26 | 101 | 100.0 | 1503.8 | 1480.5 | 50.2 |
| minimax-m2.7 | 1 | 183 | 5 | 1 | 2 | 90 | 24 | 94 | 93.8 | 1493.2 | 1473.5 | 54.1 |
| qwen3.7-max | 1 | 271 | 3 | 0 | 0 | 129 | 25 | 127 | 97.8 | 1490.0 | 1472.5 | 45.3 |
| gemini-3.5-flash | 1 | 189 | 1 | 0 | 0 | 94 | 21 | 91 | 98.9 | 1461.4 | 1449.3 | 52.9 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 93 | 30 | 98 | 96.0 | 1446.5 | 1446.2 | 53.2 |
| hy3-preview-high | 1 | 150 | 2 | 0 | 0 | 74 | 23 | 73 | 97.4 | 1446.5 | 1436.6 | 59.5 |
| step-3.7-flash-high | 1 | 258 | 2 | 0 | 0 | 123 | 25 | 129 | 98.5 | 1444.1 | 1441.9 | 46.4 |
| ernie-5.1 | 1 | 264 | 0 | 0 | 0 | 127 | 25 | 124 | 100.0 | 1432.4 | 1432.8 | 45.7 |
| grok-4.3 | 1 | 157 | 1 | 0 | 0 | 78 | 23 | 76 | 98.7 | 1427.2 | 1422.1 | 58.0 |
| mistral-medium-3.5-high | 1 | 148 | 0 | 0 | 0 | 74 | 23 | 71 | 100.0 | 1400.0 | 1406.6 | 59.5 |
| claude-fable-5-high | 0 | 205 | 5 | 0 | 0 | 102 | 21 | 102 | 97.1 | 1765.9 | 1650.6 | 50.9 |
| claude-sonnet-4-6-adaptive | 0 | 278 | 12 | 1 | 2 | 134 | 31 | 143 | 93.2 | 1616.8 | 1551.6 | 44.5 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1598.5 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1550.3 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 4 | 0 | 73 | 30 | 124 | 90.2 | 1508.6 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 51 | 16 | 54 | 96.3 | 1473.3 | 1458.8 | 71.2 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 37 | 12 | 40 | 92.5 | 1464.0 | 1482.4 | 82.9 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 31 | 15 | 52 | 61.5 | 1449.1 | 1450.0 | 90.1 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1419.1 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 33 | 11 | 36 | 91.7 | 1396.1 | 1435.4 | 87.5 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1323.2 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1299.0 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1271.6 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1087.1 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2331 | 0 | 2331 | 1182 |
| qwen3.6-max-preview | 1 | 2102 | 0 | 2102 | 1069 |
| grok-4.3 | 1 | 1750 | 0 | 1750 | 883 |
| gemini-3.1-pro-preview | 1 | 1695 | 0 | 1695 | 858 |
| gpt-5.5-high | 1 | 1568 | 0 | 1568 | 797 |
| claude-sonnet-4-6-adaptive | 1 | 1134 | 0 | 1134 | 576 |
