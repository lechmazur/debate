# Debate prop_0022__gpt-5.6-high__gemini-3.1-pro-preview__s1__tpl_placement_active_20260320f

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: gpt-5.6-high
- model_con: gemini-3.1-pro-preview
- side_swap: True

## Turn 1: PRO Opening

- model: gpt-5.6-high
- raw_words: 329
- clipped_words: 329
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A stablecoin may be built with code, but what it sells is a financial promise: give the issuer value today, receive a token represented as stable and redeemable tomorrow. Economically, that resembles a deposit or a money-market share far more than an ordinary software license. Regulation should follow the function and risk of a product, not the vocabulary used to market it.
[P1.2] First, issuers need enforceable rules for reserve quality, liquidity, segregation, disclosure, and redemption. An issuer can promise one-dollar redemption while investing reserves in assets that cannot safely be sold on demand. Once users doubt that promise, rational early redeemers rush for the exit, leaving losses to everyone else. Code audits cannot prevent that mismatch.
[P1.3] Bank- or fund-style safeguards—liquid reserves, independent verification, clear claims in insolvency, and orderly wind-down plans—directly address it.
[P1.4] Second, stablecoins increasingly function as payment and settlement infrastructure. A software outage is inconvenient; failure of a widely used stablecoin can strand payroll, remittances, merchant balances, exchange collateral, and decentralized-finance positions simultaneously. That interconnectedness justifies supervision of custody, cybersecurity, key management, operational resilience, conflicts of interest, and concentration risk. Waiting to punish misconduct after collapse does not restore money to users who believed they held cash-equivalents.
[P1.5] Third, prudential regulation makes issuers internalize risks they otherwise export. Issuers capture reserve earnings and network growth, while customers and the broader financial system absorb the costs of a run, asset fire sales, or frozen redemptions. Minimum capital or loss-absorbing resources appropriately place more of that downside on the business creating it.
[P1.6] “More like banks or money-market funds” does not mean mechanically imposing every bank rule. A fully reserved issuer that makes no loans should face requirements tailored to its narrower activities. But proportionality is not regulatory exceptionalism. The baseline must be financial: protect redemption, preserve reserves, manage runs, and supervise critical operations.
[P1.7] When millions of people are invited to treat a token as money, calling its issuer a software project does not make the promise—or its failure—any less financial.

## Turn 2: CON Opening

- model: gemini-3.1-pro-preview
- raw_words: 301
- clipped_words: 301
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.1], [P1.5], [P1.3]
- missing_claim_id_refs: (none)

[C1.1] PRO bases their case on a flawed analogy: that stablecoins are economically identical to bank deposits or money-market funds [P1.1]. This ignores fundamental mechanical differences that demand a different regulatory approach.
[C1.2] First, bank and MMF regulations exist primarily to manage the risks of maturity transformation. Banks lend long and borrow short; MMFs buy commercial paper for yield. True stablecoins do neither. They are technological routing mechanisms for 1:1 backed digital receipts, holding assets in bankruptcy-remote trusts.
[C1.3] Imposing bank-style prudential regulations—like steep capital requirements [P1.5]—on entities with no loan books mismatches the regulation to the actual risk. It creates massive barriers to entry, shielding legacy monopolies without fundamentally improving consumer protection.
[C1.4] Second, PRO demands traditional "independent verification" [P1.3]. Yet stablecoins are software, and they solve transparency better than banks ever could. Through cryptographic proof-of-reserves and open-source smart contracts, a token's backing can be verified by anyone in real-time, 24/7. We should not force 21st-century open-ledger technology into the opaque, 20th-century paradigm of delayed regulatory exams and self-reported bank audits.
[C1.5] Finally, regulating stablecoins like banks actually *creates* systemic risk. When a major stablecoin temporarily depegged in 2023, it was not because its software failed or its issuer lied. It depegged because its cash reserves were trapped inside a collapsing, heavily regulated traditional bank. Forcing stablecoins to structurally integrate with fractional-reserve banking frameworks imports legacy contagion risks directly into digital assets.
[C1.6] Stablecoin issuers are software developers providing a protocol for peer-to-peer data transfer. Existing fraud statutes, commercial laws, and protocol-level transparency already obligate them to honor the reserves they claim to hold. If an issuer misrepresents its backing, ordinary fraud laws apply perfectly well. Regulating them like ordinary software projects allows for competitive innovation and structural independence, whereas regulating them like banks simply chains them to the very vulnerabilities they were built to bypass.

## Turn 3: PRO Rebuttal 1

- model: gpt-5.6-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.2], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON’s defense works only by assuming away the problem. Its “true stablecoin” is already 1:1 backed and held in a bankruptcy-remote trust [C1.2]. But code does not create bankruptcy remoteness, dictate eligible reserves, prevent liens, or guarantee redemption. Those are legal and prudential arrangements—the very safeguards PRO defends.
[P2.2] If CON needs them to define a legitimate stablecoin, it has conceded that ordinary software regulation is inadequate.
[P2.3] The maturity-transformation response attacks a position we rejected. “More like banks or money-market funds” means regulating the financial function, not giving a fully reserved issuer a bank loan-book rulebook. Even without lending, an issuer faces reserve custody, liquidity, concentration, operational, and insolvency risks. A cash-only model has custodian exposure; a securities-backed model can face price and settlement risk. Proportional requirements can reflect those risks rather than the “steep” burdens imagined by CON.
[P2.4] Proof-of-reserves is useful but incomplete. A ledger can show token issuance and perhaps reserve wallets. It cannot by itself establish ownership of off-chain assets, reveal every liability or encumbrance, confirm custodian access, or determine customers’ priority in bankruptcy. Open-source code can execute redemption only while the issuer and payment rails can deliver money.
[P2.5] Independent verification complements cryptography; it does not replace it.
[P2.6] CON’s 2023 example [C1.5] proves our case. A depeg caused by trapped reserves shows that backing is not enough: custody concentration and immediate availability matter. Our framework does not force issuers into fractional-reserve lending. It requires segregation, diversification, contingency planning, and supervision of precisely that dependency.
[P2.7] Finally, fraud law addresses provable deception after harm. A run can arise from honest liquidity mismatch, custodian failure, cyberattack, or ambiguous insolvency claims. Punishment afterward cannot restore access when users need money. Software rules govern code; stablecoin regulation must govern the assets, legal claims, and redemption promise behind it.

## Turn 4: CON Rebuttal 1

- model: gemini-3.1-pro-preview
- raw_words: 320
- clipped_words: 320
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.3], [P2.6], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] PRO argues that because stablecoin issuers use bankruptcy-remote trusts, they have already conceded the need for bank-like regulation [P2.1]. This conflates standard commercial law with bank supervision. Countless ordinary software platforms—from digital escrow services to ticketing apps—use standard contract law and third-party trusts to isolate client funds. Relying on basic property rights and commercial contracts does not turn a software developer into a bank.
[C2.2] Realizing that bank and MMF regulations are genuinely mismatched for 1:1 backed tokens, PRO tries to retreat from the resolution. They claim they do not actually want standard loan-book rulebooks, just "proportional" rules for custody and liquidity [P2.3]. But the resolution explicitly demands regulating issuers *like banks or money-market funds*. The defining features of those regimes exist to manage maturity transformation—requiring capital buffers, yield restrictions, and systemic insurance to stop fractional-reserve bank runs.
[C2.3] If PRO must abandon the core mechanics of bank regulation to make their framework fit, they are implicitly admitting that the bank and MMF models are fundamentally wrong for stablecoins.
[C2.4] PRO’s attempt to co-opt the 2023 depeg also backfires [P2.6]. They claim bank-style supervision is needed to manage custody concentration. But the custodian that failed in 2023 *was* a heavily regulated traditional bank, repeatedly examined by the exact regulators PRO praises. The crisis was not caused by a lack of stablecoin oversight; it was caused by the failure of the traditional banking system.
[C2.5] Regulating stablecoin issuers like banks only binds them tighter to the legacy contagion they were engineered to bypass.
[C2.6] Finally, PRO dismisses cryptographic transparency because it cannot prove off-chain legal claims [P2.4]. But ordinary software companies already utilize standard financial audits. Combining routine corporate audits with real-time, on-chain proof-of-reserves provides exponentially more transparency than the opaque, delayed quarterly reporting of traditional banks or MMFs. Stablecoin issuers provide peer-to-peer data infrastructure; they should be governed by software and commercial frameworks, not suffocated by the very legacy banking rules that repeatedly fail consumers.

## Turn 5: PRO Pressure Questions

- model: gpt-5.6-high
- raw_words: 65
- clipped_words: 65
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If “routine corporate audits,” bankruptcy-remote trusts, and 1:1 backing are essential to your model, what enforceable regime—other than financial regulation—sets reserve eligibility, checks hidden liabilities, and establishes holders’ priority and prompt redemption?
[P3.2] Q2: Since your 2023 example shows that honestly reported reserves can become inaccessible at a failed custodian, how do fraud law and proof-of-reserves prevent concentration-driven depegs without liquidity, diversification, and contingency requirements?

## Turn 6: CON Pressure Questions

- model: gemini-3.1-pro-preview
- raw_words: 91
- clipped_words: 91
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: If your "proportional" framework requires abandoning the core features of bank and money-market regimes—like capital buffers for loan losses and systemic insurance [P2.3]—aren't you implicitly admitting the resolution is flawed because these legacy regimes are structurally mismatched for 1:1 digital receipts?
[C3.2] Q2: You argue bank-style supervision is needed to prevent custody concentration [P2.6]. But since the 2023 depeg was triggered by the sudden collapse of a highly supervised traditional bank, how does applying those exact same bank regulators to the software layer protect users from the banking system's own failures?

## Turn 7: PRO Rebuttal 2

- model: gpt-5.6-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: No. “More like” is comparative, not a command to copy every rule designed for lending banks. A fully reserved issuer does not need capital calibrated to loan losses, but it may need resources for operational failures, reserve shortfalls, and orderly wind-down, alongside liquidity and redemption rules. Money-market funds are especially relevant because they issue redeemable claims against pooled financial assets without making bank loans. Tailoring a financial regime to the activity is not abandoning that regime; ordinary software oversight supplies none of these protections.
[P4.2] A2: Regulation protects users by supervising the issuer’s exposure to custodians, not by guaranteeing that no bank will ever fail. Diversified custody, readily available reserve assets, backup payment channels, and contingency plans mean one custodian’s collapse need not freeze all redemptions. The premise that this requires “the exact same regulators” is also false: the proposition concerns the type of regulation, not a particular agency. A supervised bank’s failure shows that supervision is imperfect; it does not show that leaving concentrated exposure unmanaged is safer.
[P4.3] Indeed, the depeg demonstrates that nominal backing and transparent code cannot ensure timely access.
[P4.4] That exposes CON’s false choice between importing every legacy banking rule and treating issuers as software. CON’s preferred model already depends on 1:1 backing, trusts, and audits. Yet it never identifies who enforceably defines eligible reserves, checks liabilities and encumbrances, guarantees holder priority, or requires prompt redemption. A corporate audit can describe arrangements; it does not itself establish those safeguards.
[P4.5] Proof-of-reserves can display assets; it cannot make inaccessible assets liquid.
[P4.6] The decisive comparison is therefore ex ante financial protection versus ex post fraud enforcement. Fraud law works only when deception can be proven. It does nothing about an honest custodian failure, liquidity blockage, cyber incident, or ambiguous bankruptcy claim. PRO directly regulates the redemption promise while preserving proportionality for narrow issuers.
[P4.7] CON leaves the promise’s most important components outside software regulation and asks users to discover the gap during a run. When a product is marketed as stable money, that is the wrong side of the [clipped]

## Turn 8: CON Rebuttal 2

- model: gemini-3.1-pro-preview
- raw_words: 317
- clipped_words: 317
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.6]
- missing_claim_id_refs: (none)

[C4.1] A1: Standard commercial and contract law. Escrow services, payment gateways, and ordinary software platforms route billions daily using binding terms of service and standard property rights. These frameworks legally dictate asset eligibility, prohibit hidden liens, and establish strict bankruptcy priority for users without transforming a software developer into a bank or money-market fund.
[C4.2] A2: Real-time transparency and market discipline resolve concentration far better than static financial regulations. Because stablecoin mechanics are auditable, the market immediately identified the 2023 risk. Users reacted instantly, forcing the software issuer to aggressively diversify its banking relationships to survive. Proof-of-reserves empowers the market to demand contingency planning in real time, whereas bank regulators completely failed to prevent the underlying custodian's collapse.
[C4.3] PRO’s defense now relies on a massive definitional retreat. By admitting that a fully reserved stablecoin "does not need capital calibrated to loan losses" [P4.1], PRO essentially concedes that the defining pillars of bank regulation are structurally mismatched for digital receipts. They want the perceived safety of bank regulation without the actual bank rulebook.
[C4.4] But the resolution is explicit: it asks if issuers should be regulated *like banks or money-market funds*. Banks lend deposits; MMFs buy commercial paper for yield. Both engage in maturity transformation, requiring heavy capital buffers and systemic insurance to prevent runs. True stablecoins do neither; they are peer-to-peer data infrastructure.
[C4.5] PRO insists that bank-style ex ante regulation is the only way to protect consumers [P4.6]. Yet imposing bank or MMF frameworks actively harms consumers by forcing software protocols into a rigid legacy mold, erecting massive compliance barriers that entrench monopolies, and chaining digital assets to the exact traditional banking system that triggered the 2023 crisis.
[C4.6] Ordinary software projects routinely use strict commercial contracts, independent corporate audits, and property law to protect client assets. By pairing these proven legal standards with 24/7 cryptographic transparency, we deliver superior, real-time consumer protection without importing the systemic contagion of traditional finance.

## Turn 9: PRO Closing

- model: gpt-5.6-high
- raw_words: 214
- clipped_words: 214
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The ballot turns on one question: what is the issuer actually promising? Not merely that code will execute, but that a money-like claim will remain redeemable on demand. The decisive risks therefore sit behind the code—in reserve ownership, liquidity, custody, insolvency priority, and redemption. CON leaves that financial promise to private contracts and reaction after danger appears.
[P5.2] Commercial law may enforce the terms an issuer writes; it does not set adequate minimum terms. Users cannot negotiate reserve eligibility or contingency plans. Nor is market discipline a substitute. CON celebrates users reacting instantly to custodian risk, but that reaction is the run itself, not protection from it.
[P5.3] Proof-of-reserves may reveal concentration; it cannot diversify custody or release trapped funds. A race to exit rewards the fastest and exposes everyone else. Ex ante segregation, liquidity, verification, and contingency requirements prevent that race from becoming the regulatory system.
[P5.4] CON’s “definitional retreat” objection fails because the proposition says “more like,” not “identically to.” Tailoring rules to a fully reserved issuer is exactly what risk-based financial regulation does. Banks and money-market funds provide the relevant model because they are supervised around redeemable financial claims; ordinary software projects are not.
[P5.5] When stability depends on assets, legal rights, and redemption—not code alone—the regulator must govern the promise, not merely the program.

## Turn 10: CON Closing

- model: gemini-3.1-pro-preview
- raw_words: 196
- clipped_words: 196
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s case rests on a framework they had to dismantle to defend. They claim stablecoins must be regulated "more like banks or money-market funds," yet spend this debate stripping away the defining features of those very regimes to make them fit. When you remove the capital buffers, yield restrictions, and systemic insurance designed for maturity transformation, you are no longer regulating something "like a bank." You are proving our exact point: legacy financial frameworks are structurally mismatched for 1:1 digital receipts.
[C5.2] The debate comes down to which model actually aligns with the risk. True stablecoins are peer-to-peer data infrastructure. Their risks are custodial, not fractional. Ordinary software platforms—like digital escrow services—secure billions daily using standard property rights, binding commercial contracts, and bankruptcy-remote trusts.
[C5.3] When paired with 24/7 cryptographic proof-of-reserves, this software model provides superior protection. PRO’s alternative actively creates systemic risk. By forcing digital assets into bank or MMF molds, PRO chains 21st-century technology to the opaque, traditional banking system—the exact system whose own failure triggered the 2023 depeg.
[C5.4] Regulating stablecoin issuers like ordinary software projects embraces transparent innovation, whereas regulating them like banks simply traps them in the legacy contagion they were engineered to bypass.
