# Debate prop_0164__gpt-6.2-astra-high__gemini-4-argon-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0164
- proposition: Public research funders should reserve a meaningful fixed share of grant budgets for replication studies even if that reduces funding for novel projects.
- model_pro: gpt-6.2-astra-high
- model_con: gemini-4-argon-high
- side_swap: True

## Turn 1: PRO Opening

- model: gpt-6.2-astra-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The question for a public funder is not how many new ideas it can launch, but how many sound findings others can build on. When several proposed projects depend on the same uncertain result, the most valuable next grant may be the one that tests their premise.
[P1.2] Imagine a small trial finds that a tutoring program improves reading. One team proposes adapting it for younger children; another wants to put it online. If neither adaptation works, we still won't know whether the adaptations failed or the original effect was a fluke. An independent test of the original program in comparable classrooms could give both teams a reason to proceed, revise, or stop.
[P1.3] Schools deciding whether to buy the program need that information, too.
[P1.4] Yet each investigator has a reason to let somebody else do that work. The career credit for a new approach goes to its author; the benefit of checking a premise is shared across every lab and school that might rely on it. Inviting replications to compete in a pool that prizes originality doesn't solve that mismatch. Teams are unlikely to recruit partner schools and design a careful test on the chance that a panel might make an exception.
[P1.5] Reserve a meaningful fixed share across the funder's portfolio, not an identical quota in every discipline. Within that share, judge proposals on independence, rigor, and whether the answer would change an important decision. A standing commitment makes that competition credible before researchers decide what to propose.
[P1.6] Yes, a novel project at the funding line will go unfunded. But count the opportunity cost on both sides: the price of skipping one well-chosen replication can be years of inventive work spent refining something that never worked in the first place.

## Turn 2: CON Opening

- model: gemini-4-argon-high
- raw_words: 285
- clipped_words: 285
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: [P1.2], [P1.5], [P1.6]
- missing_claim_id_refs: (none)

[C1.1] Consider the reading program example [P1.2]. Why fund a standalone copy of yesterday’s trial when a smarter grant design tests the premise and advances the field simultaneously? A team adapting that tutoring program for online delivery can simply include a direct replication of the original protocol as one arm of their trial. If both arms fail, the original was a fluke; if the baseline arm works and the adaptation fails, the modification was the flaw.
[C1.2] Strong science already embeds verification inside exploration. Siloing replication into a separate budget stream pays twice to learn what a well-designed novel study resolves at once.
[C1.3] Worse, locking a meaningful fixed share of the budget into standalone replications [P1.5] turns a situational tool into a permanent bureaucratic quota. The number of findings that genuinely require expensive, standalone re-testing is neither constant nor predictable across years. In grant cycles where foundational claims are already solid, or where urgent questions are exploratory, a fixed reserve forces panels to fund second-tier confirmatory exercises just to spend down the earmarked pool.
[C1.4] Meanwhile, transformative novel proposals at the funding line [P1.6] are rejected not on comparative merit, but because their funding was walled off in advance.
[C1.5] Furthermore, if small trials produce uncertain results [P1.2], the remedy is not reserving a permanent slice of discovery budgets to audit weak studies after the fact. Funders can require pre-registration, open data, and adequate statistical power up front, while issuing targeted, temporary calls for replication only when a specific bottleneck actually emerges. Public science agencies are society's primary engine for high-risk, foundational breakthroughs that private markets will never underwrite on their own. Sacrificing those irreplaceable discoveries to satisfy an arbitrary, inflexible spending quota mistakes rigid accounting for scientific rigor.

## Turn 3: PRO Rebuttal 1

- model: gpt-6.2-astra-high
- raw_words: 283
- clipped_words: 283
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Adding a classroom arm to the online tutoring trial makes sense if both answers are needed now. But suppose the online trial is worth running only if the classroom result holds up. Running both arms simultaneously buys the adaptation before learning whether to buy it. Nor is the classroom arm free: it still needs teachers, pupils and enough observations to give an informative answer.
[P2.2] The saving from sharing a control group must be weighed against the saving from not launching the wrong trial at all.
[P2.3] The deeper problem is who chooses what gets checked. Under the embedded model, a finding gets tested because someone wants to fund an extension. A district deciding whether to renew an existing program may have no extension worth funding and every reason to check the original. Preregistration and open data help the district understand what happened in one set of classrooms; they cannot supply observations from another.
[P2.4] A temporary call requires the agency to spot that need before researchers can bid. A standing competition lets researchers bring the need to the agency.
[P2.5] Demand need not be constant for a fixed share to make sense. Set the share conservatively against recurring needs across the portfolio. One field having a quiet year does not force a panel to fund weak studies; that would require a shortage of worthwhile tests across the funder’s remit. In return for accepting that risk, the agency gives teams a dependable reason to prepare those tests rather than wait for a call that may never come.
[P2.6] Yes, a promising novel proposal loses funding. But its possible breakthrough is not the only discovery at stake: redirecting several later grants toward sounder premises buys chances for breakthroughs too.

## Turn 4: CON Rebuttal 1

- model: gemini-4-argon-high
- raw_words: 288
- clipped_words: 288
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4]
- cited_claim_ids: [P2.1], [C1.1], [C1.5], [P2.3], [P2.5], [P1.5], [P1.4], [P2.4], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Waiting for a standalone replication before testing an adaptation [P2.1] trades a single trial arm for a multi-year freeze on innovation. Standing up two separate grant cycles, two research teams, and two independent control groups costs far more in administrative overhead and lost time than embedding a baseline check inside the next study [C1.1]. And if an initial finding is truly too fragile to build upon, the error was funding an underpowered pilot as a standalone result—a flaw solved by requiring adequate sample sizes up front [C1.5], not by building a permanent aftermarket to audit weak trials.
[C2.2] Nor should discovery budgets be raided just so a school district can decide whether to renew an existing curriculum [P2.3]. Routine program evaluation for institutional buyers belongs in operational procurement budgets, not basic research agencies. Diverting scarce scientific grants into product testing for local administrators crowds out the foundational, high-risk exploration that no school board or private market will ever underwrite [C1.5].
[C2.3] Finally, retreating to a "conservatively" set reserve [P2.5] exposes the flaw at the heart of a meaningful fixed share [P1.5]. If the quota is tiny enough to never exceed baseline demand, it will not reshape academic career incentives [P1.4]; if it is large enough to be meaningful, it walls off substantial discovery funding before panels read a single proposal.
[C2.4] Crucially, agencies do not need a rigid spending quota to let researchers bring replication needs forward [P2.4]. A funder can welcome investigator-initiated replication proposals every cycle while letting the funding share float—backing a standalone replication when its decision value genuinely beats the marginal novel breakthrough [P2.6], and refusing to subsidize second-tier confirmations when novel science is stronger. That captures every benefit of researcher-driven verification without putting handcuffs on the budget.

## Turn 5: PRO Pressure Questions

- model: gpt-6.2-astra-high
- raw_words: 66
- clipped_words: 66
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If few replication bids reach your floating competition, how will panels distinguish a shortage of worthwhile questions from a shortage of teams willing to recruit partners for a competition that might fund no replications?
[P3.2] Q2: Why must a reserve reshape career incentives across academia to be meaningful if it persuades enough teams to test the premises on which the next round of novel grants depends?

## Turn 6: CON Pressure Questions

- model: gemini-4-argon-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.5], [C2.4], [P2.1], [P2.3], [C2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: If panels judge replication bids on decision value rather than originality [P1.5], why would teams testing pivotal premises fear a floating share [C2.4]—unless a fixed quota exists to force funding for replications even when the marginal novel project is stronger?
[C3.2] Q2: Why should research agencies freeze follow-on innovation for years to run sequential standalone trials [P2.1], or raid discovery budgets for school-district procurement checks [P2.3], when upfront power standards and embedded baseline arms verify premises without halting progress [C2.1]?

## Turn 7: PRO Rebuttal 2

- model: gpt-6.2-astra-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: A fair hearing is not a predictable opportunity. A team must secure partners before any panel sees its bid. Under a floating share, even the best replication proposed might lose to a slate of discoveries. A reserve does not guarantee that team a grant; it guarantees a competition worth recruiting partners for.
[P4.2] Yes, a novel bid the panel would have preferred that year may lose. The return is a better set of proposals to choose from, not a better ranking of an unchanged pile.
[P4.3] A2: Don’t delay an adaptation worth trying regardless of the original result; embed the baseline arm when that is efficient. Wait when the adaptation is worth its cost only if the premise survives. Starting both together then commits teachers and money before we know whether the adaptation merits either. Adequate power makes the first trial more informative; it cannot tell us what happens in a second set of classrooms.
[P4.4] Whether one district got what it paid for is procurement. Whether a reading effect holds across comparable classrooms is a research question whose answer no single district has reason to finance for everyone.
[P4.5] The choice is who bears the uncertainty. CON protects the panel against having too few worthy replications by making every prospective team bear the risk of no replication awards at all. A funder can draw on questions across fields when one field has a quiet year; a team recruiting classrooms has no comparable cushion. A meaningful reserve need not transform academic careers.
[P4.6] It must sustain enough competition to bring pivotal tests before panels while their answers can still guide discovery. The visible cost is a novel grant forgone; the less visible cost of flexibility is a whole round of novel grants built on a premise nobody checked.

## Turn 8: CON Rebuttal 2

- model: gemini-4-argon-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P3.1], [P1.1], [C2.4], [C1.5], [P4.1], [P1.4], [P4.2], [P4.3], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: Panels do not have to guess why replication bids are low [P3.1], because they see the entire pool of incoming novel proposals. When several novel bids depend on the same untested premise [P1.1], that bottleneck is immediately visible to reviewers, who can prioritize a replication in the floating competition [C2.4] or trigger a targeted call [C1.5]. Moreover, every researcher proposing a novel classroom or clinical trial must also recruit partner schools or hospitals knowing that stronger discoveries elsewhere might win the funding [P4.1].
[C4.2] Replication teams do not need a sheltered budget silo to bear a risk that every exploratory scientist already navigates.
[C4.3] A2: Having argued that researchers skip replications because academic credit rewards originality [P1.4], PRO now retreats to claiming a reserve need only persuade enough teams to check pivotal premises for the next grant round [P3.2, P4.5]. If the goal is merely testing specific bottlenecks rather than overhauling academic incentives, then a permanent, portfolio-wide fixed quota is massive overkill. Targeted solicitations and a floating evaluation track [C2.4] already draw teams to high-stakes questions without walling off discovery funds every single year.
[C4.4] In fact, PRO’s defense exposes the fatal flaw of a fixed share: it forces panels to reject a novel project they "would have preferred that year" just to keep the replication bucket full [P4.2]. Pause on that concession. Even after reviewers read both proposals and judge the novel breakthrough more valuable to science than the marginal replication, the quota compels them to fund the weaker study anyway.
[C4.5] Meanwhile, PRO concedes that embedded baseline arms work whenever adaptations merit testing alongside the premise [P4.3], shrinking standalone replications to a narrow subset of sequential or cross-district checks [P4.4]. When those specific bottlenecks arise, a floating share funds them on merit without sacrificing stronger discoveries to bureaucratic rigidity.

## Turn 9: PRO Closing

- model: gpt-6.2-astra-high
- raw_words: 194
- clipped_words: 194
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON is right about the hardest case: in a particular year, a panel might prefer the novel project that a reserve displaces. But the panel chooses among applications on its desk. The funder decides what researchers have reason to put there. The best rule for choosing between two finished proposals need not be the best rule to announce before either is written.
[P5.2] Consider the panel that spots three applications relying on the same classroom result. It can identify the missing test; it cannot award a grant to a team that never recruited the schools or designed the study. By the time it issues a targeted call, the dependent projects are already competing for money. Novel investigators also risk rejection, but they can pursue recognition for a discovery of their own.
[P5.3] The team checking the premise does work all three need without that same reward.
[P5.4] A meaningful fixed share makes a promise worth keeping even in a year rich in new ideas: there will be money to compete for if you do that work. Count the novel grant forgone. But count, too, the novel grants a timely test can steer away from a dead end.

## Turn 10: CON Closing

- model: gemini-4-argon-high
- raw_words: 196
- clipped_words: 196
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.2], [P5.1], [C2.4], [P5.4]
- missing_claim_id_refs: (none)

[C5.1] The case for a fixed quota rests on a fatal admission: it forces panels to reject a novel breakthrough they actively prefer on the merits, solely to finish spending an earmarked reserve [P4.2, P5.1]. That is not scientific rigor; it is bureaucratic waste.
[C5.2] Worse, that sacrifice does not even solve the timing problem in [P5.2]. When three novel applications arrive relying on the same untested classroom trial, a fixed reserve cannot retroactively conjure a finished replication from the past. Funding a standalone test alongside them still leaves those projects waiting years for an answer—whereas requiring an adaptation to embed a baseline replication arm [C1.1, C4.5] tests the premise and the innovation together.
[C5.3] Nor is a rigid quota needed to bring standalone checks to the panel's desk [P5.1]. When a replication genuinely anchors future work, a standing competition with a floating budget share [C2.4] already gives teams every reason to apply, because reviewers weigh systemic decision value directly against discovery.
[C5.4] The only thing a fixed share uniquely accomplishes is compelling funders to buy weaker confirmations in years rich with transformative ideas [P5.4]. Public agencies should fund the best science on the desk, not empty a predetermined bucket.
