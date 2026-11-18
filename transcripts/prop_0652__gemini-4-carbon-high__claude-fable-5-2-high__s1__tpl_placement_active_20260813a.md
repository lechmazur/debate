# Debate prop_0652__gemini-4-carbon-high__claude-fable-5-2-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0652
- proposition: Tech platforms that host and distribute user-prompted AI-generated content should share liability when that content infringes existing copyrights.
- model_pro: gemini-4-carbon-high
- model_con: claude-fable-5-2-high
- side_swap: True

## Turn 1: PRO Opening

- model: gemini-4-carbon-high
- raw_words: 310
- clipped_words: 310
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Legacy platform immunity was built for an era when copying required human effort and left a clear trail. User-prompted AI shatters that bargain. Today, a brief prompt can instantly yield a near-exact replica of a working illustrator’s painting, a musician’s hook, or an author’s protected characters, sometimes deliberately and sometimes without the user even realizing a model regurgitated copyrighted work. When a tech platform hosts, distributes, and monetizes that infringing output while claiming blanket immunity, rightsholders are stranded in an accountability vacuum.
[P1.2] Individual prompters are diffuse, anonymous, occasionally unwitting, and largely judgment-proof, while the platform pockets the engagement and ad revenue risk-free.
[P1.3] Existing notice-and-takedown regimes collapse under synthetic scale. Traditional piracy involved static copies of discrete files. Generative AI drops the marginal cost of producing infringing derivatives toward zero, letting users flood feeds with thousands of slightly mutated images, tracks, and videos every hour. Forcing independent creators to police the internet file by file is an unwinnable game of whack-a-mole.
[P1.4] Worse, recommendation algorithms front-load attention: by the time an artist spots an infringing AI clone and submits a takedown request, the platform has already captured the viral traffic and cannibalized the original work’s market.
[P1.5] Sharing liability aligns incentives on both sides: bad-faith prompters do not get a free pass, and platforms cannot turn a blind eye to infringement they profit from distributing. Platforms are not passive bulletin boards; they engineer the upload pipelines, algorithmically amplify reach, and stand as the cheapest cost avoiders in the ecosystem. Pricing infringement risk into platform operations drives scalable solutions, including perceptual similarity screening, AI provenance checks, limits on mass synthetic monetization, and blanket licensing pools that pay creators upfront.
[P1.6] Crucially, liability attaches only when outputs actually infringe existing copyrights, leaving fair use, parody, and non-infringing inspiration untouched. Without shared liability, platforms privatize the profits of AI distribution while socializing the theft onto human creators.

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 347
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9]
- cited_claim_ids: [P1.6], [P1.1], [P1.5]
- missing_claim_id_refs: (none)

[C1.1] Start with what the law already does. A platform that knows about specific infringement and leaves it up, or that induces infringement, is already liable; safe harbors have always been conditional. So the only thing this motion adds is liability where the platform did not know. That is the rule PRO must defend.
[C1.2] It fails for three reasons.
[C1.3] First, infringement cannot be seen in a file. Whether an image is "substantially similar," a fair-use parody, or licensed turns on context that courts take years to resolve and that no upload filter can reach. PRO says liability attaches "only when outputs actually infringe" [P1.6], but the platform must guess before any court rules. A firm facing damages for wrong guesses will delete anything that resembles anything.
[C1.4] The fan artist, the parodist and the illustrator whose own style trips the similarity screen all get removed, with no judge involved. The promise that fair use stays "untouched" holds in the statute and fails at the filter.
[C1.5] Second, the motion targets the party furthest from the copying. PRO's own example is a model that "regurgitated copyrighted work" [P1.1]. That defect belongs to whoever trained and operated the model, and the decision to publish belongs to the user. The host did neither.
[C1.6] If the generator is the cheapest cost avoider, liability should sit with it, not with every forum, portfolio site and video service downstream.
[C1.7] Third, the rule backfires on creators. Hosts cannot reliably tell AI output from human work, so liability tied to "AI-generated" content rewards platforms for not labeling and not looking. Whatever filtering survives costs a fortune, which the largest incumbents can absorb and small competitors cannot. The "blanket licensing pools" PRO offers [P1.5] will be negotiated between giant platforms and giant catalogs.
[C1.8] The independent illustrator ends up with fewer venues, a more aggressive filter and little from the pool.
[C1.9] The better regime is direct liability for those who generate and publish, with knowledge-based liability, faster takedown and repeat-infringer enforcement for hosts. Hold platforms liable for what they know and ignore, not [clipped]

## Turn 3: PRO Rebuttal 1

- model: gemini-4-carbon-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5]
- cited_claim_ids: [C1.9], [C1.1], [P1.3], [P1.4], [C1.6], [C1.7], [C1.3], [C1.4], [C1.8]
- missing_claim_id_refs: (none)

[P2.1] Defending "knowledge-based liability" and "faster takedown" [C1.9] ignores how synthetic distribution actually works. Under safe harbors, claiming a platform "did not know" [C1.1] is not innocence; it is a business model. Because recommendation feeds front-load viral traffic in hours while AI mutates clones in seconds [P1.3], [P1.4], waiting for solo artists to send URL-by-URL notices guarantees platforms pocket the ad revenue before legal "knowledge" arrives. Nor can creators simply sue the AI generator [C1.6].
[P2.2] Countless infringing outputs come from open-weight models run locally or offshore tools beyond reach, and even domestic generators never control whether private outputs get broadcast to millions. Market harm happens at distribution. Shared liability does not absolve generators or users; it stops hosts from laundering unreachable infringement for profit.
[P2.3] Claiming this rule rewards platforms for "not labeling and not looking" [C1.7] gets incentives backward. Liability turns on whether an infringing upload actually is AI-generated, not whether the host labeled it. Upload patterns, forensic artifacts, and missing human source files expose synthetic origin in litigation, so looking away leaves platforms flying blind into damages, compelling them to require provenance credentials upfront.
[P2.4] Nor will platforms "delete anything that resembles anything" [C1.3]. Engagement is their lifeblood. Just as music hosts chose licensing and revenue-sharing over mass deletion, platforms facing shared risk will use targeted guardrails: verifying human creators so illustrators never trip screens on their own work [C1.4], gating unverified synthetic matches before viral amplification, and striking collective licenses that keep remixes online legally.
[P2.5] Invoking the "independent illustrator" [C1.8] to defend safe harbors is deeply ironic. Collective registries pay independent artists just as music collectives pay indie songwriters, while usage-priced screening APIs ensure small forums are not priced out [C1.7]. Compare the real outcomes: CON’s regime condemns working creators to unpaid whack-a-mole while platforms keep every cent; shared liability makes the firms profiting from synthetic scale help bear its cost.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 344
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9], [C2.10]
- cited_claim_ids: [P2.2], [P2.3], [P1.3], [P2.1], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO's rebuttal quietly concedes the three things that sink the motion.
[C2.2] First, look at who is actually at fault. PRO admits the infringing outputs often come from "open-weight models run locally or offshore tools beyond reach" [P2.2]. So the host is liable because it is reachable, not because it did anything wrong. That is deep-pocket insurance, not responsibility.
[C2.3] It is also arbitrary: a human who traces the same painting gets the host safe harbor, while the AI copy does not, though the harm is identical.
[C2.4] Second, look at how the platform would comply. PRO says synthetic origin is exposed "in litigation" through forensic artifacts and "missing human source files" [P2.3]. That means the platform learns the answer years after it had to decide. PRO's remedy is "verifying human creators" and requiring "provenance credentials upfront."
[C2.5] So every illustrator must now prove their humanity to post their own work, and anyone who cannot is "gated." That burden lands on creators, and my over-removal argument stands.
[C2.6] Third, the music analogy cuts against PRO. Audio matching works because it compares exact recordings against a reference catalog. PRO's own complaint is "slightly mutated" derivatives [P1.3]. A filter loose enough to catch mutations will inevitably catch parody, homage and shared style, and PRO never explains how a screen separates those.
[C2.7] The music licensing deals PRO praises also grew up under conditional safe harbors, the very regime PRO calls a "business model" [P2.1]. Knowledge-based rules produced that bargain without making hosts insurers.
[C2.8] On virality, if the problem is speed, the remedy is speed. That means faster takedown duties, repeat-infringer termination, and liability for willful blindness, which the law already treats as knowledge. None of that requires punishing a host for what it could not have known.
[C2.9] Finally, "usage-priced screening APIs" [P2.5] are a per-upload tax on small forums, which still carry the damages whenever the screen misses. Giants can absorb that, and their competitors cannot.
[C2.10] So PRO's world offers identity checks for artists, filters that cannot read context, and a market reserved for incumbents. Ours targets whoever [clipped]

## Turn 5: PRO Pressure Questions

- model: gemini-4-carbon-high
- raw_words: 90
- clipped_words: 90
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.8], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: When an anonymous user posts an infringing clone from a local open-weight model [C2.2] and the platform’s feed monetizes millions of views before the artist discovers it for "faster takedown" [C2.8], does the host keep 100% of that revenue while the creator gets nothing?
[P3.2] Q2: Even after a takedown, when other users or burner accounts upload hundreds of "slightly mutated" AI copies [C2.6] of that same work, must the artist chase every new URL forever, or must the host use the very similarity filters you claim inevitably erase parody?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.3], [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: At the moment of upload, before any court has ruled, how does a host tell an infringing "slightly mutated" AI derivative [P1.3] from a lawful parody, homage, or licensed work? And when it guesses wrong and deletes lawful art, who compensates that creator?
[C3.2] Q2: A human-traced copy and an AI copy of the same painting do identical harm. Why does the host keep its safe harbor for the first and owe damages for the second, when you concede synthetic origin is only exposed "in litigation" [P2.3]?

## Turn 7: PRO Rebuttal 2

- model: gemini-4-carbon-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.6], [C2.8], [P1.3], [C3.2], [C2.5], [P2.3], [C2.2], [C2.7], [C2.9]
- missing_claim_id_refs: (none)

[P4.1] A1: Hosts separate them through layered triage, not hair-trigger deletion. Licensed works clear automatically via registry tokens, while homage and shared style imitate broad aesthetics rather than the specific composition, character design, or melody that perceptual screens match [C2.6]. Uploads carrying anonymous software provenance bypass AI screens outright, and even unverified uploads trigger a hold only when they closely replicate a specific protected work, routing close calls to rapid parody review or keeping them live under blanket remix licenses. And when a host mistakenly removes lawful art, neither regime compensates that creator, including CON’s "faster takedown" [C2.8], where risk-averse hosts already delete parodies on complaint without paying a cent.
[P4.2] Shared liability actually curbs over-removal by letting platforms profit from licensing borderline remixes instead of erasing them.
[P4.3] A2: One human tracer spends hours making a single copy; AI lets prompters generate thousands of mutated clones an hour [P1.3]. Safe harbors were built for human friction, and copyright law must draw new liability lines when automation shatters individual policing. Nor is synthetic origin exposed only in litigation [C3.2]. Cameras and creative apps can attach anonymous tool-provenance metadata at export, requiring zero personal ID checks [C2.5], while synthetic watermarks and bot upload patterns flag AI outputs upfront.
[P4.4] Litigation forensics [P2.3] simply stop hosts from disabling those checks and pleading ignorance.
[P4.5] Both answers expose why safe harbors fail overall. Calling shared liability "deep-pocket insurance" [C2.2] pretends platforms are passive storage lockers. In reality, their feeds turn unreachable AI clones into millions of monetized views before solo artists even spot the theft for "faster takedown" [C2.8]. Safe harbors exist today, yet they have produced no broad AI licensing pools [C2.7] because hosts bank viral ad revenue risk-free while creators chase endless burner re-uploads.
[P4.6] Meanwhile, usage-based APIs and damages scaled to commercial reach protect small forums [C2.9]. Platforms profiting from synthetic scale should share its legal cost.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 391
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8], [C4.9]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: No. A host that profits from infringement it had the ability to control already falls outside the safe harbor, and nothing in my regime prevents revenue earned on a claimed work from being frozen and handed to the rightsholder, as existing monetization-claim systems do. That is restitution once a specific work is identified. The motion asks for something else, which is damages for infringement the host could not have known about.
[C4.2] A2: Neither. Once an artist identifies a work, the host knows about that work. Keeping near-copies of one noticed work down means matching against a reference the rightsholder supplied, and it follows from knowledge. Terminating repeat infringers deals with the burner accounts.
[C4.3] What erases parody is the filter the motion requires, which screens every upload against all of copyrighted culture with no notice and no reference, under threat of damages.
[C4.4] Those answers show that PRO's two best scenarios, the viral revenue and the endless re-uploads, are solved by rules triggered by knowledge. So what does the motion add? It adds liability before anyone has told the host anything, and PRO's defense of that has retreated twice.
[C4.5] First, asked how a host can tell infringement from parody at upload, PRO describes "registry tokens," "rapid parody review" and "blanket remix licenses" [P4.1]. None of that exists at scale, and it assumes a complete registry of every protected work. PRO then concedes that when the screen wrongly deletes lawful art, the creator gets nothing. A takedown notice at least names a claimant, who can be answered by counter-notice.
[C4.6] A liability-driven filter has no accuser to answer.
[C4.7] Second, asked why a human-traced copy keeps the safe harbor while an AI copy does not, PRO answers with volume [P4.3]. But volume concerns repeat conduct, which repeat-infringer and stay-down duties address directly. It does not justify a line based on origin. PRO's method for detecting origin is provenance metadata, and a screenshot strips that.
[C4.8] So every unlabeled upload is treated as suspect, and the human artist carries the burden again.
[C4.9] PRO now also offers [clipped]

## Turn 9: PRO Closing

- model: gemini-4-carbon-high
- raw_words: 199
- clipped_words: 199
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.2], [C4.1], [C4.7], [P1.4], [C4.5], [C4.8], [P4.2], [P2.2]
- missing_claim_id_refs: (none)

[P5.1] The defense of safe harbors rests on six fatal words: "once an artist identifies a work" [C4.2]. Every knowledge-based remedy, whether freezing revenue [C4.1], blocking "near-copies," or terminating burner accounts [C4.2], does nothing until a solo creator personally tracks down each theft across vast algorithmic feeds. Under synthetic scale, that condition breaks copyright: while human copies trickle in slowly [C4.7], effortless AI clones flood feeds instantly, capturing viral traffic [P1.4] and clearing payouts before working artists ever know they exist.
[P5.2] Meanwhile, admitting hosts can match "near-copies" [C4.2] and divert revenue [C4.1] after notice proves scalable guardrails work. Platforms lack broad AI licensing and triage today [C4.5] only because safe harbors make ignorance profitable. Shared liability flips that incentive without gutting expression. Engagement-driven hosts will not purge ordinary unlabeled uploads [C4.8] or erase parodies they can profitably keep live under blanket licenses [P4.2].
[P5.3] Instead, pricing risk into distribution pushes platforms to screen opted-in references, gate unverified viral monetization, and fund collective creator pools.
[P5.4] When AI makes infringement effortless and unreachable [P2.2], someone bears the cost of copies solo creators cannot catch in time. That burden belongs on the platforms profiting from synthetic scale, not the artists whose work was taken.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 219
- clipped_words: 219
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.3]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing asks who should bear the cost of copies "solo creators cannot catch in time." Look at PRO's own final answer: platforms will "screen opted-in references" [P5.3]. That is a rightsholder telling the host which work to protect, and the host matching against it. It is knowledge, supplied once, with no URL-chasing.
[C5.2] Stay-down, frozen revenue and repeat-infringer termination work the same way, and all of them fit inside the regime I defended.
[C5.3] So strip away everything both sides accept and ask what the motion uniquely adds. It adds damages for works nobody identified, judged by a filter that cannot read parody, licence or context, triggered by an "AI-generated" origin that a screenshot erases. PRO never explained how a host makes that call at upload. Its answer was registries and review systems that do not exist, plus an admission that the wrongly deleted artist gets nothing.
[C5.4] That is the decisive point. When a host is punished for what it could not know, it does not become wiser. It becomes more cautious, and the caution lands on the fan artist, the parodist and the small forum, not on the offshore model that made the copy.
[C5.5] Hold platforms to account for what they know and ignore. Making them insurers for what they cannot see only moves the cost onto lawful creators.
