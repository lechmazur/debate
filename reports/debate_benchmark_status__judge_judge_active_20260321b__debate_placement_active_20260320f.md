# Debate Benchmark Status

- template_id: `judge_judge_active_20260321b__debate_placement_active_20260320f`
- keep_topics_current: 683
- debate_artifacts_seen: 1358
- completed_debates: 1273
- incomplete_debates: 85
- terminal_error_debates: 85
- content_block_debates: 14
- judgment_rows: 3817
- judgment_parse_warning_rows: 0
- rated_pair_groups: 653
- rated_models: 22
- mean_availability_score: 91.8
- published rating order follows Bradley-Terry; Glicko-2 and RD remain secondary scheduling diagnostics

## Gaps
- active participants missing completed debates: (none)
- active participants missing ratings: (none)
- active judges with no judgments: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.576
- mean absolute presented-side margin bias by judge: 0.109

## Participant Coverage
| Model | Active | Debates | Errors | Content Blocks | Incomplete | Rated Groups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6-adaptive | 1 | 170 | 12 | 1 | 0 | 87 | 18 | 91 | 91.2 | 1612.4 | 1529.1 | 56.3 |
| gpt-5.4-high | 1 | 171 | 5 | 0 | 0 | 87 | 15 | 88 | 95.5 | 1605.7 | 1540.1 | 55.9 |
| claude-opus-4-6-adaptive | 1 | 160 | 8 | 0 | 0 | 80 | 15 | 84 | 95.2 | 1598.5 | 1538.7 | 57.3 |
| claude-sonnet-4-6-0K | 1 | 175 | 9 | 1 | 0 | 88 | 18 | 92 | 94.6 | 1592.9 | 1527.4 | 55.0 |
| gemini-3.1-pro-preview | 1 | 139 | 13 | 1 | 0 | 71 | 18 | 76 | 89.5 | 1590.4 | 1516.1 | 62.0 |
| claude-opus-4-6-0K | 1 | 164 | 4 | 1 | 0 | 83 | 15 | 84 | 96.4 | 1579.3 | 1527.8 | 56.9 |
| kimi-k2.5 | 1 | 177 | 7 | 4 | 0 | 92 | 17 | 92 | 92.4 | 1547.1 | 1507.8 | 55.6 |
| gpt-5.4-none | 1 | 193 | 7 | 0 | 0 | 97 | 21 | 100 | 96.0 | 1543.7 | 1510.9 | 52.4 |
| seed-2.0-pro | 1 | 128 | 0 | 0 | 0 | 64 | 18 | 64 | 100.0 | 1541.9 | 1504.1 | 63.8 |
| glm-5 | 1 | 121 | 53 | 1 | 0 | 66 | 21 | 86 | 63.2 | 1535.9 | 1526.5 | 68.7 |
| minimax-m2.7 | 1 | 113 | 3 | 1 | 0 | 58 | 17 | 58 | 94.8 | 1519.0 | 1481.6 | 68.7 |
| grok-4.20-beta-0309-reasoning | 1 | 106 | 2 | 1 | 0 | 54 | 16 | 54 | 96.3 | 1511.5 | 1472.5 | 70.5 |
| qwen3.5-397b-a17b | 1 | 98 | 6 | 2 | 0 | 50 | 15 | 52 | 92.3 | 1502.3 | 1473.1 | 73.3 |
| grok-4.20-beta-0309-non-reasoning | 1 | 76 | 4 | 3 | 0 | 39 | 12 | 40 | 92.5 | 1476.2 | 1470.6 | 82.9 |
| mimo-v2-pro | 1 | 79 | 25 | 10 | 0 | 47 | 15 | 52 | 61.5 | 1474.6 | 1451.6 | 88.8 |
| deepseek-v32-exp | 1 | 85 | 3 | 0 | 0 | 44 | 13 | 44 | 93.2 | 1464.6 | 1452.5 | 79.0 |
| gemini-3.1-flash-lite-preview | 1 | 68 | 4 | 1 | 0 | 35 | 11 | 36 | 91.7 | 1459.4 | 1458.4 | 87.5 |
| gpt-oss-120b | 1 | 64 | 0 | 0 | 0 | 32 | 8 | 32 | 100.0 | 1352.9 | 1424.9 | 88.8 |
| ernie-5 | 1 | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1346.0 | 1376.1 | 121.7 |
| mistral-large-2512 | 1 | 53 | 3 | 0 | 0 | 28 | 7 | 28 | 89.3 | 1312.0 | 1415.9 | 99.6 |
| llama4-maverick | 1 | 63 | 1 | 1 | 0 | 32 | 8 | 32 | 96.9 | 1115.1 | 1282.2 | 90.1 |
| claude-opus-4-7-adaptive | 0 | 111 | 1 | 0 | 0 | 56 | 14 | 56 | 98.2 | 1718.8 | 1605.3 | 68.7 |

## Judge Coverage
| Judge | Active | Rows | Parse Warnings | Debates | Side-Swap Groups |
| --- | ---: | ---: | ---: | ---: | ---: |
| qwen3.5-397b-a17b | 1 | 774 | 0 | 774 | 396 |
| grok-4.20-beta-0309-reasoning | 1 | 731 | 0 | 731 | 375 |
| gemini-3.1-pro-preview | 1 | 710 | 0 | 710 | 362 |
| kimi-k2.5 | 1 | 593 | 0 | 593 | 306 |
| gpt-5.4-high | 1 | 550 | 0 | 550 | 284 |
| claude-sonnet-4-6-adaptive | 1 | 347 | 0 | 347 | 180 |
| minimax-m2.7 | 0 | 112 | 0 | 112 | 56 |
