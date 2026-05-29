# Chapter 4 — What Does Causal Mean, Exactly?

**Chapter one-line:** What Does Causal Mean, Exactly? — Counterfactuals, DAGs, Pearl's hierarchy [PLACEHOLDER]

---

## 1. Learning objectives

- Explain causation as a counterfactual claim (Understand).
- Draw a simple DAG with exposure, outcome, confounder, mediator, and collider (Apply).
- Distinguish association, intervention, and counterfactual questions (Analyze).
- Audit causal language in a draft for design support (Evaluate).

---

## 2. Opening case

A paper reports that students who used an AI tutor more often scored higher on the final exam. The Discussion says the AI tutor caused the improvement. That sentence may be true. The study has not shown it. High-motivation students may have used the tutor more, studied more, and scored higher for reasons the tutor did not create. The causal verb has smuggled in an untested comparison: what would have happened to the same students if they had not used the tutor?

---

## 3. Core concept explanation

A causal claim is a counterfactual claim. It asks whether the outcome would have been different if the cause had been absent or changed. Rubin's potential-outcomes framework expresses this as a comparison between observed and unobserved potential outcomes (Rubin, 1974). Because we cannot observe both states for the same unit at the same time, causal inference depends on design and assumptions.

Pearl's causal hierarchy separates association, intervention, and counterfactual questions (Pearl, 2009). Association asks what is seen. Intervention asks what happens if we do something. Counterfactuals ask what would have happened otherwise. Many papers live on the association rung and write as if they reached the counterfactual rung.

Directed acyclic graphs, or DAGs, make causal assumptions visible. A confounder influences both cause and outcome. A mediator lies on the pathway from cause to outcome. A collider is caused by two variables; adjusting for it can create bias. The drawing is not evidence. It is a map of the assumptions the evidence must defend (Hernán and Robins, 2020).

---

## 4. Worked example

**Situation.** Observed: AI tutor use is associated with higher exam scores.

**Analytical process.**

1. Draw AI use -> exam score as the proposed causal path.
2. Add motivation -> AI use and motivation -> exam score as a confounder.
3. Ask whether the design randomized AI access. If not, motivation remains a plausible alternative explanation.
4. Consider rewriting: "AI tutor use was associated with higher exam scores" or strengthening design through random assignment, natural experiment, or adjustment justified by a DAG.

**Resolution.** The paper can keep the association or build a causal design. It cannot keep observational evidence and write experimental verbs.

**The lesson.** The lesson: causation is not a stronger synonym for correlation; it is a different claim.

**The limit.** The limit: even strong causal designs depend on assumptions that must be stated and defended.

---

## 5. Common misconceptions

- **Correlation is not causation, so causal claims are impossible outside experiments.** Some nonrandomized designs can support causal inference, but only with explicit assumptions and identification strategies.
- **A DAG proves the causal story.** A DAG displays assumptions; it does not verify them.
- **Controlling for more variables always improves causal inference.** Adjusting for mediators or colliders can create bias.

---

## 6. Exercises

1. Draw a DAG for your main hypothesis with at least one possible confounder.
2. Find every causal verb in a draft paragraph and decide whether the design licenses it.
3. Rewrite one causal claim into associational language and one associational design into a stronger causal design proposal.

---

## 7. What would change my mind

This chapter would change if a simpler causal framework consistently helped novice writers avoid overclaiming without introducing new misunderstandings. The current approach uses counterfactuals and DAGs because they expose assumptions directly.

---

## 8. Still puzzling

- How much causal notation is useful before it becomes a barrier?
- When should beginning writers consult a statistician or methodologist rather than simplify?
- How should causal language work in historical or interpretive research?

---

## Sources used

- Rubin 1974
- Pearl 2009
- Hernán and Robins 2020
- Angrist and Pischke 2009


---

## Chapter 4 Exercises: What Does Causal Mean, Exactly?

**Project:** Research Paper Submission Dossier
**This chapter adds:** a causal-language audit and tentative DAG.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Draft a tentative DAG from a verbal design — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- List possible confounders and mediators — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Translate causal wording into associational wording when needed — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Deciding the identification strategy — *Why AI fails here:* This requires causal identification or counterfactual judgment that the model cannot supply as ground truth.
- Treating an AI-generated DAG as evidence — *Why AI fails here:* This requires causal identification or counterfactual judgment that the model cannot supply as ground truth.
- Letting AI orient causal edges without domain justification — *Why AI fails here:* This requires causal identification or counterfactual judgment that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 5 Causal and Counterfactual: the capacity to supervise machine output at the point where the project depends on counterfactual, DAG, confounder, mediator, collider, causal verb.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a tentative DAG and causal-verb audit.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: What Does Causal Mean, Exactly?. Core vocabulary for this chapter: counterfactual, DAG, confounder, mediator, collider, causal verb.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a tentative DAG and causal-verb audit. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/04-causal-audit.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will ask whether the measures actually capture the construct.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/04-causal-audit.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/04-causal-audit.md.

This file should apply Chapter 4, "What Does Causal Mean, Exactly?," to the running Research Paper Submission Dossier. Use these chapter concepts: counterfactual, DAG, confounder, mediator, collider, causal verb.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 4 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/04-causal-audit.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses counterfactual, DAG, confounder, mediator, collider, causal verb correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — What Does Causal Mean, Exactly?

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use counterfactual, DAG, confounder, mediator, collider, causal verb in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output distinguish association from causation?

□ Chapter-specific criterion 2: Does it avoid conditioning on mediators or colliders as if more controls are always better?

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

**Series connection:** This exercise trains Tier 5 Causal and Counterfactual: the capacity to catch when machine output is fluent, useful, and still not sufficient for the human conclusion.
