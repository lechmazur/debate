# Debate prop_0536__claude-opus-5-5-high__claude-fable-5-1-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0536
- proposition: Older adults should have stronger legal protection against age-based algorithmic exclusion in hiring, insurance, and financial services.
- model_pro: claude-opus-5-5-high
- model_con: claude-fable-5-1-high
- side_swap: True

## Turn 1: PRO Opening

- model: claude-opus-5-5-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A sixty-two-year-old engineer applies for two hundred jobs and never speaks to a human being. No manager ever decided she was too old. A screening model simply learned that applicants with graduation dates before 1990, or "too many" years of experience, rarely got hired in the past, and quietly filtered her out. That is age-based algorithmic exclusion, and our current laws were not built to catch it.
[P1.2] The case rests on three points.
[P1.3] First, the harm is real and already happening. Regulators have pursued companies whose hiring software automatically rejected older applicants. Platforms have faced litigation over job ads shown only to younger age bands. None of this required malice.
[P1.4] Algorithms infer age from proxies like graduation year, email domain, browsing patterns, or career length, then reproduce historical bias at scale and at machine speed.
[P1.5] Second, existing protection has gaps that algorithms exploit. Age discrimination law centers on proving intent or pointing to a decision-maker. An opaque model gives neither. Worse, several U.S. appeals courts have read the federal age statute as barring job applicants, the exact people screened out by these tools, from bringing disparate-impact claims.
[P1.6] So the most common algorithmic harm, a neutral-looking rule with a lopsided result, may be legally invisible to the person it hurts most. In lending and insurance, applicants often cannot learn which variables sank them, so they cannot challenge anything.
[P1.7] Third, the fix is targeted, not radical. Stronger protection means clear disparate-impact rights for applicants, mandatory bias audits for high-stakes models, meaningful explanations of adverse decisions, and a right to human review. Insurers could still price genuine, validated risk. What they could not do is let an unexamined proxy shut an entire age group out of coverage or credit.
[P1.8] The clash is simple. CON must defend a system where the fastest-growing decision-makers in hiring and finance face weaker scrutiny than a human loan officer would. Whenever accountability disappears into code, the law must catch up. That is all this motion asks.

## Turn 2: CON Opening

- model: claude-fable-5-1-high
- raw_words: 351
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Start with what PRO quietly conceded: insurers "could still price genuine, validated risk." That concession collapses the case. Age is the single most validated risk factor in existence. A seventy-year-old is more likely to die this year than a thirty-year-old, more likely to file a health claim, more likely to retire before a loan matures.
[C1.2] Once you grant that, "age-based exclusion" is not a bug in the model. It is the model working. The only question left is who gets to decide which correlations count as "genuine," and PRO's answer is regulators and plaintiffs' lawyers, litigating one variable at a time.
[C1.3] Now notice what age-specific disparate-impact liability actually does in hiring. Age correlates with almost everything a legitimate employer cares about: salary expectations, years of experience, currency of technical skills, time to retirement. Every "entry-level" posting, every salary band, every requirement for a recently updated certification has a lopsided age result. PRO's rule makes every ordinary hiring criterion presumptively unlawful and dares firms to justify it in court.
[C1.4] Firms respond predictably. They abandon auditable software, and revert to a recruiter's gut, which nobody can test, log, or subpoena. The sixty-two-year-old engineer loses her digital rejection and gains a silent human one.
[C1.5] That inversion is the heart of it. Algorithms are the most inspectable decision-makers we have ever built. You can run a model against a test population and measure exactly how it treats different ages. You cannot do that to a hiring manager's instincts.
[C1.6] Existing anti-discrimination law already reaches intentional proxies for age, in code or on paper. What PRO wants is not to close a loophole but to impose a stricter standard on the one decision-maker that can be checked.
[C1.7] Finally, follow the money. Age-blind pricing does not eliminate risk; it reassigns it. The twenty-five-year-old barista subsidizes the retiree's life policy and loan. Older adults are already the wealthiest and most politically protected cohort in most developed economies.
[C1.8] Layering a special legal shield over them, at the expense of accuracy and of younger people, is not justice catching up [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 333
- clipped_words: 333
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10], [P2.11]
- cited_claim_ids: [C1.2], [C1.7], [C1.3], [C1.5], [C1.4], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] CON's best line is that age-based exclusion is "the model working" [C1.2]. That is exactly the problem. In hiring, age-based screening is already illegal. A model that "works" by learning that older applicants rarely got hired is not discovering risk.
[P2.2] It is automating a practice the law already forbids, then hiding it behind a graduation year.
[P2.3] First, CON blurs pricing into exclusion. I never argued for age-blind premiums. Charging a seventy-year-old more for life insurance is validated risk. Denying a sixty-five-year-old with steady income and a clean record a credit card because a proxy flagged her cohort is not.
[P2.4] Mortality tables do not justify that denial. So the "subsidy" argument [C1.7] attacks a policy nobody proposed.
[P2.5] Second, the claim that disparate impact makes "every ordinary hiring criterion presumptively unlawful" [C1.3] is refuted by decades of practice. Disparate-impact liability has always let employers defend genuine job-related criteria. Current employees can already bring age disparate-impact claims, and entry-level postings and certification requirements survived. My proposal extends the same rule to applicants, the people these tools screen.
[P2.6] A real requirement passes. "Graduated before 1990" does not.
[P2.7] Third, CON's inspectability point [C1.5] is my argument. Yes, a model can be run against a test population and measured. But who runs it? Today, nobody has to, and the rejected applicant cannot.
[P2.8] Inspectability that no one is obliged to use protects no one. Mandatory audits turn CON's theoretical virtue into actual accountability.
[P2.9] And the retreat to "a recruiter's gut" [C1.4] will not happen. Firms automate because screening thousands of applications by hand is ruinously expensive. An audit is cheap next to that. Human recruiters also remain covered by existing law, so there is no loophole to flee into.
[P2.10] Finally, notice CON's admission: existing law reaches "intentional proxies" [C1.6]. Intentional. Algorithmic harm is almost never intentional. CON has conceded the gap I described.
[P2.11] On scale, the choice is clear. A biased manager rejects dozens. A biased model rejects millions, invisibly. The law should scrutinize the decision-maker whose errors multiply fastest.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9], [C2.10], [C2.11]
- cited_claim_ids: [P2.3], [P2.5], [P2.10], [P2.6], [P1.3], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal turns on one distinction: pricing is fine, "exclusion" is not [P2.3]. But those are the same act at different points on a curve. A premium set at genuine risk for a seventy-five-year-old's disability coverage is one no seventy-five-year-old can pay. Call that a denial and it's "exclusion"; call it a quote and it's "validated pricing."
[C2.2] PRO's motion hands that label to litigants. The distinction does no work except to make every high quote actionable.
[C2.3] Now the credit-card example [P2.3]: a woman with steady income and a clean record denied because a proxy flagged her cohort. Ask why any lender would do that. She is profitable. A model that rejects profitable customers loses money, and competitors take her.
[C2.4] Markets punish inaccurate proxies faster than any court. The proxies that persist are the ones that predict.
[C2.5] On disparate impact, PRO says decades of practice prove employers can defend criteria [P2.5]. Notice what that practice actually shows. Employee claims under age law already come with a "reasonable factor other than age" defense, because Congress recognized age correlates with legitimate factors in a way race does not. Courts excluded applicants deliberately.
[C2.6] PRO must argue those courts and that statute got it wrong, not that a gap appeared by accident.
[C2.7] And PRO's key admission: "Algorithmic harm is almost never intentional" [P2.10]. Then what is it? Criteria that legitimately matter, producing lopsided age results. PRO has just described accuracy and called it harm.
[C2.8] "Graduated before 1990" [P2.6] is an intentional proxy and already unlawful, as PRO's own opening concedes when it cites regulators pursuing exactly those companies [P1.3]. The enforcement PRO says doesn't exist is the evidence PRO opened with.
[C2.9] Finally, "who runs the audit?" [P2.7]. PRO's opening answered: regulators did. That's the current system working.
[C2.10] PRO's alternative is not audits instead of nothing. It is applicant lawsuits over every experience cap, salary band, and certification requirement, with the burden on the firm.
[C2.11] Scale cuts against PRO. One corrected model fixes millions of decisions. One frightened recruiter fixes nothing, and leaves no log.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 97
- clipped_words: 97
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.8], [C2.11], [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say "graduated before 1990" is "an intentional proxy and already unlawful" [C2.8]. If a model learns that proxy on its own and no human ever intended it, which existing law lets the rejected applicant win? She cannot see the model, and several appeals courts bar her from bringing a disparate-impact claim.
[P3.2] Q2: You say "one corrected model fixes millions" [C2.11]. Without a mandatory audit, who is actually obligated to find the error and correct it? And if your answer is "markets punish inaccurate proxies" [C2.4], why did the automated age-rejection cases regulators pursued ever happen?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 110
- clipped_words: 110
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.6], [P1.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: A seventy-eight-year-old is quoted a long-term-care premium accurately priced to her risk that she cannot pay. Under your motion, is that "validated pricing" [P2.3] or "exclusion"? If the answer is "it depends," who decides, and what stops every unaffordable quote from becoming a lawsuit?
[C3.2] Q2: You say "a real requirement passes" [P2.6]. Concretely: does an "entry-level, zero to three years' experience" posting, or "certification earned within five years," require a firm to defend itself in court once an applicant shows a lopsided age result? If yes, explain why firms won't simply stop logging. If no, name what your motion adds beyond the enforcement you cited in your opening [P1.3].

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 356
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8], [P4.9], [P4.10], [P4.11]
- cited_claim_ids: [C2.5], [P1.3], [P3.1], [C2.4]
- missing_claim_id_refs: (none)

[P4.1] A1: Validated pricing. The seventy-eight-year-old's quote is lawful, and my motion leaves it lawful. The line was never the size of the number; it is the basis for it. A premium grounded in actuarially supported individual risk is pricing, however painful.
[P4.2] Exclusion is a denial or surcharge driven by an unvalidated proxy for her cohort, such as a model that rejects anyone whose browsing pattern "looks old" regardless of health. Who decides? The insurer documents its variables in an audit, and a regulator or court checks whether they are validated. That is what insurance regulators already do when reviewing rates for unfair discrimination.
[P4.3] Unaffordability alone is never a claim, so no flood of lawsuits.
[P4.4] A2: No, those postings do not become courtroom crises. The applicant must identify a specific practice and show a disparity. The firm then invokes the "reasonable factor other than age" defense, which CON itself described [C2.5] as built for exactly this correlation. A genuine entry-level role, or a certification requirement for current technical work, clears that defense quickly.
[P4.5] CON's own point answers CON's fear.
[P4.6] What does my motion add beyond [P1.3]? The cases I opened with involved explicit, programmed age cutoffs, where a human typed the rule. My motion reaches the learned proxy that no one typed. It also answers "won't firms stop logging?"
[P4.7] Under mandatory audits, not testing is itself the violation. Firms cannot abandon screening software without drowning in applications.
[P4.8] That exchange settles the debate. Every CON warning about unaffordable quotes, experience caps, and salary bands falls under defenses my motion keeps intact. What remains is the case CON still has not answered from my first question [P3.1]. A model learns a graduation-year proxy on its own.
[P4.9] The rejected applicant cannot see it, cannot sue for disparate impact, and has no auditor on her side.
[P4.10] CON's fallback is the market [C2.4]. But when hundreds of people apply for one job, rejecting a qualified sixty-two-year-old costs the firm almost nothing. Nothing punishes that error, so nothing corrects it.
[P4.11] CON has defended a system that is [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 353
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.6], [P4.4], [P4.10]
- missing_claim_id_refs: (none)

[C4.1] A1: She wins the way she would against a recruiter who "learned it on his own": the employer answers for the criteria it deploys. Enforcers have already treated built-in graduation-year and age-band filters as age discrimination without proving anyone meant harm, because choosing to run the tool is the intent. PRO now concedes those cases involved rules "a human typed" [P4.6].
[C4.2] But if a vendor's model learns the identical rule, the employer running it is still rejecting her on age; opacity is a discovery problem, and courts order discovery. Where private applicant disparate-impact suits are barred, that reflects a statute that already hands employers the reasonable-factor defense. PRO's own A2 says ordinary criteria clear that defense "quickly" [P4.4]. So the standing PRO wants to create is mostly the right to lose faster.
[C4.3] A2: The deploying firm is obligated, because keeping a tool after it shows an age skew is knowing use, and regulators enforce exactly that. That is why the cases PRO cites exist. They did not happen because markets failed; they happened because someone hard-coded a cutoff and the law caught it. And PRO's own point [P4.10] finishes the market question: if hundreds apply for one job, rejecting a qualified sixty-two-year-old costs the firm nothing, and it also means her odds were one in hundreds regardless of age.
[C4.4] No audit changes that arithmetic. What an audit changes is the criteria: a model tuned for age parity must discount experience-related signals exactly where they predict.
[C4.5] Now watch what the motion shrank to across PRO's answers. Unaffordable premiums: lawful. Entry-level caps, certification windows, salary bands: lawful. Typed proxies: already unlawful.
[C4.6] What remains is an audit mandate aimed at learned proxies. A learned proxy that predicts nothing costs the firm money and gets pruned. A learned proxy that predicts something is a reasonable factor other than age and passes PRO's own defense. The motion catches only the sliver in between, and delivers the engineer a suit she loses "quickly" plus an audit report she never sees.
[C4.7] That is stronger protection protecting no [clipped]

## Turn 9: PRO Closing

- model: claude-opus-5-5-high
- raw_words: 211
- clipped_words: 211
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: [C4.6]
- missing_claim_id_refs: (none)

[P5.1] CON's final move was to call what remains "the sliver in between" [C4.6]. That sliver is the whole motion, and it is where older applicants are actually being rejected.
[P5.2] CON's test is that a proxy that "predicts nothing" gets pruned, and one that "predicts something" passes. But predicts what? A screening model trained on past hiring decisions predicts who used to get hired. If managers passed over sixty-year-olds, a graduation-year signal "predicts" perfectly.
[P5.3] The firm never prunes it, because it is not losing money; CON already agreed rejecting one qualified applicant among hundreds "costs the firm nothing." Yet it is not a reasonable factor other than age. It is age, laundered through history.
[P5.4] Every protection CON offered depends on someone already knowing. "Knowing use" requires knowledge. "Courts order discovery" requires a lawsuit the applicant is barred from bringing. Enforcement caught cutoffs "a human typed."
[P5.5] CON's system works only when bias is visible, and the defining feature of learned proxies is that nobody sees them.
[P5.6] My motion supplies the missing step. Audits make firms look. Applicant standing lets the person harmed ask the question. Real requirements and validated pricing still pass.
[P5.7] CON protects the sixty-two-year-old engineer only if someone typed the rule that rejected her. She deserves protection when no one did.

## Turn 10: CON Closing

- model: claude-fable-5-1-high
- raw_words: 225
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.2], [P4.1], [P4.4], [P5.3], [P4.10]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing finally names the target: a proxy that "predicts who used to get hired" [P5.2]. But that sentence is the case collapsing, not closing. If a signal merely echoes past managers, the test is whether it predicts who *performs*. Employers validate against performance, because a model that recycles stale preferences costs them talent; the same logic PRO used for insurance rates, "actuarially supported" [P4.1], applies here.
[C5.2] Experience-related signals that predict performance pass PRO's own reasonable-factor defense "quickly" [P4.4]. So the engineer gains standing and loses.
[C5.3] Notice what remains impossible for PRO. Either the defense works, and the motion hands her a suit she cannot win plus an audit she never sees, or the defense does not work, and every experience cap, salary band, and certification window is on trial the moment an applicant shows a lopsided age result. PRO spent two speeches insisting the first; the closing's "age laundered through history" [P5.3] argument only bites under the second. PRO cannot have both.
[C5.4] And the engineer? PRO conceded her odds were one in hundreds regardless [P4.10]. No audit changes that arithmetic. What changes is the criteria: models pushed toward age parity must discount experience precisely where it predicts.
[C5.5] That is not protection catching up to code. It is accuracy being legislated away, with younger applicants and honest employers paying for [clipped]
