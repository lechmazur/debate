# Debate prop_0495__qwen4-max-high__claude-fable-5-1-high__s1__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0495
- proposition: Open-source maintainers of critical infrastructure libraries should receive public funding comparable to other essential-infrastructure workers rather than be expected to maintain them for free.
- model_pro: qwen4-max-high
- model_con: claude-fable-5-1-high
- side_swap: True

## Turn 1: PRO Opening

- model: qwen4-max-high
- raw_words: 283
- clipped_words: 283
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A hospital's scheduling system, a bank's payment gateway, and a water utility's control software all sit on the same handful of parsing, encryption, and logging libraries, maintained by people nobody pays. We fund bridge inspectors, air traffic controllers, and water treatment operators because dependence creates obligation. The motion asks only that we apply that standard consistently: when a component is load-bearing for society, its upkeep is work, and work of that consequence deserves public support at infrastructure grade, not gratitude.
[P1.2] This is a textbook public good. Anyone can copy the code; no one can be charged at the door. So the benefits spread across trillion-dollar industries while the costs land on one person's evenings. Heartbleed exposed a foundational encryption library that enormous enterprises relied on while its maintenance ran on donations.
[P1.3] Log4Shell showed the same shape in logging. That is not a series of accidents; it is the predictable output of an incentive structure that rewards consumption and punishes care.
[P1.4] The failure mode is not only bugs. It is abandonment, and it is capture. An exhausted, unpaid maintainer is exactly the target for someone offering to help — the pattern behind the xz backdoor attempt. Paid maintainers with colleagues, review, and a successor are harder to burn out and harder to buy.
[P1.5] Expect the reply that nobody forced them, and that companies already sponsor. Permission to publish is not an obligation to sustain the world's plumbing forever. Sponsorship follows famous projects, not the boring transitive dependency nobody notices until it breaks. Comparable funding means stable salaries and audited stewardship, not identical pay scales.
[P1.6] Free software should stay free to use. That has never required the people holding it up to work for nothing.

## Turn 2: CON Opening

- model: claude-fable-5-1-high
- raw_words: 308
- clipped_words: 308
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Dependence creates obligation — agreed. The question is whose. When a bank's payment gateway rides on an unpaid parser, the bank is the beneficiary, not the taxpayer in a trailer park. Public salaries for maintainers would be the largest corporate subsidy in software: trillion-dollar companies get their supply chain hardened on the public dime, and the one lever that actually changes their behavior — making them pay for what they consume — is thrown away.
[C1.2] Infrastructure funding works for bridges because the public owns the bridge. Nobody owns OpenSSL, and its heaviest users are the richest firms on earth.
[C1.3] The bridge-inspector comparison cuts the other way. We pay inspectors publicly because we license them, direct them, audit them, and fire them. Comparable funding means comparable control: a ministry deciding which of millions of packages count as critical, which maintainer gets the salary, what gets merged, whether a project may be deprecated. The "boring transitive dependency nobody notices" is precisely the one no funding committee will notice either.
[C1.4] Public money follows visibility just as sponsorship does, with a bureaucracy attached.
[C1.5] Now look at the examples honestly. OpenSSL received a flood of money after Heartbleed; the fix that mattered was consumers finally auditing what they shipped. Log4j lived inside a well-established foundation. The xz attempt succeeded against a lone maintainer and was caught by a downstream engineer noticing a performance anomaly — review by users, not a paycheck.
[C1.6] Each case says the failure is consumers running code they never examined. A public salary invites the worst moral hazard imaginable: "it's government-funded, so it's safe," while the engineers who should be reading their dependencies stop.
[C1.7] The real choice is not payroll versus charity. It is beneficiary-pays — consortia, procurement rules, liability for shipping unvetted code — versus socializing corporate costs and nationalizing a commons that works because nobody is its boss.

## Turn 3: PRO Rebuttal 1

- model: qwen4-max-high
- raw_words: 281
- clipped_words: 281
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Beneficiary-pays and public funding are not rivals. We fund airports through landing fees and water systems through ratepayers; the money is public, the beneficiaries pay, and the operator still draws a stable salary. Levy the firms that ship these libraries and you have exactly this motion. "The largest corporate subsidy in software" is a claim about tax design, not an argument against paying maintainers.
[P2.2] Ownership is the wrong test. Taxpayers fund basic research whose results nobody owns and everyone uses, because otherwise it does not get done. And the public is a direct beneficiary: the hospital, the water utility, the tax-filing portal.
[P2.3] Comparable funding has never meant comparable command. We pay researchers, public broadcasters, and university chairs without a ministry deciding what they publish. Fellowships, audits, dependency-graph triage. Note the irony: a committee can read a dependency graph; a sponsorship market needs a project with a marketing team.
[P2.4] The boring transitive dependency is invisible to sponsors by construction and legible to an auditor by design.
[P2.5] Now the examples. xz was caught because one engineer happened to chase a half-second slowdown. That is luck, not a safety system, and it is offered as the mechanism. Log4j sat inside a respected foundation whose maintainers were still volunteers; a foundation is not a payroll. OpenSSL's flood of money arrived after the catastrophe, which argues for stable funding, not against it.
[P2.6] Moral hazard cuts backwards. A bridge inspector's salary does not stop drivers watching the road, and no engineer treats a grant as a warranty. Meanwhile liability for shipping unvetted code makes downstream users buy insurance and lawyers; it pays nobody to review the parser. CON's plan bills the passengers and leaves the bridge unpaid.

## Turn 4: CON Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 313
- clipped_words: 313
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.1], [P2.3], [P2.5], [P2.6]
- missing_claim_id_refs: (none)

[C2.1] Notice what just happened to the funding source. "Levy the firms that ship these libraries" [P2.1] is beneficiary-pays, conceded. So the only live question is whether that money passes through a state allocator before reaching a maintainer. Landing fees go to the runway the airline actually lands on.
[C2.2] A pooled software levy goes wherever a committee decides, and that is where the comparison collapses.
[C2.3] PRO says a committee can read a dependency graph [P2.3]. A dependency graph of modern software has millions of nodes. Deciding which are "critical" is not reading; it is ranking, and ranking by a public body is political. Basic research is the proof, not the refutation: grants flow to labs that write good proposals, and the famous institution wins the fellowship.
[C2.4] The maintainer of a boring parser does not write proposals; she writes parsers. Public money will reach her exactly as reliably as sponsorship did, with an application form in between.
[C2.5] The ownership point matters because of accountability. A publicly salaried maintainer who merges a breaking change into a package that hospitals run will be asked who approved it. "Comparable to infrastructure workers" means the answer is a supervisor. PRO wants the salary without the supervisor, which is a fellowship with a nicer name, not infrastructure employment.
[C2.6] On xz, PRO calls downstream review luck [P2.5]. But the attacker courted the maintainer directly; a paycheck changes nothing about who answers that email. What caught it was a consumer looking at the code he ran. That is the system worth paying for.
[C2.7] Which is why liability does pay someone to review the parser [P2.6]: the firm shipping it hires that reviewer, for the exact dependency it uses, not for a committee's list. The passengers are not billed. The airline is. The alternative lets the richest users of this code hand the duty of care to a ministry and call it generosity.

## Turn 5: PRO Pressure Questions

- model: qwen4-max-high
- raw_words: 78
- clipped_words: 78
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: Under your liability regime, the bank hires someone to read the parser. Who pays the person who patches it, reviews pull requests, and trains a successor? Name the mechanism in your plan that funds upstream maintenance rather than downstream auditing.
[P3.2] Q2: You say a paycheck changes nothing about who answers the attacker's email. The xz attacker deliberately chose a lone maintainer pleading for help. Does funding a team with co-maintainers change who is alone at that inbox?

## Turn 6: CON Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 90
- clipped_words: 90
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.3], [P2.1], [P2.4]
- missing_claim_id_refs: (none)

[C3.1] Q1: You say comparable funding never means comparable command [P2.3]. If a publicly salaried maintainer merges a breaking change that takes hospitals offline, or simply stops answering, who removes her? If nobody can, how is this comparable to a bridge inspector rather than tenure with a nicer name?
[C3.2] Q2: Your levy [P2.1] pools money, so some body must rank millions of packages. Who ranks them, and what stops that ranking from rewarding the famous project with a proposal writer — the exact sponsorship failure [P2.4] you promise public funding cures?

## Turn 7: PRO Rebuttal 2

- model: qwen4-max-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Whoever pays can stop paying. Fund the role through a contract with response obligations and renewal; if she merges recklessly or goes silent, the funding moves to a co-maintainer or a fork. The license stays free, so removal from payroll never means removal of the code. Compare that to today: an abandoned parser cannot be fired, cannot be compelled, cannot even be reached.
[P4.2] Hospitals currently depend on someone with no obligation to answer at all. Funding creates the first handle of accountability anyone has ever had over that dependency. CON demands a supervisor for a job that presently has no employer.
[P4.3] A2: Not a committee reading millions of nodes — a rule. Eligibility from measurable dependence: what appears in the dependency graphs of hospital systems, utilities, payment rails and government services, weighted by exposure and patch history. Thresholds, not proposals; renewal for continued maintenance, not competitive grant prose. Imperfect, yes.
[P4.4] But CON's liability regime also has to rank millions of packages — it just does it retroactively, in court, after the outage, defining "unvetted" case by case. An auditable published rule beats a popularity contest and beats a lawsuit.
[P4.5] Notice the question CON never answered. Under liability, the bank hires a reviewer. Who pays the person who writes the patch? Reading the parser is not fixing it.
[P4.6] The reviewer files an issue into an unpaid inbox and bills the airline for the reading. That is CON's whole machine: paid auditors of unmaintained code. And xz: the attacker shopped for a maintainer who was alone and asking for help. A funded team with colleagues is not that target.
[P4.7] Every mechanism CON offers works only if somebody upstream is still working for free. Ours pays them, and can hold them to it.

## Turn 8: CON Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 324
- clipped_words: 324
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.1], [P4.3]
- missing_claim_id_refs: (none)

[C4.1] A1: Liability does. A bank that can be sued for shipping an unpatched parser does not stop at hiring a reader; the reader's report is worthless until someone fixes the bug, so the cheapest way to discharge the risk is to fund the person who writes the patch. That is why the firms whose products ride on the Linux kernel employ its maintainers directly rather than auditing it from outside. The mechanism is the firm's own balance sheet: it pays the maintainer of the exact dependency it ships, through employment, support contracts, or a consortium, because an unfixed parser is now its liability.
[C4.2] No ministry list, no application form, no pooled levy deciding whose parser matters.
[C4.3] A2: A colleague changes who is alone at that inbox — but look at who the xz attacker was. He arrived as the helpful co-maintainer. A public program that recruits second maintainers for lonely projects is hiring Jia Tan at scale, with a budget. The colleagues worth having are engineers whose employer ships the code and vouches for their identity.
[C4.4] Liability produces those; a salary line produces a vacancy.
[C4.5] Now notice what the motion has become. [P4.1] offers a contract with response obligations and renewal, revocable, movable to a fork. [P4.3] offers eligibility thresholds and renewal for continued work. That is procurement, not infrastructure employment.
[C4.6] A bridge inspector is not a renewable grantee. The proposition as written promises maintainers pay comparable to essential-infrastructure workers; its defense now promises a contract that can be cancelled — which is beneficiary-pays with the state as middleman and a committee's threshold as gatekeeper.
[C4.7] And that threshold depends on "dependency graphs of hospital systems" [P4.3]. Hospitals do not publish those. The only thing that makes a firm disclose what it ships is being answerable for it. So even PRO's ranking rule runs on liability.
[C4.8] Every road here leads to the beneficiary paying; the motion merely inserts a treasury between them and the maintainer.

## Turn 9: PRO Closing

- model: qwen4-max-high
- raw_words: 194
- clipped_words: 194
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] CON's last line concedes the principle: the beneficiary must pay the person who writes the patch. Good. Then the only question left is whether any per-firm mechanism can reach the code that every firm uses and no firm owns.
[P5.2] It cannot. Liability attaches to a product. The kernel has corporate employers because it is famous and attributable; the parser three layers beneath a hospital's scheduler is nobody's product line. Each bank audits its own slice, files its own issue, and none of them buys the maintainer a colleague, a successor, or a Tuesday afternoon.
[P5.3] That is the gap CON never closed: a hundred paid readers, one unpaid inbox.
[P5.4] Pooling is not a treasury inserted between payer and plumber; pooling is what infrastructure funding is. Ratepayers, landing fees, levies: we already spread upkeep across everyone who depends, including the public hospital and the tax portal, which ship no product for liability to bite.
[P5.5] And CON wants a supervisor before a salary while defending a status quo with no employer, no obligation, no one to fire. Our contract creates the first handle of accountability that dependency has ever had. Pay the plumber, not just the inspector.

## Turn 10: CON Closing

- model: claude-fable-5-1-high
- raw_words: 197
- clipped_words: 197
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [P5.3]
- missing_claim_id_refs: (none)

[C5.1] The decisive fact is what PRO's case became under pressure. It opened promising maintainers the standing of air traffic controllers. It closed defending a revocable contract, awarded by a threshold rule, fed by a levy on firms, and triggered by dependency data that only exists if firms are made answerable for what they ship. Strip the labels and every working part is beneficiary-pays.
[C5.2] The single thing the motion adds is a gatekeeper ranking millions of packages — with the same eyesight as the sponsorship market PRO says it cures. "Hospital dependency graphs" are not published; famous projects are.
[C5.3] "A hundred paid readers, one unpaid inbox" [P5.3] is the case's last stand, and it misreads liability. A reader's report is a liability until the bug is fixed, so the hundredth firm does not file another issue; it pays for the fix, because the fix is the only thing that discharges the risk. Firms did not employ kernel maintainers out of fame; they did it because their products broke when the kernel did.
[C5.4] PRO wants the hospital's parser to matter to someone. Liability makes it matter to the bank shipping it. The motion makes it matter to a form.
