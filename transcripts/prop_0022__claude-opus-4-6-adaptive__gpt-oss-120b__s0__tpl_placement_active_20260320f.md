# Debate prop_0022__claude-opus-4-6-adaptive__gpt-oss-120b__s0__tpl_placement_active_20260320f

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: claude-opus-4-6-adaptive
- model_con: gpt-oss-120b
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-4-6-adaptive
- raw_words: 350
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When someone deposits a dollar into a stablecoin, they believe they can get that dollar back. That belief is the entire product. It is not a belief about code elegance or decentralization philosophy—it is a belief about redemption at par, which is precisely the promise that banking and money-market fund regulation exists to govern.
[P1.2] The core argument is simple: stablecoins perform the economic function of deposit-taking and short-term money claims. Regulation should follow function, not form. A stablecoin issuer that holds tens of billions in reserves, promises one-to-one redemption, and serves as a payment rail is doing exactly what a narrow bank or money-market fund does. Calling it a "software project" does not change what breaks when it fails.
[P1.3] Consider what happened when TerraUSD collapsed in 2022. Roughly forty billion dollars in value evaporated in days, dragging down connected lending platforms and wiping out retail holders who treated UST as a savings vehicle. There was no deposit insurance, no reserve transparency requirement, no orderly wind-down mechanism. The damage resembled a bank run in every economically meaningful sense—except no regulator had the tools to intervene or even inspect the reserves beforehand.
[P1.4] Even well-collateralized stablecoins present systemic concerns. Tether has repeatedly faced questions about the composition and liquidity of its reserves. When a single entity holds massive positions in commercial paper or Treasury bills to back a token used globally for payments and trading, its portfolio decisions ripple through short-term funding markets. Money-market funds learned this lesson in 2008 when the Reserve Primary Fund broke the buck and triggered a broader panic—leading directly to tighter SEC rules on liquidity, transparency, and redemption gates.
[P1.5] Stablecoins sit in the same risk space but face none of those guardrails.
[P1.6] Bank-like regulation means reserve requirements, audited disclosures, capital buffers, and redemption procedures. These are not arbitrary burdens; they are the proven architecture for institutions that promise "your dollar is safe here." The alternative—treating issuers as ordinary software projects—leaves billions of consumer dollars protected by nothing more than a whitepaper and a terms-of-service page.
[P1.7] Function dictates [clipped]

## Turn 2: CON Opening

- model: gpt-oss-120b
- raw_words: 332
- clipped_words: 332
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Stablecoins are fundamentally contracts, not deposits. When a user buys a token they receive a promise that the issuer will exchange the token for a dollar‑denominated asset; they do not acquire a creditor claim on a regulated institution in the way a bank customer does. This distinction matters because the principal dangers that bank and money‑market‑fund regulation address—maturity transformation, credit risk, and unchecked leverage—are simply not present in a well‑designed, fully‑collateralised stablecoin. The token itself cannot be “run” in the traditional sense; the issuer’s liability is limited to delivering the underlying reserve, which is already held in liquid, low‑risk assets such as cash or sovereign bonds.
[C1.2] Imposing reserve‑ratio caps, capital‑buffer tests, and stress‑scenario reporting designed for balance‑sheet institutions therefore adds layers of compliance that do not correspond to any genuine source of fragility.
[C1.3] Treating stablecoins like banks also ignores their technological architecture. Risk resides in smart‑contract code, custody arrangements, and governance mechanisms, not in the sort of credit‑exposure calculations that drive Basel III. A bank‑style regulator lacks the tools to audit immutable code or to evaluate the security of multi‑signature custodial wallets. Over‑regulating through banking prudential rules forces issuers to divert scarce resources toward irrelevant reporting, stifling the rapid innovation that makes stablecoins attractive for low‑cost cross‑border payments and decentralized finance.
[C1.4] Moreover, heavy‑handed bank regulation would create a costly competitive imbalance. Traditional deposit‑taking firms would face stringent capital and liquidity mandates, while crypto‑native firms could claim exemption by arguing they are merely “software projects.” This regulatory arbitrage would push stablecoin activity into jurisdictions with looser oversight, reducing transparency and undermining the very consumer protection the proposition seeks to achieve.
[C1.5] Finally, the systemic footprint of stablecoins remains modest compared with the broader banking sector. Targeted rules—such as custody‑risk disclosures, audit requirements, and AML/KYC obligations—address the real vulnerabilities without burdening issuers with the heavyweight edifice of bank or money‑market‑fund supervision. By keeping regulation proportional to the actual risk profile, we preserve financial inclusion, encourage competition, and maintain stability more effectively than blanket banking‑style oversight.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-4-6-adaptive
- raw_words: 388
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.1], [C1.3], [C1.4], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] The distinction between "contracts" and "deposits" in [C1.1] is precisely the kind of formalism that lets real harm slip through. A retail user holding USDT on their phone to store savings does not experience it as a contract—they experience it as a dollar balance. The economic exposure is identical to a deposit: counterparty risk on a single institution's promise to redeem at par. Calling it a contract rather than a deposit is a legal label, not a risk analysis.
[P2.2] CON claims that well-designed, fully-collateralized stablecoins cannot be "run." But this assumes the conclusion. The entire problem is that without bank-like regulation, we have no reliable mechanism to verify that reserves are fully collateralized, liquid, and accessible under stress. Tether spent years claiming full backing while holding significant commercial paper.
[P2.3] TerraUSD was marketed as stable while relying on an algorithmic mechanism with no real reserves at all. The phrase "well-designed, fully-collateralised" is doing enormous work in CON's argument—and it describes precisely the outcome that regulation is supposed to guarantee, not a baseline we can assume.
[P2.4] The claim in [C1.3] that bank regulators cannot audit smart contracts is a non-sequitur. Nobody is proposing that the Federal Reserve review Solidity code. The proposition is about reserve adequacy, liquidity management, and redemption guarantees—areas where financial regulators have deep expertise. Smart-contract risk is additive; it does not replace the financial risks that already exist.
[P2.5] You still need someone verifying that the dollars are actually there.
[P2.6] The regulatory-arbitrage argument in [C1.4] actually cuts against CON. If light-touch rules let issuers flee to permissive jurisdictions, that is an argument for coordinated, robust standards—not for keeping regulation weak everywhere. We do not let banks dodge capital requirements by incorporating offshore; the same logic applies here.
[P2.7] Finally, CON's suggestion in [C1.5] that "targeted rules" like custody disclosures and audits suffice is quietly conceding the principle. Mandatory audits, custody requirements, and redemption transparency are core components of money-market fund regulation. The question is not whether to regulate but whether the framework should be coherent and enforceable. Piecemeal "targeted" rules [clipped]

## Turn 4: CON Rebuttal 1

- model: gpt-oss-120b
- raw_words: 418
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO argues that users “feel” a stablecoin balance like a bank deposit, so the legal label is irrelevant. Yet the practical distinction determines the legal remedy. A contract gives the holder a claim against a specific reserve pool that can be independently verified, while a deposit creates a creditor‑debtor relationship subject to blanket insurance schemes and bail‑in powers. If a stablecoin fails, the claim can be settled by a simple audit of the reserve ledger, avoiding costly liquidation of a whole banking balance sheet.
[C2.2] Treating the same exposure as a deposit merely inflates the perceived systemic danger and justifies unnecessary regulatory heft.
[C2.3] PRO worries that without bank‑like supervision we cannot confirm full collateralisation, citing Tether’s opaque commercial‑paper holdings. The answer is not more Basel‑style ratios but real‑time, cryptographically provable reserve attestations. Many issuers already publish Merkle‑root proofs that can be audited instantly by any market participant. A lightweight regulator equipped with standard audit tools can verify those proofs far more efficiently than a regulator forced to inspect balance‑sheet items, loan portfolios, and capital buffers that simply do not exist in a collateral‑backed token.
[C2.4] The TerraUSD episode is used as a strawman. Terra was algorithmic, not collateralised, and its collapse illustrates why the *type* of stablecoin matters, not why every stablecoin should be shackled to banking rules. Robust design—full reserve backing, diversified liquid assets, and transparent custodial accounts—removes the very risk Terra created. Imposing bank‑like liquidity coverage ratios on a token already holding cash and sovereign bonds adds no safety but creates absurd duplication: the same liquidity is already testable on‑chain.
[C2.5] PRO claims regulators have “deep expertise” in reserve adequacy and that smart‑contract risk is merely additive. The expertise is of limited value when the entity under supervision lacks a traditional balance sheet. Requiring banks to file quarterly capital adequacy reports on a pool of Treasury bills that already trade on transparent markets is redundant and diverts resources from genuine innovation.
[C2.6] On regulatory arbitrage, the solution is not blanket banking supervision but coordinated *principle‑based* standards—mandatory third‑party audits, real‑time proof‑of‑reserves, and [clipped]

## Turn 5: PRO Pressure Questions

- model: claude-opus-4-6-adaptive
- raw_words: 93
- clipped_words: 93
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.4], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON's case in [C2.4] dismisses TerraUSD as irrelevant because it was algorithmic rather than collateralized—but under CON's preferred "targeted rules" framework, what specific mechanism would have prevented Terra from marketing itself as a stable dollar-equivalent to retail users before forty billion dollars vanished?
[P3.2] Q2: CON champions Merkle-root proofs and real-time reserve attestations in [C2.3], but most stablecoin reserves sit in off-chain bank accounts and Treasury holdings, not on-chain. How does a cryptographic proof verify that off-chain assets are unencumbered, liquid, and not double-pledged—without the kind of regulatory inspection authority CON calls unnecessary?

## Turn 6: CON Pressure Questions

- model: gpt-oss-120b
- raw_words: 106
- clipped_words: 106
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: You assert that bank‑style regulation will ensure reserve adequacy, yet you have not explained how a traditional banking regulator could inspect or enforce liquidity requirements on a stablecoin whose reserves are held in multiple, potentially offshore, custodial structures without a single legal entity—what concrete enforcement mechanism do you propose?
[C3.2] Q2: Your systemic‑risk claim treats stablecoins as comparable to banks, but they represent a tiny share of total deposits. On what quantitative threshold or risk metric would you trigger full bank‑like oversight, and why should regulators impose the same heavy‑handed rules on a sector that currently impacts less than 0.5 % of the overall financial system?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-4-6-adaptive
- raw_words: 350
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The enforcement mechanism is the same one that already governs money-market funds and bank holding companies with complex subsidiary structures: licensing conditioned on a single accountable legal entity within a jurisdiction that has examination authority. If you want to issue a dollar-redeemable token to U.S. users, you must charter or register a U.S. entity, submit to periodic examinations, and grant regulators access to custodial accounts—including offshore ones—as a condition of the license. This is not hypothetical; it is how the SEC oversees money-market funds with assets held across multiple custodians globally.
[P4.2] The multi-entity, multi-jurisdiction complexity CON raises is not a reason regulation cannot work—it is a reason self-attestation alone is insufficient.
[P4.3] A2: The "tiny share" framing misses how systemic risk actually propagates. The Reserve Primary Fund held roughly sixty billion dollars when it broke the buck in 2008—a fraction of total money-market assets—yet its failure triggered a system-wide panic requiring emergency government guarantees across the entire sector. Tether alone now backs well over a hundred billion dollars in tokens used as settlement rails across crypto markets and increasingly in cross-border payments. The threshold for systemic relevance is not percentage of all deposits; it is interconnectedness and the potential for contagion.
[P4.4] Waiting until stablecoins are five or ten percent of the financial system before applying prudential rules means regulating after the crisis, which is exactly the pattern that made 2008 so costly.
[P4.5] These answers converge on the decisive point in this debate. CON's entire framework depends on trusting issuers to be transparent and well-designed by default, then layering on lightweight verification after the fact. But every historical example—Terra, Tether's years of opacity, the Reserve Primary Fund—shows that the market cannot self-certify safety. Merkle-root proofs cannot reach off-chain bank accounts.
[P4.6] "Targeted rules" without licensing authority cannot prevent an algorithmic token from calling itself stable. Real-time attestations without examination power cannot detect encumbered or double-pledged assets.
[P4.7] Bank-like regulation supplies what CON's framework structurally lacks: the authority to look before things break, not just the tools to measure the wreckage afterward. That [clipped]

## Turn 8: CON Rebuttal 2

- model: gpt-oss-120b
- raw_words: 376
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The simple safeguard that would have stopped Terra from posing as a dollar‑stable token is a **pre‑issuance certification regime**. Under CON’s targeted‑rules framework, any entity that wishes to market a token as “fully collateralised” must first obtain an independent audit confirming that a specific, segregated reserve account holds liquid, unencumbered assets equal to the issued supply. The audit report is then cryptographically anchored on‑chain (e.g., a signed Merkle‑root hash) and must be refreshed at a short‑interval cadence. Without that certified attestation, regulators would prohibit the use of “stable” descriptors in consumer‑facing material.
[C4.2] Terra, which relied on an algorithmic peg and offered no such third‑party certification, would have been barred from presenting itself as a dollar‑equivalent token, eliminating the marketing hook that attracted $40 bn of retail capital.
[C4.3] A2: Off‑chain reserves can be verified without a full‑scale banking exam by **binding custodial attestations to on‑chain proofs**. A qualified custodian (a regulated bank or trust company) signs a statement that the assets it holds for the issuer are liquid, unencumbered, and fully available. That statement includes a unique serial number and a hash of the underlying ledger entries. The issuer then publishes the hash on the token’s smart‑contract, creating an immutable link between the on‑chain proof and the off‑chain audit.
[C4.4] Any market participant—or a lightweight regulator—can retrieve the custodian’s signed document, verify the signature, and confirm that the assets backing the tokens match the on‑chain claim. Should a custodian later double‑pledge assets, the mismatch would be exposed instantly when the hash is recomputed, triggering revocation of the issuer’s license. Thus, cryptographic proof plus legally enforceable custodial signatures supply the confidence regulators need without imposing the heavy‑handed Basel‑type supervision CON opposes.
[C4.5] Even with these mechanisms, CON’s approach remains superior. It delivers **effective pre‑emptive transparency** and **enforcement leverage** while preserving the lightweight, innovation‑friendly architecture that makes stablecoins valuable for cross‑border payments and DeFi. Full bank‑style capital ratios, stress‑testing of balance‑sheet items that simply do not exist, and the attendant compliance burden would choke the nascent market, drive issuers to opaque jurisdictions, and [clipped]

## Turn 9: PRO Closing

- model: claude-opus-4-6-adaptive
- raw_words: 206
- clipped_words: 206
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Listen carefully to what CON actually proposed in this debate's final rounds. To stop the next Terra, they want pre-issuance certification, mandatory independent audits, prohibitions on misleading marketing, and the power to revoke licenses. To verify off-chain reserves, they want legally binding custodial attestations, regulatory authority to enforce them, and automatic license revocation when mismatches appear. They want short-interval audit cadences, segregated reserve accounts, and qualified custodians.
[P5.2] That is not a lightweight alternative to bank-like regulation. That *is* bank-like regulation—licensing, examination authority, enforceable reserve requirements, and the power to shut down non-compliant issuers. CON has spent this debate opposing the label while quietly building the same edifice under a different name.
[P5.3] The honest question was never whether stablecoin issuers need robust prudential oversight. It was whether we should call it what it is and house it in proven institutional frameworks, or pretend that novel terminology and cryptographic hashes make the underlying regulatory architecture somehow different.
[P5.4] Every time CON confronted a concrete failure—Terra's deception, Tether's opacity, the impossibility of verifying off-chain assets without inspection authority—they reached for tools that already exist in banking and money-market-fund supervision. They just refused to say so.
[P5.5] The proposition wins because even its opponents cannot argue against it without proving it true.

## Turn 10: CON Closing

- model: gpt-oss-120b
- raw_words: 172
- clipped_words: 172
- claim_ids: [C5.1], [C5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The debate hinges on one decisive fact: stablecoins do not create the balance‑sheet fragilities that bank‑type prudential rules are designed to contain, so imposing those rules merely cripples the very function that makes stablecoins valuable. Their risk lives in the custody of liquid, off‑chain assets and in the correctness of immutable code—not in maturity‑transformation or leverage. A lightweight regime of real‑time, cryptographically verifiable reserve attestations, mandatory third‑party audits and custodial signatures can guarantee that every token is fully backed, while allowing issuers to innovate, keep costs low and serve cross‑border users.
[C5.2] By contrast, banking‑style capital ratios, liquidity‑coverage tests and stress‑scenario reporting force issuers to allocate vast resources to compliance that offers no additional safety; they push firms into jurisdictions with weaker oversight, amplifying opacity—the opposite of the stability the proposition seeks. Hence, the only rational path to consumer protection and systemic resilience is to regulate stablecoins on the terms of their actual risk profile, not to shoe‑horn them into a banking framework. That proportional, technology‑focused oversight is why CON’s position inevitably prevails.
