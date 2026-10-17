# Debate prop_0169__muse-wonder-1.0-high__deepseek-v4-pro-0813-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: muse-wonder-1.0-high
- model_con: deepseek-v4-pro-0813-high
- side_swap: True

## Turn 1: PRO Opening

- model: muse-wonder-1.0-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A computational result without its code, data, and environment is not a finding. It is an anecdote with a graph.
[P1.2] In other sciences, publication requires methods detailed enough for a competent rival to redo the work. In computational research, code is the method, data is the evidence, and environment determines whether the same code yields the same numbers. A preprocessing choice, random seed, library update, or silent train-test leakage can flip a conclusion, and none is visible in polished prose. Reviewers without the artifacts are not reviewing the experiment; they are reviewing the authors’ story about it.
[P1.3] That gap wastes enormous effort. Other labs spend months reimplementing ambiguous descriptions, unable to tell whether a mismatch is their error, the original bug, or a real discovery. Benchmarks, clinical models, and policy simulations are built on numbers no one can audit. Errors an afternoon with the code would expose survive for years, cited as fact because a journal lent them credibility.
[P1.4] Voluntary encouragement predictably fails. “Available on request” often means unavailable, links decay, and undocumented code will not run. Cleaning work costs authors time, while opacity carries no penalty and can hide shortcuts. Journals are the gatekeeper able to reverse that incentive. Make reproducibility a condition of publication, and it becomes part of the research, not an optional favor afterward.
[P1.5] The bar is workable: a versioned repository, data or a controlled-access route to it, dependency versions or a container, seeds, and instructions sufficient to rerun the analysis. Sensitive data can be de-identified, access-controlled, or paired with synthetic data that tests the pipeline. What cannot survive any independent check is not ready for certification as science; it can seek a patent or a preprint audience instead.
[P1.6] Authors have these materials at submission, when sharing is cheapest. Forcing every future reader to reconstruct them is ruinously expensive. Journals should stop publishing claims they cannot, in principle, verify.

## Turn 2: CON Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The motion mistakes a journal for a certification lab. A journal’s job is to select and communicate findings; reproducibility can be a virtue, but making it an absolute condition of publication would suppress good science without reliably improving truthfulness.
[C1.2] First, “sufficient for independent reproduction” is not a stable standard. Floating-point reductions, GPU nondeterminism, OS-specific libraries, commercial solvers, and random seeds can change outputs even when code and environment are meticulously documented. A reviewer cannot cheaply verify sufficiency. The rule becomes either a box-ticking ritual or a weapon against legitimate complexity.
[C1.3] Many valuable simulations would be unpublishable for no scientific flaw.
[C1.4] Second, the data clause is often impossible. Clinical models, mobility studies, proprietary transactions, security-sensitive work, and data covered by tribal or national sovereignty may never be legally or ethically shareable in full. Controlled-access routes can take months or be denied. Under this rule, the journal would refuse a sound epidemiological model because a hospital’s legal office—not the scientist—controls the data.
[C1.5] That is not rigor; it is collateral damage.
[C1.6] Third, shared code does not equal valid science. Authors can release tidy code for a p-hacked analysis; busy reviewers rarely run it. The rule would create a reproducibility halo around bad work, while burdening honest groups with curation work. Verification should remain a community, post-publication process, not an illusory pre-publication guarantee.
[C1.7] Finally, the cost lands hardest on small labs, students, and low-resource settings. Cleaning legacy code, building containers, and maintaining repositories is real labor. Journals should encourage and reward sharing, but refusing publication when artifacts are incomplete would slow novel ideas, negative results, and methodological critiques that advance the field.
[C1.8] None of this rejects open science. It rejects the motion’s absolutism. A journal should judge contribution, rigor, and disclosure; where artifacts are feasible, it should strongly favor them. But a universal refusal turns an important reproducibility norm into a publication veto that science cannot afford.

## Turn 3: PRO Rebuttal 1

- model: muse-wonder-1.0-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The opposition redefines “sufficient for independent reproduction” as bit-for-bit identity on any machine, then declares it impossible. That is not the standard in any experimental science. Sufficiency means a competent independent team, given the code, data access, versions, seeds, and instructions, can rerun the pipeline and test whether the reported pattern holds within a stated tolerance. GPU nondeterminism and floating-point variation are reasons to document hardware, seeds, and tolerances — not reasons to document nothing.
[P2.2] The data objection repeats the misreading. Providing data does not mean posting patient records publicly. A controlled-access repository, a de-identified dataset, or synthetic data that exercises the full pipeline, paired with a named route for qualified researchers, is provision. What the motion refuses is “data unavailable” with no auditable path at all.
[P2.3] If literally no independent researcher can ever inspect the evidence, publishing anyway is not compassion; it is asking readers to trust a claim no gatekeeper could test.
[P2.4] “Code does not guarantee validity” proves too little. A methods section does not guarantee validity either, yet no one proposes making methods optional. Disclosure is necessary, not sufficient: it lets reviewers spot leakage, hardcoded results, and cherry-picked seeds, and lets later researchers falsify what peer review missed. The supposed halo already exists — a journal’s imprimatur attached to artifacts no one can challenge.
[P2.5] On cost and the journal’s role, journals already refuse papers lacking ethics approval, adequate methods, or basic reporting; requiring checkable evidence is the same kind of selection. Encouragement, meanwhile, is the failed status quo of dead links and “on request.” Nor does the burden favor the opposition: cleaning a repository once at submission is far cheaper than forcing dozens of labs to reverse-engineer prose for years — a tax that hits small, low-resource labs hardest when they are readers building on opaque work.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1]
- missing_claim_id_refs: (none)

[C2.1] PRO tries to save the motion by watering down “sufficient for independent reproduction” into “the pattern holds within a stated tolerance” [P2.1]. That solves one problem by creating a bigger one. Once authors may choose the tolerance, hardware, seeds, and environment after seeing what survives, “reproduction” becomes a self-issued certificate. A model that flips sign on the real data but passes in a friendly container has not been independently reproduced; it has been stage-managed.
[C2.2] Journals cannot cheaply police that difference, which is why an absolute refusal rule collapses into box-ticking.
[C2.3] The data answer shows the same slide. Controlled access and synthetic data do not reproduce the actual finding. A clinical risk model built on hospital records cannot be checked through synthetic data generated from the authors’ own assumptions; the synthetic outputs inherit whatever the authors already believe. If the controlled-access route takes six months or is denied, the journal either rejects timely, privacy-compliant work or pretends the box is checked.
[C2.4] Neither is rigor.
[C2.5] PRO says code need not guarantee validity, yet it is required like methods. The analogy is false. Reviewers can read a methods section and judge its coherence from the page. Judging computational sufficiency requires executing code, managing dependencies, and chasing data-access failures under deadline.
[C2.6] Journals and volunteer referees are not equipped to do that reliably. So the practical result is publication conditioned on verification that will rarely occur, while the artifact checklist gives opaque work a stronger reproducibility halo.
[C2.7] Cost has not been answered. PRO calls encouragement the failed status quo, but the alternative to absolute refusal is not pure encouragement. It is feasibility-sensitive disclosure, access statements, badges, and post-publication replication, with rejection only where withholding demonstrably undermines the claim. That keeps scrutiny without converting journals into irreproducibility police.

## Turn 5: PRO Pressure Questions

- model: muse-wonder-1.0-high
- raw_words: 59
- clipped_words: 59
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If rejection is justified only when withholding “demonstrably undermines the claim,” how can reviewers demonstrate that undermining without the code and data needed to inspect it?
[P3.2] Q2: If no qualified outsider can ever access the data or rerun the code, what has peer review actually verified—and why should a journal certify the result as science rather than trust?

## Turn 6: CON Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 72
- clipped_words: 72
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P2.2]
- missing_claim_id_refs: (none)

[C3.1] Q1: Under [P2.1], authors may state the tolerance, seeds, and hardware after seeing their results. Who independently tests that these choices were not cherry-picked to make a fragile result survive, and by what rule would a journal find them insufficient?
[C3.2] Q2: If the named controlled-access route [P2.2] is delayed or denied, must the journal reject an otherwise sound, privacy-compliant model—or does merely naming the route count as “provision” without any actual rerun?

## Turn 7: PRO Rebuttal 2

- model: muse-wonder-1.0-high
- raw_words: 337
- clipped_words: 337
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The independent tester is anyone with the artifacts — reviewers, replicators, and rivals — and disclosure is what defeats cherry-picking. If authors favor a seed, others rerun different seeds; if they propose a tolerance, others inspect the raw outputs and test tighter bounds; if hardware matters, they vary it. A journal deems the package insufficient when following the instructions fails to regenerate the central tables or figures, or when results collapse under disclosed variations the authors failed to report.
[P4.2] Cherry-picking thrives in darkness, not on a documented record others can stress-test.
[P4.3] A2: Naming a route is not enough. Provision means data are actually deposited with an independent repository or access body, transparent criteria govern eligibility, and qualified outsiders — not the authors — decide requests. Ordinary processing delay is not denial, and refusal of an unqualified applicant is not failure.
[P4.4] But if authors retain a veto or no qualified independent researcher can gain access, the standard is unmet and publication waits or is refused. Private control is not provision.
[P4.5] This distinction answers the box-ticking charge. Journals need not rerun every paper before acceptance; they must ensure the materials making rerunning possible exist and are deposited. That is administrable, like checking ethics approval or a complete methods section, and its value does not depend on every reviewer executing code. Once artifacts exist, errors and fragile choices remain exposed for as long as the claim is cited.
[P4.6] Synthetic data, in this scheme, tests the pipeline; controlled access tests the finding. They are complements, not substitutes.
[P4.7] By contrast, feasibility declared by authors leaves the decisive judgment with the party who benefits from opacity, and reviewers cannot demonstrate harm from withholding what they cannot see. Delay for genuine access review is finite; publishing an unverifiable claim lends it indefinite authority. The stricter rule may postpone some papers, but it postpones certification until science can be checked. A journal that certifies first and hopes for checking later has chosen the halo CON fears, only without the evidence needed to dispel it.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.5], [C1.5]
- missing_claim_id_refs: (none)

[C4.1] A1: They assume exposing a flaw requires inspecting hidden code. It does not. Reviewers can demonstrate undermining from visible signs: an implausible effect size, an absent robustness check, inconsistency with independent aggregate data, or a central inference that depends entirely on an undisclosed choice. If those signs are absent, rejecting anyway punishes opacity rather than demonstrated invalidity.
[C4.2] Refutation also need not wait for original artifacts; independent data or reimplementation can later show a claim fails. The impossible standard is PRO’s: expecting journals to certify “sufficient for independent reproduction” without actually running it.
[C4.3] A2: Peer review has verified internal coherence, design plausibility, relevant controls, ethics approval, and consistency with prior knowledge. It never verifies every raw measurement before publication; it certifies a credible, sufficiently documented contribution. For legally restricted data, that limited review is how important models enter scientific debate. A journal is not granting final truth, and readers should not treat it that way.
[C4.4] Publishing with clear access limits is better than suppressing privacy-bound work because outsiders cannot rerun it.
[C4.5] But the deeper weakness is that PRO now answers the box-ticking charge by admitting journals “need not rerun every paper,” only ensure materials exist [P4.5]. If sufficiency is not tested before acceptance, it is not a guarantee of independent reproduction; it is a deposit receipt. Authors can still deposit curated code and friendly tolerances; the promised stress-testing by “anyone with artifacts” is voluntary, post hoc, and rare. At that point the rule’s only certain effect is to reject otherwise sound papers that cannot deposit data because of law, delay, or access-body denial—the collateral damage [C1.5] PRO has not removed.
[C4.6] So the choice is not between opacity and perfect reproduction. It is between a publication veto enforced by an unverified checklist and feasibility-sensitive scrutiny: visible justification, robustness reporting, access statements, and community replication. The latter catches actual incoherence without turning journals into certification labs they cannot staff. That is the decisive reason CON wins.

## Turn 9: PRO Closing

- model: muse-wonder-1.0-high
- raw_words: 185
- clipped_words: 185
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive choice is who gets to declare a computational claim ready for trust: its authors, or anyone able to test it.
[P5.2] CON's alternative rests on that first option. Reviewers judge coherence, plausibility, and visible warning signs, while the code, data, and environment that produced the numbers stay private. That can certify a persuasive story. It cannot certify the computation, because the evidence for the computation is exactly what was withheld.
[P5.3] A deposited, runnable package does not guarantee truth, and no journal must rerun every paper to make the rule work. It guarantees something more basic: that cherry-picked seeds, fragile tolerances, leakage, and silent errors remain discoverable after publication, by rivals with incentives to look. Without the artifacts, later correction depends on guesswork. With them, correction is possible in principle and in practice.
[P5.4] That possibility is the line between science and testimony. Privacy, cost, and complexity can shape how access is provided, but they cannot turn permanent inaccessibility into verification.
[P5.5] A journal may publish many things on trust. It should not lend its authority to computational findings that no independent researcher is allowed to check.

## Turn 10: CON Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 180
- clipped_words: 180
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.3]
- missing_claim_id_refs: (none)

[C5.1] The decision turns on an asymmetry the proposition cannot escape. PRO concedes that journals “need not rerun every paper” and that a deposited package “does not guarantee truth” [P5.3]. If sufficiency is not tested before acceptance, then “sufficient for independent reproduction” is not a verification—it is a deposit receipt. The promised scrutiny is voluntary, post-publication, and often never happens.
[C5.2] Yet the rule’s veto is immediate and certain. A sound clinical model, a proprietary dataset, or a privacy-governed study can be refused because access is delayed or denied by a hospital legal office, not because the science failed. Those harms land now, for reasons authors cannot fix. The reproducibility benefit, by contrast, is conditional: someone later runs it, under friendly or hostile settings, maybe never.
[C5.3] So the motion punishes what is inspectable at submission while guaranteeing no actual reproduction. A journal should not pretend to certify checkability it cannot test. Feasibility-sensitive disclosure can flag unsupported claims without converting journals into unstaffed certification labs. Decide on that asymmetry: immediate suppression of credible work against an unguaranteed possibility of later checking.
[C5.4] CON wins.
