# Debate prop_0255__claude-sonnet-5-high__glm-5-2__s0__tpl_placement_active_20260320f

- topic_id: prop_0255
- proposition: Data brokers should be prohibited from archiving and selling deleted or otherwise non-public digital traces of private citizens.
- model_pro: claude-sonnet-5-high
- model_con: glm-5-2
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 334
- clipped_words: 334
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every day, millions of people make an active choice: they delete a text, clear a search history, remove an old post. That choice is not incidental—it is the whole point of digital autonomy. When a data broker quietly archives that deleted material and sells it, they are not reporting on public life. They are reversing a decision the person already made about their own life.
[P1.2] That reversal, done for profit, without consent, is the harm this proposition targets.
[P1.3] Start with the clearest case: location data. Someone deletes a period-tracking app, or clears their location history after leaving an abusive partner. If a broker has already archived that trail and can sell it—to an ex, to an insurer, to anyone with a subscription—the person's decision to erase their own footprint becomes meaningless. The technology to reconstruct a stalking victim's movements already exists; the only question is whether we let a marketplace form around it.
[P1.4] Prohibition here isn't hypothetical harm-prevention—it's closing a channel that has already been used to locate people who tried to disappear from view.
[P1.5] Notice what CON must defend to win: not "data brokers add value," but specifically that brokers should be allowed to preserve and monetize things people deleted or never made public. That's a much narrower and much weaker position than it sounds. The mere fact that a byte was technically captured somewhere doesn't mean it should be perpetually re-sellable. We don't let someone keep and sell a recording of a private conversation just because a microphone happened to catch it—deletion and non-public status are the digital equivalent of a closed door.
[P1.6] This isn't a ban on all data brokering. Public records, voluntarily shared social content, aggregated demographic data—all untouched. The line drawn is narrow and principled: once you delete something, or never made it public, no one else gets to turn your reversed decision into their product. That's the frame I want this debate to run on: consent versus circumvention, and who bears the cost when the wrong side wins.

## Turn 2: CON Opening

- model: glm-5-2
- raw_words: 297
- clipped_words: 297
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition sounds narrow until you ask what "deleted" and "non-public" actually cover. Most digital traces people consider "deleted" were never erased from the systems that received them—they were removed from the user's own view, under terms of service the user accepted. When someone deletes a search from their browser, the ISP already logged it. When someone closes an account, the platform retains transaction records for years.
[C1.2] The proposition doesn't just stop brokers from selling stalking tools; it sweeps up vast categories of data that were lawfully collected, contractually permitted, and serve legitimate downstream uses.
[C1.3] Consider identity verification. Banks, employers, and landlords rely on data brokers to confirm that a person presenting a Social Security number actually matches records associated with that number. Much of that matching depends on cross-referencing historical data—old addresses, prior transactions, account closures—that the individual may have "deleted" from their own access. Strip that away, and fraud detection degrades overnight.
[C1.4] The same goes for insurance fraud investigations and law enforcement leads, both of which routinely depend on records the subject no longer surfaces publicly.
[C1.5] The emotional cases—location data reaching stalkers—are real, but they're better addressed by targeted restrictions on specific harmful uses. What the proposition does instead is burn down the entire category to reach the worst cases, destroying legitimate infrastructure that depends on retained, non-public records.
[C1.6] The microphone analogy fails because a private conversation was never offered to anyone. Most digital traces were affirmatively transmitted to a second party under an agreement. Once you share information with a platform, it's a transmitted record, not a closed door. The real question isn't whether to permit abuse; it's whether a blanket prohibition is the right instrument.
[C1.7] Targeted misuse regulation protects victims without dismantling legitimate data markets. The proposition trades a scalpel for a sledgehammer.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 286
- clipped_words: 286
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.1], [C1.3], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] CON's whole case rests on collapsing two very different actors: the platform that retained your data under its terms of service, and the broker who buys, archives, and resells it to strangers. [C1.1] says your ISP or your bank kept the record—true, and irrelevant. The proposition doesn't touch the ISP's own retention for billing or compliance. It stops a *third party* from turning your deleted search history into a product sold to whoever pays.
[P2.2] That's not sweeping up "vast categories of lawful data"—it's cutting off resale, the one link in the chain that has no legitimate claim to your reversed decision at all.
[P2.3] The identity-verification case in [C1.3] actually proves my point. Banks and landlords verify identity using historical *public* records—old addresses on file with utilities, prior court records, credit history reported under specific statutory permission. None of that requires a broker to have secretly archived a deleted text or a cleared browser history. If some narrow verification use genuinely depends on non-public deleted traces, CON can carve that exception in committee—but that's an argument for a narrower rule, not for rejecting the rule entirely.
[P2.4] CON keeps saying "sledgehammer," but refuses to name the actual overlap between "deleted personal trace" and "necessary fraud infrastructure," because there isn't much of one.
[P2.5] On [C1.6], transmitting a message to a platform for a specific purpose—storage, delivery, temporary display—is not consent to that platform's *business partner* reselling it to an ex-partner or a stalker years later. That's the whole distinction between a transmitted record and a resold one.
[P2.6] And CON's own fallback—"targeted misuse regulation instead"—concedes the harm is real while offering an after-the-fact remedy for damage that's often irreversible: once your location history reaches a stalker, no lawsuit undoes it.

## Turn 4: CON Rebuttal 1

- model: glm-5-2
- raw_words: 309
- clipped_words: 309
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.3], [P2.5], [P2.6], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal depends on a clean separation that doesn't hold: platforms retain, brokers resell, and the proposition only touches the latter. But the proposition doesn't say "resale by third parties." It prohibits "archiving and selling deleted or otherwise non-public digital traces." Archiving is the broker's core function—the cross-referenced databases that power identity verification, fraud scoring, and risk assessment.
[C2.2] You can't let brokers retain data for legitimate use while prohibiting them from archiving it. Those are the same operation.
[C2.3] PRO claims identity verification runs on "historical public records" alone [P2.3]. That misunderstands the industry. Brokers aggregate non-public data streams—transaction histories, account-closure patterns, device fingerprints, address changes derived from private utility records—and cross-reference them to produce the risk scores that catch synthetic identity fraud. Remove the non-public traces, and public records alone leave gaps that fraudsters exploit.
[C2.4] PRO's fallback here is revealing: "carve that exception in committee" [P2.3]. That concedes the proposition is overbroad. If legitimate uses exist—and PRO admits they might—then a blanket prohibition is the wrong instrument. You don't swing a sledgehammer and then chisel exceptions afterward.
[C2.5] On consent [P2.5]: PRO says transmitting data to a platform for one purpose isn't consent to resale. Fair principle—but it's an argument for purpose-limitation rules, not for prohibition. Purpose restrictions, use-case licensing, and downstream liability all address the consent problem without destroying the archival infrastructure that legitimate actors depend on.
[C2.6] The stalker scenario [P2.6] is terrifying because the use is harmful. But that argues for regulating harmful uses—banning sale of location data to individuals, mandating purpose restrictions, imposing real liability—not for demolishing the entire category. PRO offers a false choice: blanket ban or weak enforcement. Stronger targeted regulation gets the protection without the collateral damage.
[C2.7] The overlap PRO denies [P2.4] is real: most fraud-detection value comes from data consumers never made public. "Non-public" isn't a fringe corner—it's the center of the industry.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 75
- clipped_words: 75
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON claims fraud-scoring needs deleted/non-public traces [C2.3], but banks already run fraud detection on data they lawfully hold themselves—so what specific fraud outcome fails if brokers, not banks, lose access to a stalking victim's cleared search history?
[P3.2] Q2: If purpose-limitation and use-case licensing [C2.5] can already fix consent violations, why has that regime not stopped the location-data-to-stalker pipeline PRO cited—what makes CON confident a new liability rule succeeds where existing purpose limits have failed?

## Turn 6: CON Pressure Questions

- model: glm-5-2
- raw_words: 82
- clipped_words: 82
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: The proposition covers "deleted or otherwise non-public" traces, yet every example PRO cites is deleted data. Are transaction histories and device fingerprints—never deleted, just non-public—also banned, or does PRO's own framing concede the proposition sweeps far beyond its emotional examples?
[C3.2] Q2: PRO says legitimate uses can be carved "in committee" [P2.3], but the proposition prohibits archiving itself. How does an exception to an archiving ban preserve the cross-referenced databases fraud detection requires—without the archive, what does the exception even operate on?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 332
- clipped_words: 332
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Yes—"non-public" reaches beyond deleted data, and that's correct, not a concession of overbreadth. The proposition bundles "deleted" and "non-public" because both describe traces a person never offered to a resale market. A device fingerprint or transaction history the citizen never deleted was also never something they put up for sale—it exists because a platform needed it operationally, not because the person consented to a stranger buying it later. The test isn't "did you press delete," it's "did you make this available for third-party resale."
[P4.2] Neither category passes. Treating them alike is consistency, not scope creep.
[P4.3] A2: The exception CON demands already has somewhere to operate: permissioned, closed-loop data-sharing among the institutions that actually need it—bank-to-bank fraud consortiums, regulator-supervised AML frameworks, direct verification channels between employers and the record-holder. Those systems don't require a broker to have independently archived your data for resale to any paying subscriber. What the proposition bans is the broker's business model—speculative accumulation of private traces, held indefinitely, sold to whoever pays—not the narrower institutional pipelines banks already use under existing fiduciary duties.
[P4.4] "Archive" in this proposition means "build a resellable warehouse," not "retain under a direct, regulated relationship."
[P4.5] That distinction is the whole debate. CON needs the fraud infrastructure and the stalker pipeline to be the same infrastructure, because only then does prohibiting one require gutting the other. It isn't. Closed, permissioned, accountable data-sharing between institutions with a duty to the customer is categorically different from an open marketplace where an ex-partner's money is as good as a bank's.
[P4.6] CON has spent four speeches gesturing at "risk scores" and "fraud outcomes" without naming one case where a broker's resold, non-institutional archive of deleted personal data was the load-bearing piece—compare that to the concrete, already-documented pattern of resold location data reaching people who used it to find and harm someone. Weigh a speculative efficiency loss to a resale business against an irreversible safety harm to a person who did everything right and still got found. That's not close.

## Turn 8: CON Rebuttal 2

- model: glm-5-2
- raw_words: 283
- clipped_words: 283
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P3.1], [P4.4], [P4.5]
- missing_claim_id_refs: (none)

[C4.1] A1: The specific failure is cross-institutional fraud. Synthetic identity fraud—a real SSN paired with fabricated histories—spreads across multiple lenders. No single bank sees enough to catch it. Brokers aggregate non-public signals across institutions: address changes, account closures, device fingerprints from different platforms.
[C4.2] That cross-referencing flags inconsistencies. PRO asks what fails [P3.1], but the answer is that each bank holds a fragment; the broker assembles the mosaic.
[C4.3] A2: Purpose-limitation hasn't stopped the stalker pipeline because current enforcement is post-hoc and penalties are small relative to resale profits. That's not proof the approach fails—it's proof it's been under-resourced. Pre-sale licensing with mandatory purpose review, audit requirements, and liability that makes harmful resale unprofitable is structurally different from today's weak after-the-fact fines. The real comparison: a ban that destroys legitimate infrastructure versus targeted regulation that's never been seriously tried.
[C4.4] PRO's latest move [P4.4] redefines "archive" as only "resellable warehouse," excluding institutional retention. But the proposition prohibits "archiving and selling"—it doesn't distinguish between archiving for open resale and archiving for regulated use. PRO is rewriting the motion to escape the overbreadth CON identified. If the proposition only banned open-market resale to arbitrary buyers, CON would have less objection.
[C4.5] But it bans archiving itself—and the cross-referenced databases that power fraud detection are archives.
[C4.6] PRO's distinction [P4.5] between "closed institutional sharing" and "open marketplace" sounds clean, but the proposition as written doesn't preserve an archive because the sharing is "permissioned." The archive either exists or it doesn't. You can't keep the database while prohibiting the archiving. PRO is smuggling in a narrower rule through interpretation after the overbreadth became undeniable.
[C4.7] That distinction—bank buyer versus stalker buyer—belongs in targeted regulation, not in a blanket ban that pretends it doesn't exist.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.2], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] This debate comes down to one question: who should bear the cost of uncertainty?
[P5.2] CON never named a single instance where a broker's resold archive of someone's deleted or non-public trace was the irreplaceable piece of a fraud case—only an abstract "mosaic" [C4.2] that institutions with fiduciary duties and regulatory frameworks are better positioned to assemble through permissioned channels than through an open resale market. Compare that to PRO's concrete pattern: cleared location history reaching an ex-partner, a stalking victim found because a byte someone deliberately erased was warehoused and sold to whoever paid.
[P5.3] CON even concedes existing purpose-limitation rules have failed to stop this pipeline [C4.3], asking us to trust an untested stronger version—later, someday.
[P5.4] That's the asymmetry that decides this. If PRO is wrong, some fraud-detection efficiency is lost, and it can be legislated back through a narrow carve-out. If CON is wrong, people who deleted their footprint on purpose get found anyway, and that harm cannot be undone by any subsequent fine or lawsuit. A rule that risks efficiency against a rule that risks irreversible safety harm isn't a close call.
[P5.5] Prohibit the archive. Let institutions build narrower, accountable exceptions afterward—not the other way around.

## Turn 10: CON Closing

- model: glm-5-2
- raw_words: 188
- clipped_words: 188
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.5], [P4.4], [C4.2]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing reveals the problem: "Let institutions build narrower, accountable exceptions afterward" [P5.5]. Afterward. That single word concedes the proposition as written is overbroad—and that the legitimate uses CON identified are real enough to require fixing later.
[C5.2] But you cannot carve an exception to an archiving ban and still have the archive. The cross-referenced databases that catch synthetic identity fraud exist because archiving happened. PRO redefined "archive" to mean only "resellable warehouse" [P4.4], but the proposition says "archiving and selling"—two operations, both prohibited. The fraud-detection mosaic [C4.2] requires the archive.
[C5.3] No archive, no mosaic. PRO never resolved this; PRO waved at "permissioned sharing" while the motion demolishes the infrastructure that sharing depends on.
[C5.4] The stalker scenario is horrifying. It's also addressable by banning sale of location data to individuals, mandating purpose restrictions, and imposing liability that makes harmful resale unprofitable—measures CON proposed and PRO never engaged beyond noting current enforcement is weak.
[C5.5] PRO's own closing proves the point: a proposition that admits it needs exceptions built afterward is a proposition that shouldn't be adopted as written. Targeted regulation protects victims without destroying legitimate infrastructure. That's why CON wins.
