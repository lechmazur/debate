# Debate prop_0657__muse-spark-1.1-high__claude-fable-5-1-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0657
- proposition: Democracies should create internationally shared early-warning systems for AI-enabled disinformation campaigns even if that requires limited sharing of sensitive intelligence methods.
- model_pro: muse-spark-1.1-high
- model_con: claude-fable-5-1-high
- side_swap: True

## Turn 1: PRO Opening

- model: muse-spark-1.1-high
- raw_words: 281
- clipped_words: 281
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] AI disinformation is not a series of national incidents. It is one transnational campaign surface hitting many elections at once. Generative models erased the cost and language barriers that once made large-scale interference hard. A single actor can now spin thousands of credible local news clones, synthetic audio calls to voters, and hyper-personalized social pushes across Germany, France, and the US in the same week.
[P1.2] By the time one country notices, the damage is viral.
[P1.3] No democracy can see this alone. Detection depends on signals scattered across jurisdictions: model fingerprints on a platform hosted in the US, payment for inference in Singapore, bot traffic routed through European telcos, linguistic artifacts visible first to the target country. Alone, each fragment looks like noise. Aggregated in a shared early-warning system, it becomes a recognizable attack pattern in hours, not months.
[P1.4] We already learned this from counter-terror and cyber: when the threat moves at network speed, defense must too.
[P1.5] The proposition accepts a real cost: limited sharing of sensitive methods. That cost is both necessary and controllable. Modern threat intel sharing never means emailing raw sources. It means sharing sanitized indicators, detection models, and tearline analysis among vetted democracies under tiered access and originator control, exactly as Five Eyes and NATO cyber centers do today.
[P1.6] The alternative is not secrecy but unilateral blindness while adversaries coordinate perfectly.
[P1.7] If democracies refuse to pool methods because they fear leaks, they guarantee a worse leak: the leakage of their own public sphere to hostile AI manipulation. An early-warning net does not stop every lie. It gives governments, platforms, and journalists what they now lack: time to pre-bunk, trace, and attribute before a synthetic fraud decides an election.

## Turn 2: CON Opening

- model: claude-fable-5-1-high
- raw_words: 329
- clipped_words: 329
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The motion asks you to spend the one asset you cannot replace to buy something you can get for free.
[C1.2] Start with what "sensitive intelligence methods" actually are in this field. Detecting an AI-enabled campaign means knowing which model fingerprints, which timing signatures, which infrastructure tells, which linguistic artifacts give the game away. That knowledge is only valuable while the adversary doesn't have it. Disinformation is an adversarial machine-learning problem: the moment a detector's features are known, the generator is fine-tuned against them.
[C1.3] In cybersecurity a burned exploit is patched. In this domain a burned method simply trains a better liar.
[C1.4] Now multiply that fragility by a coalition. A shared system is exactly as secure as its least disciplined member. Democracies include governments with penetrated services, with ministers who leak to friendly outlets, and with parties that are themselves clients of the adversary. Every additional access point is an additional route for Moscow or Beijing to learn precisely what we can see and therefore what to stop doing.
[C1.5] Five Eyes works because it is five, vetted over decades, not thirty.
[C1.6] Second, watch what the system becomes. "Early warning for disinformation" is a machine for officially labelling speech as hostile, and its output flows to platforms. Democracies disagree profoundly on where satire ends and manipulation begins. A shared feed exports the most restrictive standard and gives every government a foreign stamp to wave at domestic critics.
[C1.7] Worse, the feed itself is a target: an adversary who understands the indicators can plant them on legitimate opposition content and let our own alarm do the censoring. We would have built the launderer for their next campaign.
[C1.8] Third, the trade is unnecessary. The useful product is the warning: "a campaign is targeting your election, here is the sanitized pattern." That already moves through bilateral channels, platform trust-and-safety teams, and journalists without exposing how it was found. Provenance standards and public resilience do more, cheaper, and leak nothing.
[C1.9] Share the conclusions. Never the methods.

## Turn 3: PRO Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.3], [C1.2], [C1.9], [P1.3], [P1.5], [C1.4], [C1.5], [P1.6], [C1.6], [C1.7], [P1.2], [P1.7]
- missing_claim_id_refs: (none)

[P2.1] Secrecy does not keep a detector alive, sharing does. CON argues a method burns once known and then "trains a better liar" [C1.3]. That is precisely why hoarding fails. Adversaries already have open-source detectors, academic papers, and their own red teams probing which artifacts we catch [C1.2].
[P2.2] A single country guarding one timing signature will be evaded in a single fine-tune. A coalition swapping many signatures can rotate, ensemble, and retrain faster than the generator can adapt. In adversarial learning, diversity of training data beats obscurity.
[P2.3] That destroys the "share conclusions, never methods" [C1.9] fantasy. A sanitized warning like "you are being targeted" without how - no model fingerprint, no infrastructure pattern, no prompt watermark - is useless to a platform that must build a classifier today and a telco that must hunt bot traffic [P1.3]. What the motion asks is limited sharing: tearline indicators, detection models as black boxes, scoring rules under originator control [P1.5], not handing raw sources. That is method-sharing, but not method-burning.
[P2.4] Least-secure-member [C1.4] proves too much. Five Eyes works because it is five [C1.5] - yet NATO cyber, financial intelligence and counter-terror all share among thirty under tiering. We already accept that risk because the cost of not sharing is unilateral blindness while adversaries coordinate perfectly [P1.6]. If a minister leaks, you tier down his access; you don't blind everyone else.
[P2.5] Finally an early-warning net is not a censorship engine [C1.6][C1.7]. Flagging a synthetic clone network run on foreign inference credits is not labeling domestic satire. It protects speech by exposing foreign coordination instead of leaving each government to guess and overblock. And planting indicators backfires when detection requires correlation across jurisdictions, not one marker.
[P2.6] Leaking a trick is repairable; leaking an election is not. Democracies can rotate a method; they cannot rerun an election decided by fraud they saw too late [P1.2][P1.7].

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 337
- clipped_words: 337
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9], [C2.10]
- cited_claim_ids: [P2.3], [P2.4], [P2.2], [P2.1], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Notice what just happened. Asked to defend "limited sharing of sensitive methods," PRO redefined it as tearline indicators and black-box models, then conceded: "That is method-sharing" [P2.3]. Good. The debate is now honest.
[C2.2] So test the two claims that make method-sharing safe.
[C2.3] First, "black boxes" don't stay black. A detection model exposed to thirty services is a model that can be queried, and a model that can be queried can be extracted. Run enough candidate fakes past it, watch what trips it, and you have reconstructed its decision boundary without ever opening the box. The adversary doesn't need the weights.
[C2.4] It needs a login, and PRO's own tiering concedes logins will be misused: "if a minister leaks, you tier down his access" [P2.4]. Tier him down after what? After the ensemble is already in Moscow. Cyber can revoke a credential.
[C2.5] It cannot revoke knowledge.
[C2.6] Second, "diversity beats obscurity" [P2.2] gets the adversarial logic backwards. An ensemble is only robust while the attacker cannot see all of it. Pool every democracy's signatures into one system and you have converted thirty independent problems for the adversary into one target that, once penetrated, fine-tunes against everyone simultaneously. Today a leak in Lisbon blinds Lisbon.
[C2.7] Under the motion, it blinds Berlin, Ottawa and Washington in the same fine-tune. That is not resilience; it is correlated failure.
[C2.8] PRO's own analogies confirm the CON line. What NATO cyber and financial intelligence actually circulate [P2.4] is hashes, IP addresses, transaction records: facts about the adversary, not the classifiers that found them. That is sharing conclusions. The motion asks for more, and nothing in PRO's speech explains why the marginal secret method, the one adversaries don't already read in open papers [P2.1], should be the thing we put on a thirty-nation feed.
[C2.9] Finally the weighing. "Leaking a trick is repairable; leaking an election is not" [P2.6]. But the leaked trick is precisely how the election is lost: the campaign you never see is the one that studied your detectors. Share the warnings.
[C2.10] Keep the eyes.

## Turn 5: PRO Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.8], [P2.3], [P1.2], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: If sharing hashes and IPs [C2.8] counts as safe "conclusions," why does sharing a sanitized model fingerprint or black-box scorer under tearline [P2.3] suddenly burn methods, when that fingerprint is the only thing a platform needs to act in hours [P1.2]?
[P3.2] Q2: You warn pooling creates correlated failure [C2.6] — but if an adversary fine-tunes against Lisbon's secret, won't that same evasion blind Berlin anyway, so how does 30 separate hoards avoid correlation better than a shared rotating ensemble?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 96
- clipped_words: 96
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.6], [P2.4], [P2.1], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say a leaked method is "repairable" because democracies "can rotate" it [P2.6], and that a leaking minister is simply tiered down [P2.4]—after the leak. What exactly recovers a detection ensemble once it is already being fine-tuned against in Moscow, given you admit knowledge, unlike a credential, cannot be revoked?
[C3.2] Q2: You concede adversaries already read open-source detectors [P2.1]. So which methods does the motion add that are secret enough to matter yet safe enough for a thirty-nation feed—and which member decides whether a flagged network is "foreign coordination" or another member's domestic opposition [P2.5]?

## Turn 7: PRO Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 283
- clipped_words: 283
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C3.1], [P2.1], [P2.3], [C3.2], [P2.5], [C1.9], [P1.2], [P3.1], [C2.6]
- missing_claim_id_refs: (none)

[P4.1] A1: No single static secret recovers, but AI detection is not a static secret. What recovers is obsolescence. You deprecate the leaked feature family that week and rotate to new ones — a different watermark, a new timing signature, a new inference-payment trail — retrained on data you only get from pooling. Moscow may learn one slice of the ensemble, not the whole, exactly because you tier and compartment.
[P4.2] So tiering down after a leak [C3.1] stops the next slice, while the leaked slice loses value as you evolve. A lone hoarder has no second slice to switch to; once burned, blind permanently.
[P4.3] A2: Open papers give you public detectors. What they don't give [P2.1] is live private telemetry that is secret enough to matter: proprietary model fingerprints from frontier labs, correlated payment for inference clusters, cross-border telco timing, platform posting synchrony. Those are sensitive because they reveal sources, but they can be shared safely as tearline scores and rate-limited black-box APIs under originator control [P2.3]. Who decides if it's foreign coordination or domestic opposition [C3.2]?
[P4.4] No single member. The system requires multi-jurisdiction corroboration — e.g., US hosting plus EU bot traffic plus Singapore billing — and packages evidence; each democracy still decides its own response. That is not a foreign stamp to censor [P2.5].
[P4.5] That is why CON's alternative collapses. Sharing only conclusions [C1.9] leaves platforms and telcos with no classifier to run in hours [P1.2][P3.1]. And their correlated failure claim [C2.6] describes their world, not mine: if Lisbon's secret is evaded, Berlin is blind anyway because the same generator hits both. Only a shared rotating ensemble sees the evasion using another member's signal and alerts Berlin before the vote, not after.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 365
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.3], [P4.1], [P4.2], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: A hash or an IP address is a fact about the adversary. It tells Moscow nothing it doesn't already know—Moscow owns the server. Burn it and we lose one address, not one eye. A scorer is a fact about us: what we perceive, and therefore what to stop doing.
[C4.2] That asymmetry is the entire distinction. And platforms don't act on classifiers in hours; they act on lists—these accounts, these domains, these content hashes. Look at PRO's own "secret enough to matter" inventory [P4.3]: payment trails, telco timing, posting synchrony. Every item is an indicator about the adversary's behaviour, shareable as a conclusion today.
[C4.3] The one thing the motion adds is the scorer—the item a platform least needs to act and the adversary most wants to read.
[C4.4] A2: Berlin is not blinded by Lisbon's leak because Berlin never depended on Lisbon's method. A generator fine-tuned against a Portuguese timing signature still trips a German linguistic detector. Thirty independent problems require thirty penetrations. Under the motion, one login exposes the union.
[C4.5] PRO concedes each leak surrenders "one slice" [P4.1]—but a thirty-member feed offers thirty times the leaks, and every slice belongs to everyone. "A lone hoarder has no second slice" [P4.2] is simply false: serious services run multiple methods and rotate them alone. Rotation is not a coalition capability. It is ordinary hygiene PRO is selling back to us at the price of the eyes.
[C4.6] Two concessions now decide this. First: these methods are "sensitive because they reveal sources" [P4.3]. So the motion means source-revealing telemetry on a thirty-nation feed guarded by a "rate-limited API." A member with a login is not an outsider hammering an endpoint; a penetrated member is a patient one.
[C4.7] Rate limits slow extraction. They never stop it. Second: the system "packages evidence" and each democracy "decides its own response" [P4.4]. That is the foreign stamp exactly—the label arrives pre-attributed, and the member with an opposition to bury waves it.
[C4.8] Weigh it. PRO's own repair story says shared methods decay within weeks. The leak is permanent. Permanent [clipped]

## Turn 9: PRO Closing

- model: muse-spark-1.1-high
- raw_words: 163
- clipped_words: 163
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: [P1.1], [C4.4], [P1.2], [P2.2], [P4.1], [P3.1]
- missing_claim_id_refs: (none)

[P5.1] The whole debate turns on one fact my opponent never answers: the attack is already correlated. One generator clones local news and robocalls voters in Germany, France and the US in the same week [P1.1]. CON imagines Berlin unaffected when Lisbon's timing signature is burned [C4.4]. That's false in generative AI - the same fine-tune that evades Lisbon evades Berlin everywhere, because it's the same model.
[P5.2] If the threat is correlated, defense must be. Independent hoards guarantee correlated blindness, learning about the evasion only after the vote [P1.2]. A shared rotating ensemble [P2.2][P4.1] trades slices for survival; when Moscow learns one slice, we deprecate it and alert using another member's signal.
[P5.3] Tearline scores and black-box APIs are not the eyes - they are the union of facts our platforms need to act in hours [P3.1]. Hoarding a classifier that no one else can run doesn't protect it. It guarantees the election it was meant to protect is lost while we keep the secret.

## Turn 10: CON Closing

- model: claude-fable-5-1-high
- raw_words: 207
- clipped_words: 207
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.1], [P4.1], [P4.3], [C4.5]
- missing_claim_id_refs: (none)

[C5.1] The whole case now rests on one sentence: "the same fine-tune that evades Lisbon evades Berlin everywhere, because it's the same model" [P5.1]. That is the mistake that decides the debate.
[C5.2] A fine-tune does not evade countries. It evades detectors. A generator trained against a Portuguese timing signature still trips a German linguistic detector, because it was never trained against it. A correlated attacker facing thirty independent methods must learn thirty separate lessons.
[C5.3] A correlated attacker facing one pooled ensemble learns one—and PRO conceded each leak surrenders a slice everyone shares [P4.1]. The attack is correlated already; the motion is what correlates the defence. It manufactures the very blindness PRO fears.
[C5.4] Everything PRO says platforms need in hours—accounts, domains, payment trails, posting synchrony [P4.3]—is a fact about the adversary, shareable today as a conclusion. The single thing the motion adds is the scorer: what we perceive, and therefore what to stop doing. PRO admits it is "sensitive because it reveals sources," guarded by rate limits that slow a patient member with a login and never stop him.
[C5.5] Rotation is hygiene any service does alone [C4.5]. PRO is selling it back at the price of the eyes. Share every warning. Keep the one thing that cannot be unlearned.
