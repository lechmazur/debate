# Debate prop_0169__glm-5-3-high__hy4-preview-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: glm-5-3-high
- model_con: hy4-preview-high
- side_swap: False

## Turn 1: PRO Opening

- model: glm-5-3-high
- raw_words: 384
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Computational research is a promise. The paper says: run this code on this data and you will get this result. A journal that publishes the paper while letting authors withhold the code, data, and environment is printing the promise without the means to check it. That's not publication; it's advertising.
[P1.2] The core problem is asymmetry. In computational fields, the result is not separable from the pipeline that produced it. A theorem can be checked line by line; a wet-lab finding can be independently replicated with different apparatus. But a machine-learning benchmark score or a simulation output cannot be verified from the methods section alone, because the methods section cannot specify the thousands of incidental choices—random seeds, library versions, preprocessing quirks, hardware-dependent defaults—that determine the number in the abstract.
[P1.3] We have all seen this play out: results that fail to replicate, benchmark claims that dissolve under scrutiny, entire subfields where later researchers quietly report they cannot reproduce headline numbers. The reproducibility crisis in computational science is not hypothetical; it is a running audit of what happens when publication does not require the artifact.
[P1.4] The proposition is the direct fix. If a journal refuses to publish without code, data, and environment details sufficient for independent reproduction, then verification becomes the default rather than the exception. Reviewers gain the ability to actually check claims instead of guessing at them. Downstream researchers stop wasting months rebuilding pipelines from vague prose.
[P1.5] And crucially, incentives shift: researchers currently pay no professional cost for irreproducible work. Making the artifact a condition of publication internalizes that cost at the only moment it bites—when the work enters the record.
[P1.6] The standard is not perfection; it is sufficiency for independent reproduction. The proposition does not demand that every rerun produce bit-identical outputs, nor that proprietary data be dumped publicly. It demands enough for an independent party to reproduce the result: the code, the data or a path to it, and the environment specification. Journals already enforce far more intrusive requirements—conflicts of interest disclosures, ethics approvals, data-sharing mandates in clinical trials.
[P1.7] [clipped]

## Turn 2: CON Opening

- model: hy4-preview-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.6], [P1.1]
- missing_claim_id_refs: (none)

[C1.1] Start with the shared premise: uncheckable computational claims are a real failure. But the motion turns a serious norm into an absolute gate: no artifacts, no publication. That trade is a mistake, because publication and reproducibility are different goods, and fusing them sacrifices too much of what journals are for.
[C1.2] Computational research is not one thing. It spans algorithm theory, simulation, machine-learning benchmarking, climate and HPC modeling, and analysis of sensitive medical or proprietary industrial data. For some, code and containers are natural. For others, the environment is legally restricted, hardware-dependent, or built on data that cannot be shipped.
[C1.3] Requiring the "sufficiency for independent reproduction" standard in [P1.6] demands a single standard across wildly different cases. "Sufficiency" is exactly what cannot be defined fairly at the moment of submission.
[C1.4] A refusal rule is not neutral. It rewards labs that can hire release engineers and containerize everything, and penalizes students, theorists, and researchers with restricted data or fewer resources. It suppresses idea-first work: a new algorithmic insight, a negative result, or a clinical study on protected records can be valuable and evaluable even when third-party rerunning is impossible. Journals that reject such papers do not create a more reproducible literature; they create a narrower, less diverse one.
[C1.5] Most importantly, a hard gate does not even buy verification. Reviewers already lack time to rebuild environments and rerun experiments. Faced with a mandate, many will check that a link exists rather than reproduce the finding. The result is compliance theater: a DOI where proof should be, the very "advertising" warned against in [P1.1], now with better metadata.
[C1.6] The fix is to make artifacts expected and rewarded, not mandatory for entry. Optional artifact evaluation, badges, registered reproduction checks, licensed repositories, and field-specific standards raise the cost of unverifiable work without exiling good ideas. Reproducibility should be a ladder journals climb after publication, not a wall they build at submission.

## Turn 3: PRO Rebuttal 1

- model: glm-5-3-high
- raw_words: 329
- clipped_words: 329
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.3], [P1.6], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] My opponent's case rests on a claim I already answered: that "sufficiency for independent reproduction" is undefinable. It isn't. Journals adjudicate contextual standards every day. Ethics approval, patient-consent requirements, clinical data-sharing plans—none of these are mechanical checkboxes; they are judgment calls with published guidelines, and editors make them without the system collapsing.
[P2.2] Why is "can an independent party plausibly rerun this?" the one standard that human judgment cannot handle? Notice also what [C1.3] quietly drops from my [P1.6]: I never demanded public dumps of proprietary or sensitive data—I said "the data or a path to it." A licensed repository, a gated enclave for protected health records, a documented access procedure all count. The legal-restriction objection attacks a rule the motion doesn't contain.
[P2.3] The equity argument inverts reality. Who is actually penalized today? The graduate student who spends six months rebuilding a pipeline from a vague methods section because a well-funded lab couldn't be bothered to release code. The refusal rule protects the resource-poor, because reading someone else's artifacts is cheap while reverse-engineering them is not.
[P2.4] And "release engineers" are not the bottleneck for the vast majority of computational work—the code already exists; writing a README and a requirements file is hours, not a hire.
[P2.5] The compliance-theater point in [C1.5] is my opponent's best card, and it proves too much. Reviewers don't rerun theorem proofs either; they check them because the artifact is on the table. Availability makes checking *possible*; withholding makes it *impossible*. A poorly enforced mandate is a fixable problem.
[P2.6] An optional badge regime is the status quo we already ran, and it produced the replication failures we both agree exist. [C1.6] asks us to try the ladder we've been standing on for a decade.
[P2.7] The remaining clash is simple: is unverifiable computational work publishable science, or isn't it? My opponent says yes, if the idea is good. But an uncheckable claim doesn't become knowledge when it's clever—it stays a promise. The literature's job is to publish knowledge.

## Turn 4: CON Rebuttal 1

- model: hy4-preview-high
- raw_words: 310
- clipped_words: 310
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.5], [P1.1], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Start with [P2.1]. Ethics approval and data-sharing plans are permissions about how research may be conducted, backed by law and review boards; failing them usually means the study was improper. "Sufficiency for independent reproduction" is different: it is a speculative prediction about whether a future stranger, with unknown budgets and licenses, can rerun a pipeline. Editors can make contextual calls, but making that prediction a precondition exiles good work whenever the guess is wrong—when data sit behind fees, an NDA, or hardware that cannot be cloned.
[C2.2] [P2.2] tries to soften this into "the data or a path to it." But the motion demands sufficiency for independent reproduction, not mere availability. A path is not sufficiency. Paid APIs, licensed compilers, and gated enclaves let an outsider beg or pay, not independently reproduce.
[C2.3] PRO wins only by redefining "sufficient" as "available," which abandons the verification the rule promises.
[C2.4] [P2.3] still flips the wrong actor. Cheap reading artifacts helps consumers who already have access; it does not help the clinician on protected records, the theorist using a commercial solver, or the under-resourced lab paying IP and containerization costs. Their work is punished at submission, while the reader's rebuild cost is better met by clearer methods, lawful code release, and funded reproduction—not rejection.
[C2.5] [P2.5] admits availability only makes checking possible. Without reviewer time and paid reproduction infrastructure, a mandate becomes a link-check: compliance theater with a nicer badge, leaving [P1.1]'s promise uncashed. A submission wall does not create verifiers; it only creates paperwork. Real verification must be built and funded after publication.
[C2.6] [P2.6] misses because voluntary badges were one weak signal, not a real ecosystem. CON rewards sharing by funding artifact evaluation, licensed repositories, and field-specific review tiers. Publication should transmit warranted contributions; reproducibility is a virtue to pursue, not a gate that kills idea-first and access-restricted work before the community can test it.

## Turn 5: PRO Pressure Questions

- model: glm-5-3-high
- raw_words: 105
- clipped_words: 105
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say verification should be built and funded *after* publication. But for a paper published without artifacts, where does the post-publication verifier get the code and data? Either authors must supply them eventually—in which case your rule is just my rule, delayed and easier to dodge—or the work stays unverifiable forever, by design.
[P3.2] Q2: You call sufficiency a "speculative prediction" editors can't make. Yet editors already judge whether a methods section is described well enough for experts to follow. What is the principled difference between assessing an adequate methods description and assessing an adequate artifact package—besides the fact that one can actually be checked?

## Turn 6: CON Pressure Questions

- model: hy4-preview-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.2], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: [P2.2] says a licensed repository, gated enclave, or documented access procedure is enough because it gives a “path to” data. If verifiers must pay a fee, get permission, or hold a license the authors control, how is that independent reproduction—not just availability?
[C3.2] Q2: Your [P2.5] says availability makes checking possible, not actual. If reviewers still lack time and funding to rerun, what does a refusal to publish add over link-check compliance theater—why exile an author with licensed data or rare hardware for a check that won’t happen?

## Turn 7: PRO Rebuttal 2

- model: glm-5-3-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: My opponent treats licensing as a loophole, but it's the honest answer to a real constraint. Clinical trials have run for decades on controlled-access repositories where qualified researchers obtain data under agreements—yet we don't say those trials weren't independently verifiable. "Independent" means independent of the authors' say-so, not free of all conditions. A verifier who obtains a licensed dataset and reruns the pipeline without the original team's involvement has performed exactly the reproduction the motion requires.
[P4.2] The alternative my opponent implies—anything short of a public dump is mere "availability"—would also invalidate most wet-lab replication, which requires materials, permissions, and budgets. That standard proves nothing because nothing can meet it.
[P4.3] A2: The gap between "checkable" and "checked" is real, but it's an argument about enforcement, not about the rule. Every gate journals operate has this shape: ethics review can be rubber-stamped, statistics can be poorly reviewed, peer review itself fails routinely. My opponent's logic would abolish every submission requirement reviewers don't exhaustively verify. The mandate's contribution is structural: once artifacts are mandatory, *someone* can check—today's reviewer, tomorrow's replication study, a skeptical reader.
[P4.4] Refusing publication without them doesn't guarantee verification; it guarantees the possibility of verification. And incentives do the rest: authors who know their code and environment will be public write better pipelines, because sloppiness now has a witness.
[P4.5] Notice where the clash has settled. My opponent conceded the failure exists and now argues only that the fix should come later and voluntarily. But their own Q1 answer was telling: post-publication verification still needs the artifacts, which means their system either demands them eventually—my rule, delayed and dodged—or never gets them at all.
[P4.6] Meanwhile the "speculative prediction" worry collapses, because editors already assess sufficiency of methods descriptions every day; the artifact package is simply that judgment applied to something checkable. A literature of promises isn't narrower when it's filtered for verifiability—it's more honest. That's what publication is for.

## Turn 8: CON Rebuttal 2

- model: hy4-preview-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P3.1], [P4.1], [P3.2], [C2.1], [P1.6], [P4.3], [C2.5], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: The dilemma in [P3.1] is false. Post-publication verification need not force authors to “eventually” supply everything under threat of rejection; it uses lawful access—licensed repositories, gated enclaves, or paid APIs. PRO’s [P4.1] concedes a licensed dataset obtained without the original team is “independent.” So my rule is not yours delayed; it is verification conditional on feasibility, not publication conditional on an editor’s guess. If an author never shares, the community can treat the result as provisional instead of exiling a contribution valuable and checkable later.
[C4.2] A2: The difference in [P3.2] is remedy, not checkability. Methods descriptions are revisable: if unclear, editors request revision and readers can still critique. An artifact-sufficiency judgment is a prediction about execution under unknown licenses, budgets, and hardware [[C2.1]]. Guess wrong, and the penalty is rejection, not clarification.
[C4.3] Thus methods assessment is ordinary editing, while making “sufficiency” a precondition turns publication into a hostage of legal and material access.
[C4.4] PRO’s redefined motion is exposed. At [P4.1], “independent” now means only independent of the authors’ say-so, not independent reproduction. A verifier who pays a fee or enters an author-arranged enclave depends on access the authors control—availability, not the verification promised in [P1.6]. PRO rewrites the rule to survive.
[C4.5] The enforcement gap returns: a mandate guarantees only the *possibility* of checking [[P4.3]], but without funded reviewers that is compliance theater [[C2.5]]. Unlike CON’s funded post-publication evaluation, refusal merely exiles researchers with restricted data or hardware.
[C4.6] Wet-lab analogies in [P4.2] prove CON’s point: we do not ban a trial because another lab cannot afford the MRI; we publish with methods and ethics, then fund replication. CON still wins because publication and reproducibility are distinct goods. The motion buys verification’s appearance by narrowing the literature at submission. The fix is to expect and reward artifacts, fund evaluation, and build licensed infrastructure after publication.
[C4.7] A wall at submission does not create verifiers; it mistakes a link for proof.

## Turn 9: PRO Closing

- model: glm-5-3-high
- raw_words: 199
- clipped_words: 199
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate ends where my opponent's own answers left it. Asked where post-publication verifiers get the artifacts, they said: licensed repositories, gated enclaves, "lawful access." That is my rule—code, data or a path to it, environment details—just unenforced and applied whenever the author feels like it. Their system isn't an alternative to the gate; it's the gate with the hinges removed.
[P5.2] Everything else follows from that one concession. A paper published without artifacts and never followed up stays a promise forever—and my opponent's remedy is that the community "treat the result as provisional." A literature of asterisks is not a fix; it's a description of the status quo that produced the replication failures we both acknowledged in round one.
[P5.3] The remaining dispute is only about where the cost lands. Under my rule, the author spends hours packaging work that already exists. Under theirs, every future reader pays—rebuilding pipelines, guessing at seeds, trusting prose that cannot be checked. That's not equity; it's a regressive tax on everyone downstream of a privileged few.
[P5.4] Publication is the moment a claim becomes part of the record. Demanding that it be checkable at that moment isn't narrowing science—it's the definition of it. Vote PRO.

## Turn 10: CON Closing

- model: hy4-preview-high
- raw_words: 199
- clipped_words: 199
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s closing calls our system “the gate with the hinges removed.” The hinges are the entire point. A gate at submission asks an editor to predict whether some future stranger, with unknown licenses and budgets, can rerun a pipeline. That is not a property of the paper; it is a guess about the world.
[C5.2] PRO’s own survival strategy proves it. Confronted with sensitive or proprietary data, they retreated from independent reproduction to a “path to” data—licensed enclaves, fees, gated repositories—and redefined “independent” as merely independent of the authors’ say-so. A verifier who must pay, beg, or enter an author-arranged environment has not gained independent reproduction; they have gained availability.
[C5.3] So the rule cannot keep its promise. Enforced strictly, it exiles the clinician on protected records, the theorist using a commercial solver, and the under-resourced lab—not because their work is bad, but because access is constrained. Enforced loosely, it becomes what PRO disparaged: a link where proof should be, compliance theater.
[C5.4] The decisive hinge is this: reproducibility is an achievement a community funds and verifies after publication, not an entry ticket an editor can demand at submission. Publication should transmit warranted contributions; reproduction should be built, not guessed. Vote CON.
