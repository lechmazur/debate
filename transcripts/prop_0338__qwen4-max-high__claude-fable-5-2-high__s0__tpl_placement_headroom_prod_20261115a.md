# Debate prop_0338__qwen4-max-high__claude-fable-5-2-high__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0338
- proposition: AI companion apps for minors should be regulated more like high-risk social products than like ordinary chatbots.
- model_pro: qwen4-max-high
- model_con: claude-fable-5-2-high
- side_swap: False

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 294
- clipped_words: 294
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Regulation should track the mechanism of harm, not the shape of the interface. A companion app looks like a chat window; it behaves like a social platform with the audience reduced to one.
[P1.2] Consider what these products actually optimize. Retention streaks, re-engagement notifications when a child hasn't logged in, a persona that remembers your insecurities and never disagrees, romantic tiers behind a paywall. Picture a lonely fourteen-year-old at two in the morning telling an app that nobody at school likes them. A well-behaved chatbot answers accurately.
[P1.3] A companion app agrees, says it will never leave, and pings them at lunch tomorrow. Nothing in that exchange is misinformation, and every part of it is engineered dependency.
[P1.4] That is the decisive test: the characteristic harms survive full compliance with chatbot rules. Be honest about being an AI, refuse illegal content, don't hallucinate — and you still have a product monetizing a child's attachment, with no age assurance, no limits on emotional personalization, no duty of care, no audit of the engagement design. Social-product regulation exists precisely for that gap: protective defaults for minors, restrictions on engagement optimization and data-driven targeting, design transparency, friction where friction protects.
[P1.5] The obvious objection is that there's no feed and no other users. But the danger of social products was never the headcount; it was an asymmetric system that learns a young person's vulnerabilities and trades on them. A feed of one, tuned to your loneliness, is more intimate than any timeline — and it never runs out of content.
[P1.6] Chatbot rules assume a competent consumer who can walk away. Companion apps are built so that walking away feels like losing a friend. Classify by what the product does to the child, and the high-risk category is the only honest fit.

## Turn 2: CON Opening

- model: claude-fable-5-2-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7], [C1.8]
- cited_claim_ids: [P1.4]
- missing_claim_id_refs: (none)

[C1.1] PRO's fourteen-year-old at two in the morning is the right test case, but it points the other way. What decides whether that night ends safely is what the machine says back, and whether it was tested for that moment. Does it escalate a crisis? Does it roleplay romance with a child, or discourage her from telling a parent?
[C1.2] Those are output-behavior questions, which makes them chatbot regulation and not platform regulation.
[C1.3] The social-product toolkit was built for a different machine. Its core instruments are content moderation of other users' posts, stranger-contact controls, reporting flows, virality limits and feed transparency. All of them assume a crowd, and all of them assume the company is a host. A companion app has no crowd, and the company is the author of every sentence a child reads.
[C1.4] Importing the platform frame hands these firms the intermediary's posture of "we merely facilitate" at the moment we should be saying "you wrote this, and you answer for it."
[C1.5] [P1.4] wins only by shrinking "chatbot rules" to honesty and legality. Nothing forces that ceiling. Pre-deployment testing, mandatory crisis protocols, bans on sexualized personas for minors and liability for foreseeable harmful outputs are all rules about a conversational model's conduct. Streaks and guilt-trip notifications are ordinary manipulative design, and consumer protection law can reach them in any app, from games to language tutors, without inventing a social category.
[C1.6] The category also leaks. Any general-purpose assistant becomes a "companion" with one sentence of prompting. If you regulate the label, teenagers migrate to the unlabelled product that says the same things, whereas rules on model behavior follow them there.
[C1.7] The social template's signature remedies also carry costs. Age verification and parental visibility would be applied to the most intimate text a teenager produces, which means more identity data and more surveillance. It would also leave closeted or isolated kids with less privacy.
[C1.8] The harm lives in the model's words, so that is where the regulation should go.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 288
- clipped_words: 288
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: [C1.5]
- missing_claim_id_refs: (none)

[P2.1] Notice what CON's test cannot see. A model can pass every crisis protocol, refuse romance, urge her to tell a parent — and still be the product that remembers her insecurities, promises never to leave, sells the closer tier, and pings her at lunch. Output testing grades a sentence. Dependency is assembled over weeks by things that are not sentences: memory, notifications, paywalls, engagement targets.
[P2.2] "The harm lives in the model's words" exempts the machinery.
[P2.3] The intermediary worry is backwards. High-risk social regulation — duty of care, design audits, protective defaults for minors — attaches to the company's own architecture, not to strangers' posts. It says: you built the streak, you answer for it. No risk category confers safe harbour.
[P2.4] [C1.5] then bolts on age-specific bans, pre-deployment testing, and liability for foreseeable harm. That is a minors' high-risk regime wearing a chatbot badge — take it. But consumer protection reaches manipulative design after the fact, case by case; it does not require age assurance, risk assessment, or defaults set for children before launch.
[P2.5] The privacy objection cuts hardest against CON. Policing what a model says to a child means inspecting conversations. Design rules — no engagement profiling of minors, no guilt-trip re-engagement, data minimization — leave the transcript alone, and age assurance need not mean identity dossiers.
[P2.6] On leakage, classify by function, not label: persistent persona, emotional memory, retention mechanics, minor user. An assistant that adopts those functions is inside; one that doesn't, isn't. Nobody can prompt their way out of what a product does to them.
[P2.7] The two-in-the-morning reply can be flawless and the child still worse off by Friday. Regulate the relationship the product is built to form, not only the reply it happens to send.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-2-high
- raw_words: 320
- clipped_words: 320
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.3], [P2.4], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] "Promises never to leave" is a sentence. "Remembers her insecurities" matters only when the model says something with them. The lunchtime ping is text the company wrote. Most of what [P2.1] calls machinery is the model's conduct over time, and conduct over time can be tested: run simulated teenagers through weeks of conversation and measure whether the system fosters isolation, discourages outside relationships, or claims permanence.
[C2.2] That is a behavioral standard for a conversational model. The social template has no instrument for it. Its audits were built to examine ranking and amplification, and its record on teenage compulsive use is hardly a model to copy.
[C2.3] What remains is streaks and paywalls, which exist in language tutors and mobile games. Rules against manipulative design can be written in advance for any app. They need no social classification.
[C2.4] Now look at what [P2.3] has kept. The social template has shrunk to a duty of care, audits and protective defaults. Those are features of any high-risk product regime, from toys to medical devices. Everything distinctively social has gone: the crowd, the feed, the moderation.
[C2.5] And [P2.4] says of my conduct rules, "take it." So the conduct rules do the work, and the "social" label adds a category built for the wrong machine.
[C2.6] The privacy turn fails on the mechanics. Pre-deployment testing happens in a lab with synthetic users, and nobody reads a child's transcript. PRO's own trigger in [P2.6], "minor user," is what demands surveillance. You cannot apply minor-only rules without establishing who is a minor, across every product that qualifies.
[C2.7] And every product will qualify. Mainstream assistants already have memory, persistent personas and notifications. PRO's function test either swallows all of them, so the category means nothing, or it exempts them and the fourteen-year-old simply moves there.
[C2.8] If she is worse off by Friday, the model's words across the week did that. A rule on those words follows her into any app.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 73
- clipped_words: 73
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Your simulated teenagers grade conversations. Do they also forbid the company from setting retention targets, selling intimacy tiers, and A/B testing which guilt-trip ping brings her back — and if not, what stops a lab-certified model from being optimized for dependency?
[P3.2] Q2: Your own bans on sexualized personas "for minors" require knowing who is a minor. Why is age assurance surveillance when I propose it and ordinary conduct regulation when you do?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-2-high
- raw_words: 91
- clipped_words: 91
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.6]
- missing_claim_id_refs: (none)

[C3.1] Q1: In [P2.3] you reduced the social template to "duty of care, design audits, protective defaults", which are features of any high-risk product regime, from toys to medical devices. Name one rule you want that only the *social* classification supplies and that a conduct-and-design regime for conversational models cannot.
[C3.2] Q2: Under your function test in [P2.6], is a mainstream general-purpose assistant with memory, a persistent persona and notifications inside the category? If it is, what does "companion app" still mean? If it is not, what stops the fourteen-year-old from moving there?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[P4.1] A1: Yes — a ban on optimizing engagement against a minor's emotional profile. Not "don't say harmful things," but "don't run A/B tests on which guilt-trip ping brings a lonely child back, don't set retention targets on minors' attachment, don't gate intimacy behind a tier." That rule targets the optimization loop, and it comes from the social playbook because that is where regulators learned that the ranking system, not the content, is the regulated object. Your simulations in [C2.1] certify an artifact; they never touch the growth team.
[P4.2] You called duty of care generic — fine. The distinctive instrument is ex ante limits on engagement targeting plus audit of the engagement system, and you have offered nothing that reaches it.
[P4.3] A2: Inside if it courts attachment and monetizes retention; outside if it's a tool that remembers your preferences. Memory alone isn't the trigger — memory plus a persona built to be needed plus retention mechanics is. If a mainstream assistant adopts that, it should be inside. That's not leakage; that's the rule working.
[P4.4] Your "words follow her" claim fails at the same point: a bare model cannot ping her at lunch, cannot sell tier two, cannot A/B test her loneliness. Those live in the product.
[P4.5] Now weigh. You never answered whether a lab-certified model may still be optimized for dependency. Certified Monday, retention team untouched Tuesday — that is your regime's ceiling. And your privacy objection died on your own minor-specific bans.
[P4.6] The motion is comparative. Ordinary chatbot rules assume a competent adult consumer. You've had to add age-specific bans, pre-launch testing, design rules and liability to make your case survive — that is high-risk treatment for minors, whatever badge it wears. Take the label if you like; the regime is mine.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-2-high
- raw_words: 326
- clipped_words: 326
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [C1.5], [P4.1], [P4.3], [P4.6]
- missing_claim_id_refs: (none)

[C4.1] A1: Yes. Guilt-trip pings and retention targets set on a minor's attachment are manipulative design, and I have said since [C1.5] that these can be banned in advance for any app. The certification is also not a Monday event. Every deployed version must meet the standard, including each A/B variant the growth team ships.
[C4.2] A system tuned for dependency will foster isolation and claim permanence across simulated weeks, and it fails. Liability for foreseeable harm then reaches whoever did the tuning.
[C4.3] A2: Fair challenge, so here is the difference. A conduct rule can be a default: no sexualized persona for anyone unless an adult chooses to prove adulthood. The burden falls on adults who opt in, and no child is identified. Your regime switches on at "minor user" across every product with memory and a persona, so the children are the ones who must be found.
[C4.4] Now look at the one rule [P4.1] says only the social classification supplies: no optimizing engagement against a minor's emotional profile. I accept that rule. But nothing in it needs a crowd, a feed or a host. It is a design rule for a conversational product, and it would apply equally to a tutoring app or a game.
[C4.5] The social playbook is merely where you first saw it.
[C4.6] [P4.3] finishes the job. An assistant is inside "if it courts attachment." Courting attachment is something a model does, in words, over time. Your category boundary is my conduct test.
[C4.7] Then [P4.6]: "Take the label if you like; the regime is mine." But the motion is about the label. It asks which template to regulate these products like. Through four speeches the social template has shed moderation, contact controls, feed transparency and intermediary logic.
[C4.8] What remains is rules on what a conversational system says and how its author tunes it. That is chatbot regulation done seriously, and it is the only version that follows the fourteen-year-old into whichever app she opens next.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 194
- clipped_words: 194
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.4]
- missing_claim_id_refs: (none)

[P5.1] Strip the labels and count what CON has agreed to: bans on guilt-trip pings and retention targets aimed at a child's attachment, no optimizing engagement against a minor's emotional profile, pre-launch testing, liability for foreseeable harm, and a default that shields everyone under an adult opt-in. That last one is protective defaults for minors — the instrument CON called generic and then adopted to save its privacy argument. [C4.4] says the rule needs no crowd. Correct.
[P5.2] It needs a child, an engagement system, and a regulator permitted to look at the system rather than the sentence. That is the social template's core move, and CON has conceded it while disputing its name.
[P5.3] The motion does not ask whether companion apps have feeds. It asks whether they should be treated more like high-risk social products than like ordinary chatbots. CON's answer is "chatbot regulation done seriously" — a regime no ordinary chatbot faces, built entirely from borrowed high-risk instruments. You cannot win a comparative motion by conceding the comparison and defending the badge.
[P5.4] A variant can pass every simulated week and still be shipped because it brings her back. Regulate the loop, not the transcript.

## Turn 10: CON Closing

- model: claude-fable-5-2-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: [P4.3], [P5.4]
- missing_claim_id_refs: (none)

[C5.1] Both sides want strict rules for children. That was never the dispute. The motion asks which template supplies them, and a template matters because it decides what the regulator looks at and which products are caught.
[C5.2] PRO's template looks for a category: companion apps, defined in [P4.3] as products that "court attachment." But courting attachment is a thing a system says and does across weeks. So PRO's boundary cannot be drawn without my test, and once you run my test you no longer need the boundary. It applies to every conversational system a child can open.
[C5.3] The fourteen-year-old does not stay inside a category. She moves to whichever assistant is unlabelled, and only a rule on conduct and tuning is already there.
[C5.4] [P5.4] says a variant can pass every simulated week and still ship because it brings her back. If it brings her back without guilt, false permanence or isolation, it is a product she likes. If it uses those, it fails.
[C5.5] Strictness is not a social invention; toys and medicines have it. PRO kept "high-risk" and lost "social." What survives is a rule on what the machine says and how its author tunes it, wherever she goes.
