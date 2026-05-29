# Chapter 2 — Foundation

**Chapter one-line:** Foundation — Lock hypothesis, evaluate sources, plan design

---

## 1. Learning objectives

- Lock a hypothesis before building an outline (Apply).
- Evaluate whether a source's design supports its claim (Analyze).
- Compare candidate study designs for fit to a research question (Evaluate).
- Build a source matrix that separates findings from limitations (Create).

---

## 2. Opening case

Noah finds five papers supporting his intervention. Each reports positive effects. He starts writing the literature review as if the field has spoken. Then he notices the details: one paper used a self-selected sample, another measured satisfaction instead of learning, one had no control group, and two reported only p-values. The problem is not that the sources are useless. The problem is that he has not yet asked what each source can actually carry.

---

## 3. Core concept explanation

The foundation of a paper has two locks: the hypothesis and the evidence plan. The hypothesis names the claim. The evidence plan asks what design, sample, measure, and analysis would make that claim defensible. Reporting standards such as JARS, CONSORT, and STROBE exist because readers cannot evaluate findings without design details (Appelbaum et al., 2018; Schulz et al., 2010; von Elm et al., 2007).

Source quality is not identical to journal prestige. A strong source for one claim can be weak for another. An observational study may be excellent evidence of association and poor evidence of causation. A trial with a narrow sample may be strong for internal validity and weak for generalization. The foundation chapter teaches students to ask: what does this source license me to say?

AI can help by generating design tradeoffs and methodological red flags. It cannot decide whether the source matters in the student's field or whether the comparison is fair. That judgment belongs to the author.

---

## 4. Worked example

**Situation.** Noah wants to claim that a feedback tool improves durable learning.

**Analytical process.**

1. He lists each source with design, sample, measure, comparison, effect size, and limitation.
2. He marks one study as satisfaction-only: useful for user experience, not learning.
3. He marks another as immediate aligned post-test: useful for short-term performance, not durable retention.
4. He identifies the best source as a randomized study with delayed assessment but notes its sample is one institution.

**Resolution.** His literature review changes. Instead of "prior work shows the tool improves learning," he writes, "prior work suggests short-term performance gains, but evidence for durable retention remains limited."

**The lesson.** The lesson: a source supports only the claim its design can bear.

**The limit.** The limit: no checklist replaces domain expertise about which comparison or measure actually matters.

---

## 5. Common misconceptions

- **A peer-reviewed source is safe to build on without inspection.** Peer review does not guarantee that the design supports the claim you want to borrow.
- **A source that supports my topic supports my hypothesis.** A source can be relevant to the topic while failing to test the exact mechanism, population, or outcome in your hypothesis.
- **Evaluating sources means finding flaws.** The goal is not to dismiss sources but to scope their contribution accurately.

---

## 6. Exercises

1. Build a six-column source matrix for three papers in your area: claim, design, sample, measure, finding, limitation.
2. Take one causal sentence from a source and decide whether the design supports causal language. Rewrite if necessary.
3. Ask AI for three possible designs for your hypothesis. For each, write what it can and cannot rule out.

---

## 7. What would change my mind

This chapter would change if evidence showed that novice writers who begin with unstructured literature summaries produce more accurate claims than writers who begin with source-design matrices. The comparison would need to assess claim accuracy, not speed.

---

## 8. Still puzzling

- How much methodology should a first-time writer learn before drafting?
- When is a source limitation serious enough to exclude the source rather than qualify it?
- How should this matrix work for theoretical or interpretive scholarship?

---

## Sources used

- Appelbaum et al. 2018
- Schulz et al. 2010
- von Elm et al. 2007
- Nosek et al. 2018


---

## Chapter 2 Exercises: Foundation

**Project:** Research Paper Submission Dossier
**This chapter adds:** a source and study-design evaluation matrix.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Create a source-evaluation table — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- List design tradeoffs for a proposed hypothesis — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Flag method details a reader must inspect — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Declaring a source credible without reading it — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Choosing the design solely from AI advice — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Collapsing weak and strong evidence into one confidence level — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on source evaluation, design fit, evidence plan, source matrix.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a design-options and source-matrix plan.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Foundation. Core vocabulary for this chapter: source evaluation, design fit, evidence plan, source matrix.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a design-options and source-matrix plan. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/02-source-design-matrix.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will classify the claim itself before choosing methods.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/02-source-design-matrix.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/02-source-design-matrix.md.

This file should apply Chapter 2, "Foundation," to the running Research Paper Submission Dossier. Use these chapter concepts: source evaluation, design fit, evidence plan, source matrix.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 2 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/02-source-design-matrix.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses source evaluation, design fit, evidence plan, source matrix correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Foundation

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use source evaluation, design fit, evidence plan, source matrix in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output separate source relevance from source strength?

□ Chapter-specific criterion 2: Does it name what each design cannot support?

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
