# Debate prop_0084__gpt-6.2-astra-high__claude-opus-5-5-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0084
- proposition: Dating apps should require stronger identity verification and fraud checks even if that makes sign-up slower and less anonymous.
- model_pro: gpt-6.2-astra-high
- model_con: claude-opus-5-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: gpt-6.2-astra-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a dating app bans a romance scammer on Tuesday, what keeps the same person from messaging someone else on Wednesday? If all it takes to return is a new email address, the app hasn’t banned a person. It has retired a username. Stronger identity verification gives a ban some force; fraud checks help establish when that force is warranted.
[P1.2] Before an account can contact strangers, the app should require credible evidence that a real person controls it and check for links to accounts removed for fraud. Identity alone cannot establish honest intent. A verified person can still send the same invented emergency to a dozen matches. The platform can act on a pattern of complaints that no individual recipient could see.
[P1.3] Make verification an optional badge, though, and the operator it removes can come straight back without one.
[P1.4] That does mean less anonymity from the service. It need not mean displaying a legal name to a coworker, an ex, or anyone browsing nearby. A verifier can return a confirmation and a service-specific identifier rather than hand the app a permanent copy of someone’s papers. People who lack standard documents need another verification route; anyone wrongly rejected needs a human appeal.
[P1.5] Those safeguards matter precisely because the check is mandatory.
[P1.6] A slower signup costs everyone time, but not in the same way. An ordinary user clears the check once. Someone who depends on replacement accounts faces it every time. Without that friction, the cost does not disappear: it lands on the next match, who may spend weeks building trust before the first request for money.
[P1.7] Better to ask the platform to check who is coming back than ask each stranger to discover why that person was banned.

## Turn 2: CON Opening

- model: claude-opus-5-5-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: [P1.2]
- missing_claim_id_refs: (none)

[C1.1] PRO's case rests on one assumption: that a mandatory identity check stops the person who was banned on Tuesday from returning on Wednesday. It doesn't. Romance fraud is often run by organized groups, and they don't use their own papers. Stolen identity documents, accounts bought from real people, recruited money mules, and increasingly convincing face-swap tools mean a determined operator passes the gate with someone else's face and name.
[C1.2] The people who reliably fail or abandon a slow check are ordinary users with expired licences, name mismatches, or no patience for a document upload.
[C1.3] Worse, mandatory verification manufactures false trust. Once every profile has been "checked," users relax. The scammer who clears the gate with a borrowed identity now carries the platform's implicit endorsement into every conversation. PRO concedes this herself: "A verified person can still send the same invented emergency to a dozen matches."
[C1.4] The pattern-of-complaints detection she praises in [P1.2] is behavioural monitoring. It works without forcing everyone to hand over identity papers first.
[C1.5] Now weigh who pays. A gay man in a country or family where exposure is dangerous. A survivor rebuilding her life away from an abuser. Someone with no standard documents at all.
[C1.6] For them, "less anonymous" is not a matter of convenience. It is a risk to their safety. PRO promises that a verifier will return only a confirmation, but the verifier still holds the link between a real identity and a dating account. That record can be breached, subpoenaed, or sold.
[C1.7] The Ashley Madison leak showed what happens when dating data is tied to real people: careers, marriages and lives were damaged.
[C1.8] The better path targets fraud where it actually appears: flagging requests for money, scanning for scripted messages, tracking device and payment signals, and offering optional verification that users can filter for. That approach catches scammers without converting millions of innocent users into a permanent identity database.

## Turn 3: PRO Rebuttal 1

- model: gpt-6.2-astra-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON’s list of ways around verification makes the case for it. Getting another email address and recruiting another person willing to surrender a verified account are not equivalent tasks. A fraud ring might manage both; that doesn’t mean it can replace accounts as cheaply or quickly under either rule. The question is how many strangers it can reach before its next account is stopped, not whether a determined ring can ever return.
[P2.2] Behavioural checks tell the app why an account should be removed. Identity checks help that decision survive a change of device. Consider a scammer who spends weeks talking to one match before asking for money. There is no mass script to flag, and by the time a complaint arrives the money may be gone.
[P2.3] If the app can recognize an identity it already removed, the next match need not supply the evidence again. No public badge is necessary: tell users plainly that the check limits repeat accounts, not that the person messaging them is trustworthy.
[P2.4] CON is right that hiding a legal name from other daters is insufficient. But proving identity need not create the record CON fears. A general-purpose credential can be issued without naming a dating app; its holder can then present proof to the app under an identifier specific to that service. The app can recognize a return without keeping papers, and the issuer need not keep a list of dating accounts.
[P2.5] Access still requires alternative evidence and human review for document mismatches. That costs time and money. But optional filtering saves the platform that work by asking each potential target to decide, before a conversation even starts, whether this stranger deserves scrutiny. The platform knows whom it banned.
[P2.6] Its users don’t. The check belongs where that knowledge is.

## Turn 4: CON Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 310
- clipped_words: 310
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.2], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal quietly shrinks her own case. The Opening promised that verification gives "a ban some force" against the person who returns on Wednesday. Now the claim in [P2.1] is only that returning costs a ring a little more. That is a far weaker benefit, and it must be weighed against a mandatory cost imposed on every honest user.
[C2.2] Consider who absorbs that cost. A fraud ring spreads the price of a stolen passport or a purchased account across dozens of victims and possibly thousands in stolen money. A teenager-turned-adult with an expired licence, a trans woman whose documents carry an old name, or a refugee without standard papers pays the full price personally, every time the check misfires. The friction is heaviest exactly where the stakes of exclusion are highest.
[C2.3] Her slow-burn example in [P2.2] actually helps CON. Identity checks do nothing for the first victim, because that scammer cleared the gate. They help only if he returns under the same identity, but rings rotate borrowed identities precisely because they expect bans. The patient scammer comes back as someone else, verified, and the app's recognition system sees a stranger.
[C2.4] Then [P2.4] tries to dissolve the privacy problem, and it contradicts itself. To recognize a returning user, the app must keep something persistent that links that person to this account. Call it a service-specific identifier, but it still has to be unique to one real person. Anything that lets the app recognize you also lets whoever breaches or subpoenas the app recognize you.
[C2.5] PRO describes an elegant credential system. Real apps would buy a vendor that stores selfies and ID scans.
[C2.6] So the comparison is this: PRO offers modest friction that organized fraud adapts around. In exchange, everyone must make their identity linkable to a dating account. Behavioural detection plus optional verification captures the real benefit without that permanent exposure.

## Turn 5: PRO Pressure Questions

- model: gpt-6.2-astra-high
- raw_words: 58
- clipped_words: 58
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If behavioural checks catch fraud early enough to protect users, why assume a ring can spread the cost of each purchased account across “dozens of victims” before it’s banned?
[P3.2] Q2: A service-specific identifier lets the app tell that the same person signed up twice. What in that identifier tells someone who steals it the person’s real name?

## Turn 6: CON Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 68
- clipped_words: 68
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: When a banned ring returns using a different stolen passport or a purchased account belonging to a real person, what exactly does your recognition system in [P2.3] match on to stop it?
[C3.2] Q2: The privacy-preserving credential in [P2.4] is not what most apps deploy today. If the only practical option is a vendor storing ID scans and selfies, do you still require every user to submit them?

## Turn 7: PRO Rebuttal 2

- model: gpt-6.2-astra-high
- raw_words: 284
- clipped_words: 284
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Nothing matches the ring if a different person’s credential clears the check. The identifier catches reuse, not the operator behind several people’s accounts. But after a ban, another email and phone no longer suffice. The ring must also obtain another verified account or successfully pass as someone else.
[P4.2] A2: No. If a vendor retaining scans and selfies really is the only practical option, I would delay mandatory enrollment rather than compel submission. But “not what most apps deploy today” doesn’t establish that constraint. A reviewer can inspect evidence without keeping the image; an issuer can confirm identity without learning where a credential is presented. Stealing the app’s identifier alone tells you that two accounts belong together, not whose name is on the passport.
[P4.3] Consider CON’s claim that a purchased account pays for itself across dozens of victims. The better behavioural checks work, the fewer chances a ring gets to recover that price before it needs another account. If detection is slow enough to allow dozens of victims, the cost of letting a banned operator start again is especially high. Either way, removing accounts quickly and making them harder to replace belong together.
[P4.4] An optional check breaks that connection precisely for the operator who most wants to avoid it.
[P4.5] Someone whose papers carry an old name deserves an alternative to uploading the same rejected document twice. Providing one puts work on the app. Forgoing a mandatory check instead puts work on the next match, who can read every message carefully and still not know the app already barred the person writing to her. A chosen name protects a dater’s privacy.
[P4.6] A disposable account defeats a justified ban. Protect the first without guaranteeing the second.

## Turn 8: CON Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8], [C4.9]
- cited_claim_ids: [P4.2], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: I never claimed behavioural checks are perfect. I claimed they are where fraud actually becomes visible. Rings don't price one account against one victim. They buy stolen identities and verified accounts in bulk and spread that cost across the whole operation.
[C4.2] So PRO's dilemma cuts against her. If detection is fast, the identity gate adds little, because the account dies quickly anyway. If detection is slow, her own patient scammer clears the gate long before the first complaint arrives. Either way, the ID check is not what protects the first match.
[C4.3] A2: Nothing in the identifier itself. But it only works because someone, an issuer or a vendor, can link a real person to that number. PRO hasn't eliminated the dangerous record. She has moved it somewhere users cannot see or control.
[C4.4] The design that keeps that link safe is still largely theoretical.
[C4.5] That brings me to the decisive concession. In [P4.2], PRO says that if a vendor retaining scans and selfies is the practical option, she "would delay mandatory enrollment rather than compel submission." That is the world this motion addresses. Apps that verify today typically rely on outside vendors that process selfies and document images.
[C4.6] PRO's case therefore depends on infrastructure that mostly doesn't exist yet. Under real conditions, she has agreed not to compel submission.
[C4.7] Then look at [P4.1]: "Nothing matches the ring if a different person's credential clears the check." The Tuesday scammer from her opening comes back on Wednesday under a borrowed name. What remains of PRO's case is a modest surcharge on rings that already budget for stolen identities.
[C4.8] Weigh that surcharge against what everyone else pays. The closeted man and the survivor in hiding become linkable to a dating account. People with mismatched papers face exclusion. Every match now carries a "checked" signal that lowers users' guard.
[C4.9] Behavioural detection plus optional verification keeps the protection PRO actually demonstrated and avoids the exposure she has conceded is unacceptable.

## Turn 9: PRO Closing

- model: gpt-6.2-astra-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The point of a fraud complaint is that the next match shouldn’t have to make it again. CON asks what verification did for the first person deceived. Ask instead what the app owes the second person once it has investigated the first complaint and imposed a ban. The app knows why it closed that account.
[P5.2] The person receiving a friendly introduction knows none of that.
[P5.3] An optional check lets the banned operator decline the very check that might identify a return. A mandatory check makes the operator risk recognition or obtain another usable identity. Buying accounts in bulk may reduce that burden; it doesn’t erase the difference between needing another person’s account and simply inventing another username.
[P5.4] That difference is worth a slower signup, not a permanent archive of passports. CON treats a vendor’s processing an image as proof it must retain the image. Those are different decisions. Require the check, discard the scan, allow alternative evidence, and let daters use chosen names.
[P5.5] The privacy worth protecting is a person’s ability to meet someone without disclosing a legal name. It need not include the ability to erase a justified fraud ban before the next introduction.

## Turn 10: CON Closing

- model: claude-opus-5-5-high
- raw_words: 204
- clipped_words: 204
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.1]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing asks what the app owes the second match. Under her own admission in [P4.1], that second match meets the same ring under a borrowed name, and "nothing matches." The mandatory check does not recognize the operator. It recognizes an identity, and the operator has already thrown that identity away.
[C5.2] So ask who the gate reliably stops. It does not stop the ring that buys verified accounts in bulk. It stops the woman whose papers carry an old name, the refugee without standard documents, and the closeted man who will not tie his real identity to a dating profile. They cannot spread the cost across a criminal operation.
[C5.3] They pay it personally, or they leave.
[C5.4] PRO's final answer is "discard the scan." But recognizing a returning user requires something persistent that links one real person to every account they open. Discarding the image does not discard that link. The link is the whole mechanism, and whoever breaches or subpoenas it inherits it.
[C5.5] That is the trade this motion demands: certain exposure and exclusion for honest users, in exchange for a surcharge that rings already budget for. Behavioural detection catches fraud where it actually appears. Optional verification serves anyone who wants it. Vote CON.
