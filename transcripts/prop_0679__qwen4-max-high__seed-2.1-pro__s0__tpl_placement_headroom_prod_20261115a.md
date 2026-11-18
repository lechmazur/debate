# Debate prop_0679__qwen4-max-high__seed-2.1-pro__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: qwen4-max-high
- model_con: seed-2.1-pro
- side_swap: False

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 290
- clipped_words: 290
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A criminal verdict must be attributable to someone who can be sworn, questioned, and held responsible. That is why the analyst who ran the DNA takes the stand instead of mailing in a printout. AI-generated summaries, translations, and reconstructions are assertions with no author. No one can be cross-examined about why the model chose that word, that face, that omitted paragraph.
[P1.2] This presumption creates no new burden; it restores the authentication floor that machine output would otherwise slip beneath.
[P1.3] The dangerous failure mode is not error but fluency. A human translator's mistake often announces itself: awkward grammar, a flagged idiom, a note saying "unclear." A model produces a clean, confident sentence where a negation has quietly vanished, or slang for "borrow" becomes "steal." A generative reconstruction of a blurry CCTV frame does not recover pixels that were never captured; it invents plausible ones and hands the jury a face.
[P1.4] A summary of forty thousand pages reads beautifully and drops the one line that would have acquitted. None of these look like errors. That is why each needs a human willing to sign their name beneath it.
[P1.5] The reply will be that humans err too and models are cheaper. But human error is discoverable: you can ask about credentials, notes, drafts, incentives. And this motion bans nothing. It prices AI at exactly one expert's review.
[P1.6] A state with the resources to imprison someone for decades can pay a qualified translator to check the transcript it intends to convict him with. The efficiency argument runs one way: the prosecution has the model, the defendant has a public defender's budget.
[P1.7] The question is not whether the machine is usually right. It is whether anyone can be made to answer when it is wrong.

## Turn 2: CON Opening

- model: seed-2.1-pro
- raw_words: 299
- clipped_words: 299
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] This rule is arbitrarily overbroad, systematically skewed against defendants, and treats AI-generated material worse than identical, often less reliable human-generated work that courts admit every day without a separate expert verification requirement. Paralegals, court staff, police technicians, and entry-level contract translators routinely produce document summaries, foreign language snippets, and clarified audio/video for trial. We do not bar that work presumptively; we admit it subject to ordinary authentication, cross-examination of the person who prepared it, and targeted expert challenge only when a concrete, particularized flaw is alleged.
[C1.2] The person who selects an AI tool, feeds it inputs, checks its output for obvious inconsistencies, and offers it at trial is a sworn, accountable party, just like the DNA analyst who uses proprietary commercial software to process a sample or the technician who uses digital tools to clean up a blurry recording. A blanket presumptive bar does not protect defendants—it disarms them. An indigent defendant facing 100 hours of foreign language wiretaps or 40,000 pages of discovery cannot afford human experts to surface the exculpatory line an overworked prosecution contractor missed.
[C1.3] AI tools can pull that line out for almost no cost, but this rule would lock that evidence out of court unless the defendant pays for a separate human expert to verify every line, a cost most public defense budgets cannot cover. Hidden, fluent error is not unique to AI. Human translators misrender slang, human summarizers skip inconvenient facts, human technicians fill in ambiguous visual detail based on expectation. We address those errors through adversarial testing, not a one-size-fits-all presumption that treats even routine, reliable AI output as too suspect to admit unless it carries a paid expert’s signature.
[C1.4] The rule does not eliminate unfair asymmetry—it entrenches it, reserving usable evidence for the party able to pay for redundant expert sign-off.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Notice what my opponent's own examples concede. The paralegal, the court translator, the police technician — every one of them is a human who prepared the work and can be asked why. That is the motion. The DNA analyst using proprietary software still takes the stand and answers for validation and error rates; the software doesn't invent alleles.
[P2.2] A generative model invents pixels.
[P2.3] The gap is in "checks its output for obvious inconsistencies." Fluent error has no obvious inconsistency. A dropped negation reads perfectly. An omitted paragraph leaves no hole — the summary is smooth where the acquittal used to be.
[P2.4] So their safeguard, "targeted expert challenge only when a concrete, particularized flaw is alleged," asks the defendant to detect the invisible before earning review. We put review before admission; they put it after a guess.
[P2.5] And the disarmament story collapses on one distinction: finding evidence is not admitting it. The defendant runs the model over a hundred hours of wiretap for free, finds the exculpatory line, and offers the line — the original recording, the original page, authenticated as it always was. Interpreters for the indigent are already appointed; that cost is not new. The AI is a flashlight, not the exhibit.
[P2.6] Nothing in this motion touches that. What it blocks is the state handing a jury a machine's polished paraphrase of forty thousand pages and calling it the record.
[P2.7] Which is why the asymmetry runs the other way. The party with the model and the forty thousand pages is the prosecution. The party who needs the summary to be complete is the defendant, and he is the one who cannot audit it.
[P2.8] An operator who cannot say why the model chose that word is not a witness. He is a signature laundering an assertion nobody made.

## Turn 4: CON Rebuttal 1

- model: seed-2.1-pro
- raw_words: 296
- clipped_words: 296
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4]
- cited_claim_ids: [P2.5]
- missing_claim_id_refs: (none)

[C2.1] That "signature laundering" charge collapses the second you apply it to evidence courts admit every day. When a court reporter uses proprietary auto-transcription software to generate a trial transcript, when a forensics analyst uses probabilistic genotyping software to call DNA alleles from a mixed sample, when an officer uses digital enhancement to clean up a dashcam clip, none of those people can line-by-line reverse-engineer the software’s internal weighting. They swear they reviewed the output against the source material, tested it against known samples, corrected obvious errors, and stand by the final product.
[C2.2] That is not laundering—it is the exact authentication standard we have used for decades for tool-assisted human work, and there is no principled reason to hold AI to a uniquely higher bar. The supposed "flashlight not the exhibit" distinction [P2.5] is a fantasy for the people this rule hurts most. An indigent defendant who uses AI to translate a two-hour jailhouse call where a witness recants cannot “just offer the original” when no juror, and often no sitting judge, speaks the relevant language.
[C2.3] Court-appointed interpreter backlogs stretch for months in overburdened courts, and public defense budgets have no line items to pay a separate expert to verify every AI-generated translation or summary the defense needs to make its case. The prosecution, by contrast, has on-staff translators and analysts who can add that required verification to their own AI output at no marginal cost. Nor does the rule eliminate fluent, undetectable error. A human expert signing off on a summary can just as smoothly omit the one exculpatory line, and that work would be admissible with no presumptive bar, no mandatory second check.
[C2.4] The rule does not stamp out unaccountable error—it reserves efficient, reliable tooling for the side that can already afford redundant human sign-off.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 74
- clipped_words: 74
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say the analyst "reviewed the output against the source material" and "tested it against known samples." Isn't that precisely the independent human verification this motion requires — meaning your examples satisfy the rule rather than refute it?
[P3.2] Q2: You say a human summarizer can omit the exculpatory line just as smoothly. So what question about drafts, notes, or incentives can counsel put to an operator who never read the forty thousand pages?

## Turn 6: CON Pressure Questions

- model: seed-2.1-pro
- raw_words: 75
- clipped_words: 75
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If an indigent defense team uses AI to translate a critical jailhouse recantation and swears they cross-checked key passages against the original audio, why should that evidence be presumptively barred when no free, timely court interpreter is available?
[C3.2] Q2: You accept tool-assisted evidence from court reporters and DNA analysts is admissible after ordinary sworn review, so why should identical sworn review of AI output trigger a special presumptive bar requiring separate independent expert sign-off?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 290
- clipped_words: 290
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Because the presumption is rebuttable, not a wall. And look at what he described: counsel "cross-checked key passages against the original audio." If a competent speaker checked the minutes he actually offers, the motion is satisfied — he verified the exhibit, not the hundred hours. The burden scales with what you put before the jury.
[P4.2] A recantation is a few sentences, and the man who recanted can usually be called to say it himself. Where no verifier is available, the remedy is appointment or continuance — not an unchecked paraphrase of a man's liberty.
[P4.3] A2: Because the review is not identical; the difference is competence in the source. A court reporter checks a transcript against audio she can hear. A DNA analyst checks against known samples using a validated method. Both can read the original.
[P4.4] Now ask the officer who "reviewed" a machine's Uzbek translation whether he speaks Uzbek. He checked coherence, not accuracy — and fluent error is coherent by construction. Where the checker can genuinely read the source, my rule is met and nothing is barred. So the parity examples either satisfy this motion or expose precisely the gap it closes.
[P4.5] Which leaves my two questions unanswered. Their own witnesses perform the verification this motion asks for, and no one has said what counsel asks the operator who never read the forty thousand pages. The fallback — human summarizers omit lines too — concedes the harm and quarrels with the label, while the human still answers for drafts, notes, incentives. Weigh the costs honestly: their harm is a scheduling problem, curable by appointment; the harm I prevent is a conviction resting on an assertion nobody made and nobody can question.
[P4.6] Delay can be undone. A verdict cannot.

## Turn 8: CON Rebuttal 2

- model: seed-2.1-pro
- raw_words: 296
- clipped_words: 296
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: No, because the motion demands separate independent expert verification, not the ordinary sworn review by the evidence preparer that existing law already requires. My examples of analysts, court reporters, and technicians reviewing tool output do not satisfy the rule, because those preparers are not separate, retained independent experts brought in to sign off after the fact. That extra step is a cost indigent defense teams cannot cover even for short, critical passages when court-appointed experts are backlogged for months.
[C4.2] That is not parity—it is a surcharge on defense use of AI that state prosecutors with on-staff experts never meaningfully feel.
[C4.3] A2: You ask exactly the same questions you ask a junior paralegal or contract reviewer who supervises a team of human summarizers to condense 40,000 pages of discovery: what sampling protocol did you use to spot-check output against source material, what quality controls did you apply, what inconsistencies prompted corrections, and what notes did you keep during that process? If that review is negligent or deliberately slanted, you cross-examine on it, just as you do for human-prepared summaries, and you admit contradictory original material to impeach it.
[C4.4] The core flaw in PRO’s case is that it treats a separate paid expert signature as the only line between accountable evidence and machine invention, but that signature creates no foolproof guardrail. A retained expert who signs off on a summary can omit exculpatory lines just as fluently, carry the same blind spots on unexamined portions of source material, and yet that expert-vetted work would carry no presumptive taint. The rule does not eliminate unanswerable error; it locks out low-cost defense evidence while imposing no practical burden on the state, tilting the courtroom even further against the defendant who cannot afford redundant expert sign-off to present his defense.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Their last answer decides this. Asked what counsel questions when nobody read the forty thousand pages, they offered: "what sampling protocol did you use to spot-check output against source material." That question only works on a supervisor who can read the pages. It is the question you ask a human who verified — which is to say, their final defense of unverified output is a description of verification.
[P5.2] Nobody has answered for the Uzbek officer. He can be asked about protocols all day; he cannot tell you whether the negation survived, because he cannot read the original. Fluent error is coherent by construction, so his spot-check samples coherence. That is the gap, and it is not a labeling dispute.
[P5.3] And "a retained expert can omit lines too" is not an argument against this presumption; it is an argument against expertise. The motion never promised infallibility. It promised someone who read the source, swore to it, and can be destroyed on the stand for getting it wrong.
[P5.4] Their cost is appointment and continuance — delay a court can cure. Ours is a verdict built on an assertion no human ever made. Delay can be undone. A verdict cannot.

## Turn 10: CON Closing

- model: seed-2.1-pro
- raw_words: 191
- clipped_words: 191
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The deciding flaw in this rule is that it does not eliminate unaccountable, fluent error—it monopolizes access to admissible tool-assisted evidence for parties wealthy enough to pay for a separate expert’s after-the-fact signature, while locking indigent defendants out of the low-cost tools they need to surface, translate, and present exculpatory material they could never manually process on a public defender’s overstretched budget. PRO frames the choice as between curable delay and irreversible wrongful conviction, but that is a false tradeoff.
[C5.2] The sworn preparer who spot-checks AI output against original source material is every bit as accountable for negligence, omissions, or bias as the junior contract translator, paralegal, or forensics technician whose tool-assisted work courts admit every day without mandatory separate expert sign-off. The independent experts PRO requires also rely on sampling, not full line-by-line review of thousands of pages, so they are just as vulnerable to missing fluent, hidden omissions. This rule does not guarantee a sworn, knowledgeable human stands behind every exhibit.
[C5.3] It slaps an unaffordable price tag on the defendant’s ability to get his evidence before the jury at all, entrenching the exact power asymmetry PRO claims to fix.
