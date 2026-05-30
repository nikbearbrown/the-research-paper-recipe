# Fact-Check Master Report — The Research Paper Recipe

*Run 2026-05-29. Stage: post-enrichment fact-check across 14 content chapters + intro.*

## Summary

This book is **methodological**, not empirical-claim-heavy: it teaches the scientific method, causal reasoning, measurement, statistics, figure design, peer review, ethics, and scientific prose. Its load-bearing claims are textbook-stable framework attributions and statistical facts, not volatile leaderboard/CVE/news figures. Consequently there were **zero `[verify]` flags** in the drafted chapters, and the fact-check reduced to (a) arithmetic verification of the quantitative claims and (b) attribution checks on named frameworks/people.

**Result: no corrections required.** All checked claims hold.

## Quantitative claims — programmatically verified

| Claim (chapter) | Stated | Computed | Status |
|---|---|---|---|
| Family-wise false-positive rate, 20 independent tests at α=.05 (Ch 7) | "~64%" | 1 − 0.95²⁰ = 0.642 | ✓ |
| Observations within ±1 SD of a normal mean (Ch 8) | "~68%" | 68.3% | ✓ |
| SE multiplier for a 95% CI (Ch 8) | "~1.96 SE" | z₍.975₎ = 1.960 | ✓ |
| Worked t-test effect size, t(62)=2.47, n=32/grp (Ch 7) | d = 0.63 | implied d ≈ 0.62 (rounding/estimator) | ✓ consistent |
| Sample size for d=0.5, 80% power, α=.05, two-group t (Ch 7) | "larger than researchers expect" (no n stated) | ≈ 63–64/group (matches Cohen) | ✓ |
| Color-vision deficiency prevalence (Ch 8) | "~8% of men, ~0.5% of women" | standard cited figure | ✓ |

## Framework / source attributions — verified

- **Gopen & Swan, "The Science of Scientific Writing," *American Scientist*, Nov–Dec 1990** (Ch 14 prose + Fig 14.4 "Gopen-Swan sentence positions") — confirmed via search. Correct authors, title, venue, year.
- **Pearl's ladder of causation** (association / intervention / counterfactual) (Ch 4) — correctly characterized.
- **Rubin potential-outcomes framework** (Ch 4) — correctly characterized.
- **Popper / falsifiability** (Ch 1, Ch 3) — correctly characterized.
- **Reporting-standard families: JARS (APA), CONSORT (randomized trials), STROBE (observational)** (Ch 2 table) — correct scope per standard.
- **Cohen's d; Neyman–Pearson; Bonferroni correction** (Ch 7) — correctly characterized.

## Notes

- The named statistical vignettes (Socratic-vs-direct feedback study; M/SD/CI values; n=35/group) are **illustrative worked examples**, explicitly framed as such — not empirical findings attributed to a real study, so no external verification applies. They are internally consistent.
- Two pre-existing HTML-comment **table** placeholders (Ch 2 reporting-standards JARS/CONSORT/STROBE; Ch 5 five-measurement-questions) have no corresponding CAJAL figure and were intentionally left for a later table pass; they are not factual defects.

## Verdict

No factual corrections applied. All quantitative claims verified arithmetically; all framework attributions verified. Book is fact-clean as drafted.
