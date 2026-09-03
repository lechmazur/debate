# Debate prop_0633__claude-fable-5-1-high__claude-fable-5-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0633
- proposition: Governments should require large employers to treat algorithmic hiring and promotion tools as “high-risk,” including mandatory bias testing and audit trails.
- model_pro: claude-fable-5-1-high
- model_con: claude-fable-5-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 351
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A résumé screened by a biased manager is one bad decision. A résumé screened by a biased algorithm is the same bad decision made ten thousand times, at machine speed, with nobody in the room who can be asked why. That asymmetry is the whole case.
[P1.2] Start with what already exists. Every developed democracy already bans employment discrimination on race, sex, age, and disability. Nobody in this debate disputes that. The question is only whether that law remains enforceable once decisions migrate from people to software.
[P1.3] Today it largely does not. A rejected applicant cannot cross-examine a model. Regulators cannot subpoena a hunch. Vendors invoke trade secrets.
[P1.4] The result is a legal right with no evidentiary path to vindicate it. Mandatory bias testing and audit trails are simply the discovery mechanism that lets existing law function in a new medium.
[P1.5] The risk is not hypothetical. Amazon famously abandoned an internal recruiting model after engineers found it had learned to penalise résumés containing the word "women's" and downgraded graduates of women's colleges—because it was trained on a decade of hires who were mostly men. Amazon caught it because Amazon happened to look. Most employers deploy vendor tools and never look, because looking is optional and costs money.
[P1.6] "High-risk" is not a ban. It is the same logic we apply to elevators, aircraft parts, and financial statements: when a failure is invisible to the person harmed and propagates at scale, we require the operator to test before deployment and keep records after. Large employers already run payroll audits, safety inspections, and pay-equity reports. Adding disparate-impact testing on a system that decides who gets a livelihood is proportionate, not radical.
[P1.7] Expect the objection that human hiring is biased too. True—and irrelevant. We are not choosing between algorithms and saints. We are choosing between algorithms that are checked and algorithms that are not.
[P1.8] Testing is what turns a machine's consistency from a liability into an asset: a biased pattern in code can actually be found and fixed, unlike a biased pattern in a thousand [clipped]

## Turn 2: CON Opening

- model: claude-fable-5-high
- raw_words: 314
- clipped_words: 314
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition rests on a hidden assumption: that if we regulate the algorithm, employers will keep using the algorithm. They won't. Make automated screening legally "high-risk"—with mandatory audits, testing regimes, and a documented trail for plaintiffs' lawyers—while human judgment stays cheap and unexamined, and rational employers retreat to the one method we know is biased and cannot be audited at all: gut feel. The mandate doesn't reduce discrimination.
[C1.2] It relocates it somewhere darker.
[C1.3] Notice that PRO's own showcase example proves the status quo works. Amazon's engineers found the bias, and the tool died—no mandate, no regulator, no audit statute. What killed it was ordinary litigation exposure under existing law. Disparate-impact doctrine already applies to algorithmic decisions; it doesn't care whether the discriminator is a manager or a model.
[C1.4] If enforcement needs teeth, fund enforcement agencies and clarify discovery rules. That is a scalpel. Declaring an entire technology category "high-risk" is a sledgehammer that hits the tool rather than the harm.
[C1.5] And the sledgehammer misses. New York City already tried mandatory bias audits for hiring algorithms, and by most accounts compliance was minimal and the audits that did occur were checkbox exercises performed by auditors chosen and paid by the audited. Meanwhile, bias testing itself requires employers to collect applicants' race, sex, and disability status at scale—a privacy intrusion PRO never mentions, and a dataset ripe for misuse.
[C1.6] Finally, weigh who bears the cost. "Algorithmic tool" has no clean boundary: a keyword filter, a spreadsheet ranking, a scheduling formula. A vague high-risk designation with audit liability entrenches the biggest vendors who can afford compliance departments, freezes iteration on the very fixes PRO wants, and slows hiring for everyone waiting in the queue.
[C1.7] The real choice isn't checked algorithms versus unchecked ones. It's enforceable outcome-based law versus a compliance regime that drives decisions back into the unauditable human skull. Choose the version that actually catches discrimination.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 343
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON's entire case hangs on one prediction: audit the software and employers flee back to gut feel. Picture what that actually means for a large employer. A national retailer receives hundreds of thousands of applications a year. Nobody is going to hire a floor of humans to read them because a testing requirement raised the vendor's price.
[P2.2] Automation saves millions; a disparate-impact test costs a fraction of that. The substitution CON fears is not rational—it is the one option the economics rule out. And the motion targets large employers precisely because they are the ones for whom reversion is fantasy.
[P2.3] Now the Amazon point, which CON has backwards. Amazon caught the bias because Amazon *built* the model and its own engineers could open it. That is the exception. Most employers license a vendor black box and receive a ranked list.
[P2.4] CON says "ordinary litigation exposure" killed the tool—but litigation exposure requires a plaintiff who can show a pattern, and no plaintiff can show a pattern inside software that keeps no logs. Nobody sued Amazon. Amazon looked. The motion makes looking mandatory.
[P2.5] Watch CON's alternative closely: "fund enforcement agencies and clarify discovery rules." Clarify them to require what, exactly? Test results and decision records. That *is* the audit trail.
[P2.6] CON has conceded the mechanism and is haggling over the label.
[P2.7] New York's law is the strongest thing CON has, and it cuts the other way. That statute let employers decide whether their own tool "substantially assisted" a decision, and enforcement was thin—so employers opted out and auditors were captured. That is a case for independent auditors and real enforcement, which the motion contemplates, not a case that testing is futile. Nobody concludes from a weak fire code that buildings shouldn't be inspected.
[P2.8] On privacy: large employers in most jurisdictions already collect voluntary demographic data for equal-opportunity reporting. Disparate-impact testing uses that same aggregate data. Nothing new is gathered.
[P2.9] The comparison is now clear. CON offers outcome-based law with no way to observe outcomes. The motion supplies the evidence. Law without evidence [clipped]

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.6]
- missing_claim_id_refs: (none)

[C2.1] PRO's substitution answer attacks a strawman. Nobody claimed the national retailer hires a floor of résumé readers. The retreat happens at the margins that matter: referral-heavy hiring, staffing agencies, credential cutoffs, and—crucially—definitional dodging. That last one isn't my prediction; it's what New York actually recorded.
[C2.2] Employers didn't stop screening. They declared their tools outside the covered category and carried on, unaudited. The mandate didn't produce checked algorithms. It produced relabeled ones.
[C2.3] PRO's answer to this—"so make enforcement real and auditors independent"—is a promissory note. Who pays the independent auditor? If the audited firm does, you've rebuilt the credit-rating-agency problem: a compliance market whose product is reassurance. PRO owes a mechanism, not an adjective.
[C2.4] On [P2.6], the alleged concession: requiring decision records in discovery when a dispute exists is categorically different from a universal ex-ante regime on every tool a large employer touches. One is triggered by a plausible harm and scoped by a judge. The other taxes every spreadsheet ranking and scheduling formula in advance, forever. If PRO wants log retention, legislate log retention—a two-line rule.
[C2.5] The motion instead imports the whole "high-risk" apparatus: pre-deployment testing, ongoing audits, liability trails. Accepting the narrow fix while defending the broad regime is the actual haggling here.
[C2.6] On Amazon: PRO says "nobody sued, Amazon looked." Exactly—the anticipation of liability made looking worthwhile before any regulator arrived. That incentive scales to vendors too, who face ruin if their black box generates a class action across a hundred client firms.
[C2.7] On privacy, PRO concedes more than intended. EEO data works because it's voluntary, aggregate, and firewalled from decisions. Model-level bias testing requires linking demographics to individual applications and scores—and the motion covers promotions, meaning demographic tracking of your own workforce tied to advancement records.
[C2.8] The clash has narrowed usefully: PRO now defends enforcement, which I endorse. The remaining question is instrument choice—and PRO's chosen instrument has already been field-tested and gamed.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 85
- clipped_words: 85
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say discovery is "triggered by a plausible harm and scoped by a judge" [C2.4]. If no one is required to test a licensed vendor black box before deployment, who ever generates the evidence that makes a rejected applicant's harm "plausible" enough to trigger that discovery?
[P3.2] Q2: You endorse log retention and enforcement "with teeth." Name the specific obligation in the motion—pre-deployment bias testing, decision records, or independent review—that you actually reject, and explain how your outcome-based law detects a disparate outcome without it.

## Turn 6: CON Pressure Questions

- model: claude-fable-5-high
- raw_words: 92
- clipped_words: 92
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7], [P2.8]
- missing_claim_id_refs: (none)

[C3.1] Q1: You concede New York failed because auditors were "captured," and your fix is auditors that are "independent" [P2.7]. Independent means paid by whom—if the answer is still the audited employer or vendor, what stops your regime from reproducing exactly the checkbox market New York produced?
[C3.2] Q2: The motion covers promotions. Since you say testing "uses that same aggregate data" [P2.8], explain how you audit a promotion model for disparate impact without linking each current employee's race, sex, and disability status to their individual scores and advancement records—and who safeguards that file?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.4], [C2.6]
- missing_claim_id_refs: (none)

[P4.1] A1: Paid by the employer—the same way every public company pays the accountant who audits its books. Financial audits work not because payment flows from a saint, but because auditors are licensed, rotate, file with a regulator, and face personal liability for false attestations. New York had none of that: coverage was self-declared, nothing was filed anywhere, nobody was fined. That is a failure of enforcement design, not of the payment model.
[P4.2] And notice what even a captured audit produces: a written record of what the tool did to whom. A checkbox is still a document a plaintiff can later tear apart. A black box is not. CON's status quo produces the black box.
[P4.3] A2: Every large employer already holds each employee's race, sex, and disability status in the same HR system as their performance ratings and promotion history. That is how workforce equal-opportunity reports and pay-equity analyses are compiled today. Testing a promotion model means comparing advancement rates across groups within that existing file—the auditor sees rates, not names. The safeguards are the ones already governing payroll and medical-leave data, and the motion can require aggregation and purpose limitation.
[P4.4] CON is describing the ordinary contents of an HR department and calling it a new intrusion.
[P4.5] Now zoom out. Both of my questions went unanswered, and the silence is the debate. CON says discovery is "triggered by a plausible harm" [C2.4] but never says who generates the evidence of harm when nobody must test the vendor's tool. CON says vendors fear "a class action across a hundred client firms" [C2.6] but a class action requires a provable pattern, and CON's regime forbids requiring the records that prove it.
[P4.6] That is a loop: liability deters only if detection is possible, and detection is exactly what CON refuses to mandate.
[P4.7] CON has conceded enforcement, conceded log retention, conceded testing "when a dispute exists." Everything left is the demand that evidence appear before anyone is obliged to create it. Outcome-based law with unobservable outcomes is not an alternative. It is the status quo [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.6], [P4.1], [P4.2], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: The same way every disparate-impact case in history was built: from outcomes, not from inside the tool. Plaintiffs and regulators have never needed to open a manager's skull to show that a facially neutral practice produced a skewed result—they compare the applicant pool to the hires. Large employers already file workforce demographic reports; a rejected applicant, a labor agency, or a union can spot a pattern in those numbers, and that pattern is exactly what makes harm "plausible" and unlocks discovery.
[C4.2] Add the two-line record-retention rule I've already endorsed, and discovery has something to find. Evidence of harm lives in outcomes, which are observable now.
[C4.3] A2: I reject the ex-ante apparatus—mandatory pre-deployment testing and the recurring third-party audit market. I accept decision-record retention. And that answers the second half: outcome-based law detects disparity through the aggregate statistics employers already generate, then uses retained records under judicially scoped discovery to attribute it. PRO's "loop" [P4.6] never closes, because detection comes from outcomes, deterrence from liability, and records from retention.
[C4.4] None of that requires the regime New York already field-tested into farce.
[C4.5] Now watch what PRO's answers cost him. Asked how to fix auditor capture, PRO invents the entire financial-audit state—licensing, rotation, regulator filings, personal liability [P4.1]—none of which is in the motion, all of which took decades to build and still gave us the era of rubber-stamped Enron books. Then comes the tell: "even a captured audit produces a written record" a plaintiff can tear apart [P4.2]. So the defensible core of PRO's own regime is... records.
[C4.6] That is my position. PRO is defending the sledgehammer while retreating to the scalpel.
[C4.7] On promotions, PRO says the auditor "sees rates, not names" [P4.3]—but rates can't audit a model; testing scores requires individual-level linkage of demographics to advancement files, precisely the intrusion PRO waved away.
[C4.8] The choice is now stark: an unlegislated ideal that failed where tried, or enforcement plus records that work today. Take the version that exists.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 208
- clipped_words: 208
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.1]
- missing_claim_id_refs: (none)

[P5.1] Everything in this debate has collapsed to one question: when does the bias test happen, and who runs it?
[P5.2] CON now says detection comes from "comparing the applicant pool to the hires" [C4.1]. Look at what that is. It is a disparate-impact test on the tool's outputs, using applicants' demographic data—the exact analysis, on the exact data, CON spent two speeches calling an intrusion and a checkbox. CON has not rejected bias testing.
[P5.3] CON has assigned it to a rejected applicant, years later, working from public filings that don't even list applicants, hoping the retained records survive and a judge unlocks them.
[P5.4] The motion assigns the same test to the employer, before deployment, on the file the employer already holds.
[P5.5] That difference is the whole case. Amazon's tool never screened a real candidate because someone looked first. Under CON's regime, that same model ships, runs across a hundred client firms at machine speed, and the pattern becomes visible only in the wreckage—thousands of livelihoods already decided, and a lawsuit that at best pays some of them back.
[P5.6] Records tell you what happened. Testing decides whether it happens. Once CON conceded the test itself, the only remaining choice is whether it occurs before the harm or after. Choose before.

## Turn 10: CON Closing

- model: claude-fable-5-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's closing asks you to choose "before or after." But the debate already tested what "before" looks like when legislated: New York, where employers relabeled their tools out of coverage and the audits that happened were purchased reassurance. PRO's rescue required inventing an entire financial-audit state—licensing, rotation, personal liability—none of which appears in the motion being voted on. You cannot vote for an apparatus PRO had to build mid-debate to make the motion survive.
[C5.2] Nor did I concede the test. Comparing applicant pools to hires uses aggregate outcome data employers already file—the foundation of every disparate-impact case ever won. That is categorically different from mandated ex-ante model audits requiring individual-level demographic linkage, run by a captured compliance market, on every "algorithmic tool" a large employer touches, forever.
[C5.3] And notice: the one genuine "before" story in this debate—Amazon killing its model before it screened a single candidate—happened under exactly my regime. Liability made looking worthwhile; no mandate existed. Deterrence plus retained records catches harm early where it counts, without the paper shield that lets a checkbox certificate say "audited" over a biased tool.
[C5.4] The motion offers a "before" that failed where tried. Take the enforcement that actually looked.
