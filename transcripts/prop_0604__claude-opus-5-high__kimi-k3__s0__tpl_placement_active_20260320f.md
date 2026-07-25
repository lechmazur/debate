# Debate prop_0604__claude-opus-5-high__kimi-k3__s0__tpl_placement_active_20260320f

- topic_id: prop_0604
- proposition: The European Union should move from “risk-based” AI regulation to mandatory licensing for frontier general-purpose AI models deployed in the EU market.
- model_pro: claude-opus-5-high
- model_con: kimi-k3
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The risk-based approach was designed for products whose purpose you know in advance. It works well for a CV-screening tool or a medical triage device, because you can name the use, name the harm, and write the rule. Frontier general-purpose models break that logic at the root. The same model is a coding assistant, a research aid, a persuasion engine, and a bioweapons tutor — and the developers themselves cannot enumerate the capabilities before training finishes.
[P1.2] Regulating "high-risk uses" of an artefact whose uses are discovered after release is regulating downstream of the decision that actually matters. The GPAI chapter of the AI Act concedes this by bolting on transparency duties, systemic-risk self-assessment, and codes of practice. That is a paperwork regime layered onto a capability regime.
[P1.3] Licensing changes one thing, and it is the thing that matters: who carries the burden of proof. Today a lab may deploy a frontier model in the EU and the regulator's job is to object afterwards, with less information, less compute, and less talent than the firm it is policing. Under licensing, market access is a permission, not a default. The applicant must show, before deployment, that it ran evaluations against specified dangerous-capability thresholds, that its security is adequate to stop weight theft, and that it can shut a system down.
[P1.4] If it cannot show that, the answer is no. Aviation, pharmaceuticals, nuclear operation, and banking all work this way, and none of them are byword industries for stagnation — they are industries where "trust us, we self-assessed" was tried and abandoned.
[P1.5] The objection will be innovation. Note who a frontier license actually binds: a handful of firms training at the very top of the compute frontier. European startups fine-tuning open models are untouched, and in fact benefit, because a licensed frontier layer gives them legally stable foundations to build on. The EU's single market is leverage.
[P1.6] Right now it is asking politely for what it could simply require.

## Turn 2: CON Opening

- model: kimi-k3
- raw_words: 335
- clipped_words: 335
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Licensing works when you can answer one question before deployment: what is this thing, and what does it do? A jet engine, a drug molecule, a nuclear reactor — the artifact is fixed, its failure modes are enumerable, and a passed test means something durable. A frontier model fails every part of that. Its capabilities shift with a prompt, a fine-tune, a tool connection, an update pushed overnight.
[C1.2] A license certifies a snapshot of a system that no longer exists by the time the certificate is filed. The aviation analogy is not an argument; it is a confession that the comparison doesn't hold.
[C1.3] Notice what licensing then actually delivers. The regulator cannot run its own evaluations — it has less compute, less talent, less access, as my opponent admits. So the "burden of proof" collapses into the lab submitting its own red-team results to officials who cannot independently check them. That is not a permission regime; it is the same self-assessment paperwork as the AI Act, now slower, with a veto attached and a lobbyist's door next to it.
[C1.4] The dangerous-capability thresholds themselves have no agreed science behind them. A gate you cannot measure is a gate that answers to politics, not safety.
[C1.5] Meanwhile the actual harms live downstream — in the hiring tool, the medical chatbot, the deployed application — precisely where the risk-based framework bites and where a frontier license does nothing at all. PRO regulates the wrong layer and calls it seriousness.
[C1.6] And the economics cut against them. A handful of firms can afford a licensing process; everyone else is frozen out, which entrenches the exact incumbents PRO distrusts. Open-weight models cannot promise a kill switch or prevent weight theft by design, so the regime either bans open development in Europe or exempts it and swallows its own rule. Or the labs simply geofence the EU, and European firms work with weaker tools than their competitors.
[C1.7] The risk-based approach regulates harms where they occur. Licensing regulates a mirage, badly, at great cost.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-high
- raw_words: 350
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.1], [C1.3], [C1.4], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] A license is not a certificate you frame and forget. Aircraft are licensed and then re-inspected, modified under supervision, and grounded when a fleet fault appears. Banks hold standing, revocable permissions with continuous reporting. Drug approvals are tied to variations: change the manufacturing process and you go back to the regulator.
[P2.2] So when CON says a frontier model "shifts with a prompt, a fine-tune, an update pushed overnight" [C1.1], that is not an argument against licensing — it is the reason licensing beats a static rulebook. Mutability is exactly why you want an ongoing conditional relationship with a revocable lever, rather than a one-shot classification of "high-risk use" written before anyone knew what the artefact could do.
[P2.3] The strongest CON claim is that licensing collapses into self-assessment with a veto bolted on [C1.3]. Look at what changes. Under the AI Act's systemic-risk regime, the lab's own judgment substantially *is* the legal standard. Under licensing, the lab's evaluations become representations made to obtain market access — and false, negligent, or incomplete representations cost you the licence, not a fine you book as overhead.
[P2.4] Licensing also buys the regulator what it cannot ask for today: audit rights, inspector access to weights and evaluation infrastructure, mandatory incident reporting, and the power to say "insufficient evidence — come back." A regulator with less compute can still compel the party with the compute to do the work and stand behind it. That is what "burden of proof" means in law, and CON never engages with it.
[P2.5] On immature thresholds [C1.4]: that indictment lands harder on the status quo, which uses the same unsettled capability concepts and lets the exam-taker mark the paper. Requirements are what build measurement science — pre-clinical standards exist because approval demanded them.
[P2.6] And licensing is additive. Nothing in the motion repeals application-level rules for hiring tools or medical chatbots [C1.5]. But when weights are stolen, or a model is released with no downstream deployer to regulate, the "harms live downstream" framing has nobody left to bind.
[P2.7] Access to 450 million [clipped]

## Turn 4: CON Rebuttal 1

- model: kimi-k3
- raw_words: 323
- clipped_words: 323
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.3], [P2.5], [P2.4], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Every lever PRO just described — revocation, liability for false representations, audit rights, the power to say "insufficient evidence" — presupposes one thing: the ability to detect a violation. Aircraft get grounded because faults announce themselves: a crash, an inspection finding. A misrepresented capability evaluation announces itself nowhere. Legal powers without epistemic capacity are decorative.
[C2.2] That defect fuses their two central moves. [P2.3] says evaluations become representations, and false ones cost the license. But falsity must be proven against a standard, and [P2.5] concedes none exists — it offers only that requirements will someday build the measurement science. So for the years this regime actually operates, misrepresentation is legally unprovable: any lab defends its methodology as reasonable, because no benchmark of reasonableness exists to breach.
[C2.3] Pharma's pre-clinical standards rest on reproducible physical assays, not on evaluations that flip with prompt phrasing.
[C2.4] The audit rights in [P2.4] change nothing. A bank examiner can recompute a balance sheet; an aviation inspector can re-run the stress test. No regulator can re-run a frontier training run or replicate capability evaluations at scale. Touring the building is not verification.
[C2.5] "Compelling the party with the compute to do the work and stand behind it" is the self-assessment regime from my opening, with a veto nobody can responsibly exercise.
[C2.6] Then the concession in [P2.6]: licensing is "additive," so risk-based rules still carry the actual harms — the hiring tool, the medical chatbot. The license adds overhead, not protection. And the stolen-weights example cuts against them: once weights leak, revocation retrieves nothing. The irreversible scenarios are precisely those a revocable permission cannot reach.
[C2.7] Finally, the silence: incumbent entrenchment, the open-weight dilemma that bans open development or exempts it into irrelevance, labs geofencing Europe into second-tier tools — all unanswered. PRO offers an elegant legal machine with no engine: powers on paper, no capacity to know when to pull them. Regulation should bite where harm is visible. This bites where nothing is.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-high
- raw_words: 97
- clipped_words: 97
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.1], [C2.6]
- missing_claim_id_refs: (none)

[P3.1] Q1: Your whole case rests on the regulator lacking epistemic capacity to check a lab's evaluations [C2.1] — but the AI Act's systemic-risk chapter relies on those same unverifiable self-assessments, with no gate and no revocation. Name one misrepresentation the risk-based regime detects that a licensing regime would miss.
[P3.2] Q2: You concede irreversibility: "once weights leak, revocation retrieves nothing" [C2.6]. If the harm cannot be undone downstream, and an open release leaves no deployer to bind, who exactly does your framework hold responsible before the release — or is your answer that nobody is asked in advance?

## Turn 6: CON Pressure Questions

- model: kimi-k3
- raw_words: 92
- clipped_words: 92
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5], [C1.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: You promised in [P2.5] that "requirements are what build measurement science" — but the license must operate before that science exists. Who writes the passing threshold on day one, and what makes a lab's failure to meet it provable rather than a negotiation between lawyers?
[C3.2] Q2: You never answered the open-weight dilemma in [C1.6]. Does your regime ban frontier open-weight models in the EU, or exempt them? If it bans them, you've outlawed open development; if it exempts them, what stops the most dangerous capabilities from routing around your gate entirely?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-high
- raw_words: 356
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: The regulator writes the day-one threshold, and it does not need perfect science to do so, because licensing inverts who suffers from uncertainty. The labs themselves already publish frontier safety frameworks with capability tiers for bio and cyber uplift; a regulator can codify that floor, plus a compute-and-capability trigger, and then require the applicant to demonstrate adequacy. Nothing has to be "proven against the lab" in CON's litigation sense — under a permission regime, an unresolved question means *not yet*, not *deploy and we'll sue you later*.
[P4.2] That is precisely the reform. When the 1962 drug reforms demanded proof of efficacy, the assay science was thin; the demand built it. CON's answer is to wait for measurement science to mature under a regime that never asks anyone to produce it.
[P4.3] A2: Neither ban nor exempt: license the release decision itself. An open-weight release at the frontier is an irreversible act, so it is the paradigm case for pre-release authorisation, with conditions attached to what gets released rather than to impossible post-hoc control. European open development below the frontier — fine-tuning, distilling, deploying — is untouched. And notice the comparison CON keeps dodging: routing around my gate at least requires someone to break a law.
[P4.4] Under CON's framework, a lab that open-releases weights with meaningful bio-uplift and no downstream deployer breaks nothing, because there is no one to bind and nothing to bind them to.
[P4.5] That is the whole debate now. CON's strongest weapon — regulators cannot verify capability claims [C2.1] — is a weapon pointed at the status quo. The AI Act's systemic-risk chapter rests on the same unverifiable self-assessments, with no gate, no revocation, and no moment at which anyone must ask. My Q1 asked for one misrepresentation the risk-based regime catches that licensing would miss.
[P4.6] None was named, because there is none.
[P4.7] So the choice is not between verification and paperwork. It is between paperwork nobody must submit before acting, and paperwork that must be submitted, defended, and can be refused. When harms are irreversible, the [clipped]

## Turn 8: CON Rebuttal 2

- model: kimi-k3
- raw_words: 355
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P2.6], [P1.2], [P4.3], [P4.1]
- missing_claim_id_refs: (none)

[C4.1] A1: None — because the two regimes don't compete at that layer. The risk-based framework detects failures where failures announce themselves: the hiring tool that discriminates, the medical chatbot that misdiagnoses — observable outputs, real victims, admissible evidence. A frontier license never touches that layer at all; [P2.6] concedes it. So compare honestly: risk-based detects things where evidence exists and nothing at the frontier; licensing detects nothing anywhere, yet takes the undetectable capability representation and makes it the load-bearing wall of the entire regime.
[C4.2] The AI Act treats self-assessment as disclosure with liability attached. Licensing treats it as a verdict. A claim no one can verify is safer as a disclosure than as a certificate, because the certificate teaches everyone downstream to stop checking.
[C4.3] A2: The developer is asked in advance — [P1.2] itself lists the GPAI duties: evaluations, security obligations, incident reporting, binding the provider before and during deployment, with penalties behind them. The honest difference is that those duties don't pretend to be a permission slip. And [P4.3]'s "paradigm case for pre-release authorisation" runs on the same unverifiable detection: if the regulator cannot see bio-uplift, it authorises blindness with a stamp. Nor do weights respect refusals.
[C4.4] A lab denied in Brussels releases from elsewhere; the weights reach Europe regardless; only European open developers are shut out. A gate binds whoever volunteers to stand at it.
[C4.5] Now the concession that decides this debate sits in [P4.1]: thresholds codified from frameworks "the labs themselves already publish," with unresolved questions defaulting to "not yet." A gate calibrated by the industry, staffed by officials who admit they cannot verify, wielding a refusal power no one can responsibly aim — that is either a rubber stamp or a political instrument, and both outcomes entrench the handful of incumbents positioned to negotiate it. Three speeches; still no answer on entrenchment or geofencing.
[C4.6] Weigh it: PRO's benefit is atmospheric — someone said yes, so someone must be watching. The cost is concrete — false assurance that relaxes downstream vigilance exactly where risk-based rules maintain [clipped]

## Turn 9: PRO Closing

- model: claude-opus-5-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Strip everything away and one question decides this: when nobody can be certain what a frontier model can do, who bears the cost of that uncertainty?
[P5.2] CON's answer, said plainly, is the public. Uncertainty resolves in favour of release, and we find out from the harm. That is what "regulate where harm is visible" means for capabilities that only become visible after they are loose — and CON conceded the irreversible case outright: once weights leak, nothing retrieves them.
[P5.3] My answer is that the party that built the thing, profits from it, and alone possesses the compute to study it bears the cost of not knowing. Unresolved question, no market access yet. That is not a stamp of safety; it is a refusal to treat ignorance as a licence.
[P5.4] And notice CON's central weapon eats its own case. "Regulators cannot verify" is not a reason to leave the same unverifiable claim as a disclosure nobody must file before acting. False assurance is a risk of any regime; unasked questions are a certainty of theirs. Geofencing and third-country releases are arguments for exercising the single market's leverage, not for declining to ask.
[P5.5] Ask first, or find out later. Vote to ask.

## Turn 10: CON Closing

- model: kimi-k3
- raw_words: 203
- clipped_words: 203
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.3], [P4.3]
- missing_claim_id_refs: (none)

[C5.1] "Ask first" assumes that asking produces knowledge. PRO's whole machine presupposes detection: revocation needs a spotted violation, misrepresentation liability a provable standard, refusal a measurable threshold. Three speeches on, thresholds remain borrowed from frameworks "the labs themselves already publish," and verification remains the lab's own evaluations read back by officials who cannot re-run them. A gate nobody can see through does not shift uncertainty's cost onto the lab; it hides it behind a signature, and the public pays with unearned confidence.
[C5.2] That answers "ignorance as a licence" [P5.3]. Today, uncertainty is disclosed, developer duties bind continuously, and downstream uses stay watched where failures announce themselves. Under licensing, uncertainty is certified, and the stamp tells every deployer to stop checking the one layer where harm is provable. False assurance is not a risk of any regime; it is licensing's foundation.
[C5.3] PRO calls open release "an irreversible act" [P4.3] — precisely where the gate is emptiest. Revocation retrieves nothing; refusal relocates the release past whoever volunteers to stand at it. You find out later under both regimes. The question is whether the interval is spent awake at the observable layer, or asleep behind a certificate.
[C5.4] Asking is not a safety technique. Knowing is. Vote CON.
