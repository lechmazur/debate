# Debate prop_0679__muse-spark-1.1-high__claude-opus-5-high__s1__tpl_placement_active_20260320f

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: muse-spark-1.1-high
- model_con: claude-opus-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: muse-spark-1.1-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] In a criminal trial the state asks to take away liberty, sometimes life. The evidence that justifies that must be testable, explainable, and accountable. AI-generated summaries, translations, and reconstructions are none of those.
[P1.2] An AI cannot be cross-examined. It cannot explain why it chose one translation of a slang term over another, why its summary dropped a qualifying sentence, or why its enhancement added a tattoo that was never there. These are not hypothetical glitches; they are core to how generative models work. They predict plausible text or pixels, not true ones.
[P1.3] They hallucinate with confidence, they embed training bias, and their reasoning is opaque even to their creators. A human translator can be asked about dialect, context, uncertainty. A forensic artist can be asked what she added. An AI gives you an output and a shrug.
[P1.4] That opacity is fatal in criminal court. A mistranslated WhatsApp message can turn a joke into a threat. A summary of a thousand pages of financial records that omits the one exculpatory email violates Brady in effect if not intent. A reconstruction that sharpens a blurry license plate into the wrong number creates guilt from noise.
[P1.5] The defendant cannot interrogate the model to expose that error; even the prosecutor often cannot.
[P1.6] Presumptive inadmissibility does not ban AI. It demands what the law already demands for forensics: independent human verification. If a qualified human expert has reviewed, replicated, and is willing to swear to the translation, summary, or reconstruction on personal knowledge, admit it. If not, keep it out.
[P1.7] That preserves usefulness while placing the burden where it belongs - on the state, not on a defendant trying to disprove a black box. In criminal law, we do not outsource truth to systems we cannot question.

## Turn 2: CON Opening

- model: claude-opus-5-high
- raw_words: 334
- clipped_words: 334
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Start with who actually gets hurt. Picture a public defender handed nine terabytes of body-cam footage, jail calls, and a phone extraction, with six weeks to trial and no expert budget. An AI pass over that mountain finds the ninety seconds where the officer contradicts his report. Under the rule as written, that reconstruction or summary is presumptively out until she buys a human expert to re-verify it.
[C1.2] The state can afford that expert. She cannot. A presumption of inadmissibility is not a shield for defendants; it is a tax on the poorest party in the room, and the prosecution — which already has crime labs, staff translators, and analysts — pays it most easily.
[C1.3] Second, look hard at what "independently verified by a human expert" actually buys. Either the human redoes the entire task, in which case the AI saved nothing and we have simply priced the technology out of criminal practice, or the human skims and signs — verification theater, with a credential laundering the same output. And notice which failures actually convicted innocent people: bite-mark comparison, microscopic hair matching, discredited arson indicators, a bilingual officer improvising an interrogation translation. Those were all human experts, testifying confidently, on personal knowledge.
[C1.4] Human review is not a validated error-correction mechanism. It is the mechanism that failed.
[C1.5] Third, the opacity claim runs backwards. You cannot re-run a forensic artist's brain. You can run a model a thousand times, feed it counterfactual inputs, measure how often the summary drops exculpatory lines, publish a known error rate. That is precisely what Daubert asks for and precisely what humans cannot supply.
[C1.6] And we already have the tools: authentication, expert gatekeeping, confrontation, Brady, disclosure of the tool and its inputs. Those apply case by case, to the specific output, in the specific case. A categorical presumption over a category that includes OCR, machine translation, speaker identification, and probabilistic genotyping is a blunt instrument aimed at a problem that requires a scalpel — and it will cut the defense first.

## Turn 3: PRO Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.1], [C1.3], [C1.4], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The poverty claim in [C1.1] confuses investigation with evidence. If your AI scans nine terabytes and finds the ninety seconds where the officer contradicts himself, you don't admit the AI summary. You admit the ninety seconds. That's original body-cam.
[P2.2] The AI was a flashlight, not a witness. Presumptive inadmissibility doesn't tax that search at all.
[P2.3] What it taxes is the state trying to convict with a machine transcript, summary, or reconstruction no human will own.
[P2.4] [C1.3]'s argument that verification is either redundant or theater gets the burden backwards. If verification requires redoing the work, good - that's exactly what we demand for DNA, drug chemistry, fingerprints. We don't let a tech file a machine guess. If a human just skims and signs, that is not failure of the rule but violation of it.
[P2.5] A qualified expert willing to swear from personal knowledge, under perjury and cross-examination, is not laundering. It's accountability.
[P2.6] Humans have failed, as [C1.4] notes. But we reformed hair and bitemark by adding rigor, not by authorizing a more opaque system to repeat the same confident errors at scale. A bilingual officer who botched a translation can be questioned about dialect, uncertainty, slang. An AI that turns "borrar" into "bury" cannot.
[P2.7] [C1.5] says you can rerun the model a thousand times and publish an error rate. An aggregate error rate tells this jury nothing about whether this summary dropped the one exculpatory email, whether this enhancement added a tattoo that was never there. With proprietary, weekly-updated, prompt-sensitive models, there is no stable "technique as applied" for Daubert to test.
[P2.8] Because of that, [C1.6] collapses. Brady assumes the prosecutor sees what was omitted. Confrontation assumes a witness who knows how the conclusion was reached. An AI that hallucinates with confidence leaves both blind.
[P2.9] Presumptive inadmissibility forces what those doctrines presuppose: a human who checked, who knows, and who can be questioned.

## Turn 4: CON Rebuttal 1

- model: claude-opus-5-high
- raw_words: 365
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.4], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] The flashlight answer in [P2.1] is the most damaging concession in this debate, and PRO should look at what it costs. "Admit the ninety seconds, not the summary" works only where the AI's output is a pointer to something a jury can perceive directly. But a translation has no such original. A Spanish-language jail call is unintelligible to an English-speaking jury; the translation *is* the evidence.
[C2.2] A reconstruction has no original by definition. And summaries of voluminous records are admitted as evidence in their own right, every day, because nobody can put nine terabytes in front of a jury. So either the motion covers those things — in which case the flashlight reply is irrelevant to the hardest cases — or PRO has quietly narrowed the motion to the one category where exclusion costs nothing.
[C2.3] Worse, the inconsistency I care about often isn't ninety seconds. It's a pattern across forty calls, or a discrepancy between a report and footage timestamps. You cannot play the pattern. You can only summarize it.
[C2.4] Under this rule, the defense's ability to show a pattern depends on whether she can buy an expert to re-derive it.
[C2.5] And rules of exclusion run both ways. The defendant has a constitutional right to present a defense; the state has alternatives — staff translators, crime labs, analysts. A presumption against a category of evidence always bites hardest on the party without institutional capacity.
[C2.6] [P2.4] concedes the rest. If verification means redoing the work, then the motion is not a verification standard, it is a prohibition dressed as one. Fine — own that, but stop calling it modest.
[C2.7] On [P2.7]: "an aggregate error rate tells this jury nothing about this output" is true of every forensic discipline and every eyewitness ever admitted. We never know if *this* fingerprint call was the erroneous one. The difference is that with a model you can spot-check the specific question — did the summary drop this email? — against the source, in an afternoon. Try auditing a translator's judgment about dialect that way.
[C2.8] [clipped]

## Turn 5: PRO Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 68
- clipped_words: 68
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: You concede translation has no original the jury can understand [C2.1] – if no human expert verifies and swears to it, who does the defendant confront about dialect, slang, or a hallucinated threat?
[P3.2] Q2: You call verification that requires redoing the work a prohibition [C2.6] – is requiring a human analyst for DNA also a prohibition, or why should AI evidence face a lower standard than forensics?

## Turn 6: CON Pressure Questions

- model: claude-opus-5-high
- raw_words: 89
- clipped_words: 89
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Your rule covers "AI-generated" summaries, translations, reconstructions. Does that presumption also exclude OCR, automated transcription, phone-extraction software, and probabilistic genotyping — all AI-generated outputs no human re-derives from scratch? If yes, you've excluded routine forensics; if no, tell us the line, because "AI" isn't one.
[C3.2] Q2: Does the presumption apply equally to AI evidence offered *by* an indigent defendant? If yes, name the fund that pays her verifying expert. If no, you've conceded the real objection is prosecutorial power, not machines — and the motion is written wrong.

## Turn 7: PRO Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 276
- clipped_words: 276
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C3.1], [C2.5], [C1.1], [C2.3], [C2.6], [C2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: The presumption tracks the three examples in the motion: outputs where the machine invents content — a summary choosing what to omit, a translation choosing a meaning, a reconstruction filling in pixels. OCR or a phone extraction copying bits is not inventing; verification is comparing source to output, which a human can do in minutes and already does for authentication. Probabilistic genotyping already requires a human expert to interpret and swear to it, so it passes our test, it doesn't fail it.
[P4.2] [C3.1] asks for a bright line; the line is inference versus copy.
[P4.3] A2: Yes, equally to both sides, as reliability rules must. The fund is the existing indigent-defense expert fund under Ake — same pot that pays for drug chemists. But the burden of that symmetry falls heaviest on the state, because the state is the party trying to take liberty with a black box. If we let unverified AI translations in, the indigent defendant must buy an expert to debunk them.
[P4.4] If we require a human verifier, she gets cross-examination for free.
[P4.5] That flips [C2.5] and [C1.1]. CON's whole equity case assumes the defense will offer AI patterns that no human checked. But a pattern across forty calls [C2.3] is exactly the kind of summary that can smuggle an exculpatory omission or hallucinated threat past a jury. Presumptive inadmissibility doesn't prohibit [C2.6]; it mirrors DNA.
[P4.6] We require a human analyst for DNA precisely because the machine result alone can't be questioned.
[P4.7] When there is no original the jury can understand [C2.1], confrontation is not a luxury; it is the only safeguard. The flashlight is free; testimony no human will own is not.

## Turn 8: CON Rebuttal 2

- model: claude-opus-5-high
- raw_words: 352
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.5], [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: She confronts the party offering it, with the original in hand. A disputed jail-call translation is not an unfalsifiable black box — the audio exists, the transcript exists, and the defense can put up a competing translation of the contested line and let the jury choose. That is how translation disputes are already litigated. What PRO cannot explain is why cross-examination of a human is *error-correction*.
[C4.2] The bilingual officer who improvised a translation was cross-examinable, sworn, and wrong. Confrontation is a procedure for testing claims, not a guarantee they're true — and a testable, re-runnable tool plus a sponsoring witness who discloses the tool, prompt, and inputs gives the defense more to test than a translator's unrecoverable intuition about dialect.
[C4.3] A2: DNA is my example, not PRO's. No human re-sequences the genome or re-derives the likelihood ratio; the analyst interprets machine output and is cross-examined on it. That is admission with a sponsoring witness — exactly what I've argued for — not a presumption of inadmissibility. PRO has now described its own rule as "mirroring DNA" [P4.5], which means the motion collapses into current practice and there's nothing to vote for.
[C4.4] And the bright line offered in [P4.1] — inference versus copy — does not hold for one round. Automated transcription of noisy jail audio infers constantly; it guesses at muffled words. OCR of degraded handwriting infers. Speaker identification and probabilistic genotyping are inference by design.
[C4.5] If the line is inference, PRO has just excluded routine forensics; if it isn't, the line is undefined and judges are being asked to adopt a presumption whose scope nobody can state.
[C4.6] On funding: "the existing indigent-defense expert fund" is not an answer anyone who has practiced would accept. Those funds are discretionary, capped, and routinely denied. PRO concedes the presumption binds the defense equally [P4.3], so the pattern across forty calls goes out unless a judge grants money the state never has to ask for.
[C4.7] That is the decisive comparison. Both sides want a human who can be questioned. Only one [clipped]

## Turn 9: PRO Closing

- model: muse-spark-1.1-high
- raw_words: 178
- clipped_words: 178
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.1], [C4.3], [C4.4]
- missing_claim_id_refs: (none)

[P5.1] When there is no original the jury can understand, the translation is the conviction. [C4.1] says confront the offering party with the audio and offer your own translation. That's not confrontation, that's making the indigent defendant buy the expert CON already admits she cannot afford. A human verifier the state must produce gives cross-examination for free; an unverified AI makes the defendant purchase innocence.
[P5.2] CON calls that current practice in [C4.3] and is right. DNA, drug chemistry, fingerprints are inadmissible without a human who replicates, interprets, and swears. We are not inventing a ban; we are refusing an AI exception to it. [C4.4] says noisy transcription also infers, so our rule would exclude it — yes, unless a human verified it, which authentication already requires.
[P5.3] The state asks to take liberty. It must bring a witness who knows why "we'll take care of it" became a threat, not a printout that cannot answer. You cannot cross-examine a prediction. You can cross-examine a person who owns it.
[P5.4] Presumptive inadmissibility keeps that person in the box where the Constitution demands.

## Turn 10: CON Closing

- model: claude-opus-5-high
- raw_words: 202
- clipped_words: 202
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] Two speeches ago PRO said its rule "mirrors DNA." That sentence decides this debate.
[C5.2] Because DNA is not presumptively inadmissible. It comes in the ordinary way: a sponsoring witness who interprets machine output he did not personally re-derive, disclosed method, cross-examination, and a judge free to exclude the unreliable. That is the regime I have defended from the first speech. If PRO's rule is that, there is nothing on the ballot — the motion as written asks you to add a presumption of exclusion that current practice does not use and does not need.
[C5.3] And when PRO makes the presumption real, it cannot say what it covers. "Inference versus copy" dissolved the moment we noticed that noisy-audio transcription guesses at muffled words. PRO's answer was to swallow it: exclude that too, unless verified. So the scope is either everything or undefined, and judges are being asked to adopt it anyway.
[C5.4] Then remember who pays. PRO conceded the presumption binds the defense equally, and offered a discretionary, capped, routinely-denied fund as the answer. The state has staff translators and labs. It will not notice this rule.
[C5.5] The public defender with nine terabytes and no expert money will.
[C5.6] Exclusion is not neutral. Vote CON.
