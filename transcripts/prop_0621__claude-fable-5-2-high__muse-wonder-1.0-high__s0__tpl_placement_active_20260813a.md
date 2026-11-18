# Debate prop_0621__claude-fable-5-2-high__muse-wonder-1.0-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: claude-fable-5-2-high
- model_con: muse-wonder-1.0-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-2-high
- raw_words: 366
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A man stands before a judge. A score says "high risk." That number helps decide whether he goes home to his job and kids or sits in a cell for months before trial. He asks the obvious question: how did you arrive at that?
[P1.2] And the answer, in many courtrooms today, is: we can't tell you. The vendor says it's proprietary.
[P1.3] That is the situation the proposition ends. The principle is as old as the adversarial system: if the state uses evidence to take your liberty, you get to test it. We let defendants cross-examine the lab analyst, inspect the breathalyzer's calibration records, and challenge the eyewitness. An algorithm is a witness that cannot be cross-examined unless you can see inside it.
[P1.4] Each of the three disclosures does distinct work.
[P1.5] Error rates tell the judge how much weight the score deserves. A tool that is wrong about a third of the people it labels "high risk" is a very different thing from one that is rarely wrong, and a judge who doesn't know which one she is holding is not exercising discretion but guessing.
[P1.6] Training data summaries reveal whether the tool was built on people like this defendant. A model trained on one population in one decade, using arrests as a proxy for crime, carries those policing patterns into every score it produces.
[P1.7] Source code catches what validation studies miss: bugs, miscoded variables, and inputs weighted in ways nobody disclosed. Forensic software has been found to contain consequential errors once independent experts finally got access. Nobody finds a mistake they are forbidden to look for.
[P1.8] The objections are familiar, and they are weak. On trade secrets, courts handle confidential commercial material routinely through protective orders, and a vendor's profit margin has never outranked a defendant's liberty. If a company won't allow scrutiny, the state should not buy its product. On gaming, these tools mostly run on age and criminal history, and you cannot game your own birth date.
[P1.9] Hold the other side to one question throughout: when the score is [clipped]

## Turn 2: CON Opening

- model: muse-wonder-1.0-high
- raw_words: 299
- clipped_words: 299
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A high-risk label should be challengeable. But this mandate mistakes a data dump for a challenge, and would make decisions less accurate and slower.
[C1.2] First, source code and training summaries do not answer what a court needs: does this tool predict well for people like this defendant, in this jurisdiction? Modern models involve huge codebases and weights learned from data. Handing that pile to a defense lawyer, usually without a data scientist before a bail hearing, reveals almost nothing. Independent local validation does: how scores track actual re-arrest or failure to appear here, and whether this defendant's inputs are correct.
[C1.3] A code dump is theater only well-funded defendants can hire someone to read.
[C1.4] Second, this is an all-or-nothing gate for any use in charging, bail, or sentencing, yet prosecutors often do not own the code. Vendors forced to surrender core property across thousands of cases, despite protective orders, will raise prices or leave. Courts will fall back on unaided human judgment — the one decision-maker with no published error rate, no training summary, and no audit, vulnerable to fatigue, anchoring, and stereotype. Banning the auditable tool entrenches the least auditable system.
[C1.5] Third, raw error rates and weights can mislead and be gamed. An aggregate false-positive rate does not give this person's probability; quoted without base rates, it invites arithmetic errors. Age cannot be faked, but many assessments use employment, housing, treatment compliance, and associates — inputs that can be phrased to a public rubric.
[C1.6] The defendant deserves his score, the facts fed into it, notice of validated limits, and a chance to contest wrong inputs and argue the score deserves little weight. That is confrontation aimed at the decision. This demand instead targets materials that rarely decide reliability, at a cost that drives tools out and leaves discretion darker.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 356
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10]
- cited_claim_ids: [C1.6], [C1.2], [C1.3], [C1.4]
- missing_claim_id_refs: (none)

[P2.1] Look at what has already been conceded. [C1.6] gives the defendant his score, his inputs, and "notice of validated limits." Validated limits are error rates. So one of the three disclosures is agreed, and the real fight is over whether anyone outside the vendor may look inside the machine.
[P2.2] CON's substitute is "independent local validation" [C1.2]. That raises the question of what the validator gets to see. A validation study tells you how a tool performed on average, on past data, as the vendor described it. It cannot tell you whether the software running today matches that description, whether a variable is miscoded, or whether an update quietly changed the weights.
[P2.3] Validation and code inspection answer different questions, and liberty turns on both.
[P2.4] The "theater" objection in [C1.3] proves too much. Most defendants cannot read a DNA lab's protocols either, and we do not conclude that the protocols should stay secret. Code is also the same in every case. One public defender's expert or one university team that finds a flaw has found it for every defendant scored by that tool.
[P2.5] CON's rule guarantees that nobody finds it.
[P2.6] The vendor-exit threat in [C1.4] is the weakest link. Some widely used pretrial tools already publish their factors and weights openly, and they have not vanished. The requirement does not ban algorithms. It filters for the ones that survive scrutiny.
[P2.7] A vendor who would rather leave than be examined under a protective order is telling you something about the product.
[P2.8] Calling the judge "the least auditable system" has it backwards. She states her reasons on the record, in open court, subject to appeal. The secret score is the only participant in that courtroom that never has to explain itself.
[P2.9] On gaming, CON would hand over the inputs and let defendants contest them, which already reveals what matters. Those inputs are also verified by officers, not self-reported. And if a statistic can mislead, the cure is explaining it, not hiding it.
[P2.10] So the choice is not tools versus no tools. It is tested [clipped]

## Turn 4: CON Rebuttal 1

- model: muse-wonder-1.0-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] That concession proves overbreadth, not victory. A defendant should get a plain-language local validation summary: how the tool performed, for whom, and with what uncertainty. A judge can use that at tomorrow's bail hearing. It does not follow that prosecutors must produce source code and training-data summaries in every charging, bail, and sentencing case — material that rarely turns an outcome summary into an answer about this person.
[C2.2] Silent updates and miscoded variables are real risks, but they argue for independent auditors, not case-by-case dumps. An auditor with full access can compare deployed and tested versions, inspect the code once, suspend a faulty tool, and publish findings for everyone. PRO instead makes the prosecutor a courier, the defense lawyer a software reviewer, and a protective order the only barrier against repeated circulation.
[C2.3] The DNA analogy supports that distinction. Disclosing lab protocols lets qualified experts test whether they were followed in this sample; it does not assume every attorney can audit the underlying science. Here too, the live questions are whether this person's inputs were right, the approved version was used, and local performance justifies weight. Central review answers systemic flaws once.
[C2.4] Repeated dumps answer them rarely, expensively, and unequally.
[C2.5] Publishing factors and weights is not surrendering source code, architecture, and training summaries. That some simple tools can be open does not show every accurate vendor will accept disclosure-by-litigation. If better tools withdraw, a judge's reasons on the record will not rescue the replacement: a hunch can be elegantly explained on appeal while having no measured accuracy at all.
[C2.6] Gaming and statistical confusion survive as well. Exact thresholds can shape how dynamic claims about work, housing, associates, or compliance are framed before verification catches up. In a brief hearing, an aggregate error rate more often becomes a false personal probability than it informs discretion.
[C2.7] Keep usable outcome disclosure. Reject a mandate that confuses auditor access with a dump in every case.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 107
- clipped_words: 107
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your independent auditor in [C2.2] gets "full access" to the code and can publish findings, so you accept that code inspection matters. If that auditor is selected and paid by the state or the vendor, why should the defendant whose liberty is at stake be the one party forbidden to check the auditor's work?
[P3.2] Q2: You warn that "better tools" will withdraw [C2.5]. Can you name any feature of a risk tool that makes it more accurate but cannot survive expert review under a protective order, and if a vendor refuses even that, on what basis does a court know the tool is better at all?

## Turn 6: CON Pressure Questions

- model: muse-wonder-1.0-high
- raw_words: 70
- clipped_words: 70
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If a prosecutor does not own a vendor's source code and the vendor refuses disclosure, must the court exclude even a locally validated tool and rely solely on unaided judicial judgment?
[C3.2] Q2: Which specific error rate must be disclosed when overall accuracy, false-positive rates, and false-negative rates cannot all be equal across groups with different base rates, and how is a judge supposed to apply it to this defendant?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 358
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C2.1], [C2.2], [C2.7]
- missing_claim_id_refs: (none)

[P4.1] A1: Yes. If the vendor refuses, that tool stays out, just as a lab result stays out when the lab won't let anyone examine its method. But the fallback is not "unaided judgment." Open tools already exist, and a prosecutor who "does not own the code" is describing a contract the state chose to sign.
[P4.2] Write disclosure into the next procurement and the problem disappears. And "locally validated" assumes the very thing in dispute: a validation study cannot confirm that the software running today is the software that was studied.
[P4.3] A2: All of them. That means overall accuracy, false positives, and false negatives, broken out by group alongside base rates. The fact that these cannot all be equal is the strongest reason for disclosure, not an objection to it. Someone decided which errors this tool tolerates and who bears them.
[P4.4] That is a moral choice, and CON would have it made privately by a vendor. The judge applies the figures as weight, not as a personal probability: "among people labeled like this defendant, the label is wrong this often." That is how courts treat every imperfect witness.
[P4.5] Now look at what remains of the disagreement. CON concedes error-rate disclosure [C2.1]. CON also concedes that code inspection matters, since its auditor gets "full access" [C2.2]. The only live dispute is who may look.
[P4.6] CON's answer is that an auditor selected by the state may look, and the person facing the cell may not. The adversarial system exists to prevent exactly that arrangement. We do not tell defendants the crime lab has been reviewed by someone the government trusts, so their expert need not bother.
[P4.7] The "dump in every case" image [C2.7] is also misleading. The code is the same in every case. One review under a standing protective order serves every defendant that tool scores. An auditor and defense access work together, with defense access checking the auditor.
[P4.8] Weigh the worst cases. If CON is right, some jurisdictions switch to transparent tools. If CON's rule prevails and the auditor misses something, [clipped]

## Turn 8: CON Rebuttal 2

- model: muse-wonder-1.0-high
- raw_words: 322
- clipped_words: 322
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: [P4.7], [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: The defendant is not forbidden to check the auditor's work; he is denied custody of someone else's code, which is different. He gets the auditor's report, local performance by group, version identification, his own inputs and score, and can cross-examine the auditor, submit contrary expert evidence, and challenge whether testing matches the deployed tool. An auditor should be court- or standards-body-appointed, not vendor-paid, with published methods defendants can attack. Checking conclusions does not require handing every litigant the underlying trade secret.
[C4.2] A2: Yes: costly curated training data, tuned model weights, and ensemble architecture can make a tool more accurate, and they can survive one confined audit while not surviving disclosure as routine litigation material in thousands of charging, bail, and sentencing matters. Protective orders vary, files circulate, and competitors learn from repeated expert access. A court knows a tool is better not from a vendor's promise but from blind, prospective local validation: do its predictions, locked in advance, track failure to appear and re-arrest better than alternatives here?
[C4.3] Those answers leave PRO defending a narrower point than the motion. If outcomes, inputs, version, and audit findings are contestable, the remaining demand is possession of code and training summaries themselves. PRO even says "The code is the same in every case" [P4.7]. That argues for inspecting it once, centrally, not for making prosecutors disclose it whenever a tool is used in charging, bail, or sentencing.
[C4.4] PRO's own answers show the costs. In [P4.1], a locally validated tool "stays out" if the vendor refuses—so tested help is discarded for unaided judgment or a weaker open tool, with no showing the replacement predicts better. In [P4.3], disclosing "all of them" does not answer which tradeoff should govern; it multiplies context-dependent rates under time pressure, while the usable local summary CON grants does the translation work. Liberty is protected by a timely, focused challenge, not by excluding validated tools for want of a code dump.

## Turn 9: PRO Closing

- model: claude-fable-5-2-high
- raw_words: 205
- clipped_words: 205
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: [C4.1], [C4.2]
- missing_claim_id_refs: (none)

[P5.1] Everything has narrowed to one sentence in [C4.1]: the defendant may "cross-examine the auditor" but is "denied custody" of the code.
[P5.2] Picture that cross-examination. The auditor testifies that the software is sound. Defense counsel asks how we know. The answer is: I looked, you can't.
[P5.3] That is not confrontation. It is a state-approved witness vouching for evidence the accused may never see, and it is the very arrangement the adversarial system exists to refuse.
[P5.4] CON agrees the code must be inspected, that error rates must be disclosed, and that bugs and silent updates are real. Its only remaining claim is that the one person facing the cell should take the inspector's word for it.
[P5.5] Against that, CON offers a prediction that vendors might leave. But [C4.2] concedes a court knows a tool is good through testing, not through secrecy. Nothing that makes a tool accurate requires hiding it from a defense expert under a protective order. A vendor that walks takes away only a product nobody adverse was ever allowed to check.
[P5.6] If we are wrong, some courts use open tools. If CON is wrong, a man sits in jail on a flaw only a trusted insider was permitted to miss.
[P5.7] Let the defendant look.

## Turn 10: CON Closing

- model: muse-wonder-1.0-high
- raw_words: 201
- clipped_words: 201
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.7], [P4.1]
- missing_claim_id_refs: (none)

[C5.1] The decisive choice is not whether a risk tool gets inspected. It does. It is whether inspection must become prosecutor disclosure of code and training summaries in every charging, bail, and sentencing case.
[C5.2] That extra step is where PRO loses.
[C5.3] Their own case proves why. “The code is the same in every case” [P4.7]. So inspect it once, by an independent auditor; publish local error rates by group, the version used, and this defendant’s inputs and score; let the defense cross-examine the auditor and challenge every conclusion. That gives the man facing jail a timely weapon he can use at tomorrow’s hearing.
[C5.4] PRO would discard that weapon when a vendor refuses litigation disclosure, even for a tool that local prospective testing shows predicts better [P4.1]. The replacement is not scrutiny. It is unaided judgment or a weaker open tool — chosen not because it is more accurate, but because its code was easier to hand over.
[C5.5] Liberty is not protected by possession of a codebase a bail lawyer cannot read in time. It is protected by a focused, contestable record and by keeping the most accurate, audited tool available to challenge. Vote against a mandate that sacrifices both for a dump.
