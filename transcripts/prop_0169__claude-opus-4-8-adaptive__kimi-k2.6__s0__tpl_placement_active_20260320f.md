# Debate prop_0169__claude-opus-4-8-adaptive__kimi-k2.6__s0__tpl_placement_active_20260320f

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: claude-opus-4-8-adaptive
- model_con: kimi-k2.6
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-4-8-adaptive
- raw_words: 318
- clipped_words: 318
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9], [P1.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A published computational result is a claim: "run this analysis on this data and you get this finding." If no one outside the authors' own machines can actually run it, that claim has never truly been tested. It has only been asserted. The motion fixes a simple defect: a journal's job is to certify knowledge, and you cannot certify what cannot be checked.
[P1.2] My case rests on three pillars.
[P1.3] First, reproducibility is the minimum definition of science, not a luxury add-on. We rightly demand that a chemistry paper list its reagents and procedures. Code, data, and environment are the computational equivalent of the methods section. A "method" that omits the actual steps isn't a method; it's a press release.
[P1.4] Refusing to publish without them isn't a new burden—it's enforcing a standard that already governs every other field.
[P1.5] Second, the status quo is demonstrably broken, and only a hard rule fixes it. We have lived through repeated episodes—in psychology, in medicine, in machine learning—where headline results evaporated once others tried to rerun them. Voluntary "available upon request" policies fail in practice: requests go unanswered, files are lost, environments rot. Soft encouragement has had decades to work.
[P1.6] It hasn't. A publication condition is the one lever that reliably changes author behavior, because it attaches the requirement to the thing researchers most want—the paper itself.
[P1.7] Third, sharing protects everyone, including authors. Hidden code hides bugs. A buried indexing error or a leaked test set can silently invent a discovery. When the pipeline is open, errors get caught early, others build on solid work instead of chasing ghosts, and the honest researcher is shielded from later suspicion.
[P1.8] Transparency is not policing; it's quality control.
[P1.9] CON will warn about burdens and edge cases. I'll meet those directly. But notice the core trade: a one-time effort to package what you already built, versus a permanent literature of unverifiable claims. Choose verifiable knowledge.
[P1.10] Vote PRO.

## Turn 2: CON Opening

- model: kimi-k2.6
- raw_words: 254
- clipped_words: 254
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The motion imposes a categorical ban: unless a paper arrives with a turnkey reproduction kit, the journal must reject it. That sounds like rigor; in practice, it is a blunt instrument that would silence legitimate research, create perverse incentives, and mistake packaging for truth.
[C1.2] First, entire computationally vital domains operate under binding constraints that make full disclosure impossible. Medical imaging relies on patient data locked behind HIPAA and ethics boards; industry collaborations hinge on proprietary code and trade secrets; government and indigenous-data agreements forbid open release. Under this rule, a groundbreaking cancer-detection model trained on sensitive clinical records is unpublishable. The authors face a false choice: violate privacy law or accept scientific silence.
[C1.3] A blanket refusal punishes researchers for constraints they do not control.
[C1.4] Second, the standard of “sufficient for independent reproduction” is far more demanding than PRO suggests. A complex climate simulation or legacy genomics pipeline may depend on obsolete libraries, bespoke hardware, and stochastic initialization sequences that no one can fully document. Requiring journals to police whether a stranger’s machine can perfectly recreate a finding turns peer reviewers into IT auditors and shifts the journal’s mission from evaluating claims to certifying software engineering.
[C1.5] Finally, the motion conflates transparency with reliability. Reproducibility can be enforced without universal publication of raw assets: independent replication by contracted labs, phased release, and third-party escrow are all viable alternatives. Hard categorical rules feel satisfying, but science advances by judging claims on their merits, not by enforcing a single packaging standard that bars whole fields at the door.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-4-8-adaptive
- raw_words: 331
- clipped_words: 331
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.2], [C1.4], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON's whole case leans on one conflation: that the motion demands a public data dump for everyone. It doesn't. The text requires materials "sufficient for independent reproduction"—and for sensitive data, that standard is met by controlled-access repositories under data-use agreements, exactly how genomics and clinical consortia already operate. The cancer model trained on HIPAA records can ship its code, its environment, and a credentialed pathway by which a qualified, ethics-approved reviewer reproduces the result.
[P2.2] That isn't a privacy violation; it's the normal machinery of medical data sharing. So [C1.2]'s "false choice" is a false dilemma. And in the rare case where literally no one—no auditor, no escrow lab, no credentialed peer—can ever check the finding? Then CON has simply described an unverifiable claim, and the honest label for that is "preliminary," not "published as certified knowledge."
[P2.3] On [C1.4]: CON inflates the standard into bit-perfect recreation, then calls it impossible. But reproduction doesn't mean a stranger regenerates every stochastic seed identically; it means the pipeline, dependencies, and data are documented well enough to test the claim. Reviewers don't become "IT auditors"—they check that the materials exist and are complete, the same way they already check that a methods section is present. A climate model that releases its code and pinned environment is categorically more verifiable than one that releases nothing.
[P2.4] CON is using the hardest imaginable case to excuse the easy 90%.
[P2.5] Now watch [C1.5] collapse CON's own position. They propose "independent replication by contracted labs, phased release, third-party escrow." Every one of those concedes my core premise: computational claims must be verifiable before we trust them. The only dispute is the lever.
[P2.6] And my opening already answered this—voluntary mechanisms, detached from the paper, fail in practice. Escrow nobody is required to fund, replication nobody is required to commission: that's "available upon request" wearing a new costume.
[P2.7] So the clash is settled in our favor. CON agrees verification matters. They just won't attach it to the one thing that reliably works—publication itself.

## Turn 4: CON Rebuttal 1

- model: kimi-k2.6
- raw_words: 300
- clipped_words: 300
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [P2.1], [P2.3], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO wants to save the motion by rewriting it. [P2.1] reads "controlled access" into a text that demands authors provide at the point of submission materials sufficient for independent reproduction, but entire categories of research live behind legal walls that bar even credentialed escrow: proprietary industrial algorithms bound by NDAs, defense simulations classified under national security law, indigenous genomic data protected by sovereignty agreements that forbid any external repository deposit. PRO labels these "rare" and calls them preliminary. That does not make them marginal; it makes the motion a publishing ban on whole applied fields that society has compelling reasons to read.
[C2.2] PRO also insists the burden is light. [P2.3] claims reviewers merely check that materials "exist and are complete." But the motion requires sufficiency for genuinely independent reproduction, not a file manifest. A container that crashes on standard hardware, a dataset locked behind an approval queue no reviewer will clear before deadline, or a stochastic climate run requiring a million-dollar cluster, bespoke storage, and custom firmware—all fail the standard in practice as written.
[C2.3] PRO cannot have it both ways: either the rule is weak enough to be painless, or it is strong enough to exclude serious science. It cannot be both.
[C2.4] Finally, [P2.5] mistakes CON's alternatives for concessions. Independent replication by contracted labs, phased release, and adjudicated trust verify claims without demanding that every author ship a turnkey kit before the title page goes live. The motion is a categorical refusal to publish outright; our alternatives are categorical permissions with independent verification layered afterward. That is not a dispute over levers.
[C2.5] PRO has offered no evidence that escrow and replication "fail in practice" beyond bare assertion, and even if they were imperfect, a leaky lifeboat does not justify scuttling the ship. The motion silences legitimate, valuable research. Reject it.

## Turn 5: PRO Pressure Questions

- model: claude-opus-4-8-adaptive
- raw_words: 88
- clipped_words: 88
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You endorse "contracted labs, phased release, and escrow" as verification done *after* publication—but who compels or funds any of it once the paper is already in print? If nothing attaches the requirement to publication, how is that not the same "available upon request" you admit can be "imperfect"?
[P3.2] Q2: For your truly sealed cases—classified defense sims, data no credentialed auditor may ever touch—if literally no independent party can check the result, on what basis should a journal stamp it as certified knowledge rather than label it preliminary?

## Turn 6: CON Pressure Questions

- model: kimi-k2.6
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If credentialed escrow and controlled access satisfy your standard, are you imposing a massive unfunded mandate on journals to build and police that infrastructure, or are you redefining "provide" to mean "point toward a gatekeeper the journal does not control"?
[C3.2] Q2: You dismiss sealed computational work as "preliminary," yet journals publish theoretical proofs and unique observations no one can independently recreate; why does computation alone deserve a categorical publishing ban you impose on no other discipline?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-4-8-adaptive
- raw_words: 324
- clipped_words: 324
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: "Provide" means authors furnish what they actually control—their code, their pinned environment, and a documented route to the data, whether that's an open deposit or a credentialed-access repository that already exists. Journals build nothing. They check that the kit and the access pathway are present, exactly as they already check that a methods section and an ethics approval are present. That's not an unfunded mandate; it's the same gatekeeping journals do every day.
[P4.2] And notice CON's dilemma cuts the other way: if pointing to a credentialed repository counts as "provide," then their HIPAA and indigenous-data fears dissolve—because those very repositories are how sensitive data is shared right now.
[P4.3] A2: The proof analogy defeats CON. A theoretical proof is the most independently checkable object in science—every reader can trace the logic line by line. A unique astronomical observation gets published precisely with its instrument, calibration, and raw frames so others can scrutinize it, and it's flagged as a single event. Computation is different in the worst way: it is perfectly checkable in principle—just rerun it—yet routinely shipped as an opaque black box.
[P4.4] We don't ban computation; we ask it to meet the same disclosure norm every other field already accepts. The sealed-classified case isn't an exception to that principle; it's research that has voluntarily left the certified-knowledge system, and should be labeled accordingly.
[P4.5] So weigh the debate. CON has spent two speeches hunting for the hardest 5%—classified sims, million-dollar clusters—to excuse the easy 90% where authors simply won't package what they already built. But a rule is judged by the behavior it changes at scale, not by its rarest edge. CON's own alternatives—escrow, contracted replication—concede verification must precede trust, yet they detach it from the one lever that reliably works.
[P4.6] Their lifeboat metaphor backfires: the status quo isn't a ship, it's a literature already taking on water from unreproducible results.
[P4.7] The clean choice stands. Verifiable knowledge, or asserted knowledge dressed as certified. Vote PRO.

## Turn 8: CON Rebuttal 2

- model: kimi-k2.6
- raw_words: 311
- clipped_words: 311
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: Funding and compulsion already sit outside journals. Grant agencies can mandate escrow deposits and replication contracts as conditions of award; consortia already commission independent audits. The structural difference from "available upon request" is that these are pre-committed, funded obligations with legal teeth, not favors that busy authors may ignore. Shifting enforcement to funders preserves the journal's role as evaluator of scientific claims rather than converting it into an IT compliance office.
[C4.2] A2: A journal certifies that claims have survived expert evaluation against the evidence presented, not that a stranger has physically rerun every step. A theoretical proof is accepted because experts trace its logic line by line; computational manuscripts can be vetted the same way through algorithmic description and sensitivity analysis. We do not label CERN findings "preliminary" because no other lab can afford the collider. Slapping "preliminary" on classified defense simulations or proprietary pharmaceutical models ghettoizes entire disciplines that society desperately needs in the published record.
[C4.3] Now PRO keeps shrinking the motion to fit reality. [P4.1] claims reviewers merely check that a pathway "exists," but the motion demands materials sufficient for genuinely independent reproduction. That standard is failed by million-dollar clusters, obsolete firmware, approval queues no reviewer will clear, and legal walls no repository penetrates. PRO dismisses these as the "hardest five percent," yet they are the daily substance of defense, industry collaboration, indigenous health, and proprietary drug discovery.
[C4.4] We do not reject telescope observations because no one can rebuild the instrument, or reject CERN findings because no lab can afford the collider. Why should computation alone face a categorical publishing ban? PRO has mistaken packaging for truth. CON defends a literature broad enough to hold both open benchmarks and sealed cancer models, verified through funded post-publication replication where feasible and rigorous peer review of methodology where it is not.
[C4.5] The motion promises rigor and delivers silence. Reject it.

## Turn 9: PRO Closing

- model: claude-opus-4-8-adaptive
- raw_words: 211
- clipped_words: 211
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7], [P5.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Strip away the edge cases and one question decides this debate: what actually changes author behavior at scale?
[P5.2] CON's entire alternative—funder mandates, contracted replication, post-publication escrow—lives everywhere except the moment that matters. They admit verification must precede trust. They just refuse to attach it to the only thing every author universally wants: the publication itself. Their A1 even concedes voluntary requests "may be ignored," then proposes shifting the duty to grant agencies the journal can't see and can't enforce.
[P5.3] That's not a fix. That's hoping someone else holds the line.
[P5.4] The motion holds it at the one checkpoint that works. And notice CON spent four speeches on classified sims and million-dollar colliders—the rarest five percent—precisely because the ordinary ninety percent has no defense. The everyday computational paper isn't blocked by HIPAA or national security. It's blocked by an author who simply never packaged the code they already wrote.
[P5.5] That is the literature taking on water, and a publication condition is the only lever that drains it.
[P5.6] CERN and telescopes don't help CON—they publish their instruments, calibrations, and frames precisely so scrutiny is possible. Computation, uniquely, is perfectly checkable yet routinely shipped sealed.
[P5.7] So choose: verification bolted to the act of publishing, or verification that depends on goodwill nobody enforces.
[P5.8] Vote PRO.

## Turn 10: CON Closing

- model: kimi-k2.6
- raw_words: 200
- clipped_words: 200
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO asks what changes behavior at scale. But the motion is not a behavior nudge—it is a categorical refusal to publish. CON has shown that entire disciplines—proprietary drug discovery, classified defense modeling, indigenous health data, industrial collaboration—operate under legal and technical walls that no repository setting can pierce. PRO calls these "the rarest five percent," yet they are the daily substance of applied computational science.
[C5.2] A rule that silences cancer models bound by HIPAA, or pharmaceutical pipelines locked by trade secrecy, is not a quality standard; it is a publishing ban on whole fields that society needs in the literature.
[C5.3] And PRO never answers the asymmetry. We publish theoretical proofs no one reruns empirically, CERN findings no lab can replicate, and observations from unique instruments. Computation alone faces a categorical bar because it is "checkable in principle." But scientific merit lies in the claim and evidence, not in whether a stranger can execute the same binary on their laptop.
[C5.4] Verification matters, but it can live in funded replication, funder escrow, and rigorous peer review of methodology—without ghettoizing sealed research as "preliminary."
[C5.5] The motion exchanges a broad literature for a narrow packaging test. That is too high a price. Vote CON.
