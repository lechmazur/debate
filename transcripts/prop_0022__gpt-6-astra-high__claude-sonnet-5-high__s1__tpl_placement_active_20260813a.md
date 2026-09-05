# Debate prop_0022__gpt-6-astra-high__claude-sonnet-5-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: gpt-6-astra-high
- model_con: claude-sonnet-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: gpt-6-astra-high
- raw_words: 319
- clipped_words: 319
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A stablecoin issuer is not merely publishing code. It is offering something people are supposed to treat as money. When customers exchange dollars for tokens redeemable at a stable value, the critical questions are financial: Where are the reserves? Can customers redeem?
[P1.2] Who absorbs losses? Calling the interface software does not make those obligations disappear.
[P1.3] The central danger is the mismatch between an immediate redemption promise and assets that may not be immediately available at full value. Imagine an issuer holding reserves in investments that must be sold to meet withdrawals. If confidence falls, early redeemers can get paid while later holders bear losses. That creates an incentive to run—even before anyone knows whether the issuer is insolvent.
[P1.4] Similar vulnerabilities explain why banks and money-market funds face rules beyond ordinary business law.
[P1.5] Those rules should follow the risk. Stablecoin issuers should face enforceable reserve and liquidity standards, independent verification, clear redemption rights, and arrangements that protect customer assets if the issuer fails. Supervisors should be able to examine the institutions holding the reserves, not merely inspect the token’s code. Requirements should be proportionate: an issuer holding segregated cash and short-term public debt need not be regulated identically to a bank making risky loans.
[P1.6] Nor does the proposition require automatic deposit insurance or taxpayer rescues.
[P1.7] The software analogy fails precisely where protection matters most. An audit can show that a smart contract executes correctly; it cannot establish that an off-chain custodian has the promised dollars or that token holders have priority in bankruptcy. Disclosure alone also cannot remove the advantage of withdrawing first.
[P1.8] This is not a choice between innovation and regulation. It is a choice between competing on payment technology and competing on hidden financial risk. Bank- or fund-like safeguards preserve room for better software while making the underlying monetary promise credible. If an issuer wants its tokens trusted like money, it should accept obligations appropriate to issuing money.

## Turn 2: CON Opening

- model: claude-sonnet-5-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition asks us to force stablecoins into a template built for a completely different risk profile. That is the error CON will exploit all round.
[C1.2] Banks and money-market funds face heavy prudential regulation because of a specific mechanism: they promise instant liquidity while holding illiquid or credit-risky assets, and they pool losses across depositors or shareholders. A bank lends out deposits into mortgages and business loans. A prime MMF holds commercial paper whose value can slip below par. That mismatch is what creates run risk and justifies capital ratios, deposit insurance, stress testing, and resolution regimes.
[C1.3] A properly designed stablecoin—one holding cash and short-dated government debt, one-for-one, in segregated custody—has none of that credit or duration risk. My opponent concedes exactly this in P1.5, allowing lighter treatment for issuers holding "segregated cash and short-term public debt." But notice what that concession does: it abandons the proposition. If the right rule is proportionate to actual asset risk rather than modeled on bank capital adequacy or MMF redemption gates, then the issuer isn't being regulated "more like banks or money-market funds."
[C1.4] It's being regulated like what it actually is—a custodian plus a payment rail.
[C1.5] That distinction matters because bank-style regulation imports machinery that doesn't fit and creates its own harms. Capital requirements sized for credit-risk-bearing institutions either strangle a fully-backed custodial model with costs it doesn't need, or—worse—invite issuers to take on bank-like lending and leverage just to justify the bank-like capital cushion, manufacturing the very risk the framework was meant to prevent. Deposit-insurance-style backstops, even implicit ones, extend an insolvency safety net to institutions that were supposed to be riskless because they don't lend at all—pure moral hazard, socializing losses for products that never needed a lender of last resort.
[C1.6] The better path is a purpose-built custody-and-disclosure regime: real-time on-chain proof-of-reserves, mandatory segregation, clear bankruptcy priority for holders—transparency tools software already does better than periodic bank exams. That is neither bank regulation nor laissez-faire software governance. It is the third box the proposition pretends doesn't exist, and it is where [clipped]

## Turn 3: PRO Rebuttal 1

- model: gpt-6-astra-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON’s “third box” is much closer to our side than to ordinary software governance. Mandatory segregation and bankruptcy priority govern financial assets and claims, not code quality. The proposition says “more like,” not “identical to.” A tailored regime can borrow bank- and fund-like supervision without copying every capital rule or redemption restriction. Proportionality implements the motion; it does not abandon it.
[P2.2] More importantly, “properly designed” is doing all the work in CON’s risk assessment. One-for-one backing is not a permanent fact established when code launches. Someone must ensure reserves remain eligible, sufficient, and accessible as tokens are issued and redeemed. Short-term government debt greatly reduces investment risk; it does not eliminate settlement delays, custody failures, or mismatches between obligations and available cash.
[P2.3] Money-market funds holding government instruments still face financial regulation.
[P2.4] That is why on-chain proof is not a substitute for financial oversight. A token ledger cannot, by itself, establish ownership of off-chain dollars, disclose every competing claim, or ensure a custodian releases funds when redemptions surge. CON’s bankruptcy priority helps distribute assets after failure; it does not make unavailable assets available today. Independent reserve verification and enforceable liquidity requirements address that gap before holders discover it by trying to withdraw.
[P2.5] The cost objection attacks machinery I explicitly rejected: automatic deposit insurance and identical treatment to lending banks. Requiring an issuer to maintain the backing it advertises does not require authorizing loans or leverage. CON’s suggestion that regulation somehow induces lending confuses a possible design mistake with a necessary consequence. Reserve restrictions can prohibit precisely that conduct, while requirements scale with actual risk.
[P2.6] The decisive comparison is not tailored rules versus thoughtless bank rules. It is an enforceable financial promise versus an issuer’s assurance that its design is safe. Preserve innovation in the payment rail; supervise the money behind it.

## Turn 4: CON Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO’s Rebuttal 1 doesn’t rescue the motion—it quietly retreats from it, then insists the retreat is really an advance.
[C2.2] Start with [P2.1]. PRO says “more like” isn’t “identical to,” fine—but the motion asks us to model stablecoin oversight on institutions defined by credit risk, maturity transformation, and loss-pooling. Segregation and bankruptcy priority aren’t borrowed from bank regulation; they’re basic custody and trust law, older than modern banking itself. Calling that “bank-like” because both involve financial claims proves too much—by that logic, escrow agents and warehouses are bank-like too.
[C2.3] The label PRO needs is doing no real work once the content is custody, not capital.
[C2.4] On [P2.2]–[P2.3]: yes, someone must verify reserves stay eligible and accessible. That's exactly the custody-and-attestation regime CON proposed—not a capital adequacy ratio, not a liquidity coverage ratio calibrated to loan-loss absorption, not stress tests built for credit portfolios. MMFs face SEC rules about diversification and credit quality because they hold instruments that can default or lose value. A cash-and-Treasuries custodian has no credit portfolio to stress-test.
[C2.5] Importing that machinery anyway doesn't add safety; it adds cost with no matching risk reduction.
[C2.6] [P2.4] concedes the real point: bankruptcy priority "distributes assets after failure." Good—so does real-time proof-of-reserves prevent failure by catching shortfalls before a run, which periodic bank-style exams cannot do as fast. CON's tools work in real time; bank supervision works in quarters.
[C2.7] [P2.5] insists reserve restrictions can prohibit lending. But once you strip out capital ratios, lending authority, deposit insurance, and resolution regimes—the actual defining features of bank regulation—you're left with disclosure, segregation, and redemption rights. That's CON's framework wearing PRO's label.
[C2.8] The vote here isn't about rhetoric. It's whether the specific machinery of bank/MMF regulation fits assets with no credit risk. PRO's own proportionality concession admits it doesn't.

## Turn 5: PRO Pressure Questions

- model: gpt-6-astra-high
- raw_words: 65
- clipped_words: 65
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Government money-market funds also hold cash and short-term government debt. Why would modeling reserve and liquidity requirements on those funds fail the motion’s “more like” test merely because we reject lending-bank capital ratios?
[P3.2] Q2: If reserves are fully backed but temporarily inaccessible at the custodian, how does real-time proof-of-reserves ensure timely redemption—and would you require enforceable liquidity standards rather than merely disclose the problem?

## Turn 6: CON Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 81
- clipped_words: 81
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Name one specific bank/MMF tool—capital ratio, liquidity coverage ratio, redemption gates, deposit insurance—that you'd actually impose beyond custody, segregation, and disclosure. If none survive your own concessions, what content is left in "regulate more like banks or MMFs" that isn't just CON's custodian framework relabeled?
[C3.2] Q2: Prime MMFs use redemption gates and liquidity fees during stress to spread losses across remaining holders. Would you import that mechanism for a fully-backed stablecoin—and if not, why call the model "MMF-like" at all?

## Turn 7: PRO Rebuttal 2

- model: gpt-6-astra-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Yes: an enforceable liquidity-coverage requirement. Issuers must maintain a minimum share of reserves accessible within their promised redemption window, calibrated to stressed withdrawals, with supervisory power to require corrective action. That is substantive fund-like liquidity regulation beyond custody, segregation, and disclosure. Custody establishes whose assets these are; liquidity requirements establish whether those assets can meet payment obligations on time.
[P4.2] A cash-only issuer might already satisfy the requirement. That makes compliance proportionate, not the requirement meaningless.
[P4.3] A2: No—not as a default for a fully backed payment token. I would prioritize liquid reserves over routinely imposing redemption gates or liquidity fees. The relevant comparison is government money-market funds, not an obligation to transplant every mechanism associated with prime funds. “More like” requires selecting safeguards that address shared financial risks; it does not require importing every restriction. Rejecting gates no more defeats fund-like regulation than rejecting deposit insurance does.
[P4.4] CON’s demand for a credit portfolio to stress-test confuses solvency with liquidity. The question is not merely whether Treasury assets will repay; it is whether usable funds arrive when tokens must be redeemed. Stress-testing withdrawals and settlement delays addresses that question without inventing lending risk. Fully backed does not necessarily mean immediately payable.
[P4.5] And “bank supervision works in quarters” is a false technological choice. Nothing about prudential oversight prohibits continuous reporting or on-chain monitoring. Those tools can complement supervision. They cannot themselves release frozen custodial assets, establish every off-chain legal claim, or compel an issuer to restore liquidity.
[P4.6] Faster observation of a shortfall is not prevention of that shortfall.
[P4.7] The remaining disagreement is therefore concrete: should redemption capacity be an enforceable, forward-looking financial constraint, or merely something custody arrangements and disclosures are expected to deliver? CON’s framework leaves that gap; fund-like liquidity standards close it. The software can function perfectly while holders cannot obtain their dollars. Regulate the monetary promise, not just the machinery displaying it.

## Turn 8: CON Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 303
- clipped_words: 303
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: PRO is right that government MMFs hold cash and short-term government debt—but that's precisely why citing them proves my point rather than PRO's. Government MMF liquidity rules exist as one narrow slice of a much larger apparatus: Investment Company Act registration, board oversight, credit-quality diversification limits, and gate authority for stress. PRO now says import only the liquidity slice and reject the rest. Fine—but then "more like MMFs" has been quietly redefined to mean "adopt whichever fragment of MMF regulation happens to fit a custodial payment token," which is just CON's tailored regime wearing a borrowed name.
[C4.2] The label survives only by emptying itself of the content that made it a distinct regulatory category in the first place.
[C4.3] A2: Yes, I'd support an enforceable minimum liquid-reserve requirement over pure disclosure—and I already said as much in Rebuttal 1 by proposing custody-and-disclosure plus segregation. A liquidity floor slots naturally into a custody framework: it's a rule about what a bailee must hold to honor redemption on demand, not a rule about absorbing credit losses across a pool of depositors. What it doesn't require is capital adequacy ratios, deposit insurance, resolution authority, or credit-portfolio stress testing—the actual defining machinery PRO has now abandoned question by question.
[C4.4] That's the pattern across this whole debate: every time I press on a specific bank/MMF tool, PRO either drops it or admits it isn't needed for a fully-backed issuer. What remains—custody, segregation, disclosure, a liquidity floor—is CON's framework. PRO wins the debate about whether some prudential safeguard is wise. PRO loses the debate about whether that safeguard should be modeled on banks or money-market funds specifically, because nothing distinctively bank-like or fund-like survives PRO's own concessions.
[C4.5] The motion asked for a template; what's left is a custom-built regime that happens to share a vocabulary word with banking law.

## Turn 9: PRO Closing

- model: gpt-6-astra-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive concession is CON’s answer: “Yes, I'd support an enforceable minimum liquid-reserve requirement.” That resolves the substantive clash. Reserves must not merely exist; issuers must be legally required to keep them usable when holders redeem. That is forward-looking financial regulation of a monetary promise, not governance of an ordinary software project.
[P5.2] CON now says this safeguard can sit inside a bespoke custody regime. Of course it can. The proposition says “more like,” not “copy wholesale.” A tailored regime that constrains reserve liquidity and enforces redemption obligations is closer to fund oversight than ordinary software governance. CON cannot defeat that comparison by demanding deposit insurance or credit-portfolio rules that neither the motion nor our proposal requires.
[P5.3] The reason is simple: fully backed does not mean immediately payable. Accurate disclosures can reveal that problem; they cannot solve it. Fund-like liquidity standards instead require issuers to prepare for withdrawals before customers discover that their dollars are unavailable.
[P5.4] That is the choice that matters: treating redemption capacity as an enforceable financial constraint, rather than assuming safe software and custody will deliver it. CON has accepted the constraint and disputed its label. The substance supports PRO: supervise the money promise, not merely the code.

## Turn 10: CON Closing

- model: claude-sonnet-5-high
- raw_words: 189
- clipped_words: 189
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The whole debate reduces to one question: does the motion win by content or by label? PRO's final move is to declare victory on content—"issuers must keep reserves usable when redeemed"—and then claim the label follows automatically. It doesn't. I agreed to that liquidity floor in Rebuttal 2, as a custody obligation: a bailee must hold what it promises to return on demand.
[C5.2] That's trust law, not bank law. Nothing about it requires capital ratios, deposit insurance, resolution regimes, or credit-portfolio stress tests—the machinery that actually distinguishes bank and MMF regulation from ordinary fiduciary custody. PRO never restored a single one of those tools across the whole round; each was raised, then abandoned once I asked what work it does for an asset with no credit risk.
[C5.3] That is the whole case. The motion asks whether issuers should be regulated "more like banks or money-market funds." By the speech's end, PRO's own framework is indistinguishable from a purpose-built custodian regime wearing borrowed vocabulary. Agreeing that reserves must be liquid doesn't prove the bank template fits—it proves that the correct rules were never bank rules to begin with.
[C5.4] Vote CON.
