# Chapter 6 — GIGO: Garbage In, Garbage Out

**Chapter one-line:** GIGO — Data quality check before analysis

---

## 1. Learning objectives

- Identify common data-quality failures before analysis (Understand).
- Distinguish MCAR, MAR, and MNAR missingness (Analyze).
- Pre-specify outlier and cleaning decisions (Apply).
- Explain why better statistics cannot rescue corrupted data (Evaluate).

---

## 2. Opening case

The analysis runs. The output is clean. The p-value is small. Then someone opens the raw file and finds negative response times, missing posttests concentrated in the treatment group, and a survey scale whose items do not correlate. The statistical result was not the beginning of knowledge. It was the end of a pipeline that had already broken.

---

## 3. Core concept explanation

Garbage in, garbage out is not a slogan about computers. It is an epistemic rule: analysis inherits the quality of the data that enters it. Missingness, coding errors, inconsistent instruments, unplanned exclusions, and incoherent composites can all produce confident-looking results that do not describe the intended phenomenon.

Missing data are especially dangerous because blank cells can mean different things. Little and Rubin distinguish missing completely at random, missing at random, and missing not at random; the mechanism determines the threat to validity and the possible remedy (Little and Rubin, 2019). A dropout pattern concentrated among struggling participants is not a clerical inconvenience. It is information about the study.

Researcher degrees of freedom also enter before the main analysis. Choices about outliers, transformations, covariates, subgroup definitions, and primary outcomes can create a garden of forking paths even without conscious fraud (Gelman and Loken, 2013; Simmons et al., 2011). Pre-specification reduces that flexibility.

---

## 4. Worked example

**Situation.** A student analyzes a 100-person intervention dataset.

**Analytical process.**

1. Check impossible values: two scores exceed the test maximum; one response time is negative.
2. Check missingness: 18 posttests are missing, 15 from the treatment group. This is unlikely to be harmless.
3. Check composites: a six-item motivation scale has low internal consistency, so the total score may mix constructs.
4. Check exclusions: the student planned to remove response times under one second before seeing outcomes. That rule is documented and applied equally.

**Resolution.** The analysis pauses. The missingness pattern and composite problem must be reported and addressed before any claim about intervention effect.

**The lesson.** The lesson: cleaning is not clerical; it is part of the argument.

**The limit.** The limit: some data problems cannot be repaired statistically and require scoping or abandoning the claim.

---

## 5. Common misconceptions

- **Imputation fixes missing data.** Imputation is a model-based response to a missingness mechanism; it does not erase bias when data are missing for outcome-relevant reasons.
- **Outliers are bad data.** Some outliers are errors; others are real observations. The rule must be stated before outcome-driven decisions.
- **A high-tech analysis makes messy data trustworthy.** Sophisticated models can make bad inputs look more authoritative.

---

## 6. Exercises

1. Create a pre-analysis data-quality checklist for your project.
2. Classify three missingness scenarios as MCAR, MAR, or MNAR and explain the consequence.
3. Write an outlier rule before seeing a result. Then state how you would report it.

---

## 7. What would change my mind

This chapter would change if automated data-validation systems could reliably detect not only impossible values but also construct-level and design-level corruption. Current tools catch syntax better than meaning.

---

## 8. Still puzzling

- How much cleaning detail belongs in Methods versus supplement?
- When does data loss make a study unrecoverable?
- How can small qualitative datasets adapt the GIGO principle?

---

## Sources used

- Little and Rubin 2019
- Cronbach 1951
- Gelman and Loken 2013
- Simmons et al. 2011


---

## Chapter 6 Exercises: GIGO: Garbage In, Garbage Out

**Project:** Research Paper Submission Dossier
**This chapter adds:** a pre-analysis data-quality checklist.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Generate data-quality checks from variable descriptions — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Draft code comments for missingness and impossible-value checks — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Suggest likely data problems to inspect — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Running unreviewed cleaning code on the only data copy — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Uploading restricted data to unapproved tools — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Choosing exclusions after seeing which result looks best — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on missingness, MCAR, MAR, MNAR, outliers, reliability, forking paths.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a data-quality risk checklist.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: GIGO: Garbage In, Garbage Out. Core vocabulary for this chapter: missingness, MCAR, MAR, MNAR, outliers, reliability, forking paths.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a data-quality risk checklist. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/06-data-quality-checklist.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will plan the statistical test and reporting.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/06-data-quality-checklist.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/06-data-quality-checklist.md.

This file should apply Chapter 6, "GIGO: Garbage In, Garbage Out," to the running Research Paper Submission Dossier. Use these chapter concepts: missingness, MCAR, MAR, MNAR, outliers, reliability, forking paths.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 6 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/06-data-quality-checklist.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses missingness, MCAR, MAR, MNAR, outliers, reliability, forking paths correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — GIGO: Garbage In, Garbage Out

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use missingness, MCAR, MAR, MNAR, outliers, reliability, forking paths in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output distinguish data cleaning from result-shopping?

□ Chapter-specific criterion 2: Does it treat missingness mechanism as substantive, not clerical?

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
