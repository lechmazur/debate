# Debate prop_0621__muse-wonder-1.0-high__claude-fable-5-2-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0621
- proposition: Prosecutors should be required to disclose the source code, training data summaries, and error rates of any algorithmic risk tool used in charging, bail, or sentencing.
- model_pro: muse-wonder-1.0-high
- model_con: claude-fable-5-2-high
- side_swap: True

## Turn 1: PRO Opening

- model: muse-wonder-1.0-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a prosecutor urges a judge to deny bail, file a heavier charge, or seek a longer sentence because an algorithm labeled someone high risk, that score is evidence. The defendant whose liberty turns on it cannot cross-examine a number, cannot ask why prior arrests counted more than employment, and cannot discover whether the tool systematically over-predicts danger for people like him. Requiring disclosure of the source code, training-data summaries, and error rates restores the basic rule that the state must show its work before it takes liberty away.
[P1.2] That transparency is the only way to catch built-in error before it becomes a jail cell. Risk tools learn from past arrests, convictions, and supervision records — data that reflect where police were deployed and whom they stopped, not simply who is dangerous. A training-data summary lets the defense see whether the model was built on a different city, a different decade, or a skewed population. The source code shows whether race is excluded in name while zip code, family criminal history, or neighborhood do the same work in practice.
[P1.3] Error rates show the cost: how often low-risk people are flagged, and whether false positives fall harder on one group than another. Without those three pieces, bias is not rebutted; it is hidden.
[P1.4] Prosecutors choose whether to invoke the tool, and they can choose a vendor willing to be inspected — under protective order if needed to prevent gaming or copying. If a company insists profit requires secret evidence in criminal court, the answer is not to lower constitutional standards to fit the contract; it is to not use that tool to jail people.
[P1.5] Judges need this record to judge rather than defer. A score without its error rate invites false precision; with it, the court can weigh, discount, or reject it. Disclosure does not ban tools — it demands the same reliability showing required of breathalyzers and forensic experts.

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: [P1.4]
- missing_claim_id_refs: (none)

[C1.1] The question is not whether defendants deserve to test the evidence against them. They do. The question is whether this mandate, which puts source code from any tool at every stage on the prosecutor, delivers that. It does not, for three reasons.
[C1.2] First, it targets the wrong actor. Most bail and sentencing risk assessments are run by pretrial services agencies, probation departments, or the courts themselves, not by prosecutors. A prosecutor cannot disclose code she has never possessed and has no legal right to obtain. The duty would fall on the one party in the courtroom least able to perform it, which produces litigation over compliance rather than insight into reliability.
[C1.3] Second, it demands the wrong thing. Source code is not where bias lives. Many widely used pretrial tools are simple point scales whose factors and weights are already published. The best-known exposure of racial disparity in a risk tool came from journalists comparing scores against real outcomes, without ever seeing a line of code.
[C1.4] Bias is found by validating the tool on local outcomes and by checking the inputs fed in for this particular defendant. A defense lawyer handed thousands of lines of code learns less than one handed the factor weights and a local validation study. PRO's own remedy, disclosure "under protective order" [P1.4], concedes that blanket disclosure is not the real standard.
[C1.5] Third, and decisively, it backfires. The mandate attaches only when a tool is used. A prosecutor's unaided hunch triggers nothing. It has no code, no error rate, and no audit trail.
[C1.6] Charging decisions in particular are discretionary and unreviewable. If the structured, testable method carries heavy burdens and gut instinct carries none, offices will choose gut instinct. PRO admits as much in [P1.4]: the answer is "to not use that tool." That would not expose bias.
[C1.7] It would move bias back into a human head that nobody can subpoena.
[C1.8] The better rule is independent validation, published factors and weights, disclosure of each defendant's inputs, and court-ordered deeper access on a showing of need. That gives [clipped]

## Turn 3: PRO Rebuttal 1

- model: muse-wonder-1.0-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The agreement that defendants must test the evidence against them decides who bears this burden. A prosecutor who asks a court to rely on a risk score cannot blame pretrial services, probation, or a vendor for keeping it secret. The burden follows use. Prosecutors do not themselves run DNA tests or calibrate breathalyzers either; they disclose the underlying material because they ask the state to act on it.
[P2.2] If they cannot obtain the code, training summary, and error rates, they may decline to invoke the score. They cannot invoke it and shield it at once.
[P2.3] Source code is also not a distraction. For a simple points scale, disclosure is easy because the logic fits on a page. For a complex model, published weights are not enough: code shows how missing data are filled in, where thresholds are set, how variables are transformed, and whether the deployed model matches the marketed one. Outcome testing does not replace this — it produces error rates, one of the disclosures required here.
[P2.4] And an aggregate disparity finding does not tell an individual defendant what population trained the tool or why its failure applies to him. He needs all three pieces to make that argument.
[P2.5] A protective order is not a retreat from disclosure. Discovery routinely handles sensitive material by limiting copying or gaming while still giving defense and court access. What the motion forbids is secrecy from the person whose liberty is at stake.
[P2.6] The backfire argument assumes a secret algorithm beats human judgment because it leaves a paper trail. A trail no one may inspect is not accountability; it is a hunch wearing a scientific label, and judges defer to scores as they do not to hunches. If a tool cannot survive inspection, not using it does not conceal bias — it removes false legitimacy. Offices that value tools will demand vendors able to meet the burden of criminal court.
[P2.7] The “showing of need” alternative is circular: a defendant cannot show the code matters without first seeing training data and error rates.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 373
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.7], [P2.1], [P2.2], [P2.6], [P2.3]
- missing_claim_id_refs: (none)

[C2.1] Look at how narrow the real dispute has become. My rule already supplies local validation, which means error rates, plus published factors, weights, and each defendant's own inputs. That disposes of [P2.7]: nothing is circular when the defendant starts with the validation results and needs a showing only for the code itself. So the only thing the motion adds is this: source code, in every case, for any tool, demanded from the prosecutor.
[C2.2] That increment is what PRO must defend, and it fails.
[C2.3] Start with the analogy in [P2.1]. A prosecutor introduces DNA and breathalyzer results at trial to prove guilt, and if she withdraws them, they vanish. A bail or sentencing risk score is different. Pretrial services or probation typically generates it and hands it to the judge whether the prosecutor mentions it or not.
[C2.4] PRO says she may "decline to invoke the score" [P2.2]. Suppose she does. The score is still sitting on the bench, the judge still reads it, and the mandate has disclosed nothing. A duty that the prosecutor can escape by staying silent, while the judge goes on using the tool, offers defendants no protection.
[C2.5] Charging is worse. There is no hearing at which a charging decision is tested, so nothing is ever "invoked." The mandate there can only do one thing, which is make offices stop using structured tools.
[C2.6] PRO has now accepted that outcome twice. [P2.6] says not using the tool "removes false legitimacy." But the bail decision does not go away when the tool does. Someone still decides, and they decide by instinct, with no factors, no weights, no error rate, and nothing to cross-examine.
[C2.7] PRO defends this by comparing a hunch to a "secret algorithm." That is not the alternative I offered. The comparison is between a validated, published, contestable tool and a hunch, and the motion pushes offices toward the hunch.
[C2.8] Finally, [P2.3] concedes that for simple scales the logic "fits on a page," so code adds nothing. For complex models, questions about missing-data handling and thresholds are exactly what [clipped]

## Turn 5: PRO Pressure Questions

- model: muse-wonder-1.0-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If the code merely confirms the published factors and weights, why is disclosing it burdensome, and if it instead reveals different thresholds, imputation rules, or proxies, why isn't that precisely what the defendant needs?
[P3.2] Q2: When the prosecutor stays silent while the judge still relies on a probation-generated score, who under your alternative bears the duty to disclose, and how does the defendant make the required showing of need for code he has never seen?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 103
- clipped_words: 103
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.4], [P2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: When pretrial services hands a score directly to the judge and the prosecutor says nothing about it, what exactly does your prosecutor-based mandate force anyone to disclose, and if the answer is nothing, how does it protect that defendant?
[C3.2] Q2: You say twice that if a tool cannot meet the mandate, the answer is to stop using it [P1.4], [P2.6]. When that happens, the bail or charging decision is made by unaided human judgment with no factors, weights, or error rate. Is that defendant better off than under a validated tool with published weights and disclosed inputs, and what does he cross-examine?

## Turn 7: PRO Rebuttal 2

- model: muse-wonder-1.0-high
- raw_words: 362
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: It forces the prosecutor, as the State's advocate in that hearing, to obtain and disclose the material from the State agency that generated it, or to stop benefiting from the score. Pretrial services is not a stranger to the prosecution; it is another arm of the same government seeking detention or punishment. Silence is not non-use when the prosecutor seeks detention, offers no objection, and lets the judge rely on a score she knows is untested. If she truly disavows it, she can say so on the record and ask that it be disregarded — then it has not been used against the defendant.
[P4.2] A2: Yes, when the alternative is a tool whose maker refuses inspection. That defendant can demand reasons from a human decision-maker, challenge the facts and assumptions stated, and ask the judge to weigh a bare recommendation for what it is. He cannot do any of that with a secret score dressed as science.
[P4.3] But this is also a false forced choice: the motion does not ban the validated, published tool CON describes. It adds code and training summaries to it. Vendors that can validate can disclose under protective order; only vendors that will not be checked are driven out.
[P4.4] Those answers expose the real divide. CON's system leaves the decisive increment hidden and then calls the hiding harmless. Local validation tells you a tool failed at some rate overall; it does not tell you whether it was trained on arrestees from another jurisdiction, how it imputes missing employment or housing data, or where it converts a continuous score into “high risk.” Those are code and training-data questions, and they determine whether the validation even applies to this defendant.
[P4.5] CON also treats prosecutorial silence and judicial reliance as a reason to impose no duty, when that is the strongest reason to impose one on the only State lawyer in the room. Otherwise the government could route every score through probation and defeat disclosure by design. A validated tool that survives disclosure beats both secrecy and intuition. [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 360
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1], [P4.5], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: The dilemma is false on both horns. Where code merely confirms published weights, the burden is not the reading. It is the mandate: expert review, protective-order litigation, and compliance fights in every case, including bail hearings held within days of arrest, all for no new information. Where the deployed tool differs from the published one, the defendant can catch that without the code.
[C4.2] He has the weights and his own inputs. If his score does not reproduce, that mismatch is the proof. Cut-points and missing-data rules are specifications that can be published like weights.
[C4.3] A2: The agency that runs the tool and the court that adopts it bear the duty, because they hold the material. The showing of need requires no access to code: a score that will not reproduce, a validation that shows poor performance for defendants like him, or no local validation at all. Any of those opens the code by court order.
[C4.4] Now compare PRO's answers. Asked what the mandate forces when the prosecutor is silent, [P4.1] says she must "obtain" the material from pretrial services, or "disavow" the score on the record. In many jurisdictions pretrial services answers to the court, not the prosecution, so she has no power to compel it. And a disavowal does not un-read a number the judge is holding.
[C4.5] PRO fears the government could "route every score through probation" [P4.5]. That is how scores already travel, and it is why a prosecutor-based duty misses them. My rule puts the duty on whoever holds the tool.
[C4.6] On the backfire, [P4.2] says yes, the defendant is better off with unaided judgment, but only "when the alternative is a tool whose maker refuses inspection." That is not my alternative, so PRO never answered the comparison that matters. PRO says he can "demand reasons from a human decision-maker." At charging no reasons are owed and there is no hearing.
[C4.7] The mandate discloses nothing there. It only makes the structured tool costlier than the hunch.
[C4.8] What remains is an increment that adds nothing where tools [clipped]

## Turn 9: PRO Closing

- model: muse-wonder-1.0-high
- raw_words: 186
- clipped_words: 186
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The choice is not whether risk tools are useful. It is whether the State may use one to take liberty while keeping the reason it works — or fails — beyond challenge.
[P5.2] That is why disclosure must attach to use, through the prosecutor who seeks detention, a heavier charge, or a longer sentence. Calling the score probation's product does not change who benefits from it or who the defendant faces. If the State will not produce the code, training summary, and error rates, it need not use the score. What it cannot do is invoke science and plead secrecy in the same breath.
[P5.3] The alternative leaves the defendant to prove he needs the code before he may see it, even though the code decides what the published weights conceal: thresholds, substitutions for missing data, and whether the model was trained on people like him. Local validation alone cannot answer those questions, and an unaided hunch, stated openly, at least receives no false authority from a number a judge cannot interrogate.
[P5.4] A vendor that will disclose survives. A score that cannot be tested should not jail anyone.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 226
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P5.2], [P5.3]
- missing_claim_id_refs: (none)

[C5.1] Three times PRO has told you what happens when this mandate bites: the State "need not use the score" [P5.2]. Take that at its word and ask what the defendant is left with.
[C5.2] At bail, he is left with a judge deciding within days on instinct. At charging, he is left with a prosecutor who owes no reasons to anyone. PRO calls this "an unaided hunch, stated openly" [P5.3], but nobody states a charging hunch openly. There is no hearing and no record, and nothing to cross-examine.
[C5.3] The bias PRO fears from arrest data is the same bias in the human's head, minus the factors, weights and error rate that would let anyone catch it.
[C5.4] That is the trade the motion makes. It takes the one decision method a defendant can actually test and makes it costlier than the one he cannot. And it does this through a prosecutor who often neither holds the tool nor controls the agency that does.
[C5.5] PRO's case rests on the secret score that sends someone to jail. My rule ends that secrecy too: published weights and cut-points, local validation, the defendant's own inputs, and the code by court order when the score will not reproduce. It gets the defendant that scrutiny without pushing offices back to the hunch.
[C5.6] A rule that pushes offices back [clipped]
