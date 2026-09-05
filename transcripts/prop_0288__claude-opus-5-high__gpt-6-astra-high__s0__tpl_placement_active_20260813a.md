# Debate prop_0288__claude-opus-5-high__gpt-6-astra-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0288
- proposition: Public agencies should never suspend benefits, visas, or fraud claims solely because an AI risk model flags a person as suspicious without meaningful human review.
- model_pro: claude-opus-5-high
- model_con: gpt-6-astra-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-high
- raw_words: 351
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A risk score is a guess about a population. Suspension is a punishment inflicted on a person. The motion asks whether the state may skip the step where somebody actually looks at the person before the punishment lands. The answer is no, and we already know what happens when the answer is yes.
[P1.2] The Netherlands ran an automated risk system over childcare benefit claims. Thousands of families — disproportionately those with immigrant backgrounds or dual nationality — were labelled fraudsters, had payments halted, and were ordered to repay sums they never owed. Some lost homes. Some lost custody of children.
[P1.3] The government eventually fell over it. Australia's Robodebt scheme did the same trick with income averaging: an algorithmic mismatch became a debt notice, and the burden of disproving the machine fell on people least equipped to carry it. Michigan's unemployment fraud system produced false accusations at a rate that would embarrass a coin flip. None of these were exotic technical failures.
[P1.4] They were the predictable result of removing the human who says: this doesn't look right.
[P1.5] Notice the structure of the harm. When a model flags a wealthy contractor, lawyers appear. When it flags a single mother on housing support or a visa applicant abroad, the suspension arrives first, the appeal takes eight months, and by then the eviction has happened. Statistical error at the population level becomes catastrophe at the individual level, and it lands hardest on the people the model was already worst at understanding.
[P1.6] Three things human review supplies that no score can. Reasons — you cannot contest a correlation you are never told about. Exceptions — models cannot see the sick relative, the clerical typo, the changed address. Accountability — a named official can be appealed to, sued, and fired; a threshold cannot.
[P1.7] The rule is modest. Use the model. Rank the queue. Route the caseworker.
[P1.8] Just do not let the number pull the trigger. CON must defend the trigger-pulling itself: that a probability estimate, unexamined, is enough to take away someone's income or their lawful [clipped]

## Turn 2: CON Opening

- model: gpt-6-astra-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] “Never” makes this proposition indefensible. It treats a brief protective suspension exactly like an indefinite deprivation, and insists that human review must always precede action, even when delay creates the greater danger. The defensible rule is proportionality: an automated flag can justify a narrowly bounded pause, not a final verdict.
[C1.2] Imagine a benefits agency minutes from a payment run. Its risk model flags an apparent coordinated takeover of recipients’ accounts. Nobody has yet examined those individual cases. Continuing payment could send beneficiaries’ money to thieves; reviewing every flagged account first may be impossible before disbursement.
[C1.3] A short automatic suspension can protect the very people PRO says must always be protected from it. That is genuinely withholding a benefit payment—not merely ranking a queue.
[C1.4] This exception requires strict limits. The model must be validated for that specific risk; the suspension must expire unless a reviewer justifies continuing it; the agency must provide notice, an urgent hardship channel, and prompt human reconsideration. The state retains the burden of establishing wrongdoing. These safeguards do not disguise prior individual review: the initial suspension happens solely because of the model’s flag.
[C1.5] They make that temporary authority bounded and contestable rather than unlimited.
[C1.6] PRO’s examples concern severe wrongful accusations, repayment demands, and devastating deprivation. Even accepting that account, those failures establish the danger of treating automated suspicion as proof—not that every automatic pause is unjustifiable. An appeal arriving after eviction is plainly inadequate. It does not follow that a tightly time-limited interruption before a potentially fraudulent transfer is equally unacceptable.
[C1.7] Human review also consumes time and scarce investigative capacity. Requiring it before every suspension can turn a sudden surge into a choice between hurried rubber-stamping and letting suspicious payments proceed. Accountability should attach to officials who authorize thresholds, deadlines, and remedies, not depend exclusively on someone clicking approval first. PRO must defend its ban even where a bounded automatic pause prevents greater harm.
[C1.8] It cannot.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-high
- raw_words: 337
- clipped_words: 337
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.2], [C1.4], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] Look closely at CON's one example, because the whole case rests on it. An "apparent coordinated takeover of recipients' accounts" [C1.2] is not a case where a model flags *a person as suspicious*. The beneficiary there is the victim. Nobody is accusing her of anything, nobody is questioning her entitlement, and nothing is being taken from her — the agency is stopping money from going to a thief who has captured her account details.
[P2.2] That is a payment-channel hold, and the entitlement survives it intact. The motion addresses suspending someone *because the model flags that person*. CON has answered a different motion.
[P2.3] Then read CON's own safeguards [C1.4]: the pause "must expire unless a reviewer justifies continuing it," plus notice, hardship channel, and "prompt human reconsideration." That is meaningful human review. The motion does not demand review at a particular clock position; it demands that a human actually looks before the deprivation stands. If a person is guaranteed reasons and a real human decision within hours, and default is restoration, CON has conceded the principle and is haggling over minutes.
[P2.4] If that guarantee is absent, CON is defending the thing that actually happened in the Hague and in Canberra.
[P2.5] Because notice what "temporary" meant in practice. Robodebt notices were provisional too — the debt was merely *asserted*, pending your evidence. The Dutch halts were pending investigation. The exception CON wants is not an alternative to those disasters; it is the exact legal form they took.
[P2.6] "Bounded pause" is what every one of these systems called itself on the way in.
[P2.7] And CON's capacity argument [C1.7] destroys its own remedy. An agency too stretched to review before suspending is precisely an agency too stretched to unwind afterwards. Reviewer scarcity does not make automatic suspension safer; it makes the expiry date theoretical.
[P2.8] Meanwhile the motion covers visas and fraud accusations, where no payment-run clock exists at all. CON has offered nothing there.
[P2.9] One narrow banking scenario, misdescribed, cannot buy the general power to let a score pull the trigger.

## Turn 4: CON Rebuttal 1

- model: gpt-6-astra-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO cannot say “do not let the number pull the trigger,” then allow it to pull the trigger provided a human checks hours later. My exception is precisely an initial suspension based solely on a model flag, followed by meaningful review. If PRO permits that, it abandons “never.” If it prohibits that, the timing dispute remains decisive: later review cannot retroactively become review before suspension.
[C2.2] On the example, make the disputed element explicit. Before the same payment run, a model flags named claimants as likely using stolen identities to obtain benefits. The agency temporarily suspends their payments. It does not merely redirect money, and no official has examined those individuals.
[C2.3] That falls squarely within the motion. The flag might be wrong; but immediately paying potentially fraudulent claims also risks losses. PRO must explain why even a strictly bounded pause is impermissible, rather than redefine every protective suspension as something else.
[C2.4] The distinction from PRO’s disasters is not the word “temporary.” It is what happens when the deadline arrives. “Suspended pending investigation” can leave someone waiting indefinitely. Automatic restoration unless an official affirmatively authorizes continuation cannot lawfully do that. Whatever earlier systems called themselves, provisional accusations and claimant burdens are not equivalent to an enforced expiry with the burden remaining on the state.
[C2.5] That also answers reviewer scarcity. Limited capacity before an imminent payment does not prove equal scarcity throughout the following review window. And if capacity remains insufficient, the suspension expires. The agency loses its authority to withhold; the claimant does not inherit its backlog.
[C2.6] A short interruption can still hurt, which is why proportionality and urgent hardship relief matter—not why every interruption must be forbidden.
[C2.7] Finally, I need not establish automatic suspension is appropriate for every visa or fraud case. PRO chose a universal prohibition. One justified, genuinely person-directed suspension defeats that prohibition without licensing indefinite deprivation. The choice is bounded emergency authority or no exception at all.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-high
- raw_words: 123
- clipped_words: 123
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: At the moment of your automatic suspension, what is the flagged claimant actually told — the reasons for the flag, or just that payment has stopped? And if the model's false-positive rate resembles Michigan's, is the "bounded pause" still proportionate when most of the people you've cut off are innocent?
[P3.2] Q2: You concede you need not defend visas or fraud cases [C2.7], but the motion is a rule for agencies. If a validated model plus an expiry clock licenses suspension before anyone looks, what principled limit stops that same reasoning being applied to visa holds and fraud accusations, where no payment-run deadline creates urgency at all — and if you cannot name one, hasn't the emergency exception simply become the ordinary practice?

## Turn 6: CON Pressure Questions

- model: gpt-6-astra-high
- raw_words: 66
- clipped_words: 66
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say review “within hours” can satisfy the motion [P2.3]. May an agency withhold a flagged claimant’s payment solely on the model’s suspicion before any human examines that case, yes or no?
[C3.2] Q2: If no reviewer is available before imminent disbursement, does your rule require paying claims flagged for identity theft even when a brief, automatically expiring suspension—with urgent hardship relief—would cause less overall harm?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-high
- raw_words: 351
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: No — not solely, and never in a way where the model is the whole reason the deprivation stands. That is what "solely" means in the motion. A guaranteed human decision, arriving with reasons and default restoration, means the flag was a routing device, not the ground of the punishment. CON wants judges to freeze the frame at minute zero and call that the whole decision.
[P4.2] But a deprivation is not an instant; it is a duration. If the human review is real, guaranteed, and the entitlement survives until someone looks, the machine did not pull the trigger — it rang a bell. If the review is not guaranteed, then yes, my rule forbids it, and CON is defending Robodebt with a nicer name.
[P4.3] A2: No. Notice what CON's hypothetical smuggles in: "no reviewer available" is not weather, it is a staffing decision. An agency that builds a model capable of flagging thousands at disbursement, and no capacity to look at any of them, has chosen to automate accusation and not adjudication. And the honest fix is to hold the *run*, verify the *identity*, or pay into a verified channel — not to cut a named woman's rent money on a probability. The asymmetry decides it: a wrongly paid claim is recoverable through the ordinary law of debt; a wrongly stopped payment produces an eviction that no expiry clock reverses.
[P4.4] That is the whole debate. CON has built one engineered minute where nobody can possibly look, and asks for a general power in exchange for it. But rules for public agencies are not judged by their best minute; they are judged by what agencies do with them at scale, under budget pressure, against the least-lawyered people on their books. Every safeguard CON lists — expiry, notice, hardship relief, state burden — is exactly what the Hague and Canberra promised on paper and abandoned in practice, because a threshold cannot be shamed and a clock cannot be appealed to.
[P4.5] Keep the human in the loop, and the model becomes a [clipped]

## Turn 8: CON Rebuttal 2

- model: gpt-6-astra-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The claimant must receive an intelligible explanation of the indicators behind the flag, the suspension’s expiry, and access to urgent human help—not merely “the computer says no.” A model unable to supply that explanation does not qualify. And no: if most flags are false positives, a timer alone does not make withholding proportionate. Our exception requires demonstrated reliability for this particular risk and a defensible comparison of harms.
[C4.2] A2: The principled limit is necessity: an imminent disbursement risk that cannot await review, no equally protective and less harmful alternative, and a tightly bounded interruption with automatic restoration. Without urgency, that justification disappears. So it does not authorize routine visa holds or fraud accusations. Authority to interrupt one imminent payment is not authority to declare someone fraudulent or suspend their status indefinitely.
[C4.3] PRO’s latest answer nevertheless permits a deprivation followed by guaranteed review, then calls the flag a “routing device.” But routing does not stop payment; our suspension does. Keeping someone legally entitled does not mean their benefit has not been suspended. A human decision tomorrow may justify continued withholding; it cannot change what solely caused withholding today. Either PRO permits that interval and accepts our exception, or its prohibition remains absolute.
[C4.4] Its proposed alternatives expose the cost of that absolute rule. Holding the entire payment run delays innocent recipients whose claims were never flagged. Verifying identity takes time—the very interval at issue. Paying through a verified channel does not establish that a claimant using stolen identity is entitled.
[C4.5] And fraudulent payments are not reliably recoverable just because debt law exists.
[C4.6] Better staffing reduces emergencies; it does not eliminate them. PRO cannot assume its mandatory review rule will work while dismissing mandatory restoration as fiction. The relevant choice is not perfect humans versus reckless automation. It is whether a necessary, bounded pause can sometimes prevent more harm than immediate payment.
[C4.7] PRO has not justified forbidding it in every case.

## Turn 9: PRO Closing

- model: claude-opus-5-high
- raw_words: 202
- clipped_words: 202
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.1]
- missing_claim_id_refs: (none)

[P5.1] Decide it on this: CON's exception cannot exist in the world CON needs it for.
[P5.2] Look at what CON now requires [C4.1]: a model demonstrated reliable for that specific risk, an intelligible explanation of the indicators to the claimant, urgent human hardship help, automatic restoration, the state's burden intact. Every one of those is a capacity commitment. An agency that can hand a flagged woman a real explanation and a live human on the phone within the hour is an agency that could have had someone glance at her file. And the agency that genuinely cannot spare a reviewer at minute zero — CON's whole scenario — is the same agency that will not deliver the explanation, will not answer the hardship line, and will let the clock quietly slip.
[P5.3] Scarcity does not politely confine itself to the moment before disbursement.
[P5.4] So the exception is safe exactly where it is unnecessary, and necessary exactly where it is not safe. That is not a proportionality rule; it is a promise written in the same ink as Robodebt's.
[P5.5] The motion asks whether a probability may stand alone as the reason someone's rent stops. Never is the right answer, because "sometimes" has always meant "routinely."

## Turn 10: CON Closing

- model: gpt-6-astra-high
- raw_words: 204
- clipped_words: 204
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s final argument confuses capacity to review with capacity to review everyone before an imminent payment. That distinction decides whether “never” protects people or prevents a necessary protective pause.
[C5.2] A model’s reliability can be assessed beforehand. Notice and automatic expiry do not require individual adjudication. Urgent human help for hardship cases does not require enough reviewers to examine every flagged file simultaneously. And having someone “glance at her file” is not the meaningful review PRO demands.
[C5.3] These safeguards can therefore exist even when universal prior review cannot.
[C5.4] Nor does a backlog have to become prolonged deprivation. Under our exception, insufficient review means restoration—not an extension while the claimant proves innocence. PRO cannot treat mandatory human review as enforceable while dismissing mandatory restoration as inherently fictional. Both require institutions to obey rules; only one accommodates the urgent interval.
[C5.5] The decisive comparison remains a necessary, narrowly bounded suspension versus an immediate payment that may be unrecoverable. Where the pause creates greater harm, our justification fails. Where less harmful alternatives exist, it fails. But where it prevents greater harm and expires without affirmative human authorization, an absolute prohibition makes the worse outcome compulsory.
[C5.6] That is why “never” loses: it forbids the justified exception along with the abuse.
