# Research: Chapter 08 — How to Design a Graph
## The Research Paper Recipe

**Chapter one-line:** How to Design a Graph — Visual encoding, chart selection, honest figures [PLACEHOLDER]
**Research date:** 2026-05-29

---

## 1. Primary Sources

### Foundational papers and texts
- **Cleveland and McGill, _Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods_ (1984, JASA).** Foundational empirical source for visual encoding accuracy. Supports the channel hierarchy.
- **Heer and Bostock, _Crowdsourcing Graphical Perception_ (2010, CHI).** Replicates/extends graphical perception work using modern crowdsourcing; useful for showing the evidence base is empirical.
- **Weissgerber et al., _Beyond Bar and Line Graphs_ (2015, PLoS Biology).** Primary source for the critique of bar/line graphs hiding distributions in biological papers.
- **Pandey et al., _How Deceptive are Deceptive Visualizations?_ (2015, CHI).** Empirical evidence that truncated axes and other distortions affect reader judgment.

### Key empirical cases
- **Bar charts of means hiding different distributions.** Use Weissgerber examples to show why raw data or distribution plots matter.
- **Truncated y-axis message exaggeration.** Use a before/after bar chart to show proportional ink violation.
- **Scatterplot with strong association and causal temptation.** Teach annotation that association is not causation unless design supports it.

---

## 2. The Core Concept — State of the Field

### What is settled
Position on a common scale is perceived more accurately than angle, area, or hue. Chart form should match the question: comparison, distribution, relationship, time, or composition. Bar charts require zero baselines.

### What is disputed
Visualization experts debate how absolute some rules should be, especially truncated axes for line charts and minimalist data-ink applications. The chapter should distinguish distortion from purposeful focus.

### What has changed recently (last 5 years)
Interactive and AI-generated figures make chart creation faster but can embed misleading defaults. Accessibility and color-vision-safe palettes are now baseline expectations.

---

## 3. Application Domain Examples

- Select chart type from the reader task, not from habit.
- Show distributions rather than only means for small samples.
- Use zero baselines for bars and shared axes for comparison panels.
- Use direct labels and explicit units.

---

## 4. The Book's Thesis Connection

Figures are visual claims in the same evidence chain as prose and statistics. The student must decide what claim the figure makes; AI or chart software can render it but cannot decide whether the encoding is honest.

A self-directed student must bring their own disciplinary expertise to the examples: the relevant construct, the plausible comparison, the meaningful baseline, and the consequences of overclaiming. Tool output can help expose gaps, but it cannot certify that the research question matters or that the interpretation is warranted.

---

## 5. The AI Wayback Machine — Candidate Figures

- **William Cleveland.** Worked directly on graphical perception and statistical graphics. Prompt: Ask Cleveland which visual channel should encode the main comparison.
- **Jacques Bertin.** Developed semiology of graphics and visual variables. Prompt: Ask Bertin why hue cannot encode magnitude well.
- **Florence Nightingale.** Used statistical graphics for health reform. Prompt: Ask Nightingale how a figure becomes an argument.

Diversity note: candidates for this chapter may skew toward twentieth-century Euro-American philosophy, statistics, and scientific-writing traditions unless the later selection pass deliberately balances gender, geography, discipline, and era across the full book.

---

## 6. Pedagogical Delivery Research

Students often choose charts by software default. Teach with chart-matching cards: question -> data structure -> chart form -> possible misread.

Effective delivery should use worked examples, contrastive cases, and error diagnosis. The target reader needs to see not only the correct form but the plausible wrong form: the vague topic, the causal overclaim, the hidden proxy, the p-value-only result, the source-by-source literature review, or the fluent but unsupported sentence.

---

## 7. Representation and Display Research

Special display required: chart-type selection matrix plus one redesigned bad figure showing before/after.

---

## 8. Open Questions and Research Gaps

Need examples from the book's likely target disciplines, not only biomedical or education data.

Sources likely to age fastest: AI-disclosure policies, journal AI-use rules, and current platform tooling. Recheck against target journal instructions before drafting or submission.

---

## 9. Sourcing Notes

Primary sources are strongest for methodology, statistics, causal inference, visualization, and genre theory. Some practical guidance sources are textbooks, reporting guidelines, or editorial policies rather than empirical studies; use them as standards and pedagogical scaffolds, not as evidence that a learning intervention works. Verify exact journal AI-disclosure language, reporting checklists, and software recommendations immediately before drafting.

---

## 10. AI Use Research — When To Use AI / When NOT To Use AI


**Series calibration:** This book belongs to *Irreducibly Human: What AI Can and Can't Do*. Across chapters, AI should be framed as a tool for interrogation, audit, transformation, and drafting from a completed specification. It should not be framed as the source of the student's research question, causal judgment, construct definition, evidentiary standard, or accountability. Current publication guidance also matters: ICMJE's 2026 recommendations state that AI tools should not be listed as authors and that humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use. COPE and major publishers follow the same basic accountability principle.

### When to use AI
- Use AI to propose chart types from a stated reader task and data structure.
- Use AI to generate ggplot2, matplotlib, seaborn, or D3 code after the author specifies the intended claim and encoding.
- Use AI to audit a chart for truncated axes, unclear error bars, color accessibility, overplotting, or mismatched chart type.

### When NOT to use AI
- Do not let AI decide the visual claim of the figure. The author must state what the reader should learn in five seconds.
- Do not accept generated charts with uninspected defaults, unlabeled transformations, inaccessible color, or decorative distortion.
- Do not let AI-generated images invent data, labels, or relationships not in the dataset.

### Disclosure and accountability note
If AI generated figure code or draft visuals, disclose the tool/task when journal policy requires it and preserve the data, code, and final human-edited figure.

### Candidate classroom prompt
The reader task is [task] and the data structure is [variables]. Recommend the honest chart type, required annotations, accessibility checks, and one misleading chart type to avoid.

### Research/policy anchors
- ICMJE Recommendations, updated January 2026: AI tools should not be authors; humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use.
- COPE position statement on authorship and AI tools, 2023: AI tools cannot take responsibility for submitted work, so they cannot meet authorship requirements.
- Nature Portfolio AI policy family: generative AI use is policy-sensitive, developing rapidly, and must be disclosed or handled according to venue rules.

