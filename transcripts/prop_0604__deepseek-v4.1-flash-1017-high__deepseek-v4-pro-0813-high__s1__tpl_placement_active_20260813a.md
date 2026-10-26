# Debate prop_0604__deepseek-v4.1-flash-1017-high__deepseek-v4-pro-0813-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0604
- proposition: The European Union should move from “risk-based” AI regulation to mandatory licensing for frontier general-purpose AI models deployed in the EU market.
- model_pro: deepseek-v4.1-flash-1017-high
- model_con: deepseek-v4-pro-0813-high
- side_swap: True

## Turn 1: PRO Opening

- model: deepseek-v4.1-flash-1017-high
- raw_words: 275
- clipped_words: 275
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The central question is not whether risk-based regulation is elegant. It is whether it can stop a frontier model from being deployed before anyone knows what it can do. It cannot. Risk-based regimes ask developers to classify and document risks; frontier general-purpose models are precisely where ex ante classification is least reliable.
[P1.2] Capabilities emerge at scale, are discovered after training, and can be repurposed across thousands of downstream uses. A developer that underestimates its own model gains a competitive advantage. Fines arrive after the model is in the market, after weights leak, after an API is embedded in products across Europe. You cannot recall a capability once it is deployed.
[P1.3] Mandatory licensing flips the burden. Before a frontier general-purpose model is deployed in the EU, the developer must satisfy an independent regulator that it has met baseline conditions: capability evaluations, security against weight theft, incident reporting, access controls, and a credible rollback plan. Licences can be conditional, time-limited, and revoked. That is not a ban on innovation; it is a gate with standards, and it can be fast-tracked for lower-risk releases.
[P1.4] The EU already accepts this logic for medicines, aircraft, and financial market infrastructure because post-market liability is too slow for catastrophic failure.
[P1.5] The opponent will call licensing rigid and captured. But risk-based regulation is also captured—captured by the regulated firm’s own risk assessment. The real choice is who bears the burden of proof: the public, after deployment, or the developer, before it. For frontier models with potential cyber, biological, or persuasion uplift, the public cannot wait for the post-mortem.
[P1.6] Licensing is the only regime that makes “may this be deployed?” precede “what went wrong?”

## Turn 2: CON Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 333
- clipped_words: 333
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] A licence cannot do the one thing the proposition needs it to do: determine before deployment what a frontier general-purpose model can do. Frontier capabilities are discovered at scale, after training, in contexts developers did not anticipate. If the developer’s own risk assessment is unreliable, transferring the decision to a regulator does not solve the epistemic problem; it adds an actor with less model access and less technical information. The result is not certified safety, but certified ignorance.
[C1.2] This matters because general-purpose models are not medicines or aircraft. Those products have stable physical properties, defined indications, and known failure modes. A foundation model has no fixed use, can be fine-tuned, repurposed, plugged into thousands of applications, and prompted in adversarial ways. No pre-market gate can test the open-ended downstream world.
[C1.3] A capability missed at licensing still enters the EU market the moment the same weights are released through an API, fine-tune, or open-weight variant. The gate gives false assurance, not containment.
[C1.4] The practical costs are severe. A mandatory licensing regime for an unstable category called “frontier” invites arbitrary designation, regulatory delay, and compliance only the largest developers can sustain. That shifts frontier work away from EU researchers and startups, or pushes deployment outside the EU while European users still access the model through non-EU providers. The EU loses influence over exactly the systems it wants to govern.
[C1.5] That is a worse safety outcome, not a better one.
[C1.6] The real alternative is stronger risk-based duties, not a different label. Require frontier developers to meet security, capability-evaluation, incident-reporting, and post-deployment monitoring obligations, with severe liability and recall-like remedies when harm emerges. That preserves speed, keeps obligations attached to the developer, and allows regulators to respond as evidence accumulates. Licensing fixes the worst failure of the status quo only if the problem is too little procedure.
[C1.7] It is not: the problem is that no procedure can know the future.
[C1.8] Reject the chokepoint. Demand enforceable obligations and real liability, not a permit that mistakes paperwork for foresight.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4.1-flash-1017-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.1], [C1.7], [C1.2], [C1.3], [C1.4]
- missing_claim_id_refs: (none)

[P2.1] The opponent’s case rests on a false dichotomy: either a licence certifies what a model will do in every downstream use, or it is worthless. No serious licensing regime claims that. A licence is a conditional permission—grounded in capability evaluations, weight-security audits, staged access, incident reporting, and revocation. It does not need to predict every fine-tune; it needs to decide who may put the base capability into circulation, under what controls, and with what power to stop it.
[P2.2] That directly answers [C1.1] and [C1.7]. Yes, regulators know less than developers. That is why licensing compels disclosure and independent testing before deployment; risk-based duties leave the developer’s self-assessment as the operating premise and reach for liability after the fact. “No procedure can know the future” is an argument against the opponent’s own evaluation and monitoring duties too. The question is not omniscience; it is whether the public gets a gate before irreversible diffusion.
[P2.3] [C1.2] and [C1.3] actually strengthen PRO. Because general-purpose models are repurposed, the licence should attach to the release channel and weight custody, not to a fixed use. Conditions can require secure APIs, customer vetting, no open-weight release for the most capable models, and rollback. If a missed capability appears, the licence can be suspended.
[P2.4] The opponent’s alternative can sue after the API is embedded across Europe; it cannot un-release the weights.
[P2.5] [C1.4]’s cost story is a design warning, not a refutation. Statutory thresholds, technical designation, time-limited licences, fast-track tiers, and fees can contain delay and arbitrariness. And if a non-EU provider serves EU users, it is in scope; regulatory arbitrage argues for a credible market gate, not for abandoning one.
[P2.6] The decisive comparison: their regime makes deployment the default and correction the exception. Licensing makes accountable permission the default. For capabilities that may be copied, embedded, and repurposed faster than liability can respond, that reversal is the whole point.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 264
- clipped_words: 264
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] The concession in [P2.1] is fatal. A license that does not certify what a model will do is not a safety finding; it is a permission slip. Every safeguard PRO lists—capability evaluations, weight-security audits, staged access, incident reporting, revocation—can be imposed as a risk-based duty. The only distinct addition of licensing is the discretionary gate, and that gate cannot perceive the relevant capability before deployment.
[C2.2] It delays, then reassures.
[C2.3] [P2.2] does not repair this. Disclosure cannot reveal capabilities nobody has found, and independent testers have less access and less understanding than the developer. If the developer’s self-assessment is unreliable because capabilities emerge later, the regulator’s earlier assessment is more unreliable, not less.
[C2.4] The release-channel move in [P2.3] concedes the point: secure APIs, customer vetting, suspension powers, and even a ban on open-weight release for defined dangerous tiers are substantive restrictions available without a license. Adding a license gives procedure, not protection. [P2.4] overstates revocation. Once weights are copied, leaked or fine-tuned outside the developer’s control, suspending a license does not un-release anything—the same irreversibility PRO uses to attack liability.
[C2.5] [P2.5] dismisses real costs as drafting problems, but the unstable frontier threshold is exactly where designation will be gamed and litigated while capability races ahead. A license also creates no added jurisdiction over non-EU providers; if the EU can enforce a license, it can enforce risk-based duties.
[C2.6] [P2.6]’s default comparison therefore fails. Risk-based law can make high-risk deployment conditional, require pre-release evaluation, and order suspension. What it avoids is the pretence that a regulatory stamp has settled a question no one can settle before deployment.

## Turn 5: PRO Pressure Questions

- model: deepseek-v4.1-flash-1017-high
- raw_words: 55
- clipped_words: 55
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say risk-based law can make deployment “conditional” and order suspension—if permission must precede release and can be revoked, what distinguishes that from licensing except the label?
[P3.2] Q2: When a developer disputes the regulator’s evaluation and withholds disclosure before release, what concrete mechanism in your regime stops deployment rather than merely triggering post-market liability?

## Turn 6: CON Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: You concede [P2.1] the licence cannot certify downstream use, yet it still decides who may put the base model into circulation. What pre-deployment finding justifies that decision, and why isn’t it the same unreliable capability assessment you say risk-based regulation mishandles?
[C3.2] Q2: If weights are released outside the EU, mirrored, or copied after licensing, how does a denied or revoked EU licence stop EU users from obtaining or using the model—what concrete mechanism reaches the circulating weights, not just the formal developer?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4.1-flash-1017-high
- raw_words: 298
- clipped_words: 298
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The finding is narrower than CON implies: not that a model is safe for every downstream use, but that the developer has demonstrated the conditions for accountable circulation—evaluations performed and disclosed, weight custody secured, access controls and rollback in place, incident reporting live. That is not the same unreliable capability assessment, because licensing does not ask the regulator to out-predict the developer. It shifts the burden and attaches enforceable conditions before release. Under risk-based duties, a disputed or incomplete self-assessment defaults to deployment plus later liability.
[P4.2] Under licensing, uncertainty is a reason to withhold permission or impose staged access. An imperfect gate still beats no gate when diffusion is irreversible.
[P4.3] A2: A denied or revoked EU licence cannot magically recall every copied weight—no regime can. But it need not. It governs the EU market: no provider may lawfully offer the model to EU users without a licence; licence conditions require EU-facing API controls, customer vetting, logging, and, for the top tier, no open-weight release. Revocation triggers a duty to cut EU access and makes EU deployers and distributors liable if they continue.
[P4.4] Grey-market copies are an enforcement problem, not a reason to legalize default release. CON’s risk-based duties face the same copied weights, but without a pre-release permission to revoke.
[P4.5] These answers expose CON’s test as impossible perfection. They demand that a licence predict downstream use and reach every copy, then conclude no licence. Their alternative cannot do either; it merely moves the decision later. The real choice is who must act before circulation.
[P4.6] Licensing says the developer must prove controls; risk-based regulation says deploy and correct. For frontier models, that difference is decisive: only licensing can say “not yet” and attach technical controls to release. CON’s conditional duties either become licensing in substance or remain post-hoc.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The distinction is not a label. A risk-based regime can make release unlawful unless defined preconditions—capability evaluation, disclosure, weight security, access controls—are objectively met and court-enforceable. That is a legal rule, not a standing discretionary permit. A licence adds the power to deny release even when those controls exist, because the regulator distrusts the remaining uncertainty.
[C4.2] That does not add safety; it gives the least-informed actor a veto. The difference is whether refusal is tied to a proven breach of duty or to an unevidenced prediction.
[C4.3] A2: The concrete mechanism is an emergency injunction or interim prohibition before release. If a developer withholds mandatory evaluation, a court or regulator can order EU-facing distributors, cloud hosts, and platforms not to carry the model, backed by daily fines. That stops European access before deployment, not after harm; it is not post-market liability. It cannot seize grey-market copies, but neither can a revoked licence, so this is no point against risk-based duties.
[C4.4] These answers expose the flaw in P4.1 and P4.3. P4.1 says the licence does not out-predict the developer, yet it uses the lack of knowledge as a reason to refuse release. So the gate can block a model because the regulator knows too little, not because any danger was demonstrated. P4.3’s API controls, vetting, logging, and no-open-weight rules are substantive risk-based duties codifiable without any licence.
[C4.5] The licence adds only the power to say no before those requirements are assessed. The decisive question remains: on what finding can a less-informed regulator refuse? If the answer is “not knowing enough,” that chokepoint suppresses safe deployments and pushes risky work outside EU oversight. Risk-based law can also act pre-release, but it is triggered by actual non-compliance, not official ignorance.
[C4.6] If PRO calls every such precondition licensing, then the protective substance already exists without mandatory licensing; if licensing means more, it is worse. Either way, the motion fails.

## Turn 9: PRO Closing

- model: deepseek-v4.1-flash-1017-high
- raw_words: 169
- clipped_words: 169
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate comes down to one question: when the evidence is incomplete, which way does the law tilt? CON’s answer is elegant but fatal: release is lawful unless a breach is proven. Their injunction needs a violation to point to. But the frontier failure mode is precisely the case where nobody can yet prove danger and the developer controls the evidence.
[P5.2] In that gap, their regime deploys; licensing withholds.
[P5.3] CON calls that a less-informed veto. It is not a prediction contest. Licensing asks the developer to demonstrate controls—evaluation, custody, access, rollback—and makes failure to demonstrate a reason for “not yet.” That is a burden shift, not omniscience. CON’s objective preconditions are either enforced before release, in which case they are licensing under another name, or enforced after proof, in which case the irreversible step has happened.
[P5.4] For capabilities that can be copied and embedded faster than courts can act, the default is the safety technology. The proposition stands because only licensing makes uncertainty pause circulation rather than authorize it.

## Turn 10: CON Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 177
- clipped_words: 177
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The debate collapses into one question: what justifies the pause. PRO says uncertainty should defer to refusal. But risk-based duties already allow pre-release prohibition for demonstrated non-compliance—no evaluation, insecure weights, no access controls, no release. The concrete safety power PRO asks for exists without licensing.
[C5.2] What mandatory licensing uniquely adds is not more knowledge. It is the power to deny deployment even when every defined condition is met, purely because the regulator still does not know enough. That is not a safety finding; it is an ignorance veto. Uncertainty cuts both ways, and a less-informed gate that blocks on unresolved doubt does not protect Europe.
[C5.3] It drives safe deployment out while grey-market copies and non-EU access still reach the same users.
[C5.4] That is the decisive flaw. The licence’s only distinctive feature is refusal without demonstrated danger. That replaces legal rules with official foreboding. It cannot know the future, and its denial power does not make the future safer.
[C5.5] So the motion fails on its own burden: it promises a gate, but delivers only procedure built on ignorance.
