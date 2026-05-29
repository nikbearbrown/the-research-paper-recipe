# Research: Chapter 06 — GIGO: Garbage In, Garbage Out
## The Research Paper Recipe

**Chapter one-line:** GIGO — Data quality check before analysis
**Research date:** 2026-05-29

---

## 1. Primary Sources

### Foundational papers and texts
- **Little and Rubin, _Statistical Analysis with Missing Data_ (2002/2019, book).** Primary reference for MCAR, MAR, MNAR and why missingness mechanisms matter before analysis.
- **Cronbach, _Coefficient Alpha and the Internal Structure of Tests_ (1951, Psychometrika).** Supports internal consistency checks for composite scales, while also inviting caution about overusing alpha.
- **Gelman and Loken, _The Garden of Forking Paths_ (2013, paper/preprint).** Explains how many reasonable analytic choices can bias results without intentional p-hacking. Essential for data-processing decisions before analysis.
- **Simmons, Nelson, and Simonsohn, _False-Positive Psychology_ (2011, Psychological Science).** Shows how flexibility in data collection, exclusions, covariates, and analysis can produce false positives.

### Key empirical cases
- **Missing not at random dropout in intervention studies.** Participants harmed or least helped may leave before outcome measurement, inflating apparent effectiveness.
- **Spreadsheet gene-name autocorrection errors.** A documented data-quality failure where software silently changed gene symbols to dates; good for showing mundane corruption.
- **Outlier exclusion after seeing p-values.** Illustrative classroom case demonstrating how defensible exclusions become biased if decided post-hoc.

---

## 2. The Core Concept — State of the Field

### What is settled
Bad raw data cannot be rescued by sophisticated analysis. Missingness, ambiguous instruments, inconsistent scoring, unplanned exclusions, and incoherent composites must be diagnosed before the main test.

### What is disputed
The best remedies for missing data and outliers depend on mechanism and design. There is no universally correct imputation or exclusion rule; transparent pre-specification matters more than ritual.

### What has changed recently (last 5 years)
Automated data pipelines and AI-assisted cleaning increase both speed and hidden transformation risk. Reproducible scripts and data provenance are becoming baseline expectations.

---

## 3. Application Domain Examples

- Run impossible-value checks before statistics.
- Create a missingness table by variable and group.
- Pre-specify outlier rules before examining outcomes.
- Compute reliability before using composite scores.

---

## 4. The Book's Thesis Connection

This chapter protects the evidence layer of the schema. The student must know how the data were produced and what corruption would mean in context; AI can generate checklists and code but cannot certify data provenance.

A self-directed student must bring their own disciplinary expertise to the examples: the relevant construct, the plausible comparison, the meaningful baseline, and the consequences of overclaiming. Tool output can help expose gaps, but it cannot certify that the research question matters or that the interpretation is warranted.

---

## 5. The AI Wayback Machine — Candidate Figures

- **Donald Rubin.** Worked directly on missing data and causal inference. Prompt: Ask Rubin when missing data are informative rather than nuisance.
- **Lee Cronbach.** Alpha and measurement reliability. Prompt: Ask Cronbach why a composite score can be precise but wrong.
- **Grace Wahba.** Pioneer in statistical modeling and smoothing, useful for data quality and model judgment. Woman statistician, Wikipedia-accessible. Prompt: Ask Wahba what a model cannot know about bad inputs.

Diversity note: candidates for this chapter may skew toward twentieth-century Euro-American philosophy, statistics, and scientific-writing traditions unless the later selection pass deliberately balances gender, geography, discipline, and era across the full book.

---

## 6. Pedagogical Delivery Research

Students often treat cleaning as clerical rather than inferential. Teach by showing how three missingness mechanisms produce the same blank cell but different validity consequences.

Effective delivery should use worked examples, contrastive cases, and error diagnosis. The target reader needs to see not only the correct form but the plausible wrong form: the vague topic, the causal overclaim, the hidden proxy, the p-value-only result, the source-by-source literature review, or the fluent but unsupported sentence.

---

## 7. Representation and Display Research

A data-quality checklist/table is required: problem / diagnostic / consequence / pre-specified response.

---

## 8. Open Questions and Research Gaps

Need field-specific examples of data corruption beyond education and psychology, especially lab, archival, and finance datasets.

Sources likely to age fastest: AI-disclosure policies, journal AI-use rules, and current platform tooling. Recheck against target journal instructions before drafting or submission.

---

## 9. Sourcing Notes

Primary sources are strongest for methodology, statistics, causal inference, visualization, and genre theory. Some practical guidance sources are textbooks, reporting guidelines, or editorial policies rather than empirical studies; use them as standards and pedagogical scaffolds, not as evidence that a learning intervention works. Verify exact journal AI-disclosure language, reporting checklists, and software recommendations immediately before drafting.

---

## 10. AI Use Research — When To Use AI / When NOT To Use AI


**Series calibration:** This book belongs to *Irreducibly Human: What AI Can and Can't Do*. Across chapters, AI should be framed as a tool for interrogation, audit, transformation, and drafting from a completed specification. It should not be framed as the source of the student's research question, causal judgment, construct definition, evidentiary standard, or accountability. Current publication guidance also matters: ICMJE's 2026 recommendations state that AI tools should not be listed as authors and that humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use. COPE and major publishers follow the same basic accountability principle.

### When to use AI
- Use AI to generate data-quality checklists from variable names, collection procedures, and expected ranges.
- Use AI to write auditable code for missingness tables, impossible-value checks, duplicate checks, and reliability calculations.
- Use AI to suggest likely missingness mechanisms or data-entry failures to investigate.

### When NOT to use AI
- Do not run AI-generated cleaning or analysis code on the only copy of the data without review and backup.
- Do not upload confidential, identifiable, or restricted data into tools whose data handling is not approved.
- Do not let AI choose exclusion, outlier, or imputation rules after seeing which choice improves results.

### Disclosure and accountability note
If AI generated cleaning code or data-quality checks, disclose the task and preserve reviewed code. If data were sensitive, document that no restricted data were uploaded to unapproved systems.

### Candidate classroom prompt
Given these variables, collection method, and expected ranges, create a pre-analysis data-quality checklist and code comments for checks I should run before modeling.

### Research/policy anchors
- ICMJE Recommendations, updated January 2026: AI tools should not be authors; humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use.
- COPE position statement on authorship and AI tools, 2023: AI tools cannot take responsibility for submitted work, so they cannot meet authorship requirements.
- Nature Portfolio AI policy family: generative AI use is policy-sensitive, developing rapidly, and must be disclosed or handled according to venue rules.

