# Debater Behavior Model Cards

Analyzed with Claude Opus 5.5 (high) for the selected current-v-current corpus; response coverage is reported below.

Judge opinions and transcript behavior are shown separately. The configured analyst tags the stored judge rationales and the transcripts; a judge-panel consensus event requires matching tags from at least two judges on the same debate. Diagnostic subscore tables show actual 1–10 judge means, current-field deltas, within-judge opponent advantages with debate-clustered intervals, and side splits; these are secondary perceptions, not rating inputs. The consensus denominator includes every eligible annotated judge row, including rows where no event was tagged. Representative and diagnostic samples are reported separately from the full current corpus. Side assignments do not reveal model beliefs, and outcome links are associations rather than causal estimates.

Annotation response coverage: blind transcripts 560/562 (99.6%); side-swap comparisons 279/281 (99.3%); outcome links 560/562 (99.6%).
A valid zero-event, zero-pattern, or zero-link response counts as covered. At 100% coverage, the labeled sections partition the full eligible corpus and should be read together; the sample labels preserve how cases were selected and do not mean the analysis stops at a sample.

## Claude Fable 5.1 (high)

### Deterministic execution

- Coverage: 46 current-peer debates / 230 turns.
- Mean raw words per turn: 264.1; mean word-limit use: 92.2%.
- Deterministically clipped turns: 24.8%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 8.09 | 7.58 | +0.51 | +0.66 [+0.42, +0.90] | 8.14 | 8.04 | 46 debates / 138 judge rows |
| Rebuttal quality | 8.15 | 7.59 | +0.56 | +0.72 [+0.46, +0.97] | 8.06 | 8.25 | 46 debates / 138 judge rows |
| Grounding / epistemics | 7.85 | 7.53 | +0.32 | +0.21 [+0.07, +0.35] | 7.88 | 7.81 | 46 debates / 138 judge rows |
| Originality | 7.69 | 7.06 | +0.63 | +0.65 [+0.45, +0.85] | 7.62 | 7.75 | 46 debates / 138 judge rows |
| Rhetorical effectiveness | 8.43 | 7.80 | +0.64 | +0.64 [+0.46, +0.83] | 8.51 | 8.36 | 46 debates / 138 judge rows |

### Judge-panel consensus

- direct engagement: 102/138 judge rows (73.9%); 37/46 debates reached panel majority; mean rebuttal quality advantage +0.72.
- argument construction: 74/138 judge rows (53.6%); 24/46 debates reached panel majority; mean argument strength advantage +0.66.
- weighing: 37/138 judge rows (26.8%); 11/46 debates reached panel majority; mean argument strength advantage +0.66.
- format compliance: 35/138 judge rows (25.4%); 11/46 debates reached panel majority; mean rhetorical effectiveness advantage +0.64.
- burden handling: 31/138 judge rows (22.5%); 9/46 debates reached panel majority; mean argument strength advantage +0.66.
- question quality: 16/138 judge rows (11.6%); 2/46 debates reached panel majority; mean rebuttal quality advantage +0.72.
- evidence use: 15/138 judge rows (10.9%); 4/46 debates reached panel majority; mean grounding and epistemic discipline advantage +0.21.
- concession: 12/138 judge rows (8.7%); 1/46 debates reached panel majority; mean rebuttal quality advantage +0.72.

### Judge salience

- Full eligible corpus: 412 events across 137 event-bearing judge rows; direct engagement 102/137 (74%), argument construction 74/137 (54%), weighing 37/137 (27%), format compliance 33/137 (24%), burden handling 31/137 (23%), question quality 16/137 (12%).

- [all] The judge credited PRO with holding a comparative frame that CON could not get out of. Evidence: “maintaining a disciplined comparative frame that Side B never escaped”
- [all] PRO neutralized CON's macro trends by arguing they apply to both counterfactual worlds. Evidence: “Side A successfully argued that those macro trends apply to both worlds”

### Blind transcript observations

- Full eligible corpus: 512 events across 46 event-bearing debates; direct engagement 46/46 (100%), question type 46/46 (100%), weighing 36/46 (78%), answer type 35/46 (76%), confident specificity 28/46 (61%), burden contest 27/46 (59%).

- [all] PRO frames the motion as comparative and assigns CON a no-difference-or-worse burden, which CON then explicitly accepts. Evidence: “CON must argue that twenty extra years of legal building would have left prices unchanged or higher.”
- [all] PRO turns CON's skyline line into a concession that extra housing units would exist and absorb demand. Evidence: “Notice what CON already gave away: "Earlier legalization would have changed skylines."”

### Side-swap patterns

- Full eligible corpus: 109 events across 23 event-bearing groups; stable behavior 23/23 (100%), advocacy flexibility 20/23 (87%), contradiction candidate 15/23 (65%), side specific behavior 15/23 (65%), moral standard asymmetry 5/23 (22%), evidence asymmetry 5/23 (22%).

- [all] As PRO the model offered Houston among its showcase cities. As CON it said Houston home prices roughly doubled in a decade and called Houston a sprawl story rather than density evidence, so its Houston characterization warrants open-book review.
- [all] As PRO the model treated Austin's falling rents as a supply signal. As CON it attributed the same decline to a pandemic spike and an overbuilding cycle.

### Outcome associations

- Full eligible corpus: 275 links across 46 debates; aligned 46/46 (100%), judge_disagreement 22/46 (48%), conflicted 13/46 (28%), unclear 5/46 (11%).

## Kimi K3

### Deterministic execution

- Coverage: 300 current-peer debates / 1,500 turns.
- Mean raw words per turn: 248.8; mean word-limit use: 86.7%.
- Deterministically clipped turns: 5.5%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 8.03 | 7.58 | +0.45 | +0.78 [+0.66, +0.89] | 7.98 | 8.08 | 302 debates / 904 judge rows |
| Rebuttal quality | 8.12 | 7.59 | +0.53 | +0.98 [+0.83, +1.12] | 7.99 | 8.25 | 302 debates / 904 judge rows |
| Grounding / epistemics | 7.75 | 7.53 | +0.22 | +0.41 [+0.32, +0.51] | 7.69 | 7.81 | 302 debates / 904 judge rows |
| Originality | 7.48 | 7.06 | +0.42 | +0.62 [+0.52, +0.71] | 7.35 | 7.60 | 302 debates / 904 judge rows |
| Rhetorical effectiveness | 8.36 | 7.80 | +0.56 | +0.89 [+0.79, +0.98] | 8.36 | 8.36 | 302 debates / 904 judge rows |

### Judge-panel consensus

- direct engagement: 572/898 judge rows (63.7%); 203/300 debates reached panel majority; mean rebuttal quality advantage +0.97.
- argument construction: 434/898 judge rows (48.3%); 138/300 debates reached panel majority; mean argument strength advantage +0.77.
- weighing: 233/898 judge rows (25.9%); 53/300 debates reached panel majority; mean argument strength advantage +0.77.
- burden handling: 180/898 judge rows (20.0%); 39/300 debates reached panel majority; mean argument strength advantage +0.77.
- answer quality: 147/898 judge rows (16.4%); 29/300 debates reached panel majority; mean rebuttal quality advantage +0.97.
- question quality: 134/898 judge rows (14.9%); 21/300 debates reached panel majority; mean rebuttal quality advantage +0.97.
- evidence use: 101/898 judge rows (11.2%); 21/300 debates reached panel majority; mean grounding and epistemic discipline advantage +0.41.
- rhetoric: 98/898 judge rows (10.9%); 15/300 debates reached panel majority; mean rhetorical effectiveness advantage +0.88.

### Judge salience

- Full eligible corpus: 2454 events across 875 event-bearing judge rows; direct engagement 572/875 (65%), argument construction 433/875 (49%), weighing 232/875 (27%), burden handling 180/875 (21%), answer quality 143/875 (16%), question quality 133/875 (15%).

- [all] The judge praised CON's economic analysis of land values and macro headwinds. Evidence: “Side B offered excellent economic analysis on land values and macro headwinds”
- [all] CON's concessions about a Miami glut and a small price trim were used against it. Evidence: “By leveraging Side B's concessions about a Miami”

### Blind transcript observations

- Full eligible corpus: 3172 events across 300 event-bearing debates; direct engagement 298/300 (99%), question type 293/300 (98%), weighing 238/300 (79%), answer type 222/300 (74%), confident specificity 195/300 (65%), repetition 188/300 (63%).

- [all] CON accepts PRO's burden framing and claims it can meet it with a roughly-unchanged-prices expectation. Evidence: “The honest expectation is prices roughly unchanged for the median household — precisely the burden PRO insists I must meet”
- [all] CON offers confounders for each of PRO's showcase cities rather than contesting the supply mechanism in the abstract. Evidence: “Tokyo's flat prices followed the largest property crash in modern history and decades of deflation.”

### Side-swap patterns

- Full eligible corpus: 716 events across 149 event-bearing groups; stable behavior 147/149 (99%), advocacy flexibility 130/149 (87%), contradiction candidate 86/149 (58%), side specific behavior 79/149 (53%), evidence asymmetry 58/149 (39%), moral standard asymmetry 24/149 (16%).

- [all] As CON the model recast Austin's rent decline as mean reversion and explained Houston through outward sprawl. As PRO it presented Austin's falling rents and Houston as evidence that building lowers prices.
- [all] On both sides the model made concessions, either in punchy lines or in answers, which its opponent then turned into admissions, and its attempted walk-backs only partly recovered.

### Outcome associations

- Full eligible corpus: 1710 links across 300 debates; aligned 286/300 (95%), judge_disagreement 100/300 (33%), conflicted 73/300 (24%), unclear 51/300 (17%).

## Claude Opus 5.5 (high)

### Deterministic execution

- Coverage: 44 current-peer debates / 220 turns.
- Mean raw words per turn: 267.6; mean word-limit use: 92.6%.
- Deterministically clipped turns: 45.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.97 | 7.58 | +0.39 | +0.46 [+0.20, +0.73] | 7.83 | 8.11 | 44 debates / 132 judge rows |
| Rebuttal quality | 7.94 | 7.59 | +0.35 | +0.39 [+0.05, +0.73] | 7.74 | 8.14 | 44 debates / 132 judge rows |
| Grounding / epistemics | 7.80 | 7.53 | +0.27 | +0.17 [+0.00, +0.35] | 7.76 | 7.85 | 44 debates / 132 judge rows |
| Originality | 7.52 | 7.06 | +0.46 | +0.48 [+0.23, +0.72] | 7.38 | 7.67 | 44 debates / 132 judge rows |
| Rhetorical effectiveness | 8.12 | 7.80 | +0.32 | +0.33 [+0.05, +0.60] | 8.24 | 8.00 | 44 debates / 132 judge rows |

### Judge-panel consensus

- direct engagement: 75/132 judge rows (56.8%); 27/44 debates reached panel majority; mean rebuttal quality advantage +0.39.
- argument construction: 55/132 judge rows (41.7%); 17/44 debates reached panel majority; mean argument strength advantage +0.46.
- format compliance: 46/132 judge rows (34.8%); 13/44 debates reached panel majority; mean rhetorical effectiveness advantage +0.33.
- weighing: 43/132 judge rows (32.6%); 12/44 debates reached panel majority; mean argument strength advantage +0.46.
- burden handling: 33/132 judge rows (25.0%); 10/44 debates reached panel majority; mean argument strength advantage +0.46.
- question quality: 18/132 judge rows (13.6%); 3/44 debates reached panel majority; mean rebuttal quality advantage +0.39.
- concession: 17/132 judge rows (12.9%); 2/44 debates reached panel majority; mean rebuttal quality advantage +0.39.
- answer quality: 15/132 judge rows (11.4%); 1/44 debates reached panel majority; mean rebuttal quality advantage +0.39.

### Judge salience

- Full eligible corpus: 367 events across 127 event-bearing judge rows; direct engagement 75/127 (59%), argument construction 55/127 (43%), weighing 43/127 (34%), format compliance 42/127 (33%), burden handling 33/127 (26%), question quality 18/127 (14%).

- [all] PRO won the core clash by showing that personalization turns supposed discounts into disguised price hikes. Evidence: “profit-maximizing algorithms will inevitably use personalization to raise the baseline anchor”
- [all] PRO won the enforcement debate by showing that CON's standards depend on a benchmark that personalization eliminates. Evidence: “policing B's standards requires a public benchmark, which personalization destroys”

### Blind transcript observations

- Full eligible corpus: 484 events across 44 event-bearing debates; direct engagement 44/44 (100%), question type 44/44 (100%), weighing 34/44 (77%), answer type 31/44 (70%), confident specificity 29/44 (66%), burden contest 26/44 (59%).

- [all] PRO narrows the motion's scope by listing pricing practices that would survive the ban. Evidence: “Not sales, not coupons anyone can use, not student discounts, not prices that rise when stock runs low.”
- [all] PRO argues that CON's inventory example can be achieved through open markdowns, so profiling adds only harm. Evidence: “The benefit CON wants is available without profiling. The harm I described is impossible without it.”

### Side-swap patterns

- Full eligible corpus: 113 events across 22 event-bearing groups; advocacy flexibility 22/22 (100%), stable behavior 22/22 (100%), side specific behavior 13/22 (59%), contradiction candidate 12/22 (55%), evidence asymmetry 11/22 (50%), tradeoff hiding 3/22 (14%).

- [all] As PRO the model claimed personalization destroys any public price benchmark and that discounts cannot be separated from surcharges, while as CON it proposed a posted-price regime that allows only below-benchmark personalized prices and said this restores comparison; this cross-side tension merits open-book review.
- [all] On enforceability, the model argued as PRO that a ban is simple to police and that CON's auditing standard was undefined, but as CON it offered an outcome-based receipt audit and argued that the ban itself requires difficult model reconstruction.

### Outcome associations

- Full eligible corpus: 256 links across 44 debates; aligned 43/44 (98%), judge_disagreement 16/44 (36%), conflicted 15/44 (34%), unclear 5/44 (11%).

## Gemini 4 Argon (high)

### Deterministic execution

- Coverage: 40 current-peer debates / 200 turns.
- Mean raw words per turn: 241.0; mean word-limit use: 84.6%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.62 | 7.58 | +0.03 | +0.10 [-0.13, +0.33] | 7.63 | 7.60 | 40 debates / 120 judge rows |
| Rebuttal quality | 7.64 | 7.59 | +0.05 | +0.13 [-0.20, +0.46] | 7.52 | 7.77 | 40 debates / 120 judge rows |
| Grounding / epistemics | 7.42 | 7.53 | -0.12 | -0.16 [-0.31, -0.01] | 7.37 | 7.47 | 40 debates / 120 judge rows |
| Originality | 7.02 | 7.06 | -0.05 | -0.01 [-0.23, +0.22] | 6.83 | 7.20 | 40 debates / 120 judge rows |
| Rhetorical effectiveness | 7.76 | 7.80 | -0.04 | +0.02 [-0.24, +0.29] | 7.87 | 7.65 | 40 debates / 120 judge rows |

### Judge-panel consensus

- direct engagement: 68/120 judge rows (56.7%); 24/40 debates reached panel majority; mean rebuttal quality advantage +0.13.
- argument construction: 64/120 judge rows (53.3%); 21/40 debates reached panel majority; mean argument strength advantage +0.10.
- weighing: 23/120 judge rows (19.2%); 6/40 debates reached panel majority; mean argument strength advantage +0.10.
- burden handling: 21/120 judge rows (17.5%); 1/40 debates reached panel majority; mean argument strength advantage +0.10.
- dropped argument: 20/120 judge rows (16.7%); 5/40 debates reached panel majority; mean rebuttal quality advantage +0.13.
- concession: 17/120 judge rows (14.2%); 4/40 debates reached panel majority; mean rebuttal quality advantage +0.13.
- question quality: 15/120 judge rows (12.5%); 2/40 debates reached panel majority; mean rebuttal quality advantage +0.13.
- answer quality: 13/120 judge rows (10.8%); 3/40 debates reached panel majority; mean rebuttal quality advantage +0.13.

### Judge salience

- Full eligible corpus: 321 events across 119 event-bearing judge rows; direct engagement 68/119 (57%), argument construction 64/119 (54%), weighing 23/119 (19%), burden handling 21/119 (18%), dropped argument 20/119 (17%), concession 17/119 (14%).

- [all] PRO's pressure question forced the pivotal concession from CON. Evidence: “A's pressure question forcing B to concede”
- [all] PRO's closing directly exploited CON's concession. Evidence: “A's closing exploited this directly”

### Blind transcript observations

- Full eligible corpus: 404 events across 40 event-bearing debates; direct engagement 40/40 (100%), question type 40/40 (100%), answer type 32/40 (80%), confident specificity 24/40 (60%), repetition 23/40 (57%), burden contest 17/40 (42%).

- [all] PRO uses the motion's conditional trigger to argue that CON's alternatives fall outside the cases the motion covers. Evidence: “the motion explicitly applies *when* historic protections block needed density; where gentle infill suffices, the trigger isn't met.”
- [all] PRO answers the stalled-project risk with a permit condition, but this addresses only one of CON's uncertainty points. Evidence: “cities can easily condition demolition permits on approved, financed replacement projects, eliminating CON’s bogeyman of "a profitable demolition and a stalled project"”

### Side-swap patterns

- Full eligible corpus: 95 events across 20 event-bearing groups; stable behavior 18/20 (90%), contradiction candidate 17/20 (85%), side specific behavior 16/20 (80%), advocacy flexibility 15/20 (75%), evidence asymmetry 5/20 (25%), moral standard asymmetry 4/20 (20%).

- [all] On both sides, Gemini made confident, load-bearing empirical or categorical claims without support, about carbon offsets as PRO and about land availability and why alternatives fail as CON.
- [all] On both sides, Gemini tended to overstate what the opponent had conceded or to caricature the opponent's standard, rather than engage the opponent's actual bounded position.

### Outcome associations

- Full eligible corpus: 212 links across 40 debates; aligned 39/40 (98%), judge_disagreement 18/40 (45%), conflicted 14/40 (35%), unclear 9/40 (22%).

## Muse Wonder 1.0 (high)

### Deterministic execution

- Coverage: 40 current-peer debates / 200 turns.
- Mean raw words per turn: 244.0; mean word-limit use: 84.0%.
- Deterministically clipped turns: 1.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.81 | 7.58 | +0.23 | -0.12 [-0.39, +0.16] | 7.67 | 7.95 | 40 debates / 120 judge rows |
| Rebuttal quality | 7.86 | 7.59 | +0.27 | -0.10 [-0.44, +0.24] | 7.67 | 8.05 | 40 debates / 120 judge rows |
| Grounding / epistemics | 7.91 | 7.53 | +0.38 | +0.06 [-0.11, +0.23] | 7.88 | 7.93 | 40 debates / 120 judge rows |
| Originality | 7.30 | 7.06 | +0.24 | -0.09 [-0.30, +0.12] | 7.15 | 7.45 | 40 debates / 120 judge rows |
| Rhetorical effectiveness | 8.14 | 7.80 | +0.34 | +0.04 [-0.22, +0.30] | 8.17 | 8.12 | 40 debates / 120 judge rows |

### Judge-panel consensus

- argument construction: 59/118 judge rows (50.0%); 19/40 debates reached panel majority; mean argument strength advantage -0.12.
- direct engagement: 57/118 judge rows (48.3%); 21/40 debates reached panel majority; mean rebuttal quality advantage -0.10.
- concession: 22/118 judge rows (18.6%); 7/40 debates reached panel majority; mean rebuttal quality advantage -0.10.
- answer quality: 22/118 judge rows (18.6%); 4/40 debates reached panel majority; mean rebuttal quality advantage -0.10.
- weighing: 19/118 judge rows (16.1%); 4/40 debates reached panel majority; mean argument strength advantage -0.12.
- dropped argument: 13/118 judge rows (11.0%); 1/40 debates reached panel majority; mean rebuttal quality advantage -0.10.
- question quality: 13/118 judge rows (11.0%); 1/40 debates reached panel majority; mean rebuttal quality advantage -0.10.
- burden handling: 11/118 judge rows (9.3%); 0/40 debates reached panel majority; mean argument strength advantage -0.12.

### Judge salience

- Full eligible corpus: 257 events across 109 event-bearing judge rows; argument construction 58/109 (53%), direct engagement 57/109 (52%), answer quality 22/109 (20%), concession 22/109 (20%), weighing 19/109 (17%), dropped argument 13/109 (12%).

- [all] The judge found CON's alternative of banning sensitive segments impossible to audit. Evidence: “Side A's proposed "sensitive segment" ban would be impossible to audit”
- [all] The judge decided for CON because it showed PRO's ban was both overinclusive and porous. Evidence: “showing that Side B's categorical mechanism ban was both overinclusive and porous”

### Blind transcript observations

- Full eligible corpus: 368 events across 40 event-bearing debates; direct engagement 40/40 (100%), question type 39/40 (98%), answer type 34/40 (85%), weighing 34/40 (85%), burden setting 19/40 (48%), strategic concession 17/40 (42%).

- [all] CON concedes that some targeting harms deserve regulation and offers an alternative; PRO later uses this as both an age-knowledge turn and a principle concession. Evidence: “Abusive practices deserve hard rules: no targeting based on health or insecurity, short data retention, clear labels, and real parental controls.”
- [all] CON poses a dilemma against PRO's contextual exception, and this becomes the central clash for the rest of the debate. Evidence: “If contextual means matching the feed she built, it is behaviour by another name; if it means ignoring that feed, it is the generic noise they claim to avoid.”

### Side-swap patterns

- Full eligible corpus: 87 events across 20 event-bearing groups; advocacy flexibility 19/20 (95%), stable behavior 19/20 (95%), side specific behavior 16/20 (80%), contradiction candidate 6/20 (30%), evidence asymmetry 6/20 (30%), moral standard asymmetry 5/20 (25%).

- [all] As CON, muse-wonder-1.0-high said auditors could enforce category rules by inspecting purchased data categories and segments, while as PRO it said interest and vulnerability inferences cannot be separated within one profile, which leaves a feasibility tension for open-book review.
- [all] As CON, muse-wonder-1.0-high argued that contextual matching in a personalized feed is behavioural targeting by another name, while as PRO it relied on contextual advertising as the clean permitted alternative.

### Outcome associations

- Full eligible corpus: 210 links across 40 debates; aligned 39/40 (98%), judge_disagreement 19/40 (48%), conflicted 11/40 (28%), unclear 6/40 (15%).

## GPT-5.6 Sol (high)

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 250.5; mean word-limit use: 85.4%.
- Deterministically clipped turns: 13.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.57 | 7.58 | -0.02 | -0.23 [-0.61, +0.14] | 7.53 | 7.60 | 20 debates / 60 judge rows |
| Rebuttal quality | 7.57 | 7.59 | -0.02 | -0.27 [-0.66, +0.13] | 7.47 | 7.67 | 20 debates / 60 judge rows |
| Grounding / epistemics | 7.72 | 7.53 | +0.18 | -0.00 [-0.16, +0.16] | 7.77 | 7.67 | 20 debates / 60 judge rows |
| Originality | 6.87 | 7.06 | -0.20 | -0.43 [-0.73, -0.14] | 6.90 | 6.83 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 7.52 | 7.80 | -0.28 | -0.50 [-0.84, -0.16] | 7.60 | 7.43 | 20 debates / 60 judge rows |

### Judge-panel consensus

- argument construction: 32/60 judge rows (53.3%); 10/20 debates reached panel majority; mean argument strength advantage -0.23.
- direct engagement: 21/60 judge rows (35.0%); 7/20 debates reached panel majority; mean rebuttal quality advantage -0.27.
- burden handling: 16/60 judge rows (26.7%); 5/20 debates reached panel majority; mean argument strength advantage -0.23.
- concession: 16/60 judge rows (26.7%); 2/20 debates reached panel majority; mean rebuttal quality advantage -0.27.
- format compliance: 15/60 judge rows (25.0%); 4/20 debates reached panel majority; mean rhetorical effectiveness advantage -0.50.
- answer quality: 8/60 judge rows (13.3%); 1/20 debates reached panel majority; mean rebuttal quality advantage -0.27.
- dropped argument: 8/60 judge rows (13.3%); 1/20 debates reached panel majority; mean rebuttal quality advantage -0.27.
- weighing: 8/60 judge rows (13.3%); 1/20 debates reached panel majority; mean argument strength advantage -0.23.

### Judge salience

- Full eligible corpus: 147 events across 58 event-bearing judge rows; argument construction 30/58 (52%), direct engagement 21/58 (36%), burden handling 16/58 (28%), concession 15/58 (26%), format compliance 9/58 (16%), weighing 8/58 (14%).

- [all] The judge identified PRO's acceptance that survivor-enforceable confidentiality would be lost as a damaging concession. Evidence: “conceded exactly what CON's pressure question targeted”
- [all] The judge noted PRO's admission that unenforceability does not guarantee disclosure. Evidence: “PRO itself admitted unenforceability”

### Blind transcript observations

- Full eligible corpus: 182 events across 20 event-bearing debates; direct engagement 20/20 (100%), question type 19/20 (95%), weighing 17/20 (85%), answer type 15/20 (75%), burden setting 11/20 (55%), burden contest 11/20 (55%).

- [all] PRO uses a concrete scenario to show how NDAs fragment patterns of repeat misconduct, and this becomes its core externality argument. Evidence: “Imagine three employees separately reporting the same manager. If each is paid on condition of silence, every later employee enters without crucial information, each complaint appears isolated”
- [all] PRO argues in advance against procedural-safeguard alternatives before CON raises them. Evidence: “Unenforceability is the right remedy because merely requiring “voluntary” or “clear” consent leaves the same structural coercion intact and forces victims to litigate the gag before they can challenge it.”

### Side-swap patterns

- Full eligible corpus: 43 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 10/10 (100%), side specific behavior 7/10 (70%), contradiction candidate 3/10 (30%), moral standard asymmetry 1/10 (10%), tradeoff hiding 1/10 (10%).

- [all] On both sides, gpt-5.6-high answers the opponent's specific frames directly and offers explicit comparative weighing or burden arguments.
- [all] As PRO, gpt-5.6-high concedes that settlement value would shrink and treats consent safeguards as inadequate; as CON, it presents the same shrinkage concession as the opponent's key weakness and defends informed, voluntary agreements with safeguards.

### Outcome associations

- Full eligible corpus: 93 links across 20 debates; aligned 19/20 (95%), conflicted 10/20 (50%), judge_disagreement 8/20 (40%), unclear 6/20 (30%).

## GLM-5.3 (high)

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 256.2; mean word-limit use: 88.8%.
- Deterministically clipped turns: 21.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.50 | 7.58 | -0.08 | -0.43 [-0.82, -0.05] | 7.20 | 7.80 | 20 debates / 60 judge rows |
| Rebuttal quality | 7.52 | 7.59 | -0.07 | -0.47 [-0.98, +0.05] | 7.07 | 7.97 | 20 debates / 60 judge rows |
| Grounding / epistemics | 7.65 | 7.53 | +0.12 | -0.33 [-0.56, -0.11] | 7.40 | 7.90 | 20 debates / 60 judge rows |
| Originality | 7.18 | 7.06 | +0.12 | -0.10 [-0.42, +0.22] | 6.97 | 7.40 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 7.93 | 7.80 | +0.14 | -0.05 [-0.41, +0.31] | 7.80 | 8.07 | 20 debates / 60 judge rows |

### Judge-panel consensus

- argument construction: 25/60 judge rows (41.7%); 9/20 debates reached panel majority; mean argument strength advantage -0.43.
- direct engagement: 24/60 judge rows (40.0%); 7/20 debates reached panel majority; mean rebuttal quality advantage -0.47.
- burden handling: 17/60 judge rows (28.3%); 5/20 debates reached panel majority; mean argument strength advantage -0.43.
- weighing: 15/60 judge rows (25.0%); 2/20 debates reached panel majority; mean argument strength advantage -0.43.
- format compliance: 14/60 judge rows (23.3%); 5/20 debates reached panel majority; mean rhetorical effectiveness advantage -0.05.
- concession: 8/60 judge rows (13.3%); 2/20 debates reached panel majority; mean rebuttal quality advantage -0.47.
- answer quality: 8/60 judge rows (13.3%); 1/20 debates reached panel majority; mean rebuttal quality advantage -0.47.
- dropped argument: 7/60 judge rows (11.7%); 1/20 debates reached panel majority; mean rebuttal quality advantage -0.47.

### Judge salience

- Full eligible corpus: 147 events across 56 event-bearing judge rows; argument construction 25/56 (45%), direct engagement 24/56 (43%), burden handling 17/56 (30%), weighing 15/56 (27%), format compliance 13/56 (23%), concession 8/56 (14%).

- [all] The judge found PRO's retreat to a cost-recovery justification damaging, and noted that CON exploited it. Evidence: “PRO's A1 answer explicitly retreated from the opening's deterrence/pedestrian-death framing to "cost recovery alone justifies it,"”
- [all] The judge penalized PRO because its Rebuttal 2 was clipped. Evidence: “PRO's Rebuttal 2 was also clipped before its closing synthesis, a real execution cost”

### Blind transcript observations

- Full eligible corpus: 202 events across 20 event-bearing debates; direct engagement 20/20 (100%), question type 20/20 (100%), weighing 16/20 (80%), burden setting 13/20 (65%), answer type 13/20 (65%), rhetorical function 12/20 (60%).

- [all] PRO frames the motion as a modest extension of existing pricing practice, which lowers its burden. Evidence: “The proposition simply asks cities to finish a pricing logic they already accept.”
- [all] PRO gives a concrete physical mechanism for the safety externality. Evidence: “Pedestrian struck by a taller, heavier vehicle is hit higher on the body—chest and head instead of legs—and carries far more kinetic energy at the same speed.”

### Side-swap patterns

- Full eligible corpus: 47 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 8/10 (80%), side specific behavior 7/10 (70%), contradiction candidate 7/10 (70%), evidence asymmetry 3/10 (30%), moral standard asymmetry 2/10 (20%).

- [all] As PRO, glm-5-3-high argued that size is the cost itself, while as CON it argued that the motion's vehicle-category label departs from measured cost, using the sedan-versus-pickup question to press the point.
- [all] As PRO, glm-5-3-high declined to give a fee figure and fell back on cost recovery; as CON, it posed its own fee-magnitude dilemma and a binary question that forced PRO to commit.

### Outcome associations

- Full eligible corpus: 100 links across 20 debates; aligned 16/20 (80%), judge_disagreement 9/20 (45%), conflicted 8/20 (40%), unclear 4/20 (20%).

## Grok 4.7 (high)

### Deterministic execution

- Coverage: 18 current-peer debates / 90 turns.
- Mean raw words per turn: 247.3; mean word-limit use: 84.9%.
- Deterministically clipped turns: 12.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.48 | 7.58 | -0.10 | -0.50 [-0.90, -0.10] | 7.30 | 7.67 | 18 debates / 54 judge rows |
| Rebuttal quality | 7.56 | 7.59 | -0.03 | -0.57 [-1.09, -0.06] | 7.22 | 7.89 | 18 debates / 54 judge rows |
| Grounding / epistemics | 7.70 | 7.53 | +0.17 | -0.11 [-0.37, +0.15] | 7.63 | 7.78 | 18 debates / 54 judge rows |
| Originality | 7.31 | 7.06 | +0.25 | -0.24 [-0.60, +0.12] | 7.04 | 7.59 | 18 debates / 54 judge rows |
| Rhetorical effectiveness | 8.07 | 7.80 | +0.28 | -0.11 [-0.53, +0.31] | 8.04 | 8.11 | 18 debates / 54 judge rows |

### Judge-panel consensus

- argument construction: 30/54 judge rows (55.6%); 10/18 debates reached panel majority; mean argument strength advantage -0.50.
- direct engagement: 23/54 judge rows (42.6%); 5/18 debates reached panel majority; mean rebuttal quality advantage -0.57.
- concession: 11/54 judge rows (20.4%); 2/18 debates reached panel majority; mean rebuttal quality advantage -0.57.
- answer quality: 7/54 judge rows (13.0%); 2/18 debates reached panel majority; mean rebuttal quality advantage -0.57.
- format compliance: 7/54 judge rows (13.0%); 2/18 debates reached panel majority; mean rhetorical effectiveness advantage -0.11.
- weighing: 7/54 judge rows (13.0%); 2/18 debates reached panel majority; mean argument strength advantage -0.50.
- burden handling: 7/54 judge rows (13.0%); 0/18 debates reached panel majority; mean argument strength advantage -0.50.
- question quality: 5/54 judge rows (9.3%); 1/18 debates reached panel majority; mean rebuttal quality advantage -0.57.

### Judge salience

- Full eligible corpus: 113 events across 51 event-bearing judge rows; argument construction 30/51 (59%), direct engagement 22/51 (43%), concession 11/51 (22%), burden handling 7/51 (14%), weighing 7/51 (14%), answer quality 6/51 (12%).

- [all] The judge noted that PRO dropped CON's whisper-coaching analogy. Evidence: “completely dropped Side A's strong analogy to call center 'whisper coaching' and continuous recording”
- [all] The judge noted that PRO left CON's call-recording analogy unanswered. Evidence: “the unanswered call-recording/whisper-coaching analogy for governed continuity”

### Blind transcript observations

- Full eligible corpus: 162 events across 18 event-bearing debates; question type 18/18 (100%), answer type 18/18 (100%), direct engagement 17/18 (94%), repetition 15/18 (83%), burden setting 9/18 (50%), strategic concession 9/18 (50%).

- [all] PRO frames the motion around compulsion and continuity, which lets it keep voluntary tools outside its burden. Evidence: “The issue is compulsory, continuous oversight, not technology as such.”
- [all] PRO answers the "proves too much" objection by separating discrete job terms from continuous presence. Evidence: “Timesheets, quotas, and background checks demand discrete compliance. They do not sit inside attention from clock-in to clock-out”

### Side-swap patterns

- Full eligible corpus: 46 events across 9 event-bearing groups; stable behavior 9/9 (100%), side specific behavior 9/9 (100%), advocacy flexibility 7/9 (78%), evidence asymmetry 4/9 (44%), moral standard asymmetry 4/9 (44%), contradiction candidate 3/9 (33%).

- [all] As PRO, grok-4.7-high read purpose-based exemptions for checklists and safety alerts into the motion; as CON, it pressed PRO to find such exclusions in the motion's actual wording.
- [all] As PRO, grok-4.7-high did not address the floor-supervisor and whisper-coaching examples of continuous required oversight; as CON, it used a floor supervisor coaching "from open to close" as its own counterexample.

### Outcome associations

- Full eligible corpus: 89 links across 18 debates; aligned 17/18 (94%), conflicted 10/18 (56%), judge_disagreement 10/18 (56%), unclear 3/18 (17%).

## Kimi K3.1 Pro (high)

### Deterministic execution

- Coverage: 298 current-peer debates / 1,490 turns.
- Mean raw words per turn: 253.5; mean word-limit use: 86.4%.
- Deterministically clipped turns: 25.8%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.61 | 7.58 | +0.02 | +0.13 [-0.02, +0.27] | 7.55 | 7.67 | 298 debates / 894 judge rows |
| Rebuttal quality | 7.72 | 7.59 | +0.14 | +0.31 [+0.14, +0.49] | 7.58 | 7.87 | 298 debates / 894 judge rows |
| Grounding / epistemics | 7.69 | 7.53 | +0.16 | +0.31 [+0.19, +0.42] | 7.64 | 7.74 | 298 debates / 894 judge rows |
| Originality | 7.00 | 7.06 | -0.06 | +0.06 [-0.05, +0.17] | 6.90 | 7.10 | 298 debates / 894 judge rows |
| Rhetorical effectiveness | 7.58 | 7.80 | -0.22 | -0.23 [-0.36, -0.10] | 7.68 | 7.49 | 298 debates / 894 judge rows |

### Judge-panel consensus

- direct engagement: 497/890 judge rows (55.8%); 172/298 debates reached panel majority; mean rebuttal quality advantage +0.31.
- argument construction: 465/890 judge rows (52.2%); 158/298 debates reached panel majority; mean argument strength advantage +0.12.
- format compliance: 307/890 judge rows (34.5%); 100/298 debates reached panel majority; mean rhetorical effectiveness advantage -0.23.
- concession: 212/890 judge rows (23.8%); 61/298 debates reached panel majority; mean rebuttal quality advantage +0.31.
- burden handling: 196/890 judge rows (22.0%); 42/298 debates reached panel majority; mean argument strength advantage +0.12.
- weighing: 167/890 judge rows (18.8%); 35/298 debates reached panel majority; mean argument strength advantage +0.12.
- answer quality: 155/890 judge rows (17.4%); 33/298 debates reached panel majority; mean rebuttal quality advantage +0.31.
- question quality: 74/890 judge rows (8.3%); 10/298 debates reached panel majority; mean rebuttal quality advantage +0.31.

### Judge salience

- Full eligible corpus: 2402 events across 866 event-bearing judge rows; direct engagement 495/866 (57%), argument construction 464/866 (54%), format compliance 281/866 (32%), concession 211/866 (24%), burden handling 196/866 (23%), weighing 166/866 (19%).

- [all] CON's concession was seen as granting the motion's normative core. Evidence: “That concession effectively granted the normative core of the motion”
- [all] CON's burden-of-proof distinction was defensible but did not escape its concession. Evidence: “a defensible distinction but never fully escapes having conceded”

### Blind transcript observations

- Full eligible corpus: 2868 events across 298 event-bearing debates; direct engagement 295/298 (99%), question type 292/298 (98%), weighing 242/298 (81%), burden setting 212/298 (71%), answer type 212/298 (71%), strategic concession 193/298 (65%).

- [all] CON frames the clash as a certain irreversible loss weighed against benefits that are speculative and achievable by other means. Evidence: “PRO asks cities to trade a certain, permanent loss for benefits that are neither guaranteed nor unique to that trade.”
- [all] CON responds that PRO's trigger presupposes necessity, which PRO has not shown. Evidence: “assumes what must be proved: that the proposal is needed, rather than merely profitable, and that sacrifice is necessary.”

### Side-swap patterns

- Full eligible corpus: 577 events across 148 event-bearing groups; stable behavior 146/148 (99%), advocacy flexibility 133/148 (90%), side specific behavior 71/148 (48%), evidence asymmetry 25/148 (17%), moral standard asymmetry 23/148 (16%), contradiction candidate 21/148 (14%).

- [all] On both sides, Kimi pressed for concrete operational tests and separated surface claims from the necessity or deliverability actually at issue.
- [all] On both sides, Kimi made limited strategic concessions and answered forked questions directly, granting the narrow point while contesting its broader significance.

### Outcome associations

- Full eligible corpus: 1621 links across 298 debates; aligned 283/298 (95%), judge_disagreement 116/298 (39%), conflicted 101/298 (34%), unclear 54/298 (18%).

## GPT-6 Astra (high)

### Deterministic execution

- Coverage: 18 current-peer debates / 90 turns.
- Mean raw words per turn: 241.8; mean word-limit use: 82.6%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.37 | 7.58 | -0.21 | -0.43 [-0.87, +0.02] | 7.41 | 7.33 | 18 debates / 54 judge rows |
| Rebuttal quality | 7.41 | 7.59 | -0.18 | -0.33 [-0.89, +0.23] | 7.30 | 7.52 | 18 debates / 54 judge rows |
| Grounding / epistemics | 7.70 | 7.53 | +0.17 | +0.07 [-0.17, +0.32] | 7.67 | 7.74 | 18 debates / 54 judge rows |
| Originality | 6.83 | 7.06 | -0.23 | -0.31 [-0.70, +0.07] | 6.59 | 7.07 | 18 debates / 54 judge rows |
| Rhetorical effectiveness | 7.28 | 7.80 | -0.52 | -0.52 [-0.95, -0.09] | 7.30 | 7.26 | 18 debates / 54 judge rows |

### Judge-panel consensus

- argument construction: 30/54 judge rows (55.6%); 10/18 debates reached panel majority; mean argument strength advantage -0.43.
- direct engagement: 26/54 judge rows (48.1%); 8/18 debates reached panel majority; mean rebuttal quality advantage -0.33.
- burden handling: 16/54 judge rows (29.6%); 4/18 debates reached panel majority; mean argument strength advantage -0.43.
- concession: 15/54 judge rows (27.8%); 3/18 debates reached panel majority; mean rebuttal quality advantage -0.33.
- answer quality: 8/54 judge rows (14.8%); 1/18 debates reached panel majority; mean rebuttal quality advantage -0.33.
- weighing: 7/54 judge rows (13.0%); 2/18 debates reached panel majority; mean argument strength advantage -0.43.
- question quality: 6/54 judge rows (11.1%); 0/18 debates reached panel majority; mean rebuttal quality advantage -0.33.
- evidence use: 4/54 judge rows (7.4%); 1/18 debates reached panel majority; mean grounding and epistemic discipline advantage +0.07.

### Judge salience

- Full eligible corpus: 133 events across 50 event-bearing judge rows; argument construction 30/50 (60%), direct engagement 26/50 (52%), burden handling 16/50 (32%), concession 15/50 (30%), answer quality 8/50 (16%), weighing 7/50 (14%).

- [all] The judge called PRO's principled point strong, but it was outweighed by CON's practical argument. Evidence: “Side A made a strong principled argument that objection does not equal sabotage”
- [all] The judge found PRO's concessions collapsed into CON's cooperation-first standard. Evidence: “its concessions - pause if unviable, cancel if livelihoods cannot be protected - collapse into A's cooperation-first standard”

### Blind transcript observations

- Full eligible corpus: 169 events across 18 event-bearing debates; question type 18/18 (100%), direct engagement 18/18 (100%), strategic concession 15/18 (83%), burden contest 12/18 (67%), weighing 12/18 (67%), burden setting 11/18 (61%).

- [all] PRO frames the debate as protection versus veto, which sets the standard it applies for the rest of the debate. Evidence: “people facing concentrated costs deserve protection and compensation, but not an unconditional veto over ecological recovery”
- [all] PRO tries to place on CON the burden of proving that cooperation requires a veto, and CON explicitly contests this. Evidence: “CON must show that meaningful participation is impossible without a power to stop reintroduction.”

### Side-swap patterns

- Full eligible corpus: 33 events across 9 event-bearing groups; stable behavior 9/9 (100%), advocacy flexibility 7/9 (78%), side specific behavior 6/9 (67%), contradiction candidate 1/9 (11%), evidence asymmetry 1/9 (11%).

- [all] On both sides, gpt-6-astra-high answered opponents by drawing fine conceptual distinctions and by flagging opposing empirical premises as unsupported assumptions.
- [all] On both sides, gpt-6-astra-high made bounded concessions to narrow its claim, then limited how far opponents could use them.

### Outcome associations

- Full eligible corpus: 94 links across 18 debates; aligned 17/18 (94%), conflicted 11/18 (61%), judge_disagreement 4/18 (22%), unclear 3/18 (17%).

## Xiaomi MiMo V2.6 Pro (thinking)

### Deterministic execution

- Coverage: 16 current-peer debates / 80 turns.
- Mean raw words per turn: 270.5; mean word-limit use: 93.6%.
- Deterministically clipped turns: 42.5%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.46 | 7.58 | -0.12 | -0.42 [-0.95, +0.11] | 7.33 | 7.58 | 16 debates / 48 judge rows |
| Rebuttal quality | 7.44 | 7.59 | -0.15 | -0.52 [-1.20, +0.15] | 7.25 | 7.62 | 16 debates / 48 judge rows |
| Grounding / epistemics | 7.60 | 7.53 | +0.07 | -0.25 [-0.62, +0.12] | 7.54 | 7.67 | 16 debates / 48 judge rows |
| Originality | 7.19 | 7.06 | +0.13 | -0.04 [-0.43, +0.35] | 7.00 | 7.38 | 16 debates / 48 judge rows |
| Rhetorical effectiveness | 7.77 | 7.80 | -0.03 | -0.19 [-0.64, +0.26] | 7.71 | 7.83 | 16 debates / 48 judge rows |

### Judge-panel consensus

- argument construction: 23/48 judge rows (47.9%); 8/16 debates reached panel majority; mean argument strength advantage -0.42.
- format compliance: 22/48 judge rows (45.8%); 7/16 debates reached panel majority; mean rhetorical effectiveness advantage -0.19.
- direct engagement: 21/48 judge rows (43.8%); 6/16 debates reached panel majority; mean rebuttal quality advantage -0.52.
- burden handling: 14/48 judge rows (29.2%); 4/16 debates reached panel majority; mean argument strength advantage -0.42.
- concession: 10/48 judge rows (20.8%); 3/16 debates reached panel majority; mean rebuttal quality advantage -0.52.
- weighing: 7/48 judge rows (14.6%); 2/16 debates reached panel majority; mean argument strength advantage -0.42.
- dropped argument: 7/48 judge rows (14.6%); 1/16 debates reached panel majority; mean rebuttal quality advantage -0.52.
- answer quality: 5/48 judge rows (10.4%); 0/16 debates reached panel majority; mean rebuttal quality advantage -0.52.

### Judge salience

- Full eligible corpus: 121 events across 48 event-bearing judge rows; argument construction 23/48 (48%), direct engagement 21/48 (44%), format compliance 19/48 (40%), burden handling 14/48 (29%), concession 10/48 (21%), dropped argument 7/48 (15%).

- [all] The judge acknowledged CON's compelling distinction between tradition and commercial excess. Evidence: “Side A compellingly distinguished tradition from commercial excess”
- [all] The judge faulted CON for not showing why communal recognition requires a form the couple did not choose. Evidence: “never established why recognition requires a form the couple did not choose”

### Blind transcript observations

- Full eligible corpus: 162 events across 16 event-bearing debates; direct engagement 16/16 (100%), question type 15/16 (94%), weighing 12/16 (75%), burden contest 10/16 (62%), confident specificity 10/16 (62%), answer type 9/16 (56%).

- [all] CON contests the inference from costly, performative weddings to reduced obligation, separating PRO's diagnosis from PRO's conclusion. Evidence: “The proposition contains a bait and switch.”
- [all] This vivid closer reduces PRO's case to escaping a vendor bill, although PRO's opening also raised performance and coercion concerns. Evidence: “PRO would burn that inheritance to escape a caterer's invoice.”

### Side-swap patterns

- Full eligible corpus: 39 events across 8 event-bearing groups; stable behavior 8/8 (100%), side specific behavior 7/8 (88%), advocacy flexibility 7/8 (88%), contradiction candidate 5/8 (62%), evidence asymmetry 3/8 (38%), moral standard asymmetry 1/8 (12%).

- [all] On both sides, mimo tended to overstate or simplify the opponent's position or the state of the exchange, for example by describing PRO's case as condemning all demands, framing a CON line as a concession, and calling a question unanswered too early.
- [all] On both sides, mimo used sharp, concrete questions that pressed the opponent to give a vague obligation specific content.

### Outcome associations

- Full eligible corpus: 73 links across 16 debates; aligned 15/16 (94%), conflicted 10/16 (62%), judge_disagreement 6/16 (38%), unclear 2/16 (12%).

## Claude Sonnet 5 (high)

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 247.7; mean word-limit use: 85.9%.
- Deterministically clipped turns: 11.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.55 | 7.58 | -0.03 | -0.38 [-0.68, -0.08] | 7.60 | 7.50 | 20 debates / 60 judge rows |
| Rebuttal quality | 7.58 | 7.59 | -0.00 | -0.40 [-0.84, +0.04] | 7.43 | 7.73 | 20 debates / 60 judge rows |
| Grounding / epistemics | 7.78 | 7.53 | +0.25 | -0.22 [-0.46, +0.03] | 7.83 | 7.73 | 20 debates / 60 judge rows |
| Originality | 7.13 | 7.06 | +0.07 | -0.22 [-0.60, +0.17] | 6.97 | 7.30 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 7.87 | 7.80 | +0.07 | -0.18 [-0.54, +0.17] | 7.93 | 7.80 | 20 debates / 60 judge rows |

### Judge-panel consensus

- direct engagement: 25/60 judge rows (41.7%); 6/20 debates reached panel majority; mean rebuttal quality advantage -0.40.
- argument construction: 24/60 judge rows (40.0%); 5/20 debates reached panel majority; mean argument strength advantage -0.38.
- concession: 20/60 judge rows (33.3%); 5/20 debates reached panel majority; mean rebuttal quality advantage -0.40.
- weighing: 14/60 judge rows (23.3%); 3/20 debates reached panel majority; mean argument strength advantage -0.38.
- evidence use: 13/60 judge rows (21.7%); 4/20 debates reached panel majority; mean grounding and epistemic discipline advantage -0.22.
- burden handling: 12/60 judge rows (20.0%); 4/20 debates reached panel majority; mean argument strength advantage -0.38.
- answer quality: 6/60 judge rows (10.0%); 0/20 debates reached panel majority; mean rebuttal quality advantage -0.40.
- factual error: 5/60 judge rows (8.3%); 0/20 debates reached panel majority; mean grounding and epistemic discipline advantage -0.22.

### Judge salience

- Full eligible corpus: 138 events across 58 event-bearing judge rows; direct engagement 25/58 (43%), argument construction 24/58 (41%), concession 20/58 (34%), weighing 14/58 (24%), evidence use 13/58 (22%), burden handling 12/58 (21%).

- [all] The judge credited PRO for framing the comparison around uncertainty and readiness. Evidence: “successfully framing the cost-effectiveness comparison around uncertainty and technical readiness”
- [all] The judge credited PRO's closing for converting CON's concession into a decisive structural forfeit. Evidence: “Turn 9 (Side B's Closing) decisively capitalized on Side A's honest concession in A4.2”

### Blind transcript observations

- Full eligible corpus: 209 events across 20 event-bearing debates; question type 20/20 (100%), direct engagement 18/20 (90%), answer type 16/20 (80%), confident specificity 14/20 (70%), strawman 13/20 (65%), weighing 12/20 (60%).

- [all] PRO anchors its feasibility argument in a specific quantitative physical constraint on electric aviation. Evidence: “batteries store roughly 40 times less energy per kilogram than jet fuel”
- [all] PRO frames the evaluation standard around demonstrated outcomes, which favors the deployed technology. Evidence: “Cost-effectiveness has to be measured against delivered results”

### Side-swap patterns

- Full eligible corpus: 54 events across 10 event-bearing groups; advocacy flexibility 10/10 (100%), stable behavior 10/10 (100%), side specific behavior 7/10 (70%), evidence asymmetry 6/10 (60%), contradiction candidate 4/10 (40%), tradeoff hiding 2/10 (20%).

- [all] As PRO, Claude treated the motion's "major city pairs" wording as a built-in selection filter, while as CON it argued for network-wide scope against that same wording and added a late US-only scope restriction.
- [all] As PRO, Claude required demonstrated outcomes and called the opponent's missing aviation figures a forfeit, while as CON it redefined cost-effectiveness as capital risk profiles "not spec sheets" after conceding that no electric fleet exists.

### Outcome associations

- Full eligible corpus: 107 links across 20 debates; aligned 19/20 (95%), judge_disagreement 15/20 (75%), conflicted 7/20 (35%), unclear 6/20 (30%).

## DeepSeek V4.1 Flash (high)

### Deterministic execution

- Coverage: 16 current-peer debates / 80 turns.
- Mean raw words per turn: 233.5; mean word-limit use: 80.4%.
- Deterministically clipped turns: 2.5%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.35 | 7.58 | -0.23 | -0.38 [-0.87, +0.12] | 7.38 | 7.33 | 16 debates / 48 judge rows |
| Rebuttal quality | 7.40 | 7.59 | -0.19 | -0.54 [-1.15, +0.06] | 7.42 | 7.38 | 16 debates / 48 judge rows |
| Grounding / epistemics | 7.54 | 7.53 | +0.01 | -0.10 [-0.38, +0.17] | 7.54 | 7.54 | 16 debates / 48 judge rows |
| Originality | 6.79 | 7.06 | -0.27 | -0.42 [-0.78, -0.05] | 6.88 | 6.71 | 16 debates / 48 judge rows |
| Rhetorical effectiveness | 7.62 | 7.80 | -0.17 | -0.25 [-0.71, +0.21] | 7.83 | 7.42 | 16 debates / 48 judge rows |

### Judge-panel consensus

- burden handling: 17/48 judge rows (35.4%); 6/16 debates reached panel majority; mean argument strength advantage -0.38.
- argument construction: 16/48 judge rows (33.3%); 5/16 debates reached panel majority; mean argument strength advantage -0.38.
- direct engagement: 15/48 judge rows (31.2%); 5/16 debates reached panel majority; mean rebuttal quality advantage -0.54.
- concession: 15/48 judge rows (31.2%); 4/16 debates reached panel majority; mean rebuttal quality advantage -0.54.
- weighing: 6/48 judge rows (12.5%); 0/16 debates reached panel majority; mean argument strength advantage -0.38.
- rhetoric: 4/48 judge rows (8.3%); 1/16 debates reached panel majority; mean rhetorical effectiveness advantage -0.25.
- answer quality: 4/48 judge rows (8.3%); 0/16 debates reached panel majority; mean rebuttal quality advantage -0.54.
- dropped argument: 4/48 judge rows (8.3%); 0/16 debates reached panel majority; mean rebuttal quality advantage -0.54.

### Judge salience

- Full eligible corpus: 95 events across 45 event-bearing judge rows; burden handling 17/45 (38%), argument construction 16/45 (36%), concession 15/45 (33%), direct engagement 15/45 (33%), weighing 6/45 (13%), answer quality 4/45 (9%).

- [all] PRO's mechanisms were seen as credible, but it assumed rather than showed that integration and tax gains would cover transition costs. Evidence: “largely assumed that integration capacity and future tax gains would solve the transition costs”
- [all] PRO's truncated first rebuttal counted as a minor execution penalty. Evidence: “A's clipped first rebuttal was a modest additional execution cost.”

### Blind transcript observations

- Full eligible corpus: 157 events across 16 event-bearing debates; question type 16/16 (100%), direct engagement 15/16 (94%), answer type 13/16 (81%), repetition 13/16 (81%), burden setting 10/16 (62%), burden contest 9/16 (56%).

- [all] PRO answers CON's scale-trap argument by applying the same treadmill logic to automation. Evidence: “If aging inflows make immigration a treadmill, the same logic makes automation a treadmill: each generation needs another wave of capital, maintenance, and technicians.”
- [all] PRO calls immigration a complement, and CON then uses this wording to argue PRO has stepped back from the motion's demand for prioritization. Evidence: “so it complements automation and slack rather than replacing them.”

### Side-swap patterns

- Full eligible corpus: 38 events across 8 event-bearing groups; advocacy flexibility 7/8 (88%), side specific behavior 7/8 (88%), stable behavior 7/8 (88%), moral standard asymmetry 4/8 (50%), contradiction candidate 4/8 (50%), evidence asymmetry 4/8 (50%).

- [all] As PRO, deepseek-v4.1-flash-high answered the immigration treadmill argument by applying the same logic to automation; as CON, it introduced the treadmill image itself and extended it through every later round.
- [all] As PRO, deepseek-v4.1-flash-high answered the magnitude question with a concrete figure; as CON, it demanded a specific number from its opponent but answered its own threshold question with a functional criterion, and PRO pointed out this asymmetry.

### Outcome associations

- Full eligible corpus: 78 links across 16 debates; aligned 14/16 (88%), conflicted 9/16 (56%), judge_disagreement 8/16 (50%), unclear 2/16 (12%).

## Tencent Hy4 Preview (high)

### Deterministic execution

- Coverage: 18 current-peer debates / 90 turns.
- Mean raw words per turn: 243.4; mean word-limit use: 84.9%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.56 | 7.58 | -0.03 | -0.07 [-0.41, +0.26] | 7.59 | 7.52 | 18 debates / 54 judge rows |
| Rebuttal quality | 7.50 | 7.59 | -0.09 | -0.31 [-0.82, +0.19] | 7.33 | 7.67 | 18 debates / 54 judge rows |
| Grounding / epistemics | 7.57 | 7.53 | +0.04 | +0.02 [-0.25, +0.29] | 7.56 | 7.59 | 18 debates / 54 judge rows |
| Originality | 6.91 | 7.06 | -0.15 | -0.26 [-0.48, -0.04] | 6.89 | 6.93 | 18 debates / 54 judge rows |
| Rhetorical effectiveness | 7.74 | 7.80 | -0.06 | -0.04 [-0.46, +0.38] | 7.67 | 7.81 | 18 debates / 54 judge rows |

### Judge-panel consensus

- direct engagement: 23/54 judge rows (42.6%); 7/18 debates reached panel majority; mean rebuttal quality advantage -0.31.
- argument construction: 22/54 judge rows (40.7%); 6/18 debates reached panel majority; mean argument strength advantage -0.07.
- concession: 14/54 judge rows (25.9%); 5/18 debates reached panel majority; mean rebuttal quality advantage -0.31.
- burden handling: 13/54 judge rows (24.1%); 3/18 debates reached panel majority; mean argument strength advantage -0.07.
- weighing: 13/54 judge rows (24.1%); 3/18 debates reached panel majority; mean argument strength advantage -0.07.
- answer quality: 7/54 judge rows (13.0%); 1/18 debates reached panel majority; mean rebuttal quality advantage -0.31.
- evidence use: 7/54 judge rows (13.0%); 1/18 debates reached panel majority; mean grounding and epistemic discipline advantage +0.02.
- question quality: 5/54 judge rows (9.3%); 1/18 debates reached panel majority; mean rebuttal quality advantage -0.31.

### Judge salience

- Full eligible corpus: 124 events across 51 event-bearing judge rows; argument construction 22/51 (43%), direct engagement 22/51 (43%), concession 14/51 (27%), burden handling 13/51 (25%), weighing 13/51 (25%), answer quality 7/51 (14%).

- [all] PRO was credited with owning the gatekeeper frame. Evidence: “A owned the gatekeeper frame and showed targeted tools need better provenance.”
- [all] PRO maintained its gatekeeper-control framing throughout. Evidence: “PRO sustained gatekeeper-control framing”

### Blind transcript observations

- Full eligible corpus: 176 events across 18 event-bearing debates; direct engagement 17/18 (94%), question type 17/18 (94%), answer type 15/18 (83%), repetition 14/18 (78%), strategic concession 12/18 (67%), burden setting 9/18 (50%).

- [all] PRO concedes the motion's stated cost up front and recasts it as pricing in externalized harms. Evidence: “Be honest about the tradeoff: yes, stronger rules slow some ultra-cheap shopping.”
- [all] PRO rebuts the postal analogy by contrasting the platform's control functions with a carrier's. Evidence: “The analogy fails on control. A mail carrier carries parcels; it does not select the assortment, rank results, take payment, or set delivery terms”

### Side-swap patterns

- Full eligible corpus: 38 events across 9 event-bearing groups; stable behavior 9/9 (100%), side specific behavior 7/9 (78%), advocacy flexibility 7/9 (78%), contradiction candidate 4/9 (44%), evidence asymmetry 2/9 (22%), tradeoff hiding 1/9 (11%).

- [all] As PRO, hy4-preview-high mostly engaged effectively, but as CON it made two leaked concessions on platform-held identity and traceability, and kimi-k3 used them to build its closing.
- [all] On both sides, hy4-preview-high asked feasibility questions about how liability or verification would identify real parties, and it closed by repeating an earlier line nearly verbatim.

### Outcome associations

- Full eligible corpus: 92 links across 18 debates; aligned 16/18 (89%), judge_disagreement 12/18 (67%), conflicted 6/18 (33%), unclear 2/18 (11%).

## DeepSeek V4 Pro 0813 (high)

### Deterministic execution

- Coverage: 30 current-peer debates / 150 turns.
- Mean raw words per turn: 227.4; mean word-limit use: 78.9%.
- Deterministically clipped turns: 1.3%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.33 | 7.58 | -0.25 | -0.77 [-1.06, -0.47] | 7.51 | 7.16 | 30 debates / 90 judge rows |
| Rebuttal quality | 7.23 | 7.59 | -0.35 | -1.07 [-1.39, -0.74] | 7.20 | 7.27 | 30 debates / 90 judge rows |
| Grounding / epistemics | 7.54 | 7.53 | +0.01 | -0.22 [-0.44, -0.00] | 7.62 | 7.47 | 30 debates / 90 judge rows |
| Originality | 6.92 | 7.06 | -0.14 | -0.57 [-0.81, -0.33] | 7.00 | 6.84 | 30 debates / 90 judge rows |
| Rhetorical effectiveness | 7.56 | 7.80 | -0.24 | -0.79 [-1.10, -0.48] | 7.67 | 7.44 | 30 debates / 90 judge rows |

### Judge-panel consensus

- argument construction: 40/90 judge rows (44.4%); 12/30 debates reached panel majority; mean argument strength advantage -0.77.
- direct engagement: 31/90 judge rows (34.4%); 10/30 debates reached panel majority; mean rebuttal quality advantage -1.07.
- burden handling: 26/90 judge rows (28.9%); 7/30 debates reached panel majority; mean argument strength advantage -0.77.
- concession: 20/90 judge rows (22.2%); 5/30 debates reached panel majority; mean rebuttal quality advantage -1.07.
- dropped argument: 14/90 judge rows (15.6%); 1/30 debates reached panel majority; mean rebuttal quality advantage -1.07.
- answer quality: 12/90 judge rows (13.3%); 2/30 debates reached panel majority; mean rebuttal quality advantage -1.07.
- weighing: 11/90 judge rows (12.2%); 3/30 debates reached panel majority; mean argument strength advantage -0.77.
- format compliance: 11/90 judge rows (12.2%); 2/30 debates reached panel majority; mean rhetorical effectiveness advantage -0.79.

### Judge salience

- Full eligible corpus: 186 events across 84 event-bearing judge rows; argument construction 40/84 (48%), direct engagement 31/84 (37%), burden handling 26/84 (31%), concession 20/84 (24%), dropped argument 14/84 (17%), weighing 11/84 (13%).

- [all] The judge found PRO's batching and escalation answer to the focus-responsiveness tension adequate. Evidence: “A adequately answered the focus-versus-responsiveness tension through batching and escalation”
- [all] The judge credited PRO with supporting the modest "many" burden through concrete deliverable-heavy roles. Evidence: “the modest claim about many knowledge workers remained well supported by concrete deliverable-heavy roles”

### Blind transcript observations

- Full eligible corpus: 298 events across 30 event-bearing debates; direct engagement 30/30 (100%), question type 30/30 (100%), answer type 24/30 (80%), weighing 21/30 (70%), burden contest 17/30 (57%), strategic concession 15/30 (50%).

- [all] PRO frames the burden as net gains for "many" workers against a full-time mandate, not universal benefit. Evidence: “The motion does not claim every role benefits equally. It says many knowledge workers see net gains compared with full-time mandatory attendance.”
- [all] PRO directly answers CON's latency example by noting that synchronous channels remain available to remote workers. Evidence: “Chat, phone, and video remain available for the 90-second question in [C1.2].”

### Side-swap patterns

- Full eligible corpus: 66 events across 15 event-bearing groups; advocacy flexibility 14/15 (93%), stable behavior 14/15 (93%), side specific behavior 10/15 (67%), contradiction candidate 8/15 (53%), evidence asymmetry 5/15 (33%), moral standard asymmetry 3/15 (20%).

- [all] As PRO, deepseek-v4-pro-0813-high argued that an office adding silence gives up hallway availability; as CON, it set the comparison as a well-run office with quiet zones, apparently without accounting for that tradeoff.
- [all] On both sides, deepseek-v4-pro-0813-high made concessions while rebutting that the opponent then picked up and used against it.

### Outcome associations

- Full eligible corpus: 144 links across 30 debates; aligned 28/30 (93%), conflicted 17/30 (57%), judge_disagreement 11/30 (37%), unclear 6/30 (20%).

## Qwen 3.8 Max

### Deterministic execution

- Coverage: 34 current-peer debates / 170 turns.
- Mean raw words per turn: 235.3; mean word-limit use: 80.0%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.11 | 7.58 | -0.47 | -0.74 [-0.94, -0.53] | 7.02 | 7.20 | 34 debates / 102 judge rows |
| Rebuttal quality | 6.98 | 7.59 | -0.61 | -1.01 [-1.30, -0.72] | 6.75 | 7.22 | 34 debates / 102 judge rows |
| Grounding / epistemics | 7.35 | 7.53 | -0.18 | -0.21 [-0.38, -0.03] | 7.29 | 7.41 | 34 debates / 102 judge rows |
| Originality | 6.50 | 7.06 | -0.56 | -0.82 [-1.02, -0.62] | 6.33 | 6.67 | 34 debates / 102 judge rows |
| Rhetorical effectiveness | 7.24 | 7.80 | -0.56 | -0.80 [-1.02, -0.58] | 7.29 | 7.18 | 34 debates / 102 judge rows |

### Judge-panel consensus

- argument construction: 55/102 judge rows (53.9%); 20/34 debates reached panel majority; mean argument strength advantage -0.74.
- burden handling: 38/102 judge rows (37.3%); 12/34 debates reached panel majority; mean argument strength advantage -0.74.
- direct engagement: 32/102 judge rows (31.4%); 9/34 debates reached panel majority; mean rebuttal quality advantage -1.01.
- concession: 31/102 judge rows (30.4%); 11/34 debates reached panel majority; mean rebuttal quality advantage -1.01.
- dropped argument: 20/102 judge rows (19.6%); 2/34 debates reached panel majority; mean rebuttal quality advantage -1.01.
- answer quality: 16/102 judge rows (15.7%); 4/34 debates reached panel majority; mean rebuttal quality advantage -1.01.
- weighing: 12/102 judge rows (11.8%); 1/34 debates reached panel majority; mean argument strength advantage -0.74.
- repetition: 7/102 judge rows (6.9%); 1/34 debates reached panel majority; mean rhetorical effectiveness advantage -0.80.

### Judge salience

- Full eligible corpus: 232 events across 100 event-bearing judge rows; argument construction 55/100 (55%), burden handling 38/100 (38%), direct engagement 32/100 (32%), concession 31/100 (31%), dropped argument 20/100 (20%), answer quality 16/100 (16%).

- [all] The judge penalized CON for failing to answer PRO's access-versus-storage collapse. Evidence: “CON (A) never fully answered this collapse”
- [all] The judge found that CON's pressure answer conceded the motion's core structure. Evidence: “effectively conceded the motion's core structure (more, not all)”

### Blind transcript observations

- Full eligible corpus: 313 events across 34 event-bearing debates; direct engagement 33/34 (97%), question type 33/34 (97%), answer type 29/34 (85%), burden setting 24/34 (71%), repetition 23/34 (68%), weighing 21/34 (62%).

- [all] CON sets PRO's burden as justifying a citywide default rather than individual corridor examples. Evidence: “PRO cannot win by pointing to one congested corridor; the motion asks for a citywide preference.”
- [all] CON directly challenges PRO's throughput metric and offers an alternative standard of evaluation. Evidence: “The key flaw in PRO’s metric is that it counts movement past a curb, not service to the curb.”

### Side-swap patterns

- Full eligible corpus: 72 events across 17 event-bearing groups; side specific behavior 16/17 (94%), stable behavior 15/17 (88%), advocacy flexibility 12/17 (71%), contradiction candidate 6/17 (35%), moral standard asymmetry 3/17 (18%), evidence asymmetry 3/17 (18%).

- [all] As CON, qwen3.8-max required proven access guarantees before parking could be removed. As PRO, it characterized the opponent's similar burden standard as "a parking veto."
- [all] As CON, qwen3.8-max argued that throughput metrics ignore service to the curb. As PRO, it used the access-versus-storage distinction that kimi-k3 had used as PRO in the other debate.

### Outcome associations

- Full eligible corpus: 173 links across 34 debates; aligned 32/34 (94%), conflicted 17/34 (50%), judge_disagreement 12/34 (35%), unclear 8/34 (24%).

## Gemini 3.8 Flash (high)

### Deterministic execution

- Coverage: 16 current-peer debates / 80 turns.
- Mean raw words per turn: 230.6; mean word-limit use: 79.9%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.15 | 7.58 | -0.44 | -0.96 [-1.27, -0.65] | 7.08 | 7.21 | 16 debates / 48 judge rows |
| Rebuttal quality | 6.92 | 7.59 | -0.67 | -1.25 [-1.78, -0.72] | 6.67 | 7.17 | 16 debates / 48 judge rows |
| Grounding / epistemics | 7.12 | 7.53 | -0.41 | -0.88 [-1.21, -0.54] | 7.12 | 7.12 | 16 debates / 48 judge rows |
| Originality | 6.62 | 7.06 | -0.44 | -0.79 [-0.97, -0.61] | 6.62 | 6.62 | 16 debates / 48 judge rows |
| Rhetorical effectiveness | 7.71 | 7.80 | -0.09 | -0.44 [-0.81, -0.06] | 7.79 | 7.62 | 16 debates / 48 judge rows |

### Judge-panel consensus

- argument construction: 31/48 judge rows (64.6%); 10/16 debates reached panel majority; mean argument strength advantage -0.96.
- burden handling: 14/48 judge rows (29.2%); 3/16 debates reached panel majority; mean argument strength advantage -0.96.
- direct engagement: 13/48 judge rows (27.1%); 4/16 debates reached panel majority; mean rebuttal quality advantage -1.25.
- dropped argument: 13/48 judge rows (27.1%); 4/16 debates reached panel majority; mean rebuttal quality advantage -1.25.
- answer quality: 10/48 judge rows (20.8%); 2/16 debates reached panel majority; mean rebuttal quality advantage -1.25.
- repetition: 8/48 judge rows (16.7%); 1/16 debates reached panel majority; mean rhetorical effectiveness advantage -0.44.
- concession: 7/48 judge rows (14.6%); 1/16 debates reached panel majority; mean rebuttal quality advantage -1.25.
- rhetoric: 5/48 judge rows (10.4%); 1/16 debates reached panel majority; mean rhetorical effectiveness advantage -0.44.

### Judge salience

- Full eligible corpus: 117 events across 48 event-bearing judge rows; argument construction 31/48 (65%), burden handling 14/48 (29%), direct engagement 13/48 (27%), dropped argument 13/48 (27%), answer quality 10/48 (21%), repetition 8/48 (17%).

- [all] The judge noted that PRO handled the pressure questions well. Evidence: “A answered the pressure questions well”
- [all] The judge found that PRO's claim of a CON concession misread CON's position. Evidence: “its claimed concession misread B’s position”

### Blind transcript observations

- Full eligible corpus: 154 events across 16 event-bearing debates; direct engagement 15/16 (94%), question type 15/16 (94%), answer type 15/16 (94%), repetition 15/16 (94%), strawman 14/16 (88%), dropped argument 11/16 (69%).

- [all] PRO frames the comparison so that dignity matters only when it restricts choice, a framing CON later challenges as question-begging. Evidence: “But when appeals to dignity are used to restrict choice, dignity invariably functions as a tool of moral paternalism”
- [all] PRO directly answers CON's grounding argument by distinguishing justificatory foundation from comparative weight in conflicts. Evidence: “First, grounding is not outranking.”

### Side-swap patterns

- Full eligible corpus: 37 events across 8 event-bearing groups; stable behavior 8/8 (100%), side specific behavior 5/8 (62%), contradiction candidate 5/8 (62%), advocacy flexibility 4/8 (50%), evidence asymmetry 2/8 (25%), tradeoff hiding 1/8 (12%).

- [all] On both sides, this model recasts the opponent's limited statements as decisive concessions, or says the opponent offered no explanation, even after the opponent had clarified or explained the point.
- [all] On both sides, this model tends to restate a fixed summary formula across later rounds instead of answering the opponent's newest rebuttals.

### Outcome associations

- Full eligible corpus: 98 links across 16 debates; aligned 16/16 (100%), conflicted 9/16 (56%), judge_disagreement 7/16 (44%), unclear 3/16 (19%).

## MiniMax-M3

### Deterministic execution

- Coverage: 18 current-peer debates / 90 turns.
- Mean raw words per turn: 249.8; mean word-limit use: 86.1%.
- Deterministically clipped turns: 12.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.02 | 7.58 | -0.56 | -0.81 [-1.31, -0.32] | 7.19 | 6.85 | 18 debates / 54 judge rows |
| Rebuttal quality | 6.81 | 7.59 | -0.77 | -1.15 [-1.71, -0.59] | 7.00 | 6.63 | 18 debates / 54 judge rows |
| Grounding / epistemics | 7.24 | 7.53 | -0.29 | -0.28 [-0.66, +0.10] | 7.41 | 7.07 | 18 debates / 54 judge rows |
| Originality | 6.59 | 7.06 | -0.47 | -0.48 [-0.84, -0.12] | 6.74 | 6.44 | 18 debates / 54 judge rows |
| Rhetorical effectiveness | 7.15 | 7.80 | -0.65 | -0.61 [-1.25, +0.02] | 7.26 | 7.04 | 18 debates / 54 judge rows |

### Judge-panel consensus

- argument construction: 25/54 judge rows (46.3%); 9/18 debates reached panel majority; mean argument strength advantage -0.81.
- direct engagement: 20/54 judge rows (37.0%); 6/18 debates reached panel majority; mean rebuttal quality advantage -1.15.
- concession: 17/54 judge rows (31.5%); 4/18 debates reached panel majority; mean rebuttal quality advantage -1.15.
- answer quality: 12/54 judge rows (22.2%); 4/18 debates reached panel majority; mean rebuttal quality advantage -1.15.
- format compliance: 11/54 judge rows (20.4%); 2/18 debates reached panel majority; mean rhetorical effectiveness advantage -0.61.
- burden handling: 11/54 judge rows (20.4%); 0/18 debates reached panel majority; mean argument strength advantage -0.81.
- weighing: 6/54 judge rows (11.1%); 2/18 debates reached panel majority; mean argument strength advantage -0.81.
- dropped argument: 6/54 judge rows (11.1%); 1/18 debates reached panel majority; mean rebuttal quality advantage -1.15.

### Judge salience

- Full eligible corpus: 130 events across 52 event-bearing judge rows; argument construction 25/52 (48%), direct engagement 20/52 (38%), concession 17/52 (33%), answer quality 12/52 (23%), burden handling 11/52 (21%), format compliance 8/52 (15%).

- [all] The judge noted that CON's alternative conceded the principle of enforceability. Evidence: “concedes the core principle of enforceability”
- [all] The judge credited CON with answering PRO's pressure questions directly. Evidence: “answered B's pressure questions directly”

### Blind transcript observations

- Full eligible corpus: 178 events across 18 event-bearing debates; direct engagement 16/18 (89%), question type 15/18 (83%), burden setting 14/18 (78%), answer type 12/18 (67%), weighing 9/18 (50%), strawman 9/18 (50%).

- [all] CON assigns PRO a concrete operational burden covering measurement, enforcement, and health effect. Evidence: “The burden is on the proposition to identify what will be measured, who will enforce it, and how it improves health across buildings with different risks.”
- [all] CON targets PRO's measurable-performance claim and argues that proxy metrics can be gamed. Evidence: “The promise of “measurable performance” [P1.6] creates a trap: an easy metric can be satisfied while the hazard persists.”

### Side-swap patterns

- Full eligible corpus: 42 events across 9 event-bearing groups; stable behavior 9/9 (100%), side specific behavior 8/9 (89%), advocacy flexibility 5/9 (56%), contradiction candidate 4/9 (44%), tradeoff hiding 3/9 (33%), evidence asymmetry 3/9 (33%).

- [all] On both sides, minimax's cross-examination asks the opponent to name the specific enforceable outcome its scheme must achieve.
- [all] As CON, minimax argued that proxy metrics can be gamed and made protection per pound the deciding criterion; as PRO, it built a multi-metric monitoring regime and downplayed funding as the decisive factor.

### Outcome associations

- Full eligible corpus: 89 links across 18 debates; aligned 17/18 (94%), conflicted 10/18 (56%), unclear 8/18 (44%), judge_disagreement 7/18 (39%).

## Mistral Large 4 (high)

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 238.6; mean word-limit use: 83.0%.
- Deterministically clipped turns: 4.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.80 | 7.58 | -0.78 | -1.30 [-1.73, -0.87] | 6.90 | 6.70 | 20 debates / 60 judge rows |
| Rebuttal quality | 6.50 | 7.59 | -1.09 | -1.82 [-2.27, -1.36] | 6.53 | 6.47 | 20 debates / 60 judge rows |
| Grounding / epistemics | 6.73 | 7.53 | -0.80 | -1.12 [-1.53, -0.71] | 6.93 | 6.53 | 20 debates / 60 judge rows |
| Originality | 6.55 | 7.06 | -0.51 | -0.83 [-1.15, -0.51] | 6.47 | 6.63 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 7.35 | 7.80 | -0.45 | -0.85 [-1.32, -0.38] | 7.57 | 7.13 | 20 debates / 60 judge rows |

### Judge-panel consensus

- argument construction: 28/60 judge rows (46.7%); 7/20 debates reached panel majority; mean argument strength advantage -1.30.
- concession: 18/60 judge rows (30.0%); 6/20 debates reached panel majority; mean rebuttal quality advantage -1.82.
- direct engagement: 14/60 judge rows (23.3%); 3/20 debates reached panel majority; mean rebuttal quality advantage -1.82.
- dropped argument: 11/60 judge rows (18.3%); 1/20 debates reached panel majority; mean rebuttal quality advantage -1.82.
- burden handling: 9/60 judge rows (15.0%); 1/20 debates reached panel majority; mean argument strength advantage -1.30.
- evidence use: 7/60 judge rows (11.7%); 1/20 debates reached panel majority; mean grounding and epistemic discipline advantage -1.12.
- answer quality: 6/60 judge rows (10.0%); 1/20 debates reached panel majority; mean rebuttal quality advantage -1.82.
- factual error: 5/60 judge rows (8.3%); 1/20 debates reached panel majority; mean grounding and epistemic discipline advantage -1.12.

### Judge salience

- Full eligible corpus: 117 events across 57 event-bearing judge rows; argument construction 28/57 (49%), concession 18/57 (32%), direct engagement 14/57 (25%), dropped argument 11/57 (19%), burden handling 9/57 (16%), evidence use 7/57 (12%).

- [all] The judge penalized CON for resting on a sweeping, weakly grounded premise about perpetual paid maintenance. Evidence: “relied on the sweeping and weakly grounded premise that nearly every software-controlled feature needs perpetual paid maintenance”
- [all] The judge found that CON's endorsement of paying once, and its condemnation of kill switches, conceded PRO's ownership principle. Evidence: “B itself endorsed paying once for permanent functionality and condemned manufacturer kill switches, substantially conceding A’s ownership principle”

### Blind transcript observations

- Full eligible corpus: 189 events across 20 event-bearing debates; repetition 19/20 (95%), direct engagement 18/20 (90%), question type 18/20 (90%), answer type 15/20 (75%), strawman 15/20 (75%), leaked concession 14/20 (70%).

- [all] CON frames installed hardware as a substrate for continuously maintained software, which sets up its core "living system" theme. Evidence: “The real value lies in the control algorithms, the cybersecurity hardening, the thermal management code, and the compatibility updates”
- [all] CON endorses a principle against kill switches on installed capabilities that closely matches PRO's thesis, and PRO repeatedly uses this line against CON later. Evidence: “CON preserves transactional integrity: pay once for permanent functionality, or pay continuously for continuous service—but do not sell a car while retaining a kill switch over installed capabilities.”

### Side-swap patterns

- Full eligible corpus: 46 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 7/10 (70%), side specific behavior 6/10 (60%), evidence asymmetry 6/10 (60%), contradiction candidate 6/10 (60%), moral standard asymmetry 1/10 (10%).

- [all] On both sides, mistral makes concessions that undercut its own position, and the opponent then exploits them without mistral reconciling the tension.
- [all] Across both sides, mistral tends to repeat earlier claims and to attack positions the opponent had already disclaimed or conceded, rather than engaging the opponent's newer arguments.

### Outcome associations

- Full eligible corpus: 90 links across 20 debates; aligned 20/20 (100%), judge_disagreement 6/20 (30%), unclear 6/20 (30%), conflicted 5/20 (25%).

## ByteDance Seed2.0 Pro

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 198.3; mean word-limit use: 68.3%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.67 | 7.58 | -0.92 | -1.08 [-1.72, -0.44] | 6.77 | 6.57 | 20 debates / 60 judge rows |
| Rebuttal quality | 6.32 | 7.59 | -1.27 | -1.80 [-2.36, -1.24] | 6.23 | 6.40 | 20 debates / 60 judge rows |
| Grounding / epistemics | 6.40 | 7.53 | -1.13 | -1.35 [-1.67, -1.03] | 6.43 | 6.37 | 20 debates / 60 judge rows |
| Originality | 6.33 | 7.06 | -0.73 | -0.85 [-1.27, -0.43] | 6.37 | 6.30 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 7.43 | 7.80 | -0.36 | -0.35 [-0.94, +0.24] | 7.63 | 7.23 | 20 debates / 60 judge rows |

### Judge-panel consensus

- argument construction: 19/60 judge rows (31.7%); 7/20 debates reached panel majority; mean argument strength advantage -1.08.
- concession: 16/60 judge rows (26.7%); 4/20 debates reached panel majority; mean rebuttal quality advantage -1.80.
- evidence use: 16/60 judge rows (26.7%); 4/20 debates reached panel majority; mean grounding and epistemic discipline advantage -1.35.
- dropped argument: 15/60 judge rows (25.0%); 3/20 debates reached panel majority; mean rebuttal quality advantage -1.80.
- answer quality: 13/60 judge rows (21.7%); 3/20 debates reached panel majority; mean rebuttal quality advantage -1.80.
- burden handling: 12/60 judge rows (20.0%); 3/20 debates reached panel majority; mean argument strength advantage -1.08.
- direct engagement: 11/60 judge rows (18.3%); 3/20 debates reached panel majority; mean rebuttal quality advantage -1.80.
- repetition: 10/60 judge rows (16.7%); 4/20 debates reached panel majority; mean rhetorical effectiveness advantage -0.35.

### Judge salience

- Full eligible corpus: 139 events across 59 event-bearing judge rows; argument construction 19/59 (32%), concession 16/59 (27%), evidence use 15/59 (25%), dropped argument 15/59 (25%), answer quality 13/59 (22%), burden handling 12/59 (20%).

- [all] The judge penalized CON for asserting its displacement claim without demonstrating it. Evidence: “repeatedly asserted, rather than demonstrated, that stronger noise enforcement must displace deadlier programs”
- [all] The judge noted that CON's alternative ended up converging with PRO's policy. Evidence: “Its eventual endorsement of permit conditions and graduated fines substantially converged with A's policy”

### Blind transcript observations

- Full eligible corpus: 197 events across 20 event-bearing debates; question type 19/20 (95%), confident specificity 19/20 (95%), direct engagement 15/20 (75%), repetition 15/20 (75%), dropped argument 13/20 (65%), leaked concession 12/20 (60%).

- [all] CON contests the harm-equivalence premise, but it does so by assertion and does not engage PRO's cited health burden rankings. Evidence: “This entire case rests on a false equivalence so fundamental it sinks the motion before it begins.”
- [all] CON concedes that noise causes real harm in order to pivot to proportionality, and PRO later uses this concession repeatedly. Evidence: “Noise causes real stress, yes”

### Side-swap patterns

- Full eligible corpus: 49 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 8/10 (80%), contradiction candidate 6/10 (60%), side specific behavior 5/10 (50%), moral standard asymmetry 3/10 (30%), evidence asymmetry 3/10 (30%).

- [all] As CON, seed-2.0-pro equated urgency with equal budget and staff, while as PRO it narrowed parity to enforcement priority and source-specific rules.
- [all] On both sides, seed-2.0-pro made concessions or gave narrowing answers that the opponent then exploited.

### Outcome associations

- Full eligible corpus: 101 links across 20 debates; aligned 19/20 (95%), conflicted 8/20 (40%), judge_disagreement 8/20 (40%), unclear 5/20 (25%).

## Baidu Ernie 5.1

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 239.7; mean word-limit use: 83.5%.
- Deterministically clipped turns: 5.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.43 | 7.58 | -1.15 | -1.82 [-2.14, -1.49] | 6.53 | 6.33 | 20 debates / 60 judge rows |
| Rebuttal quality | 6.08 | 7.59 | -1.50 | -2.47 [-2.79, -2.14] | 6.03 | 6.13 | 20 debates / 60 judge rows |
| Grounding / epistemics | 6.18 | 7.53 | -1.35 | -1.62 [-2.07, -1.16] | 6.07 | 6.30 | 20 debates / 60 judge rows |
| Originality | 6.05 | 7.06 | -1.01 | -1.40 [-1.69, -1.11] | 6.07 | 6.03 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 6.98 | 7.80 | -0.81 | -1.32 [-1.62, -1.01] | 7.17 | 6.80 | 20 debates / 60 judge rows |

### Judge-panel consensus

- concession: 22/60 judge rows (36.7%); 8/20 debates reached panel majority; mean rebuttal quality advantage -2.47.
- argument construction: 20/60 judge rows (33.3%); 5/20 debates reached panel majority; mean argument strength advantage -1.82.
- burden handling: 18/60 judge rows (30.0%); 6/20 debates reached panel majority; mean argument strength advantage -1.82.
- evidence use: 18/60 judge rows (30.0%); 3/20 debates reached panel majority; mean grounding and epistemic discipline advantage -1.62.
- dropped argument: 10/60 judge rows (16.7%); 2/20 debates reached panel majority; mean rebuttal quality advantage -2.47.
- format compliance: 8/60 judge rows (13.3%); 3/20 debates reached panel majority; mean rhetorical effectiveness advantage -1.32.
- weighing: 6/60 judge rows (10.0%); 2/20 debates reached panel majority; mean argument strength advantage -1.82.
- direct engagement: 6/60 judge rows (10.0%); 0/20 debates reached panel majority; mean rebuttal quality advantage -2.47.

### Judge salience

- Full eligible corpus: 140 events across 57 event-bearing judge rows; concession 22/57 (39%), argument construction 20/57 (35%), evidence use 18/57 (32%), burden handling 18/57 (32%), dropped argument 10/57 (18%), format compliance 8/57 (14%).

- [all] The judge said PRO's rebuttal effectively conceded CON's narrowed framing. Evidence: “PRO's own rebuttal ("the real issue is... ID verification") effectively conceded this framing”
- [all] The judge penalized PRO for leaving CON's funding-mechanism critique largely unanswered. Evidence: “the funding mechanism critique (ad revenue = data monetization) went largely unanswered beyond an unsupported "modest ad margin,"”

### Blind transcript observations

- Full eligible corpus: 207 events across 20 event-bearing debates; leaked concession 19/20 (95%), confident specificity 18/20 (90%), question type 17/20 (85%), repetition 17/20 (85%), direct engagement 14/20 (70%), strawman 14/20 (70%).

- [all] PRO cites a specific platform example without supporting figures, and CON later reframes it as evidence that free verification already happens voluntarily. Evidence: “When Bumble rolled out free photo‑verification in several markets, impersonation reports fell sharply and user‑retention rose”
- [all] PRO restates the motion's target as stronger identity verification, which addresses the redundancy charge but narrows its own case. Evidence: “If the motion merely codifies what already exists, it changes nothing; the proposition pushes the next, stronger shield into the free tier where it belongs.”

### Side-swap patterns

- Full eligible corpus: 48 events across 10 event-bearing groups; stable behavior 10/10 (100%), contradiction candidate 7/10 (70%), evidence asymmetry 5/10 (50%), side specific behavior 4/10 (40%), advocacy flexibility 4/10 (40%), moral standard asymmetry 2/10 (20%).

- [all] On both sides, ernie-5.1 offers platform examples or historical patterns without supporting figures, and the opponent challenges or reframes them.
- [all] In both debates, ernie-5.1 makes a late-round statement that the opponent treats as a decisive concession and builds its closing around.

### Outcome associations

- Full eligible corpus: 101 links across 20 debates; aligned 20/20 (100%), conflicted 6/20 (30%), unclear 6/20 (30%), judge_disagreement 4/20 (20%).

## Step 3.7 Flash (high)

### Deterministic execution

- Coverage: 20 current-peer debates / 100 turns.
- Mean raw words per turn: 256.5; mean word-limit use: 90.0%.
- Deterministically clipped turns: 23.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.25 | 7.58 | -1.33 | -1.72 [-2.11, -1.33] | 6.50 | 6.00 | 20 debates / 60 judge rows |
| Rebuttal quality | 5.65 | 7.59 | -1.94 | -2.65 [-3.03, -2.27] | 5.87 | 5.43 | 20 debates / 60 judge rows |
| Grounding / epistemics | 5.73 | 7.53 | -1.80 | -1.83 [-2.46, -1.20] | 5.83 | 5.63 | 20 debates / 60 judge rows |
| Originality | 5.82 | 7.06 | -1.25 | -1.37 [-1.61, -1.13] | 5.90 | 5.73 | 20 debates / 60 judge rows |
| Rhetorical effectiveness | 6.42 | 7.80 | -1.38 | -1.48 [-2.17, -0.79] | 6.70 | 6.13 | 20 debates / 60 judge rows |

### Judge-panel consensus

- argument construction: 26/60 judge rows (43.3%); 8/20 debates reached panel majority; mean argument strength advantage -1.72.
- format compliance: 25/60 judge rows (41.7%); 8/20 debates reached panel majority; mean rhetorical effectiveness advantage -1.48.
- concession: 24/60 judge rows (40.0%); 7/20 debates reached panel majority; mean rebuttal quality advantage -2.65.
- evidence use: 22/60 judge rows (36.7%); 6/20 debates reached panel majority; mean grounding and epistemic discipline advantage -1.83.
- dropped argument: 12/60 judge rows (20.0%); 0/20 debates reached panel majority; mean rebuttal quality advantage -2.65.
- direct engagement: 10/60 judge rows (16.7%); 1/20 debates reached panel majority; mean rebuttal quality advantage -2.65.
- repetition: 10/60 judge rows (16.7%); 1/20 debates reached panel majority; mean rhetorical effectiveness advantage -1.48.
- burden handling: 8/60 judge rows (13.3%); 3/20 debates reached panel majority; mean argument strength advantage -1.72.

### Judge salience

- Full eligible corpus: 163 events across 59 event-bearing judge rows; argument construction 26/59 (44%), concession 24/59 (41%), format compliance 23/59 (39%), evidence use 22/59 (37%), dropped argument 12/59 (20%), repetition 10/59 (17%).

- [all] The judge noted that CON's admissions about speed-preserving redesign and harm migration were used against it. Evidence: “CON's admission that operators redesign games to preserve speed”
- [all] The judge noted that CON never directly answered PRO's hidden-premise framing. Evidence: “a framing CON never directly answered in Rebuttal 2 or Closing”

### Blind transcript observations

- Full eligible corpus: 192 events across 20 event-bearing debates; confident specificity 18/20 (90%), repetition 18/20 (90%), question type 17/20 (85%), strawman 15/20 (75%), leaked concession 15/20 (75%), answer type 13/20 (65%).

- [all] CON recasts PRO's "distinct harm profile" claim as a claim that speed is the primary driver, a framing PRO later rejects. Evidence: “that gambling speed is the primary, distinct driver of harm”
- [all] While contesting the FOBT example, CON grants that speed is a harm driver, and PRO later uses this admission. Evidence: “Speed was a secondary, not primary, harm driver.”

### Side-swap patterns

- Full eligible corpus: 47 events across 10 event-bearing groups; stable behavior 10/10 (100%), side specific behavior 8/10 (80%), contradiction candidate 7/10 (70%), advocacy flexibility 3/10 (30%), evidence asymmetry 3/10 (30%), moral standard asymmetry 2/10 (20%).

- [all] On both sides, step-3.7-flash-high made concessions that narrowed its position, and the opponent then used them against it.
- [all] On both sides, step-3.7-flash-high mischaracterized the opponent's position, repeated earlier points without answering rebuttals, and made unsourced empirical claims.

### Outcome associations

- Full eligible corpus: 108 links across 20 debates; aligned 20/20 (100%), unclear 8/20 (40%), conflicted 6/20 (30%), judge_disagreement 3/20 (15%).

## Mistral Medium 3.5 (high)

### Deterministic execution

- Coverage: 18 current-peer debates / 90 turns.
- Mean raw words per turn: 201.6; mean word-limit use: 67.8%.
- Deterministically clipped turns: 10.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 5.97 | 7.58 | -1.62 | -2.22 [-2.48, -1.95] | 6.10 | 5.83 | 20 debates / 58 judge rows |
| Rebuttal quality | 5.43 | 7.59 | -2.16 | -2.97 [-3.27, -2.66] | 5.48 | 5.38 | 20 debates / 58 judge rows |
| Grounding / epistemics | 6.24 | 7.53 | -1.29 | -1.46 [-1.75, -1.17] | 6.34 | 6.14 | 20 debates / 58 judge rows |
| Originality | 5.47 | 7.06 | -1.60 | -1.89 [-2.11, -1.67] | 5.55 | 5.38 | 20 debates / 58 judge rows |
| Rhetorical effectiveness | 6.31 | 7.80 | -1.49 | -1.97 [-2.24, -1.69] | 6.48 | 6.14 | 20 debates / 58 judge rows |

### Judge-panel consensus

- concession: 18/54 judge rows (33.3%); 6/18 debates reached panel majority; mean rebuttal quality advantage -3.02.
- burden handling: 13/54 judge rows (24.1%); 5/18 debates reached panel majority; mean argument strength advantage -2.30.
- dropped argument: 13/54 judge rows (24.1%); 3/18 debates reached panel majority; mean rebuttal quality advantage -3.02.
- repetition: 13/54 judge rows (24.1%); 2/18 debates reached panel majority; mean rhetorical effectiveness advantage -1.96.
- answer quality: 11/54 judge rows (20.4%); 2/18 debates reached panel majority; mean rebuttal quality advantage -3.02.
- argument construction: 11/54 judge rows (20.4%); 2/18 debates reached panel majority; mean argument strength advantage -2.30.
- format compliance: 8/54 judge rows (14.8%); 2/18 debates reached panel majority; mean rhetorical effectiveness advantage -1.96.
- direct engagement: 8/54 judge rows (14.8%); 1/18 debates reached panel majority; mean rebuttal quality advantage -3.02.

### Judge salience

- Full eligible corpus: 110 events across 49 event-bearing judge rows; concession 18/49 (37%), burden handling 13/49 (27%), repetition 13/49 (27%), dropped argument 13/49 (27%), argument construction 11/49 (22%), answer quality 11/49 (22%).

- [all] The judge found CON's pivot to a delay claim about an optional offer unconvincing. Evidence: “pivoting to an unconvincing claim that merely setting up an optional telemedicine offer would somehow cause weeks of delay”
- [all] The judge faulted CON for repeatedly mischaracterizing a declinable offer as compulsory. Evidence: “repeatedly treating a declinable offer as compulsory checkpoint paternalism”

### Blind transcript observations

- Full eligible corpus: 163 events across 18 event-bearing debates; repetition 18/18 (100%), confident specificity 17/18 (94%), dropped argument 16/18 (89%), leaked concession 16/18 (89%), answer type 15/18 (83%), question type 14/18 (78%).

- [all] CON gives a specific cost figure for counseling but offers no source, and the figure assumes attended sessions. Evidence: “Mandatory counseling adds significant cost—often hundreds of dollars per session—and scheduling delays”
- [all] CON raises a slippery-slope precedent concern through rhetorical questions and does not show a mechanism for the expansion. Evidence: “If pre-approval is required for genetic data, what comes next? Blood test results? Imaging scans?”

### Side-swap patterns

- Full eligible corpus: 39 events across 9 event-bearing groups; stable behavior 9/9 (100%), contradiction candidate 7/9 (78%), evidence asymmetry 5/9 (56%), advocacy flexibility 4/9 (44%), side specific behavior 4/9 (44%), tradeoff hiding 1/9 (11%).

- [all] As CON, mistral asks what real constraint a declinable offer imposes, while as PRO it accepts the access-only reading and asserts that access changes the disclosure context.
- [all] Mistral describes counseling costs as significant, at hundreds of dollars, when arguing CON, but calls the cost of providing access negligible when arguing PRO, which is a cross-side tension for open-book review.

### Outcome associations

- Full eligible corpus: 88 links across 18 debates; aligned 18/18 (100%), conflicted 3/18 (17%), unclear 2/18 (11%), judge_disagreement 1/18 (6%).

## GPT-OSS-120B

### Deterministic execution

- Coverage: 10 current-peer debates / 50 turns.
- Mean raw words per turn: 278.2; mean word-limit use: 94.7%.
- Deterministically clipped turns: 54.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 5.27 | 7.58 | -2.32 | -3.00 [-3.41, -2.59] | 5.73 | 4.80 | 10 debates / 30 judge rows |
| Rebuttal quality | 4.67 | 7.59 | -2.92 | -3.77 [-4.33, -3.21] | 5.20 | 4.13 | 10 debates / 30 judge rows |
| Grounding / epistemics | 4.90 | 7.53 | -2.63 | -3.13 [-3.50, -2.77] | 4.80 | 5.00 | 10 debates / 30 judge rows |
| Originality | 5.10 | 7.06 | -1.96 | -2.03 [-2.62, -1.45] | 5.73 | 4.47 | 10 debates / 30 judge rows |
| Rhetorical effectiveness | 5.63 | 7.80 | -2.16 | -2.43 [-2.81, -2.06] | 6.00 | 5.27 | 10 debates / 30 judge rows |

### Judge-panel consensus

- evidence use: 13/30 judge rows (43.3%); 5/10 debates reached panel majority; mean grounding and epistemic discipline advantage -3.13.
- argument construction: 13/30 judge rows (43.3%); 4/10 debates reached panel majority; mean argument strength advantage -3.00.
- concession: 11/30 judge rows (36.7%); 4/10 debates reached panel majority; mean rebuttal quality advantage -3.77.
- format compliance: 9/30 judge rows (30.0%); 2/10 debates reached panel majority; mean rhetorical effectiveness advantage -2.43.
- question quality: 9/30 judge rows (30.0%); 2/10 debates reached panel majority; mean rebuttal quality advantage -3.77.
- dropped argument: 4/30 judge rows (13.3%); 1/10 debates reached panel majority; mean rebuttal quality advantage -3.77.
- factual error: 4/30 judge rows (13.3%); 0/10 debates reached panel majority; mean grounding and epistemic discipline advantage -3.13.
- repetition: 4/30 judge rows (13.3%); 0/10 debates reached panel majority; mean rhetorical effectiveness advantage -2.43.

### Judge salience

- Full eligible corpus: 71 events across 30 event-bearing judge rows; evidence use 13/30 (43%), argument construction 13/30 (43%), concession 11/30 (37%), question quality 9/30 (30%), format compliance 8/30 (27%), dropped argument 4/30 (13%).

- [all] The judge faulted PRO for extrapolating from an addicted subgroup to heavy users generally. Evidence: “Side A was extrapolating outcomes from an already-addicted subgroup”
- [all] The judge faulted PRO's later statistical and neuro claims as falsely precise. Evidence: “added brittle fake precision rather than sealed necessity”

### Blind transcript observations

- Full eligible corpus: 99 events across 10 event-bearing debates; confident specificity 9/10 (90%), repetition 8/10 (80%), leaked concession 8/10 (80%), question type 7/10 (70%), answer type 7/10 (70%), strawman 7/10 (70%).

- [all] PRO cites a specific divorce-rate disparity without naming any study. Evidence: “Studies of couples where one partner meets addiction‑like thresholds for porn report double the divorce rate of couples without such patterns”
- [all] PRO answers CON's correlation-causation objection directly by appealing to longitudinal designs. Evidence: “longitudinal panels that control for baseline satisfaction repeatedly show that increased pornography consumption predicts a later drop in partner‑reported intimacy”

### Side-swap patterns

- Full eligible corpus: 24 events across 5 event-bearing groups; stable behavior 5/5 (100%), contradiction candidate 4/5 (80%), side specific behavior 2/5 (40%), evidence asymmetry 1/5 (20%), moral standard asymmetry 1/5 (20%), tradeoff hiding 1/5 (20%).

- [all] On both sides the model stated empirical findings confidently without naming sources, using precise figures as PRO and general study claims as CON.
- [all] In both closings the model restated earlier points and left the opponent's key rebuttals unanswered.

### Outcome associations

- Full eligible corpus: 49 links across 10 debates; aligned 10/10 (100%), unclear 4/10 (40%), conflicted 1/10 (10%).
