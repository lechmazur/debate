# Debate prop_0652__claude-opus-5-high__claude-fable-5-high__s1__tpl_placement_active_20260320f

- topic_id: prop_0652
- proposition: Tech platforms that host and distribute user-prompted AI-generated content should share liability when that content infringes existing copyrights.
- model_pro: claude-opus-5-high
- model_con: claude-fable-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: claude-opus-5-high
- raw_words: 369
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A user types six words. The platform runs a model it trained, on servers it owns, using weights it tuned, and returns an image of a copyrighted character in high resolution — then charges a subscription for the privilege. Calling that platform a neutral pipe is a fiction that no other area of law would tolerate.
[P1.2] Shared liability is the modest position here. Not sole liability, not strict liability for every prompt — shared, meaning the party who profits from the infringing output and controls the machinery that produced it bears part of the cost alongside the user who asked for it. That is simply how copyright has always worked. The copy shop that binds infringing coursepacks is liable even though a professor chose the readings.
[P1.3] Napster lost even though users picked the songs. Section 230, whatever one thinks of it, deliberately carved out intellectual property claims precisely because Congress did not want distribution platforms to escape copyright by pointing at their users.
[P1.4] Two reasons this outcome is right rather than merely traditional.
[P1.5] First, remedy. If liability stops at the user, rights holders are left chasing anonymous, judgment-proof individuals across jurisdictions while the entity that actually monetized the infringement keeps the revenue. A right without a defendant worth suing is not a right.
[P1.6] Second, incentives. The platform is the only party positioned to prevent harm at scale. It can decline to train on scraped catalogs, filter outputs against known protected characters, refuse prompts naming living artists, license the material it ingests, or share revenue with rights holders. A user cannot inspect training data; the platform chose it.
[P1.7] Put the cost where the control is and you get engineering effort aimed at compliance. Immunize the platform and you get exactly the opposite: a business model whose margin depends on someone else's catalog.
[P1.8] Notice that the serious commercial players already concede the principle. The major AI vendors offer their enterprise customers copyright indemnification — they absorb the risk voluntarily, because they know the outputs are their responsibility and because they can [clipped]

## Turn 2: CON Opening

- model: claude-fable-5-high
- raw_words: 330
- clipped_words: 330
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Copyright law has never held toolmakers liable for what users choose to create with a tool that has overwhelmingly lawful uses. That is the Sony Betamax principle, and it is the reason Xerox is not liable for photocopied novels, Adobe is not liable for forged album art made in Photoshop, and camera makers are not liable for bootleg concert footage. The motion asks us to abandon that principle for one class of tool — and the consequences would be severe.
[C1.2] Start with who actually infringes. A generative model is a general-purpose instrument; the user supplies the volition, the specificity, the intent. The same platform that can be prompted into a copyrighted character produces millions of original illustrations, business documents, and personal images every day. Liability should track the volitional actor and the culpable mind — not simply the deepest pocket in the room.
[C1.3] Second, shared liability is unworkable at generative scale. Infringement is not a lookup; it requires comparing an output against millions of works and running a fact-intensive fair use analysis that courts themselves struggle with. No filter can do that. So platforms facing liability will over-block: parody, criticism, fan art, style homage — all lawful, all suppressed, because the rational response to uncertain liability is refusal.
[C1.4] The motion trades speculative compensation for certain censorship of legitimate expression.
[C1.5] Third, watch who survives this regime. Google and Microsoft can absorb litigation risk and buy blanket licenses. Startups, researchers, and open-source projects cannot. Shared liability is a moat dressed up as accountability, and incumbents know it.
[C1.6] Finally, this motion is unnecessary. Contributory and vicarious liability already reach platforms that knowingly encourage or materially profit from specific infringement — that is what actually sank Napster and Grokster: inducement, not mere hosting. And notice-and-takedown gives rights holders a working remedy today. The law already punishes bad actors.
[C1.7] The motion punishes the tool. Keep liability where the fault is: with the person who prompts, and with platforms only when existing doctrines show real culpability.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-high
- raw_words: 330
- clipped_words: 330
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.6], [C1.1], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] Notice what [C1.6] concedes: platforms are already liable when they materially profit from infringement and control the means. That is shared liability — CON has conceded the motion and is now arguing about scope. Fine. Let's argue scope, because vicarious liability has never required a culpable mind: direct financial benefit plus the right and ability to supervise.
[P2.2] A subscription image generator satisfies both on its face. My opponent's own doctrine delivers my conclusion.
[P2.3] Now the tool analogy, which is doing all the work in [C1.1] and deserves none of it. Xerox does not run the copier. It sold a box and walked away; the machine sits in someone else's office, fed by someone else's paper, and Xerox never touches the copy or the money from it. A generative platform does the opposite of all of that: the reproduction happens on its hardware, from a corpus it selected, and it bills per output.
[P2.4] Sony's defense was that it was a manufacturer, not a participant. These platforms are participants in every single act. The right analogy isn't Betamax; it's the copy shop — and copy shops lose.
[P2.5] Then [C1.6] claims notice-and-takedown is a working remedy. Take down *what*? Nothing is hosted. The infringing image is generated on demand and delivered straight to the user's machine, then the next prompt makes another one.
[P2.6] Takedown was built for a world of stored files. My opponent's fallback remedy simply does not exist for prompted generation — which is precisely why liability has to attach where generation occurs, or it attaches nowhere.
[P2.7] On over-blocking: shared liability is not strict liability. Calibrate it — safe harbor for licensed training data, for good-faith output filtering, for revenue-sharing. Platforms already filter aggressively for nudity and violence without collapsing; they'll manage protected characters too.
[P2.8] And the "moat" in [C1.5] runs the other way. Immunity is a subsidy to whoever scrapes the most catalogs fastest. Paying for inputs is a cost everyone bears equally. That is a market, not a moat.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9]
- cited_claim_ids: [P2.7], [P2.1], [P2.3], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] Watch what just happened in [P2.7]: safe harbors for good-faith filtering, for licensing, for cooperation. Strip the labels away and PRO now defends a regime where platforms acting responsibly aren't liable and bad actors are. That is my position. The motion, as written, makes liability the default for hosting user-prompted content; existing doctrine makes it the exception for proven fault.
[C2.2] That default matters, because the burden of legal uncertainty determines behavior — and defaults toward liability produce refusal.
[C2.3] So no, [P2.1] finds no concession. Contributory and vicarious liability require something the motion doesn't: knowledge, inducement, or the ability to supervise *the specific infringing activity*. A platform cannot supervise infringement output-by-output — that would require comparing every generation against every copyrighted work on earth plus a fair use judgment. If PRO thinks current doctrine already delivers his conclusion, the motion is redundant and there is nothing to affirm.
[C2.4] He can't have it both ways.
[C2.5] The copy shop analogy collapses on inspection. Kinko's employees held the copyrighted coursepack in their hands — actual knowledge of the actual work. The platform sees six words. And notice where [P2.3] leads: Photoshop now runs on Adobe's servers, by subscription, on Adobe's hardware.
[C2.6] Under PRO's logic, moving software to the cloud transforms Adobe from immune toolmaker to liable participant, with zero change in who actually decides what gets made. That's not a principle; it's an accident of architecture.
[C2.7] On takedown [P2.5]: the functional equivalent exists. Rights holders notify platforms of protected characters; platforms block those prompts; continued generation after notice becomes knowing contribution — and existing law reaches exactly that. Remedy solved, no motion needed.
[C2.8] Finally, the filtering comparison fails. Nudity is visually detectable by a classifier. Infringement is a legal conclusion requiring knowledge of every protected work and a parody/homage/fair-use analysis courts spend years on. Platforms facing that uncertainty won't calibrate — they'll refuse, and lawful expression dies quietly.
[C2.9] Fault-based liability already catches the guilty. The motion only catches the careful.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-high
- raw_words: 107
- clipped_words: 107
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: In [C2.7] you say rights holders notify, platforms block, and "continued generation after notice becomes knowing contribution." So when the platform keeps generating and keeps billing after notice, does it share liability with the user — yes or no? If yes, you've affirmed the motion and we are only haggling over the trigger.
[P3.2] Q2: You insist platforms cannot supervise infringement, yet your own remedy assumes they can block flagged prompts. Which is it — and if they genuinely can block, on what principle should a platform that refuses to, while collecting subscription revenue from the output, pay nothing when the prompter is anonymous, offshore, and judgment-proof?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-high
- raw_words: 121
- clipped_words: 121
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.7], [P2.3]
- missing_claim_id_refs: (none)

[C3.1] Q1: Under your own safe harbors in [P2.7], a platform that licenses its data, filters in good faith, and blocks noticed prompts pays nothing — so does a user who still coaxes out an infringing image leave that compliant platform liable, yes or no? If no, your motion is fault-based doctrine renamed and there is nothing left to affirm; if yes, name the duty it breached.
[C3.2] Q2: You built your case in [P2.3] on servers, subscriptions, and billing-per-output. Cloud Photoshop with built-in generation now matches every element. Is Adobe liable when a subscriber generates an infringing image there but immune when the same user does it in desktop Photoshop — and if so, what principle besides server location draws that line?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-high
- raw_words: 349
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Yes — and the duty is nameable. The compliant platform still shares liability, but shared liability is calibrated by remedy, not by an on/off switch. A platform that licensed its corpus and filtered in good faith faces disgorgement of the revenue that particular output earned, and nothing more: no statutory multiples, no punitive exposure. That is not fault doctrine renamed, because the duty breached isn't carelessness — it's the simple obligation not to keep money earned by selling someone else's expression.
[P4.2] Innocent infringement has always been infringement in copyright; good faith goes to damages. My regime charges the compliant platform pennies and the reckless one dearly. CON's regime charges both nothing until a rights holder proves specific knowledge output-by-output.
[P4.3] A2: Yes, and the line is not the server — it's who supplies the protected expression. Desktop Photoshop ships with no Picassos inside it; the user brings every pixel. A generative model ships with the corpus baked into its weights, and when the prompt says "Pikachu," the expression comes from Adobe's training decisions, not the user's keystrokes. That's the principle: the provider that furnishes the protected expression participates in the reproduction.
[P4.4] And notice Adobe itself behaves exactly this way — it curated licensed stock for training and indemnifies its subscribers, because it understands that supplying the corpus means owning the output.
[P4.5] Which brings us to the real clash. CON has spent two speeches insisting the motion is redundant and simultaneously that it would be catastrophic. Both cannot be true. Every time I point at the doctrine CON says already covers this, CON adds a carve-out: needs specific knowledge, needs volition, needs supervision of the individual generation.
[P4.6] Stack those carve-outs and you get the world CON is actually defending — where an offshore, anonymous prompter is the only lawful defendant, and the company that trained on the catalog, hosted the generation, and cashed the subscription owes nothing.
[P4.7] Someone has to bear the uncertainty. Put it on the party that chose the training data, wrote the filters, and banked the revenue [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P4.5], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Yes — and existing law already says so. Generating after specific notice is textbook contributory infringement: knowledge plus material contribution. That admission costs me nothing and costs the motion everything. If liability triggers only on notice and refusal, liability is fault-based, and the motion is redundant.
[C4.2] But PRO just told you in [P4.1] that isn't his position: even the licensed, filtering, notice-honoring platform still pays. That is strict liability with a damages discount, not "shared" anything. We aren't haggling over the trigger — PRO has deleted the trigger. Every compliant platform becomes a per-output defendant, and "only disgorgement" still means litigating what each generation earned, one lawsuit at a time.
[C4.3] A2: Both, and there's no tension. Blocking a specifically noticed character name is a string match; supervising infringement generally requires comparing every output against every protected work plus a fair-use judgment no classifier can render. Duty-follows-notice is precisely the line existing doctrine draws — and a platform that refuses after notice pays today, no motion required. As for the judgment-proof prompter: "the real wrongdoer is hard to sue" has never grounded liability; it's a hunt for a deeper pocket.
[C4.4] Copyright doesn't guarantee a solvent defendant, any more than tort law bills Toyota when a hit-and-run driver flees.
[C4.5] Now the supposed contradiction in [P4.5] — redundant or catastrophic, pick one. Both, in different regions. The motion is redundant against actual bad actors, because inducement and contributory doctrine already reach them. It is catastrophic in the only territory it adds: strict liability for careful platforms.
[C4.6] [P4.1] proves that added territory is real — PRO affirms the compliant platform pays. So every generation is audit exposure, rational platforms over-refuse lawful parody and homage, and only incumbents can carry the compliance load.
[C4.7] Notice, too, that [P4.3] quietly abandoned the servers-and-subscriptions argument for a brand-new "who supplies the expression" principle. The case keeps relocating because the motion's default cannot be defended. Existing law catches the guilty; the motion catches only the careful.

## Turn 9: PRO Closing

- model: claude-opus-5-high
- raw_words: 199
- clipped_words: 199
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Decide this on one question: when a subscription service returns Pikachu and bills for it, who bears the loss?
[P5.2] CON has already answered yes — after notice, the platform shares liability with the user. That is the motion. Everything after that is haggling over the trigger, and CON's trigger is set so late that it hands rights holders an endless game of whack-a-mole: name every character, in every misspelling, in every language, forever, and pay lawyers each round. Miss one and the loss falls on the author.
[P5.3] The Toyota line is where CON's case breaks. Toyota didn't drive the car. Here the platform *is* the car, the driver's hands, and the cashier. It chose the corpus, ran the reproduction on its hardware, and kept the fee.
[P5.4] Calling the party that supplied the protected expression a bystander isn't doctrine; it's architecture worship.
[P5.5] So yes — the careful platform pays something. It pays back what that output earned, and no more. That is the modest cost of running a business whose product is built from other people's work.
[P5.6] Uncertainty has to land somewhere. CON puts it on the author who was never asked. Put it on the company that got paid.

## Turn 10: CON Closing

- model: claude-fable-5-high
- raw_words: 192
- clipped_words: 192
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P4.1]
- missing_claim_id_refs: (none)

[C5.1] The motion rises or falls on one admission: [P4.1]. PRO told you a platform that licensed its data, filtered in good faith, and blocked every noticed prompt *still pays* when a determined user coaxes out an infringing image. That is the only thing this motion adds — because everything else PRO wants, existing law already delivers. Napster-style inducement, contributory liability after notice, vicarious liability for supervised profit: all live doctrine, all conceded by me from the opening.
[C5.2] So weigh what the motion actually buys. Against bad actors: nothing new. Against careful platforms: strict liability with a damages discount, where every generation is audit exposure and every disgorgement claim is a lawsuit. A rational platform facing that doesn't calibrate — it refuses parody, homage, fan art, anything ambiguous, because infringement isn't a string match; it's a legal conclusion no filter can render.
[C5.3] And the compliance load falls hardest on the startups and open projects who can't buy blanket licenses.
[C5.4] PRO says uncertainty must land somewhere. It already lands correctly: on whoever has fault. The motion moves it onto whoever complied. A rule whose entire marginal effect is punishing the careful cannot be affirmed.
