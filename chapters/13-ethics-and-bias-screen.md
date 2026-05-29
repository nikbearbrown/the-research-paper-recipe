# Chapter 13 — Ethics and Bias Screen

**Chapter one-line:** Ethics and Bias Screen — Disclosure, generalization, replication fitness

---

## 1. Learning objectives

- Identify disclosure obligations for conflicts, funding, ethics approval, and AI assistance (Understand).
- Audit claims for overgeneralization from narrow samples (Analyze).
- Check a literature review for confirmatory citation bias (Evaluate).
- Write an AI-use disclosure that names tool and task (Create).

---

## 2. Opening case

The study is small, local, and useful. The Conclusion says the findings show how students learn with AI. The literature review cites only supportive studies. AI helped rewrite the Discussion, but no disclosure appears because the author thinks the tool only improved style. None of these choices looks dramatic alone. Together, they make the paper less honest than it needs to be.

---

## 3. Core concept explanation

Ethics in research writing is not only about institutional approval. It is about accountability for claims. Authors must disclose conflicts, funding, human-subjects approval where relevant, limitations, and assistance that affects the work. Publication-ethics bodies state that AI tools cannot be authors because they cannot take responsibility; human authors remain accountable for all content (COPE, 2023; ICMJE, 2026).

Bias enters through sampling, citation, interpretation, and disclosure. A narrow sample does not forbid a paper, but it constrains the claim. A literature review that cites only friendly sources may produce a false sense of consensus. A Discussion that universalizes from a local case makes readers carry a conclusion the study did not earn.

The ethics screen asks whether the paper could survive replication, scrutiny, and disclosure. If the answer depends on hiding a limitation, omitting a null result, smoothing over AI assistance, or ignoring contrary evidence, the paper is not ready.

---

## 4. Worked example

**Situation.** A student study uses 43 volunteers from one university course and AI assistance for copyediting and code comments.

**Analytical process.**

1. Sample claim audit: replace "students learn" with "students in this course sample performed."
2. Disclosure audit: state whether AI was used for copyediting, code generation, figure drafting, or analysis suggestions according to target-journal policy.
3. Citation audit: add credible contrary or null findings if the review currently cites only supportive evidence.
4. Replication audit: check whether materials, measures, and analysis decisions are available enough for another researcher.

**Resolution.** The paper becomes more modest and more trustworthy. Its limitations are not confessions of failure; they are instructions for reading the evidence correctly.

**The lesson.** The lesson: ethics is the final form of claim calibration.

**The limit.** The limit: AI and journal policies change quickly, so every submission needs a current policy check.

---

## 5. Common misconceptions

- **Ethics is only IRB paperwork.** IRB is one layer; disclosure, sampling, bias, and accountable interpretation are also ethical.
- **Small studies should hide their limits.** Small studies can be valuable when claims are scoped honestly.
- **If AI only edited prose, disclosure never matters.** Policies vary. Some require disclosure for substantive assistance, and authors must check the venue.

---

## 6. Exercises

1. Write a limitations paragraph that names sample, design, measure, and timescale without apologizing.
2. Audit a reference list for one-sided citation patterns.
3. Draft an AI-use disclosure naming tool and task, then compare it to a target journal policy.

---

## 7. What would change my mind

This chapter would change if scholarly publishing adopted a universal AI-use disclosure standard. Until then, the safest rule is to check the target venue and disclose substantive assistance clearly.

---

## 8. Still puzzling

- How much AI assistance is enough to require disclosure?
- How can authors assess citation diversity without making demographic assumptions from names?
- What level of materials sharing is reasonable for sensitive or proprietary data?

---

## Sources used

- COPE 2023
- ICMJE 2026
- Fanelli 2009
- Munafò et al. 2017


---

## Chapter 13 Exercises: Ethics and Bias Screen

**Project:** Research Paper Submission Dossier
**This chapter adds:** an ethics, bias, and disclosure checklist.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Check for overgeneralization and missing limitations — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Draft disclosure language from factual AI-use notes — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Compare a disclosure to a supplied journal policy — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Letting AI decide whether nondisclosure is acceptable — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Uploading sensitive data or confidential review material — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Inferring citation diversity from names alone — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 7 Wisdom and Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on AI disclosure, conflict of interest, overgeneralization, citation bias, accountability.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** an ethics and disclosure screen.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Ethics and Bias Screen. Core vocabulary for this chapter: AI disclosure, conflict of interest, overgeneralization, citation bias, accountability.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create an ethics and disclosure screen. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/13-ethics-disclosure-check.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will revise prose without changing the claim.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/13-ethics-disclosure-check.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/13-ethics-disclosure-check.md.

This file should apply Chapter 13, "Ethics and Bias Screen," to the running Research Paper Submission Dossier. Use these chapter concepts: AI disclosure, conflict of interest, overgeneralization, citation bias, accountability.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 13 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/13-ethics-disclosure-check.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses AI disclosure, conflict of interest, overgeneralization, citation bias, accountability correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Ethics and Bias Screen

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use AI disclosure, conflict of interest, overgeneralization, citation bias, accountability in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output preserve human accountability for AI-assisted work?

□ Chapter-specific criterion 2: Does it flag policy-specific claims as aging risks?

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

**Series connection:** This exercise trains Tier 7 Wisdom and Tier 4 Metacognitive: the capacity to catch when machine output is fluent, useful, and still not sufficient for the human conclusion.
