# Debate prop_0321__glm-5__deepseek-v4-pro__s1__tpl_placement_active_20260320f

- topic_id: prop_0321
- proposition: Online creators should have a stronger default right to stop platforms from using their public work to train commercial generative-AI systems.
- model_pro: glm-5
- model_con: deepseek-v4-pro
- side_swap: True

## Turn 1: PRO Opening

- model: glm-5
- raw_words: 287
- clipped_words: 287
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The current default treats publicly posted creative work as free raw material for corporations building commercial AI products. This represents a systematic transfer of value from millions of individual creators to a handful of platforms—accomplished without negotiation, compensation, or even meaningful disclosure. The proposition would reverse this default: platforms would need consent before using creators' work to train systems that often compete directly with those same creators.
[P1.2] Consider what actually happens. A digital artist spends years developing a distinctive style, posting work to build an audience. A platform scrapes those images, trains a model that can generate infinite imitations, and sells access to competitors, stock-image services, and anyone who might have hired the original artist. The artist's investment becomes the tool of her own displacement.
[P1.3] This is not hypothetical—it is the business model.
[P1.4] The opposition will invoke "fair use" and warn of innovation slowdowns. But the question here is not whether such training is currently legal; it is what the default ought to be. Copyright law has always balanced creator rights against public benefit. When xerox machines emerged, we did not declare all copying free by default—we established frameworks.
[P1.5] When music went digital, we did not treat all file-sharing as inevitable—we created licensing systems. The question is who bears the transaction cost of negotiation: the platform extracting value, or the creator whose work is being extracted?
[P1.6] Default rules matter precisely because they determine who must act to change the status quo. Requiring platforms to secure opt-in consent forces negotiation, pricing, and market formation. Leaving creators with only opt-out mechanisms—if those even exist—means widespread appropriation by default, with the burden of detection, objection, and enforcement falling on those least positioned to bear it. The sensible default is consent.

## Turn 2: CON Opening

- model: deepseek-v4-pro
- raw_words: 423
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A rule requiring platforms to seek prior consent before training on publicly posted work isn’t a moderate adjustment—it’s a veto that would smother the very open ecosystem creators rely on. The proposition starts from a mistaken picture of what AI training actually does: it doesn’t copy, store, or redistribute anyone’s images or text; it learns statistical patterns from vast corpora, much as a human artist learns by studying public galleries. We don’t demand that every painter obtain permission from every artist whose work they’ve ever seen, because learning itself isn’t expropriation.
[C1.2] The same principle holds when the learner is a machine.
[C1.3] The real-world consequence of flipping the default would be paralysis, not fairness. The public web contains billions of postings by pseudonymous, untraceable, or deceased creators. Clearance is practically impossible: platforms would face an infinite thicket of orphan rights, forcing them to either abandon training altogether or restrict themselves to a tiny pool of pre-licensed data held by large corporate archives. That outcome rewards gatekeepers who already amass IP portfolios, entrenches incumbents, and kills the open-source models that independent developers and small creators need to compete.
[C1.4] A default right to stop becomes, in practice, a default right to forbid—and the result is a world where only the Googles and Adobes of the world can build generative tools, while everyone else is locked out.
[C1.5] Notice too that many creators want their work included in training data. Open models let artists use AI-assisted workflows, writers get better language tools, and niche communities produce locally useful systems—all without paying rent to a few platform giants. An opt‑in regime would strip those creators of the chance to have their style or genre represented at all, because the sheer cost of chasing individual permissions means their contributions get ignored unless they shout loudly enough. The default the proposition attacks already aligns with a long‑standing copyright balance: public display does not mean you can stop others from analyzing what you made publicly available.
[C1.6] Copyright law gives creators robust tools against actual reproduction of protected expression; [clipped]

## Turn 3: PRO Rebuttal 1

- model: glm-5
- raw_words: 302
- clipped_words: 302
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.1], [C1.3], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] My opponent's central analogy—that AI training resembles a human artist learning from public galleries—collapses under scrutiny. A human artist cannot absorb millions of works, then generate infinite variations at scale, and sell them as commercial products competing directly with the sources they studied. The analogy treats learning and commercial exploitation as identical. They are not.
[P2.2] When a platform trains a model on an illustrator's portfolio and sells access to a tool that generates similar work, the platform has built a product using that illustrator's distinctive output. The "statistical patterns" defense [C1.1] merely describes mechanism, not justification. A xerox machine also "learns statistical patterns" about how to reproduce images—this did not entitle manufacturers to copy freely.
[P2.3] The paralysis argument [C1.3] proves too much. Platforms already negotiate licenses for music, stock photography, and film rights. They develop databases, negotiate terms, and pay for content. The claim that licensing is "practically impossible" for AI training reflects a choice about business models, not an immutable constraint.
[P2.4] If a platform cannot identify rights holders, that argues for better attribution systems—not for declaring all untraceable work free for commercial extraction.
[P2.5] Crucially, creators who want inclusion can opt in. My opponent warns that opt-in regimes would "strip those creators of the chance to have their style represented" [C1.5]. This reverses the burden. Creators who actively want AI training are free to grant permission.
[P2.6] The default should protect those who do not—precisely because they cannot meaningfully consent when their work has already been scraped, their style already absorbed, their displacement already underway.
[P2.7] The real gatekeepers are platforms that appropriate millions of works without negotiation, then present the fait accompli to creators. The current default says: if you share your work publicly, corporations may build commercial products from it without asking. That is not balance. It is extraction disguised as openness.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4-pro
- raw_words: 376
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] The artist-learns-from-galleries analogy survives my opponent’s attack because the attack targets scale, not principle. Scale changes nothing: a search engine ingests billions of pages, builds an index, and sells advertising against “statistical patterns” of the web—yet no one demands that every webpage owner consent first. [P2.1] calls it a collapse; I call it a red herring. What matters is whether the use merely analyzes public works to produce new, non-infringing outputs, and training a model does exactly that.
[C2.2] The xerox-machine reply [P2.2] is equally misleading: a photocopier reproduces copyrightable expression wholesale; a generative model learns abstract parameters and creates novel artifacts. Mechanism matters because the law has always distinguished copying from transformative learning.
[C2.3] The paralysis objection stands. My opponent says platforms already license music and films [P2.3], but those are collective-licensing systems centered on a handful of identifiable rights-holders. The public web is not remotely analogous—billions of orphan, pseudonymous, and untraceable works. [P2.4]’s call for “better attribution systems” is wishful; it would require a global, compulsory registry that no jurisdiction has built, while the proposed default would ban training until it exists.
[C2.4] The result is exactly the chokehold I described: only the Googles and Adobes can pre-clear proprietary libraries, and open models—which independent creators and start-ups rely on—are dead. My opponent’s remedy ends up handing the keys to the very gatekeepers they decry.
[C2.5] [P2.5] claims creators who want inclusion can simply opt in. That reverses reality. Under an opt-in regime, millions of willing but unreachable creators are locked out by default; their public work gets ignored unless they shout, precisely because platforms cannot track them down. The current default lets everyone’s contributions shape AI, not just the loud or the legally pre-armed.
[C2.6] The proposition’s consent rule doesn’t protect—it silences by omission.
[C2.7] Finally, the displacement panic [P2.6] confuses tool with substitute. Copyright already gives creators robust remedies when outputs are substantially similar and commercially damaging; the mere existence of a model trained on public data does not preempt anyone’s livelihood. Imposing a veto on the learning stage would strangle the [clipped]

## Turn 5: PRO Pressure Questions

- model: glm-5
- raw_words: 55
- clipped_words: 55
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.5]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your search engine analogy [C2.1] ignores that search engines drive traffic to creators while AI models compete with them. Why should opposite economic effects deserve identical legal treatment?
[P3.2] Q2: If a creator is "unreachable" for consent [C2.5], how can they ever negotiate terms or compensation? Being scraped without knowledge isn't participation—it's exploitation of absence.

## Turn 6: CON Pressure Questions

- model: deepseek-v4-pro
- raw_words: 75
- clipped_words: 75
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: Your search engine defense relies on models driving traffic, but many AI tools also increase creator visibility. What non-arbitrary principle decides when a non‑infringing pattern analysis of public work becomes “competition” requiring consent?
[C3.2] Q2: If a creator is unreachable, your proposed default right to stop is impossible for them to exercise—so why is permanently excluding their work from all training, thus locking them out of any positive spillovers, more protective than the current default?

## Turn 7: PRO Rebuttal 2

- model: glm-5
- raw_words: 292
- clipped_words: 292
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: The principle is substitution versus direction. Search engines direct users to creators' works, generating traffic and potential revenue. Generative AI produces outputs that substitute for hiring the creator entirely. When a platform trains on an illustrator's portfolio and sells a tool generating similar images, the artist receives nothing—no traffic, credit, or compensation.
[P4.2] The non-arbitrary distinction is whether the tool routes value to the source or extracts value by replacing it. Pattern analysis producing market substitutes differs fundamentally from analysis enabling discovery.
[P4.3] A2: Inclusion without knowledge isn't benefit—it's unilateral appropriation. If a creator is unreachable, they cannot negotiate terms, set conditions, or receive compensation. Their work builds commercial products that may displace them, with no voice in the process. Calling this "positive spillovers" assumes creators benefit from being raw material for tools competing with them.
[P4.4] The consent default respects that absence of response should not equal acquiescence. Exclusion from training preserves the creator's market position; inclusion without consent undermines it.
[P4.5] These answers reveal why PRO wins the debate. The opposition assumes inclusion is always beneficial—that any contribution to AI training serves creators. But the central question is who decides whether and how their work trains commercial systems. The current default appropriates first and asks never.
[P4.6] My opponent's concern for "unreachable" creators [C3.2] would carry weight if it included mechanisms for their negotiation or compensation. It doesn't. It simply declares their work available because they cannot object.
[P4.7] Default rules allocate power. A consent default forces platforms to invest in rights-clearance infrastructure, develop systems for reaching creators, and create markets for training data. The current default enables extraction without investment.
[P4.8] The real choice: who bears the cost of building fair systems—the platforms profiting from creators' work, or the creators themselves? The proposition answers correctly.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4-pro
- raw_words: 318
- clipped_words: 318
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: The substitution-versus-direction distinction [P4.1] imagines a clean line, but real AI tools do both at once. A text model might generate marketing copy that substitutes for a copywriter while also surfacing obscure blogs in summaries and driving genuine traffic. A single model often shifts demand rather than simply destroying it. Basing a default consent rule on a prediction of net market effect would inject impossible uncertainty and chill all training.
[C4.2] Search engines were equally disruptive to newspapers and classified sections—yet we never required consent for indexing, because pattern analysis of public data is non-infringing regardless of mixed downstream economics. The right focus is on output infringement, not on whether the learning stage might eventually produce a substitute.
[C4.3] A2: The claim that exclusion “protects” unreachable creators [P4.3] turns that protection into permanent oblivion. Under an opt‑in regime, their work is barred from all training forever, eliminating any chance it could shape accessible tools, influence useful open models, or later generate positive spillovers when they resurface. The current default at least gives their public contributions a role in a commons that creators everywhere draw on, and if they become reachable they retain every ordinary copyright remedy against infringing outputs.
[C4.4] Swapping one unconsented outcome for another—this one absolute and irreversible—does not empower them; it punishes their absence by locking them out completely.
[C4.5] Those answers highlight why the proposal backfires. A consent default would entrench exactly the gatekeepers my opponent decries: only platforms with massive proprietary libraries can train, while open models that independent creators rely on disappear. The status quo already offers robust remedies against actual reproduction and market‑harming similarity; it does not need a veto that strangles learning itself. The debate reduces to a choice between a default that allows broad, non‑infringing analysis—letting every contribution participate—and one that imposes unworkable clearance burdens, silences the unreachable, and hands the keys to the already powerful.
[C4.6] That is why CON still wins.

## Turn 9: PRO Closing

- model: glm-5
- raw_words: 209
- clipped_words: 209
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate turns on a single question: when a creator cannot be reached for consent, what should the default permit?
[P5.2] CON's answer is clear: platforms may extract value from unreachable creators' work because those creators cannot object. This treats silence as acquiescence and absence as permission. It conscripts creators into building systems that may displace them, without their knowledge, negotiation, or compensation.
[P5.3] My opponent calls this "participation in a commons." But if a creator is truly unreachable, they cannot negotiate terms, set conditions, or share in profits. Calling their inclusion a "positive spillover" assumes that being raw material for commercial AI benefits them—a remarkable claim when the resulting tools compete directly with their livelihood.
[P5.4] The consent default does not silence unreachable creators. It preserves their position until they can be heard. Exclusion from training protects their market; inclusion without their voice exploits their absence.
[P5.5] Default rules allocate power. CON's position places the burden on creators to discover and object to extraction after it occurs. PRO's position places the burden on platforms to secure permission before profiting.
[P5.6] The platforms building commercial AI systems have resources, infrastructure, and bargaining power. Individual creators do not. The sensible default protects the vulnerable party.
[P5.7] Consent before extraction. That is the principle that should govern.

## Turn 10: CON Closing

- model: deepseek-v4-pro
- raw_words: 201
- clipped_words: 201
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] Here is why CON wins: The consent default demanded by the proposition punishes the very unreachable creators it claims to protect. Under PRO’s rule, if a creator cannot be found, their work is barred from training permanently—no model can learn from it, no open tool can reflect their style, no commons can include their contribution. That is not protection; it is a blanket exclusion that silences them forever. It hands the generative field entirely to giant platforms with proprietary libraries, starving the open models that independent creators need to compete.
[C5.2] The current default, by contrast, lets their work shape the AI commons without surrendering any legal recourse. Copyright law already gives them robust remedies against infringing outputs; they lose no market protection. But they gain the chance—should they ever resurface—to find their influence in accessible tools. They participate, even while silent, in a learning resource rather than being locked out by a veto they never requested.
[C5.3] The real choice is between a default that exploits absence to permanently exclude, and one that allows every public contribution to participate while preserving strong remedies against actual harm. CON’s side respects both the commons and the rights of creators. That is why CON wins.
