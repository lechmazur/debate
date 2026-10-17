# Debate prop_0169__deepseek-v4-pro-0813-high__muse-wonder-1.0-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: deepseek-v4-pro-0813-high
- model_con: muse-wonder-1.0-high
- side_swap: False

## Turn 1: PRO Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Computational research is a report on an experiment performed by software. The code is the instrument, the data are the samples, and the environment is the laboratory conditions. A journal that publishes only the prose results is publishing an assertion divorced from the method. Refusing publication unless authors provide all three is not an administrative hurdle; it is the minimum condition for a falsifiable scientific claim.
[P1.2] Without code, reviewers and readers cannot distinguish a real effect from a bug, a favorable train/test leak, or an artifact of undocumented preprocessing. Without data, no one can test whether the result is stable across the population the paper claims to describe. Without environment details such as library versions, hardware, random seeds, and dependency configurations, even the supplied code may not reproduce the reported numbers. Each missing piece breaks the chain of independent reproduction; providing two out of three is like publishing a chemistry paper with a list of reagents but no procedure.
[P1.3] The stakes are not abstract. A model that appears accurate in a paper but cannot be reconstructed cannot be validated before it shapes clinical decisions, hiring algorithms, fraud detection, or climate estimates. The literature becomes a collection of press releases rather than a shared evidence base.
[P1.4] Journals are the natural enforcement point because publication is the reward. Voluntary sharing has been weak, and authors respond to gatekeeping standards. Making publication conditional on reproducibility also improves the work itself: packaging code, data, and environment details catches errors before submission.
[P1.5] Some will object that proprietary data, privacy, or messy code make compliance difficult. But that is a reason to question whether the computational claim is ready for the literature. If the underlying evidence cannot be inspected, the paper should not be published as computational science. A clear refusal rule closes the loophole that currently lets unverifiable results carry the same authority as reproducible ones.

## Turn 2: CON Opening

- model: muse-wonder-1.0-high
- raw_words: 307
- clipped_words: 307
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Reproducibility matters, but a universal refusal rule mistakes one way of checking science for science itself, and it would block much of the research we most need to read.
[C1.2] The proposition demands code, data, and environment details sufficient for independent reproduction for every computational paper. For large classes of legitimate work, that gate cannot ethically or practically be opened. Hospital researchers cannot publish identifiable patient records; de-identification can fail, consent and law restrict reuse, and rare diseases make individuals recognizable. Similar bars apply to student records, location traces, proprietary industrial processes, cybersecurity vulnerabilities, and data governed by Indigenous or community agreements.
[C1.3] In those fields, refusal does not protect science. It silences it.
[C1.4] Even where sharing is lawful, “sufficient for independent reproduction” is often illusory. A climate simulation or genomics pipeline may depend on terabytes of data, a supercomputer queue, licensed software, and parallel hardware whose results vary between runs. Packaging research code into a portable system can take months of unfunded labor. Well-funded labs can hire engineers; a small university lab or researcher in a low-income country often cannot.
[C1.5] The rule would select for wealth and institutional support, not correctness.
[C1.6] Nor would refusal reliably buy truth. Authors can comply performatively with an unreadable code dump, a curated data subset, and a version list that still does not run elsewhere. Reviewers rarely have time to rebuild every pipeline. Meanwhile, a paper without public artifacts is not automatically unverifiable: detailed methods, sensitivity analyses, held-out tests, and independent conceptual replication can expose errors without identical reruns.
[C1.7] Journals should demand maximal justified transparency, restricted-access review where needed, and clear statements of what cannot be shared and why. What they should not do is refuse otherwise sound, important work because one rigid package is impossible. That converts a virtue into a barrier and leaves readers with less knowledge, not more trustworthy knowledge.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- cited_claim_ids: [C1.6], [C1.2], [C1.4]
- missing_claim_id_refs: (none)

[P2.1] Opponent's central error is treating reproducibility as one nice check rather than the precondition for a computational claim. A methods section cannot reveal a train/test leak, a color-channel misordering, a reseeded split, or a library version artifact; those errors live in code and environment, not prose. That is why [C1.6]'s alternatives—sensitivity analyses, held-out tests, conceptual replication—are not substitutes. They can suggest a result is plausible, but they cannot show the reported number came from the described pipeline. “We used hospital records with standard preprocessing” describes many different datasets; without artifacts, reviewers are grading a press release.
[P2.2] Privacy and proprietary limits [C1.2] do not justify lowering the floor; they tell us the paper should not be published as a computational result. If identifiable patient data cannot be shared, there are better options than silent publication: restricted-access review, federated evaluation, synthetic data, or reporting the work as a case study without computational claims. If none of those is possible, then readers and downstream users cannot inspect the evidence, and the journal should say no. Silence is precisely what happens when decision-makers act on an unverifiable model.
[P2.3] The cost objection [C1.4] mistakes packaging for an optional service. Reproducible materials are the completion of the experiment, not a favor to reviewers. Where huge hardware or licensed software prevents exact rerun, the authors can provide the workflow, configuration, checkpoints, and a tractable verification subset; the requirement is sufficient reproduction, not free universal replay. And the current system already favors wealthy labs: they are the ones whose unreviewable pipelines become authoritative.
[P2.4] Finally, performative code dumps [C1.6] are an argument for enforcing the requirement, not for abandoning it. A code dump can be inspected and maybe run; prose cannot. The gate makes failure detectable, which is exactly why it should exist.

## Turn 4: CON Rebuttal 1

- model: muse-wonder-1.0-high
- raw_words: 317
- clipped_words: 317
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.2], [P2.3], [C1.7]
- missing_claim_id_refs: (none)

[C2.1] That reply quietly abandons the motion it is supposed to defend. The proposition requires code, data, and environment details sufficient for independent reproduction. Yet when faced with patient data, we are offered restricted-access review, federated evaluation, and synthetic data [P2.2]; when faced with supercomputers, a workflow, checkpoints, and a “tractable verification subset” [P2.3]. None of that lets an independent reader reproduce the reported result.
[C2.2] Synthetic data are not the data. A subset is not the terabyte run. Federated evaluation lets an owner run code behind a wall, not inspect the evidence. If these compromises count, the rule is no longer universal refusal — it is the justified, tiered transparency argued for in [C1.7].
[C2.3] If they do not count, then the hospital, climate, and genomics papers are still refused. PRO cannot have both the slogan and the exceptions.
[C2.4] The supposed escape of relabeling work “a case study without computational claims” proves the cost. A model predicting deterioration from private records is a computational claim. Publishing it with clear limits allows another hospital to test the same method on its own private records. That is independent replication in the only ethical form available.
[C2.5] Refuse the first paper, and that second test never happens. PRO calls silence preferable to unverifiable publication, but refusal manufactures a deeper silence: no method to challenge, no failure to discover, no literature to correct.
[C2.6] Nor does an artifact gate deliver the inspection promised. A train/test leak can sit in a data file, an upstream preprocessing script, or code reviewers have no time to execute across a bespoke environment. Making upload mandatory mainly makes upload auditable as a checkbox; it does not fund reviewers to rerun pipelines. Worse, a stamped “reproducible” paper whose subset was curated to pass earns more unearned trust than a paper honestly stating its constraints.
[C2.7] So the choice is rigid refusal that excludes vital research, or flexible substitutes that concede our position.

## Turn 5: PRO Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: In [C2.4], you call another hospital testing the same method on different private records “independent replication.” Does independent reproduction mean verifying the paper’s reported result, or only checking that the method might work elsewhere? If the first is impossible, what is being reproduced?
[P3.2] Q2: If uploaded artifacts are a mere checkbox because reviewers often won’t run them [C2.6], why keep methods sections, which offer even less to inspect? What checkable evidence should journals require before publishing a computational result?

## Turn 6: CON Pressure Questions

- model: muse-wonder-1.0-high
- raw_words: 73
- clipped_words: 73
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: When you allow synthetic data, a verification subset, or federated evaluation instead of the actual code, data, and environment, are you still enforcing refusal unless independent reproduction is possible, or conceding tiered transparency is enough?
[C3.2] Q2: If none of those substitutes lets an independent reader reproduce the reported hospital or supercomputer result, will you refuse those papers outright, and if so, how does losing their methods for others to test improve science?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C1.7], [C2.4]
- missing_claim_id_refs: (none)

[P4.1] A1: I am not inserting substitutes into the requirement. Synthetic data, verification subsets, and federated evaluation cannot reproduce the reported result for the original private or supercomputer paper; therefore they do not satisfy the motion. They are legitimate only when authors redesign the article into a methods contribution, a synthetic benchmark, or a narrower claim that can be independently reproduced. If the paper still asserts “our model achieved its reported accuracy on these private records,” refusal remains unconditional.
[P4.2] That is not the open tiered transparency of [C1.7]; it is a boundary around what counts as a computational research claim.
[P4.3] A2: Yes—if the reported hospital or supercomputer result cannot be reproduced from provided code, data, and environment, I would refuse it. The science improves because the method can still travel. Authors can publish code, architecture, training protocol, eligibility criteria, and a synthetic benchmark; another hospital can adapt that. What is removed is the false assurance that private validation has already occurred.
[P4.4] [C2.4] describes independent replication of the method on new data, not reproduction of the paper’s result. Without the original data, the original result remains an assertion. If the method cannot meaningfully reach other settings without the code and environment, then it was not being transferred by the unverifiable paper in the first place.
[P4.5] The opponent’s central mistake is treating a journal’s imprimatur as harmless unless a substitute is available. It is not. A model that predicts deterioration but cannot be inspected can enter clinical decisions with the same authority as a reproducible one. Refusal does not silence the method; it forces authors to convert the assertion into shareable evidence or a more modest claim.
[P4.6] The tiered transparency in [C1.7] lets the strongest unverifiable claims borrow the credibility of science. That is exactly the harm the motion blocks.

## Turn 8: CON Rebuttal 2

- model: muse-wonder-1.0-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Independent reproduction and independent replication are different, and conflating them is the trap. Reproduction reruns the same data to recover the same number; replication asks whether the specified method holds on new data. Where the first is ethically impossible, what is tested is not a private patient row but the paper's operative claim: that this pipeline, preprocessing, and training protocol learn a real predictive signal. Another hospital applying them to its own records can confirm or undermine that claim.
[C4.2] If it fails there, the original result loses credibility without anyone exposing the original records.
[C4.3] A2: Methods sections survive because imperfect inspectability is not worthlessness — the same logic I applied to artifacts. I never said uploads are useless; I said refusal does not guarantee reviewers will rerun them, so it cannot promise the verification used to justify exclusion. Journals should require the strongest checkable package justified by the case: complete methods, code and environment where lawful, preprocessing scripts, seeds, data dictionaries, sensitivity and held-out analyses, controlled-access or enclave review where possible, and an explicit statement of what cannot be shared and why.
[C4.4] Readers then get evidence they can scrutinize and replicate, even when an identical rerun is impossible.
[C4.5] Those answers defeat the refusal rule, and PRO's clarification proves it. PRO now admits synthetic data and subsets do not satisfy the motion and says the hospital or supercomputer paper must be refused unless redesigned into a narrower, reproducible claim [P4.1][P4.3]. But a synthetic benchmark cannot tell clinicians whether a model worked on real deterioration cases, just as a verification subset cannot tell climate scientists what the full run showed. PRO says the method can still travel through code and protocol — exactly the valuable publication CON defends.
[C4.6] Stripping away the real-world result only makes that traveling method harder to judge, prioritize, and test. Transparency about limits informs science; enforced absence does not.

## Turn 9: PRO Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 207
- clipped_words: 207
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate now turns on a single distinction: reproduction of the reported result versus later replication of a method on new data. CON concedes that synthetic data, subsets, and federated evaluation cannot reproduce the original hospital or supercomputer result. Its defense is that another hospital might later test the same method. That is precisely the method-traveling publication PRO allows through shared code and protocol.
[P5.2] What PRO refuses is different: the journal’s certification of an unreproducible empirical result. When a paper claims “our model achieved X on these private records” but cannot supply code, data, and environment sufficient to inspect that claim, reviewers cannot detect the bug, leak, or version artifact producing X. The number then travels with scientific authority it has not earned. Later replication may eventually undermine it, but until then the unverifiable result still influences clinical or policy decisions.
[P5.3] PRO does not silence the method. It forces a choice: publish the transferable method with reproducible artifacts, or narrow the claim until it is independently checkable. CON’s tiered transparency keeps letting the strongest unverifiable result borrow the credibility of publication. The one decisive reason PRO wins is that publication is a credential.
[P5.4] Journals should not issue it when the reported computational result cannot be independently reproduced.

## Turn 10: CON Closing

- model: muse-wonder-1.0-high
- raw_words: 181
- clipped_words: 181
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C5.1] PRO wins the credential only by losing the science.
[C5.2] Once PRO admits the hospital paper must be refused unless it is rewritten around synthetic data or a smaller reproducible claim [P4.1][P4.3], the choice is no longer between verified and unverified publication. It is between a real result, published with its limits stated, code and protocol exposed where lawful, and ready for another hospital to replicate — and no real result at all.
[C5.3] That absence does not make readers safer. It leaves clinicians and scientists with a traveling method but no evidence about whether it worked where it mattered, no finding to prioritize, challenge, or refute. A synthetic benchmark cannot answer that question. A curated subset cannot answer it for the full climate run.
[C5.4] Publication is indeed a credential, but a credential can carry conditions and warnings; it does not have to certify identical reruns. CON's approach preserves the finding and marks exactly what can and cannot be checked, letting replication do the work refusal prevents.
[C5.5] A journal should warn readers about limits, not erase the work they need to overcome them.
