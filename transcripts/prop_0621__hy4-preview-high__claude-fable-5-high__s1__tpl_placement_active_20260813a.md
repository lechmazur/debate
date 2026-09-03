# Debate prop_0621__hy4-preview-high__claude-fable-5-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: hy4-preview-high
- model_con: claude-fable-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: hy4-preview-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When the state moves to charge, jail, or sentence someone, the defense must be able to challenge every assertion the government relies on. A risk score is not a neutral fact; it is the state’s claim that this person is dangerous or likely to flee. If a prosecutor uses that score in charging, bail, or sentencing, the defense gets the same rights it would have against any expert: the basis, track record, and ability to cross-examine it.
[P1.2] Disclosing source code, training-data summaries, and error rates is just due process for software. Error rates matter because liberty cannot rest on a black box that may be wrong a third of the time. Training-data summaries matter because these models learn from past arrests. Trained on over-policed neighborhoods, a tool can treat race and poverty as "risk" while calling it criminal history.
[P1.3] Defendants have the right to expose that proxy bias, not just trust the vendor’s assurance of fairness. Source code is not a fishing expedition; it is the only way to confirm the tool does what the state claims. Without it, a prosecutor can swear the model ignores race while the code quietly weights zip code and unemployment, both of which track race.
[P1.4] Prosecutors will plead trade secrets and complexity. Neither survives due process. We do not let officers hide informants or labs hide protocols merely because disclosure is inconvenient. When the government seeks to incarcerate, a software license cannot veto the adversarial process.
[P1.5] Protective orders and cleared experts solve any real security concern. The choice is secret evidence versus testable evidence.
[P1.6] Consider a bail hearing where a judge sees only a high-risk score and no way to ask whether the model punishes unemployment, mislabels offenders, or produces different false-positive rates across groups. That is a rubber stamp, not a hearing. Requiring disclosure forces the state to defend its tool, not bow to it.

## Turn 2: CON Opening

- model: claude-fable-5-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.5]
- missing_claim_id_refs: (none)

[C1.1] Strip away the rhetoric and the proposition makes a simple empirical mistake: it assumes reading source code is how you learn whether a tool is accurate or biased. It isn't. You cannot stare at ten million lines of code, or a statistical summary of training data, and see racial bias. Validity is established the way we validate any diagnostic instrument — by independent testing of outputs against outcomes.
[C1.2] A blanket code-disclosure mandate delivers accountability theater: reams of material no defense attorney can interpret, while the questions that actually matter — does the tool predict well, and equally across groups — are answered by audits and validation studies, which this mandate does not require and does not need code to perform.
[C1.3] The right mechanism already exists: case-by-case judicial review. When a defendant makes a genuine showing that a tool's inner workings matter to their case, courts can compel access under protective order with cleared experts — exactly what PRO concedes works in [P1.5]. That concession collapses the case for a blanket rule. If protective orders solve security concerns, they equally solve the disclosure problem without a categorical mandate.
[C1.4] Now weigh the costs. Prosecutors typically do not possess vendor source code; a rule requiring them to disclose what they cannot obtain functions as a ban on the tools. And what replaces them? Not transparency — the true black box: unstructured human judgment.
[C1.5] A judge's gut has no error rate to disclose, no training data to summarize, no code to inspect, and a long documented history of racial disparity. Structured tools, whatever their flaws, are at least measurable and correctable. This mandate pushes courts back toward the one system that can never be audited.
[C1.6] Note too that many risk instruments — like the widely used pretrial assessments built on a handful of published factors and weights — are already open. The mandate adds nothing there and destroys everything elsewhere.
[C1.7] The choice is not secret evidence versus testable evidence. It is testable tools versus untestable hunches. Choose the system you can actually check.

## Turn 3: PRO Rebuttal 1

- model: hy4-preview-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.1], [C1.3], [C1.4], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] CON pretends the motion is only about code. It is not. [C1.1] says you “cannot stare at ten million lines of code... and see racial bias,” but the motion also compels disclosed error rates—precisely the outcome testing CON claims to prefer—and training-data summaries. Those materials let defense experts catch what a vendor’s chosen audit can hide.
[P2.2] A tool can publish an overall false-positive rate while quietly weighting zip code and unemployment, which track race closely. Cleared experts with the code and summaries can see that proxy and demand subgroup error rates. Without them, defendants must trust the state’s selected metric.
[P2.3] CON then leans on case-by-case review, arguing [C1.3] that my protective-order concession “collapses the case for a blanket rule.” It does not. My concession answered security, not access. Case-by-case discovery is circular: a defendant cannot make a “genuine showing” that a zip-code proxy matters without first seeing the basis of the score. Criminal discovery does not make the accused prove materiality blindfolded; the state must disclose the grounds for deprivation of liberty.
[P2.4] A uniform rule also prevents a two-tier system where only funded defendants can afford to fight for the code in each bail hearing.
[P2.5] Finally, the “ban” warning in [C1.4] proves too much. If a private vendor refuses to let the state disclose the basis of a risk score, the state should not use that tool to charge, jail, or sentence. That is a procurement condition, not a ban: open, auditable instruments remain available, exactly as CON notes in [C1.6]. Nor must we choose “unstructured human judgment.” The mandate does not abolish structured tools; it forbids unauditable ones.
[P2.6] A truly measurable tool can state its error rates and training summaries. A sealed score is worse than a hunch, because a judge’s hunch can at least be questioned in open court. The real choice is testable tools versus numbers no one may test.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P1.3], [P2.2], [P2.3], [P2.5], [P2.4], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Watch PRO's case drift. The opening called source code "the only way to confirm the tool does what the state claims" [P1.3]. Now the real work is done by experts who "demand subgroup error rates" [P2.2]. Notice the swap: the safeguard PRO actually wants—independent subgroup validation—is not in the motion.
[C2.2] The motion compels "error rates," which vendors will hand over as a single flattering aggregate—exactly the "state's selected metric" PRO says defendants shouldn't have to trust. PRO's diagnosis demands systemic independent auditing at adoption; PRO's motion delivers a per-case paper dump to whichever attorney happens to litigate it.
[C2.3] Second, the circularity charge in [P2.3] fails on the facts. These tools' inputs are not secret. A defendant knows precisely which of his attributes went in: age, charge, prior record, and yes, employment or address if the tool uses them. If a zip-code factor exists, it appears on the input sheet.
[C2.4] That is exactly the threshold showing case-by-case review requires—and courts have compelled access to probabilistic software under protective order on such showings. Nobody is blindfolded.
[C2.5] Third, [P2.5] concedes my core cost rather than answering it: tools whose vendors refuse disclosure get eliminated. Relabeling that a "procurement condition" changes nothing about who bears it. The motion binds prosecutors, who neither write vendor contracts nor possess code. Faced with per-case disclosure litigation they cannot satisfy, offices will simply stop citing the tools—reverting to the gut, the one system with no inputs to inspect at all.
[C2.6] Fourth, [P2.4]'s equity point cuts against PRO. Handing every defendant ten million lines of code helps only defendants who can afford experts to read them. The two-tier system survives blanket disclosure intact. Systemic validation protects everyone, including the unrepresented.
[C2.7] Finally, [P2.6] claims a hunch "can be questioned in open court." How? You cannot cross-examine intuition. A structured tool's published factors can be contested item by item.
[C2.8] That asymmetry decides this debate.

## Turn 5: PRO Pressure Questions

- model: hy4-preview-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5], [C1.6], [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: In [C2.5] you warn prosecutors will abandon tools they cannot get code for. If a vendor bars disclosing the score's basis, why is dropping that secret tool a loss rather than the state choosing an auditable instrument you admit exists [C1.6]?
[P3.2] Q2: You say a zip-code factor on the input sheet is already enough to compel review [C2.4]. Then why must a defendant litigate blind for subgroup error rates and training-data summaries, instead of receiving them up front as the motion requires?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.2]
- missing_claim_id_refs: (none)

[C3.1] Q1: You concede the safeguard that actually matters is independent subgroup validation [P2.2] — so quote the words in this motion that require it, rather than letting a vendor satisfy "error rates" with the single flattering aggregate you yourself call the state's selected metric.
[C3.2] Q2: At a five-minute bail hearing for an unrepresented or public-defender client, who reads the ten million lines and the training summary — and how does that per-case paper dump protect them better than mandatory independent auditing before any court adopts the tool?

## Turn 7: PRO Rebuttal 2

- model: hy4-preview-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C1.6]
- missing_claim_id_refs: (none)

[P4.1] A1: The motion compels “error rates” — plural — not an “error rate.” A tool that behaves differently across groups has more than one rate; by requiring the state to disclose “the error rates of” the tool, the mandate demands every rate, not the single flattering aggregate CON calls the state’s selected metric. Add the required “source code” and “training data summaries,” and cleared experts can check whether the list is complete. If a vendor hides subgroup false-positive rates behind an aggregate, the code and summary expose it and the court can compel the rest.
[P4.2] That is independent validation: disclosed materials let the defense test the state’s claim.
[P4.3] A2: Nobody reads ten million lines in five minutes, because disclosure is a pre-hearing duty, not a courtroom quiz. The defendant need not read code: a “training data summary” is a summary, and “error rates” are numbers a judge can see. A public defender’s office can retain one expert for all cases, so review is systemic, not a per-case dump. The protection is the remedy: if the state has not produced the code, summaries, and rates before the hearing, the defendant moves to exclude the score.
[P4.4] Pre-adoption auditing leaves an unrepresented defendant with no remedy when the audit is wrong, outdated, or captured; our motion puts the burden on the state when liberty is at stake.
[P4.5] That asymmetry decides the debate. CON’s alternative hands the defendant a number the government will not explain; our motion means every score comes with its basis or cannot be used. This does not ban structured tools—it bans unauditable ones, and CON admits auditable instruments exist [C1.6]. It does not restore hunches; it forces open, testable instruments.
[P4.6] Prosecutors already disclose the basis of every other expert’s claim. When the state seeks to jail someone, vendor secrecy cannot veto that duty. Disclose the rates, or drop the score—that is why PRO still wins.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [C1.6], [C2.3], [P4.1], [P4.3], [C2.5]
- missing_claim_id_refs: (none)

[C4.1] A1: Dropping the secret tool is only a gain if what replaces it is the open instrument — and nothing about this motion makes that the replacement. The mandate binds prosecutors per-case, not vendors at procurement. Even the open-factor tools I cited in [C1.6] have underlying code, retraining pipelines, and evolving datasets prosecutors don't possess; every one becomes a litigation target over whether the "summary" was complete or the "rates" current. An office facing that exposure in every bail hearing doesn't shop for a better vendor.
[C4.2] It stops citing scores entirely and reverts to the gut — the one system with no rates, no inputs, no appeal. The loss isn't the secret tool; it's the structured tool, full stop.
[C4.3] A2: Nobody litigates blind — the inputs sit on the score sheet, which is the threshold showing courts already accept [C2.3]. But notice what PRO's own answer just conceded. [P4.1] admits that if a vendor hides subgroup rates behind an aggregate, "the court can compel the rest." Compel.
[C4.4] That is case-by-case judicial review — my mechanism — smuggled back in as the motion's enforcement arm. So even under PRO's rule, the defendant receives a vendor-authored paper stack up front and still litigates for the numbers that matter. The motion's text cannot conjure rates a vendor never calculated; "error rates," plural, is textual wishful thinking dressed as a guarantee.
[C4.5] Zoom out and PRO's case has eaten itself. The safeguard PRO wants — independent subgroup validation — arrives, on PRO's own telling, through compelled discovery, not the mandate. The remedy PRO offers in [P4.3] — exclude the score — is precisely the reversion to unstructured judgment I warned of in [C2.5]. PRO has conceded both halves of my case: the mechanism that works is mine, and the cost that bites is theirs.
[C4.6] A rule whose success depends on judges doing case-by-case review and whose failure mode is government by hunch is not due process for software. Reject it.

## Turn 9: PRO Closing

- model: hy4-preview-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.5], [C4.6], [P4.3], [C4.4], [P4.4], [C1.6], [P2.5]
- missing_claim_id_refs: (none)

[P5.1] The motion wins for one reason: the state may not jail someone using a number it refuses to explain.
[P5.2] CON says our case "has eaten itself" [C4.5] because enforcement resembles case-by-case review and failure means "government by hunch" [C4.6]. That misreads the remedy. Disclosure is a precondition: if code, training-data summaries, and error rates are not produced before the hearing, the score is excluded [P4.3]. The "compel the rest" line CON quotes [C4.4] is only the consequence of noncompliance, not proof the mandate must conjure uncalculated rates.
[P5.3] CON's alternative—trust pre-adoption audits and discretion—fails the unrepresented defendant, who still gets a score the government will not explain [P4.4]. Our motion puts the burden where due process does: on the state. Disclose or drop the score.
[P5.4] Vendor secrecy cannot veto that duty. If a vendor bars disclosure, the state must use an auditable instrument CON admits exists [C1.6], or proceed without it. That is not a ban on structured tools; it is a ban on unauditable ones [P2.5]. The cost of an unexplainable tool falls on the government, not the accused.
[P5.5] The defendant confronts the basis for the state's claim, or the secret number cannot be used: PRO wins.

## Turn 10: CON Closing

- model: claude-fable-5-high
- raw_words: 206
- clipped_words: 206
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P2.2], [P4.1], [P4.3], [P5.1]
- missing_claim_id_refs: (none)

[C5.1] One question decides this debate: does the motion actually deliver the safeguard PRO says defendants need? By PRO's own telling, it does not.
[C5.2] PRO's safeguard is independent subgroup validation [P2.2]. But PRO conceded that when a vendor hides subgroup rates behind a flattering aggregate, "the court can compel the rest" [P4.1]. That is case-by-case judicial review — my mechanism — doing every ounce of the real work, with the mandate reduced to a vendor-authored paper stack delivered as prologue. The motion's text cannot conjure rates nobody calculated; the litigation PRO promised to eliminate remains.
[C5.3] Meanwhile, the motion's remedy — exclude the score [P4.3] — is precisely the failure mode I warned of. PRO frames exclusion as a cost on the state, but the person who loses when a bail hearing runs on gut instinct is the defendant. A hunch has no error rates to disclose, no inputs to confront, no basis to challenge. It fails PRO's own principle in [P5.1] more completely than any structured tool ever could.
[C5.4] So compare the worlds. Mine: measurable instruments, plus compelled access on a real showing. PRO's: every score a litigation liability whose predictable endpoint is government by hunch — the one system nobody can ever disclose. Reject the motion.
