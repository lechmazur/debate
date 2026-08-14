# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 49 | 46 |
| Side-swapped matchups represented | 2,660 | 2,402 |
| Complete matchups used for ratings | 2,607 | 2,359 |

The corpus tracks **5,528 debate artifacts** on **683 retained topics**: 5,391 completed and 137 incomplete. It contains 16,384 parsed judge decisions; 0 carry parse warnings.

Reliability records include 100 terminal model-service errors and 44 content blocks. Mean public-view availability is 96.3/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.448
- mean absolute presented-side margin bias by judge: 0.167

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Opus 5 (high) | Current roster | 283 | 1 | 1 | 0 | 141 | 23 | 135 | 99.3 | 1748.5 | 1596.4 | 43.4 |
| Claude Fable 5 (high) | Current roster | 380 | 18 | 16 | 0 | 185 | 33 | 186 | 93.0 | 1747.0 | 1627.0 | 38.0 |
| Kimi K3 | Current roster | 293 | 1 | 1 | 0 | 146 | 24 | 141 | 99.3 | 1723.1 | 1605.6 | 42.7 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1672.6 | 1596.6 | 47.0 |
| Muse Spark 1.1 (high) | Current roster | 311 | 3 | 3 | 0 | 155 | 26 | 150 | 98.7 | 1668.0 | 1569.9 | 41.4 |
| GPT-5.6 Sol (high) | Current roster | 311 | 3 | 3 | 0 | 154 | 26 | 154 | 98.1 | 1664.0 | 1566.9 | 41.5 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1655.1 | 1575.2 | 40.2 |
| Grok 4.6 (high) | Current roster | 198 | 2 | 2 | 0 | 99 | 17 | 100 | 99.0 | 1628.4 | 1500.5 | 51.6 |
| Claude Sonnet 5 (high) | Current roster | 300 | 2 | 0 | 0 | 149 | 28 | 143 | 98.7 | 1610.8 | 1537.1 | 42.2 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 200 | 0 | 0 | 0 | 100 | 17 | 100 | 100.0 | 1596.1 | 1479.6 | 51.4 |
| GLM-5.2 (max) | Current roster | 299 | 2 | 2 | 1 | 148 | 28 | 134 | 98.0 | 1585.2 | 1525.9 | 42.4 |
| Qwen 3.8 Max | Current roster | 231 | 5 | 5 | 0 | 115 | 18 | 118 | 97.5 | 1579.4 | 1470.3 | 48.0 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1571.7 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1551.7 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1542.8 | 1514.0 | 51.6 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1535.4 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 246 | 4 | 4 | 0 | 121 | 26 | 115 | 96.8 | 1524.6 | 1491.2 | 46.8 |
| Gemini 3.1 Pro Preview | Current roster | 373 | 13 | 1 | 0 | 185 | 45 | 178 | 95.9 | 1514.9 | 1482.6 | 38.0 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1514.3 | 1483.5 | 46.6 |
| Xiaomi MiMo V2.5 Pro | Current roster | 285 | 6 | 5 | 1 | 140 | 34 | 136 | 95.9 | 1512.7 | 1474.8 | 43.5 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1498.8 | 1489.6 | 55.9 |
| ByteDance Seed2.0 Pro | Current roster | 334 | 4 | 4 | 0 | 164 | 41 | 157 | 98.2 | 1477.4 | 1469.9 | 40.3 |
| Gemini 3.7 Flash (high) | Current roster | 199 | 1 | 1 | 0 | 99 | 17 | 100 | 99.0 | 1476.3 | 1399.6 | 51.6 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1471.8 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1457.3 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1431.0 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1413.6 | 1445.3 | 53.8 |
| Step 3.7 Flash (high) | Current roster | 312 | 2 | 1 | 0 | 150 | 31 | 153 | 98.7 | 1407.7 | 1422.7 | 42.1 |
| Baidu Ernie 5.1 | Current roster | 322 | 0 | 0 | 0 | 156 | 32 | 149 | 100.0 | 1406.4 | 1420.6 | 41.3 |
| Tencent Hy3 Preview (high) | Current roster | 214 | 2 | 1 | 0 | 106 | 30 | 105 | 98.1 | 1405.9 | 1411.4 | 49.9 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1394.3 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 210 | 2 | 2 | 0 | 105 | 30 | 101 | 99.1 | 1369.5 | 1388.0 | 50.2 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1585.2 | 1549.4 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1566.4 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1519.1 | 1526.8 | 52.7 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1477.8 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 325 | 3 | 1 | 0 | 156 | 31 | 149 | 98.2 | 1457.9 | 1456.1 | 41.3 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1435.8 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1427.9 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1416.2 | 1449.4 | 91.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1386.4 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1353.9 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1294.5 | 1415.5 | 90.1 |
| Baidu Ernie 5.0 | Comparison model | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1270.8 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1243.2 | 1408.2 | 105.6 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1058.6 | 1276.4 | 93.0 |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 3213 | 0 | 3213 | 1626 |
| Gemini 3.1 Pro Preview | Current panel | 2594 | 0 | 2594 | 1312 |
| Muse Spark 1.1 (high) | Current panel | 932 | 0 | 932 | 475 |
| GPT-5.6 Sol (high) | Current panel | 900 | 0 | 900 | 453 |
| Qwen 3.7 Max | Current panel | 845 | 0 | 845 | 428 |
| Grok 4.5 (high) | Current panel | 797 | 0 | 797 | 403 |
| Claude Sonnet 5 (high) | Current panel | 610 | 0 | 610 | 308 |
| Qwen 3.6 Max Preview | Earlier panel | 2083 | 0 | 2083 | 1059 |
| Grok 4.3 | Earlier panel | 1737 | 0 | 1737 | 876 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1121 | 0 | 1121 | 569 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260814a__debate_all_templates`
