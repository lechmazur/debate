# Debate prop_0321__muse-spark-1.1-high__qwen3.7-max__s0__tpl_placement_active_20260320f

- topic_id: prop_0321
- proposition: Online creators should have a stronger default right to stop platforms from using their public work to train commercial generative-AI systems.
- model_pro: muse-spark-1.1-high
- model_con: qwen3.7-max
- side_swap: False

## Turn 1: PRO Opening

- model: muse-spark-1.1-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Putting your work where people can see it is not the same as giving it away.
[P1.2] An illustrator posts a portfolio on Instagram to find clients. A musician uploads tracks to SoundCloud to build listeners. A writer publishes essays to be read. In each case the implied deal is human attention for human benefit.
[P1.3] Using that work to train a commercial generator that can then produce endless mimics is not part of that deal. It converts the act of sharing into fuel for your own replacement.
[P1.4] That is why the default matters. Right now platforms write terms that claim a sweeping license, then repurpose years of public posts to build models that directly compete with the people who made them. Opt-out, if it exists, is buried, retroactive, or technically broken. The creator bears all the cost of discovering the misuse and trying to stop it, while the platform captures all the value.
[P1.5] A stronger default right simply flips that: assume no consent for commercial AI training unless clearly given, and require a real, easy way to say no that platforms must honor.
[P1.6] Nothing is banned. If a creator wants to opt in, for pay, exposure, or principle, they can. But the starting point should respect autonomy, not exploit it.
[P1.7] Without that, we create perverse incentives. If sharing publicly means surrendering your style, voice, and labor to a machine that will undercut you, rational creators will stop sharing publicly. They will lock work behind paywalls, private Discords, or not create at all. The open web gets poorer.
[P1.8] A public work should remain yours to steer, especially when the requested use is commercial cloning. A right to stop is the minimum that makes that true. That protects creators without killing AI: models can still be built from licensed, public-domain, and voluntarily contributed work.

## Turn 2: CON Opening

- model: qwen3.7-max
- raw_words: 281
- clipped_words: 281
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] PRO frames AI training as "cloning" or "fuel for replacement." This fundamentally mischaracterizes the technology. Training a generative model is not copying; it is computational reading. The model extracts statistical patterns, styles, and concepts, just as a human art student studies a public gallery to learn brush techniques.
[C1.2] Copyright protects specific expressions, not underlying styles, ideas, or facts. Granting creators a default right to block computational reading effectively grants them a monopoly over abstract patterns, breaking the foundational bargain of copyright law and threatening the architecture of the open web.
[C1.3] PRO suggests models can simply be built from licensed or public-domain work. This ignores the technical reality of modern machine learning. Foundational models require massive, highly diverse, contemporary datasets to function accurately and avoid severe bias. If we mandate a strict opt-in default, the only entities capable of negotiating millions of individual micro-licenses are massive tech incumbents with deep pockets.
[C1.4] This policy will inadvertently entrench the exact corporate monopolies PRO claims to oppose, effectively locking out open-source developers, academic researchers, and startups who rely on publicly available data to build competitive, transparent alternatives.
[C1.5] Finally, PRO warns that without this veto, creators will hide their work. But creators inherently depend on the open web for discoverability and audience building. The actual threat is not that creators will voluntarily retreat to private servers, but that platforms, facing impossible compliance burdens and liability fears, will deploy aggressive, automated upload filters. These filters will inevitably overblock legitimate fair use, human remixes, and standard sharing.
[C1.6] A default right to block AI reading doesn't protect creators; it fractures the internet into walled gardens, destroying the very audience access that makes public creation viable in the first place.

## Turn 3: PRO Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] Calling industrial scraping 'reading' doesn't make it harmless, it makes the analogy false [C1.1]. A student who studies your public gallery learns and then leaves with fallible memory. A commercial model trained on your entire portfolio retains a permanent, queryable copy of your aesthetic choices and can then produce infinite near-substitutes at zero marginal cost to undercut you. That is not a person learning a technique, it's a factory built from your labor to compete with you.
[P2.2] That is why [C1.2] misframes the right at stake. We are not asking copyright to own a style forever. We are asking for a default consent rule for a specific commercial reuse by platforms that already host the work. Posting publicly does not mean you consent to Nike using your face on a billboard, even though your face isn't copyrighted.
[P2.3] Platforms today flip that presumption through terms-of-service that grant themselves a sweeping, perpetual license for AI. A stronger default just says: for commercial training, assume no unless clearly said yes.
[P2.4] The 'we need it' argument [C1.3] is circular — we designed models to require mass non-consensual scraping, therefore we must allow it — and it gets the monopoly story backward [C1.4]. Right now only incumbents with massive crawl infrastructure can compete. A rights-respecting default creates a market for license, opt-in pools, and quality-curated data. Models trained this way already exist in the wild.
[P2.5] And note the proposition's limit: commercial generative-AI systems. The academic and open-source researchers CON invokes aren't the target.
[P2.6] Finally, who creates walled gardens [C1.5][C1.6]? Artists are already leaving public feeds and locking portfolios because they have no control, not because platforms over-filter. Giving creators a real, honored way to stay public but say no to training keeps the open web open. That better balances autonomy and innovation than a default of taking first and forcing creators to chase opt-outs that don't work.

## Turn 4: CON Rebuttal 1

- model: qwen3.7-max
- raw_words: 309
- clipped_words: 309
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.4], [P2.5], [P2.2]
- missing_claim_id_refs: (none)

[C2.1] PRO’s analogy of a "factory built from your labor" [P2.1] relies on a technical fiction. Generative models do not retain "queryable copies" of your aesthetic. They adjust billions of mathematical weights to understand concepts. If a model outputs a plagiarized image, that is an infringement at the output stage, which copyright already polices.
[C2.2] Granting a veto over the training stage because you fear the output is like banning the sale of paint because someone might paint a forgery.
[C2.3] PRO also claims this default right will magically spawn a "market for license" [P2.4]. This ignores transaction costs. Negotiating micro-licenses with millions of individual creators is practically impossible. The only entities that can afford the legal and compliance infrastructure to build these "opt-in pools" are the massive incumbents PRO claims to oppose.
[C2.4] Startups and open-source developers cannot clear these rights, so they are locked out. Far from breaking monopolies, this default right builds a moat around them.
[C2.5] Furthermore, PRO’s carve-out for non-commercial AI [P2.5] is dangerously naive. The boundary between commercial and non-commercial use is notoriously porous in tech. Many foundational open-source models are released by commercial labs, funded by venture capital, or integrated into commercial downstream applications. A strict default right to block commercial training will inevitably chill the entire open-source ecosystem, as independent developers simply cannot guarantee their models won't eventually touch a commercial use case.
[C2.6] Finally, PRO’s billboard analogy [P2.2] confuses the right of publicity with copyright. You cannot stop a human from studying your public portfolio to learn your brushstrokes, and you shouldn't be able to stop a machine from doing the same. AI training is computational reading, not identity theft. By demanding a default veto over the mechanical process of learning, PRO is not protecting creators from replacement; they are weaponizing copyright to tax the very act of observation, destroying the open web to save it.

## Turn 5: PRO Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C1.1], [C2.1], [C2.3], [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: If AI training is just human-like "reading" [C1.1] and models don't retain copies [C2.1], why can they memorize and reproduce near-verbatim works, and produce 10,000 substitutes per minute in a creator's exact client-facing style?
[P3.2] Q2: You say opt-in licensing entrenches incumbents [C2.3][C2.4], but today only firms with massive crawl infrastructure can compete — how does requiring clear consent make startup entry harder than a free-for-all where the biggest scraper wins?

## Turn 6: CON Pressure Questions

- model: qwen3.7-max
- raw_words: 69
- clipped_words: 69
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5], [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You limit this right to "commercial" systems [P2.5], but how do you legally enforce that boundary when open-weight models released for "research" are routinely deployed in commercial applications by third-party developers?
[C3.2] Q2: You claim an opt-in default creates a "market for license" [P2.4], but what specific mechanism allows millions of creators to negotiate micro-licenses without relying on the exact massive corporate intermediaries you claim this policy will dismantle?

## Turn 7: PRO Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 273
- clipped_words: 273
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [P2.5], [C3.2], [C2.3], [C3.1], [P1.2], [C1.6]
- missing_claim_id_refs: (none)

[P4.1] A1: The boundary is enforced where it matters — at the act of training by a commercial entity. If you are a university lab training for research, you are not a commercial generative-AI system under the proposal [P2.5]. If you are a company that releases an open-weight model trained on non-consensual scraping but benefits commercially from adoption, that release is commercial. Law already draws this messy-but-workable line in CC Non-Commercial, fair use factor one, and research exemptions.
[P4.2] Unlike CON's absolutist no-right, it is enforceable.
[P4.3] A2: No one needs a million one-to-one deals. The mechanism already exists: collective opt-in pools. Think stock libraries that only train on opted-in images, or YouTube's new toggle letting channels opt in to third-party AI training for a cut. Creators join a collective or platform setting a standard price; a startup licenses the pool with one agreement.
[P4.4] That intermediary works for creators [C3.2], not as a scraper stripping value for free [C2.3].
[P4.5] Those answers are why PRO still wins. CON's core is that consent is too hard to track, so we should abandon the right entirely [C3.1]. That's backwards. The burden should sit with the multi-billion-dollar platform extracting the value, not the illustrator who posted a portfolio just to find clients [P1.2].
[P4.6] If your business model depends on laundering commercial use through "research" releases that third parties then monetize, that proves the need for a default stop-right, not its impossibility. With a real opt-in default, posting publicly stays viable, and models can be built from willing work. That prevents the walled gardens CON fears [C1.6] — creators are locking portfolios now because they have *no* control, not too much.

## Turn 8: CON Rebuttal 2

- model: qwen3.7-max
- raw_words: 304
- clipped_words: 304
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.3], [P2.1], [P2.2]
- missing_claim_id_refs: (none)

[C4.1] A1: Memorization of verbatim works is a technical flaw called overfitting, not the intended function of the model's weights. When it happens, existing copyright law already penalizes the infringing output. Producing thousands of stylistic substitutes is not copying the creator; it is applying learned, uncopyrightable abstract rules like lighting or composition. Copyright protects specific expression, not style.
[C4.2] A2: In a free-for-all, a startup can scrape the open web using cheap, automated tools. Under an opt-in default, they must negotiate legal agreements, verify consent chains, and manage ongoing compliance. Incumbents have the legal teams and capital to build the "collective opt-in pools" PRO mentions [P4.3]; startups simply do not. The current ecosystem democratizes access to data, whereas a consent mandate builds an insurmountable legal moat.
[C4.3] These answers expose why PRO’s case fails. PRO is attempting to weaponize copyright to monopolize uncopyrightable styles [P2.1], policing the mechanical process of learning rather than actionable infringement. By demanding a default veto over training, PRO isn't protecting creators; they are handing the keys of the AI industry to massive corporate intermediaries.
[C4.4] PRO claims their "opt-in pools" [P4.3] solve the transaction cost problem, but this just recreates the exact gatekeepers they claim to oppose. Only well-funded platforms can afford to curate, license, and legally indemnify these pools. Independent developers and open-source researchers are locked out because they cannot clear these rights or afford the compliance infrastructure.
[C4.5] Ultimately, PRO’s framework relies on a fundamental misunderstanding of both technology and law. They want to treat computational reading as identity theft [P2.2] and use a consent mechanism that only Big Tech can navigate. If we adopt this default right, we don't empower the independent illustrator; we franchise the open web to a few licensed mega-corporations, destroying the ecosystem that allows creators to be discovered. The open web deserves better than a paywalled monopoly.

## Turn 9: PRO Closing

- model: muse-spark-1.1-high
- raw_words: 155
- clipped_words: 155
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.2], [P4.3]
- missing_claim_id_refs: (none)

[P5.1] The debate comes down to who pays for consent.
[P5.2] CON's whole engine is: tracking permission is expensive for builders, so we should make it free [C4.2]. That is not democratizing data, it's subsidizing commercial cloning with creators' careers.
[P5.3] CON says a student reading a gallery is the same as retaining a permanent weight-space copy that can pump out 10,000 substitutes in that student's exact earning style. It isn't. Human learning forgets; models never do, and the harm arrives before any single output is litigated.
[P5.4] And the monopoly story is backwards. Today only firms with planet-scale crawlers win. A default no-for-training-unless-yes creates what CON says is impossible: one deal to license a pool of willing work [P4.3] — the market YouTube's own toggle already points toward — because now the incentive is to build it.
[P5.5] If sharing publicly means surrendering your future, creators will stop sharing. The right to say no keeps the open web open.

## Turn 10: CON Closing

- model: qwen3.7-max
- raw_words: 180
- clipped_words: 180
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s case rests on a comforting fiction: that a default veto over AI training empowers the independent creator. It does not. It empowers the corporate gatekeeper.
[C5.2] When PRO demands a right to block computational reading, they are not protecting specific expressions; they are attempting to monopolize uncopyrightable styles and abstract patterns. Copyright was never meant to tax the mechanical process of observation.
[C5.3] PRO claims "opt-in pools" will solve transaction costs. But look at who actually builds these pools. Negotiating, verifying, and indemnifying millions of micro-licenses requires massive legal infrastructure. The only entities capable of clearing these rights are the exact tech incumbents PRO claims to oppose.
[C5.4] Startups and open-source developers simply cannot afford this moat. By mandating a consent default, PRO doesn't dismantle monopolies; they franchise the open web to a few licensed mega-corporations.
[C5.5] Furthermore, platforms terrified of liability will deploy aggressive upload filters, overblocking legitimate sharing and human remixes. Creators won't be protected; they will be locked out of the very ecosystem that makes public discovery possible.
[C5.6] The open web thrives on shared knowledge, not paywalled observation. Vote CON.
