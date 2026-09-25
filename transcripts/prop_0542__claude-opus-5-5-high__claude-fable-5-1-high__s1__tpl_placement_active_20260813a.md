# Debate prop_0542__claude-opus-5-5-high__claude-fable-5-1-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0542
- proposition: Courts should allow broader use of “risk-based” pretrial detention when validated tools predict serious violent reoffending, even if it increases detention rates.
- model_pro: claude-opus-5-5-high
- model_con: claude-fable-5-1-high
- side_swap: True

## Turn 1: PRO Opening

- model: claude-opus-5-5-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every night, some people released pretrial go on to shoot, stab, or strangle someone. Courts already make predictions about who those people might be. The only question is whether they predict well or badly. Right now, too often, they predict badly: they rely on cash bail, charge labels, and a judge's gut feeling.
[P1.2] Cash bail detains the poor shoplifter and frees the wealthy abuser. Charge labels treat a misdemeanor assault as minor even when the defendant has a history of strangling the same partner, which is among the strongest warning signs of later homicide in domestic abuse cases. Gut instinct varies by judge, by mood, and by who the defendant resembles.
[P1.3] The motion replaces that with something better. Validated tools are tested against real outcomes, so we know how well they sort high-risk from low-risk defendants. That record, not the impression a defendant makes in a two-minute hearing, should inform the decision. Limiting their use to serious violent reoffending focuses detention on the harm that is irreversible.
[P1.4] A missed court date can be fixed with a warrant. A murdered witness cannot be fixed.
[P1.5] Nor is this a lawless expansion. Preventive detention on dangerousness grounds has been constitutionally accepted in American federal courts for decades, provided there is an adversarial hearing, a heavy burden on the state, and a right to counsel and appeal. Risk-based detention keeps every one of those safeguards. The tool informs the judge; it does not replace the judge.
[P1.6] Expect CON to say "bias." But an algorithm can be audited, re-weighted, and tested for disparate error rates. A judge's intuition cannot. If you care about fairness, you want the decision rule written down where it can be challenged.
[P1.7] And yes, detention rates may rise. That is the honest cost, and it is worth paying. The alternative is not freedom for everyone. It is a system that detains the wrong people for the wrong reasons while releasing the defendant everyone should have seen coming.
[P1.8] Weigh a temporary, reviewable loss of liberty against a permanent loss of life. That [clipped]

## Turn 2: CON Opening

- model: claude-fable-5-1-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.6], [P1.2]
- missing_claim_id_refs: (none)

[C1.1] Strip away the framing and the motion asks one thing: should courts lock up more presumptively innocent people because a score says they might, someday, hurt someone? The motion itself admits the answer means more cages. That concession is where this debate should be decided.
[C1.2] Start with arithmetic PRO never mentions. Serious violent rearrest during the pretrial period is rare, on the order of a few percent of released defendants. When the thing you are predicting is rare, even a genuinely good tool produces far more false alarms than hits. A defendant labeled "high risk" by the leading tools typically has something like a one-in-ten chance of a violent rearrest.
[C1.3] Flip that around: broader detention on that basis jails roughly nine people who would have harmed no one to stop one who might. "Validated" does not mean accurate about you. It means accurate about a population, which is exactly what the presumption of innocence forbids courts to substitute for the individual in the dock.
[C1.4] Second, what these tools are validated against is arrest, not violence. Arrest tracks where police patrol and whom they stop. A tool that learns from that record does not predict danger; it predicts contact with the system, then hardens it. PRO says algorithms can be audited [P1.6].
[C1.5] Audited by whom? Defense lawyers cannot cross-examine a proprietary score, and judges reliably defer to a number that lets them share the blame if something goes wrong.
[C1.6] Third, detention is not a neutral holding pattern. Even a few days in jail costs people jobs, housing, and custody of children, and it produces guilty pleas from people who would otherwise have fought and won. The evidence is fairly consistent that pretrial detention makes future offending more likely, not less. The motion manufactures the risk it claims to manage.
[C1.7] PRO's contrast with cash bail [P1.2] is a false choice. The remedy for detaining the wrong people is not detaining more people; it is supervised release, which handles the strangler case PRO describes without caging nine bystanders to reach him.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.5], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] CON's case rests on one number: a "high risk" defendant has roughly a one-in-ten chance of violent rearrest [C1.2]. Take that at face value, and look at what it proves. If the typical released defendant's risk is a few percent, the flagged group is several times more dangerous than average. We issue protective orders, deny gun permits, and hold psychiatric patients on far thinner showings.
[P2.2] One-in-ten odds of a shooting or stabbing is not a false alarm. It is a warning any responsible court should heed.
[P2.3] And CON never compares the tool to the real alternative. The nine "bystanders" [C1.3] are not walking free today. Many already sit in jail because they cannot post a few hundred dollars, while the defendant who can pay walks out regardless of danger. The motion lets courts hold people for the right reason instead of the wrong one.
[P2.4] On "population, not you": every bail decision is a population judgment. A judge who says "this charge usually means danger" is using an unwritten, untested statistic. The tool writes it down and checks it against outcomes. The individual still gets a hearing, counsel, and a judge who can override the score.
[P2.5] That is individualized justice with better information.
[P2.6] On arrest as a proxy [C1.4]: that critique bites for drug and low-level offenses, where patrol patterns drive the numbers. It bites far less for shootings, stabbings, and strangulations, where a victim calls police. That is exactly why the motion is limited to serious violence.
[P2.7] On proprietary scores [C1.5]: the motion says "validated," and courts can require disclosed factors and published validation as a condition of use. CON's objection argues for doing this well, not for gut instinct.
[P2.8] Finally, supervised release [C1.7]. An ankle monitor tells you where the strangler was after he killed her. It does not stop him. CON admits detention costs the defendant a job.
[P2.9] The motion prevents costs borne by victims that no appeal can ever reverse.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9]
- cited_claim_ids: [P2.3], [P1.7], [P1.5], [P2.1], [P2.6], [C1.6]
- missing_claim_id_refs: (none)

[C2.1] PRO wants credit for two incompatible stories. In one, the tool merely reallocates detention: the nine bystanders "already sit in jail" [P2.3], so nobody new is caged. In the other, the motion honestly "increases detention rates" [P1.7]. Pick one.
[C2.2] If rates rise, then by definition the tool jails people who would otherwise be free. The reallocation argument is a dodge from the motion's own text.
[C2.3] Now the safeguards PRO leans on [P1.5]. Preventive detention survives constitutionally because the state must prove, by clear and convincing evidence, that this defendant is dangerous. A score reporting a one-in-ten chance of violent rearrest is not clear and convincing evidence that he is dangerous. It is fairly strong evidence that he probably is not.
[C2.4] So the motion faces a fork: either the standard holds, in which case the tool cannot justify "broader" detention, or the standard quietly dissolves into "the number was high enough." PRO cannot keep the safeguard and the expansion.
[C2.5] PRO's analogies confirm this. Protective orders and gun-permit denials restrict a specific activity; they do not put anyone in a cell. Psychiatric holds require imminence, last days, and come with treatment. Pretrial jail lasts months and comes with a plea offer.
[C2.6] "Several times more dangerous than average" [P2.1] is a relative statement. The presumption of innocence cares about the absolute one: nine of ten flagged people would have hurt no one.
[C2.7] The strangler is a red herring. A defendant with a documented history of strangling the same partner is already detainable under existing dangerousness law, with a hearing, today. The motion is not about him. "Broader" use means the marginal defendant with no such record, flagged because the inputs to these tools are prior arrests and system contact, the very proxy PRO conceded is polluted for low-level offenses [P2.6].
[C2.8] The outcome may be a victim's call; the inputs are patrol patterns.
[C2.9] Finally, weigh honestly. Detention increases later offending [C1.6]. A policy that jails nine harmless people and makes some of them more dangerous does not protect victims. It reschedules them.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 75
- clipped_words: 75
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.7], [C1.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: You concede that a defendant with a strangulation history is detainable today on a judge's assessment [C2.7]. What probability of serious violence would justify detention in your view, and why is a judge's untested guess at that probability more legitimate than a validated tool's?
[P3.2] Q2: Your alternative is supervised release [C1.7]. For the flagged defendant who does intend to attack, what specific mechanism stops the attack before it happens, rather than recording it afterward?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 94
- clipped_words: 94
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.5], [C1.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say preventive detention is lawful only because the state proves dangerousness by clear and convincing evidence [P1.5]. Does a validated score giving roughly a one-in-ten chance of violent rearrest meet that standard, yes or no? If no, what evidence beyond the score detains the marginal defendant that "broader" use adds?
[C3.2] Q2: You never disputed that pretrial detention itself increases later offending [C1.6]. If nine of every ten newly jailed people would have harmed no one, and some leave jail more dangerous, how many future victims does your policy accept to prevent one?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.7], [C2.1], [C2.3]
- missing_claim_id_refs: (none)

[P4.1] A1: No, a score alone does not meet clear and convincing evidence, and the motion never asks it to. The standard governs the facts the state must prove: prior violent convictions, the charged conduct, threats against a witness, access to weapons. The tool shows how strongly that proven pattern has predicted violence in the past, and the judge still decides. What "broader" use adds is eligibility.
[P4.2] In many jurisdictions, detention hearings are limited to listed felony charges, so the misdemeanor-assault defendant with an escalating record never gets a dangerousness hearing at all. He either pays or walks. CON says he is "already detainable" [C2.7], but often he is not, and that gap is the motion's target.
[P4.3] A2: Net fewer victims. The research showing detention increases reoffending comes mostly from low-risk defendants held a few days on unaffordable bail, people with jobs and homes that jail destroys. Risk-based systems release exactly that group and concentrate detention on the high-risk violent tail, where there is little stable life left to disrupt and the danger is immediate. That also resolves CON's supposed dilemma [C2.1].
[P4.4] Reallocation and a modest net increase are not contradictory. Most of the change is in who is held, plus some rise at the violent end. And "nine harmless" overstates things, because rearrest undercounts violence. Domestic abuse victims often never call.
[P4.5] Here is why PRO still wins. CON's case needs you to treat a one-in-ten chance of shooting, stabbing, or strangling someone as "probably not dangerous" [C2.3]. No parent would accept those odds for the person living next door to their child. CON's remedy for that risk is still supervised release, and CON has never named a mechanism that stops an attack rather than timestamps it.
[P4.6] The choice is between two kinds of error. CON's errors are months of wrongful detention, which are reviewable, appealable, and can be corrected at trial. PRO's errors are prevented deaths that never make headlines. When one mistake can be corrected and the other buries someone, courts should be allowed to guard against the one [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1], [P4.3], [P4.4], [P4.6]
- missing_claim_id_refs: (none)

[C4.1] A1: There is no magic number, and that is the point. Preventive detention was never legitimated by a probability threshold. It was legitimated by proof of specific facts about this defendant: threats to this witness, a weapon, prior violence against this victim. PRO now concedes exactly this: "a score alone does not meet clear and convincing evidence" and the proven facts do the work [P4.1].
[C4.2] Good. Then the tool adds nothing to accuracy. What "broader" adds, in PRO's own word, is "eligibility": more categories of defendants pulled into hearings where a number sits beside their name. A judge's finding can be cross-examined and appealed.
[C4.3] A score can only be recited. The judge is not more legitimate because he guesses better; he is more legitimate because he must answer to the person in front of him.
[C4.4] A2: Firearm surrender, no-contact orders, GPS exclusion zones with real-time victim alerts, and, for the strangler with a record, detention under law that already exists. Now hold PRO to the same question. Jail stops nothing; it postpones. The flagged defendant who "intends to attack" is released when his case ends, jobless and angrier.
[C4.5] And because serious violence is rare, most pretrial violence comes from defendants the tool scores low. PRO's mechanism misses the majority of attacks and cages nine bystanders for each one it delays.
[C4.6] Notice what PRO said to escape the reoffending evidence: the high-risk tail has "little stable life left to disrupt" [P4.3]. That is the motion's honest voice. Nine of those ten people would have harmed no one, and PRO's answer is that their lives are already not worth much.
[C4.7] PRO also cannot claim rearrest "undercounts violence" [P4.4] while calling the tool validated. It is validated against rearrest. If rearrest is wrong, so is the validation.
[C4.8] Finally, "reviewable" [P4.6]. A guilty plea taken from a jail cell to go home is not reviewed at trial; it is the trial. Detention does not delay justice for the innocent. It converts them.

## Turn 9: PRO Closing

- model: claude-opus-5-5-high
- raw_words: 210
- clipped_words: 210
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.4], [P4.2]
- missing_claim_id_refs: (none)

[P5.1] CON's final answer to the defendant who intends to attack was a list: firearm surrender, no-contact orders, GPS alerts [C4.4]. Every one of those works only if the defendant chooses to obey. The man with an escalating record against the same partner has already shown he does not. A no-contact order is a piece of paper; a GPS alert tells her he is coming.
[P5.2] That is the whole debate. For the dangerous few, CON offers conditions that depend on their cooperation, and only detention does not.
[P5.3] CON says jail merely "postpones" [C4.4]. But the pretrial window is when the danger peaks: the victim has just reported, the witness is about to testify, the case is live. Getting her safely to trial, where guilt is decided with full process, is not postponement. It is the entire purpose.
[P5.4] And CON conceded the gap. The misdemeanor-assault defendant with a violent pattern often never gets a dangerousness hearing today [P4.2]. The motion gives him one, with counsel, proven facts, and a judge who can override the score.
[P5.5] The strongest mechanisms CON has left still fail against defendants who won't comply. When the risk is a shooting, a stabbing, or a strangling, courts should be allowed to prevent it, not merely record it. Vote PRO.

## Turn 10: CON Closing

- model: claude-fable-5-1-high
- raw_words: 223
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.1], [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C5.1] Every example PRO ends on is a man with a documented, escalating record against the same partner who "has already shown he does not" comply [P5.1]. Notice what detains him: proven facts. His non-compliance is history, not a prediction. PRO admitted a score alone does not meet clear and convincing evidence [P4.1], so the strangler is held, if he is held, on evidence a judge weighs and a lawyer can cross-examine.
[C5.2] The tool is a bystander to that decision.
[C5.3] Then ask what "broader" detention actually adds. PRO's answer was eligibility [P4.1]. But a misdemeanor hearing gap is fixed by changing which charges trigger a hearing; no algorithm is required for that. The only people the motion newly reaches are those the facts do not condemn: no threats, no weapon, no prior violence, just a number beside a name.
[C5.4] That is the marginal defendant, nine of ten of whom would harm no one, and PRO's answer was that they have "little stable life left to disrupt" [P4.3].
[C5.5] That is the fork PRO never escaped. Where the facts are strong, the tool is redundant. Where the facts are weak, the score is the only thing filling the cell, and PRO agrees it cannot lawfully do so. A motion that is either unnecessary or unconstitutional cannot be worth the extra cages it openly [clipped]
