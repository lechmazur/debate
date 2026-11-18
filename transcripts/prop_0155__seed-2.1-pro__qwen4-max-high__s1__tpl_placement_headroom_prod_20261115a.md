# Debate prop_0155__seed-2.1-pro__qwen4-max-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0155
- proposition: Police departments should be prohibited from using face recognition in real-time surveillance, but allowed to use it for post-incident investigations with a warrant.
- model_pro: seed-2.1-pro
- model_con: qwen4-max-high
- side_swap: True

## Turn 1: PRO Opening

- model: seed-2.1-pro
- raw_words: 299
- clipped_words: 299
- claim_ids: [P1.1], [P1.2], [P1.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Real-time face recognition in routine police surveillance turns every public street, transit camera, and business feed into a persistent, automated ID checkpoint that tracks every person in view, no suspicion required. That level of constant, unblinking monitoring chills protected activity: people will think twice before attending a protest, visiting a reproductive health clinic, gathering for a religious service, or meeting a friend at a queer bar if they know an algorithm is logging their presence and tying it to their identity, no probable cause needed.
[P1.2] These systems carry well-documented higher misidentification rates for Black, Brown, and trans people, and real-time deployment means those errors trigger immediate, irreversible harm: wrongful stops, mistaken arrests, even use of force against someone who superficially resembles a low-level suspect, before any human can verify the match. This is not hypothetical: documented cases already exist of Black men wrongfully arrested due to unvetted facial recognition matches, with no check before police arrived at their homes. The narrow post-incident, warrant-backed carveout preserves the tool’s legitimate investigative value without accepting those mass surveillance harms.
[P1.3] When investigating a specific crime, police can bring probable cause to a neutral judge, who can limit face recognition searches to relevant timeframes, locations, and the specific suspect tied to that incident—exactly the guardrail we already use for wiretaps, home searches, and other intrusive investigative powers. We do not let police tap every phone line on the off chance a crime might occur, and we should not let them scan every face in public on that same flimsy basis. This split does not choose between public safety and civil liberties; it draws the line where the Fourth Amendment always has: individualized suspicion, reviewed by a court, for targeted searches after a crime is alleged, not dragnet monitoring of everyone going about their lives.

## Turn 2: CON Opening

- model: qwen4-max-high
- raw_words: 299
- clipped_words: 299
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Look at what this motion forbids. A child is taken from a schoolyard; an hour later a camera at the bus terminal may hold her face. Police cannot run that live feed against the abductor's photo, because no judge can be reached in time. But next week, with a warrant, they may scan every face recorded at last month's protest.
[C1.2] The narrow, urgent, single-target search is banned; the broad retrospective sweep of thousands of innocent people is licensed. That is not the Fourth Amendment's line. It is a clock.
[C1.3] A warrant does not supply what my opponent says it supplies. Individualized suspicion attaches to the suspect, not to the gallery. When police run one photo against a million stored faces, the algorithm examines a million people who are suspected of nothing, and the judge's "timeframe and location" limits do not change that. Post-incident searching is the dragnet, moved indoors and given a timestamp.
[C1.4] The chilling effect survives: what frightens the protester or the clinic patient is not being identified this second, it is being identifiable forever.
[C1.5] And the wrongful arrests my opponent invokes are not stories about live street scans. The reported cases began with a stored image from an old crime run against a database, an unvetted match, and officers who treated a software guess as an identification. Those are post-incident investigations — precisely what this motion authorizes. The failure was verification, not latency.
[C1.6] A rule that requires corroboration before any stop fixes it. A rule that makes detectives wait three days for a signature does not.
[C1.7] Real-time use can be the most constrained application imaginable: one imminent threat, one named suspect, one venue, an alert to a human being who must confirm before anyone is touched. Banning that while permitting bulk retrospective searches gets the trade backwards.

## Turn 3: PRO Rebuttal 1

- model: seed-2.1-pro
- raw_words: 297
- clipped_words: 297
- claim_ids: [P2.1], [P2.2], [P2.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The opposing side’s abduction hypothetical deliberately misdescribes what this rule permits and forbids. It does not block narrow, targeted searches for a named, dangerous suspect during an active imminent threat—exigent circumstances are a longstanding, well-settled exception to warrant requirements for exactly those split-second, life-or-death scenarios. What it bans is the always-on, citywide, camera-by-camera real-time surveillance running 24/7 that logs every passerby against loose, unvetted watchlists before any crime is reported, exactly the persistent deployments cities have already rolled out on transit lines and street corners.
[P2.2] The claim that a warrant lets police “scan every face recorded at last month’s protest” is equally false. A warrant requires particularized probable cause tied to a specific crime, limiting searches to relevant timeframes, locations, and suspect descriptions; a judge will not sign off on a fishing expedition through unrelated protest footage to identify random attendees any more than they will sign a warrant to search every home on a block for one stolen bike. The documented wrongful facial recognition arrests my opponent cites were warrantless, unvetted post-incident searches with zero judicial check—the exact practice this rule eliminates, by requiring a neutral magistrate to sign off before any search runs, and to enforce mandatory human corroboration before any stop or arrest.
[P2.3] The chilling effect difference is not trivial. People do not avoid protected protest, reproductive care, or queer gathering spaces merely because footage exists; they avoid those spaces when they know an automated system is scanning, logging, and flagging them in the moment, every time they leave home, with no trigger and no oversight. My opponent’s proposed “corroboration rule” provides no real guardrail: when a system is always running, officers will chase hundreds of low-quality false matches in real time against people who have done nothing wrong before meaningful verification can happen.

## Turn 4: CON Rebuttal 1

- model: qwen4-max-high
- raw_words: 299
- clipped_words: 299
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] Notice what just happened. To save the post-incident side, my opponent wrote in two guardrails the motion never contains: "mandatory human corroboration" and an exigency exception for live threats. Neither appears in the text we are debating. The motion bans real-time face recognition and permits warrant-backed retrospective searches.
[C2.2] Exigent circumstances excuse a warrant; they do not repeal a prohibition. Under this rule the bus-terminal feed stays unsearched while the child is still missing — and next month's protest footage gets scanned with a signature.
[C2.3] Take the corroboration concession seriously, though, because it decides this debate. If human verification before any stop is the fix, it is the fix in both modes. The wrongful arrests were not caused by a match arriving quickly; they were caused by officers treating a candidate list as an identification. That failure has nothing to do with the age of the image.
[C2.4] My opponent has conceded the real safeguard is verification, not latency — then attached it to only one side of the clock.
[C2.5] On warrants: probable cause attaches to the suspect, never to the gallery. A judge signing a warrant to find one riot suspect in a crowd authorizes examining ten thousand faces belonging to people suspected of nothing. That is the general warrant's structure — search many to find one — dressed in paperwork. And the protester's fear is not the flicker of a live alert; it is knowing the state can run her face against every open case, forever.
[C2.6] Finally, "hundreds of low-quality false matches" is a gallery-and-threshold problem. A bloated watchlist produces hundreds of false candidates whether the frame is live or from last Tuesday.
[C2.7] The line should be drawn at scope, target quality, and corroboration. This motion draws it at a timestamp, and licenses the dragnet on the far side.

## Turn 5: PRO Pressure Questions

- model: seed-2.1-pro
- raw_words: 78
- clipped_words: 78
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You claim exigent circumstances cannot apply to this real-time ban, but every other Fourth Amendment rule already allows narrow warrantless action for imminent, life-threatening harm—why would facial recognition be the only police tool stripped of that settled exception?
[P3.2] Q2: You argue human corroboration alone prevents misuse, but how can robust verification ever keep up when always-on real-time systems spit out dozens of false matches an hour across hundreds of cameras, before any reported crime narrows the search?

## Turn 6: CON Pressure Questions

- model: qwen4-max-high
- raw_words: 73
- clipped_words: 73
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Exigency and "mandatory human corroboration" appear nowhere in the motion — are you defending the text as written, or a version you'd prefer? If corroboration is the safeguard, why does it attach only after the crime?
[C3.2] Q2: A magistrate signs before the search, not after the match. What in that signature verifies the candidate photo, or shrinks the gallery of ten thousand innocent faces the judge never had probable cause to examine?

## Turn 7: PRO Rebuttal 2

- model: seed-2.1-pro
- raw_words: 300
- clipped_words: 300
- claim_ids: [P4.1], [P4.2], [P4.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: I am defending the motion as written. Longstanding, universally applied Fourth Amendment doctrines like exigent circumstances for imminent life threats apply automatically to every search rule; we do not need to restate them in every policy text any more than we carve them out for home searches or wiretaps. The warrant requirement for post-incident use does not exclude human corroboration, either: a warrant only authorizes a narrow search, it never permits an arrest on unvetted algorithmic output, because probable cause for arrest always requires reliable, human-verified evidence that courts already enforce for every other investigative tool.
[P4.2] A2: A warrant does not require a judge to personally inspect every face in the relevant footage any more than a wiretap warrant requires a judge to listen to every second of every call before collection begins. What the judge does is shrink the gallery before the search ever runs: they limit which camera feeds are used, the narrow relevant time window, and tie the search to a specific, described suspect for a documented, already reported crime, so the system never gets to trawl the faces of every person moving through public space 24/7 on open-ended watchlists.
[P4.3] That narrowing guardrail is what makes this rule work, and what my opponent’s position entirely lacks. Their preferred “corroboration only” rule puts no limit on always-on, citywide real-time scanning that generates dozens of false matches an hour, overwhelmingly against Black, Brown, and trans people, long before any crime is reported to narrow the candidate pool. Officers cannot meaningfully verify that constant flood of alerts in the split second before they stop, confront, or use force against an innocent person. The post-incident warrant rule eliminates that permanent, chilling dragnet, while preserving the tool for targeted, bounded investigative use where verification can actually happen before anyone is detained.

## Turn 8: CON Rebuttal 2

- model: qwen4-max-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Exigency excuses a warrant; it does not authorize a forbidden technique. Cities that ban chokeholds or no-knock raids don't discover an automatic emergency exception hidden inside the ban — legislatures write exceptions when they want them. So take your pick. If the text means "prohibited," the bus-terminal feed stays dark.
[C4.2] If exigency really does apply, then real-time use is permitted under judicial or emergency authorization, and the motion is no longer a ban at all — it's the warrant rule you want for both modes, with the clock erased. You cannot claim the safety of a categorical prohibition and the flexibility of an unwritten exception.
[C4.3] A2: The flood is a design variable, not a property of speed. Watchlist size, match threshold, number of cameras — turn those knobs and dozens of alerts an hour becomes one alert a week. I have never defended always-on citywide scanning; a scope cap plus human confirmation kills the flood in both modes. That is my answer to your "corroboration only" strawman: corroboration plus scope, applied on both sides of the clock, not one.
[C4.4] Your wiretap analogy breaks precisely where it matters. Wiretap warrants carry minimization — officers must stop listening to calls that aren't pertinent. Face searching has no minimization: to find one face you must process every face. The judge's "narrow window" still puts ten thousand innocent people through the algorithm.
[C4.5] Every harm you name — unvetted matches, skewed error rates, innocent people examined — sits on the side you permit. Every safeguard you praise — one suspect, one venue, one confirmed alert — is available on the side you ban. That is not a line drawn at suspicion. It is a line drawn at a timestamp, and it points the wrong way.

## Turn 9: PRO Closing

- model: seed-2.1-pro
- raw_words: 196
- clipped_words: 196
- claim_ids: [P5.1], [P5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The deciding clash here is simple: only this rule eliminates the unique, uncorrectable harm of permanent, suspicionless real-time scanning, while preserving the tool for accountable, targeted investigative use. My opponent insists scope limits and corroboration can work just as well for real-time deployment, but that ignores a structural reality: when a system runs live across public spaces before any specific crime is reported, there is no natural anchor to narrow scope, no reliable checkpoint to enforce robust corroboration before an alert triggers a confrontational, high-stakes street stop.
[P5.2] The flood of false matches, the chilled exercise of protected public life, the disproportionate misidentification risk to Black, Brown, and trans people does not come from facial recognition matching itself—it comes from running that matching on everyone, all the time, with no trigger of an alleged crime to bound the search. The post-incident warrant requirement ties every search to a specific reported crime, a neutral judge, and a narrow, defined scope before any scan runs. That is exactly the Fourth Amendment line we have always drawn between general surveillance and legitimate investigation, and it is the only line that prevents an unaccountable, always-on ID checkpoint on every public corner.

## Turn 10: CON Closing

- model: qwen4-max-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] My opponent's closing conceded the case: the harm "does not come from facial recognition matching itself—it comes from running that matching on everyone, all the time." That is a diagnosis about scope. The motion prescribes a clock.
[C5.2] A reported crime bounds the suspect, never the gallery. Ten thousand faces still pass through the algorithm to find one, whether the judge signs on Tuesday or the alert fires Monday. Nothing in "post-incident, with a warrant" caps watchlist size, sets a match threshold, or requires corroboration before a stop. The wrongful arrests happened on the permitted side.
[C5.3] Every safeguard my opponent praised—one suspect, one venue, a human-confirmed alert—is a scope rule, available in both modes, written into neither.
[C5.4] And the emergency remains unresolved. If exigency unlocks live searching, this is just a warrant rule for both modes and the clock disappears. If it doesn't, the terminal feed stays dark while the child is still missing—and next month's protest footage gets scanned with a signature.
[C5.5] Draw the line at how many innocent people are examined and whether anyone verifies the match before a hand touches a shoulder. This motion draws it at when, and licenses the dragnet on the far side.
