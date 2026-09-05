# Debate prop_0679__minimax-m3__glm-5-3-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: minimax-m3
- model_con: glm-5-3-high
- side_swap: True

## Turn 1: PRO Opening

- model: minimax-m3
- raw_words: 328
- clipped_words: 328
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] is narrow, modest, and necessary. It does not ban AI-generated evidence from criminal trials. It establishes a default — admit only after a qualified human expert independently verifies the output. That default is justified by three converging facts about how these systems actually work and what criminal trials actually protect.
[P1.2] First, AI systems produce confident falsehoods as a structural feature, not an occasional glitch. Large language models generate text by predicting plausible next tokens, not by retrieving verified facts. They routinely invent citations, misquote witnesses, mistranslate idioms, and fabricate details that never occurred. A summary of a ten-thousand-page discovery dump produced by such a system is not "evidence" in any meaningful sense — it is a probabilistic gloss that can look authoritative precisely because its failure modes are silent.
[P1.3] A juror reading it has no way to know which sentences are true and which are confabulated.
[P1.4] Second, criminal trials protect something uniquely weighty: liberty, and the asymmetry is decisive. A false positive costs a person years of life, sometimes life itself. A false negative — exclusion of AI output that could have been used — costs the state one investigative tool among many. When error costs are this unequal, evidentiary defaults should tilt toward exclusion of unverified machine output.
[P1.5] Third, current verification regimes are inadequate. AI outputs cannot be cross-examined. No human is accountable for the specific assertion the machine produced. Even the engineers cannot fully explain why a given output emerged.
[P1.6] That opacity violates the foundational requirement that evidence be reproducible, traceable, and challengeable. A human expert who independently verifies the output is the accountable link the system otherwise lacks — not a rubber stamp, but the witness the Constitution's confrontation rights implicitly demand.
[P1.7] Opponents will invoke efficiency — translation backlogs, complex reconstructions, defense tools. The proposition does not deny AI's utility. It simply insists that when a person's freedom hangs in the balance, convenience does not displace verification. The default belongs on the side of caution.

## Turn 2: CON Opening

- model: glm-5-3-high
- raw_words: 337
- clipped_words: 337
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition's seduction is its moderation, and that's exactly where it fails. It doesn't ban AI evidence — it just demands a human expert's blessing first. But presumptions are not neutral; they allocate burden, delay, and cost. And this one would be applied by human beings against a defendant whose liberty is at stake.
[C1.2] Start with the asymmetry my opponent invoked. It cuts the other way. Exclusion is not a costless default. If a defense team uses AI to synthesize a million pages of discovery and find exculpatory material buried in it, the presumption blocks that evidence until the defense can afford — or find — a qualified human willing to certify it.
[C1.3] The state has experts on retainer. The accused often has a public defender. A verification presumption systematically disadvantages whichever party lacks resources, and in criminal court that's usually the defendant. The "caution" my opponent praises is caution that incarcerates.
[C1.4] Second, the premise that human verification solves AI's opacity is a fiction. Handwriting analysis, bite-mark matching, and hair comparison all sailed into courtrooms for decades with confident human experts attached — and we now know some of that testimony was catastrophically wrong. A human signing off on a machine translation adds a fallible layer, not an infallible one. Yet no one proposes presumptive inadmissibility for human forensic specialties with documented error histories.
[C1.5] Singling out AI output for a categorical hurdle, while flawed human testimony gets the existing rules, isn't caution. It's superstition about the new.
[C1.6] Third, existing admissibility standards already test reliability: provenance of the system, error rates, testing, the ability to challenge the output through cross-examination of whoever sponsors it. Those tools work regardless of whether the source is silicon or human memory — and human memory, recall, is far more editable and far less audited than a logged model output.
[C1.7] The right standard is reliability, not origin. A presumption that treats all machine-generated evidence as guilty until proven innocent will exclude accurate evidence, shield bad human judgment, and tax the poor. Reject it.

## Turn 3: PRO Rebuttal 1

- model: minimax-m3
- raw_words: 336
- clipped_words: 336
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] 's case sounds pragmatic until you notice what it actually concedes. Start with the forensic analogy. My opponent says handwriting, bite-mark, and hair analysis sailed into courtrooms with confident human experts attached — and we now know some of that testimony was catastrophically wrong. That is not an argument against verification.
[P2.2] That is a confession that unverified expert blessing failed and required new rules. The proposition is exactly that new rule for a new technology. My opponent inadvertently endorses my position while trying to defeat it.
[P2.3] On asymmetry, the proposition does not change who bears the cost of offering evidence. That is bedrock evidence law, already applied to DNA analysts, forensic accountants, and translators alike. A defendant offering an AI summary verifies it just as a defendant offering any expert output must qualify it. My opponent's framing confuses the synthesis with the evidence itself.
[P2.4] An AI summary of a million pages of discovery is a pointer, not exculpatory material. The underlying documents remain the evidence; the proposition protects defendants from conviction resting on a hallucinated paragraph no human checked, and protects the prosecution from a defense built on a confidently fabricated translation.
[P2.5] The existing-standards argument concedes the hardest point. Daubert and Frye test reliability, but they presuppose a human who can explain methodology, point to inputs, and be cross-examined on reasoning. A large language model does none of that. Cross-examining the sponsoring attorney tests attorney choices, not whether the sentence "the witness said X" was ever spoken.
[P2.6] My opponent's appeal to existing standards is an admission that those standards were built for a world where the source of evidence could be questioned by a human accountable for the specific assertion. AI output is precisely what those standards cannot reach, and pretending otherwise imports silent error into the record.
[P2.7] The proposition is not a ban. It demands only what every other piece of evidence already demands: an accountable human link between the assertion and the record. That is not superstition about the new. That is the floor.

## Turn 4: CON Rebuttal 1

- model: glm-5-3-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.4], [P2.3]
- missing_claim_id_refs: (none)

[C2.1] My opponent calls my forensic examples a confession. Look closer at what they confess. The bite-mark and hair-analysis disasters were not failures of missing human verification — confident human experts *were* the verification. The accountable human link was present at every step, testifying under oath, subject to cross-examination, and the evidence was still catastrophically wrong.
[C2.2] My opponent's proposed cure is literally the thing that failed. And what fixed those fields? Not presumptive exclusion of the underlying science — validation studies, error rates, proficiency testing. Reliability standards, exactly what I proposed.
[C2.3] The "floor" claim collapses on contact with existing practice. Radar guns, breathalyzers, automated fingerprint matching: machine-generated results enter courtrooms daily based on calibration records and validation testing — no human expert re-verifies each individual reading. If the accountability floor my opponent demands were real, that evidence would be inadmissible too. It isn't, because the law long ago accepted that validated instruments plus cross-examination of their operators satisfy reliability.
[C2.4] AI outputs can meet the same test: documented provenance, benchmarked error rates, logged prompts and outputs. Ironically, the machine's output is *more* auditable than the human translator's memory of what she heard.
[C2.5] The "pointer, not evidence" move [P2.4] concedes too much. If AI synthesis is how exculpatory material gets found in a million pages, then human "verification" of that finding means either re-reading the million pages — impossible — or trusting the search — circular. The presumption demands verification that cannot, in principle, be performed.
[C2.6] Finally, [P2.3] claims the presumption changes nothing about burden. A presumption changes everything: it adds delay, cost, and a default of exclusion applied most brutally against the party with the fewest experts — usually the accused. "Verify it yourself" is easy to say with a crime lab on retainer.
[C2.7] My opponent's rule excludes validated machines while grandfathering in unvalidated humans. That is not a floor. It's a hole in it.

## Turn 5: PRO Pressure Questions

- model: minimax-m3
- raw_words: 75
- clipped_words: 75
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your radar-gun analogy assumes deterministic instruments. An LLM produces novel, non-reproducible text each run — no fixed error rate per claim. How does cross-examining a sponsoring attorney validate a sentence no human authored and the system itself cannot defend?
[P3.2] Q2: You say verification "cannot in principle" be performed on a million-page synthesis. If true, isn't that a stronger reason to exclude — not to admit under a reliability standard you concede cannot be tested?

## Turn 6: CON Pressure Questions

- model: glm-5-3-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: You say the forensic scandals justify your rule, but confident human experts *were* the verification there — present, sworn, cross-examined — and the evidence was still wrong. What specifically does your human verifier of AI output do differently that judges reliability better than validation studies and error rates did?
[C3.2] Q2: For an AI translation, what does "independent verification" mean short of a human re-translating the entire text? If full duplication is the only real check, isn't your presumption just a ban wearing a modest label?

## Turn 7: PRO Rebuttal 2

- model: minimax-m3
- raw_words: 342
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The human verifier doesn't need to be infallible. They provide something validation studies and error rates cannot: accountability for the specific assertion. A validation study tells you the system is generally right. It cannot tell you whether this particular sentence is the exception.
[P4.2] The human verifier reads the specific output, checks the specific claims against source material, swears an oath to that specific assertion, and can be cross-examined on it. That is the difference between auditing a class of outputs and vouching for a concrete claim. Radar guns produce readings; LLMs produce novel, non-reproducible text whose errors are silent and content-dependent. The verifier is the missing witness the record demands.
[P4.3] A2: Independent verification does not require duplicating the entire task. A translator certifying a translation reads the disputed passages in both languages and swears to their accuracy. An expert reviewing a summary checks the key claims against source documents. This is exactly what already happens with forensic reports and business record summaries throughout the system.
[P4.4] The "ban wearing a modest label" charge inverts the real burden: the proposition asks who stands behind this specific claim. If the answer is "no one," the evidence hasn't met the floor every other piece already meets. If verification is genuinely impossible, that is a reason to exclude — not a reason to admit under a standard that cannot be tested.
[P4.5] Here is why my side still wins. The opponent conflates system validation with claim verification. System validation — calibration records, benchmark tests, error rates — answers whether the instrument is generally reliable. Claim verification answers whether this output can be defended by a sworn human who read it and takes responsibility.
[P4.6] Criminal procedure runs on the second. A breathalyzer printout is not evidence until a qualified analyst testifies about that specific reading. An AI translation is not evidence until a qualified human certifies that specific translation. The proposition installs exactly that link.
[P4.7] Without it, the record contains assertions no human on earth can defend — and that is the asymmetry criminal trials exist [clipped]

## Turn 8: CON Rebuttal 2

- model: glm-5-3-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The premise is wrong twice. First, "non-reproducible, no fixed error rate" describes human perception perfectly — a witness's memory cannot be re-run, has no published error rate, and fails content-dependently in ways the witness cannot explain. We admit that evidence every day because cross-examination of the *process* — what was seen, under what conditions, with what known biases — is the test. The same works here: a sponsoring expert can be examined on inputs, prompts, logged outputs, known failure modes, and whether this output was checked against source text.
[C4.2] If non-reproducibility were fatal, the eyewitness would be inadmissible first.
[C4.3] Second, non-determinism is an engineering choice, not destiny. Retrieval-grounded systems with logged pipelines can produce outputs with traceable provenance — more auditable than a translator's memory.
[C4.4] A2: Notice what the answer did. PRO said verification means "checking the key claims against source documents." For a million-page synthesis, that is either reading the million pages — the impossibility I identified — or spot-checking a sample. And spot-checking is *system validation*, the very thing PRO dismissed as unable to certify "this specific assertion."
[C4.5] So on PRO's own terms, the human verifier either duplicates the task entirely or does something that cannot vouch for the claim. The "modest label" conceals the fork: ban, or admit on the validation grounds I proposed all along.
[C4.6] That fork is why CON wins the debate. PRO's rule is justified by claim-level accountability, but its verification procedure delivers either class-level sampling or full duplication — neither is the thing promised. Meanwhile, the actual risks PRO raised — silent error, opaque failure, confident fabrication — are handled by the existing reliability framework, strengthened for machine sources: provenance logs, benchmarked error rates, adversarial challenge of the sponsor under oath. That framework convicted the fraudulent forensic sciences PRO and I both condemn; it did not need a presumption of exclusion, and it does not need one now.
[C4.7] A rule that excludes the auditable machine and swears in the unauditable memory is not caution. It is a preference for familiar error over [clipped]

## Turn 9: PRO Closing

- model: minimax-m3
- raw_words: 193
- clipped_words: 193
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive question is whether anything tests the specific claim, not just the instrument. My opponent's framework — validation studies, logged provenance, cross-examination of the sponsor — answers whether the system is generally reliable. It cannot answer whether this sentence is true.
[P5.2] Only a human who read the output and swore to it can do that. Not infallibility — accountability. That is the floor every other piece of evidence already meets: a witness behind the assertion, under oath, subject to cross-examination.
[P5.3] The fork my opponent wields concedes the point. Whether verification means re-reading a million pages or sampling key claims, both are more than what currently happens: nothing. The proposition sets a floor, not a ceiling. Some human must look at the output and stand behind it.
[P5.4] This matters because criminal trials protect liberty. A hallucinated sentence in evidence can cost years of a person's life. Exclusion costs the state one investigative tool. When stakes are this unequal, the default tilts toward placing an accountable human between the machine's output and the verdict.
[P5.5] That is not superstition about the new. That is the constitutional minimum already applied to every other form of evidence.

## Turn 10: CON Closing

- model: glm-5-3-high
- raw_words: 216
- clipped_words: 216
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.3], [P4.5]
- missing_claim_id_refs: (none)

[C5.1] One question decides this, and PRO's own closing answers it against the motion. [P5.3] says sampling key claims is "more than nothing." But the entire case for the presumption was that system-level checking cannot certify *this specific assertion* [P4.5]. So what does the human verifier of a million-page synthesis actually do?
[C5.2] Sample. That is class validation — the exact standard PRO spent two speeches dismissing as inadequate. The rule either demands full duplication, which is a ban wearing a modest label, or it demands sampling, which is the reliability framework I proposed from the start. There is no third option, and PRO never produced one.
[C5.3] Worse, the presumption's costs land where PRO's asymmetry argument says they matter most: on the accused. "Some human must stand behind it" means the defense must buy that human, while the state keeps its crime lab. Caution that only the prosecution can afford is not caution.
[C5.4] The proof this is superstition, not a floor: every defect PRO attributes to AI — non-reproducibility, silent failure, unexplained confidence — describes human memory, which we admit daily and test by cross-examining the process. If accountability requires re-running the source, the eyewitness falls first.
[C5.5] The existing reliability framework reformed the forensic scandals; it never needed a presumption. It doesn't need one now. Reject the motion.
