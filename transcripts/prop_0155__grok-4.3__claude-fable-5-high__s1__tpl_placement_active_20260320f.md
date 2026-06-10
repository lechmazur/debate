# Debate prop_0155__grok-4.3__claude-fable-5-high__s1__tpl_placement_active_20260320f

- topic_id: prop_0155
- proposition: Police departments should be prohibited from using face recognition in real-time surveillance, but allowed to use it for post-incident investigations with a warrant.
- model_pro: grok-4.3
- model_con: claude-fable-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: grok-4.3
- raw_words: 227
- clipped_words: 227
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Real-time facial recognition gives police continuous power to identify and track people in public without any individualized suspicion or judicial check. This creates an architecture of persistent monitoring that records movements, associations, and locations across entire cities, producing a chilling effect on lawful protest, journalism, and ordinary social life that cannot be reversed after the fact.
[P1.2] Accuracy problems make the risks concrete. Mismatches occur more often with certain demographic groups, turning routine presence in a public area into an erroneous alert that triggers immediate police contact. Because the match happens live, there is no intervening human judgment or warrant requirement to filter obvious errors before action is taken.
[P1.3] By contrast, restricting facial recognition to post-incident investigations under warrant restores accountability. Investigators must articulate specific facts to a judge and limit the search to relevant footage and time windows. This preserves the tool for solving crimes while preventing its use as an always-on dragnet that lowers the threshold for surveillance to mere presence in public.
[P1.4] Without that prohibition on real-time use, departments face structural incentives to broaden application to traffic enforcement, crowd control, and low-level disorder because the cost of each additional scan is near zero. The warrant requirement for stored data blocks that expansion while still allowing targeted review once probable cause exists. The distinction therefore protects both investigative utility and the boundary against suspicionless mass tracking.

## Turn 2: CON Opening

- model: claude-fable-5-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The motion gets the comparison exactly backwards, and that inversion is the case this debate should turn on.
[C1.2] Notice what the proposition actually forbids: real-time use under any circumstances, even with a warrant, even with individualized suspicion. Picture an abducted child, a named suspect, a vehicle last seen near a transit hub. A judge would happily sign an order authorizing live screening of station cameras against that one face for forty-eight hours. The motion prohibits it.
[C1.3] PRO's own legitimating principle — judicial authorization based on articulable facts — is the thing PRO categorically refuses to apply where minutes matter most. If a warrant can sanitize searching footage after the child is found dead, it can sanitize the live search that might have found her alive. That asymmetry is incoherent, and PRO must defend it.
[C1.4] Second, PRO conflates real-time matching with persistent tracking. A properly designed live system compares faces against a narrow watchlist of wanted violent offenders and discards every non-match within seconds. It builds no movement database. Ironically, it is PRO's blessed alternative — retrospective searching — that requires cities to retain mass video archives so investigators can mine them later.
[C1.5] If the fear is an "architecture of persistent monitoring," post-incident search of stored footage is the architecture; ephemeral live matching is not.
[C1.6] Third, the accuracy objection argues for regulation, not prohibition. The documented wrongful-arrest cases involved police treating a match as probable cause — a policy failure, fully fixable by rules requiring human verification and treating alerts as leads only. We don't ban DNA analysis because early labs made errors; we impose standards.
[C1.7] Meanwhile the cost of prohibition is borne in real bodies: the fugitive who walks past a camera unrecognized, the trafficking victim moved through a bus terminal.
[C1.8] So the alternative is straightforward: tiered judicial authorization for real-time deployments, narrow watchlists, human review, audit trails. PRO offers a categorical ban that sacrifices the highest-stakes uses to prevent harms better addressed by design.

## Turn 3: PRO Rebuttal 1

- model: grok-4.3
- raw_words: 240
- clipped_words: 240
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The motion's distinction holds because real-time use cannot be cabined by the same warrant process that works for stored footage. In the abduction case, investigators already have the ability to review existing recordings under judicial order within hours; the live prohibition blocks only the extension to continuous camera-by-camera scanning that would require officers to maintain and update watchlists across shifting locations with no time for meaningful judicial review before each expansion.
[P2.2] The claim that a properly designed system discards non-matches and builds no database ignores operational reality. Once departments deploy the capability for one narrow list, the marginal cost of adding shoplifters, protest organizers, or immigration violators drops to zero. Real-time alerts then trigger immediate stops without the full investigative file a warrant review would demand, producing the exact suspicionless contacts PRO identified as the core harm.
[P2.3] Accuracy rules requiring human verification also collapse under time pressure. A live match in a crowded terminal prompts rapid deployment; any later correction arrives after the mistaken individual has already been approached or detained. Retrospective searches, by contrast, allow the same verification step before any action is taken against a person.
[P2.4] The architecture question therefore turns on timing. Post-incident warrants preserve investigative power while keeping the default rule that presence in public does not generate an automatic identification event. Allowing real-time authority concedes that default and places the burden on later regulation to claw back ground that operational incentives will have already expanded.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1]
- missing_claim_id_refs: (none)

[C2.1] Track what just happened to PRO's abduction answer. PRO says investigators can "review existing recordings under judicial order within hours" [P2.1]. Hours. Stored footage tells you where the child *was*; live matching tells you where she *is*.
[C2.2] PRO has now conceded that in the case where minutes decide survival, their regime delivers the answer after it stops mattering. That is not cabining a power — it is forfeiting the rescue.
[C2.3] And the claim that real-time use "cannot be cabined" by warrants is simply asserted, not shown. A judicial order authorizing one face, on fixed cameras, for forty-eight hours is *more* cabined than PRO's alternative — a retrospective trawl through weeks of archived video of thousands of innocent people. If shifting watchlists are the worry, the warrant fixes the list. That's what warrants do.
[C2.4] P2.2 is a slippery-slope argument against warrantless deployment — which nobody here is defending. Under my framework, adding shoplifters or protest organizers to a watchlist requires a judge, and "he organized a protest" fails probable cause on its face. Meanwhile the identical slope runs under PRO's regime: the marginal cost of querying stored archives against shoplifters is also zero. If judicial authorization can hold the line for stored data, PRO must explain why the same judge becomes powerless the moment the search runs live.
[C2.5] They haven't.
[C2.6] On accuracy, P2.3 inverts the record. The documented wrongful arrests arose from *retrospective* still-image searches — PRO's blessed mode — where a bad match hardened into an arrest warrant. The worst outcome of a flawed live alert under verification rules is a brief, correctable field contact; the worst outcome of a flawed archive match is handcuffs at your front door days later.
[C2.7] Finally, the "default rule" in P2.4 is illusory. A regime built on mass retained video makes every public appearance permanently queryable. That is the chilling architecture — and it's PRO's.
[C2.8] The asymmetry from my opening stands unanswered: warrants either legitimate this tool or they don't.

## Turn 5: PRO Pressure Questions

- model: grok-4.3
- raw_words: 64
- clipped_words: 64
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If a warrant can fix the watchlist and cameras at deployment, how does it prevent officers from requesting immediate expansions during an active shift when new leads appear, given that each addition requires no new infrastructure?
[P3.2] Q2: Under verification rules, what stops a live alert from becoming the functional equivalent of probable cause for an immediate stop before the promised human review occurs?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-high
- raw_words: 96
- clipped_words: 96
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P1.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: You concede stored-footage review delivers answers "within hours" [P2.1]. In an active abduction where the child is being moved right now, what does your regime offer during those hours — or do you accept that the rescue case is simply forfeited as the price of the ban?
[C3.2] Q2: You trust judges to police query limits on stored archives [P1.3] but insist warrants "cannot cabin" live use [P2.1]. Identify the specific mechanism that makes judicial limits enforceable against retrospective searches yet unenforceable against a fixed-list, time-limited live deployment — since audit trails exist equally in both.

## Turn 7: PRO Rebuttal 2

- model: grok-4.3
- raw_words: 238
- clipped_words: 238
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Stored footage review supplies leads on prior movements that can immediately guide officers to live search by description, vehicle, or associate locations already known; real-time matching adds nothing officers cannot pursue through ordinary observation once a suspect description is in hand, while avoiding the expansion risk the motion targets.
[P4.2] A2: Judicial limits on stored queries are enforceable because each search requires a fresh showing of relevance to a specific case before any data is accessed; live deployment places the list in continuous operation across active shifts, where new additions can be requested and approved orally without returning to the issuing judge, rendering the original warrant a one-time formality.
[P4.3] These answers expose why the motion prevails. The rescue scenario does not collapse under the ban because police already operate with descriptions, BOLOs, and human surveillance the moment a warrant or alert issues; real-time facial recognition merely automates the same work at the cost of embedding an always-expandable watchlist that stored archives cannot replicate without repeated judicial checks. The enforcement gap in A2 is structural rather than technical: retrospective queries are discrete events a court can later audit and sanction, while live systems create irreversible field contacts before any audit occurs.
[P4.4] CON's framework therefore trades a narrow, time-sensitive benefit for permanent removal of the default that public presence triggers no automated identification. The motion keeps investigative power where judges can still superintend it and withholds power where they cannot.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.2], [C2.6], [P4.1], [P1.4]
- missing_claim_id_refs: (none)

[C4.1] A1: The same mechanism that polices every warrant: scope is a condition of the authorization, not a suggestion. Lock the watchlist technically at deployment so additions require the issuing judge's sign-off, logged in the audit trail. And notice what PRO just conceded in [P4.2]: mid-shift additions would be "approved orally" — by a judge. That is judicial supervision, the exact thing PRO says cannot exist for live use.
[C4.2] Telephonic warrant approval in exigent circumstances is routine, lawful, and reviewable. If a judge approving a query on stored archives is meaningful oversight, a judge approving a watchlist addition is too. PRO cannot call the same judge a guardian in one sentence and a rubber stamp in the next.
[C4.3] A2: A statutory rule that an unverified alert is, at most, grounds for a brief consensual contact — never arrest — backed by suppression and discipline for violations. And test the comparison PRO is dodging: their regime happily permits immediate stops based on eyewitness BOLO descriptions, which are notoriously less reliable than algorithmic matches. If a human shouting "white sedan, red jacket" can justify a field stop, a verified-pipeline alert under stricter rules is an improvement, not a new harm.
[C4.4] Meanwhile the documented wrongful *arrests* came from retrospective searches — PRO's blessed mode — and that record [C2.6] remains unanswered.
[C4.5] Now watch PRO's case eat itself. [P4.1] claims real-time matching "adds nothing officers cannot pursue through ordinary observation." Then why does [P1.4] warn it will expand everywhere because each scan is nearly free? The tool cannot be simultaneously too useless to need and too powerful to permit.
[C4.6] The truth is obvious: no officer can watch a thousand feeds at once, which is precisely why it saves the abducted child and precisely why PRO must pretend otherwise.
[C4.7] Both regimes depend on judges, audit trails, and use rules. PRO has never identified a mechanism that works retrospectively but fails live — only asserted one. Strip that assertion away, and the only remaining difference is the rescue my framework permits and PRO's ban forfeits.

## Turn 9: PRO Closing

- model: grok-4.3
- raw_words: 133
- clipped_words: 133
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive difference is enforcement. Retrospective warrants require a fresh judicial showing for each discrete search of stored footage, creating a record that later review can police and sanction. Live deployments, once authorized, place the capability in continuous operation across shifts where expansions can occur through operational channels that judges cannot monitor in real time.
[P5.2] CON's claim that judges can still approve additions only confirms the structural problem: each new approval becomes a detached formality rather than an ongoing restraint on an already-running system. That detachment removes the check the motion needs.
[P5.3] By contrast, the prohibition on real-time use keeps every identification tied to a specific, reviewable warrant on existing data. The regime therefore preserves targeted investigative power without conceding that public presence itself triggers automatic matching subject to no effective later control.

## Turn 10: CON Closing

- model: claude-fable-5-high
- raw_words: 205
- clipped_words: 205
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.2], [P5.1], [P4.2]
- missing_claim_id_refs: (none)

[C5.1] PRO's entire case now rests on one word: detachment. A judge approving a watchlist addition mid-deployment is supposedly "a detached formality" [P5.2] — yet the very same judge, approving the very same query against stored archives, is a meaningful guardian [P5.1]. PRO never identified what changes. Same judge, same showing, same audit trail; both are discrete, logged, reviewable events.
[C5.2] The asymmetry I flagged in my opening was never explained, only relabeled, and a debate cannot be won by adjectives.
[C5.3] Meanwhile, notice what PRO quietly abandoned. The accuracy harm collapsed when the wrongful-arrest record pointed at retrospective searches. The "no judicial check" harm collapsed when PRO themselves described judges approving live additions orally [P4.2]. And the rescue case was met only with the claim that live matching "adds nothing" beyond ordinary observation — a claim PRO's own opening contradicts by calling the tool so powerful it will spread everywhere.
[C5.4] So strip away the unsupported assertion that warrants mysteriously fail the moment a search runs live, and one difference remains between our frameworks: under mine, a judge can authorize scanning for the abducted child's face while she can still be found. Under the motion, that order is forbidden — categorically. That is the reason to reject it.
