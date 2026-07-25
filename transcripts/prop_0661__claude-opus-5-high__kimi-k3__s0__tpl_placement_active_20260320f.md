# Debate prop_0661__claude-opus-5-high__kimi-k3__s0__tpl_placement_active_20260320f

- topic_id: prop_0661
- proposition: Employers should be required to disclose algorithmic monitoring and performance-scoring systems to workers and regulators.
- model_pro: claude-opus-5-high
- model_con: kimi-k3
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-high
- raw_words: 348
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Start with the simplest fact about work: you can be fired by a number you have never seen.
[P1.2] A warehouse worker gets a termination notice for "time off task" and only afterwards learns that the clock counted a walk to the bathroom and a jammed scanner as idleness. A delivery driver watches her score fall and never learns whether the app punished her for taking the slower but safer left turn. A call-center agent is ranked by a sentiment model that reads her accent as hostility. In each case there is a rule governing her livelihood, and she is the only person in the building not allowed to read it.
[P1.3] That is the whole case for disclosure. Every other area of employment law already assumes that the standards you are judged by must be knowable: you get the handbook, the job description, the write-up, the notice of the policy you allegedly broke. Algorithmic scoring did not repeal that principle; it just made the rulebook machine-readable and then locked it in a drawer. Requiring disclosure restores the ordinary baseline rather than inventing a new right.
[P1.4] Notice how modest the ask is. Not a ban. Not a worker veto. Not open-sourcing the model.
[P1.5] Just: tell people they are being monitored, tell them roughly what is measured and how it feeds decisions about pay, discipline, and dismissal, and file that with a regulator.
[P1.6] Regulators matter because rights that cannot be seen cannot be enforced. Discrimination law, wage-and-hour law, safety law, disability accommodation — all of them depend on someone being able to ask what drove a decision. An undisclosed scoring system is not merely private; it is functionally immune. And error goes uncorrected: metrics are proxies, proxies drift, and the person best placed to say "that reading is wrong, the scanner was broken" is the worker the score is about.
[P1.7] So the question for the other side is narrow. What legitimate business interest requires that the standard for judging a human being remain a secret from that human being? Competitive advantage in [clipped]

## Turn 2: CON Opening

- model: kimi-k3
- raw_words: 321
- clipped_words: 321
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Notice what my opponent conceded to make this sound modest: "tell them roughly what is measured." No statute can compel "roughly." That vagueness is where the mandate collapses.
[C1.2] The motion ignores a distinction every workplace lives by: the standard versus the detection system. Employment law has always required the first and never the second. The warehouse worker is entitled to know time-off-task counts against her — and she does; it's in the policy. What no law requires is publishing the machinery: where the sensors sit, how the fraud model weights variables, which threshold triggers review.
[C1.3] We don't disclose how the expense-anomaly detector works, not to hide injustice, but because a detector whose logic is public stops detecting.
[C1.4] Disclosed metrics get optimized, not obeyed. Publish the exact telematics formula and you get brake-tapping and route-gaming — driving tuned to the number, diverging from actual safety. Publish which behaviors trip the insider-risk model and you've handed data thieves the map around it. Theft, fraud, and security monitoring only function because their logic is opaque.
[C1.5] The regulator half fares no better. Filing every scoring system with an agency builds a central repository of trade secrets — often the firm's core operational asset — one breach or public-records request from competitors. And it imposes a standing compliance regime on the corner shop with one scheduling tool alongside the gig platform.
[C1.6] The harms my opponent describes are real, but the remedy exists: a worker fired by a bad number can contest the firing — wrongful termination, discrimination, disability law — and in each forum the employer must produce and defend the system, which is how the jammed scanner actually gets fixed. Targeted disclosure when there is a grievance; this mandate is universal disclosure with none.
[C1.7] They ask what legitimate interest requires secrecy. Wrong frame. Detection systems, like locks, only work on people who don't have the key. You don't publish the key and call it transparency.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-high
- raw_words: 336
- clipped_words: 336
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.4], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] CON's whole case rests on a swap: they defend the secrecy of *fraud detectors* and ask you to apply it to *performance scores*. Those are opposites. A fraud detector is a lock — it works on the assumption most people never touch it. A performance score is a rule.
[P2.2] It runs on every worker, every shift, and it decides pay and dismissal. When my opponent says the standard must be disclosed but the detection machinery need not, they've conceded the motion, because in algorithmic management the score *is* the standard. "Time off task" isn't a policy plus a sensor; the number the sensor produces is the thing you're fired for. Tell the worker the policy and hide the counter, and you've told her nothing.
[P2.3] Then take the gaming argument seriously, because it's an admission. [C1.4] says publishing the telematics formula produces "driving tuned to the number, diverging from actual safety." So the employer knows the metric diverges from safety — and fires people on it anyway. If the only thing keeping the proxy honest is that workers can't see it, the proxy was never measuring what it claimed.
[P2.4] And workers already reverse-engineer these systems; they just do it badly, through rumor and superstition. Secrecy doesn't prevent optimization. It rations accurate optimization to whoever guesses best.
[P2.5] The litigation remedy in [C1.6] is circular. Discovery follows a claim, and you cannot plead a claim about a system you have never been told exists. The worker who thinks her manager disliked her never files. Disclosure is what turns an invisible grievance into a contestable one — it is the precondition for the very remedy CON offers as a substitute.
[P2.6] On the regulator: agencies hold confidential filings constantly — drug formulations, tax records, safety data. Confidential filing is routine legislative plumbing, as are size thresholds for the corner shop.
[P2.7] And "roughly" is not vagueness; it is materiality — the same standard securities and wage-notice law have applied for a century. Enough to know what you're judged by. That's the ask.

## Turn 4: CON Rebuttal 1

- model: kimi-k3
- raw_words: 332
- clipped_words: 332
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.2], [P2.3], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Notice the tell in [P2.2]: "the score *is* the standard." From there, disclosure supposedly requires the system's logic. It doesn't. A worker told "your scanner tracks pick rate and idle time; both drive discipline" knows exactly what she is judged by — the way a teacher judged on student growth knows the criterion without the value-added model's coefficients.
[C2.2] What PRO actually wants published is the instrumentation: weights, thresholds, triggers. Renaming the formula "the standard" is a merger by rhetoric, not argument.
[C2.3] Take their best point, [P2.3]: gaming "admits" the metric diverges from safety. Divergence is the condition of every proxy ever used — that is what proxy means. The question is whether disclosure makes measurement better or worse. Worse.
[C2.4] Published formulas get gamed, so the score becomes less truthful: more brake-tapping saints, more wrongful flags, more honest workers outranked by performers. The mandate manufactures the very inaccuracy PRO complains about, then files it with a regulator as if it were reliable data.
[C2.5] [P2.5]'s circularity fails on the facts. Workers know monitoring exists — scanners, cameras, and apps are visible, and notice of electronic monitoring is already legally required in a growing number of jurisdictions. You don't plead the algorithm; you plead the firing. The worker dismissed after a bathroom break knows the adverse action and its suspicious shape; that files the claim, and discovery compels the system into the open.
[C2.6] The "precondition" is supplied by the grievance itself.
[C2.7] The confidential-filing analogy fails on dynamism. A drug formula is static; scoring models retrain constantly. Either the filing is a stale snapshot with no oversight value, or it is a standing version-by-version obligation on every firm. And [P2.6]'s size thresholds quietly surrender the principle: if being fired by an unseen number is the injustice PRO describes, it does not become just below fifty employees.
[C2.8] PRO's case needs the number to be both law and lie — binding enough that workers must see it, corrupt enough that secrecy alone excuses it. It cannot be both.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-high
- raw_words: 93
- clipped_words: 93
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say a worker "knows exactly what she is judged by" once told pick rate and idle time count [C2.1] — so when she's fired at a threshold she was never shown, on a count that logged a jammed scanner as idleness, what specifically does she point to in order to say the number is wrong?
[P3.2] Q2: You concede notice of electronic monitoring "is already legally required in a growing number of jurisdictions" [C2.5]. Do you oppose those laws — and if not, which half of this motion are you actually against?

## Turn 6: CON Pressure Questions

- model: kimi-k3
- raw_words: 88
- clipped_words: 88
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7], [P2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: You defend "roughly" as the disclosure standard for workers [P2.7] — but what does the regulator get? If the actual weights and thresholds, the filing is a breach-prone trade-secret repository; if the same rough sketch, the oversight has no teeth. Which horn do you take?
[C3.2] Q2: A cashier's shrinkage score detects theft *and* triggers discipline — one system, both functions. Is its logic published, handing thieves the map your own lock analogy [P2.1] says must stay hidden, or kept secret, conceding performance scores can legitimately stay opaque?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-high
- raw_words: 345
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C1.6], [C2.5]
- missing_claim_id_refs: (none)

[P4.1] A1: Neither horn — because the disclosure is asymmetric by design. Workers get materiality: you are scored, here is what it measures, here is what it can trigger. Regulators get the specification, filed confidentially. That is not an exotic invention; agencies hold formulations, tax data, and safety filings every day.
[P4.2] And notice CON cannot press the trade-secret worry very hard, because their own alternative — litigation and discovery [C1.6] — hands the entire model to opposing counsel and a courtroom. If disclosure to a confidential regulator is intolerable exposure, disclosure to a plaintiff's expert is worse. On teeth: the filing exists so a regulator investigating a pattern of dismissals can compare what the firm told workers with what the system actually does. Dynamism helps me here.
[P4.3] A model that retrains constantly is a model that drifts, and drift is exactly what nobody is currently watching.
[P4.4] A2: Split by function, which is the split CON themselves introduced. The cashier's theft-detection logic — thresholds, triggers, what flags an investigation — stays confidential. What cannot stay secret is that a shrinkage score exists, that it feeds discipline, and that it was what moved against her. Because when a theft model fires someone, that is an accusation of dishonesty, and no legal system we recognise permits a secret accusation with a secret evidentiary standard.
[P4.5] I am not publishing the lock. I am insisting that when the lock names you a thief, you get to hear the charge.
[P4.6] Which is where the debate resolves. CON spent two speeches defending the confidentiality of detection machinery — and I have never asked for it. Strip that away and what remains is: workers should be told the systems that judge them exist and what they bear on, and someone with authority should be able to check. CON has already conceded monitoring-notice laws are spreading and declined to oppose them [C2.5].
[P4.7] So ask who bears the cost of error. Under CON, the worker bears it, silently, with no way to know a wrong number ever existed. Under this [clipped]

## Turn 8: CON Rebuttal 2

- model: kimi-k3
- raw_words: 337
- clipped_words: 337
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P2.2], [C2.7], [P4.4], [P4.3], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: She points to what every wronged worker points to — the outcome, and its mismatch with her own record. And notice: PRO's motion gives her nothing more. Under their own design [P4.1], workers get "materiality," never the threshold; the specification goes to the regulator. So in their world she is *also* fired at a threshold she never saw.
[C4.2] The difference is that my route — contest the firing, compel the records, expose the jammed scanner — actually reaches her case, while theirs files a rough sketch with an agency that never opens her file. No published threshold reveals a jammed scanner. Only the dispute does.
[C4.3] A2: I don't oppose notice laws; they are my distinction enacted — disclose the standard, not the machinery. The half of this motion I oppose is the half PRO keeps defending: disclosure of the scoring systems themselves, the instrumentation PRO insists "is the standard" [P2.2], plus a standing specification filing with regulators. That half is the breach-prone repository and the retraining treadmill [C2.7].
[C4.4] Now see what the motion has become. Workers get materiality — notice, which exists and is spreading. Theft-detection logic stays secret even when it fires people [P4.4] — my line, conceded. Small firms fall below thresholds — the principle, abandoned.
[C4.5] Strip each concession and all that remains is the confidential regulator filing, where dynamism bites hardest: a constantly retraining model yields filings either perma-stale or a version-by-version obligation on every employer. The drift PRO invokes [P4.3] is precisely what a snapshot cannot watch; watching drift requires a trigger, and the grievance is the trigger.
[C4.6] PRO's discovery comparison [P4.2] inverts the exposure. Discovery is bounded, supervised, under protective order, opened by an actual claim. The repository is universal, standing, centralized — a scalpel versus a warehouse of keys.
[C4.7] So the worker learns the standards that judge her, the machinery stays protected, and errors get corrected in adversarial contest. That is the law we have, improving. The mandate publishes the map, manufactures the gaming it condemns, and calls it transparency.

## Turn 9: PRO Closing

- model: claude-opus-5-high
- raw_words: 207
- clipped_words: 207
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: [C4.5], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] Everything CON built rests on four words: "the grievance is the trigger" [C4.5]. That is the load-bearing beam, and it does not hold.
[P5.2] A grievance is not a natural fact. It is something a person has to *form*. The worker who believes her supervisor thought she was slow does not file a claim; she updates her résumé. Adversarial contest, discovery, protective orders — every corrective CON offers is downstream of a worker suspecting there is something to contest.
[P5.3] Disclosure is what creates that suspicion. Without it, CON's entire remedy is a courtroom with no one in it.
[P5.4] And CON has conceded the answer. They do not oppose monitoring-notice laws [C4.3]; they accept the worker should learn what judges her. So the residual dispute is whether anyone with authority may also look. But an individual worker can only ever see her own firing.
[P5.5] Only a regulator can see that a scoring system fires the same demographic at twice the rate — the pattern no single plaintiff can plead and no protective order will ever surface.
[P5.6] CON calls the status quo "the law we have, improving." It improves precisely by moving toward this motion.
[P5.7] A right you cannot know you have is not a right. It is a rumour.

## Turn 10: CON Closing

- model: kimi-k3
- raw_words: 210
- clipped_words: 210
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P5.3], [P5.5], [C2.4], [C4.6]
- missing_claim_id_refs: (none)

[C5.1] "Disclosure is what creates that suspicion" [P5.3] — that is the whole of their close, and it is backwards. Suspicion is created by the firing. The worker dismissed after a bathroom break does not need a regulator's filing to wonder what happened; the scanner on her badge, the app on her phone, and the termination letter already tell her. That is why notice laws are spreading and why I never opposed them: she should know the standard.
[C5.2] She does.
[C5.3] What remains is the pattern argument [P5.5] — only a regulator sees demographic drift. True. And regulators see it the way they always have: complaint, investigation, compelled production. Nothing in my position denies an agency the system once it has reason to look.
[C5.4] What I deny is that it needs every firm's system, filed in advance, forever.
[C5.5] So the debate resolves to one sentence: everything PRO values arrives on trigger; the motion demands it standing and universal. The standing version is where the harms live — published instrumentation gets gamed into dishonest scores [C2.4], and the repository is a warehouse of keys [C4.6]. The triggered version is what actually fixes the jammed scanner.
[C5.6] Rights enforced on demand; measurement kept honest. That is the status quo improving — toward precision, not exposure.
