# Debate prop_0154__glm-5-3-high__claude-opus-5-5-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0154
- proposition: Copyright law should create a compulsory licensing scheme for training foundation models on copyrighted text and images, with payment to rightsholders.
- model_pro: glm-5-3-high
- model_con: claude-opus-5-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: glm-5-3-high
- raw_words: 350
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Foundation models are trained on copyrighted text and images at a scale no individual licensing market can handle. That's not a hypothetical: a frontier model's corpus spans billions of documents drawn from millions of rightsholders, most of whom are impossible to identify in advance. The choice before us is not "licensing versus the status quo of permission." It is licensing versus a world where the strongest players simply take what they need and dare creators to sue.
[P1.2] Compulsory licensing is the only mechanism that gets us payment at scale.
[P1.3] Consider the precedent. When cable television retransmitted broadcast signals, and when satellite providers did the same, Congress didn't demand individual negotiation over every channel—those markets were physically impossible. It created compulsory licenses with set royalty structures, and a functioning paid ecosystem emerged. Music streaming, webcasting, and player pianos all followed the same pattern: where mass, non-rivalrous reuse meets fragmented ownership, compulsory licensing is how copyright has historically preserved both access and compensation.
[P1.4] The market alternative fails structurally here. A rightsholder negotiating with a lab faces a holdout problem in reverse: no single book moves model quality measurably, so each creator's leverage approaches zero—yet the aggregate value of millions of works is enormous. Voluntary opt-in licensing would cover only large publishers and leave the long tail uncompensated, while litigation produces a few headline settlements and no systematic payment. A collective scheme with a set rate fixes this: it converts an unpricable commons into a paid one.
[P1.5] And the fairness argument cuts my way decisively. Training uses the expressive substance of authors and artists to build products that compete with them. Copyright's whole premise is that those who profit from creative work should pay for it. Opponents will say fair use already covers training, or that any payment scheme is administratively impossible.
[P1.6] But even if fair use is eventually found in some cases, "legal to take for free" is a policy choice, not a command—and the administrative machinery exists: collective societies like ASCAP already distribute micropayments across millions of works.
[P1.7] Pay creators for [clipped]

## Turn 2: CON Opening

- model: claude-opus-5-5-high
- raw_words: 356
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.4], [P1.6], [P1.1]
- missing_claim_id_refs: (none)

[C1.1] A compulsory license is a forced sale. The motion takes the one power copyright gives creators, the right to say no, and replaces it with a government-set price they cannot refuse. PRO calls this protecting artists. It is the opposite: the illustrator who never wants her work feeding a machine that imitates her loses that choice permanently, and receives a statutory check as consolation.
[C1.2] Look at what that check would be. PRO concedes that "no single book moves model quality measurably" [P1.4]. Exactly. Split any royalty pool across billions of works and millions of rightsholders and the long tail PRO champions gets pennies, while administrators and the largest catalogues capture most of the money.
[C1.3] PRO cites ASCAP [P1.6]. Collective music distributions are known to skew heavily toward top earners, and those systems track a small set of performances. Tracing contribution across a training corpus of billions of scraped files, most of them orphaned or mislabeled, is far harder. PRO's own premise that owners are "impossible to identify" [P1.1] explains why the money won't reach them.
[C1.4] Second, the scheme entrenches the giants PRO fears. A statutory rate plus compliance and audit costs is trivial for the largest labs and fatal for universities, open-source projects and startups. Worse, once the fee is paid, training becomes legally blessed. Today, creators and publishers have real leverage through litigation and negotiation, and voluntary deals are already emerging between AI developers and news publishers and image libraries.
[C1.5] Compulsory licensing caps that leverage at whatever rate a tribunal sets, likely low, because regulators will fear pushing training offshore to jurisdictions with no fee at all.
[C1.6] Third, PRO's precedents don't fit. Cable and radio retransmitted whole works to audiences who consumed them as substitutes. Training extracts statistical patterns and delivers no copy of the work to anyone. Where a model does regurgitate or closely imitate specific work, existing infringement law already applies to that output, with full remedies rather than a capped fee.
[C1.7] The better path is to keep the right to refuse, let markets price data that [clipped]

## Turn 3: PRO Rebuttal 1

- model: glm-5-3-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.1], [C1.4], [C1.2], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] The "forced sale" framing collapses the moment you ask what the alternative actually is. Today, creators don't get to say no—they get to discover, after the fact, that their work was scraped into a corpus run by an entity they'll never identify, let alone sue. The choice isn't between consent and a check; it's between a check and nothing. [C1.1] describes a veto that doesn't exist for the long tail.
[P2.2] Only the largest publishers have any leverage, which is exactly why [C1.4]'s "voluntary deals are emerging" proves my point: those deals cover a handful of big catalogues, and everyone else is left to penniless opt-out mechanisms or nothing at all.
[P2.3] Yes, the per-work payment will be small [C1.2]. So is every Spotify stream. Small multiplied by millions of training runs across millions of works is how collective licensing has always worked—pennies are what ASCAP pays, and composers still built an income infrastructure on them. The comparison isn't pennies versus a robust voluntary market; it's pennies versus zero.
[P2.4] The "entrenches giants" argument is backwards. Compliance costs under a statutory scheme are dwarfed by the litigation exposure small players face today, where only trillion-dollar labs can absorb lawsuits. A set rate is the small player's shield, not their burden.
[P2.5] On precedents [C1.6]: my opponent says training extracts "statistical patterns," not works. But the economic substance is identical—someone else's creative output becomes the input of a competing commercial product. Copyright law has never required that the copy be shown to a human; reproduction and derivative-use liability have long attached to intermediate and transformative internal uses. And [C1.6]'s own concession—that regurgitation is fully actionable—shows why output remedies alone are insufficient: training-time compensation can't be recovered through case-by-case output suits that creators will rarely detect or afford.
[P2.6] CON's world preserves leverage only for the powerful. The motion is how the rest get paid.

## Turn 4: CON Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 348
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9]
- cited_claim_ids: [P2.1], [P2.3], [P1.1], [P2.4], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO's entire rebuttal rests on one sentence: "it's between a check and nothing" [P2.1]. That is false, and once it falls, the case falls with it.
[C2.2] The status quo is not nothing. It is unsettled law with live lawsuits, from authors, artists, news publishers and image libraries, over whether unlicensed training infringes at all. If they win, every rightsholder regains a real veto and real bargaining power. The motion ends that fight before it is decided, and creators lose.
[C2.3] It turns a contested taking into a lawful one, permanently, in exchange for a tribunal rate. PRO's "check versus nothing" is really a guaranteed small check versus a meaningful chance at full rights. Trading away that chance for everyone is surrender, not protection.
[C2.4] The detection problem PRO leans on, that creators cannot see what was scraped, has a narrower fix: require disclosure of training sources. That fix preserves consent. Compulsory licensing abolishes it.
[C2.5] Now the pennies. PRO compares this to Spotify [P2.3], but Spotify counts streams, a measurable act of consumption tied to each track. Training has no such meter. A work is ingested once, blended with billions of others, and there is no principled way to say what any single piece contributed.
[C2.6] So distribution will fall back on crude proxies, such as catalogue size or registration, which favour the big publishers PRO claims to be rescuing. PRO still has no answer to its own admission that owners are "impossible to identify" [P1.1]. Unidentifiable owners cannot be paid. Their share sits in unclaimed pools or flows to whoever registers first.
[C2.7] On giants [P2.4]: a set rate shields only those who can pay it. A university lab or open-source project faces the same statutory bill and audit burden as the richest lab, without the revenue. Litigation risk for small players is speculative. The fee is certain.
[C2.8] On precedent [P2.5]: courts have repeatedly treated intermediate, non-expressive copying as fair use, with book scanning for search the best-known example. That makes training a hard case, not an obvious taking.
[C2.9] PRO wants to rescue creators [clipped]

## Turn 5: PRO Pressure Questions

- model: glm-5-3-high
- raw_words: 81
- clipped_words: 81
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say the status quo offers a "meaningful chance at full rights" [C2.3]. For a freelance illustrator with one mislabeled image in a billion-file corpus, what does that chance cost in litigation fees—and how many of your protected creators can actually afford it?
[P3.2] Q2: Your alternative is disclosure of training sources [C2.4]. Once a creator sees her work was used, what remedy does she have without a licensing scheme—and why would any lab stop scraping rather than just publish lists?

## Turn 6: CON Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: You concede most owners are "impossible to identify in advance" [P1.1], and training has no per-use meter. Under your scheme, by what formula does money reach that freelance illustrator, and who keeps the share owed to creators nobody can find?
[C3.2] Q2: If that illustrator refuses to let her work train a model, can she opt out under your scheme? If yes, it isn't compulsory. If no, why is removing her right to say no "protecting" her?

## Turn 7: PRO Rebuttal 2

- model: glm-5-3-high
- raw_words: 356
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.2]
- missing_claim_id_refs: (none)

[P4.1] A1: The illustrator gets paid the way session musicians got paid when sampling outgrew per-use tracking: through a collective society that distributes based on the actual composition of training corpora. Labs already know what they trained on—they keep data cards, filter lists, and dataset manifests to defend fair use claims and remove harmful content. The "impossible to identify" problem is identification by the creator, not by the trainer. Mandatory provenance records turn the lab's private knowledge into a distribution key.
[P4.2] Unclaimed shares don't vanish into whoever registers first: they're held in escrow, as orphaned royalties are today, and eventually fund blanket creator programs—the same structure copyright tribunals have used for decades when a rights holder surfaces late or never does.
[P4.3] A2: No, she can't opt out, and I won't pretend otherwise. But here is the question that answers: when has she ever been able to say no? CON's veto is a legal fiction for anyone without litigation capital. Her image is scraped today, she has no realistic way to find out, no realistic way to prove it, and no realistic way to fund a suit against a trillion-dollar defendant.
[P4.4] CON offers her a "right to refuse" she cannot exercise, and calls that dignity. I offer her money she can actually deposit. A check is not consolation for a lost veto; it is the first real thing she has ever received from this pipeline.
[P4.5] Notice what these answers expose. CON's strongest ground [C3.1, C3.2] is that the scheme is imperfect and coercive. But the coercion already exists—it's just unpriced and unaccounted. The motion doesn't take away an enforceable right; it converts an unenforceable one into compensation, and it does so with machinery copyright law has built before.
[P4.6] And CON's fallback—wait for the lawsuits to settle the law [C2.2]—is a gamble with other people's livelihoods. If creators lose, they get nothing, permanently. If they win, only the largest plaintiffs collect. Either way, the long tail CON claims to defend is left holding a principled exclusion and an empty pocket.
[P4.7] The check versus [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 371
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1], [P1.1], [P4.3], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: She doesn't pay those fees, because she doesn't need to sue alone. Class actions and suits by authors' guilds, artists' groups, news publishers and image libraries are already testing whether unlicensed training infringes. A win there sets precedent for everyone, including her. One ruling that training requires permission restores her veto and hands every creator bargaining power at once.
[C4.2] PRO's scheme removes that possibility before any court decides it, for all creators, forever.
[C4.3] A2: Once disclosure shows her work was used, she has whatever remedies copyright law provides if courts find training infringing: injunctions, damages, and membership in a class. Labs would not simply publish lists and keep scraping, because a published manifest of unlicensed works is evidence of copying against themselves. Disclosure makes taking without permission costly. That pushes labs toward licensing, whether direct or collective, while creators still keep the right to refuse.
[C4.4] Now look at what PRO's own answers concede. In [P4.1], PRO says labs "already know what they trained on" through data cards and manifests. That destroys the case for compulsion. The motion's founding premise was that owners are "impossible to identify" [P1.1], so markets can't work.
[C4.5] If trainers can identify works well enough to distribute royalties, they can identify them well enough to ask permission and pay a negotiated price. PRO has proven the voluntary market is feasible and still insists on abolishing consent.
[C4.6] Second, PRO admits in [P4.3] that she "can't opt out." So the motion's defining feature is taking away her right to refuse. PRO justifies that by calling the right unenforceable, but the fix for a hard-to-enforce right is disclosure and collective enforcement. Confiscating the right does not fix it.
[C4.7] Third, PRO's escrow answer [P4.2] concedes that the unidentifiable creators' money goes into "blanket programs" run by administrators, not to them. The long tail gets a promise, and the tribunal sets the rate.
[C4.8] So the comparison is clean. PRO's world permanently legalizes taking, at a price creators cannot refuse, distributed by proxies they cannot control. Our world keeps the veto alive [clipped]

## Turn 9: PRO Closing

- model: glm-5-3-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.5]
- missing_claim_id_refs: (none)

[P5.1] CON's last word is that if labs can identify works, they can license them voluntarily [C4.5]. But identification was never the barrier—transaction costs were. Knowing what you trained on doesn't make it possible to strike millions of separate deals, each with a party who has no leverage and every incentive to hold out. A registry of provenance doesn't create a market; a collective rate does.
[P5.2] That is the whole history of compulsory licensing, and it's why CON's "voluntary market" remains a handful of big-publisher deals plus a promise.
[P5.3] And that is the single reason this debate resolves for the motion. CON's entire case is a wager: that class actions will win, that precedent will restore a veto, that disclosure will shame labs into paying. Maybe. But every branch of that wager pays out slowly, uncertainly, and mostly to the largest plaintiffs.
[P5.4] My scheme pays now, to everyone the corpus touched, through machinery copyright law has run for a century.
[P5.5] CON asks creators to bet their livelihoods on litigation they don't fund and can't control. The motion offers the only guaranteed thing on the table: payment. When one side offers a check and the other offers a lawsuit, take the check.

## Turn 10: CON Closing

- model: claude-opus-5-5-high
- raw_words: 215
- clipped_words: 215
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: [P5.1], [P4.1], [P4.3], [P4.2]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing gives the game away. PRO now says identification was never the barrier, only transaction costs [P5.1]. But transaction costs are solved by collective licensing, not by compulsion. Creators can pool their rights voluntarily, the way songwriters join collecting societies, and license a whole catalogue in one deal.
[C5.2] Labs already know what they trained on [P4.1]. So everything PRO values — the pool, the provenance records, the distribution machinery — works without forcing anyone to sell.
[C5.3] So ask what the word "compulsory" actually adds. It adds exactly two things. First, it removes the illustrator's right to refuse, which PRO admitted she "can't opt out" [P4.3]. Second, it lets a tribunal set the price instead of the people who own the work.
[C5.4] That is the motion's entire marginal contribution, and both parts take something from creators.
[C5.5] PRO calls the result a guaranteed check. By PRO's own design, the rate is set by regulators wary of pushing training offshore, and the unidentifiable creators' share goes to escrow and "blanket programs" [P4.2]. It is a small check, at a price nobody negotiated, for many creators never delivered, bought with the permanent surrender of their rights.
[C5.6] A voluntary collective gets creators paid and keeps their consent. Compulsion only takes the consent away. That is why you vote CON.
