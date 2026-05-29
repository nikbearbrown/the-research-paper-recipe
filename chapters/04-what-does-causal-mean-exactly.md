# Chapter 4 — What Does Causal Mean, Exactly?
*Causation is not a stronger synonym for correlation — it is a different question about a world you cannot observe.*

A paper reports that students who used an AI tutor more often scored higher on the final exam. The Discussion says the AI tutor caused the improvement.

That sentence may be true. The study has not shown it.

Here is the problem, stated precisely: high-motivation students may have used the tutor more, studied harder, attended more office hours, and scored higher on the final exam for reasons that had nothing to do with what the tutor specifically contributed. The causal verb — "caused" — has smuggled in a comparison that the study never made. It has claimed to answer the question: *what would have happened to these same students if the tutor had not existed?* That question has a name. It is called a counterfactual. And the reason causal inference is hard is that you can never observe both sides of a counterfactual at the same time.

You either gave a student the AI tutor or you didn't. You cannot do both and compare. This is what statisticians call the fundamental problem of causal inference, and it is the reason that "correlation is not causation" is not just a methodological slogan — it is pointing at something real about what observational data can and cannot show.

---

Let me make the counterfactual structure explicit, because once you see it, you cannot unsee it in papers you read.

When a researcher says "the intervention caused the outcome," what they are really claiming is this: if the same individuals had been exposed to the intervention, they would have had outcome Y₁; if those same individuals had instead not been exposed, they would have had outcome Y₀; and Y₁ is larger than Y₀. The causal effect, for a single person, is the difference between Y₁ and Y₀.

The problem is that you only ever see one of those. A student either got the Socratic feedback or the direct-answer feedback. You can't give both and compare the same student against themselves. The counterfactual — what would have happened otherwise — is unobservable by definition.

This is Rubin's potential outcomes framework, and it clarifies why experimental design is so valuable. When you randomly assign students to conditions, you make the two groups — on average, across many students — interchangeable in all the ways that matter. The students who got Socratic feedback and the students who got direct-answer feedback are, by random assignment, similar in prior knowledge, motivation, study habits, and all the other things you didn't measure and couldn't control for. Which means the group that got direct-answer feedback is a credible stand-in for what the Socratic-feedback group would have scored if they'd gotten direct-answer feedback instead.

Random assignment doesn't let you observe the counterfactual for any individual. It creates a comparison group that approximates the counterfactual for the group on average. That's why it works. And that's why observational data — where students chose which condition they ended up in, or where assignment was based on something correlated with the outcome — struggles to support causal claims.

<!-- → [INFOGRAPHIC: Potential outcomes diagram — single student node branching into two worlds: treated (Y₁ observed) and untreated (Y₀ unobserved) — labeled "The fundamental problem: you only see one branch"] -->

---

Judea Pearl organized the kinds of questions a researcher can ask into a three-level hierarchy, and it is one of the most clarifying frameworks I know for thinking about what a study can and cannot answer.

The first level is **association**: what do we see in the data? "Students who used the AI tutor more often scored higher." This is a statement about covariation. It requires only that you measure both variables. It makes no claim about why the pattern exists or what would happen if you intervened.

The second level is **intervention**: what happens if we do something? "If we give students access to the AI tutor, their scores will improve." This is a claim about the effect of an action. It requires a design that creates a real comparison — an experiment, or something that functions like one. It is the question that randomized controlled trials are built to answer.

The third level is **counterfactual**: what would have happened if things had been different? "Students who did not use the tutor would have scored higher if they had." This is the deepest level — it requires reasoning about worlds that didn't happen. It is the logic behind retrospective questions like "did this treatment cause this patient's recovery?" where you cannot go back and withhold the treatment.

Most observational studies in education and social science produce association-level evidence. Most researchers write at the intervention or counterfactual level. The gap between those two things is where overclaiming lives.

<!-- → [TABLE: Pearl's causal hierarchy — three rows (association, intervention, counterfactual) — columns: the question it answers, what it requires, example claim, what it cannot support, typical study design that reaches this level] -->

---

There is a tool for making the gap visible, and it is called a directed acyclic graph — a DAG. The name is intimidating. The concept is not.

A DAG is a drawing of your causal assumptions. Nodes are variables. Arrows represent causal relationships — an arrow from A to B means "A causes B." The word "acyclic" means there are no loops: you can't have A causing B causing A. The word "directed" means the arrows have a direction — they point from cause to effect.

Here is why DAGs are useful: they force you to be explicit about what you believe is causing what, before you analyze any data. And once you've drawn the DAG, it tells you something non-obvious about how to analyze your data correctly.

Consider our AI tutor example. You draw an arrow from AI tutor use to exam score — that's your hypothesis. But you also believe that student motivation affects how much they use the tutor and also affects their exam score independently. So you draw arrows from motivation to AI tutor use, and from motivation to exam score. Motivation is now a **confounder** — a variable that influences both the cause and the outcome, which is why the raw association between tutor use and exam scores doesn't tell you what the tutor itself contributed.

If you've measured motivation, you can control for it in your analysis, and the DAG tells you that you should. But if you haven't measured it — and motivation is notoriously hard to measure well — then it remains a threat to causal inference that your design has to handle some other way.

<!-- → [IMAGE: Hand-drawn style DAG — nodes: AI tutor use, exam score, student motivation — arrows: motivation→AI tutor use, motivation→exam score, AI tutor use→exam score — confounder labeled in red] -->

Now introduce a second complication. Suppose you believe that the reason Socratic feedback improves retention is that it forces students to engage more deeply — to retrieve and repair their own reasoning rather than just receiving the answer. Engagement is a **mediator**: it sits on the causal pathway from the intervention to the outcome. Engagement doesn't confound the relationship; it explains it.

This distinction matters enormously for analysis. If you want to estimate the total effect of Socratic feedback on retention, you should not control for engagement — because engagement is part of how the effect works, and controlling for it would block the very pathway you're trying to measure. If you want to test the mechanism — to ask whether retrieval effort is what's doing the work — then you need to measure engagement and analyze it as a mediator, which is a different analysis from the main effect test.

Many papers control for everything they measured because they believe more controls are always better. This is wrong. Controlling for a mediator when you want the total effect is a mistake. Controlling for a confounder when you want the direct effect is correct. The DAG tells you which is which.

<!-- → [IMAGE: DAG with mediator — nodes: Socratic feedback, retrieval effort (mediator), two-week retention — arrows: Socratic feedback→retrieval effort, retrieval effort→retention, Socratic feedback→retention (direct path dashed) — total vs. direct effect labeled] -->

---

There is a third structural element in DAGs that is less intuitive and more dangerous: the **collider**.

A collider is a variable that is caused by two other variables. If both AI tutor use and student anxiety independently cause a student to seek extra help, then "seeks extra help" is a collider — it has arrows pointing into it from both directions. The counterintuitive result: if you condition on a collider — if you analyze only the subgroup of students who sought extra help — you can create a spurious association between AI tutor use and anxiety that wasn't there in the full population.

This is known as collider bias, and it is one of the less-obvious ways that controlling for more variables can make your causal inference worse rather than better. It shows up in selection problems (analyzing only people who completed the study, when completion is caused by two of your key variables), in stratification errors, and in certain kinds of case-control designs.

The practical implication: you cannot decide what to control for by looking at what's associated with your variables. You need a causal story — a DAG — that specifies the structural relationships, and then the DAG tells you what to condition on and what to leave alone.

<!-- → [IMAGE: Collider DAG — nodes: AI tutor use, student anxiety, seeks extra help (collider) — arrows pointing into collider from both — annotation: "conditioning on this node opens a spurious path"] -->

---

I want to be honest about something that is sometimes glossed over in methods courses.

Drawing a DAG does not prove anything. A DAG is a map of your assumptions, not evidence for them. The arrows you draw represent causal relationships you believe to exist based on theory, prior research, domain knowledge, and argument. Someone else, with different beliefs about the domain, might draw different arrows and reach different conclusions about what to control for.

This is not a flaw in the DAG approach. It is a feature. Making your assumptions explicit is better than leaving them implicit, because explicit assumptions can be challenged and defended. When you write "we controlled for motivation because we believe motivation independently affects both tutor use and outcomes," you have made a claim that readers can evaluate. When you write "we controlled for all available covariates," you have hidden your causal assumptions behind a procedure.

The deep point, which Pearl has argued extensively, is that causal inference is never purely statistical. Statistics can tell you about patterns in data. Causal inference requires assumptions about the data-generating process — assumptions that come from the researcher's understanding of the domain, not from the data itself. The DAG is the place where those assumptions live.

---

Now let's return to the original paper, and look at it with everything we've built.

"Students who used an AI tutor more often scored higher on the final exam. The AI tutor caused the improvement."

The first sentence is association-level. It is supported by the observational data. The second sentence is intervention-level — it claims that if you gave students the tutor, scores would improve. To support that claim, the design needs something that creates a credible counterfactual: random assignment, a natural experiment where tutor access was assigned by something unrelated to motivation, an instrumental variable that predicts tutor use but doesn't independently affect scores.

If none of those design features are present, the paper has two honest options. It can rewrite the second sentence in association language: "AI tutor use was associated with higher exam scores; whether this reflects a causal effect remains to be tested." Or it can propose a follow-up design that would support the causal claim: "Future work should randomly assign tutor access to isolate the effect of the tool from the selection effects that likely confound this analysis."

What it cannot do, without making an error, is keep observational evidence and write experimental verbs. Causation is not a stronger synonym for correlation. It is a different claim, about a different question, requiring different evidence.

The verb "caused" is not a prize for a strong correlation. It is a commitment to a counterfactual comparison that your design either supports or doesn't. When you write it, you are telling your reader something specific about what your study showed. If the study didn't show that thing, the word is wrong — not strong.

---

## Exercises

### Warm-up

**1.** Find a Discussion section in a published paper that uses a causal verb ("caused," "produced," "led to," "resulted in," "improved"). Look at the study design in the Methods section. Does the design support a causal claim — specifically, does it create a credible counterfactual? If not, rewrite the sentence in the strongest language the design licenses.

**2.** Write the counterfactual question behind your own main hypothesis. State it in the form: "What would have happened to [population] if [condition] had been [different]?" Then describe what your study design does — or doesn't do — to approximate the answer.

### Application

**3.** Draw a DAG for your main hypothesis. Include: the proposed cause, the proposed outcome, at least one confounder you are worried about, and (if your hypothesis includes a mechanism) the proposed mediator. Label each arrow with your justification for why you believe that causal direction exists. Identify which variables you have measured and which you haven't.

**4.** Using your DAG from Exercise 3, identify which variables you should and should not control for in your main analysis, and explain why. If any variable in your design could function as a collider, describe how you would detect and handle that.

### Synthesis

**5.** Place the following three claims on Pearl's causal hierarchy and explain what design each would require: (a) "Students who completed more practice problems before using the tutor scored higher." (b) "Giving students access to Socratic feedback raised their exam scores by half a standard deviation." (c) "Students who failed to complete the course would have passed if they had received Socratic feedback in week three." For each, describe whether existing study designs in your field can reach that level, and if not, what would be required.

**6.** A classmate argues: "I controlled for twelve covariates, so my causal inference is solid." Using the confounder, mediator, and collider framework from this chapter, explain why more controls are not always better. Give one example of a variable type that, if controlled for incorrectly, would make causal inference worse rather than better.

### Challenge

**7.** Identify a published observational study in your field that makes causal claims. Draw the DAG you believe the authors implicitly assumed. Then draw an alternative DAG — with different arrow directions or additional nodes — that would be consistent with the same data but would imply different analysis choices and different conclusions. Write two paragraphs explaining why the data alone cannot distinguish between your two DAGs, and what additional evidence or design feature would be required to do so.

---

## LLM Exercises

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
