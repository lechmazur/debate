# Debate prop_0154__claude-opus-4-7-adaptive__qwen3.7-max__s0__tpl_placement_active_20260320f

- topic_id: prop_0154
- proposition: Copyright law should create a compulsory licensing scheme for training foundation models on copyrighted text and images, with payment to rightsholders.
- model_pro: claude-opus-4-7-adaptive
- model_con: qwen3.7-max
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-4-7-adaptive
- raw_words: 320
- clipped_words: 320
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Foundation models are built on the largest unlicensed taking of creative work in history. The choice in front of us is not "license vs. open internet." It is litigation chaos versus an orderly system that pays creators. Compulsory licensing is how we get the second one.
[P1.2] Start with the status quo. Right now, a handful of well-capitalized labs scraped the web, trained on copyrighted novels, journalism, photographs, and illustrations, and are litigating fair use case by case in courts that move in years. Two things follow. First, individual writers and artists cannot realistically sue a frontier lab; only the New York Times-sized rightsholders can.
[P1.3] Second, if fair use loses even once at scale, the resulting injunctions and statutory damages could detonate models people already depend on. Compulsory licensing fixes both: creators get paid by default, and labs get legal certainty.
[P1.4] Compare it to the analog precedent that actually works. Songwriters do not negotiate one-by-one with every radio station and streaming service; a compulsory mechanical license sets a rate, a collecting body distributes the money, and the music industry functions. Without that scheme, radio and Spotify would be impossible. Training corpora are the same structural problem: billions of works, impossible transaction costs, obvious public benefit to broad use.
[P1.5] That is exactly the situation compulsory licensing was invented for.
[P1.6] Look at the alternatives. Pure opt-in licensing favors incumbents who can afford bespoke deals with Reddit, Getty, and major publishers, and crushes open-source and academic labs who cannot. Pure fair use pays creators nothing while their work trains their replacements. A compulsory scheme, with a statutory rate and a collecting society, lets a university lab, a startup, and Google all train on the same terms, while a freelance illustrator actually receives a check.
[P1.7] The motion is not whether AI should exist. It is whether the people whose work makes it possible get paid. Compulsory licensing is the only mechanism that scales to "yes."

## Turn 2: CON Opening

- model: qwen3.7-max
- raw_words: 301
- clipped_words: 301
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition relies on a fatally flawed analogy and ignores the administrative reality of machine learning. PRO compares AI training to streaming a song. But a mechanical license pays for the distribution of a finished, identifiable work to a listener. AI training is fundamentally different: it is the computational equivalent of reading.
[C1.2] We do not have compulsory licensing for human students reading library books to learn how to write, and we should not have it for algorithms analyzing text to learn statistical patterns. Treating ingestion as a licensed performance misreads copyright law, which protects specific expression, not underlying facts or styles.
[C1.3] Even if we accept the premise, the mechanics of PRO’s scheme are an administrative nightmare. Foundation models train on trillions of tokens. Under a compulsory scheme, labs must track the exact provenance of every fragment, calculate its microscopic contribution to billions of neural network weights, and distribute payments. The transaction costs will dwarf the payouts.
[C1.4] We will create a massive new bureaucracy of collecting societies that absorb the vast majority of the funds in overhead, while the freelance illustrator PRO champions receives a check for fractions of a penny. It is a wealth transfer from tech companies to collection agencies, not creators.
[C1.5] Finally, PRO claims this scheme levels the playing field for startups and open-source labs. It does the exact opposite. A compulsory licensing fee on training ingestion imposes a massive upfront capital requirement before a model even generates a single output or dollar of revenue. Only hyper-capitalized incumbents can afford the billions in upfront licensing float required to ingest a trillion-token corpus.
[C1.6] Open-source developers, academic researchers, and small startups will be priced out of existence, cementing the exact monopoly PRO claims to oppose. Fair use allows David to compete with Goliath. Compulsory licensing is the moat that protects Goliath.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-4-7-adaptive
- raw_words: 335
- clipped_words: 335
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The "AI training is just reading" line is the keystone of CON's case, and it cannot hold the weight. A human reader buys the book, borrows it from a library that paid for it, or accesses it through a licensed database. The "reading" analogy actually concedes my point: somewhere in the chain, someone paid. What labs did was closer to xeroxing every book in the store and walking out.
[P2.2] And unlike a student, a foundation model is a commercial product that competes directly with the illustrators, novelists, and journalists whose work was ingested. Reading does not produce a substitute good at industrial scale. Training does.
[P2.3] On the "administrative nightmare": CON imagines we must trace each token's microscopic contribution to each weight. No compulsory scheme works that way, and mine doesn't either. Mechanical licensing doesn't measure how much each note influenced a listener's brain. It sets a statutory rate on an input — per work ingested, per gigabyte of corpus, per model trained — and a collecting society distributes by sampling and registry, the way ASCAP and the Copyright Royalty Board already do at scale.
[P2.4] Imperfect? Yes. More perfect than zero, which is what creators get now? Obviously.
[P2.5] The "moat for Goliath" argument is exactly backwards, and CON's own framing gives it away. Today, OpenAI, Google, and Meta are signing nine-figure bespoke deals with Reddit, News Corp, Getty, Stack Overflow. Startups and academics cannot replicate those deals — that is the moat, and it exists right now. A statutory rate is the anti-moat: the same posted price for everyone, with tiered or nonprofit-exempt rates for academic and open-source training, which every compulsory scheme in copyright already does.
[P2.6] CON's "fair use lets David compete" world is the world where David gets sued into oblivion the moment his model matters, while Goliath has indemnified licenses.
[P2.7] The clash is simple. Under CON: creators paid nothing, incumbents locked in by private deals, small labs exposed to litigation. Under PRO: everyone pays the same posted rate, and creators actually see money.

## Turn 4: CON Rebuttal 1

- model: qwen3.7-max
- raw_words: 304
- clipped_words: 304
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO claims AI labs "xeroxed the store." But xeroxing creates an exact copy of protected expression. Training extracts uncopyrightable statistical patterns. Copyright protects specific expression, not the underlying facts, ideas, or styles a model learns.
[C2.2] PRO’s "substitute good" argument fatally conflates market competition with copyright infringement. If I write a sci-fi novel after reading a hundred others, I compete in the same market, but I haven't infringed their copyrights. Learning is not infringement, even at industrial scale.
[C2.3] PRO retreats from tracking individual tokens, suggesting a statutory rate per gigabyte distributed via sampling, like ASCAP. This analogy collapses on contact with reality. ASCAP tracks public performances of specific, identifiable songs. You cannot "sample" a neural network to determine which of a billion ingested articles influenced its weights.
[C2.4] More importantly, a registry-based collection society only pays creators who formally register their work. The freelance illustrator PRO champions will not navigate a complex bureaucratic registry for fractions of a penny. The funds will flow almost entirely to large publishers and aggregators who already have legal teams to handle the paperwork.
[C2.5] Finally, PRO claims a statutory rate with "tiered or nonprofit exemptions" is an anti-moat. This is a fatal contradiction. If you exempt open-source and academic labs, commercial incumbents will simply release "open weights" or create nonprofit shells to bypass the fee, gutting the revenue stream. If you enforce the fee strictly on everyone, you price out the actual startups and researchers who cannot afford the massive upfront capital required for a trillion-token corpus.
[C2.6] PRO’s scheme doesn't protect David; it forces David to pay a toll to a bureaucratic registry just to learn, while Goliath exploits the open-source loophole. We should not dismantle the most successful engine of innovation in history to fund a broken collection agency. Fair use preserves the fundamental right to learn without a tollbooth.

## Turn 5: PRO Pressure Questions

- model: claude-opus-4-7-adaptive
- raw_words: 99
- clipped_words: 99
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5], [C2.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: You concede commercial labs will exploit any nonprofit exemption by releasing "open weights" shells [C2.5] — but that loophole exists only if there's a fee to dodge. Doesn't that admit the status quo already lets commercial Goliaths take everything for free, and that a strict statutory rate with anti-circumvention rules is strictly better for creators than zero?
[P3.2] Q2: If "training is just learning" and learning is never infringement [C2.2], then on your view what, if anything, do scraped novelists and illustrators recover — ever — even if a court finds the copying during ingestion was not fair use?

## Turn 6: CON Pressure Questions

- model: qwen3.7-max
- raw_words: 88
- clipped_words: 88
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO suggests rates based on "per work ingested, per gigabyte of corpus, per model trained" [P2.3]. These are mutually exclusive. If you charge a flat fee "per model," how do you distribute that lump sum to specific creators without the exact token-tracking bureaucracy you rejected?
[C3.2] Q2: PRO relies on distribution "by sampling and registry" [P2.3]. Since compulsory schemes inherently cover unregistered works, doesn't requiring creators to register to claim their share simply funnel the vast majority of funds to large publishers who already maintain comprehensive copyright databases?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-4-7-adaptive
- raw_words: 339
- clipped_words: 339
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.2]
- missing_claim_id_refs: (none)

[P4.1] A1: They're not mutually exclusive — they're layered, the way real royalty systems already work. The fee is assessed on the lab as a per-corpus or per-model statutory rate (the easy, enforceable part). Distribution to creators is a separate problem solved the way mechanical and performance royalties already solve it: a pool, with shares allocated by registry claims plus statistical sampling of the training corpus to estimate proportions by publisher, genre, language, and medium. No one needs to prove which token nudged which weight.
[P4.2] SoundExchange distributes billions without measuring how each spin affected each listener. The "exact token-tracking bureaucracy" is CON's strawman, not my scheme.
[P4.3] A2: Yes, registries skew toward organized rightsholders — which is exactly why every modern compulsory scheme pairs registry claims with unclaimed-funds rules: a fixed percentage is distributed by sampling to the class of works detected (e.g., a corpus is 12% news, 4% illustration), and unclaimed shares flow to creator funds, hardship grants, or pro-rata redistribution to small registrants. Imperfect, but the freelance illustrator gets something rather than the current something, which is zero.
[P4.4] Now the weighing. CON's whole case collapses into a dilemma they cannot escape. Either training copies protected expression — in which case creators deserve a remedy, and a statutory rate is plainly better than billion-dollar lawsuits only the New York Times can file — or training is "just learning" and creators recover nothing, ever, no matter how much their market is cannibalized. CON picked door two in [C2.2].
[P4.5] That is the honest CON position: novelists and illustrators get a thank-you note while a commercial substitute trained on their work eats their lunch.
[P4.6] Compare the two worlds. Under CON: Goliath keeps the bespoke nine-figure deals it's already signing with Reddit and News Corp, David gets sued when he matters, and creators get nothing. Under PRO: one posted rate for everyone, anti-circumvention rules on nonprofit shells, imperfect distribution that still beats zero. The administrative mess CON describes is the price of paying creators at all.
[P4.7] The alternative isn't clean — it's just unpaid.

## Turn 8: CON Rebuttal 2

- model: qwen3.7-max
- raw_words: 292
- clipped_words: 292
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.3], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: A strict statutory rate isn't better than zero if it bankrupts the startups challenging Goliath. Commercial labs won't just use nonprofit shells; they will offshore training to jurisdictions without this scheme, while domestic startups drown in compliance. Fair use allows domestic innovation to flourish, creating downstream opportunities rather than taxing the learning process itself.
[C4.2] A2: If a court finds intermediate copying during ingestion isn't fair use, the remedy is statutory damages for the unauthorized dataset copies, not a perpetual royalty on the resulting model. Copyright already remedies actual infringement of expression. We don't need a compulsory scheme taxing uncopyrightable statistical learning just to compensate for intermediate copying.
[C4.3] PRO admits their distribution relies on "statistical sampling" and "unclaimed-funds rules" [P4.3]. This is a fatal concession. They cannot pay the specific freelance illustrator whose work was ingested. Instead, they create a massive slush fund managed by collecting societies.
[C4.4] "Unclaimed shares" flowing to "creator funds" [P4.3] isn't a copyright royalty; it is a tax on AI development redistributed by a bureaucratic cartel.
[C4.5] PRO's dilemma [P4.4] is false. Recognizing that training extracts uncopyrightable patterns doesn't mean creators recover nothing if actual infringement occurs. If a model outputs verbatim copyrighted text, that is infringement, and damages apply. But PRO wants to tax the input—the learning process—because they cannot prove infringement on the output.
[C4.6] By forcing a toll on reading, PRO destroys the open-source ecosystem, empowers collection-agency middlemen, and fundamentally misreads copyright law. Fair use protects the extraction of ideas and patterns. PRO's world guarantees that only hyper-capitalized incumbents can afford the upfront float to train frontier models. We should not replace a dynamic, innovative market with a stagnant, bureaucratic tollbooth that pays pennies to aggregators while crushing the very startups that challenge incumbent monopolies.
[C4.7] Vote CON.

## Turn 9: PRO Closing

- model: claude-opus-4-7-adaptive
- raw_words: 207
- clipped_words: 207
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.2]
- missing_claim_id_refs: (none)

[P5.1] Decide this debate on the dilemma CON never escaped.
[P5.2] Either ingestion copies protected expression, or it doesn't. CON now says: if it does, the remedy is statutory damages on the dataset copies [C4.2]; if it doesn't, creators get nothing. Look at what that world actually delivers. Statutory damages are recovered by whoever can afford federal litigation against a frontier lab.
[P5.3] That is the New York Times. It is not the freelance illustrator. Under CON, the illustrator's only "remedy" is hoping the model regurgitates her work verbatim — which is exactly what labs engineer against.
[P5.4] So CON's world pays the largest rightsholders through lawsuits, pays incumbents through bespoke nine-figure deals they're already signing, and pays everyone else zero. That is the actual moat.
[P5.5] PRO's world is admittedly imperfect: sampling, registries, unclaimed-funds pools. CON calls that a "slush fund." Call it what you want — it is the only mechanism on the table that routes any money to the small creator at all, at a posted rate every lab pays, with nonprofit tiers and anti-circumvention rules.
[P5.6] The choice is not bureaucracy versus purity. It is imperfect payment to creators versus none. When the question is whether the people whose work built the model get paid, "imperfect but real" wins.

## Turn 10: CON Closing

- model: qwen3.7-max
- raw_words: 182
- clipped_words: 182
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s case rests on the illusion that their compulsory scheme actually pays the freelance illustrator. Look at the mechanics they conceded: a massive upfront tax on training data, distributed via statistical sampling and unclaimed-funds pools to registered rightsholders. That is not a royalty; it is a bureaucratic slush fund that overwhelmingly benefits large publishers and aggregators who already maintain comprehensive databases. The illustrator gets fractions of a penny.
[C5.2] Worse, this tollbooth destroys the ecosystem that actually challenges incumbent monopolies. PRO claims their posted rate is an "anti-moat," but forcing startups to secure billions in upfront licensing float before training a single model is the ultimate moat. It prices out David to protect Goliath. Commercial labs will simply offshore their training or exploit nonprofit loopholes, while domestic startups drown in compliance.
[C5.3] We do not need to dismantle fair use—the principle that allows algorithms to learn uncopyrightable patterns just as humans do—to fund a broken collection agency. Copyright protects specific expression, not the underlying facts a model learns. PRO’s scheme suffocates innovation to pay pennies to middlemen. Protect the right to learn.
[C5.4] Vote CON.
