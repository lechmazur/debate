# Debate prop_0273__claude-sonnet-5-high__muse-spark-1.1-high__s0__tpl_placement_active_20260320f

- topic_id: prop_0273
- proposition: Airlines and booking sites should have to show the full practical cost of a family trip, including baggage and seating, before users compare options.
- model_pro: claude-sonnet-5-high
- model_con: muse-spark-1.1-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 341
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A family of four books a "$79 fare" and discovers at checkout that two checked bags each way, seat assignments so the six-year-old sits next to a parent, and a basic-economy surcharge for anything beyond a personal item turn that fare into $340 per person. That gap between the advertised number and the real number is not a rounding error. It is the entire business model of drip pricing, and it is why the comparison stage of booking is structurally rigged against families before they ever click "search."
[P1.2] The core argument is simple: comparison only functions when the units being compared are the same unit. If Airline A shows $79 and Airline B shows $110, but A's real cost with bags and seats is $340 and B's is $180, then the "cheaper" option on screen is actually the more expensive option in reality. Consumers are not failing to do math. They are being shown the wrong math, at the exact moment they are told to compare.
[P1.3] This is not a hypothetical harm. Bags, seat selection, and family-seating fees are disproportionately triggered by exactly the kind of trip this proposition names: a family trip, meaning multiple travelers, multiple bags, and a hard requirement that children sit with an adult, which many airlines now charge extra to guarantee. Solo business travelers with carry-on only are the group least affected by drip pricing; families are the group most exposed to it. So this is not a generic consumer-protection nicety, it's a rule aimed at the precise failure mode the resolution describes.
[P1.4] The remedy proposed is modest and already has precedent: require the full practical cost to be shown before comparison, not buried after selection. This does not ban optional add-ons, cap prices, or dictate airline business models. It only says the number families use to compare must reflect what they'll actually pay. Markets work by comparison; comparison requires common units; airlines currently profit by breaking that unit.
[P1.5] Fixing that is not overreach, it's the minimum condition for the comparison to mean anything [clipped]

## Turn 2: CON Opening

- model: muse-spark-1.1-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.1], [P1.2]
- missing_claim_id_refs: (none)

[C1.1] There is no such thing as "the" practical cost of a family trip. That is the fatal flaw.
[C1.2] A family of four in [P1.1] could be two parents who pack four carry-ons and need no bags, or grandparents checking two suitcases each for a month. Do they need basic economy or main cabin? Window seats only? The proposal pretends we can know this before the user tells us.
[C1.3] Mandating a single "full" number at the comparison stage forces sites to invent a family, guess its luggage, and assume it will pay to sit together. That invented number is not transparent. It is fictional.
[C1.4] That fiction kills the best thing that happened to budget family travel: unbundling. Twenty years ago every ticket included two checked bags and a seat assignment whether you used it or not, so every family paid for them. Unbundling let a family flying for a weekend pay $79 and bring backpacks, while a family moving for the holidays pays for bags. Forcing the search page to show $340 before you can compare, as in [P1.2], does not reveal the real price.
[C1.5] It hides the cheap option entirely and tells search engines to punish airlines that give you the choice to opt out.
[C1.6] Comparison works because components are comparable, not because totals are presumed. The current screen lets me fairly compare base fares, then add what I need once. Your rule forces an upfront interrogation: how many bags, checked or carry-on, what ages, want to sit together? Every aggregator must block the search until you answer, or guess wrong and mislead you the other way.
[C1.7] Families are not helped by being shown a higher assumed price sooner. They are helped by being shown accurate options longer, with final all-in fees clearly disclosed before purchase, which DOT rules already require.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.4], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] CON's central move is to declare the target "fictional" and then hide behind that word for the rest of the speech. But look at what booking sites already require before showing any results: number of travelers, ages of children, dates, destinations. The site is not guessing a family into existence — the user already told it "two adults, two kids, ages 4 and 7." From that, showing the cost of one reasonable checked bag per adult and a guaranteed seat next to each child isn't invention.
[P2.2] It's using data the airline already has to compute the default price virtually every family in that search will actually pay. CON's supposed dilemma between "invent a family" and "show nothing real" is false. There's a third option: show the realistic default for the trip parameters entered, and let advanced users toggle it down if they truly need zero bags.
[P2.3] The unbundling argument in [C1.4] also proves too much. Nothing in this proposal bans unbundling or forces every family to buy bags they don't need. It only says the comparison screen must reflect the standard cost for the trip as configured, with the opt-out still available afterward. CON is defending the freedom to opt out of extras by insisting we can't tell people what the extras cost before they compare.
[P2.4] Those are different things. You can have granular pricing and honest comparison at the same time — this is what itemized receipts do in every other industry.
[P2.5] And [C1.7] actually concedes the entire debate: CON admits "final all-in fees clearly disclosed before purchase" already happen under DOT rules. But that disclosure comes after the comparison, after the click, after the sunk-cost psychology has already anchored the family to Airline A's $79 headline. The proposition is precisely about moving that already-conceded disclosure to before comparison instead of after it. CON hasn't explained why accurate information is fine at checkout but dangerous fiction one screen earlier.

## Turn 4: CON Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.2], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO says in [P2.1] that showing a bag and a seat isn't invention because the site already knows "two adults, two kids, ages 4 and 7." That tells you nothing about bags.
[C2.2] A family doing a two-night city break and a family relocating for a month for the holidays enter the exact same search. One needs no checked bags, one needs four. Calling "one reasonable checked bag per adult" reasonable isn't data. It's a stereotype you are forcing every result to carry, and then calling it transparency.
[C2.3] That is why [P2.2]'s toggle fix rewrites the proposition. The motion doesn't say "show an estimate you can toggle down." It says show the full practical cost including baggage and seating before you compare. If you need a toggle to zero to avoid punishing light packers, you've admitted the full cost is not the true cost for many families.
[C2.4] Someone now has to define what a Reasonable Family packs. That's not disclosure, that's the government inventing a family and ranking flights by its luggage.
[C2.5] [P2.5] claims I concede the debate because I support accurate all-in disclosure before purchase. That distinction is the entire debate. At checkout the total is accurate because you told the airline what you need. At the search page it is guessed.
[C2.6] One is information; the other is fiction pretending to be information. That's why accurate disclosure is fine at purchase and misleading one screen earlier.
[C2.7] And anchoring cuts both ways. If a backpack-only family that could fly for $79 now sees $340 as the headline on Google Flights, they don't comparison shop better. They stop searching. You haven't cured drip pricing, you've created shock pricing that hides the cheapest option.
[C2.8] Comparison works now because base fares are a common unit. Baggage need is not common. Aggregators also can't know if you have a co-branded card that waives bags, elite status, or that DOT now pressures airlines to seat under-13s next to a parent free. Your mandated "practical" total will be wrong for millions, in the name of accuracy.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 67
- clipped_words: 67
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: CON claims a default bag/seat estimate is an unverifiable "stereotype," yet also says DOT already pressures airlines to seat kids free — so which is it: is family need predictable enough to regulate, or too unpredictable to disclose?
[P3.2] Q2: If an adjustable default (toggle to zero) would resolve the light-packer problem, why oppose showing that adjustable default before comparison rather than showing nothing accurate at all?

## Turn 6: CON Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 79
- clipped_words: 79
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.2]
- missing_claim_id_refs: (none)

[C3.1] Q1: What exact bundle is the mandated "full practical cost" — how many bags, what type, which seats — and who gets to write that government definition of a family for every search?
[C3.2] Q2: If your fix in [P2.2] is an adjustable default that users can toggle to zero, haven't you admitted the "full" total isn't true for many families and just recreated the current system with a mandatory questionnaire that shows backpack-only families $340 before they can compare?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C1.7]
- missing_claim_id_refs: (none)

[P4.1] A1: The bundle isn't invented anew for each search — it's a single, regulator-set baseline applied uniformly, the same way nutrition labels use a standard serving size or EPA uses a standard driving cycle for MPG. Regulators already define "family seating" defaults for DOT rules CON cites in [C1.7]; extending that same defined standard — one reasonable checked bag per adult, seats held together for minors — to the comparison screen is not a mystery invention. It's applying an existing regulatory category one screen earlier.
[P4.2] A2: Yes, it's adjustable — and that is the fix, not a concession. CON's "recreate the current system" charge collapses on inspection: today the default is the bare fare with everything hidden, and correction requires clicking through extras. My proposal flips the default to the realistic total, with reduction available for people who genuinely need less. Defaults are not neutral — that's precisely why airlines fight to keep the misleading one.
[P4.3] A toggle-down option changes nothing structural; it's the anchor that matters, and CON never contests that flipping the anchor from "hidden truth" to "visible truth, adjustable" helps families instead of hurting them.
[P4.4] Zoom out: CON's whole case is that no universal family exists, so any default is "fiction." But CON never explains why an adjustable, regulator-defined default is worse than an airline-controlled silence that hides real costs from everyone. The choice was never between a perfect number and a fake number — it's between a reasonable, correctable estimate shown before comparison, or no estimate at all until after the family has already anchored on the misleading headline. CON's own checkout-disclosure concession in [C1.7] proves the accurate number is knowable; the only fight left is timing.
[P4.5] Timing is exactly what the resolution is about. An imperfect-but-adjustable default beats a hidden truth every time a family compares options — and that's the whole debate.

## Turn 8: CON Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 286
- clipped_words: 286
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: Seating proximity is predictable, baggage volume is not – and your DOT point proves it. DOT is pressuring airlines to seat kids next to parents for free, so the accurate price to mandate for that is $0, not a paid seat fee baked into every headline. That is a safety rule, not a luggage forecast. Two adults, two kids ages 4 and 7 searching for a two-night break and a two-month stay enter identical data but need zero versus four checked bags.
[C4.2] Age tells you nothing about that.
[C4.3] A2: An adjustable default doesn't fix light-packers, it punishes them up front and rewrites the motion. The proposition says show the full practical cost including baggage and seating before comparison. A toggle-to-zero admits that full cost isn't true for many families. You would replace a true common unit – the base fare – with a government family carrying one checked bag per adult, then tell backpack-only families to hunt for a toggle to reclaim the $79 fare they used to see instantly.
[C4.4] That's shock pricing, not transparency.
[C4.5] That concession wins this debate. You began saying comparison needs the same true unit, now you defend in [P4.1] and [P4.2] an imperfect, regulator-set estimate you can click away – a nutrition label that pretends to be the grocery bill. Comparison on components works because base fare is actually comparable; your fictional total is wrong for millions by design.
[C4.6] Aggregators can't know co-brand waivers, elite status, or that a family is backpack-only, so your mandatory total systematically misleads to fix a harm already cured at purchase. With accurate all-in totals already required at checkout before you buy, the cheapest option stays visible instead of being buried under a state-mandated guess.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The whole debate collapses to one question: when the default is wrong, who pays for fixing it, and when?
[P5.2] CON never denies that today's headline fare is also a guess — it guesses zero bags, zero seat needs, for every family, including the ones moving house with four suitcases. That guess is baked in silently and corrected only after the click, after the compare, after the psychological anchor has landed. CON's system doesn't avoid fiction. It just hides its fiction behind the word "base fare" and makes the family discover it's wrong at the worst possible moment — mid-checkout, sunk into a choice.
[P5.3] My system puts the same imperfect estimate where it can be corrected for free, before any commitment: one toggle, one click, done. CON keeps calling that "shock pricing," but a number you can adjust before you've chosen anything is not shock. Shock is the $79 that becomes $340 after you've already picked that airline over the alternative.
[P5.4] CON has spent this debate proving no default is perfect. Fine. But between a hidden default that favors the seller and an adjustable default that favors the buyer, comparison only means something under the second one. That's why PRO wins.

## Turn 10: CON Closing

- model: muse-spark-1.1-high
- raw_words: 194
- clipped_words: 194
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6], [C5.7]
- cited_claim_ids: [P5.2]
- missing_claim_id_refs: (none)

[C5.1] A base fare is not a fiction. $79 will put you on that plane tomorrow with backpacks. That's a real price, achievable by every family if they choose it.
[C5.2] The "practical cost" is the fiction. Two adults, two kids can be a weekend with zero checked bags or a month with four. Age doesn't tell you that. Cards, status, and now free family seating don't either.
[C5.3] To comply, regulators must invent one family - one bag per adult, paid seats - and force every search to rank by it.
[C5.4] That is what [P5.2] gets exactly backwards. A $79 base fare being low isn't a guess, it's a minimum. Your $340 mandate being high for a light packer is a guess that is actually wrong.
[C5.5] That doesn't move truth earlier. It replaces a true minimum everyone can buy with a false average most have to hunt to undo with a toggle.
[C5.6] Drip pricing is cured at checkout where the total is knowable because you told the airline what you need. Shock pricing at search buries the cheapest option before you ever compare.
[C5.7] Comparison needs a common true unit. Base fare is that. Your mandate isn't.
