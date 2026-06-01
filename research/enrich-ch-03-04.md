# Verify-and-Enrich — Chapters 3 & 4 (Deck Module 2, slides 5–9)

Scope: assertion taxonomy; falsifiability (Popper); null vs. alternative; match-design-to-claim; causal inference. Fact-checking + source enrichment only — not a rewrite. Every citation below was checked against a primary or authoritative secondary source; anything not confirmable is marked **unverified**.

---

## Chapter 3 — The Scientific Method: Assertions and How to Test Them

### Verified

- **Popper's falsifiability / asymmetry.** The chapter's core formulation — "a claim that can accommodate any possible evidence is not an empirical claim at all," and "name, in advance, what you would need to see for your claim to be in trouble" — is a faithful rendering of Popper. The key logical engine is the **asymmetry between verifiability and falsifiability**: universal statements can never be derived from singular observation statements but *can* be contradicted by a single one. Falsifiability is Popper's **demarcation** criterion between science and non-science. Source: K. Popper, *The Logic of Scientific Discovery* (orig. *Logik der Forschung*, Vienna, 1934; English ed., Hutchinson, 1959). The chapter wisely avoids dating Popper; if a date is ever added, use **1934 (German)** / **1959 (English)**, not a single year.

- **Neyman–Pearson framing of hypothesis testing.** The chapter's attribution — "Jerzy Neyman and Egon Pearson formalized statistical hypothesis testing in the 1930s as a decision procedure" — is correct. Their landmark paper is **Neyman, J. & Pearson, E. S. (1933). "On the problem of the most efficient tests of statistical hypotheses." *Philosophical Transactions of the Royal Society A*, 231, 289–337.** The "decision procedure" / explicit-alternative-hypothesis / Type-I-vs-Type-II framing the chapter uses is exactly the N-P innovation (Fisher's significance testing had no explicit alternative). The chapter's careful phrasing "a significant p-value does not confirm the alternative" and "the null is a specific quantitative claim, not 'nothing is happening'" are both standard and correct.

- **The is/ought basis for the normative row.** The chapter's claim that normative ("should") statements "cannot be settled by data alone" and require "a value judgment … separate from the empirical evidence" is the **is–ought problem**, first articulated by **David Hume, *A Treatise of Human Nature* (1739–40), Book III, Part I, §1** ("no ought from an is"). The closely related **naturalistic fallacy** is **G. E. Moore, *Principia Ethica* (1903)**. The chapter's treatment is philosophically sound; it just never names Hume (see "Deck beats / New to add").

- **Assertion taxonomy.** The seven-type taxonomy (descriptive / correlational / causal / predictive / mechanistic / normative / conceptual) is the author's own pedagogical synthesis rather than a citable named framework, and that's fine — each type's evidentiary burden is described correctly. The "verb chooses the burden of proof" framing is the chapter's signature move and is internally consistent.

### Corrections

- **No factual errors found.** One precision note, not an error: the chapter says Neyman–Pearson formalized testing "as a decision procedure" — accurate, but worth knowing that the *p-value as evidence-against-null* idea is Fisher's, and the apparatus most papers actually use is a hybrid ("NHST") that neither Fisher nor Neyman–Pearson would fully endorse. If the chapter ever wants to be bulletproof on the history, a one-clause acknowledgment that "the null hypothesis" as an evidential concept traces to Fisher while the *accept/reject decision* framing is Neyman–Pearson would prevent a knowledgeable reader's quibble. Not required.

### New to add (full citations)

1. **Lakens, D. (2017). "Equivalence Tests: A Practical Primer for t Tests, Correlations, and Meta-Analyses." *Social Psychological and Personality Science*, 8(4), 355–362.** https://doi.org/10.1177/1948550617697177 — Directly operationalizes the chapter's "failing to reject ≠ proof of the null" point. The TOST (two one-sided tests) procedure lets a researcher make a *positive* claim that an effect is absent (within bounds), instead of mistaking a non-significant result for "no effect." This is the modern, citable answer to the deck's underpowered-null warning.

2. **Altman, D. G. & Bland, J. M. (1995). "Statistics notes: Absence of evidence is not evidence of absence." *BMJ*, 311(7003), 485.** https://doi.org/10.1136/bmj.311.7003.485 — The canonical one-page source for the exact distinction the chapter makes in the null-hypothesis section: a non-significant ("negative") study shows *absence of evidence of a difference*, not *evidence of no difference*, and is usually a power problem. Highly quotable, primary, short.

3. **Hume, D. (1739–40). *A Treatise of Human Nature*, Book III, Part I, §1** — for the is/ought row. Pair with **Moore, G. E. (1903). *Principia Ethica*** (naturalistic fallacy) if the author wants the historical anchor.

### Deck beats to fold in

- The deck's **Cartesian falsification prompt** — *"what would I have to observe to conclude this is wrong?"* — is sharper than the chapter's longer prose version. It's a single memorable question the reader can apply to any sentence; worth surfacing verbatim as a callout.
- The deck's **"sponge that absorbs everything proves nothing"** metaphor is more vivid than the chapter's "noise that sounds like a claim." Either works; the sponge is more portable.
- The deck explicitly frames **H₀ as a baseline, not "nothing,"** which the chapter does cover well (point two of the three). The chapter is already at parity here.

---

## Chapter 4 — What Does Causal Mean, Exactly?

### Verified

- **Potential outcomes / Rubin / fundamental problem of causal inference.** The chapter's counterfactual machinery (Y₁ vs. Y₀ for the same unit, only one ever observed) is exactly right. Attribution: the **potential outcomes** model is **Rubin, D. B. (1974). "Estimating causal effects of treatments in randomized and nonrandomized studies." *Journal of Educational Psychology*, 66(5), 688–701.** The phrase **"fundamental problem of causal inference"** — which the chapter uses — was coined by **Holland, P. W. (1986). "Statistics and causal inference." *Journal of the American Statistical Association*, 81(396), 945–960**, who also named it the "Rubin Causal Model." The chapter attributes potential outcomes to Rubin correctly; if it ever wants to cite the "fundamental problem" phrase by name, the citation is Holland 1986, not Rubin.

- **Pearl's ladder of causation (three rungs).** The chapter's three levels — **association → intervention → counterfactual** ("seeing / doing / imagining") — match Pearl exactly, including the example questions. Source: **Pearl, J. & Mackenzie, D. (2018). *The Book of Why: The New Science of Cause and Effect*. Basic Books.** The chapter's deeper claim — "causal inference is never purely statistical … requires assumptions about the data-generating process" — is Pearl's central thesis, verbatim in spirit ("causation is … an addition to statistics, an enrichment").

- **DAGs, confounder, mediator, collider.** All four structural definitions are correct:
  - *Confounder* = common cause of treatment and outcome (control for it). ✓
  - *Mediator* = on the causal path; controlling for it blocks the effect you want when estimating a total effect. ✓
  - *Collider* = common effect of two variables; **conditioning on a collider induces a spurious association** between its causes (collider/selection bias). ✓ This is standard Pearl d-separation and is correctly stated, including the selection-bias and "only-completers" examples.
  - The chapter's warning that "you cannot decide what to control for by looking at what's associated with your variables" is the correct, non-obvious lesson and is well-supported.

- **DAGs encode assumptions, not evidence.** The chapter's honesty here ("a DAG is a map of your assumptions, not evidence for them") is exactly the orthodox position and a strength.

### Corrections

- **No factual errors found.** Minor refinements only:
  - "This is Rubin's potential outcomes framework" is correct, but the field also calls it the **Neyman–Rubin** model — Neyman introduced potential-outcomes notation for randomized experiments in **1923** (Polish; trans. *Statistical Science* 1990). Not necessary to add, but it pre-empts a specialist's objection if the author ever wants the fuller lineage.
  - The chapter says RCTs "are built to answer" the intervention question — accurate. The deck's stronger claim that there is **"no statistical workaround"** for a weak design is well-supported by Pearl (you cannot climb the ladder with cleverer statistics on rung-1 data) and could be folded in explicitly.

### New to add (full citations)

1. **Pearl, J. & Mackenzie, D. (2018). *The Book of Why: The New Science of Cause and Effect*. New York: Basic Books.** — Already implicitly the chapter's backbone (ladder of causation); it should be cited by name. This is the accessible, current, primary popularization of everything the chapter teaches.

2. **Hernán, M. A. & Robins, J. M. (2020). *Causal Inference: What If*. Boca Raton: Chapman & Hall/CRC.** (Free full text: https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) — The current standard graduate text; rigorous treatment of confounding, colliders/selection bias, and identification. The ideal "go deeper" reference for the DAG sections.

3. **Cunningham, S. (2021). *Causal Inference: The Mixtape*. New Haven: Yale University Press.** (Free: https://mixtape.scunning.com) — The modern, approachable bridge to the **quasi-experimental** toolkit the chapter currently only gestures at (random assignment / natural experiment / instrumental variable). Covers DiD, RDD, IV, matching with worked code.

4. *(For the design hierarchy)* **Angrist, J. D. & Pischke, J.-S. (2009). *Mostly Harmless Econometrics: An Empiricist's Companion*. Princeton University Press.** — The canonical reference that natural experiments, IV, DiD, and RDD are the strong quasi-experimental designs that *approximate* randomization. Supports the deck's "causal → RCT or strong quasi-experiment" hierarchy with named methods.

5. *(Optional, for the older causal-criteria tradition)* **Hill, A. B. (1965). "The Environment and Disease: Association or Causation?" *Proceedings of the Royal Society of Medicine*, 58(5), 295–300.** — Hill's **nine "viewpoints"** (strength, consistency, specificity, temporality, biological gradient, plausibility, coherence, experiment, analogy). Worth a footnote *with the caveat Hill himself gave*: these are "viewpoints," **not a checklist** and **none is a sine qua non**. Useful as the pre-Pearl, observational-era approach to causation, and a good contrast: Hill = heuristics for *when to believe* observational association; Pearl/Rubin = formal machinery for *what causation means*.

### Deck beats to fold in

- The deck's blunt line — **"causal → randomized or strong quasi-experiment; no statistical workaround"** — is crisper and more actionable than the chapter's prose, and it directly closes the chapter's open gesture toward "an instrumental variable that predicts tutor use but doesn't independently affect scores." The chapter names IV and natural experiments once but never the toolkit; the deck's framing plus a one-line roster (DiD, RDD, IV) would let the chapter deliver on its own promise.
- The deck's **match-design-to-claim** principle is the operational twin of the chapter's "the verb 'caused' is a commitment to a counterfactual comparison your design either supports or doesn't." They reinforce each other; the deck's version is the rule, the chapter's is the rationale.

---

## Citations consolidated (all verified)

- Popper, K. *The Logic of Scientific Discovery*. 1934 (German) / 1959 (English), Hutchinson. https://en.wikipedia.org/wiki/The_Logic_of_Scientific_Discovery
- Neyman, J. & Pearson, E. S. (1933). *Phil. Trans. R. Soc. A* 231:289–337.
- Hume, D. *A Treatise of Human Nature* (1739–40), Bk III, Pt I, §1; Moore, G. E. *Principia Ethica* (1903).
- Rubin, D. B. (1974). *J. Educ. Psychol.* 66(5):688–701; Holland, P. W. (1986). *JASA* 81(396):945–960.
- Pearl, J. & Mackenzie, D. (2018). *The Book of Why*. Basic Books. https://en.wikipedia.org/wiki/The_Book_of_Why
- Hernán, M. A. & Robins, J. M. (2020). *Causal Inference: What If*. CRC. https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/
- Cunningham, S. (2021). *Causal Inference: The Mixtape*. Yale UP. https://mixtape.scunning.com
- Angrist, J. D. & Pischke, J.-S. (2009). *Mostly Harmless Econometrics*. Princeton UP.
- Hill, A. B. (1965). *Proc. R. Soc. Med.* 58(5):295–300.
- Lakens, D. (2017). *Soc. Psychol. Personal. Sci.* 8(4):355–362. https://doi.org/10.1177/1948550617697177
- Altman, D. G. & Bland, J. M. (1995). *BMJ* 311(7003):485. https://doi.org/10.1136/bmj.311.7003.485
