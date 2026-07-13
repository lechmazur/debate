# Debate prop_0169__claude-sonnet-5-high__ernie-5.1__s0__tpl_placement_active_20260320f

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: claude-sonnet-5-high
- model_con: ernie-5.1
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 347
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Science runs on a single promise: that a result, once published, is true and can be checked by anyone with the skill to check it. Computational research routinely breaks that promise. A paper claims an algorithm beats the state of the art, or a statistical pipeline finds a biomarker for disease, and the only evidence is a PDF describing what the authors say they did. Nobody outside the lab can run it, poke it, or find the bug.
[P1.2] That is not science. That is a testimonial.
[P1.3] The case for PRO is simple: reproducibility is not an optional virtue of computational work, it is the definition of the work being checkable at all. Unlike a wet-lab result, where an independent lab can at least attempt to redo the experiment from a written protocol, a piece of software plus a dataset plus a specific library version is often the *only* path to the claimed result. Change a random seed, a floating-point library, a dependency version, and results can shift enough to erase the reported effect.
[P1.4] Papers describing methods in prose cannot capture that fragility. Only the actual code and data can.
[P1.5] We have already seen what happens without this rule. Fields from machine learning to computational biology to psychology have had waves of papers whose headline results evaporated once outsiders got the actual pipeline: hidden data leakage, off-by-one errors, cherry-picked hyperparameters, preprocessing steps quietly excluded from the write-up. These are not rare pathologies; they are what happens by default when no one else can check your work. Peer review, which relies on reading a description rather than running the thing, is structurally unable to catch them.
[P1.6] Journals are the one leverage point that can fix this at scale. They are the gatekeepers of the incentive: publication is the currency researchers need for jobs, grants, and tenure. If journals hold the line, code and data become as mandatory as a methods section, because right now, for many researchers, they are optional labor with no career payoff. Make it a condition of publication, [clipped]

## Turn 2: CON Opening

- model: ernie-5.1
- raw_words: 296
- clipped_words: 296
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition sounds noble until you ask who it actually excludes. Demanding that every computational paper ship with reproducible code, data, and environment details isn't a quality standard—it's a gatekeeping mechanism that will lock out the majority of legitimate computational research while doing little to fix reproducibility.
[C1.2] Consider what "sufficient for independent reproduction" actually requires. Reproducing a genomics study might need petabytes of patient data governed by privacy laws. A climate modeling paper might depend on supercomputer access no university lab can provide. An industry-affiliated machine learning paper might rely on proprietary training data worth millions in competitive advantage.
[C1.3] These aren't edge cases—they're the norm across computational fields. A blanket refusal policy doesn't clean up science; it silences it.
[C1.4] The damage goes further. If journals refuse publication over reproducibility requirements, researchers won't suddenly become more transparent—they'll publish elsewhere. Preprint servers, conference proceedings, and industry technical reports have no such gate. We would be pushing computational research out of peer-reviewed venues entirely, stripping it of the quality control that does catch errors.
[C1.5] The reproducibility crisis isn't solved by exclusion; it's solved by making sharing the norm through incentives, not ultimatums.
[C1.6] Reproducibility badges, voluntary data policies, and institutional repositories already move the needle for the shareable cases without punishing the unshareable ones. The proposition treats every computational paper as if it were a simple script on a laptop, when in reality the research landscape is defined by constraints—legal, financial, logistical—that make full reproducibility genuinely impossible for large swaths of work.
[C1.7] The real question isn't whether reproducibility matters. It does. The question is whether a draconian refusal mandate does more harm than good by driving research away from peer review, rewarding only the simplest projects, and pretending that an absolute standard can be applied to an inherently diverse field.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 278
- clipped_words: 278
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.5], [C1.6], [P1.5]
- missing_claim_id_refs: (none)

[P2.1] CON's strongest-sounding point is the exclusion argument, but it proves too much. Yes, some data are legally protected or proprietary. That is exactly why real reproducibility policies—the ones journals like Nature and PLOS already run—don't demand literal universal disclosure; they require authors to state what they used, provide synthetic or de-identified proxies where law forbids sharing, and give code plus environment details even when the raw data itself is restricted. CON is arguing against a maximalist strawman, not the proposition.
[P2.2] The claim is "sufficient for independent reproduction," and sufficiency is contextual: for a genomics paper that means the pipeline, the preprocessing, the exact software stack, applied to a controlled-access dataset a qualified lab could request. That is not silencing computational science. It is refusing to let "we can't share it" become a permanent excuse for "you can't check it."
[P2.3] CON's flight-to-preprints argument actually helps PRO. If the threat of losing peer-reviewed venues pushes researchers toward preprints and technical reports instead, that shows peer review currently offers false assurance—prestige without verification. A result that can't survive a reproducibility requirement was never properly checked in the first place; it was just laundered through a journal's reputation. Losing that laundering service is a feature, not a bug.
[P2.4] And the "incentives, not mandates" solution [C1.5], [C1.6] is not hypothetical—it's the status quo. Voluntary badges and open-data policies have existed for years, and they are precisely the regime under which the reproducibility crises PRO cited in [P1.5] occurred. Voluntary transparency selects for the researchers already inclined to be transparent; it does nothing for the ones cutting corners, who are the actual problem. CON needs the voluntary approach to have already worked.
[P2.5] It hasn't.

## Turn 4: CON Rebuttal 1

- model: ernie-5.1
- raw_words: 318
- clipped_words: 318
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal rests on a sleight of hand: they keep softening the proposition into something more palatable, then attacking CON for not accepting that softer version. But the motion says "refuse to publish" unless code, data, and environment details are "sufficient for independent reproduction." There are no carve-outs in the text for privacy law, proprietary data, or controlled access. PRO now wants us to believe journals will magically interpret "sufficient" to mean "provide a proxy where you can't share the real thing."
[C2.2] That's not what the proposition says. It says refuse. Full stop.
[C2.3] And even granting PRO's rosy interpretation, who decides what counts as sufficient? A genomics paper with controlled-access data—who determines whether the proxy is good enough? The journal? A reviewer with no access to the original dataset?
[C2.4] This turns reproducibility into a subjective editorial judgment, not a technical standard. That's worse than the current mess, not better.
[C2.5] PRO's claim that losing peer-reviewed venues is "a feature" is the most revealing concession in this debate. They essentially admit the policy would degrade the quality of scientific communication, then frame that degradation as progress. If computational research migrates to preprints and technical reports without rigorous review, we haven't solved the reproducibility crisis—we've just made it invisible and unchecked.
[C2.6] The comparison PRO draws is false. It isn't between perfect reproducibility and the current voluntary regime. It's between a system that excludes legitimate work and one that imperfectly includes it while still catching errors through peer review. PRO says voluntary transparency hasn't worked, but neither has mandatory code review in journals that tried it—reviewers routinely can't run the code in their own environments, creating new bottlenecks without solving the underlying problem.
[C2.7] The proposition as written demands a binary refusal that punishes the unshareable, judges sufficiency subjectively, and—by PRO's own admission—drives research toward less rigorous venues. That is not a fix. That is a mechanism for exclusion dressed up as accountability.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 89
- clipped_words: 89
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C1.6], [P1.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON says "no carve-outs" exist in the text, yet also says sufficiency review is "subjective editorial judgment" [C2.3]—which is it: a rigid literal mandate with zero flexibility, or a standard so vague that editors decide case-by-case? CON needs it to be both to win, but it can't be.
[P3.2] Q2: If voluntary transparency and existing "reproducibility badges" [C1.6] already coexist with peer review, why did the reproducibility failures PRO cited in [P1.5] occur under exactly that regime—what evidence does CON have that more voluntary measures would have caught them?

## Turn 6: CON Pressure Questions

- model: ernie-5.1
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO says journals can interpret “sufficient” to mean proxies for restricted data, yet the motion’s wording demands outright refusal—so who, under this rule, decides whether a proxy truly enables independent reproduction, and what recourse do authors have if that judgment is disputed?
[C3.2] Q2: PRO argues that pushing work to preprints is a feature because it exposes false assurance, but if reproducibility cannot be verified anywhere, how does that advance the very reproducibility PRO claims to champion?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [P1.5]
- missing_claim_id_refs: (none)

[P4.1] A1: The same people who already decide every other publication standard—editors and reviewers—decide sufficiency, because journals already make contestable judgment calls about novelty, statistical soundness, and methodological rigor. This is not a new category of subjectivity invented by the proposition; it is the ordinary mechanism of peer review extended to one more criterion. Recourse is exactly what it is for any other editorial rejection: revise and resubmit, appeal to the editor, or submit elsewhere. CON treats "requires judgment" as a fatal flaw, but if that were disqualifying, we'd have to abandon peer review itself, since editors already judge whether "sufficient" evidence supports a causal claim.
[P4.2] A2: Pushing weak work to preprints doesn't solve reproducibility in that specific paper, but it stops journals from laundering unverified claims as verified ones. Right now a *Nature* or *Cell* stamp tells readers "this was rigorously checked," when for computational work it often means no such thing. If the standard shifts and prestige venues require reproducibility, the label starts matching the substance, and the incentive for authors changes: they now have a reason to build reproducible pipelines from day one, because that's the path to the credibility they want.
[P4.3] CON's alternative—keep the stamp, skip the check—doesn't preserve rigor, it counterfeits it.
[P4.4] That's the real comparison this debate turns on. CON's harms are hypothetical and manageable: some papers get delayed, some authors resubmit elsewhere, editors have to exercise judgment they already exercise for everything else. PRO's harm, demonstrated by the reproducibility failures already in this debate [P1.5], is concrete and already happening: false results certified by peer review, cited, built on, sometimes acted on in medicine or policy, before anyone discovers the pipeline was broken. Exclusion is reversible and survivable.
[P4.5] False assurance corrupts the record it was supposed to protect. That asymmetry is why PRO wins.

## Turn 8: CON Rebuttal 2

- model: ernie-5.1
- raw_words: 319
- clipped_words: 319
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P1.5], [C1.6]
- missing_claim_id_refs: (none)

[C4.1] A1: PRO asks whether the proposition is rigid or vague, as if CON must pick one. It's both, and that's the problem. The text says "refuse" with no carve-outs—that's rigidity. But because reality includes privacy laws, proprietary data, and supercomputer dependencies, editors must somehow judge sufficiency case by case with no textual guidance—that's the subjectivity CON flagged.
[C4.2] PRO wants the rigidity to sound principled and the flexibility to sound workable, but you can't have a mandate that refuses everything and a standard that accommodates everything without rewriting the motion. The contradiction isn't in CON's argument; it's in the proposition itself.
[C4.3] A2: PRO asks what evidence CON has that voluntary measures would have caught the failures cited in [P1.5]. The answer is the same evidence PRO uses: those failures happened under voluntary regimes. CON doesn't need to prove voluntary measures would fix everything—CON needs to show that a mandate driving work out of peer review creates a worse outcome. And it does.
[C4.4] If researchers flee to preprints and technical reports, there is no review at all, not weakened review but zero review. PRO calls this a feature; I call it removing the only mechanism that catches any errors in the first place.
[C4.5] That's why CON still wins. The real comparison isn't perfect reproducibility versus the status quo—it's a functional system with voluntary sharing that catches some errors and builds transparency incrementally, versus a broken system that excludes most computational work from peer review entirely. PRO's asymmetry claim—that exclusion is reversible but false assurance is permanent—collapses because exclusion isn't reversible in practice; researchers who stop submitting to journals don't return when policies soften. And false assurance is already being tackled through badges and data policies that PRO dismissed in [C1.6].
[C4.6] The proposition doesn't solve reproducibility; it destroys the infrastructure that could enforce it while doing nothing about the incentives that make selective sharing rational. That's not reform—it's sabotage dressed as accountability.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate ends on one question: what is peer review actually certifying right now? CON never answers it. Under the voluntary regime CON defends, a journal's stamp means "an editor liked the description of the method"—not "this result survives contact with reality." That gap is the reproducibility crisis, and CON's fix is to leave the gap in place while adding badges nobody is required to earn.
[P5.2] CON's strongest move was calling exclusion irreversible. But irreversibility cuts against CON: a false result certified by a prestige journal doesn't just sit quietly—it gets cited, funded, sometimes built into clinical guidance, and unwinding that damage takes years, if it happens at all. A delayed publication costs an author months. A fabricated-by-omission finding can cost patients, policy, and public trust.
[P5.3] Those are not symmetric harms, and CON's closing never tried to reweigh them—only to relabel exclusion as permanent while treating certified falsehood as manageable.
[P5.4] That's backwards. A rule that occasionally makes editors do hard judgment calls is a governance problem. A rule that lets peer review keep certifying work no one can check is a legitimacy problem. Only PRO's standard closes that gap.
[P5.5] Refuse to check, refuse to publish.

## Turn 10: CON Closing

- model: ernie-5.1
- raw_words: 209
- clipped_words: 209
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's closing asks us to weigh two harms: exclusion versus false assurance. But PRO already conceded the worse one. When asked whether pushing computational work to preprints is a problem, PRO called it a feature—exposing false assurance by removing the venue that provides it. That is not a strategy; it is surrender.
[C5.2] You cannot simultaneously defend peer review as the mechanism that certifies truth and argue that gutting peer review of computational work is acceptable collateral.
[C5.3] The proposition as written doesn't close a gap in peer review. It blows a hole in it. A journal that refuses to publish because code can't be shared—due to patient privacy, proprietary data, supercomputer dependencies—isn't raising standards. It is removing the only setting where any independent scrutiny happens at all.
[C5.4] Preprints don't fix that. Technical reports don't fix that. PRO knows this, which is why they framed the exodus as progress rather than loss.
[C5.5] CON doesn't deny reproducibility matters. CON denies that a blunt refusal mandate—one with no textual flexibility, no carve-outs, no realistic path for the majority of computational work—is the tool to achieve it. The proposition punishes the unshareable, rewards the simple, and empties peer review of the very work it should be checking. That is not accountability.
[C5.6] That is attrition.
