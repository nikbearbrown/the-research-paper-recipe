# CAJAL Figure Intelligence — Chapter 12 — Peer-Review Simulation

Source: chapters/12-peer-review-simulation.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
4 figure candidates. Mechanistic density. The chapter is procedural: a targeted-prompt structure, a triage routing, the cross-section consistency check, and the generic-versus-adversarial contrast — each a multi-part relationship the prose specifies but does not let the reader hold at once.

## Figure 1: Generic review vs. adversarial simulation
Priority: Critical
Trigger: VG — the chapter's thesis is a structural contrast between what generic review catches and what adversarial review targets, not depictable from running text
Figure type: Comparison panels (surface vs. depth)
Concept statement: Generic review rewards easily detected surface qualities and misses claim-evidence-frame alignment; adversarial simulation targets exactly the structural mismatches that surface review skips.
Reader prior knowledge: Has the Lina anecdote; needs the two review modes set against the same paper to see what each reaches.
Source anchor: Section: "The problem with Lina's AI review..." and "Peer review is adversarial in the right way..."

### Block 1 — Illustrae Paste Block
Draw two stacked horizontal bands on white representing one paper, each band a row of the same four target rounded rectangles left to right: fluency, organization, completeness, and claim-evidence-frame alignment. The top band is the generic review: color fluency, organization, and completeness boxes secondary orange #E69F00 (reached), and the alignment box neutral gray with no arrow reaching it (missed). The bottom band is the adversarial simulation: color the alignment box active green #009E73 (reached and central) with a single-headed gray arrow pointing directly into it, and render the other three boxes neutral gray to show they are de-prioritized. Add one blocking-vermilion #D55E00 marker on the top band's untouched alignment box to flag the missed fatal target. Align the four box columns across both bands. Flat unannotated vector, 1pt strokes, white, no text — which box each mode reaches, and the vermilion miss marker, encode the contrast.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Same four review-target boxes shown twice: generic mode reaching three surface targets and missing alignment; adversarial mode reaching alignment.
[O - Organization] Two stacked bands with four aligned columns; arrows showing each mode's reached targets; a vermilion marker on the missed alignment box in the generic band.
[P - Presentation] Flat vector, Okabe-Ito: secondary orange #E69F00 surface targets reached by generic review, active green #009E73 alignment target reached by adversarial review, neutral gray de-prioritized boxes and arrows, blocking vermilion #D55E00 missed-target marker; 1pt strokes; no text in image.
[E - Exclusions] No target names, no person figures, no speech bubbles, no third band, no curved arrows, no shading.

### Block 3 — Negative Prompt
No target labels, no reviewer or person figures, no speech bubbles, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Cross-section consistency check
Priority: Critical
Trigger: VG — the Introduction-Results-Discussion alignment check is a structural relationship (same question across three sections) whose failure mode is a drift the prose cannot show at a glance
Figure type: Systems diagram (alignment vs. drift)
Concept statement: In a sound paper the Introduction's question, the Results' test, and the Discussion's interpretation all refer to one question; drift between them is a Critical issue where the paper answers a question it did not ask.
Reader prior knowledge: Knows the three sections; the Lina case primes them; needs the shared-question axis made visible.
Source anchor: Section: "Does the Discussion answer the research question the Introduction asks?"

### Block 1 — Illustrae Paste Block
Draw two stacked rows on white, each row three rounded rectangles left to right: Introduction, Results, Discussion. In the top row (aligned), draw a single horizontal dashed gray guideline passing through the vertical center of all three boxes, and color all three boxes active green #009E73 to read as referring to one shared question. Connect them left to right with single-headed gray arrows. In the bottom row (drift), color Introduction primary blue #0072B2 and Discussion blocking vermilion #D55E00, with Results neutral gray between them; offset the Discussion box vertically off the dashed guideline so it visibly leaves the shared axis, and draw a short vermilion divergence arrow marking the gap between the guideline and the Discussion box. Keep the three columns aligned across both rows. Flat unannotated vector, 1pt strokes, white, no text — the shared guideline plus the off-axis vermilion box encode alignment versus drift.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Introduction-Results-Discussion shown twice: an aligned row on a shared dashed question-axis, and a drift row where Discussion leaves the axis.
[O - Organization] Two stacked three-box rows with aligned columns; a dashed horizontal guideline through both rows; a divergence arrow marking the Discussion's offset in the drift row.
[P - Presentation] Flat vector, Okabe-Ito: active green #009E73 for the aligned trio, primary blue #0072B2 Introduction and blocking vermilion #D55E00 Discussion in the drift row, neutral gray Results, arrows, and dashed guideline; 1pt strokes; no text in image.
[E - Exclusions] No section names, no question text, no third row, no curved arrows, no icons, no shading gradients.

### Block 3 — Negative Prompt
No section labels, no question text, no icons, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Comment triage routing
Priority: Important
Trigger: MC — each simulated comment is sorted on two axes (valid/invalid, serious/minor) into four routes, a multi-step decision process
Figure type: Conceptual map (2x2 routing quadrants)
Concept statement: Each simulated review comment is triaged by validity and seriousness into one of four actions — fix now, fix if time allows, improve the explanation, or discard with a stated reason.
Reader prior knowledge: Knows reviews produce many comments; needs the two-axis sort and the four destinations made explicit.
Source anchor: Section: "The output of a simulated review needs to be triaged..." and the embedded TABLE comment

### Block 1 — Illustrae Paste Block
Draw a two-by-two grid of four equal square cells on white, axes implied by position only: left column valid, right column invalid; top row serious, bottom row minor. Fill the top-left cell (valid and serious, fix before submission) blocking vermilion #D55E00 to read as highest urgency. Fill the bottom-left cell (valid but minor, fix if time) secondary orange #E69F00. Fill the bottom-right cell (invalid but revealing a communication gap, improve explanation) primary blue #0072B2. Fill the top-right cell (invalid and irrelevant, discard) neutral gray, and place inside it one small required-action marker — a short single-headed arrow looping to a small dot — to encode that a discard still requires a written reason. Draw one single-headed gray arrow entering the grid from the top, the incoming comment, splitting toward the four cells. Keep cells equal and aligned. Flat unannotated vector, 1pt strokes, white, no text — cell position and color encode the four triage routes.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] A 2x2 triage grid (validity x seriousness) with four colored action cells and an incoming-comment arrow splitting into them.
[O - Organization] Four equal cells in two rows and two columns; one entry arrow from the top fanning to the cells; a small reason-required marker inside the discard cell.
[P - Presentation] Flat vector, Okabe-Ito: blocking vermilion #D55E00 fix-now cell, secondary orange #E69F00 fix-if-time cell, primary blue #0072B2 improve-explanation cell, neutral gray discard cell and arrows; 1pt strokes; no text in image.
[E - Exclusions] No axis labels, no cell text, no example comments, no fifth cell, no curved decorative arrows, no shading.

### Block 3 — Negative Prompt
No axis labels, no cell text, no example comment text, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: The four targeted simulation questions
Priority: Important
Trigger: MC — the useful simulation is a fixed ordered set of four targeted questions, each engaging a different layer of the paper, forming a process
Figure type: Process flowchart (ordered question battery)
Concept statement: A useful peer-review simulation asks four specific questions in order — tiered issues, strongest reason to reject, Introduction-Results alignment, and the causation/generalization overclaim audit — each forcing a specific answer.
Reader prior knowledge: Knows "please review this" is too vague; needs the four targeted questions shown as a deliberate sequence reaching different layers.
Source anchor: Section: "Here is a set of questions that consistently surfaces the problems..." and the embedded TABLE comment

### Block 1 — Illustrae Paste Block
Draw a vertical sequence of four rounded rectangles on white, top to bottom, joined by single-headed downward gray arrows, representing the four targeted questions in order: tiered Critical/Major/Minor issues, strongest reason to reject, Introduction-to-Results alignment, and the causation/generalization overclaim audit. To the right of each question box draw a small target node it reaches, connected by a short single-headed gray arrow: question one reaches a three-segment stacked node (the three tiers) in secondary orange #E69F00; question two reaches a single emphasized node in blocking vermilion #D55E00 (the one fatal reason); question three reaches a paired node in primary blue #0072B2 (the two sections compared); question four reaches a node in blocking vermilion #D55E00 (the overclaim flag). Keep the four question boxes left-aligned in one column, their target nodes in a parallel right column. Flat unannotated vector, 1pt strokes, white, no text — sequence order and the per-question target nodes encode the battery.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Four ordered question boxes, each linked to a distinct target node representing what that question reaches (tiers, fatal reason, section pair, overclaim flag).
[O - Organization] Left column of four stacked question boxes joined top-to-bottom by arrows; a parallel right column of four target nodes each linked by a short arrow.
[P - Presentation] Flat vector, Okabe-Ito: neutral gray question boxes and arrows, secondary orange #E69F00 tier-set target, blocking vermilion #D55E00 fatal-reason and overclaim targets, primary blue #0072B2 section-pair target; 1pt strokes; no text in image.
[E - Exclusions] No question text, no tier names, no numbering, no fifth question, no curved arrows, no shading.

### Block 3 — Negative Prompt
No question text, no tier names, no step numbers, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — generic vs adversarial review: STATIC SUFFICIENT — a fixed two-mode contrast over the same targets — fully legible in one frame.
FIGURE 2 — cross-section consistency: STATIC SUFFICIENT — alignment versus drift is a spatial relationship, no time axis — the shared guideline carries it statically.
FIGURE 3 — comment triage: STATIC SUFFICIENT — a categorical 2x2 routing — no process evolution to animate.
FIGURE 4 — four targeted questions: VIDEO CANDIDATE — an ordered question battery where each step reaches a different layer of the paper — a sequential build revealing one question and its target at a time could teach the order, though the static column already shows the full sequence.
Recommendation: Render all four as static figures; reserve Figure 4 as the single optional sequential build for a companion video.
