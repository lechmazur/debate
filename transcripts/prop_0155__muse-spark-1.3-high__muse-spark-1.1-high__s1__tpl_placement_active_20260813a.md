# Debate prop_0155__muse-spark-1.3-high__muse-spark-1.1-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0155
- proposition: Police departments should be prohibited from using face recognition in real-time surveillance, but allowed to use it for post-incident investigations with a warrant.
- model_pro: muse-spark-1.3-high
- model_con: muse-spark-1.1-high
- side_swap: True

## Turn 1: PRO Opening

- model: muse-spark-1.3-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Walking to a protest, a church, or a grocery store should not put you in a police lineup. But that is exactly what real-time face recognition does: cameras scan every face passing by, compare each one to databases, and log who was where, with whom. It turns public space into a checkpoint you can never avoid.
[P1.2] That dragnet is different in kind from looking for a suspect after a crime. Post-incident use starts with a crime, a bounded set of images, and time for careful human review. Real-time use starts with everyone, decides in seconds, and pushes officers toward stops, detentions, and force based on a machine guess made under the worst conditions — bad lighting, odd angles, low resolution, moving crowds. When the algorithm is wrong, an innocent person pays with a confrontation on the street, not a corrected file.
[P1.3] The burden also falls unevenly. Systems repeatedly perform worse on darker skin, women, and older people, meaning more false alarms directed at communities already over-policed. Multiplying cameras multiplies those mistakes across an entire city, every day, with no chance to opt out and a powerful chilling effect on speech, worship, and assembly.
[P1.4] A warrant requirement for after-the-fact searches solves what actually needs solving. Police keep a powerful tool for robberies, assaults, homicides: present probable cause to a judge, specify whose face and which footage, create a record that can be audited and challenged in court. That judicial check deters fishing expeditions through protest footage or neighborhood cameras and forces investigators to do the corroboration that prevents wrongful arrests.
[P1.5] Public safety does not require watching everyone in real time to catch someone later. Banning live identification while preserving warranted investigation is the only balance that stops mass tracking without tying detectives' hands.

## Turn 2: CON Opening

- model: muse-spark-1.1-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: [P1.5], [P1.2], [P1.1]
- missing_claim_id_refs: (none)

[C1.1] The proposal has the balance exactly backward. It bans face recognition when it can prevent a crime and permits it only after the victim has already been robbed, assaulted, or killed. A city that can use the technology to identify an abducted child at a bus terminal the next day, but not to flag that same child walking past a camera while the abductor is still holding her, is choosing paperwork over rescue.
[C1.2] Real-time is where the life-saving value lives. An active shooter moving through a mall, a known terrorist on a watchlist entering a stadium, a dementia patient or a seven-year-old on an Amber Alert lost in a crowd - these are not post-incident puzzles. In those minutes, an alert that says 'possible match, check now' lets officers intervene before harm, not assemble a case file after. [P1.5] claims public safety doesn't need this.
[C1.3] Tell that to parents waiting at the gate.
[C1.4] It is also wrong that real-time is more invasive. Properly deployed real-time systems don't store your face. The camera checks against a small hot-list - say 20 fugitives and missing persons - and instantly discards non-matches. No log of who was at the protest.
[C1.5] Post-incident investigation, which [P1.2] calls careful and bounded, does the opposite: police pull hours of footage from blocks of private and public cameras and rewind everyone's movements, creating the persistent tracking [P1.1] fears.
[C1.6] And its warrant fix cripples that investigation. Face recognition is used because you don't know who the suspect is. You have a frame from a robbery; you need a lead. What name do you put in the warrant?
[C1.7] Requiring probable cause that the unknown person is guilty before you can learn his name is circular, and waiting hours for a judge in the first 48 hours of a homicide guarantees dead ends.
[C1.8] Treating alerts as inevitable street violence ignores that alerts trigger verification, not force. Regulate accuracy, logging, and punishment for abuse - don't ban prevention.

## Turn 3: PRO Rebuttal 1

- model: muse-spark-1.3-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.4], [C1.5], [C1.6], [C1.8]
- missing_claim_id_refs: (none)

[P2.1] An abducted child at a bus terminal does not need live face recognition to be rescued — she needs an alert public, an officer looking, cameras watched by humans. An active shooter firing in a mall announces himself; police do not pause to ask an algorithm for his name before they move. Identity is rarely the bottleneck in those terrible minutes. Using rare horrors to justify scanning millions of innocent faces every day is emotional extortion, not policy.
[P2.2] The promise in [C1.4] that real-time systems “instantly discard non-matches” is unenforceable marketing. To check a crowd against even a “small hot-list” of 20, the system must still scan, map and compare every face in the crowd — tens of thousands of suspicionless searches per hour. Who audits deletion? The same department and vendor that benefit from keeping data.
[P2.3] And hot-lists never stay small. What starts as terrorists and kidnappers becomes fugitives, then shoplifters, then protest organizers. Once the cameras and software are live, expansion takes a keystroke.
[P2.4] That is why [C1.5] gets invasiveness backward. Post-incident review starts with a crime, a time, a place, and under this proposal a judge. Real-time starts with everyone, everywhere, for no reason. One is targeted investigation with a record; the other is a permanent checkpoint you cannot avoid.
[P2.5] The warrant objection in [C1.6] misunderstands warrants. You do not name the unknown suspect — you show probable cause a crime occurred, specify the probe image and the footage to be searched, just as with fingerprints or DNA. Judges are on call around the clock, and true exigency already excuses delay. And alerts do not merely “trigger verification” as [C1.8] claims.
[P2.6] A flashing “possible match” in a tense, fast-moving crowd pushes stops, handcuffs, and guns drawn long before calm review, with errors landing hardest on the people misidentified most.

## Turn 4: CON Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [P2.2], [P2.4], [P1.1], [P2.3], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] [P2.1] says an abducted child doesn't need live face recognition, just "an officer looking." One officer cannot watch 300 feeds in a bus terminal. A real-time check against an Amber hot-list does what humans physically can't: it says look here, now, while she can still be pulled off the bus. For an active shooter, identity *is* the bottleneck after the first shots - is this the shooter, a second threat, a parent running in?
[C2.2] A name lets you close the right exit, pull the right yearbook photo for officers clearing rooms, not lock down a city.
[C2.3] [P2.2] calls instant discard unenforceable marketing, confusing processing with tracking. Every officer on a corner scans hundreds of faces and compares to memory; that glance is not a Fourth Amendment search. What matters is retention, and retention is engineerable: process on the camera edge, compare to 20 hashes, drop the frame if no match, write a cryptographic log of deletions an outside auditor can verify. That's less invasive than what PRO endorses.
[C2.4] Because [P2.4] gets invasiveness backward. Live with a small hot-list touches everyone and remembers no one. Post-incident review rewinds hours of footage from ten private cameras around the scene and reconstructs who was with whom - the persistent tracking [P1.1] fears. PRO bans the amnesiac check and mandates the memory-heavy one.
[C2.5] [P2.3]'s "hot-lists never stay small" is a slippery slope against any police power. We don't ban patrol cars because they might drive to a protest. We write the policy into law: imminent threat, kidnapped child, terrorist - not shoplifting - with loss of certification for violation.
[C2.6] And [P2.5] and [P2.6] misdescribe both practice and this proposal. A fingerprint warrant specifies whose prints to take. A face probe is to *learn* whose face it is - requiring probable cause that the unknown person is guilty before you can learn his name is circular.
[C2.7] Meanwhile alerts don't require guns drawn. Policy can require what agencies already do: no stop on match alone, verification by a second trained reviewer, no use of force solely [clipped]

## Turn 5: PRO Pressure Questions

- model: muse-spark-1.3-high
- raw_words: 50
- clipped_words: 50
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You claim live checks against 20 faces discard everyone else — who independently audits deletion, and what stops that list quietly becoming 2,000 including protesters?
[P3.2] Q2: Since judges already authorize fingerprint and DNA searches from crime-scene evidence without knowing the suspect's name, why is a face-search warrant uniquely "circular"?

## Turn 6: CON Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If identity isn't the bottleneck, how do you stop a watchlisted terrorist entering a stadium or an Amber-listed child moved through a bus terminal before any crime occurs that could justify a warrant?
[C3.2] Q2: You say a face-search warrant works like fingerprints because a judge approves the probe image — but if police don't know whether that face is suspect, victim, or bystander, what probable cause specific to that face can a judge assess without first running the search?

## Turn 7: PRO Rebuttal 2

- model: muse-spark-1.3-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: An Amber-listed child has already been abducted — that kidnapping is the crime that justifies an exigent, warrantless search under this proposal, plus old-fashioned alerts, officers at exits, and transport staff. No mass scan needed. A watchlisted terrorist silently entering a stadium has committed no crime yet — and that is precisely why you cannot scan tens of thousands of innocent fans to find him. Targeted intel, ticket checks, and human security stop that threat without turning every gate into a lineup.
[P4.2] A2: A judge does not need to know the name to find probable cause, only that a crime happened and this face is tied to it by time, place, and conduct — a masked figure at the register at 2:13, not a crowd. That is exactly how a judge approves testing blood or prints from the scene without knowing whose they are. If police genuinely cannot tell suspect from victim or bystander, they have no business running a biometric search to figure it out; that admission proves the fishing expedition warrants prevent.
[P4.3] Those answers expose why prevention here loses. CON wants to run the search first to create the justification afterward: scan everyone because someone might be guilty, rewind everyone because someone might have been there. That reverses probable cause. Post-incident with a warrant starts from a crime and a bounded image, with a record a defendant can challenge; live surveillance starts from no crime and everyone’s face, with deletion promises only the vendor can verify.
[P4.4] Public safety is not paperwork versus rescue. It is preventing wrongful stops on a flashing guess — where officers act first and verify later, with mistakes falling hardest on those already misidentified most — versus solving real crimes with corroborated evidence. Ban the checkpoint, keep the investigation.

## Turn 8: CON Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 329
- clipped_words: 329
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P3.1], [P3.2], [P4.1], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: Who audits deletion? Not the vendor. Edge processing on the camera, no central storage - if no match to the hot-list hash, the frame drops. A tamper-evident log - match count, no-match count, hash of hot-list version - writes to an independent city auditor, inspector general or civilian oversight, with source escrow and quarterly public reports.
[C4.2] What stops 20 quietly becoming 2,000 including protesters? The same thing that stops any police database abuse: statute, not marketing. Write into law: hot-list capped, limited to imminent threat, kidnapped child, terrorist watchlist, each entry tied to a case number, violation = loss of certification and suppression. If "might expand" is enough to ban [P3.1], you must ban patrol cars and license readers too.
[C4.3] A2: A fingerprint warrant is not circular because the trace is inherently offender-linked - blood on the broken safe, print on the crowbar. You already have probable cause that trace is the perpetrator's. A face crop from a block of video isn't [P3.2]. You don't know if it's suspect, victim, or bystander who walked by at 2:13.
[C4.4] With DNA you test one piece of crime scene evidence. With face you must search thousands of uninvolved faces to generate suspicion in the first place. Requiring probable cause that this particular unknown bystander's face is guilty before you can learn whose face it is is circular.
[C4.5] Those answers expose why PRO loses. In [P4.1] you admit a terrorist entering a stadium hasn't committed a crime yet so you cannot scan to stop him, and you claim an Amber child can be saved by "old-fashioned alerts." That's choosing blindness when prevention is possible. In [P4.2] you say if police can't tell suspect from bystander they have "no business" searching - so a robbery on a busy sidewalk can't be investigated because the crowd hides the suspect.
[C4.6] You ban prevention where it's least invasive - the amnesiac check that remembers no one - and mandate the memory-heavy rewind that reconstructs everyone's movements.

## Turn 9: PRO Closing

- model: muse-spark-1.3-high
- raw_words: 184
- clipped_words: 184
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON’s own answer convicts its case: to catch one man who has committed no crime yet, scan tens of thousands of innocent fans. That is not prevention, it is punishment of the public — everyone searched so one might be suspect. Safety that requires suspicionless tracking of all is not safety, it is control.
[P5.2] A free society never accepted that bargain. We do not search every home to find one fugitive, stop every driver to find one drunk, open every letter to find one threat. We require a crime, a reason, a judge. Post-incident with a warrant keeps that order: a robbery, a time, a face tied to it, a record a defendant can challenge.
[P5.3] Live recognition reverses it: face first, justification later, deletion promises only the vendor can verify, a flashing guess that sends officers surging into crowds where mistakes fall hardest on those already misidentified. And hot-lists never stay small because power never stays put.
[P5.4] Ban the amnesiac checkpoint that remembers power, keep the investigation that remembers limits. That is why this balance holds. Choose suspicion with limits over surveillance without end.

## Turn 10: CON Closing

- model: muse-spark-1.1-high
- raw_words: 185
- clipped_words: 185
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.2], [P1.1]
- missing_claim_id_refs: (none)

[C5.1] The motion sells two promises: protect privacy and preserve investigation. It breaks both.
[C5.2] It bans the only form that can forget: a camera that compares a face to 20 hashes on the edge and drops the frame if there is no match, with a tamper-evident count that an independent auditor can check. And it mandates the form that must remember: pull ten cameras around the robbery, rewind hours, map who was with whom. That is not [P5.2] requiring a crime first; it is building the permanent location history [P1.1] warned about.
[C5.3] It then chokes that dragnet with a warrant no judge can meaningfully write. A bloody print is known to be the offender's. A face in a crowd at 2:13 is not. Requiring probable cause that this unknown bystander is guilty before you learn his name stops investigation before it starts.
[C5.4] Safety needs alert now, privacy needs forgetting by design. This ban forces remembering later and blindness now. That is why it must fail. Regulate accuracy, hot-list size, and deletion with criminal penalties — don't outlaw the moment when a child can still be saved.
