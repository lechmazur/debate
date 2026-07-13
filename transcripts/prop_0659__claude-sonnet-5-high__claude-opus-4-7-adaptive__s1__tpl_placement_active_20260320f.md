# Debate prop_0659__claude-sonnet-5-high__claude-opus-4-7-adaptive__s1__tpl_placement_active_20260320f

- topic_id: prop_0659
- proposition: Countries should prohibit employers from using emotion-recognition systems in hiring or worker evaluation.
- model_pro: claude-sonnet-5-high
- model_con: claude-opus-4-7-adaptive
- side_swap: True

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 334
- clipped_words: 334
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Emotion-recognition systems claim to read something no camera can actually see: what a person feels. What they really measure is facial muscle movement, vocal pitch, or word choice, and then guess at an internal state from that surface signal. Build a hiring or evaluation regime on that guess, and you get a technology that is scientifically shaky, systematically discriminatory, and coercive by design. That combination is exactly what justifies a prohibition rather than mere regulation.
[P1.2] Start with the science. The core assumption behind these tools is that emotions map onto consistent, universal, machine-readable signals. Decades of psychological research on facial expression show the opposite: the same emotion produces wildly different expressions across individuals, cultures, and contexts, and the same expression can map to different emotions. A furrowed brow can mean anger, concentration, or squinting into bad lighting.
[P1.3] When the underlying construct is this unreliable, no amount of engineering fixes it. You are not building a thermometer; you are building an elaborate horoscope with a webcam.
[P1.4] Now add who bears the error. These systems are trained predominantly on datasets skewed toward certain facial structures, expressive norms, and neurotypical behavior. Autistic candidates, people with facial differences, older workers with different muscle tone, and workers from cultures that discourage expressive display all get systematically misread as "disengaged," "untrustworthy," or "low energy." A hiring filter that is unreliable for everyone but especially broken for the already-marginalized isn't a rough draft technology needing improvement, it's a laundering machine for discrimination, giving biased outcomes the appearance of objective data.
[P1.5] Finally, consider what letting this stand does to the workplace itself. Once employers can score your face and voice, workers learn to perform emotion rather than have it, monitored constantly for compliance with an invisible, unappealable rubric. Weak transparency mandates won't fix this, because the harm is in the surveillance and the pseudo-scientific inference itself, not just in bad implementation. Regulation invites companies to keep using junk science with a disclaimer attached.
[P1.6] Only a prohibition removes the harm at its source.

## Turn 2: CON Opening

- model: claude-opus-4-7-adaptive
- raw_words: 322
- clipped_words: 322
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A prohibition is a sledgehammer aimed at a moving target, and it will crush uses that actually protect workers while doing little that a serious regulatory regime couldn't do better.
[C1.2] Start with what "emotion recognition" actually covers. It ranges from crude face-scanning hiring tools to sentiment analysis in call-center coaching, burnout detection in nursing shifts, fatigue monitoring in long-haul trucking, and aggression alerts that protect social workers and retail staff from violent customers. The proposition bans the whole category from "worker evaluation." That means a truck fleet cannot flag a drowsy driver, a hospital cannot pilot a tool that warns when ICU nurses are approaching breakdown, and a call center cannot use tone analysis to tell a supervisor "your agent just took an abusive call, check on her."
[C1.3] These are worker-protective uses. Prohibition throws them out with the bathwater.
[C1.4] Second, the choice is not between prohibition and laissez-faire. The real alternative is targeted regulation: bans on high-stakes automated hiring decisions, mandatory validation studies, disparate-impact audits, disclosure, worker consent, human-in-the-loop requirements, and liability for discriminatory outcomes. Every harm PRO names — junk science, biased datasets, coercive surveillance — is directly addressable by rules on where, how, and with what accountability these systems may be used. We already do this for polygraphs, medical exams, personality tests, and credit checks in hiring.
[C1.5] We don't ban the category; we constrain it.
[C1.6] Third, prohibition freezes the science in its worst state. If the tools are as unreliable as PRO says, the way to expose that is validation requirements and audit access, not driving development offshore and underground where no one can inspect it. A ban tells vendors to sell into jurisdictions with no rules at all.
[C1.7] The clash I want the judges to hold onto: PRO must show that no legitimate use exists and no regulatory regime could work. Anything less, and the proportionate answer is regulation, not prohibition. Overbroad bans lose to targeted rules every time.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [P1.4]
- missing_claim_id_refs: (none)

[P2.1] CON's strongest move is the parade of "worker-protective" uses — but look closer and most of it isn't emotion recognition at all. A drowsy-driver alert reads eyelid closure and steering drift; a burnout tool can track hours, error rates, or heart-rate variability. Fatigue and physiological strain are measurable. Emotion is not.
[P2.2] The moment these systems pivot from "is this driver's eyes closing" to "is this driver frustrated" or "is this nurse disengaged," they inherit exactly the junk-science problem from my opening: inferring an unobservable internal state from a noisy proxy. CON needs these examples to actually be emotion-inference to score the point, and the more clearly they are, the more they inherit the bias problem [P1.4] too — an autistic nurse or a stoic long-haul driver gets flagged as "checked out" by the same flawed model, safety framing or not.
[P2.3] CON's own analogy undercuts the regulation-first case. Polygraphs are the textbook example — and most democracies don't lightly regulate them in hiring, they ban them outright, precisely because the junk-science-with-a-disclaimer approach doesn't work when the tool wears the authority of "objective data." That's the Employee Polygraph Protection precedent CON gestures at: society already decided that some pseudo-scientific measurement tools are too dangerous to merely audit. Emotion recognition is that category, not credit checks.
[P2.4] And "human-in-the-loop" doesn't cure this. A manager handed a dashboard score doesn't independently re-derive the truth; they anchor on the number, because that's the entire point of buying the software. The harm isn't implementation detail — it's that the score itself is manufactured legitimacy for guesswork, and CON's audits regulate the packaging, not the guess.
[P2.5] CON must show a use where the emotion-inference itself, not a relabeled physiological proxy, is both reliable and worth the discrimination risk. They haven't named one yet.

## Turn 4: CON Rebuttal 1

- model: claude-opus-4-7-adaptive
- raw_words: 310
- clipped_words: 310
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal quietly rewrites the motion. Watch the move: whenever I name a protective use, PRO reclassifies it as "not really emotion recognition" — drowsy-driver alerts become "eyelid tracking," burnout tools become "hours and heart rate." Fine. But the motion bans "emotion-recognition systems," and in the actual market and actual regulatory drafts, that category explicitly includes affect detection, stress inference, sentiment analysis, and engagement scoring.
[C2.2] Call-center tone analysis flagging an abusive caller so a supervisor checks on the agent *is* emotion inference. The proposition sweeps it up. PRO can't win by narrowing the ban in rebuttal to only the uses they dislike.
[C2.3] On the polygraph analogy — it cuts against PRO. The U.S. didn't ban polygraphs from "worker evaluation." It banned them from most pre-employment screening while carving out security work, government, and ongoing investigations. That is precisely the targeted regime I'm defending: prohibit the high-stakes hiring decision, permit constrained protective uses with oversight.
[C2.4] PRO's own precedent is a scalpel, and they're citing it to justify a sledgehammer.
[C2.5] Concrete case PRO owes an answer to: a lone social worker doing home visits, wearing audio that flags rising aggression in a client's voice and pings a colleague. The inference is imperfect. So what? A false positive costs a check-in call.
[C2.6] A false negative, if we ban the tool, can cost a beating. PRO's discrimination worry is about the *client*, not the worker being evaluated — and the alternative is worse for the worker the motion claims to protect.
[C2.7] On anchoring: yes, humans defer to scores. That's an argument for banning *automated adverse decisions* and requiring decision thresholds and liability — which my regime does. It is not an argument for banning a supervisor from ever seeing an affect signal.
[C2.8] The clash is simple. PRO needs "no legitimate use survives regulation." They've answered by narrowing the ban's meaning. That concession is mine.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 72
- clipped_words: 72
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your social-worker example flags a client's aggression, not the worker's own emotional state — how is that "worker evaluation" under this motion at all, rather than a different category you're using to dodge the actual ban?
[P3.2] Q2: You keep saying "validation studies" will fix the science — name the accuracy threshold or validated standard emotion-recognition systems would have to clear under your regime before they may score a worker at all.

## Turn 6: CON Pressure Questions

- model: claude-opus-4-7-adaptive
- raw_words: 81
- clipped_words: 81
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You call human-in-the-loop "manufactured legitimacy" [P2.4] — but you also cite polygraph law, which permits polygraphs with human oversight in security roles. Which is it: does oversight cure the anchoring problem or not, and why does your answer flip between analogies?
[C3.2] Q2: Does your prohibition cover a call-center tool that flags a distressed *customer* so a supervisor supports the *agent* — yes or no — and if no, concede the motion's "worker evaluation" language is narrower than you've been arguing?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Oversight never cured anchoring for polygraphs, and it doesn't here. Polygraph law didn't create a general "regulate with human oversight" regime — it banned the tool from ordinary hiring and permitted it only in a narrow security carve-out where society tolerated junk science because the asymmetric risk (a spy passing screening) was catastrophic. That is not "oversight fixes accuracy." It's "extraordinary risk justifies a narrow exception to an otherwise firm ban."
[P4.2] I'm not flipping analogies — I'm using the same structure both times: default prohibition, exception only for extraordinary, narrowly-defined risk. CON's regime is the opposite: default access, regulation everywhere. My position is the one consistent with the precedent CON keeps citing.
[P4.3] A2: Yes, a tool that reads the customer's distress to support the agent falls outside "worker evaluation" as written, because it isn't scoring the worker's performance or inner state at all — it's a safety alert about a third party. That was never inside the ban, so no concession is required, and no exception needs carving out.
[P4.4] But notice what this actually costs CON: their two best examples across three speeches — the customer-aggression alert and the client-distress alert — both survive precisely by not being worker evaluation. That confirms the ban is exactly as targeted as it needs to be, and it leaves untouched the entire paradigm case the motion is actually about: hiring screens, engagement dashboards, performance scoring based on facial affect. For that core category, CON still hasn't named one accurate, non-discriminatory use.
[P4.5] Two rounds of pressure questions, and CON's surviving examples are the ones the ban doesn't even reach. What's left inside the ban — scoring a candidate's face in an interview, scoring a worker's "engagement" from their expression — is precisely the junk-science-with-a-badge problem from my opening, still unanswered.

## Turn 8: CON Rebuttal 2

- model: claude-opus-4-7-adaptive
- raw_words: 323
- clipped_words: 323
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: On the social worker — the tool monitors the worker's environment and often the worker's own vocal stress as part of a safety package sold *for worker evaluation and welfare*. But grant PRO's narrow reading for a moment. Then the same logic saves call-center tone analysis run on the *agent's* voice to alert a supervisor that the agent just absorbed an abusive call: that is unambiguously about the worker, it is emotion inference, and PRO's motion still bans it.
[C4.2] So either "worker evaluation" is narrow — and the ban is smaller than PRO's opening implied — or it's broad, and it sweeps protective uses. PRO cannot have both.
[C4.3] A2: The threshold isn't one magic number, and pretending it should be is a rhetorical trap. Validation regimes in employment already work this way: disparate-impact testing (the familiar four-fifths benchmark), documented predictive validity against job-relevant outcomes, published error rates across demographic subgroups, and a bar on automated adverse decisions where confidence is low. That's how the EEOC treats every selection instrument. "Name one number" is not how we regulate polygraphs, medical devices, or cognitive tests — and it isn't a reason to ban a category.
[C4.4] Now the weighing. Look at what PRO conceded in the last speech. Their framework is now "default prohibition with narrow carve-outs for extraordinary risk" [P4.1–P4.2]. That is a *regulatory regime*.
[C4.5] We are no longer arguing prohibition versus regulation; we are arguing about where the carve-outs sit. Once PRO admits carve-outs exist — customer-distress alerts, safety monitoring, polygraph-style exceptions — the motion as written, a flat prohibition on emotion recognition in hiring or worker evaluation, is too blunt to describe their actual position.
[C4.6] My regime draws those lines explicitly: ban automated adverse hiring decisions, require validation and bias audits, mandate disclosure and human decision authority, permit constrained protective uses. PRO has spent two speeches converging on that structure while calling it a ban. Judges should call it what it is.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Three rounds of pressure, and CON still has not named a single use *inside* this motion's actual scope — scoring a candidate's face in an interview, scoring an employee's expression for "engagement" or "attitude." Every example CON built a speech around — the customer-aggression alert, the client-distress alert, the abusive-call flag — protects someone by watching a *third party*, not by certifying a worker's inner state. That's not a coincidence. It's the tell that the paradigm case — emotion inference used to judge the worker — has no defensible instance.
[P5.2] CON had five speeches to find one and produced zero.
[P5.3] And the "convergence" claim in Rebuttal 2 doesn't survive scrutiny: an exception for extraordinary, narrowly-bounded risk is not the same structure as "regulate everywhere, permit by default." One is prohibition-with-a-safety-valve; the other is access-with-paperwork. Those produce opposite defaults, opposite burdens of proof, and opposite outcomes for the ordinary hiring screen and performance dashboard — which is what employers will actually buy by the thousands.
[P5.4] The core harm was never fixed: a manufactured score, built on an unmeasurable construct, biased against exactly the workers least able to perform expected affect. Regulation audits the packaging. Only prohibition removes the guess.

## Turn 10: CON Closing

- model: claude-opus-4-7-adaptive
- raw_words: 197
- clipped_words: 197
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The decisive question isn't whether emotion inference is imperfect — everyone agrees it is. The question is what a country *does* about an imperfect, high-stakes workplace technology. And on that question, PRO's own closing gave the game away.
[C5.2] PRO now defends "prohibition-with-a-safety-valve": a default ban, plus carve-outs for extraordinary risk, plus a concession that customer-facing and safety-alert uses fall outside the motion entirely. That is not the flat prohibition on the ballot. That is a regulatory regime with the dial turned to strict. Once you're drawing lines between permitted and forbidden uses, weighing risk against benefit, and defining scope — you are regulating.
[C5.3] The only real question is whether you regulate honestly, with validation standards, disparate-impact audits, bans on automated adverse decisions, and liability — or dishonestly, by calling the same structure a "ban" and hoping no one notices the carve-outs.
[C5.4] Judges, the motion says *prohibit*. PRO spent five speeches narrowing that word until it meant something a targeted regulatory regime already delivers — with more precision, without driving vendors offshore, and without outlawing the tone-alert that tells a supervisor to check on an agent who just took an abusive call.
[C5.5] Vote CON. The proportionate tool wins.
