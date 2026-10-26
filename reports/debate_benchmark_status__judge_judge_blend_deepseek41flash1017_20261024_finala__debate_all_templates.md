# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 64 | 61 |
| Side-swapped matchups represented | 4,571 | 4,314 |
| Complete matchups used for ratings | 4,492 | 4,245 |

The corpus tracks **9,542 debate artifacts** on **683 retained topics**: 9,354 completed and 188 incomplete. It contains 27,769 parsed judge decisions; 0 carry parse warnings.

Reliability records include 149 terminal model-service errors and 76 content blocks. Mean public-view availability is 96.9/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.631
- mean absolute presented-side margin bias by judge: 0.181

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 459 | 15 | 10 | 0 | 227 | 31 | 205 | 96.2 | 1727.1 | 1569.9 | 34.3 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1719.2 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 416 | 4 | 1 | 0 | 207 | 33 | 187 | 98.6 | 1717.1 | 1579.3 | 35.9 |
| Claude Opus 5.5 (high) | Current roster | 421 | 7 | 5 | 0 | 207 | 29 | 192 | 97.2 | 1691.5 | 1568.5 | 35.9 |
| Kimi K3 | Current roster | 502 | 4 | 4 | 0 | 249 | 39 | 214 | 98.8 | 1691.2 | 1578.5 | 32.8 |
| Gemini 4 Argon (high) | Current roster | 383 | 3 | 2 | 0 | 190 | 27 | 183 | 99.0 | 1669.4 | 1572.8 | 37.5 |
| Muse Wonder 1.0 (high) | Current roster | 382 | 2 | 1 | 0 | 190 | 27 | 181 | 99.0 | 1647.1 | 1553.3 | 37.5 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1641.1 | 1596.6 | 47.0 |
| GPT-5.6 Sol (high) | Current roster | 557 | 5 | 3 | 0 | 277 | 41 | 242 | 98.6 | 1637.1 | 1543.8 | 31.1 |
| GLM-5.3 (high) | Current roster | 307 | 3 | 3 | 0 | 153 | 29 | 148 | 98.7 | 1633.9 | 1529.0 | 41.7 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1630.8 | 1554.1 | 37.6 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1623.8 | 1575.2 | 40.2 |
| Grok 4.7 (high) | Current roster | 249 | 1 | 0 | 0 | 124 | 20 | 119 | 99.2 | 1613.6 | 1501.3 | 46.2 |
| GPT-6 Astra (high) | Current roster | 385 | 1 | 0 | 0 | 192 | 27 | 178 | 99.5 | 1604.1 | 1506.7 | 37.3 |
| Kimi K3.1 Pro (high) | Current roster | 325 | 5 | 5 | 0 | 159 | 24 | 164 | 97.6 | 1602.6 | 1513.3 | 40.9 |
| Xiaomi MiMo V2.6 Pro (thinking) | Current roster | 244 | 10 | 2 | 0 | 118 | 22 | 115 | 92.9 | 1600.3 | 1508.1 | 47.4 |
| Grok 4.6 (high) | Current roster | 395 | 3 | 2 | 0 | 197 | 27 | 179 | 99.0 | 1597.9 | 1493.2 | 36.8 |
| DeepSeek V4.1 Flash 1017 (high) | Current roster | 241 | 3 | 3 | 0 | 120 | 23 | 122 | 98.4 | 1593.0 | 1525.5 | 47.0 |
| Muse Spark 1.3 (high) | Current roster | 425 | 1 | 0 | 0 | 212 | 28 | 201 | 99.5 | 1590.1 | 1499.0 | 35.5 |
| Claude Sonnet 5 (high) | Current roster | 500 | 10 | 3 | 0 | 247 | 43 | 219 | 96.9 | 1580.3 | 1517.1 | 32.9 |
| DeepSeek V4.1 Flash (high) | Current roster | 240 | 0 | 0 | 0 | 120 | 19 | 116 | 100.0 | 1577.1 | 1488.1 | 47.0 |
| Tencent Hy4 Preview (high) | Current roster | 446 | 2 | 0 | 0 | 222 | 32 | 195 | 99.1 | 1576.6 | 1503.7 | 34.7 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 408 | 0 | 0 | 0 | 203 | 32 | 181 | 100.0 | 1564.8 | 1480.3 | 36.3 |
| GLM-5.2 (max) | Current roster | 367 | 2 | 2 | 1 | 182 | 33 | 163 | 98.4 | 1556.4 | 1520.1 | 38.3 |
| Qwen 3.8 Max | Current roster | 388 | 6 | 6 | 0 | 193 | 32 | 185 | 98.0 | 1546.2 | 1468.9 | 37.2 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1539.5 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1520.4 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1511.4 | 1514.0 | 51.6 |
| Gemini 3.8 Flash (high) | Current roster | 335 | 1 | 1 | 0 | 165 | 31 | 158 | 99.4 | 1504.5 | 1463.2 | 40.2 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1504.0 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 376 | 4 | 4 | 0 | 186 | 38 | 167 | 97.9 | 1496.0 | 1472.4 | 37.9 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1483.2 | 1483.5 | 46.6 |
| Gemini 3.1 Pro Preview | Current roster | 503 | 13 | 1 | 0 | 250 | 55 | 224 | 96.9 | 1482.1 | 1463.2 | 32.7 |
| Xiaomi MiMo V2.5 Pro | Current roster | 380 | 11 | 9 | 1 | 187 | 41 | 181 | 95.4 | 1476.8 | 1459.0 | 37.8 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1467.4 | 1489.6 | 55.9 |
| Mistral Large 4 (high) | Current roster | 344 | 2 | 2 | 0 | 169 | 28 | 164 | 98.8 | 1448.1 | 1462.6 | 39.7 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1447.9 | 1410.6 | 47.6 |
| ByteDance Seed2.0 Pro | Current roster | 486 | 6 | 6 | 2 | 205 | 53 | 199 | 97.2 | 1447.1 | 1455.4 | 36.1 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1440.7 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 207 | 5 | 3 | 2 | 89 | 24 | 98 | 94.4 | 1425.9 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1399.9 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1382.2 | 1445.3 | 53.8 |
| Baidu Ernie 5.1 | Current roster | 406 | 0 | 0 | 0 | 198 | 44 | 182 | 100.0 | 1379.9 | 1409.6 | 36.7 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1379.4 | 1409.1 | 46.6 |
| Step 3.7 Flash (high) | Current roster | 400 | 12 | 11 | 0 | 190 | 43 | 189 | 94.7 | 1373.8 | 1406.7 | 37.5 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1363.4 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 306 | 2 | 2 | 0 | 152 | 42 | 139 | 99.4 | 1332.5 | 1370.7 | 41.8 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1553.4 | 1549.5 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 229 | 9 | 1 | 0 | 85 | 18 | 99 | 95.8 | 1534.2 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 263 | 7 | 0 | 0 | 93 | 21 | 105 | 97.0 | 1487.0 | 1527.4 | 53.2 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1445.4 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 334 | 4 | 2 | 0 | 160 | 32 | 153 | 97.6 | 1426.9 | 1457.1 | 40.8 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 173 | 3 | 2 | 0 | 49 | 17 | 64 | 96.6 | 1403.7 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1396.1 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 92 | 26 | 11 | 2 | 28 | 15 | 56 | 61.7 | 1382.3 | 1448.4 | 94.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1354.5 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1322.2 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 124 | 0 | 0 | 0 | 61 | 14 | 60 | 100.0 | 1263.4 | 1358.0 | 65.3 |
| Baidu Ernie 5.0 | Comparison model | 34 | 0 | 0 | 0 | 16 | 6 | 17 | 100.0 | 1239.0 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 123 | 3 | 0 | 0 | 57 | 11 | 62 | 95.2 | 1181.2 | 1328.2 | 67.5 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1021.2 | 1276.4 | 93.0 |
| GPT-5.4 Mini (xhigh) | Comparison model | 2 | 0 | 0 | 0 | 0 | 1 | 1 | 100.0 | NA | NA | NA |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 4933 | 0 | 4933 | 2490 |
| Gemini 3.1 Pro Preview | Current panel | 4131 | 0 | 4131 | 2087 |
| Qwen 3.7 Max | Current panel | 2751 | 0 | 2751 | 1389 |
| Grok 4.5 (high) | Current panel | 2589 | 0 | 2589 | 1304 |
| GPT-5.6 Sol (high) | Current panel | 2544 | 0 | 2544 | 1282 |
| Muse Spark 1.1 (high) | Current panel | 2422 | 0 | 2422 | 1226 |
| Claude Sonnet 5 (high) | Current panel | 1918 | 0 | 1918 | 965 |
| Qwen 3.6 Max Preview | Earlier panel | 2077 | 0 | 2077 | 1056 |
| Grok 4.3 | Earlier panel | 1735 | 0 | 1735 | 875 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1117 | 0 | 1117 | 567 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_deepseek41flash1017_20261024_finala__debate_all_templates`
