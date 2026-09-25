# Debate prop_0628__claude-opus-5-5-high__claude-opus-5-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0628
- proposition: Governments should require frontier AI model developers to complete and publish standardized pre-deployment safety evaluations, with penalties for noncompliance.
- model_pro: claude-opus-5-5-high
- model_con: claude-opus-5-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-5-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] We don't let a drug company decide privately whether its trial results are worth sharing. We don't let an airline certify its own new jet and announce afterward that it probably won't fall out of the sky. Frontier AI systems are now being wired into search, code, customer service, and critical infrastructure, and the public learns what they can do mainly after millions of people are already using them. The motion fixes that with three modest requirements: test before release, test to a common standard, and publish the results, with teeth if you don't.
[P1.2] First, voluntary safety is not a system. It is a mood. Leading labs have made public safety pledges and released model cards. But those documents vary wildly in depth, sometimes arrive after launch, and can be quietly thinned out when a competitor ships first.
[P1.3] Race dynamics punish the careful lab. Every developer faces the same temptation to cut the evaluation week that delays launch. A binding rule removes that temptation for everyone at once, so responsibility stops being a competitive disadvantage.
[P1.4] Second, standardization is what makes disclosure mean anything. If one lab measures bioweapon uplift one way and another measures it differently, or not at all, regulators, customers, and researchers cannot compare anything. A common evaluation battery covering dangerous capabilities, cyber-offense, deception, and failure rates turns marketing claims into checkable facts. Publication then lets independent experts find what the developer missed, which is how security research works everywhere else.
[P1.5] Third, penalties are the difference between a law and a suggestion. Without consequences, the firms most eager to skip testing are exactly the ones who will.
[P1.6] Now the objection you'll hear: this strangles innovation. It doesn't. The rule targets frontier developers, a handful of companies spending enormous sums on training runs. For them, a structured evaluation costs a rounding error next to the compute bill.
[P1.7] Startups fine-tuning open models are untouched.
[P1.8] The real question is who carries the risk of an untested system: the few firms profiting from it, or everyone else. PRO puts that burden where [clipped]

## Turn 2: CON Opening

- model: claude-opus-5-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] We don't let airlines certify their own jets — true. We also spent seventy years learning what to measure on a jet: stall speeds, fatigue cycles, load limits. The word doing all the work in this motion is "standardized," and in AI it names something that does not yet exist.
[C1.2] Ask what goes in the mandatory battery. Capability evaluations today are notoriously sensitive to how you elicit the behavior: the same model scores harmless with a plain prompt and alarming with better scaffolding, a fine-tune, or a tool attached. Benchmarks get saturated and gamed within months. So a legally binding battery does one of two things.
[C1.3] Either it freezes this year's best guesses into statute, and firms optimize to pass the test rather than to be safe — the emissions-cycle problem, but for bioweapon uplift. Or the battery is vague enough to be gameable, in which case the penalties land on paperwork, not danger. Neither is safety. Both are a certificate.
[C1.4] That certificate is the real harm. Once a government stamp exists, it becomes the liability shield and the marketing line: cleared under the federal standard. A regime that formally reassures the public about risks it cannot actually measure leaves us worse off than honest uncertainty.
[C1.5] Second, publication cuts the wrong way. PRO wants a document specifying which dangerous requests the model refuses and which it doesn't, at what rate, under which phrasings. Published, that is a roadmap — a triage list telling every bad actor where the seams are, and telling every open-weight fine-tuner exactly which guardrail to strip. Security research works by coordinated disclosure to defenders, not by mandatory publication of the exploit surface on launch day.
[C1.6] Third, the harms we've actually seen — chatbots wired into products they weren't tested for, models deployed in contexts nobody anticipated — are deployment harms, not model-intrinsic ones. A pre-deployment snapshot cannot see them. Liability for downstream damage and mandatory incident reporting reach them; a pre-launch test sheet does not.
[C1.7] The motion mandates the measurable and misses the dangerous.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 357
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON's case has a strange shape. Every objection is a reason to design the rule carefully, and none is a reason to leave testing optional.
[P2.2] Take standardization first. CON says the battery "does not yet exist." Neither did aviation's, until regulators required manufacturers to measure things. Standards mature because someone must meet them.
[P2.3] Nothing here requires freezing a test into statute. An agency updates the battery the way regulators revise crash-test protocols. And CON's best point, that the same model "scores harmless with a plain prompt and alarming with better scaffolding," is my argument. Today each lab decides how hard it tries to elicit dangerous behavior.
[P2.4] A standard can require fine-tuning, tool access, and serious red-teaming. That is how you stop a lab from testing gently and calling it safe.
[P2.5] On gaming: the emissions scandal was exposed because a published standard gave outside testers something to check against. Without a common benchmark, there is no cheating to catch, only unverifiable claims.
[P2.6] The "certificate" worry gets things backwards. The motion requires publishing results, including failures and weak scores, not stamping a pass. That is the opposite of false reassurance. The false reassurance we have now is a launch blog calling a model "our safest yet," with nothing to check it against.
[P2.7] On publication as a "roadmap," publish does not mean posting exploit strings. Drug trials publish outcomes without publishing synthesis routes. Aggregate results can go public while sensitive specifics go to regulators and vetted researchers, which is exactly the coordinated disclosure CON endorses. Meanwhile, bad actors probe every major model within hours of launch anyway.
[P2.8] Secrecy protects the developer, not the public.
[P2.9] Finally, CON concedes the principle. Their alternative, liability plus mandatory incident reporting, is a government mandate with penalties. The only disagreement is timing: CON wants the state to show up after the damage. For deployment glitches, that works.
[P2.10] For a model that meaningfully helps someone build a pathogen, or open weights that can never be recalled, there is no afterward. You cannot sue your way out of an irreversible [clipped]

## Turn 4: CON Rebuttal 1

- model: claude-opus-5-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.6], [C1.4], [P2.10], [P2.7], [P1.4]
- missing_claim_id_refs: (none)

[C2.1] PRO says every objection is just a call to design the rule carefully. But "design it carefully" is the whole disagreement, and PRO has just walked into a dilemma they cannot answer both ways.
[C2.2] Ask what the penalties attach to. PRO insists in [P2.6] that the motion "requires publishing results, including failures and weak scores, not stamping a pass." Fine — then a lab can publish an evaluation showing real dangerous-capability uplift and ship anyway, fully compliant. The penalty punishes the firm that didn't file, not the firm that filed alarming numbers and launched.
[C2.3] That is a disclosure ritual with teeth pointed at paperwork. The alternative is that bad scores block release — but then it *is* a licensing regime, and the stamp I warned about in [C1.4] arrives with all its liability-shielding force. PRO must pick. Every time they pick "it's just disclosure," their pathogen scenario in [P2.10] evaporates, because disclosure doesn't stop the launch.
[C2.4] Then look what happened to publication. [P2.7] now says aggregate results go public while "sensitive specifics go to regulators and vetted researchers." That is my position, not the motion's. It also destroys [P1.4]'s promise that independent experts find what the developer missed — they can't, if the elicitation details are the part being withheld.
[C2.5] PRO has quietly conceded the confidential channel does the real work.
[C2.6] On aviation: regulators codified stall-speed tests after engineers had spent decades learning what fatigue does to aluminum. Mandating first and discovering later means the agency writing the battery has less evaluation expertise than the three companies it regulates, and will take the battery from them. The labs write the test they can pass, and now it's law.
[C2.7] And no, this isn't a dispute about timing. Liability attaches to harm itself — unfakeable, ungameable, indifferent to whether your benchmark was last year's. A compliance certificate is the single most reliable way to weaken it. PRO's regime doesn't add to accountability.
[C2.8] It buys firms a receipt.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.7], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: You rest accountability on liability because it "attaches to harm itself" [C2.7]. Once open weights that meaningfully help someone build a pathogen are released and copied worldwide, what exactly does your lawsuit recall, and who is left to pay?
[P3.2] Q2: You warn that under PRO "the labs write the test they can pass" [C2.6]. Today labs write the test, grade it, and decide whether anyone sees the results. How is that better than a public standard that outsiders can check them against?

## Turn 6: CON Pressure Questions

- model: claude-opus-5-high
- raw_words: 82
- clipped_words: 82
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7]
- missing_claim_id_refs: (none)

[C3.1] Q1: Straight answer, please: under your regime, may a developer publish an evaluation showing serious bioweapon uplift and still lawfully ship? If yes, your pathogen scenario is untouched by the motion. If no, admit this is licensing — and defend the stamp.
[C3.2] Q2: You now route sensitive specifics to "regulators and vetted researchers" [P2.7]. When a firm that passed the published battery causes harm through a capability the battery never measured, does its certified compliance help or hurt the plaintiff suing it?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 336
- clipped_words: 336
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8], [P4.9]
- cited_claim_ids: [C2.7]
- missing_claim_id_refs: (none)

[P4.1] A1: Yes, under the motion as written, a developer that publishes serious bioweapon uplift may still ship. That isn't the embarrassment CON thinks. Picture that filing going public weeks before launch. Regulators with existing powers now have a documented reason to intervene.
[P4.2] Insurers, cloud providers, and enterprise customers see it. Every future plaintiff holds a signed admission that the firm knew and launched anyway. Today that same result can sit in an internal slide deck that nobody outside ever sees. The motion doesn't need a licensing veto to change behavior.
[P4.3] It needs to make "we knew" impossible to hide, and a mandatory, penalized, pre-deployment publication does exactly that. There is also no stamp to defend, because nothing here certifies a pass. The document can say "dangerous," and it will be public.
[P4.4] A2: Compliance hurts the defendant and helps the plaintiff. The motion creates no safe harbor, and a legislature can say so explicitly. Meeting a regulatory minimum is ordinarily evidence, not immunity. What the regime adds is a record: what the firm tested, what it found, and which risks it chose not to probe.
[P4.5] When harm comes from an unmeasured capability, the plaintiff points to the published battery and asks why the firm stopped there. Without the regime, that plaintiff starts with nothing and fights for years in discovery for evaluations the firm controls.
[P4.6] So look where CON's case now stands. Their entire alternative is liability, because it "attaches to harm itself" [C2.7]. But liability runs on evidence of what the defendant knew. PRO's regime manufactures that evidence before the harm, in public, in a comparable format.
[P4.7] We don't compete with CON's remedy. We are the precondition for it working.
[P4.8] Then there is the harm liability can't touch. CON never answered what a lawsuit recalls once open weights are copied worldwide. They also never explained why labs grading their own secret tests beats a public standard. For irreversible risks, the only useful moment is before release.
[P4.9] The motion is the only side that shows up then.

## Turn 8: CON Rebuttal 2

- model: claude-opus-5-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P4.4], [P4.7]
- missing_claim_id_refs: (none)

[C4.1] A1: My lawsuit recalls nothing. Neither does PRO's test sheet — and that's the point they just conceded. In [P4.1] PRO admits a developer may publish serious bioweapon uplift and lawfully ship. So the pathogen case, the one irreversible harm carrying this entire motion, is untouched by the motion.
[C4.2] If you genuinely believe some capabilities must never be released, the honest instrument is a targeted prohibition on releasing them, not a mandate to describe them on a standardized form and proceed. PRO is prosecuting a licensing case while defending a paperwork rule.
[C4.3] A2: Because "labs grade their own tests" is not the counterfactual. Today several rival labs, academic red teams, journalists, and prospective plaintiffs all probe models by different methods, and none of them can say a firm met its legal duty. Under the motion, one battery becomes the official measure of care. That is the trade: you gain comparability and you lose evaluation diversity precisely where nobody knows yet what to measure.
[C4.4] And the firm that ran exactly the mandated battery and nothing more now has the best sentence in litigation — we performed every test the government specified.
[C4.5] PRO's answer is that a legislature "can say so explicitly" that compliance isn't immunity [P4.4]. Statutes can say that; courtrooms still treat a satisfied government standard as the benchmark of reasonableness, and defense counsel will spend a decade making exactly that argument. You cannot legislate away the inference you have created.
[C4.6] So weigh what's left. PRO's benefits — insurers reacting, enterprise customers reacting, plaintiffs holding a record of what the firm knew — all run through liability. Their own speech calls the regime "the precondition" for my remedy [P4.7]. But you can force disclosure of what a developer tested and found through duties of candor and incident reporting, without freezing this year's guesses into a legal standard of care that the three regulated firms will help write.
[C4.7] The motion buys the receipt and leaves the danger.

## Turn 9: PRO Closing

- model: claude-opus-5-5-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.6]
- missing_claim_id_refs: (none)

[P5.1] By the end, CON's case collapsed into ours. Their last alternative is to "force disclosure of what a developer tested and found through duties of candor" [C4.6]. That is a government mandate to disclose evaluations, with legal consequences. CON has conceded disclosure should be compulsory.
[P5.2] What remains is two choices: whether the disclosure comes before release, and whether it follows a common standard.
[P5.3] On both, CON's version fails exactly where the stakes are highest. Incident reporting arrives after the incident. A duty of candor with no standard lets each lab decide how hard to look, and CON's own opening warned that the same model looks harmless under gentle prompting and alarming under serious scaffolding. So under CON, the lab that tests gently files a candid, clean report and ships.
[P5.4] The standard is a floor, not a ceiling. Rival labs, academics, and journalists keep probing; now they have a baseline to measure every firm against.
[P5.5] CON calls our filing "a receipt." Consider what it says: the firm knew, in public, in comparable terms, before launch, while regulators, insurers, and customers can still act. For open weights that can never be recalled, that window is the only one that matters.
[P5.6] Vote PRO.

## Turn 10: CON Closing

- model: claude-opus-5-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P4.1]
- missing_claim_id_refs: (none)

[C5.1] Strip everything else away and one admission decides this debate. Asked directly whether a developer may publish an evaluation showing serious bioweapon uplift and still lawfully ship, PRO answered yes [P4.1]. The pathogen. The open weights that can never be recalled.
[C5.2] The irreversible harm that carried every emotional beat of their case — the motion does not stop it. It asks the firm to describe it on a standardized form and proceed.
[C5.3] So weigh honestly. The benefit PRO is left with runs entirely through liability, insurers, and customers reacting to a document. The cost is certain: one legally mandated battery becomes the official measure of care in a field where nobody yet knows what to measure, written with the help of the three firms it binds, and handed to defense counsel as the sentence "we ran every test the government specified."
[C5.4] A duty of candor asks what you knew and what you chose not to look for, and liability punishes the harm however you tested. A fixed battery rewards the firm that ran it and stopped.
[C5.5] PRO would trade an unfakeable standard — did you cause harm — for a gameable one, and gets no veto in return.
[C5.6] Vote CON.
