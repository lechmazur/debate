# Qualitative Behavior Audit

This report keeps four claims separate: prompt compliance is mechanically observed; diagnostic scores are judge perceptions; LLM transcript coding is a separate blinded layer; factual accuracy requires open-book review. Assigned advocacy is not evidence of a model's beliefs.

## Prompt Compliance

Word use is measured before and after clipping. Claim-reference errors mean an internal debate claim ID was missing; they do not measure external citation accuracy.

| Model | Mean limit use | Clipped | Format compliant | Uses claim IDs | Missing IDs when citing |
|---|---:|---:|---:|---:|---:|
| DeepSeek V4 Pro Preview | 98.2% | 53.2% | 100.0% | 34.1% | 0.0% |
| Xiaomi MiMo V2.5 Pro | 97.3% | 53.0% | 100.0% | 29.9% | 0.0% |
| MiniMax-M2.7 | 96.1% | 42.2% | 100.0% | 21.6% | 0.0% |
| GPT-5.4 (no reasoning) | 93.5% | 63.6% | 100.0% | 4.0% | 0.0% |
| Claude Fable 5.1 (high) | 92.3% | 25.9% | 100.0% | 73.4% | 0.0% |
| Claude Opus 5 (high) | 92.1% | 23.0% | 100.0% | 65.9% | 0.0% |
| GPT-5.5 (high) | 91.7% | 54.2% | 100.0% | 7.7% | 0.0% |
| GPT-OSS-120B | 91.0% | 42.3% | 100.0% | 19.7% | 0.0% |
| Mistral Large 3 | 90.2% | 34.5% | 100.0% | 19.1% | 0.0% |
| Claude Sonnet 4.6 (no reasoning) | 89.4% | 19.6% | 100.0% | 32.1% | 0.0% |
| GLM-5.3 (high) | 88.9% | 18.1% | 100.0% | 34.3% | 0.0% |
| Claude Sonnet 4.6 (high) | 88.8% | 16.2% | 100.0% | 32.3% | 0.0% |
| Claude Opus 4.8 (high) | 88.6% | 4.2% | 100.0% | 48.6% | 0.0% |
| MiniMax-M3 | 88.6% | 18.9% | 100.0% | 40.9% | 0.0% |
| Step 3.7 Flash (high) | 87.9% | 19.0% | 100.0% | 14.8% | 0.0% |
| Claude Opus 4.7 (high) | 87.8% | 3.6% | 100.0% | 23.9% | 0.0% |
| GPT-5.4 (high) | 87.7% | 24.8% | 100.0% | 24.2% | 0.0% |
| Claude Fable 5 (high) | 87.2% | 0.2% | 100.0% | 73.5% | 0.0% |
| Gemini 3.1 Pro Preview | 87.0% | 0.2% | 100.0% | 83.4% | 0.0% |
| Kimi K3 | 86.7% | 5.7% | 100.0% | 73.6% | 0.0% |
| Gemini 3.1 Flash-Lite Preview | 85.8% | 0.3% | 100.0% | 35.9% | 0.0% |
| GPT-5.6 Sol (high) | 85.6% | 14.9% | 100.0% | 6.6% | 0.0% |
| Grok 4.20 0309 (Non-Reasoning) | 85.5% | 23.5% | 100.0% | 45.9% | 0.0% |
| Claude Sonnet 5 (high) | 85.3% | 7.8% | 100.0% | 58.8% | 0.0% |
| Tencent Hy4 Preview (high) | 84.6% | 0.1% | 100.0% | 85.9% | 0.0% |
| GLM-5.1 | 83.9% | 8.3% | 100.0% | 23.1% | 0.0% |
| GLM-5.2 (max) | 83.7% | 7.7% | 100.0% | 34.0% | 0.0% |
| Kimi K2.6 | 83.6% | 4.4% | 100.0% | 63.2% | 0.0% |
| Qwen3.5-397B-A17B | 83.0% | 0.7% | 100.0% | 47.3% | 0.0% |
| GPT-6 Astra (high) | 82.6% | 0.0% | 100.0% | 2.9% | 0.0% |
| Baidu Ernie 5.1 | 82.5% | 4.9% | 100.0% | 31.2% | 0.0% |
| Xiaomi MiMo V2 Pro | 82.1% | 10.3% | 100.0% | 18.4% | 0.0% |
| Qwen 3.7 Max | 81.0% | 0.0% | 100.0% | 35.5% | 0.0% |
| DeepSeek V4 Pro 0813 (high) | 80.6% | 3.5% | 100.0% | 52.3% | 0.0% |
| Grok 4.6 (high) | 80.1% | 2.2% | 100.0% | 56.1% | 0.0% |
| Gemini 3.8 Flash (high) | 79.8% | 0.0% | 100.0% | 67.5% | 0.0% |
| Qwen 3.8 Max | 79.8% | 0.0% | 100.0% | 40.3% | 0.0% |
| Kimi K2.5 Thinking | 79.7% | 3.4% | 100.0% | 78.0% | 0.0% |
| Tencent Hy3 Preview (high) | 79.6% | 9.4% | 100.0% | 49.7% | 0.0% |
| Qwen 3.6 Max Preview | 79.5% | 0.8% | 100.0% | 16.7% | 0.0% |
| Muse Spark 1.1 (high) | 79.4% | 1.4% | 100.0% | 85.1% | 0.0% |
| Llama 4 Maverick | 78.8% | 5.4% | 100.0% | 43.7% | 0.0% |
| Grok 4.20 0309 (Reasoning) | 77.8% | 6.0% | 100.0% | 70.0% | 0.0% |
| Muse Spark 1.3 (high) | 77.7% | 0.3% | 100.0% | 32.6% | 0.0% |
| Gemini 3.7 Flash (high) | 77.5% | 0.0% | 100.0% | 59.8% | 0.0% |
| Gemini 3.5 Flash | 76.9% | 0.0% | 100.0% | 55.1% | 0.0% |
| Grok 4.5 (high) | 74.3% | 0.7% | 100.0% | 21.8% | 0.0% |
| Baidu Ernie 5.0 | 71.0% | 5.0% | 100.0% | 15.0% | 0.0% |
| ByteDance Seed2.0 Pro | 70.1% | 0.2% | 100.0% | 0.7% | 0.0% |
| Grok 4.3 | 68.9% | 0.3% | 100.0% | 5.3% | 0.0% |
| Mistral Medium 3.5 (high) | 68.0% | 6.9% | 100.0% | 7.4% | 0.0% |
| DeepSeek V3.2 | 67.4% | 0.2% | 100.0% | 28.9% | 0.0% |

## Judge Diagnostic Structure

The table uses each judge's within-row model-minus-opponent score, which cancels that row's judge intercept. Confidence intervals cluster the three judge rows to the debate before estimation. These diagnostics are not rating inputs.

The first diagnostic component explains 97.8% of model-level variance across the five axes. High overlap means axis-specific rankings should be read as residual texture, not five independent leaderboards.

| Model | Axis | Mean score | vs field | vs opponent | 95% CI | Paired PRO−CON gap |
|---|---|---:|---:|---:|---:|---:|
| Llama 4 Maverick | rebuttal quality | 4.05 | -3.29 | -4.08 | [-4.56, -3.60] | +2.02 |
| Llama 4 Maverick | argument strength | 4.46 | -2.88 | -3.45 | [-3.86, -3.04] | +1.89 |
| Llama 4 Maverick | rhetorical effectiveness | 4.63 | -2.98 | -3.37 | [-3.71, -3.03] | +1.68 |
| Llama 4 Maverick | originality of argument | 4.02 | -2.78 | -2.92 | [-3.19, -2.65] | +0.81 |
| Baidu Ernie 5.0 | rebuttal quality | 5.30 | -2.04 | -2.82 | [-3.07, -2.57] | +0.13 |
| Llama 4 Maverick | grounding and epistemic discipline | 5.17 | -2.12 | -2.42 | [-2.77, -2.07] | +1.35 |
| Baidu Ernie 5.0 | argument strength | 5.74 | -1.61 | -2.19 | [-2.40, -1.98] | +0.43 |
| Mistral Medium 3.5 (high) | rebuttal quality | 5.97 | -1.38 | -2.08 | [-2.24, -1.91] | +0.36 |
| Baidu Ernie 5.0 | originality of argument | 5.07 | -1.74 | -1.96 | [-2.16, -1.76] | -0.07 |
| Baidu Ernie 5.0 | rhetorical effectiveness | 5.93 | -1.68 | -1.95 | [-2.16, -1.74] | +0.39 |
| Claude Fable 5 (high) | rebuttal quality | 8.41 | +1.06 | +1.81 | [+1.69, +1.93] | -0.49 |
| Mistral Large 3 | rebuttal quality | 5.72 | -1.63 | -1.74 | [-2.59, -0.88] | +3.51 |
| Baidu Ernie 5.0 | grounding and epistemic discipline | 5.93 | -1.37 | -1.62 | [-1.86, -1.38] | +0.14 |
| GPT-OSS-120B | rebuttal quality | 5.98 | -1.37 | -1.53 | [-2.17, -0.90] | +1.23 |
| Grok 4.3 | rebuttal quality | 6.36 | -0.99 | -1.53 | [-1.71, -1.34] | +0.45 |
| Tencent Hy3 Preview (high) | rebuttal quality | 6.39 | -0.96 | -1.49 | [-1.68, -1.30] | +0.14 |
| Step 3.7 Flash (high) | rebuttal quality | 6.25 | -1.10 | -1.48 | [-1.66, -1.31] | +0.68 |
| Claude Opus 4.7 (high) | rebuttal quality | 8.23 | +0.89 | +1.48 | [+1.33, +1.64] | +0.11 |
| Mistral Medium 3.5 (high) | argument strength | 6.36 | -0.99 | -1.47 | [-1.61, -1.33] | +0.57 |
| Mistral Medium 3.5 (high) | originality of argument | 5.73 | -1.07 | -1.40 | [-1.52, -1.29] | +0.00 |
| Baidu Ernie 5.1 | rebuttal quality | 6.42 | -0.93 | -1.40 | [-1.56, -1.23] | +0.60 |
| Mistral Medium 3.5 (high) | rhetorical effectiveness | 6.61 | -1.00 | -1.38 | [-1.49, -1.26] | +0.46 |
| Claude Fable 5 (high) | argument strength | 8.13 | +0.78 | +1.35 | [+1.25, +1.44] | -0.05 |
| Grok 4.3 | rhetorical effectiveness | 6.65 | -0.96 | -1.34 | [-1.47, -1.22] | +0.46 |
| Claude Opus 4.8 (high) | rebuttal quality | 8.18 | +0.83 | +1.33 | [+1.17, +1.48] | -0.29 |
| Gemini 3.7 Flash (high) | rebuttal quality | 6.64 | -0.71 | -1.30 | [-1.45, -1.15] | +0.04 |
| Mistral Large 3 | argument strength | 6.01 | -1.34 | -1.29 | [-1.99, -0.60] | +2.95 |
| GPT-OSS-120B | grounding and epistemic discipline | 5.94 | -1.35 | -1.28 | [-1.73, -0.83] | +0.42 |
| Kimi K3 | rebuttal quality | 8.19 | +0.84 | +1.27 | [+1.13, +1.41] | -0.47 |
| GPT-OSS-120B | argument strength | 6.16 | -1.19 | -1.22 | [-1.75, -0.69] | +1.27 |

## Interpretive Coverage

Behavior estimates inherit the benchmark's topic mix. Representative means representative of this judged bank, not of every real-world debate a user might care about.

- Question type: mixed 68.2% (466), normative 22.1% (151), empirical 9.7% (66).
- Geography scope: global 61.3% (419), mixed 23.4% (160), non-US 8.2% (56), US 7.0% (48).
- Domain: Law / regulation / courts 19.8% (135), Labor / education / social policy 17.9% (122), Media / culture / internet 16.3% (111), Macro / trade / industrial policy 15.8% (108), Health / bioethics 9.5% (65), Energy / climate / infrastructure 7.2% (49), Science / space / frontier tech 5.0% (34), Business / antitrust / market structure 4.1% (28).

## Factual Integrity Queue

1,100 specific or check-worthy transcript claims were selected for a separate open-book audit. No accuracy judgment is inferred from named entities, confidence, or missing internal claim IDs.

## Completed Annotation Layers

The companion model-card report now includes (1) judge-rationale salience tags, (2) blinded transcript behavior events, (3) paired side-swap integrity patterns, and (4) outcome links. Full-corpus estimates are kept separate from representative and diagnostic samples, which preserve selection provenance and help surface failure modes.

## Technical metadata

- Evaluation scope: `judge_judge_blend_glm53_coverage_20260904a__debate_all_templates`
