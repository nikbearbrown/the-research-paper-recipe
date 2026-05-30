# CAJAL Figure Intelligence — Chapter 2 — Foundation

Source: chapters/02-foundation.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
4 figure candidates. Mixed density. The chapter pairs a definitional matrix (design→claim commitments) with a genuine multi-step chain (design→sample→measure→analysis→finding→claim), so process and comparison figures both earn their place.

## Figure 1: Source Chain — Design to Claim
Priority: Critical
Trigger: MC — six interdependent links (design → sample → measure → analysis → finding → claim) where any link can be strained
Figure type: Process flowchart (linear chain with strain points)
Concept statement: Every claim rests on a chain back through analysis, measurement, sample, and design, and a borrowed finding is only as strong as the link it actually came from.
Reader prior knowledge: Reader thinks of a source as "what it found"; has not seen the finding decomposed into a chain of trade-off-bearing links.
Source anchor: Section: "you are evaluating the chain from design to claim"

### Block 1 — Illustrae Paste Block
Draw a horizontal left-to-right chain of six equal rounded rectangles inside a single-column textbook frame on white, connected by single straight arrows between adjacent boxes. Order left to right: design, sample, measure, analysis, finding, claim. Color the first three boxes blue #0072B2 (the production side) and the last three sky blue #56B4E9 (the inference side). Below two specific links — between sample and measure, and between measure and analysis — place a small downward strain marker (a short open caret in orange #E69F00) indicating where the chain is commonly strained (self-selected sample, immediate test). Keep all boxes the same height and evenly spaced. Use 1pt strokes, flat fills, no shadows, no gradients. Every box and marker must be blank and unannotated — no text baked in. Components: six chain boxes, five connecting arrows, two strain markers. White background, single baseline, even horizontal spacing.

### Block 2 — Full SCOPE Prompt
[S - Specification] single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] six-box linear chain (design, sample, measure, analysis, finding, claim), five connecting arrows, two strain markers beneath the sample→measure and measure→analysis links. Relationship to preserve: claim depends on every upstream link; specific links are strain points.
[O - Organization] single horizontal row, left to right, even spacing, strain markers below the chain.
[P - Presentation] flat vector, Okabe-Ito: production boxes #0072B2, inference boxes #56B4E9, strain markers #E69F00; 1pt strokes; no text in image.
[E - Exclusions] no text, no box labels, no captions, no branching, no shadows, no gradients, no human figures, no 3D.

### Block 3 — Negative Prompt
text labels, words, box titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Design Commitment Matrix
Priority: Critical
Trigger: VG — structural matrix mapping five design types to what each licenses vs. cannot support
Figure type: Comparison panels (matrix grid)
Concept statement: Each study design is a commitment that licenses some claims (association, causation, generalization) and forbids others, independent of the finding's content.
Reader prior knowledge: Reader knows design names (RCT, observational) but not that each one fixes, in advance, what language is permitted.
Source anchor: Section: "a study design is not just a method. It is a commitment."

### Block 1 — Illustrae Paste Block
Draw a clean grid inside a single-column textbook frame on white: five rows (one per design type) by three columns (licenses-association, licenses-causation, licenses-generalization), plus a left header stub column. Leave the header cells as blank tinted bands: row-stub bands light gray #999999, column-header bands sky blue #56B4E9. In each of the fifteen body cells place a single status glyph rather than text: a solid filled square (bluish green #009E73) where the design licenses that claim, a hollow open square where it does not, and a half-filled square (orange #E69F00) where it licenses with caveat. Keep cell sizes uniform and gridlines thin. Use 1pt strokes, flat fills, no shadows, no gradients. All header bands must be blank and unannotated; only the three glyph types carry meaning — no text or words baked in. Components: 5 row-stub bands, 3 column-header bands, 15 status glyphs, grid frame. White background, uniform cells, aligned grid.

### Block 2 — Full SCOPE Prompt
[S - Specification] single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] 5-row by 3-column grid plus header stub; each body cell holds one glyph — solid square (licensed), hollow square (not licensed), half square (caveated). Relationship to preserve: design type determines which claims are licensed.
[O - Organization] matrix grid, blank tinted header bands on top row and left column, uniform body cells.
[P - Presentation] flat vector, Okabe-Ito: row stubs #999999, column headers #56B4E9, licensed glyph #009E73, caveat glyph #E69F00, hollow glyph black outline; 1pt strokes; no text in image.
[E - Exclusions] no text, no design names, no column titles, no captions, no shading gradients, no extra glyph types, no shadows, no human figures, no 3D.

### Block 3 — Negative Prompt
text in cells, words, design names, column titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Summary Table vs. Source Matrix
Priority: Important
Trigger: VG — contrast between two table types whose difference (what it found vs. what it licenses) is not visible from text
Figure type: Comparison panels (two stacked mini-tables)
Concept statement: A summary table records what each source found; a source matrix adds the column that translates findings into what you are justified in borrowing.
Reader prior knowledge: Reader equates any literature table with adequate source evaluation; has not seen the added "what it licenses" column as the load-bearing difference.
Source anchor: Section: "A source matrix is not a summary table."

### Block 1 — Illustrae Paste Block
Stack two mini-table schematics vertically inside a single-column textbook frame on white. The top schematic (summary table) is a grid of four rows by four blank columns with a light gray #999999 header strip. The bottom schematic (source matrix) is the same four rows but with five columns — the same four plus one extra rightmost column highlighted with a bluish green #009E73 fill to mark the added "what it licenses" column; its header strip is sky blue #56B4E9. Draw a single downward arrow on the left connecting the top schematic to the bottom, indicating the matrix extends the summary. Keep row heights uniform across both. Use 1pt strokes, flat fills, no shadows, no gradients. All cells blank and unannotated except the color-coded highlight column — no text baked in. Components: top 4x4 grid + header strip, bottom 4x5 grid + header strip, one highlighted license column, one connecting arrow. White background, aligned left edges, uniform rows.

### Block 2 — Full SCOPE Prompt
[S - Specification] single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] top grid 4x4 (summary table), bottom grid 4x5 (source matrix) with one extra highlighted rightmost column; connecting downward arrow. Relationship to preserve: source matrix = summary table plus a "what it licenses" column.
[O - Organization] two stacked grids, shared left alignment and row heights, highlight on the added column, arrow linking top to bottom.
[P - Presentation] flat vector, Okabe-Ito: summary header #999999, matrix header #56B4E9, added column fill #009E73; 1pt strokes; no text in image.
[E - Exclusions] no text, no column headers as words, no captions, no shading gradients, no extra columns beyond the five, no shadows, no human figures, no 3D.

### Block 3 — Negative Prompt
text in cells, column header words, citations, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: Hypothesis-Driven Evidence Plan
Priority: Supplementary
Trigger: MC — hypothesis type dictates a chain of required design elements (≥3 interdependent requirements)
Figure type: Process flowchart (conditional fan from hypothesis to requirements)
Concept statement: The form of the hypothesis (causal, mechanistic, population-specific) dictates what design, measure, and sample the evidence plan must contain.
Reader prior knowledge: Reader chooses designs by convenience or convention; has not seen the hypothesis form drive specific evidence requirements.
Source anchor: Section: "the evidence plan for your own study"

### Block 1 — Illustrae Paste Block
Draw a single root node on the left inside a single-column textbook frame on white (sky blue #56B4E9), representing the hypothesis. From it draw three straight horizontal arrows fanning rightward to three stacked condition nodes: causal (top), mechanistic (middle), population-specific (bottom), each bluish green #009E73. From each condition node draw one further straight arrow to a single requirement box on the far right (orange #E69F00): the causal node points to a "design that creates a counterfactual" box, the mechanistic node to a "measure the mediator" box, the population node to a "sample containing the target population" box. Keep the three rows parallel and evenly spaced. Use 1pt strokes, flat fills, no shadows, no gradients. All nodes and boxes blank and unannotated — no text baked in. Components: one hypothesis root, three condition nodes, three requirement boxes, six connecting arrows. White background, three parallel horizontal tracks, aligned columns.

### Block 2 — Full SCOPE Prompt
[S - Specification] single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] one hypothesis root node, three condition nodes (causal, mechanistic, population), three requirement boxes, six connecting arrows. Relationship to preserve: each hypothesis form maps to one specific evidence requirement.
[O - Organization] root on left, three parallel horizontal tracks fanning right, requirement boxes aligned in a right-hand column.
[P - Presentation] flat vector, Okabe-Ito: root #56B4E9, condition nodes #009E73, requirement boxes #E69F00; 1pt strokes; no text in image.
[E - Exclusions] no text, no node labels, no captions, no extra tracks, no shadows, no gradients, no human figures, no 3D.

### Block 3 — Negative Prompt
text labels, words, node titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — Source chain (design→claim): VIDEO CANDIDATE — sequential dependency with strain points — animating a "stress test" that travels the chain and lights strain markers would show how an upstream weakness propagates to the claim, though the static chain teaches the structure.
FIGURE 2 — Design commitment matrix: STATIC SUFFICIENT — reference lookup grid — readers scan rows/columns; simultaneity is essential.
FIGURE 3 — Summary table vs. source matrix: STATIC SUFFICIENT — side-by-side structural contrast — the added column must be seen against the baseline at once.
FIGURE 4 — Evidence plan fan: STATIC SUFFICIENT — parallel mapping read at a glance — three independent tracks are clearer held still than animated.
Recommendation: Build all four as static figures; reserve Figure 1 as the single viable animation candidate for a later video pass.
