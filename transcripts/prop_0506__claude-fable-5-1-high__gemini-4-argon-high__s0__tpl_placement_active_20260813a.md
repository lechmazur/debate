# Debate prop_0506__claude-fable-5-1-high__gemini-4-argon-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0506
- proposition: Platforms should face civil liability for AI-enabled impersonation fraud when they ignore repeated verified reports of synthetic scams.
- model_pro: claude-fable-5-1-high
- model_con: gemini-4-argon-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 365
- clipped_words: 340
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9], [P1.10]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] Picture a retiree who sees a video of a trusted television finance presenter urging viewers to put money into a "guaranteed" investment. The face is right, the voice is right, the platform ran it as a paid advertisement. It is a deepfake. She wires her savings and never sees them again.
[P1.2] Meanwhile, the presenter's team has reported that exact ad, and dozens of near-identical variants, for weeks. The platform kept collecting the ad revenue.
[P1.3] That is the only situation this motion addresses. Not every scam. Not every deepfake. Not fraud the platform could not have known about.
[P1.4] Liability attaches only when four conditions stack up: the fraud is AI-enabled impersonation, the reports are verified, the reports are repeated, and the platform ignores them. This is the narrowest, most conservative liability standard imaginable. It asks platforms to do one thing: act on what they already know.
[P1.5] Everywhere else in law, knowledge plus inaction creates a duty. A landlord warned repeatedly about a broken lock is liable when a tenant is robbed. A bank told three times that an account is being used for fraud cannot shrug when the fourth transfer goes through. The principle is simple: the party with the cheapest ability to stop the harm, who has been put on notice, should bear the cost of refusing to stop it.
[P1.6] Platforms are that party. They control the upload pipeline, the ad-approval process, and the hashing tools that can block a flagged video from being reposted under a new account.
[P1.7] Today, ignoring reports costs a platform nothing, while scam ads pay like any other ads. That arithmetic is the problem. Civil liability does not demand perfection; it simply makes the warned-and-did-nothing choice expensive, which is exactly when companies suddenly discover that enforcement is feasible.
[P1.8] Expect objections about chilling speech, floods of lawsuits, and stifled innovation. None survive the motion's wording. Verified, repeated, ignored. Legitimate content is untouched, and AI development is untouched.
[P1.9] The only thing threatened is the business model of profiting from fraud you were warned about.
[P1.10] So the question [clipped]

## Turn 2: CON Opening

- model: gemini-4-argon-high
- raw_words: 305
- clipped_words: 305
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6]
- cited_claim_ids: [P1.6], [P1.2], [P1.8], [P1.1], [P1.7]
- missing_claim_id_refs: (none)

[C1.1] Picturing a platform lazily leaving up a single reported video when it could just block it with "hashing tools" [P1.6] applies a 2010 technology to a generative AI problem.
[C1.2] Cryptographic hashes only catch identical or near-static files. Today’s synthetic scammers use automated scripts to tweak pixels, alter audio frequencies, and regenerate video across thousands of burner accounts simultaneously. Notice how [P1.2] quietly expands the standard to include "dozens of near-identical variants." Removing one reported URL takes seconds; stopping infinite AI-generated variants requires aggressive, platform-wide biometric surveillance.
[C1.3] If a scammer spins up a slightly altered variant and a victim loses their savings, a plaintiff's lawyer will tell a jury the platform "ignored repeated reports" of the scam. To avoid that catastrophic liability, platforms cannot rely on surgical takedowns; they must deploy blunt, hair-trigger filters that block anything resembling a flagged public figure.
[C1.4] Nor does the word "verified" save legitimate speech [P1.8]. Before a trial, what is a "verified report"? It is simply a formal notice from an authenticated person or their lawyer. When an executive or politician wants to bury a biting AI parody or satirical fundraising clip, their lawyers can simply submit repeated, "verified" complaints alleging impersonation fraud.
[C1.5] Faced with uncapped civil liability if they guess wrong, no platform will pay lawyers to litigate whether a video is fraud or satire. They will instantly delete it. You hand the world's most powerful figures a heckler's veto backed by tort law.
[C1.6] Finally, look at the scenario in [P1.1]: a paid advertisement and a bank wire. If the evil is platforms collecting ad revenue from scammers [P1.7], consumer regulators can already penalize deceptive ad networks, and banks police the actual financial transfer. Creating a sweeping private civil tort turns open communication platforms into deep-pocket insurers for global criminals, crushing smaller competitors that cannot afford massive compliance armies.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 357
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9]
- cited_claim_ids: [C1.2], [P1.1], [C1.6]
- missing_claim_id_refs: (none)

[P2.1] Notice what CON conceded in passing: "Removing one reported URL takes seconds" [C1.2]. That sentence ends the debate on its own terms. The retiree in [P1.1] did not lose her savings to an unreported variant; she saw the exact ad that had been flagged for weeks. The motion punishes ignoring reports, not failing to anticipate them.
[P2.2] If a scammer spins up a fresh variant nobody has flagged, no report was ignored and no liability attaches. CON's "infinite variants" nightmare is an argument against a motion nobody proposed.
[P2.3] And the variants point collapses further for paid ads. Scam ads are not anonymous uploads; they come with an advertiser account, a billing identity, and a payment method. Once a platform is told that account is running deepfake fraud, it does not need "biometric surveillance" [C1.2]. It needs to close the account and block the card.
[P2.4] Platforms already do exactly this for advertisers who violate far pettier policies.
[P2.5] On the heckler's veto: CON quietly deletes the word "fraud" from the motion. A satirical clip or parody fundraiser is not impersonation fraud unless it deceives people into handing over money while posing as a real person. "Verified" means the impersonation has been confirmed, not that a lawyer typed an angry email. Notice-and-takedown regimes for copyright have existed for decades, parody survived them, and courts routinely penalize bad-faith notices.
[P2.6] CON offers a hypothetical about politicians burying satire against a documented pattern of retirees losing life savings. Weigh the concrete against the speculative.
[P2.7] CON's fallback is that regulators and banks should handle it [C1.6]. That is a concession that the harm is real and someone must act, paired with a request to pick the slowest and most distant actors. Regulators fine years later. Banks never see the deepfake; they see a wire.
[P2.8] Only the platform sees the video, the account, and the report, and can stop it in the seconds CON admits it takes.
[P2.9] Smaller platforms receive fewer reports. A duty to act on what you are told scales exactly with size. Nothing in this motion [clipped]

## Turn 4: CON Rebuttal 1

- model: gemini-4-argon-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6]
- cited_claim_ids: [P2.1], [P2.2], [P1.2], [C1.2], [P2.3], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] [P2.1] and [P2.2] walk straight into a fatal dilemma. In [P1.2], the case rested on platforms ignoring a reported ad and "dozens of near-identical variants." Now, to escape the surveillance problem, [P2.2] retreats: if a scammer spins up a fresh variant nobody has flagged, "no liability attaches."
[C2.2] Follow the logic of that concession. If a platform satisfies its legal duty simply by deleting the exact reported URL, which takes seconds [C1.2], then the retiree still loses her life savings. Why? Because synthetic scammers do not rely on one static link; they use automated scripts to launch thousands of disposable URLs and accounts.
[C2.3] If liability only covers exact flagged URLs, this policy saves nobody. Conversely, because the motion actually says "reports of synthetic scams," not URLs, a plaintiff's lawyer will argue that once the platform knew about the underlying scam, letting a tweaked variant slip through was ignoring the report. To avoid that liability, platforms must deploy aggressive biometric filters. The proposal is either completely toothless against automated fraud or a mandate for dragnet censorship.
[C2.4] Recognizing this, [P2.3] pretends the motion only applies to paid ads where a platform can just "block the card." Read the proposition: it is not limited to advertisements. It covers all organic uploads, comments, and messages where no billing identity exists. Even in advertising, transnational crime rings rotate through thousands of stolen and virtual payment cards.
[C2.5] Nor does the copyright analogy in [P2.5] rescue legitimate speech. Copyright takedown regimes are notorious for automated over-removal of fair use. Now multiply that chilling effect: a platform faces uncapped liability for a victim's entire life savings. [P2.5] claims "verified" means the fraud is "confirmed."
[C2.6] Confirmed by whom? No judge evaluates a report when it arrives, only an accuser's lawyer. When a politician or CEO repeatedly reports a satirical AI clip attached to a grassroots fundraising link as "impersonation fraud," no platform will risk a jury trial to defend a user's joke. They will simply erase the speech.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 91
- clipped_words: 91
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C1.2], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: You conceded removing a reported deepfake ad "takes seconds" [C1.2]. When a platform leaves that exact verified, repeatedly flagged ad running for weeks, keeps the revenue, and a retiree is defrauded by that very ad, should she recover nothing from the platform — yes or no?
[P3.2] Q2: Your "toothless or dragnet" dilemma [C2.3] only works if liability reaches unflagged variants. If a platform removes every reported item and closes the reported advertiser account, what word in "ignore repeated verified reports" could a court stretch to find it still ignored anything?

## Turn 6: CON Pressure Questions

- model: gemini-4-argon-high
- raw_words: 87
- clipped_words: 87
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.2], [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: Under your rule that no liability attaches to unflagged variants [P2.2], if a platform deletes a reported link in seconds and a scammer's bot immediately posts a tweaked copy from a new burner account that defrauds a retiree, doesn't that victim still get zero recovery?
[C3.2] Q2: You claim "verified" means "the impersonation has been confirmed" [P2.5]—confirmed by whom before a court rules, and why would any platform risk uncapped damages guessing whether a political parody with a fundraising link is fraud when deleting it is free?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 343
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Yes, and that is the right answer. Liability tracks fault. A platform that acts on every report is not at fault for a variant nobody flagged, exactly as a bank that freezes a reported account is not at fault for a brand-new mule account.
[P4.2] But notice what this question concedes: CON's objection is now that the motion does not save *enough* victims. That is an argument for a broader rule, not for the status quo, where every victim, flagged ad or not, gets zero. And CON's bot scenario is weaker than it sounds. The tweaked copy still carries the same face, the same voice, the same payment link, so it is reportable as the same scam, and a platform already on notice can block that link and that payout destination without any biometrics.
[P4.3] Once ignoring reports costs money, platforms build those cheap tools. Today, they have no reason to.
[P4.4] A2: Verified by the ordinary identity check platforms already run: the impersonated person, or their authenticated team, confirms the video is not them and shows the money-collection link. Note the motion penalizes platforms that *ignore* reports, not platforms that review them and guess wrong. A platform that looks at a flagged clip, judges it obvious parody, and documents why has not ignored anything; that is a complete defense. And deleting is not "free" for platforms; engagement and ad revenue are precisely why the retiree's ad ran for weeks.
[P4.5] The heckler's veto requires a platform that is terrified of liability yet somehow indifferent to its own revenue.
[P4.6] Now weigh what each side answered. CON was asked directly whether the retiree defrauded by the *exact* ad, flagged repeatedly, left running, revenue kept, should recover nothing. CON answered by pointing at a different victim. That silence is the whole debate.
[P4.7] CON argues the motion is simultaneously too narrow to help anyone and too broad to be safe. Both cannot be true. Read as written, it is narrow, and it reaches precisely one party: the platform that was told, could act in seconds, and [clipped]

## Turn 8: CON Rebuttal 2

- model: gemini-4-argon-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6]
- cited_claim_ids: [P4.1], [P4.2], [P2.3], [P4.4], [P4.5]
- missing_claim_id_refs: (none)

[C4.1] A1: Yes, in private tort court—because consumer regulators can already disgorge illicit ad revenue to compensate victims without creating a speech-chilling private right of action. Moreover, [P4.1] just conceded that once scammers use basic automation to repost tweaked copies from new accounts, the retiree gets zero recovery under this motion anyway.
[C4.2] A2: The words right after it: "of synthetic scams." Watch [P4.1] and [P4.2] collide. [P4.1] promises no liability for unflagged variants. Literally one paragraph later, [P4.2] insists a tweaked copy with the same face and voice is "the same scam," meaning a platform "already on notice" must block it!
[C4.3] That admission proves the dilemma. Because scammers rotate payment links and funnel victims to off-platform apps, catching variants of "the same scam" requires the exact biometric dragnet [P2.3] denied.
[C4.4] Worse, [P4.4] completely unravels the motion’s liability standard. It admits "verified" just means the target claims the video is fake and points to a money link—which describes every satirical political fundraiser. To rescue parody, [P4.4] declares that if a platform reviews a flagged clip, judges it permissible, and documents why, it "has not ignored anything; that is a complete defense."
[C4.5] Follow the devastating logic of that concession. If reviewing a report and declining to delete the video means the platform did not "ignore" it, then any platform whose moderator reviews a scam ad, clicks "no violation," and leaves it up has a complete legal defense.
[C4.6] The case collapses into self-contradiction. If "ignoring" merely means failing to review, platforms escape liability with a rubber-stamp click. If "ignoring" means failing to remove what a jury later deems a scam, no platform will risk million-dollar damages to keep up a user's political parody that earns fractions of a penny in engagement [P4.5]. Either this rule does nothing to stop fraud, or it mandates automated censorship.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 212
- clipped_words: 212
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: [C4.1], [C4.6]
- missing_claim_id_refs: (none)

[P5.1] Strip away the variants, the bots, and the satire, and one answer decides this debate. Asked whether the retiree defrauded by the exact ad, flagged repeatedly, left running for weeks while the platform kept the money, should recover nothing from that platform, CON finally said: "Yes, in private tort court" [C4.1]. That is the status quo CON is defending — a platform warned, able to act in seconds, choosing revenue, and owing the victim nothing.
[P5.2] CON's offered substitute is regulators who might someday disgorge revenue. The retiree does not get a disgorgement order. She gets a press release years later, if anything.
[P5.3] CON's closing dilemma — "rubber-stamp or dragnet" [C4.6] — is the same false choice every negligence standard already resolves. A landlord who glances at a broken lock and says "looks fine" is not immune; a landlord who checks it in good faith and reasonably concludes it works is. Courts distinguish sham review from real review every day. "Ignore" is not exotic; it means failing to act in good faith on what you were told.
[P5.4] Between rubber-stamping and biometric dragnets sits ordinary reasonable care, which is all this motion demands.
[P5.5] Platforms act when inaction costs them. Today it costs nothing. That arithmetic, not any dilemma, is why the retiree lost everything.

## Turn 10: CON Closing

- model: gemini-4-argon-high
- raw_words: 200
- clipped_words: 200
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.1], [P4.1], [P4.2], [P5.3]
- missing_claim_id_refs: (none)

[C5.1] The case for this motion rests on a fatal bait-and-switch. [P5.1] asks you to decide this debate on a single static ad left up for weeks. Yet when asked what happens the moment a platform deletes that reported link in seconds, and a scammer’s bot immediately reposts a tweaked copy that defrauds the exact same retiree, [P4.1] gave away the game: she still gets zero recovery.
[C5.2] Synthetic scammers do not rely on one static link. Under [P4.1]’s narrow rule, the platform deletes the flagged URL, the bot reposts it, the retiree loses her savings, and she still recovers nothing.
[C5.3] To escape that futility, [P4.2] and [P5.3] expand the duty to blocking "the same scam" and proving to a jury that moderators exercised "good faith" and "reasonable care." A landlord checks one physical lock [P5.3]; platforms process millions of uploads. When a politician or CEO repeatedly flags a satirical AI fundraiser as "fraud," no platform will pay trial lawyers or risk uncapped damages to prove a moderator's "good faith" over a user's joke. They will automatically erase accused speech and deploy biometric dragnets to block variants.
[C5.4] Reject a rule that leaves fraud victims empty-handed while pricing free expression out of existence.
