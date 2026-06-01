# Enrichment & verification notes — Ch.07 (Statistics) and Ch.08 (How to Design a Graph)

Verify-and-enrich pass against deck Module 4 core (slides 16–23). Fact-check + research only.
All numeric claims independently recomputed; all historical/citation claims confirmed against primary or authoritative sources. No corrections were required — every checkable claim in both chapters is accurate.

---

## Chapter 07 — Statistics

### Verified (claim → source, with confirmed numbers)

- **p-value is not the probability the null is true / not the probability you're right.** Chapter framing is correct: p = probability of data at least as extreme, *assuming H₀ true*. This is exactly Principle 2 of the ASA statement. Source: Wasserstein, R.L. & Lazar, N.A. (2016), "The ASA Statement on p-Values: Context, Process, and Purpose," *The American Statistician* 70(2): 129–133. DOI 10.1080/00031305.2016.1154108. https://www.tandfonline.com/doi/full/10.1080/00031305.2016.1154108 — Confirmed: ASA's first-ever formal position statement on a statistical practice, approved 29 Jan 2016, published online 9 Jun 2016. Chapter's "issued a formal statement in 2016" and the "measure of surprise under a model" gloss are accurate.

- **ASA 2016 warned against over-reliance on p<.05.** Confirmed (above). The deck's claim 4 holds.

- **Cohen's d benchmarks 0.2 / 0.5 / 0.8 (small/medium/large) and that they are conventions, not laws.** Source: Cohen, J. (1988), *Statistical Power Analysis for the Behavioral Sciences* (2nd ed.), Lawrence Erlbaum, Hillsdale NJ. ISBN 0805802835. Confirmed d = .20 small, .50 medium, .80 large; Cohen explicitly framed them as conventions for use when no better field reference exists — chapter's caveat ("not as universal standards") matches Cohen's own intent.

- **SE = SD/√n; t = Δ/SE; d = Δ/SD_pooled with no √n.** Recomputed and correct (relationships are definitional). The chapter's algebra is sound: as n↑, √n↑, SE↓, t↑, p↓ for any nonzero Δ.

- **Wellness-app worked example (ch07 ¶ at line 60).** Recomputed exactly: SD=10, n=10,000 → SE = 10/√10000 = 10/100 = **0.10**; t = 0.4/0.10 = **4.0**; two-sided p for z/t≈4.0 ≈ **6.3e-5 ≈ .0001** (chapter says "p ≈ .0001" — correct); d = 0.4/10 = **0.04** (correct). All three numbers verified.

- **Fisher developed significance testing/p-values in the 1920s for small agricultural field plots.** Source: Fisher joined Rothamsted Experimental Station in 1919; *Statistical Methods for Research Workers* (1925, Oliver & Boyd) and *The Design of Experiments* (1935, Oliver & Boyd) formalized significance testing, the null hypothesis, ANOVA, and randomization on small agricultural plots. https://en.wikipedia.org/wiki/Statistical_Methods_for_Research_Workers ; https://en.wikipedia.org/wiki/The_Design_of_Experiments — Dates and small-sample agricultural context confirmed. (Chapter says "1920s" and "a few dozen observations" — defensible; the deck's "~30-row field plots" is illustrative-but-fair.)

- **Gosset published the t-distribution as "Student," 1908, in *Biometrika*, while at Guinness.** Source: Student [W.S. Gosset] (1908), "The Probable Error of a Mean," *Biometrika* 6(1): 1–25. Confirmed: pen name "Student" used because Guinness treated statistical methods as a trade secret; derived to handle the small samples a brewery could afford. https://en.wikipedia.org/wiki/William_Sealy_Gosset — Chapter's paragraph (line 70) is accurate in every particular.

- **df = n − constraints; fewer df → fatter tails → larger t needed; Z assumes σ known, t estimates σ.** Conceptually correct as stated; standard textbook treatment.

- **t-vs-Z convergence numbers.** Independently computed (scipy, two-tailed .05 critical values; Z = 1.95996):
  - df=30 → t = 2.0423
  - **df=60 → t = 2.0003** (chapter & deck say "≈2.00 vs Z 1.96" — confirmed exact)
  - df=120 → t = 1.9799
  - **df=200 → t = 1.9719** (deck: "agree to 3 digits by df≈200." Strictly, t=1.972 vs Z=1.960 still differ in the 3rd digit — they agree to ~3 *significant* figures / within ~0.6%, not to three decimal places. The task brief's own wording, "agree to ~3 sig figs," is the accurate phrasing; the chapter avoids the issue by saying "by a few hundred observations the gap is under half a percent," which is correct: at df=200 the gap is 0.6%, at df=500 it is 0.26%.)
  - df=∞ → t = Z by definition (confirmed).
  - **n≈60 / n≈120 / n≈10,000 thresholds:** these are illustrative rules of thumb, not exact law — and the chapter correctly hedges them ("around," "somewhere near"). Defensible: by df=60 the t-correction is ~2%; by df=120 the t-vs-Z gap is ~1%; p-as-filter degradation near n=10,000 is scenario-dependent (it is where the wellness example's trivial d=0.04 hits p=.0001). Keep all three labeled as rules of thumb.

- **Family-wise error: 20 independent tests at α=.05 → ~64%.** Recomputed: 1 − 0.95²⁰ = **0.6415** (chapter says "roughly 64%" — confirmed).

- **Winner's curse / inflated effects in underpowered studies; power depends on effect size, n, α.** Standard and correct; consistent with the replication-crisis literature.

- **Benjamini–Hochberg controls FDR and is less conservative than Bonferroni.** Correct as stated.

### Corrections
None. No numeric or factual error found in Ch.07. (One precision nuance only: see the df≈200 note above — the chapter's own wording is already correct; the only place to watch is if anyone restates the deck's "3 digits" as "3 decimal places," which would be wrong. t at df=200 = 1.972, not 1.960.)

### New to add (full citations — all verified)
- **Wasserstein, R.L., Schirm, A.L. & Lazar, N.A. (2019), "Moving to a World Beyond 'p < 0.05'," *The American Statistician* 73(sup1): 1–19.** DOI 10.1080/00031305.2019.1583913. https://www.tandfonline.com/doi/full/10.1080/00031305.2019.1583913 — The ASA's 2019 follow-up editorial to the 2016 statement, leading a 43-article special issue ("Statistical Inference in the 21st Century"). Goes further than 2016: recommends dropping the term "statistically significant" entirely. The chapter cites only the 2016 statement; the 2019 editorial is the stronger, more current capstone and should at minimum be footnoted.
- **Amrhein, V., Greenland, S. & McShane, B. (2019), "Scientists rise up against statistical significance," *Nature* 567(7748): 305–307.** DOI 10.1038/d41586-019-00857-9. https://www.nature.com/articles/d41586-019-00857-9 — Comment co-signed by 854 researchers calling to retire the dichotomous use of significance. High-visibility, directly supports the chapter's thesis. (Note: the popular short title "Retire statistical significance" is the headline; *Nature*'s published title is "Scientists rise up against statistical significance.")
- **Benjamin, D.J., Berger, J.O., Johannesson, M., Nosek, B.A., Wagenmakers, E.-J., et al. (2018), "Redefine statistical significance," *Nature Human Behaviour* 2: 6–10.** DOI 10.1038/s41562-017-0189-z. https://www.nature.com/articles/s41562-017-0189-z — Proposes lowering the default new-discovery threshold from p<.05 to p<.005. Useful as a contrasting reform position (redefine vs. retire); pairs well with Amrhein et al. to show the field is actively debating the fix, not settled.

### Deck beats to fold in (where the deck is sharper than the chapter)
- The chapter buries the "what breaks at scale" hierarchy in prose (line 76). The deck states it as a clean ladder — **df-correction gone by n≈60, t-vs-Z gone by n≈120, p-as-filter gone by n≈10,000; effect size, CIs, and practical significance survive at any n.** This is the chapter's single sharpest idea and would land harder as an explicit list or the table already stubbed at line 88.
- Deck's "report test statistic, df, exact p, AND effect size" is crisper as a four-item checklist than the chapter's running sentence at line 82 (which the chapter does deliver well at the example, line 86 — the deck just front-loads it).
- The deck's framing "could this be noise? ≠ does this matter?" (statistical vs. practical significance) is exactly the chapter's line-84 point; the deck phrases it as a memorable two-question test worth quoting verbatim.

---

## Chapter 08 — How to Design a Graph

### Verified (claim → source, with confirmed numbers)

- **Cleveland–McGill perceptual accuracy hierarchy: position on common scale > length > angle/direction > area > color/saturation.** Source: Cleveland, W.S. & McGill, R. (1984), "Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods," *Journal of the American Statistical Association* 79(387): 531–554. DOI 10.1080/01621459.1984.10478080. https://www.tandfonline.com/doi/abs/10.1080/01621459.1984.10478080 — Confirmed: their "elementary perceptual tasks" ranking (position along common scale, position on non-aligned scales, length, direction/angle, area, volume/curvature, shading/color saturation). Chapter's ordering at lines 20 and 24–26 matches the paper. "Series of experiments in the 1980s" — accurate (1984 JASA, plus follow-ups).

- **Bar charts of means hide distributional structure.** Source: Weissgerber, T.L., Milic, N.M., Winham, S.J. & Garovic, V.D. (2015), "Beyond Bar and Line Graphs: Time for a New Data Presentation Paradigm," *PLOS Biology* 13(4): e1002128. DOI 10.1371/journal.pbio.1002128. https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128 — Confirmed: a review of n=703 articles in top physiology journals found continuous data routinely presented as bar/line graphs; the authors show four different distributions (bimodal, unequal-n, outlier-driven, etc.) yielding identical bar graphs. The chapter's attribution at line 38 ("Weissgerber and colleagues demonstrated that bar graphs in biomedical research routinely hide distributional structure") is accurate.

- **Error-bar trilemma: SD vs SE vs 95% CI; SE = SD/√n; CI ≈ 1.96·SE.** Recomputed/confirmed: 95% CI half-width = z₀.₉₇₅ · SE = 1.95996·SE ≈ 1.96·SE (chapter line 74). SD captures ~68% of a normal distribution at ±1 SD (line 70) — correct. The √n-shrinkage point cross-links cleanly to Ch.07's mechanism (chapter does this explicitly, line 72).

- **Zero-baseline rule for bars; bars encode length so a truncated baseline decouples visual length from value.** Correct, and this is the textbook rationale (length is the encoding channel; perception reads bar length, not bar-top position).

- **Area must be proportional to value → radius ∝ √value.** Correct: area scales as the square of linear dimension, so radius set ∝ value over-inflates by the square. Chapter line 60 is right.

- **Color vision deficiency prevalence ~8% of men, ~0.5% of women; red-green most common.** Confirmed against multiple authoritative sources (MedlinePlus Genetics; AOA; NIH/PMC review): ~8% of men and ~0.5% of women of Northern European descent (~1 in 12 men, 1 in 200 women); red-green deficiency ≈ 99% of cases, X-linked. https://medlineplus.gov/genetics/condition/color-vision-deficiency/ — Chapter line 90 is accurate. (Minor: these figures are highest in Northern-European-descent populations; "approximately 8%" is the standard textbook figure and fine to keep.)

- **Lightness perception is more ordered than hue → heatmaps should encode magnitude by lightness, not hue.** Correct and consistent with perceptual-uniformity rationale behind viridis/cividis. viridis and cividis are real, widely-available perceptually-uniform, colorblind-safe palettes; ColorBrewer (Brewer) is the standard categorical/sequential palette source.

### Corrections
None. No numeric or factual error found in Ch.08.

### New to add (full citations — all verified)
- **Wilke, C.O. (2019), *Fundamentals of Data Visualization*, O'Reilly Media.** ISBN 978-1492031086. Free online: https://clauswilke.com/dataviz/ — The current standard practitioner reference. Directly covers the chapter's themes (encoding channels, distribution display, error-bar ambiguity, color/accessibility). Strong modern citation to anchor the chapter beyond the 1984 and 2015 primary sources. (Wilke also authored a widely-cited blog post extending Weissgerber's "beyond bar and line graphs" argument.)
- **Cairo, A. (2019), *How Charts Lie: Getting Smarter about Visual Information*, W.W. Norton.** ISBN 978-1324001560 — Accessible treatment of exactly the chapter's opening case (truncated axes, misleading area, the graph-as-argument thesis). Good for the warm-up/challenge exercises.
- **Optional deeper cut — Heer, J. & Bostock, M. (2010), "Crowdsourcing Graphical Perception," *Proc. CHI 2010*: 203–212.** DOI 10.1145/1753326.1753357 — Replicated and extended Cleveland–McGill on Mechanical Turk; supports the chapter's line-20 claim that the hierarchy was "replicated and extended by later researchers." Cite only if a modern replication anchor is wanted.

### Deck beats to fold in
- Module 4's core insight — that the **√n in SE is the same mechanism that lets a standard-error bar look tight while individual scores are wide** — is already in the chapter (line 72) and is the strongest Ch.07↔Ch.08 bridge in the book. Keep it; the deck validates it as a deliberate cross-link, not an accident.
- The deck's "report everything but lead with effect size + CI" maps onto Ch.08's caption principle (state the visual claim + give the CI). Worth making explicit that the figure's error bars should be CIs (not SE) for the same reason the text reports CIs — the chapter implies this (line 74 calls CI "the most interpretable form") but could state the parallel outright.

---

## Summary (numeric discrepancies and findings)
- **All checkable claims in both chapters verified; zero corrections required.** Every numeric worked example recomputed exactly: wellness SE=0.10, t=4.0, p≈.0001, d=0.04 (✓); 20-test family-wise = 0.6415 ≈ 64% (✓); CI ≈ 1.96·SE (✓); radius ∝ √value (✓).
- **t-vs-Z values recomputed (scipy):** df=60 → t=2.0003 vs Z=1.95996 (✓ "≈2.00 vs 1.96"); df=∞ → equal (✓).
- **One precision nuance, not an error:** the deck's shorthand "agree to 3 digits by df≈200" should be read as ~3 significant figures / within ~0.6%, not three decimal places (t at df=200 = 1.972, not 1.960). The chapter itself sidesteps this correctly ("gap under half a percent by a few hundred observations"). Flag only so no future edit restates it as "3 decimal places."
- **The n≈60 / 120 / 10,000 thresholds are sound illustrative rules of thumb; the chapter already hedges them with "around"/"near" — keep that hedging.**
- **Historical/citation claims all confirmed:** Gosset 1908 *Biometrika* "The Probable Error of a Mean" at Guinness (✓); Fisher 1925/1935 at Rothamsted, small agricultural plots (✓); Cohen 1988 0.2/0.5/0.8 as conventions (✓); ASA 2016 (Wasserstein & Lazar) (✓); Cleveland–McGill 1984 JASA hierarchy (✓); Weissgerber 2015 PLOS Biology (✓); 8%/0.5% colorblindness (✓).
- **Strongest additions:** ASA 2019 follow-up (Wasserstein, Schirm & Lazar), Amrhein/Greenland/McShane *Nature* 2019, and Benjamin et al. *Nat. Hum. Behav.* 2018 for Ch.07; Wilke *Fundamentals of Data Visualization* (2019) and Cairo *How Charts Lie* (2019) for Ch.08.
