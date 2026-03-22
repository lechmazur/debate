# Debate Benchmark Status

- template_id: `judge_judge_active_20260321b__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 1246
- completed_debates: 1162
- incomplete_debates: 84
- terminal_error_debates: 84
- content_block_debates: 14
- judgment_rows: 3424
- judgment_parse_warning_rows: 0
- rated_pair_groups: 590
- rated_models: 21
- mean_availability_score: 91.2
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.563
- mean absolute presented-side margin bias by judge: 0.122

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6-adaptive | 1 | 162 | 12 | 1 | 0 | 83 | 17 | 87 | 90.8 | 1617.5 | 1532.4 | 57.6 |
| gpt-5.4-high | 1 | 163 | 5 | 0 | 0 | 82 | 14 | 84 | 95.2 | 1610.5 | 1542.2 | 58.0 |
| claude-opus-4-6-adaptive | 1 | 152 | 8 | 0 | 0 | 76 | 14 | 80 | 95.0 | 1605.6 | 1543.8 | 59.5 |
| claude-sonnet-4-6-0K | 1 | 167 | 9 | 1 | 0 | 84 | 17 | 88 | 94.3 | 1600.4 | 1532.1 | 56.3 |
| gemini-3.1-pro-preview | 1 | 131 | 13 | 1 | 0 | 67 | 17 | 72 | 88.9 | 1599.0 | 1522.6 | 63.8 |
| glm-5 | 1 | 113 | 53 | 1 | 0 | 55 | 20 | 82 | 61.4 | 1594.6 | 1574.6 | 81.9 |
| claude-opus-4-6-0K | 1 | 164 | 4 | 1 | 0 | 83 | 15 | 84 | 96.4 | 1589.9 | 1527.8 | 56.9 |
| kimi-k2.5 | 1 | 169 | 7 | 4 | 0 | 88 | 16 | 88 | 92.0 | 1561.5 | 1514.9 | 56.9 |
| gpt-5.4-none | 1 | 185 | 7 | 0 | 0 | 93 | 20 | 96 | 95.8 | 1552.6 | 1514.9 | 53.5 |
| seed-2.0-pro | 1 | 120 | 0 | 0 | 0 | 60 | 17 | 60 | 100.0 | 1551.9 | 1512.7 | 65.8 |
| minimax-m2.7 | 1 | 105 | 3 | 1 | 0 | 53 | 16 | 54 | 94.4 | 1520.9 | 1486.8 | 71.9 |
| grok-4.20-beta-0309-reasoning | 1 | 98 | 2 | 1 | 0 | 48 | 15 | 50 | 96.0 | 1511.1 | 1476.2 | 74.8 |
| qwen3.5-397b-a17b | 1 | 90 | 6 | 2 | 0 | 45 | 14 | 48 | 91.7 | 1508.7 | 1483.2 | 78.1 |
| grok-4.20-beta-0309-non-reasoning | 1 | 76 | 4 | 3 | 0 | 39 | 12 | 40 | 92.5 | 1480.4 | 1469.8 | 84.0 |
| mimo-v2-pro | 1 | 72 | 24 | 10 | 0 | 41 | 14 | 48 | 60.4 | 1476.0 | 1458.7 | 94.5 |
| deepseek-v32-exp | 1 | 77 | 3 | 0 | 0 | 40 | 12 | 40 | 92.5 | 1469.2 | 1462.5 | 82.9 |
| gemini-3.1-flash-lite-preview | 1 | 68 | 4 | 1 | 0 | 35 | 11 | 36 | 91.7 | 1456.1 | 1453.4 | 90.1 |
| gpt-oss-120b | 1 | 64 | 0 | 0 | 0 | 32 | 8 | 32 | 100.0 | 1370.5 | 1424.9 | 88.8 |
| ernie-5 | 1 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1360.6 | 1376.1 | 121.7 |
| mistral-large-2512 | 1 | 53 | 3 | 0 | 0 | 28 | 7 | 28 | 89.3 | 1330.1 | 1415.9 | 99.6 |
| llama4-maverick | 1 | 63 | 1 | 1 | 0 | 32 | 8 | 32 | 96.9 | 1132.9 | 1282.2 | 90.1 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| qwen3.5-397b-a17b | 1 | 701 | 0 | 701 | 361 |
| grok-4.20-beta-0309-reasoning | 1 | 654 | 0 | 654 | 338 |
| gemini-3.1-pro-preview | 1 | 622 | 0 | 622 | 319 |
| kimi-k2.5 | 1 | 520 | 0 | 520 | 269 |
| gpt-5.4-high | 1 | 482 | 0 | 482 | 252 |
| claude-sonnet-4-6-adaptive | 1 | 342 | 0 | 342 | 178 |
| minimax-m2.7 | 0 | 103 | 0 | 103 | 53 |
