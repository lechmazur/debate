# Debate prop_0680__claude-sonnet-5-high__deepseek-v4.1-flash-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0680
- proposition: Cities should prohibit predictive policing systems that recommend where to deploy patrols based primarily on historical arrest and incident data.
- model_pro: claude-sonnet-5-high
- model_con: deepseek-v4.1-flash-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-sonnet-5-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Predictive policing systems that direct patrols based on historical arrest and incident data don't predict crime. They predict where police have already chosen to look. That distinction is the whole case.
[P1.2] Arrest data is not crime data—it is enforcement data. It reflects where officers were sent before, which neighborhoods got stopped-and-frisked, which blocks got extra squad cars because of decades-old zoning of "high crime areas." When a department feeds that history into an algorithm and asks it to recommend future patrol locations, the system launders past policing choices into a supposedly neutral, technical output. More patrols in a neighborhood mechanically produce more recorded arrests for the same underlying behavior, simply because more police are there to make them.
[P1.3] That inflated arrest count then gets fed back into the system as fresh "evidence" that the neighborhood is dangerous, justifying even more patrols next cycle. This is a feedback loop, not a forecast. It runs almost entirely on low-level, discretionary offenses—loitering, minor drug possession, disorderly conduct—precisely the categories most sensitive to where officers are standing, and least reflective of actual public safety need.
[P1.4] The predictable result is that over-policed communities, disproportionately poor and minority neighborhoods, get locked into permanent surveillance status by a machine that appears objective and is therefore harder to challenge than an individual officer's bias. You cannot cross-examine an algorithm's "gut feeling." Cities adopting these tools have specifically cited this dynamic as the reason for abandoning them once independent audits looked at the mechanics rather than the marketing.
[P1.5] Cities have alternative ways to allocate patrols: calls-for-service data weighted for severity, community input, response-time needs, violent crime clearance priorities. None of those require baking in a self-confirming loop built on the very disparities we are trying to fix.
[P1.6] The proposition asks for a narrow, targeted prohibition: no systems that recommend patrol deployment primarily from historical arrest and incident data. That's not banning data-informed policing. It's banning a specific mechanism that manufactures the crime patterns it claims to detect.

## Turn 2: CON Opening

- model: deepseek-v4.1-flash-high
- raw_words: 307
- clipped_words: 307
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Arrest data is enforcement data. True. But the motion does not stop at arrest data. It prohibits systems based primarily on historical arrest and incident data—and incident data includes 911 calls, shots-fired reports, burglaries, robberies, assaults, homicides.
[C1.2] Those are not manufactured by patrol presence. A homicide is recorded because someone was killed, not because an officer happened to be standing nearby. If shootings spike on three blocks, a city should send resources there, not pretend it cannot use the best available map. A prohibition written this broadly would also ban a system using only confirmed shootings and homicide reports.
[C1.3] Banning incident data does not purify policing; it blinds it.
[C1.4] The central choice is not "algorithm vs. fairness." It is "audited, contestable data systems vs. the opaque status quo." Departments already decide patrols using politics, complaints, officer intuition, and last year's map. Those methods have no audit trail and no appeal.
[C1.5] A predictive system can be required to exclude low-level discretionary arrests, document inputs, test for feedback, publish error rates, and route recommendations through human supervisors. The proposition forbids the tool instead of regulating the defect. That is like banning X-rays because some are misread.
[C1.6] The feedback loop is real but fixable: if the system over-patrols a block, that shows up in audits; if arrest data is contaminated, it can be removed from the model. Prohibition, by contrast, guarantees no correction because there is no system to correct. It also creates a dangerous vacuum. Police will still target neighborhoods; they will simply do it through informal analytics or raw hunches that residents cannot inspect or challenge.
[C1.7] That is less transparent, not more.
[C1.8] The right test is comparative. Would vulnerable neighborhoods be safer and fairer with a prohibited blackout, or with mandatory data standards, independent audits, and community oversight? The motion chooses blackout and calls it justice. Vote CON.

## Turn 3: PRO Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON's strongest move is to say the motion also bans homicide and shooting data. But look at the actual mechanism: even "incident data" like calls-for-service is not clean. Noise complaints, "suspicious person" calls, and loitering reports are saturated with the same bias as arrests — a Black man walking through a majority-white block generates more 911 calls than the same behavior elsewhere. That data flows into the same feedback loop.
[P2.2] And where a system is "primarily" driven by arrest and incident history, as the motion specifies, homicides are a tiny fraction of the volume; the model is trained overwhelmingly on the high-frequency, low-level categories I described in opening. CON's homicide hypothetical is the exception dressed up as the rule.
[P2.3] CON's second move is "regulate, don't ban" — audits, published error rates, human sign-off. But audits happen after the loop has already run for months or years, on communities that had no say in being the test case. That is not a fix, it is a promise to notice the harm later. And CON's own [C1.5] admits the system still needs low-level arrests stripped out and contamination removed before it's usable — which means the version CON wants to save is not the version cities are actually buying and deploying today.
[P2.4] The motion targets the tool as marketed and used, not a hypothetical clean model that doesn't yet exist.
[P2.5] Then there's the "vacuum" argument — police will just use informal hunches instead. But an officer's hunch doesn't carry the false authority of a "data-driven system." A hunch can be challenged in court, in a complaint, in the press, precisely because everyone knows it's a hunch. An algorithm's output gets treated as objective truth, which is exactly why the loop becomes self-insulating.
[P2.6] The real comparative question is: which failure mode is worse — a city forced to use severity-weighted response data and community input, or a machine that manufactures the crime it claims to find and hides behind neutrality while doing it? Prohibition ends the laundering. Regulation postpones reckoning with it.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4.1-flash-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P1.5]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal depends on a contradiction. [P2.1] says calls-for-service and incident data are saturated with bias and feed the same loop. But [P1.5] offered "calls-for-service data weighted for severity" as the clean alternative. You cannot condemn the data as poison and then pour it into your own model.
[C2.2] Either severity-weighting and audits can make these inputs usable—in which case they can do the same for predictive patrol systems—or they cannot, in which case PRO's alternative is equally tainted. That single inconsistency guts the supposed clean contrast between ban and regulate.
[C2.3] The motion bans systems based "primarily on historical arrest and incident data." It does not say "low-level arrest data." A city using confirmed shootings, homicides, and gunfire reports as its primary input is prohibited. PRO calls that a tiny fraction of actual models.
[C2.4] But the motion is not limited to actual models; it is a categorical ban. If the defect is discretionary loitering and drug arrests, prohibit those inputs. Do not ban the best map of where people are actually being shot.
[C2.5] PRO says audits arrive after harm. Not necessarily: pre-deployment validation, mandatory exclusion of discretionary arrest categories, published error rates, and human sign-off can be conditions of use. A flawed algorithm can be inspected, corrected, or shut off. A prohibition creates no inspection and no correction; it pushes decisions back to politics, complaints, and hunches—methods with no audit trail and no appeal.
[C2.6] Algorithmic false authority is answered by disclosing uncertainty and limits, not by banning the only version that can be audited.
[C2.7] PRO's "laundering" charge assumes the alternative is clean. It is not. And community input is itself a record of who complains loudest, not a neutral ground truth. The real comparison is between explicit, contestable inputs and the opaque status quo.
[C2.8] CON wins because the motion chooses blindness over reform.

## Turn 5: PRO Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 77
- clipped_words: 77
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C1.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: CON claims audits, exclusion rules, and human sign-off can make these systems safe—can CON name a single city where that full regime was in place *before* deployment, rather than bolted on after harm was documented?
[P3.2] Q2: If, per [C1.5], discretionary arrests must be stripped out and low-level categories excluded before the tool is usable, doesn't that concede the system as actually marketed and sold today—the one this motion targets—is exactly what CON admits must be banned?

## Turn 6: CON Pressure Questions

- model: deepseek-v4.1-flash-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P1.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: You call calls-for-service data bias-saturated in [P2.1], yet [P1.5] offers severity-weighted calls-for-service as the clean replacement. Which is it—can that data responsibly drive patrols, or not?
[C3.2] Q2: The motion bans systems based “primarily on historical arrest and incident data.” If a city uses only homicides, shootings, and gunfire reports—no discretionary arrests—is that banned? If yes, you ban the best map of violence; if no, your motion is narrower than written.

## Turn 7: PRO Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 307
- clipped_words: 307
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [P1.5]
- missing_claim_id_refs: (none)

[P4.1] A1: The difference is human contextualized judgment versus an automated feedback loop. Severity-weighted calls-for-service used by a human analyst who can discount a "suspicious person" call from a gentrifying block is not the same as an algorithm that mechanically recommends patrol coordinates and then ingests the resulting enforcement activity as new training data next cycle. My alternative in [P1.5] keeps a human in the loop who can contextualize; predictive policing systems are built specifically to remove that judgment and replace it with automated recommendation.
[P4.2] That's the mechanism the motion targets—not data itself, but data laundered through a self-reinforcing recommender.
[P4.3] A2: Technically, yes, a homicide-only tool would fall under "incident data." But CON needs this hypothetical to exist at scale to win, and it doesn't. Every documented predictive patrol system cities have actually purchased blends discretionary arrests with incident reports precisely because homicides are too rare to generate a usable spatial model on their own—you cannot train a daily patrol-allocation tool on a handful of yearly homicides. And even a homicide-only tool still triggers the loop: heavier patrol on a "hot" block generates more incidental low-level stops and arrests there, which then bleed into the next data pull unless something as generic as CON's "primarily" carve-out is doing all the work.
[P4.4] That's the tell. CON's answers rely on stripping and filtering—excluding discretionary categories, adding human sign-off, hypothesizing a homicide-only version that doesn't exist commercially. Every fix CON proposes is an admission that the actual deployed product is the one this motion bans. CON isn't defending predictive policing as marketed and sold; CON is defending a redesigned tool that would need to be built from scratch, audited before ever touching a street, and stripped of the very data that makes it commercially viable.
[P4.5] That's not a rebuttal to the motion. That's a vote for it, dressed up as reform.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4.1-flash-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: I cannot name a city that ran the full regime before deployment, and I won't invent one. But that question proves too much. The absence of a perfected example is not an argument for a categorical ban; it's an argument for making safeguards a precondition of use. We don't say "no city has perfectly pre-tested every policing tactic, so ban the tactic."
[C4.2] We require validation before deployment. The motion doesn't just pause flawed systems; it forbids the category, so the first well-audited system can never be built. PRO's harm story is about lack of safeguards, not about impossibility.
[C4.3] A2: No. Stripping discretionary arrests is input regulation, not a concession that the tool must be banned. If a system uses burglary, robbery, shooting, and homicide reports—none of which are manufactured by patrol presence—it can still be prohibited under the motion's "incident data" language. PRO conceded in [P4.3] that a homicide-only tool "technically" falls under the ban. That's the decisive overbreadth.
[C4.4] The motion is not "ban today's contaminated model"; it is a blanket prohibition on systems based primarily on historical arrest and incident data.
[C4.5] The debate has narrowed to a choice. PRO says current tools are flawed and safeguards arrive late. CON says then mandate safeguards before deployment, exclude discretionary categories, publish error rates, human review. If PRO thinks severity-weighted calls-for-service plus human judgment is acceptable, then the objection is not to data or prediction; it is to automation and feedback.
[C4.6] Those can be regulated directly. A ban cannot distinguish a contaminated arrest-driven model from a shooting map. It guarantees no correction, no audit trail, and pushes decisions back to politics and hunches—the opaque status quo. For vulnerable neighborhoods, a prohibited blackout is not fairness; it's invisibility.
[C4.7] The better rule is "prove it before you deploy," not "never deploy it." Vote CON.

## Turn 9: PRO Closing

- model: claude-sonnet-5-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.1]
- missing_claim_id_refs: (none)

[P5.1] The debate comes down to one admission CON cannot walk back: in [C4.1], CON concedes no city has ever run the "safe" version—pre-audited, stripped of discretionary arrests, human-supervised—before deployment. Every system actually sold to cities is the contaminated one. CON's entire case defends a tool that doesn't exist, against a motion written to stop the tool that does.
[P5.2] That's not a rebuttal to the proposition; it's a description of what the proposition bans. CON keeps insisting the fix is regulation-before-deployment, but that regulation requires rebuilding the product from its data up—removing the very inputs that make automated patrol-recommendation commercially viable in the first place. A system that can't run on discretionary arrests and incident volume isn't today's predictive policing with guardrails. It's a different tool CON hasn't shown exists anywhere.
[P5.3] Meanwhile the loop runs now, on real blocks, compounding with every patrol cycle CON's hypothetical audit hasn't happened. CON asks vulnerable neighborhoods to be the proving ground for a reform with no working example, while PRO offers an alternative that already functions today: severity-weighted response data plus human judgment, no laundering, no manufactured "hot spots."
[P5.4] Stop the mechanism that exists. Don't wait for the one that might.

## Turn 10: CON Closing

- model: deepseek-v4.1-flash-high
- raw_words: 164
- clipped_words: 164
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The debate turns on one textual fact. This motion does not ban merely unregulated, arrest-driven hot-spot tools. It bans systems based primarily on historical arrest and incident data—and PRO conceded a homicide-only tool “technically” falls under that ban. That is decisive.
[C5.2] It means the proposition cannot distinguish a biased feedback machine from the clearest available map of where people are actually being shot. Saying such a tool is rare today does not cure overbreadth; prohibitions bind tomorrow’s better tools too. And CON’s admission that no city has run a perfect pre-audited regime is not a reason to outlaw the category. It is a reason to make exclusion rules, pre-deployment validation, published error rates, and human review conditions of use.
[C5.3] PRO’s alternative—severity-weighted data plus human judgment—already concedes data and prediction can responsibly guide patrols. So the real choice is not safety versus algorithms. It is an auditable system versus a prohibition that guarantees no correction and returns decisions to politics, complaints, and hunches. Vote CON.
