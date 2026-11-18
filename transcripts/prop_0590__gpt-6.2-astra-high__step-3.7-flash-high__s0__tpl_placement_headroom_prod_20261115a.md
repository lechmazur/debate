# Debate prop_0590__gpt-6.2-astra-high__step-3.7-flash-high__s0__tpl_placement_headroom_prod_20261115a

- topic_id: prop_0590
- proposition: The European Union should make AI “high-risk” rules apply based on where an AI system’s impacts occur, not where the provider is headquartered.
- model_pro: gpt-6.2-astra-high
- model_con: step-3.7-flash-high
- side_swap: False

## Turn 1: PRO Opening

- model: gpt-6.2-astra-high
- raw_words: 286
- clipped_words: 286
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A bank in Lisbon uses an AI system to screen mortgage applications. One supplier is based in Portugal; another, across the Atlantic. Why should switching suppliers change what the bank is entitled to know about the system’s error rates, or whether a loan officer can meaningfully review a rejection? The borrower, the decision and the stakes have not moved.
[P1.2] Neither should the safeguards.
[P1.3] The right test is whether a system is used, or can reasonably be expected to be used, to make decisions with direct, material effects in the EU in a high-risk field. A vendor supplying the Lisbon bank knows where its scores will count before the first application is processed. It can test for foreseeable failures and document limitations before anyone loses out. A foreign lender’s decision does not come under EU rules merely because news of it reaches a European reader.
[P1.4] Headquarters is an especially poor substitute because a provider can change it without making its product any safer. Even if no firm relocates, a buyer could choose the offshore bidder precisely because its price omits testing and documentation that its European rival must fund. That rewards the omission of safeguards rather than better lending technology.
[P1.5] Nor must Europe send inspectors around the world. Require the bank to obtain evidence of compliance before relying on the scores, and empower regulators to halt local use if the supplier cannot substantiate its claims. The bank provides a point of enforcement; it cannot supply technical evidence that only the provider holds. This is a condition on deciding who gets credit in Lisbon, not on who gets credit in Lima.
[P1.6] The boundary should follow the decision that affects the borrower, not the address on the supplier’s letterhead.

## Turn 2: CON Opening

- model: step-3.7-flash-high
- raw_words: 301
- clipped_words: 301
- claim_ids: [C1.1], [C1.2], [C1.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] The proposal inverts the EU AI Act’s core accountability logic and imposes crippling extraterritorial burdens on developers with no meaningful ties to the bloc, all while failing to fix the cross-border deployment gap the PRO claims to address. The current framework already applies full high-risk rules to any provider that places an AI system on the EU market, regardless of headquarters, so a Lisbon bank using a U.S. mortgage-screening tool is already covered. The PRO’s impact-based standard does not solve that problem—it creates new ones.
[C1.2] Consider a small Finnish startup that builds open-source AI tools to detect wildfires from satellite imagery, used by volunteer firefighting groups in Australia and Chile. If a climate research institute in Berlin repurposes that open-source model to analyze European wildfire risk, the startup would suddenly be subject to full EU high-risk compliance requirements, even though it never marketed to the EU, has no EU customers, and received no compensation for the Berlin institute’s use. Open-source AI is reused across borders constantly, and a vague “impacts occur” trigger would ensnare hundreds of small, non-commercial developers who contribute to global public goods, chilling open-source innovation it champions.
[C1.3] The rule also undermines enforcement. High-risk AI obligations are most effectively imposed on the entity that designs, trains, and controls the system’s development: the provider. Shifting to impact-based jurisdiction forces EU regulators to chase down foreign providers with no EU presence for tangential cross-border impacts, while letting local deployers that chose to use the system in a high-risk context off the hook. The PRO suggests regulators can halt local use, but that punishes EU hospitals, banks, and schools for relying on foreign tools, rather than holding foreign providers accountable, and creates perverse incentives for EU entities to avoid all non-EU AI tools entirely, reducing choice and raising costs for European users.

## Turn 3: PRO Rebuttal 1

- model: gpt-6.2-astra-high
- raw_words: 282
- clipped_words: 282
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P2.1] Lisbon is already covered? Good. A supplier does not gain an exemption because its office is abroad. That is a concession against headquarters, not an objection to looking at impacts.
[P2.2] Now suppose a multinational’s overseas office commissions and runs a hiring tool specifically to shortlist applicants for jobs in Madrid. Only the shortlist reaches Spain. The supplier knows which labour market its scores will shape, even though neither the sale nor the processing occurs there. If existing rules cover that case too, their reach supports the proposition.
[P2.3] The wildfire example confuses where the effects occur with whether the use is high-risk and who controls it. Mapping fire risk for research does not itself decide who gets emergency assistance. If the Berlin institute repurposes that model for high-risk emergency dispatch, the institute must answer for the system it creates. Knowing someone in Europe can download code is not reason to expect that particular deployment.
[P2.4] Besides, Finland is in the EU: headquarters is a strange test to invoke on behalf of a developer whose intended users are in Chile.
[P2.5] CON is right that the designer holds evidence a buyer cannot manufacture. That is exactly why the buyer must demand it, not why the designer should be exempt. Requiring the Spanish office to verify the tool’s suitability before acting on the shortlist keeps the employer on the hook and gives even a distant supplier a reason to document its work. A pause for missing evidence applies equally to an unverified domestic tool.
[P2.6] The alternative is not costless choice: it makes an applicant bear the cost of an error nobody had to check. Where a job is denied matters more than where a licence was signed.

## Turn 4: CON Rebuttal 1

- model: step-3.7-flash-high
- raw_words: 290
- clipped_words: 290
- claim_ids: [C2.1], [C2.2], [C2.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C2.1] PRO’s Madrid hiring example relies on a clear contractual tie between the foreign supplier and the EU entity using the tool, but the impact-based rule they propose applies even when no such link exists. If a foreign developer open-sources a hiring tool that is later scraped, modified, and used to screen applicants in Paris without the developer’s knowledge or consent, that developer would be subject to full EU high-risk compliance obligations under PRO’s “impacts occur” standard, with no notice, no chance to adapt the model, and no EU presence to defend against enforcement actions.
[C2.2] That is not accountability—it is arbitrary extraterritorial overreach that punishes developers for uses they never authorized, unlike the current headquarters-based rule that only applies to providers who intentionally place their products on the EU market, a clear, predictable line. PRO tries to narrow the scope by invoking high-risk use cases, but the “reasonably expected to be used” trigger they endorsed earlier is vague and unworkable. A small Finnish team building satellite wildfire detection tools for global public use cannot anticipate every repurposing by research groups worldwide, yet under PRO’s rule, a single Berlin institute’s choice to deploy the tool for emergency dispatch would drag them into full EU compliance, chilling the open-source innovation PRO claims to value.
[C2.3] PRO further argues that requiring EU deployers to verify supplier compliance solves enforcement gaps, but this just shifts all burden to European banks, hospitals, and schools with no power to compel uncooperative foreign providers to share training data or audit trails. The result is not better safeguards: it is EU entities forced to abandon foreign AI tools entirely, reducing choice and raising costs for European users, while small global developers face crippling, unpredictable liability for uses they never controlled.

## Turn 5: PRO Pressure Questions

- model: gpt-6.2-astra-high
- raw_words: 66
- clipped_words: 66
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P3.1] Q1: If a supplier contracts only with an overseas office but knowingly ranks applicants for Madrid jobs, do the safeguards follow the shortlist into Spain or stop where the contract was signed?
[P3.2] Q2: In your Paris example, why would applying high-risk rules to the modified hiring tool require treating the unwitting author, rather than the party that adapted it for use in Paris, as its provider?

## Turn 6: CON Pressure Questions

- model: step-3.7-flash-high
- raw_words: 92
- clipped_words: 92
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: How do you define the vague "reasonably expected to be used" threshold for open-source tools, and what notice would a small Finnish wildfire detection developer get before facing EU compliance costs for an unplanned high-risk repurposing by a Berlin research group?
[C3.2] Q2: If your impact rule applies even when a foreign developer has no EU ties to a Paris deployer modifying their hiring tool, what enforcement mechanism would you use to compel that developer to share audit data or pay penalties, given they have no EU assets or presence to target?

## Turn 7: PRO Rebuttal 2

- model: gpt-6.2-astra-high
- raw_words: 291
- clipped_words: 291
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P4.1] A1: Ask what the developer had reason to know when supplying the tool: was there concrete evidence connecting it to a particular kind of high-risk decision in Europe? Helping Berlin configure the model to prioritise emergency calls would count; publishing a wildfire detector that anyone can download would not. The Finnish team needs no warning because it incurs no new duty for Berlin’s unplanned reuse. Berlin knows the purpose and location before it repurposes the tool, when its own responsibility begins.
[P4.2] A2: I would not compel the unwitting author to produce records or pay a penalty. The Paris modifier must document and test the resulting hiring system; the employer must check that evidence before screening anyone with it. A regulator can inspect the evidence in Paris and halt the use of unsupported rankings. That requires a defensible assessment of the system used, not possession of every record from the original author.
[P4.3] Put Paris beside Madrid. Both employers owe applicants the same safeguard: no shortlist without evidence that the ranking is fit for the job. But the Madrid supplier knows exactly which vacancies it is ranking people for. It cannot shed its share of responsibility by invoicing an overseas office.
[P4.4] The Paris author, who neither chose nor supported the modification, has no comparable responsibility. The impact identifies the decision Europe may regulate; the parties’ conduct identifies who owes which duty.
[P4.5] CON calls intentional EU market placement a headquarters rule. It is not: selling to Lisbon and being based there are different things. And its market test faces a choice in Madrid. Count the shortlist because it determines who gets interviewed in Spain, and impact does the work.
[P4.6] Exempt it, and the employer can shed a safeguard simply by moving the purchase order.

## Turn 8: CON Rebuttal 2

- model: step-3.7-flash-high
- raw_words: 311
- clipped_words: 311
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: Safeguards already attach to a supplier’s intentional placement of a system for EU use, not to the physical location of a shortlist. If a supplier knowingly builds a tool to rank Madrid applicants, it has already placed that system on the EU market under existing rules, so the current framework ensures compliance without PRO’s vague impact trigger. PRO’s framing implies safeguards would stop at the contract, but that is not the status quo CON defends.
[C4.2] A2: CON never argued the unwitting upstream developer of an open-source tool should be treated as the provider of a modified high-risk system deployed in Paris. The existing framework correctly assigns provider status to the entity that intentionally adapts and deploys the tool for EU high-risk use, which is exactly why the headquarters-based rule works: it targets the party with control over the deployment, not random contributors to global public goods. PRO’s Madrid example proves CON’s point: the current rule already captures intentional EU deployment, while PRO’s impact standard would expand liability to unintended cross-border effects no developer could anticipate.
[C4.3] PRO claims their rule only targets parties with EU ties, but their endorsed “reasonably expected to be used” standard is unworkably vague for open-source contributors, as CON’s Finnish wildfire developer example shows. A single unplanned repurposing by a Berlin research group would drag that small developer into full EU compliance, with no notice, no EU presence to defend itself, and no way to adapt to rules it never knew applied. PRO’s only solution is to shift verification burden to EU deployers, but that punishes European banks, hospitals, and schools for relying on foreign tools, rather than holding the actual deployers accountable, and creates perverse incentives to avoid non-EU AI, raising costs and reducing choice for EU users.
[C4.4] The current framework already balances accountability and innovation: PRO’s impact rule upends that balance for no practical gain.

## Turn 9: PRO Closing

- model: gpt-6.2-astra-high
- raw_words: 198
- clipped_words: 198
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P5.1] Take CON at its word: the Madrid shortlist is covered even though the system was bought and run abroad. What makes that answer right? The ranking determines who gets interviewed for jobs in Spain. That is why Europe may set a standard for it.
[P5.2] The supplier knew which jobs it was ranking people for. That is why the supplier must help substantiate the ranking. Its headquarters explains neither conclusion.
[P5.3] Now remove the supplier’s knowledge, as in Paris. That changes what the original author owes; it cannot change what the applicant is owed. Whoever adapted the tool for hiring must test the resulting system, and the employer must have grounds to trust its scores before it drops a name from the list. It takes no fine against an unsuspecting author abroad to insist on that evidence in Paris.
[P5.4] CON calls Madrid market placement and Paris intentional adaptation, but reaches both judgments without asking where anyone is headquartered. If existing rules get those cases right, preserve what makes them right: responsibility can differ with each party’s conduct, but the protection for a person seeking work in Europe must not depend on which side of a border the supplier calls home.

## Turn 10: CON Closing

- model: step-3.7-flash-high
- raw_words: 195
- clipped_words: 195
- claim_ids: [C5.1], [C5.2], [C5.3]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The core fatal flaw in PRO’s impact-based rule is that it imposes arbitrary, unpredictable extraterritorial liability on innocent parties while failing to deliver any meaningful new safeguards for EU users. PRO’s own endorsed “reasonably expected to be used” standard is unworkably vague for open-source contributors: a small Finnish developer building wildfire detection tools for global public use has no way to anticipate a Berlin research group repurposing their code for high-risk emergency dispatch, yet PRO’s rule would drag that developer into full EU compliance for a use they never authorized, controlled, or earned compensation from.
[C5.2] That is not accountability—it is extraterritorial overreach that chills the open-source innovation the EU should support.
[C5.3] The current framework already holds the correct party accountable: the entity that intentionally places or adapts an AI system for EU high-risk use. PRO’s rule does not make EU users safer; it just shifts impossible burdens to European deployers who cannot compel uncooperative foreign providers for audit data, while punishing small global developers for cross-border uses they never controlled. The intuitive appeal of following impacts disappears when it creates unworkable, unfair obligations with no corresponding gain in real protection for people in the EU.
