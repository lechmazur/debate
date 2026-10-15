# Debate prop_0461__claude-fable-5-1-high__muse-wonder-1.0-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0461
- proposition: Online platforms should be required to offer independent researchers privacy-preserving access to data on recommender systems’ societal impacts.
- model_pro: claude-fable-5-1-high
- model_con: muse-wonder-1.0-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 335
- clipped_words: 335
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9], [P1.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every day, a few companies run the largest behavioral experiment in human history. Recommender systems decide what billions of people see about elections, vaccines, their own bodies, and each other. And right now, the only people allowed to measure what that does to society are the people who profit from it.
[P1.2] That is the core of this debate. Not whether platforms deserve some secrecy, not whether privacy matters, but whether the referee of the experiment should be the experimenter.
[P1.3] We don't accept this arrangement anywhere else. Drug makers don't get to tell regulators "trust us, our internal trials look fine." Carmakers submit to independent crash tests. Banks are audited by outsiders.
[P1.4] In each case, the cost of outside scrutiny was outweighed by the simple fact that institutions grade themselves generously.
[P1.5] Platforms have already shown they grade generously. Leaked internal research in recent years indicated that at least one major company had studied harms to teenage users and kept the findings private. When independent access existed, it was voluntary and fragile: transparency tools were shut down, research APIs were priced out of reach, and the data taps closed precisely when findings became uncomfortable. Voluntary access survives only until it produces bad news.
[P1.6] That's why "required" is the operative word in this motion.
[P1.7] The privacy objection is answered by the motion itself: privacy-preserving access. The technology is mature. Differential privacy protects national census releases. Secure enclaves let vetted researchers run analyses on data they never download.
[P1.8] Clean rooms return aggregate outputs, not user profiles. Europe's Digital Services Act already mandates this kind of vetted researcher access for large platforms, so this isn't a thought experiment; it's an operating policy.
[P1.9] Nor does this expose trade secrets. Researchers need to know whether a system amplifies self-harm content or depresses local news exposure, not the weights of a neural network. Aggregate impact data isn't source code.
[P1.10] So the choice is stark: independent, privacy-protected measurement, or permanent darkness curated by the one party with a reason to keep the lights off.

## Turn 2: CON Opening

- model: muse-wonder-1.0-high
- raw_words: 351
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Independent scrutiny sounds unobjectionable until you ask what this mandate hands over: not a finished drug or a crash-test car, but the continuous behavioural record of billions of people — what they lingered on, searched for at 2 a.m., watched after a breakup, and were shown next. That record cannot be made both useful and safe simply by calling it privacy-preserving.
[C1.2] Viewing histories are fingerprints. A sequence of videos, posts, pauses and clicks is often unique even without a name, and linkage to outside datasets can re-identify it. Differential privacy and aggregation solve that only by destroying what researchers claim to need: if you add enough noise or suppress small cells to protect vulnerable minorities — teenagers exposed to self-harm content, a tiny community nudged toward extremism — those rare, concentrated harms disappear from the data. If you preserve those signals, you preserve identifiability.
[C1.3] Secure enclaves change the location of the risk, not its nature; outputs and repeated queries still leak, and universities are not hardened vaults.
[C1.4] Nor is “independent researcher” a neutral category. Someone must vet: a government, a platform, a professional board. Make vetting strict and you create licensed, politicised science, excluding critics, journalists and scholars in disfavoured countries. Make it loose and you invite competitors, foreign intelligence services, data brokers and campaign operatives behind academic affiliations.
[C1.5] There is no administrator powerful enough to police misuse who can also be trusted not to police viewpoints.
[C1.6] Even safe access would not deliver causal knowledge. Logs show what users saw and clicked, not what would have happened under a different ranking. Without running experiments or seeing ranking features — the very trade secrets said to be off-limits — outsiders will produce confident correlational stories about amplification that may reflect user demand, not algorithmic causation, then demand regulation on that basis.
[C1.7] A universal mandate therefore gives us the worst combination: real privacy exposure, illusory understanding, compliance costs only incumbents can easily absorb, and a new gatekeeper for research. Targeted regulator audits under confidentiality can investigate specific harms; a standing right for [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 356
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Strip away the atmosphere, and CON's case rests on one picture: a researcher downloading your 2 a.m. viewing history. That is not what the motion mandates. It mandates access to data on societal impacts, under privacy-preserving conditions. Nobody needs your watch list to learn whether teenagers in aggregate are shown self-harm content at rising rates, or whether local news reach fell after a ranking change.
[P2.2] Those are cohort-level questions over millions of users. Calling them "small cells" misdescribes them.
[P2.3] Where cells genuinely are small, disclosure control exists. Census bureaus and health registries have handled rare subgroups for decades without publishing fingerprints. CON says this destroys the signal. But the alternative CON offers is not a cleaner signal; it is no signal at all, with the platform alone deciding whether a harm to a small community ever gets counted.
[P2.4] Notice, too, what CON never mentions: platforms already share behavioural data with advertisers, contractors, and hand-picked academic partners under NDAs. The exposure CON fears already exists. The motion changes only who may ask questions, from people the platform chose to people it didn't.
[P2.5] On vetting, CON's dilemma proves too much. If "no administrator can be trusted not to police viewpoints," that condemns CON's own alternative, regulator audits under confidentiality, far more severely. A regulator is a single political actor whose findings stay secret. A vetted-researcher regime distributes scrutiny across universities, countries, and disciplines, and its findings are published and contestable.
[P2.6] And the status quo is already a vetting regime: run by the party being studied, revoking access when results sting.
[P2.7] On causation, CON argues that logs don't prove what a different ranking would do. Correct, and that is an argument for more access, not less. Platforms run ranking experiments every week; impact data can include their results without exposing model weights. CON's standard would also abolish epidemiology, which built public health on observational data.
[P2.8] So weigh it: a privacy-preserving, publicly accountable system of measurement, against CON's choice of secret regulators or permanent self-grading. CON has conceded outsiders should see this data. We're [clipped]

## Turn 4: CON Rebuttal 1

- model: muse-wonder-1.0-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO wants the mandate to shrink when privacy is mentioned and expand when knowledge is mentioned. That shuffle is the whole case.
[C2.2] If access is only cohort aggregates — self-harm exposure among teenagers, local news reach — it is either pre-computed by the platform, making independence theatre, or researchers can pose flexible queries in an enclave, restoring the fingerprint problem. Useful research means unanticipated slices by age, region, time, content and prior behaviour; each slice eases re-identification and output leakage. PRO cannot claim both open-ended inquiry and census-like safety.
[C2.3] The census is a static snapshot released once under controlled disclosure. Recommender logs are continuous, high-dimensional streams about people who never consented to research, and interactive access permits repeated queries that learn from prior answers. Health registries work because access is narrow and purpose-bound, not because small groups are easy to protect.
[C2.4] That platforms share data with advertisers and partners proves our distinction. Those recipients act under contract, defined purposes, monitoring and liability; they have no legal entitlement to interrogate the system and publish extracted outputs. Removing revocation for misuse while multiplying recipients does not equalise an existing risk — it scales it.
[C2.5] Scaling also answers vetting. A targeted regulator audit is bounded: one accountable institution, a specific suspected harm, confidentiality, and courts to check overreach. A standing regime needs a permanent gatekeeper to accredit thousands across borders, yet cannot recall insights once misused. Distributing access does not distribute accountability; it dissolves it.
[C2.6] Finally, causation exposes the expansion. If access includes results of platforms' own ranking experiments, knowledge remains platform-designed — independence becomes auditing summaries. If researchers shape experiments themselves, the motion becomes a right to intervene in product design, reviving trade-secret and consent problems.
[C2.7] PRO has not resolved the trilemma: safe, useful, truly independent — pick two. The mandate promises all three.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 92
- clipped_words: 92
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You concede regulator audits can investigate "specific suspected harms" safely under confidentiality [C2.5]. If a regulator can run flexible queries on these same logs without triggering your fingerprint problem, what exactly changes when a vetted academic types the same query in the same enclave — other than that the answer gets published?
[P3.2] Q2: Your bounded audit begins with a "suspected" harm. Who is supposed to suspect a harm the platform studied internally and never disclosed, when under your alternative no outsider can look until someone already knows what to look for?

## Turn 6: CON Pressure Questions

- model: muse-wonder-1.0-high
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Who sets the noise level, minimum cohort size, and permitted queries that count as “privacy-preserving” — and if a platform or regulator can veto a query on that basis, in what sense is the resulting research independent rather than curated?
[C3.2] Q2: Without ranking features or counterfactual experiments, how can a researcher prove a recommender caused an impact rather than merely reflecting user demand — and if experiments are allowed, who consents for the users experimented on?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 350
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: An independent standards body sets them, in rules published in advance and applied uniformly, with appeals. That is how disclosure control already works for census and health data: the statistician who releases a table did not design the cohort threshold, yet nobody calls the result "curated." Independence has never meant working without rules; it means the rules aren't written by the party under study, after it has seen the question. That is the status quo CON defends: platforms deciding, query by query, what outsiders may learn.
[P4.2] A published minimum cohort size applied to everyone is the opposite of a veto. And notice the question boomerangs: someone must also set the confidentiality terms for CON's regulator audits. If "who sets the rules" defeats independence, it defeats CON's alternative first, and that alternative publishes nothing.
[P4.3] A2: The same way epidemiologists establish causation without randomising who smokes: staggered rollouts of ranking changes, natural experiments when features launch in one region before another, and the results of experiments platforms already run. On consent: every recommender change is already an experiment on users who never consented, run for profit, measured in secret. The motion creates no new experiment; it lets someone outside the company read the results of experiments already happening. CON's consent objection, taken seriously, condemns the platforms' daily practice, not independent measurement of it.
[P4.4] Now the decisive point. CON's trilemma, "safe, useful, independent, pick two," applies to every proposal, including CON's own. A bounded audit with a pre-specified suspected harm is safe and independent but useless for harms nobody outside knows to suspect. A flexible regulator query is useful and independent but triggers CON's fingerprint problem exactly as an academic's would.
[P4.5] CON has already accepted that trade-off; the only variable CON is actually contesting is whether the answers reach the public.
[P4.6] That is the real clash. Both sides accept outsiders querying these logs under controls. CON wants one political actor, in secret, looking only for harms already known. The motion wants published, contestable findings from many institutions, so the next hidden teen-safety [clipped]

## Turn 8: CON Rebuttal 2

- model: muse-wonder-1.0-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Three things change: scale, incentive, and remedy. A regulator audit is one legally accountable body, querying for a defined purpose under statutory confidentiality, with serious penalties and no right to publish outputs. A researcher regime multiplies that enclave to thousands across jurisdictions whose career incentive is to publish the most granular surprising output possible — publication itself is the leakage channel. Misuse by a regulator can be investigated and enjoined; findings published by an academic cannot be recalled, and colluding queries across institutions cannot practically be policed.
[C4.2] A2: Suspicion does not require prior access to the logs. It comes from whistleblowers — PRO's own teen-harm example surfaced through a leak, not a research portal — plus user complaints, journalism, litigation discovery, and adverse-event reports platforms can be required to file with a regulator. Broad aggregate transparency can raise red flags without handing out query rights, and a low trigger suffices for a targeted audit. Researchers also need a hypothesis; blind exploration maximises privacy cost and false alarms.
[C4.3] Those answers expose why PRO's claimed symmetry collapses. We never said flexible querying is inherently safe; we said a bounded, non-public intrusion can be proportionate when justified by a specific concern. PRO must justify a standing, public-facing entitlement for general discovery. That is a different risk, and calling both “outsider access” hides it.
[C4.4] PRO's answers make the concession. A standards body setting cohort floors and noise still decides which harms are too small or specific to be seen — and unlike a census table, recommender research is iterative, so each published answer guides the next query toward disclosure. Natural experiments likewise need rollout timing, ranking features and longitudinal histories to separate algorithm from demand: either the granular access PRO promised not to need, or correlational stories dressed as causation.
[C4.5] The trilemma remains theirs: the mandate promises safe, open-ended, independent discovery; a regulator model openly trades open-endedness for safety and accountability.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 220
- clipped_words: 220
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.2], [C4.1]
- missing_claim_id_refs: (none)

[P5.1] Watch where CON ended up. Asked how anyone learns of a harm the platform studied and buried, the answer in [C4.2] was: whistleblowers. The teen-harm research "surfaced through a leak." That is offered as a defence of the status quo, and it is actually the indictment.
[P5.2] CON's model for discovering the largest behavioural harms in history is that an employee breaks her contract, copies documents, and hands them to a journalist. An accountability system whose intake valve is a felony is not a system. It is luck.
[P5.3] And notice what the privacy objection became under pressure. In [C4.1], the problem is no longer the enclave or the query; CON accepts a regulator running those. The problem is that "publication itself is the leakage channel." Strip the vocabulary and that sentence says: the danger is that the public finds out.
[P5.4] That is not a privacy argument. It is a secrecy argument wearing privacy's coat.
[P5.5] So the choice is now clean. Both sides accept controlled outside querying of these logs. CON wants one actor, in confidence, looking only for what someone already leaked. The motion wants published, contestable measurement by many institutions, bound by rules written before the question is asked.
[P5.6] A referee who reports only in secret, and only after someone else blew the whistle, is not a referee. Vote PRO.

## Turn 10: CON Closing

- model: muse-wonder-1.0-high
- raw_words: 202
- clipped_words: 202
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] Leaks are ugly; that does not make a standing right to interrogate everyone's behaviour the proportionate cure.
[C5.2] That is the distinction PRO never erased. A targeted audit uses these logs because a specific harm is already in view, under confidentiality, by one body that can be penalised before anything escapes. The motion reverses each safeguard: permanent access, for general discovery, by thousands of researchers whose reward is publishing the sharpest output they can defend.
[C5.3] Once that output is public, privacy-preserving stops being a control and becomes a hope. No standards body can recall a table, stop another institution repeating the query with a slight variation, or restore a small group identified by the interaction of published slices. PRO calls that secrecy because it is the only way to make bounded accountability sound like concealment. It is not.
[C5.4] It is the difference between inspecting a risk and distributing it.
[C5.5] A mandate should be judged by what it authorises on its worst ordinary day, not its best research paper. This one authorises irreversible disclosure in exchange for largely correlational discovery, while narrower audits, mandatory incident reporting, and court-checked investigations can pursue known harms without turning the population's viewing history into a permanent research commons.
