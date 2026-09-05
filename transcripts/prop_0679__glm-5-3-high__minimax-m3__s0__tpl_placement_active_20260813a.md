# Debate prop_0679__glm-5-3-high__minimax-m3__s0__tpl_placement_active_20260813a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: glm-5-3-high
- model_con: minimax-m3
- side_swap: False

## Turn 1: PRO Opening

- model: glm-5-3-high
- raw_words: 343
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A criminal trial is not a search engine. When a person's liberty is on the line, the evidence that convicts must be testable by a human being, in open court, under oath. AI-generated evidence fails that test at every stage, which is why it should be presumptively inadmissible unless a qualified human expert independently verifies it.
[P1.2] Start with the mechanism. Generative AI systems do not retrieve facts; they predict plausible outputs. That is why they hallucinate—confidently fabricating translations, summary content, even citations—in contexts where nothing alerts the user. A human summarizer who invents a confession can be cross-examined about why.
[P1.3] An AI that invents one cannot explain itself, and its operator usually cannot either. Black-box output is the antithesis of the adversarial process: the defendant cannot confront the "witness," probe its biases, or expose how it erred in this specific case.
[P1.4] Second, verification is not a nicety; it is the existing standard for everything else we admit. We do not accept lab results without an analyst, ballistics without an examiner, or translations without a certified interpreter. The rule simply extends a familiar principle: machine products enter the courtroom through human accountability. Opposing this rule means arguing AI evidence deserves *less* scrutiny than a breathalyzer—a device whose internals can at least be specified and challenged.
[P1.5] Third, the error asymmetry is decisive. In commerce, an occasional bad summary is a rounding error. In a criminal trial, one hallucinated phrase in a translated wiretap—"he said he would go" versus "he said he went"—can be the difference between acquittal and decades in prison. When the cost of error is catastrophic and the error rate is opaque, the burden must sit squarely on the party offering the evidence.
[P1.6] Notice what the proposition does not do. It does not ban AI. It does not demand perfection. It says: a human expert must stand behind the output before it reaches a jury.
[P1.7] If the technology is as reliable as its advocates claim, verification is cheap. If it isn't, verification is essential. Either way, the presumption is the [clipped]

## Turn 2: CON Opening

- model: minimax-m3
- raw_words: 339
- clipped_words: 339
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition asks us to flip the default. Evidence is presumptively admissible when relevant and authentic; the challenger objects. The motion would make AI evidence presumptively inadmissible, forcing whoever offers it to find, pay for, and present a human verifier before a jury ever hears it. That procedural switch is the heart of the disagreement.
[C1.2] Consider what it costs. Police translate wiretap evidence across dozens of languages. Defense investigators reconstruct surveillance from fragmented cloud footage. Prosecutors summarize tens of thousands of pages of discovery.
[C1.3] The proposition does not ban these tools; it gates them behind a paid human expert for every use. Who pays? In practice, the defense bar and public defenders' offices, already operating at a fraction of prosecutorial resources. The result is not neutral.
[C1.4] Wealthy defendants get AI-assisted reconstructions heard; indigent defendants do not. A rule framed as protecting fairness becomes a structural advantage for the state, whose institutional access to human experts the accused rarely matches.
[C1.5] My opponent's analogy to breathalyzers and lab analysts is clever but backwards. Those are physical instruments a witness can explain from first principles. AI outputs are often more reproducible than a fatigued human translator working at 2 a.m. under a deadline. The better comparison is the court reporter's transcript - routinely admitted, occasionally imperfect, tested against the recording when challenged.
[C1.6] We trust the transcript because we have a verification mechanism after the fact, not because we presume it inadmissible up front.
[C1.7] That mechanism already exists. Federal Rule of Evidence 901 requires authentication; Rule 702 governs expert testimony; Rule 403 lets judges exclude misleading evidence. A judge confronting an unreliable AI summary can keep it from the jury. What is missing is not law - it is the case-by-case showing of unreliability, raised by the party with reason to challenge.
[C1.8] The presumption this motion installs is the wrong instrument. It excludes evidence that may well be reliable in order to police a smaller set of questionable outputs, and it does so at the expense of the party least able to pay.

## Turn 3: PRO Rebuttal 1

- model: glm-5-3-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.3], [C1.4], [C1.5], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] Three claims to answer.
[P2.2] First, the cost story. My opponent says the human-verification gate burdens indigent defendants [C1.3][C1.4], but this gets the burden exactly backwards. The presumption binds whoever *offers* the evidence—and in criminal trials, that is overwhelmingly the prosecution. The state must prove guilt; the state has crime labs, staff analysts, and budgets.
[P2.3] Far from disadvantaging the poor defendant, the rule gives her something she currently lacks: a named human being who signed the translation or reconstruction and can be cross-examined about it. Today, the defense faces black-box output with no one to question. Requiring verification doesn't price the accused out of the courtroom; it gives her a target for confrontation she otherwise never gets.
[P2.4] Second, the court reporter analogy [C1.5]. It collapses on inspection. A transcript is a *verbatim capture* of words already spoken—and the recording exists as ground truth to check it against. An AI summary or translation is *generative*: it produces new content, and there is no master recording of "what the summary should have said" to test it against.
[P2.5] That is precisely why the analogy fails. We trust transcripts because verification is built into the artifact itself. With AI output, the only verification available is a human doing the work independently—which is exactly what the proposition requires.
[P2.6] Third, "the law already exists" [C1.7]. Rules 901 and 702 are the same case-by-case framework that spent decades admitting bite-mark analysis and hair comparison—junk that destroyed convictions—precisely because judges lacked the tools to screen it in individual cases. "The challenger must show unreliability" means the party without the source code, training data, or expertise carries the load.
[P2.7] Case-by-case screening has already been tried, in exactly this form, and it failed. A clear presumption with a human escape valve is the lesson learned.

## Turn 4: CON Rebuttal 1

- model: minimax-m3
- raw_words: 349
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.2], [P2.5], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] The proposition's greatest flaw is that it polices the wrong category. It excludes based on whether evidence was AI-generated, rather than whether it is reliable in this specific case. That is a categorical ban on a tool, not a reliability rule.
[C2.2] Take the cost argument first. My opponent says the burden falls on whoever offers the evidence, "overwhelmingly the prosecution" [P2.2]. But the defense offers evidence too - affirmative defenses, reconstructions of favorable surveillance, translations of alibi documents. When the prosecution offers an AI summary, the defendant still must hire her own expert to challenge it.
[C2.3] The gate the proposition installs is not symmetric. The state has crime labs; the public defender has a caseload of 400. Every new hurdle in offering evidence costs the defense more than it costs the prosecution. The proposition is not a defense tool; it is a structural subsidy to institutional prosecutors.
[C2.4] The court reporter analogy [P2.5] holds better than my opponent admits. Yes, AI can be generative - but most courtroom AI use is not. Translation has a source text. Transcription has an audio recording.
[C2.5] Reconstruction has raw footage. In all those cases, ground truth exists for after-the-fact verification, which is the system we have now. The "no master version" objection applies only to truly novel AI outputs - a small subset - and for those, judges can already exclude under Rule 403 when unreliable. The proposition sweeps in routine cases where verification is cheap and ground truth sits in the record, treating them the same as the hard cases.
[C2.6] And the bite-mark lesson [P2.7] cuts the opposite way. Those fields were admitted *because* credentialed experts vouched for them - precisely the human-verification gate my opponent praises. They failed because courts deferred to credentials without probing methodology, not because case-by-case screening is structurally broken. The same adversarial testing - Daubert motions, cross-examination - is now correcting those fields.
[C2.7] Adding a presumption against AI does not fix that pathology. It punishes a different category of evidence while leaving the underlying deference problem untouched, and it [clipped]

## Turn 5: PRO Pressure Questions

- model: glm-5-3-high
- raw_words: 81
- clipped_words: 81
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say ground truth "sits in the record" [C2.5]—but checking an AI translation or summary against that source requires a human expert doing independent work. Isn't your after-the-fact system just my verification rule, delayed until after the jury has heard the tainted version, with the defense paying for it?
[P3.2] Q2: Bite-mark evidence failed because credentialed experts *vouched* for it [C2.6]. My rule demands independent verification of the output, not deference to credentials. What in your framework actually distinguishes those two?

## Turn 6: CON Pressure Questions

- model: minimax-m3
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.7], [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: You call verification "cheap" if AI is reliable [P1.7]. When an indigent defendant needs human verification of an AI-generated alibi reconstruction, who pays, and by what concrete dollar figure per case have you measured that "cheap" against a typical public-defender budget?
[C3.2] Q2: You promise defendants "a named human being... to cross-examine" [P2.3]. If that expert simply affirms the AI's output without independent work, cross-examination is theater. What in your rule actually prevents rubber-stamping disguised as verification?

## Turn 7: PRO Rebuttal 2

- model: glm-5-3-high
- raw_words: 350
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.5]
- missing_claim_id_refs: (none)

[P4.1] A1: Who pays when an indigent defendant offers an AI alibi reconstruction? The same mechanism that pays for her defense investigator and court-appointed experts today—courts already have established procedures for appointing and compensating experts for indigent parties. But notice what my opponent's question concedes: no dollar figure will make the problem disappear, because the alternative isn't zero-cost. Under her rule, the defense still needs the identical expert work—but only after the prosecution's AI output has already reached the jury, and with the burden of challenging it on the party with the least resources.
[P4.2] Her system doesn't avoid the cost; it defers it, inflates it, and reverses who bears it.
[P4.3] A2: Rubber-stamping is a real risk, and my rule has a built-in answer: the verifier must do the underlying work, not affirm the machine. A translator must work from the source text; a reconstructionist must review the raw footage. That distinction is testable in cross-examination—"What did you translate from? Show your work product.
[P4.4] How long did the review take?"—and it is discoverable in advance. A rubber-stamp collapses the first time a competent cross-examiner asks it. Contrast bite-mark evidence, where the pathology was deference to credentials standing *in place of* checkable work. My rule doesn't just add a human title; it adds a work product the adversary can interrogate.
[P4.5] Notice what both questions share: they assume verification is expensive and hard to police. But that is precisely my case. If independent human work is that burdensome and that easy to fake, then an unverified AI output is exactly what should never reach a jury untested. My opponent has never answered the core concession buried in her own position [C2.5]: checking AI output against "ground truth in the record" requires a human expert doing independent work.
[P4.6] That is my rule. She just wants it performed after admission, at the challenger's expense, with the jury already exposed to the machine's version.
[P4.7] The presumption puts the check before the verdict, paid by the party offering the evidence, with a cross-examinable human behind every output. That [clipped]

## Turn 8: CON Rebuttal 2

- model: minimax-m3
- raw_words: 422
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: My opponent concedes the indigent defendant still needs the identical expert work - just later, paid by the defense, after the jury has already heard the prosecution's AI output [P4.1][P4.2]. That is not an answer; it is a restatement of the asymmetry. Her "court-appointed experts" mechanism applies when the defense offers evidence. When the prosecution offers an AI translation of a confession, there is no analogous state-funded defender-expert to second-guess it before trial.
[C4.2] The defendant either hires her own or cross-examines the prosecution's verifier - if one exists. My system moves the cost to the party with institutional labs and salaries, which is the opposite of what she claims.
[C4.3] A2: The "rubber-stamp" answer is reassuring but circular. If the verifier must produce independent work product to be credible, then the rule is not "human expert signs off on AI output" - it is "human expert performs the task and AI is redundant." That is not verification of AI; that is replacement of AI. When genuine verification is the standard - an expert who tests the AI's claims rather than redo them from scratch - rubber-stamping becomes nearly invisible to cross-examination, because the expert can plausibly describe reviewing the output against the source for hours.
[C4.4] The work-product requirement cannot distinguish a real check from a performed one without intrusive supervision that no rule currently mandates.
[C4.5] Here is why CON still wins. The clash has narrowed to a single question: when an AI output is offered, who does the checking, when, and at whose expense? PRO's rule front-loads the cost on the offering party and bars the evidence until a human stands behind it.
[C4.6] But front-loading does not eliminate the cost - it allocates it. And the allocator is always the party with resources, because only parties with resources can clear the gate at all. The rule does not make verification cheaper or more rigorous; it makes evidence presentation more expensive, and the bill is paid disproportionately by the defense bar and indigent defendants offering affirmative claims.
[C4.7] The proposition also conflates [clipped]

## Turn 9: PRO Closing

- model: glm-5-3-high
- raw_words: 204
- clipped_words: 204
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C2.5], [C4.3], [C4.1]
- missing_claim_id_refs: (none)

[P5.1] The debate ends where my opponent's last speech left it: she conceded that checking AI output against the source requires a human expert doing independent work [C2.5]. Since then, she has argued only about timing and billing. That is not a case against verification; it is a case for my rule with worse sequencing.
[P5.2] Her "circularity" objection [C4.3] is the final concession. If genuine verification means the human must actually engage the source material, then her alternative admits machine output to the jury *before* that engagement happens—if it happens at all. She asks us to trust that a challenged, under-resourced defendant will catch the error afterward. The bite-mark era shows exactly how post-hoc challenge fails when the credentialed artifact is already in front of the jury.
[P5.3] And her asymmetry argument inverts reality [C4.1]. The party offering evidence in a criminal trial is overwhelmingly the state. My presumption makes the state pay to verify its own evidence before conviction, not after. If verification is expensive, that is an argument against cheap convictions, not against the rule.
[P5.4] One question decides this: does a jury hear machine-generated words before or after a human stands behind them under oath? Only one answer is compatible with a criminal trial.

## Turn 10: CON Closing

- model: minimax-m3
- raw_words: 201
- clipped_words: 201
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The clash is no longer about whether AI evidence must be verified. It is. My opponent conceded that checking output against the source requires a human expert doing independent work. So the question is mechanism: presumptive inadmissibility up front, or adversarial testing once offered.
[C5.2] Her closing narrows to sequencing: before or after. That concedes the point. Verification is the principle on both sides. The difference is who clears the gate.
[C5.3] Her rule requires the offering party to find, pay for, and produce a verifier before the jury hears a word. In a criminal trial, that gate is cleared by whoever has the budget to clear it, and history is unambiguous about which side that is.
[C5.4] The bite-mark lesson she invokes is misread. Those convictions were not produced by absent verification; they were produced by deference to credentials standing in for work product. The remedy was Daubert scrutiny and cross-examination, exactly the tools Rules 901, 702, and 403 already provide. Her rule does not strengthen that machinery.
[C5.5] It adds a wealth test on top of it, and wealth tests in criminal procedure have a single consistent effect: they favor the state.
[C5.6] Same principle, better mechanism. Verify, but do not filter by wealth.
