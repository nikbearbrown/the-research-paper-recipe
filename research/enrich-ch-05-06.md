# Enrichment & verification — Ch.05 (Measurement) and Ch.06 (GIGO)

Verify-and-enrich pass. Scope = deck Module 3 (slides 10–14) + start of Module 4 (GIGO). Fact-checking and source-finding only; not a rewrite. Citations below are verified against primary/secondary sources unless explicitly marked "unverified."

---

## Chapter 05 — Measurement

### Verified

- **Bjork storage strength vs. retrieval strength / New Theory of Disuse.** Correctly attributed and correctly characterized. The distinction comes from Robert A. Bjork & Elizabeth L. Bjork (1992), "A new theory of disuse and an old theory of stimulus fluctuation." Storage strength = how durably encoded; retrieval strength = how accessible right now. Retrieval strength rises and falls with use/cues/time; storage strength accrues and is far more permanent. The chapter's claim that the two "can be dissociated" and that immediate performance can mislead about durable learning is exactly the theory's central point. VERIFIED.
- **"Desirable difficulties" framework.** Coined by R. A. Bjork; spacing, interleaving, and retrieval practice feel harder but produce better durable retention. Chapter does not over-claim here. VERIFIED.
- **Massed vs. spaced retention pattern** ("massed = high immediate / low durable; spaced = lower immediate / higher durable"). This is the standard, well-replicated spacing-effect pattern. VERIFIED (see meta-analyses under New to add).
- **Construct vs. instrument; validity as the strength of the inference from observed score to unobserved construct.** Standard and correct. Originates with Cronbach & Meehl (1955), who introduced the term "construct validity." VERIFIED.
- **Messick: validity is a property of the interpretation and use of scores, not of the instrument.** Correctly attributed to Samuel Messick. This is the core of his unified-validity argument (Messick 1989, in Linn ed., *Educational Measurement* 3rd ed.; also Messick 1995, *American Psychologist*). The chapter's phrasing ("a test is not valid or invalid in the abstract; its scores are valid for some interpretations and uses and not others") is an accurate summary. VERIFIED.
- **Reliability ≠ validity; reliability necessary but not sufficient; the consistently-4-degrees-too-high thermometer.** Standard measurement theory, correctly stated. The thermometer/biased-instrument analogy is a textbook example of reliable-but-not-valid. VERIFIED.
- **Population as a constraint on generalizability; "students" means the participants who participated.** Sound; consistent with sampling-inference logic. VERIFIED (conceptual, not a single-source claim).
- **Fifth question (what a null result would look like) framed as "Popper's question applied to measurement."** Internally consistent with the book's Module 2 falsifiability material. Reasonable framing, not a citable factual claim. OK.

### Corrections

- **No factual errors found in Ch.05.** One precision note (not an error): the chapter dates Bjork's framework only by name ("Robert Bjork's work on desirable difficulties"). If a date/citation is wanted in-text, the storage/retrieval-strength distinction should be pinned to **Bjork & Bjork (1992)**, and note it is *Robert and Elizabeth* Bjork jointly — the deck and chapter both name only Robert, which under-credits Elizabeth L. Bjork, a co-originator. Worth a parenthetical.
- **Minor attribution nuance:** "validated instrument" critique is Messick's, but the modern operational form is **Kane's argument-based validation** and the **2014 Standards** definition (validity = degree to which evidence supports interpretations of scores *for proposed uses*). Not a correction to anything written, but the chapter currently rests entirely on Messick when a one-line update to Kane/Standards would make it current (see New to add).

### New to add (full citations)

1. **Bjork, R. A., & Bjork, E. L. (1992). A new theory of disuse and an old theory of stimulus fluctuation.** In A. F. Healy, S. M. Kosslyn, & R. M. Shiffrin (Eds.), *From Learning Processes to Cognitive Processes: Essays in Honor of William K. Estes* (Vol. 2, pp. 35–67). Hillsdale, NJ: Erlbaum. — The primary source for storage strength vs. retrieval strength. (ResearchGate copy: https://www.researchgate.net/publication/281322665) Use this as the load-bearing citation for the timescale question.
2. **Latimier, A., Peyre, H., & Ramus, F. (2021). A meta-analytic review of the benefit of spacing out retrieval practice episodes on retention.** *Educational Psychology Review*, 33, 959–987. https://doi.org/10.1007/s10648-020-09572-8 — Recent, strong quantitative confirmation: spaced > massed retrieval practice on final retention, **g ≈ 0.74**. Exactly the "delayed-measure" evidence the chapter argues for. Verified venue and effect size.
3. **Kane, M. T. (2013). Validating the interpretations and uses of test scores.** *Journal of Educational Measurement*, 50(1), 1–73. https://doi.org/10.1111/jedm.12000 — The modern operationalization of Messick: validity as an *interpretation/use argument*. Pairs naturally with the chapter's "you have to argue the interpretation" move. Verified.
4. **AERA, APA & NCME (2014). *Standards for Educational and Psychological Testing*.** Washington, DC: AERA. — Current authoritative definition: validity = "the degree to which evidence and theory support the interpretations of test scores for proposed uses" (p. 11). One sentence makes the Messick framing current. Verified (definition widely quoted).

(Optional, secondary) Cronbach, L. J., & Meehl, P. E. (1955). Construct validity in psychological tests. *Psychological Bulletin*, 52(4), 281–302. — Origin of "construct validity"; useful as the historical anchor if the chapter wants to date the construct/instrument distinction. Verified (PsycNET 1956-03730-001; PMID 13245896).

### Deck beats to fold in

- **The measurement hierarchy** (hypothesis → design → data → interpretation; an upstream flaw corrupts everything downstream). The deck states this explicitly as the *frame* for Module 3; Ch.05 implies it but never states the hierarchy as a sequence. Adding one sentence ("a flaw upstream corrupts everything downstream") would tie Ch.05 to the GIGO logic of Ch.06 and is sharper in the deck.
- **Plato's cave / "the score is not the student."** The deck uses these two images for the measure–construct gap; the chapter has the concept but neither image. The "score is not the student" line is a crisp, citable-as-aphorism way to open the construct/instrument section. Deck is sharper here.
- **"Alignment" as a named third leg** alongside validity/reliability. The deck lists "validity / reliability / alignment"; the chapter folds alignment into the first measurement question but doesn't name it as a peer concept. Minor — the chapter's treatment is arguably more careful.

---

## Chapter 06 — GIGO: Garbage In, Garbage Out

### Verified

- **GIGO as an epistemic rule, not a slogan about computers; the GIGO check happens before any statistical test.** Sound framing, matches the deck. The claim that precise SEs/CIs can faithfully describe a corrupted dataset is correct and well put. VERIFIED (conceptual).
- **Little & Rubin missingness taxonomy (MCAR / MAR / MNAR), correctly attributed.** Roderick Little and Donald Rubin. The classification originates with **Rubin (1976)**, *Biometrika*, and is developed in **Little & Rubin's** book. Chapter's definitions are accurate:
  - MCAR — missingness independent of all variables, observed or not; complete cases are a random subset. VERIFIED.
  - MAR — missingness depends on *observed* variables but not on the missing value once those are accounted for; addressable by multiple imputation; the assumption is not directly testable. VERIFIED — this last point (MAR vs. MNAR is empirically unverifiable) is correct and important; the chapter states it accurately.
  - MNAR — missingness depends on the unobserved value itself; not fixable by imputation; imputation will be systematically optimistic. VERIFIED. The chapter's reasoning about why imputation fails under MNAR (the info that would correct the imputation is the missing info) is correct.
- **Differential dropout concentrated in the treatment group → MNAR-consistent, biases the effect upward.** Correct interpretation. The chapter is careful to say "consistent with MNAR" rather than "is MNAR," which is the right epistemic hedge (you cannot prove MNAR from the data). VERIFIED.
- **Impossible/out-of-range values; range checks.** Standard data-cleaning, correct. VERIFIED.
- **Composite scale failure / internal consistency via Cronbach's alpha; rough 0.7 threshold "not sacred."** Correct, and the hedge ("the threshold is not sacred") is appropriate — see correction below for a stronger version. VERIFIED with caveat.
- **Garden of forking paths, attributed to Andrew Gelman and Eric Loken.** Correct. The chapter's key claim — that the problem arises *even without conscious p-hacking and even when the hypothesis was posited in advance* — is precisely Gelman & Loken's thesis. VERIFIED.
- **p-value interpretation conditional on a pre-specified analysis** ("a p of 0.04 assumes the analysis was specified before the data were examined; if adjusted to fit the data, that probability doesn't apply"). Correct and well-stated. VERIFIED.
- **Preregistration as the remedy; transparency as the fallback for non-preregistered studies.** Standard open-science guidance, correctly stated. VERIFIED.

### Corrections

- **Cronbach's alpha — under-hedged on the methodological point, though not wrong.** The chapter treats low alpha as the signal that items aren't a coherent construct, which is fine as a teaching heuristic. But there is now strong consensus that alpha is the *wrong default* reliability estimate: it assumes tau-equivalence (all items load equally) and unidimensionality, and **coefficient omega (ω)** is generally preferred. The chapter need not change its argument, but a one-line footnote acknowledging omega would prevent a methods-literate reader from flagging the chapter as dated. NOT AN ERROR — a currency gap. (See New to add #3.)
- **Attribution precision on MCAR/MNAR terms.** The chapter says Little and Rubin "introduced" the taxonomy. Strictly, **Rubin (1976) introduced "MAR"** (and "observed at random"); the now-standard three-way MCAR/MAR/MNAR labeling was consolidated in **Little & Rubin's** book. Calling it "Little and Rubin's taxonomy" is the conventional and acceptable usage, but if precision is wanted, cite Rubin 1976 for the formal origin and Little & Rubin for the standard three-category framing. Minor.
- **No numerical or factual errors found** in the worked example (18 missing, 15 treatment / 3 control; alpha 0.41 example). These are illustrative and internally consistent.

### New to add (full citations)

1. **Rubin, D. B. (1976). Inference and missing data.** *Biometrika*, 63(3), 581–592. https://doi.org/10.1093/biomet/63.3.581 — Primary source for the missingness framework. The chapter currently cites no source for the taxonomy; this is the one to anchor it.
2. **Little, R. J. A., & Rubin, D. B. (2019). *Statistical Analysis with Missing Data* (3rd ed.).** Hoboken, NJ: Wiley. https://doi.org/10.1002/9781119482260 — The standard reference; consolidates MCAR/MAR/MNAR and multiple imputation. (Little & Rubin received the ISI Karl Pearson Prize, 2017, for this line of work.) Verified.
3. **Flora, D. B. (2020). Your coefficient alpha is probably wrong, but which coefficient omega is right? A tutorial on using R to obtain better reliability estimates.** *Advances in Methods and Practices in Psychological Science*, 3(4), 484–501. https://doi.org/10.1177/2515245920951747 — Accessible, citable basis for the "prefer omega over alpha" footnote. Verified. (Companion: McNeish, D. (2018). Thanks coefficient alpha, we'll take it from here. *Psychological Methods*, 23(3), 412–433. https://doi.org/10.1037/met0000144 — the more-cited polemic; verified.)
4. **Gelman, A., & Loken, E. (2014). The statistical crisis in science.** *American Scientist*, 102(6), 460–465. https://doi.org/10.1511/2014.111.460 — The published, citable version of the garden-of-forking-paths argument (the widely-circulated 2013 piece is the unpublished working paper). Use the 2014 *American Scientist* cite for the chapter. Verified.

(Optional, for outlier handling — the deck's "inconsistent outlier handling" failure mode) **André, Q. (2022/2024). Outlier exclusion procedures must be blind to the researcher's hypothesis.** *Journal of Experimental Psychology: General.* — Direct, citable support for the chapter's forking-paths point as applied specifically to outlier rules: exclusion rules chosen after seeing results inflate Type I error; blind/pre-specified rules are the fix. Mark **unverified on exact year/volume** (search confirmed the paper and its thesis but not full pagination). Also relevant: Leys et al. and the *International Review of Social Psychology* outlier-detection-with-preregistration guidance.

### Deck beats to fold in

- **The five named pre-analysis failure modes.** The deck enumerates them crisply: (1) measurement error, (2) systematic bias, (3) non-random missingness, (4) inconsistent outlier handling, (5) unreliable composites. The chapter covers 3 (missingness), 5 (composites), impossible values, and coding inconsistency — but does **not** name "outlier handling" as its own failure mode outside the forking-paths section, and "systematic bias" / "measurement error" are not listed as a discrete pair. The deck's five-item list is sharper as a scannable taxonomy; folding it in (e.g., in the planned failure-types table) would make the chapter's coverage map cleanly onto the deck.
- **"Sophisticated analysis of bad data → confident-looking bad results."** The chapter has this exact idea ("polished-looking output from deeply corrupted inputs") — well-matched, no gap.
- **"The GIGO check happens before any statistical test."** The deck states the *ordering* explicitly as a rule; the chapter's closing ("the question to ask before beginning analysis…") makes the same point. Equivalent; deck is marginally more quotable.

---

## Notes on what could NOT be verified
- The Aczel/André outlier-blinding paper's exact bibliographic details (year/volume/pages) are **unverified**; the thesis is confirmed by multiple secondary sources. Verify before citing.
- All other citations above were confirmed against primary records (DOIs, PsycNET/PubMed IDs, or publisher pages). No fabricated citations.
