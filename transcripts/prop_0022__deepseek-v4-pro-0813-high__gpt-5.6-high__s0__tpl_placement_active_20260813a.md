# Debate prop_0022__deepseek-v4-pro-0813-high__gpt-5.6-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: deepseek-v4-pro-0813-high
- model_con: gpt-5.6-high
- side_swap: False

## Turn 1: PRO Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 305
- clipped_words: 305
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A stablecoin is not merely a protocol. It is a promise: a user gives the issuer dollars, receives a token, and expects those dollars back on demand. The software moves the token; the financial claim creates the risk. Regulating stablecoin issuers as ordinary software projects would catch bugs, but not insolvency, runs, or broken redemption promises.
[P1.2] The decisive issue is functional equivalence. Stablecoin issuers take customer funds, hold reserve assets, and owe par redemption. That is economically indistinguishable from a money-market fund or a narrow bank. If an issuer buys commercial paper, Treasuries, or other assets with user dollars and promises 1:1 redemption, it is managing credit risk, liquidity risk, and maturity risk.
[P1.3] Software regulation has no meaningful answer to those risks. Bank and money-market fund rules do: eligible reserve assets, liquidity buffers, segregation of customer funds, independent audits, capital requirements, and limits on risky yield-seeking.
[P1.4] Run risk makes the stakes concrete. Like money-market funds, stablecoins are vulnerable to a loss of confidence. If users doubt the reserves or the peg, they redeem at once. The issuer must dump assets into falling markets, magnifying losses and locking ordinary holders out.
[P1.5] A code audit cannot stop that dynamic. Liquidity requirements, transparent reserve reporting, and credible redemption capacity can reduce it.
[P1.6] Consumer harm follows directly. Retail users treat stablecoins as safe, cash-like balances, yet reserves may be opaque, commingled, or invested in risky short-term paper. If a large issuer fails, forced asset sales can transmit stress beyond crypto markets. That is precisely the systemic concern that justifies banking and money-market fund oversight.
[P1.7] The point is not that every issuer must become a full bank. It is that issuing redeemable, money-like liabilities backed by a pool of assets should attract prudential regulation, not software-project liability. Similar risk should face similar rules; otherwise stablecoins become the next shadow-banking loophole.

## Turn 2: CON Opening

- model: gpt-5.6-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition relies on a false choice: either treat stablecoins as ordinary software or import banking and money-market-fund regulation. The better approach is a bespoke payments framework aimed directly at reserves, custody, redemption, disclosure, and operational security. Those safeguards do not require pretending every stablecoin issuer is a bank or fund.
[C1.2] “Functional equivalence” collapses crucial differences. Banks create credit, operate with leverage, transform maturities, and rely on public confidence across lending and payment systems. Money-market funds sell investment shares whose value and yield reflect a managed portfolio. A fully reserved stablecoin can instead be a payment token backed one-for-one by cash or short-term public debt, with no lending and no maturity transformation.
[C1.3] Similar-looking redemption does not make these business models economically indistinguishable.
[C1.4] Importing whole regulatory models therefore produces mismatch. Bank capital rules address losses on risky assets; the cleaner response for stablecoins is to prohibit those assets. Deposit-insurance-style treatment can generate bailout expectations. Money-market-fund rules are designed around investment products, not tokens used for rapid settlement.
[C1.5] Compliance structures built for large financial institutions impose fixed costs that squeeze out smaller entrants and consolidate issuance among a few incumbents—the opposite of resilience.
[C1.6] The proposition is also overbroad because “stablecoin” describes heterogeneous systems. A centralized issuer holding reserves presents custody and solvency risks. A protocol using overcollateralized on-chain assets presents smart-contract, oracle, and liquidation risks. An algorithmic design may not hold conventional reserves or promise legal redemption at all.
[C1.7] Calling every developer or governance participant bank-like does not control the relevant risk; it merely assigns the wrong obligations to the wrong actors.
[C1.8] Run risk justifies strict rules, but tailored ones: segregated reserves, high-quality liquid backing, enforceable redemption rights, regular attestations, cybersecurity standards, and failure-resolution plans scaled to size. These are payment-instrument protections, not evidence that the issuer should be regulated “more like” a bank or fund.
[C1.9] Good regulation follows the actual risk. The proposition follows an analogy—and when the analogy fails, regulation becomes both burdensome and less effective.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.8]
- missing_claim_id_refs: (none)

[P2.1] The opponent’s own remedy concedes the core. He rejects the label “bank or fund” but then demands segregated reserves, high-quality liquid backing, enforceable redemption rights, attestations, cybersecurity standards, and failure-resolution plans [C1.8]. That is not ordinary software regulation; it is prudential regulation of money-like liabilities. The proposition says “more like” banks or money-market funds—not “identical in every obligation.” C1.1 and C1.8 therefore attack a position I did not take.
[P2.2] C1.2’s distinction is weaker than it looks. A stablecoin promising par redemption on demand holds demand-like liabilities against a pool of assets. Even if those assets are cash or short-term public debt, the issuer still manages liquidity, redemption timing, asset quality, and market risk. Short-term debt can lose value or become hard to sell under stress—exactly why money-market funds face liquidity and asset restrictions.
[P2.3] And the fact that tokens settle rapidly makes run risk faster, not safer; confidence can vanish before an issuer can sell assets. A fully reserved narrow bank would still receive bank-like oversight for the same reason. C1.3 merely asserts otherwise.
[P2.4] The cost objection also misses the point. If an issuer can gather billions by selling cash-like tokens, prudential costs are not an arbitrary burden; they are the price of making a redeemable financial promise to the public. Heterogeneity can be met with thresholds and design-sensitive standards—not by treating centralized issuers as software. Algorithmic or overcollateralized systems do not get a free pass when they create de facto redemption obligations.
[P2.5] The deeper problem is that the opponent’s “bespoke” framework is just the bank/MMF toolbox with a different label. His side has already accepted the relevant safeguards while denying their logical classification. That is the shadow-banking loophole in miniature: adopt the substance of prudential regulation, call it something lighter, and hope the analogy fails. It does not.

## Turn 4: CON Rebuttal 1

- model: gpt-5.6-high
- raw_words: 343
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [C1.8]
- missing_claim_id_refs: (none)

[C2.1] PRO wins only by draining “more like banks or money-market funds” of content. On the weak reading—stablecoins need some rules beyond code audits—the proposition is trivial, and CON already accepts that. On the meaningful reading—bank or fund regulation should provide the governing model—it is wrong. Borrowing a useful tool does not justify importing the institutional analogy.
[C2.2] Restaurants and hospitals both face sanitation rules; that does not make restaurants hospital-like institutions.
[C2.3] The safeguards in [C1.8] are tailored product rules. Segregation protects customer property. Redemption terms enforce a contract. Reserve restrictions can eliminate risky portfolio choices.
[C2.4] Cybersecurity addresses the technology itself. None requires bank-style supervision of lending and leverage or fund-style treatment of investors buying managed portfolio shares. Classification matters because it determines licensing burdens, supervisory assumptions, permitted activities, resolution structures, and expectations of public support—not merely whether reserves are disclosed.
[C2.5] PRO also assumes the run mechanism rather than answering our design. If backing is segregated, one-for-one, and confined to cash or genuinely liquid short-term public assets, redemption does not expose a leveraged loan book. The issuer can also be required to match redemption timing to reserve liquidity. The correct response is to remove maturity and credit transformation, not regulate as though those bank-like risks must remain.
[C2.6] Rapid token transfers may accelerate exits, but speed alone cannot manufacture an asset shortfall.
[C2.7] Most damagingly, PRO’s answer to heterogeneity—“thresholds and design-sensitive standards”—is the bespoke framework it claims to reject. Once obligations depend on whether there is a legal issuer, actual redemption, reserve custody, or an autonomous protocol, the bank/MMF label has stopped doing the regulatory work. Treating a protocol’s developers as issuers because users perceive a “de facto” promise instead blurs legal responsibility and encourages enforcement against the wrong actors.
[C2.8] So the choice is not prudence versus a loophole. It is precision versus analogy. CON regulates the reserve, redemption promise, custodian, and code according to the risk each creates. PRO starts with a familiar financial label, then adds exceptions until it quietly arrives at our tailored model—after imposing unnecessary cost, concentration, and moral-hazard expectations [clipped]

## Turn 5: PRO Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 65
- clipped_words: 65
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say issuers can be required to match redemption timing to reserve liquidity [C2.5]. Stablecoins promise on-demand par redemption. What reserve asset—outside central-bank reserves or insured deposits—remains liquid enough during a broad run to satisfy that requirement?
[P3.2] Q2: If your answer requires bank-like or MMF-like liquidity backstops or oversight, what work is your “bespoke” payments framework still doing beyond relabeling the same prudential regime?

## Turn 6: CON Pressure Questions

- model: gpt-5.6-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: For a fully reserved issuer with no lending or maturity transformation, what specifically bank- or money-market-fund-style obligation is necessary beyond tailored reserve, disclosure, custody, and redemption rules—and what distinct risk does it address?
[C3.2] Q2: For a decentralized, overcollateralized protocol with no legal redemption obligor or reserve manager, who exactly is the “issuer,” and which bank or money-market-fund model applies without imposing duties on developers for risks they do not control?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 307
- clipped_words: 307
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C3.1], [C3.2], [C1.8]
- missing_claim_id_refs: (none)

[P4.1] A1: On [C3.1], the missing obligation is standing institution-level supervision: an examiner that can impose operational capital, run liquidity stress tests, restrict reserve concentration and duration, monitor custodial integrity, and put an issuer into orderly resolution before the peg breaks. That addresses a distinct risk even with no lending or maturity transformation: confidence and operational failure. On-demand par redemption means redemptions happen faster than even high-quality assets can be sold or delivered; an issuer can be solvent on paper and still fail overnight because its custodian freezes, a key administrator fails, or holders no longer trust the attestation.
[P4.2] A disclosure or reserve rule is a fixed requirement; it cannot stop a dynamic run or a failing operating structure. Narrow banks hold cash and perform no credit transformation, yet they are still prudentially supervised for exactly this reason.
[P4.3] A2: On [C3.2], if there is genuinely no legal obligor, no reserve manager, and no redeemable promise, there is no issuer in the proposition’s sense, and PRO does not regulate a ghost. Developers should not be treated as issuers merely because code exists. But that is a boundary, not a problem for PRO: most large “decentralized” stablecoins still have governance multisigs, foundations, fee-earning deployers, or treasury actors who control collateral and redemption. Those actors are the issuers.
[P4.4] Where none exists, the motion’s issuer-focused rule simply does not apply.
[P4.5] This exchange narrows the debate in PRO’s favor. CON has conceded the prudential safeguards that matter [C1.8]. The remaining dispute is whether those safeguards sit inside a durable bank/MMF-style supervisory framework or a looser bespoke wrapper. A1 shows why written product rules are not enough for a live run.
[P4.6] An issuer of redeemable, money-like liabilities needs an ongoing supervisor with examination, liquidity, and resolution powers. That is not relabeling; it is the difference between regulating a product and regulating a money-like institution.

## Turn 8: CON Rebuttal 2

- model: gpt-5.6-high
- raw_words: 329
- clipped_words: 329
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: No asset guarantees instantaneous liquidation during every conceivable broad run; that standard is impossible and is not satisfied by ordinary bank or money-market-fund regulation either. A tailored rule can require an operational cash buffer, with the remainder in very short-dated sovereign obligations matched to legally stated redemption windows. If PRO demands enough sovereign money for a simultaneous 100% redemption, supervision cannot manufacture it. The answer would be stricter reserve design or direct access to sovereign money—not a bank/MMF label.
[C4.2] A2: The bespoke framework still determines reserve eligibility, bankruptcy-remoteness, custody diversification, redemption rights, technology resilience, and resolution, with ongoing examinations and stress testing where appropriate. It omits rules built for lending, leverage, managed investment shares, and implied public backstops. Using supervision does not make an institution bank-like; payment systems and other critical infrastructures are continuously supervised too.
[C4.3] PRO’s latest answer actually abandons its key dichotomy. It says our framework is merely “written product rules,” but nothing in bespoke regulation precludes an examiner, adaptive enforcement, or orderly resolution. Those are generic regulatory methods, not proprietary features of banks and funds. Moreover, its examples—custodian freezes, administrator failure, compromised operations—are best answered by custody segregation, backup operators, key-management standards, and direct customer claims.
[C4.4] Bank capital rules cannot unfreeze an external custodian, while fund portfolio rules cannot repair compromised code.
[C4.5] PRO also concedes that where no legal obligor or reserve manager exists, its model does not apply [P4.3–P4.4]. That validates our heterogeneity objection. A governance key or fee recipient is not automatically an issuer promising redemption; assigning bank-like duties by vague “control” recreates the very responsibility mismatch PRO claims to avoid.
[C4.6] The decisive comparison is therefore precision against analogy. CON provides ongoing, enforceable protection against the actual failure channels while avoiding irrelevant institutional baggage. PRO either imports genuinely bank/MMF-specific structures, making regulation mismatched, or reduces “more like” to examinations and liquidity rules available under any serious payments regime. On the first reading it is wrong; on the second it proves no distinctive proposition.

## Turn 9: PRO Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 206
- clipped_words: 206
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive point is the redemption promise. A stablecoin issuer says: send dollars, receive a token, and get one dollar back on demand. That is not software; it is a demandable money-like liability. Once that liability exists at scale, the relevant failure is a run, not a bug.
[P5.2] Static reserve, disclosure, and custody rules cannot stop a run after doubt starts: a custodian freeze, delayed attestation, or redemption surge can break a solvent issuer overnight.
[P5.3] That is why the rule that matters is standing institution-level oversight—liquidity stress testing, operational resilience, examiner authority, and orderly resolution. CON now accepts those tools while calling them “bespoke payments regulation” or “critical-infrastructure supervision.” But for a redeemable par liability backed by managed reserves, those are precisely the bank/money-market-fund supervisory powers that give the label content. When supervision is needed to contain a systemic run, it is no longer ordinary software or generic payments oversight; it is prudential regulation of a money-like institution.
[P5.4] CON’s only answer to the broad run is stricter reserve design or access to sovereign money—a narrow bank by another name. The real choice is whether to regulate the institution as what it already is. PRO wins because CON must borrow the bank/MMF model to solve the run.

## Turn 10: CON Closing

- model: gpt-5.6-high
- raw_words: 203
- clipped_words: 203
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO wins only by redefining “bank- or money-market-fund-like” to mean “seriously supervised.” That erases the decisive regulatory question: which risks should determine the rules? Examinations, stress tests, and resolution powers are regulatory methods, not a banking model. Critical payment infrastructures can receive all three without becoming banks or funds.
[C5.2] For a fully reserved stablecoin, the relevant dangers are reserve shortfall, custody failure, redemption outages, and compromised technology. A bespoke payments regime can directly require liquid backing, bankruptcy-remoteness, enforceable redemption, operational resilience, and ongoing supervision. The bank/MMF analogy then adds either nothing or the wrong baggage. If PRO means only those tailored safeguards, it has accepted CON’s framework under a more dramatic label.
[C5.3] If it means the distinctive content of bank or fund regulation—rules and assumptions built around lending, leverage, managed investment shares, and institutional backstops—it mismatches the business model, raises barriers, and still cannot repair code or unfreeze a custodian.
[C5.4] An on-demand redemption promise establishes the need for strong liquidity and redemption rules; it does not establish institutional equivalence. PRO never identified a necessary protection that only the bank/MMF model can supply. CON can deliver every relevant safeguard without regulating nonexistent risks. Regulation should follow the failure mechanism, not the nearest familiar analogy.
