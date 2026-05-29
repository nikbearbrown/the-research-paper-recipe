# Chapter 3 — The Scientific Method: Assertions and How to Test Them

**Chapter one-line:** The Scientific Method — Assertion types, falsifiability, null/alternative hypothesis

---

## 1. Learning objectives

- Classify assertions by type (Understand).
- Match assertion type to evidence and design (Apply).
- State null and alternative hypotheses for empirical claims (Apply).
- Detect unfalsifiable or self-protecting claims (Analyze).

---

## 2. Opening case

A student writes, "AI feedback improves learning because students engage more deeply." The sentence sounds scientific. It actually contains at least three claims: a causal claim about AI feedback, a construct claim about learning, and a mechanistic claim about engagement. If the study only compares platform users with non-users, the sentence has already outrun the design.

---

## 3. Core concept explanation

An assertion is a claim that can be evaluated as true or false, even if the answer is not yet known. Different assertions require different evidence. Descriptive claims report what happened. Correlational claims say variables move together. Causal claims say one thing produces another. Predictive claims say one variable helps anticipate another. Mechanistic claims explain how or why. Normative claims say what should be done. Conceptual claims define or clarify terms.

The scientific method disciplines assertions by asking what kind of claim is being made and what would count against it. Popper's falsifiability criterion is not the whole of science, but it is a powerful guardrail against claims that can explain every outcome (Popper, 1959). Neyman and Pearson's testing framework formalized the null/alternative structure as a decision procedure, not as proof of truth (Neyman and Pearson, 1933).

The chapter's practical move is assertion typing. Before choosing methods or writing the Discussion, classify the central claim. If the assertion type and design do not match, fix the claim or fix the design.

---

## 4. Worked example

**Situation.** Claim: "Students who use AI hints learn more because hints force retrieval."

**Analytical process.**

1. Type the first clause: causal, because it says AI hints produce learning.
2. Type the second clause: mechanistic, because it explains why through retrieval.
3. State the null: students receiving AI hints do not differ in delayed unassisted learning from students in the comparison condition.
4. Ask what would falsify it: no delayed difference, better retention in direct-answer condition, or no evidence that retrieval mediated the effect.

**Resolution.** A correlational log analysis cannot test the causal/mechanistic version. The writer must either design an experiment with a process measure or rewrite the claim as an association.

**The lesson.** The lesson: the verb chooses the burden of proof.

**The limit.** The limit: real papers often contain layered assertions, so the audit must happen sentence by sentence.

---

## 5. Common misconceptions

- **A question is a hypothesis.** A question asks; a hypothesis predicts. "Does X affect Y?" does not state what you expect or why.
- **A significant p-value confirms the alternative.** A p-value evaluates data under a null model; it does not prove the alternative true.
- **Normative claims are unscientific and should disappear.** Normative claims can be legitimate, but data cannot settle them alone. They need to be separated from empirical claims.

---

## 6. Exercises

1. Classify five claims from your draft as descriptive, causal, correlational, predictive, mechanistic, normative, or conceptual.
2. Write the null hypothesis for your main empirical claim.
3. List three observations that would make your hypothesis false. If none are possible, rewrite the hypothesis.

---

## 7. What would change my mind

This chapter would change if a better classroom taxonomy helped novices align claims to designs more accurately than the current assertion categories. The criterion would be fewer design/claim mismatches in actual drafts.

---

## 8. Still puzzling

- How should mixed empirical and normative arguments be taught without flattening either?
- When is a mechanistic claim strong enough to include in a Discussion?
- How can qualitative evidence be mapped to assertion types without forcing it into experimental categories?

---

## Sources used

- Popper 1959
- Neyman and Pearson 1933
- Meehl 1967
- Kerr 1998


---

## Chapter 3 Exercises: The Scientific Method: Assertions and How to Test Them

**Project:** Research Paper Submission Dossier
**This chapter adds:** an assertion-type and falsifiability audit.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Classify draft claims by assertion type — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Generate possible null hypotheses — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Find verbs that change the evidentiary burden — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Letting AI decide the true assertion type when domain context matters — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Converting values claims into fake empirical claims — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Accepting a null that does not match the design — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive: the capacity to supervise machine output at the point where the project depends on assertion type, null hypothesis, alternative hypothesis, falsifiability.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** an assertion taxonomy for the dossier claim.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: The Scientific Method: Assertions and How to Test Them. Core vocabulary for this chapter: assertion type, null hypothesis, alternative hypothesis, falsifiability.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create an assertion taxonomy for the dossier claim. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/03-assertion-audit.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will handle causal language directly.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/03-assertion-audit.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/03-assertion-audit.md.

This file should apply Chapter 3, "The Scientific Method: Assertions and How to Test Them," to the running Research Paper Submission Dossier. Use these chapter concepts: assertion type, null hypothesis, alternative hypothesis, falsifiability.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 3 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/03-assertion-audit.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses assertion type, null hypothesis, alternative hypothesis, falsifiability correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — The Scientific Method: Assertions and How to Test Them

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use assertion type, null hypothesis, alternative hypothesis, falsifiability in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output correctly classify causal, correlational, predictive, mechanistic, normative, and conceptual claims?

□ Chapter-specific criterion 2: Does every empirical claim have a plausible falsification condition?

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
