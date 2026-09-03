# Debate prop_0154__claude-fable-5-1-high__muse-spark-1.1-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0154
- proposition: Copyright law should create a compulsory licensing scheme for training foundation models on copyrighted text and images, with payment to rightsholders.
- model_pro: claude-fable-5-1-high
- model_con: muse-spark-1.1-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 335
- clipped_words: 335
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Right now, every creator whose work sits inside a training set is in one of two positions: they are paid nothing because a court calls it fair use, or they are paid nothing because they cannot afford to sue. Meanwhile, the only licensing deals that exist are struck between a handful of frontier labs and a handful of media conglomerates. That is the status quo, and it is the worst of both worlds: creators uncompensated, and access to training data concentrated in whoever has the biggest legal department.
[P1.2] A compulsory license fixes both problems at once. Anyone may train on lawfully accessed copyrighted text and images, but they must pay a statutory royalty into a collecting mechanism that distributes to rightsholders. Copyright has used exactly this tool whenever individual bargaining collapses under transaction costs. A musician does not need permission to record a cover song; they pay the mechanical rate.
[P1.3] Cable systems retransmit broadcasts under statutory license. Radio pays performance royalties through collectives rather than negotiating with every songwriter on Earth. Training data is the extreme case of that logic: billions of works, hundreds of millions of owners, and no realistic way to clear them one by one.
[P1.4] Consider the alternatives the other side must defend. Pure fair use means the illustrator whose ten thousand drawings taught a model to draw gets nothing, forever. Pure opt-in means only companies rich enough to sign Getty and Reuters can build models, startups and researchers are locked out, and training migrates to jurisdictions that will never send a cent back to creators. Litigation as policy means a decade of inconsistent verdicts while the technology is built anyway.
[P1.5] The compulsory license is not a compromise of copyright. It is copyright doing what it was designed to do: securing payment for authors while ensuring the public still benefits from new works and new tools. The debate is not whether models will train on this material. They already have.
[P1.6] The only question is whether the people who made it get paid.

## Turn 2: CON Opening

- model: muse-spark-1.1-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: [P1.6], [P1.2], [P1.4], [P1.1]
- missing_claim_id_refs: (none)

[C1.1] Copyright was never just about getting paid. It is about control - the right to say no. An author can refuse a film adaptation she finds degrading, a photographer can refuse use by a campaign he despises. PRO reduces that entire bundle to a cash register. When they say [P1.6] "the only question is whether people get paid," they erase the illustrator who does not want her style cloned at any price.
[C1.2] Some uses are not for sale.
[C1.3] Second, their historical analogy fails. A cover song from [P1.2] still plays the song to the public. Cable retransmission still shows the broadcast to viewers. Training does not.
[C1.4] A model does not reproduce your novel to a reader; it learns statistically that sentences have verbs and cats have whiskers. That is reading to learn, the classic case for fair use - intermediate, transformative, non-expressive use. A compulsory license would declare for the first time that learning from lawfully accessed works is infringement unless you pay. That is not copyright doing what it was designed to do.
[C1.5] It is inventing a new monopoly over reading itself.
[C1.6] Third, the machinery is unadministrable and regressive. How do you weigh one New Yorker cartoon versus ten thousand Reddit comments? Who audits what was actually in the set, and how often it was seen? We know how this ends: another collecting society where major publishers bulk-register catalogs and harvest the pool, while the working artist in [P1.4] gets a statement for $1.27.
[C1.7] Finally, it achieves the opposite of [P1.1]. Fair use lets a grad student, a nonprofit lab, or an open-source community train on the public web for free. A compulsory regime imposes tracking, metering, reporting and royalties from epoch one. That does not democratize AI.
[C1.8] It kills academic research and open models and ensures only the frontier labs PRO fears can afford to build.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 333
- clipped_words: 333
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Notice the fault line running through the case you just heard. The first argument says copyright is about control, the right to say no. The second argument says training is fair use, reading to learn, free by right. Those cannot both be true. Under fair use, the illustrator who does not want her style cloned "at any price" gets no veto, no notice, and no cheque.
[P2.2] CON's own preferred outcome strips her of exactly the control they claim to be defending. The only regime that gives her a real "no" is pure opt-in, which CON conspicuously refuses to endorse because it locks out everyone but Getty's counterparties. So the choice on the table is not control versus cash. It is cash versus nothing.
[P2.3] And copyright has already made this trade. A songwriter cannot stop a cover version he finds degrading; he gets the mechanical rate. Compulsory licensing has meant "you cannot say no, but you will be paid" for a century. That is not inventing a monopoly over reading.
[P2.4] Nobody proposes licensing a human who reads a novel. The license covers a commercial enterprise copying billions of works wholesale onto its servers to build a product it sells. Calling that "learning that cats have whiskers" describes the output; it ignores that the input was complete reproduction at industrial scale. If this use were obviously non-expressive and worthless to license, frontier labs would not be paying newswires and photo agencies for it right now.
[P2.5] The market has already priced training data. The only question is whether the price is paid to everyone or only to whoever can threaten a lawsuit.
[P2.6] On administrability: the $1.27 statement is a real concern, and it is still infinitely more than fair use pays. Weighting by volume ingested is crude, but ASCAP started crude too.
[P2.7] On research: exempt noncommercial and academic training, tier rates by revenue. Startups gain certainty and guaranteed access; today they get a decade of litigation risk instead. Certainty is what lets small builders raise money.

## Turn 4: CON Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 358
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] The fault line you claim in [P2.1] is just how copyright has always worked. Authors get strong control over their core markets - who reproduces the book to readers. They don't get control over who looks at the book to learn that sentences have verbs. Style, ideas, facts were never copyrightable.
[C2.2] So there is no contradiction. The illustrator who doesn't want her drawing reprinted on t-shirts can say no. The illustrator who doesn't want anyone to learn what a hand looks like from her drawing never had a veto. My position isn't "cash vs nothing" [P2.2]; it's control where the law grants control, and freedom where it doesn't.
[C2.3] That is why your century-old trade [P2.3] doesn't travel. A cover song still delivers the song itself to the public - the exact market the songwriter owns. Cable still delivers the broadcast. Training doesn't deliver the novel to a reader.
[C2.4] It makes an intermediate copy to extract statistics, not expression. That is why courts have repeatedly called this kind of non-expressive intermediate use fair - from Sega to Google Books - even when done by commercial firms. You say in [P2.4] that this ignores wholesale copying onto servers. That wholesale copying is precisely what fair use evaluates, and commerciality alone does not make it infringement.
[C2.5] The fact labs cut deals with Reuters [P2.5] doesn't prove the whole web has a market price. They pay for freshness, live feeds, liability insurance, and lawsuit avoidance, not because a ten-year-old blog post commands a training royalty. You would extend that premium price to the entire internet, retroactively inventing a monopoly over reading itself.
[C2.6] And $1.27 is not infinitely better than zero [P2.6] if zero is the correct price. It is worse, because to pay it you force every grad student and open-source lab to install tracking, metering, and reporting from epoch one. Your patch - "exempt academic, tier by revenue" [P2.7] - is unworkable. Models start in a university, get forked on GitHub, then commercialized downstream.
[C2.7] Who owes what, when? You don't give startups certainty. [clipped]

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C1.1], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: You conceded in [C2.2] that the illustrator "never had a veto" over training. So under your regime she gets no veto and no payment; what exactly is left of the "right to say no" that [C1.1] said this debate was about?
[P3.2] Q2: If training is settled fair use, why are frontier labs paying newswires and photo agencies for "lawsuit avoidance" [C2.5]? Isn't that just a licensing market that exists only for rightsholders big enough to sue, and how does keeping it that way beat paying everyone?

## Turn 6: CON Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.6], [P1.4], [P2.7]
- missing_claim_id_refs: (none)

[C3.1] Q1: If weighting is crude but "still infinitely more than fair use pays" [P2.6], how do you set a statutory rate that doesn't funnel the pool to bulk catalog owners while the illustrator in [P1.4] still effectively gets $1.27?
[C3.2] Q2: You would exempt academic and tier by revenue [P2.7] — when a model trained for free in a lab is open-sourced, forked on GitHub, then commercialized, who owes the royalty and how do you audit what it ingested years ago?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C2.6], [C2.5]
- missing_claim_id_refs: (none)

[P4.1] A1: Set the rate as a percentage of the model operator's revenue, not a fixed per-work fee, so the pool scales with what training actually earns. Distribute by works ingested, but with a per-rightsholder ceiling and a per-work floor, so a publisher registering a million-item catalog cannot swallow the pool and a single illustrator gets a meaningful minimum. Will bulk owners still take a large share? Yes.
[P4.2] But look at who takes the money today: Reuters, Getty, the Associated Press, one hundred percent of it. The regressive-distribution objection describes CON's world perfectly and mine only partially. A crude pool that pays the illustrator something is better than a bespoke market that structurally pays her nothing.
[P4.3] A2: Liability attaches at commercialization, exactly as the mechanical license attaches when you sell the record, not when you rehearse. The academic lab owes nothing. The GitHub fork owes nothing. The company that wraps it in a paid API owes the royalty on its own revenue and must file a data manifest at that point.
[P4.4] Labs already document training sets; the scheme simply makes disclosure a condition of deployment. If a firm cannot say what its product was trained on, that is a disclosure failure, and under CON's regime it faces the identical question in discovery, with treble damages on the table instead of a rate card.
[P4.5] Now notice what went unanswered. Q1 asked what remains of the "right to say no" once you concede the illustrator "never had a veto." No answer came. The control argument is gone, and CON's case has quietly narrowed to a single sentence: zero "is the correct price" [C2.6].
[P4.6] That is the whole debate. And CON has already contradicted it. Labs pay newswires for "lawsuit avoidance" [C2.5]. Lawsuit avoidance is a price.
[P4.7] It is the price of training data, paid only to owners with litigators. CON's fair use is not free reading. It is a licensing market with an admission fee set by lawsuit capacity.
[P4.8] Compulsory licensing takes the price that already exists and pays it to everyone.

## Turn 8: CON Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [C2.2], [C1.1], [P3.2], [P4.1], [P4.3], [P2.7]
- missing_claim_id_refs: (none)

[C4.1] A1: I didn't concede control away, I located it. The illustrator keeps a full veto where copyright gives one — over reprinting her image on t-shirts, selling posters, or a model output that is substantially similar to her work. What she never had is a veto over someone studying how she draws a hand, because style, ideas, facts are not owned [C2.2]. PRO's compulsory license would erase the veto she does have: even a model that memorizes and regurgitates her drawings would be legalized for a fee.
[C4.2] That is the opposite of [C1.1].
[C4.3] A2: Labs pay Reuters and Getty in [P3.2] for what copyright never required: access behind paywalls, real-time freshness, warranties, and to avoid nuisance litigation cost before fair use is settled. Companies pay to avoid lawsuits all the time even when they would win. That avoidance payment proves there is a market for a premium live feed, not that a ten-year-old blog post commands a training royalty.
[C4.4] Those answers prove why CON still wins.
[C4.5] PRO admits in [P4.1] bulk owners still take a large share, then claims a per-work floor and per-rightsholder ceiling will fix it. A floor requires metering every image in a web crawl, which they admit labs cannot do. Their fix in [P4.3] - liability attaches only at commercialization with a data manifest - is unworkable. Common Crawl is not documented work-by-work, lineage in GitHub forks is lost, and open models would carry a retroactive legal debt that activates when someone else monetizes them.
[C4.6] That is not certainty that helps startups [P2.7]. It is a tracking, reporting and royalty tax from epoch one that kills the academic and open-source training PRO claimed to protect, while guaranteeing the pool flows to those who can bulk-register. Zero is not a giveaway; it is the correct price for non-expressive learning that extracts statistics, not expression, and keeps the right to say no where the law actually grants it.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 201
- clipped_words: 201
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C2.5], [C4.3], [C4.1]
- missing_claim_id_refs: (none)

[P5.1] Strip away the machinery and one question decides this: is the price of training data zero, or is it whatever the market already pays? CON answered it themselves. Labs pay Reuters and Getty for "lawsuit avoidance" [C2.5], and "companies pay to avoid lawsuits all the time" [C4.3]. That is a confession.
[P5.2] A price is being paid for training data today; it is simply paid only to owners who can afford litigators. "Zero is the correct price" describes the illustrator's cheque, not the market. The market has spoken, and it says training data is worth paying for.
[P5.3] Once that is true, the debate resolves. Control? CON located the illustrator's veto in t-shirts and substantially similar outputs [C4.1], and a compulsory license touches neither: it licenses ingestion, not infringing output, just as a mechanical license covers the cover, not a different song. Administrability?
[P5.4] The tracking CON fears arrives anyway, in discovery, with treble damages instead of a rate card. Research? Liability attaches at commercial deployment.
[P5.5] So the comparison is stark. CON's world: the price exists, the tracking exists, the illustrator gets nothing. Mine: the same price, the same disclosure, paid to everyone. Copyright's promise is payment for use.
[P5.6] Only one side keeps it.

## Turn 10: CON Closing

- model: muse-spark-1.1-high
- raw_words: 176
- clipped_words: 176
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.1], [C4.1]
- missing_claim_id_refs: (none)

[C5.1] The market PRO points to in [P5.1] is not a copyright market. Reuters sells access behind a gate, timeliness, warranties. Paying the bouncer does not prove the sidewalk has a toll.
[C5.2] That confusion is why CON wins on one principle. Copyright always split two worlds: control over your work being shown to the public, freedom for others to learn from it. The illustrator keeps her veto over posters and over any model output that copies her drawing — the control that actually matters [C4.1].
[C5.3] A compulsory license flips both. It legalizes the copying that should stay infringing — a model that memorizes her cat becomes licensed if you pay — and it invents infringement where there was none — learning how a hand is drawn now requires a fee.
[C5.4] So PRO does not give the illustrator control plus cash. It sells her only real veto for $1.27 and taxes every student trying to learn from the web to fund it. Zero is not a loophole. It is the price the law set for reading to learn.
