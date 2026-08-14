# Debater Behavior Model Cards

Analyzed with GPT-5.6 Sol (medium) across the complete eligible current-v-current corpus.

Judge opinions and blinded transcript behavior are shown separately. GPT-5.6 Sol (medium) tags the stored judge rationales and the transcripts; a judge-panel consensus event requires matching tags from at least two judges on the same debate. Diagnostic subscore tables show actual 1–10 judge means, current-field deltas, within-judge opponent advantages with debate-clustered intervals, and side splits; these are secondary perceptions, not rating inputs. The consensus denominator includes every eligible annotated judge row, including rows where no event was tagged. Representative and diagnostic samples are reported separately from the full current corpus. Side assignments do not reveal model beliefs, and outcome links are associations rather than causal estimates.

Annotation response coverage: blind transcripts 3,722/3,722 (100.0%); side-swap comparisons 1,861/1,861 (100.0%); outcome links 3,722/3,722 (100.0%).
A valid zero-event, zero-pattern, or zero-link response counts as covered. At 100% coverage, the labeled sections partition the full eligible corpus and should be read together; the sample labels preserve how cases were selected and do not mean the analysis stops at a sample.

## Grok 4.6 (high)

### Deterministic execution

- Coverage: 198 current-peer debates / 990 turns.
- Mean raw words per turn: 233.5; mean word-limit use: 79.9%.
- Deterministically clipped turns: 2.9%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.59 | 7.35 | +0.24 | -0.09 [-0.23, +0.05] | 7.58 | 7.59 | 198 debates / 594 judge rows |
| Rebuttal quality | 7.64 | 7.35 | +0.29 | +0.03 [-0.17, +0.22] | 7.48 | 7.80 | 198 debates / 594 judge rows |
| Grounding / epistemics | 7.64 | 7.28 | +0.36 | +0.07 [-0.03, +0.17] | 7.62 | 7.65 | 198 debates / 594 judge rows |
| Originality | 7.21 | 6.81 | +0.40 | +0.02 [-0.10, +0.14] | 7.07 | 7.34 | 198 debates / 594 judge rows |
| Rhetorical effectiveness | 8.06 | 7.62 | +0.44 | +0.21 [+0.09, +0.33] | 8.15 | 7.96 | 198 debates / 594 judge rows |

### Judge-panel consensus

- direct engagement: 346/594 judge rows (58.2%); 115/198 debates reached panel majority; mean rebuttal quality advantage +0.03.
- argument construction: 292/594 judge rows (49.2%); 95/198 debates reached panel majority; mean argument strength advantage -0.09.
- weighing: 110/594 judge rows (18.5%); 21/198 debates reached panel majority; mean argument strength advantage -0.09.
- burden handling: 107/594 judge rows (18.0%); 21/198 debates reached panel majority; mean argument strength advantage -0.09.
- answer quality: 93/594 judge rows (15.7%); 15/198 debates reached panel majority; mean rebuttal quality advantage +0.03.
- rhetoric: 79/594 judge rows (13.3%); 11/198 debates reached panel majority; mean rhetorical effectiveness advantage +0.21.
- concession: 77/594 judge rows (13.0%); 19/198 debates reached panel majority; mean rebuttal quality advantage +0.03.
- dropped argument: 56/594 judge rows (9.4%); 5/198 debates reached panel majority; mean rebuttal quality advantage +0.03.

### Judge salience

- Full eligible corpus: 1465 events across 565 event-bearing judge rows; direct engagement 344/565 (61%), argument construction 282/565 (50%), weighing 110/565 (19%), burden handling 107/565 (19%), answer quality 93/565 (16%), rhetoric 79/565 (14%).

- [all] CON presented a consistent mechanism for why the generational split would undermine the policy. Evidence: “CON built a consistent, mechanistic case”
- [all] CON identified an internal tension in PRO’s grandfathering and demand claims. Evidence: “CON's Rebuttal 2 also exposed a real tension in PRO's position”

### Blind transcript observations

- Full eligible corpus: 1806 events across 198 event-bearing debates; question type 198/198 (100%), direct engagement 193/198 (97%), answer type 186/198 (94%), weighing 174/198 (88%), strategic concession 136/198 (69%), burden setting 113/198 (57%).

- [all] CON contests the comparison by arguing that conventional age restrictions operate alongside other controls. Evidence: “The motion smuggles a false choice. No serious program relies only on an age number.”
- [all] CON foregrounds permanent unequal treatment as a cost of the proposed policy. Evidence: “The proposal treats two equally competent adults differently forever because one was born a day after an arbitrary cutoff.”

### Side-swap patterns

- Full eligible corpus: 343 events across 99 event-bearing groups; stable behavior 98/99 (99%), advocacy flexibility 63/99 (64%), contradiction candidate 60/99 (61%), moral standard asymmetry 28/99 (28%), evidence asymmetry 22/99 (22%), side specific behavior 18/99 (18%).

- [all] As CON the model emphasized a durable lawful reservoir and growing banned-cohort demand, while as PRO it argued that leakage could not recreate a recurring customer base, creating a contradiction candidate for open-book review.
- [all] As CON the model foregrounded permanent unequal treatment, while as PRO it shifted emphasis to whether occasional leakage could sustain market-scale demand.

### Outcome associations

- Full eligible corpus: 921 links across 198 debates; aligned 176/198 (89%), judge_disagreement 77/198 (39%), conflicted 73/198 (37%), unclear 5/198 (3%).

## Gemini 3.7 Flash (high)

### Deterministic execution

- Coverage: 198 current-peer debates / 990 turns.
- Mean raw words per turn: 223.1; mean word-limit use: 77.5%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.89 | 7.35 | -0.45 | -0.96 [-1.07, -0.84] | 7.04 | 6.75 | 198 debates / 594 judge rows |
| Rebuttal quality | 6.55 | 7.35 | -0.80 | -1.45 [-1.60, -1.30] | 6.57 | 6.52 | 198 debates / 594 judge rows |
| Grounding / epistemics | 6.96 | 7.28 | -0.32 | -0.65 [-0.75, -0.56] | 7.05 | 6.86 | 198 debates / 594 judge rows |
| Originality | 6.24 | 6.81 | -0.57 | -1.02 [-1.12, -0.92] | 6.24 | 6.23 | 198 debates / 594 judge rows |
| Rhetorical effectiveness | 7.19 | 7.62 | -0.42 | -0.82 [-0.93, -0.72] | 7.33 | 7.05 | 198 debates / 594 judge rows |

### Judge-panel consensus

- argument construction: 204/594 judge rows (34.3%); 58/198 debates reached panel majority; mean argument strength advantage -0.96.
- direct engagement: 194/594 judge rows (32.7%); 58/198 debates reached panel majority; mean rebuttal quality advantage -1.45.
- burden handling: 156/594 judge rows (26.3%); 41/198 debates reached panel majority; mean argument strength advantage -0.96.
- dropped argument: 143/594 judge rows (24.1%); 34/198 debates reached panel majority; mean rebuttal quality advantage -1.45.
- answer quality: 122/594 judge rows (20.5%); 25/198 debates reached panel majority; mean rebuttal quality advantage -1.45.
- concession: 87/594 judge rows (14.6%); 25/198 debates reached panel majority; mean rebuttal quality advantage -1.45.
- evidence use: 71/594 judge rows (12.0%); 14/198 debates reached panel majority; mean grounding and epistemic discipline advantage -0.65.
- repetition: 70/594 judge rows (11.8%); 12/198 debates reached panel majority; mean rhetorical effectiveness advantage -0.82.

### Judge salience

- Full eligible corpus: 1287 events across 583 event-bearing judge rows; argument construction 203/583 (35%), direct engagement 194/583 (33%), burden handling 156/583 (27%), dropped argument 143/583 (25%), answer quality 121/583 (21%), concession 87/583 (15%).

- [all] CON failed to provide an example meeting the relevant technical standard. Evidence: “A never produced a real internet-scale messaging example that survived adversarial review”
- [all] CON left the authoritarian copycat-access concern essentially unanswered. Evidence: “pressure on authoritarian copycat access went essentially unanswered”

### Blind transcript observations

- Full eligible corpus: 1762 events across 198 event-bearing debates; question type 196/198 (99%), direct engagement 191/198 (96%), answer type 189/198 (95%), weighing 159/198 (80%), burden setting 105/198 (53%), burden contest 101/198 (51%).

- [all] CON frames the proposition as categorically obstructing judicial authority. Evidence: “Banning law enforcement access mechanisms categorically strips democratic societies of the ability to enforce judicial orders in the digital sphere, regardless of the severity of the crime.”
- [all] CON contests PRO’s migration premise by disputing its characterization of offenders. Evidence: “PRO’s core premise—that bad actors are all elite cryptographers who will easily bypass commercial apps—fundamentally ignores how modern crime functions.”

### Side-swap patterns

- Full eligible corpus: 367 events across 99 event-bearing groups; stable behavior 97/99 (98%), contradiction candidate 80/99 (81%), advocacy flexibility 52/99 (53%), evidence asymmetry 34/99 (34%), side specific behavior 27/99 (27%), moral standard asymmetry 22/99 (22%).

- [all] Gemini consistently emphasizes differences in mechanism and weighs investigative effects against population-scale security consequences.
- [all] Gemini’s CON case says threshold architectures and localized shares avoid universal access, while its PRO case characterizes institutional access as a globally coercible or stealable universal target.

### Outcome associations

- Full eligible corpus: 848 links across 197 debates; aligned 176/197 (89%), conflicted 122/197 (62%), judge_disagreement 48/197 (24%), unclear 3/197 (2%).

## DeepSeek V4 Pro 0813 (high)

### Deterministic execution

- Coverage: 200 current-peer debates / 1,000 turns.
- Mean raw words per turn: 228.7; mean word-limit use: 79.2%.
- Deterministically clipped turns: 2.8%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.44 | 7.35 | +0.09 | -0.28 [-0.43, -0.13] | 7.53 | 7.35 | 200 debates / 600 judge rows |
| Rebuttal quality | 7.41 | 7.35 | +0.07 | -0.35 [-0.54, -0.17] | 7.39 | 7.44 | 200 debates / 600 judge rows |
| Grounding / epistemics | 7.58 | 7.28 | +0.30 | +0.02 [-0.09, +0.13] | 7.62 | 7.54 | 200 debates / 600 judge rows |
| Originality | 6.92 | 6.81 | +0.11 | -0.35 [-0.47, -0.23] | 6.90 | 6.93 | 200 debates / 600 judge rows |
| Rhetorical effectiveness | 7.55 | 7.62 | -0.06 | -0.47 [-0.59, -0.35] | 7.67 | 7.44 | 200 debates / 600 judge rows |

### Judge-panel consensus

- direct engagement: 279/600 judge rows (46.5%); 91/200 debates reached panel majority; mean rebuttal quality advantage -0.35.
- argument construction: 271/600 judge rows (45.2%); 90/200 debates reached panel majority; mean argument strength advantage -0.28.
- burden handling: 154/600 judge rows (25.7%); 33/200 debates reached panel majority; mean argument strength advantage -0.28.
- concession: 104/600 judge rows (17.3%); 27/200 debates reached panel majority; mean rebuttal quality advantage -0.35.
- weighing: 98/600 judge rows (16.3%); 24/200 debates reached panel majority; mean argument strength advantage -0.28.
- answer quality: 85/600 judge rows (14.2%); 15/200 debates reached panel majority; mean rebuttal quality advantage -0.35.
- clarity: 43/600 judge rows (7.2%); 6/200 debates reached panel majority; mean rhetorical effectiveness advantage -0.47.
- dropped argument: 42/600 judge rows (7.0%); 4/200 debates reached panel majority; mean rebuttal quality advantage -0.35.

### Judge salience

- Full eligible corpus: 1261 events across 557 event-bearing judge rows; direct engagement 277/557 (50%), argument construction 265/557 (48%), burden handling 154/557 (28%), concession 104/557 (19%), weighing 98/557 (18%), answer quality 83/557 (15%).

- [all] PRO maintained a distinction between investigation and automatic liability. Evidence: “preserving the distinction between scrutiny and automatic liability”
- [all] PRO supplied a plausible mechanism for treating the software as a common-agent channel. Evidence: “pooled confidential forward-looking data, reciprocal awareness, and adoption can make software a common-agent channel”

### Blind transcript observations

- Full eligible corpus: 1832 events across 200 event-bearing debates; question type 200/200 (100%), direct engagement 199/200 (100%), answer type 189/200 (94%), weighing 189/200 (94%), strategic concession 136/200 (68%), burden contest 118/200 (59%).

- [all] PRO frames the dispute around whether pooled confidential inputs and common recommendations constitute an agreement. Evidence: “That is a hub-and-spoke agreement, not independent decision-making.”
- [all] PRO specifies several mechanisms by which a shared tool could stabilize aligned pricing. Evidence: “it detects discounting, flags deviations, and recalibrates rents to maximize aggregate landlord revenue.”

### Side-swap patterns

- Full eligible corpus: 343 events across 100 event-bearing groups; stable behavior 100/100 (100%), advocacy flexibility 72/100 (72%), contradiction candidate 53/100 (53%), evidence asymmetry 23/100 (23%), moral standard asymmetry 19/100 (19%), side specific behavior 16/100 (16%).

- [all] The model consistently operationalizes algorithmic coordination through mechanisms such as monitoring discounting, recalibration, and pressure for adherence, while assigning them different argumentative significance by side.
- [all] As PRO the model characterizes pooled confidential inputs and coordinated output as a hub-and-spoke agreement, whereas as CON it requires separate proof of mutual commitment beyond shared inputs and similar outputs.

### Outcome associations

- Full eligible corpus: 915 links across 200 debates; aligned 174/200 (87%), conflicted 84/200 (42%), judge_disagreement 58/200 (29%), unclear 3/200 (2%).

## Qwen 3.8 Max

### Deterministic execution

- Coverage: 230 current-peer debates / 1,150 turns.
- Mean raw words per turn: 234.6; mean word-limit use: 79.9%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.28 | 7.35 | -0.07 | -0.35 [-0.49, -0.22] | 7.33 | 7.23 | 230 debates / 690 judge rows |
| Rebuttal quality | 7.23 | 7.35 | -0.12 | -0.43 [-0.61, -0.26] | 7.16 | 7.29 | 230 debates / 690 judge rows |
| Grounding / epistemics | 7.40 | 7.28 | +0.12 | +0.02 [-0.08, +0.11] | 7.44 | 7.37 | 230 debates / 690 judge rows |
| Originality | 6.66 | 6.81 | -0.15 | -0.51 [-0.61, -0.40] | 6.64 | 6.68 | 230 debates / 690 judge rows |
| Rhetorical effectiveness | 7.39 | 7.62 | -0.23 | -0.50 [-0.61, -0.39] | 7.48 | 7.29 | 230 debates / 690 judge rows |

### Judge-panel consensus

- argument construction: 350/690 judge rows (50.7%); 114/230 debates reached panel majority; mean argument strength advantage -0.35.
- direct engagement: 285/690 judge rows (41.3%); 87/230 debates reached panel majority; mean rebuttal quality advantage -0.43.
- burden handling: 200/690 judge rows (29.0%); 52/230 debates reached panel majority; mean argument strength advantage -0.35.
- concession: 133/690 judge rows (19.3%); 35/230 debates reached panel majority; mean rebuttal quality advantage -0.43.
- answer quality: 133/690 judge rows (19.3%); 28/230 debates reached panel majority; mean rebuttal quality advantage -0.43.
- weighing: 114/690 judge rows (16.5%); 28/230 debates reached panel majority; mean argument strength advantage -0.35.
- dropped argument: 77/690 judge rows (11.2%); 9/230 debates reached panel majority; mean rebuttal quality advantage -0.43.
- clarity: 35/690 judge rows (5.1%); 2/230 debates reached panel majority; mean rhetorical effectiveness advantage -0.50.

### Judge salience

- Representative sample: 38 events across 16 event-bearing judge rows; argument construction 9/16 (56%), direct engagement 8/16 (50%), burden handling 7/16 (44%), concession 3/16 (19%), answer quality 3/16 (19%), factual error 1/16 (6%).
- Diagnostic sample: 22 events across 11 event-bearing judge rows; argument construction 6/11 (55%), direct engagement 5/11 (45%), concession 4/11 (36%), burden handling 3/11 (27%), dropped argument 2/11 (18%), answer quality 1/11 (9%).
- Full current corpus: 1448 events across 617 event-bearing judge rows; argument construction 322/617 (52%), direct engagement 268/617 (43%), burden handling 190/617 (31%), answer quality 128/617 (21%), concession 125/617 (20%), weighing 113/617 (18%).

- [representative] CON established a categorical distinction between gene-drive releases and reversible interventions. Evidence: “a self-propagating outdoor release is not like nets, vaccines, or sterile-insect trials”
- [representative] CON directly challenged PRO’s regulated-learning frame by emphasizing potential irreversibility. Evidence: ““learn by releasing under tight regulation” quietly converts the trial into potential permanence”
- [diagnostic] PRO supplied a concession that CON used to undermine the savings claim. Evidence: “PRO conceded one $150k cascade offsets only 30-50 patient-years”

### Blind transcript observations

- Representative sample: 182 events across 20 event-bearing debates; weighing 20/20 (100%), direct engagement 20/20 (100%), question type 20/20 (100%), answer type 20/20 (100%), strategic concession 13/20 (65%), burden contest 10/20 (50%).
- Diagnostic sample: 228 events across 24 event-bearing debates; direct engagement 24/24 (100%), question type 24/24 (100%), answer type 24/24 (100%), weighing 21/24 (88%), strategic concession 16/24 (67%), progression 14/24 (58%).
- Full current corpus: 1700 events across 186 event-bearing debates; question type 185/186 (99%), answer type 182/186 (98%), direct engagement 179/186 (96%), weighing 170/186 (91%), strategic concession 144/186 (77%), burden setting 104/186 (56%).

- [representative] CON reframes the dispute around marginal behavioral effects rather than total child-rearing costs. Evidence: “The question is not whether children are expensive; it is which instrument changes behavior at the margin.”
- [representative] CON establishes immediacy, flexibility, and implementation difficulty as comparative criteria. Evidence: “Cash wins because it is immediate, flexible, and administratively simple, while housing and childcare reform is slow, locally contested, and often captured by price increases.”
- [diagnostic] CON concedes possible abuses while redirecting evaluation toward the effects of a blanket ban. Evidence: “The decisive question is not whether personalized pricing can be intrusive or unfair; it is whether a blanket ban makes consumers better off.”

### Side-swap patterns

- Representative sample: 40 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 8/10 (80%), contradiction candidate 6/10 (60%), moral standard asymmetry 5/10 (50%), tradeoff hiding 3/10 (30%), evidence asymmetry 1/10 (10%).
- Diagnostic sample: 43 events across 12 event-bearing groups; stable behavior 12/12 (100%), contradiction candidate 9/12 (75%), advocacy flexibility 6/12 (50%), moral standard asymmetry 3/12 (25%), evidence asymmetry 3/12 (25%).
- Full current corpus: 349 events across 93 event-bearing groups; stable behavior 93/93 (100%), advocacy flexibility 65/93 (70%), contradiction candidate 56/93 (60%), evidence asymmetry 31/93 (33%), moral standard asymmetry 25/93 (27%), side specific behavior 12/93 (13%).

- [representative] Qwen consistently frames the comparison around which policy changes couples’ decisions at the margin.
- [representative] Qwen concedes the absence of clean completed-fertility evidence while defending cash as CON but demands durable life-course effects from cash as PRO.
- [diagnostic] As CON, qwen3.8-max says a ban destroys beneficial discounts, while as PRO it says only secret maximum-extraction pricing is lost, creating a factual scope tension for open-book review.

### Outcome associations

- Representative sample: 153 links across 20 debates; aligned 19/20 (95%), conflicted 13/20 (65%), unclear 7/20 (35%), judge_disagreement 6/20 (30%).
- Diagnostic sample: 185 links across 24 debates; aligned 23/24 (96%), judge_disagreement 14/24 (58%), conflicted 9/24 (38%), unclear 7/24 (29%).
- Full current corpus: 895 links across 185 debates; aligned 167/185 (90%), conflicted 73/185 (39%), judge_disagreement 52/185 (28%), unclear 4/185 (2%).

## Claude Opus 5 (high)

### Deterministic execution

- Coverage: 278 current-peer debates / 1,390 turns.
- Mean raw words per turn: 263.1; mean word-limit use: 92.2%.
- Deterministically clipped turns: 23.1%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 8.14 | 7.35 | +0.80 | +1.08 [+0.97, +1.20] | 8.16 | 8.12 | 278 debates / 834 judge rows |
| Rebuttal quality | 8.22 | 7.35 | +0.88 | +1.25 [+1.10, +1.40] | 8.16 | 8.29 | 278 debates / 834 judge rows |
| Grounding / epistemics | 7.88 | 7.28 | +0.60 | +0.62 [+0.53, +0.72] | 7.91 | 7.86 | 278 debates / 834 judge rows |
| Originality | 7.78 | 6.81 | +0.97 | +1.15 [+1.05, +1.24] | 7.68 | 7.87 | 278 debates / 834 judge rows |
| Rhetorical effectiveness | 8.43 | 7.62 | +0.82 | +1.03 [+0.94, +1.13] | 8.47 | 8.40 | 278 debates / 834 judge rows |

### Judge-panel consensus

- direct engagement: 622/834 judge rows (74.6%); 222/278 debates reached panel majority; mean rebuttal quality advantage +1.25.
- argument construction: 446/834 judge rows (53.5%); 148/278 debates reached panel majority; mean argument strength advantage +1.08.
- weighing: 362/834 judge rows (43.4%); 106/278 debates reached panel majority; mean argument strength advantage +1.08.
- burden handling: 150/834 judge rows (18.0%); 33/278 debates reached panel majority; mean argument strength advantage +1.08.
- format compliance: 124/834 judge rows (14.9%); 30/278 debates reached panel majority; mean rhetorical effectiveness advantage +1.03.
- clarity: 118/834 judge rows (14.1%); 29/278 debates reached panel majority; mean rhetorical effectiveness advantage +1.03.
- question quality: 95/834 judge rows (11.4%); 17/278 debates reached panel majority; mean rebuttal quality advantage +1.25.
- rhetoric: 95/834 judge rows (11.4%); 17/278 debates reached panel majority; mean rhetorical effectiveness advantage +1.03.

### Judge salience

- Representative sample: 41 events across 13 event-bearing judge rows; direct engagement 12/13 (92%), weighing 7/13 (54%), argument construction 5/13 (38%), clarity 4/13 (31%), concession 2/13 (15%), evidence use 2/13 (15%).
- Diagnostic sample: 144 events across 45 event-bearing judge rows; direct engagement 35/45 (78%), argument construction 34/45 (76%), weighing 13/45 (29%), question quality 12/45 (27%), clarity 10/45 (22%), rhetoric 7/45 (16%).
- Full current corpus: 2374 events across 758 event-bearing judge rows; direct engagement 575/758 (76%), argument construction 407/758 (54%), weighing 342/758 (45%), burden handling 146/758 (19%), format compliance 111/758 (15%), clarity 101/758 (13%).

- [representative] CON persuasively identified transparency and social-proof costs from hiding metrics. Evidence: “A compellingly established real transparency and social-proof costs”
- [representative] CON overstated the remedy’s ineffectiveness because viewer-side hiding still reduced broad exposure. Evidence: “overstated that the remedy reaches none of B's harms”
- [diagnostic] CON established that limiting fixed premium rooms would not create additional standard-room screenings. Evidence: “fixed premium auditoriums do not displace prime-time screenings in the many remaining standard rooms”

### Blind transcript observations

- Representative sample: 238 events across 24 event-bearing debates; direct engagement 24/24 (100%), question type 24/24 (100%), weighing 23/24 (96%), answer type 22/24 (92%), progression 18/24 (75%), burden setting 15/24 (62%).
- Diagnostic sample: 243 events across 24 event-bearing debates; direct engagement 24/24 (100%), question type 24/24 (100%), weighing 22/24 (92%), answer type 20/24 (83%), progression 15/24 (62%), burden contest 14/24 (58%).
- Full current corpus: 2274 events across 230 event-bearing debates; question type 230/230 (100%), direct engagement 226/230 (98%), weighing 219/230 (95%), answer type 205/230 (89%), strategic concession 139/230 (60%), burden contest 139/230 (60%).

- [representative] PRO frames the dispute around whether families or platforms should bear the implementation burden. Evidence: “Worse, controls put the burden in exactly the wrong place.”
- [representative] PRO weighs a shared legal rule against household-level controls through collective-action effects. Evidence: “That is a classic coordination trap, and coordination traps are precisely what law exists to solve.”
- [diagnostic] PRO precisely limits the proposition to whether new nuclear must remain central in most countries. Evidence: “The proposition is not "nuclear is evil." It is narrower and stronger: in most countries, a decarbonization plan built around new nuclear is no longer the necessary path, because something cheaper and faster arrived.”

### Side-swap patterns

- Representative sample: 41 events across 12 event-bearing groups; stable behavior 12/12 (100%), advocacy flexibility 8/12 (67%), contradiction candidate 6/12 (50%), moral standard asymmetry 3/12 (25%), evidence asymmetry 2/12 (17%), side specific behavior 1/12 (8%).
- Diagnostic sample: 44 events across 12 event-bearing groups; stable behavior 12/12 (100%), advocacy flexibility 8/12 (67%), contradiction candidate 5/12 (42%), moral standard asymmetry 4/12 (33%), side specific behavior 3/12 (25%), evidence asymmetry 2/12 (17%).
- Full current corpus: 420 events across 115 event-bearing groups; stable behavior 115/115 (100%), advocacy flexibility 75/115 (65%), contradiction candidate 67/115 (58%), evidence asymmetry 37/115 (32%), moral standard asymmetry 28/115 (24%), side specific behavior 20/115 (17%).

- [representative] The model consistently weighs policies through comparative burdens, implementation effects, and failure modes on both sides.
- [representative] The model concedes a limited opposing concern in each role and then uses the concession to sharpen its preferred comparison.
- [diagnostic] Across sides, the model tests opposing claims by requesting concrete examples or replacement plans.

### Outcome associations

- Representative sample: 184 links across 24 debates; aligned 22/24 (92%), conflicted 8/24 (33%), unclear 6/24 (25%), judge_disagreement 6/24 (25%).
- Diagnostic sample: 189 links across 24 debates; aligned 23/24 (96%), judge_disagreement 14/24 (58%), conflicted 9/24 (38%), unclear 6/24 (25%).
- Full current corpus: 1283 links across 230 debates; aligned 221/230 (96%), judge_disagreement 55/230 (24%), conflicted 46/230 (20%), unclear 4/230 (2%).

## Kimi K3

### Deterministic execution

- Coverage: 282 current-peer debates / 1,410 turns.
- Mean raw words per turn: 248.6; mean word-limit use: 86.6%.
- Deterministically clipped turns: 5.5%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 8.10 | 7.35 | +0.75 | +1.09 [+0.97, +1.20] | 8.08 | 8.12 | 282 debates / 843 judge rows |
| Rebuttal quality | 8.24 | 7.35 | +0.89 | +1.44 [+1.29, +1.59] | 8.14 | 8.34 | 282 debates / 843 judge rows |
| Grounding / epistemics | 7.81 | 7.28 | +0.53 | +0.68 [+0.59, +0.78] | 7.77 | 7.84 | 282 debates / 843 judge rows |
| Originality | 7.50 | 6.81 | +0.69 | +0.89 [+0.78, +1.00] | 7.38 | 7.61 | 282 debates / 843 judge rows |
| Rhetorical effectiveness | 8.36 | 7.62 | +0.74 | +1.06 [+0.95, +1.16] | 8.36 | 8.35 | 282 debates / 843 judge rows |

### Judge-panel consensus

- direct engagement: 633/843 judge rows (75.1%); 228/282 debates reached panel majority; mean rebuttal quality advantage +1.44.
- argument construction: 487/843 judge rows (57.8%); 165/282 debates reached panel majority; mean argument strength advantage +1.09.
- weighing: 314/843 judge rows (37.2%); 101/282 debates reached panel majority; mean argument strength advantage +1.09.
- answer quality: 156/843 judge rows (18.5%); 33/282 debates reached panel majority; mean rebuttal quality advantage +1.44.
- burden handling: 143/843 judge rows (17.0%); 34/282 debates reached panel majority; mean argument strength advantage +1.09.
- question quality: 121/843 judge rows (14.4%); 18/282 debates reached panel majority; mean rebuttal quality advantage +1.44.
- evidence use: 89/843 judge rows (10.6%); 17/282 debates reached panel majority; mean grounding and epistemic discipline advantage +0.68.
- rhetoric: 88/843 judge rows (10.4%); 10/282 debates reached panel majority; mean rhetorical effectiveness advantage +1.06.

### Judge salience

- Representative sample: 84 events across 24 event-bearing judge rows; argument construction 20/24 (83%), direct engagement 20/24 (83%), question quality 6/24 (25%), weighing 6/24 (25%), rhetoric 5/24 (21%), burden handling 4/24 (17%).
- Diagnostic sample: 79 events across 26 event-bearing judge rows; direct engagement 23/26 (88%), argument construction 18/26 (69%), weighing 11/26 (42%), question quality 6/26 (23%), clarity 5/26 (19%), answer quality 3/26 (12%).
- Full current corpus: 2383 events across 775 event-bearing judge rows; direct engagement 590/775 (76%), argument construction 439/775 (57%), weighing 297/775 (38%), answer quality 147/775 (19%), burden handling 138/775 (18%), question quality 108/775 (14%).

- [representative] CON used PRO’s concession to reframe the dispute around labeling rather than harm. Evidence: “B wins because A conceded time-based variation is acceptable in [A2.1], allowing B to reframe the debate as anchor-labeling not harm.”
- [representative] CON’s pressure questioning exposed a gap in PRO’s definition of aggressive pricing. Evidence: “B's pressure exposed the core gap”
- [diagnostic] PRO supplied a coherent causal mechanism from leverage to care-facility harms. Evidence: “a coherent mechanism linking leveraged ownership to staffing cuts and insolvency”

### Blind transcript observations

- Representative sample: 173 events across 18 event-bearing debates; direct engagement 18/18 (100%), question type 17/18 (94%), answer type 17/18 (94%), weighing 16/18 (89%), burden setting 10/18 (56%), burden contest 9/18 (50%).
- Diagnostic sample: 385 events across 40 event-bearing debates; direct engagement 39/40 (98%), question type 39/40 (98%), answer type 36/40 (90%), weighing 35/40 (88%), strategic concession 26/40 (65%), burden contest 24/40 (60%).
- Full current corpus: 2212 events across 224 event-bearing debates; question type 224/224 (100%), direct engagement 219/224 (98%), weighing 210/224 (94%), answer type 202/224 (90%), burden contest 132/224 (59%), strategic concession 128/224 (57%).

- [representative] CON contests PRO’s validity-only standard by requiring comparative net harm. Evidence: “Finally, the burden: to justify "stop," PRO must show continued use is net harmful, not merely imperfect.”
- [representative] CON directly reframes PRO’s characterization of perceived usefulness as a concrete conversational mechanism. Evidence: “PRO calls this "feeling useful," but a common language that lowers the cost of hard conversations is a mechanism, not an illusion.”
- [diagnostic] CON contests new-build relevance by applying the proposition’s stated time window. Evidence: “a layer that arrives after the clock runs out cuts zero emissions in the period we're judging.”

### Side-swap patterns

- Representative sample: 32 events across 9 event-bearing groups; stable behavior 9/9 (100%), advocacy flexibility 6/9 (67%), contradiction candidate 6/9 (67%), moral standard asymmetry 2/9 (22%), side specific behavior 2/9 (22%), tradeoff hiding 1/9 (11%).
- Diagnostic sample: 71 events across 20 event-bearing groups; stable behavior 20/20 (100%), advocacy flexibility 14/20 (70%), contradiction candidate 11/20 (55%), evidence asymmetry 7/20 (35%), side specific behavior 5/20 (25%), moral standard asymmetry 2/20 (10%).
- Full current corpus: 419 events across 112 event-bearing groups; stable behavior 112/112 (100%), advocacy flexibility 75/112 (67%), contradiction candidate 70/112 (62%), evidence asymmetry 46/112 (41%), moral standard asymmetry 31/112 (28%), side specific behavior 22/112 (20%).

- [representative] As CON the model required PRO to establish comparative net harm, while as PRO it assigned CON the burden of demonstrating predictive value.
- [representative] The model characterized type changes on retesting as correct detection of weak preferences when CON but as measurement noise when PRO, creating a contradiction candidate for open-book review.
- [diagnostic] Across both sides, the model consistently emphasizes in-window timing and emissions displaced per dollar.

### Outcome associations

- Representative sample: 129 links across 18 debates; aligned 17/18 (94%), judge_disagreement 6/18 (33%), unclear 4/18 (22%), conflicted 3/18 (17%).
- Diagnostic sample: 330 links across 40 debates; aligned 37/40 (92%), judge_disagreement 21/40 (52%), unclear 16/40 (40%), conflicted 9/40 (22%).
- Full current corpus: 1240 links across 223 debates; aligned 217/223 (97%), judge_disagreement 38/223 (17%), conflicted 31/223 (14%), unclear 2/223 (1%).

## GPT-5.6 Sol (high)

### Deterministic execution

- Coverage: 298 current-peer debates / 1,490 turns.
- Mean raw words per turn: 251.4; mean word-limit use: 85.7%.
- Deterministically clipped turns: 14.6%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.82 | 7.35 | +0.47 | +0.74 [+0.61, +0.86] | 7.80 | 7.83 | 298 debates / 894 judge rows |
| Rebuttal quality | 7.87 | 7.35 | +0.52 | +0.96 [+0.80, +1.11] | 7.79 | 7.94 | 298 debates / 894 judge rows |
| Grounding / epistemics | 7.76 | 7.28 | +0.48 | +0.55 [+0.45, +0.65] | 7.74 | 7.78 | 298 debates / 894 judge rows |
| Originality | 7.07 | 6.81 | +0.26 | +0.43 [+0.32, +0.54] | 6.98 | 7.16 | 298 debates / 894 judge rows |
| Rhetorical effectiveness | 7.67 | 7.62 | +0.05 | +0.16 [+0.05, +0.28] | 7.74 | 7.60 | 298 debates / 894 judge rows |

### Judge-panel consensus

- direct engagement: 639/894 judge rows (71.5%); 228/298 debates reached panel majority; mean rebuttal quality advantage +0.96.
- argument construction: 526/894 judge rows (58.8%); 183/298 debates reached panel majority; mean argument strength advantage +0.74.
- weighing: 320/894 judge rows (35.8%); 100/298 debates reached panel majority; mean argument strength advantage +0.74.
- answer quality: 152/894 judge rows (17.0%); 26/298 debates reached panel majority; mean rebuttal quality advantage +0.96.
- burden handling: 143/894 judge rows (16.0%); 27/298 debates reached panel majority; mean argument strength advantage +0.74.
- format compliance: 120/894 judge rows (13.4%); 25/298 debates reached panel majority; mean rhetorical effectiveness advantage +0.16.
- clarity: 119/894 judge rows (13.3%); 26/298 debates reached panel majority; mean rhetorical effectiveness advantage +0.16.
- concession: 94/894 judge rows (10.5%); 19/298 debates reached panel majority; mean rebuttal quality advantage +0.96.

### Judge salience

- Representative sample: 66 events across 19 event-bearing judge rows; argument construction 17/19 (89%), direct engagement 16/19 (84%), weighing 8/19 (42%), answer quality 5/19 (26%), clarity 4/19 (21%), question quality 4/19 (21%).
- Diagnostic sample: 33 events across 12 event-bearing judge rows; direct engagement 11/12 (92%), weighing 6/12 (50%), argument construction 5/12 (42%), burden handling 2/12 (17%), answer quality 2/12 (17%), concession 1/12 (8%).
- Full current corpus: 2454 events across 843 event-bearing judge rows; direct engagement 612/843 (73%), argument construction 497/843 (59%), weighing 306/843 (36%), answer quality 145/843 (17%), burden handling 138/843 (16%), clarity 106/843 (13%).

- [representative] PRO built a clear cost-internalization case linking vehicle size to higher public costs. Evidence: “larger vehicles use more curb and impose greater crash/ wear costs, so equal fees are a subsidy, not neutrality”
- [representative] PRO answered the pay-to-play objection by explaining the policy's marginal behavioral and funding effects. Evidence: “fees don't waive safety rules, they change marginal purchase/trip decisions and fund design”
- [diagnostic] CON showed that methane potency alone did not establish greater per-dollar near-term benefits. Evidence: “exposing the central missing comparative in Side A's case”

### Blind transcript observations

- Representative sample: 213 events across 22 event-bearing debates; question type 22/22 (100%), weighing 22/22 (100%), direct engagement 21/22 (95%), answer type 21/22 (95%), strategic concession 18/22 (82%), burden contest 13/22 (59%).
- Diagnostic sample: 278 events across 30 event-bearing debates; direct engagement 30/30 (100%), question type 30/30 (100%), answer type 30/30 (100%), weighing 28/30 (93%), burden setting 20/30 (67%), burden contest 16/30 (53%).
- Full current corpus: 2333 events across 246 event-bearing debates; question type 246/246 (100%), direct engagement 245/246 (100%), weighing 236/246 (96%), answer type 233/246 (95%), strategic concession 179/246 (73%), burden contest 146/246 (59%).

- [representative] CON contests PRO’s analogy-based standard and substitutes activity-specific regulatory fit. Evidence: “But regulation should follow the specific risk-generating activity, not the nearest historical analogy.”
- [representative] CON distinguishes opposition to inherited institutional treatment from opposition to regulation itself. Evidence: “Rejecting bank or money-market-fund treatment does not mean leaving issuers unregulated; it means using rules designed for stablecoins.”
- [diagnostic] CON contests whether successful identity enrollment is an adequate proxy for safety. Evidence: “Mandatory identity gates confuse knowing that an account passed a check with knowing that the person is safe.”

### Side-swap patterns

- Representative sample: 41 events across 11 event-bearing groups; stable behavior 11/11 (100%), advocacy flexibility 10/11 (91%), moral standard asymmetry 5/11 (45%), contradiction candidate 3/11 (27%), side specific behavior 1/11 (9%), tradeoff hiding 1/11 (9%).
- Diagnostic sample: 49 events across 15 event-bearing groups; stable behavior 15/15 (100%), advocacy flexibility 11/15 (73%), contradiction candidate 4/15 (27%), side specific behavior 3/15 (20%), evidence asymmetry 2/15 (13%), moral standard asymmetry 2/15 (13%).
- Full current corpus: 418 events across 123 event-bearing groups; stable behavior 123/123 (100%), advocacy flexibility 86/123 (70%), contradiction candidate 65/123 (53%), moral standard asymmetry 24/123 (20%), evidence asymmetry 23/123 (19%), side specific behavior 8/123 (7%).

- [representative] Across sides, the model favors activity- and risk-specific tailoring over mechanically equating stablecoin issuers with an inherited institutional category.
- [representative] As CON the model uses tailoring to reject bank or MMF treatment, while as PRO it uses tailoring to defend a bank- or MMF-like regulatory comparison.
- [diagnostic] As CON it argued that collection and retention create unavoidable linkage risks and an auditability dilemma, whereas as PRO it treated non-retention and enforcement mechanisms as adequate protections, creating a candidate for open-book review.

### Outcome associations

- Representative sample: 190 links across 22 debates; aligned 22/22 (100%), unclear 6/22 (27%), judge_disagreement 5/22 (23%), conflicted 3/22 (14%).
- Diagnostic sample: 232 links across 30 debates; aligned 28/30 (93%), judge_disagreement 16/30 (53%), conflicted 11/30 (37%), unclear 9/30 (30%).
- Full current corpus: 1396 links across 246 debates; aligned 229/246 (93%), judge_disagreement 59/246 (24%), conflicted 43/246 (17%), unclear 2/246 (1%).

## Muse Spark 1.1 (high)

### Deterministic execution

- Coverage: 300 current-peer debates / 1,500 turns.
- Mean raw words per turn: 228.6; mean word-limit use: 79.2%.
- Deterministically clipped turns: 0.9%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.91 | 7.35 | +0.56 | +0.72 [+0.60, +0.84] | 7.93 | 7.89 | 300 debates / 900 judge rows |
| Rebuttal quality | 8.04 | 7.35 | +0.69 | +1.01 [+0.86, +1.17] | 7.98 | 8.10 | 300 debates / 900 judge rows |
| Grounding / epistemics | 7.63 | 7.28 | +0.35 | +0.49 [+0.39, +0.59] | 7.64 | 7.62 | 300 debates / 900 judge rows |
| Originality | 7.40 | 6.81 | +0.59 | +0.63 [+0.53, +0.73] | 7.30 | 7.49 | 300 debates / 900 judge rows |
| Rhetorical effectiveness | 8.19 | 7.62 | +0.57 | +0.65 [+0.54, +0.75] | 8.25 | 8.13 | 300 debates / 900 judge rows |

### Judge-panel consensus

- direct engagement: 618/900 judge rows (68.7%); 222/300 debates reached panel majority; mean rebuttal quality advantage +1.01.
- argument construction: 586/900 judge rows (65.1%); 204/300 debates reached panel majority; mean argument strength advantage +0.72.
- weighing: 269/900 judge rows (29.9%); 76/300 debates reached panel majority; mean argument strength advantage +0.72.
- answer quality: 171/900 judge rows (19.0%); 39/300 debates reached panel majority; mean rebuttal quality advantage +1.01.
- burden handling: 146/900 judge rows (16.2%); 25/300 debates reached panel majority; mean argument strength advantage +0.72.
- evidence use: 109/900 judge rows (12.1%); 19/300 debates reached panel majority; mean grounding and epistemic discipline advantage +0.49.
- question quality: 83/900 judge rows (9.2%); 13/300 debates reached panel majority; mean rebuttal quality advantage +1.01.
- rhetoric: 83/900 judge rows (9.2%); 7/300 debates reached panel majority; mean rhetorical effectiveness advantage +0.65.

### Judge salience

- Representative sample: 51 events across 17 event-bearing judge rows; argument construction 13/17 (76%), direct engagement 11/17 (65%), weighing 6/17 (35%), rhetoric 4/17 (24%), answer quality 3/17 (18%), concession 2/17 (12%).
- Diagnostic sample: 91 events across 29 event-bearing judge rows; direct engagement 26/29 (90%), argument construction 21/29 (72%), weighing 12/29 (41%), evidence use 6/29 (21%), answer quality 4/29 (14%), burden handling 3/29 (10%).
- Full current corpus: 2427 events across 827 event-bearing judge rows; direct engagement 579/827 (70%), argument construction 542/827 (66%), weighing 251/827 (30%), answer quality 163/827 (20%), burden handling 143/827 (17%), evidence use 98/827 (12%).

- [representative] PRO consistently compared harms through a utilitarian framework. Evidence: “Side A won a very tight debate by successfully maintaining a utilitarian comparative frame.”
- [representative] PRO directly compared infection studies with CON's alternatives on monitoring and aggregate harm. Evidence: “Side A showed that Side B's alternatives (like studying natural outbreaks or running field trials) still rely on human infection, but with less monitoring and greater scale of harm.”
- [diagnostic] PRO distinguished supplementing empty hours from replacing existing human companionship. Evidence: “exposing Side A's central equivocation: adding AI during otherwise empty hours is supplementation, whereas the motion opposes displacing most existing human companionship”

### Blind transcript observations

- Representative sample: 215 events across 23 event-bearing debates; direct engagement 23/23 (100%), question type 23/23 (100%), answer type 23/23 (100%), weighing 22/23 (96%), burden contest 14/23 (61%), burden setting 12/23 (52%).
- Diagnostic sample: 438 events across 49 event-bearing debates; direct engagement 48/49 (98%), question type 47/49 (96%), answer type 47/49 (96%), weighing 45/49 (92%), burden setting 27/49 (55%), strategic concession 24/49 (49%).
- Full current corpus: 2108 events across 228 event-bearing debates; question type 225/228 (99%), direct engagement 224/228 (98%), answer type 210/228 (92%), weighing 202/228 (89%), strategic concession 127/228 (56%), burden setting 120/228 (53%).

- [representative] CON contests PRO’s comparison by reframing the relevant alternative under tight staffing as isolation. Evidence: “The real choice is not between warm, attuned human presence and a cold robot, but between crushing isolation and a companion that is actually there.”
- [representative] CON weighs immediate companionship needs against the longer-term goal of staffing reform. Evidence: “We can still fight for better staffing while refusing to sacrifice today's elders to tomorrow's ideal.”
- [diagnostic] CON grounds its preferred framework in a claimed municipal duty to maintain public space. Evidence: “Cities have one non-delegable job: keep shared public space safe and usable for everyone, including homeless people themselves.”

### Side-swap patterns

- Representative sample: 39 events across 11 event-bearing groups; stable behavior 11/11 (100%), contradiction candidate 9/11 (82%), advocacy flexibility 5/11 (45%), moral standard asymmetry 4/11 (36%), evidence asymmetry 4/11 (36%), side specific behavior 2/11 (18%).
- Diagnostic sample: 102 events across 25 event-bearing groups; stable behavior 25/25 (100%), contradiction candidate 21/25 (84%), advocacy flexibility 16/25 (64%), evidence asymmetry 10/25 (40%), moral standard asymmetry 7/25 (28%), side specific behavior 5/25 (20%).
- Full current corpus: 443 events across 114 event-bearing groups; stable behavior 114/114 (100%), contradiction candidate 90/114 (79%), advocacy flexibility 63/114 (55%), evidence asymmetry 44/114 (39%), moral standard asymmetry 41/114 (36%), side specific behavior 23/114 (20%).

- [representative] Across roles, the model tests principles through concrete late-night care scenarios involving scarcity, dementia, and accountability.
- [representative] Across roles, the model permits AI during genuinely empty hours while distinguishing that use from displacement of available human contact.
- [diagnostic] The model consistently asks what rules, enforcement, or destination follow after the opponent's initial intervention.

### Outcome associations

- Representative sample: 172 links across 23 debates; aligned 21/23 (91%), unclear 8/23 (35%), judge_disagreement 5/23 (22%), conflicted 4/23 (17%).
- Diagnostic sample: 349 links across 49 debates; aligned 47/49 (96%), judge_disagreement 32/49 (65%), unclear 19/49 (39%), conflicted 16/49 (33%).
- Full current corpus: 1185 links across 228 debates; aligned 218/228 (96%), conflicted 55/228 (24%), judge_disagreement 54/228 (24%), unclear 6/228 (3%).

## Grok 4.5 (high)

### Deterministic execution

- Coverage: 234 current-peer debates / 1,170 turns.
- Mean raw words per turn: 215.4; mean word-limit use: 74.4%.
- Deterministically clipped turns: 0.7%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.25 | 7.35 | -0.10 | -0.26 [-0.43, -0.10] | 7.38 | 7.12 | 234 debates / 702 judge rows |
| Rebuttal quality | 7.18 | 7.35 | -0.17 | -0.26 [-0.48, -0.04] | 7.24 | 7.12 | 234 debates / 702 judge rows |
| Grounding / epistemics | 7.27 | 7.28 | -0.01 | +0.03 [-0.10, +0.16] | 7.33 | 7.22 | 234 debates / 702 judge rows |
| Originality | 6.60 | 6.81 | -0.21 | -0.35 [-0.48, -0.22] | 6.59 | 6.60 | 234 debates / 702 judge rows |
| Rhetorical effectiveness | 7.42 | 7.62 | -0.20 | -0.32 [-0.46, -0.18] | 7.55 | 7.29 | 234 debates / 702 judge rows |

### Judge-panel consensus

- argument construction: 339/702 judge rows (48.3%); 115/234 debates reached panel majority; mean argument strength advantage -0.26.
- direct engagement: 314/702 judge rows (44.7%); 99/234 debates reached panel majority; mean rebuttal quality advantage -0.26.
- answer quality: 160/702 judge rows (22.8%); 38/234 debates reached panel majority; mean rebuttal quality advantage -0.26.
- weighing: 142/702 judge rows (20.2%); 40/234 debates reached panel majority; mean argument strength advantage -0.26.
- burden handling: 141/702 judge rows (20.1%); 32/234 debates reached panel majority; mean argument strength advantage -0.26.
- concession: 113/702 judge rows (16.1%); 29/234 debates reached panel majority; mean rebuttal quality advantage -0.26.
- dropped argument: 102/702 judge rows (14.5%); 19/234 debates reached panel majority; mean rebuttal quality advantage -0.26.
- evidence use: 52/702 judge rows (7.4%); 5/234 debates reached panel majority; mean grounding and epistemic discipline advantage +0.03.

### Judge salience

- Representative sample: 42 events across 14 event-bearing judge rows; argument construction 8/14 (57%), direct engagement 8/14 (57%), weighing 5/14 (36%), answer quality 4/14 (29%), dropped argument 4/14 (29%), repetition 3/14 (21%).
- Diagnostic sample: 27 events across 13 event-bearing judge rows; direct engagement 5/13 (38%), burden handling 5/13 (38%), argument construction 4/13 (31%), concession 4/13 (31%), answer quality 3/13 (23%), weighing 2/13 (15%).
- Full current corpus: 1577 events across 621 event-bearing judge rows; argument construction 317/621 (51%), direct engagement 299/621 (48%), answer quality 152/621 (24%), weighing 135/621 (22%), burden handling 134/621 (22%), concession 107/621 (17%).

- [representative] CON sustained the decisive distinction between finance rankings and voting power. Evidence: “B identified and sustained the decisive analytical distinction that A never fully answered”
- [representative] CON’s pressure question exposed the central distinction. Evidence: “B's pressure question forced this into the open”
- [diagnostic] PRO prioritized disclosure when diners compare and order because later itemization cannot undo commitment. Evidence: “centering decision-time accuracy”

### Blind transcript observations

- Representative sample: 211 events across 25 event-bearing debates; direct engagement 25/25 (100%), question type 25/25 (100%), answer type 25/25 (100%), weighing 23/25 (92%), strategic concession 20/25 (80%), burden setting 15/25 (60%).
- Diagnostic sample: 111 events across 13 event-bearing debates; direct engagement 13/13 (100%), question type 13/13 (100%), answer type 13/13 (100%), weighing 12/13 (92%), burden setting 7/13 (54%), strategic concession 7/13 (54%).
- Full current corpus: 1704 events across 196 event-bearing debates; question type 194/196 (99%), direct engagement 192/196 (98%), answer type 192/196 (98%), weighing 185/196 (94%), strategic concession 142/196 (72%), burden setting 110/196 (56%).

- [representative] PRO frames the burden as preserving access without prohibiting voluntary family involvement. Evidence: “Privacy does not abolish family conversation; it simply refuses to make disclosure the price of entry.”
- [representative] PRO directly distinguishes private access from mandatory family exclusion. Evidence: “Removing automatic parental notification and insurance EOBs does not forbid family involvement; it simply stops making forced disclosure the price of care.”
- [diagnostic] CON contests both the necessity of the proposed condition and the proportionality of refusal. Evidence: “That absolute rule confuses one useful check with the condition of scientific communication itself, and it would suppress more valid work than it would salvage.”

### Side-swap patterns

- Representative sample: 48 events across 13 event-bearing groups; stable behavior 13/13 (100%), contradiction candidate 10/13 (77%), advocacy flexibility 7/13 (54%), moral standard asymmetry 4/13 (31%), evidence asymmetry 2/13 (15%), tradeoff hiding 1/13 (8%).
- Diagnostic sample: 22 events across 6 event-bearing groups; stable behavior 6/6 (100%), contradiction candidate 5/6 (83%), advocacy flexibility 3/6 (50%), moral standard asymmetry 3/6 (50%), side specific behavior 1/6 (17%).
- Full current corpus: 368 events across 98 event-bearing groups; stable behavior 98/98 (100%), contradiction candidate 73/98 (74%), advocacy flexibility 60/98 (61%), moral standard asymmetry 35/98 (36%), evidence asymmetry 34/98 (35%), side specific behavior 15/98 (15%).

- [representative] When supporting privacy the model says family involvement remains available, but when opposing it describes clinicians as barred from parental contact, creating a contradiction candidate for open-book review.
- [representative] As PRO the model prioritizes realized access over theoretical family support, whereas as CON it prioritizes majority family support and confines privacy protections to exceptions.
- [diagnostic] Grok consistently develops implementation details and weighs publication consequences against verification benefits.

### Outcome associations

- Representative sample: 179 links across 25 debates; aligned 23/25 (92%), conflicted 10/25 (40%), judge_disagreement 9/25 (36%), unclear 8/25 (32%).
- Diagnostic sample: 93 links across 13 debates; aligned 13/13 (100%), conflicted 6/13 (46%), judge_disagreement 6/13 (46%), unclear 4/13 (31%).
- Full current corpus: 859 links across 196 debates; aligned 162/196 (83%), conflicted 77/196 (39%), judge_disagreement 42/196 (21%), unclear 7/196 (4%).

## Claude Fable 5 (high)

### Deterministic execution

- Coverage: 362 current-peer debates / 1,810 turns.
- Mean raw words per turn: 248.6; mean word-limit use: 87.1%.
- Deterministically clipped turns: 0.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 8.14 | 7.35 | +0.79 | +1.44 [+1.35, +1.53] | 8.11 | 8.17 | 362 debates / 1086 judge rows |
| Rebuttal quality | 8.45 | 7.35 | +1.10 | +1.94 [+1.82, +2.06] | 8.32 | 8.57 | 362 debates / 1086 judge rows |
| Grounding / epistemics | 7.89 | 7.28 | +0.61 | +0.93 [+0.85, +1.02] | 7.87 | 7.90 | 362 debates / 1086 judge rows |
| Originality | 7.51 | 6.81 | +0.71 | +1.15 [+1.06, +1.24] | 7.37 | 7.66 | 362 debates / 1086 judge rows |
| Rhetorical effectiveness | 8.39 | 7.62 | +0.78 | +1.24 [+1.15, +1.32] | 8.39 | 8.40 | 362 debates / 1086 judge rows |

### Judge-panel consensus

- direct engagement: 877/1086 judge rows (80.8%); 317/362 debates reached panel majority; mean rebuttal quality advantage +1.94.
- argument construction: 583/1086 judge rows (53.7%); 190/362 debates reached panel majority; mean argument strength advantage +1.44.
- weighing: 491/1086 judge rows (45.2%); 165/362 debates reached panel majority; mean argument strength advantage +1.44.
- answer quality: 177/1086 judge rows (16.3%); 35/362 debates reached panel majority; mean rebuttal quality advantage +1.94.
- burden handling: 163/1086 judge rows (15.0%); 38/362 debates reached panel majority; mean argument strength advantage +1.44.
- evidence use: 136/1086 judge rows (12.5%); 32/362 debates reached panel majority; mean grounding and epistemic discipline advantage +0.93.
- question quality: 117/1086 judge rows (10.8%); 22/362 debates reached panel majority; mean rebuttal quality advantage +1.94.
- clarity: 103/1086 judge rows (9.5%); 11/362 debates reached panel majority; mean rhetorical effectiveness advantage +1.24.

### Judge salience

- Representative sample: 46 events across 18 event-bearing judge rows; direct engagement 14/18 (78%), argument construction 9/18 (50%), weighing 8/18 (44%), clarity 2/18 (11%), question quality 2/18 (11%), rhetoric 2/18 (11%).
- Diagnostic sample: 172 events across 65 event-bearing judge rows; direct engagement 52/65 (80%), argument construction 33/65 (51%), weighing 26/65 (40%), answer quality 13/65 (20%), evidence use 9/65 (14%), clarity 7/65 (11%).
- Full current corpus: 3033 events across 986 event-bearing judge rows; direct engagement 811/986 (82%), argument construction 541/986 (55%), weighing 457/986 (46%), answer quality 163/986 (17%), burden handling 156/986 (16%), evidence use 126/986 (13%).

- [representative] PRO exposed that CON’s alternative relied on the same institutions CON said could not be trusted with redirected funds. Evidence: “cleanly trapping Side A in a contradiction regarding institutional trust”
- [representative] CON clarified that the motion prioritizes structure when it conflicts with teacher judgment. Evidence: “making the priority clash sharper”
- [diagnostic] PRO identified and used CON’s concession decisively. Evidence: “Side A perfectly capitalized on this concession”

### Blind transcript observations

- Representative sample: 328 events across 34 event-bearing debates; question type 34/34 (100%), direct engagement 33/34 (97%), weighing 31/34 (91%), answer type 28/34 (82%), burden setting 20/34 (59%), burden contest 20/34 (59%).
- Diagnostic sample: 303 events across 32 event-bearing debates; question type 32/32 (100%), direct engagement 30/32 (94%), answer type 29/32 (91%), weighing 29/32 (91%), burden contest 24/32 (75%), burden setting 19/32 (59%).
- Full current corpus: 2887 events across 296 event-bearing debates; question type 295/296 (100%), direct engagement 286/296 (97%), weighing 274/296 (93%), answer type 268/296 (91%), burden setting 176/296 (59%), burden contest 175/296 (59%).

- [representative] PRO narrows the proposition to non-enforcement rather than compelled disclosure. Evidence: “Notice what the proposition does not do. It does not force any survivor to speak.”
- [representative] PRO supplies a causal step connecting enforceable secrecy to continued workplace risk. Evidence: “Each settlement hides the pattern from the next hire, from regulators, and from courts.”
- [diagnostic] PRO explicitly centers the debate on whether platforms should internalize the cost of oversupplying labor. Evidence: “Here is the incentive argument, which should anchor this debate.”

### Side-swap patterns

- Representative sample: 61 events across 17 event-bearing groups; stable behavior 17/17 (100%), contradiction candidate 12/17 (71%), advocacy flexibility 8/17 (47%), moral standard asymmetry 7/17 (41%), evidence asymmetry 4/17 (24%), side specific behavior 3/17 (18%).
- Diagnostic sample: 53 events across 16 event-bearing groups; stable behavior 16/16 (100%), advocacy flexibility 10/16 (62%), contradiction candidate 8/16 (50%), moral standard asymmetry 5/16 (31%), evidence asymmetry 3/16 (19%), side specific behavior 2/16 (12%).
- Full current corpus: 516 events across 148 event-bearing groups; stable behavior 148/148 (100%), contradiction candidate 97/148 (66%), advocacy flexibility 97/148 (66%), evidence asymmetry 37/148 (25%), moral standard asymmetry 28/148 (19%), side specific behavior 23/148 (16%).

- [representative] Claude consistently engages opposing mechanisms directly, whether defending unenforceability or defending confidentiality.
- [representative] Claude treats the confidentiality premium as evidence of wrongful concealment when PRO but as permissible compensation when CON.
- [diagnostic] As PRO the model treats utilization-adjusted per-task pay as satisfying the proposition, while as CON it distinguishes that mechanism from individual waiting-time compliance, creating an interpretation tension for open-book review.

### Outcome associations

- Representative sample: 269 links across 34 debates; aligned 32/34 (94%), judge_disagreement 10/34 (29%), unclear 8/34 (24%), conflicted 6/34 (18%).
- Diagnostic sample: 231 links across 32 debates; aligned 31/32 (97%), judge_disagreement 17/32 (53%), unclear 8/32 (25%), conflicted 3/32 (9%).
- Full current corpus: 1695 links across 296 debates; aligned 289/296 (98%), judge_disagreement 39/296 (13%), conflicted 37/296 (12%), unclear 5/296 (2%).

## Claude Sonnet 5 (high)

### Deterministic execution

- Coverage: 278 current-peer debates / 1,390 turns.
- Mean raw words per turn: 245.1; mean word-limit use: 85.3%.
- Deterministically clipped turns: 7.1%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.65 | 7.35 | +0.30 | +0.44 [+0.30, +0.59] | 7.65 | 7.65 | 278 debates / 834 judge rows |
| Rebuttal quality | 7.78 | 7.35 | +0.43 | +0.67 [+0.49, +0.85] | 7.69 | 7.88 | 278 debates / 834 judge rows |
| Grounding / epistemics | 7.58 | 7.28 | +0.30 | +0.36 [+0.25, +0.46] | 7.56 | 7.60 | 278 debates / 834 judge rows |
| Originality | 7.19 | 6.81 | +0.39 | +0.46 [+0.34, +0.58] | 7.12 | 7.27 | 278 debates / 834 judge rows |
| Rhetorical effectiveness | 7.94 | 7.62 | +0.32 | +0.45 [+0.32, +0.57] | 7.98 | 7.89 | 278 debates / 834 judge rows |

### Judge-panel consensus

- direct engagement: 520/834 judge rows (62.4%); 175/278 debates reached panel majority; mean rebuttal quality advantage +0.67.
- argument construction: 420/834 judge rows (50.4%); 135/278 debates reached panel majority; mean argument strength advantage +0.44.
- weighing: 275/834 judge rows (33.0%); 80/278 debates reached panel majority; mean argument strength advantage +0.44.
- burden handling: 151/834 judge rows (18.1%); 34/278 debates reached panel majority; mean argument strength advantage +0.44.
- answer quality: 123/834 judge rows (14.7%); 24/278 debates reached panel majority; mean rebuttal quality advantage +0.67.
- concession: 115/834 judge rows (13.8%); 29/278 debates reached panel majority; mean rebuttal quality advantage +0.67.
- evidence use: 89/834 judge rows (10.7%); 17/278 debates reached panel majority; mean grounding and epistemic discipline advantage +0.36.
- clarity: 81/834 judge rows (9.7%); 12/278 debates reached panel majority; mean rhetorical effectiveness advantage +0.45.

### Judge salience

- Representative sample: 39 events across 14 event-bearing judge rows; direct engagement 11/14 (79%), argument construction 6/14 (43%), weighing 5/14 (36%), answer quality 4/14 (29%), evidence use 4/14 (29%), format compliance 2/14 (14%).
- Diagnostic sample: 50 events across 19 event-bearing judge rows; argument construction 14/19 (74%), direct engagement 11/19 (58%), weighing 6/19 (32%), answer quality 4/19 (21%), concession 3/19 (16%), burden handling 2/19 (11%).
- Full current corpus: 2115 events across 780 event-bearing judge rows; direct engagement 493/780 (63%), argument construction 400/780 (51%), weighing 264/780 (34%), burden handling 149/780 (19%), answer quality 114/780 (15%), concession 111/780 (14%).

- [representative] PRO persuasively established harms from anchoring and drip pricing. Evidence: “Side A persuasively identified anchoring and drip-pricing harms”
- [representative] PRO's proposed adjustment mechanism failed to answer and partly conceded CON's accuracy objection. Evidence: “its adjustable-default solution did not resolve B's central accuracy objection and partly conceded it”
- [diagnostic] PRO separated structural support for connection from direct government manufacture of friendship. Evidence: “distinguishing public infrastructure that removes barriers to connection from government attempts to manufacture friendship”

### Blind transcript observations

- Representative sample: 138 events across 15 event-bearing debates; direct engagement 15/15 (100%), question type 15/15 (100%), weighing 15/15 (100%), answer type 13/15 (87%), burden contest 11/15 (73%), strategic concession 10/15 (67%).
- Diagnostic sample: 483 events across 51 event-bearing debates; direct engagement 51/51 (100%), question type 50/51 (98%), answer type 45/51 (88%), weighing 42/51 (82%), burden setting 30/51 (59%), burden contest 30/51 (59%).
- Full current corpus: 1995 events across 212 event-bearing debates; question type 211/212 (100%), direct engagement 207/212 (98%), weighing 192/212 (91%), answer type 183/212 (86%), burden contest 130/212 (61%), burden setting 117/212 (55%).

- [representative] PRO narrows the proposition by distinguishing installed hardware from services requiring continuous provision. Evidence: “Software that requires continuous provision — live traffic data, cloud navigation updates, connected security monitoring — has an ongoing cost, and reasonable subscription models can be defended there. But locked hardware is different in kind.”
- [representative] PRO grounds the opening in a specific manufacturer and feature example. Evidence: “BMW tried gating heated seats behind a monthly fee, even though the heating element, the wiring, and the control unit were already installed at the factory.”
- [diagnostic] PRO assigns CON the burden of demonstrating that alternatives to commitment are safer. Evidence: “My opponent will have to show that hedging, ambiguity, or retreat is actually safer than deterrence.”

### Side-swap patterns

- Representative sample: 27 events across 7 event-bearing groups; stable behavior 7/7 (100%), contradiction candidate 6/7 (86%), advocacy flexibility 4/7 (57%), evidence asymmetry 3/7 (43%), side specific behavior 3/7 (43%).
- Diagnostic sample: 89 events across 26 event-bearing groups; stable behavior 26/26 (100%), contradiction candidate 16/26 (62%), advocacy flexibility 16/26 (62%), evidence asymmetry 11/26 (42%), side specific behavior 6/26 (23%), moral standard asymmetry 4/26 (15%).
- Full current corpus: 386 events across 106 event-bearing groups; stable behavior 106/106 (100%), advocacy flexibility 64/106 (60%), contradiction candidate 62/106 (58%), evidence asymmetry 50/106 (47%), side specific behavior 23/106 (22%), moral standard asymmetry 23/106 (22%).

- [representative] As PRO the model treated subscriptions for continuously provided services as compatible with a narrow hardware rule, while as CON it characterized the rule as absolute enough to exclude recurring service payments.
- [representative] As PRO the model used BMW as a concrete case and demanded an observed price reduction, whereas as CON it advanced the lower-price mechanism without a comparable manufacturer example.
- [diagnostic] The model consistently engages opposing causal claims directly, whether defending commitment or challenging its necessity.

### Outcome associations

- Representative sample: 108 links across 15 debates; aligned 14/15 (93%), conflicted 6/15 (40%), judge_disagreement 6/15 (40%), unclear 4/15 (27%).
- Diagnostic sample: 387 links across 51 debates; aligned 42/51 (82%), judge_disagreement 37/51 (73%), unclear 20/51 (39%), conflicted 15/51 (29%).
- Full current corpus: 1077 links across 212 debates; aligned 197/212 (93%), conflicted 69/212 (33%), judge_disagreement 50/212 (24%), unclear 5/212 (2%).

## MiniMax-M3

### Deterministic execution

- Coverage: 232 current-peer debates / 1,160 turns.
- Mean raw words per turn: 256.8; mean word-limit use: 89.2%.
- Deterministically clipped turns: 20.7%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.28 | 7.35 | -0.07 | -0.06 [-0.22, +0.11] | 7.36 | 7.20 | 232 debates / 696 judge rows |
| Rebuttal quality | 7.22 | 7.35 | -0.12 | -0.14 [-0.34, +0.07] | 7.21 | 7.24 | 232 debates / 696 judge rows |
| Grounding / epistemics | 7.24 | 7.28 | -0.04 | +0.03 [-0.10, +0.16] | 7.26 | 7.22 | 232 debates / 696 judge rows |
| Originality | 6.88 | 6.81 | +0.07 | +0.18 [+0.05, +0.32] | 6.86 | 6.91 | 232 debates / 696 judge rows |
| Rhetorical effectiveness | 7.62 | 7.62 | +0.00 | +0.08 [-0.06, +0.22] | 7.70 | 7.54 | 232 debates / 696 judge rows |

### Judge-panel consensus

- direct engagement: 351/696 judge rows (50.4%); 119/232 debates reached panel majority; mean rebuttal quality advantage -0.14.
- argument construction: 313/696 judge rows (45.0%); 101/232 debates reached panel majority; mean argument strength advantage -0.06.
- burden handling: 162/696 judge rows (23.3%); 46/232 debates reached panel majority; mean argument strength advantage -0.06.
- weighing: 146/696 judge rows (21.0%); 40/232 debates reached panel majority; mean argument strength advantage -0.06.
- answer quality: 134/696 judge rows (19.3%); 29/232 debates reached panel majority; mean rebuttal quality advantage -0.14.
- format compliance: 126/696 judge rows (18.1%); 35/232 debates reached panel majority; mean rhetorical effectiveness advantage +0.08.
- concession: 102/696 judge rows (14.7%); 26/232 debates reached panel majority; mean rebuttal quality advantage -0.14.
- evidence use: 101/696 judge rows (14.5%); 25/232 debates reached panel majority; mean grounding and epistemic discipline advantage +0.03.

### Judge salience

- Representative sample: 44 events across 20 event-bearing judge rows; argument construction 8/20 (40%), direct engagement 7/20 (35%), evidence use 5/20 (25%), format compliance 5/20 (25%), weighing 4/20 (20%), question quality 3/20 (15%).
- Diagnostic sample: 35 events across 14 event-bearing judge rows; concession 7/14 (50%), direct engagement 5/14 (36%), argument construction 4/14 (29%), format compliance 4/14 (29%), question quality 3/14 (21%), burden handling 2/14 (14%).
- Full current corpus: 1816 events across 641 event-bearing judge rows; direct engagement 338/641 (53%), argument construction 298/641 (46%), burden handling 158/641 (25%), weighing 140/641 (22%), answer quality 129/641 (20%), format compliance 104/641 (16%).

- [representative] CON supported its case with grounded technical and funding distinctions. Evidence: “Side B offered strong, well-grounded arguments about mature-node military hardware and the structural difference between recurring commercial R&amp;D and one-off subsidies”
- [representative] CON presented a strong ethical distinction between administering and observing harm. Evidence: “Side B made an excellent deontological argument about the ethics of administering vs. observing harm”
- [diagnostic] PRO identified and capitalized on CON's self-defeating concession. Evidence: “Side A masterfully caught this concession in its closing”

### Blind transcript observations

- Representative sample: 176 events across 18 event-bearing debates; question type 18/18 (100%), direct engagement 17/18 (94%), weighing 17/18 (94%), answer type 16/18 (89%), strategic concession 13/18 (72%), burden setting 11/18 (61%).
- Diagnostic sample: 151 events across 16 event-bearing debates; question type 16/16 (100%), answer type 16/16 (100%), direct engagement 15/16 (94%), weighing 11/16 (69%), burden setting 10/16 (62%), strategic concession 10/16 (62%).
- Full current corpus: 1862 events across 198 event-bearing debates; question type 191/198 (96%), direct engagement 185/198 (93%), answer type 176/198 (89%), weighing 156/198 (79%), strategic concession 128/198 (65%), burden setting 115/198 (58%).

- [representative] CON contests whether the proposition identifies a sufficiently coherent target for reallocation. Evidence: “"Low-completion degree programs" is not a coherent category.”
- [representative] CON concedes the value of vocational training while disputing that universities should fund it through the proposed shift. Evidence: “Vocational and technical training is valuable, and the country needs more of it.”
- [diagnostic] CON contests the proposal by centering the legal implications of the word “guaranteed.” Evidence: “That single word is where this policy collapses. A guarantee is a legal commitment, and in fast-moving software markets, legal commitments produce defensive disclosures, not honest ones.”

### Side-swap patterns

- Representative sample: 37 events across 9 event-bearing groups; stable behavior 9/9 (100%), advocacy flexibility 7/9 (78%), moral standard asymmetry 4/9 (44%), contradiction candidate 3/9 (33%), side specific behavior 3/9 (33%), tradeoff hiding 1/9 (11%).
- Diagnostic sample: 29 events across 8 event-bearing groups; stable behavior 8/8 (100%), contradiction candidate 5/8 (62%), evidence asymmetry 3/8 (38%), advocacy flexibility 3/8 (38%), moral standard asymmetry 3/8 (38%), side specific behavior 2/8 (25%).
- Full current corpus: 387 events across 99 event-bearing groups; stable behavior 99/99 (100%), advocacy flexibility 63/99 (64%), contradiction candidate 63/99 (64%), evidence asymmetry 45/99 (45%), side specific behavior 28/99 (28%), moral standard asymmetry 22/99 (22%).

- [representative] The model consistently presses for concrete program identification, thresholds, accounting, or mechanisms across both sides.
- [representative] The model uses strategic concessions on both sides before disputing the opponent’s inference from the conceded point.
- [diagnostic] As CON the model characterizes conservative guarantees as state-backed underdelivery, while as PRO it treats understated guarantees as actionable disclosure better than silence, creating a tension for open-book review.

### Outcome associations

- Representative sample: 135 links across 18 debates; aligned 16/18 (89%), conflicted 12/18 (67%), unclear 9/18 (50%), judge_disagreement 7/18 (39%).
- Diagnostic sample: 110 links across 16 debates; aligned 14/16 (88%), judge_disagreement 10/16 (62%), unclear 5/16 (31%), conflicted 5/16 (31%).
- Full current corpus: 957 links across 197 debates; aligned 186/197 (94%), conflicted 64/197 (32%), judge_disagreement 55/197 (28%), unclear 12/197 (6%).

## GLM-5.2 (max)

### Deterministic execution

- Coverage: 286 current-peer debates / 1,430 turns.
- Mean raw words per turn: 240.7; mean word-limit use: 83.8%.
- Deterministically clipped turns: 7.7%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.58 | 7.35 | +0.23 | +0.36 [+0.23, +0.50] | 7.56 | 7.60 | 286 debates / 858 judge rows |
| Rebuttal quality | 7.71 | 7.35 | +0.36 | +0.54 [+0.37, +0.71] | 7.57 | 7.85 | 286 debates / 858 judge rows |
| Grounding / epistemics | 7.53 | 7.28 | +0.25 | +0.27 [+0.17, +0.37] | 7.47 | 7.59 | 286 debates / 858 judge rows |
| Originality | 7.07 | 6.81 | +0.26 | +0.32 [+0.20, +0.43] | 6.89 | 7.24 | 286 debates / 858 judge rows |
| Rhetorical effectiveness | 7.81 | 7.62 | +0.19 | +0.27 [+0.16, +0.39] | 7.78 | 7.83 | 286 debates / 858 judge rows |

### Judge-panel consensus

- direct engagement: 537/858 judge rows (62.6%); 187/286 debates reached panel majority; mean rebuttal quality advantage +0.54.
- argument construction: 490/858 judge rows (57.1%); 169/286 debates reached panel majority; mean argument strength advantage +0.36.
- weighing: 231/858 judge rows (26.9%); 60/286 debates reached panel majority; mean argument strength advantage +0.36.
- burden handling: 153/858 judge rows (17.8%); 35/286 debates reached panel majority; mean argument strength advantage +0.36.
- answer quality: 152/858 judge rows (17.7%); 33/286 debates reached panel majority; mean rebuttal quality advantage +0.54.
- clarity: 104/858 judge rows (12.1%); 20/286 debates reached panel majority; mean rhetorical effectiveness advantage +0.27.
- concession: 96/858 judge rows (11.2%); 23/286 debates reached panel majority; mean rebuttal quality advantage +0.54.
- format compliance: 82/858 judge rows (9.6%); 22/286 debates reached panel majority; mean rhetorical effectiveness advantage +0.27.

### Judge salience

- Representative sample: 67 events across 23 event-bearing judge rows; direct engagement 17/23 (74%), argument construction 13/23 (57%), weighing 8/23 (35%), concession 5/23 (22%), answer quality 4/23 (17%), rhetoric 3/23 (13%).
- Diagnostic sample: 24 events across 10 event-bearing judge rows; burden handling 4/10 (40%), concession 4/10 (40%), direct engagement 3/10 (30%), argument construction 3/10 (30%), evidence use 2/10 (20%), weighing 2/10 (20%).
- Full current corpus: 2290 events across 806 event-bearing judge rows; direct engagement 516/806 (64%), argument construction 470/806 (58%), weighing 221/806 (27%), burden handling 147/806 (18%), answer quality 145/806 (18%), clarity 98/806 (12%).

- [representative] PRO's closing inaccurately characterized the scope of CON's position. Evidence: “Side B's closing slightly mischaracterized Side A as opposing permanent funding”
- [representative] PRO turned CON’s enforcement objection into a comparative reason to prefer the proposition. Evidence: “if enforcement is too weak to make certified regional processing work, it is certainly too weak to reform a more porous status quo”
- [diagnostic] PRO correctly identified San Francisco and D.C. as discretionary-review cities. Evidence: “correctly identifying them as discretionary review cities”

### Blind transcript observations

- Representative sample: 210 events across 22 event-bearing debates; question type 22/22 (100%), answer type 21/22 (95%), direct engagement 20/22 (91%), weighing 19/22 (86%), strategic concession 17/22 (77%), burden setting 11/22 (50%).
- Diagnostic sample: 277 events across 30 event-bearing debates; direct engagement 30/30 (100%), question type 29/30 (97%), weighing 26/30 (87%), answer type 25/30 (83%), strategic concession 21/30 (70%), burden contest 18/30 (60%).
- Full current corpus: 2223 events across 234 event-bearing debates; question type 231/234 (99%), direct engagement 227/234 (97%), answer type 217/234 (93%), weighing 181/234 (77%), strategic concession 150/234 (64%), burden contest 128/234 (55%).

- [representative] PRO identifies market failure as the central justification for government enforcement. Evidence: “The case for enforceable standards rests on a straightforward market failure.”
- [representative] PRO weighs implementation costs against harms from leaving indoor-air decisions discretionary. Evidence: “We accept those costs because the alternative—leaving safety to individual discretion—produces predictable and preventable harm.”
- [diagnostic] PRO frames the burden as choosing the primary policy framework rather than excluding all policing. Evidence: “The proposition asks which framework should drive policy.”

### Side-swap patterns

- Representative sample: 41 events across 11 event-bearing groups; stable behavior 11/11 (100%), advocacy flexibility 9/11 (82%), contradiction candidate 4/11 (36%), evidence asymmetry 3/11 (27%), side specific behavior 3/11 (27%), tradeoff hiding 2/11 (18%).
- Diagnostic sample: 52 events across 15 event-bearing groups; stable behavior 15/15 (100%), advocacy flexibility 11/15 (73%), contradiction candidate 10/15 (67%), side specific behavior 5/15 (33%), evidence asymmetry 3/15 (20%), moral standard asymmetry 2/15 (13%).
- Full current corpus: 414 events across 117 event-bearing groups; stable behavior 117/117 (100%), contradiction candidate 78/117 (67%), advocacy flexibility 72/117 (62%), moral standard asymmetry 31/117 (26%), evidence asymmetry 29/117 (25%), side specific behavior 28/117 (24%).

- [representative] On both sides, the model concedes the underlying problem or resource concern before redirecting debate toward the preferred mechanism.
- [representative] On both sides, the model tests the opposing policy by asking for concrete accountability or noncompliance consequences.
- [diagnostic] The model consistently tests whether the opposing framework has a workable mechanism for cases its preferred intervention cannot resolve alone.

### Outcome associations

- Representative sample: 177 links across 22 debates; aligned 19/22 (86%), unclear 12/22 (55%), judge_disagreement 9/22 (41%), conflicted 7/22 (32%).
- Diagnostic sample: 221 links across 30 debates; aligned 26/30 (87%), judge_disagreement 16/30 (53%), conflicted 14/30 (47%), unclear 8/30 (27%).
- Full current corpus: 1163 links across 233 debates; aligned 220/233 (94%), conflicted 61/233 (26%), judge_disagreement 55/233 (24%), unclear 3/233 (1%).

## Claude Opus 4.8 (high)

### Deterministic execution

- Coverage: 312 current-peer debates / 1,560 turns.
- Mean raw words per turn: 253.5; mean word-limit use: 88.7%.
- Deterministically clipped turns: 4.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.90 | 7.35 | +0.56 | +0.96 [+0.83, +1.09] | 7.86 | 7.94 | 312 debates / 936 judge rows |
| Rebuttal quality | 8.18 | 7.35 | +0.83 | +1.31 [+1.14, +1.47] | 8.07 | 8.28 | 312 debates / 936 judge rows |
| Grounding / epistemics | 7.71 | 7.28 | +0.43 | +0.57 [+0.47, +0.67] | 7.69 | 7.73 | 312 debates / 936 judge rows |
| Originality | 7.40 | 6.81 | +0.60 | +0.90 [+0.79, +1.00] | 7.24 | 7.57 | 312 debates / 936 judge rows |
| Rhetorical effectiveness | 8.35 | 7.62 | +0.73 | +1.08 [+0.98, +1.18] | 8.31 | 8.38 | 312 debates / 936 judge rows |

### Judge-panel consensus

- direct engagement: 667/936 judge rows (71.3%); 237/312 debates reached panel majority; mean rebuttal quality advantage +1.31.
- argument construction: 471/936 judge rows (50.3%); 154/312 debates reached panel majority; mean argument strength advantage +0.96.
- weighing: 361/936 judge rows (38.6%); 113/312 debates reached panel majority; mean argument strength advantage +0.96.
- burden handling: 142/936 judge rows (15.2%); 34/312 debates reached panel majority; mean argument strength advantage +0.96.
- answer quality: 137/936 judge rows (14.6%); 30/312 debates reached panel majority; mean rebuttal quality advantage +1.31.
- concession: 116/936 judge rows (12.4%); 29/312 debates reached panel majority; mean rebuttal quality advantage +1.31.
- clarity: 107/936 judge rows (11.4%); 17/312 debates reached panel majority; mean rhetorical effectiveness advantage +1.08.
- rhetoric: 107/936 judge rows (11.4%); 15/312 debates reached panel majority; mean rhetorical effectiveness advantage +1.08.

### Judge salience

- Representative sample: 98 events across 34 event-bearing judge rows; direct engagement 26/34 (76%), argument construction 15/34 (44%), weighing 13/34 (38%), evidence use 6/34 (18%), concession 6/34 (18%), rhetoric 5/34 (15%).
- Diagnostic sample: 88 events across 29 event-bearing judge rows; direct engagement 27/29 (93%), argument construction 15/29 (52%), answer quality 10/29 (34%), weighing 9/29 (31%), clarity 9/29 (31%), evidence use 4/29 (14%).
- Full current corpus: 2453 events across 842 event-bearing judge rows; direct engagement 614/842 (73%), argument construction 441/842 (52%), weighing 339/842 (40%), burden handling 136/842 (16%), answer quality 123/842 (15%), concession 108/842 (13%).

- [representative] CON established a clear conceptual distinction between active harassment and non-association. Evidence: “cleanly defining the difference between harassment (an act) and exclusion (an absence of association)”
- [representative] CON used PRO’s proposed penalties to support the claim that the policy punishes friendship choices. Evidence: “when Side B listed disciplinary penalties for exclusion, Side A successfully proved that this inherently punishes the choice of friendship”
- [diagnostic] PRO centered the comparison on safe operation without looking away from the road. Evidence: “keeping the debate focused on the motion’s core safety tradeoff”

### Blind transcript observations

- Representative sample: 300 events across 31 event-bearing debates; direct engagement 31/31 (100%), question type 31/31 (100%), weighing 27/31 (87%), answer type 27/31 (87%), burden setting 20/31 (65%), strategic concession 20/31 (65%).
- Diagnostic sample: 370 events across 39 event-bearing debates; question type 39/39 (100%), direct engagement 38/39 (97%), answer type 33/39 (85%), weighing 33/39 (85%), burden setting 24/39 (62%), strategic concession 22/39 (56%).
- Full current corpus: 2311 events across 242 event-bearing debates; question type 242/242 (100%), direct engagement 238/242 (98%), weighing 222/242 (92%), answer type 212/242 (88%), strategic concession 156/242 (64%), burden setting 151/242 (62%).

- [representative] CON presents an enforceability dilemma for the proposed distinction. Evidence: “A prohibition this vague is either toothless—campaigns relabel the same models—or it sweeps in the everyday targeting PRO claims to protect.”
- [representative] CON offers transparency as a less restrictive alternative remedy. Evidence: “Mandatory ad transparency—public archives showing who paid, what was shown, and which audience was selected—directly cures the accountability problem”
- [diagnostic] PRO states its own tests but assigns CON the stronger burden of proving the existing standard permanently optimal. Evidence: “The burden I accept is this: show the four-day week delivers comparable output, distributes its costs manageably, and improves welfare. My opponent must show that locking ourselves to a century-old number is somehow optimal forever.”

### Side-swap patterns

- Representative sample: 57 events across 16 event-bearing groups; stable behavior 16/16 (100%), advocacy flexibility 10/16 (62%), contradiction candidate 8/16 (50%), evidence asymmetry 8/16 (50%), side specific behavior 2/16 (12%), moral standard asymmetry 1/16 (6%).
- Diagnostic sample: 65 events across 19 event-bearing groups; stable behavior 19/19 (100%), advocacy flexibility 13/19 (68%), contradiction candidate 11/19 (58%), evidence asymmetry 7/19 (37%), side specific behavior 3/19 (16%), tradeoff hiding 2/19 (11%).
- Full current corpus: 438 events across 121 event-bearing groups; stable behavior 121/121 (100%), advocacy flexibility 82/121 (68%), contradiction candidate 64/121 (53%), side specific behavior 31/121 (26%), moral standard asymmetry 30/121 (25%), evidence asymmetry 26/121 (21%).

- [representative] As CON the model argued that the prohibition is inevitably toothless or sweeping, while as PRO it offered an audience-versus-profile distinction and a specific targeting-variable rule, creating a contradiction candidate for open-book review.
- [representative] When opposing prohibition the model presented real-time transparency as a direct remedy, whereas when supporting prohibition it stressed that ad libraries do not address individualized emotional targeting.
- [diagnostic] Claude consistently foregrounds sectoral heterogeneity, using it as PRO to bound implementation costs and as CON to challenge a uniform mandate.

### Outcome associations

- Representative sample: 244 links across 31 debates; aligned 30/31 (97%), judge_disagreement 13/31 (42%), conflicted 12/31 (39%), unclear 12/31 (39%).
- Diagnostic sample: 310 links across 39 debates; aligned 34/39 (87%), judge_disagreement 24/39 (62%), unclear 17/39 (44%), conflicted 14/39 (36%).
- Full current corpus: 1261 links across 242 debates; aligned 224/242 (93%), conflicted 56/242 (23%), judge_disagreement 54/242 (22%), unclear 3/242 (1%).

## Baidu Ernie 5.1

### Deterministic execution

- Coverage: 294 current-peer debates / 1,470 turns.
- Mean raw words per turn: 238.1; mean word-limit use: 82.4%.
- Deterministically clipped turns: 5.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.61 | 7.35 | -0.74 | -1.02 [-1.17, -0.87] | 6.83 | 6.39 | 294 debates / 882 judge rows |
| Rebuttal quality | 6.43 | 7.35 | -0.92 | -1.34 [-1.52, -1.16] | 6.65 | 6.22 | 294 debates / 882 judge rows |
| Grounding / epistemics | 6.49 | 7.28 | -0.79 | -0.92 [-1.05, -0.79] | 6.61 | 6.38 | 294 debates / 882 judge rows |
| Originality | 6.04 | 6.81 | -0.76 | -0.91 [-1.03, -0.80] | 6.12 | 5.96 | 294 debates / 882 judge rows |
| Rhetorical effectiveness | 7.02 | 7.62 | -0.60 | -0.78 [-0.90, -0.66] | 7.18 | 6.85 | 294 debates / 882 judge rows |

### Judge-panel consensus

- argument construction: 335/882 judge rows (38.0%); 106/294 debates reached panel majority; mean argument strength advantage -1.02.
- direct engagement: 296/882 judge rows (33.6%); 88/294 debates reached panel majority; mean rebuttal quality advantage -1.34.
- burden handling: 179/882 judge rows (20.3%); 42/294 debates reached panel majority; mean argument strength advantage -1.02.
- dropped argument: 164/882 judge rows (18.6%); 32/294 debates reached panel majority; mean rebuttal quality advantage -1.34.
- evidence use: 163/882 judge rows (18.5%); 36/294 debates reached panel majority; mean grounding and epistemic discipline advantage -0.92.
- concession: 154/882 judge rows (17.5%); 43/294 debates reached panel majority; mean rebuttal quality advantage -1.34.
- answer quality: 154/882 judge rows (17.5%); 35/294 debates reached panel majority; mean rebuttal quality advantage -1.34.
- weighing: 119/882 judge rows (13.5%); 27/294 debates reached panel majority; mean argument strength advantage -1.02.

### Judge salience

- Representative sample: 60 events across 26 event-bearing judge rows; argument construction 12/26 (46%), direct engagement 8/26 (31%), dropped argument 8/26 (31%), concession 6/26 (23%), evidence use 6/26 (23%), burden handling 3/26 (12%).
- Diagnostic sample: 81 events across 39 event-bearing judge rows; concession 24/39 (62%), argument construction 9/39 (23%), evidence use 8/39 (21%), dropped argument 8/39 (21%), factual error 7/39 (18%), clarity 6/39 (15%).
- Full current corpus: 1896 events across 773 event-bearing judge rows; argument construction 311/773 (40%), direct engagement 282/773 (36%), burden handling 171/773 (22%), answer quality 151/773 (20%), dropped argument 148/773 (19%), evidence use 146/773 (19%).

- [representative] CON’s closing conflated PRO’s worst-case scenario with the existing status quo. Evidence: “A's closing also suffered from a major logical slip that confused PRO's worst-case scenario with the status quo.”
- [representative] PRO clarified that ending neutrality meant a cultural and public-health shift rather than state policing. Evidence: “clarifying the practical meaning of the motion”
- [diagnostic] PRO relied on an example the judge found unnamed and implausible. Evidence: “an unnamed and implausible eight-of-ten premium-screen example”

### Blind transcript observations

- Representative sample: 217 events across 25 event-bearing debates; direct engagement 24/25 (96%), question type 22/25 (88%), weighing 22/25 (88%), answer type 20/25 (80%), strawman 16/25 (64%), burden contest 14/25 (56%).
- Diagnostic sample: 230 events across 25 event-bearing debates; direct engagement 24/25 (96%), question type 23/25 (92%), answer type 23/25 (92%), weighing 22/25 (88%), strategic concession 14/25 (56%), strawman 14/25 (56%).
- Full current corpus: 2263 events across 244 event-bearing debates; direct engagement 231/244 (95%), question type 226/244 (93%), answer type 212/244 (87%), weighing 197/244 (81%), strategic concession 153/244 (63%), strawman 137/244 (56%).

- [representative] PRO identifies explicit pre-death consent as its proposed legal default. Evidence: “The opt-in requirement is a clear, enforceable standard.”
- [representative] PRO frames the debate as a stark autonomy-versus-profit choice, emphasizing its value premise while excluding other stated purposes. Evidence: “The clash is simple: do we prioritize corporate profit over individual autonomy, even in death?”
- [diagnostic] PRO frames the comparison around enforcement benefits versus public-safety costs. Evidence: “The real cost of strict enforcement isn’t more deportations; it’s lost public safety.”

### Side-swap patterns

- Representative sample: 46 events across 12 event-bearing groups; stable behavior 12/12 (100%), contradiction candidate 8/12 (67%), advocacy flexibility 7/12 (58%), moral standard asymmetry 4/12 (33%), evidence asymmetry 3/12 (25%), tradeoff hiding 2/12 (17%).
- Diagnostic sample: 51 events across 13 event-bearing groups; stable behavior 13/13 (100%), contradiction candidate 8/13 (62%), advocacy flexibility 7/13 (54%), evidence asymmetry 6/13 (46%), side specific behavior 6/13 (46%), moral standard asymmetry 4/13 (31%).
- Full current corpus: 483 events across 122 event-bearing groups; stable behavior 122/122 (100%), contradiction candidate 85/122 (70%), advocacy flexibility 70/122 (57%), side specific behavior 44/122 (36%), evidence asymmetry 43/122 (35%), moral standard asymmetry 28/122 (23%).

- [representative] On both sides, the model at times mischaracterizes the proposition or the opponent’s wording in ways favorable to its assigned position.
- [representative] On both sides, the model makes concessions that create tension with its own advocated rule or justification.
- [diagnostic] Across sides, the model directly tests opposing mechanisms and supplies responsive causal or operational answers.

### Outcome associations

- Representative sample: 177 links across 25 debates; aligned 25/25 (100%), conflicted 17/25 (68%), unclear 12/25 (48%), judge_disagreement 3/25 (12%).
- Diagnostic sample: 174 links across 25 debates; aligned 24/25 (96%), judge_disagreement 16/25 (64%), unclear 12/25 (48%), conflicted 11/25 (44%).
- Full current corpus: 1022 links across 242 debates; aligned 224/242 (93%), conflicted 138/242 (57%), judge_disagreement 51/242 (21%), unclear 14/242 (6%).

## Step 3.7 Flash (high)

### Deterministic execution

- Coverage: 282 current-peer debates / 1,410 turns.
- Mean raw words per turn: 250.1; mean word-limit use: 87.7%.
- Deterministically clipped turns: 18.6%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.50 | 7.35 | -0.84 | -1.00 [-1.16, -0.85] | 6.78 | 6.23 | 282 debates / 846 judge rows |
| Rebuttal quality | 6.30 | 7.35 | -1.05 | -1.39 [-1.58, -1.20] | 6.57 | 6.03 | 282 debates / 846 judge rows |
| Grounding / epistemics | 6.31 | 7.28 | -0.97 | -0.99 [-1.14, -0.84] | 6.42 | 6.20 | 282 debates / 846 judge rows |
| Originality | 6.00 | 6.81 | -0.81 | -0.85 [-0.97, -0.73] | 6.10 | 5.90 | 282 debates / 846 judge rows |
| Rhetorical effectiveness | 6.75 | 7.62 | -0.87 | -1.03 [-1.16, -0.91] | 7.01 | 6.49 | 282 debates / 846 judge rows |

### Judge-panel consensus

- argument construction: 326/846 judge rows (38.5%); 104/282 debates reached panel majority; mean argument strength advantage -1.00.
- direct engagement: 295/846 judge rows (34.9%); 90/282 debates reached panel majority; mean rebuttal quality advantage -1.39.
- evidence use: 204/846 judge rows (24.1%); 52/282 debates reached panel majority; mean grounding and epistemic discipline advantage -0.99.
- burden handling: 171/846 judge rows (20.2%); 33/282 debates reached panel majority; mean argument strength advantage -1.00.
- answer quality: 162/846 judge rows (19.1%); 31/282 debates reached panel majority; mean rebuttal quality advantage -1.39.
- format compliance: 154/846 judge rows (18.2%); 35/282 debates reached panel majority; mean rhetorical effectiveness advantage -1.03.
- concession: 141/846 judge rows (16.7%); 39/282 debates reached panel majority; mean rebuttal quality advantage -1.39.
- dropped argument: 134/846 judge rows (15.8%); 24/282 debates reached panel majority; mean rebuttal quality advantage -1.39.

### Judge salience

- Representative sample: 78 events across 30 event-bearing judge rows; argument construction 12/30 (40%), evidence use 11/30 (37%), direct engagement 9/30 (30%), burden handling 8/30 (27%), weighing 7/30 (23%), answer quality 7/30 (23%).
- Diagnostic sample: 95 events across 40 event-bearing judge rows; concession 27/40 (68%), evidence use 11/40 (28%), argument construction 8/40 (20%), format compliance 8/40 (20%), burden handling 8/40 (20%), clarity 6/40 (15%).
- Full current corpus: 1954 events across 746 event-bearing judge rows; argument construction 306/746 (41%), direct engagement 281/746 (38%), evidence use 179/746 (24%), burden handling 155/746 (21%), answer quality 147/746 (20%), format compliance 126/746 (17%).

- [representative] PRO offered a circular dividing line for aggressive pricing. Evidence: “A's line for "aggressive" was circular - "fractures shared events" in [A4.1]”
- [representative] PRO repeatedly asserted its streaming claim without comparing it to CON’s flat-pricing downside. Evidence: “A's attrition-to-streaming claim was asserted across four speeches without comparative weighing against sellout lotteries under flat pricing”
- [diagnostic] CON mistakenly switched sides in Rebuttal 2 and argued for the proposition. Evidence: “completely swapping sides to argue for public systems”

### Blind transcript observations

- Representative sample: 203 events across 22 event-bearing debates; direct engagement 22/22 (100%), weighing 20/22 (91%), question type 20/22 (91%), answer type 19/22 (86%), strawman 13/22 (59%), burden contest 11/22 (50%).
- Diagnostic sample: 190 events across 22 event-bearing debates; direct engagement 21/22 (95%), question type 21/22 (95%), answer type 20/22 (91%), weighing 17/22 (77%), burden contest 12/22 (55%), burden setting 12/22 (55%).
- Full current corpus: 2077 events across 238 event-bearing debates; question type 225/238 (95%), direct engagement 222/238 (93%), answer type 208/238 (87%), weighing 177/238 (74%), confident specificity 162/238 (68%), burden setting 122/238 (51%).

- [representative] CON contests the proposal by assigning PRO burdens concerning flexibility and consumer costs. Evidence: “A mandatory printed “guaranteed support lifespan” on packaging imposes rigid, one-size-fits-all requirements that ignore the variable, unpredictable nature of software support, while adding unnecessary costs that hit low-income shoppers hardest.”
- [representative] CON weighs asserted compliance burdens against a narrowly characterized beneficiary group. Evidence: “The mandate only punishes transparent companies to benefit the tiny share of buyers who never research a device before purchase.”
- [diagnostic] CON directly contests the premise that the resources removed necessarily constitute valuable capacity. Evidence: “PRO’s doomsday framing rests on a false equivalence: it treats all existing government headcount, contracts, and institutional routines as valuable capacity, when in reality many are the exact waste and duplication these drives are designed to eliminate.”

### Side-swap patterns

- Representative sample: 47 events across 11 event-bearing groups; stable behavior 11/11 (100%), contradiction candidate 9/11 (82%), advocacy flexibility 6/11 (55%), side specific behavior 5/11 (45%), evidence asymmetry 4/11 (36%), moral standard asymmetry 2/11 (18%).
- Diagnostic sample: 43 events across 11 event-bearing groups; stable behavior 11/11 (100%), contradiction candidate 8/11 (73%), evidence asymmetry 6/11 (55%), advocacy flexibility 4/11 (36%), side specific behavior 2/11 (18%), tradeoff hiding 2/11 (18%).
- Full current corpus: 484 events across 119 event-bearing groups; stable behavior 118/119 (99%), contradiction candidate 88/119 (74%), advocacy flexibility 59/119 (50%), evidence asymmetry 54/119 (45%), side specific behavior 39/119 (33%), moral standard asymmetry 26/119 (22%).

- [representative] As CON the model portrays fixed guarantees as rigid and impossible to lock in, while as PRO it says firms retain full flexibility and can treat extensions as bonuses, creating a contradiction candidate for open-book review.
- [representative] On both sides the model introduces a significant policy detail late, offering a QR-code alternative as CON and prospective support-quality standards as PRO.
- [diagnostic] The model uses named examples and precise quantitative details on both sides.

### Outcome associations

- Representative sample: 173 links across 22 debates; aligned 21/22 (95%), unclear 12/22 (55%), conflicted 11/22 (50%), judge_disagreement 8/22 (36%).
- Diagnostic sample: 143 links across 21 debates; aligned 19/21 (90%), judge_disagreement 16/21 (76%), conflicted 13/21 (62%), unclear 7/21 (33%).
- Full current corpus: 1118 links across 238 debates; aligned 222/238 (93%), conflicted 118/238 (50%), judge_disagreement 58/238 (24%), unclear 14/238 (6%).

## Claude Opus 4.7 (high)

### Deterministic execution

- Coverage: 172 current-peer debates / 860 turns.
- Mean raw words per turn: 251.7; mean word-limit use: 87.9%.
- Deterministically clipped turns: 3.5%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 8.01 | 7.35 | +0.66 | +1.15 [+0.98, +1.31] | 8.06 | 7.95 | 172 debates / 544 judge rows |
| Rebuttal quality | 8.21 | 7.35 | +0.86 | +1.44 [+1.24, +1.64] | 8.20 | 8.22 | 172 debates / 544 judge rows |
| Grounding / epistemics | 7.85 | 7.28 | +0.57 | +0.89 [+0.75, +1.03] | 7.89 | 7.81 | 172 debates / 544 judge rows |
| Originality | 7.35 | 6.81 | +0.54 | +0.91 [+0.77, +1.05] | 7.27 | 7.43 | 172 debates / 544 judge rows |
| Rhetorical effectiveness | 8.30 | 7.62 | +0.68 | +1.05 [+0.92, +1.19] | 8.33 | 8.26 | 172 debates / 544 judge rows |

### Judge-panel consensus

- direct engagement: 415/544 judge rows (76.3%); 137/172 debates reached panel majority; mean rebuttal quality advantage +1.44.
- argument construction: 287/544 judge rows (52.8%); 88/172 debates reached panel majority; mean argument strength advantage +1.15.
- weighing: 281/544 judge rows (51.7%); 87/172 debates reached panel majority; mean argument strength advantage +1.15.
- answer quality: 128/544 judge rows (23.5%); 23/172 debates reached panel majority; mean rebuttal quality advantage +1.44.
- burden handling: 108/544 judge rows (19.9%); 23/172 debates reached panel majority; mean argument strength advantage +1.15.
- evidence use: 59/544 judge rows (10.8%); 12/172 debates reached panel majority; mean grounding and epistemic discipline advantage +0.89.
- clarity: 52/544 judge rows (9.6%); 7/172 debates reached panel majority; mean rhetorical effectiveness advantage +1.05.
- question quality: 49/544 judge rows (9.0%); 6/172 debates reached panel majority; mean rebuttal quality advantage +1.44.

### Judge salience

- Representative sample: 67 events across 21 event-bearing judge rows; direct engagement 17/21 (81%), argument construction 14/21 (67%), weighing 13/21 (62%), concession 5/21 (24%), burden handling 3/21 (14%), clarity 3/21 (14%).
- Diagnostic sample: 58 events across 17 event-bearing judge rows; direct engagement 17/17 (100%), weighing 12/17 (71%), argument construction 8/17 (47%), evidence use 5/17 (29%), answer quality 5/17 (29%), burden handling 3/17 (18%).
- Full current corpus: 1554 events across 495 event-bearing judge rows; direct engagement 380/495 (77%), argument construction 265/495 (54%), weighing 256/495 (52%), answer quality 120/495 (24%), burden handling 102/495 (21%), evidence use 52/495 (11%).

- [representative] CON separated interface dark patterns from the ranking algorithm, narrowing what PRO had to defend. Evidence: “making a decisive tactical distinction between UI dark patterns and the recommender system itself”
- [representative] CON strategically conceded interface reforms and shifted the burden to PRO’s proposed ranking changes. Evidence: “By conceding UI reforms, A forced B to defend changing the ranking algorithm”
- [diagnostic] PRO controlled the framing by showing that CON’s preferred conditional amnesties aligned with the proposition’s comparison. Evidence: “completely controlled the strategic framing of the debate”

### Blind transcript observations

- Representative sample: 159 events across 17 event-bearing debates; direct engagement 17/17 (100%), question type 17/17 (100%), weighing 17/17 (100%), answer type 15/17 (88%), burden setting 11/17 (65%), burden contest 9/17 (53%).
- Diagnostic sample: 187 events across 19 event-bearing debates; weighing 19/19 (100%), question type 19/19 (100%), direct engagement 17/19 (89%), answer type 16/19 (84%), burden contest 13/19 (68%), burden setting 12/19 (63%).
- Full current corpus: 1321 events across 136 event-bearing debates; question type 136/136 (100%), weighing 130/136 (96%), direct engagement 130/136 (96%), answer type 126/136 (93%), burden setting 92/136 (68%), strategic concession 86/136 (63%).

- [representative] PRO narrows the proposed prohibition and distinguishes it from broader political persuasion. Evidence: “The motion does not ban political speech, persuasion, demographic outreach, or issue ads. It bans weaponizing inferred psychological profiles.”
- [representative] PRO directly distinguishes doorstep adaptation from dossier-based targeting. Evidence: “A canvasser doesn't carry a psychographic dossier built without consent, and her pitch isn't invisible to the rest of democracy.”
- [diagnostic] CON contests PRO's analogy to conventional employer-controlled availability. Evidence: “That is not employer-controlled standby — it is optionality the worker holds.”

### Side-swap patterns

- Representative sample: 27 events across 8 event-bearing groups; stable behavior 8/8 (100%), contradiction candidate 7/8 (88%), advocacy flexibility 3/8 (38%), tradeoff hiding 2/8 (25%), evidence asymmetry 2/8 (25%), moral standard asymmetry 1/8 (12%).
- Diagnostic sample: 41 events across 10 event-bearing groups; stable behavior 10/10 (100%), contradiction candidate 7/10 (70%), advocacy flexibility 7/10 (70%), evidence asymmetry 4/10 (40%), moral standard asymmetry 3/10 (30%), side specific behavior 3/10 (30%).
- Full current corpus: 233 events across 68 event-bearing groups; stable behavior 68/68 (100%), advocacy flexibility 47/68 (69%), contradiction candidate 39/68 (57%), evidence asymmetry 19/68 (28%), moral standard asymmetry 13/68 (19%), side specific behavior 12/68 (18%).

- [representative] As PRO the model presents an aggregate-versus-individual distinction and dossier-based enforcement target as workable, while as CON it argues that the same proposed boundary collapses under narrow or broad readings.
- [representative] As PRO the model says democratic auditing tools cannot see individualized psychological targeting, whereas as CON it says transparency also audits the behavior, creating a factual tension suitable for open-book review.
- [diagnostic] As CON the model says a utilization-adjusted per-trip minimum does not make logged-in time relevant to liability, while as PRO it calls that mechanism the proposition itself, creating a candidate contradiction for open-book review.

### Outcome associations

- Representative sample: 144 links across 17 debates; aligned 16/17 (94%), conflicted 6/17 (35%), unclear 3/17 (18%), judge_disagreement 2/17 (12%).
- Diagnostic sample: 153 links across 19 debates; aligned 17/19 (89%), judge_disagreement 14/19 (74%), unclear 10/19 (53%), conflicted 4/19 (21%).
- Full current corpus: 770 links across 136 debates; aligned 132/136 (97%), conflicted 22/136 (16%), judge_disagreement 17/136 (12%), unclear 2/136 (1%).

## GPT-5.5 (high)

### Deterministic execution

- Coverage: 228 current-peer debates / 1,140 turns.
- Mean raw words per turn: 269.5; mean word-limit use: 91.7%.
- Deterministically clipped turns: 54.6%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.35 | 7.35 | -0.00 | +0.09 [-0.05, +0.24] | 7.41 | 7.28 | 228 debates / 684 judge rows |
| Rebuttal quality | 7.42 | 7.35 | +0.07 | +0.16 [-0.02, +0.33] | 7.43 | 7.41 | 228 debates / 684 judge rows |
| Grounding / epistemics | 7.40 | 7.28 | +0.12 | +0.07 [-0.03, +0.18] | 7.43 | 7.38 | 228 debates / 684 judge rows |
| Originality | 6.87 | 6.81 | +0.06 | +0.18 [+0.05, +0.30] | 6.83 | 6.91 | 228 debates / 684 judge rows |
| Rhetorical effectiveness | 7.41 | 7.62 | -0.20 | -0.14 [-0.27, -0.02] | 7.55 | 7.28 | 228 debates / 684 judge rows |

### Judge-panel consensus

- direct engagement: 397/684 judge rows (58.0%); 144/228 debates reached panel majority; mean rebuttal quality advantage +0.16.
- argument construction: 365/684 judge rows (53.4%); 119/228 debates reached panel majority; mean argument strength advantage +0.09.
- format compliance: 209/684 judge rows (30.6%); 58/228 debates reached panel majority; mean rhetorical effectiveness advantage -0.14.
- weighing: 189/684 judge rows (27.6%); 49/228 debates reached panel majority; mean argument strength advantage +0.09.
- answer quality: 135/684 judge rows (19.7%); 26/228 debates reached panel majority; mean rebuttal quality advantage +0.16.
- burden handling: 119/684 judge rows (17.4%); 22/228 debates reached panel majority; mean argument strength advantage +0.09.
- clarity: 76/684 judge rows (11.1%); 7/228 debates reached panel majority; mean rhetorical effectiveness advantage -0.14.
- concession: 66/684 judge rows (9.6%); 14/228 debates reached panel majority; mean rebuttal quality advantage +0.16.

### Judge salience

- Representative sample: 45 events across 14 event-bearing judge rows; direct engagement 10/14 (71%), argument construction 7/14 (50%), weighing 6/14 (43%), format compliance 5/14 (36%), answer quality 3/14 (21%), concession 2/14 (14%).
- Diagnostic sample: 22 events across 10 event-bearing judge rows; direct engagement 5/10 (50%), argument construction 4/10 (40%), format compliance 3/10 (30%), burden handling 2/10 (20%), dropped argument 2/10 (20%), clarity 1/10 (10%).
- Full current corpus: 1888 events across 642 event-bearing judge rows; direct engagement 382/642 (60%), argument construction 353/642 (55%), weighing 183/642 (29%), format compliance 182/642 (28%), answer quality 130/642 (20%), burden handling 116/642 (18%).

- [representative] CON used PRO's concession to argue that PRO had added caveats absent from the motion. Evidence: “effectively leveraged this concession to show that Side A was quietly rewriting the motion”
- [representative] CON gained a decisive comparison by emphasizing irreversible harms from rushed return and reburial. Evidence: “Side B’s focus on irreversibility”
- [diagnostic] PRO supplied a clear mechanism explaining how regulatory accountability blocks beneficial innovation. Evidence: “establishing a clear mechanism (the asymmetry of regulatory accountability)”

### Blind transcript observations

- Representative sample: 244 events across 26 event-bearing debates; weighing 26/26 (100%), direct engagement 26/26 (100%), question type 26/26 (100%), answer type 23/26 (88%), strategic concession 19/26 (73%), burden setting 17/26 (65%).
- Diagnostic sample: 157 events across 18 event-bearing debates; direct engagement 18/18 (100%), question type 18/18 (100%), answer type 18/18 (100%), weighing 18/18 (100%), strategic concession 12/18 (67%), burden contest 11/18 (61%).
- Full current corpus: 1694 events across 184 event-bearing debates; question type 184/184 (100%), weighing 179/184 (97%), direct engagement 178/184 (97%), answer type 177/184 (96%), strategic concession 142/184 (77%), burden contest 116/184 (63%).

- [representative] CON contests whether evidence from selected trials supports a legal default covering most employees. Evidence: “The central flaw in the PRO case is the leap from “some trials maintained output” to “most full-time jobs should be legally redefined.””
- [representative] CON weighs implementation risks by emphasizing their possible concentration among the intended beneficiaries. Evidence: “The workers most exposed are not the privileged professionals who can compress meetings; they are the lower-margin, shift-based employees PRO claims to protect.”
- [diagnostic] PRO frames the burden as comparative affordability rather than universal initial affordability. Evidence: “The question is not whether every new apartment is affordable on day one. The question is whether the city has more homes than it otherwise would, and whether that reduces scarcity.”

### Side-swap patterns

- Representative sample: 41 events across 13 event-bearing groups; stable behavior 13/13 (100%), advocacy flexibility 10/13 (77%), evidence asymmetry 5/13 (38%), moral standard asymmetry 3/13 (23%), contradiction candidate 1/13 (8%), side specific behavior 1/13 (8%).
- Diagnostic sample: 31 events across 9 event-bearing groups; stable behavior 9/9 (100%), advocacy flexibility 7/9 (78%), moral standard asymmetry 4/9 (44%), contradiction candidate 3/9 (33%), tradeoff hiding 1/9 (11%), side specific behavior 1/9 (11%).
- Full current corpus: 307 events across 92 event-bearing groups; stable behavior 92/92 (100%), advocacy flexibility 66/92 (72%), contradiction candidate 32/92 (35%), moral standard asymmetry 25/92 (27%), evidence asymmetry 17/92 (18%), side specific behavior 11/92 (12%).

- [representative] In both roles, the model concedes that relevant costs exist before disputing their magnitude, incidence, or policy significance.
- [representative] Across sides, the model consistently engages the concrete financing and adaptation mechanisms for coverage-based work.
- [diagnostic] The model makes bounded concessions on both sides while preserving its central comparative position.

### Outcome associations

- Representative sample: 178 links across 26 debates; aligned 24/26 (92%), judge_disagreement 13/26 (50%), conflicted 5/26 (19%), unclear 5/26 (19%).
- Diagnostic sample: 125 links across 18 debates; aligned 13/18 (72%), judge_disagreement 12/18 (67%), conflicted 10/18 (56%), unclear 6/18 (33%).
- Full current corpus: 966 links across 184 debates; aligned 166/184 (90%), judge_disagreement 58/184 (32%), conflicted 56/184 (30%), unclear 4/184 (2%).

## GPT-5.4 (high)

### Deterministic execution

- Coverage: 134 current-peer debates / 670 turns.
- Mean raw words per turn: 255.8; mean word-limit use: 87.8%.
- Deterministically clipped turns: 25.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.54 | 7.35 | +0.20 | +0.56 [+0.35, +0.78] | 7.61 | 7.47 | 134 debates / 430 judge rows |
| Rebuttal quality | 7.56 | 7.35 | +0.21 | +0.58 [+0.31, +0.84] | 7.59 | 7.52 | 134 debates / 430 judge rows |
| Grounding / epistemics | 7.50 | 7.28 | +0.22 | +0.38 [+0.23, +0.52] | 7.50 | 7.49 | 134 debates / 430 judge rows |
| Originality | 6.92 | 6.81 | +0.12 | +0.44 [+0.26, +0.62] | 6.89 | 6.95 | 134 debates / 430 judge rows |
| Rhetorical effectiveness | 7.64 | 7.62 | +0.03 | +0.29 [+0.11, +0.47] | 7.73 | 7.55 | 134 debates / 430 judge rows |

### Judge-panel consensus

- direct engagement: 276/430 judge rows (64.2%); 89/134 debates reached panel majority; mean rebuttal quality advantage +0.58.
- argument construction: 238/430 judge rows (55.3%); 72/134 debates reached panel majority; mean argument strength advantage +0.56.
- weighing: 138/430 judge rows (32.1%); 33/134 debates reached panel majority; mean argument strength advantage +0.56.
- answer quality: 114/430 judge rows (26.5%); 24/134 debates reached panel majority; mean rebuttal quality advantage +0.58.
- burden handling: 85/430 judge rows (19.8%); 14/134 debates reached panel majority; mean argument strength advantage +0.56.
- clarity: 82/430 judge rows (19.1%); 15/134 debates reached panel majority; mean rhetorical effectiveness advantage +0.29.
- format compliance: 68/430 judge rows (15.8%); 14/134 debates reached panel majority; mean rhetorical effectiveness advantage +0.29.
- concession: 48/430 judge rows (11.2%); 6/134 debates reached panel majority; mean rebuttal quality advantage +0.58.

### Judge salience

- Representative sample: 38 events across 15 event-bearing judge rows; direct engagement 9/15 (60%), argument construction 6/15 (40%), weighing 5/15 (33%), burden handling 4/15 (27%), repetition 2/15 (13%), evidence use 2/15 (13%).
- Diagnostic sample: 6 events across 3 event-bearing judge rows; evidence use 2/3 (67%), direct engagement 2/3 (67%), concession 1/3 (33%), format compliance 1/3 (33%).
- Full current corpus: 1239 events across 396 event-bearing judge rows; direct engagement 265/396 (67%), argument construction 232/396 (59%), weighing 133/396 (34%), answer quality 113/396 (29%), burden handling 81/396 (20%), clarity 80/396 (20%).

- [representative] CON maintained a clear comparison between durable person-based incapacitation and bounded hot-spot effects. Evidence: “sustaining a cleaner comparative frame”
- [representative] CON turned PRO's pipeline argument into support for incapacitation rather than hot-spot superiority. Evidence: “recast A's pipeline argument as making hot spots merely an input into incapacitation rather than a superior substitute”
- [diagnostic] PRO failed to provide quantitative support or a concrete response on the central metric. Evidence: “received no numbers or concrete rebuttal from PRO”

### Blind transcript observations

- Representative sample: 125 events across 14 event-bearing debates; weighing 14/14 (100%), question type 14/14 (100%), direct engagement 13/14 (93%), strategic concession 13/14 (93%), answer type 13/14 (93%), burden setting 9/14 (64%).
- Diagnostic sample: 59 events across 6 event-bearing debates; direct engagement 6/6 (100%), weighing 6/6 (100%), question type 6/6 (100%), answer type 6/6 (100%), strategic concession 5/6 (83%), burden contest 3/6 (50%).
- Full current corpus: 1028 events across 114 event-bearing debates; question type 114/114 (100%), direct engagement 112/114 (98%), answer type 108/114 (95%), weighing 108/114 (95%), strategic concession 82/114 (72%), burden contest 73/114 (64%).

- [representative] CON contests the inference from absent opt-in to a legally enforceable refusal. Evidence: “For most people, that does not mean refusal; it means they never had a chance to confront the question.”
- [representative] CON weighs the prohibition’s asserted overbreadth against narrower regulation of specific harms. Evidence: “When a law suppresses preservation, speech, and remembrance to stop harms better targeted directly, it should not pass.”
- [diagnostic] CON contests the proposed equivalence between app availability and compensable employment. Evidence: “The motion confuses being available with being employed.”

### Side-swap patterns

- Representative sample: 24 events across 7 event-bearing groups; stable behavior 7/7 (100%), advocacy flexibility 5/7 (71%), moral standard asymmetry 3/7 (43%), contradiction candidate 2/7 (29%), side specific behavior 1/7 (14%).
- Diagnostic sample: 10 events across 3 event-bearing groups; contradiction candidate 3/3 (100%), stable behavior 3/3 (100%), moral standard asymmetry 1/3 (33%), advocacy flexibility 1/3 (33%), side specific behavior 1/3 (33%), evidence asymmetry 1/3 (33%).
- Full current corpus: 193 events across 57 event-bearing groups; stable behavior 57/57 (100%), advocacy flexibility 45/57 (79%), contradiction candidate 25/57 (44%), evidence asymmetry 17/57 (30%), moral standard asymmetry 10/57 (18%), side specific behavior 6/57 (11%).

- [representative] Across both sides, the model directly engages objections through distinctions, concrete safeguards, and responsive answers.
- [representative] Across both sides, the model makes explicit comparative judgments about overbreadth, historical exclusion, lost products, and consent.
- [diagnostic] As CON, the model said platform data cannot reveal multi-apping or actual use of idle time, while as PRO it treated existing timestamped status records as sufficient for pro-rata cross-platform allocation, creating a factual tension for open-book review.

### Outcome associations

- Representative sample: 115 links across 14 debates; aligned 13/14 (93%), judge_disagreement 7/14 (50%), unclear 4/14 (29%), conflicted 4/14 (29%).
- Diagnostic sample: 51 links across 6 debates; judge_disagreement 5/6 (83%), conflicted 4/6 (67%), aligned 3/6 (50%), unclear 3/6 (50%).
- Full current corpus: 687 links across 114 debates; aligned 106/114 (93%), judge_disagreement 27/114 (24%), conflicted 26/114 (23%), unclear 2/114 (2%).

## Gemini 3.5 Flash

### Deterministic execution

- Coverage: 238 current-peer debates / 1,190 turns.
- Mean raw words per turn: 221.3; mean word-limit use: 76.9%.
- Deterministically clipped turns: 0.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.83 | 7.35 | -0.52 | -0.77 [-0.92, -0.62] | 7.03 | 6.62 | 238 debates / 716 judge rows |
| Rebuttal quality | 6.65 | 7.35 | -0.70 | -1.02 [-1.21, -0.83] | 6.78 | 6.52 | 238 debates / 716 judge rows |
| Grounding / epistemics | 6.82 | 7.28 | -0.46 | -0.58 [-0.70, -0.46] | 6.96 | 6.68 | 238 debates / 716 judge rows |
| Originality | 6.16 | 6.81 | -0.65 | -0.71 [-0.83, -0.59] | 6.20 | 6.13 | 238 debates / 716 judge rows |
| Rhetorical effectiveness | 7.21 | 7.62 | -0.41 | -0.52 [-0.65, -0.40] | 7.36 | 7.06 | 238 debates / 716 judge rows |

### Judge-panel consensus

- argument construction: 314/716 judge rows (43.9%); 97/238 debates reached panel majority; mean argument strength advantage -0.77.
- direct engagement: 289/716 judge rows (40.4%); 88/238 debates reached panel majority; mean rebuttal quality advantage -1.02.
- burden handling: 165/716 judge rows (23.0%); 43/238 debates reached panel majority; mean argument strength advantage -0.77.
- dropped argument: 165/716 judge rows (23.0%); 38/238 debates reached panel majority; mean rebuttal quality advantage -1.02.
- answer quality: 155/716 judge rows (21.6%); 34/238 debates reached panel majority; mean rebuttal quality advantage -1.02.
- weighing: 109/716 judge rows (15.2%); 23/238 debates reached panel majority; mean argument strength advantage -0.77.
- concession: 81/716 judge rows (11.3%); 20/238 debates reached panel majority; mean rebuttal quality advantage -1.02.
- repetition: 78/716 judge rows (10.9%); 12/238 debates reached panel majority; mean rhetorical effectiveness advantage -0.52.

### Judge salience

- Representative sample: 52 events across 19 event-bearing judge rows; argument construction 9/19 (47%), direct engagement 8/19 (42%), dropped argument 6/19 (32%), weighing 5/19 (26%), repetition 5/19 (26%), burden handling 4/19 (21%).
- Diagnostic sample: 60 events across 28 event-bearing judge rows; concession 11/28 (39%), burden handling 8/28 (29%), argument construction 8/28 (29%), dropped argument 8/28 (29%), answer quality 6/28 (21%), direct engagement 5/28 (18%).
- Full current corpus: 1613 events across 656 event-bearing judge rows; argument construction 296/656 (45%), direct engagement 275/656 (42%), burden handling 153/656 (23%), dropped argument 151/656 (23%), answer quality 145/656 (22%), weighing 101/656 (15%).

- [representative] CON repeatedly treated cultural recognition as policing despite PRO's distinction. Evidence: “repeated conflation of cultural recognition with moralistic policing”
- [representative] CON did not adequately distinguish its gaming comparison from PRO's claimed intimate-replacement mechanism. Evidence: “failure to fully distinguish porn’s intimate replacement mechanism from generic stressors like gaming”
- [diagnostic] PRO admitted that its standard entailed unbounded extraterritorial liability. Evidence: “forcing an admission of unbounded extraterritorial liability”

### Blind transcript observations

- Representative sample: 200 events across 22 event-bearing debates; direct engagement 22/22 (100%), question type 22/22 (100%), answer type 22/22 (100%), weighing 21/22 (95%), strawman 14/22 (64%), burden contest 12/22 (55%).
- Diagnostic sample: 133 events across 14 event-bearing debates; question type 14/14 (100%), direct engagement 13/14 (93%), answer type 13/14 (93%), weighing 12/14 (86%), strawman 8/14 (57%), burden setting 7/14 (50%).
- Full current corpus: 1803 events across 202 event-bearing debates; question type 199/202 (99%), direct engagement 193/202 (96%), answer type 193/202 (96%), weighing 165/202 (82%), repetition 109/202 (54%), burden setting 107/202 (53%).

- [representative] PRO frames the platform’s obligation around correspondence between digital presentation and the person encountered offline. Evidence: “Their foundational promise is simple: the person you see on your screen is the person you will meet in real life.”
- [representative] PRO directly answers the accurate-image example by distinguishing photographic capture from synthetic generation. Evidence: “Even a highly flattering camera angle captures real-world light reflecting off a real human. An AI-generated image synthesizes pixels based on statistical models.”
- [diagnostic] PRO sets a categorical incompatibility burden for any regulatory alternative. Evidence: “There is no humane way to farm an octopus.”

### Side-swap patterns

- Representative sample: 45 events across 11 event-bearing groups; stable behavior 11/11 (100%), contradiction candidate 10/11 (91%), advocacy flexibility 5/11 (45%), moral standard asymmetry 3/11 (27%), side specific behavior 3/11 (27%), evidence asymmetry 3/11 (27%).
- Diagnostic sample: 27 events across 7 event-bearing groups; contradiction candidate 7/7 (100%), stable behavior 7/7 (100%), side specific behavior 3/7 (43%), advocacy flexibility 3/7 (43%), moral standard asymmetry 2/7 (29%), evidence asymmetry 2/7 (29%).
- Full current corpus: 388 events across 101 event-bearing groups; stable behavior 100/101 (99%), contradiction candidate 78/101 (77%), advocacy flexibility 53/101 (52%), evidence asymmetry 34/101 (34%), moral standard asymmetry 29/101 (29%), side specific behavior 20/101 (20%).

- [representative] The model consistently foregrounds implementation and circumvention problems, whether questioning verification as PRO or disclosure enforcement as CON.
- [representative] The model overstates its opponent’s position on both sides, characterizing a qualified standard as permission for complete fabrication and imperfect enforcement as total unenforceability.
- [diagnostic] As PRO it presents humane commercial farming as impossible, while as CON it asserts that viable modular enriched pilots exist, creating a factual tension for open-book review.

### Outcome associations

- Representative sample: 169 links across 22 debates; aligned 21/22 (95%), conflicted 17/22 (77%), unclear 13/22 (59%), judge_disagreement 7/22 (32%).
- Diagnostic sample: 105 links across 14 debates; aligned 12/14 (86%), judge_disagreement 9/14 (64%), unclear 7/14 (50%), conflicted 4/14 (29%).
- Full current corpus: 957 links across 202 debates; aligned 183/202 (91%), conflicted 116/202 (57%), judge_disagreement 48/202 (24%), unclear 13/202 (6%).

## Gemini 3.1 Pro Preview

### Deterministic execution

- Coverage: 256 current-peer debates / 1,280 turns.
- Mean raw words per turn: 247.7; mean word-limit use: 86.8%.
- Deterministically clipped turns: 0.3%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.18 | 7.35 | -0.16 | -0.24 [-0.37, -0.11] | 7.26 | 7.10 | 256 debates / 788 judge rows |
| Rebuttal quality | 7.16 | 7.35 | -0.19 | -0.29 [-0.46, -0.11] | 7.15 | 7.17 | 256 debates / 788 judge rows |
| Grounding / epistemics | 7.15 | 7.28 | -0.13 | -0.14 [-0.25, -0.03] | 7.22 | 7.07 | 256 debates / 788 judge rows |
| Originality | 6.55 | 6.81 | -0.26 | -0.31 [-0.43, -0.18] | 6.44 | 6.66 | 256 debates / 788 judge rows |
| Rhetorical effectiveness | 7.51 | 7.62 | -0.10 | -0.11 [-0.23, +0.01] | 7.57 | 7.45 | 256 debates / 788 judge rows |

### Judge-panel consensus

- direct engagement: 398/788 judge rows (50.5%); 125/256 debates reached panel majority; mean rebuttal quality advantage -0.29.
- argument construction: 361/788 judge rows (45.8%); 117/256 debates reached panel majority; mean argument strength advantage -0.24.
- burden handling: 176/788 judge rows (22.3%); 39/256 debates reached panel majority; mean argument strength advantage -0.24.
- weighing: 158/788 judge rows (20.1%); 36/256 debates reached panel majority; mean argument strength advantage -0.24.
- answer quality: 149/788 judge rows (18.9%); 30/256 debates reached panel majority; mean rebuttal quality advantage -0.29.
- dropped argument: 113/788 judge rows (14.3%); 15/256 debates reached panel majority; mean rebuttal quality advantage -0.29.
- concession: 101/788 judge rows (12.8%); 23/256 debates reached panel majority; mean rebuttal quality advantage -0.29.
- rhetoric: 79/788 judge rows (10.0%); 10/256 debates reached panel majority; mean rhetorical effectiveness advantage -0.11.

### Judge salience

- Representative sample: 53 events across 20 event-bearing judge rows; argument construction 12/20 (60%), direct engagement 9/20 (45%), answer quality 7/20 (35%), concession 6/20 (30%), evidence use 4/20 (20%), rhetoric 3/20 (15%).
- Diagnostic sample: 25 events across 11 event-bearing judge rows; argument construction 6/11 (55%), concession 4/11 (36%), burden handling 4/11 (36%), direct engagement 3/11 (27%), epistemic calibration 2/11 (18%), dropped argument 2/11 (18%).
- Full current corpus: 1904 events across 742 event-bearing judge rows; direct engagement 385/742 (52%), argument construction 339/742 (46%), burden handling 170/742 (23%), weighing 154/742 (21%), answer quality 141/742 (19%), dropped argument 108/742 (15%).

- [representative] CON used PRO’s concessions to establish decisive tradeoffs. Evidence: “CON won by internalizing PRO's own concessions to expose fatal trade-offs in the proposition.”
- [representative] CON connected high prices and spending caps to low procurement volumes. Evidence: “high price plus capped spending mathematically guarantees tiny procurement volumes”
- [diagnostic] PRO conceded unlimited price tolerance and permanent protectionism under pressure. Evidence: “forced PRO to concede both unlimited price tolerance and permanent protectionism”

### Blind transcript observations

- Representative sample: 146 events across 15 event-bearing debates; direct engagement 15/15 (100%), question type 15/15 (100%), weighing 15/15 (100%), answer type 13/15 (87%), confident specificity 8/15 (53%), burden contest 8/15 (53%).
- Diagnostic sample: 238 events across 25 event-bearing debates; direct engagement 25/25 (100%), question type 25/25 (100%), answer type 25/25 (100%), weighing 23/25 (92%), burden setting 13/25 (52%), strawman 13/25 (52%).
- Full current corpus: 2017 events across 216 event-bearing debates; question type 215/216 (100%), answer type 209/216 (97%), direct engagement 208/216 (96%), weighing 182/216 (84%), burden contest 109/216 (50%), burden setting 105/216 (49%).

- [representative] PRO frames the comparison around issuers’ financial functions rather than their technological form. Evidence: “We must regulate the underlying economic reality, not the technological packaging.”
- [representative] PRO directly turns CON’s proposed safeguards into support for a financial regulatory comparison, though it does not establish that they are exclusive to banks or funds. Evidence: “CON has just recited the core pillars of banking and money-market fund regulation.”
- [diagnostic] PRO frames reliable and immediate access as the central safety burden. Evidence: “Furthermore, the core functions in question are urgent safety utilities, not optional entertainment features.”

### Side-swap patterns

- Representative sample: 26 events across 7 event-bearing groups; stable behavior 7/7 (100%), contradiction candidate 6/7 (86%), advocacy flexibility 3/7 (43%), evidence asymmetry 2/7 (29%), tradeoff hiding 1/7 (14%), moral standard asymmetry 1/7 (14%).
- Diagnostic sample: 53 events across 13 event-bearing groups; stable behavior 13/13 (100%), contradiction candidate 11/13 (85%), moral standard asymmetry 8/13 (62%), evidence asymmetry 6/13 (46%), advocacy flexibility 5/13 (38%), side specific behavior 2/13 (15%).
- Full current corpus: 424 events across 108 event-bearing groups; stable behavior 108/108 (100%), contradiction candidate 87/108 (81%), advocacy flexibility 53/108 (49%), moral standard asymmetry 50/108 (46%), evidence asymmetry 35/108 (32%), side specific behavior 24/108 (22%).

- [representative] Across sides, the model evaluates regulation through economic function and risk rather than technological labels alone.
- [representative] As PRO the model endorses MMF-style requirements and prioritizes reserve value, while as CON it argues that tailoring away legacy rules concedes the bank and MMF models are mismatched.
- [diagnostic] Across sides, the model analyzes failures by distinguishing the user interface from underlying electronic controllers and functions.

### Outcome associations

- Representative sample: 132 links across 15 debates; aligned 13/15 (87%), unclear 11/15 (73%), conflicted 9/15 (60%), judge_disagreement 4/15 (27%).
- Diagnostic sample: 192 links across 25 debates; aligned 23/25 (92%), judge_disagreement 16/25 (64%), conflicted 14/25 (56%), unclear 10/25 (40%).
- Full current corpus: 1087 links across 216 debates; aligned 203/216 (94%), conflicted 86/216 (40%), judge_disagreement 68/216 (31%), unclear 12/216 (6%).

## Grok 4.3

### Deterministic execution

- Coverage: 152 current-peer debates / 760 turns.
- Mean raw words per turn: 197.7; mean word-limit use: 69.0%.
- Deterministically clipped turns: 0.4%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.52 | 7.35 | -0.82 | -1.21 [-1.38, -1.04] | 6.72 | 6.33 | 152 debates / 460 judge rows |
| Rebuttal quality | 6.32 | 7.35 | -1.02 | -1.58 [-1.79, -1.37] | 6.51 | 6.14 | 152 debates / 460 judge rows |
| Grounding / epistemics | 6.76 | 7.28 | -0.52 | -0.65 [-0.79, -0.51] | 6.93 | 6.60 | 152 debates / 460 judge rows |
| Originality | 5.94 | 6.81 | -0.87 | -1.09 [-1.23, -0.95] | 6.01 | 5.87 | 152 debates / 460 judge rows |
| Rhetorical effectiveness | 6.62 | 7.62 | -0.99 | -1.37 [-1.51, -1.24] | 6.77 | 6.48 | 152 debates / 460 judge rows |

### Judge-panel consensus

- argument construction: 158/460 judge rows (34.3%); 42/152 debates reached panel majority; mean argument strength advantage -1.21.
- direct engagement: 133/460 judge rows (28.9%); 37/152 debates reached panel majority; mean rebuttal quality advantage -1.58.
- burden handling: 115/460 judge rows (25.0%); 26/152 debates reached panel majority; mean argument strength advantage -1.21.
- dropped argument: 113/460 judge rows (24.6%); 24/152 debates reached panel majority; mean rebuttal quality advantage -1.58.
- answer quality: 101/460 judge rows (22.0%); 23/152 debates reached panel majority; mean rebuttal quality advantage -1.58.
- concession: 87/460 judge rows (18.9%); 26/152 debates reached panel majority; mean rebuttal quality advantage -1.58.
- weighing: 58/460 judge rows (12.6%); 11/152 debates reached panel majority; mean argument strength advantage -1.21.
- repetition: 44/460 judge rows (9.6%); 5/152 debates reached panel majority; mean rhetorical effectiveness advantage -1.37.

### Judge salience

- Representative sample: 38 events across 14 event-bearing judge rows; dropped argument 6/14 (43%), direct engagement 5/14 (36%), argument construction 5/14 (36%), burden handling 4/14 (29%), repetition 4/14 (29%), answer quality 3/14 (21%).
- Diagnostic sample: 27 events across 14 event-bearing judge rows; concession 6/14 (43%), argument construction 5/14 (36%), burden handling 5/14 (36%), evidence use 3/14 (21%), answer quality 3/14 (21%), direct engagement 2/14 (14%).
- Full current corpus: 907 events across 392 event-bearing judge rows; argument construction 146/392 (37%), direct engagement 125/392 (32%), burden handling 106/392 (27%), dropped argument 104/392 (27%), answer quality 95/392 (24%), concession 78/392 (20%).

- [representative] PRO did not overcome CON’s access and rationing objection. Evidence: “could not overcome the demonstrated reality that the proposition structurally monetizes a global health crisis and rations cures by wealth”
- [representative] PRO answered the reactive-enforcement defense by identifying preventive broker-dealer safeguards. Evidence: “broker-dealer status provides proactive, mandatory trips (net capital calculations and segregation audits) that prevent these collapses before they happen”
- [diagnostic] CON did not adequately ground several repeated empirical claims. Evidence: “repeatedly asserted weak uptake, displacement, and failed trials without adequately grounding those claims”

### Blind transcript observations

- Representative sample: 73 events across 9 event-bearing debates; direct engagement 9/9 (100%), question type 9/9 (100%), weighing 9/9 (100%), answer type 8/9 (89%), burden contest 5/9 (56%), strategic concession 5/9 (56%).
- Diagnostic sample: 96 events across 11 event-bearing debates; direct engagement 11/11 (100%), question type 11/11 (100%), answer type 10/11 (91%), weighing 10/11 (91%), burden contest 6/11 (55%), burden setting 6/11 (55%).
- Full current corpus: 1129 events across 132 event-bearing debates; question type 132/132 (100%), direct engagement 126/132 (95%), answer type 126/132 (95%), weighing 125/132 (95%), strategic concession 79/132 (60%), burden setting 65/132 (49%).

- [representative] PRO establishes an outcome-based standard for evaluating genuine opportunity. Evidence: “Genuine opportunity would manifest as increased mobility into better-paid work or new industries that value the additional human capital.”
- [representative] PRO directly challenges CON’s use of the wage premium as evidence of expanded productive opportunity. Evidence: “Persistent earnings gaps between graduates and non-graduates demonstrate the penalty for lacking the new minimum, but they do not show an increase in the total number of roles that reward advanced competence.”
- [diagnostic] CON contests PRO's exploitation framing by characterizing the material as ordinary family documentation. Evidence: “That shift treats ordinary family documentation as something closer to third-party commercial exploitation, when the parent is both creator and subject.”

### Side-swap patterns

- Representative sample: 17 events across 5 event-bearing groups; contradiction candidate 5/5 (100%), stable behavior 5/5 (100%), advocacy flexibility 4/5 (80%), moral standard asymmetry 1/5 (20%), side specific behavior 1/5 (20%).
- Diagnostic sample: 18 events across 5 event-bearing groups; stable behavior 5/5 (100%), contradiction candidate 4/5 (80%), advocacy flexibility 2/5 (40%), side specific behavior 2/5 (40%), tradeoff hiding 1/5 (20%), evidence asymmetry 1/5 (20%).
- Full current corpus: 237 events across 66 event-bearing groups; stable behavior 66/66 (100%), contradiction candidate 51/66 (77%), advocacy flexibility 39/66 (59%), evidence asymmetry 19/66 (29%), side specific behavior 13/66 (20%), moral standard asymmetry 12/66 (18%).

- [representative] As PRO the model described a stable set of positions with inflated entry requirements, while as CON it emphasized changed job content and an enlarged set of productive roles.
- [representative] The model flexibly moved from comparing degree growth against better-paid opportunities as PRO to emphasizing restricted-access counterfactuals and productive-role growth as CON.
- [diagnostic] As CON the model claimed existing privacy tools could handle non-exploitative cases, while as PRO it argued that only a statutory obligation could truncate ongoing indexed exposure and restrain repeated uploading.

### Outcome associations

- Representative sample: 64 links across 9 debates; conflicted 7/9 (78%), aligned 7/9 (78%), judge_disagreement 3/9 (33%), unclear 3/9 (33%).
- Diagnostic sample: 75 links across 11 debates; aligned 11/11 (100%), conflicted 6/11 (55%), judge_disagreement 6/11 (55%), unclear 5/11 (45%).
- Full current corpus: 578 links across 132 debates; aligned 116/132 (88%), conflicted 86/132 (65%), judge_disagreement 26/132 (20%), unclear 10/132 (8%).

## Tencent Hy3 Preview (high)

### Deterministic execution

- Coverage: 188 current-peer debates / 940 turns.
- Mean raw words per turn: 232.4; mean word-limit use: 79.7%.
- Deterministically clipped turns: 10.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.54 | 7.35 | -0.81 | -1.14 [-1.33, -0.95] | 6.68 | 6.39 | 188 debates / 564 judge rows |
| Rebuttal quality | 6.34 | 7.35 | -1.01 | -1.49 [-1.73, -1.25] | 6.43 | 6.26 | 188 debates / 564 judge rows |
| Grounding / epistemics | 6.54 | 7.28 | -0.74 | -0.89 [-1.04, -0.73] | 6.64 | 6.44 | 188 debates / 564 judge rows |
| Originality | 5.98 | 6.81 | -0.83 | -1.04 [-1.19, -0.89] | 6.01 | 5.95 | 188 debates / 564 judge rows |
| Rhetorical effectiveness | 6.80 | 7.62 | -0.81 | -1.08 [-1.24, -0.92] | 6.97 | 6.64 | 188 debates / 564 judge rows |

### Judge-panel consensus

- argument construction: 206/564 judge rows (36.5%); 63/188 debates reached panel majority; mean argument strength advantage -1.14.
- direct engagement: 206/564 judge rows (36.5%); 59/188 debates reached panel majority; mean rebuttal quality advantage -1.49.
- answer quality: 136/564 judge rows (24.1%); 33/188 debates reached panel majority; mean rebuttal quality advantage -1.49.
- burden handling: 125/564 judge rows (22.2%); 34/188 debates reached panel majority; mean argument strength advantage -1.14.
- dropped argument: 117/564 judge rows (20.7%); 25/188 debates reached panel majority; mean rebuttal quality advantage -1.49.
- format compliance: 100/564 judge rows (17.7%); 26/188 debates reached panel majority; mean rhetorical effectiveness advantage -1.08.
- concession: 89/564 judge rows (15.8%); 21/188 debates reached panel majority; mean rebuttal quality advantage -1.49.
- weighing: 75/564 judge rows (13.3%); 18/188 debates reached panel majority; mean argument strength advantage -1.14.

### Judge salience

- Representative sample: 42 events across 18 event-bearing judge rows; argument construction 7/18 (39%), format compliance 6/18 (33%), burden handling 6/18 (33%), direct engagement 5/18 (28%), concession 4/18 (22%), epistemic calibration 3/18 (17%).
- Diagnostic sample: 42 events across 18 event-bearing judge rows; concession 7/18 (39%), dropped argument 6/18 (33%), argument construction 5/18 (28%), burden handling 4/18 (22%), clarity 4/18 (22%), format compliance 4/18 (22%).
- Full current corpus: 1256 events across 498 event-bearing judge rows; direct engagement 199/498 (40%), argument construction 193/498 (39%), answer quality 131/498 (26%), burden handling 115/498 (23%), dropped argument 108/498 (22%), format compliance 80/498 (16%).

- [representative] CON’s clipped rebuttal incurred an execution penalty. Evidence: “Side B suffered a notable execution cost with a clipped rebuttal”
- [representative] CON relied on an unattainable security standard. Evidence: “relied on a standard of security that Side A proved was unachievable for any platform”
- [diagnostic] PRO relied on unsupported numerical specificity in a closed-book setting. Evidence: “stacks of precise, unsourced cost figures and timing claims that read as brittle fake precision”

### Blind transcript observations

- Representative sample: 160 events across 17 event-bearing debates; weighing 17/17 (100%), question type 17/17 (100%), direct engagement 16/17 (94%), answer type 16/17 (94%), burden contest 10/17 (59%), confident specificity 9/17 (53%).
- Diagnostic sample: 129 events across 15 event-bearing debates; direct engagement 14/15 (93%), answer type 14/15 (93%), question type 13/15 (87%), weighing 13/15 (87%), strawman 8/15 (53%), confident specificity 8/15 (53%).
- Full current corpus: 1412 events across 156 event-bearing debates; direct engagement 151/156 (97%), question type 151/156 (97%), answer type 145/156 (93%), weighing 125/156 (80%), burden setting 83/156 (53%), strawman 82/156 (53%).

- [representative] CON contests whether evidence from knowledge-work settings can satisfy an economy-wide burden. Evidence: “The proposition rests on a fatal category error: it equates the experience of a narrow slice of knowledge workers with the reality of the entire full-time workforce.”
- [representative] CON centers immediate payroll costs as the principal counterweight to PRO's claimed benefits. Evidence: “Cutting their workweek to four days without pay reduction forces employers to pay 25% more in payroll to cover the same 5-day operational needs, at a 25% higher effective hourly rate.”
- [diagnostic] CON characterizes PRO as making an absolute claim despite PRO’s express qualifications. Evidence: “PRO’s core error is treating housing as a generic commodity where more units always equal lower prices”

### Side-swap patterns

- Representative sample: 34 events across 8 event-bearing groups; stable behavior 8/8 (100%), advocacy flexibility 6/8 (75%), contradiction candidate 5/8 (62%), side specific behavior 4/8 (50%), evidence asymmetry 3/8 (38%), moral standard asymmetry 3/8 (38%).
- Diagnostic sample: 31 events across 8 event-bearing groups; stable behavior 8/8 (100%), contradiction candidate 6/8 (75%), moral standard asymmetry 4/8 (50%), advocacy flexibility 3/8 (38%), evidence asymmetry 2/8 (25%), side specific behavior 1/8 (12%).
- Full current corpus: 313 events across 78 event-bearing groups; stable behavior 75/78 (96%), contradiction candidate 62/78 (79%), advocacy flexibility 35/78 (45%), moral standard asymmetry 33/78 (42%), evidence asymmetry 31/78 (40%), side specific behavior 23/78 (29%).

- [representative] On both sides, hy3-preview-high directly answers sector-generalization arguments with concrete claims about frontline work.
- [representative] On both sides, hy3-preview-high makes strategic concessions while preserving its central position.
- [diagnostic] As CON the model predicts broad upzoning will spike citywide land values through option value, whereas as PRO it predicts broad legalization will collapse holdout premiums and erase scarcity rent, creating a factual tension for open-book review.

### Outcome associations

- Representative sample: 126 links across 17 debates; aligned 16/17 (94%), unclear 9/17 (53%), conflicted 7/17 (41%), judge_disagreement 4/17 (24%).
- Diagnostic sample: 99 links across 15 debates; aligned 12/15 (80%), judge_disagreement 10/15 (67%), unclear 7/15 (47%), conflicted 5/15 (33%).
- Full current corpus: 680 links across 156 debates; aligned 147/156 (94%), conflicted 98/156 (63%), judge_disagreement 24/156 (15%), unclear 4/156 (3%).

## MiniMax-M2.7

### Deterministic execution

- Coverage: 92 current-peer debates / 460 turns.
- Mean raw words per turn: 276.2; mean word-limit use: 97.2%.
- Deterministically clipped turns: 46.1%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.87 | 7.35 | -0.48 | -0.63 [-0.91, -0.36] | 7.18 | 6.55 | 92 debates / 300 judge rows |
| Rebuttal quality | 6.79 | 7.35 | -0.56 | -0.80 [-1.13, -0.46] | 7.07 | 6.51 | 92 debates / 300 judge rows |
| Grounding / epistemics | 6.97 | 7.28 | -0.31 | -0.31 [-0.53, -0.08] | 7.13 | 6.81 | 92 debates / 300 judge rows |
| Originality | 6.56 | 6.81 | -0.25 | -0.23 [-0.42, -0.04] | 6.61 | 6.50 | 92 debates / 300 judge rows |
| Rhetorical effectiveness | 7.19 | 7.62 | -0.43 | -0.57 [-0.80, -0.34] | 7.41 | 6.97 | 92 debates / 300 judge rows |

### Judge-panel consensus

- argument construction: 129/300 judge rows (43.0%); 35/92 debates reached panel majority; mean argument strength advantage -0.63.
- direct engagement: 119/300 judge rows (39.7%); 31/92 debates reached panel majority; mean rebuttal quality advantage -0.80.
- format compliance: 102/300 judge rows (34.0%); 24/92 debates reached panel majority; mean rhetorical effectiveness advantage -0.57.
- burden handling: 68/300 judge rows (22.7%); 14/92 debates reached panel majority; mean argument strength advantage -0.63.
- answer quality: 59/300 judge rows (19.7%); 8/92 debates reached panel majority; mean rebuttal quality advantage -0.80.
- concession: 56/300 judge rows (18.7%); 14/92 debates reached panel majority; mean rebuttal quality advantage -0.80.
- weighing: 44/300 judge rows (14.7%); 8/92 debates reached panel majority; mean argument strength advantage -0.63.
- clarity: 39/300 judge rows (13.0%); 4/92 debates reached panel majority; mean rhetorical effectiveness advantage -0.57.

### Judge salience

- Representative sample: 24 events across 10 event-bearing judge rows; argument construction 6/10 (60%), direct engagement 5/10 (50%), answer quality 3/10 (30%), format compliance 2/10 (20%), concession 2/10 (20%), evidence use 1/10 (10%).
- Diagnostic sample: 31 events across 11 event-bearing judge rows; concession 7/11 (64%), format compliance 6/11 (55%), burden handling 4/11 (36%), clarity 3/11 (27%), argument construction 3/11 (27%), answer quality 2/11 (18%).
- Full current corpus: 706 events across 272 event-bearing judge rows; argument construction 120/272 (44%), direct engagement 113/272 (42%), format compliance 88/272 (32%), burden handling 63/272 (23%), answer quality 54/272 (20%), concession 47/272 (17%).

- [representative] CON evaded PRO’s pressure questions. Evidence: “completely evading Side A's Pressure Questions”
- [representative] CON revisited its own questions rather than engaging PRO’s challenges. Evidence: “choosing instead to re-litigate its own questions”
- [diagnostic] CON’s defense of truth-seeking conditional amnesties effectively conceded the preference over broad silence-for-stability amnesties. Evidence: “effectively conceded the motion's preference”

### Blind transcript observations

- Representative sample: 109 events across 12 event-bearing debates; direct engagement 12/12 (100%), question type 12/12 (100%), strategic concession 10/12 (83%), weighing 10/12 (83%), answer type 8/12 (67%), burden contest 7/12 (58%).
- Diagnostic sample: 113 events across 12 event-bearing debates; direct engagement 12/12 (100%), question type 12/12 (100%), weighing 10/12 (83%), answer type 8/12 (67%), strawman 7/12 (58%), burden contest 5/12 (42%).
- Full current corpus: 637 events across 68 event-bearing debates; question type 68/68 (100%), direct engagement 61/68 (90%), answer type 57/68 (84%), strategic concession 49/68 (72%), weighing 47/68 (69%), burden setting 39/68 (57%).

- [representative] CON concedes the underlying problem while preserving disagreement over the proposed remedy. Evidence: “Indoor air quality in many buildings is poor, and that matters for health and productivity.”
- [representative] CON shifts the contested burden from demonstrating harm to justifying enforceable mandates. Evidence: “But identifying a problem is not the same as proving that government mandates are the right solution.”
- [diagnostic] CON accepts the welfare concern before contesting the proposed remedy. Evidence: “The PRO case makes a compelling case about octopus intelligence and welfare concerns. I don't deny either.”

### Side-swap patterns

- Representative sample: 21 events across 6 event-bearing groups; stable behavior 6/6 (100%), advocacy flexibility 3/6 (50%), moral standard asymmetry 3/6 (50%), contradiction candidate 2/6 (33%), side specific behavior 2/6 (33%).
- Diagnostic sample: 23 events across 6 event-bearing groups; stable behavior 6/6 (100%), contradiction candidate 5/6 (83%), side specific behavior 4/6 (67%), advocacy flexibility 2/6 (33%), moral standard asymmetry 1/6 (17%), evidence asymmetry 1/6 (17%).
- Full current corpus: 128 events across 34 event-bearing groups; stable behavior 34/34 (100%), advocacy flexibility 19/34 (56%), contradiction candidate 18/34 (53%), evidence asymmetry 13/34 (38%), side specific behavior 8/34 (24%), moral standard asymmetry 8/34 (24%).

- [representative] The model consistently foregrounds market failure or poor indoor air while treating the choice of remedy as the decisive dispute.
- [representative] Across sides, the model emphasizes operational details by probing or supplying testing, liability, sequencing, and compliance mechanisms.
- [diagnostic] As CON it rejects the inference from current constraints to permanent biological impossibility, while as PRO it makes that inference before partially softening it, creating a factual tension for open-book review.

### Outcome associations

- Representative sample: 83 links across 12 debates; aligned 11/12 (92%), conflicted 8/12 (67%), unclear 5/12 (42%), judge_disagreement 1/12 (8%).
- Diagnostic sample: 87 links across 12 debates; aligned 11/12 (92%), judge_disagreement 8/12 (67%), unclear 7/12 (58%), conflicted 3/12 (25%).
- Full current corpus: 291 links across 68 debates; aligned 63/68 (93%), conflicted 21/68 (31%), judge_disagreement 18/68 (26%), unclear 2/68 (3%).

## ByteDance Seed2.0 Pro

### Deterministic execution

- Coverage: 224 current-peer debates / 1,120 turns.
- Mean raw words per turn: 199.2; mean word-limit use: 68.8%.
- Deterministically clipped turns: 0.3%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.92 | 7.35 | -0.43 | -0.56 [-0.73, -0.40] | 6.97 | 6.87 | 224 debates / 688 judge rows |
| Rebuttal quality | 6.84 | 7.35 | -0.51 | -0.72 [-0.94, -0.51] | 6.78 | 6.89 | 224 debates / 688 judge rows |
| Grounding / epistemics | 6.62 | 7.28 | -0.66 | -0.73 [-0.88, -0.57] | 6.65 | 6.58 | 224 debates / 688 judge rows |
| Originality | 6.55 | 6.81 | -0.26 | -0.29 [-0.43, -0.15] | 6.47 | 6.64 | 224 debates / 688 judge rows |
| Rhetorical effectiveness | 7.53 | 7.62 | -0.09 | -0.09 [-0.23, +0.05] | 7.59 | 7.47 | 224 debates / 688 judge rows |

### Judge-panel consensus

- argument construction: 265/688 judge rows (38.5%); 73/224 debates reached panel majority; mean argument strength advantage -0.56.
- direct engagement: 250/688 judge rows (36.3%); 75/224 debates reached panel majority; mean rebuttal quality advantage -0.72.
- burden handling: 148/688 judge rows (21.5%); 33/224 debates reached panel majority; mean argument strength advantage -0.56.
- weighing: 141/688 judge rows (20.5%); 40/224 debates reached panel majority; mean argument strength advantage -0.56.
- evidence use: 139/688 judge rows (20.2%); 27/224 debates reached panel majority; mean grounding and epistemic discipline advantage -0.73.
- dropped argument: 115/688 judge rows (16.7%); 18/224 debates reached panel majority; mean rebuttal quality advantage -0.72.
- answer quality: 106/688 judge rows (15.4%); 20/224 debates reached panel majority; mean rebuttal quality advantage -0.72.
- concession: 96/688 judge rows (14.0%); 23/224 debates reached panel majority; mean rebuttal quality advantage -0.72.

### Judge salience

- Representative sample: 56 events across 21 event-bearing judge rows; argument construction 12/21 (57%), burden handling 7/21 (33%), direct engagement 7/21 (33%), dropped argument 6/21 (29%), answer quality 5/21 (24%), evidence use 4/21 (19%).
- Diagnostic sample: 27 events across 10 event-bearing judge rows; burden handling 5/10 (50%), direct engagement 3/10 (30%), argument construction 3/10 (30%), evidence use 3/10 (30%), answer quality 2/10 (20%), rhetoric 2/10 (20%).
- Full current corpus: 1541 events across 625 event-bearing judge rows; argument construction 249/625 (40%), direct engagement 240/625 (38%), weighing 137/625 (22%), burden handling 136/625 (22%), evidence use 129/625 (21%), dropped argument 108/625 (17%).

- [representative] PRO repeated prior claims instead of engaging CON’s mechanism. Evidence: “largely repeated earlier assertions rather than engaging the voluntary-vs-binding distinction or the walkout mechanism”
- [representative] PRO left CON’s slippery-slope concern effectively unanswered. Evidence: “B also left A's slippery-slope point (other vulnerable groups demanding the same weighting) effectively unanswered by A”
- [diagnostic] PRO converted CON's verification objection into an argument against punishment. Evidence: “turning B's main practical objection—that police cannot verify shelter availability—into Side A's strongest moral argument”

### Blind transcript observations

- Representative sample: 120 events across 13 event-bearing debates; question type 13/13 (100%), weighing 11/13 (85%), direct engagement 10/13 (77%), confident specificity 9/13 (69%), burden contest 9/13 (69%), answer type 8/13 (62%).
- Diagnostic sample: 388 events across 41 event-bearing debates; question type 40/41 (98%), direct engagement 38/41 (93%), answer type 36/41 (88%), weighing 34/41 (83%), strategic concession 26/41 (63%), burden contest 24/41 (59%).
- Full current corpus: 1571 events across 170 event-bearing debates; direct engagement 161/170 (95%), question type 161/170 (95%), answer type 145/170 (85%), weighing 126/170 (74%), confident specificity 115/170 (68%), strategic concession 105/170 (62%).

- [representative] CON identifies a class of calculating participants not covered by PRO's examples of suicidal perpetrators. Evidence: “PRO only addresses suicidal attackers when discussing deterrence. They entirely ignore the enablers: the bomb maker who does not intend to die, the attack coordinator who plans to escape and live quietly.”
- [representative] CON contests an absolute treatment of wrongful-execution risk by proposing proportionality. Evidence: “No human justice system operates at zero risk. We only ask that risk be proportional.”
- [diagnostic] CON contests PRO’s attempt to limit the relevant security concerns to data access. Evidence: “National security is not only stopping bulk data theft.”

### Side-swap patterns

- Representative sample: 26 events across 6 event-bearing groups; stable behavior 6/6 (100%), contradiction candidate 5/6 (83%), evidence asymmetry 4/6 (67%), advocacy flexibility 4/6 (67%), moral standard asymmetry 2/6 (33%), side specific behavior 1/6 (17%).
- Diagnostic sample: 84 events across 21 event-bearing groups; stable behavior 20/21 (95%), contradiction candidate 15/21 (71%), advocacy flexibility 11/21 (52%), evidence asymmetry 7/21 (33%), moral standard asymmetry 6/21 (29%), side specific behavior 5/21 (24%).
- Full current corpus: 340 events across 85 event-bearing groups; stable behavior 84/85 (99%), contradiction candidate 59/85 (69%), advocacy flexibility 45/85 (53%), evidence asymmetry 31/85 (36%), moral standard asymmetry 24/85 (28%), tradeoff hiding 18/85 (21%).

- [representative] Seed argues as CON that executed terrorists are forgotten but as PRO that execution creates permanent martyr myths, presenting a contradiction candidate for open-book review.
- [representative] Seed invokes proportional tolerance of justice-system risk when CON but elevates execution's irreversibility into an uncrossable line when PRO.
- [diagnostic] As PRO the model claimed all concrete regulator-identified risks were blocked, while as CON it attributed an unneutralized cognitive-manipulation threat to CFIUS, creating a contradiction candidate for open-book review.

### Outcome associations

- Representative sample: 92 links across 13 debates; aligned 13/13 (100%), conflicted 8/13 (62%), unclear 6/13 (46%), judge_disagreement 3/13 (23%).
- Diagnostic sample: 290 links across 41 debates; aligned 37/41 (90%), judge_disagreement 27/41 (66%), unclear 15/41 (37%), conflicted 12/41 (29%).
- Full current corpus: 747 links across 170 debates; aligned 159/170 (94%), conflicted 88/170 (52%), judge_disagreement 41/170 (24%), unclear 7/170 (4%).

## Qwen 3.6 Max Preview

### Deterministic execution

- Coverage: 152 current-peer debates / 760 turns.
- Mean raw words per turn: 225.7; mean word-limit use: 79.5%.
- Deterministically clipped turns: 0.8%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.20 | 7.35 | -0.14 | -0.15 [-0.33, +0.03] | 7.32 | 7.09 | 152 debates / 456 judge rows |
| Rebuttal quality | 7.27 | 7.35 | -0.08 | -0.12 [-0.35, +0.11] | 7.33 | 7.21 | 152 debates / 456 judge rows |
| Grounding / epistemics | 7.26 | 7.28 | -0.02 | +0.07 [-0.07, +0.21] | 7.31 | 7.21 | 152 debates / 456 judge rows |
| Originality | 6.62 | 6.81 | -0.19 | -0.20 [-0.35, -0.05] | 6.71 | 6.53 | 152 debates / 456 judge rows |
| Rhetorical effectiveness | 7.50 | 7.62 | -0.12 | -0.13 [-0.27, +0.01] | 7.65 | 7.35 | 152 debates / 456 judge rows |

### Judge-panel consensus

- direct engagement: 233/456 judge rows (51.1%); 80/152 debates reached panel majority; mean rebuttal quality advantage -0.12.
- argument construction: 219/456 judge rows (48.0%); 73/152 debates reached panel majority; mean argument strength advantage -0.15.
- burden handling: 95/456 judge rows (20.8%); 21/152 debates reached panel majority; mean argument strength advantage -0.15.
- answer quality: 94/456 judge rows (20.6%); 19/152 debates reached panel majority; mean rebuttal quality advantage -0.12.
- weighing: 88/456 judge rows (19.3%); 17/152 debates reached panel majority; mean argument strength advantage -0.15.
- dropped argument: 64/456 judge rows (14.0%); 8/152 debates reached panel majority; mean rebuttal quality advantage -0.12.
- concession: 42/456 judge rows (9.2%); 9/152 debates reached panel majority; mean rebuttal quality advantage -0.12.
- evidence use: 41/456 judge rows (9.0%); 7/152 debates reached panel majority; mean grounding and epistemic discipline advantage +0.07.

### Judge salience

- Representative sample: 30 events across 13 event-bearing judge rows; argument construction 8/13 (62%), direct engagement 8/13 (62%), rhetoric 2/13 (15%), dropped argument 2/13 (15%), burden handling 2/13 (15%), weighing 2/13 (15%).
- Diagnostic sample: 19 events across 10 event-bearing judge rows; argument construction 5/10 (50%), direct engagement 4/10 (40%), burden handling 4/10 (40%), dropped argument 2/10 (20%), answer quality 2/10 (20%), rhetoric 1/10 (10%).
- Full current corpus: 1070 events across 412 event-bearing judge rows; direct engagement 221/412 (54%), argument construction 205/412 (50%), answer quality 91/412 (22%), burden handling 89/412 (22%), weighing 86/412 (21%), dropped argument 60/412 (15%).

- [representative] CON established enforceability as the central deficiency in PRO’s guardrails. Evidence: “the proposition’s two guardrails—transparency and debris control—cannot substitute for enforceable governance”
- [representative] CON identified specific institutional gaps supporting its enforcement argument. Evidence: “the Outer Space Treaty lacks an adjudicatory body, priority rules, or injunctive power”
- [diagnostic] PRO's choice and ownership reframes did not answer CON's accountability and fixed-cost objections. Evidence: “never neutralized the accountability gap or timing of fixed-cost impacts”

### Blind transcript observations

- Representative sample: 225 events across 24 event-bearing debates; question type 24/24 (100%), answer type 24/24 (100%), direct engagement 22/24 (92%), weighing 21/24 (88%), repetition 17/24 (71%), burden contest 13/24 (54%).
- Diagnostic sample: 112 events across 12 event-bearing debates; direct engagement 12/12 (100%), question type 12/12 (100%), answer type 12/12 (100%), weighing 10/12 (83%), burden contest 6/12 (50%), confident specificity 6/12 (50%).
- Full current corpus: 1037 events across 116 event-bearing debates; direct engagement 116/116 (100%), question type 115/116 (99%), weighing 113/116 (97%), answer type 113/116 (97%), burden setting 60/116 (52%), burden contest 59/116 (51%).

- [representative] CON directly challenges the funding-follows-the-child argument with a fixed-cost mechanism. Evidence: “Public schools carry heavy fixed costs: buildings, transportation routes, special education infrastructure, and contracted staff.”
- [representative] CON allows that some families may benefit while shifting the comparison to system-wide effects. Evidence: “The question isn’t whether a subset of families might find a better fit, but whether governments should deliberately weaken the universal system that educates the vast majority.”
- [diagnostic] CON reframes the proposal around its immediate hourly-cost implication. Evidence: “Mandating a four-day week at identical base pay is not a neutral schedule change; it is a legislated twenty-five percent increase in hourly labor costs.”

### Side-swap patterns

- Representative sample: 46 events across 12 event-bearing groups; stable behavior 12/12 (100%), contradiction candidate 11/12 (92%), advocacy flexibility 9/12 (75%), moral standard asymmetry 3/12 (25%), evidence asymmetry 2/12 (17%), side specific behavior 2/12 (17%).
- Diagnostic sample: 24 events across 6 event-bearing groups; stable behavior 6/6 (100%), advocacy flexibility 4/6 (67%), contradiction candidate 4/6 (67%), evidence asymmetry 3/6 (50%), tradeoff hiding 2/6 (33%), moral standard asymmetry 1/6 (17%).
- Full current corpus: 237 events across 58 event-bearing groups; stable behavior 58/58 (100%), contradiction candidate 48/58 (83%), advocacy flexibility 37/58 (64%), evidence asymmetry 22/58 (38%), moral standard asymmetry 15/58 (26%), side specific behavior 14/58 (24%).

- [representative] As CON the model pressed the legal ability of private schools to reject students or refuse accommodations, whereas as PRO it cited schools serving disadvantaged communities without addressing the admission-mandate issue.
- [representative] As CON the model emphasized a universal educational floor, while as PRO it framed family control over education dollars as the decisive principle.
- [diagnostic] Qwen consistently answers staffing and cost objections with concrete labor-market mechanisms on both sides.

### Outcome associations

- Representative sample: 196 links across 24 debates; aligned 22/24 (92%), unclear 11/24 (46%), conflicted 11/24 (46%), judge_disagreement 10/24 (42%).
- Diagnostic sample: 78 links across 12 debates; aligned 10/12 (83%), judge_disagreement 8/12 (67%), conflicted 6/12 (50%), unclear 5/12 (42%).
- Full current corpus: 558 links across 114 debates; aligned 97/114 (85%), conflicted 52/114 (46%), judge_disagreement 40/114 (35%), unclear 2/114 (2%).

## Qwen3.5-397B-A17B

### Deterministic execution

- Coverage: 112 current-peer debates / 560 turns.
- Mean raw words per turn: 238.2; mean word-limit use: 82.1%.
- Deterministically clipped turns: 0.7%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.70 | 7.35 | -0.65 | -0.87 [-1.11, -0.64] | 6.93 | 6.46 | 112 debates / 354 judge rows |
| Rebuttal quality | 6.60 | 7.35 | -0.74 | -1.03 [-1.33, -0.74] | 6.76 | 6.45 | 112 debates / 354 judge rows |
| Grounding / epistemics | 6.75 | 7.28 | -0.53 | -0.57 [-0.76, -0.38] | 6.95 | 6.54 | 112 debates / 354 judge rows |
| Originality | 6.27 | 6.81 | -0.54 | -0.65 [-0.85, -0.45] | 6.34 | 6.20 | 112 debates / 354 judge rows |
| Rhetorical effectiveness | 7.35 | 7.62 | -0.26 | -0.25 [-0.46, -0.05] | 7.56 | 7.15 | 112 debates / 354 judge rows |

### Judge-panel consensus

- argument construction: 141/354 judge rows (39.8%); 35/112 debates reached panel majority; mean argument strength advantage -0.87.
- direct engagement: 129/354 judge rows (36.4%); 36/112 debates reached panel majority; mean rebuttal quality advantage -1.03.
- burden handling: 84/354 judge rows (23.7%); 17/112 debates reached panel majority; mean argument strength advantage -0.87.
- weighing: 75/354 judge rows (21.2%); 19/112 debates reached panel majority; mean argument strength advantage -0.87.
- dropped argument: 73/354 judge rows (20.6%); 13/112 debates reached panel majority; mean rebuttal quality advantage -1.03.
- answer quality: 56/354 judge rows (15.8%); 6/112 debates reached panel majority; mean rebuttal quality advantage -1.03.
- concession: 53/354 judge rows (15.0%); 12/112 debates reached panel majority; mean rebuttal quality advantage -1.03.
- rhetoric: 38/354 judge rows (10.7%); 4/112 debates reached panel majority; mean rhetorical effectiveness advantage -0.25.

### Judge salience

- Representative sample: 17 events across 6 event-bearing judge rows; direct engagement 4/6 (67%), weighing 3/6 (50%), argument construction 3/6 (50%), answer quality 2/6 (33%), concession 1/6 (17%), epistemic calibration 1/6 (17%).
- Diagnostic sample: 22 events across 12 event-bearing judge rows; burden handling 5/12 (42%), argument construction 5/12 (42%), concession 3/12 (25%), evidence use 2/12 (17%), direct engagement 2/12 (17%), epistemic calibration 1/12 (8%).
- Full current corpus: 775 events across 318 event-bearing judge rows; argument construction 133/318 (42%), direct engagement 123/318 (39%), burden handling 79/318 (25%), dropped argument 72/318 (23%), weighing 70/318 (22%), answer quality 53/318 (17%).

- [representative] CON conceded that local displacement was an intended feature of its auction logic. Evidence: “called locals being outbid a "feature, not a bug,"”
- [representative] PRO repeated vulnerable-case claims without fully addressing majority tradeoffs or financing. Evidence: “B's responses rely more on repeated assertions about vulnerable cases without fully engaging the majority tradeoffs or financial mechanisms”
- [diagnostic] CON presented its collapse and resistance claims too strongly. Evidence: “overstated collapse and resistance claims”

### Blind transcript observations

- Representative sample: 77 events across 8 event-bearing debates; direct engagement 8/8 (100%), question type 8/8 (100%), answer type 8/8 (100%), weighing 7/8 (88%), strawman 6/8 (75%), repetition 5/8 (62%).
- Diagnostic sample: 129 events across 14 event-bearing debates; direct engagement 14/14 (100%), question type 14/14 (100%), answer type 12/14 (86%), weighing 11/14 (79%), burden setting 8/14 (57%), strawman 8/14 (57%).
- Full current corpus: 860 events across 90 event-bearing debates; direct engagement 89/90 (99%), question type 89/90 (99%), answer type 86/90 (96%), weighing 82/90 (91%), repetition 54/90 (60%), strawman 49/90 (54%).

- [representative] CON accepts the transparency goal while contesting whether mandates are an appropriate remedy. Evidence: “Transparency is valuable, but mandates are blunt instruments that break the machine they try to fix.”
- [representative] CON characterizes preregistration as locking hypotheses despite PRO explicitly allowing exploratory analyses with labeling. Evidence: “By locking researchers into initial hypotheses before data collection, mandatory preregistration punishes the iterative nature of discovery.”
- [diagnostic] PRO frames the decision around the relative magnitude and reversibility of the competing harms. Evidence: “We must weigh minor inconveniences against irreversible loss.”

### Side-swap patterns

- Representative sample: 16 events across 4 event-bearing groups; contradiction candidate 4/4 (100%), stable behavior 4/4 (100%), tradeoff hiding 2/4 (50%), side specific behavior 1/4 (25%), evidence asymmetry 1/4 (25%).
- Diagnostic sample: 28 events across 7 event-bearing groups; stable behavior 7/7 (100%), contradiction candidate 6/7 (86%), moral standard asymmetry 4/7 (57%), side specific behavior 3/7 (43%), evidence asymmetry 2/7 (29%), advocacy flexibility 1/7 (14%).
- Full current corpus: 185 events across 45 event-bearing groups; stable behavior 44/45 (98%), contradiction candidate 34/45 (76%), advocacy flexibility 24/45 (53%), moral standard asymmetry 20/45 (44%), evidence asymmetry 19/45 (42%), side specific behavior 8/45 (18%).

- [representative] Qwen portrays preregistration as harmful hypothesis-locking when CON but defends locking methodological plans as protection against variable swapping when PRO, creating a scope-sensitive candidate for open-book review.
- [representative] Qwen receives ineffective strawman annotations on both sides for overstating the opponent’s position about the scope and rigidity of social-science preregistration.
- [diagnostic] Across sides, the model frames the dispute through comparative burdens and directly tests inconsistencies in the opposing case.

### Outcome associations

- Representative sample: 52 links across 8 debates; aligned 8/8 (100%), conflicted 7/8 (88%), unclear 3/8 (38%), judge_disagreement 1/8 (12%).
- Diagnostic sample: 117 links across 14 debates; aligned 14/14 (100%), judge_disagreement 10/14 (71%), unclear 7/14 (50%), conflicted 5/14 (36%).
- Full current corpus: 389 links across 90 debates; aligned 82/90 (91%), conflicted 50/90 (56%), judge_disagreement 19/90 (21%), unclear 5/90 (6%).

## Kimi K2.6

### Deterministic execution

- Coverage: 238 current-peer debates / 1,190 turns.
- Mean raw words per turn: 241.7; mean word-limit use: 83.6%.
- Deterministically clipped turns: 4.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.44 | 7.35 | +0.10 | -0.01 [-0.16, +0.14] | 7.53 | 7.36 | 238 debates / 713 judge rows |
| Rebuttal quality | 7.47 | 7.35 | +0.12 | -0.01 [-0.20, +0.18] | 7.51 | 7.42 | 238 debates / 713 judge rows |
| Grounding / epistemics | 7.39 | 7.28 | +0.11 | +0.07 [-0.04, +0.18] | 7.42 | 7.35 | 238 debates / 713 judge rows |
| Originality | 6.89 | 6.81 | +0.08 | +0.02 [-0.10, +0.14] | 6.90 | 6.88 | 238 debates / 713 judge rows |
| Rhetorical effectiveness | 7.85 | 7.62 | +0.24 | +0.20 [+0.08, +0.32] | 7.96 | 7.75 | 238 debates / 713 judge rows |

### Judge-panel consensus

- direct engagement: 381/713 judge rows (53.4%); 130/238 debates reached panel majority; mean rebuttal quality advantage -0.01.
- argument construction: 360/713 judge rows (50.5%); 129/238 debates reached panel majority; mean argument strength advantage -0.01.
- answer quality: 178/713 judge rows (25.0%); 49/238 debates reached panel majority; mean rebuttal quality advantage -0.01.
- weighing: 158/713 judge rows (22.2%); 34/238 debates reached panel majority; mean argument strength advantage -0.01.
- burden handling: 123/713 judge rows (17.3%); 27/238 debates reached panel majority; mean argument strength advantage -0.01.
- rhetoric: 88/713 judge rows (12.3%); 13/238 debates reached panel majority; mean rhetorical effectiveness advantage +0.20.
- dropped argument: 71/713 judge rows (10.0%); 7/238 debates reached panel majority; mean rebuttal quality advantage -0.01.
- clarity: 70/713 judge rows (9.8%); 9/238 debates reached panel majority; mean rhetorical effectiveness advantage +0.20.

### Judge salience

- Representative sample: 71 events across 24 event-bearing judge rows; argument construction 14/24 (58%), direct engagement 11/24 (46%), answer quality 8/24 (33%), burden handling 5/24 (21%), weighing 5/24 (21%), concession 4/24 (17%).
- Diagnostic sample: 25 events across 12 event-bearing judge rows; direct engagement 6/12 (50%), argument construction 6/12 (50%), question quality 2/12 (17%), concession 2/12 (17%), answer quality 2/12 (17%), rhetoric 1/12 (8%).
- Full current corpus: 1762 events across 642 event-bearing judge rows; direct engagement 363/642 (57%), argument construction 336/642 (52%), answer quality 168/642 (26%), weighing 152/642 (24%), burden handling 118/642 (18%), rhetoric 81/642 (13%).

- [representative] PRO presented the cleaner causal comparison between legal pathways and enforcement. Evidence: “A won by making the cleaner causal comparison”
- [representative] PRO effectively leveraged CON’s concession about current pathways. Evidence: “A better used B's concession that current legal pathways are too narrow and slow.”
- [diagnostic] PRO successfully challenged CON's interpretation of the proposition. Evidence: “dismantling B's overly rigid definition of "same basic terms."”

### Blind transcript observations

- Representative sample: 251 events across 27 event-bearing debates; direct engagement 27/27 (100%), question type 27/27 (100%), answer type 27/27 (100%), weighing 23/27 (85%), repetition 19/27 (70%), burden setting 15/27 (56%).
- Diagnostic sample: 129 events across 13 event-bearing debates; direct engagement 13/13 (100%), weighing 13/13 (100%), question type 12/13 (92%), answer type 12/13 (92%), burden contest 8/13 (62%), progression 8/13 (62%).
- Full current corpus: 1780 events across 198 event-bearing debates; question type 197/198 (99%), direct engagement 196/198 (99%), answer type 194/198 (98%), weighing 168/198 (85%), strategic concession 108/198 (55%), burden setting 107/198 (54%).

- [representative] CON presents a causal mechanism from unenforceability to reduced settlement value. Evidence: “Remove enforceability, and that currency evaporates. Employers no longer pay a premium for something they cannot own.”
- [representative] CON characterizes the motion as forced publicity even though disclosure is not required by the stated proposition. Evidence: “A blanket ban collapses that spectrum into a single forced-publicity regime.”
- [diagnostic] CON contests PRO's separation of continuing influence from the relevant security threat. Evidence: “For a platform whose core threat is covert algorithmic manipulation and bulk data exploitation, Chinese operational influence is the security threat.”

### Side-swap patterns

- Representative sample: 44 events across 12 event-bearing groups; stable behavior 12/12 (100%), contradiction candidate 12/12 (100%), advocacy flexibility 8/12 (67%), evidence asymmetry 3/12 (25%), side specific behavior 2/12 (17%), moral standard asymmetry 1/12 (8%).
- Diagnostic sample: 31 events across 8 event-bearing groups; stable behavior 8/8 (100%), advocacy flexibility 7/8 (88%), contradiction candidate 4/8 (50%), side specific behavior 3/8 (38%), moral standard asymmetry 1/8 (12%), evidence asymmetry 1/8 (12%).
- Full current corpus: 375 events across 99 event-bearing groups; stable behavior 99/99 (100%), contradiction candidate 71/99 (72%), advocacy flexibility 60/99 (61%), moral standard asymmetry 39/99 (39%), evidence asymmetry 27/99 (27%), side specific behavior 19/99 (19%).

- [representative] Kimi consistently tests settlement incentives and economic mechanisms through causal claims and pointed questions on both sides.
- [representative] Kimi frames payment for confidentiality as material value and autonomy when CON but as financially coercive pressure when PRO.
- [diagnostic] Across sides, the model acknowledges that ByteDance retains upstream algorithmic influence not eliminated by downstream data or deployment safeguards.

### Outcome associations

- Representative sample: 200 links across 27 debates; aligned 25/27 (93%), unclear 14/27 (52%), conflicted 11/27 (41%), judge_disagreement 6/27 (22%).
- Diagnostic sample: 95 links across 13 debates; aligned 12/13 (92%), judge_disagreement 9/13 (69%), unclear 6/13 (46%), conflicted 3/13 (23%).
- Full current corpus: 946 links across 198 debates; aligned 194/198 (98%), conflicted 74/198 (37%), judge_disagreement 45/198 (23%), unclear 6/198 (3%).

## DeepSeek V4 Pro Preview

### Deterministic execution

- Coverage: 232 current-peer debates / 1,160 turns.
- Mean raw words per turn: 289.7; mean word-limit use: 98.5%.
- Deterministically clipped turns: 53.7%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.95 | 7.35 | -0.39 | -0.59 [-0.74, -0.44] | 7.05 | 6.86 | 232 debates / 697 judge rows |
| Rebuttal quality | 6.86 | 7.35 | -0.49 | -0.82 [-1.01, -0.64] | 6.94 | 6.77 | 232 debates / 697 judge rows |
| Grounding / epistemics | 6.97 | 7.28 | -0.31 | -0.41 [-0.53, -0.29] | 6.99 | 6.95 | 232 debates / 697 judge rows |
| Originality | 6.55 | 6.81 | -0.26 | -0.34 [-0.47, -0.22] | 6.51 | 6.59 | 232 debates / 697 judge rows |
| Rhetorical effectiveness | 7.20 | 7.62 | -0.42 | -0.63 [-0.76, -0.50] | 7.34 | 7.05 | 232 debates / 697 judge rows |

### Judge-panel consensus

- argument construction: 311/697 judge rows (44.6%); 100/232 debates reached panel majority; mean argument strength advantage -0.59.
- format compliance: 295/697 judge rows (42.3%); 87/232 debates reached panel majority; mean rhetorical effectiveness advantage -0.63.
- direct engagement: 290/697 judge rows (41.6%); 98/232 debates reached panel majority; mean rebuttal quality advantage -0.82.
- burden handling: 153/697 judge rows (22.0%); 38/232 debates reached panel majority; mean argument strength advantage -0.59.
- weighing: 119/697 judge rows (17.1%); 22/232 debates reached panel majority; mean argument strength advantage -0.59.
- answer quality: 106/697 judge rows (15.2%); 20/232 debates reached panel majority; mean rebuttal quality advantage -0.82.
- dropped argument: 87/697 judge rows (12.5%); 12/232 debates reached panel majority; mean rebuttal quality advantage -0.82.
- concession: 74/697 judge rows (10.6%); 17/232 debates reached panel majority; mean rebuttal quality advantage -0.82.

### Judge salience

- Representative sample: 54 events across 20 event-bearing judge rows; direct engagement 13/20 (65%), argument construction 11/20 (55%), format compliance 7/20 (35%), weighing 5/20 (25%), evidence use 4/20 (20%), concession 3/20 (15%).
- Diagnostic sample: 28 events across 12 event-bearing judge rows; format compliance 8/12 (67%), dropped argument 4/12 (33%), direct engagement 3/12 (25%), burden handling 3/12 (25%), argument construction 2/12 (17%), concession 2/12 (17%).
- Full current corpus: 1690 events across 638 event-bearing judge rows; argument construction 296/638 (46%), direct engagement 274/638 (43%), format compliance 262/638 (41%), burden handling 148/638 (23%), weighing 113/638 (18%), answer quality 101/638 (16%).

- [representative] CON established the stronger comparative framework. Evidence: “B won by making the key comparison about frequency, chronic runoff pollution, disruption, and opportunity cost”
- [representative] CON repeatedly exceeded or mishandled the allotted format. Evidence: “B’s repeated clipping was an execution cost”
- [diagnostic] CON’s empty-room scenario did not address PRO’s policy interpretation. Evidence: “its empty-room scenario never answered B's policy of preserving scarce human moments while using AI around them”

### Blind transcript observations

- Representative sample: 287 events across 33 event-bearing debates; direct engagement 33/33 (100%), question type 31/33 (94%), answer type 31/33 (94%), weighing 27/33 (82%), burden setting 21/33 (64%), strategic concession 19/33 (58%).
- Diagnostic sample: 182 events across 21 event-bearing debates; direct engagement 21/21 (100%), question type 20/21 (95%), answer type 20/21 (95%), weighing 19/21 (90%), progression 11/21 (52%), burden setting 10/21 (48%).
- Full current corpus: 1608 events across 178 event-bearing debates; direct engagement 175/178 (98%), question type 175/178 (98%), answer type 171/178 (96%), weighing 163/178 (92%), strategic concession 112/178 (63%), burden contest 96/178 (54%).

- [representative] PRO frames the dispute as comparative weighing rather than denying that implementation has costs. Evidence: “The question is whether benefits justify the cost, and they do.”
- [representative] PRO makes a broad empirical claim without identifying any trial or result in the transcript. Evidence: “Large-scale trials across sectors and countries, from manufacturing to healthcare to finance, consistently show that when people work fewer days, they maintain output.”
- [diagnostic] PRO frames the central burden around creating new supply independent of rainfall. Evidence: “Only large-scale desalination turns an unlimited ocean into a drought‑proof, climate‑independent water supply.”

### Side-swap patterns

- Representative sample: 63 events across 17 event-bearing groups; stable behavior 17/17 (100%), contradiction candidate 14/17 (82%), advocacy flexibility 7/17 (41%), evidence asymmetry 6/17 (35%), moral standard asymmetry 4/17 (24%), tradeoff hiding 2/17 (12%).
- Diagnostic sample: 36 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 8/10 (80%), contradiction candidate 6/10 (60%), evidence asymmetry 5/10 (50%), tradeoff hiding 1/10 (10%), moral standard asymmetry 1/10 (10%).
- Full current corpus: 332 events across 89 event-bearing groups; stable behavior 89/89 (100%), contradiction candidate 66/89 (74%), advocacy flexibility 60/89 (67%), evidence asymmetry 28/89 (31%), moral standard asymmetry 23/89 (26%), side specific behavior 13/89 (15%).

- [representative] In both roles, the model acknowledges the proposal's appeal or costs and frames the dispute around whether the economic tradeoff is justified.
- [representative] Its PRO case makes broad or unquantified claims about maintained output and small residual costs, whereas its CON case more consistently specifies economic conditions and scope objections.
- [diagnostic] The model consistently engages by challenging a central premise or distinction in the opposing case.

### Outcome associations

- Representative sample: 239 links across 33 debates; aligned 29/33 (88%), conflicted 20/33 (61%), unclear 13/33 (39%), judge_disagreement 9/33 (27%).
- Diagnostic sample: 140 links across 21 debates; aligned 19/21 (90%), judge_disagreement 13/21 (62%), conflicted 9/21 (43%), unclear 5/21 (24%).
- Full current corpus: 770 links across 177 debates; aligned 158/177 (89%), conflicted 82/177 (46%), judge_disagreement 51/177 (29%), unclear 11/177 (6%).

## Mistral Medium 3.5 (high)

### Deterministic execution

- Coverage: 186 current-peer debates / 930 turns.
- Mean raw words per turn: 203.8; mean word-limit use: 68.3%.
- Deterministically clipped turns: 7.0%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 6.35 | 7.35 | -1.00 | -1.46 [-1.62, -1.31] | 6.52 | 6.18 | 186 debates / 557 judge rows |
| Rebuttal quality | 5.96 | 7.35 | -1.39 | -2.07 [-2.26, -1.89] | 6.06 | 5.86 | 186 debates / 557 judge rows |
| Grounding / epistemics | 6.51 | 7.28 | -0.77 | -0.98 [-1.12, -0.85] | 6.55 | 6.47 | 186 debates / 557 judge rows |
| Originality | 5.73 | 6.81 | -1.08 | -1.39 [-1.52, -1.27] | 5.77 | 5.68 | 186 debates / 557 judge rows |
| Rhetorical effectiveness | 6.60 | 7.62 | -1.01 | -1.35 [-1.48, -1.22] | 6.77 | 6.43 | 186 debates / 557 judge rows |

### Judge-panel consensus

- burden handling: 161/557 judge rows (28.9%); 48/186 debates reached panel majority; mean argument strength advantage -1.46.
- dropped argument: 153/557 judge rows (27.5%); 34/186 debates reached panel majority; mean rebuttal quality advantage -2.07.
- direct engagement: 152/557 judge rows (27.3%); 38/186 debates reached panel majority; mean rebuttal quality advantage -2.07.
- argument construction: 151/557 judge rows (27.1%); 33/186 debates reached panel majority; mean argument strength advantage -1.46.
- answer quality: 103/557 judge rows (18.5%); 16/186 debates reached panel majority; mean rebuttal quality advantage -2.07.
- repetition: 100/557 judge rows (18.0%); 15/186 debates reached panel majority; mean rhetorical effectiveness advantage -1.35.
- concession: 85/557 judge rows (15.3%); 20/186 debates reached panel majority; mean rebuttal quality advantage -2.07.
- evidence use: 75/557 judge rows (13.5%); 9/186 debates reached panel majority; mean grounding and epistemic discipline advantage -0.98.

### Judge salience

- Representative sample: 35 events across 14 event-bearing judge rows; argument construction 5/14 (36%), answer quality 5/14 (36%), dropped argument 5/14 (36%), direct engagement 4/14 (29%), burden handling 3/14 (21%), concession 2/14 (14%).
- Diagnostic sample: 64 events across 29 event-bearing judge rows; concession 13/29 (45%), burden handling 11/29 (38%), dropped argument 7/29 (24%), answer quality 6/29 (21%), direct engagement 6/29 (21%), argument construction 4/29 (14%).
- Full current corpus: 1136 events across 476 event-bearing judge rows; burden handling 147/476 (31%), direct engagement 142/476 (30%), dropped argument 141/476 (30%), argument construction 141/476 (30%), repetition 96/476 (20%), answer quality 91/476 (19%).

- [representative] PRO presented a strong moral argument against retaining remains obtained through colonial practices. Evidence: “Side A built a strong moral case against colonial retention”
- [representative] PRO conceded procedural prerequisites that weakened the proposition's categorical formulation. Evidence: “strategically conceded that verification, inventories, and consultation must precede return”
- [diagnostic] CON made late claims about touchscreen-dependent safety features without support. Evidence: “some late unsupported overclaims about touchscreen-required safety features”

### Blind transcript observations

- Representative sample: 214 events across 25 event-bearing debates; answer type 24/25 (96%), direct engagement 23/25 (92%), question type 22/25 (88%), weighing 19/25 (76%), repetition 15/25 (60%), confident specificity 14/25 (56%).
- Diagnostic sample: 123 events across 13 event-bearing debates; direct engagement 13/13 (100%), question type 13/13 (100%), answer type 13/13 (100%), weighing 12/13 (92%), repetition 9/13 (69%), strategic concession 9/13 (69%).
- Full current corpus: 1353 events across 148 event-bearing debates; question type 144/148 (97%), direct engagement 142/148 (96%), answer type 138/148 (93%), weighing 118/148 (80%), repetition 96/148 (65%), burden setting 80/148 (54%).

- [representative] PRO frames functional equivalence in competitive harm as the basis for scrutiny. Evidence: “The harm is identical to overt collusion: eliminated price competition, reduced consumer surplus, and a market that looks competitive but functions like a cartel.”
- [representative] PRO directly answers CON’s discretion argument by disputing whether deviation is economically meaningful. Evidence: “CON claims landlords retain discretion, but the algorithm’s design makes deviation economically irrational.”
- [diagnostic] CON contests PRO’s characterization of the proposal as modest by reframing its effect on family authority. Evidence: “This is not a modest adjustment; it is a radical redistribution of authority within the family.”

### Side-swap patterns

- Representative sample: 48 events across 12 event-bearing groups; stable behavior 11/12 (92%), contradiction candidate 10/12 (83%), evidence asymmetry 6/12 (50%), advocacy flexibility 5/12 (42%), side specific behavior 5/12 (42%), moral standard asymmetry 4/12 (33%).
- Diagnostic sample: 25 events across 7 event-bearing groups; contradiction candidate 7/7 (100%), stable behavior 7/7 (100%), advocacy flexibility 4/7 (57%), evidence asymmetry 2/7 (29%), moral standard asymmetry 1/7 (14%), tradeoff hiding 1/7 (14%).
- Full current corpus: 292 events across 74 event-bearing groups; stable behavior 73/74 (99%), contradiction candidate 56/74 (76%), advocacy flexibility 40/74 (54%), evidence asymmetry 38/74 (51%), moral standard asymmetry 29/74 (39%), side specific behavior 11/74 (15%).

- [representative] As PRO the model said deviation was economically irrational, while as CON it said overrides were routine and landlords deviated constantly because vacancies cause revenue loss.
- [representative] As CON the model demanded empirical support for irrational deviation, whereas as PRO it embedded that premise in its argument, although its own CON-side examples also lacked an identified source.
- [diagnostic] As CON the model characterized social embarrassment as temporary, whereas as PRO it characterized persistent digital exposure as irreversible, creating a factual tension for open-book review.

### Outcome associations

- Representative sample: 201 links across 25 debates; aligned 23/25 (92%), conflicted 22/25 (88%), unclear 17/25 (68%), judge_disagreement 1/25 (4%).
- Diagnostic sample: 88 links across 13 debates; aligned 12/13 (92%), judge_disagreement 8/13 (62%), conflicted 6/13 (46%), unclear 4/13 (31%).
- Full current corpus: 634 links across 147 debates; aligned 132/147 (90%), conflicted 104/147 (71%), judge_disagreement 30/147 (20%), unclear 7/147 (5%).

## Xiaomi MiMo V2.5 Pro

### Deterministic execution

- Coverage: 260 current-peer debates / 1,300 turns.
- Mean raw words per turn: 277.5; mean word-limit use: 97.4%.
- Deterministically clipped turns: 53.3%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.24 | 7.35 | -0.11 | -0.20 [-0.34, -0.06] | 7.30 | 7.17 | 260 debates / 780 judge rows |
| Rebuttal quality | 7.21 | 7.35 | -0.14 | -0.29 [-0.47, -0.11] | 7.20 | 7.22 | 260 debates / 780 judge rows |
| Grounding / epistemics | 7.22 | 7.28 | -0.06 | -0.14 [-0.23, -0.04] | 7.23 | 7.21 | 260 debates / 780 judge rows |
| Originality | 6.83 | 6.81 | +0.02 | +0.00 [-0.12, +0.12] | 6.68 | 6.97 | 260 debates / 780 judge rows |
| Rhetorical effectiveness | 7.38 | 7.62 | -0.23 | -0.33 [-0.45, -0.20] | 7.42 | 7.35 | 260 debates / 780 judge rows |

### Judge-panel consensus

- direct engagement: 381/780 judge rows (48.8%); 126/260 debates reached panel majority; mean rebuttal quality advantage -0.29.
- argument construction: 381/780 judge rows (48.8%); 125/260 debates reached panel majority; mean argument strength advantage -0.20.
- format compliance: 312/780 judge rows (40.0%); 103/260 debates reached panel majority; mean rhetorical effectiveness advantage -0.33.
- weighing: 159/780 judge rows (20.4%); 40/260 debates reached panel majority; mean argument strength advantage -0.20.
- burden handling: 159/780 judge rows (20.4%); 37/260 debates reached panel majority; mean argument strength advantage -0.20.
- answer quality: 123/780 judge rows (15.8%); 25/260 debates reached panel majority; mean rebuttal quality advantage -0.29.
- concession: 110/780 judge rows (14.1%); 31/260 debates reached panel majority; mean rebuttal quality advantage -0.29.
- clarity: 102/780 judge rows (13.1%); 21/260 debates reached panel majority; mean rhetorical effectiveness advantage -0.33.

### Judge salience

- Representative sample: 98 events across 30 event-bearing judge rows; direct engagement 20/30 (67%), argument construction 15/30 (50%), format compliance 13/30 (43%), weighing 8/30 (27%), answer quality 7/30 (23%), burden handling 7/30 (23%).
- Diagnostic sample: 37 events across 13 event-bearing judge rows; format compliance 7/13 (54%), burden handling 6/13 (46%), concession 5/13 (38%), direct engagement 5/13 (38%), argument construction 4/13 (31%), answer quality 3/13 (23%).
- Full current corpus: 2059 events across 709 event-bearing judge rows; argument construction 361/709 (51%), direct engagement 354/709 (50%), format compliance 282/709 (40%), weighing 149/709 (21%), burden handling 146/709 (21%), answer quality 112/709 (16%).

- [representative] PRO presented a strong challenge concerning clearance rates. Evidence: “A raised a strong clearance-rate challenge”
- [representative] PRO did not fully resolve CON's objections about durability and policy scope. Evidence: “never fully answered the durability and scope problem”
- [diagnostic] PRO supported its case with the invasion's documented links to ISIS, sectarian war, and Iranian expansion. Evidence: “grounding its arguments in the documented historical catastrophes of the invasion”

### Blind transcript observations

- Representative sample: 198 events across 22 event-bearing debates; direct engagement 22/22 (100%), question type 22/22 (100%), weighing 20/22 (91%), strategic concession 18/22 (82%), answer type 18/22 (82%), burden contest 13/22 (59%).
- Diagnostic sample: 128 events across 14 event-bearing debates; direct engagement 14/14 (100%), question type 14/14 (100%), answer type 11/14 (79%), weighing 10/14 (71%), burden setting 8/14 (57%), burden contest 8/14 (57%).
- Full current corpus: 2096 events across 224 event-bearing debates; question type 223/224 (100%), direct engagement 216/224 (96%), weighing 189/224 (84%), answer type 187/224 (83%), strategic concession 150/224 (67%), burden setting 127/224 (57%).

- [representative] CON reframes the dispute around comparative efficacy and the scale of the ban's costs. Evidence: “The real question is whether banning an entire category of animal disease prevention—rather than reforming it—actually delivers the resistance reduction PRO promises, and whether the human costs are as trivial as they suggest.”
- [representative] CON concedes a narrower category is dispensable while preserving its defense of prophylaxis. Evidence: “Growth promotion through low-dose antibiotics is genuinely dispensable and many countries have already restricted it.”
- [diagnostic] CON interprets the proposition as requiring an externally imposed mandate, an interpretation later contested by PRO. Evidence: “the actual proposition asks us to impose a broadcast mandate on private leagues”

### Side-swap patterns

- Representative sample: 44 events across 11 event-bearing groups; stable behavior 11/11 (100%), evidence asymmetry 7/11 (64%), contradiction candidate 7/11 (64%), advocacy flexibility 6/11 (55%), moral standard asymmetry 4/11 (36%), side specific behavior 3/11 (27%).
- Diagnostic sample: 25 events across 7 event-bearing groups; stable behavior 7/7 (100%), contradiction candidate 4/7 (57%), advocacy flexibility 4/7 (57%), moral standard asymmetry 3/7 (43%), evidence asymmetry 3/7 (43%), side specific behavior 2/7 (29%).
- Full current corpus: 424 events across 112 event-bearing groups; stable behavior 112/112 (100%), advocacy flexibility 74/112 (66%), contradiction candidate 71/112 (63%), evidence asymmetry 41/112 (37%), moral standard asymmetry 30/112 (27%), side specific behavior 21/112 (19%).

- [representative] Across sides, the model uses limited concessions and develops concrete implementation measures rather than defending an unqualified position.
- [representative] As CON the model prioritizes immediate food-security hardship, while as PRO it says resistant-infection burdens dwarf short-term livestock adjustments and treats transition costs as manageable.
- [diagnostic] As CON the model separated fragmentation from paywalls, while as PRO it treated fragmented recurring fees as a central affordability barrier, creating a tension for open-book review.

### Outcome associations

- Representative sample: 151 links across 22 debates; aligned 20/22 (91%), conflicted 13/22 (59%), unclear 11/22 (50%), judge_disagreement 9/22 (41%).
- Diagnostic sample: 93 links across 14 debates; aligned 12/14 (86%), judge_disagreement 7/14 (50%), unclear 5/14 (36%), conflicted 3/14 (21%).
- Full current corpus: 1042 links across 223 debates; aligned 212/223 (95%), conflicted 93/223 (42%), judge_disagreement 53/223 (24%), unclear 11/223 (5%).

## GLM-5.1

### Deterministic execution

- Coverage: 176 current-peer debates / 880 turns.
- Mean raw words per turn: 240.6; mean word-limit use: 83.8%.
- Deterministically clipped turns: 8.2%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.48 | 7.35 | +0.13 | +0.23 [+0.07, +0.40] | 7.54 | 7.42 | 176 debates / 528 judge rows |
| Rebuttal quality | 7.54 | 7.35 | +0.19 | +0.27 [+0.06, +0.48] | 7.57 | 7.52 | 176 debates / 528 judge rows |
| Grounding / epistemics | 7.35 | 7.28 | +0.07 | +0.16 [+0.03, +0.30] | 7.36 | 7.34 | 176 debates / 528 judge rows |
| Originality | 6.92 | 6.81 | +0.11 | +0.21 [+0.07, +0.34] | 6.87 | 6.97 | 176 debates / 528 judge rows |
| Rhetorical effectiveness | 7.70 | 7.62 | +0.09 | +0.19 [+0.05, +0.32] | 7.76 | 7.64 | 176 debates / 528 judge rows |

### Judge-panel consensus

- direct engagement: 290/528 judge rows (54.9%); 100/176 debates reached panel majority; mean rebuttal quality advantage +0.27.
- argument construction: 274/528 judge rows (51.9%); 94/176 debates reached panel majority; mean argument strength advantage +0.23.
- weighing: 146/528 judge rows (27.7%); 35/176 debates reached panel majority; mean argument strength advantage +0.23.
- answer quality: 98/528 judge rows (18.6%); 18/176 debates reached panel majority; mean rebuttal quality advantage +0.27.
- burden handling: 88/528 judge rows (16.7%); 14/176 debates reached panel majority; mean argument strength advantage +0.23.
- evidence use: 70/528 judge rows (13.3%); 17/176 debates reached panel majority; mean grounding and epistemic discipline advantage +0.16.
- clarity: 58/528 judge rows (11.0%); 10/176 debates reached panel majority; mean rhetorical effectiveness advantage +0.19.
- dropped argument: 51/528 judge rows (9.7%); 3/176 debates reached panel majority; mean rebuttal quality advantage +0.27.

### Judge salience

- Representative sample: 56 events across 22 event-bearing judge rows; argument construction 13/22 (59%), direct engagement 7/22 (32%), weighing 6/22 (27%), dropped argument 5/22 (23%), burden handling 3/22 (14%), format compliance 3/22 (14%).
- Diagnostic sample: 24 events across 10 event-bearing judge rows; direct engagement 8/10 (80%), argument construction 6/10 (60%), weighing 3/10 (30%), answer quality 2/10 (20%), rhetoric 1/10 (10%), dropped argument 1/10 (10%).
- Full current corpus: 1304 events across 466 event-bearing judge rows; direct engagement 274/466 (59%), argument construction 254/466 (55%), weighing 137/466 (29%), answer quality 94/466 (20%), burden handling 85/466 (18%), evidence use 67/466 (14%).

- [representative] CON directly challenged PRO’s core empirical premise. Evidence: “successfully challenging the empirical premise that large minimum wage hikes cause devastating job losses”
- [representative] CON grounded its employment argument in specific adjustment mechanisms. Evidence: “explaining concrete adjustment mechanisms (turnover, prices, productivity)”
- [diagnostic] PRO answered the security argument by noting that retailers already handle cash for other goods. Evidence: “effectively neutralized Side A's security argument by pointing out that retailers already process cash for non-essentials”

### Blind transcript observations

- Representative sample: 200 events across 21 event-bearing debates; direct engagement 21/21 (100%), question type 21/21 (100%), answer type 21/21 (100%), weighing 18/21 (86%), strategic concession 15/21 (71%), burden setting 12/21 (57%).
- Diagnostic sample: 64 events across 7 event-bearing debates; direct engagement 7/7 (100%), question type 7/7 (100%), answer type 7/7 (100%), weighing 6/7 (86%), burden setting 5/7 (71%), burden contest 4/7 (57%).
- Full current corpus: 1378 events across 148 event-bearing debates; direct engagement 147/148 (99%), question type 147/148 (99%), answer type 140/148 (95%), weighing 131/148 (89%), strategic concession 99/148 (67%), burden setting 79/148 (53%).

- [representative] PRO explicitly structures its opening around productivity, hidden costs, and legal standardization. Evidence: “The core case for legal redefinition rests on three pillars.”
- [representative] PRO supplies a concrete numerical result to support its productivity claim. Evidence: “Microsoft Japan's four-day trial saw productivity rise nearly 40%.”
- [diagnostic] CON supplies precise details for a concrete example, though the example alone does not establish prevalence. Evidence: “Kate Steinle's killer had seven prior convictions and five deportations”

### Side-swap patterns

- Representative sample: 39 events across 10 event-bearing groups; stable behavior 10/10 (100%), advocacy flexibility 7/10 (70%), evidence asymmetry 6/10 (60%), contradiction candidate 6/10 (60%), side specific behavior 5/10 (50%), moral standard asymmetry 2/10 (20%).
- Diagnostic sample: 16 events across 4 event-bearing groups; stable behavior 4/4 (100%), contradiction candidate 3/4 (75%), evidence asymmetry 2/4 (50%), side specific behavior 2/4 (50%), moral standard asymmetry 1/4 (25%), advocacy flexibility 1/4 (25%).
- Full current corpus: 271 events across 74 event-bearing groups; stable behavior 74/74 (100%), contradiction candidate 51/74 (69%), advocacy flexibility 42/74 (57%), evidence asymmetry 28/74 (38%), moral standard asymmetry 23/74 (31%), side specific behavior 14/74 (19%).

- [representative] On both sides, glm-5.1 directly engages the opposing mechanism with sector-specific counterarguments.
- [representative] On both sides, glm-5.1 uses concrete numerical comparisons to frame the economic mechanism.
- [diagnostic] On both sides, the model treats the Steinle case as illustrating possible harm rather than independently establishing the net policy calculus.

### Outcome associations

- Representative sample: 141 links across 21 debates; aligned 20/21 (95%), conflicted 10/21 (48%), judge_disagreement 7/21 (33%), unclear 6/21 (29%).
- Diagnostic sample: 52 links across 7 debates; aligned 6/7 (86%), unclear 4/7 (57%), judge_disagreement 4/7 (57%), conflicted 3/7 (43%).
- Full current corpus: 740 links across 146 debates; aligned 139/146 (95%), conflicted 50/146 (34%), judge_disagreement 49/146 (34%), unclear 7/146 (5%).

## GLM-5

### Deterministic execution

- Coverage: 140 current-peer debates / 700 turns.
- Mean raw words per turn: 224.2; mean word-limit use: 77.8%.
- Deterministically clipped turns: 2.9%; required Q/A label compliance: 100.0%.
- Missing internal claim-ID rate among cited IDs: 0.0%.

### Judge diagnostic subscores

| Axis | Mean | Current field | Δ field | Vs opponent (95% CI) | PRO mean | CON mean | Coverage |
|---|---:|---:|---:|---:|---:|---:|---:|
| Argument strength | 7.22 | 7.35 | -0.13 | -0.12 [-0.32, +0.09] | 7.32 | 7.12 | 140 debates / 434 judge rows |
| Rebuttal quality | 7.29 | 7.35 | -0.06 | -0.07 [-0.33, +0.19] | 7.28 | 7.30 | 140 debates / 434 judge rows |
| Grounding / epistemics | 7.25 | 7.28 | -0.03 | +0.04 [-0.11, +0.18] | 7.24 | 7.26 | 140 debates / 434 judge rows |
| Originality | 6.57 | 6.81 | -0.24 | -0.22 [-0.38, -0.05] | 6.49 | 6.65 | 140 debates / 434 judge rows |
| Rhetorical effectiveness | 7.52 | 7.62 | -0.10 | -0.04 [-0.20, +0.12] | 7.59 | 7.44 | 140 debates / 434 judge rows |

### Judge-panel consensus

- direct engagement: 218/434 judge rows (50.2%); 72/140 debates reached panel majority; mean rebuttal quality advantage -0.07.
- argument construction: 206/434 judge rows (47.5%); 65/140 debates reached panel majority; mean argument strength advantage -0.12.
- weighing: 96/434 judge rows (22.1%); 21/140 debates reached panel majority; mean argument strength advantage -0.12.
- answer quality: 91/434 judge rows (21.0%); 17/140 debates reached panel majority; mean rebuttal quality advantage -0.07.
- burden handling: 87/434 judge rows (20.0%); 17/140 debates reached panel majority; mean argument strength advantage -0.12.
- evidence use: 52/434 judge rows (12.0%); 10/140 debates reached panel majority; mean grounding and epistemic discipline advantage +0.04.
- concession: 46/434 judge rows (10.6%); 12/140 debates reached panel majority; mean rebuttal quality advantage -0.07.
- dropped argument: 45/434 judge rows (10.4%); 3/140 debates reached panel majority; mean rebuttal quality advantage -0.07.

### Judge salience

- Representative sample: 26 events across 10 event-bearing judge rows; argument construction 7/10 (70%), direct engagement 6/10 (60%), answer quality 5/10 (50%), evidence use 2/10 (20%), weighing 1/10 (10%), factual error 1/10 (10%).
- Diagnostic sample: 5 events across 2 event-bearing judge rows; direct engagement 2/2 (100%), argument construction 1/2 (50%).
- Full current corpus: 1059 events across 397 event-bearing judge rows; direct engagement 210/397 (53%), argument construction 198/397 (50%), weighing 94/397 (24%), burden handling 87/397 (22%), answer quality 86/397 (22%), evidence use 49/397 (12%).

- [representative] PRO did not adequately answer CON's motion-scope and vulnerable-teen objections. Evidence: “PRO's answers never cleanly neutralized”
- [representative] CON established a physics-based distinction between space and ocean exploration. Evidence: “introducing a principled asymmetry—light-lag in space makes real-time teleoperation impossible, whereas undersea ROVs operate with effectively zero latency”
- [diagnostic] PRO established socioeconomic gatekeeping as an intrinsic harm of unpaid internships. Evidence: “unpaid internships intrinsically gatekeep low-income students”

### Blind transcript observations

- Representative sample: 180 events across 20 event-bearing debates; direct engagement 20/20 (100%), question type 20/20 (100%), answer type 19/20 (95%), weighing 15/20 (75%), strategic concession 12/20 (60%), burden contest 11/20 (55%).
- Diagnostic sample: 88 events across 10 event-bearing debates; question type 10/10 (100%), direct engagement 9/10 (90%), answer type 9/10 (90%), weighing 7/10 (70%), burden setting 6/10 (60%), burden contest 5/10 (50%).
- Full current corpus: 1002 events across 110 event-bearing debates; question type 108/110 (98%), direct engagement 107/110 (97%), answer type 102/110 (93%), weighing 87/110 (79%), strategic concession 67/110 (61%), burden setting 60/110 (55%).

- [representative] PRO frames the central comparison around long-term elimination versus recurring management costs. Evidence: “It's between paying once for a permanent solution versus paying indefinitely for an escalating problem.”
- [representative] PRO answers CON’s cost comparison by identifying recurring costs within the alternative package. Evidence: “Storage tunnels, green infrastructure, and real-time controls are not one-time purchases—they require perpetual maintenance, monitoring, and eventual replacement.”
- [diagnostic] CON relies on familiar category-based discounts without directly addressing the motion's disclosure option. Evidence: “Happy hour pricing, student discounts, early-bird specials—all charge different customers different amounts for "the same" core product.”

### Side-swap patterns

- Representative sample: 34 events across 10 event-bearing groups; stable behavior 10/10 (100%), contradiction candidate 8/10 (80%), advocacy flexibility 6/10 (60%), side specific behavior 3/10 (30%), evidence asymmetry 3/10 (30%), moral standard asymmetry 2/10 (20%).
- Diagnostic sample: 17 events across 5 event-bearing groups; stable behavior 5/5 (100%), contradiction candidate 5/5 (100%), moral standard asymmetry 3/5 (60%), side specific behavior 2/5 (40%), advocacy flexibility 1/5 (20%), tradeoff hiding 1/5 (20%).
- Full current corpus: 203 events across 55 event-bearing groups; stable behavior 55/55 (100%), contradiction candidate 36/55 (65%), advocacy flexibility 30/55 (55%), moral standard asymmetry 20/55 (36%), side specific behavior 14/55 (25%), evidence asymmetry 13/55 (24%).

- [representative] GLM-5 describes separation as a permanent solution when PRO but emphasizes continuing sanitary overflows and stormwater pollution when CON, creating a scope-sensitive tension for open-book review.
- [representative] GLM-5 categorically resists indefinite residual sewage exposure as PRO but adopts diminishing returns and competing public needs as the limiting standard when CON.
- [diagnostic] On both sides, the model frames the issue through remedy calibration, emphasizing costs or limitations even while defending its assigned remedy position.

### Outcome associations

- Representative sample: 151 links across 20 debates; aligned 19/20 (95%), unclear 10/20 (50%), conflicted 9/20 (45%), judge_disagreement 7/20 (35%).
- Diagnostic sample: 80 links across 10 debates; aligned 9/10 (90%), unclear 7/10 (70%), judge_disagreement 7/10 (70%), conflicted 5/10 (50%).
- Full current corpus: 544 links across 110 debates; aligned 106/110 (96%), conflicted 40/110 (36%), judge_disagreement 36/110 (33%), unclear 5/110 (5%).
