# Debate prop_0621__claude-fable-5-high__hy4-preview-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: claude-fable-5-high
- model_con: hy4-preview-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-high
- raw_words: 330
- clipped_words: 330
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When the state moves to cage a human being, every instrument it uses to justify that caging must be open to challenge. That principle is centuries old. A defendant can cross-examine the officer, subpoena the lab analyst, and inspect the breathalyzer's maintenance logs. Yet today, a proprietary algorithm can label someone "high risk"—shaping whether they're charged harshly, denied bail, or given extra years—and the defense is told the tool's inner workings are a trade secret.
[P1.2] That is not a technical dispute. It is secret evidence, and secret evidence is incompatible with due process.
[P1.3] The proposition asks for three modest things: source code, training data summaries, and error rates. Notice what it doesn't require. It doesn't ban these tools. It doesn't demand raw datasets that might implicate privacy.
[P1.4] It requires disclosure—the minimum condition for adversarial testing, which is the entire mechanism by which our system separates reliable evidence from junk.
[P1.5] Why does this matter concretely? Risk tools are trained on historical data, and historical criminal justice data encodes historical policing patterns. A tool trained on arrest records in over-policed neighborhoods will flag people from those neighborhoods as riskier—not because they are, but because they were watched more. Journalistic investigations of widely used tools like COMPAS have found troubling racial disparities in false-positive rates.
[P1.6] Without disclosure, no defendant can raise that argument, no court can evaluate it, and no vendor faces pressure to fix it. Secrecy doesn't just hide errors; it removes the incentive to correct them.
[P1.7] The standard objection—trade secrets—collapses on inspection. Courts routinely handle sensitive material through protective orders and sealed review. If a vendor's business model cannot survive scrutiny by the very people its product helps imprison, that model has no place in a courtroom. We would never accept a forensic lab that refused to reveal its methods.
[P1.8] An algorithm deserves no gentler treatment simply because its errors are written in code rather than committed by hand.
[P1.9] Sunlight here isn't a burden on justice. It's the precondition for it.

## Turn 2: CON Opening

- model: hy4-preview-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.8], [P1.4], [P1.7]
- missing_claim_id_refs: (none)

[C1.1] PRO says an algorithm “deserves no gentler treatment” simply because its errors are written in code [P1.8]. I agree with the principle but reject the remedy: this motion mistakes performative disclosure for real accountability.
[C1.2] Its first error is aiming at the wrong actor. Prosecutors license risk tools; they do not own the source code and often cannot lawfully obtain training data. Forcing them to disclose those materials does not pry them from a vendor’s vault. It only puts the prosecutor in an impossible position: breach a contract, abandon the tool, or be sanctioned for not producing what the vendor holds.
[C1.3] That is a discovery trap, not due process—and it will drive validated instruments out of the courtroom.
[C1.4] PRO calls source code the “minimum condition for adversarial testing” [P1.4]. It is not. Dumping a million lines of code and a training summary on a public defender does not show whether the score is reliable here. Raw error rates without base rates, thresholds, or subgroup sample sizes are actively misleading.
[C1.5] The real test is pre-deployment validation, independent auditing, and published subgroup performance. A breathalyzer’s logs matter because they show whether that machine worked that night; a risk score is not a measurement of the defendant but a group-based research estimate. The right analogy is a sentencing study, not a lab report. What counts is competent design and judicial notice, not whether defense counsel can re-estimate the model.
[C1.6] This mandate would not expose bias; it would bury it. Defense offices lack the expertise to audit source code, hearings would stall over statistics, and defendants—the very people PRO claims to help—would sit in jail longer waiting for experts to decode material the prosecutor never needed to produce. Trade secrets do not “collapse” [P1.7]; they constrain supply. If we want better tools, certify them before they reach a prosecutor.
[C1.7] Forcing disclosure of code isn’t sunlight; it’s theater.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.5], [C1.2], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] Notice what CON just conceded. They endorse "independent auditing and published subgroup performance" [C1.5]. Published subgroup performance *is* error-rate disclosure. Training data summaries are what auditors audit.
[P2.2] CON has quietly agreed to two-thirds of the motion and is really fighting only over source code—while pretending to oppose the whole thing.
[P2.3] Now the "wrong actor" objection [C1.2]. It inverts the mechanism. The motion doesn't punish prosecutors for what vendors withhold; it conditions *use* on disclosure. If the vendor refuses, the prosecutor simply cannot deploy the tool—exactly as a prosecutor cannot introduce a lab result from a lab that refuses to reveal its methods.
[P2.4] And because prosecutors collectively are the entire market for these tools, that condition reshapes vendor behavior overnight: disclose or lose every customer. That's not a discovery trap. It's procurement leverage in the service of due process. Tellingly, open alternatives already exist—the publicly available pretrial assessment tools that publish their factors and weights prove secrecy is a business choice, not a technical necessity.
[P2.5] CON's alternative—pre-deployment certification—answers the wrong question. Who certifies? On what data? Certification without adversarial access means vendors grade their own homework, and history is unkind to that model: certified forensic labs have produced catastrophic scandals precisely because ex ante approval replaced ongoing scrutiny.
[P2.6] Our system trusts cross-examination over credentialing for a reason. And when courts *have* compelled disclosure of forensic source code, defense experts have found genuine flaws that certification missed.
[P2.7] CON's most revealing move is [C1.5]: a risk score is "not a measurement of the defendant but a group-based research estimate." Exactly. Research gets peer review, and peer review means methods and data are disclosed. CON's own framing makes secrecy indefensible—you cannot call something a study and then exempt it from the norms of science.
[P2.8] Finally, "defense offices lack expertise" [C1.6] is paternalism, not policy. One competent audit of one tool serves thousands of defendants. Secrecy forces every defendant to fight blind, forever.

## Turn 4: CON Rebuttal 1

- model: hy4-preview-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [C1.5], [P2.3], [P1.3], [P2.4], [C1.4], [P2.5], [P2.8]
- missing_claim_id_refs: (none)

[C2.1] PRO’s “you conceded two-thirds” move [P2.1] conflates regulatory validation with criminal discovery. I endorsed “independent auditing and published subgroup performance” [C1.5]; that is pre-deployment expert transparency, not a prosecutor in every bail hearing handing over source code, training summaries, and error rates. Publishing an audited error rate as a certification condition is not empowering each defendant to relitigate the model. No concession; the clash is actor, timing, and remedy.
[C2.2] The “condition of use” argument [P2.3] is a bait-and-switch. PRO insisted the motion “doesn’t ban these tools” [P1.3], yet vendor refusal means the tool cannot be used. That is a de facto ban administered by vendors. If a vendor refuses, quits, or produces an unreadable dump, the prosecutor—not the vendor—is sanctioned.
[C2.3] Prosecutors are not the sole market; pretrial services, probation, and multiple jurisdictions buy these tools, so “collective leverage” [P2.4] is overstated. The existence of open tools does not mean every validated instrument can be opened without losing maintenance and investment.
[C2.4] The analogy still fails. A risk score is not a breathalyzer measurement of this defendant; it is a group-based actuarial estimate. Code disclosure does not tell a court whether the score is reliable for this person. And raw “error rates” without thresholds, base rates, and subgroup sample sizes are misleading [C1.4].
[C2.5] Peer review publishes methods and results; it does not hand counsel raw data and code, and cannot override privacy limits on training data from real cases.
[C2.6] Certification is not vendors grading their own homework if an independent auditor performs it, reviews the code and training summaries under secure conditions, and publishes re-audits. That answers “who certifies” [P2.5]. Most tellingly, PRO’s own line—“one competent audit of one tool serves thousands of defendants” [P2.8]—is our argument, not theirs. Audit once, publish validated rates, give defendants their score, factors, and those rates, and stop burying cases in code.
[C2.7] The motion buys theatrical discovery while sacrificing systematic accountability.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-high
- raw_words: 90
- clipped_words: 90
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: You now say the auditor should review "the code and training summaries under secure conditions" and give defendants "their score, factors, and those rates" [C2.6]—so which of the motion's three disclosures do you still actually oppose, and why isn't your scheme just the motion administered through a protective order?
[P3.2] Q2: When your certifier gets it wrong—as certified forensic labs repeatedly have—what concrete mechanism lets an individual defendant challenge a flawed tool in their own case, given you deny them access to the very materials that would prove the flaw?

## Turn 6: CON Pressure Questions

- model: hy4-preview-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.3], [P2.3], [P2.8]
- missing_claim_id_refs: (none)

[C3.1] Q1: Your motion "doesn’t ban these tools" [P1.3], yet a vendor refusal means "the prosecutor simply cannot deploy the tool" [P2.3]. If a vendor withholds code, how is that not a de facto ban—and why should the prosecutor be sanctioned for material they cannot obtain?
[C3.2] Q2: You concede "One competent audit of one tool serves thousands of defendants" [P2.8]; why does your motion compel each prosecutor, in each case, to produce code and training summaries, rather than the one-time published audit and validated rates you concede serve thousands?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.3], [C3.2], [C2.6]
- missing_claim_id_refs: (none)

[P4.1] A1: Conditioning use on disclosure is how every evidentiary foundation works—it is not a ban. A lab that refuses to reveal its methods cannot introduce its results; nobody calls that a "ban on lab testing." The choice sits with the vendor, and the prosecutor's obligation is trivially satisfiable: use a tool whose vendor discloses, or use none. No prosecutor is sanctioned for material they cannot obtain—the only consequence of non-disclosure is that the score doesn't enter the case, which is exactly the consequence for any evidence lacking foundation.
[P4.2] And CON's own [C2.3] undercuts the panic: if pretrial services and probation departments also buy these tools, vendors have every commercial reason to disclose rather than forfeit the prosecutorial market. Open instruments already prove disclosure and viability coexist.
[P4.3] A2: The motion requires disclosure, not bespoke per-case production. A vendor files its code and training summaries once—publicly or under a standing protective order—and every subsequent case simply references it. Marginal cost after the first filing: nearly zero. So CON's "each prosecutor, in each case" burden [C3.2] is a strawman of their own construction.
[P4.4] Here is the real difference between our positions: the "one competent audit serving thousands" is only possible *if the materials exist somewhere the defense can reach*. Under the motion, they do. Under CON's scheme, they sit exclusively with a certifier—and when the certifier errs, as certified forensic labs repeatedly have, no defendant can ever prove it.
[P4.5] That answer is the whole debate. CON has conceded error rates should be published, factors given to defendants, and code reviewed under secure conditions [C2.6]. What remains is one question: when the official checker fails, may the accused check the checker? CON says no—trust the audit.
[P4.6] Our entire adversarial tradition says yes, because credentialed gatekeepers fail and cross-examination is the backstop. The motion gives you certification *plus* that backstop. CON offers certification alone, with the defendant locked out precisely when it matters most.

## Turn 8: CON Rebuttal 2

- model: hy4-preview-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [C1.5], [C2.6], [P2.3], [P4.5], [P4.3], [P4.1], [C1.2], [C3.1], [C2.2], [C1.4], [C1.6]
- missing_claim_id_refs: (none)

[C4.1] A1: I oppose prosecutorial disclosure of source code and training-data summaries; I have always endorsed published, contextualized error rates [C1.5], [C2.6]. That is not the motion behind a protective order. The motion forces the prosecutor to obtain and turn over those materials, conditioning use on vendor surrender, so a refusal excludes the score—a vendor-administered de facto ban [P2.3]. My auditor keeps the code and summaries under secure conditions; the prosecutor never holds them, and no case collapses because a vendor says no. A protective order still compels production of unreadable code; audited subgroup rates are what matter.
[C4.2] A2: The mechanism is the published audit, the defendant’s score and factors, and audited error rates [C2.6]. A defendant proves a group-based estimate unreliable by showing certified rates or inputs are wrong, not by reading software. When a certifier errs, the flaw appears in public rates and outcomes; any defendant can exclude it using that validation, and one exposed flaw triggers re-audit and protects everyone. That is not blind trust [P4.5]; forensic scandals are caught by scrutinizing published results, not code.
[C4.3] PRO concedes the motion is not per-case production because a vendor files once [P4.3]. That destroys the “adversarial testing in my case” rhetoric. PRO wants a filing defense experts may reach; that is upstream certification plus access to validated rates—my scheme, except routed through the prosecutor and contingent on vendor cooperation [P4.1]. That is the flaw: the prosecutor licenses tools, cannot seize vendor code, yet is sanctioned when the score is excluded [C1.2], [C3.1].
[C4.4] If vendors refuse, we lose validated instruments—a de facto ban no protective order cures [C2.2].
[C4.5] So weigh the remedies. For a group-based estimate, PRO’s code plus raw summaries is theatrical; my published rates, score, and factors are the real check [C1.4]. PRO’s backstop favors defendants who can hire experts, while others sit in jail longer [C1.6]. The accused need audited sunlight, not a million lines of code.

## Turn 9: PRO Closing

- model: claude-fable-5-high
- raw_words: 193
- clipped_words: 193
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.2], [P4.3]
- missing_claim_id_refs: (none)

[P5.1] This debate has narrowed to a single question: when the official checker fails, may the accused check the checker?
[P5.2] CON's final answer is that flaws "appear in public rates and outcomes" [C4.2]. But who computes those rates? The same certifier who approved the tool. That is circular: the only evidence a defendant may use to challenge the audit is the audit itself.
[P5.3] A defendant who suspects the certified rates are wrong has, under CON's scheme, no path to prove it—the code and training summaries sit in a vault they may never open. That is trust-the-auditor all the way down, and certified forensic labs have shown us exactly how that story ends.
[P5.4] The motion gives you everything CON wants—audits, published rates, scores and factors—plus the one thing CON withholds: adversarial access when the gatekeeper errs. Certification with a backstop beats certification alone, always.
[P5.5] And the cost? A one-time filing per tool [P4.3]. The "ban" is just evidentiary foundation: evidence that refuses scrutiny doesn't come in. We have never called that a ban; we call it due process.
[P5.6] Secret evidence with a certified stamp is still secret evidence. The accused deserve the backstop. Vote PRO.

## Turn 10: CON Closing

- model: hy4-preview-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: [P4.1], [C1.2], [C2.2], [C4.4], [C1.5], [C2.6], [C4.2], [P5.2], [P4.3], [C1.6], [C4.5]
- missing_claim_id_refs: (none)

[C5.1] The motion loses on one decisive point: it commands the prosecutor to produce what only a vendor holds. PRO says non-disclosure merely means “the score doesn’t enter the case” [P4.1]. But that “foundation” is a vendor-administered de facto ban: prosecutors license tools, cannot seize source code or training data, and lose validated instruments whenever a vendor says no [C1.2], [C2.2], [C4.4]. The state is punished for another party’s refusal.
[C5.2] That duty is also mistargeted. A risk score is a group-based actuarial estimate, not a breathalyzer reading of this defendant [C1.5]. The operative check is pre-deployment validation: published subgroup rates, the defendant’s score and factors, and re-audit when outcomes diverge [C2.6], [C4.2]. That is not circular [P5.2]; the audit is tested against case results, not the auditor’s word.
[C5.3] PRO’s “backstop” is theatrical. After a one-time filing [P4.3], only a defendant who can hire a software expert can use it; everyone else waits in jail while cases stall [C1.6]. The accused need the audited rates, score, and factors that make an actuarial estimate contestable—not a prosecutor forced to surrender software text [C4.5]. CON wins: published rates and re-audit protect everyone; the motion trades validated tools for discovery only the well-resourced can decode.
