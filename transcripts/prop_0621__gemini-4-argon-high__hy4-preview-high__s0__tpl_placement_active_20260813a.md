# Debate prop_0621__gemini-4-argon-high__hy4-preview-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: gemini-4-argon-high
- model_con: hy4-preview-high
- side_swap: False

## Turn 1: PRO Opening

- model: gemini-4-argon-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a prosecutor asks a judge to deny bail, escalate charges, or lengthen a sentence based on an algorithmic risk score, the state is using software to take away human liberty. In any fair legal system, the accused has a foundational right to test the evidence used against them. Handing the defense a bare "high-risk" label without the machinery behind it turns the algorithm into an anonymous, uncross-examinable witness.
[P1.2] All three disclosures are necessary to make scrutiny real. First, source code reveals the exact rules and hidden bugs. Independent audits of courtroom software have uncovered basic programming mistakes that accidentally inflated risk scores, alongside heavy reliance on socioeconomic proxies that penalize poverty rather than measure danger. Without the code, nobody knows whether a score reflects validated science or a software typo.
[P1.3] Second, training data summaries show whether the model actually fits the defendant. Because this requirement asks for summaries rather than raw individual records, it protects privacy while exposing systemic skew. If a tool was trained on decades-old data from another jurisdiction, or treats arrests in heavily policed neighborhoods as proof of future violence, the defense must be able to expose that mismatch.
[P1.4] Third, error rates pierce the illusion of machine objectivity. A judge cannot responsibly weigh a "high-risk" label without knowing the false-positive rate—how often the tool is simply wrong, and whether its mistakes fall disproportionately on specific demographic groups.
[P1.5] Vendor profits and prosecutorial convenience cannot override human freedom. Private companies that choose to sell tools to the criminal justice system must not hide behind trade secrets when liberty is at stake; courts can easily use protective orders to let defense experts inspect code without exposing it to commercial competitors. Moreover, providing code, data summaries, and error rates is a standard baseline per software version, not a crushing case-by-case burden. If the state will not show how its algorithm works and how often it fails, it has no business using it to put people in cages.

## Turn 2: CON Opening

- model: hy4-preview-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.1], [P1.2], [P1.4]
- missing_claim_id_refs: (none)

[C1.1] The PRO case rests on a false metaphor. [P1.1] calls a risk score an "anonymous, uncross-examinable witness." But a risk instrument is not a witness; it is a statistical tool, like a breathalyzer or forensic assay. Defendants do not get the breathalyzer's schematics in every DUI; they get proof it was calibrated, validated for the use, and open to expert challenge.
[C1.2] The safeguard that actually protects liberty is pre-use validation and judicial gatekeeping, not forcing prosecutors to dump code, data sketches, and raw error numbers on the defense.
[C1.3] Code disclosure shows the error. [P1.2] says only code reveals bugs and poverty proxies. Most lawyers, defendants, and judges cannot read code; dumping it invites expert fishing and delay, not understanding. Bugs and proxy effects are exactly what independent pre-deployment audits and outcome testing already expose.
[C1.4] A jurisdiction should have to prove a tool passes rigorous validation before it affects liberty. That is stronger than making every prosecutor hand adversaries proprietary source that vendors will protect, and the likely result of the mandate is fewer audited tools and more reliance on unaided human discretion, which is more variable and harder to challenge.
[C1.5] The same context problem sinks the other two items. A training "summary" is not a validation study; it sparks completeness fights while hiding whether the tool works here. [P1.4] treats a false-positive rate as a cross-examinable fact about a witness. In truth, one error number without base rates, thresholds, and local outcomes is a sound bite: a 30 percent false-positive rate can be alarming or trivial depending on context, and risk tools yield group probabilities, not individual verdicts.
[C1.6] Forcing this disclosure turns every case into a statistical trial within a trial, with no standard for when the numbers are good enough, and it burdens prosecutors for material that vendors, not the state, control. The mandate would thus produce the appearance of transparency while undermining real accountability.

## Turn 3: PRO Rebuttal 1

- model: gemini-4-argon-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.1], [C1.2], [C1.3], [P1.5], [C1.6], [C1.5], [C1.4]
- missing_claim_id_refs: (none)

[P2.1] CON’s case rests on a false analogy: that a risk algorithm is just like a breathalyzer ([C1.1]). A breathalyzer measures a physical molecule using universal chemistry. A risk algorithm predicts human behavior by encoding subjective policy choices—like how heavily to weight arrests in heavily policed neighborhoods or socioeconomic status. Worse for CON, when courts have allowed defense experts to inspect breathalyzer and forensic software code, they uncovered serious programming bugs that routine calibration and pre-use validation missed.
[P2.2] That exposes CON’s substitute of "pre-use validation and judicial gatekeeping" ([C1.2]). Adversarial gatekeeping requires two informed sides. If the defense cannot see the code, training summaries, or error rates, gatekeeping is just a judge rubber-stamping a vendor’s brochure. Nor does disclosure fail because "lawyers cannot read code" ([C1.3]).
[P2.3] Lawyers cannot sequence DNA either; they use experts to inspect complex evidence and explain it in court. And because code, training summaries, and error rates are fixed per software version ([P1.5]), this does not create a new statistical trial in every case ([C1.6]). Prosecutors disclose a standard packet per version, letting defense offices audit the tool once and raise targeted challenges when flaws affect their client.
[P2.4] That individualized defense is why pre-deployment audits ([C1.3]) are insufficient. A tool might pass general validation on urban adults, yet be invalid as applied to a rural teenager. Without training data summaries, the defense cannot expose that mismatch. Similarly, CON’s claim that a single error number lacks context ([C1.5]) is a reason to disclose comprehensive error rates across thresholds and demographics—not to hide how often the tool fails while liberty is on the line.
[P2.5] Finally, the state cannot outsource its duty of fairness to private vendors ([C1.6]). Governments can require disclosure in procurement contracts using protective orders ([P1.5]). And if a vendor would rather walk away than let experts verify its math ([C1.4]), courts are far better off with accountable human judgment than a secret algorithm laundering bias behind a veneer of machine objectivity.

## Turn 4: CON Rebuttal 1

- model: hy4-preview-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.3], [P2.1], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] The PRO’s case quietly shifts from system transparency to a case-by-case prosecutorial duty. If, as [P2.3] concedes, code, summaries, and error rates are "fixed per software version," the cure is a public validation dossier produced once by a regulator or court—not a discovery obligation riding into every charging, bail, or sentencing decision. A "standard packet" is still dumped on prosecutors in every prosecution for material vendors control. A public dossier also spares each prosecutor from guarding trade secrets in every courtroom while still giving defense the validated metrics.
[C2.2] PRO answers our breathalyzer analogy by saying bugs surfaced "when courts have allowed defense experts to inspect" code ([P2.1]). That is the point: inspection came through targeted, court-supervised admissibility challenges, not automatic disclosure in every DUI. Defendants already receive proof a tool was calibrated, validated, and fit for use; a vendor brochure never suffices. Foundation rules, not source dumps, prevent rubber-stamping.
[C2.3] Court-appointed experts can already test validated tools under those rules.
[C2.4] Their "rural teenager" hypothetical ([P2.4]) shows why training summaries are the wrong instrument. If a tool is invalid as applied, the defendant can force the state to prove local validity; outcome studies answer that, while data provenance invites completeness fights. Likewise, PRO’s demand for "comprehensive error rates across thresholds and demographics" ([P2.4]) intensifies the flaw we identified: without a rule for which subgroup or threshold controls, any slice can be made alarming, and every case becomes a statistical trial with no standard for "good enough."
[C2.5] Finally, PRO invites vendors to walk, leaving "accountable human judgment." That is not accountability; unaided discretion is less measurable and harder to challenge than an auditable tool. Human judgment yields no calibration curve or disparate-impact test; algorithms can be audited. The proposition would replace validated risk metrics with unmeasurable discretion while pretending to create transparency.
[C2.6] The wiser rule targets the real safeguard: pre-use validation, judicial gatekeeping, and system-wide publication—not mandatory disclosure in every case.

## Turn 5: PRO Pressure Questions

- model: gemini-4-argon-high
- raw_words: 89
- clipped_words: 89
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.4], [C2.1], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You argue defendants can bring "targeted, court-supervised admissibility challenges" ([C2.2]) when a tool is "invalid as applied" ([C2.4]). How can the defense ever make the threshold showing to trigger that inspection when the code, training summaries, and error rates are hidden beforehand?
[P3.2] Q2: You propose a one-time "public validation dossier" ([C2.1]) so tools "can be audited" ([C2.5]). If that dossier omits code, training summaries, and error rates, how can anyone check for bugs or demographic skew—and if it includes them, how does sharing a pre-made file burden prosecutors?

## Turn 6: CON Pressure Questions

- model: hy4-preview-high
- raw_words: 89
- clipped_words: 89
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.4], [C2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You concede the mandated disclosures are a fixed “standard packet” per version ([P2.3]). If the defense can audit the tool once, why must each prosecutor disclose the packet in every charging, bail, and sentencing decision, instead of a regulator or vendor publishing one system-wide dossier?
[C3.2] Q2: You demand comprehensive error rates across thresholds and demographics ([P2.4]), but what benchmark—what false-positive rate or subgroup—makes a tool too flawed to use, and who applies it without turning every hearing into a statistical trial with no standard for “good enough” ([C2.4])?

## Turn 7: PRO Rebuttal 2

- model: gemini-4-argon-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: [C2.1], [C2.4], [C2.2], [C1.6]
- missing_claim_id_refs: (none)

[P4.1] A1: Prosecutors must hold this duty because in an adversarial system, accountability requires an enforceable courtroom remedy: disclose the packet, or drop the score. A regulator’s "public validation dossier" ([C2.1]) has no self-enforcing teeth in a bail hearing, and a regulator cannot post proprietary source code online. Case-level disclosure under a routine protective order solves both problems: it protects vendor trade secrets while letting defense experts inspect the exact software version used against their client. Because the packet is compiled once per version, sharing it electronically in discovery takes seconds.
[P4.2] A2: Judges apply the standard, using the same rules of reliability and prejudice that govern all scientific evidence—and crucially, they use error rates to assign weight, not just admissibility. Even when a tool is admissible, a judge deciding whether to jail someone must know whether a "high-risk" label carries a 10 percent or 60 percent false-positive rate for that defendant’s subgroup. Hiding error rates to avoid debate ([C2.4]) simply blinds the judge into treating shaky group probabilities as objective certainty.
[P4.3] These answers expose the fatal Catch-22 in CON’s counter-model. CON insists defendants can bring "targeted, court-supervised admissibility challenges" ([C2.2]) and test whether a tool is valid as applied ([C2.4]). But how can the defense ever make the threshold showing to trigger that challenge when the code, training summaries, and error rates are kept secret? Under CON’s rule, a defendant must prove the software is broken before being allowed to look at it.
[P4.4] Moreover, by proposing a one-time dossier ([C2.1]), CON concedes that compiling system-level metrics per version is entirely feasible, which destroys their claim of a crushing burden ([C1.6]). The real choice is whether "validation" means a black box blessed behind closed doors, or real adversarial testing. If an algorithm is reliable enough to take away human freedom, its code, training data summaries, and error rates can survive the light of a courtroom.

## Turn 8: CON Rebuttal 2

- model: hy4-preview-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [C2.1], [C2.4], [P4.3], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: The threshold showing comes from the state’s own public validation dossier ([C2.1]), which prosecutors must produce to lay a foundation. That dossier documents the tool’s validated scope, audited error rates, and outcome studies. If a rural teenager is scored, counsel points to the dossier’s own limits—say, validation only on urban adults—and shows the state has not proved local validity for this subgroup ([C2.4]). That is a specific as-applied challenge triggering court-supervised inspection, like a breathalyzer defendant using calibration records, not schematics.
[C4.2] There is no Catch-22: the defense never blindly proves broken code; the state must first show fitness, and the dossier supplies the mismatch.
[C4.3] A2: The dossier is not hollow. It includes audited error rates with necessary context—base rates, thresholds, subgroup outcomes—and independent pre-deployment audits, which is precisely how bugs and demographic skew are found; it simply omits source code. Bug-hunting happens in validation, not source code. Omitting code means no trade-secret protective orders in every courtroom, so prosecutors bear no burden guarding proprietary material.
[C4.4] Training-data summaries are omitted because they invite completeness fights ([C2.4]) and prove less. Thus the dossier is checkable where it matters—through error rates and audits—while sparing prosecutors case-by-case disclosure of code and data sketches.
[C4.5] These answers rebut [P4.3] and [P4.4]. PRO claimed a Catch-22 ([P4.3]), but the dossier gives defendants the tool’s documented limits and subgroup outcomes, so targeted challenges are triggerable without precase code dumps. PRO admits one system-wide file is feasible ([P4.4]), yet their motion still forces prosecutors to disclose proprietary source and training sketches in every charging, bail, and sentencing decision. That reintroduces the very trade-secret fights and expert fishing CON warned about, while PRO’s numbers have no benchmark for "good enough."
[C4.6] CON’s model delivers the real safeguard: validate before use, publish error rates and audits system-wide, and let judges weigh them. That protects liberty through accountable, auditable tools instead of replacing them with unaided discretion.

## Turn 9: PRO Closing

- model: gemini-4-argon-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.1], [C4.3], [P2.1]
- missing_claim_id_refs: (none)

[P5.1] In [C4.1] and [C4.3], CON makes a decisive concession: to use a risk score, "prosecutors must produce" a file containing subgroup error rates and population limits to lay a foundation in court. Once prosecutors are already disclosing that pre-made packet, CON’s entire argument about case-by-case burden evaporates.
[P5.2] The only remaining question is whether the state can hide the training data summaries and source code behind pre-deployment audits. It cannot, because pre-use validation is not infallible. When courts finally allowed defense experts to inspect validated courtroom software ([P2.1]), they uncovered serious coding bugs that routine audits missed.
[P5.3] Look at the fatal flaw in CON’s threshold rule ([C4.1]): what happens when a defendant matches the dossier’s approved population—an urban adult—but a hidden coding bug or skewed training proxy artificially doubles their risk score? Under CON’s rule, because the surface dossier shows no mismatch, the defense can never trigger code inspection. The bug stays buried, and someone goes to jail for a software typo.
[P5.4] Including source code and training summaries in that same discovery packet under a standard protective order costs nothing. Hiding them strips the accused of the right to test the machinery taking away their freedom.

## Turn 10: CON Closing

- model: hy4-preview-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.1], [P5.3], [C1.3], [C2.4], [C3.2]
- missing_claim_id_refs: (none)

[C5.1] PRO’s closing narrows this to one question: once the state produces the dossier CON concedes—audited error rates and population limits ([P5.1])—must it also surrender source code and training summaries? No.
[C5.2] Take PRO’s own story: an urban adult matches the dossier, but a hidden bug or skewed proxy doubles the score ([P5.3]). If that bug exists, it is systemic. It inflates predictions across the jurisdiction, so predicted failure diverges from observed reality. That is exactly what system-wide outcome testing and post-deployment audits catch—the checks CON’s model mandates ([C1.3], [C2.4]).
[C5.3] Lawyers reading code cannot see that divergence; statisticians comparing outcomes can. Source code tells you what the programmer wrote, not whether the tool works on real people.
[C5.4] Forcing prosecutors to disclose code and training summaries thus adds no real detection. It only converts every case into a trade-secret fight and expert fishing expedition, while PRO’s comprehensive error rates still have no benchmark for “good enough” ([C2.4], [C3.2]). CON’s model already publishes the error rates, audits, and outcome studies that catch the systemic harm PRO fears. The mandate fails because it demands the wrong instrument: it hands defendants source code when liberty is protected by validation, not reverse-engineering.
