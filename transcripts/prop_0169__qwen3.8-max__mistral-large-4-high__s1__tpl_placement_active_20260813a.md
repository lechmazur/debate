# Debate prop_0169__qwen3.8-max__mistral-large-4-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: qwen3.8-max
- model_con: mistral-large-4-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen3.8-max
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Computational research makes a distinctive promise: the result is not merely observed, it can be re-executed. If a journal publishes a computational claim while withholding the code, data, and environment needed to rerun it, the journal has not certified knowledge; it has certified a narrative. The proposition sets the correct default: publication should be conditional on artifacts sufficient for independent reproduction.
[P1.2] This standard is necessary because computational results are fragile in ways that prose cannot reveal. A small change in preprocessing, a missing random seed, an unlisted library version, a different GPU, or an omitted filtering step can alter performance estimates, sometimes dramatically. Readers cannot assess robustness from a methods section alone. Independent reproduction is the only reliable check against accidental errors, selective reporting, and self-deceptive tuning.
[P1.3] The policy also fixes incentives. Today, authors are often rewarded for speed and polish, while careful artifact preparation is unpaid and undervalued. If journals make reproduction packages a condition of publication, authors will budget time for them, institutions will recognize them, and tooling will improve. The result is a healthier literature: fewer papers that cannot be built upon, fewer graduate students spending months trying to reconstruct missing pipelines, and faster cumulative progress because researchers can trust and extend prior work.
[P1.4] “Sufficient for independent reproduction” does not mean reckless disclosure. Private, medical, or proprietary data can be handled through controlled access, secure enclaves, synthetic substitutes, or detailed data dictionaries, provided an independent team can genuinely test the claim. When legal or ethical constraints make even that impossible, the work should not be published as computationally validated until it can be. Journals are the gatekeepers of the scientific record.
[P1.5] If a computational result cannot be independently rerun, it is not ready to be certified as scientific evidence.

## Turn 2: CON Opening

- model: mistral-large-4-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition mistakes a desirable practice for a workable gatekeeping rule. Journals should encourage reproducibility, not refuse publication over artifacts that are often impossible to provide or verify.
[C1.2] Consider the research this policy would exclude. Pharmaceutical companies modeling drug interactions, tech firms optimizing recommendation algorithms, and clinical researchers working with protected patient data cannot surrender proprietary code or raw datasets. Yet these fields produce computationally validated knowledge that changes medical and commercial practice. The proposition's escape hatch—controlled access—still demands secure enclaves, legal infrastructure, and curation resources that small labs and independent researchers lack.
[C1.3] The result is a literature skewed toward well-funded institutions that can afford compliance, while valuable industry and clinical work disappears from journals entirely, pushing it into preprints and technical reports where scrutiny is weaker and standards are lower.
[C1.4] The standard itself invites arbitrary enforcement. "Sufficient for independent reproduction" is technically contested: does it mean bit-for-bit identity on original hardware, or functional equivalence across different systems? Reviewers would become arbiters of technical adequacy, creating unpredictable barriers against novel methods that don't fit standard pipelines.
[C1.5] Meanwhile, the incentive structure backfires. Faced with refusal, researchers will either delay publication indefinitely to perfect artifacts, avoid computational methods altogether, or submit plausible-looking code that doesn't reflect what they actually ran—creating a worse epistemic environment than honest opacity, where readers at least know the limitations.
[C1.6] Science has advanced for centuries through theoretical argument, mathematical proof, and qualitative validation that require no execution. Post-publication scrutiny, community replication, and registered reports already police the literature effectively. Journals should adopt badges and data-availability tiers that reward openness without making it a condition of entry. Mandatory refusal is a blunt instrument that sacrifices the breadth and diversity of research for an ideal of verification that graduated incentives can achieve without locking out essential work from industry and clinical settings.

## Turn 3: PRO Rebuttal 1

- model: qwen3.8-max
- raw_words: 315
- clipped_words: 315
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The heart of CON's case is that some computational claims are valuable even if their owners cannot let others rerun them. That concedes the point. Journals do more than host claims; they certify them. If a pharmaceutical model cannot be independently executed because code and data are locked away, the paper may still be interesting, but it has not met the evidentiary standard computational publication should require.
[P2.2] The proposition does not demand public dumping of proprietary assets; it demands whatever is sufficient for independent reproduction: controlled-access enclaves, audited code, synthetic substitutes, containers, seeds, and dependency manifests. If a firm refuses even that, the answer is not to certify the claim, but to publish elsewhere or not at all.
[P2.3] CON's exclusion argument proves too much. It asks us to preserve access to unverifiable industry and clinical work at the cost of a scientific record that cannot be checked. That is precisely how fragile results accumulate: readers must trust author summaries of preprocessing, tuning, and environment. When the methods section omits a random seed, library version, or filtering threshold, no badge or post-publication scrutiny can repair the missing check.
[P2.4] A literature skewed toward reproducible work is epistemically stronger than a broader literature padded with black boxes.
[P2.5] The arbitrariness worry is also overstated. "Sufficient" should mean functional reproduction of the reported claims within their stated uncertainty, not bit-for-bit identity on original hardware. That is a clearer and more objective standard than the novelty and significance judgments reviewers already make. If anything, reproduction artifacts reduce arbitrariness by turning trust into executable evidence.
[P2.6] Finally, CON's fallback—"honest opacity"—asks journals to certify claims while admitting they cannot be checked. Voluntary badges have the weakness CON attributes to mandates: they reward openness only when cheap. Conditional publication changes incentives and makes fake code less attractive than verifiable artifacts. If computational science wants to be treated as evidence, it must make its evidence re-executable.

## Turn 4: CON Rebuttal 1

- model: mistral-large-4-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.5], [P2.2], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal rests on a sleight of hand: it redefines publication as certification of executability, then treats any exception as a failure of nerve. But journals have always certified the validity of arguments, not the portability of software. A proof in number theory or a theoretical result in physics requires no code, yet journals publish them as knowledge. Computational research spans this same range—from pure algorithmic theory to applied modeling on proprietary datasets.
[C2.2] The proposition flattens this diversity into a single technical compliance test that many legitimate forms of knowledge cannot pass, and that even passing requires infrastructure and hardware resources most independent researchers simply do not have.
[C2.3] The "sufficient for independent reproduction" standard, even interpreted functionally as PRO suggests [P2.5], remains a wealth filter. Controlled-access enclaves, audited code repositories, and secure data environments are not neutral accommodations; they are expensive infrastructure that only well-funded institutions can maintain. When PRO says firms should simply "publish elsewhere or not at all" [P2.2], the destination is preprints and technical reports—venues with weaker peer review, not stronger. The policy thus doesn't strengthen the scientific record; it bifurcates it into a verified elite and an unscrutinized periphery where excluded industry and clinical work festers without editorial oversight.
[C2.4] Most damaging is the incentive inversion. PRO assumes mandates produce honest artifacts, but they create a market for plausible facsimiles. Faced with refusal, researchers will submit code that runs but doesn't match the paper, or that requires prohibitive compute to verify, or that works only on the author's specific hardware. This "verifiable-looking opacity" is epistemically worse than the "honest opacity" PRO attacks [P2.6], because readers believe they can check what they cannot.
[C2.5] Meanwhile, the clinical researcher with protected patient data or the startup with proprietary algorithms faces a binary choice: delay life-saving publication indefinitely or abandon the field entirely.
[C2.6] Journals should instead adopt graduated transparency badges, data-availability tiers, robust post-publication scrutiny, and community replication efforts. These reward openness without making publication contingent on infrastructure that excludes exactly the applied, high-stakes research that most needs to reach the [clipped]

## Turn 5: PRO Pressure Questions

- model: qwen3.8-max
- raw_words: 49
- clipped_words: 49
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: If reproduction artifacts are a “wealth filter” [C2.3], what cheaper independent check would you let journals use to verify computational claims before publication?
[P3.2] Q2: When code and data remain inaccessible, how do badges or post-publication scrutiny certify the result, rather than just disclosing that it cannot be checked?

## Turn 6: CON Pressure Questions

- model: mistral-large-4-high
- raw_words: 68
- clipped_words: 68
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO defines "sufficient" as functional reproduction [P2.5], but if verifying a paper requires running proprietary code on specific hardware, who pays for the compute, licenses, and infrastructure that journals and reviewers would need?
[C3.2] Q2: PRO claims mandates make "fake code less attractive" [P2.6], but if journals lack resources to actually execute submissions, how does refusal deter authors from submitting plausible-looking code that doesn't reflect their actual runs?

## Turn 7: PRO Rebuttal 2

- model: qwen3.8-max
- raw_words: 277
- clipped_words: 277
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: [C3.1], [C3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: To [C3.1], the same party that pays for experiments, fieldwork, and data collection: authors and their institutions. The proposition does not require journals to buy clusters; it requires authors to make independent reproduction feasible. That can mean containers, dependency manifests, reduced datasets, synthetic data, cloud images, or controlled access to an audited environment. If a result depends on proprietary hardware or software no independent researcher can reach, then the paper is not independently reproducible, and the proposition correctly says it should not be published as computational proof.
[P4.2] A2: To [C3.2], the mandate need not turn every reviewer into a systems administrator. It makes availability a condition of entry, so journals can desk-reject missing artifacts, use artifact-evaluation committees or third-party checks, and retract papers whose packages fail independent runs. Deterrence comes from replacing “trust us” with an enforceable certification: if authors claim reproducibility, they expose themselves to falsification and retraction. Badges without that condition disclose opacity but still let journals certify unchecked results.
[P4.3] This is why PRO still wins. CON’s strongest concern is exclusion—industry models, clinical data, expensive infrastructure. But their answer is to keep the journal’s stamp of approval while withholding the means of verification. That converts scarcity into epistemic privilege: well-funded actors get to make black-box claims that others must accept.
[P4.4] PRO’s rule is narrower and stronger. It does not say valuable work must vanish; it says computational claims belong in journals only when independent researchers can test them, and otherwise belong in venues that do not pretend to validate them. If the choice is a smaller literature that can be re-run versus a larger literature that must be believed, journals should choose the former.

## Turn 8: CON Rebuttal 2

- model: mistral-large-4-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: [P3.1], [P3.2]
- missing_claim_id_refs: (none)

[C4.1] A1: To [P3.1], journals already verify computational claims through rigorous methods review, statistical re-analysis of available summary data, and comparison against established benchmarks—checks that require no execution of proprietary pipelines. Reviewers can assess whether preprocessing steps are documented, whether the described algorithms match the claims, and whether conclusions follow from the evidence presented, catching logical and statistical errors without rerunning code. These checks are cheaper, faster, and applicable to the proprietary clinical and industry models PRO fears losing.
[C4.2] A2: To [P3.2], badges and post-publication scrutiny certify by replacing false certainty with honest calibration. When a journal labels a paper "artifacts unavailable," it certifies the claim as documented but unverified, allowing readers to weigh the evidence accordingly. Community scrutiny can still catch logical errors, statistical flaws, and internal inconsistencies without rerunning the full system. This certifies the validity of the argument and the soundness of the reasoning, not the portability of software—exactly what journals have always done.
[C4.3] PRO's proposition collapses this distinction and mistakes a tool for a truth standard. It demands journals either certify executability or refuse, but legitimate science includes knowledge that cannot be executed—proprietary algorithms, protected patient data, theoretical results. By conditioning publication on infrastructure that excludes independent researchers and small labs, PRO pushes high-stakes applied work into unreviewed preprints where it escapes editorial oversight entirely. Worse, the mandate creates a market for plausible facsimiles: code that appears reproducible but conceals the actual analysis or requires prohibitive compute to verify.
[C4.4] That verifiable-looking opacity is epistemically worse than honest disclosure. Graduated transparency—badges, data dictionaries, post-publication replication—raises standards without sacrificing the breadth of the literature or locking out industry and clinical science. This preserves the journal's role as gatekeeper of argument quality while acknowledging that not all valid knowledge is executable.

## Turn 9: PRO Closing

- model: qwen3.8-max
- raw_words: 179
- clipped_words: 179
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive clash is this: CON wants journals to keep certifying computational claims while admitting they cannot be re-executed. Badges do not solve that problem; they merely label it. They let opacity borrow the authority of peer review. A paper with “artifacts unavailable” still appears in the peer-reviewed literature with the journal’s imprimatur, and downstream readers cite it as if it passed scientific validation.
[P5.2] PRO’s rule preserves the meaning of publication. If a computational result is truly scientific evidence, independent researchers must be able to test it—not just admire the authors’ description. Controlled access, containers, synthetic substitutes, or audited environments can meet that standard without dumping proprietary assets. Where even that is impossible, the claim belongs in a venue that does not pretend to validate it.
[P5.3] The question is not whether a reproducibility mandate is convenient for every actor. It is whether journals should convert computational claims into knowledge before they can be checked. They should not. Decide PRO because a smaller literature that can be re-run is more scientific than a larger literature that must simply be believed.

## Turn 10: CON Closing

- model: mistral-large-4-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s closing asks us to choose between a smaller verifiable literature and a larger believable one. But that is a false choice, because the mandate does not produce a verifiable literature. It produces a literature of plausible facsimiles.
[C5.2] When journals condition publication on artifacts they lack the compute, time, or legal infrastructure to actually execute, they do not eliminate black boxes; they disguise them. Authors respond to refusal threats by submitting code that runs, that looks legitimate, that carries dependency manifests and containers—but that either conceals the actual analysis, requires prohibitive verification costs, or reproduces nothing like the paper’s results. Readers see the badge of reproducibility and trust what they cannot check. This verifiable-looking opacity is epistemically worse than honest opacity, because honest disclosure at least signals uncertainty, while the mandate manufactures false certainty.
[C5.3] The proposition confuses the appearance of reproducibility with the fact of it. Journals should certify arguments and evidence, not software portability. Adopt graduated transparency that calibrates trust honestly: badges, data dictionaries, and post-publication scrutiny that admit when verification is impossible rather than pretending it occurred. Science advances on calibrated confidence, not on the illusion that a refusal policy can force truth into executable form.
[C5.4] Decide CON.
