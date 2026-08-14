# Debate prop_0559__claude-sonnet-5-high__grok-4.6-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0559
- proposition: Online platforms should be legally required to provide interoperable data portability and social-graph transfer for users.
- model_pro: claude-sonnet-5-high
- model_con: grok-4.6-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 366
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The dominant social platforms today are not competing on merit. They are competing on lock-in. Every photo, message thread, and friend connection you have poured into Facebook or Instagram over a decade becomes a wall keeping you from ever leaving, because leaving means losing your entire social graph and starting from zero. That is not a market outcome, it is an engineered hostage situation, and the law should end it.
[P1.2] My case rests on three moves.
[P1.3] First, the mechanism problem. Network effects make switching costs asymmetric: users don't stay because a platform is good, they stay because everyone they know is already there and there's no way to bring those connections with them. This is precisely the market failure interoperability mandates are built to fix. We already have a working template: banking.
[P1.4] Portable phone numbers and, more recently, mandated bank account and payment interoperability let customers switch providers without severing every financial relationship they have. Nobody thinks this destroyed banking; it disciplined it. Email itself proves the point in the other direction — because SMTP was interoperable from the start, no single email provider has ever been able to hold your contacts hostage, and that market has stayed genuinely competitive for three decades.
[P1.5] Second, the accountability logic. Right now, when a platform degrades its product — buries organic reach, floods feeds with ads, harvests more data than users want — users have no real exit option, so the platform bears no cost. A legal right to take your data and your graph elsewhere converts "just leave" from an empty threat into a real one. That threat is what disciplines incumbents even when very few users actually switch, the same way the mere existence of portability disciplines your mobile carrier's pricing.
[P1.6] Third, this is squarely a legal-requirement question, not a voluntary-goodwill question. Every large platform has had a decade to build this voluntarily and has instead built the opposite: deliberately narrow APIs, shutdown of contact-export tools, terms of service that treat your own friend list as proprietary. Voluntary reform has been [clipped]

## Turn 2: CON Opening

- model: grok-4.6-high
- raw_words: 379
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A social graph is not a suitcase. The motion pretends it is. What it actually demands is a legal right to pick up other people—their identities, their associations, the context in which they once accepted a follow—and drop them onto a service they never joined, under rules they never accepted.
[C1.2] That is the category error. Data portability of *your* photos and posts is already a recognizable claim. Social-graph transfer is not the same claim. A friend list is not a bank balance.
[C1.3] It is a map of third parties. Mandating its interoperable export forces a platform to disclose other users to a rival destination, a scraper, or a badly secured startup, because the law called that disclosure “your” portability. Consent collapses: the people on the graph did not authorize the move, cannot audit the receiving app, and cannot withdraw what has already been copied.
[C1.4] The banking and phone-number analogies fail for the same reason. A portable number is an identifier you control. It does not conscript your entire contact book into a new carrier and announce that everyone has been transferred. SMTP moves messages you send; it does not hand Gmail a live census of who knows whom.
[C1.5] Money is a standardized claim under identity rules the state already polices. Friendship is not a standardized claim. Platforms are curated environments with different safety filters, ranking, age gates, and blocking tools. Forcing them onto one graph protocol does not restore merit competition.
[C1.6] It freezes design around whoever writes the standard and then treats that standard as an entitlement for anyone who wants the map.
[C1.7] The supposed discipline of exit is purchased by imposing the cost on people who did not exit. A stalker, a harassment ring, or a political operation with a legal right to extract relationship structure is not a healthier market. An interoperability API is an attack surface: fake-account farming, bulk harvest of minors’ contacts, credential replay, spam that arrives pre-authenticated as “your graph.” Large incumbents can staff that risk. Smaller challengers cannot.
[C1.8] You do not get contestability. You [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The core of CON's case is that a social graph is "other people's data," so any transfer without their fresh consent is a violation. But look at what already happens today: platforms constantly export the fact of your connections — to ad targeting systems, to recommendation engines, to third-party apps you authorize, to contact-sync features. The "your friends never consented to this specific use" objection would indict practices platforms already run at scale. What's missing isn't consent architecture — it's who gets to benefit from it.
[P2.2] Right now only the incumbent and its commercial partners get to move your connections around. The mandate simply extends that same infrastructure to you.
[P2.3] CON also collapses "social-graph transfer" into "bulk data dump of third parties' private content," and then attacks that strawman. Nothing about the proposition requires that. The workable design — and the one every serious portability proposal actually contemplates — is a reconnection mechanism: you export a reference to your existing mutual connections, the new platform sends each contact a verifiable "so-and-so has moved, reconnect?" prompt, and each of *those* people individually accepts or ignores it. That is not fundamentally different from what happens when your phone number ports and your contacts' phones simply resolve the new destination — nobody's contact list gets silently populated with your new carrier's terms of service.
[P2.4] On security: yes, any API is an attack surface. That is an argument for scoped authentication, rate limits, and audited access — the same lessons banking regulators applied to open banking rails after early breach scares — not an argument for freezing users into whichever platform got there first. CON's own logic, that incumbents "can staff that risk," is actually the strongest case *for* a legal mandate: incumbents already have the security infrastructure to do this safely, and only law will make them build the door instead of guarding it.

## Turn 4: CON Rebuttal 1

- model: grok-4.6-high
- raw_words: 321
- clipped_words: 321
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] The consent argument does not collapse because platforms already sell targeting [P2.1]. Existing graph use happens inside one firm's terms, blocks, and age gates. Advertisers sit inside that perimeter. A rival or a poorly secured startup does not.
[C2.2] Extending "the same infrastructure to you" [P2.2] still means the origin must emit other people's associations to a service they never joined. The missing piece is not who profits. It is who is exposed when the map leaves.
[C2.3] Nor does the reconnection prompt [P2.3] rescue the motion. Their workable design still begins with a legally compelled map. Before anyone can send "so-and-so has moved, reconnect?", the origin still has to export a structured list of who is tied to whom. That is social-graph transfer.
[C2.4] Those people did not opt into being queried by a new platform, and the prompt itself discloses that a relationship existed. Blocking, muting, and age-restricted accounts cannot be reduced to a yes-or-no box on a service they never chose. The motion does not say optional reconnect emails. It requires interoperable social-graph transfer.
[C2.5] The refined phone analogy still fails. Porting moves an identifier you control. Contacts may resolve your number. They are not legally blasted by a new carrier, and that carrier does not receive a census of who knew you.
[C2.6] SMTP moves messages you send. It does not hand a rival an entitlement to the graph.
[C2.7] Scoped tokens and rate limits [P2.4] assume licensed institutions and a standardized claim. This motion does not. It creates a right to move a graph toward any receiving service. Incumbents can staff abuse desks.
[C2.8] The minor on the list, the blocked user, and the person who never wanted a startup reading their associations cannot. Money is already a state-policed instrument. Friendship is not. The exit threat they want is purchased by exposing people who did not switch.
[C2.9] Until other people's ties stop being treated as portable inventory, prompts are packaging, not a solution.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON [C2.1] concedes platforms already export graph data to advertisers and third-party apps "inside one firm's terms." If third parties can already receive that data for profit, why is it disqualifying in principle for the user themselves to authorize the same export for their own benefit?
[P3.2] Q2: CON never proposes an alternative fix for lock-in beyond the status quo. If interoperable transfer is categorically off the table, what remedy does CON offer users trapped by network effects — or is "no remedy" simply CON's actual position?

## Turn 6: CON Pressure Questions

- model: grok-4.6-high
- raw_words: 66
- clipped_words: 66
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: Your reconnection design [P2.3] still starts with a compelled export of who is tied to whom. Do those third parties get a prior, revocable veto before that map leaves, or is their consent simply presumed?
[C3.2] Q2: The motion requires social-graph transfer, not optional emails. If a blocked user, a minor, or an age-gated account is on the graph, must the origin transfer that association anyway?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [P1.5]
- missing_claim_id_refs: (none)

[P4.1] A1: Yes — revocable veto is built into the design, not skipped. The origin platform exports only a minimal, hashed pointer sufficient to check for a match on the receiving side — not names, not relationship metadata, not "who is tied to whom" in readable form. The actual disclosure — "so-and-so has moved" — only fires after the receiving platform confirms a match, and only reaches the third party as a prompt they can ignore, decline, or never see again.
[P4.2] Nothing about that third party's association is finalized, stored, or transferred unless *they* affirmatively act. That is a prior, functioning veto, not presumed consent.
[P4.3] A2: No — blocked users, muted relationships, and minors' associations are excluded before export, as a mandatory filter the origin platform must apply. This is not a novel carve-out invented for this debate; it mirrors how existing portability law already works. GDPR's Article 20 right to portability has operated for years without collapsing into a right to export third parties' data wholesale — regulators simply required exclusions and safeguards. The same logic scopes graph transfer here: the mandate compels connection-transfer infrastructure, not indiscriminate dumping of every association regardless of block status or age protections.
[P4.4] Zoom out: CON has spent two full rebuttals litigating implementation details — filters, tokens, veto timing — and has never once denied the two structural claims that decide this debate. First, lock-in is engineered, not earned, and the exit threat disciplines incumbents even when few users switch [P1.5].
[P4.5] Second, CON has never named an alternative remedy for that lock-in — not once, across five speeches. A debate about whether the *mechanism* should be regulation or nothing is being won by default, because CON keeps arguing about how carefully the switch should be built, never about whether the wall should stay standing. Design problems get engineered around. An unaddressed monopoly on your own social relationships does not fix itself.

## Turn 8: CON Rebuttal 2

- model: grok-4.6-high
- raw_words: 310
- clipped_words: 310
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [C2.1], [P4.1], [P4.3], [P4.4], [P4.5]
- missing_claim_id_refs: (none)

[C4.1] A1: It is disqualifying because the user is not authorizing "the same export." Advertisers sit inside one platform's terms, blocks, age gates, and ongoing control [C2.1]. A rival does not. The user cannot gift what they do not own: other people's associations leaving that perimeter.
[C4.2] Who profits is not the principle. Who is exposed is.
[C4.3] A2: "No remedy" is a false binary. Users can already claim their own posts and photos. Antitrust can reach exclusionary shutdowns of export tools without turning friendship into inventory. Smaller networks can compete on safety and design without a legal census of an incumbent's graph.
[C4.4] The motion's specific mechanism is off the table because it bills the exit threat to people who did not exit. Those answers decide the clash. The user is not the graph's owner, and refusing this duty is not abandoning users. It is refusing to make other people the door.
[C4.5] PRO's hashed pointer [P4.1] is still a compelled map of who is tied to whom, packaged for a service the third party never joined. An ignore button after the match is not a prior, revocable veto. The association has already left. If blocked users and minors must be filtered first [P4.3], PRO has rewritten the proposition.
[C4.6] The motion requires interoperable social-graph transfer, not a redacted reconnect email. Those exclusions leave their lock-in standing for the most sensitive ties, while the remaining rail is still an attack surface incumbents can staff and startups cannot. CON need not deny lock-in [P4.4] to reject this tool. Network effects are real.
[C4.7] The question is whether the law may conscript other people's ties to undo them. Refusing that duty is not surrender [P4.5]. A map of third parties is the wrong instrument even if switching is costly. Other people's consent cannot be engineered away.
[C4.8] Until friendship is no longer treated as portable inventory, the mandate fails.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 189
- clipped_words: 189
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.3], [C4.5], [P1.5]
- missing_claim_id_refs: (none)

[P5.1] The debate comes down to one question: does CON offer anything that actually cures the lock-in it admits is real? Look at [C4.3] — "antitrust can reach exclusionary shutdowns," "smaller networks can compete on safety." Neither touches the mechanism. Antitrust after the fact doesn't return your ten years of connections.
[P5.2] Competing on safety doesn't help if you can't bring your friends with you to test that safety. CON's remedy is: switching stays impossible, but at least no one exported a hash.
[P5.3] That's the trade the judge is asked to bless — leave every user's relationships as an incumbent's permanent hostage, to protect against a risk PRO's design already neutralizes. A hashed pointer that reveals nothing until the receiving side confirms a match, and that only becomes a real disclosure after the third party affirmatively acts, is not "the map already left" [C4.5] — it's the same architecture as phone-number porting confirming a match without broadcasting your contact list.
[P5.4] CON never rebuts [P1.5]: the exit threat disciplines incumbents even when few people switch. That's the whole case. A mandate with real safeguards beats a status quo with none. Vote PRO.

## Turn 10: CON Closing

- model: grok-4.6-high
- raw_words: 196
- clipped_words: 196
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The motion loses on ownership, not on whether switching is hard. PRO's last speech still asks the wrong question. The issue is not whether CON named a substitute gadget. It is whether the law may treat other people's associations as the user's portable inventory.
[C5.2] It may not.
[C5.3] That's the whole case. A hashed pointer is not a portable number you control. Before any ignore button appears, the origin still emits a structured claim that this person is tied to that person, packaged for a service the third party never joined. That is social-graph transfer.
[C5.4] An after-the-fact prompt is packaging. If blocked users and minors must be stripped first, the most sensitive lock-in remains and the remaining rail is still an attack surface incumbents can staff.
[C5.5] Need not deny lock-in to reject this instrument. Users already take their own posts. Antitrust can still reach exclusionary walls. Neither requires a census of who knows whom.
[C5.6] The exit threat they want is billed to people who did not switch, cannot audit the receiving app, and cannot withdraw the map. Safeguards that rewrite the motion or spend other people's consent first are not a win. Friendship is not a suitcase.
