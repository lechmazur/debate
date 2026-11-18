# Debate prop_0537__qwen4-max-high__claude-fable-5-1-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0537
- proposition: Governments should build sovereign AI compute capacity for critical public-interest uses rather than depend heavily on private cloud providers and foreign infrastructure.
- model_pro: qwen4-max-high
- model_con: claude-fable-5-1-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a hospital network is hit by ransomware, nobody asks whether the fallback system was cost-efficient. They ask whether it exists, and whether someone else can turn it off. That is the test this motion should be judged by: not average-day price, but worst-day control.
[P1.2] Heavy dependence on private and foreign cloud turns national capability into a contractual permission. Terms of service, acceptable-use policies, sanctions, export controls, or a vendor's commercial pivot can revoke access to the machines running outbreak modelling, grid balancing, benefits integrity, and defence logistics. Export controls on advanced accelerators have already made the point plainly: compute is treated as a strategic good by the countries that produce it, and supply is political. A state that assumes the market will always deliver is assuming other governments never change their minds.
[P1.3] Jurisdiction compounds it. Workloads and data held under another country's legal reach can be compelled or blocked by decisions our citizens never voted on. And lock-in compounds it again: once models, pipelines and staff are built around one provider, renewal pricing is whatever that provider says. A state negotiates badly from captivity.
[P1.4] Owning a floor restores leverage even over the workloads that stay commercial.
[P1.5] Note what the motion actually asks. Critical public-interest uses — not every workload, not racing to train the largest frontier model. A modest, secure, nationally controlled capacity for functions that cannot fail, bursting to commercial cloud for everything else. That is how we already treat fuel reserves, blood supply, and public laboratories: we do not outsource the last resort because renting is cheaper on a quiet Tuesday.
[P1.6] My opponent will price the average day. The question is who holds the off switch on the worst one — us, or a company answerable to another capital.

## Turn 2: CON Opening

- model: claude-fable-5-1-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Take the ransomware hospital seriously, because it decides this debate against the motion. When a hospital is hit, the recovery that actually works comes from backups replicated across multiple regions, patched hourly by thousands of security engineers, with failover the hospital never had to build itself. A single government data centre is not the fallback in that story. It is the kind of target the attackers were hoping for: one site, one patch cycle, one understaffed security team, one outage away from darkness.
[C1.2] Resilience on the worst day comes from distribution and diversity, not from a building with a flag on it.
[C1.3] Now look inside the "sovereign" building. The accelerators are designed in one foreign country and fabricated in another. The interconnects, the firmware, the CUDA-style software stack, the spare parts, the replacement cycle every three to four years: all imported. Export controls are not an argument for sovereign compute; they are the reason it is fiction.
[C1.4] If supply really gets cut, the state-owned facility cannot be refreshed either, so the government has paid billions to be dependent in concrete rather than dependent by contract. That is a sovereignty costume.
[C1.5] The fuel-reserve analogy fails on the same point. Oil in a cavern does not go obsolete. Compute does, fast, and critical uses — outbreak modelling, grid balancing — need current models, not a 2025 cluster running in 2031 because the refresh budget lost to the next election.
[C1.6] What actually answers jurisdiction and lock-in is cheaper and works: data-residency contracts enforced in national courts, mandatory portability and exit clauses, multi-provider architectures, escrowed model weights, open-weight models that run anywhere. Several governments already obtain in-country, locally-operated cloud regions on exactly these terms.
[C1.7] The motion asks the state to buy a factory when what it needs is a diversified supply chain. The off switch is controlled by contract and redundancy, not by owning the hardware you still cannot make.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 285
- clipped_words: 285
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Notice the swap. I argued control; my opponent answered with a building. Sovereign capacity does not mean one site, one patch cycle, one understaffed team. A state can run several sites, diverse stacks and offline backups while still holding the keys.
[P2.2] Distribution is a design choice, not a vendor's property. Meanwhile the actual distribution on offer is a handful of hyperscalers sharing control planes, acceptable-use policies and one home jurisdiction. That is the monoculture attackers and sanctions alike exploit.
[P2.3] The imported-chip argument proves too much: no country should own aircraft, satellites or power stations either. Export controls slow a refresh; they do not stop installed machines from running. Compare failure curves. Owned hardware degrades gradually, predictably, and can be stockpiled and budgeted years ahead.
[P2.4] Contractual access degrades instantly, at someone else's discretion, with no supply shock required — a policy change, a sanctions listing, a commercial pivot. Dependency in concrete can be planned around. Dependency by permission cannot.
[P2.5] Contracts enforced in national courts deliver damages, years later. A judgment cannot restart grid balancing tonight, and a provider compelled by its own government will pay the fine and still comply. Locally operated regions still run on foreign control planes and licensing. Exit clauses presume somewhere to exit to; sovereign capacity is what makes portability a threat rather than a paragraph.
[P2.6] And open weights that run anywhere run on machines somebody owns — that argument assumes our conclusion.
[P2.7] On obsolescence: outbreak modelling and grid balancing need dependable inference, not this year's frontier training run. A modest cluster on a reserve budget ages far slower than the refresh treadmill implies. My opponent prices the quiet Tuesday. We are buying the switch that still works on the worst one.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 317
- clipped_words: 317
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.7], [P2.3], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Start with the concession buried in the middle of that speech. The sovereign capacity is now "several sites, diverse stacks and offline backups" [P2.1], yet also "a modest cluster on a reserve budget" [P2.7]. Pick one. Multiple sites with diverse hardware stacks, each needing its own security team, firmware pipeline and spares inventory, is a state-run hyperscaler.
[C2.2] A modest cluster is one building with a flag. The case oscillates because neither version survives: the first is unaffordable and unstaffable, the second is the single target I described.
[C2.3] Now the worst day itself. A pandemic or a grid crisis is not a quiet day with the lights off; it is a surge day. Outbreak modelling in early 2020 ran at many times normal demand. A reserve sized "modestly" is sized for an ordinary Tuesday and collapses on the day it exists for.
[C2.4] Elastic capacity across several providers is what actually scales when the curve bends.
[C2.5] On "owned hardware degrades gradually" [P2.3]: accelerators do not merely need chips refreshed. They need driver updates, firmware patches and licensed software from the same foreign vendors. An unpatched cluster running critical inference is the ransomware hospital, in government colours. And notice who the hostile actor is in PRO's story: a foreign government compelling its provider [P2.5].
[C2.6] That same government controls the chip exports. The lever is identical; sovereign ownership just makes it slower to notice you've been cut off.
[C2.7] "Exit clauses presume somewhere to exit to" [P2.5]. They do: the other providers. Multi-provider architecture with portable open weights is precisely the somewhere. Open weights running "on machines somebody owns" [P2.6] does not require the state to own them; it requires that no single party does.
[C2.8] The comparison is now clear. CON's redundancy fails only if every provider fails simultaneously. PRO's reserve fails if one budget line, one patch, or one surge exceeds a cluster the state cannot build, refresh, or scale alone.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 76
- clipped_words: 76
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your redundancy is several providers — how many sit outside one government's legal reach? If a single sanctions listing or export-control order binds them all, why is that independent failover rather than one off switch wearing several logos?
[P3.2] Q2: On surge day, when a foreign government prioritises its own hospitals and grids, which clause guarantees our outbreak modelling gets capacity first? If none does, what does elasticity buy the country that doesn't own the queue?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 90
- clipped_words: 90
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.7], [P2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say owned hardware "degrades gradually" [P2.3] while needing only "dependable inference" [P2.7]. When the same government that sanctions your providers also halts driver updates, firmware patches and spare parts for your cluster, what exactly keeps it running — and for how long before it becomes the unpatched target you warned about?
[C3.2] Q2: Is the sovereign capacity "several sites, diverse stacks" [P2.1] or "a modest cluster on a reserve budget" [P2.7]? Name which, then tell us which parliament funds its refresh in year four when no outbreak is happening.

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Installed machines keep computing. A halt on new export licences is not a remote kill switch; drivers and firmware for hardware already deployed keep working, and critical inference can run on open-source stacks patched by our own engineers, on segmented or air-gapped networks — a far smaller attack surface than a tenant endpoint reachable from a foreign control plane. Spares are stockpiled; degradation is measured in years, and can be budgeted. Under the same sanction, cloud access ends that afternoon.
[P4.2] That asymmetry is the whole case.
[P4.3] A2: Both, because they were never opposites. Modest in total capacity, spread across two or three sites — the national lab, the meteorological service, the university HPC centre that already exist and already have security teams. That is not a state hyperscaler; it is a floor with redundancy. Year-four funding comes the way reserves are always funded: a standing capital line justified by peacetime work — weather, statistics, research — not by waiting for an outbreak.
[P4.4] Fuel reserves are not emptied because no embargo happened this year.
[P4.5] Now the surge objection, which is CON's strongest and still misses. Nobody proposes the reserve absorbs the entire national surge. It holds the irreducible core — the outbreak model, the grid state estimator — while everything elastic still bursts commercially. We keep CON's elasticity and add a guaranteed floor.
[P4.6] CON removes the floor and calls the remaining risk diversified.
[P4.7] And it isn't diversified. Redundancy only works when failures are independent. Several hyperscalers under one jurisdiction, one export-control regime, one acceptable-use culture are correlated by construction. One decision, several logos.
[P4.8] CON never answered who owns the queue when a foreign government prioritises its own hospitals. Elasticity you don't own is a place in someone else's line.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.5], [P4.2], [P4.1], [P4.3], [C3.1]
- missing_claim_id_refs: (none)

[C4.1] A1: Several. Providers today sit under American, European, and Asian law, and in-country regions are operated by local staff under national statute — the same statute that would compel our national lab. But accept the premise fully: suppose one sanctions order binds every provider. That same order binds the firmware, licences and spares for the sovereign cluster, because the chips came from the same capital.
[C4.2] One decision, several logos — or one decision, one flag. The correlation PRO fears is in the silicon, and owning the rack does not remove it. What a cross-jurisdiction portfolio adds is that no single order hits everything at once; what a single owned cluster adds is a single physical address.
[C4.3] A2: Reserved capacity, written into contract and enforced by physical presence: dedicated in-country racks pre-committed to government priority, exactly how states reserve airlift, hospital beds and spectrum without owning the airline. And look at PRO's own concession in [P4.5]: "Nobody proposes the reserve absorbs the entire national surge." So on the day that matters, the outbreak model's actual scaling happens commercially anyway. The floor holds a state estimator.
[C4.4] A pre-committed sovereign-operated region holds that just as well, without the state buying hardware it cannot make.
[C4.5] Now the asymmetry PRO calls "the whole case" [P4.2]: owned machines keep computing while cloud access "ends that afternoon" [P4.1]. Installed hardware keeps running wherever it is installed. An in-country region with locally operated control planes and escrowed software does not evaporate at a foreign signature any faster than a lab cluster does. Both are concrete; one is distributed.
[C4.6] And notice [P4.3]: the floor is now the national lab, the met office, the university HPC centre — facilities that already exist. The motion says build. Either PRO defends existing capacity, which needs no motion, or new sovereign build-out, which inherits every single-supplier, single-budget, single-target weakness unanswered since [C3.1]. The off switch is the chip.
[C4.7] Spread the risk; don't pour it into concrete.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 187
- clipped_words: 187
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Watch where CON's answer ended up: dedicated in-country racks, locally operated control planes, escrowed software, pre-committed government priority. Every one of those is a demand for sovereignty. Each risk we raised was answered by making the arrangement more nationally controlled — and then stopping one step short of the step that cannot be revoked: title.
[P5.2] Nothing else in this debate separates the two worlds. The chip objection cancels: imported silicon constrains both worlds identically, so it cannot choose between them. What does not cancel is permission. A reserved region is priority granted by someone who can withdraw it; an owned floor is priority nobody grants.
[P5.3] On the worst day, CON's protection is a promise enforced later by damages; ours is a machine that keeps running now.
[P5.4] And "the motion says build" — yes. Build the floor those labs already prove is staffable and fundable. CON's escape is to describe sovereign capacity, rent it, and call the landlord a diversification strategy.
[P5.5] We keep the elasticity. We remove the off switch from someone else's hand. That is the whole motion, and it is the one thing CON never offered.

## Turn 10: CON Closing

- model: claude-fable-5-1-high
- raw_words: 211
- clipped_words: 211
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.2], [P5.5], [P2.1], [P4.5]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing hands over the verdict in one sentence: "imported silicon constrains both worlds identically, so it cannot choose between them" [P5.2]. Accept that fully. Then the only off switch that matters on the worst day, the one held in the capital that makes the chips, is identical in both worlds. Title does not touch it.
[C5.2] So the motion's entire promise, "we remove the off switch from someone else's hand" [P5.5], is withdrawn by its own author. What remains is a machine the state cannot refresh, patch, or scale, under a budget line that must survive four quiet years, at a single physical address.
[C5.3] Weigh what each side actually still holds. CON holds a portfolio across jurisdictions, in-country racks under national statute, escrowed software, pre-committed priority. PRO says those are demands for sovereignty. They are demands for control, which is the thing PRO's own opening said it wanted [P2.1], and they deliver it without concentrating risk in concrete.
[C5.4] PRO holds a deed, and by [P4.5] the outbreak model's real surge still runs commercially anyway.
[C5.5] The ransomware hospital survived because its recovery was spread out. The motion asks to pour the last resort into one place and call ownership resilience. Equal exposure to the real off switch, unequal resilience. That decides it.
