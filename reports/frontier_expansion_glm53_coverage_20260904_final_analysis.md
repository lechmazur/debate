# GLM-5.3 high intake and expanded highlight coverage

Report generated at 2026-09-04T23:22:55.644117+00:00.

**459 of 466 new debate directions completed, producing 227 complete side-swapped topic groups and 1376 usable judgments.** There are 6 terminal debate content blocks/refusals, one exhausted formatting failure, and one terminal judge refusal. Every Gemini debate and judge call used port 8006. GLM used the explicit high-reasoning identity `glm-5-3-high`.

## Completed coverage

Counts below are completed directions. A shared matchup counts once for each participating highlight, while the campaign total deduplicates it. The allocation was frozen before results.

| Highlight | Before | Planned addition | Completed addition | Final total | Planned total |
|---|---:|---:|---:|---:|---:|
| GLM-5.3 (high) | 0 | 200 | 197 | 197 | 200 |
| GPT-6 Astra (high) | 200 | 78 | 78 | 278 | 278 |
| Claude Fable 5.1 (high) | 230 | 78 | 75 | 305 | 308 |
| Muse Spark 1.3 (high) | 226 | 66 | 66 | 292 | 292 |
| Tencent Hy4 Preview (high) | 268 | 60 | 60 | 328 | 328 |
| Gemini 3.8 Flash (high) | 202 | 56 | 55 | 257 | 258 |

## Final placement

The displayed leaderboard uses judge-normalized Bradley–Terry ratings. Overall ranks include all rated models; current ranks follow the chart visibility policy. Raw BT is reported separately. Changes reflect both the new evidence and recalibration of the connected comparison pool.

| Highlight | Previous displayed BT | Final displayed BT | Change | 95% CI | Overall rank | Current rank | Raw BT / rank |
|---|---:|---:|---:|---|---:|---:|---:|
| GLM-5.3 (high) | — | 1653.1 | — | 1638.1–1668.1 | 6/55 | 4/28 | 1656.6 / 5 |
| GPT-6 Astra (high) | 1613.9 | 1613.5 | -0.4 | 1599.4–1627.5 | 10/55 | 6/28 | 1613.4 / 11 |
| Claude Fable 5.1 (high) | 1752.0 | 1746.8 | -5.2 | 1734.6–1759.0 | 1/55 | 1/28 | 1751.4 / 1 |
| Muse Spark 1.3 (high) | 1603.3 | 1600.8 | -2.6 | 1589.3–1612.3 | 12/55 | 8/28 | 1603.0 / 12 |
| Tencent Hy4 Preview (high) | 1590.8 | 1590.4 | -0.5 | 1578.3–1602.4 | 14/55 | 10/28 | 1590.3 / 14 |
| Gemini 3.8 Flash (high) | 1524.7 | 1523.8 | -0.9 | 1510.2–1537.3 | 25/55 | 14/28 | 1524.8 / 25 |

GLM-5.3 high is only 0.5 normalized-BT points ahead of GPT-5.6 high (1652.6), with strongly overlapping 95% intervals. Astra stays essentially unchanged at 1613.5 versus 1613.9 before expansion; its interval width narrows from about 33.8 to 28.1 points. Its current rank moves from fifth to sixth when GLM enters above it.

## GLM opponent allocation

Each planned topic group contains two directions with sides swapped. GLM-5.2 is retained for direct predecessor comparison.

| Opponent | Planned topic groups | Planned debates | Completed debates |
|---|---:|---:|---:|
| GLM-5.2 (max) | 10 | 20 | 20 |
| GPT-6 Astra (high) | 7 | 14 | 14 |
| Claude Fable 5.1 (high) | 7 | 14 | 14 |
| Muse Spark 1.3 (high) | 6 | 12 | 12 |
| Tencent Hy4 Preview (high) | 6 | 12 | 12 |
| Gemini 3.8 Flash (high) | 6 | 12 | 12 |
| Claude Opus 5 (high) | 5 | 10 | 10 |
| Kimi K3 | 5 | 10 | 10 |
| GPT-5.6 Sol (high) | 5 | 10 | 10 |
| Grok 4.6 (high) | 5 | 10 | 10 |
| Claude Sonnet 5 (high) | 5 | 10 | 10 |
| DeepSeek V4 Pro 0813 (high) | 5 | 10 | 10 |
| Qwen 3.8 Max | 5 | 10 | 10 |
| MiniMax-M3 | 5 | 10 | 10 |
| Xiaomi MiMo V2.5 Pro | 5 | 10 | 8 |
| Gemini 3.1 Pro Preview | 5 | 10 | 10 |
| ByteDance Seed2.0 Pro | 2 | 4 | 4 |
| Step 3.7 Flash (high) | 2 | 4 | 3 |
| Baidu Ernie 5.1 | 2 | 4 | 4 |
| Mistral Medium 3.5 (high) | 2 | 4 | 4 |

## Integrity and retained failures

- The final append-only scope `judge_blend_glm53_coverage_20260904a` extends `judge_blend_astra_20260904_finala` by 1,376 judgment rows. It contains 20,634 judgments, 6,684 debates, and 3,371 tracked groups.
- The rating-eligible subset contains 3,313 groups, 6,626 debates, and 20,438 judgment rows across 55 models.
- Every completed new transcript has ten valid turns, the expected speakers, and no proxy-error text. Original and rejected raw responses are retained.
- Every assigned panel uses three distinct families and avoids debater families. Successful rows match the frozen assignments, parse correctly, retain raw responses and saved prompts, and have no duplicate keys. Terminal missing judgments remain explicit; they are not imputed or replaced.
- Debate protocol `placement_active_20260813a` / `debprot_dcec5496c621`, judge protocol `judge_active_20260711a` / `judprot_1c6058ad2d73`, temperature 1.0, and prompts are unchanged. Raw winner and margin fields are preserved in the frozen blend.
- Completed mates of refused directions remain stored and judged, while incomplete side-swapped groups are excluded from rating inputs.
- Terminal debate content block/refusal: `prop_0468__glm-5-3-high__mimo-v2.5-pro__s0__tpl_placement_active_20260813a`.
- Terminal debate content block/refusal: `prop_0468__mimo-v2.5-pro__glm-5-3-high__s1__tpl_placement_active_20260813a`.
- Terminal debate content block/refusal: `prop_0566__step-3.7-flash-high__glm-5-3-high__s1__tpl_placement_active_20260813a`.
- Terminal debate content block/refusal: `prop_0056__claude-fable-5-1-high__mimo-v2.5-pro__s0__tpl_placement_active_20260813a`.
- Terminal debate content block/refusal: `prop_0075__gemini-3.8-flash-high__step-3.7-flash-high__s0__tpl_placement_active_20260813a`.
- Terminal debate content block/refusal: `prop_0333__claude-fable-5-1-high__qwen3.8-max__s0__tpl_placement_active_20260813a`.
- Exhausted formatting failure: `prop_0102__claude-fable-5-1-high__claude-sonnet-5-high__s0__tpl_placement_active_20260813a`. Sonnet pre-assigned nonexistent C2 reference labels in all six rejected responses across the initial run and two exact resumes. Its three saved speeches are unchanged. The direction remains a validation error and is excluded from completed-only judging; the complete mate is retained. Evidence (canonical archive).
- Terminal judge refusal: `qwen3.7-max` on `prop_0161__muse-spark-1.3-high__glm-5-3-high__s1__tpl_placement_active_20260813a`; raw evidence (canonical archive).
- GLM's two HTTP 400 responses were diagnosed as terminal Z.ai moderation code 1301 from preserved router logs, with exact saved-prompt matches. Original metadata was archived before correcting availability classification; neither direction was retried. Diagnosis (canonical archive).

## Exact resumptions

Recoverable validation and request failures were resumed without overwrite. Saved valid speeches were preserved. Terminal moderation/refusal outcomes were not retried.

- frontier_expansion_glm53_coverage_20260904_muse_cap_repair_batch1 (canonical archive): 10 debate(s) repaired; 5 cached turn(s) verified unchanged.
- frontier_expansion_glm53_coverage_20260904_minimax_format_repair1 (canonical archive): 1 debate(s) repaired; 7 cached turn(s) verified unchanged.
- frontier_expansion_glm53_coverage_20260904_sonnet_citation_repair1 (canonical archive): 1 debate(s) repaired; 3 cached turn(s) verified unchanged.
- frontier_expansion_glm53_coverage_20260904_sonnet_citation_repair2 (canonical archive): six responses rejected; retained as an exhausted formatting failure; 3 cached turn(s) verified unchanged.

Two Astra/Fable preflight clients were stopped while waiting for Mistral native batch results, before generating any debate turns. Their exact shards resumed using `--model-port mistral-medium-3.5-high=8006`, while Astra and Fable stayed on 8040. Both replacement preflights passed. Routing audit (canonical archive).

One exact `qwen3.7-max` assignment was resumed on 8006 after score-field validation failed. The saved prompt is unchanged and both rejected responses remain archived. Judge repair (canonical archive).

The runtime token-cap fix makes every shard apply configured caps to each participating speaker. This preserves Muse’s validated 131072-token cap when Gemini owns their matchup. Focused validation passed 131 tests; preparation passed 47 tests.

## Outputs

- Highlighted current-model leaderboard (canonical archive)
- [Highlighted price/performance comparison](../images/debate_price_vs_performance__judge_judge_blend_glm53_coverage_20260904a__debate_all_templates.png)
- [Full leaderboard](debate_leaderboard__judge_judge_blend_glm53_coverage_20260904a__debate_all_templates.md)
- Rating table (canonical archive)
- Campaign manifest (canonical archive)
- [Integrity audit](debate_proxy_error_audit__judge_judge_blend_glm53_coverage_20260904a__debate_all_templates.md)

The initial chart render used API list pricing; the subsequent cost correction (canonical archive) restores token-based average debate costs, including Gemini thinking tokens. All six highlights have complete cost coverage for rating-eligible debates. Generated artifacts remain under the canonical benchmark archive; publication is a separate stage.

## Validation and completion

The combined historical-transcript audit found 33 old proxy-error turns in 22 stored debates, with **zero affected groups in this final rating scope**. All 13 PNGs passed file validation; the highlighted current-model leaderboard and price comparison were visually inspected.

Preparation passed 47 targeted tests. The runtime token-cap fix passed 131 targeted tests; compileall, strict transcript and judgment audits, aggregation, chart generation, PNG verification, and git diff checks passed. Commands ran with repository PYTHONPATH, memory limits, and timeouts; Plotly/Chrome used a 32 GiB systemd memory scope.

```bash
python -m pytest -q tests/test_debate_execution_helpers.py tests/test_parallel_wrapper.py tests/test_model_roster.py
python -m compileall -q run_debates.py run_benchmark_parallel.py tests/test_debate_execution_helpers.py tests/test_parallel_wrapper.py
python frontier_expansion_glm53_coverage_20260904_audit_debates.py
python frontier_expansion_glm53_coverage_20260904_freeze_blend.py
python -u aggregate_ratings.py --template-id judge_blend_glm53_coverage_20260904a --debate-template-id '*' --allow-mixed-debate-protocol-fingerprints
python -u plot_results.py --template-id judge_blend_glm53_coverage_20260904a --debate-template-id '*'
python -u audit_proxy_error_turns.py --debate-template-id '*' --judge-template-id judge_blend_glm53_coverage_20260904a
git diff --check
```

Completion commit: a46e3674a20c771965c4b78b76029c4d169ede07 — Record GLM-5.3 high and expanded highlight benchmark results. Worktree clean.
