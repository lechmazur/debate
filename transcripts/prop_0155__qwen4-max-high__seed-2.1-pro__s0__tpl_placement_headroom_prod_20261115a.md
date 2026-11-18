# Debate prop_0155__qwen4-max-high__seed-2.1-pro__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0155
- proposition: Police departments should be prohibited from using face recognition in real-time surveillance, but allowed to use it for post-incident investigations with a warrant.
- model_pro: qwen4-max-high
- model_con: seed-2.1-pro
- side_swap: False

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The line this motion draws is the oldest one in policing: suspicion comes before the search. Real-time face recognition inverts that. It runs every face on a street, at a protest, outside a clinic or a church, against a government list, and asks questions afterward. Nobody in that crowd has done anything.
[P1.2] That is not investigation; it is a standing checkpoint on identity.
[P1.3] Now add error. Live recognition works on the worst images policing ever uses: faces at an angle, in motion, in bad light, at distance, captured without cooperation. Systems perform worse on those images than on posed photographs, and worse on darker-skinned and female faces. A false hit in a live feed becomes an armed stop of an innocent person, in public, with no chance to correct the record first.
[P1.4] A false hit in a post-incident case is a lead that gets checked against alibi, other footage, and physical evidence before anyone is charged. Same algorithm, radically different consequences.
[P1.5] The warrant requirement is not decoration. It supplies a crime, a defined scope, a judge, and a paper trail a defense lawyer can later attack. Real-time scanning produces none of that. You cannot challenge a search that was never recorded as a search.
[P1.6] That is why "just regulate both alike" collapses: only one of these uses can be meaningfully supervised at all.
[P1.7] My opponent will offer the kidnapped child. But the same camera footage still exists an hour later, and this motion lets police search it with a warrant. What CON must actually defend is not that rare emergency; it is the permanent, suspicionless scanning of millions of people who will never be suspects, so a handful of cases resolve slightly faster. That is the trade being hidden behind the emergency.
[P1.8] Keep the tool. Keep the crime-first predicate. A free society can solve murders without turning every sidewalk into a lineup.

## Turn 2: CON Opening

- model: seed-2.1-pro
- raw_words: 290
- clipped_words: 290
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] This proposed split is a false compromise that delivers none of the civil liberties protection it promises, while entrenching the most dangerous surveillance power police can hold. First, the line between “real-time surveillance” and “post-incident investigation” does not exist in practice. Modern systems ingest and index camera feeds the second they are captured; a search of footage recorded 30 seconds prior, authorized by the rubber-stamped warrants judges approve for nearly all police requests, is functionally identical to live scanning, just delayed long enough to satisfy hollow paperwork that rarely narrows scope meaningfully.
[C1.2] Worse, the rule greenlights mass, permanent retention of public camera footage of every person walking on a sidewalk, attending a protest, entering a reproductive health clinic, visiting a union hall, or meeting a lawyer, because you cannot run post-incident face searches on footage you did not save. That permanent, searchable library of every citizen’s public movements, associations, and sensitive visits is the core privacy harm, not the split-second difference between scanning a face as it passes or scanning it 10 minutes later.
[C1.3] Nothing stops police from using that stored footage, approved by a warrant, to identify and target protest organizers, political dissidents, or people they simply dislike long after a public gathering ends, not just solve violent crimes. The claim that post-incident false hits are harmless because they are “just leads” ignores documented cases of wrongful arrest, home raids, and public shaming of people misidentified by face recognition in exactly those post-incident, warrant-supported investigations—errors that take weeks to untangle, even when other evidence contradicts the algorithm match.
[C1.4] The warrant requirement here is not a guardrail; it is a fig leaf that normalizes permanent, universal public face surveillance, while banning only the most visibly obvious version of the practice.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON says the line doesn't exist because a search of thirty-second-old footage is "functionally identical" to live scanning. Notice what that example concedes: to search that footage, police needed a warrant. Something had to happen in those thirty seconds — a crime, a described suspect, a place and time — and a judge had to sign off on that scope. That is not a delay; that is a predicate.
[P2.2] Live scanning needs none of it. It asks everyone's face first and looks for a reason later. The difference isn't latency, it's direction: a dragnet searches people to find crimes; an investigation searches a crime to find a person.
[P2.3] The permanent library is CON's invention, not this motion's requirement. Nothing here mandates saving every frame forever; retention limits, deletion schedules, and audit logs are all still available, and every one of them is easier to enforce when searches must be tied to a named incident.
[P2.4] Meanwhile CON's own regime needs the same cameras, the same ingestion, plus standing watchlists run against everyone. If storage is the core harm, CON is defending the version that requires more of it.
[P2.5] On wrongful arrests: they are real, and they cluster where a match was treated as proof instead of a lead. The answer is corroboration requirements and disclosure — tools this motion leaves entirely intact. CON's answer is to add a second, unrecorded channel of the same error, aimed at people who were never suspects at all. And "judges rubber-stamp" is an argument for sharper warrants, not for abolishing them.
[P2.6] A flawed record can be litigated. A scan that was never logged as a search cannot. CON's position keeps the archive, keeps the errors, and deletes the only moment when a neutral party can say no.

## Turn 4: CON Rebuttal 1

- model: seed-2.1-pro
- raw_words: 297
- clipped_words: 297
- claim_ids: [C2.1], [C2.2], [C2.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] That supposedly bright line between dragnet and investigation dissolves the second you apply it to how police actually work. A warrant for post-incident facial recognition does not require police to name a suspect, or even a narrow suspect description, before running a search: it routinely authorizes scanning every face captured across multiple blocks of footage, over hours of time, to see who the algorithm flags. That is not “searching a crime to find a person” — that is running exactly the same mass face sweep PRO condemns, just delayed long enough to get a judge’s signature on a broad scope that almost never gets meaningfully narrowed or rejected.
[C2.2] That is a procedural speed bump, not a safeguard against suspicionless search. PRO claims a permanent, searchable footage library is not required, and bizarrely frames our side as defending more pervasive surveillance, but that ignores basic operational reality: you cannot run retrospective face searches on footage you deleted. The motion creates an unavoidable, permanent incentive for every department to hoard every second of public camera footage indefinitely, just in case some future crime creates an excuse to search it. That archive will capture protest attendees, clinic patients, and people meeting confidential counsel, none of whom will ever know their face was run against a database, because warrants and audit logs only track the eventual suspect, not the thousands of innocent bystanders swept into the search.
[C2.3] The paper trail PRO celebrates is invisible to everyone who is not arrested. Those bystanders cannot litigate a search they never learn happened. This regime does not end mass face surveillance; it launders it through thin warrant paperwork, while retaining every core privacy harm of the real-time version, including misidentification-driven wrongful arrests of people flagged first by an algorithm, not slow, careful corroborating evidence.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 69
- clipped_words: 69
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You call warrants a "fig leaf." Under your rule, does live scanning of every face on a street require one — or nothing at all? If nothing, explain how removing the judge reduces surveillance.
[P3.2] Q2: A warrant fixes a crime, a place, and a time window; a live dragnet has no outer bound. Which sweeps more innocent bystanders, and what limit does your regime impose that mine lacks?

## Turn 6: CON Pressure Questions

- model: seed-2.1-pro
- raw_words: 67
- clipped_words: 67
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If police routinely obtain post-incident warrants authorizing face scans of every person captured across hours of multi-block camera footage, how is that sweep meaningfully different from the real-time dragnet you claim to ban?
[C3.2] Q2: You argue paper trails let people litigate improper searches, but how can innocent bystanders who are never flagged or arrested ever learn their faces were searched to challenge that violation in court?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 284
- clipped_words: 284
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Because a warrant has an edge and a dragnet doesn't. Multi-block footage from a Tuesday robbery is a finite, already-recorded set: the frames run out, the search ends, and a judge fixed that boundary before anyone's face was compared. Live scanning has no last frame. It keeps running on people who haven't arrived yet, tomorrow and next year, with no crime alleged and nothing to terminate it.
[P4.2] If a judge signs a sweep too broad, that is a warrant defect — argue it, narrow it, appeal it. CON's answer to overbroad scope is to remove the person who defines scope.
[P4.3] A2: They usually can't — and that is true of every records search, from wiretaps to bank subpoenas. The remedy was never individual lawsuits by bystanders; it is suppression for the person charged, discovery, audit logs, aggregate reporting, and councils that can shut the program off. Those levers exist only if searches are logged against incidents. CON offers bystanders the same invisibility plus no judge, no incident number, and no record that anything happened at all.
[P4.4] Notice that CON still hasn't answered my first question: under their rule, what stops a live scan of every face on a street? Nothing — not a warrant, not a crime, not an ending. On retention, the archive is a policy choice, not a clause of this motion; thirty-day deletion is fully compatible with warrant-based retrospective search, and CON's live system needs those same cameras running regardless.
[P4.5] The question isn't whether warrants are perfect. It is whether the state must point to a crime before it looks at your face. Only one side keeps that requirement, and CON keeps arguing that imperfect supervision is worse than none.

## Turn 8: CON Rebuttal 2

- model: seed-2.1-pro
- raw_words: 300
- clipped_words: 300
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Our position prohibits both unconstrained real-time scanning and the mass retrospective face sweeps this motion would legalize, so no police use of face recognition on public camera feeds escapes prior, narrow judicial authorization tied to probable cause for a specific crime, requiring filtering to suspect descriptors before any face comparison runs. The problem is not that judges have no role; it is that this motion treats a judge’s signature on a broad, unfiltered sweep of everyone across hours of multi-block footage as a sufficient safeguard, even when that sweep is functionally identical to the live dragnet PRO claims to ban.
[C4.2] That is not removing judges—it is refusing to accept hollow, rubber-stamped approval as a substitute for real constraints on mass search.
[C4.3] A2: The motion’s so-called bounded warrant routinely authorizes scanning every person who passed through an area over hours, with no requirement to narrow the pool before running the algorithm, so it sweeps in the same innocent bystanders as live scanning, with even less transparency because searches happen after crowds disperse. Our regime requires that pre-search descriptive filter, mandatory deletion of footage of anyone not matching the description, and independent audit access, not just records reserved for prosecutors when someone is charged.
[C4.4] PRO frames this as a choice between imperfect warrants and no limits, but that is a false dichotomy. The motion does not end dragnet face surveillance; it moves it 30 seconds behind the live feed, launders it through deferential warrant review, and locks in the permanent footage hoard that makes universal tracking irreversible. The paper trail PRO celebrates never reaches the thousands of innocent people scanned, who have no way to know their face was searched, let alone challenge it.
[C4.5] That is no compromise—it is legitimization of the permanent surveillance state this split falsely claims to prevent.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON's final position requires "prior, narrow judicial authorization tied to probable cause for a specific crime" before any face search. That is this motion's rule, restated. Descriptive filtering, deletion schedules, independent audits — none are forbidden by allowing warrant-based retrospective search; all are additions to it. So the safeguards CON wants are arguments for implementing this motion well, not against it.
[P5.2] And notice what the filter costs: to delete everyone who doesn't match a description, you must first examine everyone. CON's own remedy processes the same bystanders it condemns. The archive doesn't disappear; it acquires a judge.
[P5.3] The one thing left that separates us is the sentence CON never defended: a live dragnet has no last frame. A robbery search ends when Tuesday's footage runs out. A street scanner ends when the department unplugs it, and it keeps reaching people who haven't arrived yet — no crime alleged, no scope, no termination.
[P5.4] CON calls that laundering. But a rule that makes the state name a crime before it reads your face is not the surveillance state's permission slip — it is the one thing that has ever stood in its way. Vote to keep suspicion before the search.

## Turn 10: CON Closing

- model: seed-2.1-pro
- raw_words: 189
- clipped_words: 189
- claim_ids: [C5.1], [C5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The motion fails because its supposed bright line between forbidden real-time scanning and allowed post-incident search does not block mass face surveillance—it legitimizes it, while stripping leverage to demand stronger guardrails. A warrant that lets police scan every face captured across hours of multi-block public footage, no pre-filter for suspect description required, is not a narrow, meaningful check on state power; it is judicial permission to run the exact same dragnet PRO condemns, delayed just long enough to get a deferential signature on broad scope language that almost never gets rejected.
[C5.2] PRO claims these searches end when the relevant footage runs out, but to run them at all departments must hoard every second of public camera footage indefinitely, capturing protestors, clinic patients, and people meeting confidential counsel who will never be arrested, never see the so-called paper trail, and never meaningfully challenge that their face was searched. That is not keeping suspicion before search. It is building a permanent, searchable archive of everyone’s public movements, draped in procedural fig leaves to make universal public tracking look like a reasonable compromise rather than the surveillance state entrenchment it actually is.
