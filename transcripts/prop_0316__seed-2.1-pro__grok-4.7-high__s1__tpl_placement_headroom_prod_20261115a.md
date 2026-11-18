# Debate prop_0316__seed-2.1-pro__grok-4.7-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0316
- proposition: Users should have a right to know when a dating app uses AI to rank their profile or shape who gets shown to them.
- model_pro: seed-2.1-pro
- model_con: grok-4.7-high
- side_swap: True

## Turn 1: PRO Opening

- model: seed-2.1-pro
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When people use dating apps, they are entrusting platforms to mediate access to one of the most high-stakes, intimate choices they will ever make: who they meet, date, and potentially build a life with. Unlike algorithmic curation for entertainment or shopping, these outcomes carry tangible, life-altering weight: long-term partnership, financial security, and family formation. A right to know when AI ranks their profile or shapes who is shown to them is not an unreasonable demand for technical granularity—it is the bare minimum for informed consent, fair treatment, and basic autonomy over that process.
[P1.2] Right now, these AI systems can silently demote a profile for arbitrary, biased, or profit-driven reasons a user would never guess: penalizing single parents, people with visible disabilities, or users the algorithm judges are less likely to pay for premium visibility boosts, while giving users no signal that their reach is being artificially limited. If a user believes their matches are determined by mutual stated preferences and basic proximity, but an AI is instead curating their pool to push paid features or enforce unstated, training-data-driven beauty norms, they cannot make meaningful choices about how to present themselves, whether to pay for the service, or if the platform is worth using at all.
[P1.3] This disclosure does not require platforms to surrender trade secrets or reveal proprietary model weights. It only requires clear, upfront notice that AI is making those core ranking and curation decisions—a trivial administrative burden, fundamentally justified by the enormous sensitivity of the choices at stake. Without that basic notice, users are flying blind, unable to distinguish their own choices on the app from invisible system choices that structure every match they see. Users do not surrender their right to fair dealing just because they seek connection online.

## Turn 2: CON Opening

- model: grok-4.7-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A right to know when dating apps use AI to rank profiles sounds like informed consent. It is not. It is a notice obligation aimed at a technology label rather than at any conduct that actually harms users. Almost every dating service already sorts, filters, and suggests people by software.
[C1.2] Distance, stated preferences, response rates, and learned compatibility scores are the product. Telling users that "AI" participates does not reveal a hidden fact; it restates how the category works. Once that notice is universal, it informs no one.
[C1.3] The proposed right also fails the test its own supporters set. If the injury is biased demotion of single parents or disabled users, or paywalled visibility, a banner saying an algorithm is involved neither identifies the bias nor stops it. Users still cannot tell whether their pool was shaped by their filters, by other people's preferences, or by a revenue model. A right that withholds the only details that would matter, on the ground that weights and trade secrets stay secret, leaves autonomy exactly where it was: dependent on trust, reputation, and the choice to leave.
[C1.4] Worse, the right is unadministerable at the boundary that matters. Is a distance sort artificial intelligence? Is a hand-tuned popularity boost? Is collaborative filtering?
[C1.5] Law that turns on "when AI is used" invites either blanket boilerplate or endless disputes over model taxonomy. Compliance costs land on smaller apps first, while large platforms absorb a checkbox. Users gain no new lever over who they meet.
[C1.6] Existing tools already fit the real harms. Deceptive claims that matches are purely mutual and local can be policed as misrepresentation. Discrimination can be challenged as discrimination. What should not be created is a freestanding disclosure right whose only reliable output is a warning everyone has already learned to ignore.

## Turn 3: PRO Rebuttal 1

- model: seed-2.1-pro
- raw_words: 294
- clipped_words: 294
- claim_ids: [P2.1], [P2.2], [P2.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The claim that AI notice is a meaningless label because all dating apps use software collapses a critical distinction users already care about: fixed, transparent sorting by the criteria users explicitly set—distance, age range, stated interests—versus opaque, adaptive AI ranking that optimizes for hidden metrics like predicted willingness to pay for boosts, training-data-tethered beauty scores, or raw engagement time that has nothing to do with mutual compatibility. Right now, most users reasonably assume their match pool is shaped by those obvious, declared filters, not a learned model quietly demoting them for reasons they would never anticipate.
[P2.2] That is not universal knowledge; it is the exact information gap this right closes. The argument that a standalone notice does not single-handedly fix bias or pay-to-play throttling sets up a straw man. Notice is not the full remedy—it is the necessary precondition for every remedy critics claim already works. You cannot police deceptive misrepresentation about how matches are generated, or challenge discriminatory demotion of disabled users or single parents, if you have no idea an AI system is even making those ranking decisions in the first place.
[P2.3] A user who blames their dry spell on bad photos or bad luck will never look for, let alone prove, platform misconduct. The definitional objection is equally weak. The rule does not require litigating textbook AI taxonomies: it applies whenever adaptive, data-trained systems, rather than fixed, user-visible sort rules, shape profile ranking or match pools. That is a line every platform can already identify for its own engineering teams, requiring no more work than the standard privacy disclosures every app already posts, imposing no crushing burden on small apps while giving users the basic truth they need to decide if a platform is worthy of their time, money, and trust.

## Turn 4: CON Rebuttal 1

- model: grok-4.7-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [P2.2], [P2.3]
- missing_claim_id_refs: (none)

[C2.1] The line in [P2.1] is not a distinction an AI label can deliver. Ranking is one pass: stated age and distance sit beside response rates, mutual interest, and learned scores. Stamp the adaptive slice "AI" and you have named a method, not an objective. Compatibility, time-on-app, and willingness to pay can share that model.
[C2.2] "AI shapes who is shown" does not say which. That is the injury [P2.1] names, and this right withholds it. Autonomy here means a reason to stay, pay, or leave. A technology adjective supplies none.
[C2.3] [P2.2] inflates the label into a precondition for every remedy. It is not. Discrimination law asks who was demoted and on what protected basis, not whether the scorer was a neural net or a weighted formula. Misrepresentation law asks what the app promised.
[C2.4] A user who believes matches are purely mutual and local already has a deception claim; a user handed an AI banner still cannot prove disability bias, paywalled throttling, or a beauty penalty. Notice does not unlock enforcement. It gives platforms a compliance costume while the conduct stays opaque. Those examples, single parents and disabled users quietly demoted, remain invisible after the banner goes up.
[C2.5] A dry spell blamed on bad photos is not cured by learning the software's name.
[C2.6] The boundary in [P2.3] fails at the first hybrid. Reweight distance by a learned popularity score, or place a vendor recommender behind an age gate, and "fixed, user-visible" versus "adaptive, data-trained" is a brief, not a line. Privacy notices earn their keep by describing practices people can act on. This one describes a technique and stops.
[C2.7] If the harms are hidden pay pressure and biased demotion, demand the material factors and police the bias. Do not mint a right whose only reliable product is a warning that computation occurred.

## Turn 5: PRO Pressure Questions

- model: seed-2.1-pro
- raw_words: 58
- clipped_words: 58
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If users are never told adaptive, data-trained AI shapes their match pool, how can they ever meaningfully spot when a platform breaks its promises about mutual, preference-based matching?
[P3.2] Q2: You claim AI notice will become useless boilerplate, but why is this disclosure any less administrable than the standard privacy and pricing disclosures dating apps already routinely provide?

## Turn 6: CON Pressure Questions

- model: grok-4.7-high
- raw_words: 64
- clipped_words: 64
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: If a lawful notice may say only that AI ranks profiles, while pay pressure, beauty scores, and disability demotion stay secret, which broken promise about mutual matching can a user newly prove?
[C3.2] Q2: When a user-set distance filter is reweighted by a learned score, does [P2.3] trigger the duty, and if nearly every app already does this, what does the notice still distinguish?

## Turn 7: PRO Rebuttal 2

- model: seed-2.1-pro
- raw_words: 294
- clipped_words: 294
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: A user can newly prove that a platform’s marketing of matches as driven by mutual stated preferences and proximity is materially misleading, because they now know a hidden adaptive system is operating instead of the transparent, user-controlled filters they were sold. That baseline notice shifts the burden to platforms to stop hiding behind vague claims of “curated connection,” gives users a concrete trigger to report inconsistencies to regulators, and lets them choose competing services that stick to declared sorting rules instead of hidden optimization targets.
[P4.2] Notice does not need to prove every specific instance of bias or pay-to-play throttling on its own to be valuable; it only needs to tell users the game they are playing is not the one they were told they joined.
[P4.3] A2: Yes, that hybrid distance filter reweighted by learned scores triggers the duty, and that is a feature, not a bug. The fact that nearly every major app now blends in those learned reweightings is exactly why notice is necessary: users currently assume the distance slider they drag does what it says, not that it is quietly warped by popularity scores or pay-to-win metrics the app never acknowledges. The line is simple to apply: if a data-trained, adaptive component adjusts ranking or pool composition beyond the exact parameters the user explicitly set, disclosure applies.
[P4.4] This is no more unworkable than the existing privacy and pricing disclosures apps already provide, and it requires no release of proprietary model weights or trade secrets. CON’s preferred world of no notice leaves users flying blind, unable to even suspect misconduct until harm is already severe and nearly impossible to document. A trivial, one-sentence upfront notice is the bare minimum of respect owed to people navigating one of life’s most high-stakes, intimate choices.

## Turn 8: CON Rebuttal 2

- model: grok-4.7-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Users spot a broken promise about mutual, preference-based matching by testing the claim against the service they receive, not by learning the software's family name. Reviews, support tickets, and regulators already compare advertised "mutual and local" matching to paywalls, hidden boosts, and unexplained demotions. An AI notice adds no new fact about whether stated preferences were honored. A platform can run adaptive models that implement those preferences, or fixed rules that ignore them.
[C4.2] The banner cannot tell which, so it does not newly arm anyone to prove deception.
[C4.3] A2: Privacy and pricing notices work because they state verifiable practices and prices: data sold to advertisers, the cost of a boost. This duty hinges on a contested call—whether a learned score adjusts beyond user-set parameters—then demands only that computation occurred. Hybrids turn that call into a legal brief. Once nearly every app triggers it, the notice is boilerplate, while privacy notices still separate practices and prices still vary.
[C4.4] Those answers show why the right still fails. [P4.1] calls the banner proof that "mutual preferences" marketing is misleading, yet a notice that AI ranks profiles says nothing about objectives and does not contradict a promise that preferences matter. Users cannot newly prove disability demotion, beauty penalties, or pay pressure—the harms that were said to justify disclosure. A report trigger without a probative fact is not enforcement.
[C4.5] And if [P4.3]'s hybrid triggers on nearly every app, the notice distinguishes no competitor that "sticks to declared rules." Misrepresentation law already covers a false claim of purely mutual, local matching. Discrimination law already covers protected demotion whether the scorer is a net or a formula. The right adds only a warning everyone skips and a checkbox large platforms absorb.
[C4.6] Intimacy does not license a disclosure that withholds every material factor.

## Turn 9: PRO Closing

- model: seed-2.1-pro
- raw_words: 185
- clipped_words: 185
- claim_ids: [P5.1], [P5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate turns on one dispositive point: meaningful choice in a high-stakes, deeply intimate domain requires knowing when the basic rules of the platform are not what a reasonable user assumes when they first sign up. CON repeatedly argues an AI notice does not expose every specific bias, paywall incentive, or rigid beauty score embedded in the model, but that sets an impossible, unfair standard for any disclosure rule. No single notice can uncover and remedy every harm a system might cause, but it corrects the foundational misimpression most users hold: that their match pool is governed by the explicit sliders and stated preferences they set themselves, rather than an adaptive, data-trained system optimizing for hidden, unstated metrics the platform never names.
[P5.2] Without that baseline knowledge, users cannot even ask the right questions about unfair demotion, deceptive marketing, or misaligned incentives, let alone pursue the existing consumer protection and legal remedies CON claims are sufficient. A one-sentence, low-burden notice is not a full solution to every dating app harm—it is the non-negotiable floor of honest dealing owed to people vulnerable as they seek meaningful connection.

## Turn 10: CON Closing

- model: grok-4.7-high
- raw_words: 196
- clipped_words: 196
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C5.1] The proposition loses on one comparison: the right names a technique and withholds every fact a user could act on. Knowing that AI ranks profiles does not reveal whether stated preferences were honored, whether reach was sold, or whether someone was demoted for disability or family status. The banner leaves those injuries opaque.
[C5.2] That label is not proof of misleading marketing, despite [P4.1]. Adaptive models can implement mutual preferences. Fixed rules can ignore them. The notice cannot say which, so it proves no broken promise and arms no regulator.
[C5.3] Users still cannot document pay pressure or biased demotion. They can only recite that computation occurred.
[C5.4] [P4.3] admits the duty fires whenever a learned score touches ranking, and nearly every app already does that. The notice then separates no honest competitor. Privacy notices still distinguish practices. Prices still vary.
[C5.5] This warning becomes a sentence users skip. Misrepresentation law already polices a false claim of purely mutual, local matching. Discrimination law already reaches protected demotion whether the scorer is a net or a formula. Intimacy raises the cost of those harms.
[C5.6] It does not justify a checkbox large platforms absorb while withholding every material factor. Reject the right.
