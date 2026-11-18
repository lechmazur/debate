# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 72 | 69 |
| Side-swapped matchups represented | 5,543 | 5,286 |
| Complete matchups used for ratings | 5,464 | 5,217 |

The corpus tracks **11,660 debate artifacts** on **683 retained topics**: 11,395 completed and 265 incomplete. It contains 33,601 parsed judge decisions; 50 carry parse warnings.

Reliability records include 207 terminal model-service errors and 99 content blocks. Mean public-view availability is 96.6/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.658
- mean absolute presented-side margin bias by judge: 0.152

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 639 | 21 | 13 | 0 | 307 | 40 | 287 | 95.8 | 1705.5 | 1567.7 | 29.5 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1705.2 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 416 | 4 | 1 | 0 | 207 | 33 | 187 | 98.6 | 1703.7 | 1579.3 | 35.9 |
| Claude Fable 5.2 (high) | Current roster | 421 | 13 | 8 | 2 | 193 | 26 | 199 | 95.4 | 1687.9 | 1563.5 | 37.2 |
| Claude Opus 5.5 (high) | Current roster | 580 | 8 | 5 | 4 | 280 | 37 | 266 | 97.0 | 1680.3 | 1558.8 | 30.9 |
| Qwen 4 Max (high) | Current roster | 357 | 13 | 6 | 2 | 169 | 25 | 186 | 93.0 | 1678.8 | 1560.8 | 39.7 |
| Kimi K3 | Current roster | 502 | 4 | 4 | 0 | 249 | 39 | 214 | 98.8 | 1678.6 | 1578.5 | 32.8 |
| Gemini 4 Carbon (high) | Current roster | 396 | 10 | 5 | 10 | 186 | 26 | 202 | 93.3 | 1676.2 | 1560.8 | 37.9 |
| GPT-6.2 Astra (high) | Current roster | 336 | 20 | 2 | 0 | 156 | 24 | 178 | 93.8 | 1673.2 | 1560.9 | 41.3 |
| Gemini 4 Argon (high) | Current roster | 527 | 5 | 2 | 0 | 261 | 35 | 248 | 98.9 | 1649.0 | 1550.9 | 32.0 |
| Tencent Hy4 (high) | Current roster | 292 | 6 | 0 | 0 | 144 | 26 | 135 | 97.3 | 1646.5 | 1552.9 | 42.9 |
| Muse Wonder 1.0 (high) | Current roster | 456 | 2 | 1 | 0 | 226 | 35 | 205 | 99.1 | 1637.2 | 1546.8 | 34.4 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1627.4 | 1596.6 | 47.0 |
| GPT-5.6 Sol (high) | Current roster | 557 | 5 | 3 | 0 | 277 | 41 | 242 | 98.6 | 1624.7 | 1543.8 | 31.1 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1617.0 | 1554.1 | 37.6 |
| GLM-5.3 (high) | Current roster | 392 | 4 | 3 | 0 | 194 | 37 | 189 | 98.5 | 1613.1 | 1516.1 | 37.1 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1610.3 | 1575.2 | 40.2 |
| GPT-6 Astra (high) | Current roster | 492 | 2 | 1 | 4 | 243 | 36 | 229 | 98.4 | 1606.6 | 1511.0 | 33.2 |
| Grok 4.7 (high) | Current roster | 319 | 1 | 0 | 0 | 159 | 28 | 149 | 99.4 | 1601.1 | 1497.1 | 40.9 |
| Kimi K3.1 Pro (high) | Current roster | 411 | 5 | 5 | 8 | 200 | 32 | 209 | 96.2 | 1601.0 | 1513.1 | 36.5 |
| Grok 4.6 (high) | Current roster | 395 | 3 | 2 | 0 | 197 | 27 | 179 | 99.0 | 1585.0 | 1493.2 | 36.8 |
| Xiaomi MiMo V2.6 Pro (thinking) | Current roster | 333 | 18 | 5 | 5 | 156 | 30 | 159 | 89.3 | 1584.0 | 1495.0 | 41.3 |
| DeepSeek V4.1 Flash 1017 (high) | Current roster | 331 | 10 | 5 | 3 | 164 | 31 | 170 | 95.3 | 1578.7 | 1511.8 | 40.3 |
| Muse Spark 1.3 (high) | Current roster | 425 | 1 | 0 | 0 | 212 | 28 | 201 | 99.5 | 1577.6 | 1499.0 | 35.5 |
| Claude Sonnet 5 (high) | Current roster | 500 | 10 | 3 | 0 | 247 | 43 | 219 | 96.9 | 1567.7 | 1517.1 | 32.9 |
| DeepSeek V4.1 Flash (high) | Current roster | 240 | 0 | 0 | 0 | 120 | 19 | 116 | 100.0 | 1564.2 | 1488.1 | 47.0 |
| Tencent Hy4 Preview (high) | Current roster | 484 | 4 | 2 | 0 | 241 | 36 | 210 | 98.8 | 1561.3 | 1497.9 | 33.3 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 476 | 2 | 2 | 0 | 236 | 40 | 210 | 99.2 | 1552.3 | 1476.1 | 33.6 |
| GLM-5.2 (max) | Current roster | 367 | 2 | 2 | 1 | 182 | 33 | 163 | 98.4 | 1542.3 | 1520.1 | 38.3 |
| Qwen 3.8 Max | Current roster | 436 | 6 | 6 | 0 | 217 | 37 | 206 | 98.2 | 1534.8 | 1465.7 | 35.1 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1525.4 | 1544.0 | 45.0 |
| Step 5 Preview (high) | Current roster | 287 | 7 | 7 | 0 | 140 | 26 | 142 | 96.6 | 1521.1 | 1470.0 | 43.5 |
| MiniMax M3.1 Flash (high) | Current roster | 152 | 2 | 2 | 0 | 74 | 24 | 77 | 98.7 | 1509.4 | 1447.5 | 59.5 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1506.8 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1497.7 | 1514.0 | 51.6 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1490.4 | 1497.3 | 45.0 |
| Gemini 3.8 Flash (high) | Current roster | 405 | 1 | 1 | 0 | 200 | 39 | 188 | 99.5 | 1487.9 | 1451.9 | 36.5 |
| MiniMax-M3 | Current roster | 376 | 4 | 4 | 0 | 186 | 38 | 167 | 97.9 | 1482.9 | 1472.4 | 37.9 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1469.9 | 1483.5 | 46.6 |
| Gemini 3.1 Pro Preview | Current roster | 503 | 13 | 1 | 0 | 250 | 55 | 224 | 96.9 | 1468.2 | 1463.2 | 32.7 |
| ByteDance Seed2.1 Pro | Current roster | 151 | 3 | 2 | 0 | 75 | 24 | 76 | 97.4 | 1468.1 | 1421.1 | 59.1 |
| Xiaomi MiMo V2.5 Pro | Current roster | 380 | 11 | 9 | 1 | 187 | 41 | 181 | 95.4 | 1463.0 | 1459.0 | 37.8 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1453.5 | 1489.6 | 55.9 |
| Mistral Large 4 (high) | Current roster | 412 | 4 | 2 | 0 | 203 | 36 | 193 | 98.6 | 1442.3 | 1453.0 | 36.3 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1434.2 | 1410.6 | 47.6 |
| ByteDance Seed2.0 Pro | Current roster | 486 | 6 | 6 | 2 | 205 | 53 | 199 | 97.2 | 1433.9 | 1455.4 | 36.1 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1427.1 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 207 | 5 | 3 | 2 | 89 | 24 | 98 | 94.4 | 1412.1 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1386.5 | 1430.0 | 45.3 |
| Baidu Ernie 5.1 | Current roster | 476 | 6 | 0 | 0 | 231 | 52 | 211 | 98.3 | 1369.5 | 1400.9 | 34.0 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1368.4 | 1445.3 | 53.8 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1365.6 | 1409.1 | 46.6 |
| Step 3.7 Flash (high) | Current roster | 475 | 13 | 12 | 0 | 227 | 51 | 222 | 95.1 | 1355.0 | 1390.8 | 34.3 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1349.7 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 379 | 5 | 2 | 0 | 187 | 50 | 174 | 98.4 | 1321.4 | 1360.1 | 37.8 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1539.6 | 1549.5 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 229 | 9 | 1 | 0 | 85 | 18 | 99 | 95.8 | 1520.3 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 263 | 7 | 0 | 0 | 93 | 21 | 105 | 97.0 | 1472.8 | 1527.4 | 53.2 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1431.2 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 334 | 4 | 2 | 0 | 160 | 32 | 153 | 97.6 | 1413.6 | 1457.1 | 40.8 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 173 | 3 | 2 | 0 | 49 | 17 | 64 | 96.6 | 1389.8 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1382.3 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 92 | 26 | 11 | 2 | 28 | 15 | 56 | 61.7 | 1368.5 | 1448.4 | 94.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1340.7 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1308.4 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 220 | 0 | 0 | 0 | 108 | 24 | 108 | 100.0 | 1242.0 | 1314.8 | 49.5 |
| Baidu Ernie 5.0 | Comparison model | 34 | 0 | 0 | 0 | 16 | 6 | 17 | 100.0 | 1225.3 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 123 | 3 | 0 | 0 | 57 | 11 | 62 | 95.2 | 1169.5 | 1328.2 | 67.5 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1006.3 | 1276.4 | 93.0 |
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
| Muse Wonder 1.0 (high) | Earlier panel | 728 | 0 | 728 | 364 |
| GLM-5.3 (high) | Earlier panel | 714 | 44 | 714 | 357 |
| Grok 4.7 (high) | Earlier panel | 694 | 0 | 694 | 347 |
| Kimi K3.1 Pro (high) | Earlier panel | 670 | 1 | 670 | 335 |
| DeepSeek V4 Pro 0813 (high) | Earlier panel | 656 | 0 | 656 | 328 |
| Gemini 4 Carbon (high) | Earlier panel | 642 | 1 | 642 | 321 |
| Claude Opus 5.5 (high) | Earlier panel | 634 | 3 | 634 | 317 |
| Qwen 3.8 Max 0902 | Earlier panel | 550 | 1 | 550 | 275 |
| GPT-6 Astra (high) | Earlier panel | 544 | 0 | 544 | 272 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_astra62_intake_20261117a_judge4__debate_all_templates`
