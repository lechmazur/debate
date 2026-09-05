# Debate prop_0680__hy4-preview-high__mimo-v2.5-pro__s0__tpl_placement_active_20260813a

- topic_id: prop_0680
- proposition: Cities should prohibit predictive policing systems that recommend where to deploy patrols based primarily on historical arrest and incident data.
- model_pro: hy4-preview-high
- model_con: mimo-v2.5-pro
- side_swap: False

## Turn 1: PRO Opening

- model: hy4-preview-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The question is not whether police should use information; it is whether a city may let a machine pick patrol targets when its main ingredient is the department’s own past enforcement. That is exactly what these systems do, and that is why they should be prohibited.
[P1.2] Historical arrest and incident records are not a neutral map of crime. They map where police already looked and whom they already stopped. Feed them to an algorithm as the primary input, send officers to the flagged blocks, and the prediction fulfills itself: more patrols surface more low-level offenses, generate more arrests and incident reports, and teach next quarter’s model to send still more patrols. This is not a bug; it is the engine.
[P1.3] It converts yesterday’s enforcement choices into tomorrow’s justification and launders bias into a heat map that looks objective.
[P1.4] That ratchet lands hardest on communities already over-policed. Because past drug-war and stop-and-frisk practices concentrated arrests in Black, Latino, and poor neighborhoods, an “incident-based” model can treat geography as risk without ever naming race. Two neighborhoods with similar underlying offending will not be treated alike: the one saturated years ago gets flagged, gets more cops, and is labeled high-risk again, while its residents absorb more stops, charges, and reasons to distrust police. Trust falls, witnesses stop calling, and clearance rates suffer—real safety worsens even as the dashboard reports activity.
[P1.5] Regulating or auditing these tools misses the point. Their core data is endogenous: police deployment creates the very records used to judge deployment. Late audits cannot repair the ongoing stops, and “cleaned” inputs still carry the geometry of past bias. A ban is the proportionate response: prohibit predictive patrol systems built primarily on historical enforcement data, and redirect resources toward community-identified priorities, focused investigations of serious harm, and violence-interruption work that does not mistake surveillance for safety.

## Turn 2: CON Opening

- model: mimo-v2.5-pro
- raw_words: 303
- clipped_words: 303
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition asks us to ban a tool based on a distorted understanding of what it does and a failure to weigh its concrete benefits against a critique that, at its core, attacks all data-driven policing.
[C1.2] Predictive systems do not just mirror old patrols; they synthesize incident reports—calls for service, violent crimes, property crimes—reported by the public itself. This data reflects *where people experience harm and request help*. To treat it as nothing but a record of past enforcement choices is to dismiss the victim’s experience that generated the call. A system that identifies patterns in violent crime hotspots is not “laundering bias”; it is responding to a publicly stated need for safety.
[C1.3] The feedback loop argument is overstated. The claim that more patrols inevitably create more arrests to justify themselves assumes police only make low-level discretionary stops. In reality, a surge in serious crime reports in an area should attract resources regardless of prior deployment. Effective systems are calibrated to prioritize serious violence, not mere enforcement activity.
[C1.4] The answer to potential bias in the data is not to discard the information, but to audit outcomes, adjust weightings, and incorporate other datasets—like hospital admissions for assaults—which many cities are already doing. Prohibition halts this progress.
[C1.5] The alternative is worse. Banning these systems does not eliminate crime patterns; it just forces police to rely on gut instinct, political pressure, or truly arbitrary deployment. That is likely to be *more* biased and less effective. We should mandate transparency, independent algorithm audits, and community oversight boards with real power to review and adjust these models—not take away a tool that has demonstrably helped cities like Los Angeles allocate resources to prevent shootings and respond faster to crime surges.
[C1.6] The cost of prohibition is measurable in lives not protected. We should refine the tool, not remove it.

## Turn 3: PRO Rebuttal 1

- model: hy4-preview-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.4], [C1.3], [P1.2], [C1.2], [P1.3], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] The opposition cannot have it both ways. [C1.4] would add hospital admissions and adjusted weights; [C1.3] demands systems that prioritize serious violence, not raw enforcement activity. If that reorientation is deep enough that the model no longer runs primarily on historical arrest and incident data, the city has adopted a different tool—not the banned one.
[P2.2] But if the patrol map still derives mainly from past stops, arrests, and incident reports, then audits and reweighting leave intact the engine we indicted [P1.2].
[P2.3] The defense of incident reports [C1.2] conflates a request for help with proof that a block is criminogenic. A 911 call is shaped by where residents expect police and by decades of over-policing. Worse, patrols manufacture data: a stop, frisk, or possession arrest becomes an entry tomorrow's model reads as "demand." That is still laundering bias through an objective-looking map [P1.3].
[P2.4] [C1.3] says serious-crime surges should attract resources. Agreed—but a map fed primarily on arrest and incident history detects surges poorly. Records follow enforcement, not harm: a shooting surge on a block with little stop history stays under-flagged because the model waits for reports that only appear after police are there.
[P2.5] Meanwhile the historically flooded block, burdened with possession arrests, keeps drawing patrols and manufacturing the records that re-flag it. So the tool chases yesterday's attention, not today's violence.
[P2.6] Audits [C1.4] cannot catch up: a quarterly review cannot un-stop a resident or restore trust, and the engine runs another cycle before weights change. The "gut instinct" warning [C1.5] is a false choice; we would use community priorities, leads, and hospital data. Even if Los Angeles improved, that does not prove an enforcement-trained patrol model prevented shootings; the tool cannot isolate its effect from patterns in its training data.
[P2.7] Refine the map and you have abandoned it. Prohibit the systems that run primarily on historical arrest and incident data, and retire the self-referential engine, not the goal of safety.

## Turn 4: CON Rebuttal 1

- model: mimo-v2.5-pro
- raw_words: 349
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.3], [P2.5], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal actually sharpens why prohibition is wrong rather than right. Consider the move at [P2.1]: if adding hospital data and adjusting weightings means the city has "adopted a different tool—not the banned one," then PRO is conceding that refinement works. The proposition bans systems running *primarily* on historical arrest and incident data. A system enriched with hospital admissions, weighted toward serious violence, and subject to ongoing adjustment still uses incident data as a foundation—it has just been improved.
[C2.2] PRO's own framing shows that the policy answer is mandated improvement, not prohibition.
[C2.3] The feedback loop argument, pressed again in [P2.3] through [P2.5], proves too much. Hospital admissions for assaults, utility shutoffs, school absenteeism, and building code violations all correlate with neighborhood distress and also reflect access, policy, and institutional patterns. If contamination of any data source by prior institutional choices is grounds for banning, then no data-driven public resource allocation survives—not ambulance dispatch, not fire station placement, not school funding formulas. The relevant question is whether predictive patrol systems can be made less biased than the alternative.
[C2.4] PRO never answers that comparison.
[C2.5] And the alternative matters enormously. [P2.7] gestures toward "community priorities, leads, and hospital data," but this is a list of inputs, not an operational deployment mechanism. Police must allocate officers to specific locations at specific times. Community input can set values—"prioritize youth violence, protect elders, avoid low-level drug enforcement"—but someone still has to translate those values into a patrol map.
[C2.6] Without a predictive system, that translation falls to district commanders exercising judgment, which is precisely the discretionary, opaque, politically influenced deployment PRO claims to oppose.
[C2.7] The cost PRO dismisses is real. Cities facing gun violence surges need spatial allocation tools that respond to emerging patterns faster than quarterly community meetings. Prohibition removes that capacity and offers no comparable substitute. The motion asks for a ban.
[C2.8] The better answer is a mandate: require audits, diverse data inputs, community oversight with genuine authority, and the power to suspend any model that fails equity benchmarks. That addresses every concern PRO raises [clipped]

## Turn 5: PRO Pressure Questions

- model: hy4-preview-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You write that an enriched model “still uses incident data as a foundation” ([C2.1]). If that foundation remains the primary input driving patrols, why isn’t your improved system exactly what the motion bans?
[P3.2] Q2: You frame the choice as these maps versus “district commanders exercising judgment” ([C2.5]), but my alternative is deployment driven by community priorities, investigations, and hospital/harm data. Why compare the banned system only to the worst substitute instead of that operational alternative?

## Turn 6: CON Pressure Questions

- model: mimo-v2.5-pro
- raw_words: 94
- clipped_words: 94
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: You claim enriched systems may no longer be "the banned one" ([P2.1]), but the motion bans systems running *primarily* on historical data. What threshold of incident-data reliance triggers the ban—51 percent? 70? How would a city know in advance whether a proposed system crosses your line?
[C3.2] Q2: Hospital admissions for assaults reflect proximity to hospitals, insurance coverage, and whether victims feel safe seeking care—each shaped by prior institutional patterns. If historical incident data is too contaminated by policing to use, why isn't your preferred alternative tainted by the same kind of structural bias?

## Turn 7: PRO Rebuttal 2

- model: hy4-preview-high
- raw_words: 309
- clipped_words: 309
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: The motion’s word is “primarily,” not a statistic like 51 percent. That is a functional test: does historical arrest and incident data supply the dominant signal telling the map where to send patrols? If yes, it is banned, even with hospital admissions added or violence reweighted. Your [C2.1] says it still uses incident data as a “foundation.” A foundation is primary.
[P4.2] If stripping it out collapses the patrol recommendation, the tool is prohibited. If the map survives because harm indicators, investigations, and community priorities do the work, you have a different tool, not the banned one. Cities can know in advance by auditing the model and running a removal test: strip historical enforcement inputs and see whether the deployment logic survives. No decimal threshold is needed.
[P4.3] A2: Hospital admissions are unequal, but not contaminated in the same way. They track people arriving wounded—harm—not police stops and arrests generated by the deployment the model later justifies. That endogenous feedback is the motion’s target: patrols create records, records justify more patrols. Hospital, EMS, and trauma data have access biases, so they must be triangulated and adjusted, not worshipped; but they do not let a department launder its own stop history into a self-fulfilling heat map.
[P4.4] The alternative is not virgin data; it is plural inputs, open to correction, without the ratchet.
[P4.5] That is why PRO still wins. Your questions concede the decider: you keep defending a system whose “foundation” is historical enforcement data, and the motion bans systems run primarily on that foundation. Refinement leaving the foundation intact is still prohibition’s target; refinement that dethrones it is not. Audits arrive after the stops, after the trust loss, after another quarter of skewed records.
[P4.6] Prohibition retires the self-referential engine and leaves cities free to use hospital data, investigations, and community priorities—without pretending a map built on yesterday’s arrests is today’s safety.

## Turn 8: CON Rebuttal 2

- model: mimo-v2.5-pro
- raw_words: 337
- clipped_words: 337
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: PRO's removal test at [P4.2] actually proves my case. If a city enriches a system with hospital admissions, investigation leads, and harm-weighted indicators so that stripping historical enforcement inputs leaves the deployment logic intact, then by PRO's own functional test the system is no longer "primarily" based on historical data—and it is not banned. That means the policy answer is mandated enrichment, not prohibition. PRO has just described how to keep predictive patrol systems legal.
[C4.2] I agree with that description; I disagree that a ban is needed to force it.
[C4.3] A2: PRO's "operational alternative" is not actually operational. Community priorities and hospital data are inputs—values and signals—but someone must still translate them into specific patrol assignments at specific times. PRO never identifies who does that translation or how. Without a predictive system, the work falls to district commanders exercising discretionary judgment, which is the politically influenced, opaque deployment both sides acknowledge is worse.
[C4.4] You cannot compare my tool to an idealized vision that lacks any mechanism for allocating officers to geography. The comparison is to what actually fills the gap, and what fills the gap is gut instinct and political pressure.
[C4.5] These two answers reveal why CON wins the overall debate. PRO's own test demonstrates that refinement keeps systems outside the ban's scope—if enrichment makes incident data non-primary, the tool survives. That is precisely the mandate I have advocated: require audits, diverse data inputs, community oversight with genuine authority, and the power to suspend any model that fails equity benchmarks. PRO is defending the same policy and calling it prohibition.
[C4.6] The motion asks for a ban. But every concern PRO raises—feedback loops, biased data, trust erosion—is addressed by mandated improvement without destroying a tool that helps cities respond to surging violence faster than any alternative currently operational. PRO has not shown that community priorities or hospital data alone can generate a patrol map without falling back on discretion. They have shown that enrichment works.
[C4.7] That is the reason to reject the ban and adopt the mandate.

## Turn 9: PRO Closing

- model: hy4-preview-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C2.1], [P4.1], [P4.5], [C4.1], [P4.2]
- missing_claim_id_refs: (none)

[P5.1] The debate reduces to one line: may a patrol map be driven primarily by a department’s own past stops and arrests? No. CON’s enriched model treats historical incident data as its “foundation” [C2.1]; a foundation is primary [P4.1]. If stripping that foundation collapses deployment logic, the system runs primarily on historical enforcement data and is the banned system. Hospital data does not change the driver; it dresses up the ratchet.
[P5.2] Mandates leave the engine running; audits arrive after the stops and eroded trust [P4.5]. Regulation is after-the-fact; the harm is continuous.
[P5.3] CON says our removal test proves its case [C4.1], but the test makes the ban precise, not indiscriminate. If harm indicators, investigations, and community priorities can carry the map once historical enforcement inputs are stripped, the tool survives as a different, lawful system [P4.2]. Prohibition never threatened that; it retires only the one that cannot stand without yesterday’s arrests. The mandate CON demands is either superfluous—improved tools remain legal—or fatal, because it would license the banned foundation.
[P5.4] PRO wins because a city must not let police launder enforcement history into patrol orders. Prohibition draws that line. Refinement leaving the foundation intact is the target, not an exemption.

## Turn 10: CON Closing

- model: mimo-v2.5-pro
- raw_words: 219
- clipped_words: 219
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P4.2]
- missing_claim_id_refs: (none)

[C5.1] PRO's removal test is the debate's decisive moment, and it decides for CON. PRO says: strip historical enforcement inputs from a patrol model, and if the deployment logic survives on harm indicators, investigations, and community priorities, the system is a "different, lawful tool" that prohibition never threatened [P4.2]. That is exactly the enrichment I have advocated—mandate the shift so that incident data stops being the primary driver. PRO described my policy and called it prohibition.
[C5.2] This creates an inescapable dilemma for the motion. If enrichment genuinely moves the foundation, then mandated enrichment accomplishes everything a ban would, without destroying a transitional tool cities are already refining. If enrichment does *not* move the foundation—if any system touching incident data is still "the banned one"—then the ban sweeps far beyond what PRO intends, capturing systems overwhelmingly driven by hospital admissions and community priorities. PRO cannot have both a precise ban that targets only the self-referential engine and a broad ban that catches every system with incident data in its inputs.
[C5.3] The motion asks for prohibition. But every harm PRO identifies—feedback loops, eroded trust, bias laundering—is cured by mandated enrichment without the costs of a ban: slower emergency allocation, loss of pattern-detection during violence surges, and displacement into the discretionary, politically driven deployment neither side defends.
[C5.4] Refine the tool. Reject the ban.
