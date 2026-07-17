# Debate Proxy Error Audit

- debate_template_id: `placement_active_20260320f`
- judge_template_id: `judge_blend_20260717b`
- output_scope_id: `judge_judge_blend_20260717b__debate_placement_active_20260320f`
- contaminated_turn_rows: `32`
- contaminated_debates: `21`
- affected_side_swap_groups: `0`
- pair_groups_csv: `/mnt/r/debate-data/stats/debate_pair_groups__judge_judge_blend_20260717b__debate_placement_active_20260320f.csv`

## Debates
- `prop_0092__claude-opus-4-6-adaptive__glm-5__s0__tpl_placement_active_20260320f`  status=completed models=claude-opus-4-6-adaptive vs glm-5 proxy_error_turns=1
- `prop_0100__glm-5__qwen3.5-397b-a17b__s0__tpl_placement_active_20260320f`  status=completed models=glm-5 vs qwen3.5-397b-a17b proxy_error_turns=1
- `prop_0100__qwen3.5-397b-a17b__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=qwen3.5-397b-a17b vs glm-5 proxy_error_turns=1
- `prop_0121__glm-5__mimo-v2-pro__s0__tpl_placement_active_20260320f`  status=completed models=glm-5 vs mimo-v2-pro proxy_error_turns=1
- `prop_0121__mimo-v2-pro__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=mimo-v2-pro vs glm-5 proxy_error_turns=1
- `prop_0127__grok-4.20-beta-0309-non-reasoning__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=grok-4.20-beta-0309-non-reasoning vs glm-5 proxy_error_turns=1
- `prop_0185__glm-5__gpt-5.4-high__s0__tpl_placement_active_20260320f`  status=completed models=glm-5 vs gpt-5.4-high proxy_error_turns=1
- `prop_0185__gpt-5.4-high__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=gpt-5.4-high vs glm-5 proxy_error_turns=2
- `prop_0311__gemini-3.1-flash-lite-preview__glm-5__s0__tpl_placement_active_20260320f`  status=completed models=gemini-3.1-flash-lite-preview vs glm-5 proxy_error_turns=3
- `prop_0380__glm-5__grok-4.20-beta-0309-reasoning__s0__tpl_placement_active_20260320f`  status=completed models=glm-5 vs grok-4.20-beta-0309-reasoning proxy_error_turns=2
- `prop_0380__grok-4.20-beta-0309-reasoning__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=grok-4.20-beta-0309-reasoning vs glm-5 proxy_error_turns=2
- `prop_0400__qwen3.5-397b-a17b__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=qwen3.5-397b-a17b vs glm-5 proxy_error_turns=1
- `prop_0538__glm-5__minimax-m2.7__s0__tpl_placement_active_20260320f`  status=completed models=glm-5 vs minimax-m2.7 proxy_error_turns=2
- `prop_0538__minimax-m2.7__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=minimax-m2.7 vs glm-5 proxy_error_turns=2
- `prop_0602__gemini-3.1-flash-lite-preview__glm-5__s0__tpl_placement_active_20260320f`  status=completed models=gemini-3.1-flash-lite-preview vs glm-5 proxy_error_turns=1
- `prop_0645__gpt-5.4-high__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=gpt-5.4-high vs glm-5 proxy_error_turns=2
- `prop_0647__glm-5__mimo-v2-pro__s0__tpl_placement_active_20260320f`  status=error models=glm-5 vs mimo-v2-pro proxy_error_turns=2
- `prop_0647__mimo-v2-pro__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=mimo-v2-pro vs glm-5 proxy_error_turns=2
- `prop_0650__glm-5__grok-4.20-beta-0309-reasoning__s0__tpl_placement_active_20260320f`  status=completed models=glm-5 vs grok-4.20-beta-0309-reasoning proxy_error_turns=1
- `prop_0650__grok-4.20-beta-0309-reasoning__glm-5__s1__tpl_placement_active_20260320f`  status=completed models=grok-4.20-beta-0309-reasoning vs glm-5 proxy_error_turns=1
- `prop_0662__claude-opus-4-6-adaptive__glm-5__s0__tpl_placement_active_20260320f`  status=completed models=claude-opus-4-6-adaptive vs glm-5 proxy_error_turns=2

## Side-Swap Groups
- No affected side-swap groups found in the selected rating scope.

## Notes
- These rows are detected from stored transcript turn text, not from judge parse warnings.
- A contaminated debate here means at least one stored turn matched the proxy-style upstream error pattern `Error: {"error": ... }`.
- Side-swap groups listed above are the ones to quarantine or rerun before trusting fresh aggregate outputs for that scope.
