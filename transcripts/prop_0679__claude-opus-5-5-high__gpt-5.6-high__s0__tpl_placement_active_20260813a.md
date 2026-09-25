# Debate prop_0679__claude-opus-5-5-high__gpt-5.6-high__s0__tpl_placement_active_20260813a

- topic_id: prop_0679
- proposition: AI-generated evidence (summaries, translations, reconstructions) should be presumptively inadmissible in criminal trials unless independently verified by a human expert.
- model_pro: claude-opus-5-5-high
- model_con: gpt-5.6-high
- side_swap: False

## Turn 1: PRO Opening

- model: claude-opus-5-5-high
- raw_words: 338
- clipped_words: 338
- claim_ids: [P1.1], [P1.2], [P1.3], [P1.4], [P1.5], [P1.6], [P1.7], [P1.8], [P1.9]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[P1.1] A criminal trial asks one question above all: can the state prove guilt beyond reasonable doubt with evidence the accused can actually test? AI-generated summaries, translations and reconstructions fail that test by default. This motion does not ban them. It says the state must put a human expert behind them first.
[P1.2] First, the failure is invisible. When a human translator is unsure, they hesitate, flag ambiguity, or admit a dialect is outside their competence. A language model never hesitates. It produces fluent, confident output whether it is right or inventing.
[P1.3] Picture a wiretap in a regional dialect where "I'll finish it tonight" could mean a shipment or a person. The machine picks one reading, prints it cleanly, and the jury sees certainty that never existed. Summaries are worse: a model condensing thousands of messages decides what matters, and omission is invisible. You cannot object to the sentence you never saw.
[P1.4] Second, reconstruction manufactures evidence rather than revealing it. When software "enhances" blurry footage, it does not recover hidden pixels. It predicts plausible ones from training data. The face that emerges is partly an extrapolation of what faces usually look like.
[P1.5] Courts have already balked at AI-enhanced video for exactly this reason. Showing a jury a guess dressed as a photograph is the most dangerous kind of prejudice.
[P1.6] Third, you cannot cross-examine a model. Confrontation is the defendant's core protection. A human expert can be asked about method, error rates, and doubts. A model cannot explain why it chose one word, and its vendor may call its workings proprietary.
[P1.7] Requiring human verification restores someone who can answer for the evidence under oath.
[P1.8] Finally, weigh the costs. CON will say humans make mistakes too and verification is slow. But human mistakes can be cross-examined; model mistakes arrive pre-laundered as neutral technology. Verification costs expert time.
[P1.9] Skipping it risks wrongful convictions, the one error our system is built hardest to avoid. When liberty is at stake, the burden belongs on the party with the power to prosecute, not on the defendant.

## Turn 2: CON Opening

- model: gpt-5.6-high
- raw_words: 328
- clipped_words: 328
- claim_ids: [C1.1], [C1.2], [C1.3], [C1.4], [C1.5], [C1.6], [C1.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C1.1] Presumptive inadmissibility is the wrong legal instrument because it confuses a reason for scrutiny with a reason for exclusion. Courts already ask whether evidence is authenticated, relevant, sufficiently reliable, and more probative than prejudicial. Those tests can exclude a speculative facial reconstruction while admitting a useful transcript. The motion instead treats radically different tools as one suspect category merely because AI assisted them.
[C1.2] A summary need not replace the underlying messages; it can organize them while both sides retain access to the originals. A translation can be displayed beside the recording and challenged with an alternative. A reconstruction can be labeled as demonstrative rather than historical fact. Disclosure of prompts, model versions, editing, confidence limits, and source material gives courts concrete safeguards.
[C1.3] The proper response to uncertainty is calibrated conditions, not a categorical presumption.
[C1.4] Nor is mandatory “human verification” a guarantee of truth. If verification means independently redoing the entire task, AI’s gains in speed, cost, and access disappear. If it means briefly reviewing the output, errors can still pass through—now carrying the false prestige of expert approval. Human experts also disagree, overlook context, and may lack rare dialect or technical competence.
[C1.5] The relevant question is whether this output is testable, not whether someone with a credential has blessed it.
[C1.6] Confrontation does not require cross-examining every instrument. We do not cross-examine a calculator; we question the person who selected its inputs, operated it, and offers its result. Likewise, counsel can examine the sponsoring witness, inspect the source, reproduce the process, and expose discrepancies. If proprietary design prevents meaningful testing, that particular output may be excluded.
[C1.7] The motion also burdens defendants, small jurisdictions, and speakers of uncommon languages who may lack money for experts. An accused should not lose an exculpatory AI translation or summary solely because no qualified human is affordable. Reliability should govern admission case by case. A blanket suspicion tied to technology substitutes pedigree for proof and can keep useful, contestable evidence away from the jury.

## Turn 3: PRO Rebuttal 1

- model: claude-opus-5-5-high
- raw_words: 354
- clipped_words: 340
- claim_ids: [P2.1], [P2.2], [P2.3], [P2.4], [P2.5], [P2.6], [P2.7], [P2.8], [P2.9], [P2.10], [P2.11]
- cited_claim_ids: [C1.2], [C1.1], [C1.6], [C1.4], [C1.7]
- missing_claim_id_refs: (none)

[P2.1] The key concession is in [C1.2]: prompts, model versions, confidence limits and source material must be disclosed before AI evidence is safe. That is a presumption against admissibility. The only remaining question is who carries the burden before the jury sees the output. We say the prosecution, the party with the resources and the power to convict.
[P2.2] Start with "existing tests suffice" [C1.1]. They were built for evidence that fails visibly. A shaky witness stumbles; a smudged document looks smudged. AI output looks equally polished whether it is accurate or invented, so a judge running an ordinary reliability check sees fluency and mistakes it for reliability.
[P2.3] A presumption exists precisely because the defect is hidden. It is also rebuttable, which is calibration, not a blanket ban.
[P2.4] Next, the side-by-side safeguards. Showing a translation beside the recording helps only if someone in the courtroom speaks the dialect. That person is a human expert, so CON's safeguard quietly depends on our requirement. Keeping the originals available to check a summary sounds fair until you remember why the summary exists: nobody can read ten thousand messages.
[P2.5] The defence cannot object to an omission it would have to reread everything to find.
[P2.6] Now the calculator [C1.6]. A calculator is deterministic: the same input gives the same answer, and its method is fully known. A language model can give different answers to the same prompt and cannot explain why it chose "shipment" over "person." The sponsoring witness who "operated it" knows no more about that choice than the jury does.
[P2.7] Cross-examining the operator is theatre, not confrontation.
[P2.8] "Human verification isn't a guarantee" [C1.4]. Agreed, and nobody claimed it was. The point is accountability. The motion says "independently verified," not rubber-stamped.
[P2.9] An expert who signs off can be asked under oath what they checked, and can be impeached when they overstate it. A model cannot.
[P2.10] Finally, the defendants' burden [C1.7]. A rebuttable presumption bends where the right to present a defence demands. But weigh the errors. A lost exculpatory summary can be rebuilt by hand.
[P2.11] A [clipped]

## Turn 4: CON Rebuttal 1

- model: gpt-5.6-high
- raw_words: 327
- clipped_words: 327
- claim_ids: [C2.1], [C2.2], [C2.3], [C2.4], [C2.5], [C2.6], [C2.7], [C2.8]
- cited_claim_ids: [P2.1], [P2.10]
- missing_claim_id_refs: (none)

[C2.1] The claimed concession in [P2.1] collapses two different safeguards. Disclosure makes an output testable; independent human verification duplicates or blesses its substance. Requiring prompts, model details, and source material no more creates a presumption of inadmissibility than requiring chain-of-custody records does. It supplies the ordinary foundation on which a judge decides reliability.
[C2.2] PRO has not justified why every disclosed, reproducible use must additionally purchase an expert’s approval.
[C2.3] Nor were existing tests built only for visible failures. Courts routinely assess polished but contestable outputs: laboratory analyses, edited recordings, statistical inferences, and confident human translations. Judges examine methodology and foundation rather than facial appearance. Human experts can also speak fluently while missing ambiguity; placing one signature on an AI output may make technological authority even more persuasive.
[C2.4] The safeguard is transparent limitations and adversarial testing, not assuming human confidence cures machine confidence.
[C2.5] PRO’s “calculator” response also misses the principle. Cross-examination targets the evidentiary claim and the people responsible for presenting it. Counsel can ask what source was used, what prompt and settings were chosen, whether alternative outputs were generated, what passages were omitted, and whether the result matches the underlying record. If those questions cannot be answered, exclusion may follow.
[C2.6] But if a summary links every proposition to identifiable messages, its accuracy can be sampled and contested without an expert independently recreating ten thousand-message work. Testability can be achieved without duplication.
[C2.7] Most damagingly, PRO quietly rewrites the motion when addressing defendants. [P2.10] says the presumption can “bend,” but the proposition supplies no defendant exception and covers translations and summaries broadly. Saying exculpatory work can simply be “rebuilt by hand” ignores why AI was used: scarce language skills, time, and money. Wealthy prosecutors may hire experts; indigent defendants may lose usable evidence.
[C2.8] Speculative facial reconstruction may deserve exclusion. That proves our calibrated rule, not theirs. The decisive line is between outputs that can and cannot be meaningfully tested—not between those carrying an expert’s purchased signature and those that do not.

## Turn 5: PRO Pressure Questions

- model: claude-opus-5-5-high
- raw_words: 88
- clipped_words: 88
- claim_ids: [P3.1], [P3.2]
- cited_claim_ids: [C2.6], [C1.2]
- missing_claim_id_refs: (none)

[P3.1] Q1: [C2.6] says a summary that "links every proposition to identifiable messages" can be sampled and contested. Sampling checks what the summary included. How does the defence find the exculpatory message the summary left out, without someone rereading all ten thousand?
[P3.2] Q2: Take the dialect wiretap where "finish it" could mean a shipment or a person. Under your side-by-side safeguard [C1.2], who in the courtroom tells the jury which reading is correct? If the answer is a qualified human speaker, how is your rule any different from ours?

## Turn 6: CON Pressure Questions

- model: gpt-5.6-high
- raw_words: 58
- clipped_words: 58
- claim_ids: [C3.1], [C3.2]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C3.1] Q1: What exactly counts as “independently verified”: must the expert redo the entire task, eliminating AI’s benefit, or merely sample the output, leaving your hidden-omission problem unresolved?
[C3.2] Q2: Would you exclude a transparent, source-linked, exculpatory AI translation offered by an indigent defendant solely because no human expert is affordable—and if not, where is that exception in the proposition?

## Turn 7: PRO Rebuttal 2

- model: claude-opus-5-5-high
- raw_words: 365
- clipped_words: 340
- claim_ids: [P4.1], [P4.2], [P4.3], [P4.4], [P4.5], [P4.6], [P4.7], [P4.8], [P4.9]
- cited_claim_ids: [C2.8]
- missing_claim_id_refs: (none)

[P4.1] A1: "Independently verified" means neither of CON's two extremes. The expert does not redo the whole task, and does not merely skim a sample. They check the output against the source using a method they choose, disclose and defend under oath. For the wiretap, a qualified speaker reviews the incriminating passages and every ambiguous phrase.
[P4.2] For the ten thousand messages, the expert runs targeted searches for exculpatory categories: alibis, other suspects, recantations. They then attest to what they checked and what they did not.
[P4.3] That does not make omission impossible. It makes omission answerable. Today the gap sits inside a model nobody can question. Under our rule, a named person must say "I searched for X and not Y," and defence counsel can attack Y.
[P4.4] AI keeps its value because checking a draft is still far cheaper than building one from nothing.
[P4.5] A2: No. That exception is in the proposition. The word is "presumptively," and a presumption is rebuttable by definition. Criminal evidence rules also already yield to the accused's right to present a defence; courts have long refused to apply them mechanically against reliable exculpatory material. The asymmetry is deliberate.
[P4.6] The state must prove guilt beyond reasonable doubt. The defendant only needs to raise a doubt. A presumption built to guard against wrongful conviction naturally bites hardest on the party seeking one.
[P4.7] Now look at what these answers do to CON's case. CON's decisive line [C2.8] is "outputs that can and cannot be meaningfully tested." Ask how a judge learns that a dialect translation is testable. Someone who speaks the dialect has to say so.
[P4.8] Ask how anyone knows a summary's omissions were probed. Someone has to probe them. CON's testability standard runs through a human expert every time. The only real difference between us is who pays for that expert and when: before the jury hears the evidence, or after a conviction.
[P4.9] That is the whole debate. If we are wrong, a prosecutor spends extra expert hours. If CON is wrong, a jury convicts on fluent machine output [clipped]

## Turn 8: CON Rebuttal 2

- model: gpt-5.6-high
- raw_words: 332
- clipped_words: 332
- claim_ids: [C4.1], [C4.2], [C4.3], [C4.4], [C4.5], [C4.6], [C4.7]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C4.1] A1: The defence finds omissions through disclosed source access, targeted searches, competing queries, and, where stakes require, fuller review—not by assuming one expert has reread everything. Crucially, a source-linked summary proves the messages it cites; it need not prove that no other message exists. If the prosecution offers it as comprehensive, the judge can demand a stronger foundation or restrict that claim. PRO’s own expert searches only predicted “exculpatory categories,” so unexpected evidence remains equally hidden.
[C4.2] A2: No one should falsely tell the jury there is one correct reading. The ambiguity itself should be disclosed, with both translations and the recording presented. Participants in the conversation may explain their intended usage; a language expert may be necessary when that disputed phrase bears guilt. Then ordinary reliability rules demand one.
[C4.3] That does not justify presuming every AI translation, including routine uncontested passages, inadmissible without one.
[C4.4] These answers expose the central defect in PRO’s attempted middle ground. Its expert neither reviews all records nor knows which omitted category matters; they merely make selected searches “answerable.” But accountability for a disclosed search protocol is already available by questioning the operator and examining outputs. Adding a credentialed signatory may increase jury confidence without increasing completeness.
[C4.5] Their defendant exception also rewrites rather than reads the motion. “Presumptively” means rebuttable, but PRO offers no principled trigger beyond the same case-specific reliability and fairness assessment CON advocates. If transparent exculpatory output overcomes the presumption because an expert is unaffordable, human verification is not the decisive reliability condition. If it cannot, defendants lose useful evidence.
[C4.6] Finally, testability does not run through an expert every time. A cited summary can be checked claim by claim; a translation can be compared against alternative renderings; a reconstruction can be excluded when it invents detail. Different outputs require different foundations. The choice is not “expert now or conviction later”; it is tailored judicial scrutiny versus a costly, overinclusive credential rule.
[C4.7] Because PRO’s safeguard neither cures omissions nor fits all uses, the presumption is unjustified.

## Turn 9: PRO Closing

- model: claude-opus-5-5-high
- raw_words: 219
- clipped_words: 219
- claim_ids: [P5.1], [P5.2], [P5.3], [P5.4], [P5.5], [P5.6], [P5.7]
- cited_claim_ids: [C4.2]
- missing_claim_id_refs: (none)

[P5.1] Strip this debate to one question: when an AI error is invisible, who has to find it before the jury hears it?
[P5.2] CON's answer is the judge, running "tailored judicial scrutiny." But look at what CON conceded in [C4.2]: the ambiguity "should be disclosed," and a language expert "may be necessary when that disputed phrase bears guilt." Disclosed by whom? The model never flags doubt; it prints "finish the job" as cleanly as "good morning."
[P5.3] A judge who doesn't speak the dialect cannot know which phrase is disputed. Only a human who does can raise that flag. So CON's rule needs our expert too. It just waits until someone happens to notice the problem, and the whole danger is that nobody will.
[P5.4] That is why the default matters. Under CON, fluent output reaches the jury unless the defence can prove the hidden flaw. Under ours, the state must first put a named person under oath who says what they checked. CON calls that a "credential."
[P5.5] It is actually a target. A person can be impeached. A model cannot.
[P5.6] The asymmetry settles it. If we are wrong, prosecutors spend expert hours checking a draft. If CON is wrong, someone goes to prison on a guess no one was required to test. Criminal law has always accepted that trade.
[P5.7] Vote PRO.

## Turn 10: CON Closing

- model: gpt-5.6-high
- raw_words: 215
- clipped_words: 215
- claim_ids: [C5.1], [C5.2], [C5.3], [C5.4], [C5.5], [C5.6]
- cited_claim_ids: (none)
- missing_claim_id_refs: (none)

[C5.1] The decisive issue is whether mandatory expert verification actually separates safe evidence from unsafe evidence. PRO never establishes that line.
[C5.2] Their expert does not reread every message; they run selected searches for anticipated categories. The unexpected omission—the very hidden error PRO fears—remains hidden. A human signature therefore does not cure the central problem. Yet a transparent, source-linked summary whose claims are directly checkable still begins presumptively excluded, even where no concrete reliability defect exists.
[C5.3] Their rule is simultaneously ineffective against danger and obstructive of useful evidence.
[C5.4] PRO’s claim that, without its presumption, AI output simply reaches the jury is a false choice. The proponent still bears ordinary foundational burdens. A judge can require disclosure of sources, prompts, methods, alternatives, and limitations; narrow the purpose for which an output is offered; or exclude it entirely. Where a disputed dialect phrase bears on guilt, an expert may indeed be necessary—not because “AI” triggers a categorical suspicion, but because that particular claim otherwise cannot be meaningfully tested.
[C5.5] That is the principled dividing line: testability of the evidence, not the purchase of a credential. A presumption should track actual risk. This one tracks only technological involvement, while its supposed safeguard cannot find the unknown errors invoked to justify it. Tailored scrutiny protects defendants better than ritual verification.
[C5.6] Vote CON.
