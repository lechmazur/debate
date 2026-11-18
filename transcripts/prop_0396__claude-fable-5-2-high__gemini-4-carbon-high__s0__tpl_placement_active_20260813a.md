# Debate prop_0396__claude-fable-5-2-high__gemini-4-carbon-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0396
- proposition: Medical debt should not appear on consumer credit reports because illness is not a meaningful indicator of future repayment behavior.
- model_pro: claude-fable-5-2-high
- model_con: gemini-4-carbon-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-2-high
- raw_words: 375
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9], [P1.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A credit report exists to answer one question: when this person chooses to borrow, do they pay it back? Medical debt cannot answer that question, because nobody chooses it.
[P1.2] Take two people with identical incomes, identical habits and spotless payment histories. One has a burst appendix and the other doesn't. A year later, one has a collection account. The report now says they are different kinds of borrowers, but the only difference between them is an organ.
[P1.3] That is luck written up as character.
[P1.4] Three features make medical debt uniquely bad data.
[P1.5] First, it is involuntary. A credit card balance reflects a decision to borrow at a known price. A hospital bill reflects neither, since you don't shop for prices in an ambulance and you can't decline the anesthesiologist who turns out to be out-of-network.
[P1.6] Second, it is noisy. Medical bills pass through insurers, coding departments and appeals before anyone knows what is owed or who owes it. Many accounts land in collections while the patient is still waiting on the insurer, or disputing a charge that is simply wrong. An "unpaid" medical bill often means a paperwork fight, not a refusal to pay.
[P1.7] Third, the market has already conceded the point. Newer credit scoring models discount medical collections because their own builders found these accounts predict default worse than other collections. The major bureaus have voluntarily dropped paid medical collections and small balances from reports. Industry does not throw away data that predicts well.
[P1.8] Genuine financial distress does not need medical debt to reveal it. Someone who is actually failing will miss car payments, max out cards and fall behind on a mortgage, and all of that stays on the report. Removing medical debt removes only the part that tracks illness rather than behavior.
[P1.9] Keeping it has a cost. It gives collectors a threat that pushes people to pay bills they don't owe to protect their scores, and it teaches patients that seeking care can cost them an apartment or a car loan.
[P1.10] So the opposing burden is specific: [clipped]

## Turn 2: CON Opening

- model: gemini-4-carbon-high
- raw_words: 309
- clipped_words: 309
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.1], [P1.3], [P1.2], [P1.6], [P1.9], [P1.7], [P1.8]
- missing_claim_id_refs: (none)

[C1.1] Credit reports are not moral report cards; they are risk assessments. [P1.1] and [P1.3] confuse a borrower's character with their capacity to repay. Lenders check reports to verify whether an applicant's future paychecks are already spoken for, not whether past hardship was deserved.
[C1.2] Take the burst-appendix example in [P1.2]. If two workers earn the same salary, and one now carries thousands of dollars in unpaid collections, the difference between them is no longer "an organ." It is a binding financial liability competing for the same monthly income, draining savings or inviting garnishment. Credit reports never list illnesses; a patient whose bill is covered by insurance or an active payment plan has no collection record.
[C1.3] Reports list unpaid debts. Because future repayment depends on ability to pay as much as willingness to pay, heavy medical arrears meaningfully predict default risk even when nobody chose to get sick.
[C1.4] Nor is medical nonpayment purely involuntary or meaningless. Waiting periods, dispute protections, and removing small or paid balances directly target the billing noise in [P1.6] and curb collector coercion over errors [P1.9]. What remains are larger, persistent unpaid obligations, including elective care and deductibles that some solvent borrowers deprioritize precisely because nobody can repossess a surgery. Look at [P1.7]: scoring builders discounted remaining medical collections rather than weighting them at zero.
[C1.5] Less predictive than a credit card default is still meaningfully predictive. And waiting for missed car or mortgage payments [P1.8] is backwards; households default on their car and roof last, making unresolved collections an early warning before lenders pile new debt onto an overextended borrower.
[C1.6] Total erasure backfires. Blinded lenders extend loans underwater patients cannot survive while pricing hidden risk into higher rates for everyone else. Meanwhile, providers stripped of credit reporting turn to upfront payment demands before non-emergency care or faster collection lawsuits. Calibrate the signal; do not blind the system.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.1], [C1.2], [C1.4], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] Accept CON's reframe entirely: reports measure capacity, not character [C1.1]. Medical debt still fails.
[P2.2] Start with the contradiction inside CON's own case. [C1.2] says a medical collection reveals a borrower who cannot pay. [C1.4] says solvent borrowers "deprioritize" medical bills "precisely because nobody can repossess a surgery." Those cannot both be the signal.
[P2.3] If people who can pay routinely rank a hospital bill last, then an unpaid one tells a lender nothing about how that person treats a car loan they rank first. CON has explained why this data misleads.
[P2.4] Next, the "binding financial liability." A medical collection is not a known monthly claim on a paycheck. It carries no payment schedule, is often cut down, written off or reversed once the insurer finally acts, and its stated amount is the least reliable number on the report. Lenders who want capacity already verify income and existing obligations directly.
[P2.5] If the two workers in my example still pay every debt they chose to take on, the appendix has told the lender nothing.
[P2.6] CON's "early warning" [C1.5] fails for the same reason. A household that is truly going under shows it early in exactly the places I named: card balances climb and card payments slip long before the car or the mortgage does. If none of that appears and the only blemish is a hospital account, the report is not warning of collapse. It is recording that someone got sick.
[P2.7] Notice how much CON has conceded. Paid balances, small balances and recent bills were removed because the data was noise [C1.4]. What remains is discounted by the people who build the scores. "Less predictive is still predictive" defends a residue of a residue, and that residue is still wrong-party billing, coding errors and collector leverage.
[P2.8] The backfire story [C1.6] is speculation. Bureaus have already removed a large share of medical collections voluntarily, and CON points to no resulting collapse in lending or care. Lenders lose only the one line on a report that tracks luck and tells them nothing about repayment.

## Turn 4: CON Rebuttal 1

- model: gemini-4-carbon-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [P2.2], [P2.3], [P1.7], [P2.7], [P2.8], [P2.4], [P2.6], [P1.2], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] [P2.2] invents a contradiction. Every delinquency pool mixes people who cannot pay with people who deprioritize a bill, and a group containing both defaults far more often than borrowers without collections. Overextended borrowers threaten every creditor, including auto lenders; solvent borrowers who let valid four-figure bills hit collections rather than arrange a payment plan directly warn card issuers, personal lenders, and landlords who also cannot repossess anything [P2.3]. Because mixed motives make medical collections noisier than missed car loans, scoring models discount their weight rather than dropping it to zero.
[C2.2] Apply the exact rule from [P1.7]: "Industry does not throw away data that predicts well." Random coding errors and wrong-party bills hit patients by chance; they cannot statistically predict loan defaults. Yet after bureaus dropped paid, small, and brand-new bills awaiting insurance, empirical score builders still kept weight on large, aged medical collections. Filtering static from a recording does not leave worthless "residue" [P2.7]; it isolates the signal.
[C2.3] And [P2.8] confuses targeted cleanup with a total ban: lending and care avoided disruption precisely because major, persistent arrears stay reported. Pruning noisy co-pays is nothing like blinding lenders and stripping provider leverage on massive unpaid debts.
[C2.4] Meanwhile, [P2.4] begs the question by claiming lenders already "verify income and existing obligations directly." Paystubs verify income, but credit reports are how lenders discover existing debts; applicants rarely confess hidden collections on loan forms. And once an insurer pays or reverses a bill, it leaves the report; what remains after waiting periods is an unpaid claim that can trigger lawsuits and wage garnishment ahead of voluntary loans.
[C2.5] Finally, [P2.6] assumes distress always flashes on credit cards first. Thin-file workers without cards, or families making minimum card payments to survive while letting a hospital balance default, look "spotless" [P1.2] on chosen debts [P2.5] until a blinded lender adds the loan that breaks them. Millions get sick without entering collections; reports track unresolved debt, not illness.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You call what's left after the cleanup "the signal" [C2.2]. For a borrower who is current on every debt they chose, what does one aged medical collection tell a lender: can't pay, won't pay, or the insurer is still fighting? And how does the lender tell which?
[P3.2] Q2: Your thin-file worker [C2.5] has no cards and no loans, so the hospital account is the whole file. Isn't that the clearest case of a single illness deciding a loan, with no repayment behavior on the report at all?

## Turn 6: CON Pressure Questions

- model: gemini-4-carbon-high
- raw_words: 90
- clipped_words: 90
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P2.4], [P1.7], [P2.7], [P2.8]
- missing_claim_id_refs: (none)

[C3.1] Q1: You agree reports measure capacity [P2.1] and claim lenders "verify income and existing obligations directly" [P2.4]. Since unpaid bills never appear on paystubs or bank statements, how can a lender discover an enforceable five-figure hospital debt before extending a loan the borrower cannot afford?
[C3.2] Q2: You treat score builders as empirical authorities [P1.7] yet admit they discounted, rather than zeroed out, remaining medical collections [P2.7]. If those accounts are just luck and billing noise telling lenders "nothing about repayment" [P2.8], why do data-driven models still find they predict default?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 388
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.1], [C2.5]
- missing_claim_id_refs: (none)

[P4.1] A1: The same way lenders discover alimony, child support, or a loan from a relative: they ask. Applications require borrowers to list obligations, and lying on one is fraud. And look at the word "enforceable." Once a hospital actually enforces a debt, there is a court judgment in the public record and a garnishment line on the paystub, which is the very document you say shows nothing.
[P4.2] Before that, a collection account has no payment schedule and an amount that may yet be cut or reversed. It is not a monthly claim on income. Your five-figure case is also the rare one, and reporting is a poor tool even there, because the figure it shows is the least reliable number on the file.
[P4.3] A2: Because correlation in a pool is not information about a borrower. Medical collections cluster among people with low incomes, thin savings and no insurance. Lenders already see those facts through income, balances and payment history. Once they are accounted for, what the hospital account adds is faint, which is why its weight has fallen every time the industry has looked harder.
[P4.4] As I understand it, at least one major scoring model now ignores medical collections altogether. A discount is the midpoint of a retreat, not an endorsement.
[P4.5] The motion says "meaningful," and CON's own description decides that. [C2.1] concedes the pool mixes people who can't pay with people who won't, and that this makes the data "noisier." Add those still fighting an insurer and a lender has three different stories behind one line, with no way to tell them apart. A signal that cannot be read for the applicant in front of you is a guess about a group they happen to fall into.
[P4.6] The costs are just as uneven. On CON's side, lenders lose a discounted, ambiguous data point that an application question, a public record or a paystub can replace. On mine, the thin-file worker in [C2.5] has a hospital account as their entire file. That person is refused an apartment or a car [clipped]

## Turn 8: CON Rebuttal 2

- model: gemini-4-carbon-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.5], [P4.6], [P4.1], [C1.6], [P4.2], [P4.3], [P1.2], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: It tells the lender this applicant carries an unresolved claim that raises future default risk. After a year-long waiting period, insurer fights are largely cleared, and lingering billing disputes can be flagged directly on the report. Between "can't pay" and "won't pay," lenders need not tell which, because both elevate default odds: stretched borrowers lack financial slack, while solvent borrowers ignoring valid claims invite garnishment and warn landlords or unsecured lenders. Every credit line works this way; a missed card payment never specifies job loss versus neglect.
[C4.2] Calling probabilistic risk "a guess about a group" [P4.5] indicts credit reporting itself.
[C4.3] A2: No. An unresolved debt, not an illness, is on that file. Sick thin-file workers using insurance, charity care, or hospital payment plans never hit collections. When an account still lands there after a year, either the borrower ignored a manageable plan, which is repayment behavior, or the debt is so crushing they lack capacity for another loan. Hiding it [P4.6] just baits blinded lenders into burying underwater workers deeper.
[C4.4] Those answers expose the substitutes in [P4.1]. Credit bureaus exist precisely because honor-system loan forms miss hidden debts. And telling lenders to wait for court judgments and paystub garnishments is perverse: to spare patients a discounted credit entry, hospitals are pushed to sue and garnish wages faster [C1.6]. Worse, an unpaid collection has "no payment schedule" [P4.2] only until litigation turns it into mandatory garnishment mid-loan, whereas a reported medical collection vanishes the moment it is settled or reversed.
[C4.5] Finally, [P4.3] forgets the premise of [P1.2]: two workers with identical incomes and spotless histories. Income and past balances cannot separate them, yet only one faces thousands in competing arrears. Because that marginal risk is real, mainstream scoring models still weight large, aged medical collections even if one model drops them [P4.4]. Calibrated reporting beats blinding lenders until lawsuits and defaults strike.

## Turn 9: PRO Closing

- model: claude-fable-5-2-high
- raw_words: 216
- clipped_words: 216
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.1], [C4.2], [C4.5]
- missing_claim_id_refs: (none)

[P5.1] One line from CON settles this. Asked what an aged medical collection tells a lender about a borrower current on everything they chose, the answer was that lenders "need not tell which" [C4.1]: can't pay, won't pay, or still disputing. That is a confession that the entry cannot be read for the person in front of you.
[P5.2] CON says that indicts all credit reporting [C4.2]. It doesn't. A missed card payment is ambiguous about motive, but it is unambiguous about the thing a lender is buying: how this person handles debt they agreed to, at a price they knew, on a schedule they accepted. A hospital collection has none of those features.
[P5.3] It records that a bill of uncertain size arrived uninvited and was not cleared.
[P5.4] So return to my two workers. CON's final claim is that the one who lost an appendix is the riskier borrower [C4.5]. Yet both still pay every lender on time. The report marks one down anyway, and for the thin-file worker that mark is the entire file.
[P5.5] Whatever faint correlation survives is what the industry keeps discounting and has begun to drop. The motion asks whether this signal is "meaningful." One that has to be filtered and discounted, and still can't be interpreted for the individual, is not. Remove it.

## Turn 10: CON Closing

- model: gemini-4-carbon-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.2], [P5.4], [P5.1], [P4.1]
- missing_claim_id_refs: (none)

[C5.1] Calling credit reporting a test of how someone handles "debt they agreed to" [P5.2] exposes the core error here. A lender is not grading past choices; a lender is buying a claim on future paychecks. An uninvited liability drains a paycheck just as surely as a chosen one.
[C5.2] Credit reports never record illnesses or burst appendixes [P5.4]. Patients using insurance, charity care, or payment plans never enter collections. Once waiting periods and bureau filters remove small, paid, and insurer-delayed bills, what appears on a report is persistent, unresolved debt.
[C5.3] Look at those two workers [P5.4] when they seek a loan. One has unencumbered income; the other carries thousands in aged arrears competing for the same paycheck. Lenders need not separate "can't pay" from "won't pay" [P5.1] because both elevate default risk: either the borrower lacks financial slack for another loan, or they ignore enforceable claims until garnishment strikes. Discounting that signal calibrates its weight; erasing it pretends the liability vanished.
[C5.4] Blinding lenders never erases the bill. Relying instead on honor-system forms and court judgments [P4.1] just buries overextended workers deeper while pushing hospitals to sue and garnish faster. Reports track unpaid obligations, not illness, and capacity determines repayment.
