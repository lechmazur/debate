# Debate prop_0556__qwen4-max-high__claude-fable-5-2-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0556
- proposition: Governments should prohibit data brokers from selling individuals’ precise location data without explicit, time-limited opt-in consent.
- model_pro: qwen4-max-high
- model_con: claude-fable-5-2-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Precise location is not a preference; it is a biography. A stream of coordinates tells you where someone sleeps, which clinic they entered, which union hall, which shelter, which house they left at 2 a.m. Most commercial data describes what a person likes. This one describes what a person did, and where they will probably be tomorrow.
[P1.2] The market sells that biography on consent that does not exist. A weather app asks for location to show rain; an advertising library embedded inside it passes coordinates to brokers, who resell onward to buyers no one has ever named. Tapping "allow" to see a forecast is not agreement to be tracked into an oncology ward and sold to an insurer, a political operative, or a stalker with a credit card. Researchers and reporters have repeatedly re-identified individuals from feeds sold as anonymous, because a few nights of sleep and a few workdays are a fingerprint.
[P1.3] And the phone's owner cannot consent for everyone else their movements expose: a child's school, a patient's appointment, a source's apartment.
[P1.4] Time limits matter because location is forward-looking. A permission granted years ago to a flashlight app should not underwrite a dossier compiled today by a company that bought the archive. Expiry turns a blank check into a renewable decision.
[P1.5] The cost of this rule is a prompt and a renewal. The cost of refusing it is an unrecallable record of a life, copied to unknown buyers, forever. Legitimate mobility analysis survives on coarser, aggregated data; nothing here touches navigation or first-party services.
[P1.6] So the question CON must defend is narrow and uncomfortable: that a broker should keep selling your movements without ever asking you plainly, and without ever asking again. Convenience is not worth that.

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 324
- clipped_words: 324
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.2], [P1.3], [P1.5]
- missing_claim_id_refs: (none)

[C1.1] PRO's diagnosis indicts PRO's cure. We are told that tapping "allow" is consent "that does not exist" [P1.2], and then offered, as the remedy, another tap, repeated on a schedule. If people do not read the first prompt, they will not read the fifth. A renewal pop-up wedged between a user and their weather forecast is not a decision; it is an obstacle people click through.
[C1.2] The motion fails on three counts.
[C1.3] First, it launders the harm. Once the box is ticked, selling your trail into the oncology ward becomes lawful, to the insurer, the operative, the stalker. The rule regulates how permission is collected, not who buys or what they do. PRO concedes the deeper flaw at [P1.3]: you cannot consent for the child, the patient, the source.
[C1.4] A consent rule therefore cannot protect them. Only limits on use can: ban sales that reveal visits to sensitive sites, bar particular buyers and purposes, and require audits and deletion. Those protections work whether or not anyone clicked.
[C1.5] Second, it aims at the wrong target. Brokers have no screen on your phone and no relationship with you, so the prompt will be written by the app that profits from a yes. Meanwhile the largest platforms collect precise location first-party and monetise it internally without "selling" anything. The motion leaves them untouched and removes their smaller rivals, which concentrates the data rather than freeing people from it.
[C1.6] Third, it damages the valuable uses. Evacuation modelling, transit planning, epidemic tracking and fraud detection depend on representative movement data. Opt-in samples are small and skewed toward whoever clicks yes, and expiry destroys the continuity those analyses need. "Coarser data" [P1.5] cannot always answer block-level questions.
[C1.7] So the real choice is not between asking and never asking. It is between consent theatre that blesses the dangerous sale once a box is ticked, and rules that forbid the dangerous sale outright. Protect people from the buyer, not from the pop-up.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON says the box "launders" the harm. But nothing in this motion authorises a stalker's purchase; consent is a floor, not a licence. Use limits and consent are complements — and CON's own bans on sensitive-site sales would still leave every ordinary movement sold, forever, without asking. That is the residue CON must defend: not the oncology ward, but the whole rest of your life, sold to strangers by default.
[P2.2] "Laundering" also mistakes where enforcement bites. Use limits police buyers after the trail has already been copied onward; consent stops the copying. Every refused sale also spares the bystanders CON says consent cannot protect. A ban you cannot audit downstream is weaker than a permission that was never given.
[P2.3] On the prompt: "explicit" is doing work CON skips. Explicit means unbundled — not the weather app's rain permission, but a separate request naming the sale. And the duty sits on the broker: if the consent behind a feed is defective, the sale is unlawful. That makes the party profiting from the resale responsible for proving permission, rather than letting it hide behind an SDK.
[P2.4] Consent that is revocable, dated and attributable is not theatre; it is evidence, and it is a lever. An unread yes still beats a rule requiring no yes at all.
[P2.5] First-party platforms are not this motion's target because internal monetisation, however objectionable, is not an open market in your movements available to anyone with a credit card. CON would leave that market unregulated because a different problem exists.
[P2.6] On skew: planners can recruit and pay consented panels, and renewals preserve longitudinal continuity for those who keep agreeing. CON's answer to sampling bias is to conscript everybody. That is the real choice: a smaller, honest dataset, or a complete one nobody agreed to give.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 293
- clipped_words: 293
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.4], [P1.2], [P2.2], [P1.5], [P2.1], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] PRO's defence now rests on a sentence that should end it: "An unread yes still beats a rule requiring no yes at all" [P2.4]. An unread yes is exactly what PRO called consent "that does not exist" [P1.2]. Calling the prompt "unbundled" changes its label, not its reader. And the comparison is false.
[C2.2] My alternative is not "no yes"; it is a legal no, to re-identification, to individual buyers, to sensitive inference, which covers ordinary movements too and which nobody has to click.
[C2.3] Second, "consent stops the copying" [P2.2] only when people refuse. When they tap yes, unread, the copying proceeds with paperwork. And expiry cannot deliver what PRO promised. PRO's opening called the record "unrecallable," copied "to unknown buyers, forever" [P1.5].
[C2.4] Then a lapsed or withdrawn consent recalls nothing; it governs the next sale, not the copies already circulating. Only deletion duties and buyer restrictions reach those.
[C2.5] Third, PRO says downstream bans cannot be audited, yet requires brokers to prove consent gathered by someone else's app through an embedded SDK. That is an audit trail too, and a flimsier one: a timestamp asserting somebody tapped something. If regulators can verify that, they can verify who bought a feed.
[C2.6] Fourth, "complements" [P2.1] is a retreat. If use limits must stop the stalker and the insurer, the consent rule's distinct contribution is the seller's defence: he agreed.
[C2.7] Finally, paid panels [P2.6]. Who sells their movements for a few dollars a month? People who need a few dollars. PRO's market makes privacy a default for the comfortable and a commodity for the poor, and builds evacuation plans on whoever was cheapest to recruit.
[C2.8] So choose between a protection that depends on vigilance PRO admits people lack, and one that works while nobody is paying attention.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your "legal no" [C2.2] — does it forbid selling my precise movements to any buyer without asking me? If yes, you've adopted the motion's core; if no, name the sale you'd still permit, and why I never get asked.
[P3.2] Q2: You call a dated consent record "flimsier" than buyer audits [C2.5]. Which is genuinely easier for a regulator: checking one permission before a transfer, or proving what an anonymous buyer inferred after the copies dispersed?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: When a user taps an unread "yes" on your unbundled prompt, may the broker then lawfully sell her trail to an insurer or an anonymous individual buyer? If so, your rule blesses that sale. If not, a use limit is doing the protecting, so what does the tap add?
[C3.2] Q2: You called the record "unrecallable," copied "forever" [P1.5]. When consent expires or is revoked, what happens to copies already sold? If only deletion duties and buyer restrictions reach them, why isn't that my model rather than yours?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: No. Consent is not a licence to sell to a stalker, and the motion doesn't repeal use limits. What the tap adds is the decision use limits cannot make: whether the ordinary remainder of your life — the gym, the bar, the job interview — may be sold at all. CON's "legal no" targets sensitive inference and re-identification; that ban only bites when a regulator proves re-identification happened. CON never told us which sale it still permits.
[P4.2] That silence is the case: either CON forbids selling my precise movements without asking, which is the motion, or CON permits a vetted corporate buyer to purchase my Tuesdays forever, and I am never asked.
[P4.3] A2: Expiry governs the next transfer; revocation should carry deletion duties to buyers, and nothing in the motion bars them. But notice the asymmetry CON elides: deletion chases copies, consent prevents them. A refused sale creates no buyer to identify, no inference to prove, no archive to purge. CON's protections all start after dispersal and depend on reconstructing what a buyer did with coordinates; mine acts at the one moment the trail is still in one place.
[P4.4] Expiry also means the archive stops growing; CON's lawful sales keep feeding it forever.
[P4.5] On the poor: CON's default sells their movements too — unasked, unpaid, and to buyers they will never learn about. Poverty is an argument for a right to refuse, not for withholding it.
[P4.6] So the clash is timing. CON promises to catch misuse after your movements have been copied to strangers and interpreted; the motion asks one plain question before they leave. CON still has not named a single sale it would permit me to refuse. If it names none, it has conceded the principle and is arguing about the paperwork.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P2.4], [P4.6], [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: No, and here is the sale I would permit: precise data sold to a licensed, identified buyer, such as a transit agency, an evacuation planner or a fraud team, under a contract that bans re-identification and individual targeting and requires audit and deletion. You are not asked because your safety should not hinge on a prompt PRO concedes goes "unread" [P2.4]. Sales to individuals, insurers and operatives stay forbidden whatever anyone tapped.
[C4.2] A2: Checking the buyer is easier. The question assumes an "anonymous buyer", but anonymity exists only in PRO's world, where the gate is a timestamp. In mine, the buyer is licensed and named before the transfer. A regulator can verify a registry entry.
[C4.3] She cannot verify that a tap, collected by an app paid to obtain it, reflected any understanding at all.
[C4.4] Those answers dissolve PRO's "timing" clash [P4.6]. A buyer gate acts at the same moment as a consent gate: before the trail leaves. The difference is what each gate tests. Mine asks who is buying and for what purpose.
[C4.5] PRO's asks whether a box was ticked.
[C4.6] Look at what PRO has now conceded. The tap does not authorise the stalker or the insurer, so use limits do that work [P4.1]. Expiry recalls nothing, so deletion duties do that work [P4.3]. Every protection that reaches the dangerous sale is borrowed from my side.
[C4.7] The motion's own contribution has shrunk to one thing: letting you refuse the vetted planner. And "consent prevents copies" [P4.3] holds only for the few who refuse. For everyone who taps through, it prevents nothing and hands the seller a defence.
[C4.8] So the motion adds a prompt that protects the vigilant from the buyers who threaten them least, and it thins the data behind evacuation routes to do it. PRO says I am "arguing about the paperwork" [P4.6]. But the paperwork is the only thing the motion itself supplies.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C2.8]
- missing_claim_id_refs: (none)

[P5.1] CON finally named its permitted sale: a licensed buyer with a contract promising not to re-identify. That is not a gate on the data leaving; it is a promise about what happens after it arrives — enforceable only once broken. My gate can be refused.
[P5.2] And notice who CON's model actually protects. It claims to work "while nobody is paying attention" [C2.8]. But under explicit opt-in, inattention means no sale: the person who never reads a prompt is never sold. Under CON's registry, inattention means your movements flow to whoever gets licensed, and your only defender is a regulator guessing which purposes are benign.
[P5.3] "Fraud team" is not a narrow category; it is a label a buyer chooses.
[P5.4] The deeper point: no registry can know what is sensitive about your ordinary Tuesdays. The bar, the gym, the interview — only you know which of those, in whose hands, could ruin you. CON transfers that judgment to a licensing office and calls it protection.
[P5.5] Use limits, deletion, audits: keep them all. But the one question that cannot be delegated is whether your life is for sale. CON never lets you answer it.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 201
- clipped_words: 201
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P5.2], [P2.4], [P1.2], [P5.1], [P5.4]
- missing_claim_id_refs: (none)

[C5.1] One sentence in PRO's closing decides this: "the person who never reads a prompt is never sold" [P5.2]. That is not how prompts work, and PRO knows it. The app paid for every yes will put the request between the user and her forecast, and she will tap. PRO already called that an "unread yes" [P2.4], and consent "that does not exist" [P1.2].
[C5.2] Under the motion, inattention does not mean no sale. It means a sale with her signature on it.
[C5.3] Everything else follows from that. PRO says my licence is only a promise, "enforceable only once broken" [P5.1]. So is a consent mandate, since brokers can sell on defective permissions until someone catches them. Both gates are law.
[C5.4] The difference is what they test: mine asks who is buying and why, PRO's asks whether a thumb touched glass.
[C5.5] PRO says only you know which Tuesday could ruin you [P5.4]. True, but no prompt tells you whose hands it will reach. A ban on those hands does, for you and for the bystanders who never tapped.
[C5.6] Strip away the protections PRO borrowed, and the motion supplies a ritual, a seller's alibi, and thinner evacuation data. Regulate the buyer, not the thumb.
