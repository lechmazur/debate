# Debate Proxy Error Audit

Found **33 affected turns** across **22 debates** and **0 side-swapped matchups**.

## Debates
- `prop_0030__mimo-v2-pro__grok-4.20-beta-0309-reasoning__s1__tpl_pilot_small_20260319a` — Xiaomi MiMo V2 Pro vs Grok 4.20 0309 (Reasoning); stored status `error`; affected turns `1`
- `prop_0092__claude-opus-4-6-adaptive__glm-5__s0__tpl_placement_active_20260320f` — Claude Opus 4.6 (high) vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0100__glm-5__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f` — GLM-5 vs Qwen3.5-397B-A17B; stored status `completed`; affected turns `1`
- `prop_0100__qwen3.5-397b-a17b__glm-5__s1__tpl_placement_active_20260320f` — Qwen3.5-397B-A17B vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0121__glm-5__mimo-v2-pro__s0__tpl_placement_active_20260320f` — GLM-5 vs Xiaomi MiMo V2 Pro; stored status `completed`; affected turns `1`
- `prop_0121__mimo-v2-pro__glm-5__s1__tpl_placement_active_20260320f` — Xiaomi MiMo V2 Pro vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0127__grok-4.20-beta-0309-non-reasoning__glm-5__s1__tpl_placement_active_20260320f` — Grok 4.20 0309 (Non-Reasoning) vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0185__glm-5__gpt-5.4-high__s0__tpl_placement_active_20260320f` — GLM-5 vs GPT-5.4 (high); stored status `completed`; affected turns `1`
- `prop_0185__gpt-5.4-high__glm-5__s1__tpl_placement_active_20260320f` — GPT-5.4 (high) vs GLM-5; stored status `completed`; affected turns `2`
- `prop_0311__gemini-3.1-flash-lite-preview__glm-5__s0__tpl_placement_active_20260320f` — Gemini 3.1 Flash-Lite Preview vs GLM-5; stored status `completed`; affected turns `3`
- `prop_0380__glm-5__grok-4.20-beta-0309-reasoning__s0__tpl_placement_active_20260320f` — GLM-5 vs Grok 4.20 0309 (Reasoning); stored status `completed`; affected turns `2`
- `prop_0380__grok-4.20-beta-0309-reasoning__glm-5__s1__tpl_placement_active_20260320f` — Grok 4.20 0309 (Reasoning) vs GLM-5; stored status `completed`; affected turns `2`
- `prop_0400__qwen3.5-397b-a17b__glm-5__s1__tpl_placement_active_20260320f` — Qwen3.5-397B-A17B vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0538__glm-5__minimax-m2.7__s0__tpl_placement_active_20260320f` — GLM-5 vs MiniMax-M2.7; stored status `completed`; affected turns `2`
- `prop_0538__minimax-m2.7__glm-5__s1__tpl_placement_active_20260320f` — MiniMax-M2.7 vs GLM-5; stored status `completed`; affected turns `2`
- `prop_0602__gemini-3.1-flash-lite-preview__glm-5__s0__tpl_placement_active_20260320f` — Gemini 3.1 Flash-Lite Preview vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0645__gpt-5.4-high__glm-5__s1__tpl_placement_active_20260320f` — GPT-5.4 (high) vs GLM-5; stored status `completed`; affected turns `2`
- `prop_0647__glm-5__mimo-v2-pro__s0__tpl_placement_active_20260320f` — GLM-5 vs Xiaomi MiMo V2 Pro; stored status `error`; affected turns `2`
- `prop_0647__mimo-v2-pro__glm-5__s1__tpl_placement_active_20260320f` — Xiaomi MiMo V2 Pro vs GLM-5; stored status `completed`; affected turns `2`
- `prop_0650__glm-5__grok-4.20-beta-0309-reasoning__s0__tpl_placement_active_20260320f` — GLM-5 vs Grok 4.20 0309 (Reasoning); stored status `completed`; affected turns `1`
- `prop_0650__grok-4.20-beta-0309-reasoning__glm-5__s1__tpl_placement_active_20260320f` — Grok 4.20 0309 (Reasoning) vs GLM-5; stored status `completed`; affected turns `1`
- `prop_0662__claude-opus-4-6-adaptive__glm-5__s0__tpl_placement_active_20260320f` — Claude Opus 4.6 (high) vs GLM-5; stored status `completed`; affected turns `2`

## Side-Swap Groups
- No affected side-swap groups found in the selected rating scope.

## Notes
- These rows are detected from stored transcript turn text, not from judge parse warnings.
- A contaminated debate here means at least one stored turn matched the proxy-style upstream error pattern `Error: {"error": ... }`.
- No affected side-swapped matchup feeds the selected ratings.

## Technical metadata

- Debate scope: `all_templates`
- Judge scope: `judge_blend_20260902_finala`
- Aggregate scope: `judge_judge_blend_20260902_finala__debate_all_templates`
- Paired-matchup source table: `debate_pair_groups__judge_judge_blend_20260902_finala__debate_all_templates.csv`
