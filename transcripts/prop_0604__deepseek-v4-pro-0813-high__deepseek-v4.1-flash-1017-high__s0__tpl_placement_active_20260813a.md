# Debate prop_0604__deepseek-v4-pro-0813-high__deepseek-v4.1-flash-1017-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0604
- proposition: The European Union should move from “risk-based” AI regulation to mandatory licensing for frontier general-purpose AI models deployed in the EU market.
- model_pro: deepseek-v4-pro-0813-high
- model_con: deepseek-v4.1-flash-1017-high
- side_swap: False

## Turn 1: PRO Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 287
- clipped_words: 287
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Frontier general-purpose models are infrastructure, not ordinary products. One model can write code, translate, mimic voices, and be embedded in thousands of downstream tools. Once deployed, it is copied, fine-tuned, and impossible to recall. Risk-based regulation usually detects harm in a particular application after the model is already in circulation.
[P1.2] Mandatory pre-deployment licensing is the only chokepoint where the EU can inspect capability, safety, and control before exposure.
[P1.3] The risk-based approach classifies uses, while dangerous properties sit in the model. A general-purpose system can pass a low-risk assessment, then be fine-tuned, jailbroken, or integrated into cyber intrusion, mass deception, or biological misuse. Because downstream users are too diffuse to police individually, licensing the model layer is the highest-leverage intervention.
[P1.4] Licensing should be tiered, not a blanket ban. Frontier models above clear capability or compute thresholds must show red-team results, dangerous-capability evaluations, incident procedures, and post-deployment monitoring before EU market access. Smaller models face no licence. That keeps burdens off ordinary AI development while closing the gap for systems capable of large-scale harm.
[P1.5] The EU already licenses aircraft, medicines, nuclear installations, and financial institutions before they operate. A bank is not allowed to open first and have its fraud controls assessed only after customers lose money. Frontier models belong in that class: their failures are general, fast, and hard to reverse.
[P1.6] Voluntary safety commitments have not fixed this because market pressure rewards shipping early. A mandatory licence makes safety a legal condition of access to the EU market, not a PR pledge. Far from suppressing innovation, it creates a clear compliance path and rewards developers who build safety in from the start. The choice is to license the model before release or regulate the accident after it happens.

## Turn 2: CON Opening

- model: deepseek-v4.1-flash-1017-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] PRO's case rests on a seductive but false premise: that the model is the product and a licence is the chokepoint. Frontier general-purpose models are not medicines with fixed compositions or aircraft with frozen designs. They are mutable platforms: fine-tuned, quantised, wrapped in tools, jailbroken, and redeployed by thousands of actors. A licence issued at release is a snapshot of one version under one set of tests.
[C1.2] It cannot govern what the model becomes after integration. That is not a safety guarantee; it is a false assurance that lets dangerous deployments point to an EU stamp.
[C1.3] Risk-based regulation is not 'wait for the accident'. It can impose ex ante duties proportional to risk: capability evaluations, documentation, incident reporting, monitoring, and restrictions for systemic-risk models and high-risk uses. The difference is that those duties attach to the risk as it actually appears—at the model layer where general capabilities are developed and at the deployment layer where context creates harm—rather than freezing permission at a single moment.
[C1.4] Licensing also fails the practical test. Regulators must define 'frontier', set compute or capability thresholds, and outrun private labs whose models change monthly. Those thresholds are gameable and quickly stale. The predictable result is regulatory capture: large incumbents can absorb licensing costs and use them as a moat, while EU startups and open developers cannot.
[C1.5] The EU then loses both the innovation and the leverage to police the models people use, because deployment migrates to providers outside its jurisdiction.
[C1.6] PRO cites aircraft and banks, but those analogies cut against them. Aircraft certification tracks a controlled design and operation; banks face continuous supervision, not a one-time permission to open. Frontier AI needs the same continuous, risk-scaled oversight—not a licence that certifies yesterday's model and waves through tomorrow's fine-tune.
[C1.7] The decisive comparison is not safety versus innovation. It is adaptive accountability versus static permission. Mandatory licensing looks tough, but it regulates the paperwork at the gate, not the capability in the wild.

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] The snapshot objection gets the causal order backwards. A frontier model is dangerous precisely because its capabilities sit in the weights before downstream fine-tuning, jailbreaking, or integration scatters them. That makes the pre-release chokepoint more valuable, not less. Licensing does not have to be one static stamp.
[P2.2] The proposal conditions market access on red-team results, dangerous-capability evaluations, incident procedures, and post-deployment monitoring. A licence can be renewed, suspended, or withdrawn when new misuse or new capabilities appear. That is a gate with continuing teeth, not a certificate for yesterday’s weights.
[P2.3] The claim that risk-based regulation already supplies the same ex ante duties misses the legal default. Documentation, evaluation, and incident reporting without approval are obligations a developer can satisfy while still shipping. Licensing flips the default: no EU market access until the developer shows the model clears the safety threshold. That difference matters when a model can be copied and fine-tuned within hours.
[P2.4] By the time downstream monitoring detects harm, the weights are already outside the developer’s control.
[P2.5] On thresholds and capture, every serious regime must define scope. Risk-based law also defines systemic-risk models and high-risk uses, with no less contestable boundaries. The answer is revisable capability thresholds, not abandoning the gate. The moat objection cuts the wrong way: a tiered licence mainly touches the largest developers, while smaller and less capable models fall below the threshold.
[P2.6] And EU market access still matters enough that deployment does not simply migrate; regulation of market entry has not made Europe irrelevant in medicines or finance.
[P2.7] Aircraft and banks actually support the licence. Type approval and banking licences coexist with continuing supervision, incident reporting, and revocation. The right design is pre-market permission plus ongoing duties. The proposed contrast between adaptive accountability and static permission is a false choice.
[P2.8] The motion requires permission at the model layer precisely so accountability can operate before mass exposure, rather than after the capability is in the wild.

## Turn 4: CON Rebuttal 1

- model: deepseek-v4.1-flash-1017-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO's reply concedes the decisive point. They say the licence can be renewed, suspended, withdrawn, and paired with monitoring. Then it is no longer a pre-deployment chokepoint; it is ordinary ongoing supervision wearing a licence badge. The only distinctive addition is a permission decision at the gate—before the evidence that matters exists.
[C2.2] And if revocation comes after weights are copied, it cannot recall them. A revoked licence for an open-weight model leaves every downloaded fine-tune in place. That is not “continuing teeth”; it is a stamp on a horse that has already left the barn.
[C2.3] The “flip the default” argument assumes there is a determinate safety threshold a frontier general-purpose model can “clear.” There isn't. General capability is dual-use: the same model that helps a hospital triage patients helps someone write malware. Red-team results and capability evaluations are inputs to judgment, not a pass/fail certificate. Mandatory licensing therefore hands officials an unanswerable question—how safe is safe enough for a model that can do everything?—and invites either arbitrary refusal or capture by the few labs with legal teams.
[C2.4] Risk-based duties can require those evaluations and impose liability without pretending a licence resolves the judgment.
[C2.5] The tiering defense fails too. If only original frontier models are licensed, fine-tunes and jailbreaks escape the gate—the exact gap PRO identified. If every dangerous derivative needs a licence, the EU must license thousands of downstream modifications it cannot inspect, and open development becomes impossible. PRO cannot have a narrow gate and comprehensive coverage.
[C2.6] Aircraft and banks do not rescue this: they have stable designs, defined operations, and continuous supervisory access. Frontier weights are copied and modified beyond the regulator's reach. The rational regime is ex ante evaluation for systemic risk plus continuous duties and liability where use occurs—not a model licence that certifies a snapshot and then cannot follow the capability into the wild.

## Turn 5: PRO Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 64
- clipped_words: 64
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C2.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say [C2.3] there is no determinate safety threshold for a general-purpose model. Then what legal finding under your ex ante risk-based duties would ever justify refusing deployment of a systemic-risk model before harm?
[P3.2] Q2: You say [C2.2] revoking a licence cannot recall copied weights. If that is true, doesn’t that make pre-release clearance more urgent, not a reason to abandon the gate?

## Turn 6: CON Pressure Questions

- model: deepseek-v4.1-flash-1017-high
- raw_words: 68
- clipped_words: 68
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: You claim a licence has “continuing teeth” through renewal and revocation—so once an approved open-weight model is copied, what concrete mechanism recalls or disables those copies when you later revoke it?
[C3.2] Q2: Your tiering licenses only models above a capability threshold; if a below-threshold model is fine-tuned into a dangerous system, does it need a new licence—and if not, how is your gate anything more than symbolic?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 284
- clipped_words: 284
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The honest answer is that no mechanism can physically delete copied weights after an open-weight release. I never claimed one. The continuing teeth are market access, renewal, suspension, and withdrawal, not magical recall. Once revoked, continuing distribution, integration, or serving in the EU becomes unlawful, and downstream deployers face liability.
[P4.2] That is real leverage before the weights multiply. Risk-based oversight has even less: it discovers harm after copies exist with no pre-release permission to revoke or condition. So this objection actually strengthens the case for a pre-deployment gate.
[P4.3] A2: Yes—a below-threshold model that is fine-tuned into a dangerous system has, by definition, crossed the capability threshold or is entering a high-risk deployment; it needs fresh clearance before EU market access. The licence thus reaches substantial modification and dangerous derivatives, not only the original release. If it stays below threshold and cannot be made dangerous, it is outside the frontier problem. That is not symbolic; it flips the default for unassessed high-capability derivatives from ship-first to prove-first.
[P4.4] The opponent’s hardest questions expose the real geometry: after weights are copied or adapted, no regulator can follow every instance. That is why the only serious point of control is pre-release. A licence does not need omniscience; it changes the legal baseline and gives the EU leverage over the most dangerous model releases. And the default is not merely formal: it forces frontier developers to internalize safety costs before customers, competitors, and criminals build on the weights.
[P4.5] The alternative is to supervise the same scattered copies after the fact with no gate, no market-access condition, and no default prohibition. If the post-release enforcement gap is as wide as CON says, that favors PRO’s chokepoint, not adaptive oversight.

## Turn 8: CON Rebuttal 2

- model: deepseek-v4.1-flash-1017-high
- raw_words: 278
- clipped_words: 278
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: A refusal can rest on a concrete legal finding: the developer failed mandatory ex ante duties for a systemic-risk model—documented capability evaluations, red-team results, risk management, incident reporting—or the evidence shows unacceptable risk under statutory factors. Risk-based law can prohibit or suspend deployment on that basis. It does not need a single “safe/unsafe” certificate; it needs proportionate, evidence-based conditions. That is more defensible than asking a regulator to answer “how safe is safe enough?” once and forever.
[C4.2] A2: No. If copied weights cannot be recalled, revoking a licence is also only a legal prohibition on EU distribution—the same lever risk-based supervision already has. Pre-release evaluation is urgent; a permission stamp is not. For open weights, licensing controls one release and then loses the copies; for closed models, continuous supervision and deployment liability do the real work. The recall gap therefore supports strong ex ante duties and targeted release conditions, not a licensing regime that promises control it cannot deliver.
[C4.3] PRO’s answers [P4.1] and [P4.3] actually settle this for CON. [P4.1] concedes there is no recall mechanism, so the licence’s “continuing teeth” collapse into market-access prohibitions and liability—ordinary regulatory tools, not a distinctive safety gate. [P4.3] then says a dangerous fine-tune needs fresh clearance. That is the broad gate: regulators must assess countless derivatives, including open modifications they cannot inspect.
[C4.4] If PRO instead licenses only original frontier releases, the fine-tune gap remains. That dilemma is the debate. Risk-based regulation can require pre-deployment evaluation for systemic models and attach liability where dangerous use occurs, adapting as risk appears. PRO’s licence either misses the derivatives or becomes an unworkable permission bureaucracy.
[C4.5] Regulate the risk, not the paperwork at one gate.

## Turn 9: PRO Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 201
- clipped_words: 201
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.2]
- missing_claim_id_refs: (none)

[P5.1] The debate turns on irreversibility. CON has conceded the decisive point at [C4.2]: once frontier weights are released, no revocation reaches the downloaded copies, fine-tunes, or downstream integrations. That does not undermine licensing—it proves the motion. If post-release enforcement cannot follow the copies that matter, then the only reliable point of control is before first deployment.
[P5.2] Risk-based duties operate on a ship-by-default baseline. Developers may supply evaluations, satisfy paperwork, and still release the model. For a technology whose dangerous derivatives can multiply within hours, ship-by-default is practically no gate at all. Licensing flips that baseline: no EU market access until the model layer clears safety conditions, with renewal, suspension, and fresh clearance for dangerous modifications.
[P5.3] CON calls the safety threshold indeterminate. But precautionary judgment under uncertainty is precisely what medicines, aircraft, and banking approvals require. If a general-purpose model is too open-ended to evaluate once before release, it is far too late to evaluate after it has been copied, fine-tuned, and embedded across thousands of tools.
[P5.4] The decisive comparison is not static permission versus adaptive oversight. It is control before irreversibility versus accountability after it. The only remaining chokepoint is before the weights escape. That is why a mandatory licence wins.

## Turn 10: CON Closing

- model: deepseek-v4.1-flash-1017-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.3], [C4.1], [P4.1]
- missing_claim_id_refs: (none)

[C5.1] PRO’s closing asks you to choose control before irreversibility. Everyone wants that. The question is whether a licence supplies it—and their own answers show it does not.
[C5.2] At [P4.3], a dangerous fine-tune needs fresh clearance. So the licence must follow countless modifications regulators cannot inspect: an unworkable permission bureaucracy. If it instead covers only original releases, the dangerous derivative escapes the gate and the licence is symbolic. That dilemma is not answered by saying the alternative is worse; risk-based law can already require pre-deployment evaluations and refuse or suspend systemic-risk deployment when evidence is inadequate [C4.1].
[C5.3] It imposes the condition without pretending a certificate can outrun the capability.
[C5.4] PRO conceded at [P4.1] that revocation cannot recall copied weights. Their remaining lever is a legal prohibition on EU distribution—exactly what risk-based supervision and liability provide. Licensing adds a gatekeeping decision before the evidence exists, then loses the model after release.
[C5.5] So the decisive point is not safety versus innovation. It is that mandatory licensing cannot govern the thing that makes frontier AI dangerous: adaptation. Regulate risk continuously, including before release where systemic risk warrants it—not a static permission that either misses derivatives or drowns the EU in them.
