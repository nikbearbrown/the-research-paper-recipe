# Chapter 1 — Before You Write Anything

**Chapter one-line:** Before You Write — Topic -> Research Question -> Working Hypothesis

---

## 1. Learning objectives

- Distinguish a topic, research question, and hypothesis (Understand).
- Convert a broad curiosity into a falsifiable working claim (Apply).
- Identify when AI is useful for interrogation but dangerous for hypothesis generation (Analyze).
- Explain why prose should wait until the claim can fail (Evaluate).

---

## 2. Opening case

Maya opens a blank document and types the title, "AI tutoring in education." In ten minutes, an AI tool gives her a polished introduction: broad stakes, smooth transitions, citations to check later. It feels like progress. But when her adviser asks what exactly the paper will show, Maya has three answers: AI tutoring improves learning, AI tutoring changes feedback quality, and students use AI tutoring differently depending on motivation. None is yet a paper. They are directions. The danger is that the draft now has momentum before the claim has shape.

---

## 3. Core concept explanation

A topic is a region. A research question is a question that could be answered. A hypothesis is a claim about what the answer will be and why. A research paper starts only when the writer can say the hypothesis in one declarative sentence with a subject, verb, scope, and possible failure condition. Popper's falsifiability standard is useful here because it asks what observation would count against the claim (Popper, 1959).

This book's rule is simple: do not draft until the schema exists. The schema is the chain from claim to evidence to interpretation. A fluent paragraph written before that chain exists can hide the missing link. Open-science work on preregistration makes the same point procedurally: the timing of the hypothesis matters because post-hoc explanation is easy to mistake for prediction (Nosek et al., 2018; Kerr, 1998).

AI belongs in this stage as a pressure tool, not an author. Ask it what would make the idea testable, what rival hypotheses could explain the observation, and what measurements would distinguish them. Do not ask it to decide the hypothesis for you. The research question is the author's intellectual contribution.

---

## 4. Worked example

**Situation.** Maya begins with the topic "AI tutoring in education."

**Analytical process.**

1. First pass: "Does AI tutoring help students?" This is answerable only in the loosest sense. Help which students, with what outcome, compared with what?
2. Second pass: "How does feedback specificity in AI tutoring affect undergraduate programming practice?" Now the question has a variable and a setting, but it does not yet predict anything.
3. Hypothesis: "Socratic AI feedback improves two-week unassisted programming retention more than direct-answer feedback because students must retrieve and repair their own reasoning." This can fail: the direct-answer group might retain as much, or the Socratic group might improve only on immediate performance.

**Resolution.** The paper can now be designed. It needs at least two feedback conditions, an unassisted delayed test, and a comparison that distinguishes immediate performance from retention.

**The lesson.** The lesson: a hypothesis is not a prettier topic; it is a claim that names what would defeat it.

**The limit.** The limit: exploratory work may begin without a fixed hypothesis, but it must be labeled exploratory rather than written as if it predicted its findings.

---

## 5. Common misconceptions

- **A broad topic is enough to start writing.** A broad topic creates prose without a test. In Maya's case, a polished introduction would make three possible papers sound like one.
- **AI can generate my hypothesis if I give it enough context.** AI can generate plausible hypotheses, but plausibility is not the same as fit to the actual data, literature gap, or domain problem.
- **If the introduction sounds rigorous, the paper has a claim.** Style can imitate rigor. The test is whether the writer can state the claim and the evidence that could disconfirm it.

---

## 6. Exercises

1. Take a topic from your field and write three versions: topic, research question, hypothesis. Mark what changed at each step.
2. Ask an AI tool for three rival hypotheses that could explain an observation you care about. Reject at least one and explain why your evidence could not test it.
3. Find a published abstract and identify its central claim. If you cannot find one sentence that states it, rewrite the claim yourself.

---

## 7. What would change my mind

This chapter would need revision if strong evidence showed that novice researchers produce more valid, better-scoped hypotheses by first drafting prose and then extracting claims from it. The evidence would need to compare actual study quality, not writer confidence or perceived fluency.

---

## 8. Still puzzling

- How much exploratory freedom should beginning researchers preserve before locking a hypothesis?
- When does AI-assisted interrogation become AI-assisted authorship of the claim?
- How should this process change for humanities or conceptual papers where hypotheses may not be statistical?

---

## Sources used

- Popper 1959
- Nosek et al. 2018
- Kerr 1998
- Simmons et al. 2011


---

## Chapter 1 Exercises: Before You Write Anything

**Project:** Research Paper Submission Dossier
**This chapter adds:** a topic-to-question-to-hypothesis brief for the dossier.

---

### Exercise 1 — When to Use AI

**The judgment:** In this chapter's work, AI assistance is appropriate for the following tasks:

- Generate rival framings for a vague observation — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Suggest what evidence would make a claim testable — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.
- Create search terms and adjacent-field leads — *Why AI works here:* This is a bounded support task: AI can generate options, detect patterns, or reformat material while you retain the chapter's judgment criteria.

**The tell:** You know you are using AI appropriately when you can evaluate the output — when you have independent criteria to judge whether it is correct, complete, and fit for purpose.

---

### Exercise 2 — When NOT to Use AI

**The judgment:** In this chapter's work, the following tasks require human judgment. Delegating them to AI is not appropriate — not because AI cannot produce output, but because AI output in these cases cannot be trusted without verification that requires the same expertise as doing the task yourself.

- Choosing the final hypothesis — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Deciding what question is worth asking — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.
- Treating generated novelty claims as evidence — *Why AI fails here:* This requires human calibration, domain context, or accountability that the model cannot supply as ground truth.

**The tell:** You know you have crossed the line when you are using AI output as your reason for a conclusion rather than as a tool for reaching one. If you could not explain the conclusion without the AI, the AI did the work that should have been yours.

**Series connection:** This exercise trains Tier 4 Metacognitive and Tier 7 Wisdom: the capacity to supervise machine output at the point where the project depends on topic, research question, hypothesis, falsifiability.

---

### Exercise 3 — LLM Exercise

**What you're building this chapter:** a one-page hypothesis pressure-test memo.
**Tool:** Claude chat. It is the best fit here because the task is conceptual drafting and critique, not direct file manipulation.

**The Prompt:**

```
I am building a Research Paper Submission Dossier for a research paper I may write. The dossier is a working folder of decisions, audits, and evidence checks that should make the final paper harder to overclaim.

Current chapter: Before You Write Anything. Core vocabulary for this chapter: topic, research question, hypothesis, falsifiability.

My working research topic is: AI tutoring and student learning in undergraduate programming courses. My current tentative claim is: Socratic AI feedback may improve delayed unassisted retention more than direct-answer AI feedback because it preserves retrieval effort.

Create a one-page hypothesis pressure-test memo. Use the chapter concepts explicitly. Do not decide the final research claim for me. Do not invent citations, data, or results. Where a decision requires domain judgment, write "AUTHOR DECISION REQUIRED" and explain what judgment is needed. End with three questions I should answer before moving to the next chapter.
```

**What this produces:** A draft artifact for the running dossier, suitable to save as project-dossier/01-hypothesis-brief.md.

**How to adapt this prompt:**
- *For your own project:* Replace the research topic and tentative claim with your own domain, data source, and intended contribution.
- *For ChatGPT / Gemini:* Keep the same constraints, and add "show your reasoning as bullet points, not hidden chain-of-thought."
- *For a Claude Project:* Put the project description and standing rule "do not decide my research claim for me" in the project instructions; paste the chapter-specific task as the message.

**Connection to previous chapters:** This adds the next decision layer to the same dossier rather than starting a new artifact.
**Preview of next chapter:** Next you will test whether sources and designs can support the claim.

---

### Exercise 4 — CLI Exercise

**What you're building this chapter:** The file `project-dossier/01-hypothesis-brief.md`.
**Tool:** Codex CLI or Cowork. Use a file-aware agent because the task reads prior dossier files and writes a new markdown artifact.
**Skill level:** Beginner. Comfort with a project folder helps, but no programming is required.

**Setup:**

Before running this exercise, confirm:
- [ ] A folder named `project-dossier/` exists in your workspace.
- [ ] Any earlier chapter dossier files are saved in that folder.
- [ ] Your `AGENTS.md` or `CLAUDE.md` says: "For this project, AI may draft and audit artifacts, but the human author owns the research question, evidence standard, interpretation, and disclosure."

**The Task:**

```
Read the existing files in project-dossier/. Then create or update project-dossier/01-hypothesis-brief.md.

This file should apply Chapter 1, "Before You Write Anything," to the running Research Paper Submission Dossier. Use these chapter concepts: topic, research question, hypothesis, falsifiability.

Write the file with these sections:
1. Purpose of this dossier artifact
2. Inputs read from earlier dossier files
3. Chapter 1 analysis
4. Decisions the human author must make
5. Checks to run before moving on

Do not invent sources, data, results, or final conclusions. If information is missing, write "MISSING — author must supply" rather than filling the gap. After writing the file, report what changed and list any unresolved author decisions. Stop after writing this one file.
```

**Expected output:** `project-dossier/01-hypothesis-brief.md` exists and connects this chapter's concept to the cumulative dossier.

**What to inspect in the output:** Check whether the file uses topic, research question, hypothesis, falsifiability correctly, preserves human decision points, and avoids unsupported conclusions.

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
Validation Checklist — Before You Write Anything

□ Correctness: Does the output accurately reflect the chapter's core concept?
  Does it use topic, research question, hypothesis, falsifiability in a way this chapter would endorse?

□ Completeness: Is anything important missing?
  Would a domain expert need an additional source, measure, comparison, or limitation before trusting this artifact?

□ Scope: Did the AI stay within the task boundaries?
  Did it add claims, sources, data, results, or conclusions that were not provided?

□ Chapter-specific criterion 1: Does the output distinguish topic, question, and hypothesis?

□ Chapter-specific criterion 2: Does it name what would make the hypothesis false?

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
