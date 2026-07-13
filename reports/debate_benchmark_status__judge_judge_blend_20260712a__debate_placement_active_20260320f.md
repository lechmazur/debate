# Debate Benchmark Status

- template_id: `judge_judge_blend_20260712a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 4380
- completed_debates: 4253
- incomplete_debates: 127
- terminal_error_debates: 90
- content_block_debates: 13
- judgment_rows: 13067
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 1960
- rating_eligible_pair_groups: 1915
- rated_models: 40
- mean_availability_score: 95.8
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.452
- mean absolute presented-side margin bias by judge: 0.165

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-fable-5-high | 1 | 270 | 14 | 0 | 0 | 130 | 27 | 139 | 91.5 | 1759.9 | 1643.3 | 45.2 |
| claude-opus-4-7-adaptive | 1 | 246 | 4 | 0 | 0 | 120 | 32 | 122 | 97.6 | 1690.1 | 1596.6 | 47.0 |
| muse-spark-1.1-high | 1 | 197 | 3 | 0 | 0 | 98 | 20 | 100 | 98.0 | 1687.6 | 1592.7 | 51.9 |
| gpt-5.6-high | 1 | 198 | 2 | 0 | 0 | 98 | 20 | 100 | 98.0 | 1684.2 | 1589.6 | 51.9 |
| claude-opus-4-8-adaptive | 1 | 301 | 11 | 0 | 0 | 150 | 29 | 132 | 96.2 | 1672.7 | 1588.9 | 42.1 |
| claude-sonnet-5-high | 1 | 222 | 2 | 0 | 0 | 110 | 22 | 109 | 98.2 | 1622.1 | 1550.4 | 49.0 |
| glm-5-2 | 1 | 221 | 2 | 0 | 1 | 109 | 22 | 105 | 97.3 | 1597.6 | 1541.7 | 49.2 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 133 | 30 | 139 | 97.1 | 1592.5 | 1546.0 | 44.7 |
| gpt-5.5-high | 1 | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1567.4 | 1511.4 | 45.9 |
| glm-5.1 | 1 | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1558.5 | 1514.0 | 51.6 |
| kimi-k2.6 | 1 | 255 | 3 | 0 | 0 | 126 | 28 | 120 | 97.7 | 1553.8 | 1503.6 | 45.9 |
| minimax-m3 | 1 | 203 | 3 | 0 | 0 | 100 | 20 | 97 | 97.1 | 1541.0 | 1503.8 | 51.4 |
| gemini-3.1-pro-preview | 1 | 329 | 13 | 1 | 0 | 163 | 39 | 159 | 95.3 | 1535.8 | 1492.9 | 40.4 |
| mimo-v2.5-pro | 1 | 244 | 3 | 0 | 1 | 120 | 28 | 118 | 96.8 | 1532.0 | 1486.9 | 47.0 |
| grok-4.5-high | 1 | 200 | 0 | 0 | 0 | 100 | 20 | 99 | 100.0 | 1523.9 | 1492.6 | 51.4 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1514.7 | 1489.6 | 55.9 |
| seed-2.0-pro | 1 | 301 | 3 | 0 | 0 | 148 | 35 | 140 | 98.7 | 1494.7 | 1478.1 | 42.4 |
| deepseek-v4-pro | 1 | 226 | 0 | 0 | 0 | 113 | 28 | 108 | 100.0 | 1482.9 | 1456.3 | 48.4 |
| minimax-m2.7 | 1 | 183 | 5 | 1 | 2 | 90 | 24 | 94 | 93.8 | 1480.7 | 1473.5 | 54.1 |
| qwen3.7-max | 1 | 311 | 3 | 0 | 0 | 149 | 29 | 144 | 98.1 | 1475.4 | 1462.8 | 42.2 |
| gemini-3.5-flash | 1 | 229 | 1 | 0 | 0 | 114 | 25 | 111 | 99.1 | 1449.4 | 1439.5 | 48.2 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 93 | 30 | 98 | 96.0 | 1433.5 | 1446.2 | 53.2 |
| step-3.7-flash-high | 1 | 298 | 2 | 0 | 0 | 143 | 29 | 147 | 98.7 | 1424.9 | 1429.2 | 43.1 |
| ernie-5.1 | 1 | 304 | 0 | 0 | 0 | 147 | 29 | 140 | 100.0 | 1422.2 | 1426.3 | 42.5 |
| hy3-preview-high | 1 | 200 | 2 | 0 | 0 | 99 | 28 | 98 | 98.0 | 1421.6 | 1419.0 | 51.6 |
| grok-4.3 | 1 | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1409.7 | 1417.3 | 54.7 |
| mistral-medium-3.5-high | 1 | 196 | 2 | 0 | 0 | 98 | 28 | 95 | 99.0 | 1384.5 | 1394.9 | 51.9 |
| claude-sonnet-4-6-adaptive | 0 | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1603.7 | 1549.4 | 43.7 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1586.2 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1538.0 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 4 | 0 | 73 | 30 | 124 | 90.2 | 1495.5 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 51 | 16 | 54 | 96.3 | 1461.0 | 1458.8 | 71.2 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 37 | 12 | 40 | 92.5 | 1452.0 | 1482.4 | 82.9 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 31 | 15 | 52 | 61.5 | 1437.1 | 1450.0 | 90.1 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1407.1 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 33 | 11 | 36 | 91.7 | 1384.1 | 1435.4 | 87.5 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1310.5 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1287.4 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1259.0 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1074.5 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2760 | 0 | 2760 | 1399 |
| gemini-3.1-pro-preview | 1 | 2106 | 0 | 2106 | 1067 |
| qwen3.7-max | 1 | 385 | 0 | 385 | 198 |
| muse-spark-1.1-high | 1 | 336 | 0 | 336 | 176 |
| gpt-5.6-high | 1 | 332 | 0 | 332 | 168 |
| grok-4.5-high | 1 | 330 | 0 | 330 | 168 |
| claude-sonnet-5-high | 1 | 264 | 0 | 264 | 134 |
| qwen3.6-max-preview | 0 | 2102 | 0 | 2102 | 1069 |
| grok-4.3 | 0 | 1750 | 0 | 1750 | 883 |
| gpt-5.5-high | 0 | 1568 | 0 | 1568 | 797 |
| claude-sonnet-4-6-adaptive | 0 | 1134 | 0 | 1134 | 576 |
