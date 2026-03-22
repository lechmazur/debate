# Debate prop_0679__claude-opus-4-6-0K__gemini-3.1-pro-preview__s0__tpl_placement_active_20260320f

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: claude-opus-4-6-0K
- model_con: gemini-3.1-pro-preview
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-4-6-0K
- raw_words: 366
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Criminal convictions deprive people of liberty, sometimes for decades. That fact demands that every piece of evidence entering a courtroom meet a high threshold of reliability. AI-generated evidence—automated summaries of intercepted communications, machine translations of foreign-language documents, algorithmic reconstructions of crime scenes or forensic data—does not yet clear that threshold on its own, and treating it as presumptively admissible invites serious, preventable injustice.
[P1.2] The core problem is that large language models and similar systems hallucinate. They generate plausible-sounding outputs that are factually wrong, and they do so without any internal signal that something has gone awry. A machine translation might silently shift the meaning of a critical phrase. An AI summary might omit an exculpatory detail or inject one that never existed.
[P1.3] A forensic reconstruction tool might present a confident visualization built on statistical interpolation rather than observed fact. When liberty is at stake, "usually accurate" is not good enough. Independent human verification catches exactly the errors that matter most: the ones the system itself cannot flag.
[P1.4] Presumptive inadmissibility is not a ban. It is a procedural gate that says: before this output reaches the jury, a qualified human must confirm its accuracy. This mirrors how courts already treat other expert-dependent evidence. Forensic lab results require a certifying analyst.
[P1.5] Translations already require a sworn interpreter in most jurisdictions. AI-generated evidence should be held to at least the same standard, not a lower one, simply because it is faster or cheaper.
[P1.6] The alternative—letting AI outputs in by default and leaving challenges to cross-examination—badly overestimates what cross-examination can accomplish. Jurors are not equipped to evaluate the internal workings of a neural network. Defense attorneys may lack the resources to hire their own AI experts. The asymmetry is profound: the prosecution can generate AI evidence cheaply and at scale, while the defense bears the burden of debunking it case by case.
[P1.7] Placing the verification requirement up front distributes that burden fairly, protects defendants' due-process rights, and preserves public trust in verdicts. The cost is modest—an expert review step—while the benefit is enormous: [clipped]

## Turn 2: CON Opening

- model: gemini-3.1-pro-preview
- raw_words: 328
- clipped_words: 328
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.4], [P1.3]
- missing_claim_id_refs: (none)

[C1.1] The proposition demands a radical and paralyzing shift in how courts operate: treating all AI-generated evidence as presumptively inadmissible unless independently verified by a human expert. This blanket rule is unnecessary, unworkable, and ultimately harmful to the justice system—including to the defendants it supposedly protects.
[C1.2] First, courts already possess robust frameworks for evaluating evidence. Judges routinely assess authentication, relevance, and reliability under existing evidentiary rules. If an AI summary is demonstrably unreliable, judges already have the authority to exclude it. We do not need an arbitrary rule of "AI exceptionalism" that bypasses judicial discretion and assumes all machine-assisted outputs are inherently suspect until proven otherwise.
[C1.3] Second, PRO’s mandate for independent human expert verification [P1.4] would immediately paralyze criminal proceedings. Modern discovery often involves terabytes of data: thousands of hours of intercepted audio, mountains of seized financial records, or endless digital communications. AI tools are uniquely capable of translating, sorting, and summarizing this immense volume of information. Mandating that a human expert manually verify every AI-generated translation or summary defeats the entire purpose of using the technology.
[C1.4] The result is not safer trials, but a system where highly probative evidence is suppressed simply because human review of massive datasets is financially and practically impossible.
[C1.5] Furthermore, PRO demands an impossible standard of perfection, claiming "usually accurate is not good enough" [P1.3]. Yet, human evidence is notoriously flawed. Human translators suffer from fatigue and bias; human eyewitnesses frequently misremember; human forensic analysts make critical errors. AI systems are continually improving, inherently auditable, and often more consistent than their human counterparts.
[C1.6] Finally, this ban disproportionately harms the defense. Public defenders, chronically underfunded and overworked, increasingly rely on AI tools to quickly sift through massive prosecutorial discovery dumps to locate exculpatory evidence. Forcing the defense to hire human experts to verify their own AI-assisted findings erects a massive financial barrier to a fair trial. The solution is rigorous cross-examination and existing judicial gatekeeping, not a regressive exclusionary presumption that breaks the justice system.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-4-6-0K
- raw_words: 387
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.2], [C1.3], [C1.6], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] My opponent's case rests on two pillars: that existing judicial gatekeeping is sufficient, and that human verification is practically impossible at scale. Both collapse under scrutiny.
[P2.2] Start with judicial gatekeeping. The claim at [C1.2] that judges can already exclude unreliable AI evidence assumes judges can recognize when AI output is unreliable. That is precisely the problem. AI hallucinations do not come flagged.
[P2.3] A machine translation that subtly shifts "I was near the building" to "I was in the building" looks perfectly fluent. A summary that omits one exculpatory sentence from a thousand-page document reads seamlessly. Without independent verification, the judge has no basis to spot the error, and neither does anyone else in the courtroom. Existing frameworks were designed for evidence whose failure modes are visible—a blurry photograph, a witness who contradicts herself.
[P2.4] AI errors are invisible by design. Saying "judges can handle it" is circular: it assumes the very reliability check our proposition would require.
[P2.5] Now the scalability objection at [C1.3]. My opponent paints a picture of terabytes requiring line-by-line human review. But the proposition says AI evidence must be verified before it is *admitted at trial*, not before it is used as an investigative tool. Prosecutors and defense teams can freely use AI to search, sort, and flag material during investigation.
[P2.6] The verification gate applies only to the subset of AI-generated outputs that a party wants to put before a jury as evidence. That subset is always dramatically smaller than the full dataset. A trial might involve a handful of translated intercepts or a key summary—not the entire discovery archive.
[P2.7] The defense-harm argument at [C1.6] actually proves my case. If public defenders use AI to find exculpatory material, what they present to the court is the underlying document itself, not the AI summary. The AI is a search tool, not the evidence. Our rule targets outputs offered as evidence—the prosecution's AI-generated translation played for the jury, the algorithmic reconstruction shown on screen.
[P2.8] That is overwhelmingly prosecution-side conduct.
[P2.9] Finally, comparing AI errors to human errors at [C1.5] does [clipped]

## Turn 4: CON Rebuttal 1

- model: gemini-3.1-pro-preview
- raw_words: 321
- clipped_words: 321
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [P2.5], [P2.3], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] PRO attempts to save their unworkable standard by drawing an artificial line between investigative tools and admitted evidence [P2.5]. But this retreat exposes the very bottleneck they deny. If a trial requires admitting twenty hours of foreign-language wiretaps, demanding human experts independently re-translate every line to "verify" the AI effectively prices the evidence out of the courtroom. The volume of evidence *presented to juries* in complex financial or conspiracy cases is still massive.
[C2.2] More fundamentally, PRO’s fear of "invisible" AI errors [P2.3] fundamentally misunderstands the adversarial system. When an AI translation or summary is offered into evidence, it is not introduced in a vacuum. The opposing party has access to the underlying raw data—the original audio or the source document. If an AI translation subtly shifts "near" to "in", the defense does not need a blanket presumption of inadmissibility to fight it.
[C2.3] They use the original data to impeach the AI’s output. That is exactly how cross-examination already exposes "invisible" human errors, like a confident but mistaken eyewitness or a biased human interpreter. We do not ban human testimony because it might contain unflagged errors; we test it.
[C2.4] PRO also mischaracterizes the defense burden [P2.7]. It is simply false that the defense only uses AI for discovery. Underfunded public defenders desperately need AI to generate their own forensic reconstructions, translate defense witness statements, and summarize complex data *for the jury*. By demanding these tools be presumptively inadmissible without expensive human expert sign-off, PRO creates a system where only well-funded prosecutions can afford to clear the evidentiary gate.
[C2.5] Existing rules already require the proponent of evidence to establish its reliability. If a specific AI tool has a high hallucination rate, the judge will exclude it under current authentication standards. A categorical rule of presumptive inadmissibility replaces judicial precision with a sledgehammer, blinding juries to highly accurate, cost-effective evidence simply because it was generated by a machine instead of a predictably flawed human.

## Turn 5: PRO Pressure Questions

- model: claude-opus-4-6-0K
- raw_words: 85
- clipped_words: 85
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You claim the defense can simply use "the original data to impeach the AI's output" [C2.2]—but if a prosecution AI summary omits an exculpatory detail from a thousand-page document, how exactly does an underfunded public defender identify *what was left out* without conducting the very independent review you call unworkable?
[P3.2] Q2: You insist existing authentication standards let judges exclude unreliable AI tools [C2.5]—can you name a single established, court-validated reliability standard currently used to assess large language model hallucination rates for specific evidentiary outputs?

## Turn 6: CON Pressure Questions

- model: gemini-3.1-pro-preview
- raw_words: 85
- clipped_words: 85
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.6], [P1.2]
- missing_claim_id_refs: (none)

[C3.1] Q1: If an independent human expert must verify a massive AI-generated translation before admission [P2.6], doesn't that require the expert to manually listen to and re-translate the entire file anyway, thereby rendering the cost-saving AI completely redundant?
[C3.2] Q2: You argue AI errors are uniquely dangerous because they lack "internal flags" [P1.2], but confident eyewitnesses and biased human translators also generate invisible, unflagged errors. Why impose a strict exclusionary presumption on AI when we routinely trust the adversarial process and cross-examination to expose identical human flaws?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-4-6-0K
- raw_words: 367
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.2], [P3.1], [P3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: No, the expert does not need to re-translate the entire file from scratch. Verification is not duplication. A qualified human reviewer can audit the AI output against the source material using targeted spot-checks, flagged ambiguities, and known-difficult passages—much as a senior translator reviews a junior translator's draft rather than retranslating independently. The AI does the heavy lifting; the expert confirms critical accuracy.
[P4.2] This is how quality assurance works in every professional translation context. The cost is a fraction of full re-translation, and it is a fraction worth paying when someone's liberty hangs on whether "near" became "in."
[P4.3] A2: The comparison to eyewitnesses and human translators actually reinforces my side. We already impose significant procedural safeguards on human evidence precisely because of those flaws. Eyewitness identification requires specific jury instructions about unreliability in many jurisdictions. Human translators must be sworn and credentialed.
[P4.4] Human forensic analysts must testify and be cross-examined about their methods. The proposition simply extends equivalent safeguards to AI. The critical difference is that AI errors scale effortlessly—one flawed model can generate thousands of erroneous outputs across hundreds of cases simultaneously—while human errors are individualized and containable. An exclusionary presumption is the proportionate response to a risk that is both invisible and scalable.
[P4.5] Now let me turn these answers into the decisive comparison. My opponent's entire framework depends on the adversarial process catching AI errors after admission. But the adversarial process only works when both sides can identify what went wrong. At [C2.2], CON says the defense can "use the original data to impeach the AI's output."
[P4.6] My unanswered pressure question at [P3.1] exposed why this is fantasy: you cannot impeach an omission you never knew existed. A summary that silently drops exculpatory material gives the defense nothing to cross-examine. The error is not in what the output says—it is in what it doesn't say.
[P4.7] CON has also never answered [P3.2]: there is no established court-validated standard for assessing LLM hallucination rates. That means the judicial gatekeeping CON relies on has no metric to gate against. Presumptive [clipped]

## Turn 8: CON Rebuttal 2

- model: gemini-3.1-pro-preview
- raw_words: 316
- clipped_words: 316
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P3.1], [P3.2], [P2.3], [P4.6], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: To answer [P3.1], an underfunded public defender does not manually read the 1,000-page document to find an omission. They run their own AI queries, e-discovery tools, or simple keyword searches across the raw data to pinpoint exculpatory terms. The adversarial system relies on opposing parties independently probing the shared source evidence, not passively trusting a prosecution's summary.
[C4.2] A2: To answer [P3.2], courts use the *Daubert* standard and Federal Rule of Evidence 702. These established, court-validated frameworks require judges to assess any technical tool’s known error rates, peer review, and general acceptance. If a specific AI model cannot prove its reliability or quantify its hallucination rate, judges already have the explicit authority to exclude it.
[C4.3] Now look at the fatal contradiction PRO just exposed in their own case. Throughout this debate, PRO warned that AI is uniquely dangerous because omissions are "invisible" [P2.3] and "you cannot impeach an omission you never knew existed" [P4.6].
[C4.4] But when pressed on how human experts could actually verify massive datasets, PRO retreated. At [P4.1], they concede the human expert will merely use "targeted spot-checks."
[C4.5] This destroys PRO’s core justification. A human performing a targeted spot-check on an AI summary of a 1,000-page document will never catch a silent, invisible omission buried on page 642. PRO is demanding we upend the evidentiary system and erect massive financial barriers that prevent underfunded defense teams from introducing their own AI-generated reconstructions or translations. And for what?
[C4.6] To mandate a "spot-check" placebo that fundamentally fails to solve the exact hallucination problem PRO built their entire case on.
[C4.7] CON offers the only logically coherent approach. We leverage adversarial testing—where opposing counsel actively queries the source data to expose flaws—and we trust established judicial gatekeeping to bar objectively unreliable tools. PRO’s exclusionary presumption is a blunt instrument that strips juries of highly accurate, accessible evidence while delivering zero actual guarantees against the invisible errors they fear.

## Turn 9: PRO Closing

- model: claude-opus-4-6-0K
- raw_words: 252
- clipped_words: 220
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [P4.6], [C4.1], [C4.5]
- missing_claim_id_refs: (none)

[P5.1] The single question that decides this debate is: who bears the risk when AI evidence is wrong?
[P5.2] CON's framework places that risk entirely on the defendant. The prosecution introduces AI-generated evidence, and the defense must catch whatever errors exist—after the output is already before the jury. CON calls this the adversarial process working as designed. But my unanswered point at [P4.6] shows exactly why it fails: you cannot cross-examine an omission you never knew existed.
[P5.3] A summary that silently drops an exculpatory detail gives the defense nothing to challenge. CON never solved this problem. They suggested the defense could "run their own AI queries" on the source data [C4.1]—which is literally asking the defense to perform independent verification of the prosecution's AI output. That is our rule, just without the procedural guarantee.
[P5.4] CON claimed my expert verification model reduces to a "spot-check placebo" [C4.5]. But a qualified reviewer performing targeted audits against source material is precisely how professional translation, forensic analysis, and medical review already work. It is not perfect, but it is an institutional safeguard—one that creates accountability, catches the highest-stakes errors, and gives judges an actual basis for confidence. CON's alternative offers no safeguard at all beyond hoping the defense can somehow detect invisible errors in outputs they have no reason to distrust.
[P5.5] When liberty is at [clipped]

## Turn 10: CON Closing

- model: gemini-3.1-pro-preview
- raw_words: 204
- clipped_words: 204
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.4], [P5.3], [C4.2]
- missing_claim_id_refs: (none)

[C5.1] PRO’s entire case rests on a fatal paradox. They demand a radical exclusionary rule to prevent "invisible omissions," yet concede their human experts will merely perform "targeted spot-checks" [P5.4].
[C5.2] You cannot spot-check an omission. If an AI silently drops an exculpatory detail on page 642, an expert spot-checking other pages will never catch it. PRO demands we erect a massive financial tollbooth on the justice system for a safeguard that completely fails to solve the exact hallucination problem they fear most.
[C5.3] Furthermore, PRO mischaracterizes the adversarial process. When the defense searches raw data with their own tools, they aren't performing PRO's "independent verification" for the prosecution [P5.3]. They are actively probing the shared discovery to find what was omitted. That is the adversarial system functioning as designed, backed by existing *Daubert* standards [C4.2] that already exclude demonstrably unreliable models from the courtroom.
[C5.4] The true victim of PRO’s rule is the defense. When an underfunded public defender uses AI to translate a crucial witness statement or map a crime scene for the jury, PRO’s proposition presumptively bars it unless they can pay a human expert to bless it.
[C5.5] We must not bankrupt the defense for a spot-check placebo that offers only an illusion of safety.
