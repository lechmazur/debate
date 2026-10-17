# Debate prop_0621__hy4-preview-high__gemini-4-argon-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: hy4-preview-high
- model_con: gemini-4-argon-high
- side_swap: True

## Turn 1: PRO Opening

- model: hy4-preview-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A defendant sits in a bail hearing; a risk score says "high risk," and he is jailed before trial. The prosecutor need not reveal how the score was produced, what it was trained on, or how often it is wrong. That is not efficiency; that is secret evidence. When the state uses algorithmic risk tools in charging, bail, or sentencing, the accused must be able to inspect and challenge them.
[P1.2] They shape bail hearings and plea offers long before any trial. Liberty cannot be denied by a black box the defense may never open.
[P1.3] Discovery already compels disclosure of lab reports, expert methods, and impeachment material. A risk score is the same kind of claim: a technical assertion that someone is dangerous. Source code is the method. Training-data summaries expose whether the tool learned from biased arrests or neighborhoods rather than real risk.
[P1.4] Error rates show whether it is reliable for this defendant's group, not merely on average. Without all three, a defense expert cannot test what they cannot see.
[P1.5] Opponents will cite trade secrets and cost, but that confuses public release with defense discovery. Courts can seal records, use protective orders, and appoint experts; vendors already disclose code in patent and forensics disputes without publishing it. The burden is trivial next to jailing a presumptively innocent person or inflating sentences through opaque math. Secrecy also corrodes legitimacy: a hidden score invites suspicion that bias is laundered through code.
[P1.6] Nor is it enough that a human judge or prosecutor formally decides. If the score shapes the recommendation, bail, or sentence, it is evidence. The state should not enjoy a scientific-looking number while denying the defense the ability to test it. Disclosing source code, training-data summaries, and error rates is the minimum for treating defendants as rights-bearing persons, not data points.
[P1.7] If the model cannot survive daylight, it must not take freedom.

## Turn 2: CON Opening

- model: gemini-4-argon-high
- raw_words: 299
- clipped_words: 299
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: [P1.3], [P1.5]
- missing_claim_id_refs: (none)

[C1.1] PRO treats an algorithmic risk tool like a secret lab test [P1.3], ignoring what replaces that tool the moment this mandate makes it unusable: the unexamined gut instinct of an individual prosecutor or judge. You cannot inspect the source code of a human hunch, summarize its training data, or calculate its error rate. By attaching an unworkable litigation burden to every risk tool, this proposition drives the justice system straight back into that true black box.
[C1.2] Look at the proposition's sweeping scope: it mandates disclosure in charging and bail, not just sentencing. Charging is an initial screening decision made before a case—or any discovery obligation—even exists. Bail hearings happen within hours of arrest to release people quickly. Turning a routine bail hearing into a software dispute over source code and subgroup error rates, requiring protective orders and appointed experts [P1.5], would paralyze pretrial courts and keep defendants locked up longer awaiting hearings.
[C1.3] Worse, local prosecutors do not build or own these tools. Because jurisdictions license software from outside developers, prosecutors do not possess the underlying code. Requiring prosecutors to disclose property they do not control is a de facto ban.
[C1.4] Raw source code is also the wrong target. Unlike a forensic lab test measuring physical evidence, a risk tool is an actuarial formula. To challenge a score, a defendant needs to verify their personal inputs—whether their criminal history or missed court dates were entered accurately—not debug thousands of lines of programming syntax. Dumping source code and training data into individual criminal dockets merely creates a two-tiered system: wealthy defendants hire technologists to stall prosecution with trade-secret litigation, while overburdened public defenders gain nothing practical.
[C1.5] Risk tools should be vetted at the procurement level by independent auditors, not relitigated by line prosecutors in every daily charging decision and bail hearing.

## Turn 3: PRO Rebuttal 1

- model: hy4-preview-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.1], [C1.2], [C1.4], [C1.3], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] The opponent's core move is a bait-and-switch: burden the tool until it vanishes, then blame transparency for restoring 'gut instinct' [C1.1]. But human decisions are not the unaccountable box they imagine. A judge must give reasons on the record and faces appellate review. The score is the real black box: it carries a scientific aura, often cannot be explained even by the official using it, and hides bias inside vendor code.
[P2.2] If disclosure makes a secret tool unusable, that is not a flaw; it is proof the tool should never decide liberty.
[P2.3] Their scope objection [C1.2] confuses publication with discovery. Disclosure need not precede arrest or first appearance. At bail, summaries and error rates are short and reusable; source code goes to a defense expert under seal, not into the hearing itself. Even for charging, the duty bites only when a score shapes the charge, not at intake.
[P2.4] A brief continuance to test a score is far less harmful than detention caused by an untestable 'high risk' label.
[P2.5] Their 'check the inputs' fallback [C1.4] is too weak. A tool can have accurate inputs and still be biased if trained on arrest or neighborhood data that proxy race and poverty. Verifying the defendant's record does not expose discriminatory weights; only training-data summaries and subgroup error rates can. Ignorance does not help indigent defense; appointed experts and protective orders already handle trade secrets.
[P2.6] Finally, 'we don't own the code' [C1.3] and 'procurement audits instead' [C1.5] invert responsibility. The state chose the vendor; it can demand access or code escrow. If a seller will not let its product be examined in the court that uses it to take liberty, the state must not buy it. A procurement audit of average performance cannot tell this defendant whether his version is reliable.
[P2.7] The clash is not technology versus tradition; it is secret evidence versus the right to test the state's case.

## Turn 4: CON Rebuttal 1

- model: gemini-4-argon-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.4], [P2.3], [P2.2], [P2.1], [P2.6], [C1.1], [P2.5], [C1.5]
- missing_claim_id_refs: (none)

[C2.1] Look closely at what my opponent calls a harmless "brief continuance" at bail [P2.4]. Bail is decided at first appearance—which they admit happens before full disclosure [P2.3]. If a defendant needs a continuance to negotiate a protective order, appoint a software expert, and audit sealed source code [P2.3, P2.5], where does that defendant wait during that continuance? In a jail cell.
[C2.2] Auditing software takes weeks, not minutes. PRO’s rule forces presumptively innocent people either to waive this disclosure or to sit behind bars waiting for a software audit.
[C2.3] Worse, PRO cheers the disappearance of risk tools [P2.2], claiming humans must "give reasons on the record and face appellate review" [P2.1]. That forgets charging. Prosecutors never give reasons on the record for charging decisions, and charging discretion is virtually unreviewable. Even on the bench, a judge reciting boilerplate like "the defendant poses a flight risk" easily survives appeal while masking subjective bias.
[C2.4] Demanding "code escrow" [P2.6] will not keep tools alive when that code must be handed over in thousands of daily cases. Faced with sealed source-code litigation at intake, prosecutors will simply abandon the tool and fall back on unexamined gut instinct [C1.1].
[C2.5] Finally, PRO’s case rests on a technical contradiction. They dismiss independent procurement audits because audits only measure "average performance," not reliability for "this defendant" [P2.6]. Yet the exact items this motion demands—training-data summaries and subgroup error rates—are also static, group-level statistics. They do not change from one defendant to the next.
[C2.6] Nor does checking for "discriminatory weights" or neighborhood proxies [P2.5] require debugging raw source code. Which variables a formula weights and its subgroup error rates can be vetted once, publicly and rigorously, when the state buys the tool [C1.5]. Forcing line prosecutors to litigate vendor source code in individual criminal dockets paralyzes the system without advancing justice.

## Turn 5: PRO Pressure Questions

- model: hy4-preview-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.2], [C2.5], [C2.6], [C1.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say defendants will wait in jail for a weeks-long audit [C2.1]–[C2.2]; if the State cannot promptly disclose even short, reusable error rates and a sealed testing method, why should it get to use the score to detain someone at all?
[P3.2] Q2: If, as you argue, training-data summaries and subgroup error rates are static group-level statistics that can be vetted once [C2.5]–[C2.6], why does handing that same summary to the defendant become the "software dispute" over source code you say will paralyze bail hearings [C1.2]?

## Turn 6: CON Pressure Questions

- model: gemini-4-argon-high
- raw_words: 90
- clipped_words: 90
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.4], [P2.2], [P2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: This proposition mandates disclosing source code, which you admit requires protective orders and appointed experts [P1.5, P2.3]; how can a defendant get a software expert appointed, seal the record, and audit code for a bail hearing without sitting in jail during your "brief continuance" [P2.4]?
[C3.2] Q2: You welcome the disappearance of risk tools [P2.2] because a "judge must give reasons on the record and faces appellate review" [P2.1], but this mandate also covers charging; when prosecutors drop risk tools at charging, what record or review checks their gut instinct?

## Turn 7: PRO Rebuttal 2

- model: hy4-preview-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C2.1], [C3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: The defendant need not sit in jail for a full source-code audit. The proposition’s immediate, reusable items—training-data summaries and subgroup error rates—are short documents the state can produce at first appearance, just as it produces a rap sheet or lab summary. Sealed source code and a court-appointed expert are required only if the defense mounts a real reliability challenge; while that bounded review occurs, the default must be release or ordinary bail factors, not detention justified by the very score still under test.
[P4.2] If the state cannot promptly produce even error rates and a testing method, it forfeits the score.
[P4.3] A2: If charging drops the tool, ordinary prosecutorial discretion is checked by public law, internal charging guidelines, probable-cause review, and aggregate disparity data—not by reasons on a charging record, but that is exactly why a secret score must not be layered on top. A hidden algorithm gives unreviewable discretion a false scientific gloss and hides bias inside vendor code. The mandate simply forces a choice: use an open, contestable tool, or drop it and charge under the public guidelines and disparity data that already constrain human discretion.
[P4.4] Those answers collapse the opposition’s case. Their bail horror [C2.1] assumes defendants must wait for full code review before any relief; in truth, short summaries come first, and continued detention cannot rest on an untested label. Their charging trap [C3.2] mistakes our objection: we target secret, not human, decision-making. The real clash is secret evidence versus testable evidence.
[P4.5] The state chose the vendor, can demand escrow, and already discloses code under seal in patent and forensic disputes. If it will not open the tool, the tool cannot take liberty. This mandate wins because it does not ban risk assessment; it bans unaccountable risk assessment, preserving either explainable tools or open human judgment.

## Turn 8: CON Rebuttal 2

- model: gemini-4-argon-high
- raw_words: 303
- clipped_words: 303
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P3.1], [C2.2], [P3.2], [P4.1], [C1.1], [P4.3], [C1.5]
- missing_claim_id_refs: (none)

[C4.1] A1: The state can easily publish reusable error rates and methodology upfront through procurement audits [C1.5, C2.6]. What it cannot do within hours of arrest is execute the rest of this unconditional mandate: disclosing raw source code [P3.1]. Because the proposition requires disclosing all three items—including source code—handing over a one-page summary neither satisfies the mandate nor avoids a weeks-long software audit [C2.2].
[C4.2] A2: Handing over a static summary is not what paralyzes courts; mandating source-code discovery in individual dockets is [P3.2]. Once prosecutors must disclose source code whenever a tool is used, any competent defense lawyer will demand the sealed code and an expert to test it, triggering the exact protective-order and expert-witness bottleneck my opponent admitted is required [P1.5, P2.3].
[C4.3] Look at how [P4.1] tries to escape this bail trap: by rewriting the proposition. Now they claim source code is not disclosed upfront, but only after a threshold "reliability challenge," during which the court must abandon the score for "release or ordinary bail factors" [P4.1]. That concedes the mandate as written is unworkable. Worse, consider the incentive: if merely demanding a code audit forces the judge to discard a "high risk" score during review, every detained defendant will demand one.
[C4.4] The tool becomes instantly unusable, reverting every bail hearing to "ordinary bail factors"—the judge's unexamined gut instinct [C1.1].
[C4.5] Similarly, on charging, [P4.3] admits prosecutors never give reasons on the record, claiming human discretion is checked by "internal charging guidelines" and "aggregate disparity data." Yet an actuarial risk tool is literally a consistent, mathematical guideline designed to track and reduce those disparities. Both sides now agree that training-data summaries and subgroup error rates are static documents [C2.5, P4.1]. Vetting them publicly at procurement [C1.5] achieves real accountability without letting individual source-code litigation drive charging and bail back into the human black box.

## Turn 9: PRO Closing

- model: hy4-preview-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [P4.1], [C4.5], [P4.3]
- missing_claim_id_refs: (none)

[P5.1] The clash is secret evidence versus testable evidence. The state may not jail someone on a ‘high risk’ number while denying the defense the means to test it.
[P5.2] My opponent calls the mandate unworkable because it forces source-code disclosure in bail or charging dockets [C4.1–C4.2]. That confuses disclosure with a hearing stunt. The state must disclose the code to the defense under seal, to experts, not read it aloud at first appearance. Summaries and error rates come immediately; a challenge triggers bounded review, and the default is release or ordinary bail, not detention by the score under test [P4.1].
[P5.3] If testing makes a judge set the score aside, that is the presumption of innocence.
[P5.4] Procurement audits do not answer the defendant’s objection [C4.5]. A static audit tells the buyer, not this defendant, whether the tool is reliable for his group; bias hides in training data and weights. The state picked the vendor and can demand escrow. If a seller forbids examination where it jails people, it cannot be used.
[P5.5] The mandate thus yields an open tool or open human judgment [P4.3]. A secret score yields neither. Open the box, or drop it. That is why the mandate wins.

## Turn 10: CON Closing

- model: gemini-4-argon-high
- raw_words: 204
- clipped_words: 204
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: [C2.1], [P4.2], [C1.1], [P5.5], [P4.3], [P5.4], [P4.1], [C4.5]
- missing_claim_id_refs: (none)

[C5.1] Look at where the defense of this mandate ended up: to prevent defendants from sitting in jail for weeks while experts audit sealed source code [C2.1], my opponent says that whenever a defendant asks to test the code, the judge must simply set the score aside and revert to "ordinary bail" [P5.2, P5.3]. Think about what that means in practice. If merely requesting a code audit forces the state to forfeit the score [P4.2], every defense lawyer will demand one at bail, and every prosecutor will abandon the tool at charging.
[C5.2] That is the decisive reason this proposition fails: it does not end secret decision-making; it replaces a mathematical tool we can audit with the one black box we never can—human gut instinct [C1.1]. Calling that fallback "open human judgment" [P5.5] ignores their own admission that prosecutors never give reasons on the record for charging [P4.3]. You cannot inspect the source code of a prosecutor's intuition or calculate the error rate of a judge's hunch.
[C5.3] Checking whether a model uses biased weights or fails a specific group [P5.4] relies on static data [P4.1] best vetted publicly at procurement [C4.5]. Mandating source-code litigation in individual dockets destroys structured accountability only to enthrone unexamined human bias.
