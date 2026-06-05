# Debate prop_0653__step-3.7-flash-high__grok-4.3__s1__tpl_placement_active_20260320f

- topic_id: prop_0653
- proposition: Companies should be banned from using AI to predict an individual worker's future productivity, unionization likelihood, or chance of quitting.
- model_pro: step-3.7-flash-high
- model_con: grok-4.3
- side_swap: True

## Turn 1: PRO Opening

- model: step-3.7-flash-high
- raw_words: 223
- clipped_words: 223
- claim_ids: [P1.1], [P1.2], [P1.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The proposed ban on AI worker prediction tools is a necessary safeguard against unaccountable, discriminatory automation that erodes fundamental worker rights. These systems do not measure actual job performance: productivity predictors rely on arbitrary proxies like keystrokes, screen time, or mouse movement that systematically penalize neurodivergent workers, caregivers taking legally protected breaks, and disabled employees using assistive technology, mislabeling high-performing staff as low-productivity based on non-job-related traits. Even more insidious are unionization likelihood predictors, which let employers target and retaliate against workers before they exercise their legal right to organize.
[P1.2] These tools scrape communications, social media activity, and workplace interaction patterns to flag "high risk" organizers, enabling preemptive termination, demotion, or punitive scheduling that chills protected concerted activity for entire workforces. No worker can challenge a label marking them as a suspected union supporter before their employer acts on it. Quit risk predictors compound this harm, used to justify denying promotions, raises, or reasonable accommodations to workers flagged as "likely to leave," often for seeking better pay or safer conditions.
[P1.3] Unlike traditional performance reviews, these black-box algorithms offer no transparency, no appeal process, and no way to correct false, biased assumptions baked into their models. This is not regulatory overreach: it is a minimal, critical step to stop employers from automating discrimination and rolling back the worker rights secured over decades of struggle.

## Turn 2: CON Opening

- model: grok-4.3
- raw_words: 207
- clipped_words: 207
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Banning AI predictions of productivity, unionization risk, and quitting would force managers to rely on slower, more subjective judgments that already embed the same biases the ban claims to fix. A warehouse supervisor deciding shift assignments without data might favor familiar faces or penalize visible absences, whereas an algorithm trained on output metrics can flag genuine underperformance across thousands of workers and route targeted training instead of blanket demotions.
[C1.2] The same holds for retention. When a model identifies employees whose patterns match past voluntary exits, the firm can intervene with schedule adjustments or pay reviews before the worker leaves. Blocking that signal leaves only reactive exit interviews after damage is done, raising costs that shrink wage pools for remaining staff.
[C1.3] Unionization predictions function similarly as early diagnostics. They surface clusters of dissatisfaction that management can address through policy changes rather than waiting for formal petitions that often follow prolonged friction. Outlawing the tool does not eliminate employer awareness of workplace sentiment; it merely ensures the awareness stays anecdotal and unevenly applied.
[C1.4] Workers gain nothing from forcing decisions onto less accurate methods. The alternative to data-driven forecasts is not neutral human judgment but noisier, harder-to-audit impressions that favor the connected and punish the atypical in less visible ways.

## Turn 3: PRO Rebuttal 1

- model: step-3.7-flash-high
- raw_words: 288
- clipped_words: 288
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- cited_claim_ids: [C1.1], [C1.2], [C1.3]
- missing_claim_id_refs: (none)

[P2.1] CON’s argument rests on a false choice: it pretends the only alternative to unaccountable AI prediction is unstructured, biased human judgment, when in reality we can use transparent, job-relevant performance data without speculative black-box labels that penalize workers for exercising their rights. First, CON claims productivity predictors flag genuine underperformance better than managers [C1.1], but these tools do not measure actual output. They rely on arbitrary proxies like keystrokes, screen time, and mouse movement that systematically penalize neurodivergent workers, caregivers taking protected breaks, and disabled employees using assistive technology—mislabeling high-performing staff as low-productivity for non-job-related traits.
[P2.2] A single biased manager might harm a handful of workers, but a black-box algorithm codifies that bias at scale, with no avenue to appeal a false label that blocks promotions, raises, or even employment. CON next claims quit risk predictors let firms intervene before valued staff leave [C1.2], but the overwhelming real-world use of these tools is not to address low pay or unsafe conditions, but to target workers who have asked for raises, reported harassment, or raised safety concerns for denial of advancement or preemptive termination.
[P2.3] The “reactive exit interview” CON fears is vastly preferable to being punished for a speculative algorithm’s prediction that you might leave, even when you have no intention of doing so. Finally, CON frames unionization predictors as neutral early-warning systems [C1.3], but in practice they are used to identify and retaliate against lead organizers before they can file formal petitions, chilling protected concerted activity for entire workforces. There is no evidence these tools are deployed to “address policy changes” rather than suppress organizing.
[P2.4] A ban does not eliminate the use of performance data; it only blocks speculative, unaccountable predictions that automate discrimination and erode worker rights.

## Turn 4: CON Rebuttal 1

- model: grok-4.3
- raw_words: 251
- clipped_words: 251
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] The PRO rebuttal insists a ban merely stops speculative black-box labels while leaving ordinary performance data untouched, yet this distinction is empty. Forward-looking predictions of productivity, quitting, or dissatisfaction are the only data that let managers move from reacting to events already underway to adjusting conditions before harm accumulates. Blocking them leaves firms with after-the-fact metrics that cannot flag an employee whose output is about to drop due to schedule conflicts or whose departure is imminent because comparable roles elsewhere pay more.
[C2.2] The scale argument fares no better. A single biased supervisor affects limited workers; an algorithm trained on aggregate output flags patterns across thousands and can be audited or retrained once discrepancies appear. Human impressions, by contrast, stay locked inside individual heads with no comparable record. PRO offers no mechanism that would make those impressions suddenly fairer or more correctable once the predictive layer is removed.
[C2.3] On retaliation, the proper response is stronger enforcement of existing labor statutes, not the elimination of early signals. Without those signals, employers still sense unrest through word of mouth or exit data; they simply act on it with less precision and no opportunity for preemptive policy fixes that might raise wages or improve conditions for everyone. The same logic applies to retention forecasts. Denying firms the chance to spot and address flight risk before it materializes raises turnover costs that ultimately reduce resources available for the remaining workforce.
[C2.4] A ban therefore trades measurable, adjustable forecasts for noisier, harder-to-challenge discretion without reducing underlying employer incentives.

## Turn 5: PRO Pressure Questions

- model: step-3.7-flash-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You claim algorithms can be audited once discrepancies appear [C2.2], but when the proxy is screen time or keystrokes, the so-called discrepancy is a neurodivergent worker's disability—not a model error. What audit mechanism catches that bias before the worker is fired?
[P3.2] Q2: You say labor statutes suffice without a ban [C2.3], but when a secret algorithm flags suspected organizers and the employer quietly denies them promotions, what enforcement process discovers the causal link when there is no paper trail?

## Turn 6: CON Pressure Questions

- model: grok-4.3
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO claims ordinary performance metrics can replace forward-looking predictions without loss [P2.4], yet how would firms detect an employee’s imminent departure or rising dissatisfaction before output actually falls, using only after-the-fact numbers?
[C3.2] Q2: If the ban permits “job-relevant” data but outlaws any model that forecasts quit risk or union interest, what concrete test distinguishes the two when both rely on the same underlying patterns of schedule changes or pay complaints?

## Turn 7: PRO Rebuttal 2

- model: step-3.7-flash-high
- raw_words: 407
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: [P3.1], [P3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: The flaw in C3.1 is it treats catching hypothetical future worker behavior as a worthy goal, when that hypothetical behavior is often a legal, protected choice workers have not even acted on. Employers can address emerging dissatisfaction through transparent, voluntary mechanisms like regular check-ins, anonymous worker surveys, and stay interviews—tools that do not penalize workers for considering legal options like quitting or organizing before they take any action. For example, an autistic worker using noise-canceling headphones and taking short sensory breaks may be flagged as low-productivity by screen time proxies even if they complete 20% more tasks than peers; the harm of preemptively punishing workers for unacted-on thoughts or non-work-related traits far outweighs the minor cost of addressing issues after workers raise them voluntarily, rather than using secret algorithms to punish them preemptively.
[P4.2] A2: The test C3.2 demands is straightforward, rooted in the core harm the ban addresses: permitted tools measure current, job-related performance using direct, transparent metrics (e.g., completed project deliverables, on-time attendance for scheduled shifts, verifiable sales output) to evaluate existing work. Banned tools, by contrast, scrape indirect, often non-work-related proxies (social media activity, break timing, communication metadata, keystrokes unrelated to deliverables) to forecast future, legal, protected choices—whether a worker will quit, organize, or see future productivity drops tied to non-job factors—and use those predictions to penalize workers before they take any action.
[P4.3] CON’s “same underlying patterns” framing is a false equivalence: a worker’s current pay complaint is actionable to fix wages; using it to predict they will quit and deny them a promotion is the exact banned conduct the ban targets. These answers expose the fatal flaw in CON’s entire case: it prioritizes speculative managerial convenience over concrete, scalable worker harm. CON still has no answer to how a black-box algorithm’s bias against neurodivergent workers can be audited before they are fired [P3.1], or how a secret label marking a worker as a suspected organizer can be surfaced when there is no paper trail of retaliation [P3.2].
[P4.4] The ban does not eliminate legitimate performance management—it [clipped]

## Turn 8: CON Rebuttal 2

- model: grok-4.3
- raw_words: 247
- clipped_words: 247
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Audit mechanisms exist through outcome tracking and periodic human review rather than proxy inspection alone. Firms can compare model-flagged productivity drops against verifiable output metrics like units produced or sales closed; when a flagged neurodivergent worker meets or exceeds those metrics, the discrepancy triggers retraining or override. This process catches systematic bias at the point it produces measurable error without banning the underlying signal.
[C4.2] A2: Enforcement already uses statistical patterns in promotion and termination data under existing labor law. Disparate impact claims and union unfair-labor-practice filings routinely rely on aggregate outcomes rather than internal algorithm logs; courts and agencies have long inferred intent from timing and selection rates even when decision tools remain undisclosed. Adding a total ban does not strengthen those tools—it removes the data firms could otherwise use to demonstrate nondiscriminatory reasons.
[C4.3] These answers show that PRO’s concerns are manageable through targeted oversight instead of prohibition. A ban therefore strips away the only scalable method for spotting impending problems before they produce irreversible costs, while leaving firms with noisier, post-harm reactions that favor connected employees and raise turnover expenses passed on to remaining workers. The same logic applies to unionization signals: without forward indicators, management still detects unrest through anecdotes and exits, yet acts with less precision and no chance for preemptive fixes that could improve conditions for the entire workforce.
[C4.4] PRO’s framework thus trades adjustable forecasts for discretionary judgments that are harder to audit at scale and more likely to embed unrecorded bias.

## Turn 9: PRO Closing

- model: step-3.7-flash-high
- raw_words: 188
- clipped_words: 188
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: [C4.1], [C4.2]
- missing_claim_id_refs: (none)

[P5.1] The decisive flaw in CON’s case is that it treats speculative predictions of protected, unacted-on worker choices as a neutral managerial tool, ignoring that the entire purpose of these black-box systems is to penalize workers *before* they exercise legal rights, when no audit or labor filing can catch the harm. CON claims outcome audits catch productivity bias [C4.1], but a neurodivergent worker fired for low keystroke counts before they can complete their deliverables has no measurable “discrepancy” to trigger a review.
[P5.2] CON insists existing labor law suffices for union retaliation [C4.2], but a worker denied a promotion for a secret “unionization risk” label before they speak to colleagues has no paper trail of discrimination to bring a claim. CON’s talk of “preemptive fixes” is a smokescreen: these tools are not deployed to resolve worker complaints about pay or safety, but to punish those who raise them, or who might organize, before they can act. A ban is the only safeguard that stops employers from automating preemptive punishment for legal choices workers have not even made yet—protections no after-the-fact process can replicate.
[P5.3] That is why the ban must stand.

## Turn 10: CON Closing

- model: grok-4.3
- raw_words: 162
- clipped_words: 162
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The proposition fails because it eliminates the only scalable channel for identifying and correcting emerging problems before they generate irreversible losses that fall on remaining workers through higher turnover, compressed wages, and thinner margins for raises. Once output has already slipped or a colleague has left, audits and labor filings arrive too late to restore what was spent on recruiting, training, or overtime.
[C5.2] PRO treats those downstream costs as neutral or acceptable, yet they shrink the pool of resources available for everyone else and leave supervisors relying on the very anecdotal impressions the opening exchange showed are harder to correct at scale.
[C5.3] A firm that can still act on forward signals can adjust schedules or pay bands in time to retain the worker and preserve headcount stability; the ban converts that option into reactive damage control that cannot be undone after the fact. That difference in timing and reach is the decisive reason the prohibition harms the workforce it claims to protect.
