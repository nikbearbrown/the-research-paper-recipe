# Enrichment Pass — The Research Paper Recipe

## Run: 2026-05-31
Seeded by the 37-slide "Research Paper Recipe" slide deck (saved at `research/source-slide-deck.md`). Two phases: (1) verify the deck's specific claims + the chapters' existing claims against current primary sources and pull newer findings; (2) fold the results into the 15 chapters at **verify+enrich** depth — structure, voice, and length preserved.

## Verification result
The book was already factually clean. Across all six research groups, **no major errors** were found — only minor citation-precision fixes and several places where the deck's framing was sharper than the prose.

### Corrections applied
- **ch05** — credited **Elizabeth Bjork** alongside Robert Bjork as co-originator of the storage-vs-retrieval-strength framework (Bjork & Bjork 1992).
- **ch06** — "garden of forking paths" now cites the **published Gelman & Loken 2014** (*American Scientist*), not the 2013 working paper; MCAR/MAR/MNAR re-anchored to **Rubin 1976 + Little & Rubin 2019**.
- **ch10** — the "experts read figures/Discussion first" claim **softened** from asserted fact to "experienced readers report…" (practitioner self-report, cite Pain, *Science*/AAAS 2016) — it is not measured reading-behaviour research.
- **ch13** — "positive results increased over time" now cites **Fanelli 2012** (*Scientometrics*), not the 2010 PLOS ONE paper.
- **ch07** — no numeric change (every worked figure recomputed exact: SE 0.10, t 4.0, p≈.0001, d 0.04; 20-test family-wise ≈64%; df=60 → t 2.000 vs Z 1.960).

### New verified sources folded in (selected)
- **ch00/01/09** — Bhattacharyya et al. 2023 (*Cureus*, ChatGPT references 47% fabricated) and Walters & Wilder 2023 (*Sci. Reports*, ~55%/~18% fabrication GPT-3.5/GPT-4) to ground the fluency-vs-validity and citation-hallucination claims; FINER (Hulley et al.) + PICO (Richardson 1995); Chalmers & Glasziou 2009 (research waste); Nosek et al. 2018 (confirmatory/exploratory, HARKing).
- **ch03/04** — Altman & Bland 1995 + Lakens 2017 (underpowered nulls / TOST); Hume (is/ought); Neyman–Pearson 1933; Holland 1986 + Rubin 1974; Pearl & Mackenzie *Book of Why* 2018; Hernán & Robins 2020; Cunningham 2021; Angrist & Pischke 2009 (DiD/RDD/IV); Hill 1965.
- **ch05/06** — Latimier, Peyre & Ramus 2021 (spacing meta, g≈0.74); Kane 2013 + *Standards* 2014; coefficient-omega note (McNeish 2018; Flora 2020).
- **ch07/08** — ASA 2019 follow-up (Wasserstein, Schirm & Lazar); Amrhein, Greenland & McShane 2019 (*Nature*); Benjamin et al. 2018; Wilke 2019; Cairo 2019 — alongside existing ASA 2016, Cleveland & McGill 1984, Weissgerber 2015.
- **ch09/10** — Swales *Genre Analysis* 1990; PRISMA 2020; Whitesides 2004; Appelbaum et al. 2018 (JARS); Hartley 2014.
- **ch11–14** — Brown & Heathers 2017 (GRIM); Rothwell & Martyn 2000 + Bornmann et al. 2010 (reviewer agreement); Gopen & Swan 1990; Williams & Bizup *Style*; Sword 2012 (zombie nouns); Hyland 1998/2005; Open Science Collaboration 2015; Chambers & Tzavella 2022.

### Deck framings surfaced
- ch01: "a claim that can't fail is advocacy"; the **defend-it-without-notes-or-AI** test; intent/evidence/structure schema vocabulary.
- ch03: the **Cartesian** "what would I have to observe to conclude this is wrong?" prompt; the **sponge** metaphor.
- ch04: "causal claim → randomized or strong quasi-experiment; no statistical workaround" + DiD/RDD/IV roster.
- ch05: the measurement **hierarchy** (upstream flaw corrupts downstream); Plato's-cave / "the score is not the student."
- ch07: the **"what breaks at scale"** ladder (df-correction ~n60, t-vs-Z ~n120, p-as-filter ~n10,000) surfaced as a compact hedged table.
- ch10: all **three** reading/writing orders named; Discussion **four moves** as a checklist; abstract **five-sentence skeleton**; "never close with 'more research is needed'."
- ch11/14: the full **claim-calibration ladder** in one place (labelled the book's own heuristic, not a codified standard); the **throat-clearing** fog item added to ch14; the **Thinking → Writing → Auditing** phase-gate spine named.

### Currency (verified to May 2026)
AI-disclosure policy stated firmly with named, current citations: Nature (AI cannot be a listed author), Science/AAAS (Nov 2023 disclosure), ICMJE (Jan 2025 recommendations), COPE (Feb 2023), NIH NOT-OD-23-149 (June 2023, AI banned in grant peer review).

## Honesty flags carried forward
- The 5-rung verb→design calibration ladder is the book's **own pedagogy**, not a published standard — labelled as such in ch11/14.
- The "experts read figures-first" order is **practitioner self-report**, labelled as such in ch10.
- The n≈60 / 120 / 10,000 scale thresholds are **illustrative rules of thumb**, hedged in ch07.
- No fabricated citations anywhere; the André outlier-blinding paper (bibliographic detail unverified) was stated as a principle without a specific cite.

## Outputs
Enrichment notes: `research/enrich-ch-00-02.md`, `enrich-ch-03-04.md`, `enrich-ch-05-06.md`, `enrich-ch-07-08.md`, `enrich-ch-09-10.md`, `enrich-ch-11-14.md`. Source deck: `research/source-slide-deck.md`. All 15 content chapters edited; each now ends with a `## Sources` section.
