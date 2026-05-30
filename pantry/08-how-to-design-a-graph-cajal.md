# CAJAL Figure Intelligence — Chapter 8 — How to Design a Graph

Source: chapters/08-how-to-design-a-graph.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
5 figure candidates. Mixed density. As the meta-chapter on graph design, its own arguments are best carried by exemplar comparison panels — the zero-baseline manipulation, the encoding-channel ranking, and the error-bar ambiguity are all claims that only land when shown as good-versus-bad visuals.

## Figure 1: The truncated-baseline manipulation
Priority: Critical
Trigger: VG — the chapter's opening claim (same numbers, different visual argument) is depictable only by rendering the contrasting bars side by side
Figure type: Comparison panels
Concept statement: Identical two-condition values look modestly different when bars start at zero and dramatically different when the baseline is truncated, while an honest dot plot shows the gap without inflating it.
Reader prior knowledge: Has seen truncated-axis charts but may not register the baseline as the source of the distortion.
Source anchor: Section: Two bar charts. Same numbers.

### Block 1 — Illustrae Paste Block
Build three small panels in a single horizontal row, each in its own thin black (#000000) axis frame. Left panel: two vertical bars of nearly equal height, both tall, rising from a baseline at the very bottom of the frame (zero), the right bar only slightly taller than the left, both filled solid blue (#0072B2); a small gap is visible at the top. Middle panel: the same two bars but with the baseline raised high so the left bar is short and the right bar towers far above it, exaggerating the gap, same blue fill. Right panel: a dot plot showing two points at heights matching the true values, connected to a y-axis that does not start at zero but is clearly bracketed, each point in blue with a short vertical error bar. Keep components to six: three frames, two bar pairs, one dot pair. Render as a blank unannotated flat vector on white, no text or numerals, 1pt strokes, equal panel sizing.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] Three side-by-side panels of the same two-condition data: (1) bars from a zero baseline showing a modest gap, (2) bars from a truncated high baseline showing an exaggerated gap, (3) a dot plot with a bracketed non-zero range and error bars showing the gap honestly.
[O - Organization] Three equal-width framed panels in one row; panels 1 and 2 use bars, panel 3 uses points; the only structural difference between panels 1 and 2 is the baseline height.
[P - Presentation] Flat vector, Okabe-Ito — frames and axes #000000, all data marks #0072B2 (primary), error bars #000000, 1pt strokes, no text in image.
[E - Exclusions] No numeric axis values, no panel titles, no "zero" or "83" labels, no captions, no color difference between bars within a panel, no gridlines.

### Block 3 — Negative Prompt
numeric axis values, panel titles, baseline value labels, captions, differing bar colors, gridlines, text labels, words, gibberish letters, titles, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Cleveland-McGill encoding-channel accuracy ranking
Priority: Critical
Trigger: PQ — the ordered accuracy of perceptual channels is a ranked quantitative comparison, naturally a horizontal bar chart with zero baseline
Figure type: Statistical/quantitative
Concept statement: Perceptual channels differ in judgment accuracy — position on a common scale is read most accurately, then length, then angle, then area, with color/saturation least accurate.
Reader prior knowledge: Reaches for default chart types without knowing some encodings are inherently harder to read.
Source anchor: Section: William Cleveland and Robert McGill ran a series of experiments.

### Block 1 — Illustrae Paste Block
Draw a horizontal bar chart with a vertical category axis on the left and a horizontal value axis along the bottom, both 1pt black (#000000), the value axis starting at zero on the left. Stack six horizontal bars of equal thickness, one per row, ordered top to bottom from shortest to longest to encode increasing error (best channel at top with the shortest bar, worst channel at bottom with the longest bar): position-on-common-scale, position-on-non-aligned-scale, length, angle, area, color/saturation. Fill all bars a single solid blue (#0072B2) so the comparison rests on length alone. Anchor every bar at the common zero baseline on the left. Keep components to six bars plus the two axes. Render as a blank unannotated flat vector on white, no text or category names, no numerals, 1pt strokes, even row spacing.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] A horizontal bar chart of six perceptual encoding channels ranked by judgment error; bars anchored at a common zero baseline; ordered shortest (most accurate) at top to longest (least accurate) at bottom.
[O - Organization] Vertical category axis on the left listing six rows; horizontal value axis from zero; bars of uniform thickness, length increasing top to bottom.
[P - Presentation] Flat vector, Okabe-Ito — axes #000000, all six bars #0072B2 (primary, single color since the comparison is length), 1pt strokes, no text in image.
[E - Exclusions] No channel name labels, no numeric error values, no per-bar color variation, no legend, no gridlines beyond the two axes, no title.

### Block 3 — Negative Prompt
channel name labels, numeric error values, multicolor bars, legend, gridlines, title, text labels, words, gibberish letters, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Reader task to chart type decision map
Priority: Important
Trigger: VG — the mapping from reader task to appropriate chart form is a structural decision relationship not depictable from running prose
Figure type: Conceptual map
Concept statement: The reader's task — compare values, show distribution, track change, examine relationship, show composition — determines which chart form is appropriate before any default is reached for.
Reader prior knowledge: Defaults to bar charts of means regardless of the question.
Source anchor: Section: Before choosing a chart type, there is a prior question.

### Block 1 — Illustrae Paste Block
Lay out a central rounded node on the left labeled position (kept blank) representing the reader task, with five single-headed arrows fanning rightward to five terminal nodes arranged in a vertical column. Each terminal node contains a tiny blank glyph of the matching chart type drawn in line form: a pair of bars (compare values), a small box-and-whisker shape (distribution), a rising line segment (change over time), a small scatter of four dots (relationship), and a simple two-slice circle (composition). Draw the central node and arrows in neutral gray (#000000 thin), and render each terminal chart glyph in blue (#56B4E9). Keep the glyphs schematic and tiny. Keep components to six: one central node plus five terminal glyph-nodes (arrows belong to the connections). Render as a blank unannotated flat vector on white, no text, 1pt strokes, single-headed arrows only.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] One central reader-task node branching via five single-headed arrows to five terminal nodes, each holding a schematic glyph of the appropriate chart: grouped bars, box plot, line, scatter, two-slice pie.
[O - Organization] Central node on the left; five terminals stacked in a column on the right; arrows fan out left-to-right, one per terminal.
[P - Presentation] Flat vector, Okabe-Ito — central node and arrows #000000 thin, terminal chart glyphs #56B4E9 (primary), 1pt strokes, single-headed arrows, no text in image.
[E - Exclusions] No task names, no chart-type names, no captions, no decision-diamond shapes, no dual-headed arrows, no numbers inside glyphs.

### Block 3 — Negative Prompt
task labels, chart type names, captions, decision diamonds, dual-headed arrows, numbers in glyphs, text labels, words, gibberish letters, titles, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: Error bars mean three different things
Priority: Critical
Trigger: VG — that SD, SE, and CI produce different bar widths from identical data is a structural claim only shown by drawing them together
Figure type: Comparison panels
Concept statement: The same group mean drawn with standard-deviation, standard-error, and 95% confidence-interval bars yields visibly different bar widths, so unlabeled error bars are uninterpretable; showing individual points removes the ambiguity.
Reader prior knowledge: Sees error bars as generic "variability" without knowing which quantity they encode.
Source anchor: Section: Error bars are a case where the visual form looks precise.

### Block 1 — Illustrae Paste Block
Build four small panels in one horizontal row, each framed by a thin black (#000000) vertical axis. In panels one through three, draw the identical single mean as a small blue (#0072B2) marker at the same height, each with a vertical error bar of a different length: panel one the widest bar (standard deviation), panel two a medium bar (standard error, narrower), panel three a bar of intermediate width slightly wider than the standard error (95% confidence interval). In panel four, draw a vertical scatter of about ten small gray individual data points spread around the same mean height, with the blue mean marker and a short confidence-interval bar overlaid on top of the scatter. Keep the mean at the same vertical position across all four panels so only the error representation changes. Keep components to four panels. Render as a blank unannotated flat vector on white, no text or numerals, 1pt strokes, equal panel widths.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] Four panels of the same mean: (1) wide SD error bar, (2) narrow SE error bar, (3) intermediate 95% CI error bar, (4) individual jittered data points with the mean and CI overlaid.
[O - Organization] Four equal-width framed panels in a row; the mean marker sits at the same height in every panel; only the error representation differs; panel four adds the raw point cloud.
[P - Presentation] Flat vector, Okabe-Ito — axes and error bars #000000, mean markers #0072B2 (primary), individual data points neutral gray, 1pt strokes, no text in image.
[E - Exclusions] No SD/SE/CI labels, no numeric values, no panel titles, no captions, no color difference between the three error-bar panels, no gridlines.

### Block 3 — Negative Prompt
error type labels, numeric values, panel titles, captions, gridlines, differing panel colors, text labels, words, gibberish letters, titles, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 5: Bars of means hide the distribution
Priority: Important
Trigger: VG — that two identical-mean bars can hide opposite distributions is a structural claim depictable only by pairing bars with their underlying points
Figure type: Comparison panels
Concept statement: Two conditions with the same mean can have entirely different distributions — a bar of means conceals this, while a dot plot of individual scores reveals whether the spread, skew, or bimodality differs.
Reader prior knowledge: Treats a bar of means as a faithful summary of a group.
Source anchor: Section: If the task is understand a distribution.

### Block 1 — Illustrae Paste Block
Build two stacked rows sharing the same horizontal arrangement of two conditions. Top row: two vertical bars of equal height rising from a zero baseline, both filled blue (#0072B2), implying the two conditions are the same. Bottom row, directly beneath each bar: a vertical strip of individual data points showing the true distributions — under the left bar a tight cluster of gray points near the mean height, under the right bar a widely split set of gray points, half low and half high (bimodal), with a single blue mean marker and a short confidence-interval bar overlaid on each strip at the same mean height as the bar above. Use thin black (#000000) baselines and axes. Keep components to six: two bars, two point strips, two overlaid mean markers. Render as a blank unannotated flat vector on white, no text or numerals, 1pt strokes, vertical alignment between each bar and its point strip.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] A two-row comparison: top row two equal-height bars of means from a zero baseline; bottom row the matching individual-point distributions (one tight unimodal, one bimodal) with mean markers and CI bars, vertically aligned beneath the bars.
[O - Organization] Two conditions across the horizontal; bars on top, raw-point strips directly below each bar; identical means but visibly different spreads.
[P - Presentation] Flat vector, Okabe-Ito — axes and baselines #000000, bars and mean markers #0072B2 (primary), individual points neutral gray, 1pt strokes, no text in image.
[E - Exclusions] No condition labels, no numeric values, no titles, no captions, no gridlines, no color coding of the two distributions against each other.

### Block 3 — Negative Prompt
condition labels, numeric values, titles, captions, gridlines, distribution color coding, text labels, words, gibberish letters, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — truncated baseline: STATIC SUFFICIENT — simultaneous side-by-side contrast — the manipulation reads instantly from three coexisting panels; no motion needed, though a baseline-sliding animation would dramatize it.
FIGURE 2 — encoding ranking: STATIC SUFFICIENT — fixed ranked comparison — a single horizontal bar chart is the canonical static form.
FIGURE 3 — reader-task map: STATIC SUFFICIENT — branching reference structure — a one-glance lookup map, not a process.
FIGURE 4 — error bar meanings: STATIC SUFFICIENT — parallel comparison of fixed states — all four representations are compared at once.
FIGURE 5 — bars hide distribution: VIDEO CANDIDATE — reveal sequence — animating the bar dissolving into its underlying points would powerfully stage the "what the bar concealed" reveal, though the static two-row pairing already conveys it.
Recommendation: Produce all five as static comparison panels — this meta-chapter is best served by clean exemplars; Figure 5 is the single strongest optional video upgrade because its pedagogical force comes from a reveal that animation naturally stages.
