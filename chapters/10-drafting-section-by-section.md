# Chapter 10 — Drafting (Section by Section)

**Chapter one-line:** Drafting — Methods -> Results -> Discussion -> Introduction -> Abstract -> Title

---

## 1. Learning objectives

- Explain each empirical paper section's job (Understand).
- Draft sections in a logic-of-discovery order (Apply).
- Use a key-message sentence to control each section (Create).
- Check cross-section alignment from title through discussion (Evaluate).

---

## 2. Opening case

A student writes the Introduction first. It promises a causal study of AI tutoring and long-term learning. Weeks later, the data support only an association between use frequency and immediate quiz performance. The Introduction is now beautifully written and wrong. The paper did not fail at grammar. It failed because the framing was written before the findings were known.

---

## 3. Core concept explanation

The order a reader sees is not always the order a writer should draft. For empirical papers, Methods and Results often come first because they report what was done and found. Discussion interprets those findings. Introduction frames the actual contribution. Abstract compresses the complete paper. Title names the promise.

Each section has a job. Methods must be replicable and procedural. Results must report findings without interpretation. Discussion must interpret findings, limits, and implications. Introduction must establish territory, niche, and occupation. Abstract must stand alone. Title must help a searching reader understand the paper's claim and scope. Reporting guidelines such as JARS, CONSORT, and STROBE make many of these section duties explicit (Appelbaum et al., 2018; Schulz et al., 2010; von Elm et al., 2007).

AI is useful after the section's key message exists. It can compress an abstract, check whether Methods are replicable, or flag interpretation in Results. It should not decide the message the section must establish.

---

## 4. Worked example

**Situation.** The study is complete but unwritten.

**Analytical process.**

1. Write the Methods from the protocol and actual procedure. Ask what another researcher would need to replicate.
2. Write Results in hypothesis order, including null results.
3. Write Discussion around what the results mean and what they do not mean.
4. Then write Introduction to set up the paper that exists, not the paper once hoped for.
5. Finally write Abstract and Title from the completed argument.

**Resolution.** The paper's frame now matches its evidence. The Introduction no longer promises what the Results cannot deliver.

**The lesson.** The lesson: draft in the order that protects honesty, then arrange in the order readers expect.

**The limit.** The limit: theoretical and humanities papers may need a different drafting sequence, but section jobs still matter.

---

## 5. Common misconceptions

- **The first section should be written first.** Reading order and drafting order solve different problems.
- **The Results section should explain why findings happened.** Explanation belongs in Discussion; Results reports what happened.
- **The title is just a label.** The title is a search tool and a promise about the paper.

---

## 6. Exercises

1. For a paper you are writing, write one key-message sentence for Methods, Results, Discussion, Introduction, Abstract, and Title.
2. Find a Results paragraph and remove every interpretive phrase.
3. Compare an abstract to the Results section and list any mismatch.

---

## 7. What would change my mind

This chapter would change if a target discipline's genre conventions made this drafting order misleading. The deeper rule would remain: do not frame more than the paper can support.

---

## 8. Still puzzling

- How should the drafting order change for conceptual, legal, or humanities research?
- When should Methods include rationale rather than only procedure?
- How can AI editing be disclosed without overstating its role?

---

## Sources used

- Appelbaum et al. 2018
- Schulz et al. 2010
- von Elm et al. 2007
- Swales and Feak


---

## Chapter 10 Exercises: Drafting (Section by Section)

**Project:** Research Paper Submission Dossier
**This chapter adds:** a section-by-section drafting plan.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Check whether Methods are replicable — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Flag interpretation inside Results — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Compress a human-written abstract — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Drafting sections before the key message is settled — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Letting AI make the Introduction promise too much — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Trusting citation formatting without checking it — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on Methods, Results, Discussion, Introduction, Abstract, Title, key message.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a section key-message and drafting-order plan.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Drafting (Section by Section). Core vocabulary for this chapter: Methods, Results, Discussion, Introduction, Abstract, Title, key message.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a section key-message and drafting-order plan. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/10-drafting-plan.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will audit every claim before polish.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/10-drafting-plan.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/10-drafting-plan.md.

This file should apply Chapter 10, "Drafting (Section by Section)," to the running Research Paper Submission Dossier. Use these chapter concepts: Methods, Results, Discussion, Introduction, Abstract, Title, key message.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 10 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/10-drafting-plan.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses Methods, Results, Discussion, Introduction, Abstract, Title, key message correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Drafting (Section by Section)

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use Methods, Results, Discussion, Introduction, Abstract, Title, key message in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output preserve each section job?

□ Chapter-specific criterion 2: Does it align Introduction, Results, Discussion, Abstract, and Title?

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
