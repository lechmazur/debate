# Debate prop_0169__claude-sonnet-5-high__grok-4.5-high__s0__tpl_placement_active_20260320f

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: claude-sonnet-5-high
- model_con: grok-4.5-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 361
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Computational research makes an empirical claim: run this process on this data and you get this result. That claim is only science if someone else can test it. Without code, data, and environment details, a paper's "result" is just an assertion wearing the costume of evidence. The proposition asks journals to enforce the minimum condition for a computational claim to count as a scientific claim at all.
[P1.2] Consider what already happens without this rule. Multiple large-scale audits across psychology, biomedicine, and machine learning have found that a majority of authors, when asked, either refuse or simply fail to provide the materials needed to rerun their own analysis. Papers have been retracted years after publication because a spreadsheet error or a leaked test-label bug invalidated headline results that no one could check earlier - because no one could get the code. In machine learning specifically, entire subfields have had to walk back years of claimed benchmark improvements once independent teams tried to reproduce them and found the gains were due to unreported hyperparameter tuning or data leakage.
[P1.3] These are not hypothetical risks; they are the default failure mode of a system that takes computational results on faith.
[P1.4] The gatekeeping logic is simple and already familiar. Journals already refuse papers without a methods section, without statistical detail, without disclosed conflicts of interest. Nobody calls that censorship - it's the price of entry for making an empirical claim. Code and data are the methods section of computational research.
[P1.5] A chemistry paper that said "we synthesized the compound using a process we won't describe" would be laughed out of peer review. A computational paper that says "we got 94% accuracy using a model we won't share" should face the same fate.
[P1.6] The alternative CON must defend is a status quo where journals certify results that even the authors' own collaborators often cannot reproduce a year later. That is not a minor inconvenience - it is a structural failure of the verification function that publication is supposed to serve. My case rests on this: [clipped]

## Turn 2: CON Opening

- model: grok-4.5-high
- raw_words: 306
- clipped_words: 306
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Journals should not refuse computational papers that omit full code, data, and environment packages. That absolute rule confuses one useful check with the condition of scientific communication itself, and it would suppress more valid work than it would salvage.
[C1.2] A computational contribution is rarely just “run this exact artifact and match this number.” It includes novel algorithms, theoretical bounds, design rationales, ablation logic, and empirical patterns that other researchers can reimplement, critique, or extend from a careful methods description. Independent reconstruction already tests claims; demanding a frozen container as the price of entry elevates packaging convenience over intellectual substance. Perfect bit-level reproduction is often impossible anyway once hardware, nondeterminism, library drift, or floating-point differences enter. “Sufficient for independent reproduction” therefore becomes an elastic gate that invites endless post-hoc fights rather than settled science.
[C1.3] Worse, the rule is unworkable across large swaths of real research. Clinical models trained under privacy statutes, industrial systems built on proprietary corpora or regulated transaction streams, national-security simulations, and frontier models whose training data measure in tens of petabytes cannot simply ship the raw inputs. Refusing those papers does not increase verification; it drives the findings into closed white papers or never-shared tech reports where scrutiny is weaker still. Even fully open projects face non-trivial storage, licensing, and documentation burdens that hit smaller labs and less-resourced institutions hardest, converting every methods paper into an unpaid software-release project.
[C1.4] Journals already demand transparent methods, statistical detail, and conflict disclosure. Encouraging availability statements, optional badges, and post-publication notes is coherent with that tradition. Mandatory refusal is not. It treats every computational result as an unshareable black box unless the authors supply a runnable museum exhibit.
[C1.5] That is the wrong standard: it overweights exact rerunability and underweights the cumulative, multi-method verification that actually advances knowledge. The cost in excluded science exceeds any gain in archive completeness.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 305
- clipped_words: 305
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.2], [C1.3], [C1.4]
- missing_claim_id_refs: (none)

[P2.1] CON's whole case rests on a strawman: that PRO demands "bit-level" identical reproduction, a "runnable museum exhibit." Reread the proposition - it says "sufficient for independent reproduction," not "sufficient for pixel-identical replication." Nobody is asking for floating-point determinism. They're asking: can another competent researcher, given the code, data, and environment description, get materially the same result?
[P2.2] That standard already exists in every wet-lab field. Chemists don't reproduce reaction yields to the fourth decimal; they reproduce the reaction. CON's [C1.2] objection dissolves once you stop attacking a rule nobody proposed.
[P2.3] The proprietary and privacy cases in [C1.3] cut against CON, not for it. If a paper cannot share enough - even synthetic surrogates, restricted-access enclaves, or documented sampling protocols - for anyone to check the claim, that is not evidence the rule is too strict. That is the system confessing the claim cannot be verified. CON wants journals to certify such claims as validated science anyway.
[P2.4] But an unverifiable claim isn't demoted from science to lower-tier science - it's demoted to assertion. Those groups can still publish white papers, preprints, and internal tech reports; they just don't get to wear peer-reviewed legitimacy while refusing the one thing that legitimacy is supposed to certify.
[P2.5] And [C1.4]'s "badges and encouragement" proposal is not a competing solution - it's the status quo PRO already indicted in Opening. Voluntary availability statements are exactly what produced audits showing majority non-compliance and years-later retractions. CON is asking the debate to re-adopt the mechanism that already failed, dressed up as moderation.
[P2.6] Weigh it plainly: CON's cost is some slower-moving papers redirected to less prestigious venues until they can meet a baseline. PRO's cost of the status quo is a literature quietly full of unverifiable claims, sometimes cited hundreds of times before anyone discovers the code never worked. That is not a fair trade.

## Turn 4: CON Rebuttal 1

- model: grok-4.5-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO now claims the proposition is only mild because it seeks “materially the same result” rather than bit-level identity. That still requires journals to refuse any paper whose authors cannot hand over code, data, and environment details—the gate the motion writes. Relabeling independent reconstruction from a transparent methods description as somehow inadequate merely reasserts the same demand.
[C2.2] The wet-lab analogy does not rescue them. Chemists publish procedures so others can re-create the reaction; they are not required to ship every intermediate, solvent batch, or instrument serial number. Computational research already has the direct analogue: algorithms, architectures, hyperparameter ranges, preprocessing, and ablation logic. Forcing artifact deposit is equivalent to demanding sealed vials with every synthesis paper.
[C2.3] When materials are scarce, proprietary, or regulated, journals still accept clear methods; computational work deserves the same standard rather than a higher packaging tax.
[C2.4] PRO’s treatment of privacy and proprietary cases is the giveaway. Declaring that unshareable claims get no peer-reviewed status simply locks out clinical models under privacy law, industrial systems on proprietary streams, and large-scale simulations that cannot ship petabytes or classified inputs. Surrogates and enclaves often change the scientific question itself. The outcome is not stronger verification; it is an emptier literature and results driven into unreviewed internal reports where scrutiny is weaker.
[C2.5] Voluntary badges are not magically the same as the failed status quo PRO describes. Journals can demand precise methods, availability statements with concrete plans, and post-publication correction without converting every computational submission into a mandatory software-release project that hits smaller labs hardest.
[C2.6] Weigh the real trade: PRO understates exclusion as “some redirected papers.” The rule removes whole categories of high-stakes work from the citable record. That cost exceeds any gain from one additional packaging gate when reimplementation, theory, and multi-team extension already supply the verification science requires. Absolute refusal is the wrong instrument.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 77
- clipped_words: 77
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If a paper's underlying data or code truly cannot be shared with anyone, on what basis should a journal certify its result as verified science rather than merely publish it as an unverified claim?
[P3.2] Q2: Under CON's "methods description" standard, if independent reviewers try to reimplement a result from the paper's methods alone and get a different number, who is presumed right - and how would anyone ever know, without the original code to check against?

## Turn 6: CON Pressure Questions

- model: grok-4.5-high
- raw_words: 67
- clipped_words: 67
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: When privacy laws or proprietary data make any true share of code/data impossible without rewriting the claim itself, does PRO permanently ban those clinical and industrial results from peer-reviewed journals, or quietly abandon the "refuse unless" rule?
[C3.2] Q2: Who decides after deposit whether the materials are "sufficient," and what stops later nondeterministic reimplementations from reopening endless post-publication fights over whether the paper ever met the gate?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 333
- clipped_words: 333
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.4]
- missing_claim_id_refs: (none)

[P4.1] A1: No blanket permanent ban - PRO's ask is that journals refuse the paper as *verified science* until authors share whatever can lawfully be shared: de-identified data, synthetic surrogates matching statistical structure, containerized pipelines run on dummy inputs, or code review under an NDA-protected reviewer. In the rare case where truly nothing - not code, not synthetic data, not a documented sampling protocol - can be shared, then yes, that result doesn't get certified as verified computational science. That's not banning the research; it's refusing to grant peer-reviewed legitimacy to a claim nobody but the authors can check.
[P4.2] CON's own [C2.4] concedes surrogates "often change the scientific question" - but a changed, checkable question beats an unchanged, unverifiable one every time.
[P4.3] A2: Exactly the same body that already decides whether a methods section meets disclosure standards: editors and reviewers, using the same checklists NeurIPS and Nature already run in practice. CON acts like this is a novel, unbounded discretion problem - it isn't. Editors already adjudicate "is this control condition adequate," "is this p-value hacked," "is this sample size disclosed." Nondeterministic reimplementations reopening fights is not a cost unique to PRO's rule - it's already happening right now, except today reviewers have no original artifact to check against at all.
[P4.4] My rule gives disputes a fixed reference point; CON's status quo gives them none.
[P4.5] Notice what both answers expose: CON has quietly retreated from "the rule is unworkable" to "the rule requires judgment calls," which is true of every editorial standard journals already enforce. That retreat is the debate. CON's opening promised systemic collapse; by Rebuttal 2 all that's left is "editors will sometimes have to decide if a surrogate dataset is good enough" - a governance detail, not a reason to keep certifying claims no one can check. Weigh it: PRO's rule costs some friction and case-by-case judgment.
[P4.6] CON's status quo costs a literature where "verified" and "unverifiable" are indistinguishable at the point of citation. That's the wrong trade to keep making.

## Turn 8: CON Rebuttal 2

- model: grok-4.5-high
- raw_words: 305
- clipped_words: 305
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Journals certify such results through transparent methods enabling independent reimplementation, peer scrutiny of logic and assumptions, and cumulative multi-team testing—not through deposit of raw materials. Hard-to-share clinical or industrial claims become science when the described process withstands reconstruction and subsequent studies; they do not become mere assertions just because privacy law or proprietary streams block raw shipping. Treating artifact deposit as the sole stamp of verification confuses packaging convenience with epistemic warrant.
[C4.2] A2: Neither party is automatically right. Discrepancies trigger ordinary scientific process: authors clarify, teams reimplement under tighter specs, alternatives accumulate, and communities converge. Original code is no permanent oracle—it can contain bugs, leakage, or unreported choices. Science settles numerical conflicts by multiple lines of evidence, not by freezing one package as referee forever.
[C4.3] PRO softens the rule into “share what you can,” yet the motion still refuses peer-reviewed status unless materials suffice for reproduction. When lawful share would rewrite the claim itself, PRO’s answer remains denial of certification—permanent lockout of clinical models, industrial systems, and large simulations under another name. That empties the citable record of high-stakes work and drives findings into unreviewed white papers where scrutiny is weaker.
[C4.4] Their claim that CON merely faces familiar editorial judgment misses the point. Methods review is textual and settles at acceptance; an elastic post-deposit “sufficient” gate reopens every paper indefinitely once nondeterminism or library drift appears. A surrogate that changes the scientific question does not verify the original claim—it substitutes another.
[C4.5] Weigh the live trade: PRO’s friction and case-by-case packaging demands buy only one narrow check while excluding whole research categories and converting journals into software auditors. CON keeps methods transparency, reimplementation, and multi-method verification without the absolute refusal tax. That comparison still favors CON: verification advances through cumulative reconstruction far more than through forced artifact deposits that many legitimate papers can never supply.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 219
- clipped_words: 219
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.2]
- missing_claim_id_refs: (none)

[P5.1] CON's whole defense collapses into one admission: in [C4.2], code "can contain bugs, leakage, or unreported choices." That's exactly right - and it's exactly why CON's system cannot catch them. A leaked test label, a silently-tuned hyperparameter, a spreadsheet indexing error - none of these show up in a methods section. They are invisible in prose by definition; they only surface when someone runs the actual artifact and the number breaks.
[P5.2] CON keeps insisting "reimplementation from methods" is verification, but reimplementation from a description can only ever check whether the description is internally coherent - it can never catch what the authors didn't know to describe. That is precisely the failure mode from my opening: entire benchmark literatures were corrected not through "cumulative reconstruction" but because someone finally got the code and found the leak.
[P5.3] CON's fallback - "editors already make judgment calls" - was supposed to prove the rule collapses into chaos. Instead it proved the opposite: journals already adjudicate contested standards every day, they just currently do it without the one document that would actually let them catch a hidden bug.
[P5.4] CON asks you to keep certifying claims using a method that structurally cannot detect the errors PRO identified as the norm, not the exception. That's not a lower verification cost - it's no verification at all.

## Turn 10: CON Closing

- model: grok-4.5-high
- raw_words: 158
- clipped_words: 158
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO insists only deposited artifacts can catch hidden bugs that methods miss. That measure fails. Code itself embeds leaks, silent tuning, and indexing errors; mere deposit guarantees no detection. Detection arrives when teams reconstruct, stress-test, and fail to converge—the cumulative process CON defends, the same process that already corrected the literatures PRO cites.
[C5.2] The absolute refusal gate still exacts its real price. When privacy law, proprietary streams, or scale make true sharing rewrite the claim, the paper is denied peer-reviewed status. That empties the citable record of clinical and industrial results that transparent methods could still expose to reimplementation and multi-team challenge. Surrogates that alter the question do not verify the original; they abandon it.
[C5.3] CON’s standard—full methods, concrete availability statements, ordinary post-publication correction—keeps verification where science already succeeds, without converting journals into software auditors that refuse otherwise valid work. Forced deposit is neither necessary nor sufficient; the refusal it requires permanently costs more knowledge than it salvages.
