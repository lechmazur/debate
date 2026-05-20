# Debate Benchmark Status

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 2056
- completed_debates: 1967
- incomplete_debates: 89
- terminal_error_debates: 56
- content_block_debates: 13
- judgment_rows: 4172
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 771
- rating_eligible_pair_groups: 743
- rated_models: 29
- mean_availability_score: 95.1
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.556
- mean absolute presented-side margin bias by judge: 0.187

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7-adaptive | 1 | 169 | 1 | 0 | 0 | 78 | 24 | 83 | 98.8 | 1711.7 | 1609.7 | 58.0 |
| gpt-5.4-high | 1 | 225 | 5 | 0 | 0 | 107 | 25 | 114 | 96.5 | 1625.1 | 1553.8 | 49.7 |
| gpt-5.5-high | 1 | 128 | 0 | 0 | 0 | 64 | 15 | 63 | 100.0 | 1583.6 | 1525.6 | 63.8 |
| glm-5.1 | 1 | 129 | 1 | 0 | 0 | 64 | 15 | 65 | 98.5 | 1573.0 | 1518.3 | 63.8 |
| kimi-k2.6 | 1 | 120 | 2 | 0 | 0 | 59 | 15 | 59 | 96.7 | 1572.2 | 1516.6 | 66.4 |
| mimo-v2.5-pro | 1 | 115 | 1 | 0 | 0 | 57 | 15 | 58 | 98.3 | 1557.1 | 1506.5 | 67.5 |
| gemini-3.1-pro-preview | 1 | 213 | 13 | 1 | 0 | 99 | 28 | 111 | 92.9 | 1552.3 | 1495.9 | 51.6 |
| qwen3.6-max-preview | 1 | 112 | 0 | 0 | 0 | 56 | 15 | 55 | 100.0 | 1538.6 | 1494.9 | 68.1 |
| kimi-k2.5 | 1 | 216 | 8 | 4 | 0 | 73 | 26 | 109 | 92.9 | 1523.2 | 1488.6 | 59.9 |
| seed-2.0-pro | 1 | 136 | 0 | 0 | 0 | 45 | 19 | 68 | 100.0 | 1518.6 | 1491.0 | 75.6 |
| minimax-m2.7 | 1 | 121 | 3 | 1 | 0 | 48 | 18 | 62 | 95.2 | 1517.5 | 1487.3 | 73.3 |
| deepseek-v4-pro | 1 | 92 | 0 | 0 | 0 | 46 | 15 | 46 | 100.0 | 1515.5 | 1481.9 | 74.8 |
| hy3-preview-high | 1 | 64 | 2 | 0 | 0 | 31 | 15 | 33 | 93.9 | 1488.3 | 1473.9 | 90.1 |
| gemini-3.5-flash | 1 | 112 | 0 | 0 | 0 | 56 | 14 | 56 | 100.0 | 1478.8 | 1460.8 | 68.1 |
| qwen3.5-397b-a17b | 1 | 146 | 6 | 2 | 0 | 51 | 25 | 75 | 94.7 | 1457.7 | 1455.4 | 71.2 |
| grok-4.3 | 1 | 73 | 1 | 0 | 0 | 36 | 15 | 37 | 97.3 | 1427.3 | 1429.5 | 84.0 |
| mistral-medium-3.5-high | 1 | 64 | 0 | 0 | 0 | 32 | 15 | 32 | 100.0 | 1409.9 | 1423.4 | 88.8 |
| claude-sonnet-4-6-adaptive | 0 | 178 | 12 | 1 | 0 | 72 | 19 | 94 | 91.6 | 1627.5 | 1535.4 | 60.3 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 71 | 18 | 92 | 94.6 | 1624.5 | 1546.7 | 60.7 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 82 | 21 | 100 | 96.0 | 1568.9 | 1522.4 | 56.6 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 33 | 12 | 40 | 92.5 | 1483.6 | 1484.0 | 87.5 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 48 | 16 | 54 | 96.3 | 1477.5 | 1450.5 | 73.3 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 24 | 15 | 52 | 61.5 | 1458.7 | 1450.4 | 101.5 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 34 | 13 | 44 | 93.2 | 1437.0 | 1442.6 | 86.3 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 29 | 11 | 36 | 91.7 | 1423.9 | 1441.9 | 93.0 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 30 | 8 | 32 | 100.0 | 1350.1 | 1422.2 | 91.5 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 14 | 6 | 16 | 100.0 | 1330.3 | 1367.9 | 129.0 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 20 | 7 | 28 | 89.3 | 1299.6 | 1420.2 | 110.2 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 28 | 8 | 32 | 96.9 | 1098.5 | 1274.2 | 94.5 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 1377 | 0 | 1377 | 709 |
| qwen3.6-max-preview | 1 | 1363 | 0 | 1363 | 698 |
| claude-sonnet-4-6-adaptive | 1 | 375 | 0 | 375 | 189 |
| grok-4.3 | 1 | 373 | 0 | 373 | 187 |
| gemini-3.1-pro-preview | 1 | 352 | 0 | 352 | 178 |
| gpt-5.5-high | 1 | 332 | 0 | 332 | 168 |
