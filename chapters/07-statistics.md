# Chapter 7 — Statistics

**Chapter one-line:** Statistics — Test selection, assumptions, power, reporting

---

## 1. Learning objectives

- Interpret p-values without treating them as proof (Understand).
- Choose common statistical tests from design and variable type (Apply).
- Report effect sizes, uncertainty, and exact test results (Apply).
- Recognize multiple-comparisons and power problems (Analyze).

---

## 2. Opening case

A Results section says, "The experimental group performed significantly better (p < .05)." That sentence is not enough. Better by how much? On what measure? With what test? How many degrees of freedom? Was the effect practically meaningful? Could one significant result be the survivor of twenty tests? The number is doing less work than the prose claims.

---

## 3. Core concept explanation

Statistics expresses uncertainty under a model. A p-value is not the probability that the null hypothesis is true; the ASA statement warns against exactly that interpretation (Wasserstein and Lazar, 2016). A small p-value says the data would be unusual under a specified null model. It does not prove the effect, importance, or replicability.

A complete result includes the test statistic, degrees of freedom where relevant, exact p-value, effect size, and uncertainty. Effect size answers a different question from statistical significance: how large is the difference or relationship? Cohen's benchmarks are useful as historical reference but not universal standards (Cohen, 1992).

Multiplicity and power shape interpretation. If a study runs many tests, some will cross alpha by chance; Benjamini and Hochberg's false discovery rate method is one response (Benjamini and Hochberg, 1995). Underpowered studies produce unstable estimates and inflated significant effects, a core reason many published findings fail to replicate (Ioannidis, 2005).

---

## 4. Worked example

**Situation.** A student compares two groups on a posttest and writes only p < .05.

**Analytical process.**

1. Identify design: two independent groups, continuous outcome. A t-test may fit if assumptions are reasonable.
2. Report fully: means, standard deviations, t statistic, degrees of freedom, exact p-value, Cohen's d, and confidence interval.
3. Ask multiplicity: was this the primary outcome or one of many?
4. Ask meaning: is d = 0.18 meaningful in this field, cost, and context?

**Resolution.** The revised sentence reports the result and scopes the interpretation: "The intervention group scored higher than the control group on the delayed posttest, t(62) = 2.47, p = .016, d = 0.63, though this was the only planned primary comparison."

**The lesson.** The lesson: statistical reporting should let the reader evaluate both signal and uncertainty.

**The limit.** The limit: statistics cannot repair a bad design, weak measure, or post-hoc hypothesis.

---

## 5. Common misconceptions

- **p = .04 means the null has a 4 percent chance of being true.** That interpretation reverses the conditional probability.
- **Non-significant means no effect.** It may mean no effect, low power, noisy measurement, or a poorly matched test.
- **Large samples make findings important.** Large samples can make trivial effects statistically significant.

---

## 6. Exercises

1. Rewrite a p-value-only result into a complete statistical sentence.
2. Given three designs, choose the likely test and name its assumptions.
3. List all tests in a hypothetical Results section and decide whether a multiple-comparisons correction is needed.

---

## 7. What would change my mind

This chapter would change if journals broadly abandoned null-hypothesis significance testing in favor of estimation or Bayesian reporting. The current chapter teaches common practice while naming its limits.

---

## 8. Still puzzling

- How much statistical detail should a general research-writing book teach before referring to a methods text?
- When should confidence intervals replace significance language entirely?
- How should AI-generated analysis code be audited for defaults and assumptions?

---

## Sources used

- Wasserstein and Lazar 2016
- Cohen 1992
- Benjamini and Hochberg 1995
- Ioannidis 2005


---

## Chapter 7 Exercises: Statistics

**Project:** Research Paper Submission Dossier
**This chapter adds:** a statistical analysis and reporting plan.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Map design and variables to candidate tests — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Generate assumption-checking code for review — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Draft complete statistical reporting templates — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Letting AI choose the final model for complex designs — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Accepting software defaults without inspection — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Interpreting significance as proof or importance — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on p-value, effect size, confidence interval, power, assumptions, multiple comparisons.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a statistics plan with assumptions and reporting requirements.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Statistics. Core vocabulary for this chapter: p-value, effect size, confidence interval, power, assumptions, multiple comparisons.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a statistics plan with assumptions and reporting requirements. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/07-statistics-plan.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will decide how the evidence should be shown visually.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/07-statistics-plan.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/07-statistics-plan.md.

This file should apply Chapter 7, "Statistics," to the running Research Paper Submission Dossier. Use these chapter concepts: p-value, effect size, confidence interval, power, assumptions, multiple comparisons.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 7 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/07-statistics-plan.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses p-value, effect size, confidence interval, power, assumptions, multiple comparisons correctly, preserves human decision points, and avoids unsupported conclusions.

**If it goes wrong:** If the agent invents facts or overwrites prior work, stop and inspect the diff. Restore the previous file version if needed, then rerun with the added instruction: "Use only facts already present in the dossier or explicitly mark them missing."

**CLAUDE.md / AGENTS.md note:** Add or keep this standing rule: "Never convert AI-generated suggestions into research conclusions without a human-authored rationale and source check."

---

### Exercise 5 — AI Validation Exercise

**What you're validating:** The AI-generated artifact from Exercise 3 or 4.
**Validation type:** Reasoning chain / Agentic output.
**Risk level:** Medium. The output is useful if it structures your thinking, but dangerous if it silently makes the judgment the chapter says must remain human.

**Setup:**

Use the output from Exercise 3 or the file produced in Exercise 4 as the artifact to validate.

**The Validation Task:**

Evaluate the AI output above using the following checklist. For each item, record: Pass / Fail / Cannot determine — and explain your reasoning.

```
Validation Checklist — Statistics

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use p-value, effect size, confidence interval, power, assumptions, multiple comparisons in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output avoid p-value misinterpretation?

□ Chapter-specific criterion 2: Does it include effect size, uncertainty, assumptions, and multiplicity?

□ Failure mode check: Does this output exhibit any of the following?
  - Fluent but wrong
  - Schema-valid but semantically wrong
  - Missing ground truth
  - Automation bias trigger: a confident recommendation without evidence you can independently inspect
```

**What to do with your findings:**

- If the output passes all checks: proceed to use it in your project. Note what made it trustworthy.
- If the output fails one check: revise the prompt and re-run Exercise 3 or 4. Document what changed.
- If the output fails multiple checks or you cannot determine pass/fail: this is a "When NOT to Use AI" moment. Do this part of the task yourself.

**AI Use Disclosure prompt:**

After completing this validation, write a two-sentence AI Use Disclosure:

> *Sentence 1:* What AI produced in this exercise and how you used it.
> *Sentence 2:* One specific thing the AI could not determine that required your judgment.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to catch when machine output is fluent, useful, and still not sufficient for the human conclusion.
