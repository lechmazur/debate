# Debate prop_0621__hy4-preview-high__glm-5-2__s1__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: hy4-preview-high
- model_con: glm-5-2
- side_swap: True

## Turn 1: PRO Opening

- model: hy4-preview-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every day the government asks a judge to take someone's freedom because a black box says "high risk." That recommendation may shape the charge, bail, or sentence. Yet the defense often cannot see the code, data, or error rates behind it. That secrecy cannot coexist with due process.
[P1.2] The state's recommendation is not neutral arithmetic; it is an opinion about dangerousness dressed in numbers. In ordinary forensic contexts, the adversary system does not let the prosecution present a result while hiding methodology, error rates, and underlying data. A risk tool should be no different. If prosecutors want a judge to rely on it, they must expose it to adversarial testing.
[P1.3] Source-code disclosure, under a protective order when needed, reveals prohibited shortcuts and proxies. A model may never ask for race, but it can weight ZIP code, employment history, or family contacts that track race and poverty. Training-data summaries show whether the tool learned from biased enforcement—arrests that reflect policing patterns, not dangerousness. Error rates show whether "high risk" predicts anything real; if false positives are common, many people detained as dangerous were never going to reoffend.
[P1.4] Take two people arrested for the same low-level offense. One gets a high score because the algorithm quietly counts prior contacts concentrated in over-policed neighborhoods. Without the code and data, counsel cannot cross-examine the score; with them, counsel can show it measures disadvantage, not risk.
[P1.5] Trade-secret concerns are real but manageable. Courts already use protective orders, sealed filings, and restricted expert review. The alternative is worse: the defendant must disprove a secret instrument while the government enjoys its persuasive force.
[P1.6] The clash is simple. Either the state proves its case with evidence the defense can test, or it outsources punishment to a proprietary oracle. Requiring source code, data summaries, and error rates does not ban risk tools; it restores the baseline rule of criminal law—no secret evidence, no secret sentencing.

## Turn 2: CON Opening

- model: glm-5-2
- raw_words: 284
- clipped_words: 284
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition demands a categorical disclosure regime: source code, training data summaries, and error rates for every algorithmic risk tool used at any stage of a criminal case. That absolute mandate is the problem—not the concept of accountability.
[C1.2] "Any algorithmic risk tool" sweeps in everything from a published actuarial checklist with peer-reviewed methodology to a proprietary neural network. A tool whose methods are already transparent would still face mandatory source-code litigation—wasteful duplication that burdens prosecutors without advancing any defense.
[C1.3] More seriously, mandatory source-code disclosure is a demand to surrender core intellectual property in every prosecution. Protective orders mitigate but cannot eliminate leakage, reverse engineering, and competitive harm across hundreds of cases. If the rule is that selling a risk tool to the justice system means handing over your IP to defense experts in every case, many developers will simply exit the market. The result: fewer validated tools, more decisions made on untested judicial intuition, and a system that is less transparent—not more.
[C1.4] The proposition also mischaracterizes what a risk score is. It is a decision-support instrument, not forensic evidence the prosecution must authenticate like a DNA match. The judge remains the decisionmaker. We do not demand source code for the software prosecutors use to manage case files, even though it shapes charging decisions.
[C1.5] The relevant question is whether the tool's outputs are validated—not whether counsel can recompile the software.
[C1.6] Existing law already provides mechanisms for meaningful challenge: discovery obligations, expert testimony standards, and pretrial scrutiny of scientific evidence can require error rates and validation data when they genuinely matter. A blanket mandate that treats every tool and every use identically sacrifices proportionality for the appearance of transparency—and risks dismantling useful instruments in the process.

## Turn 3: PRO Rebuttal 1

- model: hy4-preview-high
- raw_words: 322
- clipped_words: 322
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.1], [C1.2], [C1.3], [C1.5], [C1.4], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The opponent's complaint is not that disclosure is unworkable; it is that accountability has a price. That price is worth paying whenever a risk tool shapes charging, bail, or sentencing. Liberty is no place for "proportionality" that asks a defendant to trust what the state will not explain.
[P2.2] The "categorical" objection [C1.1], that "any algorithmic risk tool" sweeps too broadly [C1.2], collapses on inspection. The trigger is narrow but firm: if the government cites an algorithmic output to justify taking freedom, the defense may test it. If the tool is a published checklist, disclosure is only a few pages. For a proprietary model, the burden is the point: a secret instrument should not carry the state's persuasive force.
[P2.3] Transparency for the already-transparent is cheap; secrecy for the black box defeats adversarial testing.
[P2.4] The trade-secret parade [C1.3] is speculative and backwards. Protective orders, sealed review, and restricted expert access are ordinary. If vendors exit rather than face scrutiny, their product has failed the same test we apply to breathalyzers or forensic methods. The state can procure auditable tools.
[P2.5] It cannot make defendants pay for corporate convenience with pretrial detention.
[P2.6] The opponent says the real question is whether outputs are "validated" [C1.5]. Exactly—and error rates and training-data summaries are the validation. A vendor's claim is not evidence. If a tool labels someone high-risk and its disclosed error rate shows many false positives, the score is little better than a coin flip with a jail order attached.
[P2.7] Nor is this like case-management software [C1.4]. That stores files; a risk tool asserts a prediction the state asks a judge to trust. Existing discovery [C1.6] leaves this to prosecutorial discretion and defense resources; our mandate closes the gap. The clash is not openness versus innovation.
[P2.8] It is evidence in daylight versus secret influence. Disclose the source code, training data summaries, and error rates—under seal if needed—and the government may use any tool it is willing to defend.

## Turn 4: CON Rebuttal 1

- model: glm-5-2
- raw_words: 271
- clipped_words: 271
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.4], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] The breathalyzer analogy in [P2.4] is my opponent's strongest point—and it defeats their own case. We do not require source-code disclosure for breathalyzers in every prosecution. We require calibration records, validation studies, and demonstrated error rates. We test the instrument's performance, not its implementation details.
[C2.2] That is exactly the accountability regime I endorsed in my opening—and it stops well short of the proposition's source-code mandate.
[C2.3] This exposes the core overreach. PRO concedes that "error rates and training-data summaries are the validation" [P2.6]. If validation is the goal, validation evidence is the remedy. Source code serves a different function: hunting for implementation bugs through line-by-line audit.
[C2.4] That is a legitimate but extraordinary remedy, not a categorical one—and courts can already order it when specific evidence of a software defect gives reason to look deeper.
[C2.5] The proposition bundles three disclosure types as if they rise or fall together. They do not. Error rates and data summaries can be produced without surrendering intellectual property; source code cannot. Bundling them forces an all-or-nothing choice when the proportional middle—validation evidence as a default, code as an exceptional remedy—is already available and already working.
[C2.6] PRO says vendors who exit "failed the same test we apply to breathalyzers" [P2.4]. But breathalyzer manufacturers sell widely without handing over source code to every defense expert. They survive because the accountability regime targets outputs, not internals. The proposition replaces that workable standard with one no forensic instrument currently meets.
[C2.7] The clash is not daylight versus secrecy. It is proportional accountability versus a mandate so broad it would dismantle the very tools that bring consistency to a system that badly needs them.

## Turn 5: PRO Pressure Questions

- model: hy4-preview-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say code is disclosed only after defense shows "specific evidence of a software defect" [C2.4]. If the state hides the code, how can defense find that defect to trigger your "exceptional remedy" [C2.5], making it a catch-22?
[P3.2] Q2: You accept disclosing error rates and data summaries as the "proportional middle" [C2.5]. But if the tool weights ZIP code as a race proxy, don't those summaries miss the proxy while only the code exposes it?

## Turn 6: CON Pressure Questions

- model: glm-5-2
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.4], [P2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: You invoke breathalyzers [P2.4], but breathalyzer makers don't hand source code to every defense expert—they disclose calibration and error rates. If that regime works for the paradigmatic forensic instrument, doesn't your proposition demand more than any current forensic standard requires?
[C3.2] Q2: You concede error rates and data summaries "are the validation" [P2.6]. Since those achieve validation without IP surrender, what does mandatory source code in every case add that justifies the market-exit risk you call speculative?

## Turn 7: PRO Rebuttal 2

- model: hy4-preview-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.5], [P3.1]
- missing_claim_id_refs: (none)

[P4.1] A1: The breathalyzer comparison proves my point. A breathalyzer measures a biological quantity through known physics, and its accuracy is checked with a known sample. A risk tool converts inputs like ZIP code and employment into an opinion about future dangerousness. That weighting and feature engineering is the model's methodology.
[P4.2] Calibration and error rates alone do not reveal it. Demanding the model is not exceeding forensic standards; it is applying the same rule: disclose the method you ask the court to trust. Under a protective order, this is ordinary, not public surrender.
[P4.3] A2: Error rates and training summaries are necessary but incomplete; they show performance, not mechanism. A summary may list a neighborhood variable; only the code shows whether the model treats it as a proxy for race or poverty. Two tools can share error rates yet rest on validated factors or policing patterns. So summaries miss the proxy I identified earlier; code is not mere bug-hunting.
[P4.4] Market-exit fear is speculative: vendors accept audit in regulated fields, and the state can procure public, auditable models. A vendor unwilling to defend its methodology under seal has no claim to shape bail or sentencing.
[P4.5] These answers expose the flaw in CON's "proportional middle" [C2.5]. It makes validation the default and code an exceptional remedy triggered by a shown defect, yet the defense cannot show a defect inside a hidden model—the catch-22 from [P3.1]. The state would enjoy the tool's persuasive force while the defense trusts an average error rate it cannot decompose. That is secret influence, not adversarial testing.
[P4.6] The debate reduces to one choice: either the government may rest a liberty deprivation on an instrument the defense can test, or it may outsource punishment to a proprietary oracle. Protective orders answer IP; they do not remove the need to see the mechanism. Source code, data summaries, and error rates are the minimum required to test a predictive instrument. That is why PRO still wins.

## Turn 8: CON Rebuttal 2

- model: glm-5-2
- raw_words: 298
- clipped_words: 298
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P3.1], [P3.2], [P1.4], [P4.3], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: The catch-22 [P3.1] assumes defense needs source code to suspect a problem. It doesn't. Defense experts can flag proxy risks from disclosed input features, cite published research on algorithmic bias, or show anomalous scoring in the case at hand. The trigger is reasonable suspicion of a defect, not proof of one—exactly the threshold courts already use for preliminary discovery orders.
[C4.2] That bar is reachable without the evidence it unlocks; otherwise no discovery regime could function.
[C4.3] A2: Training-data summaries expose race proxies without source code [P3.2]. A summary listing neighborhood, employment history, and prior contacts as input features lets an expert argue those variables track race and poverty. PRO's own example—the tool "quietly counts prior contacts concentrated in over-policed neighborhoods" [P1.4]—is a feature-selection problem, not an implementation-bug problem. Feature selection is visible in the summary; you don't need the code to argue a model weights disadvantage as risk.
[C4.4] PRO says only code reveals whether a variable is "treated as a proxy" [P4.3]—but if the summary shows the model uses that feature, the proxy challenge is already live.
[C4.5] These answers expose why the proposition still fails. It bundles source code with accountability measures that actually do the work. Data summaries expose what the model considers; error rates expose whether it predicts anything real; expert testimony connects the two. Source code audits implementation—line-by-line logic relevant only after a specific defect surfaces and a court orders deeper review.
[C4.6] PRO distinguishes breathalyzers by calling risk tools "opinions about dangerousness" [P4.1]. But that cuts against the mandate: opinions are challenged through their inputs and validation, not by auditing the calculator's internals. The proportional middle—validation evidence by default, code as a targeted remedy—achieves real accountability without forcing IP surrender in every case and risking the exit of validated tools for less testable judicial intuition.

## Turn 9: PRO Closing

- model: hy4-preview-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C2.5], [C4.5], [C4.4]
- missing_claim_id_refs: (none)

[P5.1] The debate turns on one choice: when the state would jail someone because an algorithm says “high risk,” may the defense test the tool’s reasoning, or only its résumé?
[P5.2] CON’s “proportional middle” [C2.5] gives error rates and data summaries but not code; [C4.5] says those do the work. That is not testing; it trusts the government’s description. A feature list is not a method. Two models can take ZIP code and prior contacts; one treats them as admin data, the other as a weighted race proxy.
[P5.3] The difference is the code’s coefficients, not the summary. CON calls the proxy challenge “already live” [C4.4], but defense can only cry foul, not prove why this person was flagged.
[P5.4] Withhold the mechanism and the state still gets the score’s persuasive force. The defendant is jailed, told to trust an error rate he cannot decompose. That is secret influence, not accountability.
[P5.5] Sealed disclosure is ordinary; a vendor that cannot defend its method has no claim to shape bail. The motion bundles the three because that is the minimum that lets defense test the instrument. The government may use any tool it will defend. PRO wins.

## Turn 10: CON Closing

- model: glm-5-2
- raw_words: 200
- clipped_words: 200
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.2], [P5.5], [P2.6]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing betrays the flaw. [P5.2] says a feature list "is not a method" because two models weight the same inputs differently. But that proves too much. If the weights are the problem, disclosed coefficients and validation results expose them—without surrendering the implementation logic that constitutes the vendor's intellectual property.
[C5.2] The proposition demands source code in every case. PRO never explains why a targeted order—available when defense shows that feature weighting raises proxy concerns—is insufficient. Instead, [P5.5] insists the bundle is "minimum." But PRO already conceded error rates and data summaries "are the validation" [P2.6].
[C5.3] What source code adds is line-by-line implementation audit, which serves bug-hunting, not proxy-detection.
[C5.4] That is why the mandate fails. It treats every tool and every case identically, forcing IP surrender where no defect is suspected and no proxy challenge is live. Vendors who sell validated tools without blanket litigation risk exit; judges fall back on untested intuition. The defendant PRO wants to protect gets less transparency, not more.
[C5.5] Accountability means the defense can test what the court relies on. Existing law already provides that—through disclosed features, error rates, and targeted code review when specific concerns arise. The proposition trades a working system for a slogan.
