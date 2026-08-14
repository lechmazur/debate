# Debate prop_0679__grok-4.6-high__deepseek-v4-pro-0813-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: grok-4.6-high
- model_con: deepseek-v4-pro-0813-high
- side_swap: True

## Turn 1: PRO Opening

- model: grok-4.6-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Criminal trials decide whether a person loses years of liberty. That is why we exclude unreliable evidence even when it looks polished. AI-generated summaries, translations, and reconstructions should be out unless a human expert independently verifies them.
[P1.2] The danger is not that machines are never useful. It is that they fail invisibly. A model can invent a phrase that never appeared in a recording. It can turn a witness’s hedging into a clean admission.
[P1.3] It can reconstruct a face, a room, or a sequence of events that never existed, rendered with cinematic certainty. Those errors do not announce themselves. They arrive looking like documents, official translations, or video.
[P1.4] A human expert who independently checks the output changes what the jury is seeing. Someone can say what was compared to the original, what was discarded, and where the machine guessed. That person can be cross-examined. The model cannot.
[P1.5] Without that foundation, the court is asked to trust a black box whose prompts, training data, and error patterns are unknown in the courtroom.
[P1.6] Evidence law already works this way. We do not admit raw hearsay because it sounded plausible. We do not admit a novel technique because a vendor called it accurate. We require a foundation first.
[P1.7] A presumption of inadmissibility is that foundation. It is not a ban on using AI in investigation, discovery, or a witness’s own notes. It is a ban on handing the jury an unverified machine product and calling it evidence.
[P1.8] The other rule invites polished error. Prosecution and defense would race to the most fluent reconstruction. The poorer party would lose not on facts, but on generation quality. Jurors would confuse fluency with truth.
[P1.9] Reliability cannot be an afterthought when the state seeks a conviction. Presumption first. Human verification second. Admission only then.

## Turn 2: CON Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.2]
- missing_claim_id_refs: (none)

[C1.1] PRO is defending a categorical rule for a problem that is not categorical. AI-generated evidence ranges from a machine-translated chat log to a probabilistic reconstruction of a shooting scene. Lumping them together forces courts to exclude an entire class unless one particular kind of witness has independently re-created the result, even before the opponent shows any actual error. That is not how reliability works.
[C1.2] Authentication, source data, error testing, cross-examination, and opposing experts can expose the exact failures PRO fears without excluding accurate and probative output.
[C1.3] PRO assumes AI fails invisibly while human verification makes failure visible. But human experts miss errors too, and “independent verification” can be a rubber stamp: someone reads a clean AI summary, agrees it mostly matches, and signs it. The jury still sees a polished product; now another human simply vouches for it. Verification is a process, not a guarantee.
[C1.4] A rule that excludes good evidence for that weak safeguard is overkill.
[C1.5] The rule also hits where AI is most useful: volume and speed. If thousands of foreign-language calls or messages are involved, requiring independent human verification of every translation or summary can delay trials indefinitely or make evidence disappear, even though the underlying recordings or files are available to both sides. The opponent can play the audio, hire an expert, or show where the machine guessed. That is a stronger check than a blanket precondition.
[C1.6] PRO’s core example in [P1.2]—a model inventing a phrase—is a reason to exclude that exhibit or admit it with a cautionary instruction. It is not a reason to presume every AI output inadmissible. Existing rules already require foundation, relevance, and probative value. The motion replaces inquiry with exclusion.
[C1.7] The better rule is: require the proponent to show what the system did, what it was generated from, and give the opponent a real chance to challenge it. That prevents polished error without sacrificing reliable evidence.

## Turn 3: PRO Rebuttal 1

- model: grok-4.6-high
- raw_words: 321
- clipped_words: 321
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10], [P2.11]
- cited_claim_ids: [C1.1], [C1.2], [C1.7], [C1.3], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The opponent calls the rule categorical overkill. The category is the shared defect, not the file type. A machine translation and a scene reconstruction look different. Both arrive as fluent artifacts the model invented, and neither can be asked where it guessed.
[P2.2] [C1.1] treats that lumping as a vice. It is the point. The risk is the same: the jury is asked to treat generated text or imagery as if it were the event.
[P2.3] [C1.2] and [C1.7] say authentication and opposing experts can expose failure. Those tools work on a recording. They fail on the generation. Playing the original audio does not tell jurors whether the admitted English paragraph invented a confession.
[P2.4] After the polished version is already in, hunting for the fiction is the proponent's job, done too late.
[P2.5] [C1.3] calls verification a rubber stamp. Independent verification is comparison to the source, not a signature on a tidy printout. A stamp that never compared fails the rule. A person who compared can be cross-examined on the comparison.
[P2.6] Human fallibility does not justify skipping the only witness who can be questioned.
[P2.7] [C1.5] warns volume will make evidence disappear. The recordings do not disappear. What disappears is the shortcut of handing the jury unchecked machine pages. Verify the messages that matter.
[P2.8] Delay from that work is not a reason to admit an unverified product as if it were a certified translation.
[P2.9] [C1.6] says a fabricated phrase is a reason to exclude that exhibit, not a class. That assumes the error is found. The presumption exists because fabrication will not announce itself. Existing inquiry catches obvious mistakes.
[P2.10] It is weaker against error that looks official. Waiting for the opponent to show "actual error," as [C1.1] demands, puts the burden on the party least able to see inside the box.
[P2.11] They would admit first and hope the other side finds the fiction. The motion requires a person who checked before the jury sees it.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 283
- clipped_words: 283
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [P2.3], [P2.7], [P2.10]
- missing_claim_id_refs: (none)

[C2.1] [P2.1]’s unifying defect is not distinctive to AI. A human translator can smooth a witness’s hedging into a clean admission; a human analyst can make ambiguous imagery look decisive. We handle those risks by testing against source data and opposing expertise. PRO still has not shown why AI output as a class cannot be tested that way.
[C2.2] [P2.3]’s “the model cannot take the stand” argument proves too much. Courts do not require a mass spectrometer or DNA software to testify; they require a live witness who can explain the source, method, and limits, plus an opponent who can cross-examine and offer a competing expert. The same can be done here.
[C2.3] Independent human verification is a thinner safeguard than the motion assumes. A verifier can miss the one invented phrase in a long call or sign off on a fluent summary because it mostly matches. When the underlying recording or source data exists, the stronger check is disclosure and adversarial testing: play the audio, compare the disputed passage, show the divergence.
[C2.4] The volume problem directly undercuts [P2.7]. With 20,000 intercepted calls, the unverified AI summary is often how the parties find the ten that matter. PRO says verify the messages that matter. But they only know they matter because the unverified machine flagged them.
[C2.5] The rule would exclude the very tool that makes review possible.
[C2.6] Nor is the opponent the helpless party [P2.10] imagines. The proponent still bears the burden of authenticating the underlying data and the process. The opponent can demand the source, cross-examine the proponent’s witness, and present contrary evidence. That is not admit-first-and-hope; it is a case-specific reliability inquiry.
[C2.7] The categorical presumption abandons that inquiry in favor of a costly ritual.

## Turn 5: PRO Pressure Questions

- model: grok-4.6-high
- raw_words: 60
- clipped_words: 60
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: If a juror cannot understand the source language, how does “play the audio” [C2.3] tell them the admitted English summary invented a confession?
[P3.2] Q2: When [C2.4] says parties only know the ten calls that matter because the unverified machine flagged them, is that a claim about investigation, or a demand that the unchecked summary itself go to the jury?

## Turn 6: CON Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.7], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: If unverified AI is too dangerous for a jury, why is it safe enough for arrests, warrants, charges, or plea leverage before any independent verification? Your own [P1.7] allows investigation use, so what protects the defendant at those earlier liberty losses?
[C3.2] Q2: For a reconstruction with no pre-existing original, what does “comparison to the source” [P2.5] mean? If the expert reviews only the same uncertain inputs and methodology, how does that verify the output rather than merely the procedure?

## Turn 7: PRO Rebuttal 2

- model: grok-4.6-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [P1.7], [C2.4], [C2.2], [C2.3]
- missing_claim_id_refs: (none)

[P4.1] A1: Investigation finds leads; trial finds facts. A warrant asks a magistrate for probable cause, not a jury for proof beyond a reasonable doubt. [P1.7] never called the machine product safe. It called it not evidence.
[P4.2] Affiants and magistrates may use a lead; they do not make an unchecked artifact the official record. If the unverified summary cannot become an exhibit, it loses the plea leverage CON invokes. Using a tool to locate a call is not asking jurors to treat the tool’s English paragraph as the confession.
[P4.3] A2: The source is the raw inputs, not the generated scene. The expert must independently determine what those measurements, photos, and timestamps support, then flag every detail the model added. Reviewing methodology alone is not verification; the reconstruction stays out. If no source can constrain the output, that is a reason to exclude, not to admit the movie.
[P4.4] The same distinction defeats CON’s remaining case. A detective may use an unverified translation to find the tenth call. The jury may not receive that translation as the call. [C2.4] is investigative convenience dressed as a trial right.
[P4.5] [C2.2]’s spectrometer witness can explain a measured process. A generative model’s sponsor cannot identify an invented phrase unless someone already compared output to source. A rubber-stamp verifier fails that test. A verifier who compared can be asked which sentence was guessed.
[P4.6] [C2.3] says play the audio and show the divergence. That assumes a juror who can hear it. CON still has not explained how a monolingual jury tests an English invention against foreign speech. After admission, the inquiry is an argument about a black box the jury has already seen.
[P4.7] The presumption forces the only check that can make the guess visible before fluency becomes the event.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [C2.3], [P4.4], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: The monolingual juror does not need to decode the source language alone. [C2.3]’s “play the audio” was shorthand for adversarial testing, not an instruction to the jury to translate. The juror can compare length, tone, timing, names, and visible reaction; more importantly, opposing counsel can call a human translator or expert to identify the invented phrase and cross-examine the proponent’s witness about it. If the proponent has not disclosed the source and process, the court can exclude that exhibit under ordinary foundation.
[C4.2] The safeguard is cross-examination and competing expertise, not juror fluency.
[C4.3] A2: It is an investigative claim, but it still damages the categorical rule. PRO already concedes in [P4.4] that the unverified machine can locate the tenth call. We are not demanding that unchecked summary go to the jury; we are saying the parties can then verify the few calls that matter before admission. That is the kind of targeted, case-specific check a blanket presumption abolishes.
[C4.4] That distinction is the weak point. [P4.1] says unverified AI can fuel warrants, charges, and pleas yet not become evidence. But a warrant can justify arrest and detention; plea leverage can coerce a disposition. If the output is too dangerous for a jury, it is too dangerous to shape those earlier liberty losses without verification.
[C4.5] PRO’s own carve-out admits the reliability problem is not solved, just moved to proceedings with fewer adversarial safeguards. The motion therefore does not target actual trustworthiness; it targets the moment of presentation. The better rule still wins: require source disclosure, authentication, process explanation, and genuine opportunity to challenge, then exclude particular outputs shown unreliable. That meets the fear of polished error without making human verification a mandatory precondition that every translation, summary, and reconstruction must satisfy no matter how well tested.

## Turn 9: PRO Closing

- model: grok-4.6-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.1], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] The case turns on timing. An invented confession does not look invented. Once the jury has read it as the call, later argument is an attempt to unsay a document.
[P5.2] CON’s safeguard is a human translator who can identify the invented phrase [C4.1]. That is the expert the motion requires. The only dispute is whether that person compares output to source before admission, or after the jury has already absorbed the fluent version.
[P5.3] After is too late. A monolingual jury cannot hear the fiction in the original. Competing expertise after admission is a fight over a polished artifact already treated as the event. The presumption exists so the comparison happens first, and so someone who actually checked can be asked which sentence was guessed.
[P5.4] Even CON would verify the few exhibits that count before the jury sees them [C4.3]. The presumption is that sequence as a rule, not a hope the opponent later unsays a polished page.
[P5.5] Jurors should decide facts, not generation quality. Keep the machine product out until a human has independently made the guess visible—the only moment the court can still refuse to let fluency become the event.

## Turn 10: CON Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 169
- clipped_words: 169
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] One reason decides this debate: the motion measures where a machine product is shown, not whether it is trustworthy. PRO concedes unverified AI may locate the crucial calls, support warrants, and shape charges before any human expert has compared it to a source. But liberty is lost at those stages too. A warrant can justify detention; an unverified machine-flagged confession can coerce a plea.
[C5.2] If the output is too dangerous for a jury, it is too dangerous there. If it is acceptable there with disclosure and adversarial testing, then it can be acceptable at trial under the same case-specific scrutiny. PRO’s closing recasts that tension as mere timing: expert before admission.
[C5.3] But the expert it invokes is the ordinary safeguard—a translator who compares source and output and can identify a guessed phrase. That check should be available, not a mandatory precondition for every summary. A categorical rule does not stop polished error; it moves unverified AI into earlier, less adversarial decisions while burdening reliable evidence. The better rule wins.
