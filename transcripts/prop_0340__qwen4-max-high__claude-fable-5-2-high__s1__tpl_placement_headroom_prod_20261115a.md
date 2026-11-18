# Debate prop_0340__qwen4-max-high__claude-fable-5-2-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0340
- proposition: Large social platforms should give users far more control over recommendation goals rather than optimize one feed for everyone.
- model_pro: qwen4-max-high
- model_con: claude-fable-5-2-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every feed optimizes something. The question is never whether a recommendation system has a goal, but whose goal it is. Today one objective — keep the average user scrolling — is imposed on hundreds of millions of people whose purposes are nothing alike. That is not neutrality.
[P1.2] It is a single answer to a question that has millions of correct answers.
[P1.3] Consider the new parent who wants practical sleep advice and gets pulled into culture-war video, because outrage holds the median user better than help does. Or someone recovering from an eating disorder who wants a feed that never ranks body content at all. They can mute words one at a time; they cannot state their purpose. The architecture has no slot for it.
[P1.4] Far more control means naming what the system should be trying to do for you — not hiding one more keyword.
[P1.5] This is not speculative engineering. Platforms already hand advertisers a menu of objectives — reach, clicks, conversions — and tune ranking precisely to whichever is chosen. The machinery for goal-directed ranking exists and is sold daily. Users are simply never offered the same dial.
[P1.6] The standard defence is that engagement already reveals what people want. That reasoning is circular: you design a system to extract a behaviour, then cite the behaviour as consent. And control is additive — keep the current default for anyone who wants it. Nobody is forced to configure anything; the people who do are the ones currently worst served.
[P1.7] Notice the asymmetry of error. A goal I choose and regret, I can change. A goal chosen for me is invisible, unappealable, and defended as math. Give users the dial, and the feed becomes an instrument they play rather than one played on them.

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 317
- clipped_words: 317
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: [P1.6], [P1.5], [P1.7]
- missing_claim_id_refs: (none)

[C1.1] PRO's own parent and patient show why this fails. Their problem is a bad default, and the motion's answer is to hand them a settings menu and wish them luck.
[C1.2] Start with who actually turns the dial. Wherever platforms have offered feed controls, such as chronological toggles and "not interested" buttons, only a small minority ever touch them. The exhausted new parent is not configuring objective functions at three in the morning. PRO calls control "additive" [P1.6], but that concedes the debate: if the default stays, nearly everyone stays in it.
[C1.3] What changes is the blame. Once a dial exists, every harm has a ready answer: you chose your settings. User control ends up working as a liability shield for the platform.
[C1.4] The dial also promises something the machine cannot deliver. Advertisers get goal-directed ranking [P1.5] because their goals have measurable endpoints: a click, a purchase. "Give me sleep advice that actually helps" has no conversion event. The system would still infer success from what you watch and linger on, which is the same behavioural signal PRO calls circular.
[C1.5] The label on the dial changes while the engine underneath stays the same.
[C1.6] Then ask who uses the dial most eagerly. The person in recovery may pick "no body content." The person in relapse picks the opposite, and now the platform is serving it by explicit request. The conspiracy enthusiast selects "more of what the mainstream hides."
[C1.7] PRO says a regretted choice can be changed [P1.7], but that assumes harm falls only on the chooser. Feeds shape what spreads, who is harassed and what a public believes. Those people get no dial.
[C1.8] One shared objective has an underrated virtue: it can be seen, audited, regulated and fought over. Millions of personal objectives cannot. If engagement-maximisation is the disease, change what the default optimises and hold the platform answerable for it. Don't privatise the problem and call it freedom.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] “Only a small minority touch the dial” — they touch a dial that does nothing. Chronological is not a goal; it is the absence of ranking. “Not interested” is exactly the keyword-muting I called inadequate. Low uptake of a placebo is not evidence against medicine. Ask someone whether they want a feed that stops after twenty minutes, or never ranks body content, and you are measuring something else entirely.
[P2.2] Then CON's remedy: change what the default optimises. Toward what? Whatever is chosen, it remains one answer for the parent wanting sleep advice and the person in recovery wanting nothing about bodies. CON concedes my premise — the objective matters enormously — then insists it be set once, centrally, by the same company.
[P2.3] That is not accountability. That is a single point of capture, and the people worst served stay worst served.
[P2.4] On measurement: engagement does not measure “help” either — that was my objection. Goals need direction, not a conversion event: fewer rage-bait items, more from accounts I follow, nothing about weight, stop at twenty minutes. These are ranking constraints platforms already compute. And “this isn't what I asked for” is a signal the engagement engine never collects.
[P2.5] On the person in relapse: today the system pushes that content unprompted, and CON's reformed default must still guess who is vulnerable. A stated goal creates a specification — something to default away from, add friction to, and check. Which answers auditability: you cannot test whether a feed honours “no body content” until a user is permitted to say it. One opaque objective is not more auditable; it is merely the one nobody has to justify.
[P2.6] The liability shield worry cuts the other way: a platform that must honour a declared goal has something it can be caught failing.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P1.4], [P2.4], [P2.1], [P2.5], [P2.3], [P2.2], [C1.7]
- missing_claim_id_refs: (none)

[C2.1] Look at what PRO's dial has shrunk into. The opening promised "naming what the system should be trying to do for you" [P1.4]. The rebuttal's examples are "fewer rage-bait items, more from accounts I follow, nothing about weight, stop at twenty minutes" [P2.4]. That is a topic filter, a follow list and a timer.
[C2.2] It is the keyword-muting PRO dismissed, with better engineering. So PRO faces a dilemma. If the dial means filters and limits, it is a modest safety feature that sits happily inside one accountable objective. If it means stating a purpose such as "help me," PRO has conceded there is no way to measure it.
[C2.3] The placebo defence [P2.1] is also speculation. Break reminders and time limits already exist on major apps, and people routinely swipe them away. What users say they want and what they do at midnight diverge. That gap is why defaults decide outcomes.
[C2.4] On relapse, PRO says a harmful stated goal becomes something to "default away from, add friction to" [P2.5]. In other words, the platform overrides the user. Someone must still decide centrally which goals are honoured and which are refused. The "single point of capture" [P2.3] never left; PRO has only added a menu in front of it.
[C2.5] "Toward what?" [P2.2] confuses one objective with one feed. A single standard, such as ranking by what people later say was worth their time, still gives the parent sleep advice and the recovering patient something different. Personalisation survives.
[C2.6] What changes is that one target can be published, tested and regulated for everyone, including the majority who never open settings.
[C2.7] That majority is where this is decided. PRO's world leaves the engagement default intact for them, now carrying the alibi of choice. And my point that feeds harm people who hold no dial, such as harassment targets and the misinformed public [C1.7], went unanswered. Changing the default reaches all of them, while a dial reaches only the few who configure it.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5], [C2.3], [C2.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your preferred objective ranks by "what people later say was worth their time" [C2.5] — yet you dismiss stated preferences because "what users say they want and what they do at midnight diverge" [C2.3]. Why is self-report trustworthy when the platform collects it, but disqualifying when the user volunteers it?
[P3.2] Q2: Where does the motion require keeping engagement as the default for that majority [C2.7]? If a better default and user-set goals can coexist, what exactly are you opposing?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5], [P2.3], [P2.4], [C1.7]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say a harmful stated goal becomes something to "default away from, add friction to" [P2.5]. Who decides which user goals get refused? If it is the platform, how is that not the same "single point of capture" [P2.3] you condemn?
[C3.2] Q2: Your concrete examples are a topic filter, a follow list and a timer [P2.4]. Name one user-chosen goal beyond those that the system can measure without falling back on behavioural signals, and explain how it protects harassment targets who hold no dial [C1.7].

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [P3.1], [P3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: The platform, still — but over a fence, not the whole field. Today it silently decides every ranking for everyone. Under the motion it publishes a short list of goals it will not honour, and everything else is the user's. A refusal is a visible, contestable act; a weight buried in an engagement model is neither.
[P4.2] CON's single objective is the same capture, minus the appeal.
[P4.3] A2: "Rank my feed by what the people I trust chose to share." I pick the curators — a doctor, a union, a teachers' group — and success is measured by provenance, not by how long I linger. That is an objective function, not a keyword mute, and no behavioural signal is required. Harassment targets are protected because amplification is a ranking decision: dogpiles spread because outrage holds attention.
[P4.4] Goals that stop rewarding outrage shrink that engine, and a floor banning amplification of content targeting private individuals applies to every goal, including the default.
[P4.5] Notice what went unanswered. I asked why self-report is trustworthy when the platform surveys it but disqualifying when the user volunteers it [P3.1]. No answer — and their whole metric depends on it. I asked what they oppose if a better default and user goals coexist [P3.2].
[P4.6] No answer, because there is nothing. "Change the default" is my position plus a refusal.
[P4.7] And their midnight objection argues for stronger commitment, not less choice: a goal set at noon exists precisely to bind the self at midnight. Swiping away a reminder is a weak device, not a false preference.
[P4.8] The majority who never configure anything get CON's improved default in my world too. The difference is the parent and the patient, who finally get to say what the machine is for — and can catch it failing.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 330
- clipped_words: 330
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P1.6], [C2.2], [P4.1], [P4.4], [P4.8], [P4.3], [P4.7]
- missing_claim_id_refs: (none)

[C4.1] A1: Because the two self-reports differ in kind, whoever collects them. A dial setting is a forecast about my future self, made once, by the minority who open settings. "Was that worth your time?" is a verdict on something actually experienced, sampled across everyone, including people who never configure anything, and scored against one published standard outsiders can test. I trust hindsight over forecast, and full coverage over volunteers.
[C4.2] A2: The motion's own words are "rather than." It makes individual dials the remedy in place of a shared, answerable objective, and PRO's opening said to "keep the current default" [P1.6]. That trade is what I oppose. Filters and timers inside one accountable objective I accepted in [C2.2], but they are not "far more control over recommendation goals."
[C4.3] Now look at where PRO's protections actually come from. For the person in relapse, it is a platform-published refusal list [P4.1]. For harassment targets, it is "a floor" that "applies to every goal, including the default" [P4.4]. For the majority, it is "CON's improved default" [P4.8].
[C4.4] In all three, the work is done by a central rule set for everyone. That is my case carrying PRO's label.
[C4.5] So what does the dial itself add? PRO's one new goal is "what the people I trust chose to share" [P4.3]. That is a follow list with reshares, the very item my question excluded. It also cuts both ways.
[C4.6] The careful user picks a doctor; the conspiracy enthusiast picks his own curators and receives a sealed feed by explicit request. Provenance measures loyalty, not help.
[C4.7] Even the noon-binds-midnight defence [P4.7] gives the game away. A commitment that truly binds means the platform overrides what the user wants in the moment, which is central authority again.
[C4.8] Weigh what remains. Every protection in PRO's world is a default or a floor. The dial's own contribution is a curated list for the few and an alibi for the platform. The better fix is the objective everyone actually lives under.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] A floor says what the feed must never do. It cannot say what the feed is for. That is the gap, and every protection CON claimed — refusal lists, anti-dogpile rules, a better default — sits on the floor's side of it. None of them tells the machine to stop at twenty minutes, or to rank by my curators rather than my lingering.
[P5.2] CON's standard — what people later say was worth their time — proves the point. Those verdicts differ in kind, not degree. The patient's answer is "never show me bodies at all." That is not a low score on a shared scale of worth; it is a veto no average can express.
[P5.3] Aggregate a million verdicts into one published target and her veto disappears into the mean — the same arithmetic that buried the parent under outrage.
[P5.4] And "rather than" does not mean "without floors." It means: not one feed for everyone. CON accepted filters and limits inside a shared objective, then defined the motion down to them.
[P5.5] The dial is not an alibi. It is the only place a person can state a purpose — and the only place the platform can be caught ignoring one.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 205
- clipped_words: 205
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P5.1], [P4.8], [P5.3], [C2.5], [C2.2]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing asks what the feed is for, and then answers with a timer and a list of curators [P5.1]. After five speeches, that is all the dial amounts to. Everything else that protects anyone in PRO's world comes from somewhere else. The refusal list guards the person in relapse.
[C5.2] The floor shields harassment targets. For the majority there is what PRO called "CON's improved default" [P4.8].
[C5.3] So ask where the fix actually lives. It lives in the objective everyone is under, including the people who never open settings and the people who hold no dial at all.
[C5.4] The "veto disappears into the mean" line [P5.3] mistakes one standard for one average. Under a worth-your-time objective, the patient's verdict on body content shapes her own feed, as in [C2.5]. Her hard filter sits comfortably inside that objective, and I accepted it in [C2.2]. Nothing of hers is lost.
[C5.5] What the motion adds beyond that is "purpose", which PRO never showed a machine could measure. It also adds a platform able to say of any harm, "you chose your settings."
[C5.6] Fix the objective everyone lives under and you reach the exhausted parent who never configures anything. A dial reaches only those who needed the least help.
