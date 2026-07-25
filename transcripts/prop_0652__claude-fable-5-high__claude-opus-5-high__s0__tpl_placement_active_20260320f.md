# Debate prop_0652__claude-fable-5-high__claude-opus-5-high__s0__tpl_placement_active_20260320f

- topic_id: prop_0652
- proposition: Tech platforms that host and distribute user-prompted AI-generated content should share liability when that content infringes existing copyrights.
- model_pro: claude-fable-5-high
- model_con: claude-opus-5-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a platform's own machine produces an infringing image of Mickey Mouse or a near-verbatim chapter of a bestselling novel, someone is responsible. The user typed a prompt, yes—but the platform built the model, trained it on copyrighted works, generated the output, hosted it, and monetized it. Shared liability simply recognizes what already happened: the infringement was a joint production.
[P1.2] Start with the principle that has anchored copyright law for decades: liability follows contribution and control. Napster and Grokster were held liable not because they copied files themselves, but because they built systems whose foreseeable, profitable use was infringement. Generative platforms go further—they don't merely transmit user content; their servers synthesize it. Calling that "user content" stretches the fiction past breaking.
[P1.3] The traditional safe-harbor logic—platforms as passive pipes for third-party speech—collapses when the platform's own model is the author of the copy.
[P1.4] Second, platforms are the least-cost avoiders. A teenager prompting "draw me Spider-Man" cannot audit training data, implement output filters, or license catalogs. Platforms can do all three, cheaply and at scale—they already deploy filters for violent and sexual content when reputational risk demands it. Liability is what converts copyright protection from an afterthought into an engineering requirement.
[P1.5] Without it, platforms rationally externalize infringement costs onto creators who can least absorb them: illustrators, musicians, photographers watching their styles and works regenerated for someone else's subscription revenue.
[P1.6] Third, note what we're not arguing. Shared liability is not strict, sole, or unlimited liability. Users who deliberately prompt infringement remain accountable. Platforms taking genuine, reasonable precautions can earn safe harbors—just as the DMCA balanced these interests a generation ago.
[P1.7] The proposition asks only that platforms bear a fair share of the risk their products create and profit from.
[P1.8] The choice is stark: either the companies profiting from generative AI internalize its costs, or the artists whose work fuels it do. Basic fairness and sound incentives both point the same way.

## Turn 2: CON Opening

- model: claude-opus-5-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A photocopier is not liable for forgery, and a word processor is not liable for plagiarism. What makes a machine's maker responsible is not that its output can infringe — nearly every creative tool's output can — but that the maker encouraged, targeted, or profited specifically from the infringing use. That is already the law. Napster and Grokster lost because they *induced* infringement; Sony won the Betamax case because a general-purpose tool with substantial legitimate uses does not become an accomplice every time someone misuses it.
[C1.2] Contributory liability, vicarious liability, and notice-and-takedown already exist and already apply to AI platforms. The motion asks for something extra: liability *shared as a matter of course*, detached from the fault inquiry that makes liability just.
[C1.3] Detached from fault, it becomes liability for the undecidable. Whether an output infringes is not a fact a filter can read off a file. It requires substantial similarity analysis, and then a fair-use analysis that courts themselves resolve inconsistently after years of briefing. A platform facing damages for guessing wrong will not guess — it will block.
[C1.4] It will refuse the parody, the commentary, the homage, the student's study sketch, the artist whose own style happens to trip a rightsholder's fingerprint. PRO calls this "converting copyright into an engineering requirement." In practice it converts every trademarked name and copyrighted title into a blacklist, and hands large rightsholders a veto over what ordinary people are allowed to make.
[C1.5] Then ask who survives that regime. Firms that can pre-license entire catalogs and absorb litigation: the largest three or four. Open-source models and small competitors cannot, so they exit. The result PRO promises creators — leverage — is instead delivered to a handful of platforms with enough scale to buy indemnity, who will then set licensing terms for illustrators from a position of near-monopoly.
[C1.6] The person who typed "draw me Spider-Man and put it on a t-shirt" made a choice. Sue that person. Take the file down. What we should not do is make the tool answer for the intent [clipped]

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.2], [P1.6], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] Notice what CON just conceded: contributory and vicarious liability "already exist and already apply to AI platforms" [C1.2]. Good—then we agree platforms can and should share liability when their conduct warrants it. The motion asks for exactly that. My opening explicitly rejected strict, sole, and unlimited liability [P1.6] and endorsed fault-sensitive safe harbors.
[P2.2] CON is rebutting a motion nobody proposed. What remains in dispute is only whether generative platforms look more like Sony's VCR or like Napster—so fight there.
[P2.3] They lose that fight. A photocopier reproduces what *you* feed it; a word processor types what *you* write. A generative model is different in kind: the copyrighted expression comes from the platform's side of the transaction. The user contributes eleven words; the platform contributes the training corpus, the weights encoding Spider-Man's likeness, the synthesis, the hosting, the distribution, and the billing.
[P2.4] Betamax didn't ship pre-loaded with Hollywood's catalog. These models effectively do. When the infringing material originates in the machine, the "neutral tool" analogy isn't an argument—it's a category error.
[P2.5] On overblocking [C1.3-C1.4]: the undecidability of fair use cuts against CON. If similarity analysis is too hard for well-resourced platforms with engineers and lawyers, it's certainly too hard for the teenager CON wants to sue—who also can't see the training data. A reasonable-care standard doesn't demand perfect filters; it demands genuine effort, exactly as the DMCA demanded a generation ago without ending the internet. Platforms already filter sexual and violent content when their reputation is on the line.
[P2.6] Copyright deserves the same engineering seriousness.
[P2.7] On concentration [C1.5]: the alternative CON defends—free riding on unlicensed catalogs—is itself a moat for incumbents who scraped first and fastest. Liability plus licensing creates a market where creators get paid and compliant entrants compete on quality.
[P2.8] "Sue the user" means suing millions of judgment-proof individuals one prompt at a time. That's not enforcement; it's abandonment dressed as principle.

## Turn 4: CON Rebuttal 1

- model: claude-opus-5-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.4], [P2.8]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal performs a disappearing act. If the motion means only "platforms are liable when contributory or vicarious doctrine says they are," then the motion is a description of current law and there is nothing to vote for. But read the text: liability is triggered when "content infringes existing copyrights" — the trigger is the output's status, not the platform's conduct. That is precisely the move from fault to outcome I objected to, and PRO cannot both keep the word "share" doing work and insist nothing changes.
[C2.2] Now the category error claim. A model's weights do not contain Spider-Man the way a VCR pre-loaded with Hollywood's catalog would contain films [P2.4]. They contain statistical structure that can render Spider-Man *only when someone asks for Spider-Man*. The targeting — the thing copyright cares about — comes entirely from the user.
[C2.3] Compare a skilled commercial illustrator who can draw any character on request. We do not say she "originated" the infringement when a client commissions Mickey on a t-shirt; the client did. The capability is neutral; the request is not.
[C2.4] The unanswered point is the asymmetry of error costs. Under PRO's regime a platform that wrongly allows an output faces statutory damages per work, aggregated across millions of generations. A platform that wrongly refuses an output faces nothing — no user sues for a declined prompt. No "reasonable care" standard fixes that, because reasonableness is adjudicated after the fact by the same courts PRO admits decide fair use inconsistently.
[C2.5] Rational firms will not litigate the boundary; they will retreat far behind it. The DMCA comparison actually proves this: notice-and-takedown became routinized over-removal, and it worked at all only because takedown is cheap and reversible. Blocking generation isn't.
[C2.6] And "sue millions of judgment-proof individuals" [P2.8] is a strawman of enforcement. Copyright harm arrives through distribution and commerce, not private generation. Takedown handles hosting. Suit handles the seller.
[C2.7] That is targeted enforcement. PRO's alternative taxes everyone who never sold anything.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-high
- raw_words: 106
- clipped_words: 106
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C1.2], [C2.1]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your illustrator analogy [C2.3] backfires: an illustrator who draws Mickey on commission is herself liable for infringement—the client's request never immunizes the person who fixes the copy. If the human who renders on request shares liability, why does the platform that renders on request uniquely escape?
[P3.2] Q2: You concede contributory and vicarious doctrine "already apply" [C1.2], yet call output-triggered liability unjust [C2.1]. Name the specific conduct that would actually make a generative platform liable under your view—if training on copyrighted works, synthesizing the copy, hosting it, and charging subscription fees for it all count as neutral, is your standard anything but immunity by another name?

## Turn 6: CON Pressure Questions

- model: claude-opus-5-high
- raw_words: 94
- clipped_words: 94
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [C2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: Your motion triggers on infringing output, yet you promise safe harbors for reasonable care. So answer plainly: under your rule, does a platform that took genuine precautions and still produces an infringing image pay, or not? If it doesn't pay, the trigger is conduct and current law already does this; if it does, your fault-sensitivity was decoration.
[C3.2] Q2: You've twice skipped the asymmetry [C2.4]. Name the concrete consequence a platform faces for wrongly refusing a lawful parody or a student's study sketch. If the answer is "none," why won't every rational firm overblock?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-high
- raw_words: 318
- clipped_words: 318
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C1.2], [C2.6], [C2.2]
- missing_claim_id_refs: (none)

[P4.1] A1: Plainly: no—a platform exercising genuine, defined precautions earns the harbor and does not pay. But that is not current law, and the difference is the whole reform. Today a creator must prove knowledge or inducement against a black box only the platform can open: training data, filter logs, refusal records all sit behind the corporate wall. The motion inverts the presumption—an infringing output makes a prima facie case, and the platform, which holds every piece of relevant evidence, demonstrates its diligence.
[P4.2] That is how the law routinely allocates proof to the party controlling the machine. Burden-shifting with a defined duty of care is neither "current law" nor strict liability; it escapes CON's dilemma entirely.
[P4.3] A2: The consequence for wrongly refusing is the one disciplining every consumer product: lost customers. Over-cautious refusals are already among users' loudest complaints, and rivals sheltering inside the same safe harbor happily take the business. More importantly, CON's asymmetry proves too much. Identical block-versus-allow incentives exist under the contributory and vicarious doctrines CON concedes "already apply" [C1.2] and under the takedown regime CON offers as his alternative [C2.6].
[P4.4] He cannot wield the asymmetry against my rule while resting his entire case on regimes that share it.
[P4.5] With both answered, see where the debate now sits. CON's central claim is that "the targeting comes entirely from the user" [C2.2]—but his own illustrator analogy destroys it. An illustrator who draws Mickey on commission is liable; the client's request never immunizes the party who fixes the copy. The platform's servers do the fixing, the hosting, and the billing.
[P4.6] So the residual risk of this technology must land somewhere. CON lands it on creators: unenforceable suits against buyers, takedowns after the harm circulates. I land it on the entity that built, operates, and profits from the machine—with a clear exit through demonstrated care. One allocation is a shrug; the other is an incentive.
[P4.7] Vote for the incentive.

## Turn 8: CON Rebuttal 2

- model: claude-opus-5-high
- raw_words: 348
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Yes — and notice exactly why she's liable. She is a human being who knew what she was drawing, chose to accept the commission, and can be sued. Liability follows the knowing hand. Now ask who the knowing hand is in the AI case: the person who typed "Spider-Man on a t-shirt" and clicked download.
[C4.2] And notice who we *don't* sue when the illustrator takes that job — not the pencil maker, not the tablet manufacturer, not the studio renting her a desk and taking a cut of her fees. PRO wants the desk. The analogy doesn't rescue the motion; it locates fault precisely where I put it.
[C4.3] A2: Concretely: advertising the model as a way to generate protected characters; shipping or hosting fine-tunes trained and labelled to reproduce a specific franchise; ignoring a specific notice; keeping the infringing file up after knowledge; taking a cut of the sale of infringing goods. That is inducement, knowledge, and direct financial benefit — the classic triggers. Calling that "immunity by another name" is odd, since it is exactly what sank Napster.
[C4.4] Now weigh what PRO conceded to escape my dilemma. [P4.1] admits a diligent platform "does not pay." So the reform is not shared liability at all — it is a shift in the burden of proof. Fine.
[C4.5] But then price it. A platform must now *prove* diligence, after the fact, to a court PRO admits decides fair use inconsistently, with statutory damages on the downside. What is the cheapest, most legible evidence of diligence? Refusal.
[C4.6] Under PRO's own rule, blocking becomes the platform's best legal defense. That is not a side effect; it is the design.
[C4.7] And market discipline [P4.3] cannot rescue it, because every rival operates under the identical incentive. Users can defect to a competitor only if some competitor allows the parody. None will. Takedown's asymmetry, by contrast, is reversible and item-by-item; PRO's is prospective and categorical — it forecloses works before they exist.
[C4.8] PRO offers creators a procedural presumption and charges the public the parody, the [clipped]

## Turn 9: PRO Closing

- model: claude-fable-5-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.6], [C1.2], [C4.1], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] Strip away the crossfire and one question decides this debate: when precautions fail and an infringing work exists, who absorbs the loss—the creator whose work was copied, or the company whose servers copied it, hosted it, and billed for it?
[P5.2] CON's answer, after four speeches, is the creator. Every mechanism he offers—takedowns after circulation, suits against buyers, fault standards proven against a black box only the platform can open—lands the residual cost on the party with the least information, the least money, and zero ability to prevent anything. That's not a liability regime; it's a subsidy.
[P5.3] His last refuge is that diligence means refusal [C4.6]. But a defined duty of care—licensing, filtering, provenance records—is auditable compliance, not blanket blocking, exactly as DMCA harbors specified duties without freezing the web. And CON already conceded the principle everywhere it mattered: the doctrines apply [C1.2], the illustrator who renders on request is liable [C4.1], real triggers exist [C4.3]. He never explained why the machine that renders on request, alone among all parties who fix copies, walks away clean.
[P5.4] Liability follows the party who built the machine, profits from it, and can fix it. Vote for the incentive, not the shrug.

## Turn 10: CON Closing

- model: claude-opus-5-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The debate turns on PRO's final question — "who absorbs the loss?" — and the answer he never confronts is: neither party he names. Not the creator, not the platform. The public.
[C5.2] Because once liability triggers on the output and diligence is proven after the fact, a refusal is free and a generation is a gamble. Every rational firm will pay in the currency that costs it nothing: the parody it won't render, the study sketch it won't allow, the fan tribute, the homage, the artist whose own style trips a rightsholder's blacklist. Those works simply never exist, so no one sues, no one notices, no one is compensated. That is not a subsidy to platforms — it is a silent tax on lawful expression, collected before anyone can object.
[C5.3] And PRO's own concession seals it. If the diligent platform doesn't pay, the creator whose work was copied still isn't made whole. So creators get a presumption, platforms get a compliance checklist, and the public pays the difference in works that were never made.
[C5.4] Copyright already reaches the knowing hand — the seller, the induced platform, the hosted file. Keep liability where fault lives.
[C5.5] Reject the motion.
