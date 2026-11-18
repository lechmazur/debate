# Debate prop_0666__gemini-4-carbon-high__mimo-v2.6-pro-thinking__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0666
- proposition: Courts should recognize a limited “right to explanation” when automated systems significantly affect access to housing, credit, employment, or healthcare.
- model_pro: gemini-4-carbon-high
- model_con: mimo-v2.6-pro-thinking
- side_swap: False

## Turn 1: PRO Opening

- model: gemini-4-carbon-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] When an automated system denies someone an apartment, a loan, a job, or medical care, opacity acts as an absolute shield against legal accountability. Existing laws already prohibit discrimination, fraud, and arbitrary denials across housing, credit, employment, and healthcare. Yet substantive rights become dead letters if victims cannot discover why they were rejected. When institutions delegate high-stakes gatekeeping to inscrutable software, courts must recognize a limited right to explanation so foundational legal protections do not vanish behind a digital curtain.
[P1.2] Picture a qualified nurse filtered out by hiring software that penalized a disability-related career gap, or a renter blacklisted because a screening algorithm matched their name to a stranger’s eviction record. Faced with a blank rejection, victims hit a catch-22: they cannot fix simple data errors, nor can they plead specific facts of bias to survive early dismissal in court. Recognizing a limited explanation right is therefore a core judicial function, not legislative overreach. Drawing on procedural due process, common-law duties of good faith, and the remedial logic of civil-rights statutes, courts have always adapted legal doctrines so technological shifts do not nullify existing rights while legislatures lag behind.
[P1.3] Crucially, this right is narrow and workable. It applies only when automated systems significantly affect four pillars of human livelihood, leaving ordinary commercial algorithms untouched. Nor must companies surrender proprietary source code, trade secrets, or every weight in a complex model. It requires only intelligible, decision-level reasons: the principal factors driving an adverse outcome, or what must change to alter the result, much like adverse-action notices long used in credit lending.
[P1.4] If an institution claims its machine cannot even state why it denied someone shelter or healthcare, courts should not excuse that opacity; they should refuse to let unaccountable guesswork govern human lives.

## Turn 2: CON Opening

- model: mimo-v2.6-pro-thinking
- raw_words: 340
- clipped_words: 340
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposition sounds humane, but it asks courts to invent a right that is technically hollow, institutionally misplaced, and likely to entrench the very opacity it targets.
[C1.2] First, the wrong branch. Existing law already forbids discrimination, deception, and arbitrary denials in all four domains. Where process is due, legislatures have specified it — adverse-action notices in credit, reasons for denial in insurance and benefits, agency enforcement under civil-rights statutes. Courts are being asked to manufacture a free-floating entitlement with no statutory text, no defined content, and no limiting principle beyond "significantly affect," a phrase that will generate a decade of boundary litigation before anyone gets an explanation.
[C1.3] If a new duty is warranted, an elected legislature can define its triggers, its format, its exceptions, and its penalties. Judicial improvisation instead produces fifty inconsistent standards and retroactive liability for systems built in reliance on the laws as written.
[C1.4] Second, and worse for claimants: a court-ordered "explanation" from a complex model is not truth. Feature attributions and counterfactual summaries are modeling conventions, not causal accounts; the same outcome can support several mutually inconsistent stories. What we would enshrine is a right to a plausible narrative — and institutions will supply the cheapest one. A polished adverse-action notice citing "debt-to-income ratio" satisfies the new duty while the true driver, a proxy for race or disability buried in correlated features, remains invisible.
[C1.5] The right creates a compliance ritual that immunizes decisions: "we explained ourselves," case closed.
[C1.6] Third, existing tools are better tailored. A claimant who suspects bias can plead the facts she has, and courts can order targeted discovery — including source code, training data, and validation records — once a case survives initial screening. Auditing, disparate-impact doctrine, agency supervision, and vendor-liability rules all reach the machinery without gifting every applicant a document that flatters the defendant. Letting discovery do the work keeps the disclosure calibrated to litigation risk rather than handing institutions a scripted, self-serving pre-litigation defense.
[C1.7] A right that sounds like accountability while delivering exculpation is worse than no right at all.

## Turn 3: PRO Rebuttal 1

- model: gemini-4-carbon-high
- raw_words: 292
- clipped_words: 292
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: [C1.6], [C1.5], [C1.2], [C1.4], [C1.3]
- missing_claim_id_refs: (none)

[P2.1] Start with the proposed alternative: discovery of source code and training data. By its own terms, discovery happens only "once a case survives initial screening" [C1.6]. That concession proves why silence is fatal. When an algorithm silently denies prior authorization for medical care or filters out a job applicant, the victim has no facts showing why.
[P2.2] Under modern pleading standards, bare suspicion gets dismissed before discovery ever begins. Worse, when a rejection stems from a corrupted file or misread record, telling families to litigate just to spot a data mistake is no remedy.
[P2.3] Nor does a limited explanation immunize defendants or mean "case closed" [C1.5]. Notice the contradiction between [C1.2], which praises statutory adverse-action notices in credit and insurance as proof existing law works, and [C1.4], which condemns those very notices as exculpatory shams. Both cannot be true. Explaining a decision is a threshold disclosure, never a safe harbor from discrimination law.
[P2.4] Requiring consistent disclosure of principal factors traps bad actors either way: if a lender blames debt-to-income ratio [C1.4] when finances are strong, that falsifiable claim supplies the pretext evidence needed to survive screening and unlock deep auditing; if the notice instead cites a career gap or neighborhood score, it exposes the suspect proxy rather than hiding it.
[P2.5] Meanwhile, honest disclosures let applicants fix simple input errors immediately. And if a model is genuinely so inscrutable that every summary is arbitrary fiction [C1.4], courts should not let unaccountable guesswork ration shelter or healthcare.
[P2.6] Finally, judicial action brings neither chaos nor unfair surprise [C1.3]. Courts apply thresholds like "significantly affect" [C1.2] daily and craft prospective remedies without retroactive penalties. The real institutional failure is letting gatekeepers hide life-altering denials inside black boxes today while telling victims to wait years for fifty legislatures.

## Turn 4: CON Rebuttal 1

- model: mimo-v2.6-pro-thinking
- raw_words: 288
- clipped_words: 288
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5]
- cited_claim_ids: [C1.4], [P2.5]
- missing_claim_id_refs: (none)

[C2.1] The contradiction charge collapses once both claims are read precisely. Existing statutory notices work because legislatures paired them with substantive rules — defined triggers, prescribed formats, audit duties, limits on safe-harbor effect. My point in [C1.4] is that transplanting that form into a free-floating judicial right, stripped of that statutory scaffolding, reproduces the ritual while dropping the safeguards. A notice written to satisfy a judge is not the object a regulator can demand the underlying model to support.
[C2.2] PRO also overstates the pleading trap. A qualified nurse rejected by an automated screen can plead those facts; discrimination plaintiffs have never had to prove the mechanism in their complaint. Where legislatures judged the discovery gap real, they built agency complaint routes, mandatory adverse-action notices in credit, and audit obligations — targeted fixes, not a new freestanding right. Blank rejections are a compliance failure for those tools to cure, not proof doctrine is silent.
[C2.3] None of them requires a plaintiff to first unlock the black box.
[C2.4] The "falsifiable claim" trap cuts against PRO. If a lender can cite debt-to-income with impunity, the explanation is not evidence; it is the defendant's opening statement handed over before litigation, and the claimant must now disprove a story the defendant chose. Institutions will learn to write "we weighed many factors" — unfalsifiable, fully compliant, useless. The duty rewards fluency, not honesty.
[C2.5] PRO's ultimatum concedes my case: if a model cannot render an honest account of its decision [P2.5], the answer is to bar that use or hold the deployer liable for the outcome — not order a summary that will be fiction. A right to a plausible story is worse than a right to nothing, because it dresses opacity in the language of accountability.

## Turn 5: PRO Pressure Questions

- model: gemini-4-carbon-high
- raw_words: 83
- clipped_words: 83
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.2], [P2.2], [C1.6], [C2.1], [C2.4]
- missing_claim_id_refs: (none)

[P3.1] Q1: When an automated hiring screen or gatekeeper falls outside existing notice statutes, how can someone given a blank rejection [C2.2] distinguish a corrupted file [P2.2] or hidden proxy from a lawful denial without filing a blind lawsuit just to reach discovery [C1.6]?
[P3.2] Q2: If statutory notices "work" when backed by audits requiring "the underlying model to support" them [C2.1], doesn't that concede faithful explanations are technically feasible, and why would any court accept "we weighed many factors" [C2.4] or grant safe-harbor immunity?

## Turn 6: CON Pressure Questions

- model: mimo-v2.6-pro-thinking
- raw_words: 70
- clipped_words: 70
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [C2.1]
- missing_claim_id_refs: (none)

[C3.1] Q1: If a defendant complies by citing "debt-to-income" or "we weighed many factors," what judicial standard lets a court reject that explanation as inadequate without ordering the model internals you insist the right never requires?
[C3.2] Q2: You concede legislatures build notice regimes with defined triggers, formats, and audit backing [C2.1]; what principled limit stops "significantly affect" from producing fifty improvised judicial standards instead of leaving that design to elected bodies?

## Turn 7: PRO Rebuttal 2

- model: gemini-4-carbon-high
- raw_words: 295
- clipped_words: 295
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5]
- cited_claim_ids: [C3.1], [C1.6], [C3.2], [C2.1], [C1.4], [C2.2], [P2.2], [C2.5]
- missing_claim_id_refs: (none)

[P4.1] A1: Courts reject "we weighed many factors" [C3.1] on its face, without touching model internals, using basic specificity standards familiar from privilege logs and administrative review: a compliant notice must state the principal inputs driving rejection or what change would alter the outcome. Conversely, citing "debt-to-income" satisfies initial disclosure without surrendering source code, while locking the institution into a testable factual claim. When an applicant’s actual record contradicts that story, the mismatch supplies concrete pretext to survive dismissal and unlock targeted discovery [C1.6], where audits test model fidelity.
[P4.2] Routine notices protect trade secrets; contested falsehoods trigger deep scrutiny.
[P4.3] A2: "Significantly affect" [C3.2] tracks established adverse-action doctrine: material denials, terminations, or severe access barriers in housing, credit, employment, and healthcare, excluding minor commercial sorting like ad placement. Courts apply materiality thresholds daily, and a judicial floor invites rather than blocks statutory codification, preventing a remedial vacuum while fifty legislatures deliberate.
[P4.4] Together, these answers dismantle the case for silence. Admitting that statutory credit notices "work" when backed by rules requiring "the underlying model to support" them [C2.1] abandons the claim that algorithmic explanations are inherently sham narratives [C1.4]. Faithful decision-level reasons are technically feasible, and courts already enforce anti-discrimination rules, sanctions, and discovery audits that punish notices unsupported by the underlying model, never granting safe-harbor immunity.
[P4.5] Meanwhile, relying solely on existing statutes leaves glaring black holes across automated hiring, tenant screening, and medical authorization, where blank rejections remain routine. Telling rejected nurses, renters, or patients to simply sue on bare qualifications [C2.2] ignores reality: families should not need blind lawsuits just to catch a corrupted file [P2.2], nor can victims spot hidden proxies behind total silence. Even barring unexplainable models [C2.5] is impossible if gatekeepers never have to explain themselves; without threshold reasons, unaccountable guesswork hides forever.

## Turn 8: CON Rebuttal 2

- model: mimo-v2.6-pro-thinking
- raw_words: 292
- clipped_words: 292
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5]
- cited_claim_ids: [P4.4], [C3.1], [P4.1], [C3.2]
- missing_claim_id_refs: (none)

[C4.1] A1: The blank-rejection problem is real, but an explanation right is the wrong instrument. A notice saying "debt-to-income" or "we weighed many factors" reveals nothing about a corrupted file or a hidden proxy; it reveals the story the deployer prefers. Catching data errors requires checking the input record, which correction rights and regulator-facing audit duties can mandate, while spotting proxies requires the model scrutiny only discovery or agency supervision provides. Where legislatures saw this gap in credit, they wrote mandatory notices plus verification duties.
[C4.2] Extending that pattern to hiring and tenant screening is a job for elected bodies, not for courts inventing a free-floating duty.
[C4.3] A2: PRO's concession is decisive. Faithful explanations are feasible only where "the underlying model" must support the notice [P4.4] — that is, where a legislature has defined triggers, formats, verification, and penalties. A judicial right supplies none of that scaffolding, so a court faces two choices: accept the plausible narrative, which becomes the de facto safe harbor PRO denies; or test the notice against model internals [C3.1], which abandons the promise that this right never requires source code. Either way the "limited" right collapses.
[C4.4] PRO's specificity standards borrowed from privilege logs [P4.1] do not escape this. Judging what counts as "principal factors" for every model class across four industries is precisely [C3.2]'s improvisation problem — which is why legislatures codify formats and audits rather than leave standards to case-by-case judgment.
[C4.5] Weighing: PRO needs a single disclosure to be simultaneously cheap and reliable, narrow and enforceable. A summary plausible enough to satisfy a judge is exactly what institutions will game; a duty deep enough to stop gaming is discovery and audit wearing a right's mask. The claimant's real protection stays targeted discovery plus audit-backed statutes courts already enforce.

## Turn 9: PRO Closing

- model: gemini-4-carbon-high
- raw_words: 190
- clipped_words: 190
- claim_ids: [P5.1], [P5.2], [P5.3]
- cited_claim_ids: [C4.1], [C4.5], [C4.2], [C4.3]
- missing_claim_id_refs: (none)

[P5.1] Admitting that the "blank-rejection problem is real" [C4.1] settles the decisive question: no legal protection can function behind total silence. Pointing rejected nurses, tenants, or patients toward "targeted discovery" [C4.5] while waiting for fifty legislatures to act [C4.2] offers an empty remedy. Someone staring at a blank denial cannot tell a lawful decision from a corrupted record or a discriminatory proxy, and therefore cannot plead the concrete facts needed to reach discovery at all.
[P5.2] A limited right to explanation unlocks existing law, and the supposed choice between rubber-stamping sham stories and auditing source code in every decision [C4.3] is a false dilemma. Accountability works sequentially, not all at once [C4.5]. Upfront, requiring specific principal factors, never "we weighed many factors" [C4.1], exposes zero trade secrets while forcing gatekeepers to commit to testable facts. When a notice blames "debt-to-income" [C4.1] despite minimal debt, that contradiction immediately reveals a corrupted file or supplies the pretext evidence that triggers targeted discovery and judicial sanctions against dishonest disclosures.
[P5.3] Courts do not overstep by refusing to let automated opacity nullify existing rights; they ensure the law still governs access to housing, credit, employment, and healthcare.

## Turn 10: CON Closing

- model: mimo-v2.6-pro-thinking
- raw_words: 238
- clipped_words: 206
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4]
- cited_claim_ids: [C3.1], [C2.1]
- missing_claim_id_refs: (none)

[C5.1] PRO's closing proves my point by smuggling in exactly what the motion denies: a notice specific enough to be "testable facts" enforceable by sanctions is not a limited right to explanation — it is a statutory disclosure regime with verification duties, prescribed formats, and penalties, built by judges with none of the democratic design work. The moment a court must decide whether "debt-to-income" is sufficiently principal, or sanction a disclosure as dishonest, it must test the story against the machinery behind it [C3.1].
[C5.2] That is source-code litigation wearing a notice's mask.
[C5.3] And where the notice stays truly limited — one plausible line about principal factors — it becomes the cheapest compliant story, precisely the exculpatory ritual PRO denies exists. PRO needs the disclosure to be shallow enough to protect trade secrets yet deep enough to expose corrupted files and hidden proxies. No instrument is both. Either the duty is thin, and the corrupted file survives inside "we weighed many factors"; or it is thick, and courts are improvising model-fidelity standards across four industries that elected bodies have always specified with audits and correction duties attached [C2.1].
[C5.4] The blank-rejection problem is real — but legislatures have answered it before, with notice statutes plus verification and audit backing. [clipped]
