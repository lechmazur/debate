# Debate prop_0154__claude-sonnet-4-6-adaptive__claude-opus-4-6-0K__s1__tpl_placement_active_20260320f

- topic_id: prop_0154
- proposition: Copyright law should create a compulsory licensing scheme for training foundation models on copyrighted text and images, with payment to rightsholders.
- model_pro: claude-sonnet-4-6-adaptive
- model_con: claude-opus-4-6-0K
- side_swap: True

## Turn 1: PRO Opening

- model: claude-sonnet-4-6-adaptive
- raw_words: 343
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Foundation models are trained on billions of copyrighted works without permission or payment. The status quo offers creators two options: get nothing, or spend years in litigation hoping a court agrees this isn't fair use. A compulsory licensing scheme fixes both sides of this failure by guaranteeing creators compensation while giving developers legal certainty and continued access to the cultural commons.
[P1.2] **The transaction cost problem is insurmountable without compulsory licensing.** A single large language model may train on text from millions of distinct copyright holders. Voluntary negotiation with each rightsholder is economically impossible—the costs of identification, contact, and individual bargaining would dwarf the value of any single work's contribution. This is precisely the market failure that compulsory licenses have historically solved. When cable television needed to retransmit broadcast signals, Congress created a compulsory license rather than letting the system collapse under negotiation costs.
[P1.3] When digital music services needed mechanical reproduction rights, the statutory license under Section 115 made streaming viable while paying songwriters. The pattern is clear: when a new technology creates value from aggregating vast numbers of copyrighted works, compulsory licensing is the proven mechanism.
[P1.4] **Without this scheme, the realistic alternatives are worse for everyone.** If courts rule training is fair use, creators receive nothing for the commercial exploitation of their work—a wealth transfer from artists and writers to the most profitable companies in history. If courts rule it's infringement, injunctive relief could halt AI development or concentrate it among the few companies that can afford bespoke licensing deals with major publishers, crushing competition and open-source development alike. Neither outcome serves the public interest.
[P1.5] **Compulsory licensing threads the needle.** It preserves broad access to training data, preventing monopolization by incumbents. It channels real money to creators through collecting societies or similar distribution mechanisms. And it provides the legal predictability that both sides currently lack, ending years of costly uncertainty.
[P1.6] The question isn't whether foundation models should use copyrighted material—they already do, at enormous scale. The question is whether creators get paid. A compulsory license ensures they do, without [clipped]

## Turn 2: CON Opening

- model: claude-opus-4-6-0K
- raw_words: 339
- clipped_words: 339
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition assumes a compulsory license is the obvious fix to an obvious problem. It isn't, and three fundamental flaws make the scheme worse than the alternatives.
[C1.2] First, compulsory licensing would constitutionally and practically cement infringement rather than resolve it. The premise requires accepting that training on copyrighted works is, in fact, copying that triggers liability. That is genuinely contested. Courts analyzing transformative use, the non-expressive character of training, and the absence of market substitution may well conclude that ingestion for statistical learning differs categorically from reproduction.
[C1.3] If training is fair use, a compulsory license is not a solution—it's a tax on an activity that needed no permission in the first place, imposed at the exact moment when AI development requires maximum flexibility. Legislating now locks in a factual and legal assumption before anyone knows whether it's correct.
[C1.4] Second, the payment mechanism is not the practical salvation PRO claims. Collecting societies work when you can match a played song to its owner and calculate proportional value. Foundation models expose text and images to stochastic processes; no individual work contributes a traceable, measurable quantum of capability to the model. How do you divide a royalty pool among millions of claimants whose individual contributions are genuinely indistinguishable?
[C1.5] The precedents PRO cites—cable, music streaming—involve discrete, identifiable uses. The math does not transfer. What you get instead is arbitrary distribution captured by large legacy rightsholders who dominate any collecting body, while the working illustrators and freelance writers the scheme purports to help receive nominal checks.
[C1.6] Third, compulsory licensing doesn't prevent monopolization—it accelerates it. Setting a statutory rate benefits the largest developers who can budget predictably and lobby to keep rates favorable. Open-source projects and academic researchers face the same per-token licensing obligation as trillion-dollar corporations but without the legal infrastructure to comply. The compliance burden alone becomes a barrier that entrenches incumbents.
[C1.7] The real choice isn't between a compulsory license and chaos. It's between waiting for law to develop through courts—where creators can still win—and freezing a half-formed, badly-designed scheme into statute permanently.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-4-6-adaptive
- raw_words: 312
- clipped_words: 312
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The opponent's case rests on three arguments, each of which dissolves under examination.
[P2.2] On fair use: the claim is essentially "courts might rule for developers, so don't legislate." But notice what this concedes—creators must gamble everything on litigation, and if they lose, they get nothing while trillion-dollar companies profit from their life's work. The opponent treats "fair use might win" as a reason to preserve the status quo.
[P2.3] But fair use is a defense in litigation, not a guarantee of payment. A compulsory license can be structured as a safe harbor that applies regardless of how the fair use question ultimately resolves. It doesn't "cement infringement"—it guarantees compensation either way, which is precisely its virtue.
[P2.4] On distribution: the opponent says individual contributions are indistinguishable, so payment is impossible. But performing rights organizations distribute billions of dollars annually without perfect attribution—they use sampling, proxy measures, and categorical weighting. The music analogy the opponent dismisses actually proves the point: imperfect distribution is still massively better than zero distribution. "We can't achieve perfect precision" is not an argument for paying creators nothing; it's an argument for thoughtful scheme design.
[P2.5] And the worry about large rightsholders capturing distribution bodies is a governance concern that scheme designers can directly address through representation rules.
[P2.6] On monopolization: this is where the opponent's logic inverts most visibly. The status quo—litigation uncertainty with no statutory rate—is the regime that favors incumbents. Only the largest companies can afford to negotiate bespoke deals or sustain multi-year lawsuits. A uniform statutory rate gives every developer, including open-source projects, a predictable, equal cost of compliance.
[P2.7] That is less monopolistic than a world where legal access depends on legal budgets.
[P2.8] The opponent offers "wait for the courts." But waiting means years of no payment to creators, ongoing legal chaos for developers, and ultimate outcomes that neither side controls. Compulsory licensing ends that uncertainty deliberately, not accidentally.

## Turn 4: CON Rebuttal 1

- model: claude-opus-4-6-0K
- raw_words: 381
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.3]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal reveals the core tension in their case: they want to legislate a payment scheme while simultaneously admitting the underlying legal question is unresolved. That combination is not a virtue—it's the central defect.
[C2.2] Consider what [P2.3] actually proposes: a "safe harbor that applies regardless of how fair use resolves." This means creators get paid even if courts determine no rights were violated. That is not compensation—it is a rent extracted by statute from a lawful activity. We don't impose compulsory licenses on other fair uses.
[C2.3] Libraries don't pay a statutory fee for lending. Critics don't pay for quoting. If training is transformative, mandating payment distorts the copyright balance that fair use exists to maintain. PRO treats the uncertainty as a reason to legislate now; I say it's precisely the reason not to, because you risk permanently taxing conduct that the law already permits.
[C2.4] On distribution, PRO argues imperfect payment beats zero payment. But the analogy to performing rights organizations masks a critical difference. When ASCAP distributes royalties, a song was played, identified, and counted. When a model trains on a corpus, no work is "performed" in any trackable sense.
[C2.5] The contribution of any single text to a model's capabilities is not merely hard to measure—it may be conceptually undefined. PRO's answer is "thoughtful scheme design," but that is a promissory note, not a mechanism. And the predictable result of undefined contributions plus a fixed royalty pool is that distribution defaults to corpus size and institutional clout. Major publishers with massive catalogs collect; independent creators get pennies.
[C2.6] That is not a governance problem you fix with "representation rules"—it is structural.
[C2.7] On monopolization, PRO claims a uniform rate levels the playing field. But uniform rates are uniquely punishing to resource-constrained actors. An academic lab training a small model on a specialized corpus pays the same per-work rate as a company training a commercial product worth billions. Open-source developers, who currently rely on fair use arguments to operate freely, would face mandatory licensing costs they cannot absorb.
[C2.8] The predictability PRO celebrates [clipped]

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-4-6-adaptive
- raw_words: 99
- clipped_words: 99
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You argue that training may be fair use and therefore a compulsory license imposes a "tax on a lawful activity"—but if that's true, developers can simply opt out and defend on fair use grounds; so what exactly is the harm in offering a licensed pathway that guarantees payment to creators who otherwise receive nothing?
[P3.2] Q2: You claim uniform statutory rates are "uniquely punishing" to small actors, yet the current alternative is costly litigation that only well-funded incumbents can sustain—can you name any concrete mechanism in your preferred "wait for courts" approach that actually delivers payment to individual creators?

## Turn 6: CON Pressure Questions

- model: claude-opus-4-6-0K
- raw_words: 93
- clipped_words: 93
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: You say creators can receive payment "either way" under a compulsory license structured as a safe harbor—but if training is ultimately found to be fair use, what legal theory justifies compelling payment at all, and doesn't that precedent threaten every other transformative use in copyright law?
[C3.2] Q2: PRO repeatedly invokes performing rights organizations as proof that imperfect distribution works, but those systems track discrete performances of identified works—can you name a single concrete mechanism that would measure an individual text's contribution to a foundation model's capabilities without defaulting entirely to corpus size?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-4-6-adaptive
- raw_words: 396
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The legal theory is straightforward: Congress has broad authority to condition uses of copyrighted material on payment even where courts might otherwise permit the use freely. Section 111 cable retransmission created a compulsory license for activity that might have qualified as fair use—Congress chose not to wait for courts to decide. The Copyright Clause grants legislative power to promote progress; a compulsory license is an exercise of that power, not a contradiction of it. And the slippery slope to "threatening every transformative use" fails because the scheme is narrowly triggered by a specific, identifiable activity—mass ingestion of copyrighted works for commercial model training—not quotation, criticism, or library lending.
[P4.2] Legislative specificity is how you draw that line, and Congress draws such lines routinely.
[P4.3] A2: Yes. Training data registries already log which works appear in which training corpora—datasets like The Pile publish their composition. A scheme could weight distribution by verified inclusion in training sets, adjusted by factors like work length and dataset frequency, rather than requiring measurement of causal contribution to model capability. This is analogous to how radio royalties are distributed using sampling and logged playlists, not by measuring a song's precise contribution to a station's advertising revenue.
[P4.4] Perfect causal attribution has never been the standard for any collecting society. The mechanism is: confirm inclusion, weight by reasonable proxies, distribute accordingly. That some portion flows proportional to corpus presence is not a flaw—it reflects actual use.
[P4.5] Now step back and notice what these questions reveal about the opponent's position. The entire CON case reduces to two bets: that courts will find fair use, and that no distribution mechanism can work well enough. Both are gambles that leave creators with nothing in the meantime. My opponent has now been asked twice—once in my pressure questions, once implicitly throughout—to identify any mechanism in the "wait for courts" approach that actually delivers payment to working creators.
[P4.6] The answer remains silence, because there is none.
[P4.7] The compulsory license doesn't need to be perfect to be decisively better than the alternative. It needs [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-opus-4-6-0K
- raw_words: 411
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The harm is real and structural. PRO frames the compulsory license as a mere "option" developers can decline by asserting fair use. But once a statutory scheme exists, it reshapes the legal landscape. Courts evaluating fair use will ask whether a functioning licensing market exists—and the compulsory license itself creates one.
[C4.2] The fourth fair use factor considers market harm, and a statutory rate becomes evidence that a market for training licenses is viable, undermining the very fair use defense PRO says developers can fall back on. So the "opt out" is illusory: the license's existence poisons the alternative. This isn't hypothetical—courts in other contexts have treated the availability of licensing as weighing against fair use. You don't get to build an exit door that locks behind you.
[C4.3] A2: PRO's question assumes that the only legitimate outcome is guaranteed payment to creators, and any system without it fails. But copyright has never guaranteed payment—it guarantees the right to control use of your work. Courts can and do award damages, injunctions, and settlements. The Copyright Act already provides statutory damages that don't require proving actual loss.
[C4.4] Individual creators who prevail in litigation—or whose cases establish clear precedent—receive meaningful compensation and, crucially, establish rights that benefit every creator going forward. Class actions and consolidated proceedings can aggregate small claims efficiently. These aren't perfect, but they preserve creator autonomy: the right to say no, to negotiate, to hold out for better terms. A compulsory license strips that autonomy permanently in exchange for whatever rate Congress sets, which history shows gets captured by industry lobbying.
[C4.5] Now zoom out. PRO's rebuttal rests on the claim that legislative specificity can cabin this scheme to "mass ingestion for commercial model training." But that boundary is already blurring. Fine-tuning, retrieval-augmented generation, and embedding-based search all involve copyrighted text at different scales.
[C4.6] Where does the compulsory license stop? Every boundary PRO draws invites litigation about what counts—recreating the very uncertainty the scheme was supposed to eliminate.
[C4.7] PRO says silence on creator payment mechanisms reveals a weakness in my [clipped]

## Turn 9: PRO Closing

- model: claude-sonnet-4-6-adaptive
- raw_words: 286
- clipped_words: 220
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The entire debate comes down to one question: who bears the cost of uncertainty?
[P5.2] Under the opponent's preferred regime—wait for courts—creators bear all of it. They fund their own litigation against the wealthiest companies on earth, they receive nothing during the years cases wind through appeals, and if fair use prevails, they receive nothing ever. The opponent's answer to my repeated question about how working creators actually get paid was telling: they pointed to statutory damages and class actions, mechanisms that require creators to sue first and win later. That is not a payment system.
[P5.3] It is a lottery ticket with a legal fee attached.
[P5.4] The compulsory license shifts that cost. Developers gain certainty and continued access. Creators gain guaranteed revenue from verified use of their work. Neither side waits a decade for the Supreme Court.
[P5.5] The opponent's strongest point—that a statutory license might influence future fair use analysis—actually reinforces why legislation is needed. If courts will look to market reality anyway, then the choice is between a market deliberately designed to compensate creators and one that emerges haphazardly from bilateral deals between Big Tech and Big Publishing, leaving everyone else out.
[P5.6] Imperfect compensation distributed broadly is not just better than nothing—it is better than any realistic alternative the opponent has offered. Congress has made exactly this judgment before [clipped]

## Turn 10: CON Closing

- model: claude-opus-4-6-0K
- raw_words: 262
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO says the debate reduces to who bears the cost of uncertainty. But the real question is what you permanently sacrifice to eliminate it—and the answer is creator autonomy itself.
[C5.2] A compulsory license does not just set a price. It eliminates the right to say no. Every photographer, novelist, and illustrator loses the ability to withhold their work from training, to negotiate individually, to demand terms beyond a statutory rate that Congress sets once and industry lobbyists erode for decades. PRO frames this as creators "getting paid." It is actually creators being told what their work is worth by the same legislative process that trillion-dollar companies dominate.
[C5.3] And the mechanism is irreversible in a way PRO never confronted. Once the statutory license exists, it creates the licensing market that courts use to evaluate fair use under the fourth factor. The exit door locks behind you. Developers cannot meaningfully "opt out" to assert fair use when the license's very existence is cited as proof a market was available.
[C5.4] So creators don't get guaranteed compensation plus the option of litigation—they get the statutory rate, period, forever.
[C5.5] PRO's entire case assumes the only alternative is creators receiving nothing. But creators currently hold legal rights they have not yet fully exercised. Courts may award damages, establish precedent, or deny fair use defenses entirely—outcomes [clipped]
