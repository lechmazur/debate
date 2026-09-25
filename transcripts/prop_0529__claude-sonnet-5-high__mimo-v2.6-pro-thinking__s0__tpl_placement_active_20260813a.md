# Debate prop_0529__claude-sonnet-5-high__mimo-v2.6-pro-thinking__s0__tpl_placement_active_20260813a

- topic_id: prop_0529
- proposition: Countries should coordinate public compute and cloud access for academic researchers rather than leave frontier AI research capacity to large firms.
- model_pro: claude-sonnet-5-high
- model_con: mimo-v2.6-pro-thinking
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 348
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Frontier AI research now runs on one input above all others: compute. Training and even serious fine-tuning of state-of-the-art models requires clusters of tens of thousands of GPUs, costing hundreds of millions of dollars. That resource sits almost entirely inside a handful of firms - the same firms whose products, safety claims, and business models academic researchers are supposed to independently evaluate. That is the core problem this motion answers, and it is why coordinated public compute is not a nice-to-have but a structural necessity.
[P1.2] Consider what "leaving it to large firms" actually means in practice. A university lab that wants to study whether a large language model can be manipulated into leaking training data, or whether a specific alignment technique generalizes at scale, cannot run that experiment. They can only study what a firm chooses to expose through an API, at a price the firm sets, under terms of service the firm writes. The firm becomes both the subject of study and the gatekeeper of the tools needed to study it.
[P1.3] That is not a research ecosystem; it is a monitored courtyard.
[P1.4] Coordinated national or multinational compute infrastructure - a public cloud for research, jointly funded and shared across universities - breaks that dependency. It is the same logic that built CERN, national supercomputing centers, and human genome sequencing infrastructure: when a capability becomes too expensive and too consequential for any single institution, states pool resources so that inquiry does not become the exclusive property of whoever can afford it. AI safety research, interpretability research, and bias auditing are exactly the kind of public-good science that private firms are structurally under-incentivized to fund fully, because the findings might slow their own products down.
[P1.5] The comparison the judges should hold onto for the rest of this debate is simple: a world where independent verification of frontier AI is possible, versus a world where it depends on the goodwill of the companies being verified. Coordination doesn't just help academic careers - it is the precondition for AI research remaining a check [clipped]

## Turn 2: CON Opening

- model: mimo-v2.6-pro-thinking
- raw_words: 377
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Public compute for academics is a reasonable add-on. It is a bad substitute. The motion says "rather than," and that word is where it dies.
[C1.2] Start with what the coordinated alternative actually builds. Frontier AI hardware rots fast: clusters that define "frontier" this year are mid-tier two or three years from now. Firms refresh constantly because revenue depends on it. Multinational public infrastructure does not move that way — it moves at the speed of budget cycles, intergovernmental agreements, procurement law, and site selection fights.
[C1.3] By the time a jointly funded cross-border cluster is specified, tendered, and stood up, the research questions that justified it have moved to hardware it does not have. We would spend billions to create a permanently lagging tier of compute and call it access.
[C1.4] Second, the counterfactual is a fiction. Academics are not locked out of compute today; they are priced out of owning it. Those are different problems with different solutions. GPU capacity is a functioning market — cloud providers rent exactly the accelerators frontier labs use, by the hour, including in research-credit and grant-credit programs.
[C1.5] If the concern is that talented labs cannot afford runs, the efficient fix is money: funded compute allocations, procurement vouchers, block grants redeemable at any provider. Notice what that policy is. It buys capacity from large firms rather than replacing it. The proposition's own stated goal collapses into a subsidy and procurement program, and its distinctive mechanism — states coordinating and operating frontier-scale public infrastructure — becomes unnecessary overhead.
[C1.6] Third, coordination introduces a worse gatekeeper than the one it removes. A public cluster at frontier scale is scarce, so somebody allocates it: a national body, a multinational board, a review committee with priorities set by whichever ministries fund it. That means topic triage, national-interest tests, and geopolitical bargaining over which country's researchers get which quotas — the export-control and alliance politics we already see applied to chips, now applied to who may run what experiments. A firm's terms of service constrain some work; a state allocation board decides [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON's whole case rests on one move: pretend the motion demands academics out-race Nvidia's newest chips. It doesn't. Public compute coordination succeeds if it lets researchers run independent, reproducible, large-scale experiments without asking permission from the company they're studying. CERN's magnets were never "frontier" compared to whatever the newest physics equipment was that year either — the point was never speed parity, it was independent capability.
[P2.2] A two-year-old cluster is still fully capable of testing whether an alignment technique generalizes, whether a model leaks training data, whether bias persists across scale. "Slightly behind the absolute frontier" is a research platform. "Zero platform, rent-by-the-hour access on the subject's own terms" is not.
[P2.3] That exposes the hole in C1.4 and C1.5. "Academics are priced out, not locked out" only works if what's for sale is what researchers need. It isn't. Cloud vendors rent GPU-hours against a firm's API; they do not sell weight access, training logs, internal activation data, or the right to fine-tune the base model without a monitoring agreement.
[P2.4] No voucher program buys that, because it isn't on the market — the firm chooses what to expose, at what granularity, under what NDA. A subsidy check written to the very company under study cannot manufacture independence that the company has decided not to grant.
[P2.5] And C1.6's "worse gatekeeper" argument actually cuts against CON. Yes, a public allocation board sets priorities — but it does so under freedom-of-information law, legislative oversight, and academic peer review, the same mechanisms that already govern national supercomputing grants. A firm's terms of service answer to shareholders and legal risk, full stop. Replacing an unaccountable gatekeeper with an accountable one, even an imperfect one, is precisely the improvement AI oversight needs — not overhead, but the actual mechanism through which independent verification becomes structurally possible rather than optional.

## Turn 4: CON Rebuttal 1

- model: mimo-v2.6-pro-thinking
- raw_words: 329
- clipped_words: 329
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO's strongest point — vendors won't sell weight access, training logs, or activation data — is the one that sinks the motion. Public compute doesn't conjure those either. A state cluster gives you silicon; it does not give you the weights of a model another lab trained. The scarce good PRO names is model access, and the mechanism on the table — coordinate compute — is orthogonal to it.
[C2.2] If researcher access to weights and internals is the binding constraint, the fix is a regulatory access regime: mandated researcher credentials, vetted audit agreements, disclosure duties imposed on the firms holding the models. That works whether the GPU-hours come from a public rack or a rented one, and it needs no multinational cluster. PRO's own framing quietly converts this from a debate about compute into a debate about access regulation — not the proposition.
[C2.3] Second, CERN is doing work it cannot do. At CERN, the instrument is where the physics happens: build the machine and you can run the collision. The frontier-model analogue is the training run that produced them — inside a firm, on their data, with their recipe. A year-lag public cluster gives you a lab to build lesser models of your own.
[C2.4] That is real science, and universities already run it on national supercomputing allocations. It is not independent verification of the deployed frontier systems PRO says we must check.
[C2.5] Third, "freedom-of-information law and legislative oversight" is asserted, not shown. The motion says countries coordinate: a multinational allocation board sits above any single FOI regime, and its quotas will be set by the same export-control and alliance bargaining already visible on chips. A firm's terms of service can at least be bargained with; an intergovernmental quota pact cannot be appealed by one lab. PRO promised accountability and delivered bureaucracy with flags on it.
[C2.6] Targeted researcher-access rules plus flexible compute procurement secure independence at a fraction of the cost — and without building a permanently lagging public tier.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 72
- clipped_words: 72
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If researcher-access regulation is CON's fix, where do vetted auditors run the mandated audits — on compute they still don't own, rented from the firm they're auditing? Doesn't that just re-import the dependency PRO named?
[P3.2] Q2: The motion allows national coordination, not only a single multinational board. Why does CON's "quota pact with flags on it" objection apply to a national public-cloud program overseen by existing domestic FOI and grant-review law?

## Turn 6: CON Pressure Questions

- model: mimo-v2.6-pro-thinking
- raw_words: 72
- clipped_words: 72
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Rented hardware still runs mandated audits; independence comes from legal access rights, not rack ownership. So name one audit PRO can run on a public cluster that it cannot run on rented silicon under the same access regime.
[C3.2] Q2: If PRO retreats to purely national programs, what happened to "coordinate"? Fragmented national clusters just duplicate cost and reintroduce the geopolitical quota politics PRO dismissed — so which horn does PRO take?

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The audit that rented silicon cannot host safely is the long-duration, high-volume adversarial stress test — running thousands of jailbreak variants, fine-tune probes, or interpretability sweeps continuously over months. Under rented compute, the firm being studied still sets the meter: it can throttle usage, change API terms mid-study, revoke access when findings get uncomfortable, or price sustained access out of reach. Legal access rights on paper don't stop a firm from making the infrastructure itself unreliable or unaffordable for exactly the research that threatens it.
[P4.2] A public cluster, once regulation grants the access right, removes that commercial leverage entirely — the audited party no longer controls the meter on its own audit. That's not a difference in silicon quality; it's a difference in who can quietly strangle the study.
[P4.3] A2: No retreat. "Countries coordinate" was never limited to one supranational allocator — it covers interoperable national programs bound by shared research-access standards, the same way national supercomputing centers already share reciprocal access without one central quota board. That avoids CON's single-point quota-politics image while still capturing the economies of scale and mutual recognition that make coordination worth doing. CON built a strawman version of coordination to attack, then declared victory when I declined to defend it.
[P4.4] Both answers point at the same collapse in CON's case: C2.1-C2.2 concede that model access is the binding constraint, then hand the compute layer straight back to the firms being audited. That reunites the auditor's infrastructure with the auditor's subject — the exact dependency this motion exists to break. National, standards-linked public compute is the only version of "researcher access" where the entity under investigation cannot also decide whether the investigation keeps running. CON's fix regulates the front door while leaving the firm holding the building's power switch.

## Turn 8: CON Rebuttal 2

- model: mimo-v2.6-pro-thinking
- raw_words: 372
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [C3.1]
- missing_claim_id_refs: (none)

[C4.1] A1: PRO's answer quietly shifts the fight from capability to reliability, and even there it loses. Rented silicon — from several independent providers, or from existing national supercomputing allocations — hosts exactly the sustained workloads PRO describes. Thousands of jailbreak variants and interpretability sweeps are just long GPU jobs, and long jobs are what procurement contracts are for: escrowed multi-month allocations, service-level terms, multi-provider redundancy. If a mandated access regime can compel a firm to release weights and logs, it can equally bar that firm from sabotaging the audit it has been compelled to submit to — and that is enforced by courts, not by rack ownership.
[C4.2] [C3.1] still stands: PRO has not named one audit a public cluster runs that rented or academic silicon under identical access rights cannot. And notice what PRO's own framing concedes: once the mandated weights move to the auditor's machine, that machine can be rented. The firm no longer holds the power switch.
[C4.3] A2: "Interoperable national programs bound by shared research-access standards," with "reciprocal access" and "mutual recognition" — that is not states coordinating public compute in place of large firms. That is states coordinating rules, credentials, and purchasing while researchers still buy GPU-hours and model access from commercial providers. It is C1.5's policy wearing PRO's colors. If that is the landing zone, PRO has conceded the motion's "rather than": frontier capacity remains with the firms, public money flows into their clouds, and coordination happens at the regulatory layer where CON always said it belonged.
[C4.4] Meanwhile the domestic-board variant still leaves a scarce public tier rationed by national-interest priorities — the quota politics PRO tried to wave away, now just with one flag instead of several.
[C4.5] The debate has narrowed to one question: does publicly owned compute do any work that legal access rights plus funded procurement do not? PRO's A1 answer is about contract enforcement, not silicon. PRO's A2 answer keeps commercial clouds inside the research loop by design. What is left is a permanently lagging, expensively operated public tier no audit uniquely [clipped]

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 202
- clipped_words: 202
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] This debate comes down to one question CON never actually answers: what happens the day a firm decides an audit is going badly for it?
[P5.2] CON's whole fix — "courts enforce the access rights, not rack ownership" — assumes enforcement is instant and costless. It isn't. Contracts get breached first and litigated second. A firm facing an embarrassing jailbreak study or a training-data leak can throttle bandwidth, cite a vague terms-of-service clause, or simply "have an outage" for the months a lawsuit takes to resolve.
[P5.3] By the time a court rules, the research window has closed and the finding is stale. That is not a hypothetical gap in CON's model — it is the structural weakness of putting the auditor's infrastructure inside the auditee's market.
[P5.4] Public ownership doesn't need to win that fight, because it removes the leverage before it's ever exercised. Nobody can throttle a machine they don't operate. That is the difference between a right you must sue to enforce and a capability you simply hold.
[P5.5] CON offered faster procurement. PRO offers the one thing procurement can't buy: an audit that can't be quietly starved by its own subject. That is why coordination, not contracts, is what independence actually requires.

## Turn 10: CON Closing

- model: mimo-v2.6-pro-thinking
- raw_words: 223
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO's closing turns on one claim: firms can quietly starve an audit, so independence requires publicly owned silicon. Grant the fear. It still fails on its own logic, because the leverage PRO describes doesn't live in the GPU-hours.
[C5.2] A firm threatened by a jailbreak study does not need to throttle a rented cluster. It withholds the weights, the training logs, the activation data — the inputs PRO itself named as the scarce good. A public rack with none of those hosts nothing; the audit stalls just as silently, and no amount of copper in a national facility changes it. The auditee's power switch was never the power meter.
[C5.3] It is the model.
[C5.4] That is the whole debate in one line: PRO has identified a real dependency and prescribed a remedy that does not touch it. The thing that makes an audit starvable is discretionary model release, and the fix for that is a legal access regime — mandated researcher credentials, compelled disclosure, escrowed weights — enforced against the party holding the goods. That regime works identically on rented silicon, on national supercomputing allocations, or on anything else.
[C5.5] What the motion uniquely buys is billions spent on a lagging public tier that still leaves the actual gatekeeper's gate standing. When the remedy for access is more hardware, you have misdiagnosed the [clipped]
