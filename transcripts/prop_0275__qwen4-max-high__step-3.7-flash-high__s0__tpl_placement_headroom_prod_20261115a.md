# Debate prop_0275__qwen4-max-high__step-3.7-flash-high__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0275
- proposition: Vacation-rental platforms should be required to show cleaning fees, resort fees, and house rules before users click into checkout or request to book.
- model_pro: qwen4-max-high
- model_con: step-3.7-flash-high
- side_swap: False

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A nightly rate that no guest can actually pay is not a price; it's bait. When a platform lets a listing advertise $120 a night and then adds a $90 cleaning fee and a $35 resort fee at checkout, the search results are ranked by a number nobody pays. Sorting by price — the single most basic tool a marketplace offers — becomes actively misleading. The proposition simply asks that the number used to attract a click be the number the guest will owe.
[P1.2] House rules matter for a different reason: they aren't fine print, they're conditions of the product. No pets. No children under twelve. A mandatory ID upload.
[P1.3] Checkout chores at 10 a.m. A family that filters for pet-friendly, spends an hour comparing kitchens and driveways, and only then learns the host forbids dogs hasn't been informed — they've been used. Material terms that can disqualify you belong before you invest in the choice, not after you've requested to book and handed over your card details.
[P1.4] The mechanism here is well understood in ordinary retail: reveal costs late, and people anchor on the low figure and finish the transaction because starting over is expensive. That's not a market working; it's a market exploiting the cost of starting over. And the fix is cheap. These fees are already calculated by the platform's own software — it must compute them to display them at checkout.
[P1.5] Nothing new is created by moving them one screen earlier. Airlines were pushed to all-in pricing and survived; competition got sharper, not weaker.
[P1.6] So the burden on the other side is specific: name who is genuinely better off learning the real price later, and why that benefit outweighs a guest misled at the moment of comparison.

## Turn 2: CON Opening

- model: step-3.7-flash-high
- raw_words: 300
- clipped_words: 300
- claim_ids: [C1.1], [C1.2], [C1.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The PRO side’s framing mistakes dynamic, booking-dependent costs for deceptive bait-and-switch, ignoring the real tradeoffs of rigid pre-checkout disclosure. Cleaning fees are not static line items: they scale directly with group size and length of stay. A solo traveler booking a 1-night stay might face a $50 cleaning fee, while a family of four staying a week will be charged $120 to cover extra laundry and trash removal. Requiring hosts to list a single fixed cleaning fee before a user even enters their group size or dates would force hosts to either inflate base rates to cover worst-case cleaning costs, or post a misleadingly low fee that jumps at checkout anyway—making the problem the PRO side highlights worse for guests.
[C1.2] Resort fees, similarly, often depend on the number of occupants and amenities selected, so a pre-checkout display would be either inaccurate or useless. House rules, too, are not rigid product conditions as the PRO side asserts, but flexible guidelines hosts use to manage properties and accommodate guest needs. A host may list a “no late-night noise” rule but waive it for a guest with a medical condition who needs to rest during the day, or adjust a 10 a.m. checkout time for a traveler with a late flight if asked.
[C1.3] Mandating that every rule be displayed as a non-negotiable condition before booking eliminates this flexibility, pushing hosts to enforce harsh one-size-fits-all policies that alienate reasonable guests with needs. The PRO side claims the fix is “cheap” but ignores that platforms would have to spend millions rebuilding interfaces to display dynamic fees that cannot be accurately calculated without booking details, plus train hosts to rewrite flexible rules as rigid fine print. All these costs get passed directly to guests via higher base rates, hurting the travelers the proposition claims to protect.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.1]
- missing_claim_id_refs: (none)

[P2.1] Notice what my opponent's case requires: that the platform cannot know the cleaning fee until checkout, yet somehow knows it exactly at checkout. No new information arrives between those two screens. The guest has already typed dates and party size into search — that's how the calendar and the occupancy filter work. The same inputs that produce $120 at checkout produce $120 on the listing.
[P2.2] [C1.1] isn't an argument about feasibility; it's an argument about placement, which is precisely what the motion changes.
[P2.3] And if a fee genuinely varies, show the schedule: $50 for one guest, $120 for four. A range, a per-guest line, a "from" figure — any of these beats a number chosen to win the sort. CON's answer to imperfect disclosure is no disclosure. That trade is indefensible.
[P2.4] The inflation point defeats itself. If folding cleaning costs into the base rate makes a listing look worse, that is an admission that the low nightly figure was doing deceptive work. Same total, honestly presented, is not a harm to guests; it's the harm ending.
[P2.5] On rules, CON has swapped disclosure for rigidity. Nothing in this motion forbids a waiver. "No late-night noise" displayed on the listing is still a rule a host can relax for a guest with a medical condition — and now that guest can ask before paying, instead of discovering the conflict after handing over a card. CON's own example is an argument for early disclosure: flexibility is only useful to someone who knows the rule exists.
[P2.6] The "millions" are a guess; checkout already renders these figures. Nothing new is built — a number moves one screen earlier, and the flexibility survives untouched. What doesn't survive is the profitable gap between the price that attracts the click and the price the guest owes.

## Turn 4: CON Rebuttal 1

- model: step-3.7-flash-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [C2.1], [C2.2], [C2.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO’s entire feasibility argument rests on a false assumption: that users input all booking details before they click a listing. In reality, most travelers browse aggregated search results scrolling past $120 headline rates, only entering stay dates, group size, and amenity requests after landing on a property page. Requiring exact fee totals on the initial search page would force platforms to either display static placeholder fees that jump dramatically once users input their actual trip details, or eliminate variable fee structures entirely, raising base rates for all guests to cover worst-case cleaning costs.
[C2.2] That replaces one misleading number with another, higher one—hardly the win PRO claims. Unlike airline tickets, where passenger count is fixed before fare display, vacation rental cleaning fees scale with stay length and group size, parameters not available until a user is already on a specific listing page, making pre-search exact fee calculation impossible without breaking the core search experience. PRO also insists house rule flexibility will survive pre-checkout disclosure, but platform compliance systems will erase it. A rule reading “no late-night noise, exceptions for medical needs” will be flagged as ambiguous by automated moderation tools, forcing hosts to either strip the exception or post a rigid no-waiver rule to avoid liability.
[C2.3] Hosts will not risk being held responsible for unapproved waivers, so the very flexibility PRO cites as a benefit will be eliminated by platform enforcement. PRO dismisses implementation costs as a “guess,” but rebuilding search infrastructure to calculate dynamic per-booking fees in real time across millions of listings, and retraining hosts to rewrite flexible terms as rigid pre-checkout fine print, carries non-negligible operational costs that will be passed directly to guests via higher service fees, undoing any theoretical benefit of earlier disclosure.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: The motion requires disclosure before checkout or request to book — not on the initial search grid. Since your entire feasibility case attacks search-page totals, what objection survives once fees appear on the listing page, where dates and guest count are already entered?
[P3.2] Q2: Where does the motion say a host must strip a medical exception? If nothing does, is your moderation-and-liability story anything more than a guess about how platforms might choose to comply?

## Turn 6: CON Pressure Questions

- model: step-3.7-flash-high
- raw_words: 95
- clipped_words: 95
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Your entire feasibility case assumes pre-checkout disclosure requires showing fees on the initial search grid, but the motion only mandates disclosure before checkout or booking request, after users enter dates and group size on the listing page where all dynamic fee variables are known. What objection remains to accurate fee display?
[C3.2] Q2: You claim platforms will force hosts to strip flexible rule exceptions to avoid liability, but the motion only requires disclosing existing house rules, not rewriting them as rigid terms. What evidence supports your claim that platforms would impose that extra, unrequired change?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.1], [C2.2]
- missing_claim_id_refs: (none)

[P4.1] A1: None — and that is the concession this debate turns on. Once fees appear on the listing page after dates and party size are entered, every variable CON called unknowable is known. [C2.1]'s picture of travelers scrolling past headline rates is an argument about the search grid, which the motion never touches. The listing page is pre-checkout.
[P4.2] The objection dissolves at the exact line the motion draws.
[P4.3] A2: No evidence, because I never made that claim — CON did, in [C2.2]: moderation tools "flagging" medical exceptions, hosts stripping waivers to dodge liability. That is a chain of speculation about how platforms might choose to comply with a rule that only asks them to display what they already wrote. A disclosed rule and an enforceable rule are different things; hosts waive noise limits and checkout times every day under today's disclosure. If CON wants rigidity counted as a cost of this motion, CON has to show the motion causes it.
[P4.4] Asking me to prove a negative doesn't supply that link.
[P4.5] So weigh what's left. On one side: a guess about interface rebuilds, and a guess about moderation behavior, both offered as reasons to keep a checkout surprise. On the other: the guest with a dog who spends an hour comparing kitchens before learning dogs are banned, and the traveler whose $120 nightly rate becomes $245 after fees they could have been shown one screen earlier.
[P4.6] And CON's fallback — that disclosure "replaces one misleading number with another, higher one" — concedes the whole case. A higher number you actually pay is not misleading; it is the price. The only thing late disclosure protects is the advantage of not being compared honestly. CON still hasn't named one guest better off learning the real figure later.

## Turn 8: CON Rebuttal 2

- model: step-3.7-flash-high
- raw_words: 305
- clipped_words: 305
- claim_ids: [C4.1], [C4.2], [C4.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: That concession is far narrower than PRO claims. Even on the listing page where dates and guest count are entered, platforms will still default to displaying the lowest possible cleaning fee as a headline “from” figure, which anchors users the same way the current low nightly rate does—guests will still latch onto that low number, scroll past, and only notice the higher actual fee once they’re already invested in the listing, replicating the checkout surprise PRO decries. Resort fees, meanwhile, are often tied to add-ons like parking or pool access selected after the base fee displays, so the “pre-checkout” figure would still be incomplete and misleading.
[C4.2] A2: PRO disavows the moderation claim, but their own framing of the motion as a simple “display what you already wrote” rule ignores how platform compliance teams operate. When house rules are marked as pre-book binding conditions, automated moderation systems will flag any rule with carve-outs or exceptions as ambiguous, because ambiguous terms create liability for the platform if a guest claims they were misled. Hosts will be forced by interface constraints to either remove medical or accessibility exceptions entirely or rewrite rules as hard, non-waivable conditions to avoid moderation flags, eliminating the flexibility PRO cites as a benefit.
[C4.3] Weigh the tradeoffs: PRO’s case rests on an idealized view of disclosure that ignores real market incentives and platform operational pressures. The supposed benefit of earlier fee display is either undermined by anchoring to low “from” figures or outweighed by the certain harm of higher base rates, as hosts bake worst-case cleaning costs into nightly prices to avoid dynamic fee confusion, and the loss of rule waivers that help travelers with unique needs. CON wins because the motion’s costs are real and immediate, while PRO’s promised benefits are unproven and easily erased by the systems the rule would create.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Every harm CON has named needs a second decision this motion never requires. Platforms must choose to headline a misleading "from" figure. Moderators must choose to strip medical exceptions. Hosts must choose to bake worst-case cleaning into nightly rates.
[P5.2] The motion asks for one thing: show the fee and the rules you already wrote, before the guest commits. Nothing in it licenses those choices — and if a platform games a "from" label, that is a labeling failure to police, not a reason to keep the fee hidden entirely. CON's answer to imperfect disclosure is still no disclosure.
[P5.3] The harm on my side needs no second decision. It happens by default, every night, on every listing where the sorting number isn't the payable number. That asymmetry decides this debate: a certain, structural deception versus a chain of predictions about compliance behavior CON has never evidenced.
[P5.4] And CON's anchoring complaint concedes the mechanism — numbers shown early change what people choose. That is precisely why they must be true. Still, no one has named a single guest better off learning the real price later. Only hosts better off not being compared honestly.

## Turn 10: CON Closing

- model: step-3.7-flash-high
- raw_words: 199
- clipped_words: 199
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s entire case rests on a fantasy of compliant implementation that no market incentive will support. They ask us to assume platforms will display accurate dynamic fees without anchoring guests to misleading low “from” figures, and that moderation systems will preserve flexible rule waivers even when ambiguous terms create liability. CON already proved variable cleaning fees cannot be accurately displayed pre-checkout without either misleading placeholders or across-the-board rate hikes, and PRO’s only answer is to pretend those incentives don’t exist.
[C5.2] The rule creates exactly the pressures that will erase any theoretical benefit: hosts will bake worst-case cleaning costs into inflated base rates to avoid dynamic fee confusion, and platforms will strip rule exceptions to dodge moderation flags, leaving guests paying more for less flexibility, with no reduction in misleading price signals. The certain, immediate costs of this rule — higher base rates for every traveler, lost accommodation for guests with medical or accessibility needs — outweigh PRO’s speculative, unenforceable benefits.
[C5.3] PRO has never named a single guest better off under this mandate, because the only guaranteed outcome is that guests pay more for the same stays, with no fix to the comparison shopping problem PRO claims to care about.
