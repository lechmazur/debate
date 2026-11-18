# Debate prop_0556__glm-5-3-high__hy4-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0556
- proposition: Governments should prohibit data brokers from selling individuals’ precise location data without explicit, time-limited opt-in consent.
- model_pro: glm-5-3-high
- model_con: hy4-high
- side_swap: False

## Turn 1: PRO Opening

- model: glm-5-3-high
- raw_words: 353
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Precise location data is not ordinary commercial information. A record of where you sleep, pray, seek medical care, and who you meet is a profile of your intimate life, assembled without your knowledge and sold to strangers. That is why governments should prohibit data brokers from selling it without explicit, time-limited opt-in consent.
[P1.2] Three features make this market uniquely dangerous. First, location data is generated involuntarily. You cannot use a phone, a weather app, or a maps service without generating it, and it flows through advertising pipelines to brokers who never had a relationship with you. Consent that was never asked for is not consent.
[P1.3] Second, location data is impossible to anonymize in practice. A trail of timestamps and coordinates identifies a person even without a name — researchers have repeatedly shown that a handful of spatiotemporal points distinguish one individual from millions. Promises of "de-identification" are fig leaves, not safeguards.
[P1.4] Third, the harms are irreversible and physical. Domestic abuse shelters, mosques, synagogues, clinics providing abortion care, and military bases have all appeared in commercially available location datasets. A leaked password can be changed; your home address and daily routine cannot.
[P1.5] The remedy must match the harm. Opt-out regimes fail structurally: they bury choices in dark-pattern settings, apply to data already collected, and assume people have time to police dozens of invisible middlemen. Time-limited opt-in forces the question up front, in plain terms, before harm occurs. The time limit matters because a permission granted in 2019 should not silently license tracking through 2035 — relationships between users, apps, and purposes change, and consent that never expires is not meaningful consent.
[P1.6] This is not a radical burden on commerce. Advertisers can still contextual-advertise to a weather app without knowing which clinic you visited. Legitimate uses — a rideshare you hailed, a delivery you ordered — involve consent in the ordinary course. What the rule targets is the resale of your movements to parties you've never heard of, for purposes you never imagined.
[P1.7] Default permission for perpetual physical tracking is a policy [clipped]

## Turn 2: CON Opening

- model: hy4-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: [P1.4], [P1.5], [P1.6]
- missing_claim_id_refs: (none)

[C1.1] Precise location can reveal intimate facts. That is why this rule is too weak and too blunt. It regulates the last cash register in a long chain: phones, apps, ad networks, SDKs, service providers, analytics vendors, and brokers. The same trail can be modeled in a clean room, shared under a “service provider” contract, or moved abroad without a sale.
[C1.2] A broker’s checkbox cannot trace lawful consent through a rotating device identifier to a real person. The sensitive-site examples [P1.4] show the need for use restrictions, not consent at resale.
[C1.3] Broaden “sale,” and the remedy becomes either an effective ban or click theater. Brokers usually have no relationship with the person whose coordinates they hold. Some app must ask users to authorize unknown buyers, purposes, and renewals. That relocates the dark patterns [P1.5] condemns upstream.
[C1.4] Repeated prompts produce reflex clicks; cautious users decline, so datasets overrepresent the least privacy-conscious. Shared phones, children, workplace devices, tourists, and reset IDs make expiring consent less like control.
[C1.5] The losses from this rule are concrete. Fraud teams use location continuity to flag a card used far from the customer’s phone. Transit agencies use historical movements to plan bus routes and evacuation capacity. Mobility data also helps estimate foot traffic and outbreak exposure.
[C1.6] These uses do not resemble rideshare or delivery [P1.6], where a person requests the service. They require continuous, representative datasets. Per-person, expiring permissions shred continuity, bias samples, and price public-interest users out.
[C1.7] Governments can ban sensitive-site geofencing, require warrants, cap retention, mandate deletion, prohibit onward transfer, impose purpose-bound contracts and audit logs, and punish misuse. Those duties hit the dangerous act: identifying, targeting, retaining, or exposing movements. A time limit on a broker’s permission gives the state a checkbox while the dataset keeps moving. A brittle ritual should not defeat direct, enforceable control.

## Turn 3: PRO Rebuttal 1

- model: glm-5-3-high
- raw_words: 373
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.7], [C1.6], [C1.3]
- missing_claim_id_refs: (none)

[P2.1] My opponent's own opening concedes the core of my case: precise location data reveals intimate facts, and the harms I described are real. Their argument is that we should treat the disease elsewhere. But look at what that argument does — it moves from "this rule is insufficient alone" to "this rule should not exist." That leap fails, twice over.
[P2.2] First, brokers are the chokepoint, not the last cash register. Data is collected upstream precisely because there is a downstream market that pays for it. Prohibit the sale without consent and you collapse the price of un-consented location trails; apps collect less because brokers buy less. Demand-side regulation works backwards through the chain.
[P2.3] Attacking "the dangerous act" of retention and transfer, as [C1.7] proposes, still requires someone to enforce duties on a dataset that only exists because brokers monetized it. Their alternative regulates the fuel spill after endorsing the pipeline.
[P2.4] Second, "too blunt" collapses under their own examples. Fraud teams checking whether a card was used near the customer's phone don't need to *buy* that trail from a broker — the bank already has it through its service relationship. Transit planning works on aggregated, anonymized flows, and where it needs more, agencies can obtain consent in the ordinary course, the way they run surveys and studies today. What [C1.6] actually defends is the convenience of continuous representative datasets built without asking anyone.
[P2.5] "Representative" here means "surveilled without knowing" — that bias toward silent collection is the problem, not a feature to preserve.
[P2.6] On [C1.3], the consent-theater worry: yes, prompts can be designed to manipulate. But that is an argument for regulating dark patterns and requiring plain-language, time-limited asks — the FTC already polices deceptive consent — not for abandoning consent entirely. And note the asymmetry: under my rule, the default is no sale, and a manipulative prompt fails loudly and correctably. Under theirs, the default is perpetual sale of your movements, and the "direct, enforceable controls" are invisible to you until after exposure.
[P2.7] The honest clash is simple: when the [clipped]

## Turn 4: CON Rebuttal 1

- model: hy4-high
- raw_words: 323
- clipped_words: 323
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.2], [P1.6], [P2.3], [P2.4], [P1.3], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] The concession is not the case. Location is sensitive; the question is whether this prohibition protects it. Rejecting a badly fitted instrument is not inaction. A ban on sale regulates a receipt, not a pipeline.
[C2.2] Brokers are not a “chokepoint” [P2.2]: location can be monetized through targeted ads, clean-room matching, service contracts, audience segments, or affiliates. If “sale” means paid transfers of raw trails, firms keep tracking and drop the invoice. Broadening it to catch substitutes is a general processing ban, not the modest remedy advertised in [P1.6].
[C2.3] “Demand-side regulation works backwards” is a slogan: apps collect because location improves targeting, measurement, fraud checks, and analytics. A payment rule may lower one price but not stop upstream collection, retention, inference, or non-sale sharing. The spill metaphor [P2.3] points the other way: the danger is building, identifying, retaining, and targeting from the trail. Purpose bans, legal-process rules, retention caps, deletion, onward-use limits, and audits bite whatever the transaction is called.
[C2.4] These examples expose a double standard. [P2.4] trusts anonymized flows for transit; [P1.3] calls de-identification a fig leaf. If aggregation is safe, purpose-bound rules can permit it without opt-in from every passerby. If unsafe, surveys cannot recreate continuous mobility maps for routes or evacuations.
[C2.5] Nor is a bank’s own app signal a cross-institution continuity check after a reset or new account. Consent-selected samples omit the people planners most need to count.
[C2.6] Dark patterns are not cured by moving them earlier. [P2.6] imagines a plain-language ask that fails loudly, but the broker has no relationship with the person, so an app must request permission for unknown buyers, changing purposes, affiliates, and renewals. Repetition produces fatigue, and a bad prompt is discovered after copies have moved. Once they add prompt-design rules, audits, purpose limits, deletion, and correction, enforceable use controls do the real work.
[C2.7] The real default is no sensitive-site targeting, capped retention, and deletion duties—not a perpetual sale. Governments should reject this brittle resale checkbox.

## Turn 5: PRO Pressure Questions

- model: glm-5-3-high
- raw_words: 80
- clipped_words: 80
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.3], [C2.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say use restrictions "bite whatever the transaction is called" [C2.3] — so name the mechanism: who discovers, and who enforces against, a trail held by a buyer nobody knows exists, when the person surveilled never sees the dataset?
[P3.2] Q2: If any broad definition of "sale" becomes a processing ban [C2.2], does any consent rule you'd accept exist at all — or is your real position that no sale of location data should ever require asking the person first?

## Turn 6: CON Pressure Questions

- model: hy4-high
- raw_words: 60
- clipped_words: 60
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P3.2], [P3.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: Before asking whether any consent rule survives [P3.2], can you define “sale” to cover clean-room matches, ad auctions, affiliates, and service-provider transfers without becoming the processing ban you deny?
[C3.2] Q2: If your hidden-buyer objection defeats use restrictions [P3.1], who verifies, before the next resale, that every downstream copy held by that unknown buyer has a current, purpose-specific, time-limited opt-in?

## Turn 7: PRO Rebuttal 2

- model: glm-5-3-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C1.7], [C3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: Yes. "Sale" should cover any exchange of value — money, data, reduced fees, or service — for access to precise location trails, whether raw, tokenized, or matched in a clean room. What it does not cover is the service relationship itself: when you hail a rideshare, the company processing your location to deliver the ride you asked for isn't selling anything. The line is honest and workable: processing to fulfill a user's request is exempt; transferring location data to anyone whose purpose the user didn't request requires asking first.
[P4.2] If firms respond by relabeling transfers, that is an argument for drafting definitions to catch evasion — not for skipping the ask. Notice that my opponent's alternatives [C1.7] need the same definitional line: a "purpose-bound contract" and a "sale" both require knowing what a transfer is for. They cannot claim definitions are impossible while proposing their own.
[P4.3] A2: The broker carries the burden. Under my rule, the sale is the checkpoint: no verifiable, current, time-limited opt-in, the transfer is unlawful on its face. That creates a paper trail regulators can audit, a contract a whistleblower can produce, and a violation that doesn't depend on the surveilled person finding the buyer. My opponent's hidden-buyer objection [C3.2] cuts against them: their use restrictions bind the same unknown downstream holders, but with no licensing moment — no record, no gate, no clear violation before exposure.
[P4.4] That is the decisive comparison. Their toolkit — purpose limits, retention caps, deletion — is available in both worlds. The only question this debate decides is whether those controls run alone or on top of a consent gate at the moment of transfer. Their system watches the spill with no valve.
[P4.5] Mine closes the valve and still keeps the watchers. Choose both.

## Turn 8: CON Rebuttal 2

- model: hy4-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P3.1], [P4.1], [C2.2], [P3.2], [P4.3], [C3.2], [P4.5], [C2.6], [C1.6], [C2.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Not the person; regulators discover and enforce through a duty on every holder of precise-location trails: a logged, purpose-bound chain of custody; registered recipients; capped retention; audit access; and liability on the transferor for any unlogged transfer. Logs, counterparties, whistleblowers, or any surfacing copy reveal the buyer. The duty follows the trail into that buyer's hands; it does not wait for the surveilled person to find a dataset or a broker's invoice. That is the mechanism [P3.1] says is missing.
[C4.2] A2: No. Asking can be required in a direct relationship for a new, named purpose beyond the requested service; that is not this motion. I reject the motion's universal broker-resale gate: an app authorizing unnamed buyers, affiliates, clean-room matches, and renewals for people it cannot identify. That delegates consent to the party least able to describe it. And [P4.1]'s "honest and workable" line either exempts those exchanges—leaving the hidden buyer—or covers them and becomes the processing ban [C2.2] named.
[C4.3] So [P3.2]'s dilemma is false. I never denied definitions; I denied that this one holds.
[C4.4] [P4.3]'s "paper trail" is the same artifact use controls require, but weaker: "unlawful on its face" helps only once a regulator knows a transfer occurred; an unknown unlogged copy yields no contract for a whistleblower. [C3.2] still stands: who verifies every downstream copy's current, purpose-specific opt-in before the next resale? A broker's one-time attestation cannot bind copies moving as "service," affiliates, or ad auctions.
[C4.5] "Choose both" [P4.5] is not additive. The gate diverts enforcement into checking forms, moves dark patterns upstream [C2.6], and breaks the continuous datasets that make fraud checks, transit counts, and audits workable [C1.6]. A valve that cannot see relabeled pipes is not a valve. Purpose bans, warrants, deletion, retention caps, onward logs, and audit duties attach to the dangerous act whatever it is called [C2.3].
[C4.6] PRO offers a visible ritual at sale; CON offers liability that follows the movement. That is the comparison that decides the motion.

## Turn 9: PRO Closing

- model: glm-5-3-high
- raw_words: 205
- clipped_words: 205
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6]
- cited_claim_ids: [C4.6]
- missing_claim_id_refs: (none)

[P5.1] The one question this debate actually decides: before your movements change hands to a stranger, must someone ask you first?
[P5.2] My opponent never says yes. Their entire case is a list of controls — logs, retention caps, purpose limits — that could run alongside my rule. They conceded that in their own comparison: [C4.6] contrasts a "ritual at sale" with "liability that follows the movement."
[P5.3] But liability without a gate means the default is transfer, and enforcement begins after your trail is already in a stranger's hands. Every control they name discovers harm downstream. Mine stops the harm at the moment of transfer, and adds nothing they must give up.
[P5.4] That asymmetry is why the definitional anxiety fails. Yes, drafting "sale" takes care; their purpose-bound contracts need the same line. Evasion is an argument for sharper definitions, never for abandoning the ask.
[P5.5] And remember what the ask protects: where you sleep, pray, and seek care — facts they admitted are intimate at the top of their first speech. A rule that lets those facts move silently by default, hoping audits catch it later, has the sequence backwards. Consent before transfer; enforcement after. Not the reverse.
[P5.6] Close the valve, keep the watchers. That is the motion.

## Turn 10: CON Closing

- model: hy4-high
- raw_words: 190
- clipped_words: 190
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.1], [P4.5]
- missing_claim_id_refs: (none)

[C5.1] Intimate movements deserve protection; the sale checkbox cannot provide it. The harm is not the invoice, but a precise trail in someone’s hands: retained, identified, geofenced, matched, or exposed. Those acts can occur before, after, or without any covered “sale.” PRO’s “valve” fits one pipe while data moves through clean rooms, affiliates, service contracts, and ad systems.
[C5.2] Their question—“must someone ask you first?” [P5.1]—hides the substitution. At broker resale, “you” are not there; an app pre-authorizes unnamed buyers, future affiliates, changing purposes, and repeated renewals. That is not personal choice but a blanket permission slip for a chain. “Choose both” [P4.5] is not free: it diverts enforcement into checking forms, invites dark patterns, and breaks continuous datasets that direct use controls could preserve.
[C5.3] The stronger gate is possession itself: every holder should be logged, purpose-bound, retention-capped, auditable, with the transferor liable for any unlogged copy. Then a hidden buyer is already unlawful from the start, not validated by a form. Consent forms ask whether a checkbox existed. Liability that follows the movement asks what matters: who has your trail, for what, and how long.
[C5.4] Reject the ritual; impose the control.
