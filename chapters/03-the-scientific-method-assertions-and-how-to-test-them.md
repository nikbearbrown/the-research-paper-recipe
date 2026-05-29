# Chapter 3 — The Scientific Method: Assertions and How to Test Them
*The verb in your claim chooses the burden of proof.*

Here is a sentence a student once handed me:

"AI feedback improves learning because students engage more deeply."

It reads like a scientific claim. It has the structure of an argument — a cause, an effect, a mechanism. It uses the vocabulary of educational research. And yet, in twelve words, it has made at least three distinct bets: that AI feedback causes better learning outcomes, that the operative mediator is engagement depth, and that engagement is an explanatory construct that genuinely means something. If the study behind this sentence only compared students who used an AI platform with students who didn't — no random assignment, no measure of engagement, no delayed unassisted test — then the sentence has already outrun the evidence by several lengths.

This happens constantly. Not because researchers are dishonest, but because the verbs in natural language carry more weight than writers notice when they're writing. "Improves" is a causal verb. "Because" is a mechanistic connective. Both carry evidentiary burdens that a comparison study cannot discharge.

The scientific method, at its core, is a discipline for noticing when your language has made a promise your evidence can't keep.

---

Before we get to the machinery of null hypotheses and testing frameworks, I want to spend some time on a concept that precedes all of that: the assertion.

An assertion is a claim that can, in principle, be evaluated as true or false — even if you don't yet know the answer. This sounds trivially obvious, but it rules out more than you'd expect. "AI is interesting" is not an assertion in this sense — there's no observation that would settle it. "I prefer Socratic feedback" is a report of preference, not a claim about the world. "Students should receive more individualized feedback" is a normative claim — a claim about what ought to happen — and data alone cannot settle it, no matter how well designed the study.

The reason the distinction matters is that different types of assertions require different types of evidence, and using the wrong evidence for an assertion type is a logical error regardless of how strong the evidence is.

Let me walk through the taxonomy, because once you have it, you start to see it everywhere.

A **descriptive** claim reports what happened or what is true in some population: "Sixty percent of students in the sample used AI hints at least once per problem set." This requires measurement. It does not require a control group, a comparison, or a causal argument. Its evidentiary burden is: did you measure the right thing in the right population?

A **correlational** claim says that two variables move together: "Students who used AI hints more frequently scored higher on the post-test." This requires that both variables be measured and that their covariation be estimated. It does not license you to say one caused the other. The evidentiary burden is: did you measure both, and did you account for other variables that might explain the pattern?

A **causal** claim says one thing produced another: "AI hints improved post-test performance." This is the claim that requires the most from a design. To support it, you need something that creates a counterfactual — what would the same students have scored without AI hints? Random assignment to conditions is the standard tool for this, because it distributes all the other possible causes (motivation, prior knowledge, study habits) roughly equally between groups, leaving the intervention as the only systematic difference.

A **predictive** claim says one variable helps anticipate another, without necessarily specifying why: "Students who spend more time on problem sets before using hints score better on retention tests." This is weaker than causation but stronger than correlation — it implies a practical use (you could use hint delay as a predictor) even without a causal story.

A **mechanistic** claim explains how or why: "AI hints improve retention because they force students to identify their own errors before receiving feedback, which produces deeper processing." This is the hardest to test, because it requires not just a comparison of outcomes but evidence about the process. If you claim engagement mediates the effect, you need to measure engagement, show it varies with the intervention, and show that when you control for engagement, the effect shrinks.

A **normative** claim says what should be done: "Instructors should prefer Socratic AI feedback for courses where long-term retention matters." Data can inform this claim — evidence about what produces retention is relevant — but the claim itself involves a value judgment about what matters, which evidence alone cannot settle.

A **conceptual** claim defines or clarifies: "By 'durable retention,' I mean unassisted recall of core concepts after a two-week delay." This doesn't require empirical support; it requires precision and coherence.

<!-- → [TABLE: Assertion taxonomy — seven rows (descriptive, correlational, causal, predictive, mechanistic, normative, conceptual) — columns: definition, what evidence is required, what evidence cannot support it, example] -->

---

Now here is the move the chapter title is pointing at.

The scientific method is not, at its heart, a set of procedures for producing results. It is a discipline for keeping assertions honest. And the specific tool it uses for that is falsifiability — the demand that an empirical claim name the conditions under which it would be false.

Karl Popper's argument, stated simply, is this: a claim that can accommodate any possible evidence is not an empirical claim at all. If "AI feedback improves learning" is true when test scores go up, and also true when they go down (because "learning" is redefined to mean something that didn't get measured), and also true when there's no difference (because "improve" meant "prevents decline"), then the sentence isn't making a claim. It's making a noise that sounds like a claim.

What falsifiability demands is that you name, in advance, what you would need to see for your claim to be in trouble. For a causal claim like "Socratic AI feedback improves two-week retention more than direct-answer feedback," the falsification conditions are clear: the Socratic group's retention is not higher, or it is higher immediately but not at two weeks, or it is higher only for students who already have strong retrieval habits, making it a moderator rather than a main effect.

Each of those falsification conditions is also a design choice. If you want to be able to detect whether the effect is moderated by prior retrieval habits, you need to measure prior retrieval habits. If you want to be able to detect the difference between short-term performance and two-week retention, you need two assessment points. The falsification conditions tell you what the design requires.

<!-- → [INFOGRAPHIC: Falsifiability spectrum — from "can accommodate any evidence" on one end to "specific enough to be wrong in multiple ways" on the other — with three example claims placed along the spectrum] -->

---

The second tool the chapter title is pointing at is the null and alternative hypothesis structure, and I want to be precise about what this is and what it isn't.

Jerzy Neyman and Egon Pearson formalized statistical hypothesis testing in the 1930s as a decision procedure. The logic is not "find out whether the null is true." The logic is: assume the null is true, calculate how surprising your data would be under that assumption, and decide, at a pre-specified threshold, whether the data are surprising enough to act as though the null is false.

The null hypothesis is usually stated as the absence of the effect you're looking for: "Students who receive Socratic feedback do not differ in two-week retention from students who receive direct-answer feedback." This is the baseline — the world as it would be if your intervention does nothing. The alternative is your actual prediction: "Students who receive Socratic feedback show higher two-week retention than students who receive direct-answer feedback."

Three things are worth being clear about, because they trip up even experienced writers.

First, a significant p-value does not confirm the alternative hypothesis. It means the data would be unlikely — specifically, less likely than your threshold (usually 5%) — if the null were true. That's evidence against the null, but it's not proof that your alternative is right. There could be other explanations for the result that you haven't considered.

Second, a null hypothesis is not the same as the claim "nothing is happening." It is a specific quantitative claim — usually that the difference is zero, or that the correlation is zero. You are not testing whether "AI feedback matters in general." You are testing whether this specific measured difference, in this specific sample, at this specific time point, is larger than what you'd expect by chance.

Third, the null hypothesis is chosen by the researcher, not by convention. Your null should be the specific claim that your design is positioned to challenge. If you've designed a study to detect a retention advantage at two weeks, your null is "no retention advantage at two weeks" — not "no effect of AI feedback on anything, ever."

<!-- → [TABLE: Null vs. alternative hypothesis pairs for the three assertion types that have them (correlational, causal, predictive) — common mistakes in null formulation alongside correct versions] -->

---

Let me return to the student's sentence from the beginning of the chapter, because now we can do something with it.

"AI feedback improves learning because students engage more deeply."

Clause one — "AI feedback improves learning" — is a causal claim. Its null hypothesis is: students receiving AI feedback do not differ in learning outcomes from students in the comparison condition. The design needed to test it requires at least two conditions, a measure of learning (which needs to be defined precisely — immediate performance? delayed retention? transfer to novel problems?), and something that controls for the other differences between groups.

Clause two — "because students engage more deeply" — is a mechanistic claim. Its null hypothesis is: any effect of AI feedback on learning is not mediated by engagement depth. Testing this requires that engagement be measured, that the relationship between feedback and engagement be established, and that a mediation analysis show that the indirect path (through engagement) accounts for the outcome difference. This is a substantially more demanding design than clause one already required.

If the study behind the sentence only compared platform users with non-users — no random assignment, no engagement measure, no mediation analysis — then neither clause is supported by the design. The most the study can support is a correlational version: "Students who used AI feedback scored higher on [some measure]." The causal language and the mechanism have to come out.

This is not a small edit. It changes what the paper claims to contribute. A correlational finding is a real finding — it says something about the world — but it says something weaker than a causal finding, and the difference matters for how educators and policymakers should respond to it.

The practical move is assertion typing. Before you choose your methods, classify your central claim. Before you write the Discussion, audit every sentence for its assertion type. When you find a causal verb where you have correlational evidence, you have a choice: redesign the study or rewrite the sentence. The scientific method doesn't tell you which to choose. It tells you that you have to choose one.

---

One more thing, because it comes up in almost every paper I review.

Normative claims are legitimate. They are not unscientific. Education, medicine, public policy — all of these fields exist to make normative recommendations, and a research paper that never says anything about what should happen is often failing its audience. But normative claims cannot be settled by data alone. They require a value judgment about what matters, and that judgment is separate from the empirical evidence even when the evidence is relevant.

The common mistake is to slide between normative and empirical claims without marking the transition. "Students who receive Socratic feedback retain more, therefore instructors should use Socratic feedback" treats a causal finding as if it settles a normative question. It doesn't — not because the finding is wrong, but because "should use" involves a judgment about tradeoffs (time, implementation cost, equity of access, what other goals matter) that the data can inform but not resolve.

Separate the claims. Say: "These findings suggest that Socratic feedback produces better two-week retention under these conditions. Whether that retention advantage justifies the additional design complexity is a question that depends on the instructional context." The empirical claim stands on its own. The normative claim is made explicitly, as a claim, not dressed up as a finding.

---

## Exercises

### Warm-up

**1.** Take five sentences from your draft introduction or literature review. Classify each as descriptive, correlational, causal, predictive, mechanistic, normative, or conceptual. For any sentence that is causal or mechanistic, ask whether your study design can support that classification. If it cannot, rewrite the sentence in the strongest language your design actually licenses.

**2.** Write a null and alternative hypothesis for your main empirical claim. Make the null specific — not "no effect" in the abstract, but the specific quantitative claim your design is positioned to challenge. Read both aloud and ask: is the null actually falsifiable by the study you're running?

### Application

**3.** Take the following sentence and perform a full assertion audit: "Students who use AI tutoring systems outperform their peers because the immediate feedback loop reinforces correct reasoning before errors consolidate." Identify every assertion type present, write the null hypothesis for each falsifiable claim, and describe what study design would be required to test the mechanistic claim.

**4.** Find a published Discussion section in your field. Identify two sentences where causal language appears and check whether the study design — as described in the Methods — supports that language. If it doesn't, rewrite both sentences in the strongest language the design licenses. Note whether the paper's contribution changes when you make this substitution.

### Synthesis

**5.** Your hypothesis is: "Socratic AI feedback improves two-week unassisted programming retention more than direct-answer feedback because students must retrieve and repair their own reasoning." (a) Classify every assertion type in this sentence. (b) Write the null for the causal claim and the null for the mechanistic claim. (c) Describe what the study would need to measure, and when, to give the mechanistic null a fair chance of being falsified. (d) Explain what the study can still conclude if the outcome effect is found but the mediation is not.

**6.** A classmate argues: "Normative claims don't belong in empirical papers — data should speak for itself." Write a response using this chapter's framework. Explain what normative claims are, why they are legitimate in research papers, and what discipline is required when making them alongside empirical claims.

### Challenge

**7.** Design a study that could test the mechanistic claim in the hypothesis above — specifically, that retrieval-and-repair mediates the retention advantage of Socratic feedback. Describe the design, the measures required, and the analysis you would run. Then identify the strongest rival mechanism that your design could not rule out, and explain what additional measurement or condition would be required to distinguish them. Consider: does your revised design still fit within a realistic semester-length study, and if not, what do you give up?

---

## LLM Exercises

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
