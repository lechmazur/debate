# Debate prop_0615__claude-fable-5-high__deepseek-v4-pro-0813-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0615
- proposition: Governments should require large generative-AI providers to document and disclose the copyrighted and personal-data sources used to train their models.
- model_pro: claude-fable-5-high
- model_con: deepseek-v4-pro-0813-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-high
- raw_words: 321
- clipped_words: 321
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every legal right the public already holds against AI companies is currently unenforceable for one simple reason: nobody outside the company knows what went into the model. Authors cannot claim infringement they cannot see. Individuals cannot exercise privacy rights over data they cannot trace. Regulators cannot audit systems whose inputs are secret.
[P1.2] Disclosure requirements do not create new obligations—they make existing law functional again.
[P1.3] Start with copyright. Courts around the world are wrestling with whether training on copyrighted works is fair use or infringement. But that question cannot even be litigated honestly when plaintiffs must guess whether their work was ingested. Today, a novelist who suspects her books trained a model must reverse-engineer it through clever prompting—a lottery, not due process.
[P1.4] Mandated documentation converts a rigged discovery game into an ordinary legal question courts are equipped to answer, whichever way they answer it.
[P1.5] The same holds for personal data. Data-protection regimes already grant people rights to know how their information is processed and to object. Those rights are dead letters if a company can scrape millions of profiles, medical forum posts, and leaked databases, then shrug and say the training set is proprietary. Transparency is the minimum condition for consent frameworks to mean anything.
[P1.6] The burden objection collapses on inspection. These companies already curate, deduplicate, filter, and version their datasets with meticulous internal records—you cannot build a frontier model otherwise. The mandate asks them to disclose documentation that largely exists. Nor does it expose trade secrets: the proposition covers sources, not model weights, architectures, or training techniques.
[P1.7] Knowing a model trained on Common Crawl plus licensed news archives reveals nothing about how it was built well.
[P1.8] Finally, disclosure disciplines the market. It lets licensed-data companies compete on legitimacy rather than lose to whoever scrapes most aggressively. Secrecy rewards the worst actors.
[P1.9] The question is whether powerful firms should be exempt from the transparency every other regulated industry accepts. They should not.

## Turn 2: CON Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Mandatory source disclosure is not a transparency fix; it is a liability machine.
[C1.2] The premise is that rights are unenforceable because outsiders cannot see the inputs. But a list of sources does not tell a court or regulator whether a right was violated. Copyright claims turn on whether protected expression was actually copied and whether the use is lawful—not whether a title appeared in a training crawl. Personal-data claims turn on whether a model makes an identifiable person processable, not whether a forum post was ingested.
[C1.3] A disclosure rule would flood courts and privacy offices with false-positive claims from anyone who can spot their name or work in a source index, even when the legal claim is weak. That is not due process; it is discovery by public registry.
[C1.4] Second, the burden objection does not collapse. Internal data-curation logs for deduplication and filtering are not a due-diligence document that classifies copyright status and personal-data provenance across billions of items. Copyright status is contestable and changes by jurisdiction; personal data is not cleanly labeled in web text. Requiring that classification forces providers either to over-report everything, making the registry useless, or to build a second legal-clearance bureaucracy that only the largest incumbents can afford.
[C1.5] The result is consolidation, not accountability.
[C1.6] Third, public disclosure has its own harms. It exposes suppliers, licensing terms, data partners, and sensitive source collections to competitors and attackers. Worse, forcing providers to publish where personal data came from can amplify privacy harms by confirming which sources contain sensitive populations. And source lists reveal little about weights or architecture, but they are valuable enough to undercut legitimate data markets; that is a real trade secret loss, not a hypothetical.
[C1.7] Accountability can be enforced through targeted discovery, data-protection requests, and regulator subpoenas when there is a concrete allegation. That approach preserves the ability to litigate real claims without converting the AI input supply chain into a speculative claims registry.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-high
- raw_words: 314
- clipped_words: 314
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.2], [C1.3], [C1.4], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] Notice what CON never disputes: that today, no author, no data subject, and no regulator can even begin to enforce existing rights against these systems. Everything CON offers is a reason disclosure is imperfect. Nothing they offer restores enforceability. That asymmetry decides the debate.
[P2.2] Take the "a source list doesn't prove violation" point [C1.2]. Of course it doesn't—no disclosure regime works that way. Financial statements don't prove fraud; ingredient labels don't prove poisoning. Disclosure establishes the threshold fact that lets the merits be litigated at all.
[P2.3] CON concedes copyright turns on what was actually copied—but a plaintiff cannot reach that question without knowing ingestion occurred. CON's standard would gut every transparency requirement in law.
[P2.4] The "flood of false positives" [C1.3] gets the comparison backwards. Weak claims face pleading standards, motions to dismiss, and fee-shifting—courts filter frivolous suits daily. What has no filter is the current regime of universal false negatives, where every meritorious claim dies at the door. Filterable noise beats permanent silence.
[P2.5] The burden argument [C1.4] rebuts a mandate nobody proposed. The proposition requires documenting sources—"Common Crawl snapshot X, this scraped forum, that licensed archive"—not adjudicating the copyright status of billions of items. CON built the hardest imaginable version of the rule and then declared it impossible. And on consolidation: secrecy is the incumbent's moat.
[P2.6] Established players already scraped the open web under cover of darkness; disclosure is what lets licensed-data challengers compete on legitimacy.
[P2.7] Finally, CON's alternative [C1.7] is circular. Targeted discovery and subpoenas require a concrete allegation—which requires knowing your data was used—which is precisely what secrecy prevents. CON's remedy presupposes the information only disclosure provides. And genuinely sensitive source collections can be disclosed to regulators under confidentiality tiers; that's a design detail, not an objection to the mandate.
[P2.8] Strip away the machinery and CON's position is simple: rights on paper, secrecy in practice. That is not accountability. It is amnesty.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.2], [P2.4], [P2.5], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] The supposed asymmetry [P2.1] is a false choice. Enforcement can begin without a source registry: a near-verbatim output, a distinctive reproduction, observable processing of a data subject, or a whistleblower gives a concrete allegation that unlocks targeted discovery. PRO’s demand is not enforceability; it is pre-litigation discovery for everyone. That is what converts constrained legal claims into a public lottery.
[C2.2] The threshold-fact analogy [P2.2] fails. Financial statements reveal actual transactions; ingredient labels reveal substances causally tied to harm. A training-source index reveals only that an item appeared among billions of inputs—possibly licensed, fair use, de minimis, or irrelevant to model weights. It is not the element of a copyright or privacy claim.
[C2.3] False positives are not cheap [P2.4]. Dismissal still requires counsel, motions, and public accusation. Providers would face speculative filings from anyone who finds their name in a registry. And the current regime is not “universal false negatives”: some claims proceed through observed outputs and subpoenas.
[C2.4] The registry adds noise without curing the hard cases.
[C2.5] The burden objection [P2.5] is sharpest. If disclosure is only “Common Crawl snapshot X,” it cannot show a particular author’s work was ingested, so it fails PRO’s enforceability goal. If it reaches item-level detail, providers must classify billions of records, because “copyrighted source” and “personal-data source” are not labels in a crawl log. Dedup records prove nothing about rights.
[C2.6] PRO cannot have useful disclosure and cheap compliance.
[C2.7] Nor is the disclosure inert. Publishing supplier lists and licensing terms reveals where competitors should license or scrape. Shifting to confidential regulator-only disclosure [P2.7] abandons private enforcement. The motion is either harmful or useless, and both versions favor the largest incumbents.
[C2.8] That is the real asymmetry: PRO promises enforceable rights and delivers an expensive registry that proves less than a targeted subpoena.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-high
- raw_words: 81
- clipped_words: 81
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.7]
- missing_claim_id_refs: (none)

[P3.1] Q1: Under your subpoena-first regime [C2.1], how does a person whose scraped medical-forum posts or leaked records never appear verbatim in any output ever form the "concrete allegation" you require—or do you accept that privacy rights against training simply cannot be exercised?
[P3.2] Q2: You attack confidential regulator-tier disclosure for "abandoning private enforcement" [C2.7]—yet your own alternative leaves private parties with nothing until they already possess evidence secrecy denies them. So does private enforceability matter, or only when it counts against disclosure?

## Turn 6: CON Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 77
- clipped_words: 77
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.5], [P2.7]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say a novelist only needs source-level disclosure to know ingestion occurred [P2.3], yet you disclaim item-level classification as a strawman [P2.5]. Without an item-level index, how does she know her book was in “Common Crawl snapshot X”?
[C3.2] Q2: Does a private plaintiff get the public source list needed to sue, or not? If yes, how do you avoid amplifying the personal-data harms you just called a design detail [P2.7]; if no, isn’t private enforceability abandoned?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-high
- raw_words: 324
- clipped_words: 324
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.6], [C2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: She checks the corpus itself. That is the whole point of naming sources at the dataset-and-version level: Common Crawl snapshots are publicly inspectable archives she can search for her URLs today; known book corpora have indexed contents; a provider's proprietary scrape can be disclosed as a manifest of domains and files it already keeps to run the crawl. Identification of the corpus shifts item-level lookup onto an inspectable dataset—the plaintiff, journalists, or collective-licensing bodies do the search. The provider never classifies the copyright status of a single item.
[P4.2] CON's dilemma [C2.6] assumed usefulness requires provider-side legal adjudication of billions of records. It doesn't. It requires naming the haystack precisely enough that others can find their needle. That dissolves the "useful or cheap—pick one" argument entirely.
[P4.3] A2: Yes—plaintiffs get the source list, tiered. Ordinary corpora and licensed archives are public, which is where copyright enforcement lives. Genuinely sensitive collections—leaked databases, scraped medical forums—go to regulators, who notify affected classes and enforce with real subpoena power that finally has a trigger. Note what the "amplification" worry actually amounts to: saying "we trained on breach X" republishes nothing; the leak is already circulating, and the new harm was the ingestion CON wants kept invisible.
[P4.4] Tiering doesn't abandon private enforcement; it routes each claim to the forum that can act on it. CON's regime routes every claim to nowhere.
[P4.5] And that returns us to the question CON must still answer: the person whose scraped medical posts never surface verbatim in any output. Under subpoena-first enforcement [C2.1], she can never form the concrete allegation the subpoena requires. CON's model works only for the lucky plaintiff who catches a verbatim reproduction—a lottery ticket dressed up as due process.
[P4.6] So the final comparison is clean. My regime: inspectable manifests, tiered sensitivity, existing rights made operable. CON's regime: rights that activate only after evidence secrecy is designed to withhold. One of these is accountability.
[P4.7] The other is amnesty with extra steps.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 268
- clipped_words: 268
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P2.5], [P4.3], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: She is not limited to output evidence. A documented breach is itself a concrete allegation: if the medical-forum leak is publicly known and circulating, she can allege that a provider acquired or processed the known breached corpus, and discovery or a regulator can test which provider did so. No verbatim appearance is required. If the leak is wholly unknown, PRO’s source-level disclosure does not help either: a manifest naming “Common Crawl snapshot X” or “proprietary scrape Y” would not tell her whether her posts were in it unless it becomes the item-level index PRO calls a strawman [P2.5].
[C4.2] So the hardest case is not solved by the motion; it is better reached through breach notification, security research, whistleblowing, and regulator investigation.
[C4.3] A2: Private enforceability matters, but it does not override privacy and source-chain costs. Our side is coherent: private plaintiffs sue on observable copying or processing; regulators investigate hidden ingestion. PRO is the one with the tension. They hand private plaintiffs a public source list for ordinary corpora, but for sensitive collections—the very privacy cases your question raises—they route enforcement to regulators [P4.3], the same mechanism they call “nowhere” when we propose it.
[C4.4] And [P4.1] shifts the real search burden onto plaintiffs: hunting through vast crawls is not cheap due process, it is a lottery with a longer ticket.
[C4.5] That is why CON still wins. PRO cannot make source-level disclosure useful without making it expensive or harmful. A targeted, harm-triggered system preserves actual claims through known outputs, breaches, and regulator power without publishing a speculative registry that exposes suppliers and sensitive collections. Real investigation beats guessed liability.

## Turn 9: PRO Closing

- model: claude-fable-5-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.3], [C4.4]
- missing_claim_id_refs: (none)

[P5.1] The debate comes down to one question: what triggers enforcement? Everything else is machinery.
[P5.2] CON's final position [C4.3] claims symmetry—we both route sensitive cases to regulators, so my tier is no better than their subpoena. But the regimes are opposites. Under the mandate, regulators receive the sensitive source lists automatically; investigation starts from knowledge. Under CON's system, the regulator must already suspect ingestion before any subpoena issues—and the whole point of secrecy is that nobody, including the regulator, has grounds to suspect anything.
[P5.3] CON's regulator waits for a tip that the rule itself makes impossible. Mine acts on a filing that arrives by law. That is not symmetry; it is the difference between a fire alarm and hoping someone smells smoke.
[P5.4] And CON's "longer lottery ticket" [C4.4] concedes the point: searching an inspectable manifest is work, but it is possible. Today's search is impossible. A hard road beats a wall.
[P5.5] CON never named a mechanism by which the ordinary rights-holder—no verbatim output, no publicized breach—ever learns her data was used. After five speeches, that silence is the answer. Rights that can never be triggered are not rights. Vote for the regime where enforcement can begin.

## Turn 10: CON Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 152
- clipped_words: 152
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The decisive question is what turns a right into a trigger. PRO’s mandate promises a fire alarm; in fact the alarm only rings if someone already knows where the needle is. Take the ordinary victim—no verbatim output, no publicized breach. A regulator handed “Common Crawl snapshot X” or “proprietary scrape Y” learns nothing new about her medical-forum posts or leaked records.
[C5.2] For that list to trigger her claim, the provider must itemize ingested records—the exact legal classification PRO called a strawman. Without it, she is told to search a haystack. With it, the mandate becomes the expensive, privacy-amplifying registry.
[C5.3] So the motion fails its own test. Targeted subpoenas, known breaches, and observable copying are imperfect, but they attach process to actual harm rather than financing speculative claims. A source registry that cannot find the very victim PRO says is central is not enforceability. It is accountability theater.
[C5.4] The motion should be rejected.
