# Debate prop_0169__grok-4.5-high__claude-sonnet-5-high__s1__tpl_placement_active_20260320f

- topic_id: prop_0169
- proposition: Journals should refuse to publish computational research unless authors provide code, data, and environment details sufficient for independent reproduction.
- model_pro: grok-4.5-high
- model_con: claude-sonnet-5-high
- side_swap: True

## Turn 1: PRO Opening

- model: grok-4.5-high
- raw_words: 222
- clipped_words: 222
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Computational research lives or dies by independent checks. Code, data, and the exact environment are not optional extras; they are the experiment itself. A paper claiming a model halves error rates or solves protein folding is incomplete without materials that let another lab rerun it. Journals that publish the claim alone are printing theater, not science.
[P1.2] Confirmation is how knowledge holds. Wet-lab work already requires methods detailed enough for outsiders to redo the protocol. Computation is identical: library versions, seeds, floating-point modes, and hardware routinely flip results. The record is already full of papers whose findings evaporate once the missing artifacts are demanded. “Available on request” and voluntary repositories have failed; large fractions of computational articles still ship without usable code or data.
[P1.3] Only a refusal rule changes the incentive.
[P1.4] Modern packaging removes any serious burden. Containers, notebooks, and repositories make complete release routine. Journals already mandate conflict statements and data-availability claims; requiring the actual artifacts simply enforces the same principle. Proprietary or sensitive data can use controlled-access mechanisms or synthetic substitutes.
[P1.5] The alternative is a literature of unreplicable claims that later collapse, wasting effort and eroding trust.
[P1.6] Journals filter for reliability, not just novelty. Refusing incomplete computational work is the only standard that matches that duty. Anything weaker leaves the field open to error and hype that cannot even be diagnosed.

## Turn 2: CON Opening

- model: claude-sonnet-5-high
- raw_words: 335
- clipped_words: 335
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition sounds obviously virtuous until you ask what a "refusal rule" actually does to real research pipelines. It doesn't just punish bad actors. It filters out entire categories of legitimate, often crucial work, and it does so through a mechanism journals are not equipped to run.
[C1.2] Start with the data problem PRO waves away. Clinical trial data, genomic records tied to identifiable patients, proprietary industry datasets, social-media data restricted by platform terms of service — these are not edge cases, they are a huge share of high-impact computational research. "Synthetic substitutes" and "controlled-access mechanisms" are precisely the voluntary, negotiated middle ground that a hard refusal rule bulldozes, because refusal is binary: comply fully or don't get published. A lab studying suicide risk prediction from real patient records, or a public-health team analyzing restricted census microdata, cannot hand over the raw materials no matter how good their intentions are.
[C1.3] Under this rule, that research doesn't get better — it disappears from peer-reviewed journals and reappears, unreviewed, on preprint servers or industry white papers where no one checks anything at all. That is a worse outcome for reliability, not a better one.
[C1.4] Second, exact reproduction is frequently impossible even for authors acting in perfect good faith. Floating-point behavior differs across chip architectures, cloud providers deprecate the exact instance types a paper used, proprietary compilers change silently. "Sufficient for independent reproduction" is not a bar authors can reliably clear even when honest, which means the rule either becomes unenforceable window-dressing or arbitrarily kills papers for hardware drift no one controls.
[C1.5] Third, journals lack the technical capacity to verify what PRO's own opening treats as self-evident. Unpaid reviewers are not going to spin up containers and audit seeds for every submission. The rule becomes compliance theater — a checkbox for a zip file nobody runs — while doing real damage to researchers who can't check that box for reasons that have nothing to do with rigor.
[C1.6] The reliability goal is right. Refusal is the wrong tool for it.

## Turn 3: PRO Rebuttal 1

- model: grok-4.5-high
- raw_words: 282
- clipped_words: 282
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON concedes the reliability goal yet defends the exact status quo that already fails it. Journals that accept computational claims without the materials needed to check them are not protecting science; they are certifying theater. The right response to unreplicable work is refusal at the gate, not relocation of the same problem.
[P2.2] Their data objection collapses the distinction between controlled access and total secrecy. Secure enclaves, audited data-use agreements, and synthetic surrogates already allow external verification of suicide-risk models or restricted census analyses without dumping raw patient files into public repositories. A refusal rule simply insists that authors demonstrate such pathways actually work for independent parties; it does not ban them. What disappears under the rule is the currently common practice of claiming public scientific findings while permanently withholding every means of confirmation.
[P2.3] Industry or platform-restricted results that cannot meet even that standard belong in white papers, not journal authority.
[P2.4] Hardware drift and floating-point variation do not make the standard unenforceable. “Sufficient for independent reproduction” has never required bit-identical outputs on deprecated cloud instances. It requires pinned libraries, seeds, containers, and scripts that recover the same scientific conclusion under ordinary numerical tolerance. Authors who already publish usable artifacts clear this bar routinely; those who cannot are not victims of physics, they are authors of incomplete experiments.
[P2.5] Reviewer capacity is equally overstated. Journals already demand conflict statements and availability declarations that no unpaid reviewer re-audits line-by-line. The difference is that empty declarations leave nothing for the community to check later. Providing the artifacts turns paper promises into usable materials.
[P2.6] CON’s softer path has already produced a literature full of evaporating claims. Only a refusal rule stops journals from laundering them as certified knowledge.

## Turn 4: CON Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 304
- clipped_words: 304
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO's response to the data problem is to say restricted research "belongs in white papers, not journal authority." Read that sentence again — that is not a rebuttal, it is a confession. I said the refusal rule pushes clinical, genomic, and platform-restricted research out of peer review into unreviewed venues. PRO's answer is: yes, and that's fine.
[C2.2] It is not fine. A white paper has no peer review, no referee scrutiny of methods, no editorial accountability at all. PRO's rule doesn't fix the reliability problem for that research; it removes the one filter that currently exists.
[C2.3] The "secure enclaves and audited data-use agreements" line understates what those require. These arrangements take institutional review boards, months of negotiation, and infrastructure most authors and most third-party verifiers don't have standing access to. Making that the price of publication doesn't discipline bad science — it discriminates against researchers who work with sensitive, high-value data precisely because that data is sensitive and valuable, regardless of how careful their methods are.
[C2.4] On hardware drift, PRO now says the standard only needs "ordinary numerical tolerance," not bit-identical output. Fine — but who decides what tolerance is ordinary, case by case, across every subfield from cryptographic simulation to deep learning? PRO already told us reviewers don't re-audit declarations line by line [P2.5]. So the same reviewers who can't verify a conflict-of-interest statement are now supposed to judge whether a divergent result falls inside acceptable numerical drift.
[C2.5] That is not a coherent enforcement mechanism — it's the checkbox theater I named, just relabeled as tolerance.
[C2.6] PRO wants credit for closing the reliability gap while admitting, in the same speech, that no one will actually check compliance and that entire legitimate fields get exiled from review. That is not a fix. It is the status quo's failures plus a new set of casualties.

## Turn 5: PRO Pressure Questions

- model: grok-4.5-high
- raw_words: 53
- clipped_words: 53
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If peer review without code, data, or environment artifacts cannot verify computational claims, how does keeping those unreplicable papers inside journals improve reliability more than excluding them?
[P3.2] Q2: Since voluntary repositories and “available on request” already fail to produce usable materials, what non-refusal mechanism does CON claim will actually compel independent reproduction?

## Turn 6: CON Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.4], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO conceded restricted-data research should go to "white papers, not journal authority" [P2.3]. Isn't abandoning peer review for entire fields like clinical and genomic research a worse reliability outcome than keeping it under imperfect journal scrutiny?
[C3.2] Q2: PRO now says the bar is "ordinary numerical tolerance," judged case by case [P2.4], while also admitting reviewers don't re-audit declarations line by line [P2.5]. Who exactly decides that tolerance, and how is that not the same checkbox theater PRO's rule was supposed to eliminate?

## Turn 7: PRO Rebuttal 2

- model: grok-4.5-high
- raw_words: 236
- clipped_words: 236
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: No. Peer review without artifacts is not imperfect scrutiny of clinical or genomic claims—it is scrutiny of a story whose results cannot be checked. Journals that stamp unreplicable work as reliable certify theater and erode trust faster than redirecting permanently inaccessible material. Controlled-access enclaves and agreements already keep sensitive studies inside peer review whenever authors can show independent parties recover the conclusions. Only work that forever blocks every verification path leaves the journals.
[P4.2] A2: Editors and field norms set ordinary tolerance exactly as they already set “adequate methods”: whether the supplied container, pins, and seeds recover the paper’s scientific claims under ordinary variation. Reviewers need not re-spin every image any more than they re-run wet-lab protocols; the artifacts exist so the community can later test them. That ends the empty “available on request” checkbox by converting promises into reusable experiments.
[P4.3] Those answers decide the clash. CON’s alternative is more of the voluntary regime that already fails to produce usable materials, plus a plea to keep certifying claims no one can diagnose. Refusal does not abandon fields; it forces every paper that seeks journal authority to demonstrate a workable path—public, controlled, or synthetic—so independent reproduction remains possible. Where no path exists, the result correctly loses the peer-reviewed stamp it never earned.
[P4.4] Journals filter for reliability, not volume of stories. Incomplete computational research fails that filter by design. Only the refusal rule stops the literature from evaporating.

## Turn 8: CON Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 309
- clipped_words: 309
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.1], [P2.3], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: Keeping an unreplicable paper inside journals with a clear, honest limitations note is still better than PRO's rule, because the alternative isn't "excluded paper vanishes cleanly" — it's "excluded paper republishes somewhere with zero editorial oversight." PRO's own [P4.1] concedes this: work that "forever blocks every verification path" simply "leaves the journals." Leaves to where? Not to nonexistence — to white papers, preprints, and industry blogs, exactly as PRO already admitted in [P2.3].
[C4.2] Reliability is not served by moving clinical and genomic research out of the one venue that still has editors, referees, and retraction mechanisms. A flagged, honestly-limited journal paper is more checkable than an unreviewed one PRO exiled to satisfy a purity test.
[C4.3] A2: CON never claimed a single silver-bullet mechanism replaces refusal, because reliability isn't produced by one lever — it's produced by graduated pressure: mandatory data-availability statements with teeth, post-publication audits, replication-focused funding, registered reports, and journal-specific tiered requirements matched to what a field's data actually allows. That mixed regime can tighten over time without the binary cliff-edge PRO defends. PRO's "who decides tolerance" answer in [P4.2] just relocates the same discretion CON flagged — "editors and field norms" is not an enforcement mechanism, it's an admission that judgment calls remain unavoidably human and unaudited, the very theater PRO promised to eliminate.
[C4.4] That's the whole debate in miniature: PRO wants credit for a bright-line rule while every actual answer reintroduces discretion, exceptions, and case-by-case judgment. Once you admit editors decide tolerance, and controlled-access counts as compliance, you no longer have a refusal rule — you have exactly the graduated, negotiated system CON proposes, just relabeled as compulsory. The only place where PRO's rule stays sharp and binary is the data-access cases, and there its own answer is publish nowhere reviewed. That's not a fix for reliability.
[C4.5] That's abandoning the fields where reliability matters most.

## Turn 9: PRO Closing

- model: grok-4.5-high
- raw_words: 178
- clipped_words: 178
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Journals certify that a claim can survive independent inspection. Computational research that withholds the code, data path, and environment needed for that inspection has not earned the seal. A stamp on such a claim is not imperfect scrutiny; it is counterfeit reliability. That single fact decides the debate.
[P5.2] CON’s softer alternative—limitations notes, graduated pressure, voluntary regimes with teeth—has already failed. It leaves declarations no one can convert into checks, and high-impact claims that evaporate when artifacts finally appear. A polite caveat on an unreplicable paper does not improve reliability; it launders a result no outsider can diagnose into the literature of record.
[P5.3] CON treats controlled access and numerical tolerance as collapse into their negotiated system. They are not. Authors either demonstrate a workable path—public, enclave, or synthetic—for independent recovery of the conclusion, or they receive no journal authority. Ordinary judgment about tolerance already exists for every methods standard; the refusal rule still ends claiming certification while permanently blocking every check.
[P5.4] Where no path exists, the stamp was never deserved. Only refusal stops journals from printing theater as science.

## Turn 10: CON Closing

- model: claude-sonnet-5-high
- raw_words: 189
- clipped_words: 189
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: [P2.3], [P5.1], [P4.2]
- missing_claim_id_refs: (none)

[C5.1] The whole debate collapses to one admission PRO never took back: restricted-data research, told to leave journals, goes to "white papers, not journal authority" [P2.3]. That is not a solution to unreliability — it is a transfer of clinical, genomic, and public-health research from the one venue with editors, referees, and retraction mechanisms into venues with none. PRO's closing calls the journal stamp "counterfeit reliability" [P5.1], but counterfeit scrutiny inside a system that can still flag, retract, and correct beats zero scrutiny in a white paper that no one audits at all.
[C5.2] Meanwhile PRO's enforcement keeps dissolving into judgment calls it swore to eliminate: editors deciding "ordinary tolerance" [P4.2], enclaves "counting as compliance." Every attempt to make refusal workable smuggles back the graduated, human, negotiated system CON proposed from the start — except in the one place it stays binary, where sensitive data can't be released, and there it doesn't refine science, it exiles it.
[C5.3] A rule that improves the papers it doesn't apply to while pushing the highest-stakes research into unreviewed obscurity is not a reliability standard. It is worse than the status quo it claims to fix.
