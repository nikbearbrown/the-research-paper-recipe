# Chapter 11 — Quality Control
*The strongest sentence is the one the evidence can carry — not the one that sounds the most confident.*

The paragraph is elegant. The sentences flow. The argument builds to a clean conclusion: "This intervention demonstrates that AI improves learning."

The table in the Results section says something narrower. One subgroup. One immediate outcome measure. No delayed test. No control group that was identical in all other respects. The effect is real, but it is specific in ways the sentence is not.

The problem is not the sentence's sound. The problem is the distance between what the sentence claims and what the evidence shows. That distance is invisible when you're reading for flow. It becomes very visible when a reviewer reads the sentence and then opens the table.

Quality control starts with claims, not commas. The sentence sounds good. The sentence may not be true at the scope it's asserting. Those are different problems, and only the second one is a quality failure.

---

The procedure I call a claim audit is simple in principle and uncomfortable in practice.

Read through your draft and highlight every sentence that makes a claim about the world — not about what prior research found, not about what the study did, but about what is true. "The intervention improves learning" is a claim about the world. "Socratic feedback produced higher delayed retention scores" is a claim about the world. "AI tutoring is increasingly common in undergraduate settings" is a claim about the world.

For each highlighted sentence, ask: what specific evidence supports this, and is that evidence sufficient for the scope of this claim? Then label the sentence as one of: supported (the evidence I have licenses this specific claim in this specific scope), partially supported (some evidence supports this but it requires qualification), overstated (the scope is broader than the evidence), unsupported (no evidence provided or referenced), needs citation (the claim requires a source and doesn't have one), or needs qualification (the claim is true under some conditions but stated as universal).

This is the audit. It is not a readability check. It is a truth check.

The claim "demonstrates that AI improves learning" will almost certainly come back labeled overstated. "Demonstrates" is too strong — demonstration requires a design that rules out alternative explanations. "AI" is too broad — you studied a specific AI tutoring system with a specific feedback type. "Improves learning" is too broad — you measured one outcome, at one time point, in one population. The label isn't a criticism. It's a diagnosis. The sentence needs to be narrowed to the scope the evidence actually supports.

<!-- → [TABLE: Claim audit labels — six rows: supported, partially supported, overstated, unsupported, needs citation, needs qualification — columns: definition, what triggers this label, example claim, what revision looks like] -->

---

The worked example from the beginning of the chapter makes the mechanics concrete.

Original claim: "The intervention demonstrates improved learning across students."

Break it down. "Demonstrates" — requires a design that rules out rival explanations. Is that what you have? If the comparison group is weaker on pre-test scores, or if assignment wasn't random, "demonstrates" is too strong. "Improved learning" — which learning measure? What timescale? What type of learning? If the only measure is an immediate aligned post-test, this is at most "improved immediate performance on aligned items." "Across students" — all students, or the students in your sample at this institution? If generalizability is unargued, "across" is unsupported.

Revised claim: "The intervention improved immediate performance on the aligned post-test in this sample."

The revised claim is less dramatic. It is also more true. It is the claim the evidence can carry. A reviewer who pushes back on this sentence will need to argue that the immediate aligned post-test is not a valid measure of what it says it measures — which is a more specific and answerable objection than "you haven't demonstrated learning across all students." The narrower claim is harder to attack because it makes fewer promises. Making fewer promises than you can keep is not timidity. It is precision.

There is a real limit here, worth naming: excessive qualification makes real findings unreadable. "In this sample of 70 undergraduate students at one research university, using one AI tutoring platform for one semester, on one aligned immediate post-test, the intervention group scored numerically higher than the control group with a moderate effect size, though this may not generalize" is technically accurate and practically useless. The goal is calibration — claims scoped to what the evidence supports — not maximum hedging. The test is: does the claim make promises the evidence can't keep? If yes, narrow it. If no, leave it.

---

A claim audit handles the logic layer of quality control. There is a second layer that is more mechanical but equally important: statistical integrity.

Statistical integrity is a claim audit for numbers. Every quantitative claim in the paper — every p-value, every effect size, every confidence interval, every comparison stated in words — needs to match what the output and tables actually show. This sounds obvious. The failure rate in published papers is not negligible.

The GRIM test (Granularity-Related Inconsistency of Means) and related methods have identified systematic reporting errors in published research — means that are mathematically impossible given the sample size and scale, p-values that don't correspond to the stated test statistics and degrees of freedom. Some of these are mistakes. Some are errors introduced during transcription between software output and manuscript. None of them are caught by prose editing, because the error lives in the number, not in the sentence surrounding it.

The statistical integrity check: for every quantitative claim, trace it to its source. The p-value in the Discussion discussion should match the p-value in the Results table, which should match the output file. The effect size described in the Abstract should match the effect size reported in Results. The comparison described in words in the Discussion ("Socratic feedback produced significantly better retention") should correspond to a specific test with a specific result reported somewhere in Results, not to a general impression of the findings.

This is tedious. Do it anyway. The reviewer who catches a mismatch between a p-value in the text and a p-value in the table has found evidence of either carelessness or error, and will reasonably wonder what else might be wrong.

<!-- → [TABLE: Statistical integrity checklist — rows: p-values, effect sizes, confidence intervals, comparison language, descriptive statistics — columns: where it should appear in the paper, what to check against, common mismatch patterns] -->

---

There is a particular failure mode with AI editing tools that this chapter needs to name directly, because it is specific to the current moment and its consequences are non-obvious.

AI tools are very good at improving prose style. They can turn an awkward sentence into a clean one, vary sentence length for rhythm, find more precise vocabulary, and make a paragraph read more smoothly. This is useful. It is not quality control.

The specific danger: AI polish can make an unsupported claim harder to detect. An unsupported claim in rough prose draws attention to itself because the sentence is awkward; something feels off, and the reader looks more closely and finds the problem. The same claim, polished to fluency by an AI tool, reads smoothly and confidently, and the reader's attention flows past it. The error is still there. It is now harder to see.

The implication is sequencing: run the logic audit and the statistical integrity check before any AI editing. Fix the logical errors in rough form, where they're visible. Then improve the prose. If you improve the prose first, you are at risk of polishing over problems that should have been corrected.

This is not a criticism of AI editing tools. It is a description of how human cognition works: fluent text is easier to accept, harder to question. The tool is working as designed. The writer's job is to use it at the right point in the revision process.

---

There is a third tool for quality control that is distinct from the claim audit and the statistical integrity check, and it provides something neither of those can: outside perspective.

Give a section of your draft to someone who has not been living inside your research. Not a domain expert — a naive reader. Ask them to summarize, in their own words, what the section claims. Then compare their summary to your intended claim.

The gaps that appear in this comparison are the most informative feedback you can get about claim drift.

Claim drift is what happens when a paper accumulates successive layers of reasonable prose additions, each of which slightly expands the scope of a claim, until the final version is making a claim that the original evidence doesn't support — and no single step in the drift is obviously wrong. The introduction says the study examines AI feedback and learning. The literature review says prior work suggests gains from AI feedback. The Discussion says this study adds to the evidence that AI feedback supports learning. Each step is a small escalation. The aggregate escalation may have crossed from what the evidence supports into territory the evidence can't defend.

The naive reader has no investment in the escalation. They read what the text says. If they report that the paper claims AI feedback improves learning across contexts, and the evidence is from a single sample at a single institution, the gap between their summary and your intended claim is exactly the calibration problem you need to fix.

The naive reader test works best on the Discussion and the Abstract, because those sections are where claim drift concentrates. The Discussion is where the writer is most tempted to expand findings into implications, and the Abstract is the compression of whatever the paper became in the drafting process — including any drift that accumulated along the way.

---

Logic problems and style problems are different kinds of problems, and they require different kinds of fixes.

A style problem makes a sound claim hard to read. Passive voice where active voice would be cleaner. A sentence that is grammatically complex enough to require re-reading. A pronoun with an unclear referent. These are real problems — they slow the reader, create ambiguity, and reduce the paper's impact. But they are not epistemic failures. A claim that is awkwardly expressed but well-supported by evidence is a style problem. Fix it and move on.

A logic problem makes the claim unsupported by the evidence. The subject of the sentence is too broad. The verb implies a causal relationship the design doesn't support. The scope is universal when the sample is narrow. These are not prose problems. Smoothing the sentence does not fix them. The fix requires narrowing the subject, changing the verb, or qualifying the scope — changes to what the sentence claims, not to how the sentence reads.

Mixing these two types of problems up creates a particular failure: revising for logic when you should be revising for style, and vice versa. The writer who changes "demonstrates" to "suggests" because it sounds less aggressive has made a style choice, not a logic correction — "suggests" is still too broad if the evidence is from a single subgroup. The writer who rewrites a clear, well-supported sentence because it feels flat has spent time on style when the sentence was already doing its job.

The claim audit sorts these. A sentence labeled overstated needs a logic revision — change what it claims. A sentence labeled unclear or wordy needs a style revision — change how it says it. Don't mix them.

<!-- → [TABLE: Logic problem vs. style problem — rows: six example sentences — columns: what kind of problem it is, what the fix looks like for each type, what the wrong fix looks like] -->

---

One last note about the claim audit in the context of what's come before in this book.

Chapters 1 through 10 are about getting things right before the draft exists: the right hypothesis, the right design, the right measures, the right data quality, the right statistical test, the right framing. Chapter 11 is about what to do after the draft exists. The premise is that you followed the earlier steps, the draft is broadly honest, and now you are checking whether any drift crept in during the writing — whether any sentence outran the evidence in ways that the drafting process introduced.

The claim audit cannot fix a study with a wrong design, a measure that doesn't capture the construct, or data that was missing for outcome-relevant reasons. Those problems were addressed, or not, before the draft was written. What the claim audit can do is ensure that the draft accurately represents what the study actually showed — no more, no less.

The strongest sentence is not the most confident sentence. It is not the most impressive-sounding sentence. It is the sentence that says something specific and true, in the exact scope the evidence supports, in language that lets a reader evaluate it. That sentence will survive review. The confident sentence that outruns the evidence will not — and the longer it survives in the draft, the more it costs to remove.

---

## Exercises

### Warm-up

**1.** Take one page of a draft you are working on. Highlight every sentence that makes a claim about the world (not about what a source said, not about what the study did — about what is true). For each highlighted sentence, assign one label: supported, partially supported, overstated, unsupported, needs citation, or needs qualification. Do not revise yet — just label. Count how many sentences in each category. Note which category is most common.

**2.** Take the following sentence and run it through the claim audit process: "AI tutoring systems improve student learning outcomes by providing timely and personalized feedback." (a) Identify every claim the sentence makes. (b) Ask what specific evidence would be required to support each claim at this scope. (c) Label the sentence using the audit taxonomy. (d) Rewrite it in the most precise language that a typical study in this area could actually support.

### Application

**3.** Find a Discussion section in a published paper. Read it once for comprehension, then read it again specifically hunting for: causal verbs in observational studies, scope claims that are broader than the sample, certainty language for findings with wide confidence intervals, and implications stated as conclusions rather than possibilities. Mark each instance. Then write the revised sentence for the three most serious examples.

**4.** Take a quantitative sentence from a Results section ("The experimental group scored significantly higher, *p* = .03") and trace every number in it to its source. Find: the test output, the table it should appear in, and the corresponding claim in the Abstract. Check whether all three match. If they don't, describe the mismatch and what would be needed to resolve it.

### Synthesis

**5.** Give the Discussion section of a paper you're working on to someone who has not read it before. Ask them to write a two-sentence summary of what the paper claims. Compare their summary to your intended claim. Write a paragraph analyzing the gap: what did they report that you didn't intend, or fail to report that you thought was clear? Identify which sentences in the Discussion produced the misalignment and revise them.

**6.** A colleague uses an AI editing tool to polish their Discussion section before running a claim audit. They report that the revised version reads much more smoothly. Using this chapter's argument, explain specifically what risk the colleague has introduced by running style improvement before logic audit. Give one example of how a style improvement can make a logic problem harder to detect.

### Challenge

**7.** Take a complete Abstract from a published paper. Run a full claim audit on it: for each claim, identify the assertion type (from Chapter 3), locate the specific evidence in the paper that supports it, label the claim, and note whether the abstract's scope matches the Results section's scope. Then write a revised abstract that passes the claim audit — every sentence supported at the scope it asserts, no drift from Results to Abstract. Note: this exercise is harder than it looks if the paper has any drift between sections.

---

## LLM Exercises

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
