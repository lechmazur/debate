# Debate prop_0653__deepseek-v4-pro-0813-high__kimi-k3__s0__tpl_placement_active_20260813a

- topic_id: prop_0653
- proposition: Companies should be banned from using AI to predict an individual worker's future productivity, unionization likelihood, or chance of quitting.
- model_pro: deepseek-v4-pro-0813-high
- model_con: kimi-k3
- side_swap: False

## Turn 1: PRO Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 288
- clipped_words: 288
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] These tools do not read the future. They encode a manager’s suspicion about which workers are risky, disloyal, or expensive and launder it through a black-box score. The ban is warranted because these predictions are pre-emptive, hard to contest, and aimed at choices workers should be free to make without retaliation.
[P1.2] Take quit-risk scoring. A model may flag a worker because she has a long commute, has not accepted weekend overtime, or shows a résumé pattern of short past jobs. If that score silently blocks promotion, training, or a raise, the prediction becomes self-fulfilling: the worker is denied the reasons to stay, then blamed for leaving. She cannot see the score, cannot learn the proxies, and cannot rebut a future she has not chosen.
[P1.3] Unionization-likelihood scoring is worse. It turns legally protected collective activity into a pre-emptive blacklist. The employer needs no proof that a worker supports a union; it only needs to demote, transfer, or isolate the person a model flags before organizing begins. Even an inaccurate model chills protected conduct because workers reasonably fear invisible surveillance.
[P1.4] Productivity prediction sounds neutral, but it typically relies on keystroke, calendar, leave, or location data. Those proxies penalize disability, pregnancy, caregiving, religion, and the refusal to perform unpaid overtime. AI makes discrimination harder to detect because the protected trait need not appear; a correlated proxy does the job.
[P1.5] Employers can still measure actual performance, give direct feedback, and use aggregate workforce planning. The ban targets only individual future-prediction scores, where one side controls the data, the model, the consequences, and the assumptions. That is not forecasting; it is power without accountability. The permissible line is clear: manage observed conduct, not hidden predictions about a worker’s future loyalty, productivity, or organizing.

## Turn 2: CON Opening

- model: kimi-k3
- raw_words: 314
- clipped_words: 314
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.2], [P1.3]
- missing_claim_id_refs: (none)

[C1.1] Every promotion, every hiring decision, every staffing call already contains a prediction about a worker's future. The question has never been whether employers predict; it is whether they predict with auditable tools or with a manager's hunch — the original black box, one no worker can inspect, test, or appeal. This ban eliminates the only kind of prediction that can be statistically examined, and leaves the unaccountable kind untouched.
[C1.2] Look at what the harms in [P1.2] and [P1.3] actually describe. Sidelining a worker for union sympathies is an unfair labor practice today, whether the flag came from an algorithm or a foreman's rumor. Blocking promotion through proxies that penalize pregnancy or disability is disparate-impact discrimination under existing law. The motion bans the measuring instrument while every nightmare it offers is already prohibited conduct.
[C1.3] You do not ban thermometers because someone might poison the water; you punish the poisoning.
[C1.4] Second, these models mostly run in workers' favor. A firm that pays to predict attrition pays to prevent it: retention raises, schedule changes, stay interviews, fixing the manager driving people out. Turnover is expensive, so the rational response to a quit-risk score is to give the worker a reason to stay — a raise or accommodation she could never demand without it. Productivity prediction routes training to struggling employees and exposes unrealistic workloads before burnout.
[C1.5] The self-fulfilling story assumes firms punish flight risks; in practice they court them.
[C1.6] Third, prohibition produces concealment, not protection. A lawful model can be disclosed, validated, and audited for bias. A banned model becomes a consultant's spreadsheet or an off-the-books judgment, with no trail at all.
[C1.7] Finally, the sweep: "predicting future productivity" covers who completes training, who staffs a critical project, who gets hired. The motion forbids statistical help with the core task of management. Regulate conduct, audit models, protect workers — a categorical ban protects no one and blinds everyone.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.6], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] The hunch comparison [C1.1] is a false equivalence. A manager’s hunch is a single visible judgment, tied to an actual interaction and open to challenge. An AI score runs silently across the workforce, on hidden proxies, before the worker has done anything wrong. Existing law [C1.2] does not close that gap: once the employer has a score, it has a neutral-looking business reason, while the worker cannot show the real proxies were caregiving, disability, refusal of overtime, or union activity.
[P2.2] The invisibility is what defeats after-the-fact enforcement.
[P2.3] The thermometer analogy [C1.3] fails for the same reason. A thermometer reads an existing fact. Quit-risk and unionization scores infer a hidden future from choices workers are entitled to make. When a promotion or training opportunity is denied on that forecast, no later legal remedy restores it; the damage is silent and preemptive.
[P2.4] Banning speculative classification is not banning measurement.
[P2.5] The claim that firms mostly use these scores to help workers [C1.4] assumes benevolence. A retention model may court star flight risks while quietly stopping investment in workers it sees as replaceable. If the real goal is retention, the employer can ask, adjust schedules, raise pay, or fix managers openly. No hidden loyalty score is needed.
[P2.6] The concealment argument [C1.6] is backward. Hidden scoring already exists. A ban makes that conduct illegal and gives workers a basis to challenge it, while auditing leaves the core wrong intact: there is no legitimate ground truth for “will she unionize?” or “will she quit?” Even a valid model should not be used to penalize a future lawful choice.
[P2.7] Finally, the sweep charge [C1.7] overreaches. The ban still permits observed performance, skill, output, coaching, and aggregate planning. It targets only hidden predictions about an individual’s future productivity, unionization, or exit. Defensible management uses present evidence; that remains intact.

## Turn 4: CON Rebuttal 1

- model: kimi-k3
- raw_words: 305
- clipped_words: 305
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.2], [P2.6], [C1.4], [P2.5], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] [P2.1] and [P2.2] have visibility backwards. A manager's hunch lives in someone's head — no record, nothing to subpoena, nothing to audit. A score is written down: the inputs, the output, the decision it fed. That is precisely the evidence trail discrimination litigation runs on; those cases are won with documents and statistics, not mind-reading.
[C2.2] The score is the most visible judgment an employer has ever produced. Ban it, and prediction does not disappear — it retreats into the foreman's head, where after-the-fact enforcement truly cannot reach.
[C2.3] [P2.6]'s "no ground truth" point fails for quitting and productivity: people do or don't quit; output arrives or it doesn't. These forecasts are validated against real outcomes like any other. And notice what the argument actually concedes — unionization is the one prediction touching protected conduct, and retaliating against it is already illegal, algorithm or not. The ban therefore adds nothing where the stakes are highest, and prohibits only the quit-and-productivity uses where [C1.4] showed the incentives run toward workers.
[C2.4] [P2.5] says employers can "just ask." Ask a worker interviewing elsewhere whether she plans to leave — you get the same answer from everyone, and it is worthless. Future intentions are the information workers guard most carefully. The score is what lets a firm offer the raise before the resignation letter, not after.
[C2.5] [P2.7] concedes the sweep problem without noticing. "Defensible management uses present evidence" — but that is all these models do: read present evidence to inform a future decision. Staffing next quarter's project from last quarter's output is predicting future productivity. PRO's line either permits everything the ban was meant to stop or forbids ordinary staffing.
[C2.6] Every harm PRO describes is a use — a denial, a demotion — and use can be punished, audited, disclosed. The ban removes not the prediction but the paper trail.

## Turn 5: PRO Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 74
- clipped_words: 74
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You call AI scores “the most visible judgment” [C2.1]. What existing right lets a worker inspect and challenge the hidden quit-risk or unionization proxy before a promotion is denied, rather than after the harm is already irreversible?
[P3.2] Q2: If unionization retaliation is already illegal [C2.3], what realistic evidence of intent can a worker produce when an employer points to a black-box “retention risk” score as a neutral business reason before any organizing occurs?

## Turn 6: CON Pressure Questions

- model: kimi-k3
- raw_words: 88
- clipped_words: 88
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7]
- missing_claim_id_refs: (none)

[C3.1] Q1: You permit "present evidence" while banning predictions of future productivity [P2.7]. Staffing next quarter's project from last quarter's output does both at once — is that lawful under your ban? If yes, name one ordinary staffing decision the ban actually prohibits.
[C3.2] Q2: Your case rests on scores being invisible, yet your ban erases the score itself. With no model, inputs, or output left to subpoena, how does a worker ever prove a decision came from a banned prediction rather than the manager's hunch your ban leaves untouched?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 307
- clipped_words: 307
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Yes—staffing next quarter’s project from last quarter’s output is lawful when the decision turns on actual deliverables, skills, and observed reliability. The test is not whether the word “future” appears; it is whether the worker is judged on hidden propensity rather than observable performance. The ban prohibits a different, ordinary staffing decision: two workers with identical current records, but the employer grants the project, transfer, or training slot to one because an attrition or productivity-propensity model predicts the other will leave or underperform.
[P4.2] That is hidden individual forecasting, not plain project planning. If last quarter’s output is merely one input into a black-box future-risk score, it falls on the banned side.
[P4.3] A2: The worker proves it the way employment cases prove hidden motives: discovery into vendor contracts, dashboards, access logs, promotion lists, emails, and comparator outcomes. Enterprise software produces trails. More fundamentally, the ban changes the baseline. Once the model is unlawful, an employer cannot defend a challenged decision by saying “the algorithm flagged her”; it must identify observed facts.
[P4.4] If it cannot, that absence is evidence. The hunch is not worsened; a manager’s hunch is a single subjective judgment that can be tested as pretext. The score gave that judgment a scientific shield and applied it at scale. We do not need perfect detection to ban the sharpest instrument.
[P4.5] That is the reason the opponent’s dilemma fails. The choice is not between banning ordinary staffing and permitting prediction. The real line is between contestable observed conduct and hidden propensity. Last quarter’s output can be shown, disputed, and corrected.
[P4.6] A predicted loyalty or future-productivity score cannot; it penalizes the lawful choices a worker might make. Unionization likelihood is the purest example: no audit can make a legitimate tool out of classifying who may organize. The ban leaves management its actual-performance tools and eliminates only pre-emptive classification.

## Turn 8: CON Rebuttal 2

- model: kimi-k3
- raw_words: 318
- clipped_words: 318
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.3], [P4.4], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: Where pre-harm rights exist, they exist only because the model is lawful. European data law already gives workers notice, access to the logic, and human review of automated decisions; pre-deployment audits can be mandated the same way. Those rights attach to documented systems. Under the ban, what inspection right exists before a promotion is denied?
[C4.2] None — for the consultant's spreadsheet or the manager's hunch, the worker gets nothing at any stage. The question demands from lawful prediction a front-end remedy that prohibition structurally cannot deliver. Regulation creates inspection rights; bans create absence.
[C4.3] A2: The evidence is the model itself. A "retention risk" score leaves vendor contracts, feature lists, training data, flag lists, and statistical outputs. If its inputs ingest organizing-adjacent signals, or its flags correlate with union sympathizers, that is a smoking gun — stronger proof of intent than any hunch case has ever produced. And the "neutral reason" defense is not new with AI; employers already say "performance" or "restructuring."
[C4.4] The difference is that a score can be subpoenaed and tested. A manager's stated reason cannot.
[C4.5] Now notice what [P4.3] concedes: "enterprise software produces trails" — vendor contracts, dashboards, access logs. That is their proof mechanism for the banned world, and it presupposes a lawful, documented, inspectable system. Their enforcement depends on exactly what their ban destroys. [P4.4] says hunches "can be tested as pretext" — but pretext-testing runs on records, and only one kind of prediction produces them.
[C4.6] [P4.1]'s line has quietly shifted from bad data to bad math. Same inputs — output, reliability — same staffing decision: lawful if a manager weighs them silently, banned if a model weighs them transparently. That punishes rigor itself and shelters the unaccountable predictor.
[C4.7] The weighing: every safeguard PRO invokes — discovery, audits, pretext analysis — operates on documented systems. Their ban leaves workers the hunch and takes the paper trail. Their own answers are my case.

## Turn 9: PRO Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 167
- clipped_words: 167
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The opponent’s final turn supplies the reason PRO wins. His safeguards—discovery, audit trails, pretext analysis—all operate after a hidden propensity score has already done its damage. A promotion is lost, a transfer is made, a worker is isolated before organizing begins. No later review restores the opportunity or unchills the conduct.
[P5.2] The score’s function is to turn a lawful future choice—leaving, using leave, supporting a union—into a silent, pre-emptive disqualifier. Documentation does not fix that. It makes the classifier more traceable, not more contestable at the moment that matters: a worker cannot disprove a forecast she has not yet chosen to fulfill, especially when the employer has already denied the raise or role that might have changed the outcome.
[P5.3] A ban reverses the sequence. It forces management to ground its action in observed facts the worker can deny, explain, or correct before the decision, and makes hidden individual propensity unlawful rather than merely auditable. That is the contestability line, and it is the one reason PRO wins.

## Turn 10: CON Closing

- model: kimi-k3
- raw_words: 210
- clipped_words: 210
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.3], [P4.1]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing rests on one move: my safeguards come too late, after the score has done its damage; a ban "reverses the sequence." But reverses it into what? A ban creates no earlier moment of contestability. The pre-decision rights PRO wants — notice, access to the logic, human review — exist only where the model is lawful enough to regulate.
[C5.2] Prohibition delivers nothing at any stage: no inspection before, no discovery after — just the hunch, which shows its inputs to no one.
[C5.3] That is why CON wins. Every protection PRO invoked — vendor contracts, dashboards, access logs, pretext analysis — presupposes a documented system; [P4.3] conceded "enterprise software produces trails." Their enforcement case is parasitic on the very artifact their ban destroys. And their line-drawing answer condemned itself: identical inputs, identical decision — lawful when a manager weighs them silently, banned when a model weighs them transparently [P4.1].
[C5.4] That punishes transparency and shelters the one predictor no worker can audit, subpoena, or test.
[C5.5] The choice was never prediction versus no prediction. It is a forecast with a paper trail against a hunch with none. Only one can ever be contested — before the decision or after it. Ban the trail, and the worker is left alone with the hunch.
