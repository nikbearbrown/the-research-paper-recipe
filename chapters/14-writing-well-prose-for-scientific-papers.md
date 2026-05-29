# Chapter 14 — Writing Well: Prose for Scientific Papers

**Chapter one-line:** Writing Well — Prose quality, clarity, precision, economy, flow

---

## 1. Learning objectives

- Identify prose features that obscure scientific claims (Understand).
- Revise nominalizations, vague quantifiers, and evasive passives (Apply).
- Calibrate epistemic verbs to evidence strength (Evaluate).
- Rewrite a paragraph so the claim, actor, and evidence are visible (Create).

---

## 2. Opening case

The draft says, "An improvement in performance was observed following implementation of the intervention." The sentence is grammatical. It hides the actor, the measure, the comparison, and the size of the change. Scientific prose can fail while sounding scientific. The job of the sentence is not to wear a lab coat. It is to move a claim from writer to reader with as little distortion as possible.

---

## 3. Core concept explanation

Scientific prose is a precision instrument. Gopen and Swan argue that readers interpret sentences through expectations about topic position, stress position, and logical flow (Gopen and Swan, 1990). Williams and Bizup teach the same practical lesson through characters and actions: make the central actor the subject and the central action the verb when clarity requires it (Williams and Bizup).

Fog appears as nominalization, noun strings, vague quantifiers, unnecessary passive voice, and hedging that no longer matches the evidence. Passive voice is not forbidden. It is useful when the actor is irrelevant: "Samples were analyzed." It becomes a problem when it hides decisions: "Outliers were removed" without saying who removed them and by what rule.

Good hedging is calibrated. "Demonstrates" is strong and often causal. "Suggests" is moderate. "Is consistent with" is minimal. A sentence can be overconfident, but it can also be underconfident when excessive hedging makes a clear result sound like a rumor.

---

## 4. Worked example

**Situation.** Original sentence: "A significant improvement in student outcomes was observed after implementation."

**Analytical process.**

1. Find the nominalization: improvement. Ask who improved and on what.
2. Find vague terms: significant, outcomes, implementation. Ask statistical or practical significance? Which outcome?
3. Restore actor and measure: "Students in the intervention group scored higher on the delayed posttest."
4. Add evidence: "...than students in the control group, t(62) = 2.47, p = .016, d = 0.63."
5. Calibrate verb: if randomized, "scored higher after receiving" may be acceptable; if observational, use "was associated with."

**Resolution.** Revised: "Students in the intervention group scored higher on the delayed posttest than students in the control group, t(62) = 2.47, p = .016, d = 0.63."

**The lesson.** The lesson: clear prose is claim discipline at sentence scale.

**The limit.** The limit: some disciplines require conventional phrasing, but convention should not hide decisions or inflate claims.

---

## 5. Common misconceptions

- **Scientific writing should sound impersonal.** Scientific writing should be accountable. Sometimes that is impersonal; sometimes it requires naming the decision-maker.
- **Hedging always makes a claim safer.** Unnecessary hedging can make evidence harder to interpret and can understate a real result.
- **Style is separate from truth.** Verb choice, scope, and precision can change the claim itself.

---

## 6. Exercises

1. Find every -tion, -ment, -ance, and -ence noun in a paragraph. Convert three back into verbs.
2. Replace every vague quantifier in a paragraph with a number, percentage, or scoped phrase.
3. Choose the right epistemic verb for three findings: demonstrate, show, indicate, suggest, appear, or is consistent with.

---

## 7. What would change my mind

This chapter would change if evidence showed that conventional opaque prose improves expert comprehension more than clear actor-action prose. Until then, clarity and precision remain the default standard.

---

## 8. Still puzzling

- How direct can prose be before it violates a field's register?
- When does simplification remove necessary nuance?
- How should writers preserve their own voice after AI-assisted editing?

---

## Sources used

- Gopen and Swan 1990
- Williams and Bizup
- Helen Sword 2012
- Orwell 1946


---

## Chapter 14 Exercises: Writing Well: Prose for Scientific Papers

**Project:** Research Paper Submission Dossier
**This chapter adds:** a prose revision and claim-drift check for the final dossier.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Find foggy prose and nominalizations — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Offer contrastive rewrites for author review — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Calibrate hedging when evidence is supplied — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Smoothing prose before claim accuracy is checked — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Accepting rewrites that change causal force or scope — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Letting AI erase disciplinary voice and accountability — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive and Tier 7 Wisdom: the capacity to supervise machine output at the point where the project depends on nominalization, hedging, passive voice, claim drift, precision, economy.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a final prose revision with claim-drift notes.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Writing Well: Prose for Scientific Papers. Core vocabulary for this chapter: nominalization, hedging, passive voice, claim drift, precision, economy.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a final prose revision with claim-drift notes. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/14-final-prose-review.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** The dossier is ready for author review before any submission.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/14-final-prose-review.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/14-final-prose-review.md.

This file should apply Chapter 14, "Writing Well: Prose for Scientific Papers," to the running Research Paper Submission Dossier. Use these chapter concepts: nominalization, hedging, passive voice, claim drift, precision, economy.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 14 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/14-final-prose-review.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses nominalization, hedging, passive voice, claim drift, precision, economy correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Writing Well: Prose for Scientific Papers

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use nominalization, hedging, passive voice, claim drift, precision, economy in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output improve clarity without changing meaning?

□ Chapter-specific criterion 2: Does it preserve causal force, scope limits, statistics, and hedges?

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

**Series connection:** This exercise trains Tier 4 Metacognitive and Tier 7 Wisdom: the capacity to catch when machine output is fluent, useful, and still not sufficient for the human conclusion.
