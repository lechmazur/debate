# Debate prop_0666__qwen3.8-max__gpt-5.6-high__s1__tpl_placement_active_20260320f

- topic_id: prop_0666
- proposition: Courts should recognize a limited “right to explanation” when automated systems significantly affect access to housing, credit, employment, or healthcare.
- model_pro: qwen3.8-max
- model_con: gpt-5.6-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen3.8-max
- raw_words: 303
- clipped_words: 303
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A person denied an apartment by a tenant-screening score, or a loan by a credit model, often cannot tell whether the cause was bad data, unlawful proxy discrimination, or a statistical artifact. Without a reason, the decision is unreviewable. Courts should recognize a limited right to explanation: not source code or trade secrets, but enough meaningful information—inputs, key factors, data sources, and their role—to let the affected person test legality and accuracy. This is not a right to perfect interpretability; it is a right to contestability.
[P1.2] This is a modest extension of familiar legal commitments. Courts already insist that when the state or regulated actors deprive people of important benefits, they give notice and a reason. Where statutes lag, courts can enforce this baseline case by case. Automated systems should not get a free pass because they are proprietary or technical.
[P1.3] In housing, credit, employment, and healthcare, these systems do not merely advise; they allocate access to opportunities essential for autonomy and survival. If a hospital triage tool deprioritizes a patient, or a hiring platform filters out applicants with employment gaps, the affected person deserves to know whether the result rests on a prohibited or erroneous basis.
[P1.4] The “limited” qualifier is decisive. Courts can tailor the duty: require explanations proportional to impact, protect confidential methods through summaries or in camera review, and allow plaintiffs to meet initial burdens with inference before shifting explanation duties. That answers concerns about burden and trade secrets without surrendering accountability.
[P1.5] The real alternative is black-box adjudication. If courts refuse even a minimal explanation, they convert opacity into immunity. A company can say “the model said no,” and the injured party cannot show error, bias, or illegality. A limited right preserves the possibility of legal review when automated power decides who gets a home, a job, credit, or care.

## Turn 2: CON Opening

- model: gpt-5.6-high
- raw_words: 352
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A “limited” right with no limiting principle is not modest. What counts as an automated system, a significant effect, or a meaningful explanation? A hospital may combine a risk score with clinical judgment; an employer may use software only to rank thousands of applications. Courts would have to invent which actors are covered, what must be disclosed, when causation is sufficient, and what remedy follows.
[C1.2] Those are policy choices with major economic and technical consequences, not a baseline courts can coherently derive.
[C1.3] An explanation also does not create the “contestability” PRO promises. Many models do not generate a single human-style reason; outcomes can reflect interactions among numerous variables. Requiring “key factors” pressures firms to produce simplified, post hoc narratives that sound intelligible but do not reveal whether the system is accurate or discriminatory. Individual explanations are especially weak against systemic bias: telling an applicant that income, employment history, and location mattered cannot establish whether the model disadvantages a protected group across thousands of cases.
[C1.4] The duty would also impose real countervailing harms. Detailed disclosures can expose other people’s data, reveal fraud-detection methods, enable strategic gaming, and compromise proprietary systems. In healthcare, defensive explanation requirements could make providers hesitate to use useful decision-support tools. Compliance costs will fall hardest on smaller lenders, clinics, landlords, and employers, encouraging standardized denials or withdrawal from marginal applicants rather than more individualized access. “In camera review” merely transfers technical evaluation to judges and expensive experts; it does not make the underlying tradeoffs disappear.
[C1.5] Opacity is not immunity. Courts can enforce statutory notice duties, anti-discrimination law, contract rules, and constitutional due process where state action exists. Through ordinary discovery, they can order targeted production when a legally grounded claim is brought. Regulators and legislatures can require sector-specific notices, audits, validation, and confidentiality safeguards with clear definitions and technical expertise.
[C1.6] That is superior to judicially creating one vague right across four radically different fields.
[C1.7] The choice is not accountability versus secrecy. It is accountable, tailored law versus an indeterminate judicial mandate that may generate plausible-sounding explanations [clipped]

## Turn 3: PRO Rebuttal 1

- model: qwen3.8-max
- raw_words: 306
- clipped_words: 306
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.3], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON’s main strategy is to treat a limited right as an unlimited one. But the proposition supplies the limiting principle: it applies only to housing, credit, employment, and healthcare; only where an automated system significantly affects access; and only to enough information to test legality and accuracy, not source code. Courts already draw lines like “significant,” “meaningful,” and “proportional” in due process, discovery, and unfair-practices cases. Refusing to do so here would not preserve judicial restraint; it would let opacity defeat the legal claims courts already recognize.
[P2.2] CON says explanations cannot create contestability because models are complex [C1.3]. That proves too much. A denied tenant does not need a full causal map to know if the screening file attributes another person’s eviction to her, or if a lender’s explanation shows ZIP code dominating the decision. Those facts let a person correct error or raise a proxy-discrimination inference.
[P2.3] And individual explanations are often the first step toward systemic proof: without knowing which variables matter, plaintiffs cannot identify patterns, frame discovery, or show disparate impact. CON’s alternative leaves systemic bias perfectly hidden.
[P2.4] The burden and secrecy objections are answered by the motion’s own limits. Courts can require summaries, not trade secrets; redact or use in camera review; and scale the explanation to the decision’s stakes. A small landlord using a screening report can disclose the report’s source and principal adverse items without revealing proprietary weights. What CON calls “countervailing harms” mostly assumes maximum disclosure, not the limited duty actually proposed.
[P2.5] Finally, CON’s reliance on existing discovery is circular [C1.5]. A plaintiff cannot plead enough facts about a model she cannot see. If the only evidence needed to state a claim is locked inside the defendant’s system, ordinary discovery never begins. A limited right to explanation is not judicial policymaking; it is the minimum condition for law to operate.

## Turn 4: CON Rebuttal 1

- model: gpt-5.6-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO calls four sectors and two adjectives a limiting principle, but neither “significantly affects” nor “enough information” decides the hard cases. Does a ranking count when a manager makes the final choice? Must a hospital explain a tool that altered urgency but not treatment? Courts can apply flexible standards when legislation supplies purpose, coverage, and remedies.
[C2.2] That familiar task does not justify creating the substantive duty whose boundaries are precisely disputed.
[C2.3] Their examples collapse correction into explanation. If a screening file contains another person’s eviction, the useful remedy is access to and correction of that record; a list of “key factors” may not reveal the mismatch. If ZIP code mattered heavily, that fact alone establishes neither unlawful proxy use nor inaccuracy; geography may correlate with lawful considerations. Actually testing a model’s accuracy or systemic bias requires validation methods, comparison groups, and aggregate outcomes—not an individualized narrative.
[C2.4] The supposedly limited version is inadequate; the adequate version becomes the technical audit PRO disclaims.
[C2.5] The discovery argument is therefore a false dilemma. Plaintiffs can ground claims in their own records, inconsistent treatment, communications, comparator evidence, or alleged patterns, then seek targeted production. Legal systems can also adjust pleading rules for facts uniquely held by defendants. PRO instead demands an explanation automatically after a covered outcome, before any factual basis for wrongdoing.
[C2.6] That is not preserving existing review; it creates a new disclosure regime.
[C2.7] Nor do “summaries” resolve the tradeoff. A summary vague enough to protect fraud controls, patient data, and model design may be useless; one detailed enough to support challenge creates the very exposure, gaming, and expert costs CON identified. In camera review gives information to a judge, not an explanation to the affected person, while adding expense.
[C2.8] PRO has not found a modest midpoint. It has renamed the unavoidable choice: either thin, potentially misleading reasons, or broad disclosure with consequences courts are poorly placed to design. That is why tailored legislation and sector regulation remain superior.

## Turn 5: PRO Pressure Questions

- model: qwen3.8-max
- raw_words: 57
- clipped_words: 57
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: Under [C2.5], how does a plaintiff obtain discovery when the only facts showing automated harm are held by the defendant and cannot be inferred from outside records?
[P3.2] Q2: If individual explanations are too thin to contest bias, how can a denied person ever start the case that would justify the aggregate audit you say is necessary?

## Turn 6: CON Pressure Questions

- model: gpt-5.6-high
- raw_words: 54
- clipped_words: 54
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: What legal principle empowers courts to impose a freestanding disclosure duty on private landlords, employers, lenders, and healthcare providers when no statute, contract, or state action requires one?
[C3.2] Q2: What specific information is sufficient to test systemic discrimination yet limited enough to avoid becoming the technical audit—and trade-secret, privacy, and gaming risk—you disclaim?

## Turn 7: PRO Rebuttal 2

- model: qwen3.8-max
- raw_words: 313
- clipped_words: 313
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The principle is not freestanding; it is the court’s ordinary power to make recognized legal protections enforceable and to stop undisclosed justifications from defeating them. Housing, credit, employment, and healthcare law already prohibit discriminatory, inaccurate, or arbitrary denials. When an automated system holds the only facts that can show those rights were violated, courts may impose a narrow, proportional disclosure burden as an ancillary remedy—just as they use discovery, burden-shifting, and adverse inferences when evidence is uniquely held by one party.
[P4.2] A2: The minimum is not a full audit. It is: the principal factors that drove the adverse result; the data sources and input values used; whether protected-class data, geography, or known proxies were included; the system’s role—score, ranking, or automatic cutoff—and any existing or readily producible validation or disparity statistics for that decision type. That gives a claimant enough to identify error or a proxy and frame targeted discovery, while withholding source code, training data, exact weights, and fraud rules.
[P4.3] It is disclosure for contestability, not redesign.
[P4.4] Those answers expose the decisive flaw in CON’s case. CON says plaintiffs can use ordinary discovery, but ordinary discovery requires a plausible claim; here, the facts needed to make the claim are inside the black box. If courts deny even this threshold information, they do not preserve legal neutrality—they make automated decisions effectively unreviewable. CON’s alternative is all-or-nothing: either no explanation until after a plaintiff somehow proves hidden automated bias, or a full technical audit.
[P4.5] The motion chooses the sensible middle: enough to start, not enough to steal the model.
[P4.6] That is why PRO wins. Our right is limited by sector, significance, and purpose. It protects trade secrets through summaries and in camera review. It enables correction of bad data and lets individuals trigger, rather than never reach, the aggregate proof CON says is required.
[P4.7] Opacity should not be a shield against the law.

## Turn 8: CON Rebuttal 2

- model: gpt-5.6-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: A plaintiff can plead facts on information and belief where key evidence is uniquely controlled by the defendant, using the adverse outcome plus available circumstances to seek targeted discovery. If literally nothing observable supports illegality—not the plaintiff’s records, communications, comparators, or patterns—then discovery may not begin.
[C4.2] But that threshold protects everyone from fishing expeditions; it does not justify compelling an explanation after every covered denial without any predicate of wrongdoing.
[C4.3] A2: A denied person can start with a demonstrable data error, inconsistent stated criteria, comparator evidence, testing, public patterns, or communications suggesting automation or discrimination. Regulators can investigate aggregate effects without depending on one applicant’s narrative. Where none of those exists, a list of “principal factors” still cannot establish systemic bias. It supplies suspicion, not the comparison needed to make discrimination plausible.
[C4.4] PRO’s latest specification proves our central objection. The proposed “minimum” now includes whether “known proxies” were used and any “validation or disparity statistics” that are readily producible. “Known proxy” has no stable boundary, and disparity statistics are aggregate model evaluation—not an explanation of one decision. Producing them requires choices about populations, outcomes, benchmarks, and confounders. The allegedly narrow right has already expanded toward the technical audit PRO says it avoids.
[C4.5] Their legal theory also conflates procedural authority with substantive authority. Discovery, burden-shifting, and adverse inferences operate inside a legally authorized claim. They do not empower courts to impose a standing disclosure obligation on every private employer, landlord, lender, or provider merely because existing law sometimes prohibits discrimination or error. Indeed, private decisions are not generally unlawful simply because PRO labels them “arbitrary.”
[C4.6] The decisive comparison remains unchanged. A thin factor list cannot test systemic legality and may falsely legitimize a complex decision. A sufficiently informative disclosure entails aggregate analysis, privacy judgments, gaming risks, and costly technical standards. Legislatures and sector regulators can define triggers, safeguards, and remedies; courts cannot manufacture those choices by calling them “ancillary.” Because PRO cannot identify a useful stopping point between empty narrative and audit, the proposed judicial right should be rejected.

## Turn 9: PRO Closing

- model: qwen3.8-max
- raw_words: 199
- clipped_words: 199
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive reason PRO wins is that CON’s rule makes the law unavailable when it is needed. CON says plaintiffs can plead on information and belief, use comparators, or wait for regulators. But when an automated screening, credit, hiring, or triage system holds the decisive facts, the denied person has no comparator, no communication, and no way to know whether the result came from wrong data, a prohibited proxy, or a hidden cutoff. CON demands proof before proof is obtainable.
[P5.2] That is not judicial restraint; it is letting black-box opacity defeat rights recognized in housing, credit, employment, and healthcare law. The proposition does not ask courts to design technology policy or order audits. It asks them to do what courts do when evidence is uniquely held by one party: impose a narrow, proportional disclosure duty sufficient to test legality and accuracy. Principal factors, data sources, and the system’s role can be disclosed through summaries, redactions, and in camera review while protecting secrets.
[P5.3] If CON prevails, a company can say “the model said no,” and the injured person cannot even begin. That converts legal protection into theoretical protection. Courts should recognize the limited right because without it, contestability is impossible.

## Turn 10: CON Closing

- model: gpt-5.6-high
- raw_words: 209
- clipped_words: 209
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The decisive flaw is that PRO cannot make this right both limited and legally useful. A list of principal factors, data sources, and the system’s role may show what was considered, but not whether the model was accurate, causally decisive, or discriminatory. “ZIP code mattered” creates suspicion, not proof. To bridge that gap, PRO added known proxies, validation, and disparity statistics—aggregate analysis whose meaning depends on comparison groups, benchmarks, and technical judgments. That is an audit regime, not an individual explanation.
[C5.2] PRO’s “proof before proof” slogan therefore misstates the choice. Courts can relax pleading when facts are uniquely held and then order targeted discovery based on observable circumstances. Requiring some predicate is what distinguishes adjudication from automatic investigation after every covered denial. If no record, comparator, communication, inconsistency, or pattern suggests illegality, inability to inspect a private model is not itself a legal injury.
[C5.3] Yet the motion asks courts to create that injury and design a cross-sector disclosure duty around it. Calling the duty “ancillary” cannot supply its triggers, safeguards, scope, or remedies. The thin version produces plausible narratives without testing legality; the useful version requires policy choices about privacy, trade secrets, gaming, costs, and statistical proof. Because PRO offers no stable midpoint, courts should not recognize this right.
