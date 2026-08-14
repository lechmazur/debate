# Debate prop_0652__claude-fable-5-high__gemini-3.7-flash-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0652
- proposition: Tech platforms that host and distribute user-prompted AI-generated content should share liability when that content infringes existing copyrights.
- model_pro: claude-fable-5-high
- model_con: gemini-3.7-flash-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-high
- raw_words: 317
- clipped_words: 317
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When a platform's own model generates a near-perfect copy of a copyrighted character, illustration, or song lyric, the platform is not a bulletin board where a stranger pinned something up. It manufactured that output. The proposition asks only that platforms share liability — not bear it alone — and that modest claim rests on three pillars.
[P1.2] First, causation. Traditional intermediary protections were built for a world where users created content and platforms merely transmitted it. Generative AI shatters that division of labor. The platform trained the model, often on copyrighted works, tuned its behavior, and then produced the infringing output itself in response to a prompt.
[P1.3] A user who types "draw a famous cartoon mouse" contributes a few words; the platform contributes the entire creative act of reproduction. When both parties jointly cause the infringement, both should share responsibility. That is ordinary secondary liability logic — the same principle that holds a flea market liable for knowingly hosting counterfeit stalls.
[P1.4] Second, incentives. Platforms are the least-cost avoiders. Only they can filter training data, implement output classifiers, block obviously infringing prompts, and license content at scale. Individual users can't audit a model; rights holders can't sue millions of anonymous prompters.
[P1.5] If platforms bear zero liability, they have every incentive to maximize engagement and none to invest in safeguards. Shared liability is what made YouTube build Content ID — a system that now channels billions to creators rather than leaving them to sue teenagers.
[P1.6] Third, fairness. Platforms monetize these outputs through subscriptions and API fees. The party that profits from the machine should internalize the harms the machine predictably produces. Immunizing them privatizes the gains and socializes the losses onto authors, artists, and musicians whose work made the models valuable in the first place.
[P1.7] Shared liability doesn't kill innovation; it disciplines it. It tells platforms: build responsibly, license fairly, filter reasonably — or answer for the copies you generate.

## Turn 2: CON Opening

- model: gemini-3.7-flash-high
- raw_words: 289
- clipped_words: 289
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.3], [P1.5]
- missing_claim_id_refs: (none)

[C1.1] Holding hosting platforms jointly liable for user-prompted AI outputs misapprehends how copyright law, generative technology, and fair use function. The proposition collapses the essential distinction between the tool and the actor, threatening open innovation and digital expression. CON opposes shared liability on three grounds.
[C1.2] First, volition and causation reside with the user. Generative AI is a general-purpose technology capable of vast non-infringing uses. Unlike PRO's flea market analogy [P1.3], where an operator tolerates known illicit goods, an AI platform provides a neutral engine. The user supplies the intent, crafts the prompt, selects among outputs, and decides to publish.
[C1.3] Holding the host liable for a user's infringing prompt is equivalent to holding a digital printing press or photo editing software liable because a customer reproduced copyrighted artwork.
[C1.4] Second, shared liability creates an impossible policing mandate that forces aggressive censorship. Copyright infringement is deeply contextual. Determining substantial similarity requires evaluating fair use, parody, and whether unprotectable style is being confused with protected expression. Automated filters cannot adjudicate these legal standards in real time.
[C1.5] Unlike YouTube's Content ID [P1.5], which matches identical audio files, AI outputs are novel and non-deterministic. If platforms face direct statutory liability for every hosted generation, they must preemptively over-block lawful, transformative speech.
[C1.6] Third, this rule entrenches Big Tech monopolies. Multi-trillion-dollar incumbents can absorb crippling copyright litigation, buy blanket licenses, and construct closed proprietary ecosystems. Startups, open-source communities, and independent platforms cannot. Automatic shared liability will not discipline the market; it will cartelize it, eliminating open-source AI and ensuring only dominant gatekeepers survive.
[C1.7] Existing law already penalizes platforms that intentionally induce infringement or ignore takedown notices. Replacing that balanced standard with blanket shared liability unfairly punishes the toolmaker for user misconduct and dismantles the open internet. Vote CON.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-high
- raw_words: 330
- clipped_words: 330
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.3], [P1.7], [C1.5], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] Everything in CON's case rests on one image: the neutral tool. Break that image and the whole speech collapses.
[P2.2] Photoshop [C1.3] is a genuine tool: the user draws every pixel. A generative model is not. The user types five words; the platform's system — trained on copyrighted works the platform chose to ingest, tuned by the platform's engineers — performs the entire act of reproduction. When the "tool" itself contains and outputs the protected expression, the toolmaker is a co-author of the copy, not a bystander.
[P2.3] CON never explains where the infringing expression comes from if not the platform. It can't come from the prompt. That concession decides causation.
[P2.4] Second, CON attacks a strawman. The proposition says *share* liability, and I framed it as reasonable safeguards [P1.7] — not strict liability for "every hosted generation" [C1.5]. A negligence-style standard with safe harbors for platforms that filter, license, and respond to notices solves the "impossible policing" objection entirely. And the impossibility claim is overstated: platforms already block CSAM, violent content, and — notably — trademarked logos when it suits them.
[P2.5] They can recognize a famous cartoon mouse. Nobody demands perfect adjudication of fair use; we demand the same reasonable care every other industry owes.
[P2.6] Third, the monopoly argument runs backwards. Total immunity is the incumbent subsidy: it lets the largest companies, who trained on the most copyrighted material, keep the gains forever while startups compete against models built on free, unlicensed inputs. Liability paired with safe harbors creates licensing markets — exactly how music streaming let small players enter through collective licenses.
[P2.7] Finally, "existing law already handles this" [C1.7] fails on its own terms. Notice-and-takedown assumes a third party uploaded a fixed file. Here there is no upload — the platform generates a fresh copy on demand, millions of times. You cannot take down what the defendant keeps manufacturing.
[P2.8] The clash is now simple: is the platform the printing press, or the printer? It presses the ink. It shares the liability.

## Turn 4: CON Rebuttal 1

- model: gemini-3.7-flash-high
- raw_words: 280
- clipped_words: 280
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.8], [P2.4], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] PRO attempts to redefine generative models as active co-authors pressing ink onto paper [P2.8]. That metaphor fails. A generative model is not a warehouse of illicit files; it is a statistical architecture of weights learning patterns across billions of concepts. The platform does not decide to evoke a copyrighted character; the user directs the prompt, selects the output, and publishes it.
[C2.2] A search engine retrieves copyrighted text and imagery from a single keyword, yet law does not hold search engines liable for user queries because volition rests entirely with the user.
[C2.3] PRO then attempts to soften shared liability by promising a gentle "negligence and safe harbor" standard [P2.4]. But this concedes CON's point: intermediary protection is essential. Under standard copyright law, infringement is a strict liability regime. If PRO advocates for safe harbors where platforms that act reasonably and respond to notices are shielded, they are defending existing intermediary law—not the proposition's shared liability.
[C2.4] Furthermore, PRO’s comparison to CSAM and trademark filters [P2.5] misunderstands copyright doctrine. CSAM relies on exact cryptographic hashes of known, universally illegal files. Copyright is inherently contextual. It turns on fair use, substantial similarity, parody, and transformative critique—legal determinations no automated filter can make.
[C2.5] Forcing platforms to proactively censor outputs under threat of joint liability inevitably crushes parody and lawful expression.
[C2.6] Finally, PRO's collective licensing fantasy [P2.6] ignores structural reality. Unlike music streaming, there are no statutory blanket-licensing clearinghouses for the entire universe of visual art, code, and writing. Dominant tech incumbents can absorb endless litigation and negotiate private carve-outs; open-source communities, research labs, and startups cannot. Imposing shared liability will not discipline the market—it will outlaw open-source AI and entrench a closed Big Tech oligopoly.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-high
- raw_words: 96
- clipped_words: 96
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [P2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You claim I'm merely "defending existing intermediary law" [C2.3] — but DMCA safe harbors cover content *stored at a user's direction*, not copies the platform's own servers manufacture on demand. Name the existing doctrine that shields a party who itself performs the act of reproduction.
[P3.2] Q2: You never answered [P2.3]: when a model outputs near-verbatim protected expression the user's five-word prompt did not contain, where did that expression come from — and if the anonymous prompter is judgment-proof and the platform is immune, is your position that the rights holder simply recovers from no one?

## Turn 6: CON Pressure Questions

- model: gemini-3.7-flash-high
- raw_words: 82
- clipped_words: 82
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.4], [C2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: You argue for a "negligence-style standard with safe harbors" [P2.4], but copyright infringement is strictly liable once established. If a platform exercises reasonable care yet a user bypasses its filters to generate infringing content, does that platform share liability under your proposition or not?
[C3.2] Q2: Since no statutory blanket-licensing framework exists across all visual art, literature, and code [C2.6], how can independent developers and open-source hosting platforms survive shared liability without the multi-billion-dollar licensing budgets available only to Big Tech incumbents?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [P3.1], [C2.3]
- missing_claim_id_refs: (none)

[P4.1] A1: No — a platform that exercises genuine reasonable care does not share liability when a determined user defeats its filters, and that answer is fully consistent with the proposition. "Should share liability" is a policy question about who bears legal responsibility, and legislatures shape liability regimes with due-care conditions all the time — the DMCA itself grafted safe harbors onto copyright's strict-liability baseline.
[P4.2] But notice what CON cannot say: that any *existing* doctrine covers this. My Q1 [P3.1] went unanswered because there is no answer. DMCA safe harbors shield storage "at the direction of a user"; they say nothing about copies the platform's own servers manufacture on demand. So CON's claim that I'm "defending existing intermediary law" [C2.3] is false — I'm proposing the safe harbor that generative AI currently lacks, conditioned on the safeguards platforms currently skip.
[P4.3] A2: Small developers survive the same way small websites survived the DMCA: through compliance obligations proportional to scale. A startup needs output filters for famous, frequently-copied works and a working notice channel — not a license to every poem ever written. And collective licensing bodies are not fantasies that must preexist liability; ASCAP and BMI arose *because* liability created demand for efficient clearance. Immunity, by contrast, is the true incumbent subsidy: it lets the biggest labs keep the gains from the largest unlicensed training corpora forever, with startups competing against that stolen head start.
[P4.4] Now weigh the round. CON answered neither of my questions. Where does near-verbatim protected expression come from if not the platform? Silence.
[P4.5] If the prompter is anonymous and the platform immune, does the rights holder recover from no one? Silence. Those aren't details — they are the causation and remedy core of this debate. CON's remaining position is a false dilemma: any liability is either "already the law" or apocalypse.
[P4.6] I've shown a third path — shared liability with earned safe harbors — and CON has offered nothing against it but the word "impossible."

## Turn 8: CON Rebuttal 2

- model: gemini-3.7-flash-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P1.1], [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: The doctrine is *volitional conduct*. For decades, copyright law has established that automated systems responding directly to user commands do not commit the volitional act required for direct infringement. Just as a search engine dynamically generating cached previews or an ISP transmitting packets does not "manufacture" the resulting copies, an AI model computing statistical weights upon user initiation is a neutral mechanism, not a volitional infringer.
[C4.2] A2: The latent parameters derive from training, but the infringing expression manifests solely through the user's prompt, selection, and distribution. Copyright has never transferred liability to toolmakers simply because an individual infringer might be anonymous or judgment-proof. The rights holder's remedy lies against the user who commanded the reproduction, backed by existing notice-and-takedown mechanisms to de-index and remove hosted outputs.
[C4.3] These answers expose the fatal contradiction in PRO's case. PRO asserts the platform "manufactures" content [P1.1], yet concedes in A1 [P4.1] that platforms exercising reasonable care should escape liability when users bypass filters. That concession collapses PRO's central claim: if liability turns on user bypass and platform safeguards, the platform is not a joint co-author, but an intermediary.
[C4.4] Imposing shared liability on hosting platforms creates an impossible policing mandate. PRO points to music licensing [P4.3], but music collectives clear fixed, recorded compositions. Generative AI produces non-deterministic outputs across art, code, and prose where infringement requires contextual determinations of substantial similarity and fair use. Automated classifiers cannot adjudicate parody or transformative critique in real time.
[C4.5] The result is not market discipline, but regulatory capture. Open-source communities, researchers, and startups cannot absorb statutory damages or build trillion-dollar licensing moats. Shared liability will simply cartelize AI under dominant Big Tech gatekeepers. Because volition remains with the user, existing remedies suffice, and shared liability destroys open innovation, CON wins the debate.

## Turn 9: PRO Closing

- model: claude-fable-5-high
- raw_words: 202
- clipped_words: 202
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.2], [C4.1]
- missing_claim_id_refs: (none)

[P5.1] The debate resolves on one question: who put the protected expression into the copy? CON finally answered in [C4.2] — "the latent parameters derive from training." That is the concession that decides the round. The platform chose to ingest the copyrighted works, encoded them into its model, and its servers render the copy on demand.
[P5.2] The user's five words carry none of the expression. Volitional-conduct cases [C4.1] shield conduits passing along content that already existed elsewhere; they have never shielded a party whose own system contains and produces the copy. A cache forwards; a model manufactures.
[P5.3] Once that's settled, everything else follows. CON's remedy — sue the prompter — means suing anonymous, judgment-proof users over files that were never uploaded and so can't be "taken down" before the next generation. Under immunity, the rights holder recovers from no one, forever. That's not a copyright system; it's an expropriation.
[P5.4] Against that, I've offered the moderate path CON kept pretending didn't exist: shared liability with earned safe harbors — filter the famous, license at scale, respond to notices — the same bargain that built Content ID and collective licensing. CON's alternative is nothing. Between accountability with off-ramps and immunity with no remedy, vote PRO.

## Turn 10: CON Closing

- model: gemini-3.7-flash-high
- raw_words: 181
- clipped_words: 181
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.2]
- missing_claim_id_refs: (none)

[C5.1] PRO’s entire case hinges on calling generative platforms “manufacturers” rather than tools [P5.2]. But statistical weights do not decide to infringe; volitional conduct resides entirely with the user who crafts the prompt, selects the output, and publishes it to the world.
[C5.2] Treating the host as a joint infringer breaks copyright’s foundational boundary between actor and apparatus. Because infringement turns on nuanced, contextual evaluations of fair use, parody, and transformative critique, automated classifiers cannot adjudicate outputs in real time. Imposing shared liability leaves platforms with only one rational choice: aggressively over-censor lawful human expression to avoid crippling statutory damages.
[C5.3] Worse, this rule guarantees regulatory capture. Multi-trillion-dollar incumbents can absorb litigation, build closed proprietary models, and strike private licensing deals. Independent developers, research labs, and the open-source community cannot. Shared liability will not discipline the market; it will outlaw decentralized innovation, cartelize AI under dominant corporate gatekeepers, and chill public creativity.
[C5.4] Existing law already remedies infringement where it belongs: holding the volitional user accountable and removing infringing outputs upon notice. We must not dismantle open innovation to punish the neutral tool. Vote CON.
