# Debate prop_0182__claude-fable-5-2-high__claude-fable-5-1-high__s1__tpl_placement_length_headroom_20261115a

- topic_id: prop_0182
- proposition: Commercial software vendors should be held strictly liable for monetary damages resulting from insecure code that leads to major cyberattacks.
- model_pro: claude-fable-5-2-high
- model_con: claude-fable-5-1-high
- side_swap: True

## Turn 1: PRO Opening

- model: claude-fable-5-2-high
- raw_words: 293
- clipped_words: 293
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a carmaker ships a defective brake, it pays for the crash. When a software vendor ships a defective authentication routine and a hospital network goes dark, the vendor pays nothing — the license agreement says so. That asymmetry is the whole debate.
[P1.2] First, liability belongs with the party who can prevent the harm cheapest. Only the vendor can see the source code, choose memory-safe languages, fund testing, and ship secure defaults. The customer — a hospital, a city, a school district — cannot audit a closed binary. We have put the cost on the one party powerless to prevent it.
[P1.3] Second, the market won't fix this by itself. Security is invisible at purchase; features and ship dates are not. So vendors rationally underinvest, because the cost of a breach lands on someone else. Consider the recurring pattern: a widely deployed file-transfer or remote-management product falls to an injection flaw or hardcoded credential — bug classes understood for decades — and thousands of downstream organizations pay ransoms, recovery costs, and breach notifications.
[P1.4] The vendor issues a patch and an apology. Strict liability makes insecurity a line item on the vendor's own balance sheet, which is the only place it changes engineering decisions.
[P1.5] Third, strict liability, not negligence, is the right standard. Negligence requires victims to prove what a reasonable development process looked like inside a company whose code and records they can't see, against a defendant with every advantage. Strict liability asks one question: did your insecure code cause this major attack? That's precisely how we treat manufacturing defects in every other industry, and those industries did not collapse; they got safer, bought insurance, and priced risk.
[P1.6] Whoever profits from shipping the code, and alone controls its quality, should pay when it fails.

## Turn 2: CON Opening

- model: claude-fable-5-1-high
- raw_words: 309
- clipped_words: 309
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A carmaker pays for a brake that fails on its own. It does not pay when a thief defeats the lock, hotwires the car, and drives it into a crowd. Every major cyberattack has a thief in it. Strict liability erases that person from the story and bills the locksmith for the burglary.
[C1.2] That is the first problem with "strict." Brakes fail against physics, which does not adapt. Code fails against adversaries who spend years hunting one flaw, sometimes with the resources of a nation-state. No vendor, however careful, ships software with zero exploitable bugs; every working cryptographer and engineer will tell you this is not a budget question but a mathematical one.
[C1.3] Strict liability therefore does not punish carelessness. It punishes existence. The diligent vendor using memory-safe languages and funding audits is liable exactly as much as the sloppy one, because the standard asks nothing about care. That destroys the very incentive PRO wants to create.
[C1.4] Second, causation. A hospital goes dark because a patch sat uninstalled for a year, an administrator reused a password, a phishing email landed, and the network was flat. Under this motion the vendor pays regardless. The customer, now insured by someone else's balance sheet, has less reason than before to patch, segment, or train.
[C1.5] We call that moral hazard, and it moves risk toward the party PRO says cannot manage it.
[C1.6] Third, exposure. One library in millions of deployments means damages measured in billions for a bug no human could have foreseen. That is uninsurable. Small vendors exit, open-source companies stop selling support, and survivors stop serving hospitals and utilities, the high-damage customers who need them most.
[C1.7] Only the largest incumbents remain.
[C1.8] Vendors should answer for negligence, with burdens shifted toward them and secure-by-design baselines enforced. Strict liability is not accountability. It is a lottery with the keys handed to the attacker.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 332
- clipped_words: 332
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.3], [C1.4], [C1.6], [C1.8]
- missing_claim_id_refs: (none)

[P2.1] CON's thief analogy collapses on contact. A lock exists to stop thieves. Sell a deadbolt that opens with a paperclip and "a burglar did it" is no defense, because the burglar is the precise risk the product was sold to withstand. Networked software is the same: attackers are its known operating environment, not a surprise.
[P2.2] And since the thief is usually overseas and uncollectable, the real question is which of the two remaining parties eats the loss, the one who wrote the flaw or the hospital that couldn't see it.
[P2.3] Next, "it punishes existence" [C1.3]. It doesn't. The motion attaches liability to insecure code that causes a major attack. That is a defect requirement and a causation requirement.
[P2.4] Strict liability removes only the need to prove fault. The diligent vendor ships fewer exploitable defects and therefore pays less, so the incentive survives intact. Indeed it is sharper than under negligence, where care stops at whatever checklist a court calls "reasonable." Under strict liability, every additional bug prevented is money saved.
[P2.5] CON's flat-network, year-old-patch hospital [C1.4] is a causation argument, and causation stays. Strict product liability has always coexisted with misuse and comparative-responsibility defenses. If the customer's own neglect caused the loss, the damages didn't "result from" the code. The same answers moral hazard: victims still bear downtime, reputational harm, and patients turned away.
[P2.6] No hospital courts ransomware for a later reimbursement fight.
[P2.7] Then exposure [C1.6]. Those billions do not vanish when vendors are immune. They are being paid now, by schools, cities, and clinics, one uninsured victim at a time. A vendor can spread that cost across every license it sells.
[P2.8] A victim cannot. If a product cannot cover the harm it causes, its victims are subsidizing it.
[P2.9] Notice what CON conceded: vendors should pay, with burdens shifted against them [C1.8]. So the remaining dispute is narrow. When a defect slips through despite care, who absorbs it, the profiting party who can price and insure it, or whoever happened to be hit?

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.5], [P2.4], [P2.7], [P2.9]
- missing_claim_id_refs: (none)

[C2.1] Start with the deadbolt, because it loses PRO the debate. A lock that opens with a paperclip is a lock built below any reasonable standard. That is a negligence case, and I would win it for the hospital. But a deadbolt rated for burglars, cut open by a nation-state with a thermal lance, is not defective.
[C2.2] It met its standard and met a stronger adversary. PRO's own analogy requires a standard of quality, and "insecure code" has no meaning without one. Every shipped program contains undiscovered bugs; "insecure" either means "fell below reasonable care," which is negligence, or "was exploited," which is existence.
[C2.3] Watch what PRO does with this at [P2.5]. Causation stays. Comparative responsibility applies. The hospital's patching, passwords, and flat network all get litigated.
[C2.4] Fine, but then courts must weigh the hospital's carelessness against the vendor's, which means deciding what reasonable vendor care looked like. That is negligence with the label torn off. PRO has rebuilt my position and called it strict.
[C2.5] Next, [P2.4]: the diligent vendor "ships fewer defects and therefore pays less." No. Damages do not scale with bug count; they scale with deployment and attacker interest. A diligent vendor with one flaw in a library used by ten thousand hospitals pays more than a sloppy vendor with fifty flaws in a niche tool nobody targets. The incentive strict liability actually creates is to be small, obscure, and absent from critical infrastructure.
[C2.6] Which answers [P2.7]. Spreading cost across licenses requires an insurer, and insurers price independent risks, not correlated ones. One bug detonates in thousands of networks the same week. That is the risk insurers already flee.
[C2.7] The billions do not spread; the product withdraws, and the clinic gets fewer vendors at higher prices.
[C2.8] PRO's narrow question at [P2.9] is honest: who pays when a defect slips through despite care? That is the no-fault case. Punishing it is punishing existence, which is the motion, and it is why the motion fails.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.8], [C2.5], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: In the no-fault case you call decisive [C2.8], the loss does not disappear. Name who should pay it: the clinic that could neither see nor fix the code, or the vendor that wrote it and profited from it?
[P3.2] Q2: You say damages scale with deployment [C2.5] and that correlated risk is uninsurable [C2.6]. If that risk is too heavy for a vendor collecting license revenue from ten thousand hospitals, why is it bearable for each hospital, alone and uninsured?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say comparative responsibility stays [P2.5]. When a court weighs the hospital's unpatched server against the vendor's code, what standard does it use for the vendor's share other than reasonable care — and if it uses reasonable care, how is that not negligence?
[C3.2] Q2: Define "insecure code" without reference to care or to the fact of exploitation. If every shipped program contains undiscovered bugs, which bug is "insecure" before an attacker finds it, and who decides?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C2.2], [C2.5], [C2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: The hospital's standard, not the vendor's. In strict product liability with comparative responsibility, the court asks two things about the vendor: was there a defect, and did it cause the loss? Then it asks whether the plaintiff's own conduct, the year-old unapplied patch, contributed, and reduces recovery accordingly. Reasonable care is measured on the victim's side only.
[P4.2] Nobody must reconstruct what happened inside the vendor's engineering department, the burden negligence imposes and victims cannot carry.
[P4.3] A2: Insecure code is code that violates the product's own security promise: it lets an unauthorized party read, alter, or run what the design says they cannot. An authentication bypass is a deviation from the vendor's own specification, just as a cracked brake line is. It exists before anyone finds it, the way the crack exists before the crash; exploitation doesn't define the defect, it merely triggers damages. Who decides?
[P4.4] Courts with experts, using classifications the industry already applies whenever it catalogs a vulnerability.
[P4.5] So "negligence or existence" [C2.2] is a false choice; the law's third option is defect, measured against the product's own function.
[P4.6] CON's remaining argument: damages scale with deployment, so strict liability punishes the vendor inside ten thousand hospitals [C2.5]. Yes. That is the design working. Revenue scales with deployment too, and so should caution.
[P4.7] The vendor whose single flaw can darken ten thousand hospitals is precisely the one that should spend most on prevention; under CON's rule it stops at the checklist.
[P4.8] Finally, CON's thermal lance [C2.1]. Even against an unstoppable adversary, someone pays, and CON bills the clinic. If correlated catastrophic risk is too heavy for the firm collecting every license fee, it cannot belong on each victim alone. Put the loss where the code was written, the profit was taken, and the fix is possible.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 324
- clipped_words: 324
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P1.1], [P4.3], [P4.6]
- missing_claim_id_refs: (none)

[C4.1] A1: The loss is spread, not dumped. Three places, in order: the attacker, through asset seizure and sanctions; the vendor, whenever it fell below reasonable care, with the burden of proving its own process shifted onto it; and the victim's own insurer for the residue. That residue is insurable precisely because one hospital's loss is bounded and independent. Nobody bills the clinic alone.
[C4.2] PRO's rule is the one that leaves a single party holding the whole bill: the careful vendor.
[C4.3] A2: Because ten thousand separate, bounded risks are what insurers write, and one concentrated, correlated risk is what they refuse. A hospital's exposure is its own network, which it caps with backups and segmentation and insures at a known premium. The vendor's exposure under this motion is every customer's network in the same week, uncapped, for a flaw it may not know exists. Distribution is not cruelty; it is the only structure in which the money actually gets paid.
[C4.4] Now watch what PRO's answers did. [P4.1]: reasonable care is "measured on the victim's side only." So the hospital that left a patch uninstalled for a year earns a reduction, while the vendor that funded audits and used memory-safe languages earns nothing. PRO opened by condemning asymmetry [P1.1] and has built a worse one: carelessness counts on one side, care is invisible on the other.
[C4.5] [P4.3] finishes it. Insecure code is anything that "violates the product's own security promise." Every exploitable bug does that, including the one a nation-state finds after years. That is my definition of existence, adopted by PRO.
[C4.6] And [P4.6] accepts that the vendor inside ten thousand hospitals pays most, calling it "the design working." The design works by driving that vendor out of hospitals.
[C4.7] Weigh it. My rule pays victims when vendors are careless and keeps vendors in critical infrastructure. PRO's rule charges careful vendors for mathematically unavoidable bugs until they stop selling to hospitals. Keep the thief in the story.

## Turn 9: PRO Closing

- model: claude-fable-5-2-high
- raw_words: 211
- clipped_words: 211
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7], [P5.8]
- cited_claim_ids: [C4.1], [C4.3], [C4.4]
- missing_claim_id_refs: (none)

[P5.1] Strip away the analogies and one question decided this debate: when a defect slips through and the attacker is beyond reach, who pays?
[P5.2] CON finally answered at [C4.1]. First the attacker, through "asset seizure", which is a hope and not a remedy. Then the vendor, if negligence can be proven. Then "the victim's own insurer for the residue."
[P5.3] That residue is the motion's entire territory, and CON puts it on the clinic through its premiums, its deductibles, and its exclusions.
[P5.4] CON's justification is that the vendor's risk is correlated and therefore uninsurable [C4.3]. But the correlation doesn't dissolve when the bill moves. The same bug hits the same ten thousand hospitals in the same week, whoever is holding the policy. CON has not made the catastrophe insurable.
[P5.5] He has made it someone else's, and that someone is the only party who can't shrink it.
[P5.6] The vendor can. One codebase, one fix, and ten thousand networks are protected. Care is not "invisible" under strict liability [C4.4], because every defect prevented is a catastrophe the vendor never pays for.
[P5.7] CON says keep the thief in the story. Fine. He's in it, and he's gone. Two parties remain, and only one wrote the code, sold it, and can fix it.
[P5.8] Send the bill there.

## Turn 10: CON Closing

- model: claude-fable-5-1-high
- raw_words: 206
- clipped_words: 206
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P4.1], [P4.3], [C2.5], [P5.6], [P5.4]
- missing_claim_id_refs: (none)

[C5.1] One question resolves this: does the motion reward care? PRO's own answers say no. At [P4.1], reasonable care is weighed on the victim's side only. At [P4.3], insecure code is anything that violates the product's security promise, which is every exploitable bug ever found, including the one a nation-state digs out after years. Put those together and the vendor that funded audits, used memory-safe languages, and shipped secure defaults pays exactly what the sloppy one pays, scaled not by effort but by how many hospitals it serves [C2.5].
[C5.2] PRO says care still matters because "every defect prevented is a catastrophe never paid for" [P5.6]. But the defects that remain after genuine care are the undiscoverable ones. You cannot prevent what no process reveals. A rule that charges for the unpreventable does not buy prevention; it buys withdrawal.
[C5.3] And PRO's correlation point [P5.4] cuts against him. Ten thousand bounded losses across independent insurers get paid. One uncapped loss on one balance sheet does not; it bankrupts the vendor or drives it out of hospitals before any bill arrives. The clinic ends up with fewer vendors, higher prices, and the same breach.
[C5.4] Negligence with shifted burdens pays victims when vendors fail. Strict liability charges existence. Reject the motion.
