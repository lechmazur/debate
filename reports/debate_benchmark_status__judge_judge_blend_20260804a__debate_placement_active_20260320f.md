# Debate Benchmark Status

- template_id: `judge_judge_blend_20260804a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 4970
- completed_debates: 4836
- incomplete_debates: 134
- terminal_error_debates: 97
- content_block_debates: 41
- judgment_rows: 14719
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 2247
- rating_eligible_pair_groups: 2200
- rated_models: 43
- mean_availability_score: 96.1
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.450
- mean absolute presented-side margin bias by judge: 0.148

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5-high | 1 | 223 | 1 | 1 | 0 | 111 | 20 | 107 | 99.1 | 1758.9 | 1594.6 | 48.8 |
| claude-fable-5-high | 1 | 320 | 18 | 16 | 0 | 155 | 30 | 164 | 91.7 | 1753.3 | 1630.3 | 41.4 |
| kimi-k3 | 1 | 233 | 1 | 1 | 0 | 116 | 21 | 115 | 99.1 | 1730.2 | 1608.3 | 47.8 |
| claude-opus-4-7-adaptive | 1 | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1676.8 | 1596.6 | 47.0 |
| muse-spark-1.1-high | 1 | 251 | 3 | 3 | 0 | 125 | 23 | 124 | 98.4 | 1675.5 | 1572.7 | 46.0 |
| gpt-5.6-high | 1 | 251 | 3 | 3 | 0 | 124 | 23 | 127 | 97.6 | 1669.8 | 1568.5 | 46.2 |
| claude-opus-4-8-adaptive | 1 | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1659.6 | 1575.2 | 40.2 |
| claude-sonnet-5-high | 1 | 264 | 2 | 0 | 0 | 131 | 25 | 128 | 98.5 | 1612.3 | 1536.2 | 45.0 |
| glm-5-2 | 1 | 263 | 2 | 2 | 1 | 130 | 25 | 121 | 97.7 | 1589.7 | 1527.7 | 45.2 |
| qwen3.8-max | 1 | 195 | 5 | 5 | 0 | 97 | 15 | 100 | 97.0 | 1587.5 | 1464.9 | 52.1 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1575.8 | 1544.0 | 45.0 |
| gpt-5.5-high | 1 | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1555.9 | 1511.4 | 45.9 |
| glm-5.1 | 1 | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1547.0 | 1514.0 | 51.6 |
| kimi-k2.6 | 1 | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1539.6 | 1497.3 | 45.0 |
| minimax-m3 | 1 | 228 | 4 | 4 | 0 | 112 | 23 | 108 | 96.6 | 1529.0 | 1492.6 | 48.6 |
| gemini-3.1-pro-preview | 1 | 355 | 13 | 1 | 0 | 176 | 42 | 169 | 95.7 | 1520.5 | 1484.2 | 38.9 |
| mimo-v2.5-pro | 1 | 270 | 3 | 2 | 1 | 133 | 31 | 129 | 97.1 | 1517.7 | 1475.8 | 44.7 |
| grok-4.5-high | 1 | 226 | 0 | 0 | 0 | 113 | 23 | 112 | 100.0 | 1515.6 | 1482.8 | 48.4 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1502.9 | 1489.6 | 55.9 |
| seed-2.0-pro | 1 | 322 | 4 | 4 | 0 | 158 | 38 | 151 | 98.2 | 1480.3 | 1470.0 | 41.0 |
| deepseek-v4-pro | 1 | 244 | 0 | 0 | 0 | 122 | 31 | 116 | 100.0 | 1470.0 | 1448.1 | 46.6 |
| minimax-m2.7 | 1 | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1461.5 | 1470.6 | 54.4 |
| gemini-3.5-flash | 1 | 247 | 1 | 1 | 0 | 123 | 28 | 120 | 99.2 | 1434.9 | 1430.5 | 46.4 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1417.8 | 1445.3 | 53.8 |
| step-3.7-flash-high | 1 | 312 | 2 | 1 | 0 | 150 | 31 | 153 | 98.7 | 1411.9 | 1422.7 | 42.1 |
| ernie-5.1 | 1 | 322 | 0 | 0 | 0 | 156 | 32 | 149 | 100.0 | 1410.6 | 1420.6 | 41.3 |
| hy3-preview-high | 1 | 214 | 2 | 1 | 0 | 106 | 30 | 105 | 98.1 | 1410.2 | 1411.4 | 49.9 |
| grok-4.3 | 1 | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1398.2 | 1417.3 | 54.7 |
| mistral-medium-3.5-high | 1 | 210 | 2 | 2 | 0 | 105 | 30 | 101 | 99.1 | 1373.8 | 1388.0 | 50.2 |
| claude-sonnet-4-6-adaptive | 0 | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1589.2 | 1549.4 | 43.7 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1570.5 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1523.3 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1481.8 | 1488.6 | 59.9 |
| qwen3.7-max | 0 | 325 | 3 | 1 | 0 | 156 | 31 | 149 | 98.2 | 1462.1 | 1456.1 | 41.3 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1439.9 | 1455.3 | 72.6 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1431.9 | 1481.2 | 84.0 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1420.2 | 1449.4 | 91.5 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1390.4 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1358.0 | 1430.6 | 90.1 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1298.6 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1274.8 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1247.4 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1062.7 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2937 | 0 | 2937 | 1488 |
| gemini-3.1-pro-preview | 1 | 2398 | 0 | 2398 | 1214 |
| muse-spark-1.1-high | 1 | 658 | 0 | 658 | 338 |
| grok-4.5-high | 1 | 626 | 0 | 626 | 317 |
| gpt-5.6-high | 1 | 615 | 0 | 615 | 310 |
| qwen3.7-max | 1 | 581 | 0 | 581 | 296 |
| claude-sonnet-5-high | 1 | 411 | 0 | 411 | 208 |
| qwen3.6-max-preview | 0 | 2083 | 0 | 2083 | 1059 |
| grok-4.3 | 0 | 1737 | 0 | 1737 | 876 |
| gpt-5.5-high | 0 | 1552 | 0 | 1552 | 789 |
| claude-sonnet-4-6-adaptive | 0 | 1121 | 0 | 1121 | 569 |
