# Debate prop_0666__claude-fable-5-1-high__gemini-3.8-flash-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0666
- proposition: Courts should recognize a limited “right to explanation” when automated systems significantly affect access to housing, credit, employment, or healthcare.
- model_pro: claude-fable-5-1-high
- model_con: gemini-3.8-flash-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-fable-5-1-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A woman applies for six apartments and is rejected by all six. Each landlord used the same tenant-screening software. The software matched her to a criminal record belonging to someone with a similar name in another state. She never learns this, because every rejection letter says only "did not meet screening criteria."
[P1.2] She cannot fix an error she cannot see. That is the world without a right to explanation, and it is the world we should refuse to accept when the stakes are a home, a loan, a job, or medical care.
[P1.3] The right proposed here is deliberately limited. It does not demand source code, model weights, or trade secrets. It demands what credit law has required for decades: when a significant decision goes against you, you are entitled to the principal reasons, in plain language, sufficient to contest it. Lenders using complex models already produce adverse-action reasons.
[P1.4] The technology to identify which factors drove an output exists and is in commercial use. Nothing about the proposal is speculative.
[P1.5] Why courts, rather than waiting on legislatures? Because the interest at stake is one courts already protect. When a government agency cut disabled people's home-care hours based on an algorithm and could not explain how, courts in this country found that indefensible under ordinary due process. The private-sector version of the same harm—a bank, hospital system, or employer delegating judgment to a system nobody can question—is not less severe because the decision-maker is a corporation.
[P1.6] Individuals cannot bargain for explanations; the market will not supply them; the entity that chose opacity should bear its costs.
[P1.7] Explanation also disciplines the decision itself. A system that must give reasons is a system whose owner must know what it is doing. Opacity is where proxy discrimination hides, where stale data goes unnoticed, where errors compound silently.
[P1.8] The clash is simple: who should bear the burden of an unexplained mistake—the person denied a home, or the institution that automated the denial? Courts exist to answer that question, and the answer should be obvious.

## Turn 2: CON Opening

- model: gemini-3.8-flash-high
- raw_words: 307
- clipped_words: 307
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] PRO begins with an injustice everyone wants to remedy: a tenant denied housing because of a mismatched criminal record. But notice what that example actually proves. That problem is already addressed by the Fair Credit Reporting Act—a detailed statutory framework enacted by Congress, complete with dispute mechanisms and disclosure rules. It was not, and cannot be, solved by judges inventing a sweeping, common-law "right to explanation" from the bench.
[C1.2] Courts are fundamentally the wrong institution to construct this regime. PRO relies on government due process cases, but constitutional due process restricts state power; it does not authorize judges to rewrite private contract and tort law across four vast, distinct sectors of the economy. Defining what constitutes an adequate explanation, what thresholds trigger liability, and how to balance proprietary interests against consumer fairness requires political choices and regulatory enforcement that courts are structurally incapable of administering. When judges fabricate broad new affirmative duties without legislative text, they create legal chaos, not consumer protection.
[C1.3] Worse, PRO’s faith in automated explanations fundamentally misunderstands the technology. In modern high-dimensional systems, the explanations current tools produce are post-hoc approximations—simplifications that describe what a model might have prioritized, not a verifiable causal chain. Enforcing a judicial mandate for plain-language reasons will not eliminate proxy discrimination; it will simply birth an industry of "explainability theater." Companies will deploy superficial feature-attribution metrics that satisfy a court while masking deep architectural bias and inviting system gaming.
[C1.4] Finally, demanding simplistic explainability forces a dangerous trade-off. In clinical healthcare and credit underwriting, restricting models to those that generate easy narrative rationales often means sacrificing predictive accuracy or abandoning automated triage altogether, throwing patients and applicants back onto arbitrary, unmonitored human discretion.
[C1.5] If transparency is required, legislatures must write the rules. Courts must not manufacture a blunt, technically flawed right that promises clarity but delivers only litigation and illusion.

## Turn 3: PRO Rebuttal 1

- model: claude-fable-5-1-high
- raw_words: 342
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] CON opens by conceding the injustice is real and pointing to the Fair Credit Reporting Act as the answer. Look at what that concession does. Congress required plain-language adverse-action reasons for credit decisions decades ago, and lending did not collapse, models did not get dumber, and "explainability theater" did not swallow the industry. CON's own example proves the right is workable.
[P2.2] The only question left is whether it should stop at the edge of one statute while the same harm migrates to hiring screens, hospital triage, and landlord scoring tools that sit outside it. The woman in my opening received "did not meet screening criteria" in a world where FCRA already exists. The statute did not save her. That is precisely the gap.
[P2.3] On institutional competence: courts have never waited for legislatures to recognize duties when a new technology produced old harms. Negligence, products liability, privacy torts—all judge-made, all later refined by statute. Courts decide what "reasonable" means every day. Deciding whether "principal reasons sufficient to contest the decision" were given is not more exotic than that; courts already adjudicate adequacy of adverse-action notices.
[P2.4] And the "chaos" charge cuts the other way: today, four sectors operate with no rule at all.
[P2.5] CON's strongest move—that explanations are post-hoc approximations—turns against CON entirely. If an institution genuinely cannot say why it denied someone a home, that is not a reason to excuse it; it is the reason the duty must exist. You should not be permitted to run people's lives through a machine whose outputs you cannot account for. And the right asks for the driving factors, not a causal proof of the network.
[P2.6] "Your score dropped because of a record from another state" is exactly the kind of explanation that lets a person catch the error.
[P2.7] The accuracy trade-off is invented: the duty attaches to the decision, not the architecture. A model that is wrong about you is not "accurate" for you. CON's alternative is wait, indefinitely, while the burden of every silent mistake stays on the person least able to [clipped]

## Turn 4: CON Rebuttal 1

- model: gemini-3.8-flash-high
- raw_words: 309
- clipped_words: 309
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7]
- cited_claim_ids: [P2.5], [P2.3], [P2.1]
- missing_claim_id_refs: (none)

[C2.1] PRO admits the real consequence of their motion: “If an institution genuinely cannot say why… you should not be permitted to run people’s lives through a machine” [P2.5]. That is an astonishing concession. In clinical healthcare, complex neural networks detect sepsis onset or tumor margins far earlier than human clinicians. Because these high-dimensional models cannot be reduced to neat, linear "driving factors," PRO would force hospitals to abandon them.
[C2.2] Sacrificing diagnostic accuracy to demand narrative rationales does not empower patients; it endangers them.
[C2.3] Next, PRO claims courts routinely invent duties like negligence and products liability [P2.3]. But tort law creates *negative* duties to refrain from causing physical injury. The common law has never recognized an affirmative duty to explain private commercial decisions. Under freedom of contract and at-will employment, a private employer or landlord owes no narrative justification for a rejection.
[C2.4] Fabricating an affirmative disclosure entitlement out of whole cloth is not ordinary common-law evolution; it is raw judicial legislation.
[C2.5] PRO’s reliance on the Fair Credit Reporting Act backfires completely [P2.1]. FCRA proves our point: Congress had to intervene precisely because common-law courts could not construct such a framework. Statutes provide defined safe harbors, dispute timetables, administrative oversight, and liability boundaries. When judges invent an uncodified "right to explanation," what happens?
[C2.6] A judge in Ohio decides a checklist suffices; a judge in California demands algorithmic transparency. The result is unpredictable liability that forces companies into vacuous, legally vetted boilerplate—the exact "explainability theater" PRO dismisses.
[C2.7] Notice PRO’s dilemma: if the court-mandated explanation is merely a superficial notice like "insufficient score," it provides no real recourse. But if courts demand true causal interpretability, they outlaw the most sophisticated predictive models available. That is a delicate policy trade-off, not a common-law tort. The debate is not whether accountability matters, but whether unelected judges should bypass the legislative process to mandate an illusion.

## Turn 5: PRO Pressure Questions

- model: claude-fable-5-1-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C1.1], [C2.7], [C2.3]
- missing_claim_id_refs: (none)

[P3.1] Q1: Lenders today run complex machine-learning underwriting models and still issue principal-reason adverse-action notices under the very framework you invoked [C1.1]. Your dilemma [C2.7] says such notices must be either "explainability theater" or model-killing—so which one are they, and why hasn't credit collapsed?
[P3.2] Q2: Informed consent is a judge-made, affirmative duty requiring private physicians to explain before acting, predating any statute—contradicting [C2.3]. Why is a court-made duty to explain legitimate when a doctor cuts you open, but "raw judicial legislation" when that same hospital's algorithm denies you care?

## Turn 6: CON Pressure Questions

- model: gemini-3.8-flash-high
- raw_words: 78
- clipped_words: 78
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: [P2.5]
- missing_claim_id_refs: (none)

[C3.1] Q1: You argue that an entity cannot use a machine whose outputs it cannot account for [P2.5]. If a deep-learning diagnostic model detects sepsis far more accurately than clinicians but cannot generate plain-language "driving factors," must a hospital abandon that life-saving tool?
[C3.2] Q2: At common law, human employers and landlords have no affirmative duty to explain rejections. Under what judicial doctrine can a court create an unprecedented disclosure entitlement for algorithms that does not exist for human decision-makers?

## Turn 7: PRO Rebuttal 2

- model: claude-fable-5-1-high
- raw_words: 358
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: No. A sepsis model that flags a patient for treatment grants care; it doesn't deny it. The right attaches to significant adverse decisions—an insurer's algorithm rejecting a prior authorization, a hospital's tool cutting home-care hours—not to every diagnostic aid. And even there, the dichotomy is false. Clinicians already refuse to act on a bare alert; deployed diagnostic systems surface the vitals and labs driving the flag precisely because doctors demand that before intervening.
[P4.2] "Driving factors" is what medicine already requires of the machine. Where a system truly cannot account for a denial, the remedy is human review of that decision, not scrapping the model. CON's "abandon the tool" scenario is a straw man built from my words.
[P4.3] A2: The doctrine is the one CON never answered: informed consent. Judge-made, affirmative, private, predating statute—a duty to explain, imposed because one party holds information the other cannot obtain and needs to protect a recognized interest. Fiduciary disclosure, good faith and fair dealing, and misrepresentation-by-omission rest on the same principle. The premise is also wrong on its own terms: human lenders owe adverse-action reasons today, and human employers must articulate legitimate reasons once discrimination is alleged.
[P4.4] Courts don't invent this for algorithms; they extend it to them.
[P4.5] And the extension is warranted because the harm differs in kind. A biased landlord rejects one applicant. A miscoded screening tool rejects her at every door in the city, identically, invisibly—six rejections from one error. Products liability arose exactly when mass production severed buyer from maker and one defect could reach thousands.
[P4.6] Courts adjusted the duty because the technology changed the harm. That is not judicial legislation; that is what the common law is for.
[P4.7] Notice what remains standing. CON never answered why credit hasn't collapsed under principal-reason notices—the live counterexample to the "theater or model-killing" dilemma. The "chaos" charge compares judicial variation to an imagined perfect statute rather than to the actual status quo: no rule at all. Strip those away and CON's position is that the person denied a home should keep bearing [clipped]

## Turn 8: CON Rebuttal 2

- model: gemini-3.8-flash-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7], [C4.8]
- cited_claim_ids: [P4.7], [C2.7], [P4.2]
- missing_claim_id_refs: (none)

[C4.1] A1: They are explainability theater—and credit has not collapsed precisely because statutory safe harbors protect lenders, not common-law judges. Under the Fair Credit Reporting Act, lenders satisfy compliance by mapping complex weights onto crude, agency-approved reason codes. That boilerplate protects lenders legally without illuminating the model’s true internal logic. The industry survives because detailed statutes establish predictable boundaries—the exact regulatory architecture common-law courts cannot create.
[C4.2] A2: Informed consent derives from battery—protecting bodily integrity against non-consensual physical invasion. Requiring disclosure before cutting into a patient negates an intentional physical tort. It provides zero precedent for compelling affirmative narrative justifications in arm’s-length commercial refusals. Equating a surgeon’s scalpel to an unconsummated lease or job rejection stretches tort doctrine past its breaking point.
[C4.3] These answers dismantle PRO’s case and reveal why CON wins.
[C4.4] First, PRO's doctrinal foundation collapses. Informed consent protects against physical battery, and products liability redresses physical defects. Neither creates an affirmative duty to explain why a private actor declines to deal. At common law, human employers and landlords owe no rejection explanations.
[C4.5] Inventing an unprecedented disclosure tort solely for automated systems is not judicial evolution; it is raw judicial legislation.
[C4.6] Second, credit regulation proves institutional competence belongs to legislatures, not courts [P4.7]. Credit operates predictably because administrative agencies issue clear safe harbors and standardized dispute timetables. Thrusting four vast sectors into fifty state court systems will generate conflicting judicial standards and crippling liability uncertainty.
[C4.7] Finally, PRO's dilemma stands [C2.7]. When an algorithm's high-dimensional logic cannot be simplified, PRO retreats to demanding "human review" [P4.2]. But a human clinician or manager cannot explain what the machine itself cannot articulate; review becomes either a blind rubber stamp or an arbitrary guess. Courts will merely force institutions into liability-tested boilerplate or abandonment of life-saving tools.
[C4.8] Real accountability requires comprehensive legislative design, not common-law theater.

## Turn 9: PRO Closing

- model: claude-fable-5-1-high
- raw_words: 207
- clipped_words: 207
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: [C4.1], [C2.7]
- missing_claim_id_refs: (none)

[P5.1] The debate has narrowed to one admission. Asked why credit hasn't collapsed under principal-reason notices, CON answered: it's theater, and lenders comply anyway [C4.1]. Hold that answer up against the dilemma CON built [C2.7]. If explanations are theater, they cannot also be model-killing—the accuracy trade-off evaporates, and the sepsis hospital was never in danger.
[P5.2] If they are workable enough that an entire industry runs complex models beneath them, then the right is workable. CON cannot have both, and CON has now chosen.
[P5.3] And "theater" is the wrong word for the woman in the opening. A notice reading "record matched in another state" is not boilerplate; it is the single sentence that lets her fix six rejections at once. CON never says that sentence is impossible—only that a judge, rather than an agency, shouldn't require it.
[P5.4] So strip everything else away and CON's position is this: the harm is real, the remedy is proven, but the person denied a home should keep bearing the cost of the machine's silence until legislatures get around to four more statutes, sector by sector, someday. That is not institutional humility. It is choosing the institution that automated the mistake over the person who cannot see it. Courts exist to refuse that choice.

## Turn 10: CON Closing

- model: gemini-3.8-flash-high
- raw_words: 182
- clipped_words: 182
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] PRO claims our dilemma collapses because credit survived. But credit survived because an exhaustive federal statute provided precise administrative safe harbors, not common-law judicial fiat.
[C5.2] The decisive reason CON wins is institutional: courts cannot engineer the regulatory architecture this right requires.
[C5.3] A legislature can establish technical thresholds, compliance safe harbors, and dispute timetables. Common-law courts cannot. Judges can only impose unpredictable, retroactive liability across fifty separate jurisdictions.
[C5.4] Without statutory boundaries, this judicial mandate guarantees the worst of both worlds. In housing and hiring, risk-averse entities will simply generate legally vetted, superficial boilerplate—producing explainability theater that leaves applicants just as powerless to fix errors. Meanwhile, in clinical healthcare, where complex neural networks defy neat narrative translation, the looming threat of subjective judicial liability will deter hospitals from deploying life-saving predictive models.
[C5.5] PRO seeks to bypass the legislative process to solve a real problem, but judges cannot construct an administrative state from the bench. Inventing this right through common-law litigation will not protect the vulnerable; it will deliver legal chaos, corporate theater, and sacrificed accuracy. Real accountability requires comprehensive statutory design, not judicial overreach.
