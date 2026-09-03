# Debate prop_0273__qwen3.8-max__gemini-3.8-flash-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0273
- proposition: Airlines and booking sites should have to show the full practical cost of a family trip, including baggage and seating, before users compare options.
- model_pro: qwen3.8-max
- model_con: gemini-3.8-flash-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen3.8-max
- raw_words: 327
- clipped_words: 327
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The core of this debate is whether comparison tools should compare real choices or marketing hooks. For family travel, the headline fare is often not the price a household will actually pay. Parents cannot reasonably send children away with no checked baggage, and airlines often charge for carry-ons or checked bags. They also cannot safely or practically let young children sit scattered across the cabin, yet many low fares charge extra for seat selection or only offer middle seats unless families pay.
[P1.2] Once those add-ons are included, a fare that looks cheap can become one of the most expensive options.
[P1.3] The proposition asks for disclosure at the point where consumers compare options, not after they have entered dates, passenger details, and payment information. That timing matters. Sorting and filtering are the decisive moments. If a family can rank only by base fare, the interface systematically rewards airlines that hide essential costs and punishes carriers whose sticker price is more honest.
[P1.4] That is not neutral competition; it is a subsidy for drip pricing. Requiring the full practical cost up front lets the market compete on the number that actually matters.
[P1.5] This is especially important for families because their trip costs scale in ways solo travelers can avoid. A single business traveler may bring a backpack and take any seat. A family of four usually needs multiple bags, and the adults need to sit with children. Those are not luxury preferences; they are the ordinary requirements of the trip.
[P1.6] If a booking site displays $99 per person but the realistic total with baggage and adjacent seats is $260, the family has not been given a comparable price. It has been given an anchor.
[P1.7] The requirement also preserves choice. Airlines can still unbundle, offer basic fares, and charge for extras. The rule simply says: before you ask customers to compare, show them what the trip will actually cost. That makes advertising more truthful, search less manipulative, and competition more efficient.

## Turn 2: CON Opening

- model: gemini-3.8-flash-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.5], [P1.7]
- missing_claim_id_refs: (none)

[C1.1] The proposition confuses fee transparency with a rigid mandate that breaks travel search. Requiring platforms to calculate the "full practical cost" of a family trip *before* users can compare options creates two fatal problems: it relies on a fictional standard of "practicality," and it paralyzes consumer discovery.
[C1.2] First, "practical cost" is entirely subjective. PRO assumes that every traveling family requires identical, expensive add-ons: multiple checked bags and premium seat-selection fees [P1.5]. In reality, families are not a monolith. A family of four taking a four-day trip often shares two carry-ons, while airlines and regulators increasingly seat minors beside parents without extra charges.
[C1.3] To show a single total upfront, booking engines would have to fabricate a standardized bundle. If an algorithm defaults to four checked bags and four seat fees, it artificially inflates the displayed fare by hundreds of dollars. That punishes price-sensitive families who deliberately economize, misleading them into believing they cannot afford to fly.
[C1.4] Second, the motion's timing mandate destroys search functionality. To display a realistic total before comparison begins, booking engines cannot simply show flights for "two adults and two kids." They would have to demand an exhaustive pre-search intake form: exact luggage counts, bag dimensions, passenger ages, and specific seating preferences before revealing a single schedule or price. This erects massive friction against exploratory browsing.
[C1.5] Parents comparing multiple weekends, alternate airports, or destination options would be forced through a bureaucratic questionnaire on every single search.
[C1.6] Unbundled pricing empowers families to control their own budgets. PRO claims this preserves choice [P1.7], but forcing arbitrary bundled totals into the initial sorting mechanism distorts competition and obscures the true lowest-cost carrier. The proper remedy for hidden fees is clear, standardized disclosure of optional add-ons alongside baseline fares—not forcing algorithms to guess every family's unique trade-offs and display an arbitrary total before comparison even begins.

## Turn 3: PRO Rebuttal 1

- model: qwen3.8-max
- raw_words: 306
- clipped_words: 306
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] My opponent’s case rests on a false choice: either show only the headline fare or force every family to fill out an exhaustive questionnaire. The proposition does neither. It says that once a user asks for a family trip, the price used for comparison must include the costs a family ordinarily cannot avoid: bags and sitting with children. That can be done with a simple, disclosed default—two adults, two children, standard baggage, adjacent seats—and then adjusted with one or two toggles before sorting.
[P2.2] The alternative is not precision; it is leaving the comparison field anchored to a number the family is unlikely to pay.
[P2.3] The “subjective” objection proves too much. Every price disclosure uses a default. Tax-inclusive airfare, hotel taxes, or a car rental’s mandatory fees are not perfect estimates of each traveler’s preferences, but they are better than advertising a sticker price and revealing the real total at checkout. If the standard is disclosed and editable, it is not fabrication; it is comparability.
[P2.4] Their claim that families are not a monolith actually strengthens the need for full-cost comparison. Some families travel light; some need checked bags. Some carriers seat children with parents, some only if the fare class or seat fee allows. Those differences are exactly why a consumer cannot reliably sort by base fare.
[P2.5] Clear standardized totals let families see which airline is cheap under the assumptions they choose, instead of discovering it after clicking through.
[P2.6] Finally, the proposed remedy—baseline fare plus a menu of add-ons—does not solve the problem. It leaves sorting, filtering, and initial ranking controlled by the misleading number. A family can be shown $99 plus a list of fees, but the interface still ranks them against $120 fares whose bags and seats are included. If the goal is consumer choice, comparison must begin with the practical total, not an anchor.

## Turn 4: CON Rebuttal 1

- model: gemini-3.8-flash-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.3], [P2.1]
- missing_claim_id_refs: (none)

[C2.1] PRO’s case collapses on a fundamental false equivalence. My opponent equates practical family costs to mandatory hotel taxes and airport fees [P2.3]. But mandatory taxes are fixed and unavoidable for every passenger. Baggage and seat assignments are not.
[C2.2] They are variable, operational choices.
[C2.3] By retreating to an arbitrary "disclosed default" [P2.1], PRO concedes our core argument: a search engine cannot know the "practical cost" without making crude guesses. And those guesses actively harm consumers. If an algorithm defaults to four checked bags and four paid seat selections, it fabricates an inflated phantom price. Consider an ultra-low-cost flight at $50 and a full-service flight at $110.
[C2.4] A frugal family sharing two carry-ons actually pays $65 on the budget carrier. But under PRO's mandatory default bundle, that budget carrier is weighed down with hundreds of dollars in assumed fees, artificially appearing more expensive and getting buried in the search rankings. PRO does not eliminate distortion; it institutionalizes a distortion that penalizes price-sensitive households and rewards higher-priced legacy carriers.
[C2.5] Furthermore, PRO’s proposed fix traps them in a dilemma. If platforms require users to adjust "toggles before sorting" [P2.1] to see accurate results, PRO admits the exact search friction we warned against—locking basic schedule and price discovery behind mandatory preference inputs. If platforms sort by default before toggling, they deceive consumers with an arbitrary number.
[C2.6] Finally, PRO ignores reality regarding seating. Airlines and regulators increasingly ensure young children sit with a parent at no extra cost. Forcing seat-selection fees into the default upfront cost compels families to evaluate tickets burdened by a phantom surcharge for a service they legally or practically already receive.
[C2.7] The honest solution is not forcing algorithms to invent an arbitrary bundle before families can even browse. It is displaying unbundled baseline prices alongside transparent, clear add-on menus that let families calculate their own reality.

## Turn 5: PRO Pressure Questions

- model: qwen3.8-max
- raw_words: 54
- clipped_words: 54
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Under your remedy, if sorting still uses base fare and add-ons appear only in a menu, how does a family identify the truly cheaper trip before clicking?
[P3.2] Q2: If you reject any disclosed default for bags and seating, how can platforms show total family costs without requiring the very detailed intake you condemn?

## Turn 6: CON Pressure Questions

- model: gemini-3.8-flash-high
- raw_words: 69
- clipped_words: 69
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: When airlines already seat children beside parents without charge, doesn't your mandated default seat fee artificially inflate budget fares and mislead families by ranking genuinely cheaper flights as more expensive?
[C3.2] Q2: Because the proposition mandates showing the full practical cost *before* users compare options, how can any booking site calculate that total without either imposing arbitrary bundled defaults or forcing travelers through a mandatory questionnaire before displaying results?

## Turn 7: PRO Rebuttal 2

- model: qwen3.8-max
- raw_words: 307
- clipped_words: 307
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C2.7]
- missing_claim_id_refs: (none)

[P4.1] A1: No. If an airline truly seats a child beside a parent at no extra charge, the default total should count that fee as zero and label it included. The default is not an invented surcharge; it is the cost of the family’s necessary condition—guaranteed adjacent seats and ordinary baggage. Where budget fares leave that to chance at check-in, the practical cost includes the least-cost way to make it certain. That makes genuinely cheaper family products easier to find, not harder.
[P4.2] The supposed inflation is only inflation relative to a headline price the family would not actually pay. A zero fee where it exists is not inflation; it is a competitive advantage that base-fare sorting hides.
[P4.3] A2: Platforms can do this without a questionnaire because the user has already supplied the core facts: origin, dates, and “two adults, two children.” The motion’s “before users compare options” means before results are ranked, not before any search input. The site applies a disclosed, editable family default—standard bags and adjacent seats—and lets users toggle up or down before sorting. That is not an exhaustive intake; it is the same kind of convention used when prices include mandatory taxes. The only alternative is to let comparison run on a number stripped of predictable costs.
[P4.4] These answers decide the debate. CON keeps saying the fix is a menu of fees [C2.7], but a menu does not change what the interface ranks. If sorting still uses base fare, the family sees the $99 anchor above the $120 inclusive fare, even though the first will cost more once bags and seats are added. PRO’s disclosed default can be imperfect, but it is corrigible: users can adjust it.
[P4.5] CON’s base-fare sorting is misleading by design. If their worry is an overinclusive default, the answer is better disclosure and toggles, not preserving a false starting point.

## Turn 8: CON Rebuttal 2

- model: gemini-3.8-flash-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.3], [P4.4], [P4.1], [P2.3]
- missing_claim_id_refs: (none)

[C4.1] A1: By viewing clear, standardized fee tags alongside the base fare directly on each search card—such as "+$30 bag, free family seating"—before clicking through. Families instantly calculate their own needs without booking engines fabricating an arbitrary bundled sum that hides the true entry price.
[C4.2] A2: Platforms cannot, which exposes why the proposition is unworkable. PRO concedes in [P4.3] that their "practical cost" is merely an arbitrary guess ("an editable family default") requiring users to "toggle up or down before sorting." That confirms our dilemma: platforms must either force families through pre-search preference toggles before displaying flights, or rank flights using inaccurate assumptions that distort true prices.
[C4.3] This concession decides the debate. By admitting that any pre-comparison total is merely an "imperfect default" [P4.4], PRO abandons actual practical costs for manufactured costs that mislead consumers.
[C4.4] Consider the harm in practice. In [P4.1], PRO insists their default must include the "least-cost way to make it certain" that families sit together, treating paid seat-selection fees as mandatory whenever an airline does not formally guarantee adjacent seating until check-in. This systematically distorts the market. A frugal family taking a two-hour flight may gladly rely on automated seat assignment at check-in and share two carry-ons.
[C4.5] Yet PRO’s mandate forces search engines to slap hundreds of dollars in phantom seat fees and checked-bag charges onto that budget ticket before comparison even begins.
[C4.6] The result is anti-competitive distortion. A $200 legacy fare with included bags is artificially ranked above a $60 budget fare burdened by PRO's arbitrary $160 phantom bundle, even though that family would actually pay only $80. PRO calls this "comparability" [P2.3], but ranking options against an algorithm's fictional bundle is not transparency—it is price distortion. Real consumer protection preserves unbundled base fares alongside transparent, itemized fee disclosures, empowering families to calculate their own reality rather than having platforms dictate what is practical.

## Turn 9: PRO Closing

- model: qwen3.8-max
- raw_words: 183
- clipped_words: 183
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive point is simple: comparison cannot be fair if it is sorted by a number the family is not actually offered. My opponent’s remedy keeps the base fare in command of the screen—ranking, filtering, and order—while putting the real costs in a side menu. That leaves families choosing among anchors, not trips.
[P5.2] PRO’s default is not a fantasy price; it is the least-cost way to make the ordinary family requirements certain: bags enough for children, seats that keep parents beside young kids. If an airline provides those without charge, the total should show zero and the airline gains rank. That is how truthful competition works.
[P5.3] CON’s real objection is that any default can be edited or improved. But an editable default can be wrong in a visible, correctable way. Base-fare sorting is wrong in a hidden, structural way: it rewards carriers that advertise low and charge later. If the choice is between a corrigible estimate and a persuasive anchor, consumer protection requires the estimate.
[P5.4] Vote PRO because only our rule makes the first price families compare the price they can actually pay.

## Turn 10: CON Closing

- model: gemini-3.8-flash-high
- raw_words: 190
- clipped_words: 190
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P4.4], [P4.1]
- missing_claim_id_refs: (none)

[C5.1] This debate turns on a single, decisive reality: you cannot mandate a “practical cost” without forcing an algorithm to dictate what a family needs.
[C5.2] PRO concedes that practical costs are not fixed taxes, but an “imperfect default” [P4.4] that guesses how many bags a family packs and whether they must purchase seat assignments [P4.1]. That concession is fatal. When a booking platform is forced to calculate an arbitrary bundle before families can compare options, it doesn't eliminate misleading prices—it manufactures them.
[C5.3] Consider what that means for a frugal household. A family sharing two carry-ons and accepting automated seat assignments could fly for $80 on a budget carrier. Under PRO’s rule, the platform slaps hundreds of dollars in assumed seat-selection fees and checked-bag surcharges onto that ticket before comparison begins, burying it beneath a $200 legacy fare. An algorithm’s fictional bundle has now misled that family into believing travel is unaffordable.
[C5.4] True transparency does not mean letting algorithms invent phantom totals that penalize price-conscious families. It means showing real baseline fares alongside clear, unbundled fee disclosures, empowering parents to calculate their own reality. For honest comparison and consumer choice, vote CON.
