# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 59 | 56 |
| Side-swapped matchups represented | 3,740 | 3,482 |
| Complete matchups used for ratings | 3,672 | 3,424 |

The corpus tracks **7,702 debate artifacts** on **683 retained topics**: 7,536 completed and 166 incomplete. It contains 22,818 parsed judge decisions; 0 carry parse warnings.

Reliability records include 129 terminal model-service errors and 59 content blocks. Mean public-view availability is 96.6/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.556
- mean absolute presented-side margin bias by judge: 0.183

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 357 | 13 | 8 | 0 | 177 | 26 | 165 | 95.7 | 1737.6 | 1572.6 | 38.8 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1726.5 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 416 | 4 | 1 | 0 | 207 | 33 | 187 | 98.6 | 1724.2 | 1579.3 | 35.9 |
| Claude Opus 5.5 (high) | Current roster | 197 | 3 | 2 | 0 | 97 | 13 | 89 | 97.0 | 1701.0 | 1521.9 | 52.1 |
| Kimi K3 | Current roster | 402 | 4 | 4 | 0 | 200 | 34 | 180 | 98.5 | 1697.7 | 1584.4 | 36.5 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1648.5 | 1596.6 | 47.0 |
| GPT-5.6 Sol (high) | Current roster | 487 | 5 | 3 | 0 | 242 | 36 | 218 | 98.4 | 1645.1 | 1548.8 | 33.2 |
| GLM-5.3 (high) | Current roster | 257 | 3 | 3 | 0 | 128 | 24 | 125 | 98.5 | 1639.0 | 1528.5 | 45.5 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1637.5 | 1554.1 | 37.6 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1630.9 | 1575.2 | 40.2 |
| Grok 4.7 (high) | Current roster | 199 | 1 | 0 | 0 | 99 | 15 | 95 | 99.0 | 1619.8 | 1498.6 | 51.6 |
| Xiaomi MiMo V2.6 Pro (thinking) | Current roster | 191 | 9 | 2 | 0 | 92 | 17 | 90 | 92.0 | 1609.2 | 1511.6 | 53.5 |
| GPT-6 Astra (high) | Current roster | 305 | 1 | 0 | 0 | 152 | 21 | 151 | 99.3 | 1605.6 | 1508.2 | 41.8 |
| Grok 4.6 (high) | Current roster | 395 | 3 | 2 | 0 | 197 | 27 | 179 | 99.0 | 1604.1 | 1493.2 | 36.8 |
| Muse Spark 1.3 (high) | Current roster | 359 | 1 | 0 | 0 | 179 | 25 | 174 | 99.4 | 1592.6 | 1500.4 | 38.6 |
| Claude Sonnet 5 (high) | Current roster | 439 | 5 | 0 | 0 | 217 | 37 | 198 | 97.7 | 1584.9 | 1520.9 | 35.1 |
| DeepSeek V4.1 Flash (high) | Current roster | 200 | 0 | 0 | 0 | 100 | 15 | 97 | 100.0 | 1582.3 | 1487.1 | 51.4 |
| Tencent Hy4 Preview (high) | Current roster | 390 | 2 | 0 | 0 | 194 | 27 | 173 | 99.0 | 1578.9 | 1504.0 | 37.1 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 348 | 0 | 0 | 0 | 174 | 27 | 161 | 100.0 | 1572.1 | 1482.2 | 39.1 |
| GLM-5.2 (max) | Current roster | 367 | 2 | 2 | 1 | 182 | 33 | 163 | 98.4 | 1563.1 | 1520.1 | 38.3 |
| Qwen 3.8 Max | Current roster | 328 | 6 | 6 | 0 | 163 | 26 | 158 | 97.6 | 1552.5 | 1470.4 | 40.4 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1547.6 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1527.5 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1518.7 | 1514.0 | 51.6 |
| Gemini 3.8 Flash (high) | Current roster | 273 | 1 | 1 | 0 | 136 | 26 | 135 | 99.3 | 1514.2 | 1471.3 | 44.2 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1511.0 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 316 | 4 | 4 | 0 | 156 | 32 | 146 | 97.5 | 1502.2 | 1480.5 | 41.3 |
| Gemini 3.1 Pro Preview | Current roster | 433 | 13 | 1 | 0 | 215 | 51 | 198 | 96.4 | 1491.0 | 1474.5 | 35.2 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1490.2 | 1483.5 | 46.6 |
| Xiaomi MiMo V2.5 Pro | Current roster | 380 | 11 | 9 | 1 | 187 | 41 | 181 | 95.4 | 1483.7 | 1459.0 | 37.8 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1474.6 | 1489.6 | 55.9 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1455.2 | 1410.6 | 47.6 |
| ByteDance Seed2.0 Pro | Current roster | 358 | 4 | 4 | 0 | 176 | 47 | 166 | 98.3 | 1453.7 | 1465.3 | 38.9 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1447.7 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1433.5 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1406.9 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1389.7 | 1445.3 | 53.8 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1385.7 | 1409.1 | 46.6 |
| Baidu Ernie 5.1 | Current roster | 346 | 0 | 0 | 0 | 168 | 38 | 159 | 100.0 | 1383.3 | 1416.7 | 39.8 |
| Step 3.7 Flash (high) | Current roster | 334 | 4 | 3 | 0 | 160 | 37 | 160 | 97.6 | 1381.8 | 1417.2 | 40.8 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1370.3 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 234 | 2 | 2 | 0 | 117 | 36 | 110 | 99.2 | 1343.9 | 1381.7 | 47.6 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1561.0 | 1549.4 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1542.4 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1495.1 | 1526.8 | 52.7 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1453.8 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 325 | 3 | 1 | 0 | 156 | 31 | 149 | 98.2 | 1433.8 | 1456.1 | 41.3 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1411.8 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1403.9 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1392.2 | 1449.4 | 91.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1362.4 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1330.0 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1270.4 | 1415.5 | 90.1 |
| Baidu Ernie 5.0 | Comparison model | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1246.8 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1219.2 | 1408.2 | 105.6 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1034.5 | 1276.4 | 93.0 |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 4276 | 0 | 4276 | 2160 |
| Gemini 3.1 Pro Preview | Current panel | 3498 | 0 | 3498 | 1768 |
| Qwen 3.7 Max | Current panel | 1939 | 0 | 1939 | 980 |
| Muse Spark 1.1 (high) | Current panel | 1803 | 0 | 1803 | 914 |
| GPT-5.6 Sol (high) | Current panel | 1790 | 0 | 1790 | 902 |
| Grok 4.5 (high) | Current panel | 1728 | 0 | 1728 | 871 |
| Claude Sonnet 5 (high) | Current panel | 1291 | 0 | 1291 | 650 |
| Qwen 3.6 Max Preview | Earlier panel | 2083 | 0 | 2083 | 1059 |
| Grok 4.3 | Earlier panel | 1737 | 0 | 1737 | 876 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1121 | 0 | 1121 | 569 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260923_finala__debate_all_templates`
