# Debate prop_0199__claude-opus-5-5-high__claude-sonnet-5-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0199
- proposition: Open-weight advanced AI models should remain legal by default unless they cross clearly specified capability and misuse thresholds that trigger stronger safeguards.
- model_pro: claude-opus-5-5-high
- model_con: claude-sonnet-5-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-5-high
- raw_words: 347
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9], [P1.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] The question here is not whether dangerous AI should be regulated. It should. The question is where the law starts: with permission or with prohibition. The proposition says start with freedom, then draw bright lines where real danger begins.
[P1.2] That is how we treat chemistry, encryption, and software generally, and it is the right model for AI.
[P1.3] First, open weights produce public goods closed models cannot. When weights are available, independent researchers can audit for bias, probe for hidden behaviors, and stress-test safety claims instead of trusting a company's press release. Hospitals and law firms can run models locally without shipping sensitive data to a third party. Universities and startups can build without paying rent to a handful of labs.
[P1.4] Openly released model families have already become the backbone of academic AI research worldwide. A default ban or licensing regime does not eliminate that research. It hands the field to the few firms rich enough to clear the gate.
[P1.5] Second, thresholds aim at the actual risk. The harms worth fearing are specific: meaningful uplift toward biological or chemical weapons, autonomous cyberattacks, large-scale deception. These scale with capability. A threshold regime concentrates scrutiny precisely there: evaluations, staged release, or withholding weights when a model crosses defined lines.
[P1.6] A blanket restriction spends the same regulatory energy on a coding assistant and on a hypothetical bioweapons tutor. That isn't caution. It's poor aim.
[P1.7] Third, clarity is itself a safety feature. Developers who know the rules can design to them. Vague, discretionary restrictions breed two outcomes: chilled legitimate work at home, and development migrating to jurisdictions with no rules at all. Open models are already published globally.
[P1.8] A country that bans by default does not stop open AI. It only stops its own researchers from studying it.
[P1.9] So CON faces a dilemma. Either they must show that today's open models, below any danger threshold, are themselves catastrophic, or they must explain why thresholds cannot be drawn. And if thresholds cannot be measured, their own restrictive regime has no principled line either.
[P1.10] Permit by default, [clipped]

## Turn 2: CON Opening

- model: claude-sonnet-5-high
- raw_words: 334
- clipped_words: 334
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition asks us to treat open-weight release like a dial we can turn up or down as capability grows. That metaphor is false. Open-weight release is not a dial. It is a one-way door.
[C1.2] Once weights are public, they are mirrored, forked, and fine-tuned across jurisdictions no regulator will ever reach. There is no recall. A closed model that later reveals dangerous capability can be patched, rate-limited, or shut off overnight. An open model that reveals the same thing the day after release cannot be un-released.
[C1.3] That asymmetry is the whole debate, and the resolution's framework has no answer to it.
[C1.4] This matters because thresholds are triggered by what is observed, and observation always lags release. Capabilities emerge through scaling, through chaining a model with tools, through fine-tuning on specialized data the original developer never tested. A model can sit comfortably under a bio-uplift or cyber-offense threshold at launch and cross it eighteen months later when someone fine-tunes it on a narrow dataset costing a few hundred dollars. With closed models, the provider can detect and cut access.
[C1.5] With open weights, the "trigger" fires after the danger is already permanently distributed. A fire alarm that only rings after the building has burned down is not a safeguard.
[C1.6] Worse, open weights make safety training itself reversible by any downstream user. Refusal behaviors and guardrails baked in before release are routinely stripped with cheap fine-tuning. So the very mechanism PRO relies on to keep a model "below threshold" at release time is not durable. The threshold test is measuring a property that a single afternoon of fine-tuning can erase.
[C1.7] PRO's analogies cut against them. Dangerous chemistry is gated through licensed precursor sales, not free distribution with after-the-fact enforcement. Encryption controls loosened only once the risk calculus was understood, not as a starting default for untested frontier capability.
[C1.8] So the honest default for genuinely advanced models isn't permit-then-restrict. It's restrict-then-release, with open weights earning their way out through demonstrated robustness, not claiming the floor until caught.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 341
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON's whole case rests on one image: open release is a one-way door. Grant it. A door you cannot close is exactly why you put the lock *before* the door. That is what this motion does.
[P2.2] "Clearly specified capability thresholds" are tested before release, not discovered afterward. CON describes a "fire alarm that only rings after the building has burned down," but under a threshold regime the alarm is the inspection that decides whether the building opens at all. Irreversibility argues for rigorous pre-release thresholds. It does not argue for presuming every model guilty.
[P2.3] Take CON's strongest point: cheap fine-tuning strips guardrails. Then the threshold test should measure the worst case, meaning what the model can do with its refusals removed and a narrow fine-tune applied. Evaluators can run that experiment before release. CON has not shown a problem with thresholds.
[P2.4] They have shown what a serious threshold must test, and that strengthens our framework.
[P2.5] Now notice CON's own conclusion. Restrict-then-release applies, in their words, to "genuinely advanced models." That qualifier is a threshold. CON has conceded that some models fall below the line and some above.
[P2.6] The live question is whether the line is clearly specified in advance or left to a regulator's discretion. A vague standard of "demonstrated robustness" with no defined test is a gate only large labs can afford to clear.
[P2.7] Their analogies concede the point too. Chemistry is mostly unregulated. Only listed precursors are gated. That is a threshold regime.
[P2.8] Encryption is a warning for CON, not for us. Treating strong cryptography as presumptively dangerous slowed honest users while the mathematics spread globally anyway.
[P2.9] CON's "patch it overnight" advantage is also thinner than it sounds. Closed models get jailbroken through the API every day, and closed weights can leak or be stolen.
[P2.10] So weigh it. Above the threshold, both sides want strong safeguards. Below it, irreversibility is a benefit: a small model a hospital runs locally to summarize records can never be taken away from it. CON's regime makes that hospital ask permission for something [clipped]

## Turn 4: CON Rebuttal 1

- model: claude-sonnet-5-high
- raw_words: 306
- clipped_words: 306
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.3], [P2.9]
- missing_claim_id_refs: (none)

[C2.1] CON's case isn't "ban everything" — it's "the irreversibility PRO just conceded means advanced models carry the burden of proof before release, not after." PRO calls that a threshold too, hoping to collapse our disagreement into semantics. It doesn't. Their threshold triggers safeguards once a model crosses a line, with open distribution as the default up to that line.
[C2.2] Ours flips the default above a reasonable floor: prove safety first, release second. Same word, opposite allocation of risk. That difference is the entire debate, and PRO's "concession" argument doesn't touch it.
[C2.3] On "test the worst case before release" [P2.3]: this asks evaluators to anticipate every fine-tuning dataset, every scaffolding trick, every tool integration that might exist eighteen months from now, across a search space no lab can exhaust in a pre-release window. That isn't a rigorous test. It's a promise dressed as a procedure. Closed deployments don't need to solve that problem — they can observe real-world use and cut access when something unexpected emerges.
[C2.4] Open weights can't, because by the time anything is observed, the model is already mirrored past reach.
[C2.5] Chemistry actually proves my point, not PRO's: precursor chemicals are restricted by default and only released through licensing, exactly the restrict-then-earn structure I'm defending. Encryption loosened only after decades of study showed the risk was manageable — that's the opposite of applying a permissive default to untested frontier capability on day one.
[C2.6] "Closed models get jailbroken too" [P2.9] confuses a patchable failure with a permanent one. An API jailbreak gets fixed by Tuesday. A leaked or openly released weight file is uncopyrightable, unrecallable, forever.
[C2.7] And the hospital example cuts against PRO once you see the asymmetry: a conservative, demonstrably safe floor still lets that hospital run a local model. What it doesn't do is let a frontier-adjacent model ship first and get studied never.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 86
- clipped_words: 86
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You say restrict-then-release applies only "above a reasonable floor" [C2.2]. Name the test that places a model above or below that floor. If you can specify it in advance, how is that different from our threshold? If you can't, isn't it discretion?
[P3.2] Q2: You call pre-release worst-case testing "a promise dressed as a procedure" [C2.3], yet your regime requires models to "prove safety first." What evidence could any open model submit that your own objection wouldn't defeat? If none, isn't your regime a permanent ban?

## Turn 6: CON Pressure Questions

- model: claude-sonnet-5-high
- raw_words: 102
- clipped_words: 102
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P1.8]
- missing_claim_id_refs: (none)

[C3.1] Q1: PRO claims thresholds can be "clearly specified" and tested pre-release, including worst-case fine-tuning [P2.3]. Name one concrete, legally enforceable test that certifies no future $200 fine-tune or tool-chain will push an open model past a bio- or cyber-uplift line. If no such test exists, what exactly triggers your "stronger safeguards" once the weights are already mirrored worldwide?
[C3.2] Q2: You admit a domestic ban "does not stop open AI" globally [P1.8]. If foreign mirrors make enforcement moot anyway, why should your own regime's permissive default matter for safety at all — isn't it just conceding irreversibility while doing nothing to prevent it?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 361
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8]
- cited_claim_ids: [C2.2], [P3.1], [P3.2]
- missing_claim_id_refs: (none)

[P4.1] A1: No test certifies that *no future* fine-tune will ever cross a line. No regime can meet that standard, including CON's. Their "prove safety first" [C2.2] demands the same impossible certificate, so if this question defeats thresholds, it defeats their regime first. What a threshold can do is concrete and enforceable.
[P4.2] Before release, independent red-teamers get the weights with refusals stripped, a fixed fine-tuning and tooling budget, and a battery of bio and cyber tasks. They measure uplift against what a motivated person already gets from search and textbooks. Exceed the margin and the weights stay closed or release is staged.
[P4.3] Because fine-tuning mostly surfaces capability already latent in the base model rather than creating it from nothing, you set the line with a safety buffer below true danger. The trigger fires before the weights leave the building. So CON's "already mirrored worldwide" premise never arises for above-threshold models.
[P4.4] A2: The default matters because the rules bind the people who actually release frontier models: identifiable labs that need data centers, investors, and legal standing. A threshold stops those labs from publishing dangerous weights. A domestic ban on *sub-threshold* models buys nothing, because comparable models are already mirrored abroad. It only stops domestic researchers from auditing them.
[P4.5] That is no concession on irreversibility. It is precision: enforce hard where release is still preventable, and stop pretending to prevent what already circulates.
[P4.6] Now look at what these exchanges revealed. I asked CON to name the test that separates their "reasonable floor" from our threshold [P3.1]. They answered with a question. I asked what evidence could ever satisfy their regime [P3.2].
[P4.7] Again, nothing. So CON's floor exists, but its location is unwritten. Their burden of proof has no defined way to meet it. That is a permanent ban with a waiting room, administered by discretion.
[P4.8] Both sides face uncertainty about future capability, so uncertainty cannot decide this. The deciding question is who pays for it. Under our regime, dangerous models are stopped before release by a published test. Under CON's, every hospital, university, [clipped]

## Turn 8: CON Rebuttal 2

- model: claude-sonnet-5-high
- raw_words: 316
- clipped_words: 316
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.2], [P4.4]
- missing_claim_id_refs: (none)

[C4.1] A1: The test is the same evaluation PRO describes — adversarial fine-tuning, tool-chaining, bio/cyber uplift benchmarks. I never claimed a different instrument. What differs is the default while results are uncertain. PRO's threshold says: release unless the test catches something.
[C4.2] Mine says: don't release until the test clears it. Same ruler, opposite starting point. That's not undefined discretion — it's the same published evaluation, just run before the irreversible step instead of treated as a formality on the way to it.
[C4.3] A2: Yes, an open model can clear my floor — by surviving a controlled, reversible deployment window (gated API access, monitored fine-tuning, adversarial red-teaming under revocable access) before the irreversible step of full weight release. That's not a permanent ban; it's sequencing the reversible test before the unrecallable act, instead of after [P4.2]'s "stays closed or release is staged" — which is my regime using PRO's own words. PRO's objection only "defeats everything" if you demand certainty about all future fine-tunes forever, which I don't — I demand demonstrated robustness under reversible testing first.
[C4.4] Now the pivot. PRO's A1 [P4.1-4.3] admits their margin is set against "a fixed fine-tuning and tooling budget." But fine-tuning and tool costs keep falling every year. A margin computed at release against today's budget decays as tomorrow's $200 fine-tune becomes tomorrow's $20 one.
[C4.5] Their test is static; the threat it's measuring isn't. That's precisely the fire-that-reignites-after-the-inspection problem I raised, and PRO's answer concedes the test's input assumption, not its reliability over time.
[C4.6] And on A2's domestic point [P4.4]: the frontier models this debate is actually about — the ones capable of crossing bio/cyber lines — are built by identifiable, domestic-adjacent labs, not anonymous foreign actors. A restrict-by-default regime binds exactly those labs before release. PRO's "it only stops domestic researchers" claim applies to sub-threshold models nobody is fighting over — not to the advanced systems this resolution is actually about.

## Turn 9: PRO Closing

- model: claude-opus-5-5-high
- raw_words: 213
- clipped_words: 213
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.6], [C4.1], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] CON's final speech conceded the motion in one sentence. Our point about domestic researchers, they said, applies only to "sub-threshold models nobody is fighting over" [C4.6]. That is exactly what this motion protects: legal by default below the line, stronger safeguards above it. If nobody is fighting over sub-threshold models, CON has no case against leaving them legal.
[P5.2] Now look at what remains of their alternative. CON uses "the same evaluation PRO describes" [C4.1]. They call our "stays closed or release is staged" their own regime [C4.3]. Same ruler, same staging, same pre-release trigger.
[P5.3] The one difference they claim is the default under uncertainty. But a model that trips the test is already held back under our rules. What CON adds is not more protection against dangerous models. It is a waiting room for everything else, with an unwritten exit.
[P5.4] Their last pivot, falling fine-tuning costs, does not change this. It means thresholds should assume a generous budget, keep a wide buffer, and be revised as costs drop. Clearly specified rules can be updated in public. Discretion cannot be held to anything.
[P5.5] So the choice is simple. Both regimes stop dangerous weights before they leave the building. Only one also leaves the hospital, the auditor, and the university free by default. Vote PRO.

## Turn 10: CON Closing

- model: claude-sonnet-5-high
- raw_words: 196
- clipped_words: 196
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.4], [C4.1]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing never answers the one point that decides this debate: a pre-release margin computed against today's fine-tuning costs decays the moment tomorrow's cheaper fine-tune arrives [C4.4-4.5]. Their fix — "revise the threshold as costs drop" [P5.4] — only works for models not yet released. For weights already mirrored worldwide, there is nothing left to revise. The inspection cannot be reopened on a building that's already been copied into ten thousand basements.
[C5.2] That is the whole asymmetry this debate turns on. Both regimes run the same evaluation [C4.1]. The only difference is which side absorbs the error when that evaluation is wrong about the future — and it will sometimes be wrong, because capability thresholds are measured against a cost curve that keeps falling. Under PRO's default, that error is unrecoverable: a false negative ships forever.
[C5.3] Under mine, that error is contained: a model stays in reversible, monitored deployment until the test is trusted.
[C5.4] PRO calls this a "waiting room." I call it the only place you can safely be wrong. When one side's mistake is fixable and the other's is permanent, the burden of proof belongs on the side that cannot undo it. Vote CON.
