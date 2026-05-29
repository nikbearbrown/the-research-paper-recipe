# Research: Chapter 04 — What Does Causal Mean, Exactly?
## The Research Paper Recipe

**Chapter one-line:** What Does Causal Mean, Exactly? — Counterfactuals, DAGs, Pearl's hierarchy [PLACEHOLDER]
**Research date:** 2026-05-29

---

## 1. Primary Sources

### Foundational papers and texts
- **Donald B. Rubin, _Estimating Causal Effects of Treatments in Randomized and Nonrandomized Studies_ (1974, Journal of Educational Psychology).** Foundational potential-outcomes source; directly supports counterfactual framing and the idea that causal effects compare observed and unobserved states.
- **Judea Pearl, _Causality: Models, Reasoning, and Inference_ (2000/2009, book).** Primary source for structural causal models and DAG-based reasoning. This chapter can use it to make assumptions visible.
- **Hernán and Robins, _Causal Inference: What If_ (2020, open textbook).** Best practical bridge for students: treatment strategies, exchangeability, positivity, consistency, and target trials.
- **Angrist and Pischke, _Mostly Harmless Econometrics_ (2009, book).** Useful for natural experiments, instrumental variables, differences-in-differences, and regression discontinuity as practical identification strategies.

### Key empirical cases
- **Smoking and lung cancer causal inference.** Shows how causal claims can become strong without simple randomized assignment, using converging evidence and mechanisms.
- **Oregon Health Insurance Experiment.** A natural experiment useful for distinguishing randomized access from treatment received.
- **Minimum wage difference-in-differences studies.** Good example of causal identification debate, assumptions, and contested interpretation.

---

## 2. The Core Concept — State of the Field

### What is settled
Causal claims require assumptions beyond association. Randomization helps by balancing confounders in expectation; observational causal inference requires explicit assumptions, design logic, and sensitivity to confounding, mediation, and collider bias.

### What is disputed
There are active disagreements between DAG, potential-outcomes, econometric, and domain-specific traditions about notation, emphasis, and what counts as credible identification. The chapter should not present one framework as total victory.

### What has changed recently (last 5 years)
Causal inference has become central in machine learning, policy evaluation, and epidemiology, but automated causal discovery remains fragile. AI-generated DAGs should be treated as assumption drafts, not evidence.

---

## 3. Application Domain Examples

- Draw a DAG from a verbal hypothesis and mark confounders, mediators, and colliders.
- Translate a causal claim into a counterfactual question.
- Audit every causal verb in a Discussion.
- Choose between rewriting the claim or strengthening the design.

---

## 4. The Book's Thesis Connection

This chapter prevents the most dangerous design/claim mismatch in the book: writing causation when the evidence supports association. The student must supply domain knowledge about plausible confounders and mechanisms.

A self-directed student must bring their own disciplinary expertise to the examples: the relevant construct, the plausible comparison, the meaningful baseline, and the consequences of overclaiming. Tool output can help expose gaps, but it cannot certify that the research question matters or that the interpretation is warranted.

---

## 5. The AI Wayback Machine — Candidate Figures

- **Donald Rubin.** Worked directly on potential outcomes and treatment effects. Famous in statistics, less known to general students. Prompt: Ask Rubin what outcome is missing when we say X caused Y.
- **Judea Pearl.** Developed structural causal models and do-calculus. Famous in CS/statistics. Prompt: Ask Pearl why a DAG is an argument, not a decoration.
- **Trygve Haavelmo.** Econometrician connected to probability approaches to causal inference. Lesser-known Nobel laureate. Prompt: Ask Haavelmo why causal assumptions precede estimation.

Diversity note: candidates for this chapter may skew toward twentieth-century Euro-American philosophy, statistics, and scientific-writing traditions unless the later selection pass deliberately balances gender, geography, discipline, and era across the full book.

---

## 6. Pedagogical Delivery Research

Students often know the slogan "correlation is not causation" but not what would make causation credible. Teach through DAG editing and verb audits rather than abstract warnings.

Effective delivery should use worked examples, contrastive cases, and error diagnosis. The target reader needs to see not only the correct form but the plausible wrong form: the vague topic, the causal overclaim, the hidden proxy, the p-value-only result, the source-by-source literature review, or the fluent but unsupported sentence.

---

## 7. Representation and Display Research

A structural diagram is required: association -> intervention -> counterfactual, plus a small DAG showing X, Y, confounder, mediator, and collider.

---

## 8. Open Questions and Research Gaps

Need careful simplification so DAG terminology does not overload novice writers. Add one running example across the whole chapter.

Sources likely to age fastest: AI-disclosure policies, journal AI-use rules, and current platform tooling. Recheck against target journal instructions before drafting or submission.

---

## 9. Sourcing Notes

Primary sources are strongest for methodology, statistics, causal inference, visualization, and genre theory. Some practical guidance sources are textbooks, reporting guidelines, or editorial policies rather than empirical studies; use them as standards and pedagogical scaffolds, not as evidence that a learning intervention works. Verify exact journal AI-disclosure language, reporting checklists, and software recommendations immediately before drafting.

---

## 10. AI Use Research — When To Use AI / When NOT To Use AI


**Series calibration:** This book belongs to *Irreducibly Human: What AI Can and Can't Do*. Across chapters, AI should be framed as a tool for interrogation, audit, transformation, and drafting from a completed specification. It should not be framed as the source of the student's research question, causal judgment, construct definition, evidentiary standard, or accountability. Current publication guidance also matters: ICMJE's 2026 recommendations state that AI tools should not be listed as authors and that humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use. COPE and major publishers follow the same basic accountability principle.

### When to use AI
- Use AI to draft a tentative DAG from a verbal study description, then manually inspect every node and edge.
- Use AI to list plausible confounders, mediators, colliders, and reverse-causation threats for a proposed causal claim.
- Use AI to translate causal language into associational language when the design does not support causation.

### When NOT to use AI
- Do not let AI decide the identification strategy. Variable selection and edge direction require domain judgment.
- Do not treat an AI-generated DAG as evidence. It is an assumption sketch.
- Do not use AI to justify causal claims from observational data unless the assumptions and design are independently defensible.

### Disclosure and accountability note
If AI helped draft a DAG or causal-language audit, disclose it as causal-audit support. The author should retain the final DAG, assumptions, and rationale.

### Candidate classroom prompt
From this study description, propose a DAG with exposure, outcome, possible confounders, mediators, and colliders. Then list which edges are uncertain and what domain knowledge would be needed to defend them.

### Research/policy anchors
- ICMJE Recommendations, updated January 2026: AI tools should not be authors; humans remain responsible for accuracy, attribution, permissions, plagiarism checks, and transparent AI use.
- COPE position statement on authorship and AI tools, 2023: AI tools cannot take responsibility for submitted work, so they cannot meet authorship requirements.
- Nature Portfolio AI policy family: generative AI use is policy-sensitive, developing rapidly, and must be disclosed or handled according to venue rules.

