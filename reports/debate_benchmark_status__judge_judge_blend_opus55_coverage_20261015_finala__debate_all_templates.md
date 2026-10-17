# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 62 | 59 |
| Side-swapped matchups represented | 4,298 | 4,041 |
| Complete matchups used for ratings | 4,223 | 3,976 |

The corpus tracks **8,988 debate artifacts** on **683 retained topics**: 8,808 completed and 180 incomplete. It contains 26,143 parsed judge decisions; 0 carry parse warnings.

Reliability records include 141 terminal model-service errors and 68 content blocks. Mean public-view availability is 96.9/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.634
- mean absolute presented-side margin bias by judge: 0.181

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 429 | 13 | 8 | 0 | 212 | 29 | 195 | 96.4 | 1733.5 | 1571.2 | 35.5 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1722.4 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 416 | 4 | 1 | 0 | 207 | 33 | 187 | 98.6 | 1720.1 | 1579.3 | 35.9 |
| Kimi K3 | Current roster | 452 | 4 | 4 | 0 | 225 | 37 | 197 | 98.7 | 1694.0 | 1580.5 | 34.5 |
| Claude Opus 5.5 (high) | Current roster | 391 | 7 | 5 | 0 | 192 | 27 | 179 | 97.0 | 1691.1 | 1566.7 | 37.3 |
| Gemini 4 Argon (high) | Current roster | 353 | 3 | 2 | 0 | 175 | 25 | 169 | 98.9 | 1672.7 | 1575.1 | 39.0 |
| Muse Wonder 1.0 (high) | Current roster | 352 | 2 | 1 | 0 | 175 | 25 | 168 | 98.9 | 1651.9 | 1556.1 | 39.0 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1644.1 | 1596.6 | 47.0 |
| GPT-5.6 Sol (high) | Current roster | 537 | 5 | 3 | 0 | 267 | 39 | 238 | 98.5 | 1642.0 | 1545.7 | 31.6 |
| GLM-5.3 (high) | Current roster | 287 | 3 | 3 | 0 | 143 | 27 | 138 | 98.6 | 1637.7 | 1530.0 | 43.1 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1633.9 | 1554.1 | 37.6 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1626.7 | 1575.2 | 40.2 |
| Grok 4.7 (high) | Current roster | 229 | 1 | 0 | 0 | 114 | 18 | 110 | 99.1 | 1616.1 | 1500.1 | 48.2 |
| GPT-6 Astra (high) | Current roster | 365 | 1 | 0 | 0 | 182 | 25 | 171 | 99.5 | 1608.0 | 1507.2 | 38.3 |
| Xiaomi MiMo V2.6 Pro (thinking) | Current roster | 224 | 10 | 2 | 0 | 108 | 20 | 106 | 92.3 | 1604.6 | 1509.5 | 49.5 |
| Grok 4.6 (high) | Current roster | 395 | 3 | 2 | 0 | 197 | 27 | 179 | 99.0 | 1600.9 | 1493.2 | 36.8 |
| Muse Spark 1.3 (high) | Current roster | 425 | 1 | 0 | 0 | 212 | 28 | 201 | 99.5 | 1593.3 | 1499.0 | 35.5 |
| Claude Sonnet 5 (high) | Current roster | 480 | 8 | 1 | 0 | 237 | 41 | 214 | 97.1 | 1582.5 | 1517.8 | 33.6 |
| DeepSeek V4.1 Flash (high) | Current roster | 230 | 0 | 0 | 0 | 115 | 18 | 112 | 100.0 | 1578.5 | 1487.3 | 48.0 |
| Tencent Hy4 Preview (high) | Current roster | 426 | 2 | 0 | 0 | 212 | 30 | 186 | 99.1 | 1577.6 | 1503.1 | 35.5 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 386 | 0 | 0 | 0 | 193 | 30 | 174 | 100.0 | 1567.2 | 1480.0 | 37.2 |
| GLM-5.2 (max) | Current roster | 367 | 2 | 2 | 1 | 182 | 33 | 163 | 98.4 | 1559.3 | 1520.1 | 38.3 |
| Qwen 3.8 Max | Current roster | 368 | 6 | 6 | 0 | 183 | 30 | 177 | 97.9 | 1549.3 | 1469.0 | 38.2 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1542.7 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1523.4 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1514.4 | 1514.0 | 51.6 |
| Gemini 3.8 Flash (high) | Current roster | 315 | 1 | 1 | 0 | 155 | 29 | 151 | 99.4 | 1509.7 | 1466.2 | 41.4 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1506.8 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 356 | 4 | 4 | 0 | 176 | 36 | 159 | 97.8 | 1496.0 | 1472.5 | 38.9 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1486.1 | 1483.5 | 46.6 |
| Gemini 3.1 Pro Preview | Current roster | 503 | 13 | 1 | 0 | 250 | 55 | 224 | 96.9 | 1485.2 | 1463.2 | 32.7 |
| Xiaomi MiMo V2.5 Pro | Current roster | 380 | 11 | 9 | 1 | 187 | 41 | 181 | 95.4 | 1480.0 | 1459.0 | 37.8 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1470.4 | 1489.6 | 55.9 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1451.2 | 1410.6 | 47.6 |
| Mistral Large 4 (high) | Current roster | 324 | 2 | 2 | 0 | 159 | 26 | 156 | 98.8 | 1451.2 | 1466.1 | 40.9 |
| ByteDance Seed2.0 Pro | Current roster | 466 | 6 | 6 | 2 | 195 | 51 | 191 | 97.0 | 1448.1 | 1456.9 | 37.0 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1443.6 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 207 | 5 | 3 | 2 | 89 | 24 | 98 | 94.4 | 1429.0 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1402.8 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1385.2 | 1445.3 | 53.8 |
| Baidu Ernie 5.1 | Current roster | 386 | 0 | 0 | 0 | 188 | 42 | 173 | 100.0 | 1383.0 | 1412.3 | 37.7 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1382.0 | 1409.1 | 46.6 |
| Step 3.7 Flash (high) | Current roster | 376 | 8 | 7 | 0 | 180 | 41 | 176 | 96.4 | 1377.0 | 1409.5 | 38.5 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1366.2 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 286 | 2 | 2 | 0 | 142 | 40 | 130 | 99.3 | 1336.6 | 1374.0 | 43.2 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1556.4 | 1549.5 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 229 | 9 | 1 | 0 | 85 | 18 | 99 | 95.8 | 1537.2 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 263 | 7 | 0 | 0 | 93 | 21 | 105 | 97.0 | 1490.3 | 1527.4 | 53.2 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1448.7 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 334 | 4 | 2 | 0 | 160 | 32 | 153 | 97.6 | 1429.8 | 1457.1 | 40.8 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 173 | 3 | 2 | 0 | 49 | 17 | 64 | 96.6 | 1406.7 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1398.8 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 92 | 26 | 11 | 2 | 28 | 15 | 56 | 61.7 | 1385.1 | 1448.4 | 94.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1357.3 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1324.9 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 104 | 0 | 0 | 0 | 51 | 12 | 51 | 100.0 | 1272.9 | 1373.3 | 71.2 |
| Baidu Ernie 5.0 | Comparison model | 34 | 0 | 0 | 0 | 16 | 6 | 17 | 100.0 | 1241.6 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 123 | 3 | 0 | 0 | 57 | 11 | 62 | 95.2 | 1184.9 | 1328.2 | 67.5 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1025.6 | 1276.4 | 93.0 |
| GPT-5.4 Mini (xhigh) | Comparison model | 2 | 0 | 0 | 0 | 0 | 1 | 1 | 100.0 | NA | NA | NA |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 4829 | 0 | 4829 | 2438 |
| Gemini 3.1 Pro Preview | Current panel | 3858 | 0 | 3858 | 1949 |
| Qwen 3.7 Max | Current panel | 2478 | 0 | 2478 | 1251 |
| Grok 4.5 (high) | Current panel | 2309 | 0 | 2309 | 1163 |
| GPT-5.6 Sol (high) | Current panel | 2308 | 0 | 2308 | 1163 |
| Muse Spark 1.1 (high) | Current panel | 2185 | 0 | 2185 | 1107 |
| Claude Sonnet 5 (high) | Current panel | 1695 | 0 | 1695 | 853 |
| Qwen 3.6 Max Preview | Earlier panel | 2077 | 0 | 2077 | 1056 |
| Grok 4.3 | Earlier panel | 1735 | 0 | 1735 | 875 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1117 | 0 | 1117 | 567 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_opus55_coverage_20261015_finala__debate_all_templates`
