# Debate prop_0679__gpt-oss-120b__gpt-6-astra-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: gpt-oss-120b
- model_con: gpt-6-astra-high
- side_swap: True

## Turn 1: PRO Opening

- model: gpt-oss-120b
- raw_words: 288
- clipped_words: 288
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] AI‑generated evidence—automated summaries, machine translations, forensic reconstructions—must be presumed inadmissible until a qualified human expert independently verifies it. The core of criminal justice is the guarantee that every fact presented to a jury rests on a reliable foundation. Unlike a forensic analyst who can explain methodology, error rates, and chain‑of‑custody, a black‑box algorithm offers no such transparency. Even state‑of‑the‑art models produce hallucinations: a recent case in which a language model fabricated a citation within a purportedly accurate translation led to a mistaken identification of a suspect.
[P1.2] Without a human check, the jury would hear a convincing but false narrative.
[P1.3] Second, bias is baked into training data. Algorithms trained on predominantly police‑generated reports inherit the same systemic prejudices that already skew investigations. An AI summary of surveillance footage could downplay exculpatory angles while emphasizing incriminating frames, subtly shaping juror perception. Human experts can spot these distortions and adjust or reject the output, preserving the adversarial balance required by due‑process law.
[P1.4] Third, the adversarial system demands that the prosecution’s evidence be subject to rigorous cross‑examination. When the underlying material is an opaque codebase, defense counsel cannot meaningfully interrogate its assumptions, rendering any challenge ineffective. A presumption of inadmissibility forces the state to meet the traditional burden of proof: to produce evidence that can be independently inspected and contested.
[P1.5] Finally, the precautionary principle is already embedded in evidentiary rules that treat hearsay, scientific testimony, and digital forensics with heightened scrutiny. Extending that safeguard to AI‑generated outputs simply updates the rule for the technology of today. Until a human expert validates accuracy, relevance, and reliability, such evidence threatens wrongful convictions and erodes public trust. Courts that ignore this safeguard risk setting a precedent that permits unchecked algorithmic authority to replace human judgment.

## Turn 2: CON Opening

- model: gpt-6-astra-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Criminal courts should test evidence for reliability, not impose a mandatory professional credential because software helped produce it. The proposition confuses those standards. It would presumptively exclude even an output whose accuracy is demonstrable from disclosed records, unless a human expert independently verifies it. That is an unnecessary gate, not a reliable dividing line.
[C1.2] Consider an AI-generated chronology of timestamped messages. Every entry links to its original; both parties receive the complete conversation; a witness authenticates the messages. Lawyers can expose omissions, and the judge can compare disputed entries directly. What additional expertise is necessary to verify that Tuesday preceded Wednesday?
[C1.3] Requiring a specialist here adds expense without identifying a missing safeguard.
[C1.4] That expense matters especially for defendants. This motion covers defense evidence too. An accused person using a straightforward chronology to reveal an alibi faces another funding hurdle, even when the underlying records are available for inspection. A rule advertised as protection against wrongful convictions can obstruct the presentation of exculpatory evidence.
[C1.5] PRO’s concerns about hallucination and bias justify scrutiny, but not this universal prerequisite. Expert review does not automatically make an opaque reconstruction transparent; access to inputs, methods, assumptions, and limitations makes it contestable. Nor does verifying individual sentences necessarily expose a summary’s selective omissions. Expert verification can help, but it is neither sufficient nor necessary in every case.
[C1.6] The better rule requires the party offering evidence to establish a foundation proportionate to its use and risk. Demand source access, disclose AI involvement, permit challenges, and exclude outputs whose reliability cannot be demonstrated. Complex forensic reconstructions may require experts; directly checkable summaries need not. That preserves scrutiny without making expert availability the price of presenting reliable evidence.
[C1.7] The decisive question is whether a claim can be tested, not whether checking it required an expert.

## Turn 3: PRO Rebuttal 1

- model: gpt-oss-120b
- raw_words: 285
- clipped_words: 285
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Con’s insistence that a simple AI‑generated chronology “needs no expert” ignores the very nature of algorithmic opacity. Even a list of timestamps can be corrupted by subtle, invisible transformations—automatic timezone normalization, duplicate‑removal heuristics, or confidence‑threshold filtering—that reorder events or drop messages without any trace in the raw log. Only a qualified forensic analyst can audit the preprocessing pipeline, verify that the AI’s internal rules did not discard a crucial text, and explain the error‑rate statistics required by Daubert. Your example presumes the output is a verbatim copy; the hallucination incident cited in our opening demonstrates that models routinely fabricate citations or splice together unrelated fragments while still presenting a plausible‑looking document.
[P2.2] Trusting the “original conversation” alone is a false security, because the AI can inject fabricated lines that appear in the displayed chronology but never existed in the source files.
[P2.3] The cost argument also collapses under scrutiny. Criminal courts already fund expert testimony for DNA, ballistics, and digital forensics; adding a modest verification step for AI does not create a new burden but extends an existing safeguard to a technology that can produce far more misleading narratives than a fingerprint. If the prosecution may rely on an unchecked AI reconstruction, the defense is forced either to hire an equally expensive expert or to forfeit crucial exculpatory material—precisely the imbalance you claim the rule would create.
[P2.4] Our presumption of inadmissibility is not a blanket ban; it merely places the burden on the proponent to produce a human‑validated report, just as any scientific claim must survive expert scrutiny. By allowing any AI output that merely links to a source, the courts would open the floodgates to hidden manipulations, undermining the reliability standard that the adversarial system demands.

## Turn 4: CON Rebuttal 1

- model: gpt-6-astra-high
- raw_words: 286
- clipped_words: 286
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO’s strongest objection confuses two different tasks: validating a software pipeline and establishing that a particular exhibit accurately represents authenticated records. A court need not certify every internal operation to check a short chronology against the complete, independently accessible messages. If the AI invents a line absent from those records, comparison reveals the invention; it does not make comparison impossible.
[C2.2] Timezone conversions and missing messages are legitimate concerns, but PRO must show why they invariably require specialist knowledge. Visible timestamps can be compared; a small, complete message set can be checked for omissions. Where sources are inaccessible or transformations genuinely technical, require expert assistance or exclude the exhibit. That is targeted scrutiny, not permission to admit anything with a hyperlink.
[C2.3] Nor does invoking scientific admissibility standards turn every summary into a scientific inference. A reconstruction estimating a vehicle’s speed may require methodological expertise; an accurate ordering of authenticated messages need not. The proposition erases that distinction by making expert status, rather than the adequacy of verification, the threshold. The label “AI-generated” cannot supply the missing justification.
[C2.4] PRO also cannot call verification “modest” while demanding audits of preprocessing pipelines, internal rules, and error rates. Existing funding for some forensic testimony does not establish adequate funding for every defense summary or translation. Crucially, the motion can exclude reliable defense evidence even when its accuracy is demonstrable without that expenditure.
[C2.5] Finally, my rule does not allow prosecutors to submit unchecked reconstructions. The proponent must establish reliability; the defense must have a meaningful opportunity to challenge it. Calling PRO’s rule a presumption rather than a ban does not cure its unnecessary condition. When ordinary verification establishes accuracy, excluding evidence until an expert repeats the work protects neither truth nor defendants.

## Turn 5: PRO Pressure Questions

- model: gpt-oss-120b
- raw_words: 84
- clipped_words: 84
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You argue that a raw message log can be directly compared to an AI‑generated chronology, yet you admit that hidden preprocessing (timezone normalization, duplicate removal) can silently alter the sequence—how can a lay judge detect such covert transformations without a qualified expert audit?
[P3.2] Q2: If the prosecution can introduce an AI‑produced reconstruction that may hallucinate or fabricate entries, what mechanism does your rule provide to ensure the defense can challenge those insertions promptly, given that you deny any requirement for independent expert verification?

## Turn 6: CON Pressure Questions

- model: gpt-6-astra-high
- raw_words: 67
- clipped_words: 67
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If both parties and the judge verify every entry and check for omissions against a complete, authenticated message set, would you still presumptively exclude an exculpatory AI chronology solely because none is a forensic expert?
[C3.2] Q2: You call verification “modest” while requiring audits of preprocessing, internal rules, and error rates; what guarantees that an indigent defendant can obtain those audits in time to present exculpatory evidence?

## Turn 7: PRO Rebuttal 2

- model: gpt-oss-120b
- raw_words: 291
- clipped_words: 291
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Even if the parties and the judge compare the AI chronology with the original log, the judge cannot see the invisible transformations that the algorithm may have applied. Time‑zone conversion, message de‑duplication, confidence‑threshold pruning, or language‑model paraphrasing can change the order or even create entries that never existed, yet leave the visible timestamps unchanged. Only a qualified forensic analyst can reconstruct the pipeline, expose hidden parameters, and certify that the output reflects the raw data without alteration. Therefore the presumption of inadmissibility remains essential; without an expert audit the surface comparison is insufficient to guarantee reliability.
[P4.2] A2: The rule does not leave indigent defendants defenseless. Criminal procedure already provides for court‑appointed experts when specialized knowledge is required, as in DNA or ballistics cases. A modest statutory fund or a public defender’s budget can be extended to cover the verification of AI‑generated evidence, exactly as it does for other scientific testimony. Moreover, the burden sits on the proponent—typically the state—to produce a human‑validated report before the evidence is admitted.
[P4.3] This shifts the cost to the party seeking to introduce the evidence, ensuring that the defense is not forced to finance duplicate audits merely to access its own exculpatory material.
[P4.4] Having answered the pressure questions, the core of the debate remains: AI‑generated outputs are opaque, prone to hallucination and bias, and lack the methodological disclosure required by Daubert and Frye. Expert verification is the only practical way to expose error rates, training‑data influences, and algorithmic quirks, preserving the adversarial balance and preventing wrongful conviction. The presumption of inadmissibility is not a blanket ban but a calibrated safeguard mirroring DNA and digital‑forensics rules. Requiring independent human validation thus upholds reliability, fairness, and public confidence while still permitting vetted AI evidence to aid fact‑finding.

## Turn 8: CON Rebuttal 2

- model: gpt-6-astra-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: A judge need not reconstruct hidden processing to detect its effect on a short, independently authenticated message set. If five messages become four, an omission is visible; if their order changes, comparison reveals it; if a sentence is invented, it lacks an original. Unchanged timestamps do not hide reordered entries. Where interpreting timestamps genuinely requires technical knowledge, require an expert.
[C4.2] But PRO's answer assumes that hidden operations must produce undetectable errors even after every entry, omission, and ordering has been checked. That does not follow.
[C4.3] A2: Require disclosure before admission of the precise output, its underlying materials, and any material transformations, with sufficient time for the defense to inspect and challenge them. Resolve disputed reliability before the jury sees the exhibit. If sources are unavailable, fabrication cannot be meaningfully tested, or technical uncertainty requires expertise, withhold admission unless that deficiency is cured. I reject a universal expert prerequisite, not expert review when necessary.
[C4.4] A prosecutor cannot bypass these requirements by calling a reconstruction a summary.
[C4.5] PRO's latest answers expose the decisive mismatch. Asked about an exculpatory chronology already fully checked, PRO still demands a pipeline audit. That audits a production process without identifying any remaining question about the exhibit's accuracy. A technical reconstruction needs technical validation; a directly verifiable exhibit need not become a forensic investigation merely because AI prepared it.
[C4.6] And making the proponent pay does not protect a defendant who is the proponent. PRO's proposed funding extension is an additional promise, not a guarantee supplied by this motion. It cannot erase the delay and expense its rule creates.
[C4.7] Both approaches can exclude inadequately supported evidence. Only mine permits reliable, contestable defense evidence without an unnecessary credential barrier. Criminal justice should demand adequate verification, not insist that adequate verification counts only when performed by an expert.

## Turn 9: PRO Closing

- model: gpt-oss-120b
- raw_words: 193
- clipped_words: 193
- claim_ids: [P5.1], [P5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] At the heart of this dispute lies a single, unambiguous question: can a court rely on a black‑box output whose inner workings are inaccessible, or must it demand the same reliability safeguards that govern every other scientific aid? The answer is clear. AI‑generated summaries, translations, or reconstructions are not transparent artifacts; they can hallucinate, embed hidden preprocessing, and reproduce systemic bias without any trace in the visible product. Without a qualified forensic analyst to audit the model, disclose error rates, and explain how training data shape the result, the jury would be asked to treat an opaque algorithm as a trustworthy witness.
[P5.2] That gamble threatens wrongful convictions far more seriously than the modest cost of expert verification, a cost the state already bears for DNA, ballistics, and digital forensics. By imposing a presumption of inadmissibility until a human expert independently validates the output, the rule preserves the adversarial balance, guarantees Daubert‑compliant reliability, and protects public confidence. Any alternative that allows unchecked AI evidence sacrifices the fundamental safeguard against error, and therefore must lose. The justice system cannot compromise its core principle of proof beyond a reasonable doubt for the convenience of unvetted technology.

## Turn 10: CON Closing

- model: gpt-6-astra-high
- raw_words: 186
- clipped_words: 186
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The choice is not expert verification or unchecked evidence. Our alternative requires demonstrated reliability before admission, disclosure of the underlying material, and a meaningful opportunity to challenge it. Require an expert when the uncertainty requires expertise. The disagreement concerns evidence whose accuracy can already be established without one.
[C5.2] An opaque production process does not make every resulting claim opaque. If a short chronology matches the complete, authenticated messages in content and order, auditing hidden model parameters adds no identified protection against an error in that exhibit. PRO was asked about that fully checked case and still demanded exclusion without an expert. That answer exposes the rule’s defect: it makes credentials, rather than demonstrated reliability, decisive.
[C5.3] This is not convenience weighed against wrongful conviction. When the defendant offers the chronology to establish an alibi, exclusion itself can undermine a just verdict. Calling the cost “modest” or promising expanded funding does not justify withholding evidence already shown to be accurate.
[C5.4] Both approaches can keep untestable reconstructions from the jury. Only ours avoids excluding testable, reliable evidence solely because no specialist repeated a check that required no specialist knowledge.
