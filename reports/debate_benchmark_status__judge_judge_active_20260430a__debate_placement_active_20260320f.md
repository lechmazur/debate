# Debate Benchmark Status

- template_id: `judge_judge_active_20260430a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 3226
- completed_debates: 3115
- incomplete_debates: 111
- terminal_error_debates: 75
- content_block_debates: 13
- judgment_rows: 9653
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 1385
- rating_eligible_pair_groups: 1352
- rated_models: 34
- mean_availability_score: 95.6
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.576
- mean absolute presented-side margin bias by judge: 0.161

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-fable-5-high | 1 | 205 | 5 | 0 | 0 | 102 | 21 | 102 | 97.1 | 1770.9 | 1650.6 | 50.9 |
| claude-opus-4-7-adaptive | 1 | 218 | 2 | 0 | 0 | 106 | 29 | 107 | 98.2 | 1706.8 | 1606.4 | 49.9 |
| claude-opus-4-8-adaptive | 1 | 241 | 11 | 0 | 0 | 120 | 23 | 105 | 95.2 | 1690.7 | 1600.3 | 47.0 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 133 | 30 | 139 | 97.1 | 1610.0 | 1546.0 | 44.7 |
| gpt-5.5-high | 1 | 192 | 0 | 0 | 0 | 96 | 21 | 87 | 100.0 | 1584.6 | 1522.4 | 52.4 |
| glm-5.1 | 1 | 191 | 3 | 0 | 0 | 94 | 21 | 95 | 96.9 | 1576.4 | 1515.9 | 52.9 |
| kimi-k2.6 | 1 | 186 | 2 | 0 | 0 | 92 | 21 | 86 | 97.9 | 1569.7 | 1511.9 | 53.5 |
| gemini-3.1-pro-preview | 1 | 269 | 13 | 1 | 0 | 133 | 33 | 134 | 94.3 | 1551.8 | 1500.9 | 44.7 |
| mimo-v2.5-pro | 1 | 176 | 2 | 0 | 0 | 87 | 21 | 87 | 97.8 | 1549.3 | 1496.5 | 55.0 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1533.1 | 1489.6 | 55.9 |
| deepseek-v4-pro | 1 | 156 | 0 | 0 | 0 | 78 | 21 | 76 | 100.0 | 1508.6 | 1472.6 | 58.0 |
| seed-2.0-pro | 1 | 194 | 0 | 0 | 0 | 95 | 24 | 93 | 100.0 | 1506.3 | 1482.9 | 52.7 |
| minimax-m2.7 | 1 | 173 | 5 | 1 | 2 | 85 | 23 | 89 | 93.4 | 1495.6 | 1475.2 | 55.6 |
| qwen3.7-max | 1 | 251 | 3 | 0 | 0 | 119 | 23 | 117 | 97.6 | 1491.7 | 1473.2 | 47.2 |
| gemini-3.5-flash | 1 | 169 | 1 | 0 | 0 | 84 | 19 | 81 | 98.8 | 1465.1 | 1451.9 | 55.9 |
| hy3-preview-high | 1 | 130 | 2 | 0 | 0 | 64 | 21 | 64 | 97.0 | 1462.4 | 1447.5 | 63.8 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 93 | 30 | 98 | 96.0 | 1451.1 | 1446.2 | 53.2 |
| step-3.7-flash-high | 1 | 238 | 2 | 0 | 0 | 113 | 23 | 120 | 98.3 | 1449.5 | 1445.0 | 48.4 |
| ernie-5.1 | 1 | 244 | 0 | 0 | 0 | 117 | 23 | 115 | 100.0 | 1439.6 | 1436.8 | 47.6 |
| grok-4.3 | 1 | 137 | 1 | 0 | 0 | 68 | 21 | 66 | 98.6 | 1430.8 | 1424.7 | 62.0 |
| mistral-medium-3.5-high | 1 | 128 | 0 | 0 | 0 | 64 | 21 | 62 | 100.0 | 1403.9 | 1409.8 | 63.8 |
| claude-sonnet-4-6-adaptive | 0 | 278 | 12 | 1 | 2 | 134 | 31 | 143 | 93.2 | 1621.4 | 1551.6 | 44.5 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1602.7 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1554.4 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 4 | 0 | 73 | 30 | 124 | 90.2 | 1513.3 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 51 | 16 | 54 | 96.3 | 1477.3 | 1458.8 | 71.2 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 37 | 12 | 40 | 92.5 | 1467.8 | 1482.4 | 82.9 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 31 | 15 | 52 | 61.5 | 1452.9 | 1450.0 | 90.1 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1423.0 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 33 | 11 | 36 | 91.7 | 1399.9 | 1435.4 | 87.5 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1327.6 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1302.8 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1276.0 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1091.5 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2165 | 0 | 2165 | 1099 |
| qwen3.6-max-preview | 1 | 1943 | 0 | 1943 | 989 |
| grok-4.3 | 1 | 1610 | 0 | 1610 | 813 |
| gemini-3.1-pro-preview | 1 | 1555 | 0 | 1555 | 788 |
| gpt-5.5-high | 1 | 1405 | 0 | 1405 | 715 |
| claude-sonnet-4-6-adaptive | 1 | 975 | 0 | 975 | 496 |
