# Debate prop_0679__claude-fable-5-high__mimo-v2.5-pro__s0__tpl_placement_active_20260320f

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: claude-fable-5-high
- model_con: mimo-v2.5-pro
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A man's liberty should never hinge on output no one can cross-examine. That single principle decides this debate.
[P1.2] Start with what the motion actually demands. It is not a ban. It is a presumption: AI summaries, translations, and reconstructions enter the courtroom only after a qualified human has checked them. This mirrors how evidence law already works.
[P1.3] Lab results require an analyst who can testify. Foreign-language documents require a certified translator. Photographs require authentication. The motion simply refuses to carve out an exception for the one category of evidence that is most fluent, most persuasive-looking, and least accountable.
[P1.4] Why does AI evidence deserve this gate? Three reasons. First, error without warning. Large models hallucinate confidently — they invent quotes, smooth over ambiguities, and translate idioms in ways that flip meaning.
[P1.5] A summary that converts "he said he didn't do it" into "he admitted involvement" looks identical in polish to an accurate one. There is no smell test a jury can apply. Second, confrontation. The Sixth Amendment tradition rests on the right to confront one's accuser.
[P1.6] You cannot cross-examine a model. You cannot ask it why it reconstructed a blurry license plate as one number rather than another. A human verifier restores the witness the Constitution presumes. Third, asymmetric stakes.
[P1.7] In civil disputes, errors cost money; in criminal trials, they cost years of a life. When the downside is wrongful conviction, the default must be caution, and the burden must sit on the party offering the machine's word.
[P1.8] Notice what the presumption preserves: every genuine efficiency of AI. Police can still triage thousands of hours of footage; prosecutors can still draft with machine translation. The tool stays. Only the untested output is kept from the jury box.
[P1.9] So the question for the opposition is simple: name the principle under which unverified, uncross-examinable, error-prone output should reach a criminal jury faster than a lab report or a human translator ever could.

## Turn 2: CON Opening

- model: mimo-v2.5-pro
- raw_words: 324
- clipped_words: 324
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The PRO asks me to name a principle under which unverified AI output should reach a jury faster than a lab report. Here's one: evidence rules already gate reliability, and this motion piles a uniquely burdensome presumption on top of them.
[C1.2] The motion doesn't say AI evidence must meet authentication—it already must. It doesn't say judges must assess reliability—they already do under rules like Federal Rule 901 or *Daubert*. It says something far more extreme: AI evidence is *presumptively inadmissible* unless an independent human expert verifies it. No other category of evidence faces this default.
[C1.3] The PRO's own analogies betray the case. Lab results require an analyst to testify—but that's the analyst who ran the test, not a second independent scientist who reproduced the results before they're presumptively admissible. Translations require a translator—but the translator authenticates their own work; no second translator is required. The motion doesn't extend existing conventions to AI.
[C1.4] It invents a harsher standard that exists nowhere in evidence law.
[C1.5] The scope is wildly overbroad. A blanket presumption sweeps in everything from a simple Spanish-to-English text translation to a complex facial reconstruction from degraded video—treated identically. A department using machine translation to render a Tagalog voicemail would need an independent expert before that output is even presumptively admissible. That's not caution; it's obstruction.
[C1.6] And the cost falls hardest where resources are thinnest. Expert verification is expensive and slow. Under-resourced public defenders and rural prosecutors face the same bottleneck. The motion creates a two-tier system: wealthy jurisdictions access the tool; poorer ones are locked out.
[C1.7] Defendants lose access to potentially exculpatory AI-assisted analysis too.
[C1.8] The confrontation argument proves too much. You don't cross-examine a breathalyzer—you cross-examine the officer who operated it. AI output is authenticated by the person who deployed it and can testify to the process.
[C1.9] Existing rules already handle this. The motion doesn't fix a gap in evidence law—it singles out a technology for exclusion that no comparable tool faces.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.4], [C1.8], [C1.9], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] Every one of CON's analogies smuggles in the very thing AI lacks: a human author. The lab analyst testifies because she *performed the analysis* and can explain her choices. The translator authenticates his own work because he *made* the translation and can defend it under oath. Who occupies that seat for an AI summary?
[P2.2] Nobody. The motion doesn't invent a "harsher standard" [C1.4] — it supplies the accountable human that every other evidence category has built in by definition. CON's complaint amounts to: AI should be the first form of evidence in history with no author who can answer for it.
[P2.3] The breathalyzer comparison [C1.8] fails on its own terms. A breathalyzer is a calibrated, deterministic instrument with validated error rates; the officer can testify to maintenance and protocol, and that testimony actually speaks to reliability. An officer who pasted a transcript into a language model can testify to nothing relevant. He cannot explain why the model rendered an ambiguous phrase as a confession, because the model's reasoning is opaque even to its makers.
[P2.4] Operating a black box is not authenticating it.
[P2.5] "Existing rules handle this" [C1.9] is CON's load-bearing claim, and it's wrong about what those rules test. Rule 901 authentication asks whether evidence is what it purports to be — a low bar a flawless-looking but wrong summary clears easily. And when a Daubert challenge does happen, what does it require? A qualified human evaluating reliability.
[P2.6] The motion simply makes that check the default rather than a lottery dependent on whether an overworked defender thinks to demand it.
[P2.7] On overbreadth [C1.5]: verification scales naturally. A bilingual officer confirms a routine voicemail translation in minutes; only complex reconstructions need more. That's proportionate, not obstruction. And the cost argument [C1.6] inverts the stakes: the genuinely two-tier system is one where defendants facing polished, unchecked machine output have no realistic way to expose its errors.
[P2.8] A modest verification cost against years of wrongful imprisonment isn't a close call.

## Turn 4: CON Rebuttal 1

- model: mimo-v2.5-pro
- raw_words: 285
- clipped_words: 285
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.7], [P2.8]
- missing_claim_id_refs: (none)

[C2.1] The PRO's central move—AI has no "human author"—confuses two questions. Can you explain a tool's internal mechanism, and can you be cross-examined about how you used it? Digital forensic tools, algorithm-driven instruments—all involve code the operator didn't write and can't fully explain. Yet no presumption of inadmissibility applies.
[C2.2] We cross-examine the operator on inputs, methodology, and validation. That seat is occupied.
[C2.3] A detective summarizing wiretap audio with AI chose the inputs, reviewed the output, and decided to present it. Cross-examination probes: Did you compare the summary to the original? Did you spot-check sections? What anomalies did you notice?
[C2.4] That testimony is no less meaningful than a forensics examiner explaining her extraction methodology. The PRO demands a transparency standard no forensic instrument meets—then uses that impossible bar to justify blanket exclusion.
[C2.5] The scaling concession [P2.7] collapses the blanket presumption. If a bilingual officer verifies a voicemail translation in minutes, existing authentication already handles routine AI uses. The motion sweeps in every AI-assisted output, requiring "independent expert" verification the PRO just admitted isn't always necessary. That's the overbreadth the PRO tried to wave away.
[C2.6] Defendants face the same bottleneck. Using AI to reconstruct alternative timelines or translate exculpatory recordings would require the same expert verification. The presumption doesn't protect defendants—it locks out the parties most vulnerable to prosecutorial resource disparities.
[C2.7] The PRO's closing appeal to "years of wrongful imprisonment" [P2.8] misdirects. The question isn't whether verification has value—it's whether a blanket presumption of inadmissibility is the right mechanism when case-by-case judicial discretion already exists. Eyewitnesses err at shocking rates, forensic hair analysis has produced documented wrongful convictions, and false confessions are routine—none carry this presumption. The motion doesn't correct a gap in evidence law.
[C2.8] It invents one.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-high
- raw_words: 104
- clipped_words: 104
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C1.5], [C2.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your detective only gives meaningful testimony if he "compared the summary to the original" and "spot-checked sections" [C2.3] — but that comparison *is* human verification. So what unchecked AI output do you actually defend admitting, other than cases where nobody performed the check you just described?
[P3.2] Q2: When the officer who ran a Tagalog voicemail through machine translation speaks no Tagalog [C1.5], what could cross-examining him about "inputs and methodology" [C2.2] possibly reveal about whether the translation flipped a denial into a confession — and if the answer is nothing, who in your system answers for that error before the jury hears it?

## Turn 6: CON Pressure Questions

- model: mimo-v2.5-pro
- raw_words: 168
- clipped_words: 140
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.7]
- missing_claim_id_refs: (none)

[C3.1] Q1: Every forensic tool the PRO accepts—breathalyzers, digital extraction software, algorithm-driven instruments—contains code or chemistry the operator cannot fully explain. The PRO says those are different because they're "calibrated" with "validated error rates" [P2.3], but AI models also have measurable performance benchmarks on specific tasks. What principled evidence-law distinction separates "I can't explain the spectrometer's internal chemistry but I can testify to how I used it" from "I can't explain the language model's reasoning but I can testify to how I used it" — other than the PRO's conclusion that one should be admitted and the other excluded?
[C3.2] Q2: You conceded that verification "scales naturally" and a bilingual officer can confirm a routine voicemail translation in minutes [P2.7]. If routine AI verification is that quick and proportionate, why is a blanket presumption of inadmissibility necessary rather than existing case-by-case [clipped]

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C3.1], [C2.3]
- missing_claim_id_refs: (none)

[P4.1] A1: The principled distinction is what the validation attaches to. A spectrometer is validated for the exact, narrow task it performs, every time, under known conditions — its error rate travels with each individual measurement. A language model's "benchmarks" [C3.1] are aggregate averages across test sets that say nothing about whether *this* output on *this* recording is right. The spectrometer fails loudly and within bounds; the model fails silently and without limit — it doesn't mismeasure a quantity, it invents content that never existed.
[P4.2] The operator of a calibrated instrument testifies to conditions that actually constrain the result. The operator of a generative model testifies to conditions that constrain nothing. That's not my conclusion smuggled in; it's the difference between a measurement and an authorship — and evidence law has always demanded an author.
[P4.3] A2: Because a quick check and a guaranteed check are not the same thing, and only a presumption guarantees it. The bilingual officer confirming a voicemail in minutes *is* the verification the motion requires — the presumption is satisfied at trivial cost. What case-by-case discretion gives you instead is a lottery: the check happens if a judge is alert and a defender has the time and budget to demand it. Defaults decide outcomes precisely for the defendants least able to litigate admissibility fights.
[P4.4] Now watch what CON has conceded across this debate. The detective's testimony is meaningful only because he "compared the summary to the original" and "spot-checked sections" [C2.3] — that comparison *is* human verification. Routine verification takes minutes [C3.2's own framing]. So CON agrees the check should happen and agrees it's cheap.
[P4.5] The only remaining dispute is whether it's mandatory before a jury hears the output, or optional and unevenly enforced. CON never answered my Tagalog question: when the operator speaks no Tagalog, nobody in their system answers for a flipped confession. A rule that costs minutes where CON's system works, and catches errors where it doesn't, wins this debate.

## Turn 8: CON Rebuttal 2

- model: mimo-v2.5-pro
- raw_words: 337
- clipped_words: 337
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: The detective who compared the summary to the original and spot-checked sections was doing what authentication under existing rules demands — the operator reviewing his own work, not a second independent expert. That's the same standard every forensic tool meets. PRO's spectrometer analogy [P4.1] actually proves my point: we admit spectrometer results based on the operator's testimony about how he used the instrument, not on a second scientist independently reproducing each measurement. The motion demands that second scientist for AI alone.
[C4.2] A2: The officer who speaks no Tagalog is exposed on exactly the cross-examination PRO describes: he relied on a tool he couldn't evaluate, and a jury can weigh that. But a judge already has discretion to demand more before admitting that output. The Tagalog scenario justifies robust case-by-case gatekeeping — not a blanket presumption that treats a Spanish text message identically to a facial reconstruction from degraded video.
[C4.3] This is why CON wins overall. PRO's strongest examples — the Tagalog voicemail, the opaque model — are precisely the cases where existing judicial discretion already empowers judges to demand verification before admitting AI output. The motion adds nothing there except mandatory exclusion absent expert sign-off.
[C4.4] But where AI use is straightforward — a bilingual officer confirming a translation in minutes, a detective spot-checking a summary against the original — the motion still imposes its presumption, its cost, its delay.
[C4.5] PRO says I've conceded verification is cheap and should happen [P4.4]. Precisely: it already happens under existing authentication and *Daubert* frameworks, and where it doesn't, judicial discretion corrects for it. The blanket presumption is either redundant in easy cases or destructive in hard ones. It locks out defendants from exculpatory AI analysis, burdens poor jurisdictions with expert fees, and treats all AI output identically regardless of actual risk.
[C4.6] That isn't caution — it serves the resource-rich while denying access to everyone else.
[C4.7] The motion doesn't fill a gap in evidence law. It creates costs where existing rules already work and ignores the case-by-case nuance that justice demands.

## Turn 9: PRO Closing

- model: claude-fable-5-high
- raw_words: 199
- clipped_words: 199
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.2], [C4.4]
- missing_claim_id_refs: (none)

[P5.1] Strip away everything else and one disagreement remains: CON agrees the human check should happen and agrees it's cheap, but insists it stay optional. That choice loses them this debate, and the Tagalog voicemail shows why.
[P5.2] CON's final answer to my hardest question [C4.2] was that the non-Tagalog-speaking officer is "exposed on cross-examination" and "a jury can weigh that." Read that carefully. It means the flipped confession *reaches the jury*, and the safeguard is hoping twelve laypeople — who also speak no Tagalog — discount a polished, fluent translation they cannot evaluate. That isn't gatekeeping.
[P5.3] That's surrender dressed as discretion.
[P5.4] CON says judges "already" demand verification in hard cases. Sometimes — if the defender knows to object, if the judge understands the technology, if the budget exists for the fight. A presumption replaces that lottery with a guarantee, at a cost CON himself admitted is minutes in routine cases [C4.4]. Redundant where the check happens anyway; decisive where it doesn't.
[P5.5] When evidence can silently invent a confession, the question is never whether errors get caught — it's whether catching them is mandatory or lucky. In a criminal trial, liberty cannot depend on luck. That is why the presumption stands.

## Turn 10: CON Closing

- model: mimo-v2.5-pro
- raw_words: 229
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's case reduces to one claim: mandatory beats optional because optionality is a lottery. That sounds compelling until you realize what the motion's guarantee actually guarantees.
[C5.2] It guarantees that the jurisdiction with one part-time forensic analyst and a backlog of cases cannot use a machine translation that a bilingual officer could confirm in five minutes — until that expert gets to it, if one exists at all. It guarantees that a defendant seeking to reconstruct an alternative timeline from hours of body-camera footage must first retain an independent verification expert, at the same cost barrier that already prevents most indigent defendants from mounting effective forensic challenges.
[C5.3] The presumption doesn't protect the vulnerable. It prices them out.
[C5.4] PRO never answered this. The response was that verification "scales naturally" and "costs minutes" — but only if the verifier exists, has the expertise, and has the time. That's not a guarantee; it's a description of well-resourced courts.
[C5.5] The motion treats a Spanish text message and a facial reconstruction identically. It treats prosecution and defense access identically. It treats jurisdictions with surplus experts and those with none identically. A rule this blunt doesn't replace a lottery with certainty — it replaces a lottery that sometimes fails defendants with a certainty that always locks them out.
[C5.6] That is why this presumption, however well-intentioned, does [clipped]
