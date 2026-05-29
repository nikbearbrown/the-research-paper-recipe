# Chapter 13 — Ethics and Bias Screen
*Ethics is the final form of claim calibration — what you disclose, what you scope, and what you owe the reader.*

Here is a paper that looks fine on inspection.

The study is small — 43 volunteers from one undergraduate programming course at one university. The Conclusion says the findings "demonstrate how students learn with AI tutoring." The literature review cites eight sources, all reporting positive effects of AI feedback on learning outcomes. An AI tool rewrote the Discussion for clarity; the author decided this was only a style improvement and added no disclosure. The limitations section describes one limitation — sample size — and frames it as minor given the consistency of findings.

None of these choices is dramatic. No data was fabricated. No result was misreported. The statistics are correctly calculated and honestly presented. And yet the paper is less honest than it needs to be. The claim "how students learn with AI tutoring" is not what 43 volunteers from one course demonstrates. The eight supportive citations do not represent what the field found — they represent one corner of what the field found. The AI assistance that reshaped the Discussion did affect the argument, even if the facts themselves didn't change. The limitations section names one thing and implies the evidence is otherwise solid.

Each gap is small. Together they add up to a paper that overstates its generalizability, conceals its intellectual debt, and gives readers insufficient information to calibrate how much to trust the findings.

This chapter is about finding those gaps before submission.

---

Disclosure is the most procedurally clear layer of the ethics screen, so it is a good place to start.

Publication ethics bodies have established that authors are accountable for all content in a paper — regardless of who or what produced any of it. The COPE (Committee on Publication Ethics) guidelines and ICMJE statements both address this: AI tools cannot be listed as authors, because authorship carries accountability for the work, and AI systems cannot take that accountability. The human authors who used AI tools remain fully responsible for the content those tools helped produce.

The practical implication is disclosure: when AI tools contributed to the work in any substantive way, that contribution should be named. What "substantive" means is not universally defined, and different journals have different thresholds. Some require disclosure of any AI assistance in the manuscript preparation process. Some require disclosure only for AI involvement in data analysis or interpretation. Some are still developing their policies. The only reliable approach is to check the target journal's current author guidelines before submission.

The disclosure should be specific. Not "AI tools were used" — which tells the reader nothing — but "An AI language model (Claude, Anthropic) was used to assist with restructuring the Discussion section for clarity. All substantive content, including all claims, citations, and interpretations, was produced by the authors and verified independently." This sentence tells the reader what was done, who or what did it, and what the human authors retained responsibility for.

The common rationalization for omitting disclosure is that the AI "only helped with style" and therefore doesn't count as substantive assistance. This rationalization is problematic for two reasons. First, style and substance are not fully separable in research writing — how a Discussion is structured determines what claims are foregrounded and how uncertainty is communicated. Second, journal policies don't always make this distinction, and an author who omits disclosure based on their own judgment about what counts may be violating the policy of the venue they're submitting to. When in doubt, disclose. A disclosure that wasn't required costs nothing. An omitted disclosure that was required can cost the paper.

<!-- → [TABLE: AI disclosure template — rows: different types of AI use (analysis, writing/restructuring, code generation, figure preparation, literature search assistance) — columns: example disclosure language, what the disclosure must name, what human accountability statement is needed] -->

---

The second layer of the ethics screen is overgeneralization — and this is where the ethical question and the epistemic question become the same question.

A narrow sample does not forbid a paper. Studies with small, local samples can be valuable, precisely because they produce detailed knowledge about a specific context. The ethical problem is not the sample size. The ethical problem is claiming more generalizability than the sample supports.

"Students learn more effectively with Socratic AI feedback" is a claim about students in general. "Students in this sample — 43 undergraduates in an introductory programming course at a research university — showed higher delayed retention scores in the Socratic feedback condition" is a claim about this sample. The first claim is what a reader takes away when they encounter the finding in an abstract or conclusion. The second claim is what the evidence actually supports.

The gap between these two claims is not just a stylistic difference. It is the difference between a paper that instructs instructors about what to do for their students, and a paper that reports a finding in a specific context that may or may not generalize to theirs. Readers who encounter the broader claim and act on it are operating on information the study didn't earn. The author who wrote the broader claim is responsible for that.

The practical audit: for every generalization in the Abstract, Introduction, and Conclusion, identify the sample it is based on. If the sample is specific — particular institution, particular course level, particular population characteristics — the claim needs to reflect that specificity. Not through disclaimers appended to the end of the sentence, but through the structure of the claim itself. "In our sample of introductory programming students" is part of the subject, not an afterthought.

Limitations sections are the natural home for this, and most papers have them. The problem with many limitations sections is that they treat the limitations as apologies rather than as instructions for reading. A limitations section that says "the small sample size limits generalizability" and then returns to claiming broad implications is not doing the work it claims to do. A limitations section that specifies which aspects of the findings are specific to this context and which might plausibly extend further — and why — is doing genuine epistemic service.

<!-- → [TABLE: Overgeneralization audit — rows: Abstract, Introduction niche statement, Discussion conclusion, Limitations — columns: what broad claim appears, what the sample actually is, revised language scoped to sample] -->

---

Citation bias is the third layer, and it is the one that is easiest to rationalize away.

The natural impulse when building a literature review is to find sources that support the argument you want to make. This is partly appropriate — you are building a case, and the sources are your evidence. The problem arises when the selection becomes systematically one-sided: citing only the studies that found positive effects, omitting the null findings, citing the larger effects and not the smaller ones, ignoring the methodological critiques.

Research on publication bias and citation bias documents that this is not a hypothetical problem. Fanelli demonstrated that the proportion of positive results in published papers has increased over time, which suggests either that research has become more efficient or that negative findings are systematically underrepresented. A literature review built on published sources inherits that bias unless the author actively looks for contrary evidence.

The citation audit asks: is this literature review representative of what the field actually found, or only of what got published and what I chose to cite? The check is not just about whether disconfirming evidence exists — it's about whether the review's characterization of the field is accurate.

The practical steps: search specifically for null findings, for methodological critiques, for replications that found smaller effects. Note what proportion of your citations found positive, mixed, or null effects. If the answer is all positive, either the field has unusually consistent findings (which should be noted) or you have inadvertently built a one-sided review (which needs correcting). A literature review that acknowledges "most studies found positive effects, though several observational studies found null effects when controlling for prior ability" is more trustworthy than one that presents convergent positive evidence without noting that some of the convergence may be selection effects.

This is not the same as both-sidesing every literature review with artificial balance. It is the difference between accurately characterizing what is known and presenting a curated selection that overstates consensus.

---

There is a fourth layer of the ethics screen that is less about disclosure and more about future-use accountability: replication fitness.

A paper that cannot be replicated is a paper that makes a claim the field cannot verify. Replication fitness is not identical to full open science — some data is legitimately sensitive or proprietary, some materials are protected, some analyses require specific software licenses. But it is a question every author should ask: if another researcher wanted to test whether this finding holds in a different sample, what would they need, and is that information available?

At minimum, replication fitness requires that the methods be described in enough detail that another researcher could implement the same design. The intervention should be specified precisely enough to reproduce. The measures should be named and referenced. The analysis decisions — the ones that matter, including the pre-specified primary outcome, the exclusion criteria, the covariates — should be reported.

The researcher who omits these details may be protecting intellectual property or simplifying a complex protocol. The cost is that the finding cannot be tested. A finding that cannot be tested is one that the community of researchers cannot build on — they can cite it, but they cannot know whether it holds beyond this sample and this context.

The ethics screen asks whether the paper is written in a way that allows scrutiny. Not whether it invites challenge, but whether the information needed for challenge is present.

---

The chapter's central claim deserves to be stated plainly: ethics in research writing is not only about institutional approval, consent forms, and conflict-of-interest statements. Those things matter. They are also the layer that gets the most attention and often the only layer that gets systematic attention. But they are the beginning of the ethics question, not the end of it.

The deeper ethics question is: does this paper give its readers an accurate picture of what was found, in a form that allows them to evaluate it and act on it appropriately? That question runs through the scope of the claims, the representativeness of the citations, the completeness of the disclosures, the specificity of the limitations, and the adequacy of the methods description.

None of these are decorative requirements. They are what it means for a research paper to be honest. The study was small and local and useful. Saying it was small and local and useful is not a failure. It is what allows the finding to contribute accurately to the field. A small, local finding reported honestly is more valuable than a small, local finding reported as if it were universal — because the honest version can be integrated correctly, while the overstated version will eventually be found out and discounted, along with anything the author writes thereafter.

Ethics is the final form of claim calibration. The earlier chapters calibrated the claim against design, measurement, data quality, and statistics. This chapter calibrates the claim against accountability: who knows what, what was disclosed, what was concealed, and whether a reader who trusted this paper would be well served or misled.

---

## Exercises

### Warm-up

**1.** Read the Abstract and Conclusion of a paper you are working on or have found. For every generalization — every claim about "students," "learners," "practitioners," or other general groups — identify the specific sample the finding is based on. Rewrite each generalization so that its subject accurately reflects the sample. Note which revisions change the paper's apparent contribution and which do not.

**2.** Draft an AI-use disclosure for a study in which: an AI language model was used to suggest alternative phrasings for the Discussion section, AI-generated code was used to produce the data visualizations (with all values supplied by the researcher), and an AI tool was used to generate initial search terms for the literature review. Write the disclosure in a form that would satisfy a journal that requires disclosure of any substantive AI assistance. Then check it against one published journal's author guidelines for AI use.

### Application

**3.** Audit the reference list of a literature review — either your own or a published paper's. Sort the citations by finding direction: positive, null, mixed, or unclear. Calculate the proportion in each category. If the positive proportion is substantially higher than what you'd expect from a representative sample of the field, write the sentence that should appear in the literature review acknowledging this pattern.

**4.** Write a limitations paragraph for the AI tutoring study. The sample is 43 undergraduates at one research university in one programming course. The design is randomized but the attrition was differential. The measure is a two-week delayed retention test on programming concepts covered in the course. Write the paragraph in a form that names the limitations as instructions for reading — what the findings apply to, what they do not, and what would be needed to extend them — rather than as apologies.

### Synthesis

**5.** A paper's current Conclusion reads: "These findings demonstrate that Socratic AI feedback improves learning outcomes for students, with implications for instructional design across higher education." Run the overgeneralization audit on this sentence. Identify every claim that outpaces the sample (43 undergraduates, one institution, one course, two-week delayed retention on programming concepts). Then rewrite the Conclusion in the most specific language that the evidence can support — language that names the actual contribution without shrinking from it.

**6.** The student in the chapter's opening case decided that AI assistance with "only style" did not require disclosure. Write a response that explains why this reasoning is problematic, using three distinct arguments: one about the style/substance distinction, one about the author's accountability, and one about journal policy. Conclude with the disclosure the author should have written.

### Challenge

**7.** You are preparing to submit the AI tutoring study to a journal. Find the current author guidelines for one relevant journal in your field. Check them for: AI disclosure requirements, limitations-section requirements, data/materials sharing requirements, and conflict-of-interest requirements. Write the full disclosure section — all four components — that you would include in your submission, using the actual journal's requirements as your standard. Note any requirement that the study as described would not currently satisfy, and describe what would need to change.

---

## LLM Exercises

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
