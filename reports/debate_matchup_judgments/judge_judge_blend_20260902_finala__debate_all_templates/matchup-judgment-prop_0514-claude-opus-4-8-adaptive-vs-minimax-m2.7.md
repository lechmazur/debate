# Debate Matchup Judgment Report

**Claude Opus 4.8 (high)** vs **MiniMax-M2.7**

- Paired result: **Claude Opus 4.8 (high)**
- Mean entertainment: `8.17 / 10`
- Judge decisions: `6` across two side-swapped debates

**Motion:** Public procurement should favor open standards and switching portability over single-vendor integrated stacks for school and health IT.

## Debates and evidence

- [Debate A transcript](../../../transcripts/prop_0514__claude-opus-4-8-adaptive__minimax-m2.7__s0__tpl_placement_active_20260320f.md): PRO = **Claude Opus 4.8 (high)**, CON = **MiniMax-M2.7**
- [Debate B transcript](../../../transcripts/prop_0514__minimax-m2.7__claude-opus-4-8-adaptive__s1__tpl_placement_active_20260320f.md): PRO = **MiniMax-M2.7**, CON = **Claude Opus 4.8 (high)**
- [Public judge decision table](../../../judgments/judge_results__judge_blend_20260902_finala.csv)

## Debate A

- Transcript: [read the full debate](../../../transcripts/prop_0514__claude-opus-4-8-adaptive__minimax-m2.7__s0__tpl_placement_active_20260320f.md)
- Roles: PRO = **Claude Opus 4.8 (high)**, CON = **MiniMax-M2.7**
- Judged result: Unanimous `3-0` for **Claude Opus 4.8 (high)**.
- Entertainment scores: `8`, `8`, `8`
- Mean signed raw margin (PRO+): `+2.27`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = Claude Opus 4.8 (high) (PRO); B = MiniMax-M2.7 (CON) | Claude Opus 4.8 (high) | +1.8 | +1.93 | 8.0 |
| Gemini 3.1 Pro Preview | A = Claude Opus 4.8 (high) (PRO); B = MiniMax-M2.7 (CON) | Claude Opus 4.8 (high) | +2.5 | +2.08 | 8.0 |
| Qwen 3.6 Max Preview | A = Claude Opus 4.8 (high) (PRO); B = MiniMax-M2.7 (CON) | Claude Opus 4.8 (high) | +2.5 | +2.50 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = Claude Opus 4.8 (high) (PRO); B = MiniMax-M2.7 (CON)): A won because it made the exit-rights and enforceability comparison clearer: contracts only discipline vendors if the public buyer can actually leave, and leaving requires readable, portable, documented data. B had credible concerns about integration burden and accountability, but often overstated the motion as a universal mandate and its contractual portability alternative largely conceded the need for standards and switching portability. B also suffered from clipped turns and a rebuttal section that effectively endorsed A's competitive-integration point.
  Most decisive rebuttal noted: A's strongest exchange was against B's contract answer: an export clause is not meaningful if it points to a closed or unreadable format, so portability and open standards are what give contract remedies teeth rather than replacing them.
- **Gemini 3.1 Pro Preview** (A = Claude Opus 4.8 (high) (PRO); B = MiniMax-M2.7 (CON)): Side A decisively won by exposing a fatal contradiction in Side B's case. Side B attempted to offer "contractual portability" as an alternative to the motion, but Side A expertly used a Pressure Question and their Closing to demonstrate that such clauses inherently require the very open standards the motion advocates.
  Most decisive rebuttal noted: Side A's Pressure Question 1 and subsequent Closing (A5.1-A5.3) completely dismantled Side B's main alternative mechanism.
- **Qwen 3.6 Max Preview** (A = Claude Opus 4.8 (high) (PRO); B = MiniMax-M2.7 (CON)): Side A won by decisively collapsing Side B's core alternative. B argued that "competent contracts" with export clauses could provide escape hatches without mandating open standards, but A correctly demonstrated that contractual portability is functionally empty unless an open, documented standard exists to export into. A's closing crystallized this perfectly: B's "competent contract" wasn't an alternative to the motion, it was the motion written on a different page. Additionally, B suffered a critical execution error in Rebuttal 1 (B2.4-B2.5), accidentally conceding A's entire point on integration costs by arguing that open standards enable competitive bidding while proprietary stacks create monopolies. A answered pressure questions cleanly, maintained a consistent stewardship frame, and landed a memorable, decisive closing. B's modal-case and risk-theater arguments were plausible but ultimately couldn't survive the collapse of their contractual alternative and the integration concession.
  Most decisive rebuttal noted: Side A's collapse of Side B's "competent contract" frame across Rebuttal 2 and Closing. A showed that B's proposed export clauses inherently require open standards to function, turning B's main alternative into a proof of A's necessity. This, combined with B's accidental concession on integration competition in Rebuttal 1, gave A a clean, unanswerable path to victory.

## Debate B

- Transcript: [read the full debate](../../../transcripts/prop_0514__minimax-m2.7__claude-opus-4-8-adaptive__s1__tpl_placement_active_20260320f.md)
- Roles: PRO = **MiniMax-M2.7**, CON = **Claude Opus 4.8 (high)**
- Judged result: Unanimous `3-0` for **Claude Opus 4.8 (high)**.
- Entertainment scores: `9`, `8`, `8`
- Mean signed raw margin (PRO+): `-1.73`

| Judge | Presented sides | Winner | Signed Margin (PRO+) | Normalized | Entertainment |
| --- | --- | --- | ---: | ---: | ---: |
| GPT-5.5 (high) | A = MiniMax-M2.7 (PRO); B = Claude Opus 4.8 (high) (CON) | Claude Opus 4.8 (high) | -1.5 | -1.61 | 8.0 |
| Gemini 3.1 Pro Preview | A = MiniMax-M2.7 (PRO); B = Claude Opus 4.8 (high) (CON) | Claude Opus 4.8 (high) | -2.5 | -2.08 | 9.0 |
| Qwen 3.6 Max Preview | A = MiniMax-M2.7 (PRO); B = Claude Opus 4.8 (high) (CON) | Claude Opus 4.8 (high) | -1.2 | -1.20 | 8.0 |

### Judge Notes

- **GPT-5.5 (high)** (A = MiniMax-M2.7 (PRO); B = Claude Opus 4.8 (high) (CON)): Side B won a clear but competitive debate. Side A established a plausible lock-in and leverage problem, but overclaimed that open standards guarantee competition and never fully solved B's strongest objections: standards can be gamed, migration involves workflows and training beyond data formats, and modular systems can create accountability gaps at dangerous seams. B made the cleaner comparison by arguing that portability can be secured through contract terms, export obligations, escrow, and acceptance gates while preserving integrated-stack accountability and performance. A's final paper-versus-architecture framing was rhetorically strong, but B effectively showed that A's architecture also depends on paper-like enforcement and does not uniquely deliver real switching power.
  Most decisive rebuttal noted: B's most decisive exchange was against A's certification/standards answer: B argued that spec compliance does not mean years of workflows, integrations, and training can actually migrate, then reframed contract-based export requirements as delivering comparable switching leverage without seam risk.
- **Gemini 3.1 Pro Preview** (A = MiniMax-M2.7 (PRO); B = Claude Opus 4.8 (high) (CON)): Side B won by successfully co-opting Side A's core mechanisms and turning Side A's concessions against them. When Side A conceded that standards are frequently gamed and that the real benefit is the 'credible threat' of switching rather than the switch itself, Side B effectively proved that contract-based export gates provide that exact threat without introducing the critical integration 'seam' risks Side A's model suffers from.
  Most decisive rebuttal noted: Side B's Rebuttal 2 brilliantly capitalized on Side A's admission that switching is just a 'credible threat' and that fixing a component failure requires replacing a piece, proving Side A's architecture causes the very harm it seeks to fix.
- **Qwen 3.6 Max Preview** (A = MiniMax-M2.7 (PRO); B = Claude Opus 4.8 (high) (CON)): Side B wins by successfully turning Side A's core claims and maintaining a sharper comparative frame. B effectively leveraged A's concession that standards are frequently gamed to argue that architectural mandates do not guarantee real-world migratability, reducing A's structural leverage to theoretical hope. B's argument that contractual export gates and data escrow can deliver portability without fracturing systems directly undercut A's necessity claim. Additionally, B's emphasis on single-vendor accountability and the real-world danger of seam failures in critical health and school IT provided a more compelling impact calculus than A's focus on exit ramps. B consistently answered pressure, turned A's slogans, and resolved the central trade-off more cleanly.
  Most decisive rebuttal noted: Side B's Rebuttal 2 masterfully turned Side A's credible threat argument by demonstrating that contracts with escrow and tested export formats provide the exact same switching threat, but without the integration costs and seam-failure risks of a multi-vendor open assembly. This collapsed A's unique advantage and decisively resolved the leverage clash.

## Technical metadata

- Evaluation scope: `judge_judge_blend_20260902_finala__debate_all_templates`
- Topic ID: `prop_0514`
- Side-swap group ID: `prop_0514__claude-opus-4-8-adaptive__minimax-m2.7__tpl_placement_active_20260320f`
- Raw paired winner: **Claude Opus 4.8 (high)**
- Mean normalized margin for Claude Opus 4.8 (high): `+1.90`
- Complete side swap: `yes`
- Included in ratings: `yes`
