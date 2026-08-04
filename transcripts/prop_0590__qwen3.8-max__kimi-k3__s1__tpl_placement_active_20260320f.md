# Debate prop_0590__qwen3.8-max__kimi-k3__s1__tpl_placement_active_20260320f

- topic_id: prop_0590
- proposition: The European Union should make AI “high-risk” rules apply based on where an AI system’s impacts occur, not where the provider is headquartered.
- model_pro: qwen3.8-max
- model_con: kimi-k3
- side_swap: True

## Turn 1: PRO Opening

- model: qwen3.8-max
- raw_words: 307
- clipped_words: 307
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] High-risk AI rules exist to prevent serious harm to people and fundamental rights. If that is their purpose, the trigger should be where the harm is felt, not where the company keeps its registered office.
[P1.2] First, impacts-based application protects the people the EU is responsible for. Imagine a non-EU firm supplies an AI system used by European employers to screen job applicants, by European banks to assess credit, or to manage safety-critical infrastructure. The decisions land on EU residents, shaping jobs, loans, and public services. A headquarters rule would let the same system escape high-risk duties simply because the provider is incorporated abroad.
[P1.3] That creates a protection gap exactly where risk is greatest.
[P1.4] Second, an impacts rule stops regulatory arbitrage and protects fair competition. If obligations turn on headquarters, EU providers face conformity assessments, data governance, logging, and human oversight, while foreign rivals can sell into the same market under weaker duties. The result is not more freedom; it is a race toward the lowest-risk rules and a subsidy for offshore incorporation.
[P1.5] Third, this is administratively realistic. EU law already polices cross-border conduct through effects-based jurisdiction in competition law and data protection. The AI regime can require non-EU providers with substantial, foreseeable EU impacts to appoint a representative, keep documentation, and work with importers and deployers. That is a narrower and clearer burden than trying to classify every AI company on earth by corporate domicile.
[P1.6] CON may warn about overlap or burdens. But the alternative is worse: a rule that lets dangerous systems opt out of high-risk safeguards by changing their address. This is not overreach; it is ordinary territorial jurisdiction, because the risk materializes inside the regulated market. The question is not whether the provider has an EU logo; it is whether the risk has an EU address.
[P1.7] The EU should regulate where the consequences occur.

## Turn 2: CON Opening

- model: kimi-k3
- raw_words: 338
- clipped_words: 338
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The motion sounds like common sense: regulate where the harm lands. But "where impacts occur" is not a legal trigger — it is a fog. And a compliance regime built on fog fails the very people it claims to protect.
[C1.2] First, high-risk duties are ex ante. Conformity assessments, data governance, registration, human oversight — these must be satisfied before a system operates, which means a provider must know in advance whether the regime applies. Headquarters and market targeting are knowable and verifiable. Impacts are not.
[C1.3] AI outputs cross borders by design: a model built in Seoul, hosted in Texas, used by a multinational employer may touch an EU resident next Tuesday. No provider can map where its impacts will "occur"; many would learn they were "high-risk" only after the fact. A trigger you cannot know in advance cannot be complied with — it can only be punished, arbitrarily.
[C1.4] Second, paper jurisdiction is not protection. Effects-based enforcement in EU competition law works because the targeted firms have EU subsidiaries, revenues, and assets to fine. A pure impacts rule asserts authority over providers with no presence and nothing to seize — including, ironically, the offshore shell operators PRO worries about. Those actors escape any trigger.
[C1.5] The firms the EU can genuinely reach are those deliberately placing systems on its market, whom existing law already captures through market-placement and output-use provisions.
[C1.6] Third, impacts-based jurisdiction is a precedent the EU cannot afford. If merely touching an EU resident grounds full EU regulation, then touching a Chinese or American resident grounds theirs. Expect conflicting global regimes, geofencing, and delayed launches — Europeans already see AI tools arrive late or never — plus reciprocal claims on EU exporters abroad.
[C1.7] Finally, the gap PRO describes is largely closed: EU law already reaches foreign providers who place high-risk systems on the EU market and already burdens EU importers and deployers. The motion goes further, sweeping in providers who never aimed at Europe at all. That is overreach without added safety. Regulate the doorway, not the weather.

## Turn 3: PRO Rebuttal 1

- model: qwen3.8-max
- raw_words: 314
- clipped_words: 314
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON calls impacts “a fog,” but their real objection is that the law should protect Europeans only when a foreign provider conveniently chooses Europe. That is backwards. The trigger is not accidental global reach; it is foreseeable, substantial impact inside the EU. A provider selling recruitment AI to European employers, pricing in euros, offering EU-language support, or contracting with EU deployers knows before launch that its system will decide European jobs.
[P2.2] That is not weather; it is a doorway the provider walks through.
[P2.3] CON says existing market-placement rules close the gap. But formal placement can be evaded by routing through intermediaries while knowingly serving EU users. Impacts close that loophole.
[P2.4] Second, ex ante duties are not impossible. The provider controls design, intended purpose, marketing, customer lists, and deployer instructions. If a system is likely to affect EU residents in high-risk settings, the same information that lets CON rely on “market targeting” tells the provider to conduct conformity assessment, appoint a representative, and log failures. Headquarters, by contrast, can be moved overnight and hidden behind subsidiaries.
[P2.5] If knowability matters, a test tied to foreseeable EU effects is more honest than one tied to a registered office.
[P2.6] Third, CON says paper jurisdiction cannot bind firms with no assets. But the motion does not require catching phantom shell companies; it requires attaching obligations to providers who choose EU impacts. If they want EU customers, they must meet EU conditions or lose access. Importers and deployers give enforcement leverage, and market access is itself an asset.
[P2.7] The headquarters rule, meanwhile, gives a clean escape route: incorporate abroad, sell the same harmful system into Europe, and avoid duties.
[P2.8] Finally, reciprocity is not a reason to disarm. Other states may regulate harms to their residents; that is why firms should meet the rules where harm lands. The EU should not narrow its protection because foreign providers prefer a weaker flag.

## Turn 4: CON Rebuttal 1

- model: kimi-k3
- raw_words: 329
- clipped_words: 329
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.7], [P2.6], [P2.8]
- missing_claim_id_refs: (none)

[C2.1] Notice what just happened. Every example PRO offers of a "knowable" impact is actually evidence of market targeting: pricing in euros, EU-language support, contracting with European deployers, choosing EU customers [P2.1]. But targeting is the existing trigger — what market-placement and output-use rules already capture. PRO is not defending "where impacts occur"; they are defending "where providers aim at Europe."
[C2.2] That is a different motion, and it is already law.
[C2.3] Strip away the targeting gloss and the motion as written sweeps in the cases PRO never mentions: the provider with no European intent whose tool touches an EU resident — a global hiring platform a multinational applies to EU candidates. There, impacts are not foreseeable in any operational sense; no conformity assessment can be completed in advance. PRO's "foreseeability" test [P2.1] only works by borrowing targeting back in.
[C2.4] Second, the horror story is false. "Incorporate abroad, sell the same harmful system into Europe, and avoid duties" [P2.7] does not work under existing law: duties already attach to placing high-risk systems on the EU market and to outputs used in the EU, wherever the provider sits. Importers and deployers already carry obligations — PRO cites them as leverage [P2.6]. The arbitrage gap is closed; the motion adds only the unreachable residue — providers with no EU presence, assets, or intent, the very actors PRO shrugs off as not worth catching.
[C2.5] Third, reciprocity. "Other states may regulate harms to their residents" [P2.8] is not reassurance; it is the problem. If impacts ground jurisdiction everywhere, global providers face dozens of conflicting regimes at once, and the rational response is geofencing — Europeans get AI tools late or never. That is not protection; it is self-harm.
[C2.6] The choice is now sharp. Either "impacts" means targeting, and the motion changes nothing — or it means what it says: unknowable ex ante, unenforceable against the true offshore actor, and an invitation to global pile-ups. Both ways, it fails. Keep the doorway; don't legislate the weather.

## Turn 5: PRO Pressure Questions

- model: qwen3.8-max
- raw_words: 50
- clipped_words: 50
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say “targeting” already captures everything. If a foreign provider targets EU users, isn’t the operative trigger foreseeable EU impact rather than headquarters?
[P3.2] Q2: If impacts are “foggy” ex ante, how can your existing “output used in the EU” trigger be clear unless providers can foresee where impacts occur?

## Turn 6: CON Pressure Questions

- model: kimi-k3
- raw_words: 84
- clipped_words: 84
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1], [P2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: You define the trigger as "foreseeable, substantial impact" [P2.1], yet every indicator you offer — euro pricing, EU languages, EU contracts — is market targeting. Name one enforceable provider your test catches whom existing market-placement and output-use rules miss.
[C3.2] Q2: Your enforcement leverage runs entirely through importers, deployers, and market access [P2.6]. For the only providers your motion newly sweeps in — those with no EU customers, intermediaries, or intent — what exactly do you fine, seize, or block when an impact "occurs"?

## Turn 7: PRO Rebuttal 2

- model: qwen3.8-max
- raw_words: 307
- clipped_words: 307
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C3.1], [C3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: To [C3.1], yes. Take a non-EU vendor selling workforce AI to a multinational retailer for use in EU stores. It has no EU headquarters and makes no formal EU sale; access is routed through one central contract. Existing duties may stop at the deployer, but an impacts trigger catches the provider because EU effects are contracted, known, and recurring.
[P4.2] Enforcement is real: EU deployers and importers may not lawfully use or procure the system until the provider complies, and the provider can be barred from EU contracts and market access.
[P4.3] A2: To [C3.2], for accidental touches, nothing. The motion applies to substantial, foreseeable EU impacts, not trivial contact. If a provider has no EU customers, intermediaries, or intended use, there is no high-risk EU impact to regulate. Where impacts are foreseeable, leverage is market access: require a representative, documentation, and conformity assessment as the price of serving EU deployers; if the provider refuses, block its use through deployer duties, procurement exclusions, and injunctions.
[P4.4] These answers expose CON’s dilemma. Their first pressure question treats every knowable impact as “already” targeting, which concedes the decisive premise: what matters is foreseeable EU effect, not corporate address. Targeting is evidence of impact, not the trigger. Their second invents a phantom provider with no EU connection, then complains it cannot be fined.
[P4.5] The motion need not chase ghosts; it must stop providers from choosing EU harm while hiding behind a foreign registered office.
[P4.6] CON’s remaining objection is only that effects are harder to map than a headquarters checkbox. But ex ante compliance uses the same facts providers control: intended purpose, customer contracts, deployment instructions, and likely high-risk use. If CON is right that current law already does this, their case collapses; if wrong, headquarters rules leave the gap PRO identifies. Either way, regulate where risk lands, not where the letterbox sits.

## Turn 8: CON Rebuttal 2

- model: kimi-k3
- raw_words: 323
- clipped_words: 323
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: No. The operative trigger under existing law is neither headquarters nor impact — it is conduct: deliberately placing a system on the EU market. Foreseeable impact is merely evidence of that conduct, which is why all of PRO's examples — euro pricing, EU-language support, contracts covering EU stores — are acts of targeting. A trigger built on a choice the provider knows it made can be obeyed ex ante; a trigger built on consequences can only be punished ex post.
[C4.2] PRO's question itself concedes this: "targets EU users" is the existing trigger doing the work.
[C4.3] A2: Because "output used in the EU" anchors to a verifiable event — a deployer in the EU using the output, usually inside a contract the provider knows about. It is a fact, not a forecast. And it binds those who placed the system on the market — choice again, not chance. "Where impacts occur" has no stopping rule: the EU candidate screened out in New York, the EU data inside a training set, the recommendation shown to a traveler in transit.
[C4.4] Knowing where your customers are is categorically easier than predicting where consequences ripple.
[C4.5] PRO's own rebuttal confirms both answers. Their flagship case [P4.1] is a vendor serving EU stores through "one central contract" — that is market placement, and deployer duties already reach it. And [P4.3] abandons the motion's plain text: "for accidental touches, nothing." But impacts do not check customer lists; an untargeted impact still occurs where it occurs.
[C4.6] So the motion as written either re-enacts existing law — every case PRO actually wants — or asserts authority over providers with no presence, assets, or intent, which PRO disclaims. What remains between is fog: providers who cannot know their status ex ante, reciprocal regimes worldwide, geofencing that keeps AI tools from Europeans.
[C4.7] Protection requires a trigger firms can know and the EU can enforce. Impacts fail both; market placement passes both. Keep the doorway.

## Turn 9: PRO Closing

- model: qwen3.8-max
- raw_words: 184
- clipped_words: 184
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The decisive reason PRO wins is that CON cannot protect Europeans from foreseeable EU harm without relying on the very thing it rejects: impacts. If a foreign vendor supplies hiring or safety AI used in EU stores, its contracts, customers, and deployment instructions make the EU impact knowable. CON calls that targeting, but that only proves impact is the substance; headquarters and formal placement are labels.
[P5.2] If impacts are knowable, CON’s case collapses into the motion. If they are not knowable, CON leaves the central gap: a provider can route a high-risk system through one central contract or intermediary, foreseeably affect Europeans, and hide behind paperwork. Its answer—regulate the doorway—fails when the doorway is rearranged.
[P5.3] Enforcement is not a fantasy. The EU need not chase ghosts; it can condition market access, bind deployers, and exclude noncompliant systems. That makes the provider choose: comply with high-risk duties or stay out. That is the only test that stops incorporation from becoming a shield against safeguards.
[P5.4] Vote on this: when AI imposes serious risk inside Europe, the law should follow the harm, not the provider’s registered address.

## Turn 10: CON Closing

- model: kimi-k3
- raw_words: 191
- clipped_words: 191
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P5.1], [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C5.1] Notice what PRO's closing never does: defend the motion's actual words. "Where impacts occur" appears nowhere in their final case; instead they offer "knowable," "foreseeable," "contracted" impacts [P5.1]. But foreseeability is a rescue, not the trigger they wrote — and every rescuing fact, EU contracts and deployment instructions, is market placement, which existing law already captures. The central-contract scenario [P4.1]?
[C5.2] Deployer-side duty, current rules, no amendment needed.
[C5.3] The whole debate rested on a false binary: impacts or headquarters. The real trigger is neither — it is conduct, deliberately placing a system on the EU market, which already ignores the registered office. Strip that away and the motion as written asserts jurisdiction over accidental touches, which PRO itself disclaims: "for accidental touches, nothing" [P4.3].
[C5.4] But impacts do not check intent before occurring.
[C5.5] So the dilemma stands: read charitably, the motion changes nothing; read literally, it is unknowable ex ante, unenforceable against the true offshore actor, and an invitation for every regime on earth to claim Europeans by impact alone. A trigger firms cannot know cannot protect; a trigger that duplicates existing law need not be passed. Keep the doorway. Reject the weather.
