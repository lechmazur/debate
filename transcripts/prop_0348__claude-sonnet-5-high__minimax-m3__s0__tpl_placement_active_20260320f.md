# Debate prop_0348__claude-sonnet-5-high__minimax-m3__s0__tpl_placement_active_20260320f

- topic_id: prop_0348
- proposition: Health systems should let patients use approved AI symptom-checking and triage tools as a front door to routine care rather than discourage them.
- model_pro: claude-sonnet-5-high
- model_con: minimax-m3
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The question is not whether AI symptom-checkers are perfect. It is whether patients are better served by a health system that channels them through an approved front door, or one that leaves them to Google their chest pain at 2 a.m. and guess. Once you frame it that way, the case for PRO writes itself.
[P1.2] Start with the baseline patients actually use today. Nobody facing a strange rash or a persistent cough sits quietly until an appointment opens up. They search the internet, ask a friend, or simply wait and hope. Unregulated search engines and forums are the real competitor to a triage app, not some idealized world where every patient has instant access to a thoughtful physician.
[P1.3] An approved triage tool, built on clinical protocols and updated with real outcome data, is a strict upgrade over that baseline. It asks structured questions, flags red flags like chest pain radiating to the arm, and routes people to the right level of care instead of a random subreddit.
[P1.4] Second, capacity is not infinite, and misallocation is the actual crisis in most health systems. Emergency rooms are clogged with low-acuity visits while urgent cases wait. Primary care panels are full months out. A triage layer that sorts the sprained ankle from the stroke, and sends each to the right venue, is not a gimmick, it is basic queueing theory applied to medicine.
[P1.5] Used at scale, it frees clinician time for what only clinicians can do.
[P1.6] Third, discouraging these tools does not make risk disappear, it just relocates it to the least accountable channel. If regulators approve a tool, subject it to safety monitoring, and integrate it into the referral pathway, that risk is visible, measurable, and correctable. Telling patients "don't use this" pushes them back into invisible, unmonitored self-diagnosis where nothing gets fixed because nothing gets tracked.
[P1.7] The comparison that should decide this debate is not "AI triage versus a perfect doctor." It is "AI triage versus what patients do when you take it away." On that comparison, PRO wins clearly.

## Turn 2: CON Opening

- model: minimax-m3
- raw_words: 398
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition asks health systems to install algorithmic triage as the literal front door to care. I want to argue that even when a tool is "approved," making it the entry point does not just rearrange the existing system. It introduces specific, predictable categories of harm that we would be choosing systematically.
[C1.2] First, the word "approved" in this motion is doing heavy lifting it cannot bear. Regulatory clearance for clinical software is typically narrow and product-class based, not the kind of prospective evidence we demand for a new drug or device. A clearance stamp is not proof that a tool performs reliably across the full diversity of patients, languages, and presentations that will actually reach it. The motion's own language quietly assumes a degree of validation that does not yet exist for this category of product.
[C1.3] Second, AI triage systems are at their best on common presentations of common conditions. They are at their worst precisely where triage is most consequential, on rare conditions, atypical presentations, multimorbid patients, and cases that do not fit the training distribution. A front door that systematically misroutes these patients toward self-care is more dangerous than the messy human-staffed doors it replaces, because the algorithmic door delivers false confidence where honest uncertainty is the correct clinical answer.
[C1.4] Third, the displacement story is misleading. The real alternative to a front-door AI is not "Google at 2 a.m." It is the nurse advice line, the urgent care clinic, the community pharmacist, the GP receptionist who asks one more clarifying question. These handles are imperfect, but they can escalate ambiguity in real time, across languages and literacy levels.
[C1.5] Replacing them with an algorithmic gatekeeper creates a new digital equity gap that maps directly onto existing health inequalities, and it does so at the most consequential point in the system.
[C1.6] Finally, accountability gets diffused. When an approved tool sends a chest pain home and the patient deteriorates, liability is fragmented between vendor, regulator, and a downstream clinician who never saw the patient. Discouraging the tool concentrates harm in [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] CON's case rests on comparing AI triage to an idealized human safety net that, in practice, doesn't exist at scale. Let's test each claim against that reality.
[P2.2] On [C1.2], "approval isn't rigorous enough" is an argument for tightening regulatory standards, not for discouraging patients from using approved tools. The motion specifies approved tools precisely because it assumes a regulatory floor. If CON thinks that floor is too low, the fix is a higher floor, not telling patients to go back to guessing. You cannot use "regulation might be imperfect" to justify abandoning regulated tools in favor of zero oversight.
[P2.3] On [C1.3], CON says AI is worst exactly where triage matters most: atypical and rare presentations. But good triage design handles uncertainty by escalating, not reassuring. A well-built tool that isn't confident should default to "see a clinician now," the same conservative bias we want from a nurse line. And the comparison point still stands: an overworked receptionist or a worried patient self-diagnosing is not more reliable on atypical presentations than a protocol-driven tool with red-flag logic.
[P2.4] CON hasn't shown human default channels beat AI on the hard cases, only asserted it.
[P2.5] On [C1.4] and [C1.5], nurse lines and pharmacists are exactly the kind of scarce, unevenly distributed resource that creates the equity gap CON worries about. Wait times on nurse advice lines, language barriers at the GP desk, transport barriers to urgent care, these are the actual current inequities. A multilingual, always-available triage tool sitting in front of that system doesn't erase human handles, it reduces the number of people who never reach them at all because they gave up or waited.
[P2.6] On [C1.6], accountability isn't diffused by an approved tool, it's diffused by the status quo, where a symptom goes unaddressed with literally no one responsible. An approved tool creates a logged, auditable decision trail. That's traceable. Silence is not.

## Turn 4: CON Rebuttal 1

- model: minimax-m3
- raw_words: 377
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] The "raise the floor" response to my approval objection is an admission dressed as a rebuttal. PRO effectively concedes that current approval standards may not be rigorous enough to license a front-door deployment. That concession is fatal. The motion asks us to install these tools as gatekeepers now, not after an unspecified future regulatory upgrade.
[C2.2] Asking health systems to run a front door on validation we have not actually performed is not caution. It is the kind of premature deployment that produces the very scandals and rollbacks that discredit genuinely useful tools for a generation.
[C2.3] On uncertainty handling, PRO says a well-built tool "should default to see a clinician now" when it is unsure. That is wishful thinking, not triage. A tool that escalates ambiguity to a clinician is just a slower, friction-laden path to the same bottleneck. The empirical record on this product class contradicts the assumption of conservative self-knowledge: confidently wrong advice on rare conditions, demographic skew in failure rates, hallucinated recommendations.
[C2.4] "Flagging what the tool doesn't know" is a design aspiration, not a measured property of deployed products. PRO is describing the tool they wish existed, not the one the motion asks us to install.
[C2.5] On equity, calling a tool "multilingual and always available" is not the same as showing it reduces known disparities. The patients least served by human systems are often the patients least likely to have reliable broadband, devices, or the digital literacy to confidently interact with a chatbot. And documented performance gaps across demographics mean the tool risks encoding, at the most consequential entry point, exactly the inequities PRO claims it dissolves. A tool that fails more often on the populations already poorly served is a regression, not a remedy.
[C2.6] On accountability, an auditable trail is not accountability. A log of what a tool decided does not establish who bears clinical responsibility when that decision harms a patient. Vendors disclaim, downstream clinicians never met the patient, regulators approved on narrow criteria. PRO is comparing a messy status quo, where named humans carry [clipped]

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 74
- clipped_words: 74
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: CON, you say approval standards are too weak for "front door" use—does CON's case oppose the motion in principle, or only oppose today's specific tools, meaning CON would concede the motion once validation improves?
[P3.2] Q2: You say a logged AI decision isn't "accountability," but in today's status quo, when a patient never reaches any human channel and deteriorates at home, who is accountable then—and how is that clearer than an auditable, escalating tool?

## Turn 6: CON Pressure Questions

- model: minimax-m3
- raw_words: 81
- clipped_words: 81
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO, your case keeps leaning on the word "approved." What specific prospective evidence base — not a 510(k)-style clearance, but outcomes data — would a tool need before you'd let it gatekeep front-door care, and does any deployed symptom-checker today actually meet that bar?
[C3.2] Q2: You assert the AI front door shrinks health inequities, yet demographic performance gaps in this product class are documented. Name one jurisdiction where rolling out AI triage measurably narrowed, rather than re-encoded, a known disparity.

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 299
- clipped_words: 299
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: A defensible bar is not a randomized controlled trial before any deployment, it is what CON's own preferred channels never had either: continuous post-market surveillance, escalation-accuracy audits by presentation type, and mandatory recalibration when demographic performance gaps are detected. That is the model already used for triage protocols run by nurse lines and for clinical decision software in other domains. No single deployed symptom-checker today has a decade of outcome data, but neither did any nurse triage line before it was trusted at scale.
[P4.2] CON's implied standard would disqualify every human triage system we already rely on. The honest answer is: monitored, iterating deployment under an approval regime is the realistic bar, and it is exactly what "approved" in this motion contemplates.
[P4.3] A2: No, I cannot name a jurisdiction with a measured, controlled reduction in disparity from AI triage rollout. But CON cannot name one where discouraging these tools narrowed a disparity either. Neither side has a clean natural experiment to point to. That symmetry matters: CON's C3.2 demands proof of a counterfactual gain that the status quo has never had to produce for its own channels.
[P4.4] Nurse lines and GP receptionists were never shown to close equity gaps through controlled evidence; they were adopted because doing something monitored beats doing nothing accountable. That is the same standard the motion needs to meet, and it does.
[P4.5] Step back. CON's pressure questions assume PRO must prove a perfected tool before deployment. But the motion is comparative: approved-and-monitored triage versus unapproved silence or overloaded human bottlenecks. CON has spent two rounds demanding an evidentiary gold standard that no incumbent triage channel currently meets, while never showing that channel outperforms a monitored algorithmic front door.
[P4.6] That asymmetry is why PRO wins the framing fight, and the framing fight is this debate.

## Turn 8: CON Rebuttal 2

- model: minimax-m3
- raw_words: 322
- clipped_words: 322
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: CON opposes the motion as written, and that matters because the motion is written in the present tense. It asks health systems to install these tools as the front door now, using whatever "approved" means today, not after some unspecified future regulatory upgrade. Saying "we'll fix the evidence regime later" asks real patients to be the validation cohort at the most consequential entry point in the system. The principle-versus-today framing is a false choice; "approved tools" in this motion means tools approved under standards PRO has just admitted may be too weak for this use.
[C4.2] A2: When a patient deteriorates at home without ever reaching a clinician, that is a capacity failure, and everyone in the chain can see it: the unanswered phone, the closed panel, the long wait. When an approved tool logs "low acuity, self-care" and the patient collapses twelve hours later, that is a different failure mode. It produces false reassurance that actively suppresses the help-seeking behavior that would otherwise have occurred. The logged trail PRO celebrates is evidence that the system confidently misrouted a patient, not evidence of accountability.
[C4.3] PRO's symmetry argument assumes these two failures are comparable in type. They are not. One is a queue that everyone knows is too long; the other is a gatekeeper that told the patient the queue did not apply to them.
[C4.4] This is why CON still wins the comparison the motion forces us to make. PRO keeps reframing the choice as "monitored AI versus invisible silence." But the proposition is not "should we monitor patients." It is "should the front door be an algorithmic gatekeeper approved under today's regime."
[C4.5] On that specific question, even granting PRO's monitoring aspirations, deploying an inadequately validated tool as the system's literal entry point manufactures a failure mode—confident misrouting at scale—that the alternatives it displaces do not produce. The motion asks us to accept that failure mode as the price of admission. CON declines.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON's closing move is that an approved tool's "confident misrouting" is a categorically worse failure than an unanswered phone. That distinction collapses under its own weight. False reassurance is not a new failure mode CON has discovered, it is the oldest one in medicine. It's what happens right now when a patient searches their symptoms, decides it's probably nothing, and stays home.
[P5.2] It's what happens when an overworked receptionist says "sounds like it can wait." The status quo is saturated with confident misrouting. The only difference is that nobody logs it, nobody audits it by presentation type, and nobody is required to recalibrate when it skews against a demographic group.
[P5.3] That is the actual choice on the table: a failure mode you can see, measure, and correct, versus the same failure mode you cannot. CON never rebuts this, it just insists the invisible version is somehow more tolerable because no algorithm signed its name to it. That's not a safety argument, it's a preference for ignorance over accountability.
[P5.4] Discouraging approved triage tools doesn't prevent confident misrouting. It just makes sure no one is watching when it happens. PRO wins that comparison.

## Turn 10: CON Closing

- model: minimax-m3
- raw_words: 215
- clipped_words: 215
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6], [C5.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The decisive difference is authority, and PRO's closing collapses it.
[C5.2] PRO says an approved tool's "confident misrouting" is just the same failure as a patient Googling at 2 a.m., only now logged. That is wrong, and the distinction is exactly why this motion is dangerous.
[C5.3] When a patient self-searches and decides to stay home, no system endorsed that call. The nurse line is still there tomorrow. The pharmacist is still there. The GP receptionist is still there.
[C5.4] The patient remains the decision-maker, and the help-seeking infrastructure underneath them is untouched.
[C5.5] When an approved triage tool - wearing the system's imprimatur, sitting at the literal front door - tells a patient "low acuity, self-care," it actively intercepts care-seeking at the system's most consequential point. The patient has been told by the official channel that they do not need care. Help-seeking is suppressed, not deferred. That is a categorically different harm than an uninstrumented self-assessment, and no amount of auditing changes what it does to the patient in the moment.
[C5.6] You do not solve a confidence problem by installing a more confident gatekeeper. You solve it by reserving authority for channels that can earn it.
[C5.7] Discouraging the tool does not endorse the status quo. It refuses to launder the status quo's worst failure with a system logo.
