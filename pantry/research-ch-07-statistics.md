# Research: Chapter 07 — Statistics
## The Research Paper Recipe

**Chapter one-line:** Statistics — Test selection, assumptions, power, reporting
**Research date:** 2026-05-29

---

## 1. Primary Sources

### Foundational papers and texts
- **Jacob Cohen, _A power primer_ (1992, Psychological Bulletin).** Accessible source for power, effect size, and the difference between statistical and practical significance. Use with caution about universal benchmarks.
- **Benjamini and Hochberg, _Controlling the False Discovery Rate_ (1995, Journal of the Royal Statistical Society B).** Primary source for FDR correction; supports multiple-comparisons section.
- **Ioannidis, _Why Most Published Research Findings Are False_ (2005, PLoS Medicine).** Metascience source connecting low power, bias, multiplicity, and false-positive findings.
- **Wasserstein and Lazar, _The ASA Statement on p-Values_ (2016, The American Statistician).** Modern consensus statement correcting common p-value misinterpretations.

### Key empirical cases
- **False-Positive Psychology simulations.** Demonstrates how optional stopping and analytic flexibility inflate false positives.
- **Open Science Collaboration reproducibility project.** Shows that statistically significant published findings may not replicate reliably.
- **Education intervention effect-size benchmarking.** Use Kraft's field-based education benchmarks to show context matters for effect size interpretation.

---

## 2. The Core Concept — State of the Field

### What is settled
A complete result needs test statistic, degrees of freedom where applicable, exact p-value, effect size, and uncertainty. Statistical significance is not practical importance, proof, or replicability.

### What is disputed
Debate continues over p-value thresholds, Bayesian alternatives, estimation-first reporting, and whether NHST should be abandoned or disciplined. The chapter should teach common practice while exposing limits.

### What has changed recently (last 5 years)
Many journals now encourage or require effect sizes, confidence intervals, open data/code, and preregistered analysis plans. AI-generated statistics code raises verification risk.

---

## 3. Application Domain Examples

- Choose tests from design and variable types.
- Report effect size and confidence interval with each result.
- Apply multiple-comparison corrections to planned test families.
- Run assumption checks before interpreting output.

---

## 4. The Book's Thesis Connection

The chapter enforces the evidence-to-interpretation link. Students must understand what the statistics say and do not say; AI can generate code, but the author owns the interpretation and reporting.

A self-directed student must bring their own disciplinary expertise to the examples: the relevant construct, the plausible comparison, the meaningful baseline, and the consequences of overclaiming. Tool output can help expose gaps, but it cannot certify that the research question matters or that the interpretation is warranted.

---

## 5. The AI Wayback Machine — Candidate Figures

- **Florence Nightingale.** Used statistics and graphics for public-health argument; diverse historical candidate. Prompt: Ask Nightingale why numbers need display and context.
- **Jacob Cohen.** Worked on power and effect sizes. Prompt: Ask Cohen why p-values are not enough.
- **Yoav Benjamini.** Co-developed FDR control. Prompt: Ask Benjamini how to think about many tests without pretending only one was run.

Diversity note: candidates for this chapter may skew toward twentieth-century Euro-American philosophy, statistics, and scientific-writing traditions unless the later selection pass deliberately balances gender, geography, discipline, and era across the full book.

---

## 6. Pedagogical Delivery Research

Misconceptions: p = .04 means a 4% chance the null is true; non-significant means no effect; large sample makes a result important. Teach through interpretation drills and incomplete-results repair.

Effective delivery should use worked examples, contrastive cases, and error diagnosis. The target reader needs to see not only the correct form but the plausible wrong form: the vague topic, the causal overclaim, the hidden proxy, the p-value-only result, the source-by-source literature review, or the fluent but unsupported sentence.

---

## 7. Representation and Display Research

A test-selection table is required: design / outcome / test / assumptions / reporting elements.

---

## 8. Open Questions and Research Gaps

Need care around advanced designs: multilevel, longitudinal, Bayesian, and qualitative mixed-methods require referral rather than oversimplification.

Sources likely to age fastest: AI-disclosure policies, journal AI-use rules, and current platform tooling. Recheck against target journal instructions before drafting or submission.

---

## 9. Sourcing Notes

Primary sources are strongest for methodology, statistics, causal inference, visualization, and genre theory. Some practical guidance sources are textbooks, reporting guidelines, or editorial policies rather than empirical studies; use them as standards and pedagogical scaffolds, not as evidence that a learning intervention works. Verify exact journal AI-disclosure language, reporting checklists, and software recommendations immediately before drafting.

---

## 10. AI Use Research — When To Use AI / When NOT To Use AI


**Series calibration:** This book belongs to *Irreducibly Human: What AI Can and Can't Do*. Across chapters, AI should be framed as a tool for interrogation, audit, transformation, and drafting from a completed specification. It should not be framed as the source of the student's research question, causal judgment, construct definition, evidentiary standard, or accountability. Current publication guidance also matters: ICMJE's 2026 recommendations state that AI tools should not be listed as authors and that humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use. COPE and major publishers follow the same basic accountability principle.

### When to use AI
- Use AI to map design, variable type, independence, and time structure to candidate statistical tests.
- Use AI to generate assumption-checking code and reporting templates that include test statistic, degrees of freedom, p-value, effect size, and confidence interval.
- Use AI to explain statistical output in plain language for author review.

### When NOT to use AI
- Do not let AI choose the final analysis without human statistical understanding or methodologist review for complex designs.
- Do not accept AI defaults for model specification, reference levels, missing data, covariates, or multiple-comparison correction.
- Do not use AI to interpret significance as proof, importance, causation, or replicability.

### Disclosure and accountability note
If AI generated statistical code or helped interpret output, disclose the task and note that code and results were human-verified against the analysis plan.

### Candidate classroom prompt
Here is my design and variable list. Recommend possible tests, state assumptions, give assumption-checking code, and list decisions I must verify manually before reporting.

### Research/policy anchors
- ICMJE Recommendations, updated January 2026: AI tools should not be authors; humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use.
- COPE position statement on authorship and AI tools, 2023: AI tools cannot take responsibility for submitted work, so they cannot meet authorship requirements.
- Nature Portfolio AI policy family: generative AI use is policy-sensitive, developing rapidly, and must be disclosed or handled according to venue rules.

