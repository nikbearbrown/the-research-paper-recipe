# Verify-and-Enrich Notes — Chapters 00–02 (Deck Module 1 + Foundation)
## The Research Paper Recipe

**Pass type:** Verify-and-enrich (fact-check + source enrichment). NOT a rewrite. Enrichment notes only.
**Scope:** Deck Module 1 (slides 1–4) + foundation material — papers fail before writing (fluency ≠ validity); topic→question→hypothesis ladder; build the argument/schema before prose; a claim that can't fail is advocacy not a hypothesis; the "defend it without notes or AI" test.
**Date:** 2026-05-31
**Hard rule observed:** No fabricated citations. Anything not run to a primary/authoritative source is marked "unverified."

---

## Chapter 00 — Introduction

### Verified
- **The book's central "fluency vs. trustworthiness" frame** ("The first sign of trouble is usually not failure. It is fluency.") is well supported by the LLM-hallucination literature. High-confidence hallucinations — output that is fluent, coherent, linguistically correct, and factually wrong — are documented as the hardest failure mode to detect. → *Survey and analysis of hallucinations in LLMs*, Frontiers in Artificial Intelligence, 2025 (https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1622292/full); *Factuality of Large Language Models in the Year 2024*, arXiv:2402.02420.
- **No checkable named-person / dated / statistical claims appear in Ch00.** The introduction is framing prose ("execution vs. judgment," the Medhavy/Medhavi note). The Sanskrit gloss of मेधावी as "intelligent / intellectually brilliant" is accurate. Nothing to correct.

### Corrections
- None. (Ch00 makes no falsifiable factual claims to mis-state.)

### New to add
- **Bhattacharyya, Miller, Bhattacharyya & Miller (2023), "High Rates of Fabricated and Inaccurate References in ChatGPT-Generated Medical Content," *Cureus* 15(5):e39238.** (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10277170/). Of 115 references generated, **47% were entirely fabricated, 46% were authentic but inaccurate, and only 7% were both authentic and accurate.** This is the single sharpest empirical anchor for the book's thesis: a fluent, confident, professionally formatted artifact can be ~93% wrong on its verifiable substrate. Strengthens the opening "polish ≠ trust" argument and the closing "Note About AI." Use the 7%-accurate figure as a concrete hook rather than the current all-abstract framing.
- **Wasserstein, Schirm & Lazar (2019), "Moving to a World Beyond 'p < 0.05'," *The American Statistician* 73(sup1):1–19** — the ASA's own follow-up editorial to its 2016 statement, arguing that statistical "significance" itself confers a false sense of validity. Useful as a one-line forward reference in the intro's organizing logic (judgment ≠ surface signal), since the same fluency-vs-validity error recurs in the statistics chapters.

### Deck beats to fold in
- The deck's slide-1 litany ("The chart has labels. The code runs. The plan has phases") is essentially already in Ch00 ¶2 — good. The deck framing that fluency is *the first sign of trouble* maps cleanly; no change needed, but the Bhattacharyya number would let the intro show the gap instead of only asserting it.

---

## Chapter 01 — Before You Write Anything

### Verified
- **Popper's falsifiability / demarcation, and the asymmetry of confirmation vs. refutation.** Correctly attributed. Popper's *Logik der Forschung* (1934); English *The Logic of Scientific Discovery* (1959). A universal law cannot be conclusively verified but can be conclusively refuted by a single counter-instance — exactly the chapter's "intellectual content comes from what it rules out." → Stanford Encyclopedia of Philosophy, "Karl Popper" (https://plato.stanford.edu/entries/popper/); *Falsifiability*, Wikipedia (https://en.wikipedia.org/wiki/Falsifiability). The chapter wisely cites "Popper's insight" without a date, so no dating risk.
- **Topic → research question → hypothesis ladder.** The chapter's definitions (topic = region of inquiry, no edges; research question = answerable in principle; hypothesis = prediction with mechanism) are consistent with standard research-methods pedagogy and with the FINER/PICO frameworks below. No error.
- **The "a claim that can accommodate any finding cannot be tested" formulation** is a faithful, correct statement of Popperian demarcation (deck slide 4: "a claim that can't fail is advocacy"). Verified against SEP.
- **Confirmatory vs. exploratory / HARKing framing** (relevant to the chapter's "rival hypotheses" and "specify before you draft" sections): correctly aligns with Nosek, Ebersole, DeHaven & Mellor (2018), "The preregistration revolution," *PNAS* 115(11):2600–2606 (https://www.pnas.org/doi/10.1073/pnas.1708274114). HARKing = hypothesizing after results are known, presented as a priori — matches the chapter's warning against letting prose/results generate the claim retroactively.

### Corrections
- None in the chapter body. (Minor adjacent note: the **pantry** research note `research-ch-01-…` cites "ICMJE Recommendations, updated January 2026." Verified ICMJE updates are **January 2024** and **January 2025**; I found no confirmed January 2026 version. The chapter file itself does not cite an ICMJE date, so the chapter is clean — but if the "2026" date migrates into prose during the enhance pass, it should read **"ICMJE Recommendations (2024/2025 updates)"** until a 2026 revision is confirmed. → https://www.icmje.org/news-and-editorials/updated_recommendations_jan2024.html)

### New to add
- **FINER criteria — Hulley, Cummings, Browner, Grady & Newman, *Designing Clinical Research* (Wolters Kluwer; criteria introduced in this textbook line).** FINER = **F**easible, **I**nteresting, **N**ovel, **E**thical, **R**elevant. (https://converge-training.colorado.edu/wp-content/uploads/2021/02/FINER-Criteria-for-Developing-Research-Questions-1.pdf). Strengthens the "What goes into the compression?" section — gives readers a named, transferable checklist for *evaluating* a candidate question, complementing the chapter's falsifiability test (which only handles testability, not feasibility/novelty/relevance). Good as a sidebar or one paragraph.
- **PICO framework (Population, Intervention, Comparison, Outcome)** — standard in evidence-based medicine; widely taught (Cochrane: https://www.cochranelibrary.com/about-pico; PICO process, Wikipedia: https://en.wikipedia.org/wiki/PICO_process). Strengthens the topic→question step: the chapter already implicitly uses P/I/C/O when it says a research question needs "a variable, a population, and an outcome." Naming PICO makes the move explicit and portable to clinical/health readers. Pairs naturally with the chapter's own example.
- **Chalmers & Glasziou (2009), "Avoidable waste in the production and reporting of research evidence," *The Lancet* 374(9683):86–89** (https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(09)60329-9/abstract). Their framework puts **"the relevance/framing of research questions" as the first of four sources of waste**, contributing to an estimated ~85% of research investment wasted. This is the missing *cost* argument: the chapter argues that a weak question is intellectually empty; Chalmers & Glasziou show it is also economically and scientifically wasteful. Strengthens the opening "momentum without a destination" section and the closing "the paper starts when you have the third thing."
- **Nosek et al. (2018), "The preregistration revolution," *PNAS*** (full cite above) — already in the pantry list but worth flagging as the strongest modern anchor for the chapter's central move: preregistration is the institutional form of "state the falsification condition before you see the result." Folds into the "what would have to be true for your paper to be wrong?" frame and the AI-shouldn't-choose-the-hypothesis section (HARKing is exactly the failure of letting the result/AI write the claim backwards).

### Deck beats to fold in
- **Deck slide 4 phrasing — "a claim that can't fail is advocacy, not a hypothesis."** This is crisper than the chapter's current "a claim that can accommodate any finding cannot be tested." The *advocacy* word does real work — it names the motive, not just the logical defect. Recommend folding the word "advocacy" in near Figure 1.4.
- **Deck's "defend it without notes or AI" test.** The chapter has the equivalent ("can you explain, in your own words, why this hypothesis and not a related alternative? If you need the AI to explain it, the AI did the work that should have been yours") — strong already. The deck's compression to a named *test* ("the defend-it-without-notes-or-AI test") is more memorable; consider promoting it to a named, boxed test rather than leaving it as a sentence.
- **Deck's three-layer schema (intent / evidence / structure).** Ch01 covers *intent* (the hypothesis layer) thoroughly; this vocabulary is worth a one-line forward reference so the reader sees Ch01–Ch02 as building the same schema, with Ch02 supplying the *evidence* layer.

---

## Chapter 02 — Foundation

### Verified
- **JARS = Journal Article Reporting Standards (APA).** Correct. The quantitative standards were published as **Appelbaum, Cooper, Kline, Mayo-Wilson, Nezu & Rao (2018), "Journal Article Reporting Standards for Quantitative Research in Psychology," *American Psychologist* 73(1):3–25.** A JARS-Qual companion (Levitt et al., 2018) exists in the same issue. → https://www.researchgate.net/publication/322587285 ; the standards trace to an APA Pub & Communications Board task force appointed 2015.
- **CONSORT = the reporting standard for randomized trials.** Correct. **CONSORT 2010 Statement** (Schulz, Altman & Moher for the CONSORT Group, *BMJ* 2010 / *PLoS Medicine*). The chapter's pairing of CONSORT with trial reporting is accurate. (Note: a **CONSORT 2025** update now exists; not required for the chapter, but the "2010" is still a correct and citable anchor.)
- **STROBE = the reporting standard for observational epidemiology.** Correct. **von Elm, Altman, Egger, Pocock, Gøtzsche & Vandenbroucke (2007), "The Strengthening the Reporting of Observational Studies in Epidemiology (STROBE) Statement," *PLoS Medicine* 4(10):e296.** Matches the chapter's "STROBE for observational epidemiology."
- **The design-licenses-claims logic** — RCT licenses causal language (within the randomized population); observational designs license "associated with / predicted / related to" but not "caused." This is mainstream causal-inference orthodoxy and is correctly stated. No overreach in the chapter's own claims.

### Corrections
- None in the chapter body. All three reporting standards (JARS/CONSORT/STROBE) are correctly named and correctly matched to their domains. The chapter is careful and accurate.
- Optional precision (not an error): the chapter says "JARS … specifies what methodological details readers need … for a psychology study." Accurate; could add that JARS-Quant explicitly *cross-references* CONSORT and STROBE-style flow reporting, which reinforces the chapter's point that these are one family of logic, not three unrelated checklists. → Appelbaum et al. 2018.

### New to add
- **Appelbaum et al. (2018), *American Psychologist* 73(1):3–25 (full cite above)** — currently only in the pantry note; should be the explicit in-text citation when the JARS sentence is enhanced, rather than the bare acronym. Same for von Elm et al. 2007 (STROBE) and Schulz/Altman/Moher 2010 (CONSORT). These are the load-bearing primary sources for the reporting-standards paragraph and the planned TABLE (line 66 of the chapter).
- **Nosek et al. (2018), "The preregistration revolution," *PNAS*** — strengthens the chapter's "second lock … the evidence plan." Preregistration is the mechanism that operationalizes "decide what design/sample/measure the claim requires *before* data," which is precisely the evidence-plan move. Good as the modern complement to the older reporting-standard citations.
- **(Optional, AI-era)** Bhattacharyya et al. (2023, *Cureus*; cite under Ch00) doubles as support for Ch02's "Exercise 6 / peer-review-doesn't-resolve-it" point and the "don't trust an AI source summary without opening the source" rule (LLM Exercise 2): with ~47% fabricated references, AI-produced source lists cannot be trusted as a source matrix without verification. Reinforces the chapter's existing "open the source" discipline.

### Deck beats to fold in
- **Deck's "intent / evidence / structure" three-layer schema (slide 3).** Ch02 *is* the evidence layer (source matrix + evidence plan), but the chapter never names it as such. Adding "this chapter builds the **evidence layer** of the schema" near the source-matrix introduction would tie it to Ch01's intent layer and the deck's framing, making the book's spine visible.
- **Deck's compression "build the argument/schema before the prose."** Ch02's closing ("The writing, when you finally begin it, goes faster … because you know what the material can bear") says the same thing well. The deck's *schema-before-prose* label is sharper; worth echoing the word "schema" once so the reader connects it across chapters.
- **Deck framing that design choice is "a commitment."** The chapter already uses "a study design is not just a method. It is a commitment" — this is strong and matches the deck. No change; just noting alignment.

---

## Cross-chapter notes / flags for the enhance pass

1. **Strongest single add across all three chapters:** the **Bhattacharyya et al. 2023 (47% fabricated / 46% inaccurate / 7% accurate)** statistic. It is the empirical spine of the whole "fluency ≠ validity" thesis and currently the book asserts the gap rather than quantifying it. Verified to primary source (Cureus / PMC).
2. **Named-frameworks gap:** Ch01 teaches the topic→question→hypothesis ladder by example but never names **FINER** or **PICO** — both are real, standard, citable, and would make the chapter's craft transferable to clinical/health/social-science readers. Verified.
3. **ICMJE date hygiene:** the pantry notes carry an unverified "January 2026" ICMJE date. Use 2024/2025 until a 2026 revision is confirmed. Chapters themselves are clean.
4. **No fabricated-citation risk introduced:** every citation above was run to a primary or authoritative source (journal/publisher/SEP/Cochrane/ICMJE). Nothing left "unverified" except the ICMJE-2026 date, which is explicitly flagged.
