# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 55 | 52 |
| Side-swapped matchups represented | 3,371 | 3,113 |
| Complete matchups used for ratings | 3,313 | 3,065 |

The corpus tracks **6,962 debate artifacts** on **683 retained topics**: 6,808 completed and 154 incomplete. It contains 20,634 parsed judge decisions; 0 carry parse warnings.

Reliability records include 117 terminal model-service errors and 56 content blocks. Mean public-view availability is 96.6/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.568
- mean absolute presented-side margin bias by judge: 0.178

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 305 | 13 | 8 | 0 | 151 | 22 | 145 | 95.0 | 1746.8 | 1576.7 | 42.0 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1735.6 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 357 | 3 | 1 | 0 | 178 | 29 | 165 | 98.9 | 1732.0 | 1585.5 | 38.7 |
| Kimi K3 | Current roster | 357 | 3 | 3 | 0 | 178 | 30 | 164 | 98.9 | 1705.4 | 1590.6 | 38.7 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1657.8 | 1596.6 | 47.0 |
| GLM-5.3 (high) | Current roster | 197 | 3 | 3 | 0 | 98 | 20 | 100 | 98.0 | 1653.1 | 1541.0 | 51.9 |
| GPT-5.6 Sol (high) | Current roster | 441 | 5 | 3 | 0 | 219 | 32 | 204 | 98.2 | 1652.6 | 1553.2 | 34.9 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1646.4 | 1554.1 | 37.6 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1640.2 | 1575.2 | 40.2 |
| GPT-6 Astra (high) | Current roster | 278 | 0 | 0 | 0 | 139 | 19 | 139 | 100.0 | 1613.5 | 1508.7 | 43.7 |
| Grok 4.6 (high) | Current roster | 310 | 2 | 2 | 0 | 155 | 23 | 146 | 99.4 | 1612.5 | 1495.7 | 41.4 |
| Muse Spark 1.3 (high) | Current roster | 292 | 0 | 0 | 0 | 146 | 21 | 146 | 100.0 | 1600.8 | 1502.1 | 42.7 |
| Claude Sonnet 5 (high) | Current roster | 395 | 3 | 0 | 0 | 196 | 34 | 182 | 98.5 | 1594.8 | 1524.6 | 36.9 |
| Tencent Hy4 Preview (high) | Current roster | 328 | 0 | 0 | 0 | 164 | 23 | 154 | 100.0 | 1590.4 | 1509.7 | 40.3 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 308 | 0 | 0 | 0 | 154 | 23 | 145 | 100.0 | 1579.7 | 1480.9 | 41.5 |
| GLM-5.2 (max) | Current roster | 367 | 2 | 2 | 1 | 182 | 33 | 163 | 98.4 | 1572.6 | 1520.1 | 38.3 |
| Qwen 3.8 Max | Current roster | 300 | 6 | 6 | 0 | 149 | 24 | 148 | 97.4 | 1561.8 | 1469.9 | 42.2 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1557.0 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1536.9 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1528.1 | 1514.0 | 51.6 |
| Gemini 3.8 Flash (high) | Current roster | 257 | 1 | 1 | 0 | 128 | 22 | 128 | 99.2 | 1523.8 | 1473.5 | 45.5 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1520.4 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 316 | 4 | 4 | 0 | 156 | 32 | 146 | 97.5 | 1511.5 | 1480.5 | 41.3 |
| Gemini 3.1 Pro Preview | Current roster | 433 | 13 | 1 | 0 | 215 | 51 | 198 | 96.4 | 1500.3 | 1474.5 | 35.2 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1499.3 | 1483.5 | 46.6 |
| Xiaomi MiMo V2.5 Pro | Current roster | 342 | 9 | 8 | 1 | 168 | 40 | 161 | 95.5 | 1495.0 | 1464.8 | 39.8 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1484.0 | 1489.6 | 55.9 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1464.0 | 1410.6 | 47.6 |
| ByteDance Seed2.0 Pro | Current roster | 358 | 4 | 4 | 0 | 176 | 47 | 166 | 98.3 | 1463.0 | 1465.3 | 38.9 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1456.9 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 183 | 5 | 3 | 2 | 89 | 24 | 94 | 93.8 | 1442.8 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1416.1 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1399.0 | 1445.3 | 53.8 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1395.2 | 1409.1 | 46.6 |
| Baidu Ernie 5.1 | Current roster | 346 | 0 | 0 | 0 | 168 | 38 | 159 | 100.0 | 1392.6 | 1416.7 | 39.8 |
| Step 3.7 Flash (high) | Current roster | 334 | 4 | 3 | 0 | 160 | 37 | 160 | 97.6 | 1391.1 | 1417.2 | 40.8 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1379.7 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 234 | 2 | 2 | 0 | 117 | 36 | 110 | 99.2 | 1353.2 | 1381.7 | 47.6 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1570.5 | 1549.4 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 175 | 9 | 1 | 0 | 85 | 18 | 92 | 94.6 | 1551.7 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 193 | 7 | 0 | 0 | 95 | 21 | 100 | 96.0 | 1504.5 | 1526.8 | 52.7 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1463.1 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 325 | 3 | 1 | 0 | 156 | 31 | 149 | 98.2 | 1443.1 | 1456.1 | 41.3 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 106 | 2 | 1 | 0 | 49 | 16 | 54 | 96.3 | 1421.1 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1413.3 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 79 | 25 | 10 | 0 | 30 | 15 | 52 | 61.5 | 1401.6 | 1449.4 | 91.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1371.8 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1339.3 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1279.8 | 1415.5 | 90.1 |
| Baidu Ernie 5.0 | Comparison model | 32 | 0 | 0 | 0 | 16 | 6 | 16 | 100.0 | 1256.2 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 53 | 3 | 0 | 0 | 22 | 7 | 28 | 89.3 | 1228.6 | 1408.2 | 105.6 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1043.9 | 1276.4 | 93.0 |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 3915 | 0 | 3915 | 1978 |
| Gemini 3.1 Pro Preview | Current panel | 3144 | 0 | 3144 | 1588 |
| Qwen 3.7 Max | Current panel | 1578 | 0 | 1578 | 796 |
| Grok 4.5 (high) | Current panel | 1491 | 0 | 1491 | 751 |
| Muse Spark 1.1 (high) | Current panel | 1489 | 0 | 1489 | 755 |
| GPT-5.6 Sol (high) | Current panel | 1430 | 0 | 1430 | 720 |
| Claude Sonnet 5 (high) | Current panel | 1094 | 0 | 1094 | 550 |
| Qwen 3.6 Max Preview | Earlier panel | 2083 | 0 | 2083 | 1059 |
| Grok 4.3 | Earlier panel | 1737 | 0 | 1737 | 876 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1121 | 0 | 1121 | 569 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
