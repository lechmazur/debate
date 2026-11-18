# Debate prop_0169__mistral-medium-3.5-high__gpt-6.2-astra-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: mistral-medium-3.5-high
- model_con: gpt-6.2-astra-high
- side_swap: True

## Turn 1: PRO Opening

- model: mistral-medium-3.5-high
- raw_words: 273
- clipped_words: 273
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Computational research without reproducible artifacts is not science—it is assertion. If a paper claims a new algorithm outperforms state-of-the-art but withholds code, data, or environment specifications, readers must accept results on faith, violating the bedrock principle of verifiability. Journals exist to disseminate reliable knowledge; publishing unverifiable computational work undermines their very purpose and corrodes trust in the scientific enterprise.
[P1.2] The reproducibility crisis in computational fields is severe. Countless published findings cannot be replicated because essential materials are absent or incomplete. Even with good intentions, undocumented hyperparameters, seed values, or library versions can render results irreproducible. Mandating code, data, and precise environment details forces thorough documentation and enables genuine independent verification, benefiting both science and the authors through increased credibility and citation.
[P1.3] Opponents will claim this imposes an unreasonable burden. But the cost is negligible compared to the harm of propagating flawed or irreproducible work that wastes collective resources and misleads entire fields. Modern version control and repository platforms make sharing trivial, and the time investment is minimal relative to the research effort. As for proprietary concerns: if findings cannot be shared openly, they do not belong in academic journals.
[P1.4] Journals can address exceptional cases with temporary embargoes or controlled access, but reproducibility must remain the default.
[P1.5] The trend is unequivocal: leading computational venues now require code submission for publication. Journals must adopt this as a baseline standard. Without it, computational research risks becoming a black box of unverifiable claims, eroding public trust in science and squandering resources on work that cannot be built upon or validated. This is not an excessive demand—it is the minimum requirement for scientific credibility in the computational age.

## Turn 2: CON Opening

- model: gpt-6.2-astra-high
- raw_words: 293
- clipped_words: 293
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A journal should refuse a claim its evidence cannot support. That is different from refusing a claim nobody can rerun on the original inputs. A rerun asks whether the same computation produces the reported number. The scientific question may be whether the number measures what the authors say it does.
[C1.2] Those tests can come apart in either direction.
[C1.3] Suppose a hospital finds that a sepsis predictor looks accurate in hindsight because its evaluation uses lab results unavailable when the prediction would have been made. Rebuild the evaluation using only results available at the decision time, and performance drops. The hospital can publish its code, environment, timestamp definitions, and aggregate comparisons, but suppose patient consent precludes giving outside researchers access to individual records, even in a secure room. A second hospital can independently implement the test on its own records.
[C1.4] If it sees the same drop, readers have evidence beyond either team's word, though neither team can provide the data needed to rerun its original analysis. What does science gain by refusing that warning? An embargo cannot change the terms of consent.
[C1.5] Conversely, a perfectly packaged version of the original, flawed evaluation would reproduce its impressive score every time. Sharing the package helps someone spot the mistake; rerunning it does not settle the claim. That is why editors should demand artifacts where feasible, require authors to identify exactly what cannot be checked and why, and judge whether independent tests support the conclusion. An algorithm's alleged speed advantage resting solely on an undisclosed benchmark may well deserve rejection under that standard.
[C1.6] The hospital warning need not.
[C1.7] The choice is not repositories or faith. It is whether editors may recognize evidence other than a rerun, even when that evidence tests the conclusion more directly. They should.

## Turn 3: PRO Rebuttal 1

- model: mistral-medium-3.5-high
- raw_words: 281
- clipped_words: 281
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Your hospital example proves our point. If a sepsis evaluation uses future data, sharing code exposes this error; without it, the flaw persists undetected, risking real harm as others adopt the approach. Another hospital testing on its own data does not verify the original claim—it tests a different system on different data, which may not reveal the original error. In computational research, code and data are the experimental apparatus; execution is the experiment.
[P2.2] Without rerun capability, results are unverifiable assertions. The reproducibility crisis shows this is not hypothetical—it undermines scientific progress.
[P2.3] You argue editors should accept other evidence, but for computational claims, the computation is the primary evidence. When a paper reports "our model achieves 95% accuracy," that percentage is the direct output of code execution. If you cannot reproduce it, the claim lacks empirical foundation. Your "where feasible" clause is the core problem: it allows unverifiable claims to be published as science.
[P2.4] Your alternative—editors judging other evidence—creates an opaque system where methodological flaws can hide in descriptions rather than be exposed in code. This is backwards; code is where flaws should be visible for inspection and correction.
[P2.5] Furthermore, this approach shifts an impossible burden onto already overstretched editorial processes. Reproducibility artifacts provide a clear, verifiable standard that benefits the entire scientific community at large. If legitimate constraints like patient privacy prevent open data sharing, journals can implement secure access mechanisms, but the principle of verifiability must remain non-negotiable. Leading computational venues now require code submission because they understand: without reproducibility, computational research is not science—it is speculation.
[P2.6] Journals that refuse to adopt this standard are not upholding scientific rigor; they are enabling the continued erosion of trust in computational research.

## Turn 4: CON Rebuttal 1

- model: gpt-6.2-astra-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] The hospital shares its code. That is why “sharing code exposes this error” cuts against refusal: a reader can inspect which timestamp the evaluation uses. What the hospital cannot supply is the patient file needed to recover its particular score. A secure room can limit who sees a record; it cannot authorize a use patients never consented to.
[C2.2] Under the proposed rule, the very paper that exposes the error must be refused.
[C2.3] Take the “95% accuracy” claim seriously enough to ask: accuracy at what task? An independent analyst might recover 95% exactly and still have no evidence that the model could predict sepsis before the lab results arrived. Conversely, a second hospital need not reproduce 95% to test whether using future information inflates measured accuracy. Different patients are a weakness if the question is what number appeared at the first hospital.
[C2.4] They are a strength if the question is whether the problem extends beyond it. Publish the local estimate as a reported observation, not an independently confirmed benchmark; draw the methodological conclusion the evidence supports.
[C2.5] Nor does a clear submission rule relieve editors of judgment. Checking that files exist is easy; checking that they suffice for reproduction takes work. Even a successful rerun leaves reviewers to decide whether the timestamps mean what the authors say. Requiring authors to state precisely which result outsiders cannot check makes that judgment visible to readers rather than opaque.
[C2.6] The choice is not between a hospital paper with records and one without. Consent takes the first option off the table. It is between publishing a warning with inspectable code, disclosed limits and an independent test, and refusing it. Refusal does not correct the flawed evaluation; it withholds a way to recognize it.

## Turn 5: PRO Pressure Questions

- model: mistral-medium-3.5-high
- raw_words: 51
- clipped_words: 51
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your hospital example shares code but withholds data. Without the data, how can the original accuracy claim be independently reproduced?
[P3.2] Q2: You argue that an independent test on different data validates the warning. But that test does not reproduce the original result. Why should journals accept unverified claims as evidence?

## Turn 6: CON Pressure Questions

- model: gpt-6.2-astra-high
- raw_words: 66
- clipped_words: 66
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If the claim is that including later lab results can inflate measured accuracy, what part of that claim goes untested when a second hospital independently demonstrates the inflation on its own records?
[C3.2] Q2: Under your rule, why should a paper with files nobody has yet rerun clear the publication threshold that this independently tested warning fails, solely because consent bars access to the original records?

## Turn 7: PRO Rebuttal 2

- model: mistral-medium-3.5-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The untested part is the original paper’s exact numerical claim. A second hospital’s independent demonstration proves the possibility of inflation but does not verify that the first hospital’s specific reported accuracy was inflated by future data. Without the original records, the published figure remains an unverified assertion—code alone cannot validate the outcome without the data it operated on.
[P4.2] A2: It shouldn’t clear the threshold. The rule requires capability for independent reproduction; inaccessible records mean this capability is absent. A paper with complete, rerunnable files meets the standard because its claims can be verified, even if not yet. The hospital paper fails because its central numerical claims cannot be checked.
[P4.3] This exposes the flaw in the alternative: it conflates general evidence with verification of published results. In computational research, the specific execution is the experiment; without reproducing it, we cannot confirm the reported outcome. The hospital warning is valuable, but its specific findings are unverifiable, and journals must not publish unverifiable claims as science. Accepting such papers would normalize a system where results are taken on faith, which has already damaged computational fields.
[P4.4] Your hospital example does not undermine our rule—it proves it necessary. Without verifiable artifacts, computational research risks becoming a black box of unverifiable assertions. The principle is non-negotiable: for results to be published as science, they must be independently reproducible. This is not an excessive burden; it is the minimum standard for scientific credibility in the computational age.
[P4.5] Modern version control and repository platforms make sharing trivial, and the time investment is minimal relative to the research effort. As for legitimate constraints like patient privacy, journals can implement secure access mechanisms, but the principle of verifiability must remain non-negotiable. Leading computational venues now require code submission because they understand this: without reproducibility, computational research is not science—it is speculation.

## Turn 8: CON Rebuttal 2

- model: gpt-6.2-astra-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: It cannot. Without access to the original patient records, an outsider cannot rerun the analysis to recover the first hospital’s accuracy figure. The paper should say that beside the figure, and no editor should present it as an independently confirmed benchmark.
[C4.2] A2: Journals should not accept the second test as verification of the first score. They should accept it as evidence for the warning. Hold the patients and prediction task fixed within the second hospital; change whether later lab results are admitted. If admitting them raises measured accuracy, that comparison supports the warning without requiring readers to believe a word about the first hospital’s score.
[C4.3] That last distinction settles what is “central” here. You concede that the second demonstration “proves the possibility of inflation.” That possibility is precisely what a clinician deciding whether to trust a retrospective evaluation needs to know. Set the first estimate aside entirely: the reason to check when the inputs became available survives. If the paper instead claimed that the first hospital overstated accuracy by a particular amount, setting its estimate aside would destroy the conclusion.
[C4.4] An editor has grounds to insist on access for the latter claim without suppressing the former.
[C4.5] Your rule values the opportunity for a future check. So does mine. But consent rules out a rerun here, whether the journal publishes or refuses. Refusal therefore buys no opportunity to check the disputed figure; it costs readers an independently tested reason to question what such figures measure.
[C4.6] Requiring the authors to disclose that limit, share the code and narrow the conclusion protects readers against the inference you rightly contest. Rejecting the entire paper also denies them the inference you expressly concede. That is not a higher standard of evidence; it is a failure to distinguish what the evidence supports.

## Turn 9: PRO Closing

- model: mistral-medium-3.5-high
- raw_words: 193
- clipped_words: 193
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] For computational research, the experiment is the execution of code on data; without the means to rerun it, the result is not science. Computational papers assert specific numerical outcomes that must be verifiable. Without code, data, and environment, these outcomes are unverifiable assertions. The hospital example proves it: the reported accuracy cannot be reproduced without the original records.
[P5.2] Independent tests on other data do not validate that specific number—they test a different instance. Science cannot be built on unverified numbers. Therefore, journals must refuse publication unless the means of verification are provided. This is not about the value of a warning; it is about the integrity of the published claim.
[P5.3] The reproducibility crisis in computational fields demonstrates the real-world harm of leniency. Privacy constraints, while legitimate, do not justify publishing unverifiable claims; secure access mechanisms can often resolve them without sacrificing verifiability. The burden of sharing is minimal compared to the damage of propagating unverified results. Without the requirement, journals publish faith, not evidence.
[P5.4] In the computational age, reproducibility is not optional—it is the foundation of trust in scientific results. Journals that fail to enforce it undermine the very purpose of scientific communication.

## Turn 10: CON Closing

- model: gpt-6.2-astra-high
- raw_words: 201
- clipped_words: 201
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] Set the first hospital’s accuracy figure aside. Suppose its analyst made a mistake and the figure is wrong. Does the warning fall with it? At the second hospital, the patients and prediction task stayed the same; what changed was whether the evaluation admitted lab results unavailable when a prediction had to be made.
[C5.2] The rise in measured accuracy there gives a clinician reason to check the timing of the inputs before trusting a retrospective score. That reason owes nothing to the disputed number.
[C5.3] The objection that “they test a different instance” is therefore exactly right. A different instance cannot establish how much accuracy was inflated at the first hospital. It can establish that inflation is possible. The integrity of the published claim depends on making that distinction, not on pretending the second test settles both questions.
[C5.4] When consent bars access to the original records, rejection gives nobody a better look at them. It keeps an independently tested warning out of the journal. Require the authors to share the code, identify what cannot be rerun, and withdraw any conclusion that depends on the disputed number. A journal earns trust by refusing the unsupported inference, not the paper that supports a different one.
