# Chapter 11 — Quality Control

**Chapter one-line:** Quality Control — Claim audit, statistical integrity, style vs. logic

---

## 1. Learning objectives

- Run a claim audit on a draft section (Apply).
- Separate logic problems from style problems (Analyze).
- Check statistical claims against reported evidence (Evaluate).
- Use naive-reader feedback to detect claim drift (Apply).

---

## 2. Opening case

The paragraph is elegant. It says the intervention demonstrates that AI improves learning. The table says something narrower: one subgroup improved on one immediate outcome, with no delayed measure. The problem is not the sentence's sound. The problem is the distance between the sentence and the evidence.

---

## 3. Core concept explanation

Quality control starts with claims, not commas. Highlight every major claim and ask what evidence supports it. Label each as supported, partially supported, overstated, unsupported, needs citation, or needs qualification. This practice aligns with broader reproducibility recommendations that emphasize transparency, reporting, and methods that make claims checkable (Munafò et al., 2017).

Statistical integrity is a claim audit for numbers. Every p-value, effect size, confidence interval, and comparison sentence must match the output and table. Reproducibility work shows why this matters: published results are not automatically reliable just because they passed peer review (Open Science Collaboration, 2015; Ioannidis, 2005).

Style and logic are different. A style problem makes a sound claim hard to read. A logic problem makes the claim unsupported. AI can improve style so quickly that logic problems become harder to see. Run the logic audit first.

---

## 4. Worked example

**Situation.** A Discussion sentence says, "The intervention demonstrates improved learning across students."

**Analytical process.**

1. Claim: demonstrates improved learning across students.
2. Evidence: immediate aligned posttest, one university, treatment group higher than control.
3. Status: overstated. "Demonstrates" is too strong, "learning" too broad, "across students" too general.
4. Revision: "The intervention improved immediate performance on the aligned posttest in this sample."

**Resolution.** The revised sentence is less dramatic and more true. It can survive a reviewer's evidence check.

**The lesson.** The lesson: the strongest sentence is the one the evidence can carry.

**The limit.** The limit: excessive qualification can make a real finding unreadable; the goal is calibration, not timidity.

---

## 5. Common misconceptions

- **Revision means improving style.** Revision also means repairing logic, evidence, scope, and statistical reporting.
- **If a claim is mostly true, it can stay.** A mostly true claim often needs a narrower subject, verb, or scope.
- **AI polish is quality control.** AI polish can hide unsupported reasoning unless a claim audit happens first.

---

## 6. Exercises

1. Highlight all claims in one page of your draft and label their evidence status.
2. Take a quantitative sentence and ask "compared with what?" Add the missing reference.
3. Give a section to a naive reader and compare their summary to your intended claim.

---

## 7. What would change my mind

This chapter would change if automated claim-checking tools reliably matched prose to data, tables, and cited sources across disciplines. Current tools help flag problems but cannot own the audit.

---

## 8. Still puzzling

- How much qualification is enough before prose becomes unreadable?
- How can teams divide claim-audit labor without losing accountability?
- What should be done when a beautiful central claim fails the audit?

---

## Sources used

- Munafò et al. 2017
- Ioannidis 2005
- Open Science Collaboration 2015
- Kerr 1998


---

## Chapter 11 Exercises: Quality Control

**Project:** Research Paper Submission Dossier
**This chapter adds:** a claim audit and revision triage table.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Identify strong, causal, quantitative, or unsupported claims — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Compare claims against supplied tables and outputs — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Separate style problems from logic problems — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Using AI polish as quality control — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Letting AI verify facts without source data — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Accepting support judgments without quoted evidence — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on claim audit, supported, overstated, unsupported, style problem, logic problem.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a claim-audit table.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Quality Control. Core vocabulary for this chapter: claim audit, supported, overstated, unsupported, style problem, logic problem.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a claim-audit table. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/11-claim-audit.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will simulate peer review.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/11-claim-audit.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/11-claim-audit.md.

This file should apply Chapter 11, "Quality Control," to the running Research Paper Submission Dossier. Use these chapter concepts: claim audit, supported, overstated, unsupported, style problem, logic problem.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 11 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/11-claim-audit.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses claim audit, supported, overstated, unsupported, style problem, logic problem correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Quality Control

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use claim audit, supported, overstated, unsupported, style problem, logic problem in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output cite evidence for each support judgment?

□ Chapter-specific criterion 2: Does it distinguish style weakness from logic weakness?

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
