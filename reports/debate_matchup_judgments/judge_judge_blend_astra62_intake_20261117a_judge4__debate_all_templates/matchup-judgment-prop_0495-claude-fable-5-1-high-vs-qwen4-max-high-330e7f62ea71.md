# Debate Matchup Judgment Report

**Claude Fable 5.1 (high)** vs **Qwen 4 Max (high)**

- Paired result: **Claude Fable 5.1 (high)**
- Mean entertainment: `8.67 / 10`
- Judge decisions: `6` across `2` side-swapped debates

**Motion:** Open-source maintainers of critical infrastructure libraries should receive public funding comparable to other essential-infrastructure workers rather than be expected to maintain them for free.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0495__claude-fable-5-1-high__qwen4-max-high__s0__tpl_placement_headroom_prod_20261115a.md): PRO = **Claude Fable 5.1 (high)**, CON = **Qwen 4 Max (high)**
- [Debate B transcript](../../../transcripts/prop_0495__qwen4-max-high__claude-fable-5-1-high__s1__tpl_placement_headroom_prod_20261115a.md): PRO = **Qwen 4 Max (high)**, CON = **Claude Fable 5.1 (high)**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_astra62_intake_20261117a_judge4.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0495__claude-fable-5-1-high__qwen4-max-high__s0__tpl_placement_headroom_prod_20261115a.md)
- Roles: PRO = **Claude Fable 5.1 (high)**, CON = **Qwen 4 Max (high)**
- Judged result: Split `2-1` for **Claude Fable 5.1 (high)**.
- Entertainment scores: `8`, `9`, `9`
- Mean signed raw margin (PRO+): `+0.50`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| DeepSeek V4 Pro 0813 (high) | A = Claude Fable 5.1 (high) (PRO); B = Qwen 4 Max (high) (CON) | Qwen 4 Max (high) | -1.2 | -1.29 | 8.0 |
| Gemini 4 Carbon (high) | A = Claude Fable 5.1 (high) (PRO); B = Qwen 4 Max (high) (CON) | Claude Fable 5.1 (high) | +1.4 | +1.05 | 9.0 |
| Kimi K3.1 Pro (high) | A = Claude Fable 5.1 (high) (PRO); B = Qwen 4 Max (high) (CON) | Claude Fable 5.1 (high) | +1.3 | +1.22 | 9.0 |

### Judge Notes

- **DeepSeek V4 Pro 0813 (high)** (A = Claude Fable 5.1 (high) (PRO); B = Qwen 4 Max (high) (CON)): B won because A's main move was to treat any public payment for maintainer work as a concession of the motion. B exposed that this collapse makes the essential-worker parity claim decoration: ordinary procurement already buys audits and fixes, but it cannot buy the enforceable duty that makes essential-infrastructure comparisons meaningful. A's fallback to conditional funding and co-maintainers was undercut by B's point that loss of funding merely returns the project to the volunteer crisis and that forking a trusted project does not transfer trust. B answered pressure questions more sharply and left A needing an enforcement mechanism against a maintainer who can refuse terms or walk away.
  Most decisive rebuttal noted: B's payment-is-not-compulsion line was the most decisive: A treated paid maintainers as accountable, but B showed that taking back a grant punishes the public by returning the library to unfunded risk while compelling nothing from the maintainer. B's follow-up that forking xz does not fork trust directly damaged A's co-maintainer fallback.
- **Gemini 4 Carbon (high)** (A = Claude Fable 5.1 (high) (PRO); B = Qwen 4 Max (high) (CON)): Side A wins a high-level debate by defending a coherent, realistic reading of the proposition and exposing a fatal gap in Side B's counter-model. Side B smartly distinguished public utilities—where the public owns the plant and can compel or swap operators—from open-source repositories where independent maintainers hold commit rights and downstream trust. However, Side A showed from the outset that funding "comparable to essential-infrastructure workers" means ongoing, conditional infrastructure contracts (continuity, living wages, inspections, and second signers) rather than unconditional handouts or leaving maintainers unpaid. When Side A pressed on who actually writes, merges, and releases fixes at 2 a.m. if external auditors lack commit rights, Side B pivoted in Rebuttal 2 to publicly buying commit rights, patch authorship, release engineering, second signers, and on-call rotas via signed contracts. That concession surrendered most of the substantive dispute—paying commit-holders continuously to stay on call rather than work for free—while suffering from the exact same consent and ownership limits Side B used to attack Side A. Side A loses a sliver of execution credit for mislabeling B4.3/B4.7 as [C4.3, C4.7] in closing, keeping the margin competitive.
  Most decisive rebuttal noted: Side A's Q2 and Rebuttal 2 [A3.2, A4.4, A4.6-A4.7] decisively broke Side B's "buy external review, not maintainer salaries" counter-model: A pointed out that in xz the maintainer was a known, exhausted person rather than a pseudonymous holdout, and that an external reviewer without commit rights only files bug reports while leaving the unpaid maintainer to merge fixes at 2 a.m. or accept malicious "free help," forcing B to concede funding commit-holders and on-call rotas.
- **Kimi K3.1 Pro (high)** (A = Claude Fable 5.1 (high) (PRO); B = Qwen 4 Max (high) (CON)): A won a clear but competitive debate. B landed the sharper conceptual warning that grants do not transfer ownership, trust, or commit rights, but A answered with renewable conditional funding, paid co-maintainers, and continuity obligations. More importantly, B ultimately supported publicly paid patching, release engineering, on-call coverage, and succession, leaving CON objecting mainly to the worker comparison rather than defending unpaid maintenance. The motion did not require unconditional salaries or public ownership.
  Most decisive rebuttal noted: A's pressure question about who writes, merges, and releases the fix forced B to concede that fixes and continuing obligations should be publicly purchased. That substantially blunted B's procurement-versus-maintainer distinction; B's fork-trust response was strong but did not show why funding should therefore be withheld.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0495__qwen4-max-high__claude-fable-5-1-high__s1__tpl_placement_headroom_prod_20261115a.md)
- Roles: PRO = **Qwen 4 Max (high)**, CON = **Claude Fable 5.1 (high)**
- Judged result: Unanimous `3-0` for **Claude Fable 5.1 (high)**.
- Entertainment scores: `8`, `9`, `9`
- Mean signed raw margin (PRO+): `-1.13`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| DeepSeek V4 Pro 0813 (high) | A = Qwen 4 Max (high) (PRO); B = Claude Fable 5.1 (high) (CON) | Claude Fable 5.1 (high) | -1.2 | -1.29 | 8.0 |
| Gemini 4 Carbon (high) | A = Qwen 4 Max (high) (PRO); B = Claude Fable 5.1 (high) (CON) | Claude Fable 5.1 (high) | -1.2 | -0.90 | 9.0 |
| Kimi K3.1 Pro (high) | A = Qwen 4 Max (high) (PRO); B = Claude Fable 5.1 (high) (CON) | Claude Fable 5.1 (high) | -1.0 | -0.94 | 9.0 |

### Judge Notes

- **DeepSeek V4 Pro 0813 (high)** (A = Qwen 4 Max (high) (PRO); B = Claude Fable 5.1 (high) (CON)): B wins a close but clear debate. A opened with a strong public-goods and infrastructure-stewardship case, but B successfully narrowed the clash to whether a public allocator would actually reach the right maintainers. B exposed that A's levy-plus-threshold model depended on unpublished hospital dependency data, while liability forces the exact firms shipping the code to disclose and fund it. B also effectively answered A's strongest attack—that liability pays readers, not fixers—by explaining that a liability report is useless until the patch exists, so firms have reason to fund the maintainer. A's "hundred paid readers, one unpaid inbox" crystallized well, but B's closing directly answered it and reframed the xz point as a co-maintainer problem. A left the ranking/disclosure and Jia Tan objections insufficiently resolved.
  Most decisive rebuttal noted: B's rebuttal to the "who pays the patch?" challenge was decisive: a downstream audit is worthless unless the fix is made, so liability gives the shipping firm reason to fund the upstream maintainer—not merely a reviewer.
- **Gemini 4 Carbon (high)** (A = Qwen 4 Max (high) (PRO); B = Claude Fable 5.1 (high) (CON)): In a high-level debate, Side B won by systematically dismantling Side A's institutional model at each stage and turning Side A's concessions into a cleaner comparative case. Side A presented a compelling public-good argument for pooled upstream maintenance and won early clashes on Heartbleed, Log4j, and moral hazard. However, Side B trapped Side A on what funding comparable to infrastructure workers entails: under pressure, Side A shifted from infrastructure-worker salaries to basic-research fellowships (which Side B showed reward proposal writers and lack accountability) and then in Turn 7 to revocable procurement contracts based on critical-sector dependency thresholds. Side B then landed two decisive, unanswered Turn 8 hits—that hospital dependency graphs are not public unless firms are first made answerable, and that recruiting co-maintainers via public vacancies without shipping-employer backing repeats the xz/Jia Tan vector—while directly answering Side A's core challenge on why liability compels firms to fund patches and support contracts rather than merely audit code. Side A also committed a minor flow error in A4.5 by accusing Side B of never answering a Pressure Question before Side B's answering speech had occurred.
  Most decisive rebuttal noted: Side B's multi-round takedown of Side A's allocation and governance model: turning Side A's basic-research analogy in B2.3-B2.5 ("The maintainer of a boring parser does not write proposals; she writes parsers") to force Side A into proposing revocable threshold contracts in A4.1-A4.3, and then exposing in B4.5-B4.7 that this retreat abandoned infrastructure employment for procurement while relying on unpublished hospital dependency graphs.
- **Kimi K3.1 Pro (high)** (A = Qwen 4 Max (high) (PRO); B = Claude Fable 5.1 (high) (CON)): B earned a narrow edge through superior progression and pressure handling. A’s public-good case, levy response, and diffuse-maintenance argument remained viable, but B directly answered the unpaid-upstream challenge and turned A’s contract and eligibility answers into concrete allocation and dependency-data burdens. A’s closing crystallized the free-rider gap well but did not fully neutralize those feasibility objections.
  Most decisive rebuttal noted: B’s second rebuttal was decisive: it explained how liability could fund upstream fixes, addressed the xz team argument, and used A’s own accountability and ranking proposals to sharpen the critique of revocable procurement and gatekeeping.

## Technical metadata

- Evaluation scope: `judge_judge_blend_astra62_intake_20261117a_judge4__debate_all_templates`
- Topic ID: `prop_0495`
- Side-swap group ID: `prop_0495__claude-fable-5-1-high__qwen4-max-high__tpl_placement_headroom_prod_20261115a`
- Raw paired winner: **Claude Fable 5.1 (high)**
- Mean normalized margin for Claude Fable 5.1 (high): `+0.68`
- Complete side swap: `yes`
- Included in ratings: `yes`
