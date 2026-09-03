# Debate prop_0615__muse-spark-1.1-high__muse-spark-1.3-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0615
- proposition: Governments should require large generative-AI providers to document and disclose the copyrighted and personal-data sources used to train their models.
- model_pro: muse-spark-1.1-high
- model_con: muse-spark-1.3-high
- side_swap: False

## Turn 1: PRO Opening

- model: muse-spark-1.1-high
- raw_words: 306
- clipped_words: 306
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Generative AI is the first industry built by ingesting the entire expressive output of humanity without asking. A model that can write like Stephen King or draw like a living illustrator did not learn from thin air; it learned because someone copied those works into a dataset. Current law already gives creators and citizens rights over that copying. Those rights are unenforceable if the copying is secret.
[P1.2] Disclosure is not a new regulation; it is the precondition for existing law to function.
[P1.3] For copyright, secrecy creates perfect infringement. A photographer sees her portfolio replicated in model outputs, but she cannot prove which dataset scraped her site, whether it was opt-out respected, or whether a license market even exists. Without a mandated source ledger, licensing cannot emerge. With it, publishers can negotiate, collecting societies can price, and courts can distinguish fair use from systematic piracy.
[P1.4] The alternative is a permissionless free-for-all where only litigants with millions to subpoena get answers.
[P1.5] For personal data, the stakes are higher. Models have been trained on scraped professional headshots, children's photos posted by parents, leaked medical chats, and location-tagged images that allow re-identification. Data protection law grants a right to know, to object, to delete. That right is fiction if providers never have to say they trained on personal data at all, let alone what categories and from where.
[P1.6] This burden is modest and targeted. Large providers already maintain internal manifests for engineering reasons. The rule does not demand publishing the books or releasing weights — only documenting and disclosing sources: which datasets, which domains, what types of personal data, under what license assumption. We require ingredient lists for food, not the secret recipe.
[P1.7] Society depends on these models to inform, hiring, and education. We cannot audit them for bias, non-consensual imagery, or disinformation sourcing without knowing what they were fed.

## Turn 2: CON Opening

- model: muse-spark-1.3-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Forcing AI labs to publish their training sources promises accountability but delivers the opposite: an unusable phone book that harms the very creators and citizens it claims to help.
[C1.2] Modern frontier models train on trillions of words and billions of images swept from the open web — crawl snapshots, open code repositories, digitized books. No lab can reliably list every copyrighted photo, poem, or blog post inside that flood, because the web does not come labeled with owners. The result will not be the neat ledger proponents imagine. It will be millions of URLs and domain names too vast to audit and too vague to prove anything.
[C1.3] A photographer who sees a style copy cannot tell from “example.com appeared thousands of times” whether her work was taken, whether it mattered, or whether the use was lawful. Transparency theater replaces evidence.
[C1.4] For personal data the mandate is worse than useless; it is dangerous. Privacy protection means minimizing collection and limiting further exposure. This rule demands the opposite: build a detailed inventory of whose headshots, family photos, chats, and location-tagged posts you ingested, then disclose it. That disclosure becomes a treasure map for stalkers, data brokers, and extraction attackers to probe the model for exactly those people.
[C1.5] Confirming that children’s photos from a parenting forum or patients’ posts from a support site are inside invites targeted jailbreaks to regurgitate them. You do not protect victims by advertising their presence in the machine.
[C1.6] Finally the curation, filtering, and mixing of data is the core engineering investment. Mandating its publication strips leaders of trade secrets, hands rivals a free recipe, and tells poisoners exactly which domains to contaminate next. Instead of orderly markets, a public source list invites mass shakedown litigation where inclusion on a list is treated as proof of infringement even when learning patterns is lawful.
[C1.7] Punish infringing outputs and real privacy leaks when they happen. Do not require a public catalogue of the ocean.

## Turn 3: PRO Rebuttal 1

- model: muse-spark-1.1-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] My opponent wins only by rewriting the proposal.
[P2.2] [C1.2] imagines we demand a line-item list of every copyrighted photo on the internet. That is not the rule. The rule is document and disclose sources: which datasets you used, which major domains you scraped, what categories of personal data you included, what license status you assumed. That is an ingredient list, not a genome sequence.
[P2.3] Large labs already maintain this internally to dedupe, filter CSAM, and reproduce training — if they can engineer with it, they can account for it.
[P2.4] Because [C1.3] calls that "theater," ask who benefits from no theater at all. When a photographer's style is cloned, "example.com appeared 10k times" plus a preserved manifest is exactly what lets her ask: did you respect robots.txt? Is my site in your Common Crawl subset? Without it she has nothing.
[P2.5] [C1.4] and [C1.5] turn privacy law upside down. GDPR and other data laws already require Records of Processing — you must know what personal data you hold. We are not asking firms to publish Jenny Smith's baby photo. We ask them to admit: "we trained on public posts from supportforum.com containing health disclosures and children's faces."
[P2.6] That does not create a treasure map; the secret hoard is the treasure map for extraction attackers today. Disclosure lets parents object and regulators test for memorization before leakage.
[P2.7] [C1.6] on trade secrets confuses the recipe with the ingredients. Publishing that you used The Pile, LAION, and licensed Shutterstock does not reveal mixing weights. Poisoners already know LAION; openness allows defenders to clean it.
[P2.8] Punishing only bad outputs [C1.7] is closing the barn after the horse is cloned. Once a model has swallowed private chats, the harm is baked in. Disclosure makes existing rights real; secrecy keeps them fictional.

## Turn 4: CON Rebuttal 1

- model: muse-spark-1.3-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.2], [P2.5], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] The ingredient list sounds modest until you ask what it actually does.
[C2.2] If disclosure stops at ‘we used Common Crawl, LAION, and licensed data containing faces,’ [P2.2] then the photographer learns nothing. A domain appearing thousands of times does not tell her if her photo was scraped, if an opt-out was honored, or if her work influenced anything. Courts cannot price licenses off food labels. That vagueness confirms the theater charge: a billion-item haystack summarized as ‘hay.’
[C2.3] If disclosure goes further, to preserved manifests detailed enough to answer ‘was my site in your subset, did you respect robots.txt,’ then it stops being modest. It becomes a queryable map of exactly which forums, hospital comment pages, and parenting sites were swallowed. Privacy law understands this difference, which is why Records of Processing are kept internally for regulators, not published for the public. [P2.5] Confusing an internal audit log with a public admission — ‘yes, we trained on health disclosures and children’s faces from supportforum.com’ — turns minimization on its head.
[C2.4] Parents cannot meaningfully object after ingestion, but attackers can meaningfully target.
[C2.5] Secrecy is not what enables extraction today; specificity does. A model that may have seen the whole web is hard to probe. A model confirmed to contain a small support forum is easy to jailbreak, again and again, until it regurgitates.
[C2.6] The same holds for competition. The Pile and LAION are already known; [P2.7] what matters, and what disclosure would expose, is which domains were kept, filtered, up-weighted, and under what claimed license. That selection is the product. Publishing it hands rivals the curation and tells poisoners where to dump toxins next, while inviting lawsuits that treat presence on a list as guilt.
[C2.7] Disclosure does not unbake the model. It adds exposure on top of ingestion.

## Turn 5: PRO Pressure Questions

- model: muse-spark-1.1-high
- raw_words: 73
- clipped_words: 73
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.5], [C1.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: You can't have it both ways: is a domain-level disclosure useless theater [C2.2] or a precise treasure map for jailbreaks [C2.5]? If it's too vague to identify any person, how does it help attackers target them?
[P3.2] Q2: If we only punish bad outputs [C1.7], how does anyone exercise a GDPR right to object or delete, or prove their work was scraped, when providers are never required to admit what sources they used?

## Turn 6: CON Pressure Questions

- model: muse-spark-1.3-high
- raw_words: 51
- clipped_words: 51
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: If disclosure is only datasets and major domains, how can a specific photographer prove her work was used or claim payment?
[C3.2] Q2: If you publicly confirm training on health disclosures or children's photos from a named forum, how can victims delete it from baked-in weights, except by inviting targeted extraction?

## Turn 7: PRO Rebuttal 2

- model: muse-spark-1.1-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4]
- cited_claim_ids: [C2.2], [C2.5], [C1.7]
- missing_claim_id_refs: (none)

[P4.1] A1: It doesn't need to prove one photo by itself — it proves the ingestion pathway. If the disclosed manifest shows your portfolio domain was included in Common Crawl subset X on March 2023 with no license flag, and the model then mimics your style, you now have what courts need for discovery and what a collecting society needs to demand a blanket fee. That is how licensing emerged in music. My opponent's alternative is zero evidence, so no one can ever prove anything.
[P4.2] A2: You can't perfectly delete from baked-in weights today, but that is exactly why ex ante disclosure matters. GDPR does not promise magic unlearning; it promises the right to object to future training, demand output filtering, unlearning attempts, and make continued processing unlawful. If providers never have to admit "yes, we used supportforum.com which contains health disclosures and images of minors," victims never know to object and regulators cannot test for memorization. Secrecy keeps the vulnerability baked in forever; disclosure starts the fix cycle.
[P4.3] Both CON objections collapse into the contradiction we pressed. He calls domain-level disclosure useless theater [C2.2] and a precise treasure map for jailbreaks [C2.5]. It cannot be both. A summary that says "includes health data and minor's photos from parenting and support forums" is specific enough to exercise rights and general enough not to name any person — just as food labels list allergens without publishing supplier invoices.
[P4.4] Punish-only-outputs [C1.7] leaves rights fictional. Without a documented source ledger for regulators and a public summary of datasets, domains, categories and license assumptions, you cannot object, you cannot opt out, you cannot price a license. Disclosure does not publish Jenny's photo; it forces the provider to admit it trained on places where Jenny's photo lives.

## Turn 8: CON Rebuttal 2

- model: muse-spark-1.3-high
- raw_words: 297
- clipped_words: 297
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.3], [P4.1], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: No contradiction. A domain summary is too coarse to prove my photo was taken, yet coarse enough to aim attacks. Telling a photographer 'we used portfolio-site.com 10k times' does not show her image was in the subset, respected opt-out, or mattered. Telling an attacker 'we trained on supportforum.com with health posts and children's faces' shrinks the whole web to one vulnerable target to jailbreak until it leaks.
[C4.2] Vague for justice, precise for abuse.
[C4.3] A2: Rights do not require a public catalogue. Copyright claims already proceed from outputs plus discovery, and privacy law already requires internal records for regulators, not publication. A creator who sees mimicry can sue and get the manifest under seal; a regulator can audit memorization. What public naming adds is not deletability — weights cannot unswallow — only confirmation that invites probing while offering no erasure.
[C4.4] That distinction is why publicity loses. PRO's model in [P4.3] wants disclosure general enough to hide Jenny yet specific enough to empower her. In practice it lands in the worst middle: [P4.1] admits it cannot prove one photo, only an 'ingestion pathway' that courts must then price like music.
[C4.5] But music licensing works because plays are counted; a domain mention is not a play count. So you get shakedown leverage without proof.
[C4.6] And [P4.2] concedes unlearning fails, then claims admission 'starts the fix.' It starts extraction, not fixing. Once baked in, naming the forum does not enable filtering for one victim without scanning for her, which recreates the privacy violation. Disclosure adds a second harm on top of ingestion without undoing the first.
[C4.7] Punish real leaks and infringing outputs, keep detailed logs with regulators under seal. That gives creators discovery and citizens enforcement without handing rivals curation, poisoners targets, and stalkers confirmations. Do not publish the map.

## Turn 9: PRO Closing

- model: muse-spark-1.1-high
- raw_words: 186
- clipped_words: 186
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C1.7], [P4.2], [P4.1]
- missing_claim_id_refs: (none)

[P5.1] The debate converged where CON hoped it wouldn't: they now accept documentation must exist, but want logs under seal for regulators only. So secrecy isn't needed for engineering or privacy - it's just about keeping citizens in the dark.
[P5.2] That is why they lose. Rights you can only discover under seal after hiring lawyers are not rights. A photographer cannot sue if she never knows her portfolio domain was harvested. A parent cannot object under GDPR if no provider ever has to admit it trains on "parenting forums containing children's photos."
[P5.3] Punish-only-outputs [C1.7] leaves the harm baked in and invisible, which is exactly why [P4.2] matters.
[P5.4] Disclosure of datasets, major domains, categories of personal data, and license assumption is not publishing Jenny's photo. It is admitting what pantry you cook from. That admission is specific enough to trigger discovery and licensing, as in [P4.1], yet general enough not to name any person - an allergen label, not an invoice.
[P5.5] CON's own model is internal records without public categories. That preserves power, not privacy.
[P5.6] Without a public source ledger, law is fictional. With it, law becomes enforceable.

## Turn 10: CON Closing

- model: muse-spark-1.3-high
- raw_words: 160
- clipped_words: 160
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.1], [P4.2]
- missing_claim_id_refs: (none)

[C5.1] The deciding test is not whether records exist. Both sides want logs. It is whether publishing them helps victims more than attackers.
[C5.2] It does not. PRO concedes the list cannot prove one photo was taken, only an 'ingestion pathway' [P4.1], and concedes baked-in weights cannot be unlearned [P4.2]. So a photographer gets no proof, no price, no payment — only leverage for shakedown suits. A parent gets no deletion — only public confirmation that her forum was swallowed.
[C5.3] What is vague for justice is precise for abuse. Naming 'support forums with health posts and children's faces' shrinks the whole internet to one target to jailbreak until it leaks.
[C5.4] Sealed manifests with regulators plus discovery from outputs already deliver what rights need: audit, objection to future training, lawsuits under seal — without handing rivals curation, poisoners targets, and stalkers confirmations.
[C5.5] Creators deserve remedies, children deserve obscurity. Do not add exposure on top of ingestion. Punish real harm, keep the map sealed.
