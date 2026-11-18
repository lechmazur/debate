# Debate prop_0182__claude-fable-5-1-high__claude-fable-5-2-high__s0__tpl_placement_length_headroom_20261115a

- topic_id: prop_0182
- proposition: Commercial software vendors should be held strictly liable for monetary damages resulting from insecure code that leads to major cyberattacks.
- model_pro: claude-fable-5-1-high
- model_con: claude-fable-5-2-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 303
- clipped_words: 303
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every other industry that sells products capable of causing mass harm lives under the same rule: if your product's defect hurts people, you pay. Carmakers pay for exploding fuel tanks. Drug companies pay for contaminated batches. Elevator manufacturers pay when cables snap.
[P1.2] Commercial software is the lone exception, and it has earned that exemption not through safety but through a click-wrap license that says, in effect, "this product may fail catastrophically and that is your problem." The result is exactly what economics predicts: the vendor keeps the profit, and the hospital, the pipeline operator, the city government, and the patient keep the loss.
[P1.3] Strict liability fixes this by placing cost on the cheapest cost avoider. Only the vendor can see the code, choose memory-safe languages, run fuzzing, and refuse to ship a known-vulnerable component. A customer running a file-transfer appliance cannot audit its SQL injection surface. When MOVEit-style flaws expose millions of records, the victims had no realistic way to prevent it; the vendor did.
[P1.4] Liability belongs with capacity.
[P1.5] Why strict rather than negligence? Because negligence is unprovable in software. Source code is secret, development practices are opaque, and "reasonable care" has no settled industry floor. A negligence regime hands vendors a permanent defense: we did what everyone does.
[P1.6] Strict liability eliminates that shrug. Causation must still be shown—the attack must result from the insecure code—but once shown, the vendor pays.
[P1.7] The predictable objection is that this bankrupts innovation. It will not. Vendors will insure, as every manufacturer does, and insurers will demand secure development practices the way fire underwriters demanded sprinklers. Premiums become a price signal: sloppy code costs more to sell.
[P1.8] That is the market finally pricing risk honestly instead of exporting it.
[P1.9] Right now insecurity is free for the people who create it. Make it expensive, and it becomes rare.

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.1], [P1.7], [P1.5]
- missing_claim_id_refs: (none)

[C1.1] A fuel tank does not have an enemy. Software does. That is the difference the car analogy in [P1.1] hides: nobody spends years, with nation-state budgets, hunting for the one flaw in an elevator cable. Every complex program contains exploitable bugs, including those built by the best-funded security teams on earth.
[C1.2] Strict liability therefore does not punish sloppy vendors; it punishes all vendors, because under it care is irrelevant. The company that fuzzed, audited, and used memory-safe languages pays exactly what the careless one pays. A rule that ignores care cannot reward it.
[C1.3] Second, the vendor is often not the cheapest cost avoider. In WannaCry and the Equifax breach, patches existed well before the attacks; the victims had not installed them. Strict liability sends the bill to the vendor anyway, telling every customer that patching, segmentation, and multifactor authentication are someone else's problem. That makes attacks more likely, not less.
[C1.4] Third, the insurance rescue in [P1.7] fails on its own terms. Fires are independent events; one building burning does not ignite ten thousand others. A single software flaw hits every customer simultaneously. That is correlated risk, the kind insurers cap, exclude, or flee.
[C1.5] Giants can self-insure; small vendors and newcomers cannot. Result: a more concentrated market, with more of the world riding on fewer codebases.
[C1.6] Fourth, when every disclosed vulnerability is a liability trigger, vendors disclose less, patch quietly, drop support for older products faster and treat security researchers as plaintiffs' witnesses.
[C1.7] The real complaint in [P1.5] is that negligence is hard to prove. Then fix proof: discovery opens source code, and a defined secure-development standard supplies the floor. Liability for fault deters fault. Liability regardless of fault deters only selling software, and nobody is safer when the careful vendor leaves and the attacker stays.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 324
- clipped_words: 324
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.2], [C1.4], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] The adversary point cuts the other way. Yes, software has enemies. So do safes, bank vaults, and vaccines. Nobody argues that because burglars exist, lockmakers should stop answering for locks that open with a paperclip.
[P2.2] Foreseeable attack is the reason to demand hardening, not the excuse for skipping it. A vendor who knows nation-states are hunting its code and still ships an unauthenticated admin endpoint is more culpable, not less.
[P2.3] [C1.2] claims strict liability ignores care. It does not; it prices care. Toyota and a shoddy carmaker both face strict liability, yet they do not pay the same, because the careful one produces fewer defects, faces fewer claims, and carries cheaper premiums. The fuzzing, auditing vendor pays rarely.
[P2.4] The careless one pays constantly. That is reward, delivered through outcomes rather than through a lawyer's argument about process.
[P2.5] On patching: the motion covers damages "resulting from insecure code." Where a customer ignored an available fix for months, the damage results from that failure, and causation breaks—exactly as product liability already treats misuse. WannaCry and Equifax are cases for a causation defense, not against vendor accountability for flaws no customer could have patched because no patch existed.
[P2.6] [C1.4] is the most serious objection, and it concedes the case. Correlated risk is precisely what one flaw inflicts on ten thousand victims today. The only question is who holds it. Right now it sits on hospitals and water utilities that cannot reduce it.
[P2.7] Strict liability moves it to the one party that can. If insurers refuse to price a vendor's correlated exposure, that is the market telling the vendor its code is too dangerous to ship as written—which is the signal we want.
[P2.8] And [C1.7]'s "defined standard" becomes a compliance ceiling that vendors lobby, that lags attackers by years, and that converts every trial into a decade of discovery. Negligence asks whether paperwork was in order. Strict liability asks whether the product failed. Victims deserve the second question.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.5], [P2.8], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] Look at the examples PRO chose. A lock that "open[s] with a paperclip." A vendor who "still ships an unauthenticated admin endpoint" and is therefore "more culpable." Culpability is the vocabulary of fault.
[C2.2] Every vivid case in [P2.1] and [P2.2] is a negligence case, and a negligence rule wins it. Strict liability adds only one thing: liability for the vendor who did everything right and was beaten anyway by a novel exploit. PRO has not defended that case once. Nor does anyone make the safe-maker pay for every heist by a skilled crew.
[C2.3] [P2.3] says outcomes will reward care. In software, outcomes track attacker attention. The most-targeted code is the most widely deployed, not the sloppiest. A careful vendor with a huge customer base draws the best adversaries, and one zero-day produces damages across every customer at once.
[C2.4] "Pays rarely" means little when a single payment is fatal. That is a lottery, not a price signal.
[C2.5] Then [P2.5] gives away the simplicity. Once unpatched customers break causation, every trial must examine what the customer knew, when the patch shipped, and whether their network was segmented. That is the fault inquiry and the "decade of discovery" [P2.8] claimed strict liability avoids. What remains for the vendor is the zero-day, a flaw it did not know existed.
[C2.6] That is where liability deters least.
[C2.7] [P2.7] is the most revealing answer. If insurers will not price the exposure, the code is "too dangerous to ship." But no complex software is provably free of exploitable bugs, so the signal is not "ship safer" but "don't ship", or ship only if you are large enough to absorb the hit. The hospital is not made whole by a judgment against a bankrupt vendor.
[C2.8] It keeps its loss and loses the company that would have written the patch.
[C2.9] A standard that evolves is imperfect. A rule that treats the diligent and the reckless identically is worse, because it gives up on telling them apart.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.8]
- missing_claim_id_refs: (none)

[P3.1] Q1: Under your negligence rule, when a vendor meets your "defined secure-development standard" yet ships the flaw that empties a hospital's records, you say the hospital "keeps its loss" [C2.8]. Why should the party that earned nothing from the code absorb that loss instead of the party that sold it?
[P3.2] Q2: Who writes that standard, and how does a water utility prove a vendor fell below it when the code, build logs, and internal bug reports stay in the vendor's hands until a judge orders discovery years later?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 74
- clipped_words: 74
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5], [P2.8]
- missing_claim_id_refs: (none)

[C3.1] Q1: A vendor fuzzes, audits, uses memory-safe languages, and is still breached by a nation-state zero-day nobody could have found. What exactly should it have done differently, and if nothing, what behavior does your rule deter besides selling software?
[C3.2] Q2: [P2.5] says an unpatched customer "breaks" causation. How does a court decide that without investigating patch timing, customer knowledge, and network configuration, the very fault inquiry and "decade of discovery" you condemned in [P2.8]?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C3.1], [C2.8], [P3.1]
- missing_claim_id_refs: (none)

[P4.1] A1: "What should it have done differently" is the negligence question, and strict liability deliberately refuses to ask it. The rule's purpose in the perfect-vendor case is not deterrence but allocation: someone must absorb the loss from a flaw nobody could find, and the choice is between the seller who priced the product, collected the revenue, and can spread the cost across every customer, or the hospital that saw none of the code and earned none of the money. That is why drug makers answer for manufacturing defects even when their process was flawless.
[P4.2] And the truly blameless vendor is rarer than [C3.1] suggests. Even a zero-day's damage depends on choices the vendor made: how much privilege the product demanded, how wide its blast radius, how fast it could be patched. Strict liability deters shipping risk you cannot contain, which is exactly the behavior that turns one bug into ten thousand victims.
[P4.3] A2: The causation defense is a bright line, not a fault trial. Was a patch released, and when? Those are public dates on release notes. Compare the negligence inquiry: whether the vendor's secret development process met a contested standard, provable only after years of discovery into build logs the vendor controls.
[P4.4] One question looks at a calendar; the other looks inside a black box. And in the cases that matter most, the question vanishes entirely, because no patch existed. MOVEit's victims could not install a fix that had not been written.
[P4.5] That exposes where this debate now turns. [C2.8] concedes that under negligence the diligent-vendor zero-day leaves the hospital with its loss, and [P3.1] asked why; no answer came. CON's rule tells victims: you were harmed by a product you could not inspect, sold by a company that profited from it, and you pay. Mine says the party that sold the risk owns the risk.
[P4.6] Negligence protects the careful vendor's balance sheet. Strict liability protects the patient's records. Pick the one that answers to the victim.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1], [P1.9], [P4.2], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Because the hospital pays under either rule. Strict liability is compulsory insurance folded into the license price, with the vendor as insurer. It is the worst insurer available, since every one of its policyholders claims on the same day and it goes insolvent exactly when they do.
[C4.2] First-party cyber coverage pays the hospital faster, is priced to that hospital's own defenses, and survives the vendor's collapse. Nor did the hospital "earn nothing" from the code; it ran its operations on it.
[C4.3] A2: Standards bodies and regulators write it, building on secure-development frameworks that already exist. Proof gets fixed by flipping the burden. Once a breach is traced to a flaw, the vendor must produce its build records and show it met the standard, or it loses. The black box opens on day one, and fault still matters.
[C4.4] Now look at what [P4.1] gave up. In the diligent-vendor case, the rule's purpose is "not deterrence but allocation." That is the only case where strict liability differs from negligence, and PRO now admits it makes no code safer there. [P1.9]'s promise, "make it expensive, and it becomes rare," is gone for the one margin the motion adds.
[C4.5] [P4.2] tries to recover with privilege, blast radius, and patch speed. Those are design choices a court can judge, and they are negligence all over again.
[C4.6] The "calendar" in [P4.3] is no bright line either. Is a patch released yesterday enough to break causation? Last week? The answer depends on what was reasonable for that customer, which is a fault trial aimed at the victim.
[C4.7] What remains is a pure compensation question, and PRO's mechanism fails on it. It routes catastrophic, correlated loss through a single defendant, pays victims cents on the dollar in bankruptcy court, and drives out every vendor too small to self-insure.
[C4.8] Fault liability with a reversed burden punishes the reckless, and insurance compensates the unlucky. Strict liability mostly bankrupts the diligent without deterring the attacker.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 209
- clipped_words: 209
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.2], [C1.7], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] The debate comes down to one question: who pays for a flaw nobody outside the vendor could see? CON's final answer is first-party cyber insurance [C4.2]. Follow that money. The hospital buys coverage priced to its own defenses, the premium rises every time a vendor's product fails, and the vendor's license fee never moves.
[P5.2] Insecurity remains free for the only party that creates it. That is the status quo with a new name.
[P5.3] CON's correlation objection applies to its own cure. A single MOVEit-style flaw hits every insured hospital on the same day too; the risk is correlated wherever it sits. The only choice is whether the price of that risk lands in the vendor's license, where it can be reduced by better code, or in the victim's premium, where it cannot be reduced at all.
[P5.4] And notice how far CON traveled: from "liability for fault" [C1.7] to a reversed burden where the vendor loses unless it proves compliance [C4.3]. That is an admission the black box cannot be opened from outside. Once you presume against the vendor, the remaining defense is "we followed the checklist," which protects the checklist, not the patient.
[P5.5] A product's price should include the cost of its failure. Only strict liability makes that true.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 212
- clipped_words: 212
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P5.2], [P4.1], [P5.3]
- missing_claim_id_refs: (none)

[C5.1] Strip away everything both sides agree on. The vendor who ships the paperclip lock pays under my rule too, and with the burden reversed, it pays unless it opens its own records. So insecurity is not "free" under fault liability, whatever [P5.2] says. Careless code costs the vendor that wrote it.
[C5.2] The motion adds exactly one thing: liability for the vendor who did everything right and was beaten anyway. And on that single margin, PRO told you the purpose is "not deterrence but allocation" [P4.1].
[C5.3] That admission sinks [P5.3]. The risk supposedly belongs in the license fee because there "it can be reduced by better code." But in the diligent-vendor case there is no better code to buy. PRO conceded that.
[C5.4] The price signal has nothing left to signal.
[C5.5] So judge strict liability as what it now is, a compensation scheme. It names as sole insurer the one party certain to be insolvent the day every customer claims. A hospital's own coverage is spread by its insurer across many vendors and rewards its own defenses. A judgment against a bankrupt vendor pays almost nothing.
[C5.6] Punish fault and insure misfortune. Strict liability confuses the two. It makes no code safer, and it removes the careful vendors who would have written the next patch.
