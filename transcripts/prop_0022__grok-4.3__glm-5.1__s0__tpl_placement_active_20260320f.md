# Debate prop_0022__grok-4.3__glm-5.1__s0__tpl_placement_active_20260320f

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: grok-4.3
- model_con: glm-5.1
- side_swap: False

## Turn 1: PRO Opening

- model: grok-4.3
- raw_words: 300
- clipped_words: 300
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Stablecoin issuers manage funds that users treat as a stable medium of exchange and store of value. They take in deposits, publish commitments to maintain parity with the dollar or other assets, and provide redemption channels. This structure replicates the essential characteristics of bank deposits and money-market fund shares, where the value of liabilities depends on the soundness of the assets backing them. The technological delivery method does not change the fact that a run can force rapid liquidation and losses.
[P1.2] Software projects do not solicit or hold customer balances with an expectation of fixed redemption. They produce code that operates independently of any guarantee about external value. Stablecoin operations, by contrast, center on the preservation of nominal value. When reserves prove inadequate or illiquid, as occurred during the collapse of algorithmic stablecoins in 2022, the damage falls directly on users who had no reason to anticipate a software-like failure mode.
[P1.3] Holders in those cases expected bank-like stability, not the volatility associated with software products.
[P1.4] Banks and money-market funds operate under rules governing asset eligibility, liquidity ratios, and regular reporting because their products support payments and short-term funding markets. Stablecoin issuers occupy a similar position today. Volumes processed through major stablecoins reach significant fractions of certain payment flows, and their tokens serve as collateral across decentralized platforms. Absent parallel standards for reserve quality and auditability, issuers benefit from monetary-like utility while remaining free of the constraints that limit risk-taking in regulated deposit-taking entities.
[P1.5] Regulation should track the risk profile created by the activity rather than the form of the provider. When an entity issues instruments that circulate as money, it must meet the prudential standards that protect the public in comparable cases. This approach prevents the externalization of risk that arises when monetary functions escape the oversight designed for them.

## Turn 2: CON Opening

- model: glm-5.1
- raw_words: 314
- clipped_words: 314
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Stablecoin issuers are not banks, and treating them as such would import a regulatory framework built for fundamentally different risk profiles. The proposition collapses a critical distinction: banks accept demand deposits and lend them out, creating maturity transformation and credit risk. Stablecoin issuers hold reserves; they do not originate loans. Money-market funds take duration risk in pursuit of yield.
[C1.2] Fully-reserved stablecoins do neither. The activity matters, and so does the mechanism.
[C1.3] When USDC depegged briefly in 2023 after Silicon Valley Bank failed, it recovered within days because the reserves existed and were redeemable. The problem wasn't the stablecoin structure—it was the banking system's own fragility that briefly infected the reserve holder. Regulating the stablecoin like a bank would not have prevented SVB's collapse; it would have merely layered redundant compliance costs onto an entity that was already doing exactly what regulators should want: holding liquid, high-quality assets one-to-one against liabilities.
[C1.4] The real danger of bank-style regulation is regulatory capture disguised as consumer protection. Capital requirements, lending restrictions, and FDIC insurance exist because banks take risks that stablecoin issuors, properly structured, do not. Imposing these frameworks creates compliance costs that only large incumbents can absorb, entrenching dominant players while locking out smaller, more transparent alternatives. This does not protect users; it protects incumbents from competition.
[C1.5] Software-style regulation—focused on disclosure, auditability, and operational resilience—matches the actual risk. Users need to verify that reserves match claims. They need smart-contract security and redemption guarantees. They do not need capital adequacy ratios for lending operations that do not exist.
[C1.6] The 2022 algorithmic collapses cited by PRO prove the opposite of what is claimed: those failures came from structures mimicking central-bank monetary policy without reserves, not from software-style issuance with transparent backing. The right lesson is to distinguish genuinely reserved stablecoins from unbacked experiments, not to lump all of them under banking rules that address risks they do not create.

## Turn 3: PRO Rebuttal 1

- model: grok-4.3
- raw_words: 319
- clipped_words: 319
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The claim that stablecoin issuers avoid bank-like risks simply because they do not lend deposits misstates the relevant exposure. The core threat is not credit creation but the need to meet simultaneous redemptions from assets that may prove less liquid or less certain than claimed. Money-market funds face the same redemption pressure without originating loans, which is why they are already subject to liquidity and asset-quality rules. Treating the distinction as decisive ignores that users hold stablecoins for immediate exchange and value preservation, not for code inspection.
[P2.2] The USDC episode illustrates rather than refutes the point. Brief depegging occurred precisely because reserves sat at a single bank that failed, forcing reliance on that institution's solvency and access. Rapid recovery depended on external interventions and remaining buffer, not on any inherent software safeguard. Regulation that focuses on where reserves are held, what instruments qualify, and how often independent verification occurs would directly address this single-point vulnerability instead of hoping market discipline substitutes for it.
[P2.3] Disclosure and smart-contract audits, the proposed software alternative, leave the composition and custody of reserves under issuer control between audit dates. Nothing in ordinary software oversight prevents an issuer from shifting into less liquid commercial paper or concentrating at one custodian, provided those moves are later reported. When users treat the token as cash, such gaps create externalized losses that surface only during stress, exactly the pattern that banking and money-market rules were designed to constrain.
[P2.4] Arguments about compliance costs favoring incumbents overlook that unregulated status already allows scale without equivalent transparency, letting large issuers absorb reserves through existing banking relationships while smaller entrants face skepticism. Proportionate prudential standards would raise baseline requirements for all, reducing the advantage that currently flows to those able to obscure reserve details. The economic function of issuing redeemable liabilities at fixed nominal value aligns with deposit or fund activities, so oversight should follow that function rather than the delivery method.

## Turn 4: CON Rebuttal 1

- model: glm-5.1
- raw_words: 293
- clipped_words: 293
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] The money-market fund comparison collapses on inspection. Money-market funds take duration and credit risk in pursuit of yield—that is why they need liquidity gates and asset-quality rules. Fully-reserved stablecoins holding cash and short-term Treasuries pursue neither. The risk profile is fundamentally different, and PRO's insistence that "redemption pressure" alone makes them equivalent would also sweep in prepaid card issuers and gift-card programs.
[C2.2] When the mechanism matters, the regulation must track it.
[C2.3] PRO concedes the key point about USDC: the reserves existed and were redeemable, enabling rapid recovery. The failure was in the banking system, not the stablecoin structure. Bank-style capital requirements would not have prevented SVB's collapse. Liquidity rules governing where reserves can be held and what assets qualify sound reasonable in the abstract, but these are disclosure and custody standards—exactly the software-style oversight I advocate.
[C2.4] PRO is smuggling ordinary transparency requirements into "banking regulation" and claiming them as evidence for the proposition, when they belong to the framework I already proposed.
[C2.5] The claim that software regulation permits dangerous shifts between audits ignores reality. On-chain reserve attestation offers continuous, machine-readable verification that banking examinations could never match. Traditional banks face weeks between regulatory examinations; stablecoins can publish proof-of-reserves daily or hourly. The transparency problem PRO identifies is actually solved more effectively by the tools of software regulation than by periodic supervisory review.
[C2.6] On competitive effects, "proportionate prudential standards" sound reasonable until you examine what banking regulation actually entails: chartering requirements, capital adequacy ratios designed for lending risk, FDIC insurance premiums. These are not modular add-ons; they form an integrated framework built around maturity transformation and credit creation—activities stablecoin issuers do not perform. Imposing this architecture on entities that hold liquid reserves one-to-one is not proportionate; it is category error dressed in regulatory language.

## Turn 5: PRO Pressure Questions

- model: grok-4.3
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If daily on-chain attestations already provide superior, continuous transparency, why did USDC still depeg when its reserves were concentrated at one failing bank, and what enforcement tool under pure software rules would have forced diversification before the event?
[P3.2] Q2: Since you agree reserve location and quality rules are needed, where exactly does the "software framework" end and the bank-style constraints on custodians and eligible assets begin without becoming the proportionate prudential oversight the motion requires?

## Turn 6: CON Pressure Questions

- model: glm-5.1
- raw_words: 59
- clipped_words: 59
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Which specific banking regulation—capital adequacy, lending restrictions, or FDIC insurance—would have prevented SVB's failure and thus the USDC depeg, and why impose rules designed for lending risk on entities that don't lend?
[C3.2] Q2: If redemption pressure and reserve management alone justify bank-style regulation, why doesn't PRO's logic also require treating prepaid card issuers and escrow services as banks?

## Turn 7: PRO Rebuttal 2

- model: grok-4.3
- raw_words: 302
- clipped_words: 302
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: None of the listed banking regulations applied directly to stablecoin issuers would have prevented SVB's failure itself. Capital adequacy rules address lending risks, which these issuers lack. Yet rules on reserve asset quality and diversification, similar to money-market fund standards, would have prohibited heavy concentration at one bank and required higher-quality liquid holdings, avoiding the depeg trigger. The motion does not demand full lending restrictions; it calls for analogous treatment of the shared redemption risk.
[P4.2] A2: Prepaid card and escrow services operate at smaller scale without issuing widely circulating instruments that underpin decentralized finance and serve as settlement assets. Their users do not expect systemic stability or face the collateral cascade effects of a stablecoin run, so they do not create equivalent external risks warranting the same prudential framework.
[P4.3] These answers show why the software framework cannot substitute for bank-like or money-market standards on reserve management. Users treat these tokens as reliable cash equivalents rather than variable software outputs, generating the same need for safeguards against illiquidity that money-market rules address. Attestations reveal positions but offer no enforcement against concentrating reserves at risky custodians until a failure occurs, as with USDC. Prudential rules modeled on those for redeemable liabilities would mandate diversified holdings and eligible assets in advance, preventing the transmission of bank fragility to stablecoin users.
[P4.4] This demonstrates that redemption pressure creates a distinct regulatory need that disclosure alone does not meet. Treating stablecoins like software ignores that users rely on nominal stability for payments and collateral, not code properties. The distinction from prepaid cards holds because only stablecoins embed into broader financial ecosystems at volumes that amplify runs into systemic concerns. Therefore, regulation must match the monetary character of the activity, supporting the proposition that stablecoin issuers warrant oversight closer to traditional financial intermediaries than to pure technology projects.

## Turn 8: CON Rebuttal 2

- model: glm-5.1
- raw_words: 289
- clipped_words: 289
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: USDC depegged because of a banking system failure, not because its transparency framework was inadequate. The concentration at SVB was publicly known—on-chain attestation and reserve reports already disclosed the custodial arrangement. The problem wasn't hidden information; it was that no rule forced diversification. Software-style regulation can and should include custodial diversification requirements as a governance standard, just as data-center redundancy rules are software regulations, not bank regulations.
[C4.2] You don't need a capital adequacy ratio or FDIC insurance to mandate that an issuer diversify custodians.
[C4.3] A2: The boundary is straightforward: software regulation governs what the system must disclose, how reserves must be verified, and what operational resilience—including custodial diversification—is required. Bank-style regulation governs capital adequacy, lending activity, deposit insurance, and chartering—tools designed for maturity transformation and credit creation. Requiring diversified custody and high-quality reserve assets is a transparency and governance requirement perfectly suited to a software framework. PRO keeps smuggling these reasonable obligations into "banking regulation" because banking law happens to include them alongside its core lending-focused apparatus.
[C4.4] But the motion says "more like banks than like software projects"—that comparison implicates the whole framework, not just the narrow slice that overlaps with disclosure.
[C4.5] This is why CON wins. PRO's strongest examples—diversification rules, asset-quality requirements—belong to the software-style framework I've advocated from the start. PRO has never justified capital adequacy ratios, lending restrictions, or deposit insurance for entities that don't lend. Instead, PRO retreats to the subset of rules that overlap with disclosure and custody governance, then claims this proves the banking label fits.
[C4.6] But regulatory categories carry entire architectures. Banking regulation isn't a menu; it's an integrated system built around credit creation. Imposing it on entities holding liquid reserves one-to-one entrenches incumbents without addressing risks these issuers don't create.

## Turn 9: PRO Closing

- model: grok-4.3
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive difference lies in timing. Stablecoin issuers create liabilities that users can and do redeem on demand at par, exactly as banks and money-market funds do. That structure produces the same incentive to run when confidence falters, and the same need for rules that lock in asset quality and diversification before any stress materializes.
[P5.2] On-chain attestations and post-event disclosure cannot substitute. They reveal what an issuer chose to hold, but they do not constrain the choice itself. USDC’s concentration at a single failing bank was visible yet still occurred; only an enforceable requirement on eligible custodians and liquid assets would have barred it in advance. Software-style oversight can verify after the fact; it cannot prevent the concentration that turns a solvent reserve pool into a redemption trigger.
[P5.3] CON’s claim that such requirements belong to a lighter software framework therefore misplaces the regulatory function. Rules that force prudent reserve management up front are not optional transparency add-ons. They are the core prudential discipline that follows once an entity offers circulating claims on fixed nominal value. Treating the same activity as ordinary software leaves that discipline discretionary, exposing users to losses that the bank and money-market template was built to avoid.

## Turn 10: CON Closing

- model: glm-5.1
- raw_words: 203
- clipped_words: 203
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's entire case has retreated to a single slice of banking regulation—reservequality and diversification rules—and then claimed thisjustifies treating stablecoins "more like banks." But diversification requirements arenot uniquely banking rules. Software regulation routinely mandates redundancy, operational resilience, and custody standards as enforceable, upfront conditions, not optional disclosures.
[C5.2] What PRO has never justified is the rest of the banking architecture: capital adequacy ratios designed for lending risk, deposit insurance premiums for institutions that create money through fractional reserves, and chartering requirements for entities that originate credit. These exist because banks transform maturities and take credit risk—activities stablecoin issuers, properly structured, do not perform.
[C5.3] That is the category error at the heart of this debate. The motion asks whether stablecoin issuers should be regulated more like banks than like software. PRO's strongest examples prove the opposite: the specific protections users need—verified reserves, custodial diversification, asset eligibility standards—are governance requirements that fit naturally within a software framework. Importing banking's core apparatus for risks that don't exist entrenches incumbents and misallocates regulatory attention.
[C5.4] The activity determines the regulation. Holding liquid reserves one-to-one against redeemable liabilities is not banking. It demands transparency, verification, and operational resilience—exactly what software regulation delivers without the dead weight of lending-focused prudential architecture.
