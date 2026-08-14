# Debate prop_0679__deepseek-v4-pro-0813-high__grok-4.6-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: deepseek-v4-pro-0813-high
- model_con: grok-4.6-high
- side_swap: False

## Turn 1: PRO Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 260
- clipped_words: 260
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Criminal trials cannot run on plausible guesses. The state may deprive someone of liberty only on evidence whose source can be questioned, whose method can be explained, and whose errors can be exposed. AI-generated summaries, translations, and reconstructions are none of those things until a human expert independently verifies them. That is why they should be presumptively inadmissible.
[P1.2] A translation model does not know what a speaker meant; it predicts words. In high-stakes language—negation, consent, threats, dialect, tone—one wrong prediction flips meaning. “He said he didn’t take the bag” and “he said he’d take the bag” are separated by a syllable, but they are opposite facts. The model cannot be cross-examined about why it chose that reading. A human translator can.
[P1.3] Summaries are dangerous because they delete. Witness interviews, police narratives, and forensic records contain exculpatory details, hesitation, contradictions, and context. A summary optimized for brevity may erase precisely the detail the defense needs. There is no declarant to ask what was omitted or why.
[P1.4] Reconstructions are worse: generative models fill gaps with detail that looks real but was never observed. That turns speculation into visual or textual confidence, and juries trust completeness. The more vivid the output, the harder it is to treat it as a mere guess.
[P1.5] Presumptive inadmissibility is not a ban. It simply puts the burden on the party offering the output to place a responsible, cross-examinable human expert between the algorithm and the verdict. That is a modest safeguard measured against a catastrophic failure mode: conviction based on machine output no one can truly challenge.

## Turn 2: CON Opening

- model: grok-4.6-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Criminal courts do not exclude evidence because a tool is new. They exclude it when it cannot be authenticated, when it is hearsay without an exception, or when prejudice swamps its value. AI summaries, translations, and reconstructions should face those same tests, not a special presumption of unreliability.
[C1.2] A detective’s hurried notes of a three-hour interview come in once the officer takes the stand. A machine transcript of the same recording is more complete, searchable, and checkable against the audio. Barring that transcript until an independent expert blesses every line treats the better record as the more dangerous one. That inversion is the proposition’s core mistake.
[C1.3] Humans already do what the other side fears. Interpreters drop a negative. Detectives omit the hesitation that later matters. Reconstruction artists fill unseen gaps with theory.
[C1.4] The difference is not that people can be cross-examined and models cannot. The proponent still must show what system was used, what went in, what settings applied, and what audit trail exists. The other side can play the original tape, sample the translation, call its own linguist, or attack the method. That is how courts already handle software-scored DNA, GPS tracks, and financial reconstructions.
[C1.5] A presumption of inadmissibility is not a modest safeguard. It is a default ban that taxes whoever needs the evidence—often a defendant drowning in bodycam, intercepts, or foreign-language discovery. “Independently verified by a human expert” sounds careful until you ask what it requires: full retranslation of every intercept? Recreating a crash by hand? The phrase invites a fight about the gatekeeper instead of the facts, and well-funded offices will clear that gate more easily than indigent defendants.
[C1.6] Reliability, not a human signature, is the right standard. If an output can be checked against source material, challenged on method, and weighed with ordinary caution, it should come in on the same terms as every other tool. The real catastrophic failure is excluding the record while admitting the officer’s memory of it.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 274
- clipped_words: 274
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.4], [C1.3], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The transcript argument is the opponent’s strongest move, but it cuts against them. A transcript is only safe because a human can compare it with the audio. Where comparison is simple, verification is cheap, and the presumption costs little. The cases that matter—ambiguous dialect, a summary deleting exculpatory context, a reconstruction inventing unseen detail—have no such easy audit.
[P2.2] The original meaning is exactly what is disputed, and an “audit trail” will not show why a word was rendered as consent rather than resistance.
[P2.3] That answers [C1.4]. Courts admit DNA or GPS output because those tools have known error rates and deterministic behavior. A generative language model is not that. It yields statistically fluent output that can be confidently wrong, and can shift with model version or sampling.
[P2.4] Cross-examining “the method” supplies a vendor’s architecture, not the reason a contested sentence came out as guilt.
[P2.5] On [C1.3]: yes, humans err. That is not a reason to import a new error source that cannot be confronted. We handle human error by putting the human on the stand. The remedy for a bad officer note is cross-examination.
[P2.6] The remedy for a bad AI translation cannot be cross-examining the model; it is cross-examining the expert who verified it. That is exactly what the presumption forces.
[P2.7] Finally, [C1.5] overstates the tax. The rule does not ban useful output; it requires a responsible human between the machine and the verdict. If output is truly checkable, that check is fast. If retranslating every intercept is expensive, that cost reflects the gravity of using machine-generated meaning to take liberty.
[P2.8] And [C1.6] is circular: reliability is precisely what an unverified model cannot demonstrate.

## Turn 4: CON Rebuttal 1

- model: grok-4.6-high
- raw_words: 310
- clipped_words: 310
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] The other side now admits the easy case. Where the source remains, they say verification is cheap and the presumption “costs little.” That wrecks their rule. If comparison is cheap, ordinary authentication already requires it: play the tape, mark the line, let the jury hear both. A presumption is not that check.
[C2.2] It is a default exclusion that must be lifted before the comparison even starts. They say the cases that matter have no easy audit. The presumption still fails: it excludes the checkable mass to catch that fringe, while speculation rules already bar a reconstruction with no measurements.
[C2.3] They retreat to dialect, omitted context, and invented detail, insisting an audit trail cannot explain why a model chose “consent” over “resistance.” A human interpreter cannot reconstruct that inner choice either. We still admit the rendering, play the original, and call a competing expert if meaning is truly disputed. That is confrontation. An independent verifier first does not decide the word; it only sells a ticket to the same fight.
[C2.4] Their DNA contrast overreaches. Courts do not require every software step to be deterministic. They require inputs, a testable method, and a chance to attack the output. Model drift is impeachment material: change the setting, show the shift.
[C2.5] The source, not the architecture, is the point. A deleted detail is exposed by the original file; invented debris, by the measurements. Those are ordinary attacks, not a reason to exclude first.
[C2.6] A blessing expert is one remedy, not the only one. The proponent’s witness, the recording, and a defense linguist already put a human on the stand. The presumption turns that optional contest into a mandatory gate. If the check is fast, existing rules capture it.
[C2.7] If redoing every intercept is costly, the gate rations justice by budget. Reliability is comparison and challenge, not a prior human signature redefined as reliability itself.

## Turn 5: PRO Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 89
- clipped_words: 89
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say “play the tape, mark the line, let the jury hear both.” For a foreign-language recording, how does the jury compare the AI translation to the original without itself relying on another human translation—turning your cheap check into the very verification gate you call optional?
[P3.2] Q2: You say omitted detail is “exposed by the original file.” When the source is hundreds of hours or thousands of pages, who in court actually performs that comparison before the AI summary fixes the jury’s view of what the source says?

## Turn 6: CON Pressure Questions

- model: grok-4.6-high
- raw_words: 69
- clipped_words: 69
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: If a certified interpreter reviews the AI translation against the recording, testifies, and is cross-examined, is that still insufficient? What extra “independence” does your presumption require that ordinary confrontation does not?
[C3.2] Q2: You said where comparison is simple the presumption “costs little” [P2.1]. Why then default-exclude the checkable translation instead of playing the tape and letting competing linguists contest the word, as courts already do with human interpreters?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C3.1], [P2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: If a certified interpreter reviews the AI translation against the recording, testifies, and is cross-examined, that is sufficient. That is not a gap in the presumption; it is the presumption satisfied. The “independence” required is not some extra layer beyond ordinary confrontation. It means the rendering offered to the jury is no longer the model’s unexplained prediction but an accountable human expert’s judgment after checking the source.
[P4.2] Once that witness is on the stand, the output comes in. So [C3.1] does not refute the rule—it describes the rule’s central gate.
[P4.3] A2: Because for a foreign-language recording the jury cannot “play the tape” and know what it means. The comparison the opponent imagines requires another human translation—the very verification they call optional. A human interpreter is admissible because the interpreter is the witness; a raw AI translation has no witness. Letting competing linguists contest the word after admission means the unverified output has already been placed before the jury as evidence.
[P4.4] Presumptive exclusion only moves the certified review before that exposure. Where [P2.1] says comparison is simple, that gate is quick and low-cost.
[P4.5] The opponent’s alternatives keep assuming the safeguard. Their certified interpreter, their competing linguist, their comparison against the original all require a responsible human taking an interpretive position under oath. The real disagreement is timing: should the jury first see the raw machine output and then hear it attacked, or first receive a human-verified rendering? The risk is not symmetrical.
[P4.6] A jury that hears a fluent machine translation or a clean summary first anchors on it. A later defense linguist must then do double work: offer a different reading and undo the false certainty the machine already created. The presumption avoids that order of proof without banning the evidence.

## Turn 8: CON Rebuttal 2

- model: grok-4.6-high
- raw_words: 305
- clipped_words: 305
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: The jury never becomes bilingual—not with AI, and not with a human interpreter. Comparison already works by playing the clip, putting a sponsoring linguist on the stand, and letting a competing expert mark the disputed syllable. That is ordinary confrontation, not the proposition’s default ban. The cheap check is a preserved source, not twelve laypeople decoding dialect.
[C4.2] Needing a human to explain foreign speech does not turn authentication into presumptive exclusion. Courts already live with that dependence on experts. It is not a reason to start from exclusion.
[C4.3] A2: The same people who already do it: counsel, the offering witness, and a defense expert—just as when a detective summarizes a week of bodycam. No trial audits every hour before any narrative reaches the jury. Volume is why summaries exist. An omitted line is proved from the original file.
[C4.4] The summary does not erase the source; it is impeachable the moment the page is produced.
[C4.5] Those answers end the clash. They now concede a testifying interpreter who checked the source is enough [P4.1]. That is a sponsoring witness, not a special presumption. Authentication already keeps a naked, unsponsored printout out.
[C4.6] Their rule still default-excludes until a motion lifts the ban, so the complete machine transcript stays out while the officer’s memory of the same call comes in.
[C4.7] They recast the remaining fight as timing: hide the output so the jury cannot “anchor.” But a detective’s fluent recap already anchors. A human interpreter’s confident reading already anchors. We do not default-exclude those first impressions. Anchoring is cured by playing the source and calling a rival expert, not by rationing the better record behind a gate the well-funded party clears first.
[C4.8] Reliability is still comparison and challenge—not a prior human signature that only delays the same fight and prices the poorer party out of the complete record.

## Turn 9: PRO Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.5], [P4.1]
- missing_claim_id_refs: (none)

[P5.1] CON has already conceded the dispositive point: authentication keeps a naked, unsponsored AI printout out [C4.5], and a testifying interpreter who checked the source is enough [P4.1]. That is not a different standard; it is the presumption satisfied. The rule never bans the output. It requires one cross-examinable human to take responsibility before the jury receives machine-generated meaning.
[P5.2] So the only live dispute is order of proof. CON would admit first and let a rival expert attack afterward. But a foreign-language recording does not interpret itself, and a thousand-page record does not expose its own omissions. The later attack requires another human translation or search—the verification CON calls optional—arriving only after the jury has anchored on the fluent machine version.
[P5.3] Once that false certainty lands, the defense must do double work: undo the machine’s confidence, then substitute its own reading.
[P5.4] Flipping the order is cheap where the output is checkable; where it is costly, the cost reflects the stakes of letting an unexplained model supply evidence for liberty. The reason to decide for PRO is not distrust of algorithms. It is that criminal proof must enter through a human who can be questioned, and no unverified AI output has one.

## Turn 10: CON Closing

- model: grok-4.6-high
- raw_words: 181
- clipped_words: 181
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The other side has already described ordinary authentication and called it a presumption. A human who checked the source and takes the stand is enough. Courts already keep an unsponsored printout out. So the only work left for their rule is exclusion first—hide the output so the jury cannot hear the fluent version before a rival attacks it.
[C5.2] That is not a reliability standard. Juries already hear first a detective's recap of the same interview and a human interpreter's first reading of the same tape. Those impressions also anchor. We still admit them, play the source, and let another expert contest the word.
[C5.3] We do not default-exclude because a first account sounds complete.
[C5.4] Once the source can be compared and a human can be questioned, the output is already testable. No special presumption is required to reach that fight. Their rule adds no confrontation. It only holds the better record behind a gate while the officer's memory of the same call comes in, and the poorer party waits longest.
[C5.5] Reliability is comparison and challenge. That inversion is why the proposition fails.
