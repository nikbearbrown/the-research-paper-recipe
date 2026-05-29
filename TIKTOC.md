# The Research Paper Recipe
### A Complete Workflow from Raw Curiosity to Submission

---

## The Core Principle

A research paper is not a writing product. It is a public knowledge claim. Treat it that seriously.

The most common reason papers fail review is not bad writing — it is that they were submitted before the thinking was done. Polished prose cannot save a vague hypothesis or a method that cannot support its conclusions. This recipe separates the intellectual work from the writing work, and puts gates between the chapters so a weak foundation does not get hidden by better prose.

The order here matters. Do not skip ahead.

### The schema before the draft

Build the argument structure before writing prose. The schema is the chain from hypothesis to evidence to interpretation: each link explicit, each gap named, each inferential step defensible. A researcher who drafts without a schema produces prose that hides its own holes in fluency. A researcher who builds the schema first finds the holes before they are embedded in polished sentences.

The schema for a research paper has three layers. The intent layer: what is the central claim, who is the reader, what should they understand after reading? The evidence layer: what data supports each component of the claim, what is the comparison, what would falsify it? The structural layer: which sections exist, what does each one do, and in what order must they be confirmed before the next is drafted?

Nothing drafts until the schema is built. This applies especially to AI-assisted writing: if you prompt for prose before the argument is clear, you get fluent text organized around whatever the model inferred your argument to be — which may not be your argument at all.

### The fluency trap

AI generates fluent prose. Fluency is not understanding. A paragraph that reads smoothly can contain a conclusion the data does not support, causal language the design cannot justify, and a structure that sounds like argument but is not. The fluency of the output is a poor signal of its intellectual validity.

The test: can you explain the central claim, its evidential basis, and its limitations to a colleague who has not seen your data? If you cannot, you do not yet understand your own paper well enough to let AI draft any part of it. AI generates prose against a specification you provide. If the specification is incomplete, the output is polished incompleteness.

---

## Chapter 1 — Before You Write Anything

### Start with a main point, not a topic

A topic is an area. A research question is answerable. A hypothesis is testable.

| Stage | Example |
|---|---|
| Topic | AI tutoring in education |
| Research question | How does AI tutoring affect feedback quality in undergraduate programming courses? |
| Hypothesis | AI tutoring improves learning when it gives immediate, specific feedback, but its benefit decreases when students use it to bypass problem-solving |

A good paper needs a claim that can fail. If nothing could prove you wrong, you are writing advocacy, not research.

**Test:** Write your thesis as a single declarative sentence — subject, verb, scope. If you cannot do this, you are not ready to write. Every paragraph in the finished paper must illuminate this thesis. Do not start writing until you know the main point. Until you know the main point, you have nothing to say.

### Map the narrative arc

Before touching the IMRaD structure, sketch the story. What did you want to learn? Why did you need to learn it? What did you do? What do you know now?

This approach follows a logic of discovery rather than a logic of presentation. It begins by defining the core reasoning of the paper before turning to methods, results, and interpretation — separating the work of thinking from the work of phrasing.

Most strong empirical papers have a two-part narrative arc. One part is too thin. Three or more parts is a monograph. Common two-part schemes: Experiment 1 → Experiment 2; Simple model → Complicated model; Experiment → Model to explain experiment; Observational study → Intervention.

### Know when to start writing

The manuscript itself is best begun with a clean slate. Starting too early risks reinforcing preliminary interpretations, creating cognitive inertia, and diverting attention from discovery toward justification. Treat the manuscript as a retrospective on completed research, not a running log of it.

### AI at Chapter 1

You have an observation, a hunch, or a domain. You do not yet have a hypothesis. This is the one phase where AI should be used for interrogation, not generation.

**What to do:** Describe your observation to AI and ask it to help you pressure-test whether it is testable. Ask: "What would I need to measure to confirm or disconfirm this?" Ask it to generate three competing hypotheses that could explain the same observation — then decide which one is yours and why.

**What not to do:** Ask AI to generate your hypothesis. It will produce something plausible. It will have no relationship to what your data can actually support or what gap genuinely exists in your specific context.

**Research leads:** AI is useful here as a first-pass scout. Describe your topic and ask for key researchers, foundational papers, competing theoretical frameworks, and adjacent fields you might be missing. Treat everything it gives you as a lead to verify, not a citation to use. Expect hallucinated titles and misattributed findings. Go to Google Scholar, Semantic Scholar, or your library database to confirm everything before it enters your notes.

---

## Chapter 2 — Foundation

### Step 1: Lock the research question and hypothesis

A hypothesis must name a mechanism or predict a direction. "More research is needed on X" is not a hypothesis — it is a gap statement. A gap statement is the *reason* for the hypothesis, not the hypothesis itself.

Ask: Is my research question specific, answerable, and tied to a testable hypothesis? If the answer is no, do not move forward. Outline nothing until this is solid.

### Step 2: Evaluate your sources before you build on them

Sources are not equally credible, but credibility is not just about prestige. Ask for each one: Is this replicable? Is this sample generalizable? Are effect sizes reported, or just p-values? Does the methodology support the causal language used?

A literature review that uncritically accepts overclaimed prior work inherits those overclaims.

### AI at Chapter 2

**Study design:** You have a hypothesis. Now you need a design. AI can generate candidate study designs for a given research question and lay out their tradeoffs — RCT vs. quasi-experiment vs. observational, between-subjects vs. within-subjects, which confounds each design controls for and which it does not. You still choose the design; AI gives you the option space and the tradeoffs. Ask it: "What are the three most likely ways this design fails to test this hypothesis?"

**Statistical planning:** Tell AI your design and ask what statistical tests are appropriate, what assumptions those tests carry, what sample size you need for adequate power, and what you should do if the data violates normality. This is not a substitute for knowing your own stats, but it is a fast way to check your plan and catch mismatches before you collect data.

**Source evaluation:** Paste an abstract or methods section and ask AI to identify methodological red flags — missing control groups, underpowered samples, p-hacking indicators, causal language in correlational designs. Verify against the actual paper. AI summaries miss details; AI critique of methods is often sharper.

---

## Chapter 3 — The Scientific Method: Assertions and How to Test Them

Before you can design a study, run a statistical test, or write a Discussion section, you need to know what kind of claim you are making. Not all claims are the same. Some are testable. Some are not. Some look testable but are structured in ways that make them immune to disconfirmation. Getting the assertion right before the study begins is not a formality — it determines whether the paper you write afterward is a contribution to knowledge or a sophisticated-looking exercise in circular reasoning.

This chapter is about assertions: what they are, what types exist, which types science can actually test, and what the scientific method does to an assertion to generate knowledge from it.

---

### What an assertion is

An assertion is a claim that has a truth value — a claim that is either true or false, even if we do not currently know which. "The intervention improved retention" is an assertion. "Please improve the intervention" is not — it is a directive. "Would the intervention improve retention?" is not — it is a question. "The intervention is promising" is borderline — it could be an assertion ("this is worth testing") or a performance of enthusiasm that carries no falsifiable content.

A scientific paper is a structured argument for an assertion. The assertion is the paper's intellectual center. Everything else — the literature review, the methods, the results, the discussion — exists in service of the assertion. If the assertion is not clearly stated, specific enough to test, and of the type that evidence can bear on, the paper cannot succeed at its core task regardless of how well the other parts are executed.

The first question to ask of any paper you are writing or reading: what is the assertion? State it in one sentence. If you cannot, the paper does not yet have one.

---

### The taxonomy of assertions

Assertions are not all the same kind of thing. The type of assertion determines what kind of evidence can support or undermine it, what design could test it, and what it would mean to be wrong about it.

**Descriptive assertions** report what is or what was. "Students who received the intervention scored higher than students who did not." "The species was present in the region prior to 1950." "User engagement dropped 34% in the three weeks following the interface change." These are empirical claims about states of affairs. They are testable by observation and measurement. They can be wrong because the observation was conducted poorly, the measurement was invalid, or the sample was unrepresentative.

**Causal assertions** claim that one thing produces another. "The intervention caused the improvement in scores." "Deforestation caused the local extinction." "The interface change caused the drop in engagement." These are stronger claims than descriptive assertions. They require not just that two things co-occurred but that the co-occurrence was not coincidental — that one thing made the other happen. Establishing a causal claim requires ruling out alternative explanations: confounds, selection effects, reverse causation, common causes. A correlational study, no matter how large, does not establish causation. Causal claims require experimental designs that manipulate the proposed cause and hold everything else constant, or quasi-experimental methods that approximate this under conditions where full experiment is not possible.

**Correlational assertions** claim that two things tend to co-occur or move together, without claiming that either causes the other. "Higher income is associated with better health outcomes." "Students with higher prior knowledge scores tend to perform better on the post-test." These are weaker claims than causal assertions but are often what the evidence actually supports. One of the most common failures in research writing is using causal language when the design only supports correlational assertions.

**Predictive assertions** claim that knowledge of one thing allows you to anticipate another. "Given these ten features, the model will correctly classify patients as high- or low-risk with 89% accuracy on held-out data." Predictive assertions do not require a causal mechanism — they require that the pattern holds in the new context. This distinction matters: a model can predict accurately without anyone understanding why, and a model can be built on a correct causal understanding and still predict poorly.

**Mechanistic assertions** claim to explain how or why a relationship holds. "The intervention improves retention because it requires students to retrieve rather than re-read, which strengthens long-term memory traces." Mechanistic assertions are more explanatory than predictive ones. They are also harder to test directly — you need to measure the proposed mechanism (retrieval effort) as well as the outcome (retention), and show that the mechanism mediates the relationship.

**Normative assertions** claim what should be, what is good, or what ought to happen. "Educational technology companies should report intention-to-treat effect sizes rather than per-protocol effect sizes." "Researchers have an obligation to pre-register their hypotheses." These are not empirical claims — no observation can make them true or false, because they are claims about value and obligation rather than about how the world is. Science cannot resolve normative disputes directly. It can, however, provide empirical input that is highly relevant to normative questions: if you believe educational equity matters, the finding that a particular tool benefits only the 5% who engage intensively is empirically relevant to the normative question of whether to deploy it at scale.

**Definitional and conceptual assertions** claim what a term means or how a concept should be understood. "Learning, properly understood, requires durable retention rather than immediate performance." "Statistical significance is not the same as practical significance." These can be argued — better and worse definitions can be distinguished on grounds of clarity, coherence, productivity, and fit with established use — but they cannot be tested against data in the way empirical assertions can. Conceptual work is real and important work; it is just different work.

---

### The crucial distinction: falsifiable vs. unfalsifiable assertions

Karl Popper's contribution to the philosophy of science is the concept of falsifiability as the criterion that separates scientific assertions from non-scientific ones. A scientific assertion must, in principle, be capable of being shown false by some possible observation. If no possible observation could count as evidence against a claim, the claim is not making an empirical move — it is either a tautology (true by definition) or a claim about values or metaphysics that evidence cannot bear on.

This is not a criterion for meaningfulness in general. Normative assertions, definitional assertions, and metaphysical claims can be meaningful and important without being falsifiable. The point is that only falsifiable assertions are the kind that the scientific method can test.

**Unfalsifiable in practice vs. unfalsifiable in principle.** A claim can be falsifiable in principle but protected from falsification in practice by the way it is formulated. "Our intervention improves learning for students who engage with it at sufficient dosage" is technically falsifiable but structured to be very hard to falsify: any null result can be attributed to insufficient dosage. This is not scientific dishonesty — it may be a genuine claim about implementation fidelity. But it is also a claim structured to absorb negative evidence without modification. Notice the difference from: "Our intervention improves retention on a delayed unassisted test for students with access to it, measured by intention-to-treat analysis." The second version can fail clearly.

The Cartesian move (Chapter 4: what would make this wrong?) is the operational form of Popper's criterion. Before you write a hypothesis, ask: what would I have to observe to conclude this hypothesis is false? If the answer is "nothing — any result can be explained," the hypothesis is not doing scientific work. Rewrite it until it can fail.

**The asymmetry of evidence.** Popper's second key insight is that confirming instances are cheap and falsifying instances are decisive. One white swan does not confirm "all swans are white" because the next one might not be. One black swan refutes it. The asymmetry is permanent: a hypothesis can accumulate support without being proven, but a single well-documented counterexample under the specified conditions defeats it.

This is why the scientific method has the shape it does. It does not seek confirmation — it seeks to survive falsification. A hypothesis that has survived many rigorous attempts to falsify it is better supported than a hypothesis that has been confirmed many times without facing serious tests.

---

### The scientific method as a procedure

The scientific method is not a slogan. It is a specific sequence of operations designed to generate claims that are more likely to be true than the claims we started with. The sequence:

**Observation.** Something in the world draws your attention. A pattern that seems surprising, an anomaly in prior data, a claim in the literature that does not quite hold together, a practical problem that does not have a satisfying answer. The observation is the starting point. It is not yet a hypothesis — it is the prompting condition for one.

**Hypothesis formation.** You generate a specific, falsifiable claim that, if true, would explain the observation. The hypothesis must name a mechanism or predict a direction — not just say "there is some relationship between X and Y." It must be stated with enough specificity that you can design a test that could defeat it.

**Prediction.** From the hypothesis, you derive what you would expect to observe if the hypothesis were true. The prediction must be specified in advance of data collection — this is what distinguishes a prediction from a post-hoc explanation. "If students who receive Socratic prompting retain more than students who receive direct answers, then on a two-week delayed unassisted test, the Socratic group will score significantly higher." The prediction bridges the hypothesis (abstract) and the test (concrete).

**Test design.** You design a study that could falsify the prediction. The key question is not "can this study confirm the prediction?" — confirmation is easy. The key question is: "if the prediction is wrong, would this study detect that?" The design must include a comparison condition, specify the outcome measure, identify the population, and control for the main alternative explanations.

**Data collection.** The test runs. Data is collected. The question of data quality — whether what was collected actually measures what the prediction requires — is the subject of subsequent chapters. For now: the data must be collected according to the pre-specified plan, and any deviations must be reported.

**Analysis and interpretation.** The data are analyzed. The question is whether the results are consistent or inconsistent with the prediction, and how confident you should be about that judgment. Statistics is the language in which this judgment is expressed. A significant result is not proof — it is evidence of a specified strength under specified conditions.

**Communication.** The finding is communicated in a form that allows others to evaluate the evidence, attempt replication, and build on or contradict the finding. This is where the research paper enters. The paper is not a record of the research process — it is an argument for a claim, structured to allow evaluation of the evidence.

The cycle restarts. The finding, if confirmed, becomes a datum that the next hypothesis must be consistent with. If disconfirmed, it becomes a constraint that eliminates a class of hypotheses.

---

### The null and alternative hypothesis

The statistical apparatus of hypothesis testing formalizes the scientific method's logic into a specific structure. Every statistical test is built around a pair of competing assertions:

**The null hypothesis (H₀)** is the default position — typically, that there is no effect, no relationship, no difference, or that any observed pattern is attributable to chance. The null hypothesis is what you would believe in the absence of evidence for the alternative. It is not "no truth" — it is a specific baseline claim, usually the claim that the interesting thing you observed did not really happen.

**The alternative hypothesis (H₁ or Hₐ)** is the claim you are testing — typically, that there is an effect, a relationship, or a difference that is not attributable to chance alone. The alternative hypothesis is what you believe the data would show if your prediction is correct.

The logic of statistical testing is: if the null hypothesis were true, how likely would data this extreme (or more extreme) be? If the answer is "very unlikely" (typically, less than 5% of the time — the p = .05 threshold), you reject the null hypothesis in favor of the alternative. If the data are not that unlikely under the null, you fail to reject it.

Notice what this logic does and does not do. It does not prove the alternative hypothesis. It says: the null is probably not the right explanation for this data. That is weaker and more honest than "our hypothesis is confirmed." It also does not prove the null when you fail to reject it. Failing to reject the null means: we did not find convincing evidence against the null, which could mean the null is true, or it could mean our study was not powerful enough to detect the effect, or our measurement was too noisy, or we tested the wrong thing.

---

### Matching assertion type to design

The type of assertion you are making determines the study design you need. This mapping is not discretionary — it is a logical requirement.

| Assertion type | Required design | What weaker designs produce |
|---|---|---|
| Causal | Randomized controlled experiment (or strong quasi-experiment with adequate controls) | Evidence of association, not causation |
| Correlational | Observational study with appropriate controls | Correlation, possibly confounded |
| Predictive | Train/test split, held-out validation, prospective evaluation | In-sample accuracy, possibly overfitted |
| Mechanistic | Mediation analysis, manipulation check, process measure | Black-box input-output, mechanism hypothesized but unverified |
| Descriptive | Representative sample, reliable measures | Estimate of limited generalizability |
| Normative | Philosophical argument, stakeholder engagement, ethical analysis | Cannot be established by data alone |

The most common mismatch: a correlational design used to argue a causal assertion. This failure occurs at the assertion-formation stage, before a single participant is recruited. If you write a causal hypothesis but have a correlational design, you will produce data that does not test what you claimed to test. The solution is not to find a statistical method that bridges the gap — it is to either redesign the study or rewrite the assertion.

---

### Constructing a testable assertion from a vague observation

Most research starts not with a hypothesis but with a sense that something is interesting, a pattern in preliminary data, a tension between two prior findings, or a practical problem that lacks a principled solution. The scientific method requires converting this observation into a testable assertion. This conversion is intellectual work that cannot be skipped.

The conversion has four steps:

**Step 1: Name the phenomenon.** What exactly are you observing? Be specific. Not "AI tutoring seems to help some students" but "students who receive Socratic-style AI prompting during mathematics practice sessions perform differently on subsequent unassisted tests than students who receive direct-answer AI assistance."

**Step 2: Identify the type.** Is this a descriptive, causal, correlational, predictive, or mechanistic claim? The type determines the design. If you want to claim causation, say so explicitly — and then ask whether you can actually design a study that tests it.

**Step 3: Apply the Cartesian test.** What would have to be true for this assertion to be false? Specify at least three conditions under which the assertion would not hold. If you cannot identify any such conditions, the assertion is not falsifiable and is not a scientific hypothesis.

**Step 4: State the null.** What is the default position the assertion competes against? Writing the null hypothesis makes the assertion's content concrete: what, specifically, does your claim add beyond the null?

---

### The four moves as scientific method applied

The Computational Skepticism framework — Cartesian doubt, the Humean limit, Popperian falsifiability, and Plato's Cave — maps directly onto the scientific method's logic, translated into tools for evaluating AI claims and empirical claims alike.

**Cartesian doubt** is the assertion-formation move. Before accepting any claim — including your own — ask what would have to be true for it to be wrong. This is not cynicism. It is the procedure by which unexamined assumptions become explicit and testable. In a research context: apply it to your hypothesis before you collect data.

**The Humean limit** is the generalization move. Evidence from a past sample does not logically guarantee what will happen in the next case. The model trained on historical data, the effect established in one population, the finding replicated in one lab — none of these are guaranteed to hold in the next context. Confidence accumulated from observation is a fact about the procedure, not about the world. In a research context: apply it when you describe who your findings generalize to.

**Popperian falsifiability** is the hypothesis-evaluation move. An assertion that no observation could refute is not making a scientific claim. In practice: specify the metric, the threshold, and the measurement window for any claim you make. "The intervention works" is compatible with any outcome. "The intervention produces a 0.20 sigma or larger effect on an independent standardized assessment at six-month follow-up" is falsifiable.

**Plato's Cave** is the measurement move. The data is not the world. The score is not the student. The metric is not the construct. Every measurement is a shadow cast by a procedure — reliable to the degree that the procedure tracks the thing it is supposed to track. In a research context: apply it when choosing outcome measures (Chapter 4).

---

### Common errors at the assertion stage

Most of these errors are invisible once you are inside the study. They must be caught at the hypothesis-formation stage, before any data is collected.

*The underdefined hypothesis.* "Technology X will improve learning outcomes for students." What outcomes? Which students? Improve over what baseline? At what timescale? An underdefined hypothesis cannot be tested because any result is compatible with it.

*Causal language on a correlational design.* Writing "will cause" or "produces" when the study will be observational. The language commits you to a claim the design cannot support.

*The question masquerading as a hypothesis.* "This study will explore whether X affects Y." A statement of intent to investigate is not a hypothesis. State what you expect to find and why.

*The normative hypothesis disguised as an empirical one.* "Students should engage with AI tutoring because it improves outcomes." The first part is normative (should); the second part is empirical (improves outcomes) but serves as hidden justification for the normative claim. Keep them separate.

*The unfalsifiable qualifier.* "The intervention improves outcomes for students who engage with it appropriately." What counts as appropriate engagement? If this is defined after the fact to exclude non-responders, the hypothesis has been written to absorb any null result.

*The construct-measure conflation.* "We will measure learning by scoring students on the post-test." Scoring students on the post-test is not the same as measuring learning — it is measuring post-test performance. Chapter 4 addresses this in depth. At the assertion stage: name the construct you care about and separately name the measure you will use. They are different things and the difference matters.

---

### AI at Chapter 3

**Assertion typing:** Paste your hypothesis and ask: "What type of assertion is this — descriptive, causal, correlational, predictive, mechanistic, or normative? Is this type consistent with the study design I have described?" It is reliable at identifying the mismatch between causal language and correlational designs, and at flagging normative claims embedded in empirical framing.

**Cartesian test:** Paste your hypothesis and ask: "List five conditions under which this hypothesis would be false. Include at least one that challenges the validity of the outcome measure, one that challenges the representativeness of the sample, and one that would reverse the direction of the effect." Use the list as a pre-registration checklist: if your design is not protected against at least three of these, revise the design.

**Null hypothesis formulation:** Describe your hypothesis and ask: "State the null hypothesis this competes against. Make it specific: what exactly would the data show if the intervention had no effect?" A vague null reveals a vague hypothesis.

**Falsifiability check:** Paste your hypothesis and ask: "Can this hypothesis be falsified? What specific observation would prove it wrong? If I run the study and get a null result, does this hypothesis have a built-in explanation for why the null result does not count?" Any hypothesis that can explain away its own disconfirmation is not falsifiable in practice — revise it.

**Prediction generation:** Paste your hypothesis and ask: "Derive three specific, advance predictions from this hypothesis — statements of what you would observe if the hypothesis is true, stated in measurable terms." Compare these predictions to what your study is actually measuring. If the study measures something different from what the predictions require, you are not testing the hypothesis.

---

## Chapter 4 — What Does Causal Mean, Exactly? *(placeholder)*

> **Status: placeholder — to be drafted**
>
> **Placement rationale:** Chapter 3 introduces causal assertions as a distinct type and flags them as requiring stronger designs than correlational claims. This chapter delivers what Chapter 3 owes: a rigorous treatment of what causation actually means, how causal claims are established, and why the distinction matters practically.
>
> **Core concepts (planned):**
> - The counterfactual theory of causation — X caused Y if, had X not occurred, Y would not have occurred. Why this is the right frame and why correlation doesn't satisfy it.
> - Judea Pearl's causal hierarchy: Association (seeing) → Intervention (doing) → Counterfactual (imagining). What questions each rung can and cannot answer. Why most educational and medical research lives on rung one and claims rung three.
> - Directed Acyclic Graphs (DAGs) — how to draw the causal structure you are assuming and why making it explicit changes what you can claim. Confounders, mediators, colliders, and why adjusting for the wrong variable makes things worse.
> - The three strategies for approaching causation when you cannot randomize: natural experiments, instrumental variables, difference-in-differences, regression discontinuity. What each buys and what it costs.
> - Why "correlation is not causation" is true but insufficient — the real question is what additional assumptions and designs would be needed to establish the causal claim, and whether those are available.
> - The causal language audit: a practical tool for identifying every causal verb in a draft (causes, leads to, produces, drives, explains, results in) and asking whether the design licenses each one.
>
> **Key sources:** Pearl & Mackenzie *The Book of Why* (2018); Hernán & Robins *Causal Inference: What If* (2020, free online); Angrist & Pischke *Mostly Harmless Econometrics* (2009); Rubin potential outcomes framework.
>
> **Connection to running project:** After this chapter, students return to their hypothesis from Chapter 3 and re-examine the assertion type. If the hypothesis is causal, does the design support it? If not, does the hypothesis need to be rewritten as correlational, or does the design need to be strengthened?

### AI at Chapter 4 *(placeholder)*

> To be written when chapter is drafted. Planned tasks: DAG construction from a verbal research description; causal language audit on a draft Methods or Discussion section; identification of confounders given a specified research design; translation between correlational and causal hypothesis formulations.

---

## Chapter 5 — Measurement

This chapter deserves its own treatment because measurement is where most research papers — and most entire research fields — go wrong without knowing it. Getting your measurement right is not a statistical question. It is a conceptual one: *what exactly are you claiming to observe, and does your instrument actually observe it?*

---

### The hierarchy: hypothesis → design → data → interpretation

The order is fixed. A flaw at any level corrupts everything downstream.

**Hypothesis — Is the claim specific and testable?**

A hypothesis names a mechanism or predicts a direction. It makes a claim that evidence could falsify. The more precisely it is stated, the more honest the test.

Weak: *Students who use AI tutoring will learn more.*
Stronger: *Students who use AI tutoring with Socratic prompting (hints, no direct answers) will retain more on an unassisted test two weeks later than students who use AI tutoring with direct-answer responses.*

The second version specifies the mechanism (Socratic vs. direct-answer), the outcome (retention), the measure (unassisted test), and the timescale (two weeks). It can fail. The first version cannot meaningfully fail — any positive result will confirm it, and any null result will be attributed to implementation.

**Design — Can the method actually answer the question?**

Your design determines which confounds you can rule out. An experiment that assigns students to conditions by classroom, then treats the classroom as the unit of analysis, will produce inflated estimates — students in the same classroom are not independent observations. A longitudinal study without a control group cannot attribute change to the intervention. An observational study of enthusiastic platform users cannot separate the platform's effect from the motivation that produced the enthusiasm.

The central design question is: *if my hypothesis is wrong, would my study be able to detect that?* A design that would confirm the hypothesis regardless of whether the hypothesis is true is not a test. It is theater.

**Data/evidence — Does the instrument measure the construct, or something adjacent to it?**

This is the subtlest and most important question in measurement. The construct is what you are claiming to measure. The instrument is what you actually measure. The gap between them is where most measurement error lives — and most researchers never examine it explicitly.

A researcher studying whether AI tutoring improves *learning* collects post-test scores. The scores are real. The question is whether post-test scores measure learning in the sense the researcher means: durable understanding that transfers to new problems, persists over time, and reflects genuine conceptual change. They might. They might measure something narrower: performance on familiar item types, in a familiar testing context, immediately after the intervention, on content specifically aligned with what the intervention taught. Both are real things. They are not the same thing. The researcher's claim licenses different conclusions depending on which one the instrument actually indexes.

This gap is not exotic or rare. It is the ordinary condition of empirical research. Robert Bjork's distinction between *storage strength* and *retrieval strength* names precisely this problem: conditions that produce high immediate performance often produce low long-term retention, because they boost retrieval without building the durable storage that supports later recall. An outcome measure administered immediately after an intervention captures retrieval strength. Whether it also captures storage strength is a separate question requiring delayed measurement.

**Interpretation — Do the conclusions match the evidence?**

After data collection, researchers must move from "what I observed" to "what this means." This is the step most prone to inflation. A finding that students in the AI-tutoring condition scored higher on the immediate post-test becomes "AI tutoring improves learning" in the Discussion — a claim that licenses more than the measurement supports.

The rule is simple: your conclusions should be as specific as your measurement was. If you measured performance on aligned items at immediate timescale in a selective population, your conclusion should say that. If you want to say something broader, you need a broader measurement.

---

### The measure-construct gap

Every number in a research paper is a measurement. Every measurement is a proxy for a construct. The construct is the thing you actually care about — *learning*, *understanding*, *engagement*, *mastery*, *effectiveness*. The measurement is what you can actually observe — test scores, time-on-task, click patterns, completion rates, standardized assessment results.

The gap between measurement and construct is the central analytical problem in empirical research. It is not solvable; it can only be managed honestly.

**What good management looks like:**
- State explicitly which construct you are claiming to measure
- Describe how your instrument indexes that construct
- Acknowledge where the instrument might diverge from the construct
- Scope your conclusions to what your measurement actually supports

**What poor management looks like:**
- Using measurement vocabulary ("we found," "data shows") when construct vocabulary ("students understand," "the intervention improves learning") is what the claim actually requires
- Selecting an outcome measure because it is available or convenient, then writing conclusions as if it were the gold standard
- Treating a correlated proxy as though it were the construct itself

A concrete example. A researcher studying whether students *understand* fraction division gives a post-test of fifteen fraction-division problems. The scores measure performance on these specific problems, in this specific format, on this specific day. Whether the scores index *understanding* — the capacity to reason about fractions flexibly, to recognize fraction-division situations in new contexts, to explain why the invert-and-multiply procedure works — depends on whether the test was designed to detect those capacities. A test of procedural fluency and a test of conceptual understanding can look identical on the surface. Their scores are measuring different things.

---

### Five questions to ask of any measurement

These questions apply to your own research and to every study you cite. Getting fluent with them is the difference between a researcher who can defend their methodology and one who cannot.

**1. What was actually measured, and was it aligned to the intervention?**

When an intervention is designed to teach specific skills and is evaluated on a test of those same skills, the intervention and the outcome measure are *aligned*. Aligned assessments reliably produce larger effect sizes than independent assessments of the same intervention, because the test and the intervention share content, format, and context. This is not necessarily dishonest — it is legitimate to measure whether students learned what was taught. It does constrain your claims. A high effect size on an aligned measure is evidence about performance on that specific aligned content. It is not automatically evidence about generalized learning, transfer, or durable understanding.

The question is not whether your measure is aligned. The question is whether you are making claims that exceed what an aligned measure supports.

**2. What was the baseline, and is the comparison what it appears to be?**

Every effect size is a difference. A result of 0.30 standard deviations does not mean "students learned 0.30 SD worth of material." It means students in the treatment condition scored 0.30 SD higher than students in the comparison condition. The comparison condition determines what that 0.30 is an effect *against*. Students compared against no instruction, students compared against conventional instruction, students compared against an alternative intervention at the same cost — these produce different interpretations of the same number.

Check: could the baseline be artificially weak? Comparing your intervention against a minimal control (no instruction, waitlist, business-as-usual in a low-resource setting) will produce a larger effect size than comparing it against an active control (the best available alternative at comparable cost). Both are valid research designs. They answer different questions. Be clear which question yours is answering.

**3. What population is this a finding about?**

Your sample is your sample. It is not the population your claims implicitly invoke. A study of motivated volunteers who sought out the intervention is not a study of all students who would receive the intervention if it were mandated. A study of Harvard undergraduates is not a study of secondary-school students in under-resourced settings. A study of students who completed the platform at the recommended level is not a study of all students provided access to the platform.

The most common version of this problem: *intention-to-treat* versus *per-protocol* analysis. If 95% of your sample did not use the intervention as intended, the effect size on the 5% who did is not a finding about your intervention's impact on the full sample. Report both. Do not present the per-protocol finding as though it were the intention-to-treat finding.

**4. What timescale, and what kind of claim does it support?**

A post-test administered immediately after the intervention measures performance when the material is maximally fresh. Bjork's distinction is decisive here: retrieval strength (how easily the material comes to mind now) and storage strength (how durably it is encoded in long-term memory) dissociate. Conditions that boost short-term retrieval often fail to build durable storage. The classic finding: massed practice (studying everything at once) produces higher immediate post-test performance than spaced practice (studying distributed over time), but spaced practice produces much higher delayed retention. If you only measure immediately, you may be measuring the wrong thing.

A claim about *learning* requires a delayed measure. A claim about *retention* requires a delayed measure. A claim about *transfer* requires a measure on material the student did not practice. An immediate aligned post-test supports a claim about immediate performance on familiar content. That claim has value. It is not the same as a claim about learning.

**5. What would a null result have looked like, and would your design have detected it?**

This question reveals whether your study can actually test your hypothesis. A study designed such that any plausible outcome confirms the hypothesis is not a study; it is a procedure for generating confirmatory-looking numbers. The population of students who engage intensively with a learning platform are not a random sample of students with platform access — they are self-selected by motivation, available time, and home environment. Comparing them to low-engagement students produces a finding that conflates the platform's effect with the preexisting differences between these groups. A null result (no effect of the platform) would be invisible because the motivated-vs-unmotivated confound would produce a positive result regardless.

Before collecting data: if your hypothesis is false, what would your data look like? If the answer is "about the same as if it were true," reconsider the design.

---

### Reading measurement claims in prior work

You will build your paper on prior findings. The measurement problems above are endemic to the literature you will be citing. You inherit the overclaims of every paper you cite without examining. A literature review that treats a high effect size on an aligned immediate post-test as equivalent to a finding about durable generalized learning is not a careful literature review; it is a literature review that has borrowed the measurement error of the original study.

Before citing a finding, ask:
- Was the outcome measure aligned to the intervention?
- Was the baseline comparison the comparison it appears to be?
- Was the sample representative of the population the claim invokes?
- Was there a delayed measure, or only an immediate post-test?
- Is the causal language in the claim licensed by the design (experimental) or assumed (observational)?

A finding that survives all five questions is one you can cite without qualification. A finding that fails one or more of them can still be cited — but with the appropriate qualification stated explicitly. "Prior work suggests X, though this finding relied on an aligned researcher-designed assessment at immediate timescale, so durability remains uncertain."

This is what it means to build on the literature rather than to inherit its errors.

### AI at Chapter 5

**Construct clarification:** Describe your outcome measure to AI and ask: "What construct is this instrument measuring? What constructs does it fail to capture that a researcher claiming to study [your claim] should care about?" It will identify the gap between what you are measuring and what you might be claiming to measure more reliably than most researchers examine on their own.

**Measure-construct audit:** Paste your Methods section and your Discussion and ask: "Does the Discussion make any claims that go beyond what the outcome measure described in the Methods can support?" It is reliable at catching claims about generalized learning, long-term retention, or transfer when the measure was an immediate aligned post-test.

**Baseline comparison check:** Describe your study design and comparison condition and ask: "What confounds could explain a positive result in this comparison that would not be attributable to the intervention?" The list it generates is your threat-to-validity checklist.

**Population scope check:** Paste your sampling description and your Discussion and ask: "Does the Discussion generalize to any population larger than the sample described in the Methods?" Any overgeneralization it identifies is a qualification to add.

**Timescale audit:** Paste your outcome measure description and ask: "Is this measure capturing retrieval strength (immediate performance) or storage strength (durable retention)? What would a delayed measure need to look like to address the durability question?" Use the output to decide whether to add a follow-up assessment or qualify your retention claims appropriately.

---

## Chapter 6 — GIGO: Garbage In, Garbage Out

Sophisticated analysis applied to bad data does not produce good results. It produces confident-looking bad results, which are worse than obviously bad results because they travel further.

GIGO is the measurement principle the five questions above cannot catch, because those questions ask about what you are measuring and how. GIGO asks about the quality of the raw material before any analysis begins. A study can have an appropriate construct, a well-matched instrument, an honest baseline, a representative population, and a sensible timescale — and still produce garbage, if the data itself is corrupted, biased, or incomplete in ways the analysis never surfaces.

**What garbage looks like before it enters the analysis:**

*Measurement error in the instrument.* A survey that all participants interpret differently is not measuring the same thing in all participants. A test with ambiguous items produces scores that mix the construct with item-confusion. A sensor that drifts over time produces readings that are time-contaminated as well as construct-contaminated. Before analysis, check whether your instrument performs consistently: do independent coders agree (inter-rater reliability)? Do multiple items meant to measure the same construct correlate with each other (internal consistency)? Does the instrument produce stable results when the underlying construct hasn't changed (test-retest reliability)?

*Systematic bias in data collection.* If the researcher knows which condition each participant is in and is also the person scoring the outcome, the scores are at risk of experimenter bias — not dishonesty, but the ordinary human tendency to perceive ambiguous evidence in a direction that confirms expectations. Pre-specify your scoring criteria, blind the scorer to condition whenever possible, and use validated instruments rather than ad hoc measures. Social desirability bias in self-report data is another systematic contaminant: participants report what they think they should report rather than what is true. Whenever the construct involves something evaluative — attitudes, effort, honesty, learning — self-report data requires particular skepticism.

*Missing data that isn't missing at random.* Missing data is almost never a random sample of all possible data. Students who drop out of a study are not a random subset of students who enrolled. Participants who skip survey items are not randomly distributed across the sample. When the students most likely to be harmed by an intervention are also the most likely to leave the study before the outcome is measured, the remaining sample produces an inflated estimate of the intervention's effectiveness. This is not a statistical problem; it is a design problem. The fix is not imputation — it is understanding why data is missing and what that mechanism implies for who remains in your analysis.

*Outliers handled inconsistently.* Every analysis involves decisions about outliers: data points so far from the rest that they distort summary statistics. The problem is not that outliers exist — they always do. The problem is making outlier decisions after seeing the results. If you remove outliers that hurt your p-value and retain outliers that help it, you have introduced a bias that your methods section — which will describe outlier handling in general terms — will not reveal. Pre-register your outlier criteria before looking at the data. State them explicitly in the Methods: "Participants scoring more than three standard deviations from the group mean on the pretest were excluded." Then apply that rule regardless of which direction it moves your finding.

*Composite scores built on shaky foundations.* Many outcomes are measured by combining multiple items into a single score: a survey scale, a total test score, a rubric-based rating. This only makes sense if the items are actually measuring the same underlying construct. If your ten-item scale is measuring three different things simultaneously, the composite score is a mixture that represents none of them clearly. Run a reliability analysis (Cronbach's alpha, or better, a confirmatory factor analysis) before using the composite. An alpha below 0.70 is a warning that your items may not be measuring what you think they are measuring. Do not assume a composite is valid because someone else used the same composite in a prior paper.

*Researcher degrees of freedom quietly expanding.* Many small decisions between data collection and final analysis — which covariates to include, whether to log-transform a variable, how to define a subgroup, which time point to treat as the primary endpoint — collectively constitute a "garden of forking paths." Each decision, reasonable on its own, can be made in the direction that makes results look better. When all these decisions accumulate, the final reported result may be the most favorable outcome of many possible analyses of the same dataset, not a neutral summary of what the data showed. The remedy is pre-registration: commit to your analysis plan before seeing the data. Even partial pre-registration — committing to your primary outcome measure, your comparison conditions, and your main statistical test — substantially constrains the forking paths.

**The GIGO check before analysis:**

Walk through your dataset before running any statistical test and ask:

Is there any systematic pattern in which observations are missing, and what does that pattern imply about who is represented in my analysis?

Are there values that are implausible given what the measure is — test scores above the maximum, negative response times, survey responses that are all the same value? What do they indicate, and what is my pre-specified rule for handling them?

If I am combining items into a composite, do those items actually cohere empirically, not just conceptually?

Does my data file match my intended design? Do I have the sample size, the group assignments, and the variable names I think I have?

None of these checks are exotic. They are the difference between an analysis that reports what the data contains and an analysis that reports what the data collection, processing, and decisions together produced.

The five questions in the previous section ask whether your measurement design is sound. The GIGO check asks whether your data, as it actually exists, is fit for that measurement design. Both are required. Clean data analyzed with the wrong construct is garbage. Valid construct, valid design, corrupted data — also garbage. Sophisticated statistics applied to either: garbage with confidence intervals.

---

### AI at Chapter 6

**Data quality audit:** Paste a description of your dataset — variable names, data types, collection method, sample size — and ask: "What data quality problems should I check for before analysis? What patterns of missingness, measurement error, or systematic bias are most likely given this collection method?" Use the list as a pre-analysis checklist.

**Missing data diagnosis:** Describe your missingness pattern to AI — how many missing values, which variables, what the likely reason — and ask: "Is this pattern consistent with MCAR, MAR, or MNAR? What does each mechanism imply about the validity of my analysis if I proceed without addressing it?" The classification matters because the appropriate remedy differs for each.

**Outlier pre-specification:** Before you look at your results, paste your analysis plan and ask: "Write me an explicit outlier rule for this dataset that I can pre-register. What are the standard criteria for [your analysis type] and what should I specify?" Committing to outlier rules before seeing the data prevents the quiet bias of post-hoc exclusion.

**Reliability check code:** Give AI your scale or instrument items and ask it to write code (R or Python) to compute Cronbach's alpha, item-total correlations, and a parallel analysis for dimensionality. Run the reliability check before you trust any composite score.

**Consistency cross-check:** Describe your study design and ask: "Given this design, what inconsistencies or logical impossibilities should I check for in the raw data?" Examples include test scores outside the possible range, response times below human minimums, or condition assignments that violate the randomization protocol.

---

## Chapter 7 — Statistics

Statistics is the language in which empirical claims are made and contested. A paper that misuses statistics does not just produce wrong numbers — it makes claims the evidence cannot support and contributes to a literature that subsequent researchers build on in good faith.

This chapter is an overview. Each topic here is a book. The goal is to give you the vocabulary to recognize what you need, know when you need help, and read statistical claims in prior work with appropriate skepticism.

---

### What statistics actually does

Statistics does not tell you whether something is true. It tells you how surprising your data would be if a specified null hypothesis were true. That is a narrower and stranger claim than most researchers treat it as.

A p-value of 0.04 means: if the null hypothesis were true (typically, if there were no effect), you would see data this extreme or more extreme about 4% of the time. It does not mean the probability that the null hypothesis is true is 4%. It does not mean the effect is real, important, or replicable. It does not mean the study was conducted well. It means the observed data would be unlikely under a specific baseline assumption.

This distinction matters because the entire enterprise of statistical significance testing has been widely misinterpreted — in published papers, in textbooks, and in media coverage of research — for decades. The misinterpretation produces overclaiming. Knowing what the numbers actually say is the prerequisite to writing about them honestly.

---

### The four things every result needs

A complete statistical result contains four elements. Any result that omits one is incomplete and forces the reader to guess at what was found.

**The test statistic.** The number produced by the statistical test — t, F, χ², z, or whatever is appropriate for the design. This tells the reader the raw signal in the data.

**Degrees of freedom.** The number of independent pieces of information available to estimate the parameter. It tells the reader the size and structure of the comparison. Without it, the test statistic cannot be evaluated.

**The exact p-value.** Not "p < .05" but the actual number — p = .016, p = .43. "p < .05" hides information. A result with p = .049 and a result with p = .001 are not the same finding, and treating them identically by reporting only that both crossed the threshold erases meaningful information about the strength of the evidence.

**Effect size.** The magnitude of the difference or relationship, expressed in a standardized unit. Cohen's d for mean differences, η² or ω² for ANOVA, r for correlations, odds ratios for logistic regression. The p-value tells you whether the effect is distinguishable from noise at a given sample size. The effect size tells you how big it is. These are independent questions. A trivially small effect can be statistically significant with a large enough sample. A practically important effect can be non-significant with a small sample. Both the p-value and the effect size are required to interpret a result.

What a complete result looks like: "Students in the experimental group scored higher on the posttest (M = 74.3, SD = 8.1) than students in the control group (M = 68.7, SD = 9.4), t(62) = 2.47, p = .016, d = 0.63." Not: "Students in the experimental group performed significantly better (p < .05)."

---

### Choosing the right test

The test you use is determined by your design. Using the wrong test is not a minor reporting error — it produces wrong numbers. The most common mismatches:

**Comparing two group means — continuous outcome:** Independent-samples t-test (between-subjects) or paired t-test (within-subjects, or pretest-posttest). Assumptions: approximately normal distribution within each group, or large enough sample that the Central Limit Theorem applies; homogeneity of variance for the independent-samples version (check with Levene's test).

**Comparing more than two group means — continuous outcome:** One-way ANOVA. Use two-way ANOVA when you have two independent variables and want to test their interaction. Post-hoc tests (Tukey, Bonferroni) are required if you want to compare specific pairs after a significant F. Running multiple t-tests instead of ANOVA inflates the Type I error rate.

**Relationships between two continuous variables:** Pearson correlation (linear relationship, both variables normally distributed) or Spearman correlation (rank-based, no normality assumption). Correlation is not causation. A correlation of r = .30 shared variance is 9%. Keep that in mind when describing the "strength" of an association.

**Categorical outcomes:** Chi-square test of independence for testing whether two categorical variables are associated. Fisher's exact test when cell counts are small. Logistic regression when you want to model a binary outcome as a function of one or more predictors.

**Repeated measures or longitudinal data:** Repeated-measures ANOVA or mixed-effects models (linear mixed models in R: `lme4`; in Python: `statsmodels MixedLM`). Treating repeated observations from the same person as independent violates the independence assumption and inflates effective sample size. This is one of the most common errors in educational and psychological research.

**Predicting a continuous outcome from multiple predictors:** Multiple linear regression. Check: linearity (residual plots), independence of observations, homoscedasticity (constant variance of residuals), normality of residuals, and multicollinearity (VIF below 5–10 for each predictor).

---

### Effect sizes and what they mean

Cohen's benchmarks — small d = 0.2, medium d = 0.5, large d = 0.8 — are often quoted as though they are universal standards. They are not. Cohen derived them from his experience with psychological research in the mid-twentieth century. Whether an effect of d = 0.2 is meaningful depends entirely on what is being measured, at what cost, in which context.

A drug that reduces mortality by a small amount across an entire population may be enormously important. An educational intervention that produces d = 0.5 on an aligned researcher-designed assessment administered immediately after a single tutoring session is a much weaker finding than d = 0.5 on a standardized measure administered six months later across a heterogeneous school population.

Matthew Kraft's revised benchmarks for field-based education research — where anything above 0.20 qualifies as "large" — reflect the fact that well-implemented, scalable educational interventions rarely produce effects above 0.10–0.15 on independent measures. The lab effect and the field effect are systematically different, and treating them as interchangeable is how the efficacy literature inflates.

Report effect sizes. Report confidence intervals around them. Let the reader see the uncertainty.

---

### The multiple comparisons problem

If you run 20 statistical tests at α = .05, you expect one significant result by chance even if every null hypothesis is true. This is not a fringe concern. It is the mechanism behind a substantial portion of false positives in the published literature.

The correction depends on how the tests are related. The Bonferroni correction divides the alpha by the number of tests (α/n), which is conservative. False Discovery Rate (FDR) correction (Benjamini-Hochberg) is less conservative and appropriate when tests are correlated. Both require pre-specifying which tests you are running — applying the correction post-hoc to only the tests that approached significance is not a solution.

The deeper issue is not which correction to apply but whether you are running more tests than your hypothesis requires. If your hypothesis is about one primary outcome and you are reporting results on twelve secondary outcomes, you have a multiple comparisons problem regardless of correction. Pre-register your primary outcome and your planned comparisons before collecting data.

---

### What p-hacking is and why it happens

P-hacking is the practice of making analysis decisions — often unconsciously — in ways that push p-values below 0.05. It includes: collecting data until a test becomes significant and then stopping; trying multiple outcome measures and reporting the one that worked; running the analysis with and without covariates and reporting the version that produced the lower p-value; removing outliers after seeing the results and checking whether significance changes.

None of these practices requires intent. They are the natural result of treating p = 0.05 as a publication threshold and making reasonable-seeming analysis decisions when the results don't yet cross it. The 2011 Simmons, Nelson, and Simonsohn paper "False Positive Psychology" demonstrated that these practices, each individually defensible, can together produce p < .05 for a hypothesis that is false essentially at will.

The remedy is pre-registration: committing to your hypothesis, sample size, primary outcome, and analysis plan before data collection. Pre-registration does not prevent exploratory analysis — it separates it from confirmatory analysis so that each is read correctly. An exploratory finding reported as exploratory generates hypotheses. An exploratory finding reported as confirmatory is a false positive.

---

### HARKing

HARKing — Hypothesizing After Results are Known — is the practice of presenting post-hoc hypotheses as though they were a priori predictions. A researcher runs an exploratory analysis, finds an interesting pattern, and writes the Introduction and Hypothesis section to frame the study as though the finding was predicted in advance.

HARKing is not always conscious fraud. It emerges from the incentive structure of academic publishing, which rewards confirmatory findings and penalizes null results, combined with the cognitive difficulty of remembering what you expected before you saw the data. But the result is the same: the reader cannot distinguish genuine prediction from post-hoc rationalization, the reported finding has much weaker evidentiary value than its framing implies, and the literature accumulates findings that cannot be replicated.

If you ran the study exploratorily and found something interesting, say so. "This study was designed to explore X. We observed a relationship between Y and Z that warrants further confirmatory investigation." That is an honest and useful contribution. Dressing it as a confirmed hypothesis is not.

---

### Power and sample size

Statistical power is the probability that your study will detect a true effect of a specified size. Under-powered studies produce results that fluctuate wildly — a study with 30% power will sometimes find a significant effect and sometimes not, from samples drawn from the same population. The estimate of the effect from an under-powered significant result is also systematically inflated (the "winner's curse" — only the most extreme samples clear the significance threshold).

Determine your required sample size before data collection using a power analysis. The inputs are: the significance threshold (α, typically 0.05), the desired power (1 − β, typically 0.80 or 0.90), and the expected effect size. The expected effect size should come from prior literature on similar interventions with independent outcome measures — not from the inflated effect sizes on aligned assessments that populate much of the efficacy literature.

Use G*Power (free software), the `pwr` package in R, or `statsmodels` in Python. For multilevel designs (clustered data, repeated measures), use software designed for multilevel power analysis — the intraclass correlation (ICC) substantially affects required sample size and is ignored in most simplified power calculations.

A study that is too small to detect a plausible true effect should not be run as a confirmatory test. It can be run as pilot work, with appropriate labeling.

---

### Assumption checking

Every statistical test makes assumptions. Violating them does not automatically invalidate the result — some tests are robust to moderate violations of specific assumptions — but unchecked violations can produce meaningfully wrong conclusions.

Check these before finalizing results:

**Normality:** For t-tests and ANOVA, the assumption is normality of residuals (not necessarily of raw scores). Shapiro-Wilk test for small samples; Q-Q plots for visual inspection. With n > 30 per group, the Central Limit Theorem means mild non-normality has little practical effect.

**Homogeneity of variance:** For independent-samples t-test and ANOVA, Levene's test. If violated, use Welch's t-test (which does not assume equal variances) or Welch's ANOVA.

**Independence of observations:** This cannot be tested statistically — it must be established by design. Students in the same classroom are not independent. Repeated measurements from the same person are not independent. Failing to account for clustering inflates the effective sample size and produces false positives.

**Linearity:** For regression, plot residuals against fitted values. A pattern in the residuals indicates a non-linear relationship that a linear model will misfit.

**Multicollinearity:** For multiple regression, compute variance inflation factor (VIF) for each predictor. VIF above 5 is a warning; above 10 is a serious problem indicating that the coefficient estimates are unstable.

---

### Confidence intervals

A 95% confidence interval means: if you repeated this sampling procedure many times and computed the interval each time, 95% of those intervals would contain the true population parameter. It does not mean there is a 95% probability that the true value lies within this particular interval.

Confidence intervals communicate effect size and precision simultaneously. A narrow interval indicates a precise estimate. A wide interval indicates that the data are consistent with a wide range of true values — including, potentially, effects large enough to matter and effects too small to care about. A statistically significant result with a wide confidence interval spanning from trivially small to extremely large effects tells you that the data are consistent with significance, but does not tell you much about what the true effect is.

Always report confidence intervals alongside point estimates. When reviewing prior work, look at the width of the confidence interval, not just whether it excludes zero.

---

### Common statistical errors in published papers

These appear in peer-reviewed papers regularly enough that knowing them is part of reading the literature critically:

*Treating non-significant as "no effect."* A non-significant result does not prove the null hypothesis. It means the study lacked the power or precision to detect an effect of the size observed. "We found no significant difference" and "there is no difference" are not the same claim.

*Reporting only within-group change.* A pre-post design that shows significant improvement in the treatment group from Time 1 to Time 2 does not establish that the treatment caused the improvement without a control group. Both groups might have improved.

*Comparing p-values across studies.* A result with p = .02 is not stronger evidence than a result with p = .04. The p-values reflect different sample sizes, measurement contexts, and populations. They cannot be directly compared.

*Using SEM where SD is needed.* The standard error of the mean (SEM) is smaller than the standard deviation (SD) and is appropriate for describing the precision of a mean estimate, not the spread of the data. Error bars showing SEM look more precise than error bars showing SD. When describing data variability, use SD. When describing estimate precision, use SEM or a confidence interval — and label which you are using.

*Percent change as evidence without raw values.* "A 50% improvement" tells you nothing about whether the improvement was from 2% to 3% or from 40% to 60%. Always report the underlying values.

---

### AI at Chapter 7

**Test selection:** Describe your design — number of groups, outcome variable type, whether observations are independent, number of time points — and ask AI which statistical test is appropriate and what assumptions it carries. It is reliable on common designs. For multilevel, longitudinal, or Bayesian analyses, verify against a statistical textbook or consult a methodologist.

**Assumption checking code:** Give AI your analysis plan and ask it to write code that runs all assumption checks before the main analysis. Include: Shapiro-Wilk for normality of residuals, Levene's test for homogeneity of variance, VIF for multicollinearity if using regression, Durbin-Watson for autocorrelation in time series. Review and understand what each test is checking before running it.

**Power analysis code:** Describe your design and the effect size you expect (from prior literature using independent measures), and ask AI to write a power analysis in G*Power syntax, R (`pwr` package), or Python (`statsmodels`). Ask it to show how required sample size changes as effect size changes from small to medium to large — this makes the sensitivity visible.

**Statistical reporting check:** Paste a Results paragraph and ask: "Does every statistical claim include the test statistic, degrees of freedom, exact p-value, and effect size? Are there any claims that use only 'significant' without reporting the actual numbers?" Fix every flag.

**Multiple comparisons audit:** List all statistical tests you are running and ask: "Does this set of tests require a multiple comparisons correction? What is the appropriate correction given the structure of the comparisons?" Apply the correction your analysis plan calls for, not whatever makes the results look better.

---

## Chapter 8 — How to Design a Graph *(placeholder)*

> **Status: placeholder — to be drafted**
>
> **Placement rationale:** Chapter 7 (Statistics) teaches what the numbers mean. This chapter teaches how to show what the numbers mean. It is not a Results-section writing tip — it is a conceptual chapter on visual encoding, what different chart types actually claim, and what makes a graph honest or misleading. Poor graph design is a form of miscommunication that statistical competence does not prevent.
>
> **Core concepts (planned):**
> - What a graph is doing — visual encoding of data as position, length, angle, area, color, or shape. Why some encodings are more accurately perceived than others. Cleveland and McGill's perceptual hierarchy and what it implies for chart selection.
> - Choosing the right chart type for the claim being made — the match between what you want to show (distribution, comparison, relationship, composition, change over time) and the geometry that shows it honestly. Common mismatches: pie charts for continuous data, bar charts for correlations, line charts implying continuity that doesn't exist.
> - What makes a graph lie without misrepresenting a single number — truncated axes, dual axes with independent scales, area encodings that show diameter instead of area, smoothing that hides variance, color gradients that imply ordinal structure in nominal data.
> - Error bars and what they must say — the SD/SEM confusion as a pervasive misrepresentation. What a confidence interval around a mean actually looks like vs. what the data's spread looks like, and why conflating them misleads.
> - Visualization for exploratory analysis vs. visualization for communication. The graph you use to understand your data and the graph you use to report it can and should be different. Tufte's data-ink ratio as a principle for the communication graph.
> - Accessible visualization — color choices that work for the 8% of readers with color vision deficiency; redundant encoding (color + shape, not color alone); resolution considerations for print vs. screen.
>
> **Key sources:** Edward Tufte *The Visual Display of Quantitative Information* (1983/2001); Cairo *The Functional Art* (2012); Wilke *Fundamentals of Data Visualization* (2019, free online); Cleveland & McGill "Graphical Perception" *JASA* (1984); Healy *Data Visualization: A Practical Introduction* (2018, free online).
>
> **GIGO connection:** The GIGO book's data visualization chapter (histograms, box plots, scatter plots, heatmaps, violin plots) provides the technical catalog. This chapter provides the design principles that determine when each is appropriate and how to execute it honestly.
>
> **Connection to running project:** Students produce or redesign one figure from their draft paper applying the chapter's principles. They write a one-paragraph caption that does what Chapter 12 (Writing Well) requires: states what the figure shows, not what it is.

### AI at Chapter 8 *(placeholder)*

> To be written when chapter is drafted. Planned tasks: chart-type selection for a described finding; error-bar specification (SD vs. SEM vs. CI) given a stated claim; axis-truncation check on a described figure; caption critique against the "what it shows, not what it is" standard; color-accessibility check for a described palette.

---

## Chapter 9 — Literature Review

### Synthesize, do not summarize

A literature review organized source-by-source is a bibliography with connective tissue. A real literature review is organized by theme, debate, or gap. Each paragraph should address one idea and draw on multiple sources — not one source and multiple ideas.

What you are building toward: a gap statement. What is known? What is not? Why does your question sit in between?

### The CARS framework for your introduction

Swales's "Create a Research Space" model gives you the three moves every strong introduction makes:

Move 1 — Establish a territory: provide background on the topic and make topic generalizations. Move 2 — Establish a niche: indicate a gap, counter-claim prior work, or raise a question. Move 3 — Occupy the niche: outline the paper's purposes and describe its contribution to filling the established gap.

Establishing a research niche is often signaled by specific terminology that expresses a contrasting viewpoint, a critical evaluation of gaps in the literature, or a perceived weakness in prior research — drawing a clear distinction between deficiencies in previous studies and the research you are presenting that is intended to help resolve those deficiencies.

A weak introduction is excessively broad, vague, and lacks context. It focuses too much on the author's work rather than the field. It may overlook the research difficulty or literature gap, use too much technical jargon, or make unsupported statements.

### AI at Chapter 9

**Finding papers:** Give AI a seed paper (title, abstract, or DOI) and ask it to identify related work, citing authors, key debates, and methodological splits in the field. Cross-check everything in Semantic Scholar, Connected Papers, or Google Scholar. Use AI output as a search strategy, not a reading list.

**Organizing what you've read:** Once you have read your sources, paste your notes into AI and ask it to identify recurring themes, contradictions between studies, and gaps across the literature. This is a reorganization task — the reading and judgment must already be done.

**Never generate citations.** AI hallucination rate on specific citations is high. Every reference must come from a paper you have personally located, opened, and confirmed exists. "It sounds right" is not verification.

**Thematic restructuring:** If your draft review is structured source-by-source, paste it and ask AI to suggest a thematic grouping. Evaluate the suggestions — it will sometimes identify real themes, sometimes group by surface similarity. Then restructure the draft yourself using those themes as scaffolding.

**Prose tightening:** Once the intellectual content is finalized, AI can reduce redundancy, sharpen transitions, and flag where the argument jumps without connection. This is the last step, not the first.

---

## Chapter 10 — Drafting (Section by Section)

Write the sections in this order, not the order they appear in the paper: **Methods → Results → Discussion → Introduction → Abstract → Title.** This is the logic-of-discovery order. The Introduction frames what you found; you can only write it honestly after you know what that was. The Abstract compresses everything; write it last.

### The drafting discipline

**Get a working draft fast.** The goal of a first pass is a document that exists, not a document that is good. A draft you can read is infinitely more useful than a perfectly planned document that hasn't been written. Write to discover what you actually think, then revise against what you find.

**Iterate on the artifact, not the specification.** Once a section exists, the revision target is the section, not the outline. Read the draft against the schema. Identify the specific failure — an unsupported claim, a missing comparison reference, a result that appears before it is introduced — and fix that one thing. Do not rewrite the whole section to fix one sentence.

**One concern per pass.** When multiple things are wrong, fix them in sequence. Pass 1: structural failures (wrong claims, missing evidence, broken logic). Pass 2: paragraph-level failures (unclear sentences, unsupported assertions, misplaced interpretation). Pass 3: surface failures (prose, transitions, style). Trying to fix structure and style simultaneously produces a draft that is better at neither.

**Structural failures before stylistic ones.** A well-polished paragraph making the wrong point is harder to fix than a rough paragraph making the right point. Do not polish until the structure is sound.

### The Feynman Test for prose

Each section should pass a comprehension test: can you explain the central claim of this section to a non-specialist in under two minutes without referring to your notes? If you cannot, the section may not contain a clear claim. Smooth prose can make vague thinking undetectable to a reader and invisible to the writer. The Feynman Test makes the vagueness visible before submission.

Apply it section by section: Introduction (what gap does this paper fill and why does it matter?), Methods (what specifically did you do and why was this design appropriate?), Results (what did you find, including null results?), Discussion (what does it mean and what are its limits?). A section you cannot explain is a section that is not yet written, regardless of how many words it contains.

### The key message test

Before drafting any section, write one sentence — the main point this section must establish. Not a description of what the section covers: a claim. "The experimental group outperformed the control group on retention but not on immediate recall" is a key message. "This section presents the results" is not.

Every paragraph in the section must either establish or support this key message. Paragraphs that do neither are candidates for removal or relocation. If you cannot write the one-sentence key message for a section, you are not ready to draft it.

---

### Methods

**What it is:** A complete, transparent record of exactly what you did — specific enough that another researcher in your field could reproduce the study from your description alone, without contacting you. Nothing more, nothing less. The Methods section is purely procedural: no results, no interpretation, no explanation of what you hoped to find.

**What it is not:** A narrative of how the research went. You do not include the approaches you tried and abandoned, the protocol changes that didn't affect outcomes (unless you report them as limitations), or the reasoning that led you to your design choices — just the choices themselves. Write in past tense, passive voice: "Participants were recruited via..." not "We recruited participants via..."

**What must be in it:**

*Participants or data source.* Who or what was studied? How many? How were they selected — random sampling, convenience sample, purposive selection? What were the inclusion and exclusion criteria? For human subjects: relevant demographics (age range, gender distribution, relevant expertise level), recruitment method, any compensation, and ethics approval or IRB number. For datasets: the source, the version or date accessed, any preprocessing applied before your analysis began.

*Design.* Name the study design explicitly — randomized controlled trial, quasi-experiment, cross-sectional survey, case study, mixed-methods, etc. Specify whether it is between-subjects (different people in different conditions) or within-subjects (same people in all conditions). Explain why this design is appropriate for your research question.

*Materials and instruments.* Name every survey, test, scale, piece of software, or apparatus used. If a measure is validated, cite the original validation study and report its reliability (Cronbach's alpha or equivalent). If you modified a validated instrument, say so and explain why. "A questionnaire was used" is not sufficient — name the questionnaire.

*Procedure.* Walk through exactly what happened, in the order it happened. If there were multiple conditions, describe each. If participants completed tasks in sequence, list them in sequence. If there was a training phase, a testing phase, and a debrief, describe all three. The goal is a timeline a stranger could follow.

*Variables.* Identify your independent variable (what you manipulated or used to group participants), your dependent variable (what you measured), and any covariates or control variables. Explain how each was operationalized — not just "we measured learning" but "learning was operationalized as the score on a 20-item posttest, with each item scored 0 or 1."

*Data preparation.* Describe what you did to the data before analysis: how missing values were handled (listwise deletion, imputation, exclusion threshold), how outliers were defined and treated, any transformations applied (log transformation, z-scoring), how any composite scores were created.

*Analysis.* Name the specific statistical tests used and why. Report the software and version (R 4.3.1, SPSS 29, Python 3.11 with scipy 1.11). State your significance threshold (α = .05) and whether you applied corrections for multiple comparisons.

**The replicability test:** Hand your draft Methods to a colleague who was not involved in the study. Ask them to list any question they would need to ask you before they could run the same study. Every question they have is a gap in the Methods section.

**Common failures:**
- "Standard protocols were followed" with no citation and no description
- Participants described only as "students" with no demographics or selection criteria
- Instruments named without citations or reliability statistics
- The procedure described at the level of "participants completed the task" with no detail about what the task actually was
- No mention of IRB or ethics approval for studies involving human participants
- Analysis described as "statistical analysis was conducted" without naming the tests

**Checklist:**
- Is the study design named and justified?
- Are participants described with sample size, relevant demographics, and selection criteria?
- Is the ethics approval / IRB number included?
- Are all instruments named and cited?
- Is the procedure written step-by-step in the order it occurred?
- Are independent, dependent, and control variables identified and operationalized?
- Is data preparation (missing values, outliers, transformations) described?
- Are specific statistical tests named, along with software and version?

---

### Results

**What it is:** A report of what the data showed — nothing more. The Results section is a factual account of outcomes, organized to mirror the order in which the Methods described the study. Every number that appears in the paper appears first in the Results.

**What it is not:** An interpretation. Any sentence that explains *why* a result occurred, what it *means*, or how it *relates to prior work* belongs in the Discussion, not the Results. "Participants in the experimental group scored higher, which suggests the intervention was effective" has crossed the line. "Participants in the experimental group scored higher" is Results. "This suggests the intervention was effective" is Discussion.

**Structure:** Follow the same sequence as your Methods and hypotheses. If you stated three hypotheses at the end of the Introduction, report results for Hypothesis 1, then Hypothesis 2, then Hypothesis 3 — in that order. Begin each subsection by restating the hypothesis being tested, then report the result.

**What a complete statistical result looks like:** Every claim must include the full statistical reporting: test statistic, degrees of freedom, exact p-value, and effect size. Not "the experimental group performed significantly better (p < .05)" but "the experimental group scored higher on the posttest (M = 74.3, SD = 8.1) than the control group (M = 68.7, SD = 9.4), t(62) = 2.47, p = .016, d = 0.63." The effect size (Cohen's d, η², r, odds ratio) tells the reader whether the difference is trivially small or practically meaningful — the p-value alone does not.

**Tables and figures:** Every table and figure must be referenced in the text with a sentence that describes what it shows. Never include a figure without a pointing sentence: "Figure 2 shows the distribution of posttest scores by condition." The table or figure is a supplement to the text, not a replacement for it.

**Negative results:** A null result — a hypothesis that was not supported — is a result and must be reported. "No significant difference was found between conditions (t(62) = 0.43, p = .67, d = 0.11)" is a legitimate, important finding. Omitting it is selective reporting. Reviewers and readers need to know what you tested and did not find, not only what you tested and found.

**Common failures:**
- Reporting means without standard deviations
- Reporting p-values without test statistics or effect sizes
- Using "significant" to mean "important" rather than "statistically significant at α = .05"
- Describing what figures show without pointing to the specific figure
- Omitting null results or burying them in supplementary material
- Including interpretation ("this shows that...") rather than just reporting the finding

**Checklist:**
- Are results reported in the same order as the Methods and hypotheses?
- Does every statistical claim include the test statistic, degrees of freedom, exact p-value, and effect size?
- Are means reported with standard deviations?
- Is every table and figure referenced and described in the text?
- Are null and negative results reported, not omitted?
- Is there any interpretation in the Results section that should move to the Discussion?

---

### Discussion

**What it is:** The section where you interpret what the results mean, connect them to what was already known, and acknowledge what the study could not resolve. The Discussion is the intellectual center of the paper — where you argue rather than report.

**What it is not:** A summary of the Results. The Discussion must not open by restating "we found X, we found Y, we found Z." The reader just read the Results. That space is wasted. Start with what the findings mean.

**The structure of a strong Discussion:**

*Lead with the main finding and its meaning.* The first paragraph answers the research question directly. Not "we conducted a study examining..." — you are past that. State the central result and what it implies. "Students who used AI assistance during practice retained less on the unassisted posttest, suggesting that the tool displaced the cognitive struggle that consolidates learning, rather than augmenting it."

*Connect each finding to prior work.* Work through your results systematically, explaining how each confirms, contradicts, extends, or qualifies existing findings. This is where the citations from your Introduction and Literature Review pay off — each result should link to at least one prior finding or theoretical claim. "This finding is consistent with Bastani et al. (2024), who found similar retention deficits when AI provided immediate solutions rather than scaffolded hints."

*Explain the unexpected.* If any result surprised you, say so and offer possible explanations. Reviewers appreciate intellectual honesty about anomalies. "The null result for Hypothesis 2 was unexpected given the strong effect reported by [prior study]. One possible explanation is..."

*Limitations.* Name the specific constraints on your conclusions — not as a defensive formality but as honest guidance about how far the findings generalize. A convenience sample of undergraduates at one institution constrains generalizability. A short study duration may not capture long-term effects. A self-report measure may not reflect actual behavior. Each limitation should appear where it is most relevant, not stockpiled at the end. "These findings should be interpreted cautiously given the short (4-week) study duration; longer-term retention effects may differ."

*Implications.* What does this mean for practice, theory, or future research? Be specific. "Instructors using AI tutoring tools should configure them to provide hints rather than direct answers" is an implication. "Future research should examine other contexts" is not.

**The causal language trap.** If your study is correlational or observational, you cannot claim causation in the Discussion no matter how strong the correlation. "X was associated with Y" is honest. "X caused Y" requires an experimental design that ruled out confounds. Review every causal-sounding verb: "demonstrates," "shows," "proves," "produces," "leads to." Each one may need to become "suggests," "is associated with," or "is consistent with."

**Common failures:**
- Opening with a restatement of the Results
- Discussing only the significant findings and not addressing the null results
- Connecting findings to prior work only vaguely ("consistent with previous research") without naming specific studies
- Acknowledging limitations only in a single defensive paragraph at the end ("all studies have limitations")
- Overclaiming causation from correlational or observational data
- Ending with "more research is needed" rather than a specific implication or direction

**Checklist:**
- Does the first paragraph state the central finding and its meaning — not a restatement of results?
- Does it connect each finding to specific cited prior work?
- Does it address null and unexpected results, not just significant ones?
- Does it acknowledge specific limitations where relevant, not just generically at the end?
- Does it avoid causal language if the design was correlational or observational?
- Does it end with specific implications rather than vague calls for more research?

---

### Introduction

**What it is:** A funnel. Start broad with the domain and its importance, narrow to the specific problem your paper addresses, narrow further to the gap in existing knowledge your paper fills, and end with your research question and hypothesis. By the final paragraph, the reader should understand exactly what this paper will do and why it needs doing.

**Why write it last:** You are framing what actually happened, not what you hoped would happen. Writing the Introduction first produces a paper that promises one thing and delivers another — a mismatch reviewers catch immediately. Write it after the Results and Discussion so you frame your real contribution accurately.

**The three moves (Swales CARS model):**

Move 1 — *Establish the territory.* Describe the field, its importance, and what is already known. This is where you cite background work and establish the stakes. Why does this domain matter? What progress has been made?

Move 2 — *Establish the niche.* Identify what is missing, contested, or not yet understood. This is the gap your paper fills. It must be specific — "little is known about X" is weak unless you can name what specifically is not known and why that matters. "Prior work has examined AI tutoring in math, but has not isolated whether the benefit depends on whether the AI provides answers or scaffolded hints."

Move 3 — *Occupy the niche.* State what this paper does: the research question, the method in brief, and the hypothesis. This should be one or two short paragraphs. The Introduction ends here. Everything else belongs in the Methods.

**What it is not:** A literature review. The Introduction cites enough prior work to establish the gap; the full synthesis of the field goes in the Literature Review or Background section, if your paper has one. The Introduction also does not present your findings — those go in the Results and Abstract.

**Common failures:**
- Opening with something so broad it could apply to any paper in the field ("Technology is increasingly important in education...")
- Failing to identify a specific gap — describing the territory in detail but never stating what is missing
- Presenting the research question but not explaining why answering it matters
- Ending with a list of what each section contains ("Section 2 describes the methods...") rather than the hypothesis
- Writing the Introduction before the paper is finished, so it promises something different from what was delivered

**Checklist:**
- Does it open with the domain, not with the specific study?
- Does it identify a specific, nameable gap — not just "more research is needed"?
- Does it explain why filling this gap matters?
- Does it end with a clear, testable research question or hypothesis?
- Are citations current (within 5 years) unless citing a foundational work?
- Does the Introduction set up exactly what the paper delivers — no more, no less?

---

### Abstract

**What it is:** A standalone summary that allows a stranger to decide whether to read the full paper. In most databases, the abstract is all anyone sees. It must contain the complete argument in miniature: problem, gap, method, finding, implication — all in 150 to 250 words (or whatever the journal specifies).

**What it is not:** An introduction to the paper. The abstract is not the place to build context — it is the place to deliver the argument in compressed form. It is also not a table of contents: "The paper is organized as follows..." tells the reader nothing about the content.

**The five-sentence test.** A functional abstract can usually be built from five sentences, one per element:
1. *Problem:* What is the issue or question this paper addresses?
2. *Gap:* What does existing work not yet know or resolve?
3. *Method:* What did you do to address the gap? (Study type, participants or data, key measures)
4. *Finding:* What did you find? (Be specific — a number, a direction, a relationship)
5. *Implication:* What does it mean or what should be done differently?

If any of these is missing, the abstract is incomplete. Most weak abstracts fail on the finding (vague) or the implication (absent or generic).

**Common failures:**
- Opening with "This paper examines..." or "This study explores..." — wasted words that say nothing
- Describing the method in detail while omitting the finding
- Ending with "results are discussed" or "implications are presented" — which tells the reader nothing
- Claiming more than the data supports (a correlational study whose abstract says "demonstrates that X causes Y")
- Reporting only that results were significant without giving the direction or magnitude

**Checklist:**
- Does it state the problem in the first one or two sentences?
- Does it name the gap explicitly?
- Does it describe the method specifically enough to know what kind of study this is?
- Does it give the primary finding with enough specificity to be useful?
- Does it state an implication — not just "results are discussed"?
- Could it stand alone, with no access to the rest of the paper?
- Does it stay within the journal's word limit?

---

### Title

**What it is:** A search tool and a promise. It tells a stranger scrolling a database whether this paper is relevant to their question. It also makes a specific, verifiable claim about what the paper found — not what it studied.

**What it is not:** A topic label. "Artificial Intelligence in Education" describes an area. "AI Tutoring Reduces Retention When Students Bypass Problem-Solving" describes a finding. The second one tells the reader whether to read the paper. The first one tells them almost nothing.

**The anatomy of a strong title:** Subject (what was studied) + Verb (what was found or tested) + Scope (in what context, with what population). Two-part titles with a colon are common in the social sciences: the first half makes the argument, the second specifies the scope.

Weak: *"A Study of AI Tutoring Effects on Learning"*
Strong: *"Borrowed Cognition: AI Assistance Reduces Posttest Retention in Undergraduate Math Practice"*

**Checklist:**
- Does the title state a finding, not just a topic?
- Does it tell a stranger whether this paper answers their question?
- Is it under 15 words?
- Does it avoid phrases like "a study of," "an investigation into," or "the effects of"?

---

### AI at Chapter 10

**Data cleaning code:** Give AI your data structure — column names, data types, known issues (missing values, duplicates, inconsistent coding) — and ask it to write the cleaning script in R or Python. It will produce working code the majority of the time. Review the logic before running it; do not run unreviewed code on your only copy of the data. Ask it to add comments explaining each step so you can verify the intent matches the operation.

**Statistical analysis code:** Tell AI your design (between-subjects ANOVA, logistic regression, mixed-effects model) and your data structure, and ask it to write the analysis. It knows standard statistical libraries well — `scipy`, `statsmodels`, `lme4`, `lavaan`. It will sometimes choose defaults that need adjusting (e.g., wrong reference level, no correction for multiple comparisons). Understand what the code is doing before you report the output.

**Visualization code:** AI substantially lowers the barrier to publication-quality figures. Describe what you want — "a box plot with individual data points overlaid, grouped by condition, with significance brackets" — and ask for `ggplot2`, `matplotlib`, or `seaborn` code. Iterate on the output. This is one of the highest-value uses of AI in empirical research: getting to a clean figure in an hour instead of a day.

**Replicability check (Methods):** Paste your Methods section and ask: "What would an independent researcher need to know to replicate this study that is not in this description?" Treat every gap it identifies as an item to add.

**APA/AMA/Vancouver formatting:** Paste your reference list and ask AI to reformat it to the required style. Verify every entry against the original source — AI makes errors on capitalization, author order, and page numbers. Use this to get close quickly, not as a final product.

**Abstract compression:** Write out your answers to the five abstract questions in plain sentences, then ask AI to compress them into a coherent paragraph under your word limit. Revise the output — it will typically soften findings and over-inflate implications. The finding and implication must remain in your words.

**Discussion structure check:** Write the Discussion yourself. Then paste it and ask: "Does this Discussion open with a restatement of results, or with the meaning of the central finding?" and "Does every result connect to a specific cited prior study?" These structural checks are reliable.

### Labor separation for writing

Every AI use in research writing involves a division of cognitive labor. Some of that division accelerates the work without cost. Some of it delegates the cognitive work that constitutes the research.

**What AI handles reliably:** Generating structural scaffolding from a complete argument you have already built. Reformatting citations. Compressing a five-sentence draft abstract you have written. Writing data cleaning or analysis code from a complete specification. Flagging missing elements in a Methods section you have drafted. Prose-level tightening — reducing redundancy, sharpening transitions — after the intellectual content is finalized.

**What the author must keep:**

*Problem formulation.* Deciding which question is worth asking, which gap is genuine, which hypothesis is worth testing. AI will generate a plausible hypothesis from your description. The problem is that plausibility is not the same as relevance to your actual data, your actual field, or the actual gap that exists. The research question is yours to formulate.

*Causal reasoning.* Establishing which variables belong in the analysis, what the right comparison is, and what confounds need to be addressed. AI processes statistical patterns but cannot perform the identification layer — the domain-specific judgment about which variables to include and which causal story the design can actually support. The Discussion's interpretive claims belong to you.

*Plausibility auditing.* Reading AI output against what you actually know about how your domain works. AI produces confident-sounding sentences. The confidence is calibrated for fluency, not for epistemic accuracy. Only a researcher with genuine domain knowledge catches the claim that sounds right but isn't — and catching it requires the domain knowledge that AI cannot supply.

*Accountability.* You sign the paper. Every claim in it is yours. AI-generated prose that you submit without understanding is a claim you are making without being able to defend it. The question to ask of any AI output before it enters the manuscript: can I explain why this is true, in this study, for this data? If you cannot, rewrite it yourself.

**The audit question:** Before submission, for each section that AI contributed to, ask: does this section contain claims I did not reach myself, in my own thinking, before asking AI to write it? If yes, the section may be fluent without being true to your research.

---

## Chapter 11 — Quality Control

### Calibrate every claim

The single most common failure in research writing is overclaiming. Match your language to your evidence:

| Evidence type | Claim you can make |
|---|---|
| Correlational data | X is associated with Y |
| Experimental design | X appears to affect Y |
| Small sample | Preliminary evidence suggests |
| Literature review | Prior work indicates / suggests |
| Case study | This case illustrates |
| Anecdote | This example raises the possibility |

### Run a claim audit

Before submission, highlight every major claim in the paper. For each one, ask: What evidence supports this? Then label it: Supported / Partially supported / Overstated / Unsupported / Needs citation / Needs qualification. Fix everything that is not "Supported."

### Statistical integrity check (empirical papers)

Statistical mistakes have their origins in ineffective experimental designs, inappropriate analyses, and flawed reasoning — and they appear in papers that advance claims that do not follow from the data, papers that are often taken at face value despite being wrong.

Check for:

- Effect sizes reported, not just p-values
- Confidence intervals included where appropriate
- Multiple comparison corrections applied
- Exact p-values used, not just p < 0.05
- Tests appropriate for the data type
- Repeated measures treated correctly
- Error bars defined (SD vs. SEM, not interchangeable)
- Null and failed results included

**Do not HARK** (Hypothesize After Results are Known). Do not run twenty tests, find two significant ones, and write the paper as if you predicted those two all along. A 2024 meta-analysis of 75,000 studies across a broad range of fields concluded that results from as many as one in seven may have been at least partially faked — and the replication crisis in science stems at least partly from selective reporting and post-hoc hypothesis generation.

### The prose verification stack

Run three checks in order before treating any section as complete.

**Layer 1 — Format check (10 seconds).** Does the section do what it is supposed to do structurally? Methods: past tense, no results. Results: no interpretation. Discussion: no result-summaries opening, no vague "more research is needed" closing. Introduction: CARS three moves present, ends with hypothesis. These are pass/fail. Catch them first so the other checks apply to the right content.

**Layer 2 — Fact check (read the section against the data).** Does every quantitative claim in the text match the corresponding table or figure? Is every "significant" result actually significant at the stated alpha level? Do the means, standard deviations, test statistics, and effect sizes in the text match the analysis output exactly? Do not rely on memory. Go back to the data. One mismatch in a published paper can contaminate the entire finding.

**Layer 3 — Test (naive reader check).** Give the section to someone unfamiliar with your study. Ask them what they understood the paper to claim. Where their summary diverges from your intent, the writing is unclear — or the claim is not actually in the text, only in your head. The section is done when the naive reader's summary matches the claim you intended.

Do all three. Do them in order. Do not skip to Layer 3 before Layer 2, or revise prose before the factual claims are verified.

### The "compared with what?" check for written claims

Every quantitative claim in the paper needs an explicit reference. Not just in figures — in every sentence that makes a quantitative assertion.

"Students in the AI group scored 14% higher" — compared with the control group? Compared with their own pretest? Compared with a benchmark? The reference must be in the sentence. If it is not, the claim has no meaning.

"The effect was large" — by what standard? Cohen's d of 0.63 is large by Cohen's conventional thresholds. By what comparison is this large or small in the context of this intervention? Name it.

"Performance improved substantially" — from when to when? By how much? In which direction?

Before submission: highlight every quantitative claim in the paper. For each one, ask: "compared with what?" If the reference is not in the sentence, it belongs there.

### Separate style problems from logic problems

These are different diagnoses and require different fixes.

**Style weakness** — The writing is unclear, repetitive, awkward, or poorly organized. Fix: revise sentences, transitions, structure, paragraph flow.

**Logic weakness** — The research question is vague, the method does not test the claim, the evidence is insufficient, the conclusion goes beyond the data. Fix: revise the argument, methods, scope, or claim.

Clear writing cannot save bad reasoning.

### AI at Chapter 11

**Claim audit:** Paste a section and prompt: "Identify every causal or strong claim in this text. For each one, flag whether the language is stronger than what a correlational study with n=X can support." It is reliable at catching "proves," "demonstrates," and "shows" where "suggests" is correct. Verify all flags — it will occasionally misread the claim, but most of the flags will be real.

**Statistical reporting check:** Paste a results paragraph and the statistical method used and ask: "Does the language accurately reflect what this test can and cannot establish? Are effect sizes, confidence intervals, and exact p-values reported?" Then fix everything it flags.

**Assumption checks:** Ask AI to write code to run assumption checks for your statistical tests — normality (Shapiro-Wilk), homogeneity of variance (Levene), multicollinearity (VIF), autocorrelation (Durbin-Watson), whatever applies to your design. Running these should happen before finalizing any results.

**Style vs. logic triage:** Paste a weak paragraph and ask: "Is this weak because of unclear writing, or because the argument itself is not sound?" Any logic problem it identifies must be addressed by you. Style problems can be fixed collaboratively.

**Warning:** AI will make the writing more fluent, which makes logic problems harder to see. After AI editing, re-read explicitly for argument logic, not just prose quality.

---

## Chapter 12 — Peer-Review Simulation

Before submission, read your paper the way a rigorous reviewer will. That means understanding what each section is supposed to do — and checking whether yours actually does it. Most first papers fail not because the research is bad but because the writing doesn't match the section's job.

---

### Title

**What it is:** A title is a search tool and a promise. It tells a stranger scrolling a database whether this paper is relevant to them, and it makes a specific, verifiable claim about what the paper found.

**What it is not:** A topic label. "Artificial Intelligence in Education" is a topic, not a title. "AI Tutoring Reduces Learning Gains When Students Bypass Problem-Solving" is a title.

**The anatomy of a strong title:** Subject (what you studied) + Verb (what you found or tested) + Scope (in what context, with what population, under what conditions). Two-part titles with a colon are common in social sciences: the first half makes the argument, the second specifies the scope. *"Borrowed Cognition: AI Assistance Reduces Retention in Undergraduate Math Practice"* is better than *"The Effects of AI on Math Learning."*

**Checklist:**
- Does the title state a finding, not just a topic?
- If someone searched for it, would they know from the title whether this paper answered their question?
- Is it under 15 words?

---

### Abstract

**What it is:** A standalone summary that allows a reader to decide whether to read the full paper. In most databases, it is all anyone sees. It must contain the complete argument in miniature.

**What it is not:** An introduction. Not "In this paper we explore..." — that is wasted space.

**The five-sentence test:** Every abstract should be able to answer these five questions, each in roughly one sentence:
1. What problem does this paper address?
2. What gap in existing knowledge does it fill?
3. What method did you use?
4. What did you find?
5. What does it mean or imply?

If any of these is missing, the abstract is incomplete.

**Common failures:** Leading with background instead of the problem. Describing what the paper does rather than what it found ("we analyze," "we present" instead of the actual result). Claiming more than the data supports. Ending with "the implications are discussed" — which tells the reader nothing.

**Checklist:**
- Does it state the problem in the first sentence?
- Does it include the gap the paper fills?
- Does it name the method (not just "we conducted a study")?
- Does it give the primary finding in specific terms?
- Does it state an implication, not just "results are discussed"?
- Could it stand alone, with no access to the rest of the paper?

---

### Introduction

**What it is:** A funnel. It starts broad — the domain and why it matters — narrows to the specific gap in existing knowledge, and ends with your research question and hypothesis. By the last paragraph of the Introduction, the reader should understand exactly what this paper will do and why it needs to be done.

**What it is not:** A literature review. The Introduction cites enough prior work to establish the gap; the full synthesis of the literature goes in the Literature Review or Background section. It is also not the place to present your findings.

**The three moves (Swales CARS model):**
- Move 1 — Establish the territory: what is the field, why does it matter, what is already known?
- Move 2 — Establish the niche: what is missing, contested, or not yet understood?
- Move 3 — Occupy the niche: what does this paper do, and how does it address the gap?

The transition from Move 2 to Move 3 is where most introductions fail. The gap must be specific enough to motivate exactly this study — not vague enough to motivate any study in the area.

**Checklist:**
- Does it open with the broader domain, not with your specific study?
- Does it identify a specific gap — not just "more research is needed" but exactly what is missing and why it matters?
- Does it end with a clear, testable research question or hypothesis?
- Are citations current (within 5 years) unless citing a foundational work?
- Does the Introduction set up exactly what the paper delivers — no more, no less?

---

### Methods

**What it is:** A complete, transparent description of what you did — specific enough that another researcher could replicate the study exactly. The Methods section is the only section of the paper that is purely procedural. It contains no analysis, no interpretation, and no results.

**What it is not:** A narrative of how the research went. You don't include dead ends, protocol changes made mid-study (unless reported as a limitation), or procedural decisions that didn't affect the outcome. Write it in past tense, passive voice.

**What must be in it:**
- *Participants or data source:* Who or what was studied, and how were they selected? What were the inclusion/exclusion criteria? For human subjects: demographics, sample size, recruitment method, compensation, ethics approval / IRB number.
- *Design:* What type of study is this? Between-subjects or within-subjects? Experimental or observational? Longitudinal or cross-sectional? The design justification belongs here — why was this design appropriate for the question?
- *Materials and instruments:* What tools, surveys, software, or stimuli were used? Name the specific instrument (not just "a survey"), cite it if it is validated, and describe any modifications.
- *Procedure:* Step by step, in the order it happened. What happened first, what happened next, what happened last. If there were conditions, describe what each condition entailed.
- *Variables:* What was the independent variable (what you manipulated or observed)? What was the dependent variable (what you measured)? What covariates or control variables did you include and why?
- *Data preparation:* How did you handle missing data? Outliers? What transformations or cleaning steps were applied before analysis?
- *Analysis:* Exactly which statistical tests were used, and why. Which software and version. What alpha level did you use for significance?

**The replicability test:** Hand your Methods section to someone in your field who was not involved in the study. Ask them whether they could run the same study. If they have to ask you questions, those answers belong in the Methods section.

**Checklist:**
- Are participants/data described with enough detail to assess generalizability?
- Is the design named and justified?
- Are instruments named specifically and cited if validated?
- Is the procedure written step-by-step in the order it occurred?
- Are all variables — independent, dependent, and control — identified?
- Is data cleaning described?
- Are the specific statistical tests named?
- Is IRB/ethics approval mentioned for human subjects research?
- Could an independent researcher replicate this study from this description alone?

---

### Results

**What it is:** A report of what the data showed, in a logical sequence that mirrors the Methods. The Results section is the only section of the paper that is purely descriptive — no interpretation of what the findings mean, no connection to prior literature, no implications.

**What it is not:** An interpretation. Phrases like "this suggests," "this is likely because," or "this demonstrates" belong in the Discussion, not the Results. Any sentence that explains *why* a result occurred has crossed the line.

**Structure:** Walk the reader through the findings in the same order the Methods described them. If you described three hypotheses in order, present the results for each hypothesis in the same order. Every table and figure must be referenced in the text — never include a table without a sentence that points to it and describes what it shows.

**Negative results:** Null results, failed hypotheses, and unexpected non-findings must be reported. A result that shows no effect is a result. Omitting it is selective reporting.

**Common failures:** Reporting only significant findings and burying or omitting non-significant ones. Describing what figures show in vague terms rather than specific values. Using the word "significant" without reporting the actual statistics. Presenting percentages without the underlying counts.

**What a complete statistical result looks like:** Not "students in the experimental group performed better (p < .05)" but "students in the experimental group scored higher on the posttest (M = 74.3, SD = 8.1) than students in the control group (M = 68.7, SD = 9.4), t(62) = 2.47, p = .016, d = 0.63."

**Checklist:**
- Are findings reported in the same order as the Methods described them?
- Does each claim include the specific statistic (test statistic, degrees of freedom, p-value, effect size)?
- Is every table and figure referenced in the text?
- Are null and unexpected results reported, not omitted?
- Is there any interpretation in the Results section? (Remove it.)

---

### Discussion

**What it is:** The section where you interpret what the results mean, connect them to what was already known, and address what the study could not resolve. This is the intellectual core of the paper — where you argue, not just report.

**What it is not:** A summary of the Results. The Discussion should not begin with "We found that..." and restate everything from the Results section. That space is wasted. The reader just read the Results.

**The structure of a strong Discussion:**
1. *Lead with the main finding:* The first paragraph states your central result and what it means — directly, without preamble.
2. *Connect to prior work:* How does each finding relate to what was previously known? Does it confirm, contradict, extend, or qualify existing findings? This is where you cite the literature from the Introduction and the Literature Review.
3. *Explain the unexpected:* If any result was surprising, what might explain it?
4. *Acknowledge limitations honestly:* Not "this study has limitations, as all studies do" — name the specific limitations and why they matter. A small sample, a specific population, a lab setting, a cross-sectional design, a self-report measure — each of these constrains what can be concluded, and the reader needs to know.
5. *Implications:* What does this mean for practice, theory, policy, or future research? Be specific. "Future research should explore this area further" is not an implication.

**The causal language trap:** If your study is correlational or observational, you cannot claim causation in the Discussion no matter how strong the correlation. "X was associated with Y" is honest. "X caused Y" requires an experimental design that ruled out confounds. Using causal language in a correlational paper is one of the most common and consequential errors in research writing.

**Checklist:**
- Does the first paragraph state the central finding and its meaning — without restating the whole Results section?
- Does it connect findings to specific cited prior work?
- Does it acknowledge limitations where they are relevant, not just in a single defensive paragraph at the end?
- Does it avoid causal claims if the design was not experimental?
- Does it end with something more specific than "more research is needed"?

---

### Conclusion

**What it is:** A brief, final statement of what the paper established, why it matters, and what it means going forward. Typically one to three paragraphs. It is not a summary of the whole paper — the abstract did that. It is the closing argument.

**What it is not:** A repeat of the Discussion. If the Conclusion restates everything already in the Discussion, one of them is redundant.

**What it should contain:** The answer to the research question, stated plainly. The contribution the paper makes — what does it add to the field that was not there before? And if relevant, one or two specific directions for future work — not "researchers should study this more" but a concrete question this paper opens that was not previously visible.

**Checklist:**
- Does it answer the research question stated in the Introduction?
- Does it state the paper's contribution to the field?
- Does it avoid restating the Discussion?
- Does it avoid empty closings ("this is an important area for future research")?

---

### AI at Chapter 12

Peer-review simulation is one of the highest-value AI tasks in the entire workflow.

**Structured review:** Paste the full paper and prompt: "You are a rigorous peer reviewer for [target journal]. Produce a review in three sections — Critical (grounds for rejection), Major (required revisions), Minor (recommended improvements). Be specific; cite section and paragraph." Then evaluate each item. Most will be real issues. Some will be confused or inapplicable; you should be able to tell the difference if you know your own paper.

**Section-specific checks:** Use the checklist questions above as prompts. "Does the Results section contain any interpretation — any sentence that explains why a result occurred rather than what it was?" "Does the Discussion open with a restatement of the Results, or with the meaning of the central finding?" These narrow prompts produce sharper feedback than asking AI to review the whole paper at once.

**Cross-section consistency:** Ask AI to compare specific pairs of sections: "Does the Discussion answer the research question stated in the Introduction?" "Does the Abstract match the actual findings in the Results?" "Do the hypotheses stated at the end of the Introduction correspond exactly to the tests reported in the Results?" These alignment failures are extremely common and easy to miss when you have been too close to the paper.

**Push past AI politeness:** AI defaults to diplomatic critique. Ask explicitly: "What is the single strongest reason to reject this paper?" and "What assumption in this paper is most likely to be wrong?" It will often identify real weaknesses when pressed this way.

**Venue-specific simulation:** Tell AI the target venue — CHI, NeurIPS, NEJM — and ask it to review from that community's perspective. CHI reviewers weight contribution to HCI theory and design implications differently than NeurIPS reviewers weight technical novelty and benchmark performance. AI knows these norms well enough to give useful calibration.

---

## Chapter 13 — Ethics and Bias Screen

Before finalizing, ask:

- Are conflicts of interest disclosed?
- Is funding disclosed?
- Are limitations honestly stated?
- Does the paper universalize from a narrow sample?
- Does the literature review cite only sources that agree with the thesis?
- Are claims about people, learning, health, or behavior appropriately bounded?

The replication crisis persists in part because verification produces public goods while imposing private costs. Replication attempts can be time-consuming, hard to publish, and professionally risky — and editorial policies requiring data and code have improved availability, but compliance and usability vary widely. Submitting a paper that could not survive replication is an ethical failure, not just a methodological one.

### AI at Chapter 13

**Overgeneralization check:** Paste the Discussion and Conclusion and ask: "Flag any claim that generalizes beyond what the sample or study design can support." It is reliable at catching "users prefer," "students learn better," "this approach improves" when what you actually have is "43 undergraduates at one institution in a 4-week study."

**Confirmatory bias check:** Paste the literature review and ask: "Does this review appear to selectively cite sources that support the thesis while ignoring contradictory evidence?" It will identify one-sided framing in aggregate patterns even when individual citations look fine.

**Citation diversity:** Paste your reference list and ask: "What patterns do you notice in the geography, institution, gender, or time period of these citations?" Use the output as a starting point for your own audit, not a verdict.

**AI disclosure:** Know the policy of your target journal before you submit. Policies vary: some require disclosure only for generated text, some for any substantive AI assistance, some have no policy. When in doubt, disclose. Add a brief statement to the Acknowledgments or Methods describing what AI tools were used and for which tasks — data cleaning code, figure generation, copy editing, peer-review simulation. Disclose the tool and the task; do not disclose the content of the conversation.

---

## Chapter 14 — Writing Well: Prose for Scientific Papers

Having a valid hypothesis, a sound design, clean data, and honest statistics is necessary. It is not sufficient. A paper that cannot be read cannot be used. And a surprising number of papers that survive peer review for their methodology fail their readers at the level of the sentence: the claim is there, but it is buried; the logic is there, but the reader has to excavate it; the finding is real, but the prose makes it feel tentative or grandiose or both at once.

Scientific writing is not a relaxed version of regular writing with more jargon. It is a precise instrument for transmitting claims and their evidentiary basis with minimal loss and minimal distortion. Every failure at the prose level is a failure to communicate what the research actually found. This chapter is about that.

---

### What scientific prose is actually for

The function of a scientific sentence is to move information from the writer's mind into the reader's with minimal friction and no loss of precision. This sounds obvious. It is not practiced.

The failure mode is not stupidity. It is the accumulation of conventions that developed for other reasons — impersonality conventions, hedging conventions, citation-density conventions — until the prose becomes a delivery mechanism for the appearance of rigor rather than for the thing itself. A paragraph can be hedged so thoroughly that it no longer says anything. A sentence can be so nominalized that it requires the reader to reconstruct the verb the writer removed. A methods section can be so passive and impersonal that the reader cannot tell what the researcher actually did.

The question to ask of every sentence is: what is this sentence claiming, and does the way I have written it convey that claim as clearly and as efficiently as the language allows? If the answer is no — if the sentence is working against its own content — the sentence needs to be rewritten regardless of whether it follows disciplinary conventions.

---

### Clarity: the no-fog principle

Fog is the distance between what a sentence says and what it means. Every word that does not do work is fog. Every abstraction that could have been a concrete example is fog. Every passive construction that obscures who did what is fog.

The no-fog principle is not a ban on complexity. Complex claims require complex sentences. It is a ban on complexity that is not doing any work — sentences that are long, nested, and abstract when they could be shorter, direct, and concrete without any loss of precision.

**The most common fog generators in scientific writing:**

*Nominalizations.* A nominalization takes a verb and turns it into a noun: "investigate" becomes "the investigation of," "measure" becomes "the measurement of," "improve" becomes "improvement in." The sentence that was about an action becomes a sentence about a thing. The actor disappears. The motion stops. "We conducted an investigation of the relationship between X and Y" says the same thing as "We investigated how X and Y are related" — in more words, with less energy, and with the verb buried inside a noun phrase.

Test every -tion, -ment, -ance, -ence noun in your draft. Most can be cut by converting back to the verb.

*Noun strings.* "Student performance improvement measurement methodology" is four nouns stacked. The reader has to reassemble the relationships that the grammar has collapsed. "How we measured whether students performed better" uses more words but fewer reassembly operations.

*Unnecessary hedging.* Hedging is appropriate and required in scientific writing — claims should be scoped to the evidence. But hedging can become reflexive: every claim receives "it may be suggested that," "the data appear to indicate," "there is some evidence to suggest." A sentence that hedges a finding the data clearly supports is not more scientific — it is less accurate. The reader cannot tell whether the hedge reflects real uncertainty or a habit of verbal protection.

The rule: hedge to the degree the evidence requires. Not less, not more. "The intervention produced a significant improvement in test scores" is accurate if the data support it. "The intervention appeared to possibly contribute to a trend toward improvement in some test-score metrics" is not more careful — it is more dishonest, because it understates what the data showed.

*Vague quantification.* "Many students," "a significant number of participants," "most of the data." These are not quantitative claims. They are the shape of quantitative claims without the substance. Replace every vague quantifier with the actual number: "74 of 91 students (81%)," "63 of the 240 data points that met inclusion criteria."

---

### Precision: the right word

Precision in scientific writing means using the word that names exactly the thing you mean, not a word that is approximately right.

The most common precision failures:

**Causal vs. correlational language.** This is covered in the Statistics chapter, but it is also a prose failure. "X leads to Y," "X causes Y," "X produces Y" are causal claims. "X is associated with Y," "X predicts Y," "Y is higher when X is higher" are correlational claims. The choice of verb is the claim. An observational study that uses "causes" is not imprecise — it is wrong, at the sentence level.

**Significant.** In everyday English, "significant" means "important" or "notable." In statistics, it means "statistically distinguishable from what would be expected by chance at a specified alpha level." These are different claims. Do not write "significant improvement" when you mean "statistically significant improvement" and do not write "statistically significant" when you mean "practically important." The two can coincide or not. Specify which you mean.

**Prove.** Science does not prove. Science provides evidence that is more or less consistent with a hypothesis. "This study proves that X causes Y" is not a precision failure by convention — it is a precision failure because it is a false claim. Science accumulates evidence. It converges. It sometimes establishes something well enough that we treat it as settled. It does not prove. Use "demonstrates," "provides evidence that," "strongly suggests," "is consistent with" — appropriately calibrated to what the evidence actually shows.

**The weasel vocabulary.** "Interesting," "important," "novel," "promising," "significant" (the non-statistical sense), "valuable," "noteworthy." These words are conclusions posing as descriptions. They tell the reader what to think rather than providing the evidence that would produce the thought. Replace every evaluative word with the thing that makes it evaluative: not "this is an important finding" but "this finding has a direct implication for how clinicians currently use X protocol."

---

### Economy: no wasted words

Economy is not brevity for its own sake. It is the ratio of information to words — more information per word, not fewer words regardless of content. A long sentence that conveys a complex claim clearly is economical. A short sentence that conveys nothing is not.

The sentence-level cuts that almost always improve scientific prose:

*Cut throat-clearing.* "It is important to note that," "it should be mentioned that," "it is worth observing that." These phrases announce that you are about to say something without saying it. Cut them and say the thing.

*Cut meta-commentary on what you are doing.* "In this section, we will describe the results of our analysis." You are about to describe the results. The description will describe itself. Cut the announcement.

*Cut redundant pairs.* "Each and every participant," "null and void," "basic and fundamental." These pairs usually say one thing twice. Pick one.

*Cut filler adverbs and intensifiers.* "Clearly," "obviously," "certainly," "of course," "quite," "rather," "very," "extremely." These words claim more than they deliver. "Clearly the results indicate" does not make the indication clearer. It signals that you want the reader to agree without additional argument. Cut them.

*Cut "in order to."* It is almost always "to."

*Cut "the fact that."* It is almost always the clause that follows.

*Cut "it is" and "there are" constructions.* "There are three reasons why X is important" → "X is important for three reasons." "It is the case that students in the experimental group performed better" → "Students in the experimental group performed better."

---

### The passive voice question

Passive voice has a legitimate function in scientific writing. It allows the writer to foreground the object of the action — the thing measured, the thing studied, the result — rather than the agent doing the measuring. "Participants were recruited from three university courses" keeps the focus on participants, not on the researchers. "Blood samples were analyzed by mass spectrometry" foregrounds the analysis, not the person who ran the machine.

The problem is not passive voice. The problem is passive voice used to evade responsibility for claims and decisions. "It was determined that the sample size was adequate" hides who determined it and on what basis. "The outliers were removed from the analysis" hides who removed them and why. These are decisions that belong to specific people for specified reasons, and using the passive to remove the decision-maker is not scientific objectivity — it is the appearance of objectivity masking the absence of accountability.

The rule: use passive when the agent is irrelevant or conventional (standard lab procedures, participant selection). Use active when a decision was made that readers should be able to evaluate — methodological choices, analytical decisions, interpretive judgments.

---

### Paragraph structure for scientific prose

A scientific paragraph has one job: establish one claim and support it. If a paragraph is doing two things, split it. If a paragraph is doing nothing, cut it.

The structure most reliable for scientific writing is the same structure taught in every rhetoric textbook because it works: topic sentence, development, closure.

**Topic sentence.** The first sentence of a paragraph states the claim the paragraph will support. Not the background that leads to the claim. Not a setup that will arrive at the claim in the final sentence. The claim, stated plainly, first. Every sentence that follows should be doing work in service of this claim.

A topic sentence that merely announces the topic ("The next section discusses the results") is not a topic sentence — it is a transition. The topic sentence makes a claim: "Students in the Socratic-prompting condition retained significantly more on the two-week delayed test than students in the direct-answer condition."

**Development.** The sentences that follow the topic sentence do one of three things: they provide evidence for the claim, they explain the mechanism behind the claim, or they qualify the claim's scope. A paragraph that does only one of these is usually stronger than a paragraph that does all three badly. Know which job each sentence is doing.

**Closure.** The final sentence of a paragraph can do several things — drive home the claim, name the implication, or transition to the next paragraph's claim. What it should not do: introduce new evidence that the paragraph did not develop, or repeat the topic sentence in slightly different words.

The test for a paragraph: remove the topic sentence and ask whether the paragraph's content implies it. If yes, the paragraph is coherent. If no — if the evidence in the middle could support several different claims — the paragraph does not have a clear center, and the topic sentence is decorative rather than structural.

---

### Transitions and flow

A well-structured paper should not need explicit transitions as much as novice writers think it does. When each paragraph ends on its implication and the next paragraph opens with a claim that extends that implication, the reader moves forward naturally.

But when sections shift — from Methods to Results, from Results to Discussion, from one hypothesis to the next — the transition must name the shift explicitly. The reader needs to know: we have finished with X and are now turning to Y because of Z.

Transition sentences do three things: they close the prior unit, they name the next unit, and they explain the logical connection between them. "Having established that the experimental manipulation produced no difference in pretest scores, we now examine whether it produced differences in posttest performance" does all three. "Now we turn to the results" does only one.

The transitions most useful in scientific writing are logical, not decorative: "however" (contradiction), "therefore" (consequence), "in contrast" (comparison), "this suggests" (interpretation), "consistent with this" (corroboration), "an alternative explanation" (qualification). The decorative transitions — "furthermore," "additionally," "moreover," "in addition" — usually signal that you are adding something rather than connecting something. When you find yourself reaching for "furthermore," ask whether the next sentence is actually doing logical work that needs naming, or whether it is merely another item that you have not yet integrated.

---

### Hedging well

The epistemic requirement in scientific writing is to match the confidence of your claim to the quality of the evidence behind it. This is not optional decoration — it is accuracy. A claim that is overconfident relative to its evidence is a false claim, even if the underlying finding is real.

But hedging that has decoupled from evidence is its own failure. When every sentence is hedged to the same degree regardless of evidential status, the hedging becomes noise. The reader can no longer tell which claims are well-established and which are speculative. Everything sounds equally uncertain.

Good hedging is discriminating. Within the same paper, some claims can be stated flatly because the evidence is strong: "Students in the experimental group scored higher on the posttest, t(62) = 2.47, p = .016, d = 0.63." Other claims require hedging because they are interpretive: "This pattern suggests, though does not confirm, that the benefit of Socratic prompting operates through retrieval practice rather than through motivational mechanisms." The reader who can see both types of claim understands the paper's epistemic landscape. The reader who sees only uniformly hedged language understands nothing about where the paper stands.

The epistemic verbs to know and calibrate: *demonstrate* (strong, causal, requires experimental design), *show* (strong, requires careful handling in observational work), *indicate* (moderate, correlational is fine), *suggest* (moderate, appropriate for speculation), *appear to* (weak, appropriate for preliminary evidence or trend data), *is consistent with* (minimal — simply means the data do not contradict the hypothesis, which is not the same as supporting it).

---

### Voice and register

Scientific writing is not a single register. A methods section and a discussion section are different genres within the same paper, and they call for different voices. The methods section is procedural: past tense, often passive, impersonal, specific. The discussion section is argumentative: it takes positions, connects claims, engages with competing interpretations. A discussion section written in the voice of a methods section will be boring and will fail to argue. A methods section written in the voice of a discussion will be confusing and will fail to convey procedure.

Know which mode you are in and write accordingly. In the discussion, you are an analyst with a view. State the view. Make the argument. Engage with the evidence directly. "The most parsimonious explanation of these results is X" is a discussion sentence. "It may be possible that one interpretation could be X" is a discussion sentence that has forgotten it is allowed to argue.

---

### Checklist: prose quality review

Run this on a draft before the peer-review simulation.

*Nominalizations.* Find every -tion, -ment, -ance, -ence noun. Convert back to a verb where possible. Did the sentence improve?

*Passive voice audit.* Find every passive construction. For each: is the agent irrelevant (keep passive) or is there a decision-maker who should be named (convert to active)?

*Vague quantifiers.* Find every "many," "most," "several," "some," "a number of." Replace with the actual number or percentage.

*Hedging calibration.* Find every hedge word or phrase. For each: does the hedge match the strength of the evidence, or is it either over- or under-hedging relative to what the data shows?

*Causal language.* Find every causal verb: causes, leads to, produces, results in, drives, explains. For each: is this claim licensed by an experimental design that rules out confounds? If not, convert to correlational language.

*Evaluative adjectives.* Find every "important," "significant" (non-statistical), "notable," "interesting," "valuable." For each: replace with the claim that makes it evaluative, or cut.

*Throat-clearing.* Find every "it is important to note," "it should be mentioned," "it is worth observing." Cut them all. The important thing to note should be noted without announcing the noting.

*Topic sentence check.* For each paragraph: does the first sentence state a claim? Cover the paragraph and ask: could the topic sentence be inferred from the development? If yes, the paragraph is coherent.

---

### AI at Chapter 14

**Fog audit:** Paste a paragraph and ask: "Identify every sentence in this paragraph where the prose is making the content harder to read rather than easier. Nominalizations, unnecessary passives, vague quantifiers, throat-clearing." It is reliable at flagging these at the sentence level. Verify each flag — it will occasionally misidentify a legitimate passive or a hedged claim that is appropriately hedged. Most flags will be real.

**Nominalization hunt:** Paste a paragraph and ask: "Find every nominalization in this text — every verb that has been converted to a noun (-tion, -ment, -ance, -ence, -al endings). For each one, rewrite the sentence using the verb." Compare the revisions to the originals. Many will be better. Some will not — keep the originals where the nominalization is doing real work (naming a concept that the verb would not capture as precisely).

**Register check:** Paste a discussion section and ask: "Does this text read like a methods section — procedural, impersonal, avoiding positions — when it should be reading like an argument? Identify any sentence that is avoiding stating a position when the evidence licenses one." Discussion sections written in the voice of a methods section are a common failure, and AI catches it reliably.

**Hedging calibration:** Paste a paragraph alongside the statistical results it is describing and ask: "Is the confidence of the language in the prose paragraph matched to the strength of the evidence described? Flag any claim that is overconfident or underconfident relative to the statistics." AI cannot judge epistemic appropriateness from evidence it has not seen — you must give it both the prose and the numbers.

**Before/after revision:** Write your weakest paragraph first. Then ask AI to rewrite it eliminating fog, nominalizations, and vague quantifiers. Do not use its version — instead, use the contrast between your version and its version to find where your prose is working against your content. Revise your version in light of that contrast. The revision is yours; the comparison is the tool.



```
Ch. 1  Before You Write — Topic → Research Question → Working Hypothesis
Ch. 2  Foundation — Lock hypothesis, evaluate sources, plan design
Ch. 3  The Scientific Method — Assertion types, falsifiability, null/alternative hypothesis
Ch. 4  What Does Causal Mean, Exactly? — Counterfactuals, DAGs, Pearl's hierarchy [PLACEHOLDER]
Ch. 5  Measurement — Construct, instrument, five questions, reading prior work
Ch. 6  GIGO — Data quality check before analysis
Ch. 7  Statistics — Test selection, assumptions, power, reporting
Ch. 8  How to Design a Graph — Visual encoding, chart selection, honest figures [PLACEHOLDER]
Ch. 9  Literature Review — Synthesize, CARS framing, thesis locked
Ch. 10 Drafting — Methods → Results → Discussion → Introduction → Abstract → Title
Ch. 11 Quality Control — Claim audit, statistical integrity, style vs. logic
Ch. 12 Peer-Review Simulation — Section-by-section review before submission
Ch. 13 Ethics and Bias Screen — Disclosure, generalization, replication fitness
Ch. 14 Writing Well — Prose quality, clarity, precision, economy, flow

---

Assignment
  → Topic
  → Research Question (falsifiable, specific, answerable)
  → Working Hypothesis (testable mechanism or relationship)
  → Measurement plan: construct, instrument, five questions
  → Data quality check (GIGO)
  → Statistical plan: test, assumptions, power
  → Study Design / Evidence Plan
  → Preliminary Research
  → Working Bibliography
  → Source Evaluation (apply five questions to prior work)
  → Notes → Pattern / Gap
  → CARS framing (territory → niche → occupation)
  → Thesis locked
  → Methods drafted
  → Results drafted
  → Discussion drafted
  → Introduction drafted
  → Abstract drafted
  → Title finalized
  → Claim Audit
  → Statistical / Evidence Check
  → Citation Check
  → Revision
  → Peer-Review Simulation
  → Ethics/Bias Screen
  → Final Proofread
  → Submission
```

---

## What Kills Papers

These are the patterns that generate rejections. Know them before you draft.

**Vague hypothesis** — A topic dressed as a claim. Nothing to test against.

**Design/claim mismatch** — Correlational data making causal claims. Survey data predicting behavior. Small samples generalizing to populations.

**HARKing** — Results found first, hypothesis written to match. The paper looks confirmatory but is exploratory, without being labeled as such.

**Selective reporting** — The two significant results out of twenty tests. The studies that worked, not the ones that failed.

**Overclaiming** — "Proves," "demonstrates," "revolutionary." The gap between what the data shows and what the conclusion asserts.

**Polished prose hiding weak reasoning** — The best-written papers can be the hardest to reject when the argument does not hold. Do not let writing quality substitute for logical validity. AI makes this failure mode significantly more dangerous: it is now trivially easy to produce a paper that reads like rigorous work without being rigorous work.

**Citation monoculture** — A literature review that only cites work from one lab, one decade, or one geography. Reviewers notice.

**AI-laundered thinking** — A hypothesis generated by an AI tool, dressed in the author's voice, submitted as the author's contribution. The paper will be fluent. The claim will be untethered from any actual intellectual engagement with the problem. Reviewers who know the field will feel it even if they cannot name it.

---

## The AI Rule That Runs Through Every Phase

Effective use of AI requires metacognitive and metalinguistic skills: you must know what you are trying to say, how it might be misunderstood, and how to instruct the tool to help. For novice writers, the risk is not simply factual error or hallucination, but substituting fluency for clear thinking.

Complete the intellectual work — hypothesis, design, evidence, interpretation — before using AI tools. They are most useful at the editing stage, not the reasoning stage. Using AI to generate a hypothesis you have not thought through is like using autocomplete to decide what to argue. The words will be fluent. The thinking will not be yours.

A useful test: can you explain, in your own words and without AI assistance, every major claim in your paper, the evidence that supports it, and the reasoning that connects them? If not, the paper is not ready for submission — and no amount of AI polishing will fix that.

---

---

## Phase 5 — Figures and Data Visualization

A chart in a research paper is not decoration. It is a public visual claim subject to the same intellectual honesty standard as every other claim in the paper. A misleading figure is not an aesthetic failure — it is a scientific one.

### The question before the chart

Before building any figure, write one sentence: "After looking at this chart, the reader will be able to [specific action — rank, compare, identify, track] [specific thing] in five seconds." If you cannot write that sentence, you do not have a chart. You have a dataset and a hope.

This is Cairo's four-step framework applied to research:

1. **Key message** — what does the reader need to understand? Not "here is the data." A claim. "Intervention group recovery times were faster in every age cohort." "The correlation between X and Y is stronger in urban samples than rural ones."
2. **Data structure** — how many variables, how many observations, is there time, is there hierarchy?
3. **Functional category** — is this a comparison, a distribution, a relationship, a change over time, a part-to-whole?
4. **Specific form** — given the category, which chart?

The category determines the form. Not the data's structure, and not what you've used before. The question determines the category. The category determines the form.

### The channel hierarchy

The human visual system reads some encodings more accurately than others. William Cleveland and Robert McGill established the accuracy ranking empirically in 1984; Jeffrey Heer and Michael Bostock replicated it in 2010:

| Rank | Channel | What it's good for |
|---|---|---|
| 1 | Position along a common scale | Quantitative comparison — the bar chart's channel |
| 2 | Position along non-aligned scales | Secondary quantitative |
| 3 | Length | Quantitative, needs a baseline |
| 4 | Angle | Moderate — pie chart's channel |
| 5 | Area | Systematically underestimated |
| 6 | Color luminance | Ordered, ~7 levels reliably |
| 7 | Color hue | Category identity only — cannot be ranked |

The implication for research figures: encode your most important variable on the highest-ranked appropriate channel. If you need to show a quantitative ranking, use position (bar chart), not color. If you need to distinguish groups, use hue, not luminance. Putting a quantitative variable on a color hue channel — making some bars red and others blue to imply magnitude — is a Bertin-class encoding error. The reader cannot rank by hue.

**Magnitude channels** (position, length, area, luminance) suit quantitative or ordered data. They convey "more" and "less."

**Identity channels** (hue, shape, texture) suit categorical data. They convey "different from" but not "greater than."

The single most common encoding error in research figures: quantitative variable on a color hue channel.

### The zero baseline rule

Bar charts encode magnitude as length from a baseline. The reader's eye measures bar area swept from the baseline upward. If the baseline is not zero, the visual area encodes (value minus baseline), not value. A truncated y-axis makes a 6% difference look like a 50% difference. This is not a stylistic preference — it is a perceptual distortion that has been confirmed experimentally. Pandey and colleagues (2015) showed that subjects given truncated bar charts gave systematically inflated estimates of differences, not by small amounts but by large margins.

The rule: **zero baseline is non-negotiable for bar charts.** The bar's length is the magnitude channel. Truncating the baseline breaks the channel.

The exception: line charts use point position as the channel, not bar length. A line chart y-axis that does not start at zero is not a proportional ink violation — the channel is point position. Tight y-axis ranges are legitimate for line charts when the variation is what you are showing.

Area charts (filled regions under a line) do require a zero baseline — their channel is area, and the same rule applies.

### Chart type selection by research question

**Comparison — which groups differ, and how much?**
Horizontal bar chart, sorted by value, zero baseline. Horizontal when labels are long (more than 10–12 characters). Sorted by value, not alphabetically, unless alphabetical order is meaningful. For multiple sub-groups: grouped bars (multiset) when within-group comparison is the question; stacked bars when total + composition is the question; small multiples with shared axes when cross-group comparison is the question.

**Distribution — what is the spread of this variable?**
Histogram for overview; bin width is a design decision that changes the story (test three bin widths; bimodality that survives all three is real). Box plot for cross-group comparison of quartiles and outliers — Tukey's 1.5×IQR rule for whiskers; whiskers to data min/max is not a box plot, it is a range chart with no outlier detection. Violin plot when shape including multimodality is the question. Match the form to the audience's graphicacy: general audience gets histogram; statistically trained audience can handle box plots; visualization-trained audience can handle violin plots.

**Distribution failure:** reporting only means. Weissgerber et al. (2015) analyzed over 700 biology research papers and found that more than 88% contained bar graph errors — typically reporting means with error bars in a way that hid the underlying distribution. A bar chart of means with standard error bars can look identical for a normal distribution and a bimodal one. Show the distribution.

**Change over time — how does this variable evolve?**
Line chart. Time on the x-axis. Multiple series legible up to about five lines; more than that, consider small multiples. Do not connect discrete unrelated categories with a line — the line claims continuity between the points. If your data has gaps, mark them explicitly rather than compressing the axis. A compressed axis makes the slope appear steeper than the data supports.

**Relationship — how do two variables co-vary?**
Scatterplot. The most honest form in this book, because both channels are position — the highest accuracy available. The most morally demanding, because the visual authority of a tight cloud around an upward-sloping trend line invites the causal inference the data cannot support. **Required annotation:** a visible callout inside the chart reading "Correlation does not imply causation. These variables are associated; the causal mechanism is not established by this chart." This is not decorative. It is the annotation that completes the claim.

For large n (more than a few hundred points), overplotting hides the cloud shape. Use alpha transparency (opacity 0.1–0.3), jittering for discrete data, or 2D hexagonal binning.

Bubble charts add a third variable as circle area. The rule: encode by area, not radius. Radius-linear encoding makes a doubled value produce four times the visual area. Use `d3.scaleSqrt` or equivalent — the area must be proportional to the value.

**Part-to-whole — how do components compose a total?**
Pie chart for five or fewer categories with meaningful differences; beyond five slices, the angle channel degrades below useful. The five-slice rule traces to Cleveland and McGill's angle-perception findings. For more categories: a sorted horizontal bar chart usually communicates more accurately — the question "which category got the most?" is a comparison question, not a part-to-whole question, and comparison wants position, not angle.

### The proportional ink principle

Any visual element that represents a data value must have visual area proportional to that value. Violations:

- Truncated y-axis on bar charts (covered above)
- Radius-linear bubble encoding (see above)
- 3D bar effects: perspective foreshortening makes equal-height bars look different heights
- Polar area charts: area scales as the square of the radial length; the chart amplifies differences beyond what the data supports

Three-dimensional chart effects serve no research purpose. They distort the primary encoding channel. Remove them.

### The annotation test

Every annotation in a figure should answer a question the reader might have:
- What does this chart show? (Title)
- What unit is this? (Axis label with units)
- What is the comparison? (Subtitle naming the reference: "compared with control group," "compared with 2019 baseline")
- Why is this value unusual? (Callout on outlier)
- Where does this data come from? (Source citation)

An annotation that does not answer a question from this list is chartjunk. Remove it. The flip side: if a question from this list is unanswered, add the annotation.

Direct labels on bars, lines, or data points are almost always better than a detached legend. A legend requires two eye movements: read the element, scan to the legend, return to the element. A direct label requires zero. For seven or fewer categories, prefer direct labels.

### Color

Three distinct uses, each with its own rules:

**Categorical color:** Distinct hues for unordered groups. No implied magnitude. Maximum five to seven hues before the eye cannot distinguish reliably. Use color-blind safe palettes — approximately 8% of male readers have some form of color vision deficiency.

**Sequential color:** Single hue varying from light to dark for ordered or quantitative data. The convention: pale = low, dark = high. Reversing this without clear labeling creates confusion.

**Diverging color:** Two hues meeting at a neutral midpoint, for data with a meaningful zero or reference point (temperature anomalies above and below average; scores above and below a threshold). The midpoint must be genuinely meaningful. If your data has no meaningful midpoint, use sequential.

The error: using categorical hue (red versus blue) to imply that one group is "better" or "higher" when the channel cannot support that reading.

### The audit before submission

Before including any figure in a final submission, run this checklist:

**Text**
- Title names the finding, not the occasion ("Food Security funding exceeded all other sectors" not "Q4 Funding Summary")
- Axes labeled with units
- Data labels readable at print size
- Subtitle names the comparison ("compared with control group," "compared with prior year")

**Arrangement**
- Sort order is meaningful — by value for comparison, by time for temporal, by category when identity is the point
- Related elements grouped by proximity
- No diagonal or rotated labels where horizontal would work (horizontal bars solve this)

**Color**
- Color encodes something — not decorative
- Palette type matches data type (categorical / sequential / diverging)
- Survives grayscale reproduction
- Color-blind safe (test with a deuteranopia simulator)

**Encoding honesty**
- Zero baseline on all bar charts
- Area encoding uses square-root scaling for bubble charts
- No 3D perspective effects
- No truncated axes without explicit justification in the caption
- Line charts imply continuity — data points have a meaningful "between"

**Accessibility**
- ARIA labels if producing web figures
- Sufficient contrast between marks and background

### Common figure failures in published research

**Bar charts of means that hide distributions.** The same mean and standard error can describe a normal distribution and a bimodal one. Show violin plots, box plots, or histograms for distributions; reserve bar charts for truly single-valued summaries.

**Pie charts with more than five slices.** A twelve-category pie chart cannot be read. The reader cannot rank the middle categories. Use a sorted bar chart.

**Choropleths showing absolute counts.** A map shaded by total cases per state mostly shows where people live. Normalize to rate per 100,000 residents. Cairo's "compared with what?" check applied geographically: what is the denominator?

**Scatterplots without correlation caveats.** A strong r without the annotation invites the causal inference the chart cannot support.

**Inconsistent y-axes across panels.** If you are comparing trends across panels, the y-axes must be the same scale. Panels with different scales cannot be visually compared. Make the shared scale explicit.

**Rainbow color palettes for sequential data.** Hue has no perceptual order. A rainbow palette applied to a quantitative variable forces the reader to memorize a color-to-value mapping rather than reading the magnitude directly. Use a single-hue sequential scale.

---

*Built from: Drake & Han (2025), PLOS Computational Biology; Swales CARS framework; CRITIQ peer-review protocol; replication crisis literature; Cleveland & McGill (1984); Heer & Bostock (2010); Pandey et al. (2015); Weissgerber et al. (2015); Cairo, The Truthful Art and How Charts Lie; Tufte, The Visual Display of Quantitative Information; Few, Show Me the Numbers.*
