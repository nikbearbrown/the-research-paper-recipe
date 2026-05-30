# CAJAL Figure Intelligence — Chapter 4 — What Does Causal Mean, Exactly?

Source: chapters/04-what-does-causal-mean-exactly.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
5 figure candidates. Mechanistic density. The chapter teaches causal structure through unobservable counterfactuals and DAG topology (confounder, mediator, collider), where the structural relationships are not depictable from prose alone and demand explicit node-arrow diagrams.

## Figure 1: Potential outcomes — the unobserved branch
Priority: Critical
Trigger: VG — structural claim (one individual, two worlds, only one observable) that text cannot render concrete
Figure type: Systems diagram
Concept statement: A causal effect is the difference between two potential outcomes for the same individual, but only one is ever observed, making the counterfactual unobservable by definition.
Reader prior knowledge: Knows correlation differs from causation; new to potential-outcomes notation and the idea that the counterfactual is structurally invisible.
Source anchor: Section: "Let me make the counterfactual structure explicit"

### Block 1 — Illustrae Paste Block
Draw a flat vector diagram of a single student node on the left in blue (#56B4E9), from which two divergent solid arrows branch rightward into two stacked outcome boxes. The upper branch leads to an outcome box rendered in solid green (#009E73) representing the treated, observed world. The lower branch leads to an outcome box rendered in solid gray representing the untreated, unobserved world, drawn with a thinner 1pt outline and no fill to signal absence. Place a small bracket on the far right spanning both outcome boxes, with a short connector indicating the gap between them as the per-person causal effect. Keep all arrows single-headed, pointing left to right, 1pt strokes. Use only the blue source node, green observed outcome, gray unobserved outcome. No more than five components total: one node, two arrows, two outcome boxes, one bracket. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] One individual node; two potential-outcome boxes (observed treated, unobserved untreated); a difference bracket joining them.
[O - Organization] Individual node at left; two solid single-headed arrows diverge rightward to upper (observed) and lower (unobserved) outcome boxes; bracket at far right spans both, with a short connector marking their difference.
[P - Presentation] Flat vector, Okabe-Ito: source node #56B4E9, observed outcome #009E73, unobserved outcome neutral gray (unfilled, thin outline); 1pt strokes; no text in image.
[E - Exclusions] No second observed branch, no probability values, no equations, no axes, no legend, no shading to imply 3D, no decorative framing.

### Block 3 — Negative Prompt
double observed outcomes, equations, probability numbers, axes, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Pearl's causal hierarchy
Priority: Critical
Trigger: VG — three-level hierarchy with ascending requirements, a structural ladder not depictable from running text
Figure type: Hierarchy/taxonomy
Concept statement: Pearl's three rungs — association, intervention, counterfactual — form an ascending ladder where each higher level answers a deeper question and demands a stronger study design.
Reader prior knowledge: Understands association as covariation; less clear on how intervention and counterfactual sit above it and require progressively more.
Source anchor: Section: "Judea Pearl organized the kinds of questions"

### Block 1 — Illustrae Paste Block
Draw three horizontal bars stacked vertically as ascending rungs of a ladder, lowest at the bottom, each bar wider in conceptual height as you rise. The bottom rung is neutral gray (association). The middle rung is secondary orange (#E69F00) for intervention. The top rung is primary blue (#0072B2) for counterfactual. Place a single upward-pointing arrow on the left side spanning bottom to top to indicate increasing depth. To the right of each rung, attach a small empty placeholder box of matching outline color, suggesting a slot for the design that reaches that level. Keep three rungs, one ascent arrow, three slot boxes — seven components maximum. All strokes 1pt, single-headed arrow only. Blank unannotated flat vector on white background, no text or numbers anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] Three stacked rungs (association, intervention, counterfactual); one ascending arrow; three empty design-slot boxes.
[O - Organization] Rungs stacked vertically bottom-to-top; vertical upward arrow on the left margin; one empty slot box aligned to the right of each rung.
[P - Presentation] Flat vector, Okabe-Ito: bottom rung neutral gray, middle #E69F00, top #0072B2, slot boxes outlined to match; 1pt strokes; no text in image.
[E - Exclusions] No fourth rung, no pyramid 3D solid, no numbers, no example sentences, no axis, no legend, no shading gradients.

### Block 3 — Negative Prompt
fourth rung, pyramid 3D solid, numbers, example sentences, axes, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Confounder DAG
Priority: Critical
Trigger: VG — directed-graph topology where a third variable points into both cause and outcome; not depictable from prose
Figure type: Structural schematic
Concept statement: A confounder is a variable with arrows into both the proposed cause and the outcome, which is why the raw cause-outcome association does not isolate the cause's contribution.
Reader prior knowledge: Knows arrows mean "causes" from the chapter's DAG definition; needs to see the confounder's two outgoing arrows as the structural signature.
Source anchor: Section: "There is a tool for making the gap visible"

### Block 1 — Illustrae Paste Block
Draw a three-node directed acyclic graph. Place the cause node lower-left in blue (#56B4E9) and the outcome node lower-right in blue (#56B4E9), with a single solid arrow from cause to outcome along the bottom. Place the confounder node at top-center in secondary orange (#E69F00). Draw two solid single-headed arrows fanning down from the confounder: one to the cause node, one to the outcome node, forming a triangle. The bottom cause-to-outcome arrow is the hypothesis path; the two descending arrows are the confounding paths. Keep exactly three nodes and three arrows. All arrows single-headed pointing from cause to effect, 1pt strokes. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] Cause node, outcome node, confounder node; arrow cause→outcome; arrows confounder→cause and confounder→outcome.
[O - Organization] Cause lower-left, outcome lower-right, confounder top-center; triangular arrangement with the confounder fanning two arrows down and the base arrow running left to right.
[P - Presentation] Flat vector, Okabe-Ito: cause and outcome #56B4E9, confounder #E69F00; 1pt strokes; single-headed arrows; no text in image.
[E - Exclusions] No mediator node, no collider, no fourth variable, no dashed paths, no equations, no shading, no legend.

### Block 3 — Negative Prompt
mediator node, collider node, fourth variable, dashed paths, equations, axes, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: Mediator DAG — total vs. direct path
Priority: Important
Trigger: VG — chain topology where a node sits on the causal pathway, with a distinct direct path; structural distinction from confounder
Concept statement: A mediator lies on the causal pathway between cause and outcome, so the cause's total effect splits into an indirect route through the mediator and a residual direct route.
Figure type: Structural schematic
Reader prior knowledge: Has just seen the confounder triangle; must contrast it with a chain where the third node is downstream of the cause, not upstream of both.
Source anchor: Section: "Now introduce a second complication"

### Block 1 — Illustrae Paste Block
Draw a three-node directed graph in a horizontal chain. Place the cause node at left in blue (#56B4E9), the mediator node at top-center in green (#009E73) because it carries the active effect, and the outcome node at right in blue (#56B4E9). Draw a solid single-headed arrow from cause up to mediator, and a solid single-headed arrow from mediator down to outcome, tracing the indirect pathway through the top. Draw a second arrow directly from cause to outcome along the bottom, rendered as a distinct 1pt path to mark the direct route. The top two-arrow route is the total/indirect path; the bottom is the direct path. Keep exactly three nodes and three arrows. All arrows single-headed pointing cause to effect. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] Cause node, mediator node, outcome node; arrows cause→mediator, mediator→outcome (indirect route); arrow cause→outcome (direct route).
[O - Organization] Cause at left, outcome at right, mediator raised at top-center; two arrows form the top indirect chain, one arrow forms the bottom direct path.
[P - Presentation] Flat vector, Okabe-Ito: cause and outcome #56B4E9, mediator #009E73 (active); 1pt strokes; single-headed arrows; bottom direct path drawn as a visually distinct solid stroke; no text in image.
[E - Exclusions] No confounder node above both, no collider, no labels of "direct/total," no equations, no shading, no legend.

### Block 3 — Negative Prompt
confounder node, collider node, fourth variable, equations, axes, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 5: Collider DAG
Priority: Important
Trigger: VG — counterintuitive topology where two causes point into one downstream node; conditioning opens a spurious path
Figure type: Structural schematic
Concept statement: A collider is a variable with arrows pointing into it from two otherwise-unrelated causes, so conditioning on it opens a spurious association between those causes.
Reader prior knowledge: Has internalized that arrows mean "causes"; the collider inverts the confounder picture (arrows in, not out) and this reversal is the whole point.
Source anchor: Section: "There is a third structural element in DAGs"

### Block 1 — Illustrae Paste Block
Draw a three-node directed graph arranged as an inverted triangle. Place two cause nodes at the top, upper-left and upper-right, both in blue (#56B4E9). Place the collider node at bottom-center in blocking orange-red (#D55E00) to mark it as the dangerous node. Draw two solid single-headed arrows descending into the collider, one from each upper cause node, so both arrowheads meet at the collider — the defining signature. Add a short dashed horizontal connector between the two top nodes to suggest the spurious path that conditioning would open, drawn thinner and dashed to distinguish it from the real causal arrows. Keep exactly three nodes, two solid arrows in, and one dashed spurious connector — six components. All causal arrows single-headed. Blank unannotated flat vector on white background, no text anywhere in the image.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] Two cause nodes; one collider node; two arrows into the collider; one dashed spurious connector between the two causes.
[O - Organization] Two cause nodes across the top, collider at bottom-center; both arrows point downward into the collider; a thin dashed line links the two top nodes.
[P - Presentation] Flat vector, Okabe-Ito: cause nodes #56B4E9, collider #D55E00 (blocking); solid single-headed causal arrows at 1pt; spurious connector thin and dashed; no text in image.
[E - Exclusions] No confounder fanning out, no mediator chain, no fourth node, no arrowheads on the spurious dashed line, no equations, no shading, no legend.

### Block 3 — Negative Prompt
confounder fan-out, mediator chain, fourth node, arrowheads on the dashed connector, equations, axes, legends, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — potential outcomes: STATIC SUFFICIENT — single-state structural claim — the unobserved branch is a fixed topological fact, not a process unfolding in time.
FIGURE 2 — causal hierarchy: STATIC SUFFICIENT — taxonomy/ladder — a stable three-level classification with no temporal or animated transition.
FIGURE 3 — confounder DAG: STATIC SUFFICIENT — fixed graph topology — the confounding structure is fully legible in one frame.
FIGURE 4 — mediator DAG: VIDEO CANDIDATE — sequential path decomposition — an animation that first traces the indirect chain, then the direct path, then shows controlling-for-mediator blocking the indirect route would clarify why "more controls" harms total-effect estimation.
FIGURE 5 — collider DAG: VIDEO CANDIDATE — conditioning opens a path — animating the moment conditioning lights up the spurious dashed connector dramatizes the counterintuitive collider mechanism better than a static frame.
Recommendation: Build all five as static figures first; if production budget allows one or two animations, prioritize Figure 5 (collider conditioning) then Figure 4 (mediator path-blocking), where the harm of over-controlling is dynamic and most often misunderstood.
