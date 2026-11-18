# Debate prop_0666__mimo-v2.6-pro-thinking__gemini-4-carbon-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0666
- proposition: Courts should recognize a limited “right to explanation” when automated systems significantly affect access to housing, credit, employment, or healthcare.
- model_pro: mimo-v2.6-pro-thinking
- model_con: gemini-4-carbon-high
- side_swap: True

## Turn 1: PRO Opening

- model: mimo-v2.6-pro-thinking
- raw_words: 314
- clipped_words: 314
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a lender denies a mortgage because a model scored an applicant low, or a hospital triage tool deprioritizes a patient, the person affected faces a wall of opacity. They cannot tell whether the outcome reflects legitimate risk or a flawed variable acting as a proxy for race, disability, or neighborhood. A limited right to explanation is the tool that turns abstract fairness duties into enforceable ones.
[P1.2] The proposition is deliberately modest. It is not a demand for source code, training data, or trade secrets. It is a demand for reasons: which categories of information drove the decision, how roughly those factors weighed against the applicant, and what could realistically be changed. Courts already require this in substance.
[P1.3] Adverse action notices under fair lending law compel creditors to state reasons for denial. The right to explanation simply insists that when an algorithm makes that call, the obligation does not vanish into the machine. Anything else lets a regulated duty evaporate through outsourcing.
[P1.4] Three reasons courts should recognize it. First, process: a person cannot correct an error or challenge discrimination in a decision they cannot reconstruct. Contestability is empty without intelligibility. Second, remedy: disparate treatment and disability discrimination law require proof of causation and intent-related facts that only the decision-maker holds.
[P1.5] Discovery fights over models already clog litigation; a defined, narrow explanation right resolves them cheaply and predictably. Third, accountability incentives: firms choose opacity when opacity is free. Making explanation the price of deploying automated systems in high-stakes domains pushes them toward systems they can justify.
[P1.6] Notice the bounded scope. Housing, credit, employment, healthcare — access to the necessities of modern life. Significant adverse effects only. Not every app, not every ranking.
[P1.7] The opponent must argue that even there, even at that threshold, silence is the better legal rule. That is a hard position to defend when the alternative is a two-paragraph statement of reasons.

## Turn 2: CON Opening

- model: gemini-4-carbon-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: [P1.7], [P1.3], [P1.2], [P1.5], [P1.4]
- missing_claim_id_refs: (none)

[C1.1] The alternative to a court-invented right is not legal silence [P1.7]. Notice that adverse action notices in lending [P1.3] come from detailed statutes and agency rules, not judges improvising from the bench. Asking courts to manufacture a freestanding “right to explanation” across housing, credit, employment, and healthcare confuses regulatory design with adjudication.
[C1.2] First, courts lack the institutional competence to define this right. Mortgage underwriting, resume screening, and emergency triage operate under radically different timelines, error costs, and technical architectures. Judges deciding individual lawsuits cannot coherently specify when an effect is “significant,” which approximations count as honest “reasons” [P1.2], or when telling applicants what to change exposes screening thresholds to gaming. Far from ending discovery fights [P1.5], an elastic judge-made standard invites endless litigation over whether a two-paragraph summary faithfully captured the underlying math.
[C1.3] Second, mandated individual explanations produce comforting fictions, not real contestability [P1.4]. Complex predictive models evaluate non-linear interactions across hundreds of variables. Compressing them into rough factor weights [P1.2] yields post-hoc rationalizations: plausible boilerplate that masks systemic proxy bias while handing defendants a badge of procedural compliance. Detecting discrimination requires statistical auditing and targeted discovery, not simplified narratives.
[C1.4] Worse, penalizing models that resist simple storytelling [P1.5] harms patients: hospitals get pushed from higher-accuracy diagnostic or sepsis tools toward cruder checklists simply because checklists are easier to explain in court.
[C1.5] Third, singling out automated systems creates a perverse refuge in the most opaque black box of all: unrecorded human discretion. Attaching special judicial liability whenever software assists hiring or tenant screening encourages firms to rely on subjective human gatekeepers, whose biases leave no auditable trail. Legislatures and regulators can tailor rules, audits, and notices domain by domain; courts inventing a cross-sector explanation right trade predictive accuracy and genuine accountability for an illusion of transparency.

## Turn 3: PRO Rebuttal 1

- model: mimo-v2.6-pro-thinking
- raw_words: 291
- clipped_words: 291
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.5], [P1.3], [C1.2], [C1.3], [C1.4]
- missing_claim_id_refs: (none)

[P2.1] Every objection today rests on a quiet concession: a person denied housing or deprioritized in a care queue by an automated system currently gets no intelligible reason at all. CON never defends that silence; the defense is always that legislatures and regulators should design something eventually [C1.5].
[P2.2] But courts decide the cases in front of them, and they already enforce adverse action duties against the actual decision-maker [P1.3]. "The algorithm decided" is not an answer to why this applicant was rejected.
[P2.3] The competence objection [C1.2] proves too much. Courts routinely apply standards like "significant" and "material factor" in discrimination, consumer, and due process cases. The proposed right seeks the same substance adverse action notices already supply: factor categories, rough weight, realistic levers. Yes, disclosure duties spawn boundary disputes; we resolve them, we do not abolish the duty.
[P2.4] The "comforting fiction" argument [C1.3] gets the comparison backwards. A rough explanation is falsifiable: the applicant says "I have no bankruptcy and no late payments," and the firm must produce the actual driver. Silence is the fiction, because proxy discrimination goes unchallengeable. A post-hoc story that contradicts the model is precisely what a duty of faithful reasons exposes, and the narrow discovery I propose punishes it.
[P2.5] The accuracy worry [C1.4] misreads the rule. Nothing bars complex models. A nonlinear triage tool can still say which inputs drove this patient's ranking. If a hospital cannot justify a tool that shapes who gets care, that tells us something about its readiness for that use.
[P2.6] Finally, the human-discretion refuge [C1.5] is not a refuge at all. Existing law reaches human decisions — reasons for firing, eviction, denial — and the anomaly is that automation erases the record while raising the stakes. CON would let opacity buy immunity.

## Turn 4: CON Rebuttal 1

- model: gemini-4-carbon-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4]
- cited_claim_ids: [P2.2], [P2.6], [P2.1], [P2.3], [C1.5], [P2.4], [P1.1], [C1.3], [P1.2], [P1.5], [C1.2], [P2.5], [C1.4]
- missing_claim_id_refs: (none)

[C2.1] The baseline in [P2.2] and [P2.6] rests on a legal fiction. Courts enforce adverse action notices in lending because statutes created them, and where those statutes already cover automated credit or tenant screening, applicants do not face legal silence today [P2.1]. Conversely, under ordinary employment and healthcare law, human decision-makers owe no general duty to hand rejected job applicants or triaged patients a breakdown of "factor categories, rough weight, realistic levers" [P2.3]. By inventing that duty exclusively for automated systems, a court-made rule leaves subjective, unrecorded human rejection untouched while taxing auditable software [C1.5].
[C2.2] Meanwhile, [P2.4] unravels the case on both contestability and discovery. Catching a mistaken bankruptcy on a file requires access to input records, not an explanation of algorithmic weights. Actual proxy discrimination [P1.1], by contrast, is never falsifiable through an individual two-paragraph notice. If a model penalizes work-history gaps or residential mobility, the rejected applicant receives a completely accurate, legitimate-sounding reason that still masks systemic disparate impact, which only cohort-level statistical auditing can expose [C1.3].
[C2.3] Worse, [P2.4] promises to punish post-hoc stories whenever one "contradicts the model." How can a court verify whether a simplified summary faithfully reflects a hundred-variable nonlinear network without opening discovery into the model’s architecture and training data, triggering the exact litigation battles [P1.2] and [P1.5] promised to avoid?
[C2.4] Finally, [P2.3] confuses familiar legal adjectives with technical design. Applying "significant" to case facts does not equip generalist judges to choose among competing mathematical attribution methods across credit, hiring, and emergency care [C1.2]. Look at the stark admission in [P2.5]: if a hospital cannot translate a nonlinear tool’s ranking into a courtroom-ready narrative, it is unready for hospital deployment. Even when clinical validation proves a complex triage tool saves more lives, this rule sidelines it for failing a storytelling test [C1.4].

## Turn 5: PRO Pressure Questions

- model: mimo-v2.6-pro-thinking
- raw_words: 77
- clipped_words: 77
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C1.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say only cohort-level auditing can catch proxy discrimination [C2.2], but the denied applicant lacks that data and standing to commission studies. Under your rule, who explains this specific rejection, and what exactly can that person contest tomorrow morning?
[P3.2] Q2: You claim taxing software drives firms toward unrecorded human discretion [C1.5]. But lenders already owe adverse action reasons regardless of who decides. Doesn't your rule instead reward automated opacity precisely where existing duties would otherwise bind?

## Turn 6: CON Pressure Questions

- model: gemini-4-carbon-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.2], [P2.4], [P2.3], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: You exclude source code, training data, and trade secrets [P1.2], yet promise discovery when explanations contradict the model [P2.4]. How can a court verify whether a two-paragraph summary faithfully captures a nonlinear model without opening discovery into the model itself?
[C3.2] Q2: Your rule requires "rough weight" and "realistic levers" [P2.3] while questioning hospital tools that cannot be justified [P2.5]. When a validated triage model saves lives through nonlinear vital-sign interactions lacking stable weights or patient levers, must courts penalize its use or accept post-hoc approximations?

## Turn 7: PRO Rebuttal 2

- model: mimo-v2.6-pro-thinking
- raw_words: 297
- clipped_words: 297
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.2], [P2.3], [C1.5]
- missing_claim_id_refs: (none)

[P4.1] A1: Verification is narrow and targeted. The court does not need training data to test a stated reason; it needs the applicant's own file and the firm's records showing the stated driver drove the outcome. If the notice says "derogatory credit history" and the file shows none, the summary is falsified without opening the code. Where fidelity turns on the model, a neutral expert under a protective order can sample cases — the very model-level scrutiny your cohort-auditing remedy requires [C2.2], which cannot run without access to inputs and outputs.
[P4.2] You cannot both insist audits are the only real check and insist no court can ever examine a model. My rule converts the discovery you fear into bounded, triggered review; your rule leaves the applicant with nothing to verify.
[P4.3] A2: The triage case is my strongest case, not yours. Nonlinear interactions still admit case-level attributions: which inputs pushed this patient down the queue. "Rough weight" is deliberately rough [P2.3]. If a tool truly cannot say why it deprioritized this patient, we cannot distinguish a validated lifesaver from a miscalibrated one that systematically buries a subgroup — precisely the error the right exists to surface.
[P4.4] Clinical validation speaks to groups; the person in the queue needs a reason now.
[P4.5] Both answers expose the same defect in your case. Your world gives the affected person silence and defers to unnamed regulators and cohort audits [C1.5]. But audits need plaintiffs with standing and data the denied applicant does not have. The limited right supplies both the reason and the trigger for the check you say is the only real one.
[P4.6] Grant your caution about judge-made standards and the two-paragraph duty still wins: it is the only rule that puts a check in front of the person the decision just excluded.

## Turn 8: CON Rebuttal 2

- model: gemini-4-carbon-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.5], [C2.1], [P4.1], [P4.3], [P1.5], [P4.2], [P2.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Where credit or consumer-reporting statutes govern, lenders and screeners must provide statutory notices and file access so applicants can contest factual errors tomorrow morning. Elsewhere, nobody owes a math summary, yet rejection itself confers standing whenever inconsistent criteria, testing, or disparities suggest bias, while regulators audit cohorts directly without private studies. Conversely, telling one rejected applicant that "short job tenure" lowered their score supplies zero cohort data [P4.5]; it merely hands the firm a lawful-sounding shield.
[C4.2] A2: Rejecting a newly invented judicial right never suspends existing statutes. Where adverse-action laws already bind, as in lending, courts enforce them equally against algorithms and humans, rewarding automated opacity nowhere [C2.1]. The perverse incentive arises where humans owe no general explanation, like hiring and clinical care: targeting only "automated systems" penalizes auditable models while leaving unrecorded human gatekeeping untouched.
[C4.3] Put those two realities together with the concessions in [P4.1] and [P4.3], and the case for a judge-made right collapses. First, [P4.1] concedes that catching a phantom delinquency requires only the applicant's file, whereas testing model fidelity requires neutral experts sampling cases under protective orders. That destroys the promise of cheap, predictable resolution [P1.5]. Courts can examine models during discrimination discovery [P4.2], when experts test for actual unlawful bias.
[C4.4] Under the proposed right, however, courts referee costly expert battles simply to decide whether "deliberately rough" prose [P4.3] faithfully summarized nonlinear math.
[C4.5] Second, [P4.3] gets clinical triage backwards. Telling one patient which vital signs lowered their priority cannot distinguish a lifesaver from a tool that "systematically buries a subgroup"; subgroup miscalibration is a population pattern invisible in a single notice. Yet demanding courtroom-ready weights and nonexistent patient "levers" [P2.3] still chills validated, lifesaving models. Enforcing targeted statutes and audits beats inventing cross-sector boilerplate that masks systemic bias while taxing accuracy.

## Turn 9: PRO Closing

- model: mimo-v2.6-pro-thinking
- raw_words: 220
- clipped_words: 220
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate reduces to one question: what does the person standing outside the locked door have? CON's world gives them a file to inspect and a hope that someone else — a regulator, a future plaintiff, a cohort study — eventually audits the pattern. But notice the sequence CON must defend: the applicant must first know enough to suspect bias, then find standing and data, then fund or trigger expert scrutiny of a model they have been told nothing about.
[P5.2] That is contestability designed backwards.
[P5.3] My limited right inserts the one thing that starts that machinery: an intelligible, testable reason from the decision-maker itself. Not code, not weights, not a courtroom-grade mathematical proof — the substance adverse action law already demands, which CON never argues should be surrendered to a machine. When the stated reason contradicts the file, the claim is narrow and cheap. When it hides a proxy, the duty of faithful reasons plus targeted expert sampling exposes it.
[P5.4] CON calls that a fiction, but a falsifiable statement is the opposite of fiction; the silence CON preserves is what makes proxy discrimination invisible in the individual case.
[P5.5] Existing duties already bind firms that decide by hand. CON would let them escape those duties by outsourcing the decision to a system no one may interrogate. Courts should close that gap.

## Turn 10: CON Closing

- model: gemini-4-carbon-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: [P5.1], [P5.4], [P5.3], [P5.5], [P4.3]
- missing_claim_id_refs: (none)

[C5.1] Stand beside the person outside that locked door [P5.1] and ask what a court-invented explanation actually puts in their hand. File access catches factual errors without summarizing weights. When the harm is proxy discrimination, suppose a model penalizes work-history gaps or residential mobility. The two-paragraph notice states, truthfully, that those factors drove the rejection.
[C5.2] That statement matches the file and faithfully reflects the model. Nothing is falsified [P5.4], so nothing ever triggers expert sampling [P5.3]. Far from starting the machinery of contestability, the notice hands the applicant a lawful-sounding dead end and hands the firm a badge of procedural compliance.
[C5.3] Manufacturing that empty shield from the bench rests on the false baseline in [P5.5]. Where statutes require adverse-action reasons, as in credit, courts already enforce them against algorithms and humans alike; no duty vanishes into a machine. Where law requires no explanation from humans, as in hiring and clinical triage, imposing a judicial storytelling test exclusively on software steers decisions toward unrecorded human discretion while penalizing validated, lifesaving models whose nonlinear math resists "deliberately rough" prose [P4.3]. Courts protect people by enforcing tailored statutes and auditing systemic outcomes, not by mistaking plausible boilerplate for justice.
