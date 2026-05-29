# Chapter 8 — How to Design a Graph

**Chapter one-line:** How to Design a Graph — Visual encoding, chart selection, honest figures [PLACEHOLDER]

---

## 1. Learning objectives

- Match chart type to research question (Apply).
- Explain visual encoding channels and their limits (Understand).
- Detect common misleading graph choices (Analyze).
- Redesign a figure to make its claim honest and readable (Create).

---

## 2. Opening case

Two bar charts show the same data. One starts the y-axis at zero; the other starts at 83. The second makes a small difference look dramatic. No number has been changed. The visual claim has. A graph is not a picture of data. It is an argument encoded in position, length, color, area, and annotation.

---

## 3. Core concept explanation

Graph design starts with the reader task: compare, rank, identify distribution, track change, inspect relationship, or understand composition. Cleveland and McGill showed that people judge position along a common scale more accurately than length, angle, area, or color (Cleveland and McGill, 1984). Heer and Bostock later replicated graphical perception patterns with crowdsourced experiments (Heer and Bostock, 2010).

The form must match the question. Comparisons usually need bars or dot plots. Distributions need histograms, box plots, violin plots, or raw points. Relationships need scatterplots. Change over time usually needs lines. Part-to-whole claims sometimes use pies, but only with few categories and a true composition question.

Honesty is structural. Bar charts use length from a baseline, so a zero baseline is non-negotiable. Area encodings must be proportional to values. Color hue identifies categories but does not reliably encode magnitude. Error bars must say what they represent: standard deviation, standard error, or confidence interval.

---

## 4. Worked example

**Situation.** A paper reports mean test scores for two conditions with a bar chart and SEM error bars.

**Analytical process.**

1. Ask the question: compare group means or show distribution? If n is modest, the distribution matters.
2. Replace bars with dot plot plus mean and confidence interval so readers see spread.
3. Use a zero baseline only if bars remain; for dot plots, choose an axis that shows the relevant range and label it honestly.
4. Caption the claim: "Scores were higher in the Socratic condition, but overlap between individual scores was substantial."

**Resolution.** The redesign prevents a mean from pretending to represent every participant. Weissgerber et al. show why bar graphs often hide distributional structure in biomedical papers (Weissgerber et al., 2015).

**The lesson.** The lesson: the graph should answer the research question without adding a false visual claim.

**The limit.** The limit: no chart can compensate for poor measurement or weak design.

---

## 5. Common misconceptions

- **A graph is neutral if the numbers are correct.** Encoding choices can exaggerate, hide, or imply relationships without changing the data.
- **Color makes quantitative differences easier to read.** Hue is good for category identity, not ordered magnitude.
- **Bar charts are the default for all group comparisons.** Bars hide distributions and should be reserved for single-valued summaries where length is the right channel.

---

## 6. Exercises

1. Take one figure from your field and write the reader task in one sentence.
2. Redesign a bar chart of means as a distribution plot. Explain what changes.
3. Find a chart with a truncated axis, dual axis, 3D effect, or unclear error bars and write a correction note.

---

## 7. What would change my mind

This chapter would change if new empirical visualization research showed that a common rule here, such as the zero-baseline rule for bars, did not affect reader judgment in realistic research contexts. Current evidence supports treating these as cognitive, not decorative, rules.

---

## 8. Still puzzling

- How should interactive figures be archived for long-term scholarly access?
- When does simplification for accessibility become loss of necessary detail?
- How should AI-generated figures disclose data transformations and defaults?

---

## Sources used

- Cleveland and McGill 1984
- Heer and Bostock 2010
- Weissgerber et al. 2015
- Pandey et al. 2015


---

## Chapter 8 Exercises: How to Design a Graph

**Project:** Research Paper Submission Dossier
**This chapter adds:** a figure plan and visual-honesty audit.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Recommend chart types from a reader task — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Generate plotting code after the visual claim is specified — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Audit chart defaults and accessibility — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Letting AI decide the visual claim — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Accepting invented data or labels in generated figures — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Using decorative chart forms that distort the evidence — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on visual encoding, zero baseline, proportional ink, chart type, distribution, annotation.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a figure-design brief.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: How to Design a Graph. Core vocabulary for this chapter: visual encoding, zero baseline, proportional ink, chart type, distribution, annotation.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a figure-design brief. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/08-figure-plan.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will synthesize sources into the literature review.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/08-figure-plan.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/08-figure-plan.md.

This file should apply Chapter 8, "How to Design a Graph," to the running Research Paper Submission Dossier. Use these chapter concepts: visual encoding, zero baseline, proportional ink, chart type, distribution, annotation.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 8 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/08-figure-plan.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses visual encoding, zero baseline, proportional ink, chart type, distribution, annotation correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — How to Design a Graph

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use visual encoding, zero baseline, proportional ink, chart type, distribution, annotation in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output match chart type to reader task?

□ Chapter-specific criterion 2: Does it respect zero-baseline, proportional-ink, distribution, and accessibility rules?

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
