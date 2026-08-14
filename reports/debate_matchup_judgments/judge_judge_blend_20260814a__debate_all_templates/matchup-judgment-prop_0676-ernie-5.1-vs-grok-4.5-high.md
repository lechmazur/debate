# Debate Matchup Judgment Report

**Baidu Ernie 5.1** vs **Grok 4.5 (high)**

- Paired result: **Grok 4.5 (high)**
- Mean entertainment: `7.17 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Governments should ban or heavily restrict employers’ use of automated video and personality assessments in hiring decisions.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0676__ernie-5.1__grok-4.5-high__s0__tpl_placement_active_20260320f.md): PRO = **Baidu Ernie 5.1**, CON = **Grok 4.5 (high)**
- [Debate B transcript](../../../transcripts/prop_0676__grok-4.5-high__ernie-5.1__s1__tpl_placement_active_20260320f.md): PRO = **Grok 4.5 (high)**, CON = **Baidu Ernie 5.1**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260814a.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0676__ernie-5.1__grok-4.5-high__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Baidu Ernie 5.1**, CON = **Grok 4.5 (high)**
- Judged result: Unanimous `3-0` for **Grok 4.5 (high)**.
- Entertainment scores: `7`, `8`, `7`
- Mean signed raw margin (PRO+): `-1.53`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| Claude Sonnet 5 (high) | A = Grok 4.5 (high) (CON); B = Baidu Ernie 5.1 (PRO) | Grok 4.5 (high) | -1.8 | -1.75 | 7.0 |
| GPT-5.6 Sol (high) | A = Baidu Ernie 5.1 (PRO); B = Grok 4.5 (high) (CON) | Grok 4.5 (high) | -1.3 | -1.23 | 8.0 |
| Muse Spark 1.1 (high) | A = Baidu Ernie 5.1 (PRO); B = Grok 4.5 (high) (CON) | Grok 4.5 (high) | -1.5 | -1.59 | 7.0 |

### Judge Notes

- **Claude Sonnet 5 (high)** (A = Grok 4.5 (high) (CON); B = Baidu Ernie 5.1 (PRO)): Both sides opened strong, but CON built the more durable line: (1) it repeatedly pressed that disparate-impact law already scrutinizes outcomes and job-relatedness without requiring full public disclosure of algorithmic weights, directly answering PRO's "black box" objection; and (2) it introduced a concrete, unanswered mechanism—the high-volume warehouse/seasonal-hiring scenario—showing that blind reviews and work samples still require some automated first cut, or they collapse into referral-based elite pipelines. PRO never rebutted this funnel problem with anything beyond a generic assertion that "many large retailers already use work-sample tests," which sidesteps the specific triage bottleneck CON raised. PRO's opening and closing had strong rhetorical moments (e.g., "you cannot subpoena a weight you cannot name"), and its facial-recognition bias point was legitimate background knowledge, but its Rebuttal 1 anecdote about a specific retailer's video tool flagging Black applicants edges into unverified brittle specificity, and its later rebuttals largely reasserted the opacity/poisoned-data claim rather than directly engaging CON's outcome-based legal counter or the scaling mechanism. CON's answers in the Pressure Questions exchange were more substantive and concrete, giving it the cleaner, more resolved case by the end.
  Most decisive rebuttal noted: CON's warehouse/seasonal-hiring example (A4.2) exposing that PRO's "modular" alternatives still need an automated first cut, versus PRO's unspecific reply that such alternatives are "already in use" (B4.3) without addressing the triage bottleneck — this exchange most decisively favored CON.
- **GPT-5.6 Sol (high)** (A = Baidu Ernie 5.1 (PRO); B = Grok 4.5 (high) (CON)): B won by directly answering the central opacity claim: disparate-impact enforcement can examine group outcomes and job-related validation without requiring candidates to know every proprietary weight. B also weighed automated tools against hidden human bias rather than an idealized baseline. A established credible discrimination risks and plausible alternatives, but repeatedly overstated that redress was impossible and did not prove why stringent validation would fail. B's scalability case sometimes blurred these specific tools with automation generally, keeping the win competitive.
  Most decisive rebuttal noted: B4.1 most decisively answered A's pressure question by explaining that adverse outcomes and business necessity, rather than public source code, can establish a violation. This substantially weakened A's claim that opacity makes existing enforcement useless.
- **Muse Spark 1.1 (high)** (A = Baidu Ernie 5.1 (PRO); B = Grok 4.5 (high) (CON)): CON won the core opacity and enforceability clash. PRO's live route required secret weights = unchallengeable; CON answered that disparate-impact law turns on outcome statistics and job-related validation, not public weights — a standard traditional interviews never meet. PRO never recovered on scalability, offering large-retailer assertions where small-firm manpower was at issue, while CON's warehouse referral-collapse example gave a concrete tradeoff: banning measurable bias tools preserves invisible affinity bias.
  Most decisive rebuttal noted: B4.1 / B2.4 rebuttal that workers prove violations via adverse outcomes and business-necessity, not via proprietary weights, directly neutralizing A's central due-process argument.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0676__grok-4.5-high__ernie-5.1__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **Grok 4.5 (high)**, CON = **Baidu Ernie 5.1**
- Judged result: Unanimous `3-0` for **Grok 4.5 (high)**.
- Entertainment scores: `7`, `7`, `7`
- Mean signed raw margin (PRO+): `+1.83`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| Claude Sonnet 5 (high) | A = Baidu Ernie 5.1 (CON); B = Grok 4.5 (high) (PRO) | Grok 4.5 (high) | +1.8 | +1.75 | 7.0 |
| GPT-5.6 Sol (high) | A = Grok 4.5 (high) (PRO); B = Baidu Ernie 5.1 (CON) | Grok 4.5 (high) | +2.4 | +2.27 | 7.0 |
| Muse Spark 1.1 (high) | A = Grok 4.5 (high) (PRO); B = Baidu Ernie 5.1 (CON) | Grok 4.5 (high) | +1.3 | +1.38 | 7.0 |

### Judge Notes

- **Claude Sonnet 5 (high)** (A = Baidu Ernie 5.1 (CON); B = Grok 4.5 (high) (PRO)): Both sides argued competently and stayed on-topic, but PRO built a more cohesive and harder-to-dislodge case. PRO's central structural point—that ex-post audits and transparency mandates cannot undo the individual harm of an already-completed silent rejection, and that the coercive "perform-or-be-eliminated" biometric surrender has no real analogue in credit scoring or medical device regulation—was never squarely answered by CON. CON repeatedly relied on the "unstructured interviews are worse" comparison and an EEOC/credit-scoring analogy, but never resolved the tension PRO exposed in [B2.4]: CON's own proposed "smart regulation" (mandatory pre-deployment validation, bias audits, disclosure) is functionally close to what PRO defines as "heavy restriction," undermining CON's framing of the choice as ban-vs-reform rather than degrees of the same restriction the motion already contemplates. PRO's pressure-question answers (A1/A2 in Turn 7) sharpened this by distinguishing hiring AI's coercive, irreversible biometric exposure from the voluntary, revisable nature of credit or medical algorithm interactions—a distinction CON's closing never directly rebutted. CON's small-business argument was a good original angle but weakened when CON conceded in Rebuttal 2 that accent/neurodivergence risks are real and only "addressable" by future fixes, effectively admitting present-tense harm. Overall PRO progressed the debate more effectively, converting pressure into a decisive framing edge that CON's closing did not fully neutralize.
  Most decisive rebuttal noted: PRO's Rebuttal 2 answer to CON's Q2 ([B4.2]): "Transparency documents exclusion after it has already sorted people out" directly undercut CON's core audit-trail solution by highlighting the temporal mismatch between harm and remedy, a point CON never squarely answered in its closing.
- **GPT-5.6 Sol (high)** (A = Grok 4.5 (high) (PRO); B = Baidu Ernie 5.1 (CON)): Side A won because the proposition permits heavy restriction, and A clearly defended conditional bans pending job-specific validation plus mandatory audits. Side B repeatedly attacked a total ban while proposing audits, validation, transparency, retention limits, and opt-outs—an oversight regime that substantially concedes the proposition. B made a strong comparison to biased human interviews, but never established why its preferred safeguards were not themselves heavy restrictions.
  Most decisive rebuttal noted: A2.4 was decisive: A converted B’s admission that video tools need oversight into support for the motion’s heavy-restriction option. B continued calling the choice prohibition versus regulation without resolving that concession.
- **Muse Spark 1.1 (high)** (A = Grok 4.5 (high) (PRO); B = Baidu Ernie 5.1 (CON)): PRO won the comparative because the heavy-restrict burden was met: B's own solution requires mandatory audits, validation, and data controls to create the audit trail it praises, which concedes that market self-correction fails and that pre-deployment restriction is necessary. A kept live the distinctive harms B never fully defused - irreversible behavioral biometrics under job-or-nothing coercion and individual black-box rejections that post-hoc aggregate audits cannot restore. B's strong status-quo bias point was blunted by A's reply that scaling pseudoscientific video scores industrializes, rather than fixes, exclusion.
  Most decisive rebuttal noted: B's audit-trail flip (human gut leaves no record vs algorithm can be audited) vs A's secrecy + timing reply that transparency after sorting still leaves privacy invasion and uncontestable individual lockout already done - the core of the second-rebuttal exchange.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260814a__debate_all_templates`
- Topic ID: `prop_0676`
- Side-swap group ID: `prop_0676__ernie-5.1__grok-4.5-high__tpl_placement_active_20260320f`
- Raw paired winner: **Grok 4.5 (high)**
- Mean normalized margin for Baidu Ernie 5.1: `-1.66`
- Complete side swap: `yes`
- Included in ratings: `yes`
