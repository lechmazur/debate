# Debate prop_0679__claude-opus-5-high__muse-spark-1.1-high__s0__tpl_placement_active_20260320f

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: claude-opus-5-high
- model_con: muse-spark-1.1-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A criminal trial is the one arena where the state can take a person's liberty, and the rules of evidence exist because we have decided that speed is never worth a wrongful conviction. The proposition asks for something modest inside that logic: before a machine's summary, translation, or reconstruction goes to a jury as evidence, a human being who can be examined must have checked it. Not banned. Not excluded forever.
[P1.2] Presumptively inadmissible until verified — a rebuttable presumption, exactly like the ones we already apply to hearsay, to expert opinion, to lab results with a broken chain of custody.
[P1.3] The reason is the specific failure mode of generative systems: they are optimized to produce output that *reads* correct, not output that *is* correct. A hallucinated sentence does not arrive flagged in red. It arrives in the same confident register as the true ones. That is the opposite of every other evidentiary risk we tolerate, where unreliability usually announces itself — the shaky witness, the smudged print, the interpreter who says "I'm not sure."
[P1.4] A model that invents a threat inside a summarized 400-hour wiretap, or renders an ambiguous Arabic idiom as an explicit confession, or "reconstructs" a plausible-looking face or trajectory that never existed, hands the jury a fabrication wearing the costume of fluency.
[P1.5] And there is nobody to cross-examine. The defense cannot ask the model why it chose that word, what it discarded, what its confidence was, whether it was primed by the prosecution's prompt. Confrontation is not a formality; it is our only working machine for exposing error before it becomes a verdict. Human verification restores an examinable witness who can be asked "did you listen to the original tape?" and be held responsible for the answer.
[P1.6] Weigh the costs honestly. Requiring verification slows some cases and costs some hours. Not requiring it produces convictions built on text no human ever checked against the source. In criminal law we have always accepted the first cost to avoid the second — and nothing about a fluent machine [clipped]

## Turn 2: CON Opening

- model: muse-spark-1.1-high
- raw_words: 283
- clipped_words: 283
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Presumptive inadmissibility is a cure that guarantees the disease it claims to prevent: less reliable evidence, slower trials, and an evidence rule that privileges human fallibility over tested accuracy.
[C1.2] Criminal law already has calibrated filters — authentication, hearsay, expert qualification under Daubert, and Rule 403 balancing. An AI-generated transcript is not admitted because a computer said so; it is admitted because a witness testifies how it was created, its error rate, and because the defense can attack it with the original audio, alternative translation, or competing reconstruction. That adversarial testing is more searching than asking a single hired verifier "did you check it?"
[C1.3] The proposition treats all AI as one dangerous black box. That ignores reality. For low-resource languages, for 40 hours of jail calls, for blurry video upscaling, machine systems consistently outperform the average bilingual officer or court interpreter. Requiring "independent verification by a human expert" — what expert?
[C1.4] Certified in what model? — makes the less accurate human the gatekeeper for the more accurate system. A court interpreter guessing at slang is admissible today without an expert double-check; an AI that logs every token probability and can be re-run would be presumptively excluded.
[C1.5] Who pays that presumption? Not well-funded prosecutors. The public defender with a client whose WhatsApp messages are in Pashto cannot afford a $400-an-hour linguist to bless a translation that the state can then challenge anyway. The rule invites exclusion of exculpatory material the defense found precisely because AI made it accessible.
[C1.6] Finally, human verification is theater. A signature that says "verified" replaces scrutable error rates and prompt logs with an unaccountable nod. Reliability comes from transparency and adversarial challenge of the process, not from a human rubber stamp.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.2], [C1.5], [C1.3]
- missing_claim_id_refs: (none)

[P2.1] Notice what CON's own admissibility story requires. [C1.2] says AI transcripts come in because "a witness testifies how it was created, its error rate," and can be cross-examined. That witness is my rule. A human being who takes the stand, vouches for the output, and can be held to it — that is exactly what "independently verified by a human expert" means.
[P2.2] CON has conceded the motion and then called it theater. You cannot simultaneously promise the jury an examinable sponsoring witness and tell me a human in the loop adds nothing.
[P2.3] And if there truly is no such human — if the output arrives self-certifying — then adversarial testing collapses. You cannot cross-examine token probabilities. You can hand the defense the original audio and say "go check forty hours of Pashto yourself," but that is not confrontation; that is outsourcing the state's burden to the poorest party in the room.
[P2.4] Which answers [C1.5] directly. A presumption falls on the *proponent*. The party ordinarily offering machine-processed wiretaps, upscaled video, and reconstructed trajectories is the state, with forensic budgets. My rule is not a tax on the public defender; it is a tax on the side that must prove guilt beyond reasonable doubt.
[P2.5] And courts already treat defense-offered exculpatory material more permissively — a rebuttable presumption bends the same way. CON's "who pays" argument is aimed at a rule that burdens the accused. That is not this rule.
[P2.6] On accuracy [C1.3]: I do not dispute that machines beat the average interpreter on average. Averages are the wrong metric in criminal law. We do not ask whether a method is usually right; we ask what happens when it is wrong. The interpreter who guesses at slang says "I think" and hedges on the stand.
[P2.7] The model renders the guess in the same flat confident prose as the truth, and logs a high probability for it because fluency is what it optimized. Verification is cheap precisely where it matters: one person, one comparison against the source, one name on the record.

## Turn 4: CON Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.7], [P2.4], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO's [P2.1] rewrites its own rule. A witness who testifies "this system was tested at X error rate, here is the prompt, version, and source file, and the output is linked to timestamps" is not a human expert who independently verified the content against the source. The first is process authentication under 901(b)(9), already required. The second is duplication.
[C2.2] We defend the first; the motion demands the second. So there is no concession in [P2.2].
[C2.3] That distinction answers [P2.3]. You *can* cross-examine a system more searchingly than a human. You can ask what alternative translations were in the n-best list, what confidence the model assigned, whether a summary sentence maps to any source byte or is unsupported, whether the reconstruction used data beyond the input. A human interpreter who says "that's my best reading" gives you nothing to re-run and no log to audit.
[C2.4] The log is a witness that does not forget.
[C2.5] Mandating a human verifier destroys that advantage. [P2.7] calls it cheap — "one person, one comparison." For a 400-hour wiretap summary or a Pashto bundle, independent verification is not a glance, it is redoing 400 hours. For a reconstruction, what counts as independent verification — building a second model?
[C2.6] When forced to be gatekeepers, humans exhibit automation bias: they sign. You replace scrutable uncertainty with un-auditable confidence, and juries overweight it precisely because it has a name.
[C2.7] [P2.4] and [P2.5] try to save the rule by saying judges will bend it for the defense. The proposition as written does not. Presumptively inadmissible means presumptively inadmissible, whether the proponent is the state or the public defender offering AI-translated exculpatory WhatsApps she found because AI made them accessible. And even on the state-only story, the incentive is perverse: skip the better-logged AI and use the monolingual officer who guesses at slang, because his guess is admissible today without any second expert.
[C2.8] What we need is a transparency requirement — original, prompt, version, confidence — subject to adversarial testing, not a human rubber stamp as a condition of admission.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-high
- raw_words: 106
- clipped_words: 106
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[P3.1] Q1: Under your transparency-only regime, when a summary asserts a threat that appears nowhere in the 400 hours — high logged confidence, plausible timestamp attached — who catches that before the verdict, and does *anyone* ever compare that sentence against the source audio?
[P3.2] Q2: You call verification "duplication" [C2.1]: must your sponsoring witness have listened to any part of the original, or may she vouch entirely from the log? If entirely from the log, name the party you expect to fund the 400-hour check — and if that party is the defense, explain how your rule isn't the exact burden-shift you accused my rule of being.

## Turn 6: CON Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7], [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You call verification "one person, one comparison" [P2.7] — for a reconstruction or super-resolved frame with no ground-truth pixel, what source does your human verify against, and how is that not just unreviewable subjective approval?
[C3.2] Q2: You claim the presumption burdens only the state [P2.4] — the proposition says all AI evidence is presumptively inadmissible: would you exclude a defendant's AI-translated exculpatory messages unless she can afford your human expert?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-high
- raw_words: 354
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The verifier verifies against the *input*, and her most important testimony is often negative: "these forty pixels cannot support that face." Where there is no ground truth, someone must say so under oath — and that is precisely the sentence a log will never volunteer. Call it subjective; it is *reviewable* subjectivity, because she can be cross-examined on it, impeached, and contradicted. A super-resolved frame with no human willing to stake their name on what it shows is not evidence the jury should see as a photograph of the defendant.
[P4.2] If nobody can verify it, that is a reason to exclude, not a reason to admit.
[P4.3] A2: Yes, the presumption applies to both sides — and it is trivially rebuttable for the defense, because a "human expert" is not a $400-an-hour linguist. It is any competent bilingual person who read the Pashto and will take the stand. The defendant's cousin who speaks the language qualifies. Courts already fund defense experts for indigent clients and already relax evidentiary bars where excluding exculpatory material would violate due process.
[P4.4] CON's cost objection only bites if you imagine the most expensive possible verifier; my rule asks for the cheapest available one.
[P4.5] And notice what CON still has not answered. My Q1 asked who catches the hallucinated threat that never occurs in the four hundred hours. The reply was a log. A log records that the model was confident.
[P4.6] It cannot record that the model was wrong, because the model does not know. Under a transparency-only regime, a jury can convict on a sentence no human being ever compared to the tape — and CON has told you, in effect, that this is fine because the defense could have checked.
[P4.7] CON's best argument is automation bias: verifiers will rubber-stamp. But bias in a duty to look is strictly better than no duty at all. Some verifiers will check carelessly; every one of them checks more than nobody. And the careless one has a name, an oath, and a cross-examination waiting.
[P4.8] That is the [clipped]

## Turn 8: CON Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P3.1], [C2.1], [P3.2], [P4.1], [P4.3], [C3.2], [P4.7]
- missing_claim_id_refs: (none)

[C4.1] A1: Under transparency, the hallucinated threat in [P3.1] is caught before verdict because admission requires grounding — every summary sentence must cite source offsets. A sentence with a fake timestamp and no underlying audio fails authentication under current 901 and would be excluded at a pretrial hearing without any 400-hour listen. The proponent must show the link; the defense spot-checks that link, not the whole haystack. Your verifier doing a blind 400-hour re-listen is the inefficient way to catch it.
[C4.2] A2: My witness is not vouching from a log alone. [C2.1] drew the line: she testifies to process, error rates, and that she sampled and verified grounding, not that she duplicated 400 hours. [P3.2] asks who funds the full check — no one, upfront. Like DNA electropherograms, the proponent shows methodology and traceability; the opponent only funds a full re-review if the grounding fails or is challenged.
[C4.3] Your rule forces that full cost as the price of admission for both sides.
[C4.4] That flips the debate. [P4.1] admits that where there is no ground-truth pixel, your human cannot verify against input — she just announces her own subjective limit. That is not verification, that is veto by hunch, and you would exclude a super-resolution that log data can audit for exactly what information it added. And [P4.3] now says a cousin counts as an expert — if any bilingual will do, the safeguard is theatre; if you really demand an expert, your cost defense collapses and [C3.2]'s exculpatory Pashto stays out because the defender cannot pay.
[C4.5] [P4.7] says a duty to look beats no duty, but a named verifier who rubber-stamps induces jury overconfidence exactly when he is wrong, while transparent uncertainty preserves skepticism. We don't need a presumptive ban to stop hallucinations. We need grounding plus adversarial testing — more reliable than a rubber stamp with a name.

## Turn 9: PRO Closing

- model: claude-opus-5-high
- raw_words: 194
- clipped_words: 194
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.2]
- missing_claim_id_refs: (none)

[P5.1] Decide this on one sentence CON wrote: her witness "sampled and verified grounding" [C4.2]. That is a human expert independently checking the machine's output against the source before it reaches a jury. That *is* the motion. The remaining quarrel is only over how much sampling suffices — a question of degree that judges answer case by case, exactly as a rebuttable presumption invites.
[P5.2] CON has spent five speeches defending my rule and calling it a rubber stamp.
[P5.3] And grounding alone cannot close the gap. A timestamp catches the crude hallucination — the threat citing audio that does not exist. It cannot catch the dangerous one: a sentence anchored to real audio that says something the audio never said. The tape is there, the offsets match, the confidence is high, and the words are invented.
[P5.4] Nothing in a log will ever flag that. Only a person who listened will.
[P5.5] So the choice is not stamp versus science. It is whether the single most consequential sentence in a case gets compared to reality by someone under oath, or by no one at all. When liberty is what we are spending, the answer cannot be no one.

## Turn 10: CON Closing

- model: muse-spark-1.1-high
- raw_words: 179
- clipped_words: 179
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] That last sentence rewrites the motion. A witness who shows how a system links each claim to its source, discloses error rates, prompts and n-best alternatives, and submits spot-checks to pretrial adversarial testing is not a human who independently verified the content. The first is auditable process under rules we already have. The second is forced duplication that PRO admits collapses into a cousin or a rubber stamp.
[C5.2] Grounding defeats more than crude hallucinations. A translation anchored to real audio that invents meaning fails when the defense offers a competing translation from the same log — which the log preserves and a human memory does not. Your verifier who glanced and signed gives the jury a name to trust; my log gives them a reason to doubt.
[C5.3] And because the presumption as written hits both sides, the exculpatory Pashto bundle the public defender could finally read stays out unless she can afford the stamp. Presumptive inadmissibility doesn't protect confrontation. It replaces a transcript you can interrogate with a person you cannot, and tells the jury to trust the person.
