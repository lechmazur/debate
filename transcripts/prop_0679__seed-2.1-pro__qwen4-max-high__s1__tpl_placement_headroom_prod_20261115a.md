# Debate prop_0679__seed-2.1-pro__qwen4-max-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: seed-2.1-pro
- model_con: qwen4-max-high
- side_swap: True

## Turn 1: PRO Opening

- model: seed-2.1-pro
- raw_words: 288
- clipped_words: 288
- claim_ids: [P1.1], [P1.2], [P1.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Criminal trials turn on proof beyond a reasonable doubt, where a single misrepresented detail can separate acquittal from decades of incarceration, or even execution. That high-stakes context demands a default rule excluding AI-generated summaries, translations, and reconstructions unless an independent human expert verifies their accuracy, for one unshakable core reason: fluent, undetectable hallucination is not a fixable bug in current generative AI systems—it is an inherent, well-documented feature. Generative AI produces output that sounds authoritative, coherent, and precise even when it invents case citations, misstates witness testimony, flips the nuance of a translated phrase from self-defense to premeditation, or fills gaps in a surveillance reconstruction with invented details that never happened.
[P1.2] Unlike a human witness or expert who can be cross-examined about their perceptual gaps, memory lapses, or analytical biases, an AI model cannot account for why it inserted a false detail, because it does not “know” the difference between verified source material and statistically plausible filler it generated to complete a prompt. Placing the burden on the party offering the evidence to secure independent human verification is not a rejection of AI as a productivity tool. Attorneys and investigators can use AI to sift thousands of documents, flag leads, or draft initial translations to speed up work, just as they use spellcheck or legal search tools, but work product offered as evidence of fact carries a far higher burden of reliability.
[P1.3] It is a guardrail against the predictable injustice of asking underresourced defendants, time-strapped judges, and lay juries to spot subtle, convincing fabrications after evidence has already been admitted and colored the jury’s perception of the case. Without that presumption, the justice system will absorb unvetted AI errors at scale, and innocent people will pay the price.

## Turn 2: CON Opening

- model: qwen4-max-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Authentication already does this work. No exhibit proves a fact until a human takes the stand, lays a foundation, and answers for it — the translator who swears to the rendering, the analyst who explains the reconstruction and produces the source footage. Unverified machine output is already inadmissible. So this presumption either restates existing law, or it adds something.
[C1.2] What it adds is the phrase "independent human expert," and that phrase is a resource test wearing a reliability costume.
[C1.3] The state has a crime lab, a budget, and a roster of certified analysts; it can buy verification for its AI-assisted video reconstruction. The defendant has a public defender with a crushing caseload and a phone recording in a dialect spoken by a few thousand people, for which no certified expert exists anywhere in the state. Under this rule, the prosecution's reconstruction comes in with a signature, and the defendant's exculpatory translation is presumptively out — not because it is wrong, but because he cannot afford to prove it right.
[C1.4] The case for this motion is built on underresourced defendants; the motion itself is what disarms them.
[C1.5] And the signature guarantees little. A busy expert who skims an output and initials it satisfies the rule completely while adding no accuracy. Meanwhile, human forensic disciplines — bite marks, hair comparison — have sent innocent people to prison with credentials attached. The rule screens for provenance and paperwork, not truth.
[C1.6] The real question is whether a specific claim can be checked against a specific source, and courts already ask that exhibit by exhibit, on cross-examination.
[C1.7] You cannot cross-examine a model — you cannot cross-examine a breathalyzer either. You cross-examine the operator, the inputs, the log, the error rate. That safeguard is already human. This rule replaces it with a credential the party with money will always clear.

## Turn 3: PRO Rebuttal 1

- model: seed-2.1-pro
- raw_words: 299
- clipped_words: 299
- claim_ids: [P2.1], [P2.2], [P2.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] That argument flips both the burden of proof and the power dynamic in criminal court. Existing authentication rules do not require independent verification of AI output at all: a prosecutor can currently take the stand, say they fed surveillance footage to a commercial AI tool to sharpen and reconstruct a blurry frame, and admit that output without any separate check that the tool did not invent a tattoo, a weapon, or a facial match that never existed. The claim that current practice already blocks this is false, as courts across the country are already grappling with unvetted AI-generated evidence introduced with no more foundation than a user’s say-so.
[P2.2] The claimed asymmetry cuts the other way. The prosecution, with its crime labs and massive budgets, already introduces most forensic and analytical evidence at trial. A presumptive inadmissibility rule places the verification burden squarely on the party offering the evidence—most often the state—before that convincing, polished AI output ever colors a jury’s perception. For indigent defendants, the rule does not permanently lock out their exculpatory translations or summaries; it triggers the existing duty to appoint necessary expert assistance for material defense evidence, rather than forcing overworked public defenders to rebut the state’s unvetted AI reconstructions out of their own overstretched budgets.
[P2.3] The breathalyzer comparison fails too: breathalyzers have disclosed, tested error rates and standardized calibration requirements. Current generative AI has no consistent error rate, no required audit trail for invented details, and no way for an operator to explain a hallucination unless they independently checked every output against the original source—exactly the human verification this rule requires. Flawed disciplines like bite mark comparison grew from unvetted testimony, not from verification requirements. A rubber-stamp expert can be cross-examined for cutting corners; no expert at all leaves no one accountable for hidden fabrications.

## Turn 4: CON Rebuttal 1

- model: qwen4-max-high
- raw_words: 293
- clipped_words: 293
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] His own example proves my point. A prosecutor who says "I fed the footage to a tool" and never produces the footage has an authentication problem, not an AI problem. Under his rule, that same prosecutor buys an expert's initials and walks the reconstruction in. The invented tattoo survives the signature; it dies on comparison with the source.
[C2.2] That comparison is what he keeps describing — "independently checked every output against the original source." Agreed. That is my criterion, and it needs no presumption and no second credential.
[C2.3] His rubber stamp gets cross-examined, he says. Cross of a skimming expert establishes that he skimmed; it does not tell the jury whether the tattoo exists. Bite marks were sold to juries by credentialed experts, confirmed by other credentialed experts. Independence did not save those defendants.
[C2.4] On asymmetry, he offers appointed expert assistance: discretionary, gated on a necessity showing, fee-capped, delayed, frequently denied. No judge can appoint a fluent speaker of a dialect with a few thousand living speakers. And "independent" disqualifies the person best placed to verify — the translator who did the work. The rule demands a second human who often does not exist, then excludes the defendant's evidence because he cannot be found.
[C2.5] The state's cure is a purchase order; the defendant's is a hope. Excluding the state's proof costs a prosecution; excluding the defense's proof costs an innocent man his freedom.
[C2.6] His breathalyzer distinction supports exhibit-by-exhibit reliability testing, which courts already do — not blanket presumption. Human translation of a rare dialect has no published error rate either; his standard would exclude it too.
[C2.7] He wants sources checked. So do I. He also wants evidence excluded whenever a credential is unaffordable or nonexistent. That is the part that convicts the innocent.

## Turn 5: PRO Pressure Questions

- model: seed-2.1-pro
- raw_words: 62
- clipped_words: 62
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If existing authentication rules already sufficiently block undetectable AI hallucinations, why are courts already admitting AI-generated reconstructions and translations with no line-by-line check against original source material?
[P3.2] Q2: If independent human verification is as meaningless as you claim, who do juries cross-examine when an operator who never independently checked the output cannot explain a hidden AI hallucination no layperson can spot?

## Turn 6: CON Pressure Questions

- model: qwen4-max-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: When no independent expert in that dialect exists anywhere — not unaffordable, nonexistent — is the defendant's exculpatory translation admissible under your rule, yes or no?
[C3.2] Q2: Your rule is satisfied by an expert who initials the reconstruction without ever demanding the original footage. What does that signature exclude that simply requiring the source would not? Name one invented tattoo your presumption stops that comparison with the footage does not.

## Turn 7: PRO Rebuttal 2

- model: seed-2.1-pro
- raw_words: 292
- clipped_words: 292
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Yes. Where no certified expert exists for a rare dialect, the rule does not permanently bar the defendant’s exculpatory translation. It does not demand a credentialed specialist; it requires a competent, unbiased human with fluency to compare the AI output to the original recording, swear to its accuracy, and face cross-examination about discrepancies. It also triggers existing duties to help indigent defendants secure that verification for material exculpatory evidence, rather than forcing them to meet the state’s unvetted proof empty-handed.
[P4.2] That is a lower bar, not a higher one, for an indigent defendant with access to a native speaker in his community than it is for the state with its six-figure forensics contracts. Critically, the same standard applies equally to prosecution evidence, which makes up the overwhelming majority of AI-generated forensic content currently admitted without any source check.
[P4.3] A2: It does not. A lazy expert who initials output without reviewing original source material does not satisfy the rule, because independent verification by definition requires line-by-line comparison against the underlying record. The presumption forces that check to happen before the jury ever sees a polished, convincing AI reconstruction, rather than relying on after-the-fact cross-examination to undo the damage of an invented weapon, tattoo, or inculpating phrase lay observers cannot distinguish from real evidence. My opponent claims access to original source material alone solves this problem, but that ignores that AI often fills gaps with plausible, seamless fabrications that leave no obvious marker for a judge or juror to flag mid-trial.
[P4.4] This guardrail does not tilt the playing field against defendants—it corrects the existing tilt, where the state can introduce unvetted AI evidence for free while defendants scramble to debunk convincing hallucinations after they have already irreparably colored the jury’s perception of guilt.

## Turn 8: CON Rebuttal 2

- model: qwen4-max-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Because a judge accepted "I ran it through a tool" as a foundation. That is a failure to demand the source, and the cure is demanding the source — which he now says his rule requires. His evidence of courts admitting unchecked output is evidence for my remedy, not his presumption. And a judge who accepts "I ran it through a tool" will accept "an expert verified it."
[C4.2] A2: The operator, on the record. "Did you compare this frame to the original footage?" "No." That is the most damaging cross-examination in the case, and it is available today. What his rule adds is a second witness who says "yes, I compared" — and juries cannot tell whether he did or merely said so.
[C4.3] His check on the rubber stamp is the rubber stamp's own assurance.
[C4.4] Now the collapse. He answered my second question "It does not." He concedes his presumption stops no invented tattoo that comparison with the footage does not stop. And he has rewritten "independent human expert" into "a competent, unbiased human with fluency" who swears and faces cross.
[C4.5] That is a translator on the stand. That is existing authentication. Strip away the label and his motion is my position with a presumption attached — and the presumption does no work except when the competent human cannot be found.
[C4.6] That residue is the whole dispute. My condition is that the record exist; his condition is that a person exist. Footage either exists or doesn't. A fluent, willing, unbiased verifier may simply not exist — and then his rule excludes the defendant's proof of innocence, while the state, with its contracts, never faces that problem.
[C4.7] He calls that correcting the tilt. It is the tilt, written into the rule.

## Turn 9: PRO Closing

- model: seed-2.1-pro
- raw_words: 185
- clipped_words: 185
- claim_ids: [P5.1], [P5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The entire dispute collapses to one unshakable truth about criminal trials: prejudice from convincing, undetectable AI hallucination cannot be cured after the jury sees it. My opponent says demanding original source material and cross-examining the operator mid-trial is enough, but that treats AI-generated evidence like any other flawed exhibit, ignoring that generative AI leaves no obvious red flags when it invents details. It fills blurry surveillance gaps with a tattoo that never existed, shifts a translated phrase from self-defense to premeditation, stitches missing transcript lines into perfectly coherent, authoritative text indistinguishable from a verified record.
[P5.2] Cross-examination after admission cannot unring that bell. Jurors do not shed vivid, plausible inculpatory details because a lawyer later points out a flaw no lay observer could flag on first view. The presumption places the required line-by-line check exactly where due process demands it: before that polished, false detail ever reaches the jury, on whichever party offers the evidence. The rare edge case where a competent verifier is hard to locate is trivial next to the predictable, large-scale injustice of letting unvetted AI fabrications tilt verdicts before anyone catches them.

## Turn 10: CON Closing

- model: qwen4-max-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] He concedes his presumption stops no invented tattoo that demanding the footage does not stop. His own answer: "It does not." Nothing in his closing takes it back. Everything he wants — the line-by-line check, before the jury sees anything — I want too, and courts can order it today by refusing to admit an exhibit whose source is never produced.
[C5.2] Timing is not the dispute; he can have his pretrial check without a presumption. So ask what the presumption adds beyond that. One thing: a veto that operates only when a second, independent, fluent, unbiased human cannot be found. He calls that a trivial edge case.
[C5.3] It is not trivial to the man whose only witness to his own words is a recording in a dialect nobody in the courthouse speaks. And notice his answer to undetectability: if jurors cannot spot a fabricated tattoo, they cannot spot a fabricated assurance that someone checked. His safeguard is exactly as invisible as the danger. When the rule's only unique effect is silencing the defense's proof of innocence, while the state buys compliance, the presumption is not a guardrail.
[C5.4] It is the tilt.
