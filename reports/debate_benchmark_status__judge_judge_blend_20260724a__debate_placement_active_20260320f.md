# Debate Benchmark Status

- template_id: `judge_judge_blend_20260724a__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 4770
- completed_debates: 4641
- incomplete_debates: 129
- terminal_error_debates: 92
- content_block_debates: 36
- judgment_rows: 14134
- judgment_parse_warning_rows: 0
- side_swap_groups_seen: 2149
- rating_eligible_pair_groups: 2103
- rated_models: 42
- mean_availability_score: 96.0
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.451
- mean absolute presented-side margin bias by judge: 0.152

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5-high | 1 | 199 | 1 | 1 | 0 | 99 | 19 | 96 | 99.0 | 1763.4 | 1594.3 | 51.6 |
| claude-fable-5-high | 1 | 300 | 14 | 12 | 0 | 145 | 29 | 153 | 92.4 | 1756.8 | 1632.8 | 42.8 |
| kimi-k3 | 1 | 209 | 1 | 1 | 0 | 104 | 20 | 105 | 99.0 | 1734.3 | 1611.5 | 50.4 |
| muse-spark-1.1-high | 1 | 227 | 3 | 3 | 0 | 113 | 22 | 114 | 98.3 | 1679.6 | 1575.7 | 48.4 |
| claude-opus-4-7-adaptive | 1 | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1678.7 | 1596.6 | 47.0 |
| gpt-5.6-high | 1 | 228 | 2 | 2 | 0 | 113 | 22 | 115 | 98.3 | 1670.9 | 1569.3 | 48.4 |
| claude-opus-4-8-adaptive | 1 | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1661.6 | 1575.2 | 40.2 |
| claude-sonnet-5-high | 1 | 248 | 2 | 0 | 0 | 123 | 24 | 122 | 98.4 | 1610.2 | 1534.8 | 46.4 |
| glm-5-2 | 1 | 247 | 2 | 2 | 1 | 122 | 24 | 116 | 97.6 | 1589.6 | 1528.0 | 46.6 |
| gpt-5.4-high | 1 | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1577.8 | 1544.0 | 45.0 |
| gpt-5.5-high | 1 | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1557.7 | 1511.4 | 45.9 |
| glm-5.1 | 1 | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1549.0 | 1514.0 | 51.6 |
| kimi-k2.6 | 1 | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1541.4 | 1497.3 | 45.0 |
| minimax-m3 | 1 | 220 | 4 | 4 | 0 | 108 | 22 | 104 | 96.4 | 1531.1 | 1493.8 | 49.5 |
| gemini-3.1-pro-preview | 1 | 347 | 13 | 1 | 0 | 172 | 41 | 167 | 95.6 | 1522.5 | 1484.8 | 39.3 |
| mimo-v2.5-pro | 1 | 262 | 3 | 2 | 1 | 129 | 30 | 127 | 97.0 | 1519.8 | 1476.5 | 45.3 |
| grok-4.5-high | 1 | 218 | 0 | 0 | 0 | 109 | 22 | 108 | 100.0 | 1515.1 | 1482.3 | 49.2 |
| qwen3.6-max-preview | 1 | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1505.1 | 1489.6 | 55.9 |
| seed-2.0-pro | 1 | 318 | 4 | 4 | 0 | 156 | 37 | 149 | 98.1 | 1481.8 | 1470.2 | 41.3 |
| deepseek-v4-pro | 1 | 240 | 0 | 0 | 0 | 120 | 30 | 114 | 100.0 | 1472.0 | 1448.6 | 47.0 |
| qwen3.7-max | 1 | 325 | 3 | 1 | 0 | 156 | 31 | 149 | 98.2 | 1464.0 | 1456.1 | 41.3 |
| minimax-m2.7 | 1 | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1463.5 | 1470.6 | 54.4 |
| gemini-3.5-flash | 1 | 243 | 1 | 1 | 0 | 121 | 27 | 118 | 99.2 | 1438.2 | 1431.9 | 46.8 |
| qwen3.5-397b-a17b | 1 | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1419.8 | 1445.3 | 53.8 |
| step-3.7-flash-high | 1 | 312 | 2 | 1 | 0 | 150 | 31 | 153 | 98.7 | 1413.8 | 1422.7 | 42.1 |
| ernie-5.1 | 1 | 318 | 0 | 0 | 0 | 154 | 31 | 147 | 100.0 | 1413.2 | 1421.4 | 41.5 |
| hy3-preview-high | 1 | 214 | 2 | 1 | 0 | 106 | 30 | 105 | 98.1 | 1412.1 | 1411.4 | 49.9 |
| grok-4.3 | 1 | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1399.8 | 1417.3 | 54.7 |
| mistral-medium-3.5-high | 1 | 210 | 2 | 2 | 0 | 105 | 30 | 101 | 99.1 | 1375.7 | 1388.0 | 50.2 |
| claude-sonnet-4-6-adaptive | 0 | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1591.0 | 1549.4 | 43.7 |
| claude-sonnet-4-6-0K | 0 | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1572.4 | 1542.0 | 55.6 |
| gpt-5.4-none | 0 | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1525.2 | 1526.8 | 52.7 |
| kimi-k2.5 | 0 | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1483.8 | 1488.6 | 59.9 |
| grok-4.20-beta-0309-reasoning | 0 | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1441.8 | 1455.3 | 72.6 |
| grok-4.20-beta-0309-non-reasoning | 0 | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1433.8 | 1481.2 | 84.0 |
| mimo-v2-pro | 0 | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1422.1 | 1449.4 | 91.5 |
| deepseek-v32-exp | 0 | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1392.3 | 1441.0 | 79.0 |
| gemini-3.1-flash-lite-preview | 0 | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1359.8 | 1430.6 | 90.1 |
| gpt-oss-120b | 0 | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1300.5 | 1415.5 | 90.1 |
| ernie-5 | 0 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1276.6 | 1359.2 | 121.7 |
| mistral-large-2512 | 0 | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1249.3 | 1408.2 | 105.6 |
| llama4-maverick | 0 | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1064.7 | 1276.4 | 93.0 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| kimi-k2.6 | 1 | 2822 | 0 | 2822 | 1430 |
| gemini-3.1-pro-preview | 1 | 2297 | 0 | 2297 | 1163 |
| qwen3.7-max | 1 | 581 | 0 | 581 | 296 |
| muse-spark-1.1-high | 1 | 558 | 0 | 558 | 288 |
| gpt-5.6-high | 1 | 525 | 0 | 525 | 265 |
| grok-4.5-high | 1 | 521 | 0 | 521 | 264 |
| claude-sonnet-5-high | 1 | 337 | 0 | 337 | 171 |
| qwen3.6-max-preview | 0 | 2083 | 0 | 2083 | 1059 |
| grok-4.3 | 0 | 1737 | 0 | 1737 | 876 |
| gpt-5.5-high | 0 | 1552 | 0 | 1552 | 789 |
| claude-sonnet-4-6-adaptive | 0 | 1121 | 0 | 1121 | 569 |
