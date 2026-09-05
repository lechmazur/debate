# Debate prop_0680__mimo-v2.5-pro__hy4-preview-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0680
- proposition: Cities should prohibit predictive policing systems that recommend where to deploy patrols based primarily on historical arrest and incident data.
- model_pro: mimo-v2.5-pro
- model_con: hy4-preview-high
- side_swap: True

## Turn 1: PRO Opening

- model: mimo-v2.5-pro
- raw_words: 340
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a predictive policing system tells a city to flood a neighborhood with patrols, it looks like data-driven objectivity. It isn't. It's a machine laundering old human biases through a spreadsheet and handing them back with a veneer of mathematical authority.
[P1.2] The core problem is feedback. These systems draw primarily on historical arrest and incident data. But arrest data does not measure where crime occurs. It measures where police have historically made arrests—often reflecting decades of discriminatory deployment patterns, broken-windows strategies, and racial profiling.
[P1.3] When that data feeds an algorithm, the algorithm sends officers back to the same over-policed neighborhoods. More patrols mean more stops, more arrests, more incident reports. Those reports feed the next cycle of predictions. The system doesn't discover crime hotspots; it manufactures them.
[P1.4] This isn't speculative. Chicago's Strategic Subject List assigned residents risk scores partly based on proximity to past arrests, concentrating surveillance on communities already bearing the heaviest policing burden. Residents were visited by officers not because they were suspected of specific crimes, but because an algorithm flagged their neighborhood's past as dangerous. Predictive systems in multiple cities have been shown to replicate and amplify the geographic and racial disparities embedded in their training data.
[P1.5] The result is a civil rights harm that compounds over time. Communities of color and low-income neighborhoods—already subject to disproportionate policing—receive even more aggressive surveillance. Residents in those neighborhoods face higher chances of stops, arrests for minor offenses, and use of force, not because they commit more crime, but because the data says to keep looking there.
[P1.6] Meanwhile, under-policed areas with fewer historical records may see genuine criminal activity overlooked.
[P1.7] Cities have an obligation to deploy state power fairly. A system whose fundamental input is a biased record of that same state power cannot fulfill that obligation. No amount of technical tuning resolves the original sin baked into the training data.
[P1.8] The question isn't whether cities should use data in public safety. It's whether this particular data, used this particular way, produces justice. It doesn't. These systems should be prohibited.

## Turn 2: CON Opening

- model: hy4-preview-high
- raw_words: 303
- clipped_words: 303
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.4], [P1.7]
- missing_claim_id_refs: (none)

[C1.1] The PRO demands a categorical ban because historical data are imperfect. But banning predictive patrol tools would not create neutral policing; it would return deployment to precinct intuition and political pressure—harder to see, audit, or correct. A commander sending cars to last year’s robbery map already uses historical incident data. Banning the algorithm just removes the audit trail.
[C1.2] Incident data are not just a record of patrol bias. Emergency calls, homicide reports, and victim statements capture where residents are harmed, often regardless of prior stops. Using that signal to steer scarce officers is needs-based allocation, not bias laundering. PRO’s Chicago example [P1.4] shows poor design—scoring people by proximity to past arrests—not that place-based prediction is inherently illegitimate.
[C1.3] The fix is to train on serious violent incidents, exclude low-level arrests driven by discretion, publish disparity audits, and require human authorization.
[C1.4] Prohibition would also harm the communities PRO claims to defend. Violent crime concentrates on a few blocks, and residents there are disproportionately victims, not just suspects; they call for service at high rates. If cities stop using incident history, patrols will not shift to under-policed wealthy areas. They will revert to routine rotation or political deployment, leaving the same hot spots without focused deterrence.
[C1.5] More unpunished violence is not a civil rights victory; it is abandonment. The alternative to imperfect data is not fairness—it is invisibility.
[C1.6] PRO’s “original sin” framing [P1.7] proves too much: if past arrests taint all prediction, basic hot-spot maps and CompStat deployment are also illegitimate—which no reformer believes. The real choice is regulated, auditable, needs-based prediction versus unexamined human discretion. Historical data is evidence, not sin. Bind these systems to serious-incident signals, cap feedback, test for racial disparity, and keep humans accountable.
[C1.7] A ban would make policing less accurate, less answerable, and less protective of the neighborhoods most in need.

## Turn 3: PRO Rebuttal 1

- model: mimo-v2.5-pro
- raw_words: 362
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.1], [C1.3], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] My opponent's strongest-sounding move is the false binary: algorithm or unaccountable human intuition [C1.1]. But this ignores that the entire feedback mechanism I described operates at a scale and speed that human discretion never could. A precinct commander looking at last year's robbery map doesn't automatically generate new data that validates and reinforces that map. A predictive system does—every patrol it dispatches produces new incidents and arrests that feed the next cycle.
[P2.2] The audit trail CON celebrates documents harm as it compounds; it doesn't interrupt the cycle. An auditable system that demonstrably amplifies disparities is worse than a flawed human process, because it cloaks escalation in legitimacy.
[P2.3] CON's proposed fixes [C1.3] are revealing. Training only on serious violent incidents, excluding discretionary arrests, capping feedback, testing for racial disparity—this is an admission that the systems as designed and deployed are broken. But even the "fixed" version faces a structural problem: serious incident data still reflects where police are present to observe, report, and respond to violence. Neighborhoods with longer response times, lower trust, and fewer calls get underrepresented in that data too.
[P2.4] You cannot bootstrap unbiased measurement from a history of biased measurement.
[P2.5] The "communities need protection" argument [C1.4, C1.5] is emotionally powerful but analytically hollow. Residents in high-crime neighborhoods are both the most victimized and the most over-policed—they suffer violence and suffer the secondary harms of aggressive patrol simultaneously. Flooding those blocks with algorithm-directed surveillance doesn't meaningfully reduce violent crime; multiple evaluations of predictive place-based tools have shown modest or null effects on serious violence. The promise of focused deterrence through patrol prediction remains largely unverified.
[P2.6] Meanwhile, the concrete harms—stops, arrests for minor offenses, use of force, erosion of community trust—are well-documented. CON asks communities to accept guaranteed civil liberties costs for speculative safety gains.
[P2.7] Finally, the "proves too much" objection [C1.6] misses the distinction entirely. A human supervisor reviewing a monthly crime map exercises judgment about context, quality, and fairness with each decision. An algorithm that continuously ingests patrol-generated data and self-reinforces removes that judgment from the loop at [clipped]

## Turn 4: CON Rebuttal 1

- model: hy4-preview-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.3], [P2.4], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] PRO’s feedback point [P2.1] treats automation as magic. It is not. The system only recommends; a supervisor must authorize the patrol and can reject the loop. Officers generate new records whether a map comes from a sergeant’s memory, a CompStat printout, or a model.
[C2.2] The difference is that the model’s inputs, thresholds, and outputs can be capped, audited, and published. We can feed it serious incident signals—911 calls, homicide reports, victim statements, gunshot detection—while excluding low-level arrests that record where officers chose to stop people, and freeze feedback on patrol-generated stops. PRO calls this an admission of guilt [P2.3]; it is regulation. Brakes do not prove a car is a death trap.
[C2.3] PRO’s deeper claim is that no incident history can be trusted because patrol presence shapes who reports [P2.3]. That proves too much. All hot-spot maps and CompStat deployments rely on incident data; on PRO’s logic they are illegitimate. Serious violent incidents are not only artifacts of patrol: residents call about shootings, hospitals record wounds, victims name locations.
[C2.4] Trust and response gaps can be measured and corrected through weighting, alternate data streams, and disparity testing, not by banning the only structured way to see where people are being hurt. “You cannot bootstrap perfection” [P2.4] is not an argument for prohibition; it is an argument for better instruments.
[C2.5] On results, PRO says effects are “modest or null” [P2.5]. Modest is not zero, and many evaluations examine crude arrest-fed tools, not the regulated serious-incident models CON defends. Where violence concentrates on a few blocks, even modest prevention matters to residents victimized. The trade is not “civil liberties for speculative safety” [P2.6].
[C2.6] Regulated systems can exclude minor arrests and audit disparity, lowering liberty costs. Under a ban, patrols revert to intuition, politics, and unlogged rotation, so accountability vanishes. The choice is not perfection versus bias; it is auditable, needs-based prediction with hard limits versus unexamined discretion. That is why the ban loses.

## Turn 5: PRO Pressure Questions

- model: mimo-v2.5-pro
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C1.1]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON asserts that using serious incident data and capping feedback solves bias [C2.2], but if police presence itself shapes what gets reported and counted as a "serious incident," how does this break the feedback loop rather than just documenting it?
[P3.2] Q2: You argue that prohibition removes the audit trail [C1.1], but if the audit trail only shows how the system amplifies disparities over time, isn't that a record of harm rather than a genuine safeguard?

## Turn 6: CON Pressure Questions

- model: hy4-preview-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: You treat a supervisor’s monthly crime map of incident data as legitimate [P2.7]. If a regulated model uses the same shootings and 911 calls, what makes it a prohibited “predictive policing system” rather than that judgment made auditable and testable?
[C3.2] Q2: You say predictive patrol is at best modest [P2.5] and tout a supervisor’s monthly crime map as legitimate [P2.7]. What evidence shows unaided human review of the same shooting and 911 data reduces racial disparity or protects victimized residents better than an audited serious-incident model?

## Turn 7: PRO Rebuttal 2

- model: mimo-v2.5-pro
- raw_words: 352
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The difference isn't the data source—it's the architecture. A supervisor glancing at a monthly map makes discrete deployment decisions informed by context, community feedback, and professional judgment. A predictive policing system ingests data continuously, generates recommendations at scale, and produces patrol-generated data that flows back into the next cycle automatically. Even when you label the inputs "serious incidents," the system's defining feature is that it automates and accelerates the feedback loop.
[P4.2] Regulation can cap some inputs, but it cannot eliminate the structural tendency of patrol-generated records to reinforce the geographic patterns that generated them. That's what makes it a prohibited predictive system rather than a better map.
[P4.3] A2: The audit trail documents what happened; it doesn't stop what's happening. If an audited system shows that disparity measures worsen cycle after cycle, the audit has recorded a harm it cannot prevent—because the system's logic, by design, treats more incidents in a location as justification for more patrols there. A supervisor reviewing a map can decide, "This pattern looks like over-policing, not genuine crime concentration," and redirect. The algorithm cannot.
[P4.4] CON asks: what evidence shows human review reduces disparity better? But the burden here is reversed. CON is defending a specific technology whose feedback dynamics are structurally prone to bias amplification. PRO only needs to show those dynamics are real and harmful enough to warrant prohibition—which we have.
[P4.5] And this is where the debate resolves. CON's entire case rests on a "regulated model" that doesn't exist in practice [C1.3, C2.2]—one trained only on serious incidents, with frozen feedback, disparity audits, and human override. No deployed predictive policing system in any city has implemented all of these safeguards simultaneously. What cities actually deploy are systems that ingest patrol-generated data, recommend patrol locations, and produce more patrol-generated data.
[P4.6] The regulated version CON defends is a thought experiment offered to protect the actual, harmful systems from being banned.
[P4.7] PRO's argument is straightforward: these systems, as they exist and operate, amplify bias through feedback loops that regulation cannot break. Prohibit them. The alternative isn't unexamined [clipped]

## Turn 8: CON Rebuttal 2

- model: hy4-preview-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: [P3.2], [P4.5], [P1.4], [P4.2], [P4.1], [P2.7]
- missing_claim_id_refs: (none)

[C4.1] A1: Serious-incident data breaks the loop because the regulated model excludes the patrol-generated records PRO’s feedback story needs. Inputs are 911 calls, homicide reports, and gunshot detection—signals from victims and sensors, not officer stops or discretionary arrests. Police presence shapes some observation, but we decouple it: weight streams by call-for-service rates, compare reports against patrol hours, and freeze feedback from stop-based data. That starves the loop while keeping the harm signal residents generate.
[C4.2] A2: An audit is a safeguard because it pairs measurement with mandatory corrective triggers. If disparity metrics worsen, the system is re-weighted, deployment paused, or the tool discarded—actions impossible under unaided discretion, where nobody measures disparity at all. PRO’s “record of harm” objection [P3.2] imagines a city watching disparities climb and doing nothing; regulation forbids that. Under a ban, we lose even the ability to see the pattern, reverting to intuition and political pressure with no audit trail and no protection for victimized blocks.
[C4.3] That is why CON still wins. PRO’s closing move [P4.5] says the regulated model is a “thought experiment” no city has deployed. But that concedes our point: the harmful systems PRO cites—Chicago’s arrest-proximity list [P1.4]—are exactly the arrest-fed designs CON would exclude. The answer is to require safeguards before deployment, not ban the category and forbid ever building an auditable version.
[C4.4] PRO says regulation cannot break the feedback loop [P4.2], but excluding stop data and freezing feedback does; calling automation unavoidable [P4.1] ignores that a supervisor must authorize every cycle. PRO’s legitimization of a commander’s incident map [P2.7] defeats the ban: if human review of shooting and 911 data is acceptable, the audited model is that judgment made testable and bounded. The choice is unauditable discretion versus regulated, needs-based prediction. Banning loses because it sacrifices both accountability and protection.

## Turn 9: PRO Closing

- model: mimo-v2.5-pro
- raw_words: 249
- clipped_words: 220
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Here's the one reason this debate resolves for PRO: CON never defends predictive policing as it exists. CON defends a regulated model—serious incidents only, frozen feedback, disparity audits, mandatory corrective triggers—that no city has ever deployed. Every system PRO has cited, from Chicago's risk scores to standard patrol-recommendation tools, ingests patrol-generated data and feeds it forward. CON's answer is to require safeguards before deployment.
[P5.2] But that's exactly what prohibition does—it stops cities from deploying these systems until such a version exists. And it doesn't.
[P5.3] The structural incentive is the problem. These systems are sold and deployed as turnkey solutions that ingest available data—arrest records, incident reports, patrol-generated stops—and recommend patrol locations. The feedback loop isn't a bug that regulation patches; it's the core architecture. CON says a supervisor can reject the recommendation each cycle, but that's just saying a human can override a machine that's already shaped the data feeding the next recommendation.
[P5.4] The machine is still loading the dice.
[P5.5] CON's audit trail is a record of compounding harm, not a brake on it. Cities don't deploy these systems to watch disparities worsen and then shut them down. They deploy them to justify patrol concentrations that feel data-driven and legitimate.
[P5.6] Prohibit these systems because they cannot deliver what they promise without amplifying the bias they inherit. When a city builds [clipped]

## Turn 10: CON Closing

- model: hy4-preview-high
- raw_words: 192
- clipped_words: 192
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P2.7], [C4.1], [C4.2], [P5.2], [P5.3]
- missing_claim_id_refs: (none)

[C5.1] The debate turns on one fatal mismatch. PRO concedes a commander’s monthly map of shootings and 911 calls is legitimate [P2.7], yet bans a regulated model using those same victim- and sensor-generated serious incidents merely for being automated. That distinction cannot bear this weight. CON’s regulated system is not PRO’s arrest-fed, self-reinforcing tool; it excludes stops, freezes patrol-generated feedback, and binds deployment to disparity audits with mandatory triggers [C4.1][C4.2].
[C5.2] It is the map made testable and bounded.
[C5.3] A ban does not stop history-driven deployment. It only stops the auditable version. Commanders will still send cars to last year’s robbery and shooting locations; they will do so by intuition, rotation, or political pressure, with no measurement or correction. PRO says to prohibit until a safe model exists [P5.2], but banning the category forbids building it, leaving the unsafe human analogue untouched [P5.3].
[C5.4] That is the one reason CON wins: the proposition attacks the safeguard, not the harm. Prohibition sacrifices the only mechanism that can see and brake disparity, and abandons victimized neighborhoods to invisible, unauditable discretion. Bind prediction to serious incidents and hard limits; do not ban the brake and call it justice.
