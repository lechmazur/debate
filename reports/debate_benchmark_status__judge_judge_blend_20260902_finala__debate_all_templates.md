# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 53 | 50 |
| Side-swapped matchups represented | 3,039 | 2,781 |
| Complete matchups used for ratings | 2,986 | 2,738 |

The corpus tracks **6,296 debate artifacts** on **683 retained topics**: 6,149 completed and 147 incomplete. It contains 18,658 parsed judge decisions; 0 carry parse warnings.

Reliability records include 110 terminal model-service errors and 50 content blocks. Mean public-view availability is 96.5/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.572
- mean absolute presented-side margin bias by judge: 0.173

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 214 | 10 | 6 | 0 | 107 | 14 | 106 | 95.5 | 1754.3 | 1557.5 | 49.7 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1740.6 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 335 | 3 | 1 | 0 | 167 | 27 | 158 | 98.8 | 1737.1 | 1587.1 | 39.9 |
| Kimi K3 | Current roster | 339 | 3 | 3 | 0 | 169 | 28 | 157 | 98.8 | 1707.5 | 1591.3 | 39.7 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1662.9 | 1596.6 | 47.0 |
| GPT-5.6 Sol (high) | Current roster | 391 | 5 | 3 | 0 | 194 | 30 | 183 | 98.0 | 1657.0 | 1557.1 | 37.1 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1651.5 | 1554.1 | 37.6 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1645.2 | 1575.2 | 40.2 |
| Grok 4.6 (high) | Current roster | 274 | 2 | 2 | 0 | 137 | 21 | 132 | 99.3 | 1616.7 | 1495.8 | 44.0 |
| Muse Spark 1.3 (high) | Current roster | 200 | 0 | 0 | 0 | 100 | 12 | 100 | 100.0 | 1608.5 | 1487.8 | 51.4 |
| Claude Sonnet 5 (high) | Current roster | 356 | 2 | 0 | 0 | 177 | 32 | 165 | 98.9 | 1599.2 | 1529.9 | 38.8 |
| Tencent Hy4 Preview (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 16 | 116 | 100.0 | 1593.6 | 1501.1 | 46.6 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 270 | 0 | 0 | 0 | 135 | 21 | 130 | 100.0 | 1583.3 | 1483.4 | 44.3 |
| GLM-5.2 (max) | Current roster | 347 | 2 | 2 | 1 | 172 | 32 | 154 | 98.3 | 1576.4 | 1523.7 | 39.3 |
| Qwen 3.8 Max | Current roster | 259 | 5 | 5 | 0 | 129 | 22 | 129 | 97.7 | 1564.4 | 1471.5 | 45.3 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1562.2 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1542.1 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1533.4 | 1514.0 | 51.6 |
| Gemini 3.8 Flash (high) | Current roster | 200 | 0 | 0 | 0 | 100 | 14 | 99 | 100.0 | 1528.5 | 1467.1 | 51.4 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1525.5 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 270 | 4 | 4 | 0 | 133 | 29 | 125 | 97.1 | 1517.2 | 1491.5 | 44.7 |
| Gemini 3.1 Pro Preview | Current roster | 375 | 13 | 1 | 0 | 186 | 46 | 179 | 95.9 | 1505.4 | 1482.7 | 37.9 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1504.2 | 1483.5 | 46.6 |
| Xiaomi MiMo V2.5 Pro | Current roster | 285 | 6 | 5 | 1 | 140 | 34 | 136 | 95.9 | 1502.6 | 1474.8 | 43.5 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1489.4 | 1489.6 | 55.9 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1468.4 | 1410.6 | 47.6 |
| ByteDance Seed2.0 Pro | Current roster | 334 | 4 | 4 | 0 | 164 | 41 | 157 | 98.2 | 1467.5 | 1469.9 | 40.3 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1461.8 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1447.8 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1421.0 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1404.2 | 1445.3 | 53.8 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1399.9 | 1409.1 | 46.6 |
| Step 3.7 Flash (high) | Current roster | 312 | 2 | 1 | 0 | 150 | 31 | 153 | 98.7 | 1398.0 | 1422.7 | 42.1 |
| Baidu Ernie 5.1 | Current roster | 322 | 0 | 0 | 0 | 156 | 32 | 149 | 100.0 | 1396.6 | 1420.6 | 41.3 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1384.9 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 210 | 2 | 2 | 0 | 105 | 30 | 101 | 99.1 | 1359.6 | 1388.0 | 50.2 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1575.6 | 1549.4 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1556.8 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1509.6 | 1526.8 | 52.7 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1468.3 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 325 | 3 | 1 | 0 | 156 | 31 | 149 | 98.2 | 1448.2 | 1456.1 | 41.3 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1426.2 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1418.3 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1406.6 | 1449.4 | 91.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1376.8 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1344.4 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1285.0 | 1415.5 | 90.1 |
| Baidu Ernie 5.0 | Comparison model | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1261.2 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1233.7 | 1408.2 | 105.6 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1049.1 | 1276.4 | 93.0 |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 3563 | 0 | 3563 | 1801 |
| Gemini 3.1 Pro Preview | Current panel | 2874 | 0 | 2874 | 1452 |
| GPT-5.6 Sol (high) | Current panel | 1266 | 0 | 1266 | 636 |
| Qwen 3.7 Max | Current panel | 1237 | 0 | 1237 | 624 |
| Muse Spark 1.1 (high) | Current panel | 1216 | 0 | 1216 | 617 |
| Grok 4.5 (high) | Current panel | 1175 | 0 | 1175 | 592 |
| Claude Sonnet 5 (high) | Current panel | 834 | 0 | 834 | 420 |
| Qwen 3.6 Max Preview | Earlier panel | 2083 | 0 | 2083 | 1059 |
| Grok 4.3 | Earlier panel | 1737 | 0 | 1737 | 876 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1121 | 0 | 1121 | 569 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260902_finala__debate_all_templates`
