# CAJAL Figure Intelligence — Chapter 6 — GIGO: Garbage In, Garbage Out

Source: chapters/06-gigo-garbage-in-garbage-out.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
4 figure candidates. Mechanistic density. The chapter turns on a process pipeline (data → cleaning → analysis), a structural missingness taxonomy, and the branching "garden of forking paths" — each a multi-step or hierarchical structure that prose alone cannot make legible.

## Figure 1: GIGO pipeline — garbage propagates
Priority: Critical
Trigger: MC — a multi-stage pipeline (raw data → cleaning → model → output) where corruption entering early survives every downstream step
Figure type: Process flowchart
Concept statement: Statistical analysis inherits the quality of the data entering it, so corruption present in the raw data propagates unchanged through cleaning and modeling into a clean-looking but untrustworthy output.
Reader prior knowledge: Thinks a clean statistical output implies clean data; needs to see corruption flowing through the pipeline intact.
Source anchor: Section: "This is the problem the acronym names"

### Block 1 — Illustrae Paste Block
Draw a left-to-right horizontal flowchart of four stages connected by single-headed arrows: a raw-data box, a cleaning box, a model box, and an output box. Render the raw-data box in blocking orange-red (#D55E00) to mark it as the corrupted source, and carry a small matching orange-red marker (a solid dot in the corner) through the cleaning, model, and output boxes to show the defect persisting unchanged downstream. Draw the three later boxes themselves in primary blue (#0072B2) so the pipeline reads as ostensibly clean while the embedded red dot signals hidden corruption. Connect the four boxes with three solid single-headed arrows pointing rightward. Keep four stage boxes, three arrows, and the carried defect marker — components within budget. 1pt strokes. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] Four pipeline stages (raw data, cleaning, model, output); a corruption marker originating in raw data and persisting in every later stage; three connecting arrows.
[O - Organization] Four boxes in a horizontal left-to-right row; three single-headed arrows between consecutive boxes; a small solid defect dot in each box from raw-data onward.
[P - Presentation] Flat vector, Okabe-Ito: raw-data box #D55E00 (corrupted source), later boxes #0072B2, defect marker dot #D55E00; arrows neutral gray; 1pt strokes; no text in image.
[E - Exclusions] No branching, no p-value numbers, no equations, no second clean pipeline for contrast, no shading, no legend.

### Block 3 — Negative Prompt
branching paths, p-value numbers, equations, second pipeline, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Missingness mechanisms — MCAR / MAR / MNAR
Priority: Critical
Trigger: VG — three structurally distinct dependency patterns (missingness depends on nothing / on observed / on the missing value itself) not depictable from prose
Figure type: Structural schematic
Concept statement: The three missingness mechanisms differ by what the probability of being missing depends on — nothing (MCAR), observed variables (MAR), or the unobserved missing value itself (MNAR) — and that dependency determines the threat.
Reader prior knowledge: Knows a blank cell means "unknown, not zero"; needs to see the three mechanisms as different arrow patterns into a missingness indicator.
Source anchor: Section: "Roderick Little and Donald Rubin introduced a taxonomy"

### Block 1 — Illustrae Paste Block
Draw three small stacked panels, one per mechanism, each containing a missingness-indicator node on the right and the same set of source nodes on the left: an observed-variable node and a missing-value node. In the top panel (MCAR), draw no arrows into the missingness indicator, leaving it isolated. In the middle panel (MAR), draw a single solid arrow from the observed-variable node into the missingness indicator. In the bottom panel (MNAR), draw a single solid arrow from the missing-value node into the missingness indicator, and render that arrow in blocking orange-red (#D55E00) to mark the dangerous dependence on the unobserved value. Use neutral gray for source nodes, primary blue (#0072B2) for the missingness indicators, and keep the observed-dependence arrow in secondary orange (#E69F00). Three panels, two source node types, the missingness indicators, and the distinguishing arrows — within budget. 1pt single-headed arrows. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] Three panels sharing an observed-variable node, a missing-value node, and a missingness-indicator node; MCAR has no incoming arrow, MAR has observed→indicator, MNAR has missing-value→indicator.
[O - Organization] Three stacked panels of identical layout; source nodes at left, missingness indicator at right; arrows present only as the mechanism dictates.
[P - Presentation] Flat vector, Okabe-Ito: source nodes neutral gray, missingness indicators #0072B2, MAR arrow #E69F00, MNAR arrow #D55E00 (dangerous); 1pt single-headed arrows; no text in image.
[E - Exclusions] No probabilities, no percentages, no fourth panel, no dataset grid, no equations, no legend, no shading.

### Block 3 — Negative Prompt
probabilities, percentages, fourth panel, dataset grids, equations, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Differential dropout by condition
Priority: Important
Trigger: PQ — a quantitative imbalance (15 of 18 missing post-tests in treatment vs. 3 in control) shown as a proportional comparison
Figure type: Statistical/quantitative
Concept statement: Missing post-tests concentrated in the treatment condition (15 vs. 3) are not clerical noise but evidence of MNAR dropout that biases the apparent treatment effect.
Reader prior knowledge: Has the worked example's numbers; a bar comparison makes the lopsidedness immediate.
Source anchor: Section: "The missing post-tests concentrated in the treatment group"

### Block 1 — Illustrae Paste Block
Draw a simple two-bar chart with a vertical count axis beginning at zero and a horizontal axis with two categories: treatment and control. Draw the treatment bar tall, representing fifteen missing post-tests, in blocking orange-red (#D55E00). Draw the control bar short, representing three missing post-tests, in primary blue (#0072B2). The treatment bar should be five times the height of the control bar to preserve true proportion, with the vertical axis starting at zero so the visual ratio is honest. Keep two bars, one vertical axis, one horizontal baseline — four components. 1pt strokes. Blank unannotated flat vector on white background, no numerals or text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated; vertical axis from zero.
[C - Content] Two bars comparing missing-post-test counts: treatment (tall, 15) and control (short, 3); vertical count axis from zero.
[O - Organization] Two vertical bars side by side on a shared zero baseline; treatment bar five times the height of the control bar.
[P - Presentation] Flat vector, Okabe-Ito: treatment bar #D55E00 (the concerning group), control bar #0072B2, axes neutral gray; 1pt strokes; no numerals or text in image.
[E - Exclusions] No axis numbers, no data labels, no third bar, no percentage, no legend, no gridlines, no truncated axis.

### Block 3 — Negative Prompt
axis numbers, data labels, third bar, percentage figures, legends, gridlines, truncated axis, equations, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: The garden of forking paths
Priority: Critical
Trigger: MC — a branching decision tree where each analytic choice multiplies the possible results, an inherently multi-step structure
Figure type: Process flowchart
Concept statement: Between collected data and reported result lies a tree of defensible analytic choices, and choosing among them after seeing the data multiplies possible "results" and breaks the calibration of p-values.
Reader prior knowledge: Understands that analysis involves choices; needs to see how a single dataset fans out into many possible reported results.
Source anchor: Section: "Andrew Gelman and Eric Loken described"

### Block 1 — Illustrae Paste Block
Draw a left-to-right branching tree starting from a single root node on the left representing the collected dataset, drawn in primary blue (#0072B2). From the root, draw solid single-headed arrows branching to two nodes at the first decision point (an outlier-rule choice). From each of those, branch again at a second decision point (a covariate-set choice), and once more at a third (an outcome-measure choice), so the tree widens left to right into several terminal nodes on the right edge. Render the terminal result nodes in secondary orange (#E69F00) to mark the many possible reported outcomes from one dataset. Keep the structure to three decision levels and no more than six terminal nodes, with branching arrows single-headed throughout. 1pt strokes. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] One root dataset node; three successive binary decision levels (outlier rule, covariate set, outcome measure); multiple terminal result nodes.
[O - Organization] Root at left; arrows branch rightward through three decision levels; terminal result nodes along the right edge (cap at six).
[P - Presentation] Flat vector, Okabe-Ito: root node #0072B2, intermediate branch nodes neutral gray, terminal result nodes #E69F00; single-headed branching arrows at 1pt; no text in image.
[E - Exclusions] No p-value numbers, no probabilities, no more than three decision levels, no looping arrows, no shading, no legend.

### Block 3 — Negative Prompt
p-value numbers, probabilities, extra decision levels, looping arrows, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — GIGO pipeline: VIDEO CANDIDATE — propagation over stages — animating the corruption marker traveling intact from raw data through to the clean-looking output makes the "garbage survives the pipeline" point vivid, though a static carried-defect marker also works.
FIGURE 2 — missingness mechanisms: STATIC SUFFICIENT — three fixed dependency structures — the arrow-pattern contrast reads in one frame.
FIGURE 3 — differential dropout: STATIC SUFFICIENT — single quantitative comparison — two bars need no motion.
FIGURE 4 — garden of forking paths: VIDEO CANDIDATE — combinatorial fan-out — animating the tree branching level by level, multiplying terminal results from one dataset, dramatizes how unconstrained choices inflate possible outcomes.
Recommendation: Produce all four as static figures; if animation budget exists, prioritize Figure 4 (forking paths branching) where the multiplying-results idea is intrinsically dynamic, then Figure 1 (defect propagation).
