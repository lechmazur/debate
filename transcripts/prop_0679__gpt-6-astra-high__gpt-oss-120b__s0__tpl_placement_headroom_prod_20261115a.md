# Debate prop_0679__gpt-6-astra-high__gpt-oss-120b__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: gpt-6-astra-high
- model_con: gpt-oss-120b
- side_swap: False

## Turn 1: PRO Opening

- model: gpt-6-astra-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Criminal trials should not convert machine-generated plausibility into proof without an accountable person checking the result. That is the core of this proposition: AI-generated summaries, translations, and reconstructions should be presumptively excluded unless a qualified human independently verifies their evidentiary content.
[P1.2] These outputs do more than display existing evidence. They select, interpret, and sometimes supply details absent from the source. A summary can omit a witness’s uncertainty. A translation can turn an ambiguous expression into an apparent confession.
[P1.3] A reconstruction can make one speculative sequence look like recorded reality. The danger is not merely error; it is error presented with fluency and apparent completeness that obscure where inference replaced observation.
[P1.4] Independent verification creates a concrete safeguard. An expert must compare the output with its underlying material, examine consequential ambiguities and assumptions, and explain what the evidence actually supports. That is not a rubber stamp or a demand for infallibility. It gives the court someone who can defend the translation, justify the reconstruction, or identify what the summary left out.
[P1.5] CON may say ordinary cross-examination and judicial discretion are enough. But cross-examining the officer who uploaded a file cannot establish whether its automated translation is accurate. Nor does a model’s generally strong performance verify this defendant’s words. Waiting for the opposing party to uncover hidden errors shifts the burden from the party offering evidence to the party endangered by it.
[P1.6] This rule preserves useful technology while denying it unearned authority. AI can still help investigators locate material and lawyers prepare cases. Verified outputs remain eligible for admission. Verification costs time and money, but admitting an unverified shortcut does not eliminate that cost; it transfers it to adversaries trying to expose mistakes.
[P1.7] When liberty is at stake, reliability must precede persuasion.

## Turn 2: CON Opening

- model: gpt-oss-120b
- raw_words: 299
- clipped_words: 299
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] AI‑generated summaries, translations and reconstructions are not a new, untested class of evidence; they are simply another tool for processing raw material that courts already admit when the underlying source is authentic. The proposition’s presumptive exclusion ignores the fact that the same reliability concerns apply to any forensic analyst, a handwriting expert, or a digital‑forensic examiner, none of which must be independently re‑verified before every piece of testimony is admitted. Existing rules—Daubert, Frye, and the opportunity for cross‑examination—already give judges the discretion to weed out unreliable output.
[C1.2] Adding a blanket presumption of inadmissibility merely duplicates those safeguards and does so in a way that tips the balance toward procedural paralysis.
[C1.3] Requiring a separate human expert for every AI‑produced artifact creates a prohibitive cost burden. In a murder trial, a forensic linguist might spend weeks re‑checking a machine translation that a well‑trained model can produce in seconds with error rates comparable to a seasoned translator. The delay jeopardises the right to a speedy trial and forces defense resources into a costly verification race that the prosecution never has to meet. Moreover, the presumption assumes that human verification is inherently more trustworthy, yet numerous studies show that expert testimony can be biased, inconsistent, or simply wrong.
[C1.4] AI, when trained on large, representative corpora, can deliver more consistent outputs than a single human, especially in languages with scarce qualified translators.
[C1.5] Finally, the rule undermines the very purpose of admissibility: to allow the trier of fact to hear all relevant, probative material. Excluding AI‑generated evidence unless a second party voluntarily steps forward creates a de facto advantage for the side that can afford the extra expert, skewing the playing field. The proper approach is to treat AI outputs like any other evidence—subject to relevance, authenticity, and reliability tests—not to bar them a priori.

## Turn 3: PRO Rebuttal 1

- model: gpt-6-astra-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] An authentic recording does not authenticate its translation. That is the central mistake in calling AI “simply another tool.” A genuine interview can be summarized inaccurately; a genuine crime-scene photograph can support a reconstruction that invents a movement. Rules establishing where the source came from do not establish whether the generated claim is true.
[P2.2] The comparison with human forensic testimony also misfires. A human analyst is already a person who must explain and defend the analysis. We are not demanding that every human opinion receive a second opinion. We require the first qualified, accountable witness who has independently checked the AI’s evidentiary assertions.
[P2.3] Judicial reliability tests need a foundation: someone who can explain why a disputed idiom became a confession, not merely report that the software usually works.
[P2.4] Human fallibility is therefore no answer. Verification need not make humans universally superior to models; it must connect this output to this source through review that can be challenged. CON’s claims about comparable error rates and consistent performance do not establish accuracy in the contested passage. Consistently choosing the wrong meaning is still consistently wrong.
[P2.5] On cost, CON says the prosecution “never has to meet” the verification burden. The rule applies to whoever offers the evidence, including prosecutors. Without it, prosecutors can generate persuasive material cheaply while defendants must fund the expertise needed to discover its defects. Verification places that burden before admission, rather than after jurors have absorbed the claim.
[P2.6] Defense access matters, but admitting unchecked transformations is not an equalizer: it gives well-resourced parties more opportunities to flood the record. Preserve the underlying evidence, use AI to find it, and admit verified outputs. Criminal admissibility is not a contest to display everything relevant; it is a safeguard against treating an untested interpretation as proof.

## Turn 4: CON Rebuttal 1

- model: gpt-oss-120b
- raw_words: 286
- clipped_words: 286
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO correctly points out that a raw recording does not itself verify a translation, but the same issue arises with any human‑produced transcription. Courts already admit such translations after the witness who performed them is cross‑examined; the rule does not require a second, independent expert. By demanding a separate verification step uniquely for AI, PRO creates a double standard that privileges human testimony without evidentiary justification. The presumption of inadmissibility therefore adds an unnecessary procedural hurdle.
[C2.2] The cost argument is overstated. Verification can be performed by the same qualified analyst who generated the AI output, using the original data and the model’s audit logs. Modern platforms provide traceability—parameter settings, training‑data provenance, confidence scores—that let a single expert assess reliability in minutes. Requiring an additional specialist for every output would double expenses, while the current system already forces parties to fund experts to explain human‑generated translations or reconstructions.
[C2.3] PRO’s claim that prosecutors would evade this burden ignores the rule’s language: “unless independently verified by a human expert,” which applies to whoever offers the evidence.
[C2.4] Moreover, AI can be more reliable than scarce human translators in low‑resource languages, reducing the risk of misinterpretation PRO fears. A human sanity‑check of the model’s result satisfies the gate‑keeping function without sacrificing efficiency.
[C2.5] Finally, the presumption undermines the purpose of evidentiary rules: to allow the trier of fact to consider reliable information. A blanket exclusion forces courts to discard probative material simply because it was produced by a machine, even when the underlying data are authentic and the output is demonstrably accurate. The proper balance is a case‑by‑case reliability assessment, not a sweeping inadmissibility rule. Such a nuanced approach respects both the defendant’s rights and the court’s need for timely, trustworthy evidence.

## Turn 5: PRO Pressure Questions

- model: gpt-6-astra-high
- raw_words: 67
- clipped_words: 67
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say a qualified analyst can check the output against original data “in minutes”; if that independently verifies its content, what costly extra step does the motion require?
[P3.2] Q2: If your proposed “sanity-check” does not verify content, how do audit logs and confidence scores establish that a disputed translation is accurate, rather than leave the defendant to pay an expert to uncover its errors after admission?

## Turn 6: CON Pressure Questions

- model: gpt-oss-120b
- raw_words: 81
- clipped_words: 81
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If the prosecution can present an AI‑generated translation without a prior human audit, how can the trial satisfy the constitutional guarantee of due process when the defendant cannot challenge a black‑box output before the jury hears it?
[C3.2] Q2: Given that audit logs and confidence scores are internal model data, why should the court accept them as a substitute for a thorough expert review rather than requiring a qualified linguist to confirm the translation's meaning, especially when the stakes are life‑and‑death?

## Turn 7: PRO Rebuttal 2

- model: gpt-6-astra-high
- raw_words: 282
- clipped_words: 282
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: On your stated facts, admission without a meaningful opportunity to challenge the translation’s accuracy undermines due process. Cross-examining the person who clicked “translate” cannot test a linguistic judgment that person cannot explain. Your question identifies the reason for our presumption: establish an accountable foundation before jurors hear the generated claim.
[P4.2] A2: They should not accept logs and confidence scores as substitutes for substantive review. Those records may help explain how an output was produced; they do not independently confirm what a speaker meant. A qualified linguist must check the translation against the original, including consequential ambiguity. Your proposed safeguard is the proposition’s safeguard.
[P4.3] The remaining dispute is therefore not whether human review matters, but whether it must actually verify evidentiary content. Earlier, you said the same qualified analyst could perform verification “in minutes.” If that analyst genuinely checks the source and independently supports the output, the condition is satisfied. Independence concerns the check, not an obligatory second hire. If the analyst merely accepts the model’s confidence, your own second question explains why that falls short.
[P4.4] This also resolves your objection to excluding “demonstrably accurate” outputs. Demonstration through independent expert verification opens the gate; presumed accuracy based on authentic inputs or impressive model performance does not. The rule preserves case-specific assessment while specifying the minimum foundation it requires.
[P4.5] Verification costs remain real, particularly where expertise is scarce. But scarcity does not make an ambiguous translation trustworthy. Your alternative saves money only by dispensing with the check or shifting it onto the opponent. Our rule permits efficient AI assistance while requiring whoever offers its conclusions to substantiate them.
[P4.6] In a criminal trial, an unverified shortcut should not become someone else’s burden to disprove.

## Turn 8: CON Rebuttal 2

- model: gpt-oss-120b
- raw_words: 284
- clipped_words: 284
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The “extra step” the motion demands is not a new expert hire but a brief, documented sanity‑check performed by the same qualified analyst who generated the AI output. Modern platforms export audit logs, confidence intervals, and the exact input text, allowing the analyst to confirm that the translation or summary faithfully reflects the source within minutes. That check satisfies the rule’s independence requirement because it is a separate, accountable evaluation, not a mere button press.
[C4.2] A2: Audit logs and confidence scores alone do not constitute proof of accuracy; they only describe the model’s internal certainty. The motion therefore requires the analyst to compare the AI result with the original material and explicitly state whether any ambiguity or alternative rendering exists. If the analyst finds a discrepancy, the evidence must be excluded or corrected before the jury hears it. Thus the defendant is not left to discover errors after admission; the verification step itself guarantees that any contested meaning is vetted.
[C4.3] The core of our case remains that existing evidentiary standards already mandate such verification for any interpretive evidence, whether produced by a person or a machine. Requiring a separate, pre‑admission human review simply codifies what judges already do under Daubert and Rule 702, ensuring due‑process consistency without creating a procedural bottleneck. Moreover, the cost is minimal—a few minutes of an analyst’s time—whereas the alternative allows unchecked AI outputs to flood the record, shifting the burden onto defendants who must later mount costly challenges.
[C4.4] By imposing a lightweight, mandatory check, the proposition preserves reliability, protects constitutional rights, and avoids the speculative, costly “verification race” the PRO side warns of. Consequently, the presumption of inadmissibility is unnecessary and harmful; a simple, case‑by‑case reliability gatekeeper suffices.

## Turn 9: PRO Closing

- model: gpt-6-astra-high
- raw_words: 196
- clipped_words: 196
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive question is whether an AI-generated claim may reach the jury before anyone qualified has checked its fidelity to the source. CON’s final answer is no. They require an analyst to compare the output with the original, identify alternative meanings, and exclude or correct discrepancies before the jury hears them. They even call this a “lightweight, mandatory check.” That is our admission condition, not an alternative to it.
[P5.2] Calling that protection existing practice does not establish that it is unnecessary or harmful. If existing rules already require independent human verification, this proposition states the minimum foundation CON accepts. If those rules sometimes permit admission without it, the presumption closes precisely the gap CON now says must be closed. Either way, judicial discretion cannot substitute for the substantive check both sides recognize as necessary.
[P5.3] Nor does our rule demand a second hire or perfect certainty. It demands an accountable expert who independently tests the generated content against its source. Where that check is straightforward, compliance is straightforward. Where it is difficult, dispensing with it does not make the evidence reliable.
[P5.4] The party offering a machine’s interpretation must substantiate it before another person’s liberty bears the risk.

## Turn 10: CON Closing

- model: gpt-oss-120b
- raw_words: 187
- clipped_words: 187
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The decisive advantage of the CON position is that the law already gives courts a proven, flexible mechanism to guarantee reliability without imposing a blanket pre‑admission ban. Under Daubert and Rule 702, any interpretive evidence—whether a human transcription or an AI‑generated summary—must be examined for relevance, authenticity and methodological soundness before a jury may see it. Judges routinely require the same “independent verification” that the proposition demands, by calling the analyst to the stand, demanding error rates, or ordering a side‑by‑side comparison with the source material.
[C5.2] Adding a presumptive exclusion therefore creates a redundant procedural hurdle that multiplies cost and delays, yet offers no additional protection because the same gate‑keeping question is already answered in the trial. The modest, minutes‑long sanity check described by CON fits neatly within existing practices and does not threaten the speedy‑trial right. Consequently, the proposition’s blanket rule merely complicates procedure while achieving nothing that the current evidentiary framework does not already provide. By preserving the established, case‑by‑case reliability test, CON ensures both efficiency and due‑process safeguards, making our side the clear winner.
[C5.3] Justice depends on using tools wisely, not on arbitrary bans.
