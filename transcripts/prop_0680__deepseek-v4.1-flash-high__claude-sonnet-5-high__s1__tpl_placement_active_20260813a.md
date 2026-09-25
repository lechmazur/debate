# Debate prop_0680__deepseek-v4.1-flash-high__claude-sonnet-5-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0680
- proposition: Cities should prohibit predictive policing systems that recommend where to deploy patrols based primarily on historical arrest and incident data.
- model_pro: deepseek-v4.1-flash-high
- model_con: claude-sonnet-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: deepseek-v4.1-flash-high
- raw_words: 303
- clipped_words: 303
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Predictive policing built on historical arrest and incident data does not forecast crime. It forecasts police contact. An arrest is not a neutral measurement of offense; it is the product of an officer being present, choosing to stop, and choosing to charge. Incident data is no better: reports depend on who trusts police, who gets believed, and where officers already patrol.
[P1.2] Feed that into an algorithm and the output is a map of past enforcement, not future harm.
[P1.3] Then the loop closes. The system flags a neighborhood as hot. More patrols flood in. More stops, citations, and low-level arrests follow.
[P1.4] Those new arrests become tomorrow's training data, and the neighborhood looks hotter still. The system does not discover the hot spot; it manufactures it. This is not a speculative edge case—it is the logical core of deploying police based on police records.
[P1.5] The harm is concentrated and coercive. Over-policed neighborhoods—often poor and Black—receive more surveillance, more frisks, more arrests, and more violent encounters, all justified by a score that treats their prior over-policing as evidence of danger. That is a self-fulfilling prophecy with constitutional stakes. The people targeted bear the cost; the algorithm bears none.
[P1.6] Prohibition is the right remedy because patrol allocation is a unique exercise of state force. No audit can undo a stop, a search, or a death. And no technical fix solves the label problem: if you correct for bias in the data, you are still using the biased product of police decisions as the ground truth. Cities can respond to emergencies, investigate crimes, and invest in community violence prevention.
[P1.7] They should not use historical enforcement records as the primary driver of where to send patrols. The debate is not whether data can be useful; it is whether cities should launder past discrimination into future policing. They should not.

## Turn 2: CON Opening

- model: claude-sonnet-5-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Predictive policing is not compared against a perfect world. It is compared against how patrol allocation happens without it: informal discretion, precinct captains reacting to political pressure, officers patrolling wherever they "feel" crime is, wherever the loudest complaints come from. That baseline is not neutral either—it is just invisible. A prohibition does not remove bias from policing; it removes the one part of the process that can be measured, audited, and corrected.
[C1.2] Consider what "incident data" actually contains. Most of it is not arrests—it is 911 calls, victim reports, shots-fired sensors, burglary reports. When a resident in a high-crime block calls police because their car was stolen, that is a request for protection, not an act of state coercion. Ignoring where residents are actually calling for help, in the name of avoiding bias, abandons exactly the neighborhoods that need service most.
[C1.3] Under-policing violent crime in poor communities is not a neutral default; it has its own victims, and they are disproportionately the same populations PRO claims to protect.
[C1.4] PRO's feedback-loop story assumes patrol presence mechanically generates arrests that then inflate future scores. But that loop is a design flaw to fix, not a reason to ban the entire category. Cities can weight victim-reported violent crime over discretionary low-level arrests, cap how much any one data point moves future allocation, and require independent audits before renewal. Prohibition forecloses every one of those improvements in favor of pure guesswork.
[C1.5] Notice also the word "primarily" in the resolution. PRO must defend banning any system where historical data is the main input, even alongside demographic-neutral factors like population density or reported violent victimization. That is a sweeping ban on data-informed policing itself, not a narrow fix for a bias problem.
[C1.6] The real choice is not "biased algorithm" versus "unbiased city." It is transparent, auditable, correctable data systems versus opaque human discretion that has never once been held to the same scrutiny PRO now demands only of software.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4.1-flash-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.2], [C1.4], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON’s case rests on a seductive swap: it calls today’s discretion invisibly biased and predictive policing measurably biased, then asks us to prefer the bias we can see. But measurement is not correction. If the training label is police contact, auditing the model only audits how faithfully it reproduces that contact.
[P2.2] Yes, 911 calls are not arrests [C1.2]. But the motion does not ban answering calls. It bans systems that recommend patrol deployment based primarily on historical arrest and incident data. Live dispatch and community requests remain.
[P2.3] The question is whether a city should turn the historical geography of who calls, who is believed, and who gets stopped into a predictive patrol map. That is not protection; it is predicting demand shaped by past access and trust.
[P2.4] The proposed fixes—weights, caps, audits—are not fixes [C1.4]. Weighting victim-reported violent crime over low-level arrests still uses reported crime, itself filtered by patrol presence and reporting behavior. Caps only limit how fast the loop spins. Audits cannot recover unreported crimes or erased stops, and no audit reverses a stop, a search, or a death.
[P2.5] The correction arrives too late.
[P2.6] “Primarily” is not sweeping; it is the line that matters [C1.5]. Cities may use population density, infrastructure, live calls, credible threats, and community violence intervention. They cannot make historical enforcement the main engine of patrol allocation. CON is right that under-policing has victims.
[P2.7] The remedy is answering current calls and investing in violence prevention, not sending patrols where the algorithm says they were already most policed.
[P2.8] The real choice is not opaque discretion versus software. It is a feedback machine that launders past bias into future force versus a city that must justify patrols through current, public, non-predictive criteria. Prohibition stops the laundering.

## Turn 4: CON Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] CON's opponent tells us "measurement is not correction" [P2.1]. Flip that: unmeasured discretion is uncorrectable by definition. A precinct captain who moves patrols on gut instinct, political pressure, or personal prejudice leaves no data trail to audit, no model to inspect, no pattern to challenge in court. PRO's whole case is that visible bias is worse than invisible bias.
[C2.2] That is backwards. You cannot fix what you cannot see, and prohibition guarantees you cannot see it.
[C2.3] Now watch the carve-outs pile up in P2.6: population density, live calls, credible threats, infrastructure. Ask what a "credible threat" assessment or "infrastructure risk" score is built from if not... prior incidents at that infrastructure, prior calls at that address, prior threat patterns. PRO's permitted inputs are historical data wearing a different label. The resolution bans systems "primarily" driven by historical arrest and incident data, but any serious multi-factor allocation model will lean heavily on exactly the categories PRO just blessed.
[C2.4] That means either the ban is symbolic—cities relabel their inputs and keep functionally similar systems—or it is not symbolic and it also guts the live-call responsiveness PRO claims to preserve. PRO cannot have it both ways.
[C2.5] On the loop: PRO never explains why a cap on how much one data point moves future allocation, combined with independent audit and mandatory reweighting toward victim reports, fails to break compounding. The claim is repeated, not argued. "The correction arrives too late" [P2.5] is asserted about every regulatory fix ever proposed for every institution; it proves nothing specific about this one.
[C2.6] Here is the actual trade PRO is offering: give up a correctable, evidence-based tool that can be forced to answer where shootings and burglaries are actually reported, in exchange for a ban that leaves discretion untouched and pushes the same historical signal back into policing through disguised categories. That is not a remedy. That is theater that abandons the neighborhoods calling for help.

## Turn 5: PRO Pressure Questions

- model: deepseek-v4.1-flash-high
- raw_words: 67
- clipped_words: 67
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You call caps and audits a fix [C2.5]. What stops the next patrol from being sent because past arrests made a block “hot,” before any audit or renewal can intervene?
[P3.2] Q2: If permitted inputs are all just historical data relabeled [C2.3], do you actually defend using historical arrest data as the primary driver of patrol allocation—or can you name a primary input that is not historical?

## Turn 6: CON Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.6], [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO says "credible threats" and "infrastructure risk" are permitted [P2.6], but these categories are built from prior incident records. Where exactly is the line between a permitted "current" criterion and a banned "historical" one—can PRO name a concrete, non-historical input a city could use tomorrow?
[C3.2] Q2: PRO claims "no audit reverses a stop" [P2.4] as a reason to ban predictive tools. Doesn't that same logic condemn all patrol allocation, including pure officer discretion, since no audit reverses a bad discretionary stop either?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4.1-flash-high
- raw_words: 314
- clipped_words: 314
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C1.4]
- missing_claim_id_refs: (none)

[P4.1] A1: The line is temporal and causal, not a label. A live 911 call reporting an in-progress shooting, a named suspect at a known address, a real-time credible threat, a permitted event letting out, a closed road or severe weather—these direct patrols to current need or static logistics. They do not predict tomorrow from yesterday's police contacts. Historical incident data is an aggregate of past calls, stops, and reports used to score a place.
[P4.2] Sending patrols because a call is happening now is dispatch; sending them because a block generated many past reports is the banned prediction loop. That is concrete and workable: cities can act on current demands tomorrow without making historical enforcement the primary engine.
[P4.3] A2: That same logic does not condemn all patrol allocation. "No audit reverses a stop" defeats audits as a sufficient remedy for a system that manufactures its own justification. It does not mean no allocation can be constrained. A city can publish non-predictive deployment rules, answer live calls, use community violence intervention, and discipline discretionary abuses.
[P4.4] The predictive system is different because it scales past coercion into future force with an algorithmic alibi. If CON's audits can correct that, they can audit ordinary deployment too; prohibition simply removes the self-reinforcing multiplier.
[P4.5] So CON's relabeling objection collapses. There are non-historical inputs. The audit objection collapses too: we are not demanding perfection, we are refusing to encode past bias as the primary basis for patrols. CON's best fixes—caps and reweighting [C1.4]—admit the loop compounds; they just slow it.
[P4.6] Patrols are coercive state force, and the person stopped cannot wait for renewal. CON never explains why a slower loop is acceptable when each turn is a stop. The proposition wins because it draws the only line that stops the laundering while preserving current response and prevention: no historical arrest and incident data as the main engine of where patrols go.

## Turn 8: CON Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Caps and reweighting are not something that waits for a renewal cycle—they are built into the deployment logic itself. A decay function that discounts the weight of an arrest the moment it ages, or a rule that live victim reports of violence always outrank historical incident scores in that day's allocation, operates on every single patrol cycle, not once a year. Compare that to PRO's own fallback: an officer or captain who has decided a block is "always trouble."
[C4.2] That bias applies on every shift, with no decay, no cap, no audit, ever. PRO is demanding a perfect brake on the tool that at least has a mechanism, while accepting zero brake on the tool that has none.
[C4.3] A2: I defend weighted historical data as one input among several, not history "wearing a disguise." But notice what PRO just conceded in P4.1: "a live 911 call," "a real-time credible threat," "a named suspect at a known address" are all offered as acceptable primary inputs. Those are incident data. The only difference PRO offers is timing—today's call versus last month's call.
[C4.4] But a shooting reported this morning becomes "historical" the instant it's used to route tomorrow's patrol. PRO has not drawn a line between prediction and dispatch; it has drawn a line between data that is one day old and data that is thirty days old, and called one banned and the other permitted. That is not a workable legal test a city could actually implement—it is a moving target dressed up as clarity.
[C4.5] That is the deeper problem with PRO's whole rebuttal: it wants the audit trail without the tool that produces it. P4.3 says discretionary abuses can be "disciplined"—but discipline requires evidence, and evidence requires exactly the kind of logged, patterned data PRO wants banned. Prohibition doesn't stop the laundering of bias into force. It just launders it through discretion instead of code, and removes the one record that could ever catch it.

## Turn 9: PRO Closing

- model: deepseek-v4.1-flash-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate turns on one question: what actually breaks the loop CON admits compounds? CON's answer is a decay function or a priority rule — a slower loop. But every turn of that loop is a stop, a frisk, a person pressed against a car. A slower machine that still treats where we policed yesterday as the primary reason to police there today has not stopped manufacturing hot spots; it has scheduled them.
[P5.2] CON's final move is that prohibition just launders bias through discretion instead of code. But that concedes the decisive point: discretion is bounded by a human being who can be questioned, disciplined, and held to account in a courtroom. The algorithm's output arrives as a neutral score, and CON's own framing — auditable, correctable, evidence-based — is exactly the alibi that makes it harder to contest, not easier. A captain can be asked why he sent officers to a block.
[P5.3] Software answers that the model recommended it.
[P5.4] Prohibition wins because it refuses to let the historical geography of who was stopped become the main engine of who gets stopped next. Answer the live call. Fund prevention. Do not launder past coercion into future force.

## Turn 10: CON Closing

- model: claude-sonnet-5-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.3]
- missing_claim_id_refs: (none)

[C5.1] The debate comes down to one comparison PRO never actually wins: which world produces less bias in practice — a logged, auditable system forced to justify itself, or a ban that hands allocation back to unlogged human judgment?
[C5.2] PRO's closing repeats that "software answers that the model recommended it" [P5.3], as if that's worse than a captain's unwritten instinct. But a model's recommendation is discoverable, challengeable, and reversible through policy change. A captain's instinct leaves no such trace — PRO conceded exactly this in P4.3, where "discipline" for discretionary abuse was offered as the safeguard, without ever explaining what evidence would trigger that discipline once the data trail is banned.
[C5.3] PRO also never answered C4.3/C4.4: the claim that "live" versus "historical" data is a timing distinction, not a bias distinction. A shooting reported this morning is incident data the moment it routes tomorrow's patrol. PRO's whole permitted category collapses into the banned one.
[C5.4] Prohibition doesn't remove bias from patrol allocation. It removes the only mechanism that could ever measure, cap, or correct it — and hands the same historical pull back to discretion, unrecorded and unaccountable. That is the losing trade.
