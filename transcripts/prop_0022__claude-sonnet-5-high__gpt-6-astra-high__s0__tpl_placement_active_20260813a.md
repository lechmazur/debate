# Debate prop_0022__claude-sonnet-5-high__gpt-6-astra-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: claude-sonnet-5-high
- model_con: gpt-6-astra-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 367
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A stablecoin is a promise: one token equals one dollar, redeemable on demand. That promise is functionally identical to what a bank makes when it issues a deposit, or what a money-market fund makes when it sells a share priced at a dollar. Function should determine regulation, not the label on the wrapper. If it walks like a bank and quacks like a bank, treating it like a GitHub repository is a category error with systemic consequences.
[P1.2] Consider the mechanism of a run. Tether or USDC users don't hold code, they hold a claim on reserves held somewhere else, managed by someone else, in assets that may or may not be liquid. When Terra's UST collapsed in 2022, it wiped out tens of billions of dollars and spilled contagion into crypto lenders and exchanges within days. When Silicon Valley Bank wobbled in 2023, USDC briefly broke its peg because a chunk of its reserves sat in that very bank.
[P1.3] These are not software bugs. They are classic asset-liability mismatches and counterparty risks, the exact pathologies banking and money-market-fund regulation exists to contain.
[P1.4] Banks face capital requirements, reserve composition rules, deposit insurance, and lender-of-last-resort backstops precisely because deposit-like promises are fragile and contagious. Money-market funds face rules on reserve liquidity and disclosure after the 2008 "breaking the buck" episode taught regulators that a dollar-denominated claim needs enforced backing, not just a marketing promise. Stablecoins present the identical fragility at greater speed and scale, since redemption and panic can happen in seconds via smart contracts, with no opening bell to pause trading and no deposit insurance to stop the run.
[P1.5] Software-project regulation, meaning disclosure-light, code-is-law oversight, is built for products where failure means a buggy app, not a wiped-out payment system. Stablecoins increasingly function as payment rails and dollar substitutes for millions of users, including in economies with weak currencies. Letting issuers self-certify reserves, as many have historically done with vague attestations rather than real audits, is regulatory malpractice for something this systemically load-bearing.
[P1.6] The proposition isn't asking whether stablecoins are exactly [clipped]

## Turn 2: CON Opening

- model: gpt-6-astra-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A dollar target does not make every stablecoin a bank deposit or a money-market share. PRO’s analogy skips the decisive question: is the issuer intermediating customers’ savings, or providing software that transfers a fully backed payment claim? Regulate the activity, not the resemblance of the price.
[C1.2] Banks typically fund lending with redeemable liabilities. Money-market funds pool investors’ money into portfolios to earn returns. Neither activity is necessary to issue a payment token. An issuer that merely transfers claims on segregated cash resembles a digital warehouse operator more than a credit institution.
[C1.3] If it starts lending reserves or selling investment returns, regulate those activities accordingly. That does not justify making financial-institution oversight the default for the entire category.
[C1.4] The alternative is not PRO’s caricature of “code-is-law” immunity. Require truthful representations, enforce redemption contracts, protect customer property from the operator’s creditors, and impose liability for negligent software and security practices. Custodians should answer for custody; developers for systems they control; anyone secretly gambling with customer assets for that conduct. Fraud, custody, and contractual performance do not become banking merely because they concern dollars.
[C1.5] These targeted obligations address identifiable failures without imposing an institution-centered prudential regime.
[C1.6] PRO’s examples actually expose the weakness of its umbrella analogy. Terra’s stabilization mechanism and USDC’s exposure to a troubled bank were different vulnerabilities. Neither is adequately explained by saying both looked like deposits. Architecture, collateral, and custody matter.
[C1.7] Putting another layer of bank-like supervision over an issuer does not itself remove the risks of the bank holding its reserves.
[C1.8] The costs of that default matter, too. Prudential licensing and continuing supervisory overhead favor large incumbents, even where a smaller operator takes no credit risk. That can concentrate payment infrastructure without improving its underlying design. PRO must establish why bank or fund treatment outperforms direct controls on the actual hazard—not merely show that losing money is serious.
[C1.9] Preserve the software starting point; escalate regulation when the issuer’s financial activities warrant it.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 303
- clipped_words: 303
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.4], [C1.6], [C1.2], [C1.8]
- missing_claim_id_refs: (none)

[P2.1] CON’s whole case rests on one move: rename the risk so it sounds smaller. But look at what CON actually concedes in [C1.4] — truthful representations, enforced redemption, segregated custody, liability for negligence. That is not an alternative to bank/MMF regulation. That is bank/MMF regulation, minus the parts that actually work: capital buffers, liquidity ratios, and a mechanism to prevent contagion before it happens rather than suing about it after.
[P2.2] Take CON’s own example, USDC and Silicon Valley Bank [C1.6]. CON says this shows "architecture, collateral, and custody matter," as if that helps their side. It doesn't. USDC's reserves were exactly the kind of "segregated cash" CON says makes an issuer a mere warehouse operator [C1.2].
[P2.3] Segregation didn't stop a run. The peg broke because reserve composition and counterparty concentration weren't governed by any liquidity or diversification rule — the precise gap that bank reserve requirements and MMF liquidity rules exist to close. CON's fix, "protect customer property from the operator's creditors" [C1.4], would have done nothing here, because Circle wasn't insolvent — its bank was. Only prudential-style rules on where and how reserves are held prevent that failure mode.
[P2.4] CON's "warehouse operator" analogy [C1.2] also quietly assumes token holders have a clean, immediate claim on segregated assets. In practice they hold a contractual promise, redeemable at the issuer's discretion and speed, resolved through the same kind of opaque reserve reports that MMFs were required to fix after 2008. That's not a warehouse receipt; it's a demand liability, indistinguishable from a bank deposit in every way that matters to a run.
[P2.5] And the incumbency worry in [C1.8] cuts against CON: it's precisely because reserve, custody, and redemption failures are cheap to hide and expensive to unwind that lighter-touch "targeted obligations" invite the next Terra or the next SVB-style break, not fewer of them.

## Turn 4: CON Rebuttal 1

- model: gpt-6-astra-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO treats every enforceable financial promise as evidence for bank regulation. That classification proves too much. Truthfulness, protection of customer property, and liability also govern ordinary businesses. Sharing those obligations with banks does not justify importing their capital, liquidity, and supervisory framework.
[C2.2] Nor are targeted obligations merely “suing about it after.” Segregation and legally enforceable redemption rights constrain an issuer before failure. Software-security duties address failures capital ratios cannot prevent. PRO must compare preventive mechanisms, not relabel everything outside prudential supervision as after-the-fact litigation.
[C2.3] On USDC, the important distinction is between ownership of reserves and access to them. I never claimed segregation eliminates custodian failure. But exposure to a regulated bank does not establish that supervising the token issuer like another bank resolves the problem. Diversification could reduce that exposure; it cannot guarantee access during broader banking stress.
[C2.4] Capital can absorb some losses; it does not automatically unlock frozen deposits. PRO’s claim that “only” prudential rules prevent this failure oversells what those tools accomplish.
[C2.5] The warehouse objection also reverses the policy question. If users lack a clean claim on safeguarded assets, require that claim rather than treating its absence as an immutable feature of stablecoins. A pooled investment portfolio warrants fund-style oversight. A fixed claim on safeguarded cash does not become an investment portfolio merely because software transfers it.
[C2.6] The relevant distinction is what the operator does with customer assets, not whether the interface displays one dollar.
[C2.7] That is why the default matters. PRO’s framework subjects even a non-lending, non-investing operator to institutional oversight because other designs create intermediary risk. Our framework escalates when those activities actually appear. It preserves enforceable safeguards without pretending every architecture requires the same supervisory machinery.
[C2.8] Finally, hidden risks do not answer the incumbency objection. Expensive compliance can exclude transparent entrants while leaving opaque risks at large institutions. The better rule follows the hazard and the actor controlling it—not the token’s price target.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 95
- clipped_words: 95
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.7], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON says regulation should "escalate when the issuer's financial activities warrant it" [C2.7] — but Terra and Tether both hid their real reserve composition until after collapse. Who is supposed to detect the escalation trigger before the run, if not a prudential regulator with ongoing examination authority?
[P3.2] Q2: CON distinguishes a "fixed claim on safeguarded cash" from an investment portfolio [C2.5], but nearly every major issuer invests reserves in short-term securities to earn yield for itself — structurally identical to what MMFs do with shareholder cash. What non-arbitrary line separates that from fund-style pooling?

## Turn 6: CON Pressure Questions

- model: gpt-6-astra-high
- raw_words: 59
- clipped_words: 59
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: You claim Terra and Tether hid reserves “until after collapse.” What Tether collapse are you referring to, and why should that example support compulsory prudential examination?
[C3.2] Q2: If even a non-lending, non-investing issuer with verified cash reserves requires bank/MMF-style oversight, what limiting principle prevents your framework from imposing the same regime on ordinary escrow providers and cash custodians?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 279
- clipped_words: 279
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: [C2.7]
- missing_claim_id_refs: (none)

[P4.1] A1: I misspoke calling it a "collapse" — Tether never de-pegged catastrophically. But that's the point, not an escape for CON. Tether spent years telling the public its tokens were "fully backed by dollars," then, when regulators finally examined the books, had to disclose commercial paper, other issuers' bonds, and even loans to affiliated entities, and paid settlements for those misrepresentations. No run happened only because no one forced a test.
[P4.2] That is exactly the danger of self-certified reserves: the market can't distinguish a well-run issuer from a hollow one until stress hits, which is why banks and MMFs face mandatory, ongoing examination rather than voluntary attestation. CON's model relies on the public correctly pricing risk it cannot see.
[P4.3] A2: The limiting principle is functional, not size-based: an obligation becomes bank/MMF-like when (1) it's redeemable on demand, (2) it circulates as a medium of exchange among strangers who never chose counterparty risk with the issuer, and (3) the issuer earns a yield spread by investing the backing assets. Escrow providers fail all three — funds are bilateral, tied to one transaction, not traded as money, and the escrow agent doesn't profit from investing your funds elsewhere. Stablecoin issuers satisfy all three, which is why USDC and Tether look like banks and an escrow account never will.
[P4.4] That answers CON's questions, but notice what's left standing: CON never rebuilds the limiting principle it demanded of me. "Escalate when activities warrant it" [C2.7] still assumes someone catches the escalation trigger before failure — and CON's own Tether example shows self-report doesn't. Prudential examination isn't redundant with disclosure; it's the only mechanism that finds the hidden mismatch before, not after, the run.

## Turn 8: CON Rebuttal 2

- model: gpt-6-astra-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Independent reserve verifiers, custodians confirming balances directly, and enforcement authorities inspecting compliance with custody restrictions can detect hidden investment before a run. Those checks should be mandatory and recurring—not voluntary self-certification. That is verification of customer-property duties, not necessarily supervision of a risk-taking financial institution. PRO must justify capital requirements, liquidity ratios, and institutional licensing separately; calling every effective compliance check “prudential” assumes its conclusion.
[C4.2] A2: The non-arbitrary line is whether the operator invests customer backing assets rather than merely safeguarding cash. An issuer managing a pooled securities portfolio crosses that line; retaining the yield itself does not make investment management disappear. Fund-style safeguards can attach to that activity. But issuance alone does not cross the line.
[C4.3] Regulating an investment business that also issues tokens is different from making token issuance presumptively an investment business.
[C4.4] PRO’s latest limiting principle actually requires that “the issuer earns a yield spread by investing the backing assets.” That excludes our non-lending, non-investing issuer. PRO therefore cannot simultaneously defend that principle and demand bank/MMF-style treatment for that issuer merely because its claims circulate. The prevalence of investment-backed tokens supports regulating investment activity, not making the stablecoin label the regulatory trigger. That distinction determines which obligations are justified, rather than merely which institution gets to impose them.
[C4.5] The repaired Tether example establishes a reason to verify representations, not the exclusive necessity of prudential supervision. “No run happened only because no one forced a test” is an unsupported counterfactual, not proof that alternative enforcement cannot work. PRO still has not shown why checking assets must bring capital requirements or institutional licensing along with it.
[C4.6] The choice is not supervision versus blindness. It is enforceable safeguards tied to actual activities versus a financial-institution default that burdens even architectures without investment intermediation. PRO has demonstrated that some issuers conduct financial businesses. It has not demonstrated that stablecoin issuance should therefore be regulated as one.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 180
- clipped_words: 180
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.2]
- missing_claim_id_refs: (none)

[P5.1] CON's whole case now stands or falls on one line: bank/MMF treatment applies only when "the operator invests customer backing assets rather than merely safeguarding cash" [C4.2]. Test that line against reality. Circle invests USDC's reserves in Treasury securities and repo. Tether invests its reserves in commercial paper, bonds, and secured loans.
[P5.2] Every stablecoin large enough to matter earns yield by putting customer backing assets into a portfolio it manages and controls the proceeds of. By CON's own admitted trigger, these issuers "cross that line" [C4.2] into fund-style regulation.
[P5.3] So the disagreement was never really about principle. It's about who gets the money-market fund next door and who gets a "verification of customer-property duties." CON needed a category of stablecoin issuer that safeguards cash without investing it, to keep the software default alive. That category is empty in practice.
[P5.4] The moment you apply CON's own limiting principle honestly, it produces PRO's conclusion: prudential-style oversight for the issuers that actually exist, not a hypothetical warehouse operator that doesn't. Regulate the activity, CON says. The activity is banking. Regulate it like banking.

## Turn 10: CON Closing

- model: gpt-6-astra-high
- raw_words: 208
- clipped_words: 208
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s closing substitutes a description of today’s leading firms for a justification of the regulatory default. Even if every major issuer invests its reserves, that establishes where our activity-based rule applies today. It does not establish that token issuance itself is investment management.
[C5.2] Two rules can cover the same firms today and still create different incentives tomorrow. Under our rule, an operator that stops investing customer assets can shed the obligations justified by that investment activity, while retaining mandatory custody, redemption, verification, and software-security duties. Under PRO’s category-based default, abandoning the risky business model does not establish an exit from institutional oversight. That is precisely where unnecessary compliance costs can protect incumbents rather than customers.
[C5.3] Calling the cash-safeguarding category “empty in practice” does not answer this distinction. A regulatory rule should accommodate safer architectures, not make today’s dominant business model the compulsory template. PRO’s own limiting principle included investing backing assets; its closing cannot erase that condition merely because prominent issuers satisfy it.
[C5.4] The decisive question is what justifies the additional regulation. Our answer identifies an activity and attaches safeguards to it. PRO identifies a label and generalizes from its largest users. Regulate the portfolio because it is a portfolio—not token issuance because leading issuers also manage one.
