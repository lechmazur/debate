# Debate prop_0354__deepseek-v4-pro-0813-high__claude-fable-5-2-high__s1__tpl_placement_active_20260813a

- topic_id: prop_0354
- proposition: Advanced driver-assistance systems should default to intelligent speed assistance rather than leave speed warnings and limiters mostly optional.
- model_pro: deepseek-v4-pro-0813-high
- model_con: claude-fable-5-2-high
- side_swap: True

## Turn 1: PRO Opening

- model: deepseek-v4-pro-0813-high
- raw_words: 352
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Every time a driver drifts a few km/h over the limit, the car already knows the limit and could gently hold the speed. The question is whether that safety function should be on when the engine starts or buried in a settings menu. It should be on.
[P1.2] Speed warnings are the worst of both worlds: they demand attention, punish with noise, and are easily ignored or switched off after the first annoying beep. A driver approaching a school zone at 40 in a 30 does not need information; they need the vehicle to reduce speed before the crosswalk, not after the warning has been processed. Optional limiters fail for the same reason. The people who activate them are already cautious.
[P1.3] The people who need them most disable them, ignore them, or never find the menu.
[P1.4] Default intelligent speed assistance changes the social meaning of speeding. Instead of normal driving with occasional warnings, the legal limit becomes the vehicle’s baseline, and exceeding it requires an explicit override. That is not a ban on driver judgment. It is the same logic as traction control or automatic emergency braking: the car starts in the safer mode, and the driver can consciously opt out for a specific maneuver.
[P1.5] The burden shifts from remembering to be safe to choosing to be less safe.
[P1.6] The safety payoff is not marginal. Crash energy rises with the square of speed, so even a modest reduction in the fastest driving produces a disproportionate reduction in fatal and serious injuries. Default ISA compresses the top of the speed distribution, where the deadliest crashes live. It protects pedestrians, cyclists, children, older drivers, and anyone who makes a momentary error on an unfamiliar road.
[P1.7] Technical limits do not defeat this. A false low limit causes a brief, correctable slowdown. A missed high limit causes a crash. The asymmetry favors defaulting to the safer interpretation.
[P1.8] The real choice is between a car that starts safe and lets you override, and a car that starts permissive and hopes you will opt into safety. The [clipped]

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 377
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8], [C1.9]
- cited_claim_ids: [P1.7], [P1.2], [P1.3], [P1.4]
- missing_claim_id_refs: (none)

[C1.1] PRO's case rests on one sentence: "the car already knows the limit." It doesn't. It guesses, from camera reads of signs and from map data that goes stale. Anyone who has driven with these systems has seen the motorway where the car picks up a 30 sign from the parallel slip road, the roadworks limit that ended two miles back, or the time-of-day school sign it can't parse.
[C1.2] A default built on a guess does not make the legal limit the baseline. It makes the car's error the baseline.
[C1.3] That breaks the asymmetry in [P1.7]. A false low limit is not a "brief, correctable slowdown" when the car sheds speed in fast traffic with a truck behind you. It creates an unexpected speed differential, which is exactly how rear-end crashes happen. A missed high limit does not "cause a crash" either, because it leaves you where an optional system leaves you, driving the car yourself.
[C1.4] The harm unique to the default is the wrong intervention.
[C1.5] PRO has also described the fatal flaw in its own proposal. Per [P1.2], annoying systems get "switched off after the first annoying beep", and per [P1.3], the people who most need them disable them. A default that intervenes wrongly and often is the most annoying system of all. So PRO faces a dilemma.
[C1.6] If override is easy, the reckless drivers at the deadly top of the distribution press through or switch it off, and the safety payoff vanishes. If override is hard, the car resists you mid-overtake or mid-merge, exactly when hesitation is dangerous.
[C1.7] The traction-control analogy in [P1.4] fails for the same reason. Traction control and emergency braking sense physical reality, wheel slip or an obstacle, and intervene rarely. ISA enforces a legal inference and intervenes constantly. It also anchors drivers to a number that is not the safe speed.
[C1.8] The limit in fog, on ice, or outside a school at pickup time is too fast, and a car that holds the limit teaches drivers to stop judging.
[C1.9] Speed assistance works where drivers trust [clipped]

## Turn 3: PRO Rebuttal 1

- model: deepseek-v4-pro-0813-high
- raw_words: 315
- clipped_words: 315
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8]
- cited_claim_ids: [C1.3], [C1.6], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] The core of CON’s case is that ISA guesses, so its errors become the baseline. But that treats a misread limit as more dangerous than a missed one. It is not. A false low limit produces a predictable, gradual reduction to a speed that is still lawful on the adjacent road; a missed or false high limit leaves a driver at lethal speed where the car could have intervened.
[P2.2] If the system has the roadwork sign wrong, the driver can override or brake. If the limiter was optional and off, there is no second chance. [C1.3] calls the wrong intervention the unique harm, but the wrong intervention is the safer error.
[P2.3] The rear-end scenario overstates the intervention. ISA does not need to brake abruptly. It can cap acceleration or bleed speed gently enough for a following driver to react. A truck that cannot respond to a normal slowdown is already following too close.
[P2.4] The crash cause is not the cap; it is the unsafe following distance. And the driver retains an override for merges and overtaking.
[P2.5] The override dilemma in [C1.6] demands all-or-nothing safety. Defaults work even when override is easy. Most drivers depart in the default mode and exceed the limit only when they make a deliberate choice. The determined speeder may push through, but the large middle of the distribution does not.
[P2.6] Compressing that middle is where fatal and serious crash reductions come from. We do not need to physically defeat the most reckless driver to change the baseline.
[P2.7] Finally, [C1.7] proves too much. Legal limits are not random guesses; they encode road geometry, visibility, and vulnerable users. Saying a limit is too fast in fog is not an argument against default ISA. A default cap is a ceiling, not a target.
[P2.8] The driver can still slow below it. What they should not be able to do casually is exceed it without noticing.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 362
- clipped_words: 340
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8], [C2.9], [C2.10]
- cited_claim_ids: [P1.6], [P2.5], [P2.8], [P1.2], [P2.1], [P2.3], [P2.2], [P1.4], [P2.7]
- missing_claim_id_refs: (none)

[C2.1] PRO has quietly moved the goalposts. The opening said default ISA "compresses the top of the speed distribution, where the deadliest crashes live" [P1.6]. Now, "the determined speeder may push through" and the payoff comes from "the large middle" [P2.5]. That concedes the top.
[C2.2] And the middle, the ordinary driver drifting a few over, is exactly who responds to a clear prompt. PRO's own closing standard is that drivers shouldn't exceed the limit "without noticing" [P2.8]. Noticing is information. The opening said drivers do "not need information" [P1.2].
[C2.3] One of those claims has to go.
[C2.4] The error asymmetry in [P2.1] compares the wrong worlds. When the system misses a limit, the default car and the optional car behave identically, because neither intervenes. That harm is shared, so it cannot count for the default. A false high reading is worse under PRO's design, because the driver has been taught the car holds the limit.
[C2.5] A false low intervention exists only in PRO's world. Saying the speed is "still lawful on the adjacent road" is no comfort on the road you are actually on.
[C2.6] On the truck, "already following too close" [P2.3] assigns blame; it does not prevent the collision. Defaults must be built for the traffic that exists. Close following on fast roads is part of that traffic.
[C2.7] PRO's fix for every wrong intervention is "the driver can override" [P2.2]. Follow that through. If the car misreads signs regularly, overriding stops being the "explicit" and "deliberate choice" of [P1.4]. It becomes a reflex performed several times a trip.
[C2.8] A default that trains drivers to push through it has destroyed the social meaning PRO wanted to create. PRO still hasn't answered its own observation that annoying systems get "switched off after the first annoying beep."
[C2.9] Finally, "a ceiling, not a target" [P2.7] contradicts "the legal limit becomes the vehicle's baseline" [P1.4]. A baseline is what drivers settle onto, in fog as in sunshine.
[C2.10] So what does the default uniquely add? It adds wrong interventions and reflexive overrides, and it leaves a top [clipped]

## Turn 5: PRO Pressure Questions

- model: deepseek-v4-pro-0813-high
- raw_words: 73
- clipped_words: 73
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: You say a false high reading is worse under default because drivers are “taught the car holds the limit.” What mechanism makes default drivers trust a known-guessing system more than drivers using optional warnings, rather than checking the displayed limit?
[P3.2] Q2: You concede annoying systems get switched off. If optional warnings are the alternative, why would the middle driver you rely on keep them enabled instead of disabling them after repeated beeps?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 100
- clipped_words: 100
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5], [P2.8], [P1.2]
- missing_claim_id_refs: (none)

[C3.1] Q1: You now concede "the determined speeder may push through" [P2.5], and your standard for everyone else is that they shouldn't exceed the limit "without noticing" [P2.8]. What does a default limiter add for that middle driver that a clear warning doesn't, other than physical interventions when the car has misread the limit?
[C3.2] Q2: You said annoying systems get "switched off after the first annoying beep" [P1.2]. Why would a car that wrongly slows itself on a misread sign survive longer than a beep? And if drivers override it several times a trip, how is override still a "deliberate choice"?

## Turn 7: PRO Rebuttal 2

- model: deepseek-v4-pro-0813-high
- raw_words: 296
- clipped_words: 296
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: The default limiter adds safety in the normal, correct-read case—not merely a penalty in the misread case. A warning only helps if the middle driver notices it while distracted, tired, or looking at the road rather than the speedometer. The drift happens precisely when attention is elsewhere. Default ISA holds the speed before the driver must perceive, interpret, and decide.
[P4.2] That is the safety, not an incidental addition to it. A clear warning still leaves unintentional speeding possible without an active choice; the limiter makes exceeding the limit a deliberate act.
[P4.3] A2: The repeated wrong slowdown is a bad implementation, not an argument against the default principle. ISA can cap acceleration gently rather than brake, so an occasional overread is less aggravating than an alarm. It also uses map, sign, and time data together, so several false interventions per trip is not the necessary condition. And an override remains deliberate: pressing through the pedal or switch because the displayed limit is wrong is nothing like reflexively silencing a beep while continuing at the same speed.
[P4.4] The reason warnings get switched off is that they demand attention and deliver no direct safety result. A soft cap delivers a direct result—the car is slower—and can be reversed only by conscious action.
[P4.5] That is why PRO still wins. CON’s case assumes the relevant driver is already attentive enough to respond to a warning. But the motion exists for drivers who do not notice. A warning off by default never reaches them.
[P4.6] A default limiter protects before attention exists, while easy override preserves driver control. CON treats the false low intervention as the unique harm, but the uneven comparison remains: a brief, correctable slowdown is safer than an unnoticed high speed. The system should fail slow, not fail fast.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 367
- clipped_words: 340
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8], [C4.9]
- cited_claim_ids: [P4.1], [P4.3], [P4.2], [P4.6]
- missing_claim_id_refs: (none)

[C4.1] A1: The mechanism is PRO's own selling point. A warning leaves the driver in charge of speed, so the driver keeps monitoring it. A limiter takes the task over. PRO says default ISA works "before the driver must perceive, interpret, and decide" [P4.1].
[C4.2] A driver who no longer needs to perceive is not "checking the displayed limit". They rest their foot against the cap, as people do with cruise control. When the car reads 50 in a 30, it carries them to 50.
[C4.3] A2: Some will disable warnings. But a wrong beep costs a moment of irritation, while a wrong slowdown costs speed in live traffic. If the middle driver won't tolerate the first, they will not tolerate the second. Optionality also lets drivers choose the form they can live with, whether a visual prompt, a haptic pedal, or a limiter.
[C4.4] Systems people choose are the ones they keep on.
[C4.5] Those answers settle the debate, because PRO's defence has now retreated to a car that doesn't exist. Asked why wrong slowdowns would survive, PRO replied that this is "a bad implementation, not an argument against the default principle" [P4.3]. But a default ships on real sensors, real maps, and real signage. A principle that is only safe when the implementation is good is exactly a feature to leave optional until it is.
[C4.6] PRO's protected driver has changed again, too. It is now the "distracted, tired" one [P4.1]. Put that driver in the misread case. The car bogs down on a fast road with traffic behind, and they do what any half-attentive person does and push the pedal harder.
[C4.7] That is a reflex, not the "deliberate act" of [P4.2]. The same inattention PRO relies on makes the override meaningless.
[C4.8] "Fail slow, not fail fast" [P4.6] sounds prudent until you look at both failures. Failing slow in fast traffic creates the speed differential that causes rear-end crashes. Failing fast happens in both worlds, and it is worse in PRO's because the driver has stopped watching.
[C4.9] So the default's unique contributions are unrequested [clipped]

## Turn 9: PRO Closing

- model: deepseek-v4-pro-0813-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] The debate reduces to one question: which failure should the car be built to make? CON has spent the entire round on the false-low misread, but that failure is self-limiting—the car slows, the driver can override, and the error is visible. The failure PRO targets is the unnoticed drift, the driver who never perceives the limit at all. That failure is invisible, and a warning cannot reach it because the driver is not attending.
[P5.2] Default ISA acts before attention exists; that is not a retreat, it is the entire point. CON's alternative only works for the driver who is already monitoring speed, which is precisely the driver who does not need the system. The override objection fails for the same reason: pressing through a physical cap is a conscious act, while ignoring a beep is not. A driver who overrides a wrong limit has noticed the limit; a driver who never hears a warning has not.
[P5.3] The one reason PRO wins is that the default changes the baseline from 'speed unless I notice' to 'limit unless I choose otherwise.' That shift, not perfect sign-reading, is the safety gain. Fail slow is safer than fail fast.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 223
- clipped_words: 220
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6], [C5.7], [C5.8], [C5.9]
- cited_claim_ids: [P5.2], [P4.3], [P4.1], [P5.3]
- missing_claim_id_refs: (none)

[C5.1] PRO's final claim is that default ISA "acts before attention exists" [P5.2]. That sentence decides this debate, and it decides it against them.
[C5.2] A system that acts without the driver's attention is only as safe as its reading of the road. PRO never defended that reading. When pressed, it called wrong slowdowns "a bad implementation, not an argument against the default principle" [P4.3]. But drivers get the implementation, not the principle.
[C5.3] Take the driver PRO says it protects, the "distracted, tired" one [P4.1]. Every safeguard PRO offers needs the attention that driver lacks:
[C5.4] - **The error is "visible"** only to someone looking.
[C5.5] - **Override is "a conscious act"** only for someone conscious of the mistake.
[C5.6] - **A false high reading** gets checked only by someone still tracking their speed, and the cap has taught them to stop.
[C5.7] So PRO's default hands speed control to a guess for exactly the driver least able to catch it when it is wrong.
[C5.8] A warning does the opposite. It exists to summon attention, and it leaves the judgment with the person who can see the truck behind and the fog ahead.
[C5.9] "Limit unless I choose otherwise" [P5.3] is really "the car's guess unless I happen to notice." A default must be trustworthy before it is trusted with the pedal. Until then, the choice belongs [clipped]
