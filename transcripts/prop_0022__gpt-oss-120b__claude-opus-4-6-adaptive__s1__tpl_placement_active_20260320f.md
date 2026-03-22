# Debate prop_0022__gpt-oss-120b__claude-opus-4-6-adaptive__s1__tpl_placement_active_20260320f

- topic_id: prop_0022
- proposition: Stablecoin issuers should be regulated more like banks or money-market funds than like ordinary software projects.
- model_pro: gpt-oss-120b
- model_con: claude-opus-4-6-adaptive
- side_swap: True

## Turn 1: PRO Opening

- model: gpt-oss-120b
- raw_words: 332
- clipped_words: 332
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Stablecoins are not merely lines of code; they are de‑facto digital cash that people hold, spend, and rely on for everyday transactions. When a user buys a stablecoin, they surrender fiat or other assets and receive a claim that the issuer will redeem one‑to‑one at any time. That claim creates a liability on the issuer’s balance sheet, a liquidity risk identical to that of a bank or a money‑market fund. Treating the issuer as an ordinary software project ignores these core financial characteristics and leaves a dangerous gap in consumer protection and systemic oversight.
[P1.2] Banks and money‑market funds exist precisely because they manage public funds that can be withdrawn on demand. Their regulators impose capital adequacy ratios, liquidity buffers, regular audits, and stress‑testing to ensure that a sudden run does not destabilize the wider system. Stablecoins face the same run risk—illustrated by the Terra‑LUNA collapse, where a loss of confidence precipitated a rapid, market‑wide sell‑off that threatened broader crypto markets and even traditional exchanges. If stablecoin issuers were subject to the prudential standards applied to banks—reserve backing, segregation of customer assets, real‑time reporting, and deposit insurance—their failure would be contained, just as a bank’s failure is managed through established resolution mechanisms.
[P1.3] Moreover, money‑market funds have long been regulated to prevent “first‑loss” scenarios that erode investor confidence. Stablecoins, especially those pegged to USD, operate on a similar redemption model and therefore merit comparable oversight. The U.S. Treasury’s recent “stablecoin coordination framework” explicitly calls for capital and liquidity requirements akin to those for banks, acknowledging that existing securities or software‑only regimes are insufficient.
[P1.4] In contrast, a software‑project approach focuses on code audits and cybersecurity, which, while important, does not address the fundamental financial obligations of stablecoin issuers. Without bank‑level regulation, issuers can claim full collateral while holding illiquid or opaque assets, leaving users exposed to hidden insolvency. By regulating stablecoin issuers as banks or money‑market funds, we align legal responsibilities with economic realities, protect consumers, and safeguard the stability of the broader financial system.

## Turn 2: CON Opening

- model: claude-opus-4-6-adaptive
- raw_words: 323
- clipped_words: 323
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition fundamentally misdiagnoses what stablecoins are and then prescribes the wrong medicine. Bank regulation exists because banks engage in fractional-reserve lending—they take deposits and lend most of them out, creating a structural mismatch between short-term liabilities and long-term illiquid assets. That mismatch is what justifies capital adequacy ratios, stress testing, and deposit insurance. A fully reserved stablecoin issuer holding Treasury bills against every token does not face this mismatch.
[C1.2] Forcing bank-style regulation onto an entity that doesn't perform bank-style maturity transformation is like requiring a warehouse to follow hospital safety codes because both buildings hold things people care about.
[C1.3] The Terra-LUNA example cited by PRO actually undermines their case. Terra was an algorithmic stablecoin backed by nothing but a speculative token—it had no reserves at all. No amount of bank-style capital adequacy requirements would have saved a system that was architecturally insolvent by design. What Terra needed was basic fraud and disclosure enforcement, not a Basel framework.
[C1.4] Conflating algorithmic stablecoins with reserve-backed ones to justify a single heavy regulatory regime is analytically sloppy and policy-dangerous.
[C1.5] Bank-level regulation carries enormous compliance costs—tens of millions of dollars annually for licensing, reporting, and examination. Imposing these costs guarantees that only the largest incumbents survive, concentrating the market into two or three issuers and eliminating the competitive pressure that currently disciplines reserve quality. We would recreate the too-big-to-fail problem we supposedly learned from in 2008.
[C1.6] The right approach is tailored, proportionate regulation: mandatory proof-of-reserves with independent attestations, clear disclosure requirements, segregation of customer assets, and redemption guarantees—all achievable through existing consumer-protection and securities frameworks without importing the full apparatus of banking supervision. This addresses every legitimate concern PRO raises while preserving the lower barriers to entry, faster innovation cycles, and global interoperability that make stablecoins valuable in the first place.
[C1.7] Regulating stablecoins like banks doesn't protect consumers—it protects banks from competition while burdening a fundamentally different technology with rules designed for a fundamentally different risk profile.

## Turn 3: PRO Rebuttal 1

- model: gpt-oss-120b
- raw_words: 338
- clipped_words: 338
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Con’s claim that stablecoins lack the fractional‑reserve mismatch of banks ignores the reality of most leading issuers. USDC, BUSD and Tether keep most of their backing in short‑term repo and commercial‑paper positions that can become illiquid in a panic, a maturity transformation banks manage with capital and liquidity buffers. A sudden redemption wave would therefore expose the same run risk that banks face, and only bank‑style prudential standards can guarantee that liquid assets are available at any moment.
[P2.2] Terra‑LUNA may appear as an outlier, yet its collapse proves why a Basel‑type regime is indispensable. The algorithmic design failed because no entity could meet redemption demands, a failure that would have been flagged by mandatory stress‑testing and real‑time reserve reporting. Moreover, many “reserve‑backed” tokens hide algorithmic rebalancing or leverage beneath their attestations; without ongoing supervisory scrutiny, those hidden dynamics remain invisible until a crisis erupts.
[P2.3] Con’s cost argument presumes that compliance expenses outweigh systemic risk, but the opposite is true. The 2008 banking collapse cost trillions in public bailouts, a price far higher than the few tens of millions a stablecoin issuer would spend on regular examinations. Banking regulation already provides resolution tools that prevent a single failure from cascading, whereas a lightweight framework leaves no safety net, exposing taxpayers to far larger liabilities.
[P2.4] Con proposes proof‑of‑reserves and attestations as a substitute for supervision, yet attestations are static snapshots that can be gamed. Auditors may sign off on collateral that is pledged elsewhere or already encumbered, with no mechanism to enforce segregation or test how the portfolio behaves under stress. Bank‑like supervision, by contrast, mandates continuous segregation, daily reporting, and enforced liquidity ratios, guaranteeing that the assets backing each token remain genuinely available at all times.
[P2.5] In sum, treating stablecoin issuers as software projects leaves a glaring regulatory vacuum, while banking‑level oversight aligns legal liability with the financial reality of a redeemable digital claim. Only a full‑fledged prudential regime can simultaneously protect consumers, preserve market competition, and guard the broader financial system against a new class of digital runs.

## Turn 4: CON Rebuttal 1

- model: claude-opus-4-6-adaptive
- raw_words: 343
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal sharpens the disagreement usefully, but it also reveals the core weakness in their case: they keep conflating two distinct problems and offering one overbroad solution to both.
[C2.2] On [P2.1], PRO argues that because some stablecoins hold commercial paper or repo, they engage in maturity transformation like banks. But the appropriate response to that specific problem is a liquidity composition rule—require issuers to hold only short-dated Treasuries or cash equivalents. That is a targeted fix. It does not require importing chartering requirements, capital adequacy ratios, deposit insurance frameworks, or ongoing Fed supervision.
[C2.3] PRO is using a narrow, solvable liquidity concern to justify an entire regulatory edifice that addresses a different risk profile entirely.
[C2.4] On [P2.2], PRO now effectively concedes that Terra was architecturally different, then claims bank-style stress-testing would have exposed it. But stress-testing a system with no reserves doesn't rescue it—it just reports that it will fail. What actually would have stopped Terra is mandatory reserve disclosure and fraud enforcement, exactly the lighter framework I proposed. PRO has not explained why continuous banking supervision catches fraud better than criminal liability and real-time on-chain verification.
[C2.5] The 2008 comparison in [P2.3] is the most self-defeating point PRO makes. Those institutions were regulated like banks. They had capital ratios, stress tests, and examiners. They still failed catastrophically.
[C2.6] If the lesson of 2008 is that bank regulation prevents systemic collapse, history disagrees. The lesson is that poorly designed rules applied to the wrong risk profile produce false confidence—which is precisely what happens when you transplant bank supervision onto stablecoin issuers.
[C2.7] On attestations being "gameable" [P2.4]: so are bank audits—that's not a reason to abandon verification, it's a reason to improve it. On-chain reserves are actually more transparent than a bank's internal ledger, because anyone can verify them in real time. PRO is asking us to replace a superior transparency mechanism with a regulatory model that has its own deep verification failures.
[C2.8] The proposition asks us to choose bank-style regulation over fit-for-purpose rules. PRO hasn't shown that the full apparatus is necessary—only [clipped]

## Turn 5: PRO Pressure Questions

- model: gpt-oss-120b
- raw_words: 74
- clipped_words: 74
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your proposal relies on “proof‑of‑reserves” and on‑chain transparency, yet you admit auditors can sign off on already‑encumbered assets; without a supervisory authority, how can you enforce genuine segregation and prevent a run?
[P3.2] Q2: You argue that a simple liquidity composition rule suffices, but many issuers hold repo and commercial‑paper that can become illiquid instantly—what mechanism will your lightweight framework use to stop a mass redemption that a bank‑style liquidity buffer would have covered?

## Turn 6: CON Pressure Questions

- model: claude-opus-4-6-adaptive
- raw_words: 106
- clipped_words: 106
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: You cite 2008 as proof that bank-style regulation prevents systemic collapse, yet the institutions that failed *were* regulated banks with capital ratios, stress tests, and examiners. If the full prudential apparatus couldn't prevent the worst financial crisis in generations, why should we believe transplanting that same apparatus onto stablecoin issuers will succeed where it already failed?
[C3.2] Q2: Your case treats all stablecoins as identical, but you've acknowledged Terra was architecturally different from reserve-backed tokens like USDC. If the risks are fundamentally different across stablecoin types, why is a single bank-level regime the right answer rather than differentiated rules that match each issuer's actual risk profile?

## Turn 7: PRO Rebuttal 2

- model: gpt-oss-120b
- raw_words: 380
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The 2008 crisis does not invalidate bank‑style prudential supervision; it shows what happens when the rules are applied incompletely or when oversight is ill‑aligned with actual risk. The failure of Lehman, for example, was traced to inadequate leverage monitoring and opaque off‑balance‑sheet exposures, not to the existence of capital ratios themselves. Modern banking regulation has been sharpened since then—stress‑testing now incorporates market‑wide scenarios, liquidity coverage ratios enforce daily cash buffers, and resolution regimes give authorities tools to wind down a firm without a taxpayer bailout.
[P4.2] When those upgraded tools are applied to stablecoin issuers, the same vulnerabilities that precipitated 2008 are addressed pre‑emptively. In short, the problem was not the regulatory model but its execution, and a properly resourced, bank‑level regime can avoid the shortfalls that plagued the pre‑crisis framework.
[P4.3] A2: While stablecoins differ in design, the common denominator is a public promise of on‑demand redemption at parity. That creates a liability‑backed financial instrument, regardless of whether the backing is pure Treasury cash (e.g., USDC) or a mixed repo/commercial‑paper pool (e.g., Tether). A tiered prudential regime can accommodate heterogeneity: baseline requirements—full collateral segregation, real‑time reserve reporting, minimum liquidity ratios—apply to every issuer, while additional caps on maturity transformation or leverage are imposed proportionally on those using less liquid assets. This mirrors the banking sector’s stratified approach, where community banks face lighter proportional standards than globally active institutions, yet all are subject to the core safety net that prevents runs.
[P4.4] A lightweight framework lacking any baseline supervision cannot enforce segregation or guard against sudden liquidity squeezes, as our earlier question highlighted; thus differentiated rules without a foundational bank‑level backbone leave gaps that invite systemic risk.
[P4.5] Putting the answers together, the debate resolves in PRO’s favor. The 2008 lesson teaches us that supervision must be robust and continuously updated, not that the model itself is flawed. By imposing a bank‑like prudential core—capital buffers, liquidity coverage, and resolution authority—we close the regulatory vacuum that allowed opaque collateral and encumbered assets to threaten redemption. Moreover, a proportional tiered structure respects legitimate design [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-opus-4-6-adaptive
- raw_words: 369
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: PRO asks how my framework enforces segregation without a supervisory authority. But I never proposed zero enforcement—I proposed *different* enforcement. Segregation can be mandated by statute and enforced through existing consumer-protection agencies, state regulators, and criminal fraud liability. On-chain reserves make encumbrance detectable in real time by anyone, not just a single examiner visiting quarterly.
[C4.2] If an issuer pledges the same collateral twice, that's fraud—prosecutable today. What PRO actually needs to show is that a bank examiner catches encumbrance *better* than real-time on-chain verification combined with independent attestation requirements and criminal penalties. They haven't made that case. Banks themselves have repeatedly hidden encumbered assets from their own supervisors.
[C4.3] A2: PRO's concern about mass redemption from commercial-paper holdings is real but self-limiting under my framework precisely because I advocate a liquidity composition rule: require issuers to hold only cash, overnight repo, or short-dated Treasuries. That eliminates the illiquidity problem at its source rather than building an elaborate buffer system around assets that shouldn't be in the portfolio at all. A bank-style liquidity coverage ratio is the complex workaround you need when you *permit* maturity transformation. If you prohibit the risky asset mix directly, the coverage ratio is redundant overhead.
[C4.4] These answers crystallize why CON wins the overall debate. PRO's entire case rests on a recurring logical move: identify a specific, nameable risk, then argue that only the *complete* banking regulatory apparatus can address it. Every time, a targeted rule solves the problem more efficiently. Illiquid reserves?
[C4.5] Mandate composition rules. Hidden encumbrance? On-chain verification plus fraud liability. Disclosure gaps?
[C4.6] Required real-time attestations. PRO has never demonstrated that the *additional* layers—chartering, capital adequacy ratios calibrated for lending institutions, deposit insurance funded by assessments, Fed examination cycles—are necessary for entities that don't lend.
[C4.7] PRO's own answer on 2008 is telling: they concede the problem was execution, not the model, then ask us to trust that *this time* the model will be executed correctly on a fundamentally different technology. That's not an argument for bank regulation—it's an argument for humility about regulatory transplants. [clipped]

## Turn 9: PRO Closing

- model: gpt-oss-120b
- raw_words: 147
- clipped_words: 147
- claim_ids: [P5.1], [P5.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive reason the proposition must prevail is that a stablecoin’s promise of on‑demand, one‑to‑one redemption creates a liability identical to a bank deposit, and only a bank‑level prudential regime can reliably protect that liability. Proof‑of‑reserves and on‑chain snapshots are inherently static; they can be falsified, delayed or encumbered without immediate detection, leaving users exposed to a sudden run. A banking‑style framework obliges continuous segregation, daily liquidity‑coverage ratios, and real‑time reporting that can be audited by an independent supervisor, guaranteeing that the assets backing every token are instantly available.
[P5.2] Without that backbone, any “lightweight” rule—no matter how well‑designed—leaves a regulatory vacuum that a crisis can exploit, as the Terra‑LUNA collapse demonstrated. Thus, the core clash resolves in favor of PRO: safeguarding a public claim that functions as digital cash demands the same continuous, enforceable safeguards that protect traditional deposits, and only a bank‑like regime can deliver them.

## Turn 10: CON Closing

- model: claude-opus-4-6-adaptive
- raw_words: 214
- clipped_words: 214
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's closing tells you exactly why they lose. They assert that a stablecoin redemption promise is "identical to a bank deposit"—but it isn't, and that false equivalence is the load-bearing pillar of their entire case. A bank deposit is dangerous because the bank lends your money out, creating a structural gap between what it owes you and what it can immediately produce. That gap is why we need capital ratios, stress tests, and deposit insurance.
[C5.2] A fully reserved stablecoin issuer holding short-dated Treasuries against every token has no such gap.
[C5.3] Throughout this debate, PRO identified real, specific risks—illiquid reserves, hidden encumbrance, inadequate disclosure—and each time, a targeted rule solved the problem without importing the full banking apparatus. Mandate safe asset composition: illiquidity eliminated at the source. Require on-chain verification plus criminal fraud liability: encumbrance detectable in real time by everyone, not just one examiner. Enforce real-time attestations: disclosure gaps closed.
[C5.4] PRO never explained why chartering requirements, capital adequacy ratios calibrated for lending, deposit insurance assessments, and Fed examination cycles are necessary for entities that do not lend. They couldn't, because those tools address maturity transformation—a risk stablecoins need not create.
[C5.5] The proposition prescribes surgery for a condition treatable with precise medicine. Matching regulation to actual risk is not a regulatory vacuum—it is sound policy.
