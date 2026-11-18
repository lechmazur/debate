# Debate prop_0556__claude-fable-5-1-high__gemini-4-carbon-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0556
- proposition: Governments should prohibit data brokers from selling individuals’ precise location data without explicit, time-limited opt-in consent.
- model_pro: claude-fable-5-1-high
- model_con: gemini-4-carbon-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 339
- clipped_words: 339
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Your phone's location trail is not just data about where you've been. It is a record of who you are: the clinic you visited on Tuesday, the mosque on Friday, the shelter you fled to, the apartment where you spent the night. Precise location is the one dataset from which every other secret can be inferred, and it is currently bought and sold by companies you have never heard of, to buyers you cannot see.
[P1.2] That is the status quo CON must defend. Not location services, not maps, not weather apps. The sale, by third-party brokers, of individual-level movement records to anyone with a credit card, authorized by nothing more than a buried clause in a terms-of-service nobody read.
[P1.3] The harms are not hypothetical. A priest was publicly outed after commercially available app location data was matched to his movements. Prayer-app data has reportedly ended up with military contractors. Bounty hunters and stalkers have purchased near-real-time phone locations.
[P1.4] Visitors to reproductive health clinics have been packaged into purchasable audience segments. None of these people consented in any meaningful sense, and the "anonymization" defense collapses the moment one notices that a device sleeping at your address and parking at your office is you.
[P1.5] Three features make the motion proportionate. First, it targets brokers, not first-party services: your navigation app still works. Second, it requires explicit opt-in because consent you can't recall giving isn't consent. Third, it is time-limited because a "yes" from 2019 should not license perpetual resale after your life changes, after you start chemotherapy or leave an abusive partner.
[P1.6] Why government rather than the market? Because the market cannot fix a transaction the victim cannot observe. You can't shop around against a broker you don't know exists, and the harm often falls on third parties, the people whose homes you visit. That is textbook market failure.
[P1.7] If selling someone's whereabouts creates real value, companies can ask and people will say yes. The only business model this motion destroys is the one that depends on people never being asked.

## Turn 2: CON Opening

- model: gemini-4-carbon-high
- raw_words: 314
- clipped_words: 314
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.7], [P1.4], [P1.5], [P1.1], [P1.3], [P1.6]
- missing_claim_id_refs: (none)

[C1.1] PRO’s entire case rests on a comforting premise: if selling location data creates real value, "companies can ask and people will say yes" [P1.7]. Trace how people actually respond to recurring prompts, however, and this motion fails from both directions: it destroys vital public data whenever users tap "no," yet fails to stop abuse whenever apps extract a "yes."
[C1.2] Start with where users tap no. Municipal transit planners, disaster modelers, epidemiologists, and small retailers do not run mobile operating systems; they license device-level trajectory panels from brokers to understand how populations commute, flee storms, or shop. Because PRO counts even unnamed home-to-work device trails as individual data [P1.4], those civic and commercial uses hit this ban head-on. Yet no individual captures the diffuse public benefit of better bus routes or outbreak tracking when facing a pop-up asking to sell their location.
[C1.3] Opt-in collapses into a tiny, skewed sample, and mandatory expirations sever the longitudinal continuity needed to measure how a storm or new transit line reshapes neighborhood movement over time.
[C1.4] Now look at where apps extract a yes. By targeting only brokers while exempting first-party services [P1.5], PRO leaves dominant tech platforms free to hoard precise location in-house, infer every secret [P1.1], and sell sensitive audience targeting inside walled gardens. Independent weather, transit, and utility apps own no walled garden; losing broker revenue pushes them toward paywalls or recurring consent gates. Lower-income users who cannot afford subscriptions tap "Allow" to keep free tools, turning privacy into a luxury good while consolidating market power in Big Tech.
[C1.5] Worse, once clicked, PRO’s rule legally blesses broker resale during that window: stalkers, bounty hunters, and predatory buyers [P1.3] can still purchase those records, and third parties whose homes that user visits [P1.6] remain exposed without ever consenting.
[C1.6] Explicit opt-in is a mirage: it leaves Big Tech untouched, leaves stalkers one pop-up away, and blinds vital public planning.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 325
- clipped_words: 325
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.3], [C1.6], [C1.2], [C1.4], [P1.6], [C1.5]
- missing_claim_id_refs: (none)

[P2.1] CON's case contradicts itself. One half says opt-in produces "a tiny, skewed sample" [C1.3]; the other half says consent will be so pervasive that stalkers remain "one pop-up away" [C1.6]. Pick one. If consent is scarce, the stalker marketplace starves.
[P2.2] If consent is abundant, the planners have their data. Either way, one of CON's two pillars falls.
[P2.3] Now the "vital public data" pillar [C1.2]. The motion prohibits selling individuals' precise location. It does not touch aggregated, non-reidentifiable flow statistics, which is what transit planners actually use: how many devices moved from this zone to that one at eight a.m. Epidemiologists tracked a pandemic largely with aggregated mobility indices.
[P2.4] If a disaster modeler genuinely needs device-level trails, the answer is a lawful, safeguarded public channel, not a market where the same feed is sold to a bounty hunter next door. CON is asking you to keep the stalker marketplace open so that bus routing can free-ride on it.
[P2.5] The Big Tech argument [C1.4] is not a reason to reject the motion; it is a complaint that the motion doesn't go further. A first-party platform is at least a counterparty you can see, sue, and leave. A broker is the one actor you cannot observe, which is exactly the market failure CON never answers [P1.6]. And the "privacy as luxury good" worry describes the status quo: today the poorest users are already sold, perpetually, without being asked.
[P2.6] Under the motion, their yes at least expires.
[P2.7] On the consent window [C1.5]: yes, a time-limited yes licenses resale during that window. Compare to CON's world, where everyone is for sale, forever, with no window at all. A stalker buying from a small, expiring, consented pool is harder than one buying from a universal, permanent one.
[P2.8] Third-party exposure shrinks for the same reason.
[P2.9] CON has spent a speech arguing the motion is too narrow and too weak. That is a strange position for the side defending no limit at all.

## Turn 4: CON Rebuttal 1

- model: gemini-4-carbon-high
- raw_words: 302
- clipped_words: 302
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [P2.1], [P2.6], [P1.5], [P2.2], [P2.7], [P2.4], [P1.6], [P2.8], [P2.3], [P1.4], [P2.5], [P1.1], [P2.9]
- missing_claim_id_refs: (none)

[C2.1] PRO claims scarce planner data and stalker exposure cannot coexist [P2.1], confusing volume with selection bias. Strip independent apps of broker revenue and they erect pay-or-consent walls; whenever PRO’s timer expires [P2.6], they block the screen and re-prompt. Affluent users pay or decline, while lower-income users—or someone trying to "leave an abusive partner" [P1.5] without a separate card for subscriptions—get pushed into tapping "Allow" to keep free transit or weather apps working. Both outcomes follow at once [P2.2]: losing affluent neighborhoods and resetting IDs shatters representative, multi-year research baselines, yet a stalker [P2.7] needs one vulnerable target, not a representative sample.
[C2.2] PRO does not close the stalker marketplace [P2.4]; PRO legally licenses it [P2.7] behind recurring prompts that neither reveal downstream buyers [P1.6] nor protect third parties whose homes that user visits [P2.8].
[C2.3] PRO’s rescue for civic science fails too. Eight a.m. zone headcounts [P2.3] cannot track multi-stop bus transfers, clinic catchments, or whether storm evacuees ever returned home, and only tech giants own enough first-party scale to build broad mobility indices without brokers. Answering those questions requires linking one device over time—which PRO already defined as "you" [P1.4], banning trajectory panels outright. Realizing that, PRO invents "a lawful, safeguarded public channel" [P2.4] written nowhere in this motion.
[C2.4] Under the actual proposition, universities, transit agencies, and small businesses are locked out.
[C2.5] Finally, sparing Big Tech is not a harmless gap where users can simply "leave" [P2.5]. Leave to what—a third smartphone operating system? Outlawing independent apps’ monetization while leaving walled gardens free to infer every secret [P1.1] actively entrenches a mobile duopoly and, unlike today [P2.5], penalizes lower-income users who tap "no" by locking everyday utilities behind paywalls. Blinding public science, entrenching monopolies, and stamping statutory consent onto predatory resale is not merely "too narrow" [P2.9]; it makes the status quo worse.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.5], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You claim the motion makes the status quo worse [C2.5]. Today every user is sold, permanently, without any prompt at all. Name one person who is better off being sold forever without being asked than being asked, able to tap "no," and having any "yes" expire.
[P3.2] Q2: You insist planners need device-level trajectory panels from brokers [C2.3]. Would you accept any rule restricting who may buy them, or must the transit agency and the bounty hunter remain customers of the same feed?

## Turn 6: CON Pressure Questions

- model: gemini-4-carbon-high
- raw_words: 71
- clipped_words: 71
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P3.1], [P2.4], [P1.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You assume users are freely "able to tap 'no'" [P3.1]—under your motion, may a free independent app lock users who tap "no" behind a subscription paywall, or is conditioning free access on opt-in prohibited?
[C3.2] Q2: Since the motion as written contains no "safeguarded public channel" [P2.4], may brokers still sell unnamed longitudinal device trajectories [P1.4] to disaster modelers and epidemiologists without opt-in, or does your motion ban those sales too?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 366
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: An app may charge for its own service; that is pricing, and the motion does not touch it. What it may not do is make the sale of your trail to third parties the toll for entry, because consent extracted under a "pay or be sold" wall is not "explicit" consent to the sale. Explicit means the yes is to the thing itself, freely given.
[P4.2] But notice what the question concedes. If apps must build paywalls to pry out a yes, that is because, asked honestly, most people say no. CON's funding model for "free" apps is, by CON's own account, selling users who would refuse if asked. That is the motion's indictment, not a defense against it.
[P4.3] A2: Yes, it bans them. Individual-level precise trajectories are covered whether or not a name is attached, because a device that sleeps at your address is you, and CON has not disputed that. The feed sold to the epidemiologist is the same feed sold to the bounty hunter; a broker's price list does not check motives. The motion restricts brokers; it does not stop a legislature creating a research channel with vetting and penalties, and it does not stop researchers recruiting consented panels, which they already do.
[P4.4] What CON actually demands is that the open market stay open, for everyone, so that a few customers with good intentions can keep buying.
[P4.5] Now step back. CON's two questions were about edge cases in the motion. My two questions were about the core of CON's position, and both went unanswered. CON never named a single person better off being sold forever without being asked.
[P4.6] CON never said whether any buyer restriction is acceptable, which means CON's position is that the transit agency and the stalker must remain customers of the same shelf.
[P4.7] That is the choice. Under the motion, the worst case is a smaller pool, consenting, for a window that closes. Under CON, the pool is everyone, the window never closes, and nobody is asked. Even granting every coerced tap CON imagines, [clipped]

## Turn 8: CON Rebuttal 2

- model: gemini-4-carbon-high
- raw_words: 312
- clipped_words: 312
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.2], [P4.1], [P1.1], [P4.3], [P4.7], [P1.5], [P1.6]
- missing_claim_id_refs: (none)

[C4.1] A1: Take a low-income bus rider or storm-zone resident relying on free independent transit and weather apps. Under PRO’s own rule, because "most people say no" [P4.2] and consent-supported free tiers are barred, an independent app must "charge for its own service" [P4.1] or fold. Priced out of newly paywalled utilities, that resident is pushed onto Big Tech’s free first-party apps—which still log every clinic, mosque, and shelter visit [P1.1] without expiry—while losing the unnamed trajectory feeds that route their buses and guide hurricane evacuations ("Yes, it bans them" [P4.3]).
[C4.2] Losing free tools and emergency planning while Big Tech still tracks you leaves that person concretely worse off.
[C4.3] A2: Yes—restricting buyers and uses by banning sales to stalkers, bounty hunters, or re-identification while preserving vetted civic panels is sensible policy. Opposing this proposition rejects a blunt upstream opt-in ban, not targeted buyer rules. Ironically, PRO’s motion as written keeps the stalker and transit agency on the same shelf: because "a broker's price list does not check motives" [P4.3], everyone inside PRO’s "smaller pool" [P4.7]—whether via perks, prompt fatigue, or a "yes" clicked weeks before fleeing an abuser [P1.5]—remains legally for sale to bounty hunters, while every "no" locks out epidemiologists and planners.
[C4.4] Even judged strictly against today’s status quo, PRO’s own concessions prove this motion does more harm than good. First, it blinds public-interest mobility science immediately ("Yes, it bans them" [P4.3]). This motion contains no "research channel," and small pre-recruited panels [P4.3] cannot retroactively supply before-and-after baselines where an unexpected wildfire, flood, or outbreak strikes. Users tap "no" [P4.2] because no individual captures citywide public goods at a pop-up, not because evacuation modeling lacks value.
[C4.5] Second, PRO’s rule starves independent apps into paywalls [P4.1], herds users into Big Tech’s permanent first-party tracking, and still licenses downstream sales exposing opted-in users and unconsenting third parties [P1.6]—sacrificing vital public capabilities for illusory privacy.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 219
- clipped_words: 219
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.3], [C4.1], [P4.2]
- missing_claim_id_refs: (none)

[P5.1] Strip away the trajectory panels and paywalls and one admission decides this. Asked whether the transit agency and the bounty hunter must remain customers of the same shelf, CON answered that banning sales to stalkers and preserving vetted civic panels is "sensible policy" [C4.3]. That is a concession that the open broker market is indefensible. Yet CON's side of this motion is the open broker market.
[P5.2] There is no third option on the ballot; opposing the proposition keeps the shelf exactly as it is: everyone on it, forever, nobody asked.
[P5.3] Measure CON's best victim against that. The low-income bus rider [C4.1] is "worse off" because a free app can no longer fund itself by selling her movements without telling her. CON's own words say she would refuse if asked [P4.2]. A benefit that survives only because the person paying for it doesn't know she's paying is not a benefit CON gets to weigh.
[P5.4] And the research question answers itself through the same door CON opened: if vetted channels are sensible, legislate them. Nothing in the motion forbids that. What the motion forbids is the status quo CON cannot bring itself to defend out loud.
[P5.5] Scarce consent starves the stalker. Abundant consent feeds the planner. Either way, the yes is real and the yes expires. That is the whole case.

## Turn 10: CON Closing

- model: gemini-4-carbon-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: [P5.2], [P5.4], [P4.3], [C4.3], [P5.5], [P1.5], [P1.6], [P4.2], [P5.3], [P4.1], [P1.1], [C4.1]
- missing_claim_id_refs: (none)

[C5.1] PRO insists "there is no third option on the ballot" [P5.2], then tells you to "legislate" vetted channels [P5.4] to rescue the disaster, outbreak, and transit data this motion destroys ("Yes, it bans them" [P4.3]). Saying targeted buyer rules would beat the status quo [C4.3] never justifies a blunt consent law that makes today’s world worse.
[C5.2] Test PRO’s closing binary [P5.5] against the motion actually on the ballot. Scarce consent does not starve the stalker: a predator needs just one target, like someone who tapped "yes" weeks before fleeing an abuser [P1.5], who remains legally for sale to any buyer [C4.3], exposing every home she visits [P1.6]. Yet scarce consent does blind the planner: because no lone user captures citywide flood evacuations or bus routing at a pop-up, "most people say no" [P4.2], wiping out unskewed baselines overnight.
[C5.3] Meanwhile, that low-income bus rider [P5.3] still pays with her movements: when independent apps paywall or fold [P4.1], she is pushed onto Big Tech’s free first-party tools, which log every clinic and shelter visit [P1.1] without expiry [C4.1]. PRO locks out the public planner, hands permanent tracking to Big Tech, and leaves the bounty hunter at the same shelf.
