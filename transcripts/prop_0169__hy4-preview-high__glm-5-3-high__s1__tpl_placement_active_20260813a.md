# Debate prop_0169__hy4-preview-high__glm-5-3-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: hy4-preview-high
- model_con: glm-5-3-high
- side_swap: True

## Turn 1: PRO Opening

- model: hy4-preview-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a paper reports that a model achieves 94% accuracy, the number is not the finding; the finding is that the code, run on the data, in that environment, produced 94%. Strip away the code, data, and environment, and the paper is a press release, not a result. Computational research turns method into artifact: the experiment is the pipeline. If journals will not demand the pipeline, they are certifying conclusions while withholding the only thing that could prove them.
[P1.2] Verification, not trust, is the engine of science. In bench biology, a methods section is a promise; in computational work, a methods section without executable artifacts is barely more than an unbacked promise. Bugs, silent data-preprocessing choices, random seeds, library versions—these decide results and stay invisible in prose. Consider how often headline results collapse once someone reruns them: an undisclosed spreadsheet formula, a test-set leak, a deprecated package.
[P1.3] Those errors were not caught by reading; they were caught by running.
[P1.4] The usual objection is burden. But the asymmetry is decisive: a physical sample degrades and costs money to ship; bits do not. Containers freeze environments, repositories issue DOIs, and preservation costs nothing next to the value of trust. The marginal cost of sharing what is already on the researcher's machine is near zero, while the cost of an unreproducible published claim is enormous: wasted follow-up studies, misallocated funding, and misplaced confidence.
[P1.5] Refusing publication is therefore not a disproportionate sanction; it is the only one with teeth. We already demand conflict-of-interest disclosure; this is the same logic applied to evidence.
[P1.6] A journal that prints a computational result it refuses to let anyone verify is not a journal; it is a bulletin board. The proposition simply says: if you want Science's imprimatur, show the experiment. No code, no data, no environment, no paper.

## Turn 2: CON Opening

- model: glm-5-3-high
- raw_words: 276
- clipped_words: 276
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition demands an absolute rule: no artifacts, no publication—ever. That rule is unworkable, epistemically confused, and it punishes the wrong people.
[C1.2] Start with the cases the rule cannot survive. Research built on licensed commercial data, electronic health records protected by privacy law, proprietary code from industry partners, or data gathered under consent agreements that forbid redistribution. The authors cannot legally share what the proposition requires. Under this policy, a valid study of hospital outcomes or a collaboration using a licensed satellite archive is unpublishable—not because it is wrong, but because its evidence is not freely transferable.
[C1.3] A rule that excludes good science to exclude bad science has failed on its own terms.
[C1.4] Second, the burden claim is false. "Sharing is near-free" confuses the file with the artifact. Making code runnable by strangers—documenting, de-identifying, checking licenses, packaging environments, answering correspondents—is hours of skilled labor, often falling on graduate students and researchers at under-resourced institutions. Wealthy labs absorb this; others stop submitting.
[C1.5] The mandate becomes a regressive filter on who may publish, not a filter on what is true.
[C1.6] Third, and decisive: reproducibility is not validity. Software can run perfectly and encode a flawed design—test-set leakage, biased sampling, a meaningless metric. The headline retractions PRO invokes were caught by scrutinizing methods and statistics, not by anyone rerunning a container. What PRO actually wants—soundness—is enforced by review, theory, and replication of findings, none of which the proposition requires.
[C1.7] It demands the ceremony of a clean pipeline while leaving every real failure mode untouched.
[C1.8] The journals already have proportionate tools: badges, encouraged deposit, dedicated reproducibility reviewers. Refusal-to-publish is the one option that is both blunt and self-defeating. Reject it.

## Turn 3: PRO Rebuttal 1

- model: hy4-preview-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.8], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The rule you attack is a straw man. You say the proposition demands public GitHub dumps; your Exhibit A is licensed data and EHRs [C1.2]. But the motion says code, data, and environment "sufficient for independent reproduction"—not "downloadable by anyone." That means controlled-access repositories, de-identified extracts, licensed-auditor execution, or a container with a documented data interface.
[P2.2] Your hard cases do not "exclude good science" [C1.3]; they are where the rule matters most, because when data are sealed, silent preprocessing and leakage are invisible, and vetted reproduction is the only check. If no independent party, even under license, can run the pipeline, the journal has no business certifying the result.
[P2.3] The burden argument [C1.4] mislabels the experiment as packaging. Documenting the pipeline is doing the experiment, not polishing it after. Yes, deposit takes work; irreproducibility costs far more—failed replications, wasted grants, careers chasing ghosts. Your "wealthy labs absorb it" point cuts the other way: opacity helps insiders.
[P2.4] Under-resourced scholars are the ones who cannot email a famous lab to ask which NumPy version it used. Badges and encouraged deposits [C1.8] have already failed as soft tools; they generate empty READMEs and dead links. A requirement makes compliance routine, not decorative.
[P2.5] You are right that reproducibility is not validity [C1.6]—and that is irrelevant. Running code does not guarantee sound design, but it is the only way to expose unsound execution. Leakage, mislabeled splits, bad filters: these hide in the run, not the prose. Reviewers can suspect from methods; they can prove only by running.
[P2.6] Without artifacts, even those suspicions could not be confirmed.
[P2.7] You offer softer tools to preserve a comfortable status quo. The clash is simple: does a journal's seal mean "peer-reviewed" or "verifiable"? If a computational result can be published without its pipeline, the seal is decoration. Refusal is not blunt; it is the only sanction aimed at the actual artifact.

## Turn 4: CON Rebuttal 1

- model: glm-5-3-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [C1.2], [P2.3], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal concedes more than it defends. Notice what happened to the rule: to survive my hard cases, it dissolved. "Sufficient for independent reproduction" now means controlled-access repositories, licensed-auditor execution, containers with "documented data interfaces" [P2.1]. That is not one requirement; it is a spectrum of negotiated arrangements, each requiring lawyers, data-use agreements, ethics amendments, and auditor infrastructure that does not exist at most journals.
[C2.2] The absolute rule—"no artifacts, no publication"—has quietly become a case-by-case judgment call. A proposition that must be reinterpreted this heavily in round two was never a publishable policy.
[C2.3] And the reinterpretation doesn't even work. Licensed-auditor execution means the journal must recruit, fund, and trust vetted third parties for every sealed-data paper. Who pays? Who audits the auditors?
[C2.4] For a mid-tier venue handling dozens of computational submissions, this is a fantasy bureaucracy. In practice, editors facing an impossible review pathway will desk-reject the hospital-outcomes study—exactly the exclusion I flagged [C1.2], now by inconvenience rather than by rule.
[C2.5] On burden [P2.3]: calling packaging "doing the experiment" is a category error. The experiment produced knowledge; the packaging produces compliance. Researchers already document methods for peers. What PRO demands is engineering for strangers—hours that buy no new scientific insight, taken from the same graduate students who actually do the science.
[C2.6] Most damaging: PRO's own concession. "Running code does not guarantee sound design" [P2.5]—agreed. So the mandate screens for neither flawed design nor statistical error nor bias, the failure modes that actually retract papers. It guarantees only that a pipeline executes.
[C2.7] That is a certificate of mechanical hygiene. Meanwhile, PRO admits reviewers "can suspect from methods" [P2.5]—so review, the existing tool, is doing the epistemic work in their own example.
[C2.8] The seal PRO wants—"verifiable"—verifies the wrong thing. Mandate ceremony, get ceremony.

## Turn 5: PRO Pressure Questions

- model: hy4-preview-high
- raw_words: 67
- clipped_words: 67
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4], [C2.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: You call controlled-access verification a "fantasy bureaucracy" [C2.4], yet journals already enforce consent and data-use agreements; why is verifying execution uniquely impossible, rather than just an administrative task you refuse to fund?
[P3.2] Q2: You say review is "doing the epistemic work" from methods alone [C2.7]; but leakage, mislabeled splits, and bad filters are execution errors. How does prose-only review *disprove* them, rather than merely suspect them?

## Turn 6: CON Pressure Questions

- model: glm-5-3-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: The motion says authors must "provide code, data, and environment details." Where in that text is your license for controlled-access repositories and licensed auditors [P2.1]? If the rule only works once you've rewritten it, why defend it as written rather than defend the amended version you actually argued?
[C3.2] Q2: You conceded "running code does not guarantee sound design" [P2.5]. Which failure mode that actually causes retractions—flawed design, statistical error, bias—does your mandate catch? If the honest answer is none, what scientific error are we gatekeeping against?

## Turn 7: PRO Rebuttal 2

- model: hy4-preview-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C3.1], [C1.2], [C2.4], [P3.1], [C3.2], [P2.5], [C2.7], [P2.4]
- missing_claim_id_refs: (none)

[P4.1] A1: The license is in “sufficient for independent reproduction.” Your question treats the text as if it said “freely transferable” [C3.1]; it does not. The motion never says “publicly downloadable”; it says provide what lets an independent party reproduce. For licensed or sealed data, providing means controlled access: a documented container, a de-identified interface, or execution by an auditor bound by the same data-use terms. That is not rewriting; it is applying a functional standard to CON’s hard cases [C1.2].
[P4.2] If the rule meant only public posting, it would collapse even for ordinary large datasets. CON calls verification a “fantasy bureaucracy” [C2.4], yet journals already enforce consent and data-use agreements [P3.1]; enabling execution is administrative, not impossible.
[P4.3] A2: Your second question assumes the honest answer is none [C3.2]; it is not. I do not need to catch every retraction cause; I need to catch the class only artifacts can catch. Running code does not guarantee sound design [P2.5], but it exposes unsound execution: test-set leakage, mislabeled splits, silent preprocessing, metric miscalculation, and seed or library drift. Those are the gap between a paper’s claimed method and the computation that produced the number.
[P4.4] Prose review can only suspect them [C2.7]; artifacts let reviewers prove them. That is why soft tools yield empty READMEs and dead links [P2.4].
[P4.5] The real clash is not public versus controlled; it is certifiable versus decorative. CON’s “rewritten rule” jab fails because enforceable standards use functional thresholds—“sufficient,” “independent”—which delegate method without surrendering principle. Their practical objection is audits cost time. But preserving bits is cheap, while an unreproducible certified claim is expensive: wasted grants, wrong follow-ups, false confidence.
[P4.6] Reviewers already assess design and statistics; artifacts let them check that the paper describes the pipeline that generated the result. Controlled access excludes no good science—it excludes unverifiable certification. No verified pipeline, no Science’s seal; that is not bluntness, it is the minimum condition for a computational result.

## Turn 8: CON Rebuttal 2

- model: glm-5-3-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.5], [C1.2], [C1.4], [P2.5]
- missing_claim_id_refs: (none)

[C4.1] A1: Data-use agreements and consent enforcement are passive checks: an editor reads a document, stamps it, and moves on. Verifying execution is active: someone must be recruited, paid, granted compute, and trusted to run every sealed-data pipeline a journal publishes. No journal has that staff, and the motion provides no funding for one. Worse, "who audits the auditors" is not rhetoric—it is a real liability question when a licensed dataset leaks through a journal's vetted reproducer.
[C4.2] Journals can decline to publish a paper whose paperwork is missing; they cannot manufacture a verification infrastructure that does not exist. The administrative-task framing hides a new institution.
[C4.3] A2: It often cannot—and that concedes my point, because the proposition doesn't require anyone to run anything either. Read the motion: authors must *provide* code, data, and environment details. It is a deposit mandate, not a verification guarantee. A paper with test-set leakage and a buggy pipeline sails through if the buggy, leaky pipeline is deposited.
[C4.4] The seal PRO promises—"verifiable"—is never actually earned under his own rule; a journal can comply fully while never executing a single line of code. His "certifiable versus decorative" clash [P4.5] collapses: provided is not verified.
[C4.5] That is the decisive comparison. PRO's entire case rests on the value of *running* artifacts, but the motion as written mandates only *handing them over*. So the benefits he claims—caught leakage, exposed preprocessing—are delivered by a different policy, one requiring funded reproduction review, that he has not defended. What the motion actually delivers is exclusion of legally constrained science [C1.2], a regressive burden on under-resourced researchers [C1.4], and a certificate that artifacts exist somewhere.
[C4.6] The failure modes that retract papers—design, statistics, bias—remain untouched, as PRO admitted [P2.5]. A mandate that buys ceremony at the price of good science should be refused. The proportionate tools—badges, deposit encouragement, optional reproduction review—are the ones that can evolve into real verification. Refuse the motion; keep the science.

## Turn 9: PRO Closing

- model: hy4-preview-high
- raw_words: 189
- clipped_words: 189
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.4]
- missing_claim_id_refs: (none)

[P5.1] CON's final attack is that the motion only forces authors to provide artifacts, so “provided is not verified” [C4.4]. That mistakes the standard. The proposition requires only that the materials authors hand over are “sufficient for independent reproduction,” not that journals execute them. The seal is verifiability, not verification on demand.
[P5.2] No policy can make every editor run every container, and CON's own alternative—badges, encouraged deposit, optional review—leaves results neither verified nor verifiable. That is the decisive asymmetry.
[P5.3] A deposited pipeline with test-set leakage can be caught the moment anyone reruns it; an undisclosed pipeline can never be caught at all. Reviewers can suspect flawed design or statistics from prose, but only provision turns execution errors—leakage, mislabeled splits, silent preprocessing, library drift—from permanent ghosts into testable claims. The motion does not promise to catch bad design; it refuses to certify a computational claim no one can ever check.
[P5.4] Controlled access answers the licensed-data cases; documenting the pipeline is doing the experiment, not packaging. If a journal prints a number and withholds the only thing that could disprove it, the seal is decoration. Minimum condition: no verifiable pipeline, no paper.

## Turn 10: CON Closing

- model: glm-5-3-high
- raw_words: 208
- clipped_words: 208
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.1], [P5.3], [C1.2], [C1.4], [P2.5]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing concedes the case. "The seal is verifiability, not verification" [P5.1]—but verifiability that no one is required to exercise is a filing cabinet with a ribbon on it. His own words: leakage is caught "the moment anyone reruns it" [P5.3]. Under his motion, that moment never has to come.
[C5.2] Authors hand over a leaky, buggy pipeline; the journal stamps it; the number stands. The errors that sink papers stay exactly where they were.
[C5.3] That is the whole debate. The proposition's promised benefit—errors exposed by execution—belongs to a different policy, one with funded reproduction review, which PRO never defended. What he defended as written is a deposit ritual: authors provide artifacts, no one checks them, and the seal gets upgraded anyway.
[C5.4] So weigh what the motion actually delivers against what it costs. Delivered: a compliance certificate, ceremony. Cost: valid research on licensed, private, and consent-restricted data pushed toward desk rejection [C1.2], and hours of packaging labor that filter out under-resourced researchers [C1.4]—while design flaws, statistics, and bias, the failure modes PRO admits his rule cannot touch [P2.5], sail through untouched.
[C5.5] Badges, encouraged deposit, evolving reproduction review can grow into real verification. A blunt mandate buys ritual and pays for it in good science. That trade fails. Refuse it.
