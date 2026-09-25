# Debate prop_0628__claude-opus-5-high__claude-opus-5-5-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0628
- proposition: Governments should require frontier AI model developers to complete and publish standardized pre-deployment safety evaluations, with penalties for noncompliance.
- model_pro: claude-opus-5-high
- model_con: claude-opus-5-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: claude-opus-5-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Right now, the most powerful AI systems in the world are graded by their own makers, on tests the makers design, with results the makers choose whether to publish. If a pharmaceutical company did that, we would call it fraud. In AI, we call it a system card.
[P1.2] The core problem is not that frontier labs are evil. It is that they are racing. A lab that discovers a worrying capability two weeks before launch faces a brutal choice: delay and watch a competitor take the market, or ship and describe the finding in soft language. Voluntary commitments do nothing about this, because the moment safety becomes costly is exactly the moment voluntary commitments stop binding.
[P1.3] That is the whole reason we do not let airlines self-certify their own aircraft, or let banks audit their own books. Penalties are not an insult to good-faith developers; they are what makes a good-faith developer's promise credible to everyone else, and what protects the responsible lab from being undercut by the reckless one.
[P1.4] Standardization matters just as much as disclosure. Today each lab picks its own benchmarks, its own thresholds, its own definitions of "dangerous capability," which makes the published results genuinely incomparable. Nobody outside can tell whether Model A is safer than Model B, or whether a lab quietly loosened its criteria between releases. A common evaluation floor—cyber-offense uplift, bio-relevant capability, autonomous replication, deception under testing—turns marketing into evidence.
[P1.5] Publication then lets outside researchers, insurers, downstream deployers, and hospitals and utilities deciding what to plug in actually price the risk.
[P1.6] Note how narrow this is. It binds a handful of firms training the largest models, all of whom already run these evaluations internally and already employ safety teams. The obligation is to do the work honestly and show the homework. If a company cannot survive disclosing what its own tests found, that is not a compliance burden.
[P1.7] That is the finding.

## Turn 2: CON Opening

- model: claude-opus-5-5-high
- raw_words: 351
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9], [C1.10]
- cited_claim_ids: [P1.1], [P1.6]
- missing_claim_id_refs: (none)

[C1.1] The proposition promises to turn marketing into evidence. It will turn evidence into compliance theater, and it will make the most dangerous findings public.
[C1.2] Start with the science. We do not yet know how to reliably measure what frontier models can do. Evaluations for bio-uplift, deception, or autonomous replication are research projects, not settled instruments. A model can fail a test because of a prompting quirk and pass it after a minor fine-tune.
[C1.3] The pharmaceutical analogy in [P1.1] actually cuts against PRO. Drug regulators can standardize because they have validated endpoints built over decades: blood pressure, tumor size, mortality. AI has nothing comparable. Standardize now and you freeze today's immature tests into law.
[C1.4] That freeze creates the second problem: teaching to the test. Once a fixed battery determines legal compliance, labs optimize for that battery. Models get tuned to look clean on the published checklist, while the capabilities nobody thought to standardize go unmeasured. The public sees a green scorecard and concludes the model is safe.
[C1.5] That is worse than no scorecard, because it is false assurance carrying a government seal.
[C1.6] Third, penalties change what labs want to find. PRO says in [P1.6], "If a company cannot survive disclosing what its own tests found..." Exactly. Tie legal liability to published findings, and every finding becomes a liability.
[C1.7] Lawyers enter the red-teaming room. Exploratory probing shrinks to the mandated minimum, because looking harder only creates discoverable evidence. You get the airline paperwork without the airline safety culture.
[C1.8] Fourth, publication itself is dangerous. A standardized, public report on cyber-offense or bioweapon uplift tells attackers which model to target and which capabilities to extract. Detailed dangerous-capability results belong with security-cleared evaluators, not on a website.
[C1.9] Finally, "a handful of firms" writing to "a common floor" is a recipe for capture. The incumbents who can afford compliance teams will shape the standard, lock it in, and wall out challengers, including open researchers.
[C1.10] The real choice is not oversight versus none. It is brittle, public, penalty-driven checklists versus adaptive, confidential scrutiny that can evolve as [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.7], [C1.8], [C1.9]
- missing_claim_id_refs: (none)

[P2.1] Every one of CON's objections is an objection to the status quo, dressed up as an objection to me.
[P2.2] Take the science point [C1.2]. If bio-uplift and deception evals are immature research projects, then right now the most powerful systems on earth are being cleared for release using immature research projects, run in private, reported selectively, by the party with the strongest incentive to like the answer. The tools are the same tools. The only question is whether anyone outside the building gets to see the results and check the methodology.
[P2.3] Immaturity is an argument for external scrutiny, not against it.
[P2.4] And the pharma point cuts my way [C1.3]. Validated endpoints did not fall from the sky and then summon a regulator. Regulators created the demand that built them. Nobody standardized tumor measurement as a hobby.
[P2.5] A published floor is exactly what turns eval science from a scattered in-house craft into a field with replication, criticism, and careers.
[P2.6] On freezing and teaching to the test [C1.4]: a floor is not a ceiling. Labs publish the mandated battery *and* their own additional probing — and unlike today, quietly loosening your thresholds between releases becomes misrepresentation rather than a footnote nobody can audit. Gaming happens now, on benchmarks labs choose themselves, with zero penalty. My regime at least makes the gaming visible and actionable.
[P2.7] The chilling argument [C1.7] assumes the aggressive exploratory red-teaming exists and would be lost. We cannot know that, because we cannot see it. Liability attaches to failing to test and failing to disclose — not to finding something.
[P2.8] Infohazards [C1.8] are a formatting problem, not a defeater. Publish scores, thresholds, methodology; withhold prompts, weights, and exploit artifacts. A hospital deciding what to plug into its systems needs the score. It does not need the payload.
[P2.9] Then capture [C1.9]. CON's alternative is confidential, discretionary, lab-influenced evaluation with no penalty for ignoring it. That *is* capture — it just doesn't have a filing deadline.
[P2.10] Strip the adjectives off "adaptive confidential scrutiny" and you get today. Today is what we are [clipped]

## Turn 4: CON Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 362
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9], [C2.10]
- cited_claim_ids: [P2.2], [P2.4], [P2.6], [P1.2], [P2.7], [P2.8], [P2.9]
- missing_claim_id_refs: (none)

[C2.1] The central claim, "Strip the adjectives off 'adaptive confidential scrutiny' and you get today," is false, and the rest of PRO's case depends on it. My alternative is not labs grading themselves. It is government evaluators with compulsory pre-deployment access, free to change their tests every quarter and reporting to regulators rather than to a website. That is external scrutiny.
[C2.2] It lacks exactly the three features this motion adds: frozen standards, public scores, and penalties pinned to both.
[C2.3] Take PRO's concession: evals are immature [P2.2]. Then the question is who should see immature results. Expert reviewers can discount a noisy bio-uplift score. The public, the press and plaintiffs' lawyers cannot.
[C2.4] Even PRO's pharma story shows this [P2.4]. Endpoints matured because regulators saw raw trial data first and iterated privately for decades. They did not publish a standardized scorecard on day one and fine anyone who missed it.
[C2.5] "A floor is not a ceiling" [P2.6] collapses under PRO's own opening. [P1.2] says voluntary commitments evaporate "the moment safety becomes costly." So the extra probing PRO promises, which is voluntary, disappears at crunch time. What survives is the mandated, published, penalized floor, and that is where optimization concentrates.
[C2.6] PRO's logic shows the checklist becomes the ceiling.
[C2.7] On chilling [P2.7], PRO says liability attaches to "failing to disclose," not to finding. But the duty to disclose everything you find is precisely why you stop looking past the required battery. Every extra probe becomes a mandatory public confession and future exhibit in a lawsuit.
[C2.8] On infohazards [P2.8], the score is the payload. A public line reading "Model X: high cyber-offense uplift" tells every attacker which system to jailbreak. And the hospital does not need a bioweapon score. It needs reliability data, which requires no penalty regime.
[C2.9] On capture [P2.9], standards written in public by incumbents with compliance departments are still captured. A formal standard, once written into law, is also far harder to revise.
[C2.10] So weigh the two models. PRO offers false assurance with a government seal, a targeting guide for attackers, and a [clipped]

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-high
- raw_words: 107
- clipped_words: 107
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your counterplan rests on "compulsory pre-deployment access" [C2.1]. Compulsory how — what actually happens to a lab that refuses access, stalls, or hands over doctored results? If your answer is a penalty, you have conceded the enforcement half of the motion and we are only arguing about publication.
[P3.2] Q2: Under confidential-only reporting, name the mechanism by which anyone outside the building — an insurer, a hospital, a journalist, an academic — ever learns that the regulator's clearance was wrong. And if none exists, which is the more dangerous false assurance: a published score that critics can attack, or a government approval nobody is permitted to inspect?

## Turn 6: CON Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: When a lab's voluntary probing, beyond your mandated floor, uncovers a dangerous capability, is it legally required to publish that finding? If yes, you have made every extra probe a public confession that labs will avoid. If no, the penalized checklist is the only thing guaranteed to survive, and your floor becomes the ceiling.
[C3.2] Q2: How often does your standardized battery change? If rarely, labs tune models to pass a known test. If constantly, your promised comparability between Model A and Model B [P1.4] disappears.

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-high
- raw_words: 343
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C2.1], [C2.10]
- missing_claim_id_refs: (none)

[P4.1] A1: Yes — and that duty is precisely what prevents your trap. The rule is not "publish every log." It is: publish the standard battery in full, and disclose any capability you discover that crosses a defined severity threshold, however you found it. Disclosure keyed to *severity*, not to volume of probing.
[P4.2] Crucially, you cannot escape by not looking, because reckless failure to test is itself a violation — the same way a manufacturer cannot defend itself by proving it never inspected. So the incentive is not "probe less"; it is "find it before an outsider does, when disclosing it is cheap." And notice: your counterplan has the identical structure. Compulsory reporting to a regulator is also a confession.
[P4.3] Either your regime punishes concealment — in which case the chilling argument applies to you too — or it doesn't, and labs simply decline to hand over the bad news.
[P4.4] A2: A stable core plus a rotating, partly held-out component. The core gives you comparability across Model A and Model B; the rotating portion is what you cannot train against, because you haven't seen it. This is not exotic — it is how auditing works. Accounting standards are stable; which accounts get sampled this year is not.
[P4.5] Volkswagen's defeat device wasn't a failure of having emissions standards; it was a failure of never testing off the known cycle. The fix was unpredictable testing, not abandoning the standard.
[P4.6] So strip this debate down. CON now concedes external evaluators, compulsory access, and pre-deployment review [C2.1]. The remaining disagreement is one thing: whether the public gets to see the result.
[P4.7] And on that single question, CON's position is self-defeating. Their strongest argument is "false assurance with a government seal" [C2.10] — yet their counterplan *is* a government seal, issued privately, using the same immature evals, with no outsider ever able to check the reasoning. A published score can be attacked by a graduate student. A confidential clearance can only be attacked by whoever leaks it.
[P4.8] Secrecy does not make immature science mature. Publication is [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 358
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.6], [P4.5], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: A lab that refuses access, stalls, or doctors results faces sanctions for obstruction and fraud. That concedes enforcement, but not the motion. The motion enforces a specific package: a standardized battery, completed and published, with penalties attached to that package. I oppose what gets enforced, not whether anything is.
[C4.2] Punishing a lab for lying to an evaluator is ordinary law. Fining it for not posting a frozen scorecard is this motion. PRO says the fight has narrowed to publication [P4.6]. I accept that, because publication is where their case breaks.
[C4.3] A2: Outsiders learn a clearance was wrong the way they always have: deployment itself. Once a model ships, independent researchers, insurers, and journalists probe it directly. Add whistleblower protections, legislative oversight, published methodology, and delayed release of model-specific results once mitigations are in place. PRO's own Volkswagen example proves the point [P4.5].
[C4.4] The cheating was exposed by off-cycle testing, not by reading the official scorecard. A published standardized score is exactly the known cycle a lab can tune toward. PRO's fix, a rotating held-out component, concedes that the standardized core is gameable, and a held-out test cannot be published in advance anyway.
[C4.5] So which false assurance is worse? The public one. A confidential clearance does not advertise itself as a safety rating to hospitals and consumers. A government-mandated public score does, and every attacker reads it too.
[C4.6] Now the answer that decides the round. PRO claims my regime has an "identical structure" because reporting to a regulator is also a confession [P4.2]. It is not identical. A confidential report of a severe capability costs a lab a delayed launch.
[C4.7] A public disclosure costs it a headline, a lawsuit exhibit, and a published targeting map for attackers. That difference in cost is the whole chilling argument. PRO's promise to "find it before an outsider does, when disclosing it is cheap" fails because public disclosure of a severe finding is never cheap.
[C4.8] Both sides now agree on external, compulsory, pre-deployment scrutiny. The only thing PRO adds is the publication requirement, and [clipped]

## Turn 9: PRO Closing

- model: claude-opus-5-high
- raw_words: 193
- clipped_words: 193
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Both sides now stand in the same place: external evaluators, compulsory pre-deployment access, penalties for obstruction. CON has conceded the architecture and kept only one objection — don't let the public see the result.
[P5.2] So decide the round on that.
[P5.3] CON's final argument is that public disclosure costs a lab "a headline, a lawsuit exhibit." That cost *is* the mechanism. A private regulator's frown is a cost a racing lab can absorb and litigate quietly. A published finding is the only consequence that reaches the people actually exposed — the hospital, the insurer, the utility deciding what to wire into its systems.
[P5.4] CON asks them to accept a clearance they are not permitted to inspect, produced by tests CON himself calls immature research projects.
[P5.5] That is the asymmetry that decides this. Under my regime, if the evaluation is wrong, a graduate student can say so before deployment. Under CON's, the error surfaces after the model ships — his own answer was "deployment itself."
[P5.6] One regulator, one blind spot, no second reader, and the first outside check happens after release. Immature science cannot be corrected in a sealed room.
[P5.7] Make them show the homework.

## Turn 10: CON Closing

- model: claude-opus-5-5-high
- raw_words: 207
- clipped_words: 207
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6], [C5.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's closing handed me the round in one sentence: the headline and the lawsuit exhibit are "the mechanism." Exactly. That is a punishment triggered by discovering danger. Any system that makes finding a severe capability expensive will produce fewer findings.
[C5.2] Not fewer dangers. Fewer findings.
[C5.3] So weigh what each side protects. My regime protects the discovery itself. A lab that uncovers bio-uplift reports it to cleared evaluators, eats a delayed launch, and fixes it. Finding the danger is survivable, so labs keep looking.
[C5.4] PRO's regime turns that same finding into a public confession, a litigation exhibit, and a line telling every attacker which model to jailbreak. The rational lab runs the mandated battery, tunes to it, and stops there.
[C5.5] And PRO's graduate student? He reads the published score, not the model. He can critique a number produced by the standardized core that PRO admitted is gameable. PRO's own Volkswagen story makes the point: the scandal broke off the official cycle, not by reading the scorecard.
[C5.6] So the hospital PRO keeps invoking gets a government-mandated green light built on the tests labs learned to pass, while the evidence that mattered never gets generated.
[C5.7] Show-your-homework sounds like accountability. Penalizing the homework teaches students to stop doing it. Vote CON.
