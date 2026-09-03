# Debate prop_0621__glm-5-2__hy4-preview-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: glm-5-2
- model_con: hy4-preview-high
- side_swap: False

## Turn 1: PRO Opening

- model: glm-5-2
- raw_words: 312
- clipped_words: 312
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a courtroom uses an algorithm to help decide whether someone goes free or stays locked up, the defendant cannot cross-examine that algorithm. They cannot question the training data, test the source code, or learn how often the tool errs. Prosecutors who rely on these tools bring into the courtroom a witness the defense cannot see or challenge. That is a due process problem at its core.
[P1.2] The proposition asks for three things: source code, training data summaries, and error rates. These are not technical luxuries. They are the minimum needed to evaluate whether a tool works, whether it discriminates, and whether its output is reliable enough to decide someone's liberty.
[P1.3] Consider what happens without disclosure. A risk tool recommends detention. The defense asks: What data trained this model? Can't tell you.
[P1.4] How often does it misclassify? Can't tell you. Can we review the code? Trade secret.
[P1.5] The defendant sits in jail based on a number nobody can explain or challenge. An error rate of even five percent means one in twenty defendants is wrongly categorized—and without that number, no one can identify which ones.
[P1.6] This is not speculative. Algorithmic risk tools already influence charging, bail, and sentencing. When they encode bias—because historical arrest data overrepresents certain communities—that bias stays invisible without disclosure. A prosecutor cannot simply say we trust the software.
[P1.7] If the state uses a tool to restrict someone's freedom, the state must show that the tool deserves that power.
[P1.8] The counterargument will invoke trade secrets and operational burdens. But trade secret law already accommodates protective orders and sealed filings—mechanisms that shield proprietary information while preserving a defendant's ability to challenge evidence. The burden of disclosure falls on the party using the tool, and that is exactly where it belongs.
[P1.9] When the government uses algorithms in criminal justice, transparency is not optional. Liberty should never hinge on a black box.

## Turn 2: CON Opening

- model: hy4-preview-high
- raw_words: 310
- clipped_words: 310
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.5]
- missing_claim_id_refs: (none)

[C1.1] Transparency is not the same as dumping a codebase into a case file. Requiring source code, training-data summaries, and error rates for any algorithmic risk tool in charging, bail, or sentencing sounds like due process. In practice it is a disproportionate, self-defeating mandate that makes liberty less secure.
[C1.2] These tools are advisory inputs, not decision-makers. When a risk score influences a prosecutor or judge, the state should disclose that use and the output. The defense can argue the score was misapplied, unreliable, or outweighed—real adversarial testing. Source code adds almost nothing; no lawyer, judge, or juror can audit it usefully.
[C1.3] It only helps defendants game future assessments and strips vendors of trade-secret protection that protective orders cannot fully preserve. Training-data summaries are no softer: for models trained on criminal-history records, summaries risk exposing sensitive records and proprietary methods while telling the court little it can use.
[C1.4] Worse, the mandate is overbroad. “Any algorithmic risk tool,” even a simple validated checklist, triggers full disclosure. Vendors will not accept that exposure. They will withdraw or refuse audits, and jurisdictions will revert to unstructured human judgment—the discretion that produces the racial disparities the motion invokes. A human bail decision is the real black box: no published error rate, no training data, no inspectable code.
[C1.5] This motion targets the one input we can in principle validate, while leaving the more opaque driver untouched. The result is not transparency but regression.
[C1.6] Finally, “error rates” are not self-interpreting. A 5% figure means nothing without false-positive versus false-negative rates, thresholds, and the human baseline. The claim that a 5% rate “means one in twenty defendants is wrongly categorized” [P1.5] ignores that human detention decisions are wrong more often and more biasedly. The remedy is independent validation, audit, and cross-examination of the human decision-maker—not compelled disclosure that makes vendors vanish and leaves judges with nothing but gut instinct.

## Turn 3: PRO Rebuttal 1

- model: glm-5-2
- raw_words: 303
- clipped_words: 303
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The opponent's core move reframes disclosure as a burden that destroys useful tools. This gets the relationship backwards. A tool that cannot survive scrutiny doesn't become unreliable when examined—it was never reliable enough to put someone in jail.
[P2.2] Calling risk tools "advisory" [C1.2] doesn't dissolve the due process problem. When a score recommends detention and a judge relies on it, the defendant's liberty turns on a process they cannot examine. "The human signed off" is not adversarial testing of the input that shaped the decision. And the claim that "no lawyer, judge, or juror can audit it usefully" ignores that defense teams retain expert witnesses.
[P2.3] We don't exclude DNA evidence because most lawyers can't run a gel.
[P2.4] On trade secrets [C1.3]: every disclosure regime in litigation—discovery, Brady, expert disclosure—balances proprietary interests against a defendant's right to challenge evidence. Trade secrecy is a commercial interest. It does not outrank the right to examine what restricts your freedom.
[P2.5] The vendor-withdrawal argument [C1.4] is a threat, not a reason. If a vendor refuses to let its tool be examined in court, that tells us the tool shouldn't be trusted with liberty. The market can adapt—open-source alternatives, public audits, simpler transparent models. The opponent asks us to accept unaccountable algorithms because accountable ones might be scarce.
[P2.6] That concedes the principle.
[P2.7] The claim that error rates "mean nothing" without context [C1.6] is exactly why the motion demands all three: source code, training data summaries, and error rates together. The argument against partial disclosure is an argument for full disclosure.
[P2.8] Finally, the human-judgment fallback is a false alternative. The motion doesn't ban tools; it demands they be examinable. A judge's instinct is flawed but can be questioned on the record. An unexaminable algorithm combines the authority of data with the opacity of instinct—and that is worse than either alone.

## Turn 4: CON Rebuttal 1

- model: hy4-preview-high
- raw_words: 317
- clipped_words: 317
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.5], [P2.6], [P2.3], [P2.7], [C1.6], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] The claim that a tool which cannot survive scrutiny was never reliable [P2.1] mistakes validation for exposure. A risk instrument can be accurate in a jurisdiction because it was prospectively validated and audited, yet still destroyed as a product if the state must hand its source code and training-data summaries to every defendant. That is not a tool failing a reliability test; it is a workable tool regulated out of existence. Predicting vendor withdrawal [P2.5] is therefore not a threat that "concedes the principle" [P2.6]; it identifies the motion's practical effect.
[C2.2] If accountability means in-case code disclosure, we get fewer audited tools and more unaided human judgment.
[C2.3] Nor do retained experts solve this. Most indigent defendants cannot fund a specialized AI expert, so a source-code mandate creates two tiers of justice: wealthy defendants get a code audit; everyone else gets nothing. The DNA analogy [P2.3] proves our point: DNA is admissible only after the state discloses validated methodology, error rates, and permits independent testing—not the lab's instrument firmware or software repository in every case. Certification, known error context, and testable use are the right model.
[C2.4] The "all three together" reply [P2.7] is mistaken about what supplies context. An error rate becomes meaningful through false-positive/false-negative rates, thresholds, and the human baseline—my point in [C1.6]. Source code and data summaries do not provide that; a jurisdiction-specific validation study does. Independent auditors can publish that context without forcing vendors to surrender the model.
[C2.5] Protective orders [P2.4] limit public release, not competitive destruction or re-identification risk in criminal-history summaries.
[C2.6] So the clash is not transparency versus secrecy, but compelled production versus accountable design. Disclose that a tool was used and what it output; require independent validation and audit-reported error context; let the defense cross-examine the human who relied on it. Liberty is safest when the score is auditable and the decision-maker answerable—not when the algorithm is scared out of the courtroom.

## Turn 5: PRO Pressure Questions

- model: glm-5-2
- raw_words: 90
- clipped_words: 90
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your alternative is "independent validation and audit-reported error context" [C2.4]. But if an auditor needs source code and training data to validate the tool, why should the defense get only the auditor's summary rather than the materials that let them challenge the audit itself?
[P3.2] Q2: You concede DNA requires disclosed methodology, error rates, and independent testing [C2.3]. The proposition asks for the same three things for risk tools. What specifically makes source code, data summaries, and error rates appropriate for forensic DNA but excessive for an algorithm deciding bail?

## Turn 6: CON Pressure Questions

- model: hy4-preview-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P3.2], [C2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: The motion covers "any algorithmic risk tool." If a validated bail checklist or spreadsheet with fixed weights qualifies, what exactly is its "source code" and "training-data summary," and how do you avoid forcing disclosure for every actuarial table used in justice?
[C3.2] Q2: You equate risk tools with DNA [P3.2], but DNA has no machine-learned training data and our model compels validation and error context, not firmware [C2.3]. What "training-data summary" would DNA produce, and what rule compels source code in every case?

## Turn 7: PRO Rebuttal 2

- model: glm-5-2
- raw_words: 275
- clipped_words: 275
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: For a fixed-weight checklist, source code is the formula in the cells, the training-data summary is the population used to derive the weights, and error rates are the validation results. Disclosure there is trivial because everything is already transparent. The burden only becomes meaningful for proprietary models whose internals are hidden. The motion's breadth isn't a flaw — simple tools comply effortlessly, and complex tools must either comply or explain why they can't survive examination.
[P4.2] A2: DNA isn't a learned model, so it has no training data — but the principle is identical. The state must disclose how the tool works (methodology ≈ source code), what population it was validated on (≈ training-data summary), and how often it errs. DNA shows exactly why this matters: if a lab's protocols were secret, no one could challenge the result. The opponent's model "compels validation and error context" but not the underlying materials — which is the gap: the defense gets an auditor's conclusion without what the auditor relied on.
[P4.3] That gap is where this debate is decided. The opponent keeps describing a disclosure regime that stops one step short — at the auditor's summary rather than the materials that let the defense challenge it. Independent validation without source-code access produces an auditor's say-so. Error context without training-data summaries can't reveal demographic bias.
[P4.4] The defense doesn't need to trust the auditor; it needs to test the auditor. That requires exactly what the motion demands.
[P4.5] The opponent's alternative isn't lighter disclosure — it's transferred trust: from the vendor's black box to the auditor's black box. The whole point of adversarial process is that no one's word is final.

## Turn 8: CON Rebuttal 2

- model: hy4-preview-high
- raw_words: 321
- clipped_words: 321
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [C2.4], [P4.2], [P4.1], [C2.5], [C1.4]
- missing_claim_id_refs: (none)

[C4.1] A1: The defense is not stuck with a bare summary. Our model discloses the validated error context: false-positive and false-negative rates, thresholds, subgroup performance, and validation population [C2.4]. That is the audit’s factual basis, enough for a defense expert and cross-examination to test the auditor. An auditor may inspect code under confidentiality, but the defendant needs no source code to attack the audit, just as a DNA defendant re-tests the sample and cross-examines the analyst without obtaining sequencer firmware.
[C4.2] Q1 demands the wrong material: source code would destroy the product without making the audit testable.
[C4.3] A2: The DNA analogy fails. Forensic DNA has no machine-learned training data, and discovery compels methodology, validation studies, and error rates plus independent re-testing of the sample—not the manufacturer’s instrument source code. DNA methodology is a disclosable written protocol; the risk-tool analogue is a functional description and audit, which we already require. PRO calls methodology “≈ source code” [P4.2], but no rule compels sequencer code, and “training-data summary” has no DNA analogue.
[C4.4] Our model matches DNA: validation population, error context, independent review. The motion adds source code and training-data summaries; that extra step is excessive, not the error-rate disclosure we both support.
[C4.5] That distinction preserves CON’s victory. PRO concedes the real bite is on proprietary models: “The burden only becomes meaningful for proprietary models whose internals are hidden” [P4.1]. For those tools, disclosure means surrender or withdrawal; protective orders cannot undo that or re-identification risk [C2.5]. We revert to unaided human judgment—no error rates, deeper disparity, the real black box [C1.4].
[C4.6] Our alternative already makes auditors testable through disclosed validation, subgroup error rates, and cross-examining the auditor and the human who relied on the score [C2.4]. No two-tier justice. The motion is not transparency; it forces unexaminable code or no validated tool. Liberty is safest with accountable design: auditable tools, real error context, answerable humans—not a rule that scares the algorithm away and leaves instinct unreviewed.

## Turn 9: PRO Closing

- model: glm-5-2
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.1]
- missing_claim_id_refs: (none)

[P5.1] CON's entire case reduces to one move: trust the auditor. Give the defense error rates and validation summaries — but keep the source code and training data behind a wall only the auditor can see.
[P5.2] That is not lighter disclosure. It is transferred trust.
[P5.3] CON says the defense can "cross-examine the auditor" [C4.1]. But cross-examination without underlying materials is theater. You can ask whether the model is biased, but you cannot inspect the training data that would prove it. You can ask whether the code has a flaw, but you cannot see the code that would expose it.
[P5.4] The defense argues with conclusions it cannot test.
[P5.5] DNA discovery doesn't stop at the analyst's summary. It requires methodology, validation studies, and independent re-testing of the evidence. CON's model gives the defense the report but denies them the sample.
[P5.6] The state should not restrict liberty with a tool the defense cannot examine. The motion demands source code, training data summaries, and error rates because those are what make challenge real, not theatrical. Anything less is a black box with a stamp of approval — and a stamp of approval is not due process.

## Turn 10: CON Closing

- model: hy4-preview-high
- raw_words: 187
- clipped_words: 187
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.1], [C2.4], [C2.5], [C1.4]
- missing_claim_id_refs: (none)

[C5.1] The charge that we ask defendants to “trust the auditor” [P5.1] is backwards. The defense is not handed a bare conclusion; it receives the audit’s factual basis: false-positive and false-negative rates, thresholds, subgroup performance, and validation population [C2.4]. That is the material needed to test reliability. Source code and raw training summaries add no testing power; they are the instrument, not the sample.
[C5.2] In DNA terms, the defense re-tests the biological sample and cross-examines the analyst; it does not receive the sequencer’s firmware. The comparable “sample” is the disclosed score, its inputs, and validated error context.
[C5.3] So the real choice is not trust versus examination. It is examination of an audited tool versus no tool at all. PRO’s mandate is either redundant—for a transparent checklist, there is nothing to extract—or lethal: for proprietary models it forces surrender or withdrawal, and protective orders cannot restore the product or erase re-identification risk [C2.5]. That leaves judges with unaided instinct, the true black box [C1.4].
[C5.4] CON wins because it keeps the score auditable and the decision-maker answerable, rather than scaring the algorithm away and replacing reviewable data with unreviewable gut.
