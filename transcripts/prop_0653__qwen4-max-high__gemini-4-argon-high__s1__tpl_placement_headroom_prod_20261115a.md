# Debate prop_0653__qwen4-max-high__gemini-4-argon-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0653
- proposition: Companies should be banned from using AI to predict an individual worker's future productivity, unionization likelihood, or chance of quitting.
- model_pro: qwen4-max-high
- model_con: gemini-4-argon-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] There is a difference between measuring work and forecasting a person. Counting the calls you handled last month is accountability. Predicting whether you will organize, quit, or slow down — and acting on that score today — punishes you for something you have not done and may never do. That is the practice this ban reaches, and it should.
[P1.2] Start with unionization, because it exposes the whole enterprise. Ask what a manager is supposed to do with a list of likely organizers. There is exactly one actionable use: move first. Cut their hours, split them across shifts, find a pretext to fire them before the card signing starts.
[P1.3] The score has no purpose except to defeat a legally protected right, and it does damage even when wrong, because workers who suspect they are being profiled stop talking to each other. That chilling is the product, not a side effect.
[P1.4] Flight-risk and productivity scores fail differently: they manufacture their own evidence. A woman flagged as likely to quit is passed over for training, then quits — and the model is declared accurate. Nobody observes the counterfactual. Meanwhile the inputs are proxies: gaps in shifts, medical leave, zip code, a complaint filed last spring.
[P1.5] Pregnancy, disability, and race walk in through the back door wearing a probability.
[P1.6] Regulation cannot fix this, because the injury is the inference itself. You cannot meaningfully consent to scoring when refusal costs you the job, and transparency only tells the worker the name of the machine that ranked her. We already accept that some employer inferences are simply off-limits — lie detector tests, genetic screening, blacklists of union members. This belongs in that category.
[P1.7] Judge the work a person actually does. Not the prophecy about them.

## Turn 2: CON Opening

- model: gemini-4-argon-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.1], [P1.4], [P1.5], [P1.2], [P1.3], [P1.6]
- missing_claim_id_refs: (none)

[C1.1] Predicting a workplace problem does not mean punishing the worker [P1.1]. In reality, predicting a problem is how good employers help workers before it is too late. When a hospital uses AI to predict which nurses face a high chance of quitting or a productivity drop from exhaustion, it does not punish them; it offers retention bonuses, lighter shifts, or extra support. Banning these models blinds organizations to burnout until the resignation letter is already on the desk.
[C1.2] Furthermore, this ban does not eliminate workplace forecasting; it just makes it un-auditable. Every promotion, staffing plan, and raise is a prediction of future productivity and retention. Without AI, managers still guess who will slow down or quit [P1.4]. They simply rely on gut instinct, the exact place where stereotypes about pregnancy, disability, and race [P1.5] thrive invisibly.
[C1.3] You cannot inspect a manager’s subconscious bias. You can audit an algorithm, forbid protected inputs like medical leave [P1.4], and mathematically test for disparate impact.
[C1.4] What about unionization [P1.2]? Cutting hours or firing workers to stop a union drive is already illegal under labor law, and coercive surveillance that chills organizing [P1.3] is already actionable. Meanwhile, predicting labor dissatisfaction legitimately helps executives spot toxic supervisors and raise wages voluntarily. The injury is not the inference [P1.6]; it is the unlawful retaliation.
[C1.5] Ironically, a blanket ban makes catching bad actors harder. When an employer uses software to target organizers or sideline mothers, it leaves a discoverable digital trail of inputs and weights that regulators can subpoena. Push those predictions back into unrecorded managerial whispers, and the retaliation continues without the evidence.
[C1.6] We do not ban spreadsheets because bosses might list union activists on them. Regulate the data and punish illegal retaliation, but do not outlaw tools that help workers stay and succeed.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 290
- clipped_words: 290
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The nurse story assumes the score stays with a benevolent employer. But the same number that buys her a lighter shift also justifies skipping her for training — she's a flight risk. Nothing in the tool separates care from triage; only the employer's mood does. And burnout prediction needs hours worked, patient loads, vacancy rates: measurements of conditions, not prophecies about a person.
[P2.2] A hospital can staff the ward without ranking its nurses by loyalty. The sympathetic case survives this ban; only the individual score dies.
[P2.3] On gut instinct: a hunch is local, contestable, about one person. A score is portable, persistent, applied to ten thousand people at once, wearing the authority of mathematics. When a manager says "I don't think she's committed," you can argue. When the dashboard says 81% flight risk, the argument is over.
[P2.4] Banning the score repeals no anti-discrimination law; the biased boss stays liable. He simply cannot buy his bias by the seat. And an audit can test inputs for disparate impact; it cannot test the future of the woman who was never trained.
[P2.5] "Already illegal" is the weakest link. Retaliation law requires proving motive, and the score launders motive: the organizer is fired for "performance," and nobody knows a number existed. The worker who never learns she was scored never files. A ban is enforceable where enforcement is cheap — at purchase and deployment — not years later in a discovery fight over a subpoenaed spreadsheet.
[P2.6] That is why we ban lie detectors rather than auditing them, and outlaw union blacklists rather than waiting for the firing. The spreadsheet analogy proves our point: we do ban the list. Some inferences are wrong to make about a person, however accurate the vendor claims to be.

## Turn 4: CON Rebuttal 1

- model: gemini-4-argon-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.3], [P2.4], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Ward-level averages [P2.1] do not save individual workers. A hospital ward can have normal average patient loads while one specific nurse works consecutive night shifts, handles the hardest cases, and quietly burns out. Nor do ward averages help remote employees or solo technicians with no "ward." To give a struggling worker a retention bonus, a mentor, or a lighter schedule, you must identify the individual.
[C2.2] And we do not have to trust the "employer's mood" to separate care from triage [P2.1]: targeted regulation can easily prohibit using flight-risk scores to deny training or promotions while permitting them for retention support.
[C2.3] The defense of gut instinct [P2.3] relies on a fantasy about how workplace bias works. A biased manager does not announce, "I don't think she's committed," inviting a fair debate [P2.3]. He silently skips her for training and invents a pretext. In that world, the counterfactual problem [P2.4] is completely unsolvable: one woman is passed over, and she can never prove why.
[C2.4] Algorithmic scale [P2.3] is actually what solves this. When a model scores ten thousand workers, auditors can see patterns—like young mothers systematically losing training opportunities—that are invisible when scattered across hundreds of unrecorded managerial hunches.
[C2.5] Finally, scores do not launder illegal motive [P2.5]; they expose it. Under existing law, when a boss fires a union organizer using a human hunch and blames "performance," proving retaliatory motive is notoriously difficult. But if an employer buys union-scoring software [P2.5] or flags an organizer days before firing her, that digital trail is a smoking gun for regulators and whistleblowers. Conversely, enforcing a total ban "at purchase" [P2.5] fails in practice because turnover and productivity models are not standalone lie detectors [P2.6]—they are basic regressions built into standard enterprise software.
[C2.6] Ban the abusive actions, not the math.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 74
- clipped_words: 74
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Name one legitimate use of an individual unionization score that is not moving against the worker before she organizes. If none exists, what exactly does "regulate the use, don't ban the tool" leave permitted?
[P3.2] Q2: You say scale lets auditors catch mothers systematically denied training. Where is that denial recorded, and who files the complaint when the worker never learns she was scored? Without that record, isn't your smoking gun merely the inputs?

## Turn 6: CON Pressure Questions

- model: gemini-4-argon-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say hospitals can address burnout using "hours worked" and "patient loads" [P2.1]. If software uses those exact metrics to flag that one overworked nurse is likely to quit, so HR can offer her a retention bonus, does your ban outlaw helping her?
[C3.2] Q2: You claim a manager’s hunch is "contestable" when he says, "I don't think she's committed" [P2.3]. Why would a biased boss ever announce that out loud, rather than silently denying her training without leaving the company-wide statistical trail an algorithm creates?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: No — and that's the point. If the software flags "six consecutive night shifts, thirty hours of overtime," it is reporting what she already did. That's a workload record, and my ban doesn't touch it; give every nurse crossing that threshold the lighter shift. What the motion forbids is the extra step: converting her record into a prophecy about her future loyalty, then letting that prophecy travel to the people who decide training and promotion.
[P4.2] Your helping case survives entirely on the measurement. It never needed the forecast.
[P4.3] A2: Granted — he doesn't announce it. My comparison was about reach, not confession. You've now confirmed the silent denial is the norm, which means the model's trail records inputs and scores, not the training she never received. That was Q2, and it stands unanswered: no record of the denial, no complainant who knows she was scored, no counterfactual to audit.
[P4.4] You are auditing the prophecy and calling it justice, while the injury stays off the ledger.
[P4.5] And Q1 stands unanswered too. Name one legitimate use of an individual unionization score. "Spot toxic supervisors" needs complaints and turnover rates, not a ranked list of probable organizers. Your own framework — regulate the use — leaves that score with zero permitted uses.
[P4.6] That is a ban on an inference — our principle, not yours. The only remaining question is how far that principle runs, and a flight-risk score that quietly reroutes mothers away from training is the same wrong wearing a friendlier label.
[P4.7] Scale is not your friend here. A bigot harms the women he meets. A model harms ten thousand at once, and your audit arrives afterward, counting the damage. Better a harm that stays small and answerable than one that ships as a feature.

## Turn 8: CON Rebuttal 2

- model: gemini-4-argon-high
- raw_words: 288
- clipped_words: 288
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P3.1], [P3.2], [P4.1], [P4.3], [P4.7]
- missing_claim_id_refs: (none)

[C4.1] A1: A legitimate use of predicting individual unionization likelihood [P3.1] is proactive grievance resolution: identifying specific high-value technicians whose scheduling, safety, or pay complaints are driving them toward organizing, so leadership can conduct stay-interviews and fix their working conditions voluntarily. More importantly, even if labor boards barred union-scoring entirely under existing labor law, that cannot justify your proposition, which also bans productivity and retention forecasting. You are using one narrow edge case to outlaw the core tools of modern workforce support.
[C4.2] A2: Training denials do not need a secret "denial log" [P3.2] because every HR system records who receives training and promotions. When auditors cross-reference actual training recipients against flight-risk scores and demographics, the systematic exclusion of mothers jumps off the page. Nor does enforcement require a worker who already knows her score: mandatory algorithmic audits or a single bypassed employee filing a routine discrimination charge unlocks that entire company-wide dataset.
[C4.3] Those two realities decide this debate. Look at the arbitrary line drawn in [P4.1]: flagging a nurse with "six consecutive night shifts" and "thirty hours of overtime" is permitted, while predicting her chance of quitting is banned. Why is a blunt two-variable rule legal, while an AI model that catches complex burnout—combining shift irregularity, skill mismatch, and patient acuity—is outlawed? A threshold is just a clumsy prediction.
[C4.4] Banning AI simply forces employers to use worse math, missing the quietly struggling worker who does not fit a rigid checklist.
[C4.5] Finally, [P4.3] concedes our central point: biased managers silently deny training without announcing it. In a ten-thousand-person enterprise, the alternative to AI is not one isolated bigot [P4.7]—it is hundreds of managers making silent, unrecorded prophecies every day. Human bias already scales. Banning the algorithm just burns the evidence.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Everything CON offers ends in an audit, and an audit needs something to check against. The training records exist; the woman who would have stayed if she'd been trained does not. Cross-reference scores against outcomes and you get a model that looks brilliant: flag her, skip her, she leaves, prediction confirmed. That is not evidence of accuracy; it is the injury, filed as validation.
[P5.2] Their remedy cannot see the harm because the harm erases its own control group.
[P5.3] That is why the line isn't arbitrary. A threshold on night shifts is a rule about conditions — it fires for everyone who crosses it, and the nurse can point at her own hours and demand what the rule promises. A score is a verdict about her, and it travels wherever decisions get made. More variables don't make it fairer; they make it harder to contest.
[P5.4] Human bias scales too, but it never arrives wearing a certificate of accuracy.
[P5.5] Their union answer proves it: stay interviews follow complaints she actually filed. Nobody needed the prophecy.
[P5.6] Ban the inference that cannot be checked, cannot be answered, and rewards itself for the damage it does.

## Turn 10: CON Closing

- model: gemini-4-argon-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.1], [C4.2], [C2.2], [P5.3], [P5.5]
- missing_claim_id_refs: (none)

[C5.1] You cannot ban workplace forecasting; you can only choose whether it happens in the light or in the dark, and whether it is used to help workers or hurt them.
[C5.2] Consider the self-fulfilling prophecy in [P5.1]: a woman is labeled a flight risk, denied training, and quits. Banning AI does not stop that injury. When a human manager silently assumes a new mother will quit, skips her for training, and watches her leave, he feels vindicated too. The woman who would have stayed is equally erased [P5.1].
[C5.3] The only difference is that the manager’s silent prophecy leaves zero evidence behind.
[C5.4] An algorithmic audit does not celebrate her departure as "accuracy" [P5.1]. It cross-references scores against training records [C4.2], immediately catching that the employer used flight-risk predictions to withhold training rather than provide support [C2.2]. The algorithm is what proves the crime.
[C5.5] Yet to stop an abuse that regulation easily forbids, this ban outlaws early intervention. It restricts help to workers who cross a blunt overtime rule or file a formal complaint [P5.3] [P5.5], abandoning everyone who burns out quietly. Do not burn the evidence of discrimination just to blind the tools that help workers stay.
