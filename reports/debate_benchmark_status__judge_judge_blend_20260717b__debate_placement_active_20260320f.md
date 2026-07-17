# Debate Benchmark Status

- template_id: `judge_judge_blend_20260717b__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 4570
- completed_debates: 4442
- incomplete_debates: 128
- terminal_error_debates: 91
- content_block_debates: 35
- judgment_rows: 13537
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 2049
- rating_eligible_pair_groups: 2004
- rated_models: 41
- mean_availability_score: 95.9
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.451
- mean absolute presented-side margin bias by judge: 0.158

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-fable-5-high | 1 | 280 | 14 | 12 | 0 | 135 | 28 | 144 | 91.8 | 1757.2 | 1639.5 | 44.3 |
| kimi-k3 | 1 | 189 | 1 | 1 | 0 | 94 | 19 | 95 | 98.9 | 1740.8 | 1625.4 | 52.9 |
| claude-opus-4-7-adaptive | 1 | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1684.7 | 1596.6 | 47.0 |
| muse-spark-1.1-high | 1 | 207 | 3 | 3 | 0 | 103 | 21 | 105 | 98.1 | 1684.2 | 1587.1 | 50.6 |
| gpt-5.6-high | 1 | 208 | 2 | 2 | 0 | 103 | 21 | 105 | 98.1 | 1680.5 | 1583.9 | 50.6 |
| claude-opus-4-8-adaptive | 1 | 311 | 11 | 1 | 0 | 155 | 30 | 137 | 96.3 | 1668.0 | 1584.4 | 41.4 |
| claude-sonnet-5-high | 1 | 232 | 2 | 0 | 0 | 115 | 23 | 114 | 98.3 | 1618.5 | 1545.4 | 48.0 |
| glm-5-2 | 1 | 231 | 2 | 2 | 1 | 114 | 23 | 109 | 97.4 | 1594.9 | 1537.2 | 48.2 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1583.7 | 1544.0 | 45.0 |
| gpt-5.5-high | 1 | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1563.6 | 1511.4 | 45.9 |
| glm-5.1 | 1 | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1554.7 | 1514.0 | 51.6 |
| kimi-k2.6 | 1 | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1547.4 | 1497.3 | 45.0 |
| minimax-m3 | 1 | 212 | 4 | 4 | 0 | 104 | 21 | 101 | 96.3 | 1537.4 | 1499.4 | 50.4 |
| gemini-3.1-pro-preview | 1 | 339 | 13 | 1 | 0 | 168 | 40 | 164 | 95.5 | 1529.1 | 1488.5 | 39.8 |
| mimo-v2.5-pro | 1 | 254 | 3 | 2 | 1 | 125 | 29 | 123 | 96.9 | 1526.4 | 1481.1 | 46.0 |
| grok-4.5-high | 1 | 210 | 0 | 0 | 0 | 105 | 21 | 104 | 100.0 | 1519.4 | 1486.4 | 50.2 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1510.8 | 1489.6 | 55.9 |
| seed-2.0-pro | 1 | 311 | 3 | 3 | 0 | 153 | 36 | 145 | 98.7 | 1488.6 | 1473.6 | 41.7 |
| deepseek-v4-pro | 1 | 236 | 0 | 0 | 0 | 118 | 29 | 113 | 100.0 | 1477.7 | 1450.6 | 47.4 |
| qwen3.7-max | 1 | 321 | 3 | 1 | 0 | 154 | 30 | 148 | 98.1 | 1469.9 | 1457.9 | 41.5 |
| minimax-m2.7 | 1 | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1469.4 | 1470.6 | 54.4 |
| gemini-3.5-flash | 1 | 239 | 1 | 1 | 0 | 119 | 26 | 116 | 99.2 | 1444.2 | 1434.1 | 47.2 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1425.6 | 1445.3 | 53.8 |
| step-3.7-flash-high | 1 | 308 | 2 | 1 | 0 | 148 | 30 | 151 | 98.7 | 1420.5 | 1425.0 | 42.4 |
| ernie-5.1 | 1 | 314 | 0 | 0 | 0 | 152 | 30 | 145 | 100.0 | 1418.9 | 1423.1 | 41.8 |
| hy3-preview-high | 1 | 210 | 2 | 1 | 0 | 104 | 29 | 103 | 98.1 | 1416.8 | 1413.1 | 50.4 |
| grok-4.3 | 1 | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1405.6 | 1417.3 | 54.7 |
| mistral-medium-3.5-high | 1 | 206 | 2 | 2 | 0 | 103 | 29 | 99 | 99.0 | 1381.7 | 1390.3 | 50.6 |
| claude-sonnet-4-6-adaptive | 0 | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1597.2 | 1549.4 | 43.7 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1578.6 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1531.4 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1489.8 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1447.9 | 1455.3 | 72.6 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1440.0 | 1481.2 | 84.0 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1428.3 | 1449.4 | 91.5 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1398.5 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1366.1 | 1430.6 | 90.1 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1306.6 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1283.0 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1255.4 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1070.7 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2739 | 0 | 2739 | 1388 |
| gemini-3.1-pro-preview | 1 | 2186 | 0 | 2186 | 1107 |
| qwen3.7-max | 1 | 481 | 0 | 481 | 246 |
| muse-spark-1.1-high | 1 | 452 | 0 | 452 | 235 |
| gpt-5.6-high | 1 | 426 | 0 | 426 | 215 |
| grok-4.5-high | 1 | 423 | 0 | 423 | 215 |
| claude-sonnet-5-high | 1 | 337 | 0 | 337 | 171 |
| qwen3.6-max-preview | 0 | 2083 | 0 | 2083 | 1059 |
| grok-4.3 | 0 | 1737 | 0 | 1737 | 876 |
| gpt-5.5-high | 0 | 1552 | 0 | 1552 | 789 |
| claude-sonnet-4-6-adaptive | 0 | 1121 | 0 | 1121 | 569 |
