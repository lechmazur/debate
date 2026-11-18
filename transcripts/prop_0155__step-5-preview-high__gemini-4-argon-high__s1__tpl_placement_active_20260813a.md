# Debate prop_0155__step-5-preview-high__gemini-4-argon-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0155
- proposition: Police departments should be prohibited from using face recognition in real-time surveillance, but allowed to use it for post-incident investigations with a warrant.
- model_pro: step-5-preview-high
- model_con: gemini-4-argon-high
- side_swap: True

## Turn 1: PRO Opening

- model: step-5-preview-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The proposition draws the one line that matters: police may watch a suspect after a crime, but they may not turn the public square into a dragnet. Real-time face recognition converts every street corner, protest, clinic, and place of worship into a checkpoint of automated suspicion. It chills lawful assembly, deters vulnerable people from seeking services, and treats every passerby as a person of interest before anything has happened. That is not investigation; it is population-level monitoring, and no administrative safeguard can undo the knowledge that you are always identifiable to the state.
[P1.2] The harm is not hypothetical. Face recognition remains demonstrably imperfect, and its errors fall hardest on women, people of color, and other groups underrepresented in training datasets. When the system runs in real time, a false match does not sit quietly in a database; it becomes an officer running toward an innocent person in a crowd. The speed of real-time deployment removes the deliberate pause that filters out bad leads, and once that officer stops you, the constitution has already been violated in practice.
[P1.3] By contrast, post-incident use with a warrant keeps the tool where it belongs: after a specific crime, with a named suspect, and under judicial review. The warrant requirement forces police to articulate probable cause and narrows the scope to the matter at hand. It preserves investigative utility without licensing mass monitoring.
[P1.4] The counterargument that real-time use merely accelerates existing investigation collapses once you see the category error. Speeding up investigation is not the same as eliminating the threshold for investigation. Real-time face recognition does not make targeted policing faster; it makes untargeted policing possible.
[P1.5] We should prohibit the panopticon and permit the probe. That is exactly what the motion proposes.

## Turn 2: CON Opening

- model: gemini-4-argon-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.1], [P1.3], [P1.2]
- missing_claim_id_refs: (none)

[C1.1] The proposition gets public safety backward at both ends: it blinds police during active, life-or-death emergencies when seconds matter, and it paralyzes post-incident investigations with a legal Catch-22.
[C1.2] First, an absolute ban on real-time recognition is reckless. [P1.1] assumes real-time use must mean an unrestricted dragnet tracking every citizen at protests or clinics. That confuses mass logging with targeted crisis deployment. When a child is abducted, a fugitive flees a mass shooting, or an armed suspect enters a transit hub, police do not need to catalog the public.
[C1.3] They need to check live feeds against a narrow watchlist of one or two faces while a life can still be saved. Under PRO’s rigid rule, police must let an abductor walk past a station camera in real time, wait until the harm is done, and only then examine the footage. Good policy bans generalized tracking while permitting real-time searches under exigent circumstances or strict judicial orders for serious violent crimes.
[C1.4] Second, PRO accidentally exposes why the motion’s warrant requirement is broken. [P1.3] claims post-incident warrants work because they happen "with a named suspect" and "probable cause." Think about that contradiction. When an unknown assailant commits an armed robbery on security footage, police compare that image against a mugshot database to find out who the suspect is.
[C1.5] If officers already had a named suspect and probable cause, they would not need facial recognition to identify the perpetrator. Requiring a probable-cause warrant just to generate an initial investigative lead from an unidentified face creates an impossible paradox: you cannot run the search until you have probable cause, which you cannot get without running the search.
[C1.6] Finally, [P1.2]’s fear of false arrests is solved by operational rules, not a broken clock: mandate independent human verification and prohibit a facial match alone from establishing probable cause to arrest. Do not ban rescuing lives in real time while locking post-incident leads behind a legal paradox.

## Turn 3: PRO Rebuttal 1

- model: step-5-preview-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.3], [C1.4], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] CON’s emergency case proves the danger, not the exception. A system that can match a “narrow watchlist” to live public feeds is still a live public-scanning system. It requires the same cameras, same network, same databases, and same officers with discretion to say “urgent now.” [C1.3]’s child-abduction scenario does not require face recognition as such; officers can watch the live feed, seal exits, follow tips, and stop people based on observed conduct. The motion does not prohibit rescue.
[P2.2] It prohibits an automated checkpoint that tells the state who each stranger is before it has any reason to know them. Once that capability exists, the watchlist will not stay one face long.
[P2.3] The supposed warrant paradox is easy to dissolve. [C1.4] says police cannot get probable cause without knowing the suspect’s name, but search warrants do not require that. After a crime, a court can authorize a narrow, defined search: compare the recorded image of the offender, taken at this place and time, against a specified, lawfully held gallery. Probable cause supports searching the gallery for the person depicted; it does not claim to prove who that person is.
[P2.4] The result is an investigative lead, not an arrest. [C1.5] collapses “identify a lead” into “establish grounds to arrest,” which the motion does not do. That is the same logic used for unknown fingerprints or biological evidence, where a warrant can authorize matching evidence without naming the criminal in advance.
[P2.5] And [C1.6]’s human-review fix is weakest exactly where real-time use is strongest. A match delivered to an officer in a crowd is not a quiet file note; it is a flashing target. The stop happens first, verification later, and the constitutional injury is the stop. Post-incident warrants preserve investigative value because time allows scrutiny.
[P2.6] Real-time surveillance is not faster investigation; it is pre-crime identification of everyone.

## Turn 4: CON Rebuttal 1

- model: gemini-4-argon-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [P1.3], [P2.3], [P2.1], [P2.2], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] In [P1.3], PRO promised post-incident warrants would require a "named suspect." Forced to confront reality, [P2.3] abandons that claim and invents a new analogy: police can get a warrant to search a mugshot gallery just as they do for "unknown fingerprints." That analogy destroys PRO's case. Police do not need a warrant to run an unknown crime-scene fingerprint or biological sample against existing police databases, nor to look through booking photos.
[C2.2] Searching records the government already lawfully holds is routine lead generation. Under [P2.3]'s revised standard—where a warrant merely notes a crime was caught on camera—the requirement becomes a bureaucratic rubber stamp that adds zero privacy protection while stalling the critical first hours of an investigation in court backlogs.
[C2.3] Meanwhile, PRO’s defense of banning real-time rescue is jarring. [P2.1] claims that during a child abduction, police do not need algorithms because human officers "can watch the live feed." No human team can simultaneously scan dozens of crowded transit-hub cameras during rush hour to spot one abductor or active shooter. Under PRO's rule, police can watch the live video and hold the suspect’s photo, yet must wait until the child is harmed—"post-incident"—before letting software find that face.
[C2.4] Nor does a targeted crisis search tell the state "who each stranger is" ([P2.2]). Ephemeral matching against a one-face watchlist never identifies passersby; non-matching faces are discarded in milliseconds without touching a broader database. And [P2.2]'s slippery slope—that watchlists inevitably balloon—contradicts PRO's own faith in legal limits. If statutes and judges can restrict post-incident searches, they can strictly restrict real-time watchlists to life-threatening emergencies, just like emergency wiretap rules.
[C2.5] Finally, [P2.5] assumes alerts go straight to patrol officers in a crowd. Standard safeguards route real-time hits to a command-center analyst who verifies the image in seconds before dispatching officers—preventing false stops without sacrificing lives.

## Turn 5: PRO Pressure Questions

- model: step-5-preview-high
- raw_words: 82
- clipped_words: 82
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4], [C2.1], [P2.3], [C1.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say non-matches are “discarded in milliseconds” [C2.4], but the system must still facially match every passerby to know they do not match. Do you deny real-time recognition is running on each person—and what keeps a “one-face” watchlist from becoming the standing database the motion bans?
[P3.2] Q2: If unknown fingerprints need no warrant against booking databases [C2.1], why is PRO’s [P2.3] gallery warrant a “Catch-22” [C1.5]? Do you object to judicial review for facial leads, or only to any post-incident limit?

## Turn 6: CON Pressure Questions

- model: gemini-4-argon-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P2.3], [P1.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: You allow officers to watch live feeds for a child abductor ([P2.1]) and trust courts to limit post-incident searches ([P2.3]): why can’t strict legal rules likewise limit real-time watchlists to active, life-threatening emergencies instead of forcing police to wait until after a victim is harmed?
[C3.2] Q2: Having abandoned [P1.3]’s impossible "named suspect" requirement, [P2.3] now demands a warrant merely to compare crime-scene video against police-held mugshots; since searching existing fingerprint databases requires no warrant, what does your rule achieve besides stalling urgent investigations in court backlogs?

## Turn 7: PRO Rebuttal 2

- model: step-5-preview-high
- raw_words: 248
- clipped_words: 248
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C3.1], [C3.2], [P2.3]
- missing_claim_id_refs: (none)

[P4.1] A1: [C3.1] assumes legal limits alone can make real-time recognition safe. They cannot. To alert on one wanted suspect, the system must extract and compare the faces of everyone crossing the camera, then discard nonmatches; that is continuous biometric triage of the public, not officer judgment. A “life-threatening only” exception does not change the architecture or the standing capability: once live scanning exists, officials decide what is urgent, watchlists grow, and ordinary people become identifiable to the state before any suspicion attaches.
[P4.2] PRO still permits manual live response—watch the feed, seal exits, follow tips, stop observed conduct. It bans automated identification, not rescue.
[P4.3] A2: [C3.2] misdescribes the warrant. [P2.3] never required a named suspect; it authorizes a narrow search of a specified gallery using a recorded image from a particular crime. Unlike routine fingerprint lead generation, face recognition can be aimed at the public everywhere, so the warrant is the boundary that keeps it retrospective, event-triggered, and judicially reviewed. Fingerprint databases compare physical evidence after custody; they do not scan strangers as they walk.
[P4.4] The rule therefore prevents gallery creep and fishing without demanding impossible probable cause, and expedited judicial review remains available for violent crime.
[P4.5] CON’s case depends on confusing a rare emergency with continuous surveillance. Even if emergency real-time matching could save a life, the proposition preserves post-incident investigative power while rejecting a standing capability to identify everyone. The decisive comparison is an event-limited probe versus a panopticon. PRO bans the latter and keeps the former.

## Turn 8: CON Rebuttal 2

- model: gemini-4-argon-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.2], [P1.3], [P4.3], [P2.3], [P4.1], [P4.4], [P4.5]
- missing_claim_id_refs: (none)

[C4.1] A1: Software ephemerally checks passersby against a single photo in volatile memory just as an officer holding a photograph visually checks every face in a crowd ([P4.2]) to see who is not the abductor. Because non-matches are never logged or matched to a name database, the state never learns who any stranger is. What stops a one-face watchlist from becoming a standing database? The exact mechanisms PRO trusts post-incident: statutory bans, hard-coded software limits, audit logs, and emergency judicial sign-offs modeled on wiretap laws.
[C4.2] A2: Probable-cause warrants normally require specific reason to believe a target is in a database—which is why [P1.3] explicitly promised warrants "with a named suspect," a claim [P4.3] now falsely denies making. When [P2.3] redefines "warrant" to mean merely noting a crime was filmed, the Catch-22 becomes hollow bureaucratic delay. We support strict post-incident limits—audit logs, human verification, and barring arrests on facial matches alone—without freezing routine booking-photo lookups in court queues.
[C4.3] These answers expose the fatal contradiction in PRO’s case. In [P4.1], PRO claims laws and courts are powerless to stop an emergency one-face search from expanding into mass surveillance; yet in [P4.4], PRO insists those exact same courts and laws reliably prevent "gallery creep" after the fact. If legal guardrails work after a crime, they can likewise restrict real-time watchlists to active, life-threatening crises.
[C4.4] Meanwhile, [P4.3] defends the post-incident warrant by claiming fingerprint checks do not "scan strangers as they walk." Neither does a post-incident mugshot search. Comparing one crime-scene image against existing booking photos is identical to running an unknown crime-scene fingerprint; requiring a warrant merely stalls investigations during the critical opening hours.
[C4.5] Ultimately, [P4.5] makes a chilling concession: "Even if emergency real-time matching could save a life," PRO bans it anyway. Forcing police to wait until an abducted child is harmed before letting software spot the kidnapper, while tying post-incident leads in red tape, gets public safety backward at both ends.

## Turn 9: PRO Closing

- model: step-5-preview-high
- raw_words: 206
- clipped_words: 206
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON’s final case treats a live scan of the public like an officer glancing at a photo in a crowd. It is not. To find one face, the system must process every passerby; nonmatches are compared and discarded. That is the capability PRO bans: standing power to identify strangers before suspicion exists.
[P5.2] Once that machinery exists, urgency is whatever officials declare, and a one-face watchlist is a promise, not a structural limit.
[P5.3] The supposed contradiction fails. PRO does not trust courts equally before and after a crime. Post-incident review is anchored to a recorded image, a place and time, and a specified gallery; a judge can see scope and stop fishing. Real-time emergency authority is vague, fast, and aimed at everyone, so legal limits are weakest where CON wants them strongest.
[P5.4] The warrant still matters: it need not name the suspect in advance, but it particularizes the search, prevents gallery creep, and creates a record. Fingerprint or booking-photo comparison does not scan strangers as they walk.
[P5.5] CON would keep a permanent biometric checkpoint for rare emergencies. PRO keeps urgent human response—watch feeds, seal exits, follow tips—and uses recognition only after a crime under judicial review. Prospective identification of everyone loses to retrospective investigation of a suspect.

## Turn 10: CON Closing

- model: gemini-4-argon-high
- raw_words: 190
- clipped_words: 190
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.3], [P5.1], [P4.5], [P5.4]
- missing_claim_id_refs: (none)

[C5.1] The proposition fails because it confuses a tool with its abuse, sacrificing lives during active crises to prevent a privacy harm that targeted rescue never causes.
[C5.2] In [P5.3], PRO claims legal limits work post-incident because courts have "a recorded image, a place and time, and a specified gallery," whereas real-time emergencies are too vague. That distinction collapses. When a child is abducted or a shooter flees into a station, a crime has already occurred: police have a specific crime, a recorded image, and a gallery of one face.
[C5.3] Checking live feeds against that single photo cannot grant "power to identify strangers" ([P5.1]), because software holding only the kidnapper's identity literally cannot tell the state who any passerby is. Yet PRO concedes ([P4.5]) they would ban that search even when it costs a life, forcing officers to scan dozens of screens unaided until after the victim is harmed.
[C5.4] Then, once tragedy strikes, PRO’s warrant requirement stalls routine mugshot lookups that—as [P5.4] admits—never scan strangers in public anyway. Strict statutes, audit logs, and human verification stop mass dragnets without forcing police to let a preventable tragedy happen just to investigate it later.
