# Debate prop_0420__qwen4-max-high__hy4-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0420
- proposition: Replacing most first-line customer service with AI chat agents reduces costs more than it degrades trust, accountability, and resolution quality.
- model_pro: qwen4-max-high
- model_con: hy4-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Most first-line customer service is not judgment work. It is lookup work: where is my order, why was I charged twice, how do I reset this password, what is your return window. The human agent answering those questions is reading the same database the software can read. What the human adds is a queue, a hold song, and a shift schedule.
[P1.2] Judge the swap against the real baseline, not an idealized one. Today's tier one is long waits, high turnover, offshore scripts, agents who guess because they cannot find the policy, and customers who hang up before anyone answers. That is already a trust deficit, priced in labor. Trust follows competence, not species.
[P1.3] An AI agent answers in seconds, at 3 a.m., in the customer's language, with the current policy rather than last quarter's training deck. When an airline melts down and ten thousand people need rebooking, the human queue is four hours long; software rebooks them while the queue would still be forming.
[P1.4] Accountability improves, not erodes. Every exchange is logged, searchable, reviewable. A bad answer can be traced to its cause and fixed once for every future customer; a bad phone call disappears into a recording nobody audits and a coaching session six weeks later.
[P1.5] The cost side is not marginal. Human support scales linearly with volume — every new customer adds headcount, training, attrition. Software's marginal cost per conversation approaches zero, and it absorbs surges without hiring.
[P1.6] The word doing the work in this motion is "most." The hard tenth — the bereavement, the disputed fraud, the exception that needs authority — keeps a human path, and gets a better one, because agents are no longer drowning in password resets. Certain, recurring savings against bounded, escapable degradation: that is the trade.

## Turn 2: CON Opening

- model: hy4-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- missing_claim_id_refs: (none)

[C1.1] Start with the flaw in the word “lookup.” [P1.1] describes order status, duplicate charges, password resets, and return windows as if the customer arrives with a clean key. Real first-line contact turns messy facts into a case: a card charged under another name, a refund posted to the wrong account, a package marked delivered but missing, a bereavement request that begins as a cancellation. A human is not valuable merely because hands type into a database; the human can notice a discrepancy, ask one clarifying question, admit uncertainty, and own the next step.
[C1.2] The baseline of long waits and scripts [P1.2] proves only that bad human service is bad. It cannot prove a net gain from replacing most first-line service. Trust does not follow speed, policy freshness, or species; it follows recoverability: someone understands the problem, has authority to fix it, and is answerable when the fix fails. An instant answer at 3 a.m.
[C1.3] [P1.3] is not resolution if the bot applies current policy to wrong facts, refuses an exception, or loops the customer. A fast wrong answer only looks closed.
[C1.4] Nor does a transcript create accountability. [P1.4] A log proves harm happened; it does not name someone empowered to reverse it, and responsibility disperses across model, vendor, prompt, policy text, and escalation design. The near-zero marginal cost claim [P1.5] counts the cheap conversation, not repeat contacts, chargebacks, complaints, churn, compliance work, or senior agents repairing confident mistakes. Those costs are less visible, not smaller.
[C1.5] Measure the whole episode: deflection is delayed labor plus damaged trust.
[C1.6] “Most” is where the trade breaks. [P1.6] The hard tenth is not pre-labeled; it emerges in first contact, and replacing that layer removes the trained bench and context that make escalation real. A thin, late human path is a fig leaf, not a safeguard.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Take recoverability as the test; it is the right one. Now apply it honestly. Today's human first line rarely has authority to reverse anything either — they read a script, open a ticket, and escalate. The agent who "notices a discrepancy, admits uncertainty, owns the next step" is a tier-two specialist costed at tier-one volume.
[P2.2] The real comparison is two triage layers, one of which asks the clarifying question in seconds instead of after forty minutes of hold music. Nothing prevents software from asking whether the charge appeared under another name. That is a prompt, not a soul.
[P2.3] On whole-episode accounting: repeat contacts, chargebacks and churn get charged to us, while the abandoned call and the customer who never complains, just leaves after a four-hour hold, stay uncounted. Invisible costs cut both ways. If we measure episodes, measure the ones that never begin because nobody answered.
[P2.4] A log does not name someone empowered; neither does a phone call. But a log finds the one wrong policy sentence that harmed ten thousand people and fixes it once. "Responsibility disperses across vendor and prompt" describes a contract with a named counterparty you can sue. An agent who quits in month five is answerable to nobody.
[P2.5] "Most" is a volume claim, answered with vivid cases instead of a distribution. The bereavement that arrives as a cancellation is real and rare. Escalation triggers — uncertainty, dispute language, a customer simply asking for a person — are the same routing decision tier one makes now, except software can be tuned to over-escalate cheaply, while human queues ration escalation by exhaustion. And the bench is concentrated, not destroyed: humans stop resetting passwords and start doing the judgment work CON says they exist for.

## Turn 4: CON Rebuttal 1

- model: hy4-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] [P2.1] is a concession, not an answer. If first-line humans "rarely have authority," the defect is a misdesigned human layer; fix it with bounded authority and tools, not an automated gatekeeper before the person who can reinterpret the case. [P2.2] says the clarifying question is "a prompt, not a soul." Precisely: prompts work inside frames designers anticipated.
[C2.2] Asking whether a charge appeared under another name helps if that possibility was imagined; it fails when a refund went to a closed account, a dependent used the card, or an odd date signals fraud. A fast question preserving the wrong frame is faster mishandling.
[C2.3] [P2.3] is right that invisible costs cut both ways, which is why the net-saving claim collapses. The abandoned hold call is a failed queue; the abandoned bot chat is booked as containment. "Episodes that never begin" are speculative; falsely closed episodes are billed, logged, and return as repeat contacts, chargebacks, complaints, senior cleanup, or silent churn. Hidden automation costs answering hidden human costs remove the accounting certainty PRO needs.
[C2.4] [P2.4] confuses traceability with accountability. A log finds the bad policy sentence after thousands met it; useful, but an autopsy of a scaled error. "A named counterparty you can sue" helps lawyers, not the customer needing a reversal tonight. When an agent quits, the employer still owns the file and relationship.
[C2.5] Accountability is an authorized person who can say: I see what happened, I can fix it, and answer for it.
[C2.6] [P2.5] supplies the final dilemma. Over-escalating "cheaply" means paying and staffing the human bench that replacing "most" first-line service was supposed to remove; narrow triggers miss hard cases emerging inside ordinary intents. A rare category can still define the service's worst failures when no person owns the mistake. Savings require the very capacity safety requires cutting.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your remedy is giving human first-line agents bounded authority, better tools, and training. Does that version cost less than today's script-readers — and if it costs more, why is it the baseline we must beat rather than an upgrade nobody has funded?
[P3.2] Q2: You call over-escalation a dilemma. At what escalation rate do the savings actually vanish, when routine contacts dominate volume? Name a plausible share, or concede the dilemma is rhetorical rather than arithmetic.

## Turn 6: CON Pressure Questions

- model: hy4-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.4], [P1.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: If recoverability is now conceded as the test, where in [P2.4] does a customer get an authorized reversal tonight, not a "named counterparty you can sue" after one bad policy sentence has harmed thousands?
[C3.2] Q2: Before claiming "certain, recurring savings" [P1.6], what maximum share of over-escalation, repeat contacts, and standby human capacity can your whole-episode accounting absorb before the net gain disappears, instead of booking falsely closed chats as resolved?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Tonight, from a person with authority — except the queue ahead of them is gone. And most reversals require no reinterpretation: refund under the threshold, waive the fee, reverse the duplicate charge. Software executes those instantly and uniformly, while a junior night agent often must wake a supervisor. Above the limit, the case routes to an on-call human who reads the transcript rather than starting cold.
[P4.2] CON's authorized person survives; she simply stops resetting passwords.
[P4.3] A2: Approximately: a human-handled contact costs several dollars in loaded labor; a machine-handled one costs cents. That gap lets you escalate a quarter, even a third, absorb repeat contacts and standby staffing, and still cut the bill sharply. Break-even requires failure approaching most of volume. Asked for a share, CON offered none — the dilemma is rhetorical, not arithmetic.
[P4.4] Meanwhile CON's own remedy, bounded authority plus better tools plus training, makes the human layer dearer than today's script-readers. That is an upgrade, not a baseline.
[P4.5] "Falsely closed chats booked as containment" indicts a metric, not a mechanism. Count repeat contacts instead — the transcript makes that countable, which is precisely what the phone queue never was. And the scaled-error objection cuts our way: a wrong sentence in last quarter's training deck reaches thousands of customers too, only there is no autopsy, no trace, and no single fix.
[P4.6] The motion asks which effect is larger, not whether machines ever fail. CON has supplied vivid failures and no distribution, an accountability standard today's tier one already misses, and a remedy that raises costs. Savings land on the routine majority every day; degradation lands on a minority we can route, measure, and repair. That trade holds at the scale the word "most" actually describes.

## Turn 8: CON Rebuttal 2

- model: hy4-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P3.1], [P4.3], [P4.5], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: No. Bounded authority, tools, and training may cost more than script-readers, but [P3.1] mistakes the question: the motion asks whether automation's savings exceed degradation, not whether a starved tier one is cheap. A recoverable human layer is the standard for degradation. If funded, PRO's savings shrink; if unfunded, PRO compares automation to neglect.
[C4.2] A2: At roughly a quarter to a third of AI episodes needing human rescue, savings plausibly vanish once repeats, supervisor review, chargebacks, and paid standby capacity are included. [P4.3] says a quarter, even a third, can escalate and "still cut the bill sharply." That is not safety margin; it is the dilemma. Cheap escalation requires keeping the bench; cutting the bench is where "most" replacement promises savings.
[C4.3] PRO's arithmetic works only by pricing a contact, not an episode. A handoff includes bot time, repetition, reading, lost context, and often senior repair after the first answer hardened a wrong frame. [P4.5] says count repeat contacts, but that misses customers who abandon, dispute a charge, or leave silently. A chat marked resolved before recovery elsewhere is a mechanism of hidden cost, not merely a bad metric.
[C4.4] [P4.1] gives an on-call reader who arrives after containment, not as the authorized first-line owner recoverability requires. A junior agent's employer still owns the file after she quits; a transcript does not give tonight's customer someone empowered to reverse the mistake. Logs are autopsies, not authority.
[C4.5] So PRO's "more" collapses. It needs abundant humans to protect trust but scarce humans to book savings; it needs logs after harm where the customer needed authority now. Once baseline, episode, and authority are weighed consistently, cheap interactions are not a net surplus. Because PRO bears the burden of showing the surplus, that unresolved gap defeats it.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 192
- clipped_words: 192
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON finally named a number: a quarter to a third of episodes needing human rescue. Then called that number the dilemma. It isn't — it is the arithmetic of the motion. "Most" was never "all."
[P5.2] Keep a third of the bench, remove two thirds, and the wage bill falls by roughly that much while every hard case still reaches a person. That is not savings needing the capacity safety cuts; the two-thirds we remove fund the third we keep.
[P5.3] For the objection to bite, rescue would have to approach the whole volume: nearly every password reset and order-status check ending in senior repair. Nothing in CON's case establishes that distribution. The vivid cases were always the minority, and CON never denied routine contacts dominate. Charge repeats, chargebacks and standby staffing against us generously — two-thirds of contacts handled for cents still carries it.
[P5.4] The other move, judging us against a funded, empowered human layer, asks to be measured against a service that does not exist. Degradation is counted from where customers actually stand tonight: on hold.
[P5.5] Cheap where volume lives, human where judgment lives, logged where errors hid. That surplus is real.

## Turn 10: CON Closing

- model: hy4-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.3], [P5.2], [P5.4]
- missing_claim_id_refs: (none)

[C5.1] PRO’s last speech reduces the claim to “two-thirds of contacts handled for cents” [P5.3]. That is the decisive mistake. A handled contact is a cost event; trust, accountability, and resolution quality are episode facts, known only after the customer is made whole. The wage line disappears.
[C5.2] The degradation appears when a chat is closed before the dispute is understood, when a handoff arrives after the wrong frame hardens, or the customer never returns to be counted. PRO calls those minorities, but “most” replacement puts them at the seam where judgment emerges.
[C5.3] The third kept in [P5.2] cannot repair this and keep the surplus. Staff and authorize it to reverse mistakes; standby capacity absorbs the savings. Keep it thin, and the log is an autopsy, the human path late. The quarter-to-a-third rescue rate was no flourish: cheap conversations stop being net savings when repeats and repair are priced as episodes.
[C5.4] Nor can “customers actually stand tonight: on hold” [P5.4] lower the standard. Neglect is not permission to degrade trust. The proposition needs a surplus after recoverability, not a cheaper queue labeled resolved. On the same unit of account, PRO’s benefit is certain only before the customer’s problem is tested.
