# Chapter 9 — Literature Review

**Chapter one-line:** Literature Review — Synthesize, CARS framing, thesis locked

---

## 1. Learning objectives

- Distinguish synthesis from source summary (Understand).
- Use CARS moves to establish a research niche (Apply).
- Build a synthesis matrix across themes and methods (Create).
- Detect citation monoculture and one-sided evidence (Analyze).

---

## 2. Opening case

A literature review paragraph begins, "Smith found X. Garcia found Y. Chen found Z." Every sentence is true. The paragraph still has no argument. The reader knows what three sources said but not how the field is structured, what is disputed, or why this new paper needs to exist.

---

## 3. Core concept explanation

A literature review is not a parade of sources. It is a map of what is known, what is contested, and what gap the present paper will occupy. Swales's Create a Research Space model gives a durable pattern for introductions: establish territory, establish niche, and occupy the niche (Swales, 1990).

Synthesis means organizing by problem, method, population, mechanism, or debate rather than by source. Booth, Colomb, and Williams describe research writing as a movement from problem to claim to evidence, which fits the literature review's job: it should make the student's claim necessary rather than merely possible (Booth et al., 2016).

AI can help cluster notes and suggest themes, but it must not generate citations. Every reference belongs to a source the author has located, opened, and verified. Citation hallucination is not a formatting error; it is a provenance failure.

---

## 4. Worked example

**Situation.** A student has eight articles on AI tutoring.

**Analytical process.**

1. Source-by-source version: each paragraph summarizes one study. The gap remains invisible.
2. Matrix version: rows are themes such as feedback specificity, student agency, retention timescale, and measurement type; columns are studies.
3. The pattern appears: many studies measure immediate performance; few isolate direct answers versus scaffolded hints; fewer use delayed unassisted tests.
4. CARS version: territory = AI tutoring is expanding; niche = feedback form and retention are under-isolated; occupation = this study tests direct-answer versus Socratic prompting on delayed retention.

**Resolution.** The literature review now builds the need for the hypothesis instead of listing adjacent work.

**The lesson.** The lesson: the literature review should make the research question feel inevitable.

**The limit.** The limit: CARS is a model, not a universal template; disciplines vary in how directly they state the niche.

---

## 5. Common misconceptions

- **A literature review proves I read enough sources.** It proves the writer can locate the claim within a field.
- **One paragraph per source is organized.** It is easy to follow but intellectually weak unless each source is part of a cross-source claim.
- **AI can safely provide citations if asked for real ones.** Every citation must be independently verified against an actual source.

---

## 6. Exercises

1. Build a synthesis matrix for five sources with rows for theme, method, measure, population, and limitation.
2. Annotate a published introduction for CARS Moves 1, 2, and 3.
3. Rewrite a source-by-source paragraph as a theme-driven paragraph.

---

## 7. What would change my mind

This chapter would change if empirical writing research showed that novice writers learned synthesis better through another model than matrices plus CARS. The criterion would be stronger gap statements and fewer source-list paragraphs.

---

## 8. Still puzzling

- How explicit should the gap statement be in fields that value indirect argument?
- How can citation diversity be improved without tokenistic source selection?
- When does a literature review become a separate article rather than a section?

---

## Sources used

- Swales 1990
- Swales and Feak
- Booth Colomb Williams
- Torraco 2005


---

## Chapter 9 Exercises: Literature Review

**Project:** Research Paper Submission Dossier
**This chapter adds:** a CARS-aligned synthesis matrix.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Cluster verified notes into themes — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Suggest adjacent literatures to verify — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Diagnose source-by-source organization — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Generating citations or claims about unread papers — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Replacing source reading with AI summaries — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Smoothing away disagreement into fake consensus — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive and Tier 6 Collective: the capacity to supervise machine output at the point where the project depends on synthesis, CARS, territory, niche, occupation, citation monoculture.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a literature synthesis and CARS niche memo.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Literature Review. Core vocabulary for this chapter: synthesis, CARS, territory, niche, occupation, citation monoculture.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a literature synthesis and CARS niche memo. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/09-literature-synthesis.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will draft sections in an order that protects the claim.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/09-literature-synthesis.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/09-literature-synthesis.md.

This file should apply Chapter 9, "Literature Review," to the running Research Paper Submission Dossier. Use these chapter concepts: synthesis, CARS, territory, niche, occupation, citation monoculture.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 9 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/09-literature-synthesis.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses synthesis, CARS, territory, niche, occupation, citation monoculture correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Literature Review

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use synthesis, CARS, territory, niche, occupation, citation monoculture in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output synthesize across sources rather than summarize one by one?

□ Chapter-specific criterion 2: Does it preserve disagreement, method differences, and citation diversity concerns?

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
