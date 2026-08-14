# Debate prop_0559__grok-4.6-high__claude-sonnet-5-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0559
- proposition: Online platforms should be legally required to provide interoperable data portability and social-graph transfer for users.
- model_pro: grok-4.6-high
- model_con: claude-sonnet-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: grok-4.6-high
- raw_words: 259
- clipped_words: 259
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Users do not own the platforms they inhabit, but they should own the relationships they built there. A handful of firms treat the social graph as private infrastructure. Leave Instagram and the audience evaporates. Leave a messenger and years of ties become a static export.
[P1.2] That is not a market. It is captivity.
[P1.3] Legal interoperability and social-graph transfer end the captivity. A photo dump is not portability. Users need the right to move identity, contacts, and follow-relationships to a competing service, with consent, through standardized interfaces. Without the graph, “portability” is a souvenir of a life you are not allowed to take with you.
[P1.4] Platforms will not volunteer this. The graph is their moat. Number portability had to be mandated because carriers would never surrender lock-in. The same incentive problem exists here.
[P1.5] Absent a legal duty, incumbents keep people by making exit painful, then extract rents from trapped attention.
[P1.6] The gains are practical. A new service can compete on design, moderation, and privacy instead of starting at zero friends. Users can abandon a feed that degrades, a firm that mishandles data, or a product that fails against harassment without orphaning their communities. Exit with your graph is the disciplinary force these markets lack.
[P1.7] Third-party privacy is a design constraint, not a veto. Transfers can require consent, scoped access, and the same notice already used when someone joins an app and finds existing contacts. The status quo is worse: it concentrates power and lets a few firms set the terms of association. Human connections should not be non-transferable corporate assets.

## Turn 2: CON Opening

- model: claude-sonnet-5-high
- raw_words: 347
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The social graph is not one person’s property to hand over. It is other people’s data. When you export your contact list or follower relationships, you are exporting the private associations of everyone connected to you — most of whom never consented to being ported to a new platform, a new jurisdiction, or a new business model. Consent from the exporting user cannot substitute for consent from the exported.
[C1.2] This is not a minor implementation detail to smooth out with “scoped access”; it is the core reason large-scale graph transfer has already produced real harm. The Cambridge Analytica scandal existed precisely because a portability-style API let one user’s permission unlock millions of friends’ data. Mandating this at platform scale, by law, for every competitor who wants an audience, does not fix that problem — it institutionalizes it.
[C1.3] Standardized transfer interfaces are also a gift to exactly the bad actors PRO wants to protect users from: scrapers, stalkers, spammers, and abusive ex-partners. A “right to move your graph” is indistinguishable, technically, from a mandated bulk-export pipeline. Once you build the pipe for legitimate competitors, you have built it for harassment campaigns and data brokers too. Platforms currently spend enormous resources preventing exactly this kind of graph-scraping; a legal mandate forces them to build the very door security teams have been trying to wall shut.
[C1.4] There is also a competition paradox at the heart of PRO’s case. Interoperability mandates require standardized protocols, audit regimes, and compliance infrastructure. Building and maintaining that machinery is expensive. Meta and Google can absorb it easily; the scrappy two-year-old challenger PRO wants to enable cannot.
[C1.5] We have already watched this play out with GDPR-style data rules, which entrenched incumbents even as they were sold as pro-user reforms. A legal portability mandate does not dismantle the moat — it just makes incumbents the toll collectors on the new bridge.
[C1.6] Nothing here requires a government mandate to fix. Voluntary standards, targeted antitrust action against genuine anticompetitive lock-in, and existing data-export rights already address the real problem without forcing the [clipped]

## Turn 3: PRO Rebuttal 1

- model: grok-4.6-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON’s privacy claim treats a public follow as a secret. When someone follows you, that tie is already displayed, already used for recommendations, already copied into contact-matching. What CON forbids is not handing over other people’s diaries. It is letting you take the same visible relationship to a rival.
[P2.2] If “other people’s data” really vetoed transfer, platforms could not show follower lists, suggest mutual friends, or grow by importing address books. They do all of that for themselves. The veto applies only when you try to leave.
[P2.3] [C1.2] folds a covert harvesting abuse into the entire idea of exit. Cambridge Analytica was not a user moving, with consent, to a competing service. It was an app vacuuming profile fields the host should never have exposed. That is an access-control failure, not proof that authenticated, purpose-limited graph transfer “institutionalizes” the scandal.
[P2.4] Ban every interface that was once abused and incumbents would also have to wall off the pipes they use to recruit.
[P2.5] The stalker hypothetical does the same work. [C1.3] assumes the law requires an unauthenticated bulk pipe. Identity checks, rate limits, scoped consent, and recipient authentication are design conditions, not reasons to keep communities hostage. Incumbents already spend to stop scrapers while hoarding the graph inside the castle.
[P2.6] CON’s answer is to leave the castle standing.
[P2.7] [C1.4] and [C1.5] invert the cost. Recreating millions of relationships from nothing is what kills challengers. A receiving app does not need Meta’s legal department to accept a user’s consented follows. The expensive party is the incumbent told it cannot hoard the exit.
[P2.8] Number portability did not entrench the largest carrier; it made leaving that carrier possible. Paperwork is not the comparison. Lock-in is.
[P2.9] Voluntary standards and souvenir exports leave the moat untouched, because the graph is the product. Without a duty to transfer it, incumbents remain toll collectors on the only road that matters: your friends.

## Turn 4: CON Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [P2.1], [P2.3], [P2.5], [P2.7], [P2.8]
- missing_claim_id_refs: (none)

[C2.1] CON's opponent wants you to believe a public follow is just a light switch anyone can flip for you. But visibility to a friend, or to a platform's recommendation engine, is not the same as consent to bulk-export that relationship to an unknown third-party service, under a different privacy policy, in a different jurisdiction, forever. [P2.1] collapses "I can see this" into "I consented to this being moved," and that collapse is exactly what enables the harm.
[C2.2] On Cambridge Analytica, [P2.3] says this was "access-control failure," not proof against mandated transfer. But look at what the law PRO wants would create: a standardized, legally guaranteed pipeline through which one user's consent extracts data about everyone connected to them, built to spec, audited for compliance, available to any company that registers as a competitor. That is not a bug fix. That is CA's mechanism, legislated into permanence and handed to every new entrant, good or bad, who wants an audience.
[C2.3] [P2.5] waves this away as "design conditions" — identity checks, rate limits, scoped consent. Fine in a slide deck. In practice, verifying that a "receiving app" is legitimate, that its recipient authentication is real, that its data handling matches the exporting platform's promises to the *other* people in the graph — that is an enforcement nightmare no regulator has solved, and PRO offers no mechanism for it beyond gesture.
[C2.4] On cost: [P2.7] and [P2.8] treat social graphs like phone numbers. They are not. A phone number is a static identifier. A social graph is layered relational data — who follows whom, what groups, what inferred intimacy — and standing up compliant, audited transfer infrastructure for that is far more expensive than routing a number.
[C2.5] That compliance burden falls hardest on the challenger PRO claims to be helping, while incumbents absorb it as a cost of doing business and keep their scale advantage anyway.

## Turn 5: PRO Pressure Questions

- model: grok-4.6-high
- raw_words: 72
- clipped_words: 72
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: [C2.1] says seeing a follow is not consent to move it. Then why may platforms already display follower lists, suggest mutual friends, and import address books for growth, while the user cannot take that same visible tie to a rival?
[P3.2] Q2: [C2.2] treats any mandated pipeline as Cambridge Analytica made permanent. What concrete exit mechanism would you accept that actually transfers the graph, rather than leaving users with a souvenir export?

## Turn 6: CON Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 81
- clipped_words: 81
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO's "identity checks, rate limits, scoped consent" require verifying every receiving platform's compliance before releasing other people's relational data — who bears legal liability when a "competitor" turns out to be a scraper or data broker, the exporting platform or the mandate itself?
[C3.2] Q2: If compliance infrastructure must be robust enough to prevent another Cambridge Analytica, how does that same infrastructure remain cheap enough for PRO's "scrappy two-year-old challenger" to build, rather than becoming another moat only incumbents can afford?

## Turn 7: PRO Rebuttal 2

- model: grok-4.6-high
- raw_words: 317
- clipped_words: 317
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C3.1], [C3.2], [C2.1], [C2.2]
- missing_claim_id_refs: (none)

[P4.1] A1: The recipient that exceeds scope or turns out to be a broker bears primary liability, just as an app does today when it abuses an API. The exporter is liable only if it releases the graph without authenticating the user and a registered destination. [C3.1] makes this sound unsolvable by imagining a nameless dump. Payment networks already assign fault after a verified transfer; they do not ban wires because a merchant might later launder money.
[P4.2] Platforms already share relational data with advertisers and contact importers. They do not get a special liability crisis only when the destination is a rival.
[P4.3] A2: The challenger does not stand up the incumbent's export plant. It receives a consented, scoped follow list. Anti-abuse and registry checks belong on the side that already holds the graph. [C3.2] loads Meta's full stack onto the two-year-old challenger, then calls the result a moat.
[P4.4] Starting at zero friends is the actual killer. Accepting an authenticated ingest is cheaper than rebuilding a community from a photo dump.
[P4.5] CON's questions only work if the choice is an open firehose or captivity. It is not. [C2.1] still treats a visible follow as a secret the moment you try to leave. [C2.2] still recasts Cambridge Analytica — covert harvesting of profile fields — as any legal exit.
[P4.6] If a platform can display followers, suggest mutuals, and import address books for itself, it can authenticate a competitor the way it authenticates its own growth partners. Liability and cost fall on the party that fails its duty, not on users who want their communities. Until CON names a transfer that actually moves the graph, its case is a veto dressed up as caution. Asked for a real exit, it offered liability riddles.
[P4.7] Users still cannot leave a degrading feed without orphaning an audience. A souvenir ZIP file does not discipline anyone. Exit with relationships is the force this market lacks.

## Turn 8: CON Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 314
- clipped_words: 314
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Display and import are not the same as export, because they happen inside the accountability boundary the exported-to person actually agreed to. When someone follows you on Platform X, they consented to visibility under X's privacy terms, X's moderation, X's jurisdiction. A mandate to move that tie to Platform Y breaks that chain — Y never made the promises the follower relied on. Platforms can show followers to *themselves* and import address books for *their own* growth because the accountable party doesn't change.
[C4.2] Interoperability legislation forces a data hop across accountability lines that the original consent never covered.
[C4.3] A2: We'd accept exactly what already exists in most GDPR-style regimes — a user exporting their own content and their own list of accounts they follow, where the recipient of the export is the user, not a competing platform's ingest pipeline. What we reject is the standardized, legally mandated, bulk graph-*reconstruction* infrastructure PRO wants, where a rival firm receives structured relational data about thousands of other people and rebuilds the network on its own servers. PRO calls the first a "souvenir" and demands the second.
[C4.4] The second is the CA mechanism, legislated.
[C4.5] PRO's answer to my questions in [P4.1]-[P4.3] just relocates the problem: liability "falls on the recipient," verified through a registry the exporting platform must police. But someone has to audit that registry, in every jurisdiction, for every startup claiming to be a legitimate competitor — that's the enforcement nightmare CON identified, unsolved, not "riddled." The payment-network analogy fails: wire transfers sit on decades of licensing and AML law; "is this a real social network" has no such regime, so the exporting platform either rubber-stamps registrants — reopening the door to scrapers — or builds gatekeeping heavy enough that only incumbents can run it.
[C4.6] Either way, PRO's mechanism produces the moat CON warned about, or the harm CON warned about. It cannot produce neither.

## Turn 9: PRO Closing

- model: grok-4.6-high
- raw_words: 193
- clipped_words: 193
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: [C4.3], [C4.6]
- missing_claim_id_refs: (none)

[P5.1] The contest is not privacy versus portability. It is whether a visible relationship may leave with the person who built it, or stay locked inside the firm that hosts it.
[P5.2] CON made the choice explicit. Display the follow, import the address book, use the graph for growth — permitted, because the accountable party does not change. Move the same public tie to a rival, and it becomes other people's data, Cambridge Analytica, an unsolvable registry. [C4.3] then names the only exit CON will allow: a list you download yourself.
[P5.3] That souvenir rebuilds nothing. It disciplines no one. It leaves the graph where the rent is collected.
[P5.4] If a follow were a secret across corporate lines, platforms could not already traffic in it. They can. The veto appears only at exit. That is not accountability.
[P5.5] It is the moat, restated as consent.
[P5.6] [C4.6] offers harm or a new moat. Those are the costs of refusing a scoped, authenticated transfer, not of requiring one. Until the graph can move, users do not have a market. They have a host.
[P5.7] A souvenir cannot punish a degrading product. Only exit with your people can. Mandate the transfer.

## Turn 10: CON Closing

- model: claude-sonnet-5-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: [P5.4], [C4.5]
- missing_claim_id_refs: (none)

[C5.1] The whole debate collapses to one unanswered question: who is accountable to the thousands of other people in the graph once it moves? PRO never answers it. [P5.4] insists a follow is already "trafficked" across corporate lines, but display and import happen inside the boundary the follower actually agreed to — the same company, the same policy, the same jurisdiction. A mandate breaks that chain and hands relational data about non-consenting third parties to a rival PRO cannot vet, because [C4.5] stands unrebutted: there is no licensing regime for "is this a legitimate competing platform," so the exporting platform either rubber-stamps registrants and reopens the door to scrapers, or builds gatekeeping only an incumbent can afford.
[C5.2] PRO calls that a false choice, then never names the third option. "Authenticate like a growth partner" is not an answer; growth partners are chosen by the platform, not owed entry by law to everyone's followers.
[C5.3] A souvenir export is imperfect. But a legally mandated pipeline that must choose between institutionalized harm and a new incumbent-only moat is not a fix — it is the same captivity, wearing a portability label. Don't mandate a dilemma.
