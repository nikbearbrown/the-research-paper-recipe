# CAJAL Figure Intelligence — Chapter 11 — Quality Control

Source: chapters/11-quality-control.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
4 figure candidates. Mechanistic density. The chapter is built from procedures — the claim audit, the statistical integrity trace, the sequencing rule, the logic/style sort — each a multi-step process or a structural distinction that running prose enumerates but does not let the reader see as a whole.

## Figure 1: The claim audit as a flow
Priority: Critical
Trigger: MC — labeling each claim then routing it to a revision is a repeatable ≥3-step decision process applied per sentence
Figure type: Process flowchart (decision-and-route)
Concept statement: A claim audit takes each world-claim, tests evidence against scope, assigns one of six labels, and routes overstated or unsupported claims to narrowing while supported claims pass.
Reader prior knowledge: Knows what a claim is; has not seen the six labels organized by what each one routes to next.
Source anchor: Section: "The procedure I call a claim audit..." and the embedded TABLE comment

### Block 1 — Illustrae Paste Block
Draw a top-to-bottom flowchart on white. Start with a single rounded rectangle for an incoming world-claim in primary blue #0072B2. Draw a single-headed arrow down to a diamond decision node, neutral gray, representing the evidence-versus-scope test. From the diamond fan out single-headed arrows to a horizontal row of six small rounded rectangles, one per audit label. Color the leftmost (supported) active green #009E73. Color the next two (partially supported, needs qualification) secondary orange #E69F00 to read as conditional pass. Color the final three (overstated, unsupported, needs citation) blocking vermilion #D55E00 to read as must-fix. From each vermilion label draw a short single-headed arrow down to one shared terminal rounded rectangle, the narrowed claim, in active green #009E73, showing every failing label converges on a scope-narrowing revision. Keep the six labels evenly spaced and aligned. Flat unannotated vector, 1pt strokes, white, no text — position and the green/orange/vermilion gradient of severity encode the labels.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Incoming claim, one evidence/scope decision diamond, six label outcome nodes, and a single converging "narrowed claim" terminal that the failing labels route to.
[O - Organization] Vertical flow: claim at top, diamond below, six labels in an aligned horizontal row, failing labels routing down to one shared terminal box.
[P - Presentation] Flat vector, Okabe-Ito: primary blue #0072B2 incoming claim, neutral gray decision diamond, active green #009E73 supported label and terminal, secondary orange #E69F00 conditional labels, blocking vermilion #D55E00 must-fix labels; 1pt strokes; no text in image.
[E - Exclusions] No label names, no example sentences, no table, no checkmarks, no curved arrows, no more than six outcome nodes.

### Block 3 — Negative Prompt
No label names, no example claim text, no table grid, no checkmark or X icons, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Statistical integrity trace
Priority: Important
Trigger: MC — a number must be traced across four locations (output → table → Results text → Abstract) and matched at each, a multi-step verification chain
Figure type: Systems diagram (traceability chain)
Concept statement: Every quantitative claim must trace identically from software output through the Results table to the in-text statement and the Abstract; any mismatch between linked points is a reporting error.
Reader prior knowledge: Knows a paper has tables and an abstract; has not seen the number's required identity across all four locations made explicit.
Source anchor: Section: "Statistical integrity is a claim audit for numbers..." and the embedded checklist TABLE comment

### Block 1 — Illustrae Paste Block
Draw four rounded rectangles arranged left to right on white, representing in order: software output, Results table, Results in-text statement, Abstract. Connect each to the next with a single-headed gray arrow, and add a small equals-sign glyph straddling each arrow to encode that the value must match across the link. Color the four boxes primary blue #0072B2, since all are sanctioned source locations of the same number. Below the chain, draw one alternate Abstract box in blocking vermilion #D55E00 connected upward to the in-text box by a short single-headed arrow crossed by a small "not-equal" slash glyph, representing the caught mismatch. Keep the four primary boxes on one horizontal baseline, the vermilion mismatch box offset below the last link. Flat unannotated vector, 1pt strokes, white, no text — the equals and not-equal glyphs plus the vermilion box encode match versus mismatch.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Four-stage trace chain (output, table, in-text, abstract) joined by match links, plus one offset mismatch box marked not-equal.
[O - Organization] Horizontal left-to-right chain of four boxes with equals-glyph links; one vermilion mismatch box offset below, linked by a not-equal slashed arrow.
[P - Presentation] Flat vector, Okabe-Ito: primary blue #0072B2 for the four trace boxes, blocking vermilion #D55E00 for the mismatch box, neutral gray arrows and equals/not-equal glyphs; 1pt strokes; no text in image (mathematical = and ≠ glyphs permitted as geometry, not lettering).
[E - Exclusions] No statistic values, no p-values, no table contents, no box labels, no curved arrows, no third row.

### Block 3 — Negative Prompt
No statistic values or numbers, no p-value text, no box labels, no table contents, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Sequence the audit before the polish
Priority: Important
Trigger: VG — the chapter's sequencing rule (logic audit first, AI polish second) is a structural ordering claim whose danger of reversal is not depictable from text
Figure type: Process flowchart (correct order vs. inverted order)
Concept statement: Run the logic and statistical audits while errors are still visible in rough prose, then apply AI polish; reversing the order hides unsupported claims under fluency.
Reader prior knowledge: Knows AI tools smooth prose; has not seen why their timing relative to the audit determines whether errors stay detectable.
Source anchor: Section: "There is a particular failure mode with AI editing tools..."

### Block 1 — Illustrae Paste Block
Draw two horizontal three-node sequences stacked on white. The top sequence (correct order) runs left to right: rough-draft node in neutral gray, then audit-and-fix node in active green #009E73, then polish node in primary blue #0072B2 with a small green check-region inside, joined by single-headed rightward gray arrows. The bottom sequence (inverted order) runs: rough-draft node gray, then polish node in primary blue, then audit node in blocking vermilion #D55E00, also joined by rightward arrows. Inside the bottom polish node draw a small vermilion hidden-defect marker (a filled dot) and carry a faint vermilion dot forward into the audit node to show the defect now hidden under fluency. Vertically align the two rough-draft start nodes. Flat unannotated vector, 1pt strokes, white, no text — node order plus green-good/vermilion-hidden encode the correct versus dangerous sequence.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Two three-node sequences sharing a rough-draft start: correct order (audit then polish) and inverted order (polish then audit) carrying a hidden-defect marker.
[O - Organization] Top correct sequence and bottom inverted sequence, each left-to-right with rightward arrows; aligned start nodes; a small defect dot persisting through the inverted path.
[P - Presentation] Flat vector, Okabe-Ito: neutral gray rough-draft starts, active green #009E73 audit step, primary blue #0072B2 polish step, blocking vermilion #D55E00 mis-timed audit and the hidden-defect dot; 1pt strokes; no text in image.
[E - Exclusions] No step labels, no tool names, no icons of robots or pens, no third sequence, no curved arrows, no shading.

### Block 3 — Negative Prompt
No step labels, no tool or AI names, no robot or pen icons, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: Logic problem vs. style problem
Priority: Supplementary
Trigger: VG — two problem types with two correct fixes and two wrong fixes form a 2-axis distinction the prose lists but cannot show as opposed routes
Figure type: Comparison panels (two-route split)
Concept statement: A style problem makes a sound claim hard to read and needs a how-it-reads fix; a logic problem makes a claim unsupported and needs a what-it-claims fix — and swapping the fixes fails.
Reader prior knowledge: Tends to conflate the two; needs the parallel structure and the cross-applied wrong fix made visible.
Source anchor: Section: "Logic problems and style problems are different kinds of problems..." and the embedded TABLE comment

### Block 1 — Illustrae Paste Block
Draw two vertical panels side by side on white, separated by a thin gray divider. Left panel header-region is secondary orange #E69F00 for the style problem; right panel header-region is blocking vermilion #D55E00 for the logic problem. In the left panel draw a downward single-headed gray arrow to one rounded rectangle in active green #009E73, the correct style fix (change how it reads). In the right panel draw a downward arrow to one green rounded rectangle, the correct logic fix (change what it claims). Then draw one diagonal single-headed arrow crossing from the left panel's problem down to the right panel's green box and another crossing the opposite way, each crossing arrow rendered in vermilion and terminating at a small vermilion X-region, encoding that applying the other panel's fix fails. Keep the two panels equal width and aligned. Flat unannotated vector, 1pt strokes, white, no text — panel color, vertical good-fix arrows, and crossed vermilion arrows encode the right and wrong routes.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook figure, 300 DPI, vector, white background, unannotated.
[C - Content] Two problem panels (style, logic), each with its correct fix, plus two crossing arrows showing the mismatched fix failing.
[O - Organization] Side-by-side equal panels with a central divider; vertical arrow to a correct-fix box within each; two diagonal cross-panel arrows ending in failure markers.
[P - Presentation] Flat vector, Okabe-Ito: secondary orange #E69F00 style-problem header, blocking vermilion #D55E00 logic-problem header and the crossing wrong-fix arrows, active green #009E73 correct-fix boxes, neutral gray vertical arrows and divider; 1pt strokes; no text in image.
[E - Exclusions] No example sentences, no panel titles, no checkmark or X letterforms (use plain marker regions), no third panel, no curved arrows.

### Block 3 — Negative Prompt
No example sentence text, no panel titles, no letterform checkmarks, no legend, plus: text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — claim audit flow: VIDEO CANDIDATE — a per-sentence routing process where claims enter, get labeled, and route to revision — a build that animates a claim moving through the diamond to its label could teach the loop, though the static flowchart is self-contained.
FIGURE 2 — statistical integrity trace: STATIC SUFFICIENT — a fixed traceability identity across four points — the match/mismatch is fully shown in one frame.
FIGURE 3 — sequence audit before polish: STATIC SUFFICIENT — two short fixed orderings — the contrast reads instantly side by side.
FIGURE 4 — logic vs style: STATIC SUFFICIENT — a categorical 2x2-style distinction — no temporal dimension.
Recommendation: Produce all four as static figures; Figure 1 is the only reasonable animated build and only if a companion video accompanies the chapter.
