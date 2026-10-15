# Debate Benchmark Status

This status page separates the complete stored rating graph from the public view, which hides retired or superseded identities while preserving their results in the source tables.

| Measure | Full stored graph | Public view |
| --- | ---: | ---: |
| Rated model identities | 62 | 59 |
| Side-swapped matchups represented | 4,031 | 3,774 |
| Complete matchups used for ratings | 3,961 | 3,714 |

The corpus tracks **8,444 debate artifacts** on **683 retained topics**: 8,273 completed and 171 incomplete. It contains 24,556 parsed judge decisions; 0 carry parse warnings.

Reliability records include 132 terminal model-service errors and 61 content blocks. Mean public-view availability is 96.9/100.

The published rating order follows Bradley-Terry; Glicko-2 and RD are secondary scheduling diagnostics.

## Coverage checks
- Current-roster participants missing completed debates: (none)
- Current-roster participants missing ratings: (none)
- Current judges with no decisions: (none)

## Judge Diagnostics
- mean cross-judge winner agreement: 0.625
- mean absolute presented-side margin bias by judge: 0.182

## Participant coverage
| Model | Benchmark role | Debates | Errors | Content blocks | Incomplete | Rated matchups | Opponents | Topics | Avail | BT | Glicko | RD |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Claude Fable 5.1 (high) | Current roster | 427 | 13 | 8 | 0 | 211 | 29 | 194 | 96.4 | 1734.8 | 1570.6 | 35.6 |
| Claude Fable 5 (high) | Current roster | 420 | 20 | 18 | 0 | 205 | 35 | 201 | 93.2 | 1722.9 | 1617.5 | 36.1 |
| Claude Opus 5 (high) | Current roster | 416 | 4 | 1 | 0 | 207 | 33 | 187 | 98.6 | 1721.0 | 1579.3 | 35.9 |
| Kimi K3 | Current roster | 452 | 4 | 4 | 0 | 225 | 37 | 197 | 98.7 | 1695.2 | 1580.5 | 34.5 |
| Claude Opus 5.5 (high) | Current roster | 247 | 3 | 2 | 0 | 122 | 16 | 114 | 97.6 | 1692.7 | 1523.2 | 46.6 |
| Gemini 4 Argon (high) | Current roster | 219 | 1 | 0 | 0 | 109 | 12 | 110 | 99.1 | 1676.4 | 1540.6 | 49.2 |
| Muse Wonder 1.0 (high) | Current roster | 220 | 0 | 0 | 0 | 110 | 12 | 110 | 100.0 | 1654.6 | 1514.4 | 49.0 |
| Claude Opus 4.7 (high) | Current roster | 246 | 4 | 3 | 0 | 120 | 32 | 122 | 97.6 | 1643.9 | 1596.6 | 47.0 |
| GPT-5.6 Sol (high) | Current roster | 537 | 5 | 3 | 0 | 267 | 39 | 238 | 98.5 | 1643.0 | 1545.7 | 31.6 |
| GLM-5.3 (high) | Current roster | 287 | 3 | 3 | 0 | 143 | 27 | 138 | 98.6 | 1639.1 | 1530.0 | 43.1 |
| Muse Spark 1.1 (high) | Current roster | 379 | 5 | 5 | 0 | 189 | 30 | 177 | 98.4 | 1634.4 | 1554.1 | 37.6 |
| Claude Opus 4.8 (high) | Current roster | 331 | 11 | 1 | 0 | 165 | 31 | 144 | 96.5 | 1626.9 | 1575.2 | 40.2 |
| Grok 4.7 (high) | Current roster | 229 | 1 | 0 | 0 | 114 | 18 | 110 | 99.1 | 1617.4 | 1500.1 | 48.2 |
| GPT-6 Astra (high) | Current roster | 355 | 1 | 0 | 0 | 177 | 24 | 167 | 99.4 | 1608.4 | 1508.4 | 38.8 |
| Xiaomi MiMo V2.6 Pro (thinking) | Current roster | 220 | 10 | 2 | 0 | 106 | 20 | 105 | 92.2 | 1606.3 | 1510.9 | 49.9 |
| Grok 4.6 (high) | Current roster | 395 | 3 | 2 | 0 | 197 | 27 | 179 | 99.0 | 1601.7 | 1493.2 | 36.8 |
| Muse Spark 1.3 (high) | Current roster | 399 | 1 | 0 | 0 | 199 | 26 | 189 | 99.5 | 1592.3 | 1497.5 | 36.6 |
| Claude Sonnet 5 (high) | Current roster | 439 | 5 | 0 | 0 | 217 | 37 | 198 | 97.7 | 1582.1 | 1520.9 | 35.1 |
| DeepSeek V4.1 Flash (high) | Current roster | 230 | 0 | 0 | 0 | 115 | 18 | 112 | 100.0 | 1579.9 | 1487.3 | 48.0 |
| Tencent Hy4 Preview (high) | Current roster | 390 | 2 | 0 | 0 | 194 | 27 | 173 | 99.0 | 1576.5 | 1504.0 | 37.1 |
| DeepSeek V4 Pro 0813 (high) | Current roster | 348 | 0 | 0 | 0 | 174 | 27 | 161 | 100.0 | 1569.8 | 1482.2 | 39.1 |
| GLM-5.2 (max) | Current roster | 367 | 2 | 2 | 1 | 182 | 33 | 163 | 98.4 | 1559.9 | 1520.1 | 38.3 |
| Qwen 3.8 Max | Current roster | 328 | 6 | 6 | 0 | 163 | 26 | 158 | 97.6 | 1549.9 | 1470.4 | 40.4 |
| GPT-5.4 (high) | Current roster | 275 | 5 | 0 | 0 | 131 | 30 | 139 | 97.1 | 1541.7 | 1544.0 | 45.0 |
| GPT-5.5 (high) | Current roster | 252 | 0 | 0 | 0 | 126 | 27 | 114 | 100.0 | 1523.5 | 1511.4 | 45.9 |
| GLM-5.1 | Current roster | 201 | 3 | 0 | 0 | 99 | 22 | 100 | 97.1 | 1514.3 | 1514.0 | 51.6 |
| Gemini 3.8 Flash (high) | Current roster | 273 | 1 | 1 | 0 | 136 | 26 | 135 | 99.3 | 1511.7 | 1471.3 | 44.2 |
| Kimi K2.6 | Current roster | 265 | 3 | 2 | 0 | 131 | 29 | 125 | 97.8 | 1507.0 | 1497.3 | 45.0 |
| MiniMax-M3 | Current roster | 316 | 4 | 4 | 0 | 156 | 32 | 146 | 97.5 | 1499.1 | 1480.5 | 41.3 |
| Grok 4.5 (high) | Current roster | 244 | 0 | 0 | 0 | 122 | 26 | 120 | 100.0 | 1486.5 | 1483.5 | 46.6 |
| Gemini 3.1 Pro Preview | Current roster | 473 | 13 | 1 | 0 | 235 | 52 | 213 | 96.7 | 1486.2 | 1465.9 | 33.7 |
| Xiaomi MiMo V2.5 Pro | Current roster | 380 | 11 | 9 | 1 | 187 | 41 | 181 | 95.4 | 1480.4 | 1459.0 | 37.8 |
| Qwen 3.6 Max Preview | Current roster | 168 | 0 | 0 | 0 | 84 | 20 | 80 | 100.0 | 1470.3 | 1489.6 | 55.9 |
| Mistral Large 4 (high) | Current roster | 199 | 1 | 1 | 0 | 98 | 14 | 100 | 99.0 | 1461.8 | 1467.5 | 51.9 |
| Gemini 3.7 Flash (high) | Current roster | 235 | 1 | 1 | 0 | 117 | 18 | 115 | 99.2 | 1452.3 | 1410.6 | 47.6 |
| ByteDance Seed2.0 Pro | Current roster | 424 | 4 | 4 | 2 | 175 | 47 | 175 | 97.7 | 1449.3 | 1464.8 | 39.0 |
| DeepSeek V4 Pro Preview | Current roster | 256 | 0 | 0 | 0 | 128 | 34 | 121 | 100.0 | 1443.8 | 1451.5 | 45.5 |
| MiniMax-M2.7 | Current roster | 207 | 5 | 3 | 2 | 89 | 24 | 98 | 94.4 | 1428.5 | 1470.6 | 54.4 |
| Gemini 3.5 Flash | Current roster | 259 | 1 | 1 | 0 | 129 | 31 | 126 | 99.2 | 1403.1 | 1430.0 | 45.3 |
| Qwen3.5-397B-A17B | Current roster | 196 | 6 | 2 | 0 | 91 | 30 | 98 | 96.0 | 1384.9 | 1445.3 | 53.8 |
| Tencent Hy3 Preview (high) | Current roster | 246 | 2 | 1 | 0 | 122 | 31 | 118 | 98.4 | 1382.0 | 1409.1 | 46.6 |
| Baidu Ernie 5.1 | Current roster | 346 | 0 | 0 | 0 | 168 | 38 | 159 | 100.0 | 1379.4 | 1416.7 | 39.8 |
| Step 3.7 Flash (high) | Current roster | 334 | 4 | 3 | 0 | 160 | 37 | 160 | 97.6 | 1377.8 | 1417.2 | 40.8 |
| Grok 4.3 | Current roster | 177 | 1 | 0 | 0 | 88 | 25 | 86 | 98.9 | 1366.2 | 1417.3 | 54.7 |
| Mistral Medium 3.5 (high) | Current roster | 254 | 2 | 2 | 0 | 127 | 37 | 118 | 99.2 | 1336.3 | 1382.4 | 45.7 |
| Claude Sonnet 4.6 (high) | Comparison model | 288 | 12 | 1 | 2 | 139 | 32 | 147 | 93.4 | 1555.9 | 1549.5 | 43.7 |
| Claude Sonnet 4.6 (no reasoning) | Comparison model | 229 | 9 | 1 | 0 | 85 | 18 | 99 | 95.8 | 1536.6 | 1542.0 | 55.6 |
| GPT-5.4 (no reasoning) | Comparison model | 263 | 7 | 0 | 0 | 93 | 21 | 105 | 97.0 | 1488.8 | 1527.4 | 53.2 |
| Kimi K2.5 Thinking | Comparison model | 246 | 18 | 5 | 0 | 73 | 30 | 124 | 90.2 | 1447.5 | 1488.6 | 59.9 |
| Qwen 3.7 Max | Comparison model | 334 | 4 | 2 | 0 | 160 | 32 | 153 | 97.6 | 1430.2 | 1457.1 | 40.8 |
| Grok 4.20 0309 (Reasoning) | Comparison model | 173 | 3 | 2 | 0 | 49 | 17 | 64 | 96.6 | 1406.1 | 1455.3 | 72.6 |
| Grok 4.20 0309 (Non-Reasoning) | Comparison model | 76 | 4 | 3 | 0 | 36 | 12 | 40 | 92.5 | 1398.6 | 1481.2 | 84.0 |
| Xiaomi MiMo V2 Pro | Comparison model | 92 | 26 | 11 | 2 | 28 | 15 | 56 | 61.7 | 1384.8 | 1448.4 | 94.5 |
| DeepSeek V3.2 | Comparison model | 85 | 3 | 0 | 0 | 41 | 13 | 44 | 93.2 | 1357.0 | 1441.0 | 79.0 |
| Gemini 3.1 Flash-Lite Preview | Comparison model | 68 | 4 | 1 | 0 | 31 | 11 | 36 | 91.7 | 1324.7 | 1430.6 | 90.1 |
| GPT-OSS-120B | Comparison model | 64 | 0 | 0 | 0 | 31 | 8 | 32 | 100.0 | 1258.0 | 1415.5 | 90.1 |
| Baidu Ernie 5.0 | Comparison model | 34 | 0 | 0 | 0 | 16 | 6 | 17 | 100.0 | 1241.5 | 1359.2 | 121.7 |
| Mistral Large 3 | Comparison model | 93 | 3 | 0 | 0 | 42 | 8 | 48 | 93.8 | 1176.8 | 1359.7 | 78.1 |
| Llama 4 Maverick | Comparison model | 63 | 1 | 1 | 0 | 29 | 8 | 32 | 96.9 | 1020.9 | 1276.4 | 93.0 |
| gpt-5.4-mini-xhigh | Comparison model | 2 | 0 | 0 | 0 | 0 | 1 | 1 | 100.0 | NA | NA | NA |

## Judge coverage
| Judge | Panel role | Decisions | Parse warnings | Debates | Side-swapped matchups |
| --- | --- | ---: | ---: | ---: | ---: |
| Kimi K2.6 | Current panel | 4543 | 0 | 4543 | 2294 |
| Gemini 3.1 Pro Preview | Current panel | 3687 | 0 | 3687 | 1863 |
| Qwen 3.7 Max | Current panel | 2229 | 0 | 2229 | 1125 |
| Grok 4.5 (high) | Current panel | 2053 | 0 | 2053 | 1034 |
| GPT-5.6 Sol (high) | Current panel | 2051 | 0 | 2051 | 1033 |
| Muse Spark 1.1 (high) | Current panel | 1982 | 0 | 1982 | 1004 |
| Claude Sonnet 5 (high) | Current panel | 1530 | 0 | 1530 | 770 |
| Qwen 3.6 Max Preview | Earlier panel | 2077 | 0 | 2077 | 1056 |
| Grok 4.3 | Earlier panel | 1735 | 0 | 1735 | 875 |
| GPT-5.5 (high) | Earlier panel | 1552 | 0 | 1552 | 789 |
| Claude Sonnet 4.6 (high) | Earlier panel | 1117 | 0 | 1117 | 567 |

## Technical metadata

- Evaluation scope: `judge_judge_blend_mistral4_20261014_finalb__debate_all_templates`
