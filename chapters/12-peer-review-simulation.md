# Chapter 12 — Peer-Review Simulation

**Chapter one-line:** Peer-Review Simulation — Section-by-section review before submission

---

## 1. Learning objectives

- Explain what peer reviewers evaluate (Understand).
- Use structured review categories to triage revision (Apply).
- Run cross-section consistency checks (Analyze).
- Decide which simulated reviewer comments are valid (Evaluate).

---

## 2. Opening case

Before submission, Lina asks an AI tool to review her paper. It says the paper is clear, timely, and well organized. She is relieved. Then a human colleague asks one question: "Why does the Discussion answer a different research question than the Introduction asks?" The polite review missed the fatal mismatch.

---

## 3. Core concept explanation

Peer review is not a proof of truth. It is a structured judgment by readers who evaluate contribution, method, evidence, clarity, fit, and ethics. The process is valuable and flawed; editors and scholars have documented inconsistency, bias, and conservatism in peer review (Smith, 2006; Tennant et al., 2017).

A useful simulation is adversarial and specific. Ask for Critical, Major, and Minor issues. Ask for the strongest reason to reject. Ask whether the Results answer the Introduction's question, whether the Abstract matches the Results, and whether the Discussion overclaims the design. Narrow prompts beat generic "review this" prompts.

AI review has boundaries. Some journals restrict uploading unpublished manuscripts to AI systems because of confidentiality. Current editorial guidance treats authors as accountable for AI-assisted work and may require disclosure (ICMJE, 2026). Use tools only within venue and institutional rules.

---

## 4. Worked example

**Situation.** Lina runs a peer-review simulation.

**Analytical process.**

1. Prompt 1: "Give Critical/Major/Minor issues with section references."
2. Prompt 2: "What is the strongest reason to reject?"
3. Prompt 3: "Compare the Introduction hypothesis to the Results tests."
4. Prompt 4: "Does the Discussion claim causation beyond the design?"
5. She rejects one irrelevant comment about a method her field does not use, but keeps the cross-section mismatch.

**Resolution.** The revision plan separates fatal alignment repairs from minor polish. The paper gets harder to reject because its claim, evidence, and sections now agree.

**The lesson.** The lesson: simulated review is useful only when it is specific enough to hurt.

**The limit.** The limit: AI cannot replace a real reviewer with domain expertise, venue knowledge, and accountability.

---

## 5. Common misconceptions

- **A positive AI review means the paper is ready.** Generic AI reviews often reward fluency and miss field-specific weaknesses.
- **Every reviewer comment should be followed.** Comments must be triaged by validity, severity, and fit to the paper's claim.
- **Peer review only checks writing.** Reviewers check contribution, evidence, design, ethics, and fit.

---

## 6. Exercises

1. Run a Critical/Major/Minor review prompt on one section and convert the output into a revision table.
2. Ask for the strongest rejection reason and write whether you agree.
3. Compare your Abstract to your Results and list every mismatch.

---

## 7. What would change my mind

This chapter would change if journals converged on stable, permissive AI-review policies and robust private tools for confidential peer-review simulation. Current policy variation requires caution.

---

## 8. Still puzzling

- How can authors use AI review without violating confidentiality?
- When should a simulated critique be ignored as outside the field's norms?
- How can students learn to receive critique without treating it as identity threat?

---

## Sources used

- Smith 2006
- Tennant et al. 2017
- Munafò et al. 2017
- ICMJE 2026


---

## Chapter 12 Exercises: Peer-Review Simulation

**Project:** Research Paper Submission Dossier
**This chapter adds:** a reviewer-style critique and revision plan.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Generate Critical, Major, and Minor review comments — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Cross-check Abstract against Results — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Turn critique into revision tasks — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Uploading confidential material to prohibited tools — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Replacing human domain review — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Following every generic AI reviewer preference — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive and Tier 6 Collective: the capacity to supervise machine output at the point where the project depends on peer review, Critical, Major, Minor, venue fit, cross-section consistency.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a structured simulated peer review.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Peer-Review Simulation. Core vocabulary for this chapter: peer review, Critical, Major, Minor, venue fit, cross-section consistency.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a structured simulated peer review. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/12-peer-review-plan.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will screen ethics, bias, and disclosure.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/12-peer-review-plan.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/12-peer-review-plan.md.

This file should apply Chapter 12, "Peer-Review Simulation," to the running Research Paper Submission Dossier. Use these chapter concepts: peer review, Critical, Major, Minor, venue fit, cross-section consistency.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 12 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/12-peer-review-plan.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses peer review, Critical, Major, Minor, venue fit, cross-section consistency correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Peer-Review Simulation

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use peer review, Critical, Major, Minor, venue fit, cross-section consistency in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output identify evidence-level issues rather than only prose polish?

□ Chapter-specific criterion 2: Does it distinguish valid reviewer concerns from generic or venue-misaligned advice?

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

**Series connection:** This exercise trains Tier 4 Metacognitive and Tier 6 Collective: the capacity to catch when machine output is fluent, useful, and still not sufficient for the human conclusion.
