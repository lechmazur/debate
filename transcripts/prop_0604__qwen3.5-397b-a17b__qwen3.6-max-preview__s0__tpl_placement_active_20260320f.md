# Debate prop_0604__qwen3.5-397b-a17b__qwen3.6-max-preview__s0__tpl_placement_active_20260320f

- topic_id: prop_0604
- proposition: The European Union should move from “risk-based” AI regulation to mandatory licensing for frontier general-purpose AI models deployed in the EU market.
- model_pro: qwen3.5-397b-a17b
- model_con: qwen3.6-max-preview
- side_swap: False

## Turn 1: PRO Opening

- model: qwen3.5-397b-a17b
- raw_words: 307
- clipped_words: 307
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Frontier AI models are not consumer products; they are dual-use technologies capable of catastrophic biological, cyber, or informational harm. The current risk-based framework treats these systems as mere commodities, requiring compliance checks often after development is complete. This is insufficient. When potential harm is catastrophic, prevention must precede deployment.
[P1.2] Mandatory licensing establishes a clear gate. Before a model exceeding specific compute thresholds enters the EU market, developers must prove safety, robustness, and alignment. This shifts the burden of proof where it belongs: on the creator, not the regulator chasing shadows after release.
[P1.3] Risk-based regulation relies on post-market monitoring. By the time a systemic risk is identified under current rules, the model is already deployed across borders. Licensing stops the release until safety is verified independently. We license pilots and power plants because the cost of failure is too high for society to bear.
[P1.4] Frontier AI poses systemic risks comparable to these high-stakes sectors. Irreversible damage defines this technology. Post-deployment audits cannot contain capabilities once released into the wild where weights can be copied instantly.
[P1.5] Licensing provides enforceable liability that fines cannot match. If a licensed model causes harm, the license can be revoked, and deployment halted immediately. Risk-based frameworks often result in financial penalties that companies simply budget for as operational costs. Licensing threatens the ability to operate entirely within the bloc.
[P1.6] Closing the EU market to unlicensed models forces global compliance from developers seeking access to European users.
[P1.7] We cannot afford to wait for a catastrophe to validate the need for stricter controls. The precautionary principle demands action before harm occurs, not after damages are calculated. Mandatory licensing is the only mechanism robust enough to manage the unique dangers of general-purpose intelligence. It ensures that safety is a prerequisite for market access, not an afterthought negotiated during compliance reviews.
[P1.8] This is the only responsible path forward.

## Turn 2: CON Opening

- model: qwen3.6-max-preview
- raw_words: 276
- clipped_words: 276
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Mandatory licensing sounds like a safety gate, but in practice it operates as a compliance cartel. The proposition assumes that pre-deployment permits will filter out catastrophic risk while preserving innovation. That trade-off is illusory. Licensing frontier models does not stop malicious actors; it simply prices out everyone except the handful of well-capitalized incumbents who can absorb the legal, auditing, and insurance overhead.
[C1.2] The EU would not be gating danger so much as cementing foreign monopolies and suffocating its own AI ecosystem.
[C1.3] The mechanism itself is technically unworkable. PRO wants to trigger licenses at specific compute thresholds, yet capabilities do not scale linearly with training compute, and dual-use risks emerge unpredictably through fine-tuning, prompt engineering, and open-weight derivatives. You cannot safely “certify” a general-purpose model before release any more than you can certify a new programming language or a scientific textbook. By the time a licensing board evaluates a static snapshot, the ecosystem has already moved on, and dangerous capabilities can be distilled into smaller, unlicensed systems.
[C1.4] The gate catches legitimate developers while misuse flows around it.
[C1.5] The existing risk-based framework already addresses this mismatch by imposing ex-ante conformity assessments on high-risk applications, not abstract base models. It scales obligations to concrete harm, allows iterative regulatory sandboxes, and adapts as capabilities evolve. Swapping that for mandatory licensing trades adaptability for bureaucratic theater. It will drive European research offshore, force startups to route through non-EU infrastructure, and hand strategic dominance to firms that treat compliance as a competitive moat.
[C1.6] The EU cannot afford to outsource its technological future to a permitting regime that delivers neither safety nor sovereignty. Proportionate, application-targeted rules manage real harm without freezing the market.

## Turn 3: PRO Rebuttal 1

- model: qwen3.5-397b-a17b
- raw_words: 309
- clipped_words: 309
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.1], [C1.3], [C1.5], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] My opponent frames licensing as a barrier to innovation, but this is a false dichotomy. Innovation without safety is fragility, not progress. CON claims licensing creates a compliance cartel that prices out startups [C1.1]. However, if a frontier model enables an engineered pandemic or critical grid collapse, the EU market disappears entirely.
[P2.2] Licensing protects the market's very existence, ensuring innovation can continue without triggering a catastrophic backlash that bans the technology outright.
[P2.3] CON argues the mechanism is technically unworkable because capabilities do not scale linearly with compute [C1.3]. While imperfect, compute thresholds are the most observable proxy available for potential capability. We license nuclear reactors despite complex physics and unpredictable failure modes. Difficulty of regulation is not an excuse for the absence of control.
[P2.4] Furthermore, CON suggests dangerous capabilities can be distilled into smaller systems. This proves the need for upstream control on the large models that enable such distillation in the first place.
[P2.5] CON prefers application-level rules over base model licensing [C1.5]. This fundamentally misunderstands general-purpose AI. A base model is a factory for risks, not a single tool. Regulating only the application ignores the capability to generate harmful applications instantly.
[P2.6] You cannot audit every downstream use if the core engine remains unchecked. Once weights are released, fine-tuning bypasses application-layer guards effortlessly.
[P2.7] Finally, CON warns of driving research offshore [C1.6]. If EU safety standards are meaningful, developers must comply to access European users. This is not outsourcing sovereignty; it is exercising it through market power. Just as we demand safety standards for imported cars or pharmaceuticals, we must demand them for intelligence systems.
[P2.8] The choice before us is not between growth and safety, but between managed growth and reckless exposure. We cannot gamble the continent's security on the hope that post-market monitoring will catch existential threats before they materialize. Licensing ensures the gate holds before the danger enters.

## Turn 4: CON Rebuttal 1

- model: qwen3.6-max-preview
- raw_words: 285
- clipped_words: 285
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.7], [P2.3], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] PRO’s comparison to cars and pharmaceuticals [P2.7] fails. You can inspect physical shipments at Rotterdam; you cannot customs-check model weights downloaded from foreign servers or accessed via offshore APIs. Licensing erects a tollbooth only compliant developers will use. Malicious actors, open-weight communities, and foreign providers will simply route around it.
[C2.2] The result is not a safer bloc, but a strategically dependent one that outsources its AI infrastructure to jurisdictions with no such gates.
[C2.3] PRO admits compute thresholds are an “imperfect” proxy [P2.3], but flawed metrics breed false security. Algorithmic efficiency and architectural breakthroughs routinely slash the compute needed for dangerous capabilities. Models trained well below any arbitrary threshold can be fine-tuned or distilled to replicate frontier risks. Licensing the “factory” [P2.5] is useless when the blueprints are already global and the machinery can be rebuilt cheaply elsewhere.
[C2.4] The gate catches the compliant while lightweight, specialized derivatives flow underneath it.
[C2.5] Risk-based regulation wins because it targets deployment contexts, not abstract capabilities. You prevent harm by regulating high-stakes applications, not by certifying general-purpose engines. When models touch critical infrastructure, biotech, or finance, ex-ante conformity assessments and strict liability already apply. This approach scales with actual danger, preserves foundational research, and remains enforceable because it focuses on tangible use cases within EU jurisdiction rather than chasing training receipts across borders.
[C2.6] PRO’s regime is simultaneously overbroad and underinclusive. It suffocates legitimate European developers while missing the actual pathways to misuse. Trading adaptability for static permits does not manage growth; it surrenders it. The EU needs rules that catch real harm without handing a compliance moat to foreign incumbents.
[C2.7] Risk-based regulation delivers that. Licensing is security theater that leaves Europe both technologically hollowed out and no safer against genuine threats.

## Turn 5: PRO Pressure Questions

- model: qwen3.5-397b-a17b
- raw_words: 62
- clipped_words: 62
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You admit malicious actors will bypass licensing via open weights [C2.1], but if those weights are released, how does your application-level regulation stop a user from running them locally to generate biological weapons?
[P3.2] Q2: You dismiss compute thresholds as imperfect [C2.3], yet offer no alternative technical trigger; without a clear line, how do you identify dangerous models before they are released?

## Turn 6: CON Pressure Questions

- model: qwen3.6-max-preview
- raw_words: 100
- clipped_words: 100
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P1.4], [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You claim licensing prevents catastrophic harm, yet you concede weights can be copied instantly [P1.4]. If a foreign lab releases open weights globally, how does an EU license stop a malicious actor in Berlin from downloading those unlicensed weights hosted offshore, given you cannot customs-check digital files?
[C3.2] Q2: You argue for upstream control to prevent distillation [P2.4], but once a licensed model is deployed, adversaries can use it to distill dangerous capabilities into smaller, unlicensed models that fall below your compute threshold. How does licensing the "teacher" stop the proliferation of dangerous "students" that your regime no longer tracks?

## Turn 7: PRO Rebuttal 2

- model: qwen3.5-397b-a17b
- raw_words: 316
- clipped_words: 316
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C1.5]
- missing_claim_id_refs: (none)

[P4.1] A1: You cannot stop every individual download, but licensing criminalizes commercial deployment and cloud inference within EU jurisdiction. Catastrophic misuse requires significant compute infrastructure, not just a laptop. By regulating cloud providers and enterprise users, we deny attackers the scale needed for biological or cyber attacks. If a bank or hospital runs an unlicensed model, they face severe penalties.
[P4.2] This kills the legitimate market for unlicensed frontier AI, forcing infrastructure providers to block them.
[P4.3] A2: Distillation requires a capable teacher. By licensing frontier models, we control the only sources powerful enough to teach dangerous skills to smaller students. You cannot distill capabilities that do not exist accessible within the market. Restricting the teacher drastically reduces the pool of dangerous students, whereas risk-based regulation leaves the teacher completely open.
[P4.4] Distillation also degrades capability; frontier risks require frontier models.
[P4.5] CON's argument assumes perfect evasion is possible, so no regulation is worth it. That is defeatism. Licensing raises the cost of misuse significantly. Risk-based regulation waits for the application to appear; licensing stops the capability from entering the ecosystem unchecked.
[P4.6] Even if some leakage occurs, reducing the availability of frontier weights is superior to monitoring applications after the fact. CON offers no upstream barrier, only downstream cleanup. In high-stakes safety, reducing the source is the only viable strategy. We must choose the mechanism that attempts to hold the line at the border of capability, not the one that cleans up the mess afterwards.
[P4.7] CON claims adaptability [C1.5], but you cannot adapt fast enough to a pandemic released overnight. Licensing is the only tool that treats AI like the dual-use technology it is, rather than a standard software product. The stakes demand prevention, not reaction. We cannot gamble on enforcement chasing harms that arrive faster than bureaucracy.
[P4.8] Licensing places the burden of proof on safety before deployment, which is the only logical stance for technologies capable of ending markets entirely.

## Turn 8: CON Rebuttal 2

- model: qwen3.6-max-preview
- raw_words: 301
- clipped_words: 301
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: [P4.1], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: Application-level regulation doesn’t pretend to stop isolated laptop misuse; it targets the infrastructure and deployment contexts where catastrophic scale actually occurs. Bio-weapon synthesis requires specialized lab equipment, supply chains, and iterative testing—chokepoints already governed by existing dual-use export controls, biosafety protocols, and strict liability for high-risk applications. Licensing a chatbot does nothing to secure a centrifuge or DNA synthesizer. Risk-based rules focus enforcement where harm materializes, not where code is compiled.
[C4.2] A2: We don’t need a single technical trigger for base models because danger emerges from use, not parameters. The risk-based framework uses concrete deployment triggers: sector classification, intended function, and impact assessment. If a model operates in critical infrastructure, healthcare, or biotech, it faces ex-ante conformity checks regardless of training compute. This avoids the false precision of compute thresholds while capturing actual threat vectors.
[C4.3] You regulate the hazard, not the horsepower.
[C4.4] PRO’s upstream gate is both technically blind and practically leaky. They claim licensing “denies scale” [P4.1], but cloud providers already face risk-based obligations for high-risk workloads. Adding a blanket model permit simply taxes general research while determined actors route through offshore APIs or distilled weights. PRO concedes distillation degrades capability [P4.4], yet frontier risks routinely migrate to smaller systems through fine-tuning and synthetic data.
[C4.5] Their “teacher” gate closes after the lesson is already global.
[C4.6] The decisive clash is enforceability versus illusion. PRO trades context-specific safeguards for a static regime that catches compliant EU developers while malicious pathways flow around it. Risk-based regulation scales liability to real-world impact, preserves strategic autonomy, and adapts as capabilities shift. Licensing delivers bureaucratic friction without catastrophic prevention.
[C4.7] The EU needs rules that govern tangible harm, not permits that mistake general-purpose code for a controllable commodity. Safety requires targeting the chokepoints where damage actually occurs, not erecting tollbooths that only the lawful will pay.

## Turn 9: PRO Closing

- model: qwen3.5-397b-a17b
- raw_words: 191
- clipped_words: 191
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: [C4.1]
- missing_claim_id_refs: (none)

[P5.1] CON argues we should regulate lab equipment, not code [C4.1]. But frontier AI *is* the equipment. It designs pathogens and writes exploits. Regulating specific uses assumes harms arrive slowly enough to classify.
[P5.2] They will not.
[P5.3] CON argues licensing isn't perfect because weights leak. But perfection is not the standard; survival is. By the time risk-based rules identify harm, the model is everywhere. Licensing is the only mechanism that acknowledges the unique physics of intelligence: once released, it cannot be recalled.
[P5.4] Downstream controls assume we have time to react. We do not.
[P5.5] When the threat is a synthetic pathogen or grid collapse, prevention must precede deployment. Yes, licensing creates friction. But friction is a feature, not a bug, when the alternative is irreversible catastrophe. The cost of compliance is negligible compared to the cost of containment.
[P5.6] They offer a system managing harm after it emerges. We prevent harm from entering the ecosystem. Risk-based regulation is a bet we cannot afford to lose. In a world of dual-use technologies, market access must be earned through proven safety, not assumed until proven dangerous.
[P5.7] Choose the gate that holds, not the net catching falling bodies.

## Turn 10: CON Closing

- model: qwen3.6-max-preview
- raw_words: 178
- clipped_words: 178
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO’s case rests on a single metaphor: a gate that holds. But for general-purpose software, that gate is an illusion. You cannot customs-check weights, recall open models, or stop distillation from turning a licensed “teacher” into unregulated “students.” Licensing does not contain catastrophic risk; it simply taxes compliant European developers while malicious actors route through offshore APIs and leaked derivatives. The permit catches the lawful and misses the dangerous.
[C5.2] Risk-based regulation wins because it abandons this false upstream chokepoint and targets where harm actually materializes. Catastrophic misuse requires infrastructure and physical dual-use vectors—labs, cloud scale, critical systems. Context-targeted rules govern those tangible pathways with ex-ante checks and strict liability, without freezing foundational research or surrendering strategic autonomy to foreign incumbents.
[C5.3] PRO asks you to trade adaptability for a static permit that delivers neither safety nor control. A tollbooth only the compliant will use is not a safeguard; it is strategic surrender. The EU needs rules that remain enforceable in a digital ecosystem. Choose the framework that actually governs harm, not the one that mistakes bureaucratic friction for security.
