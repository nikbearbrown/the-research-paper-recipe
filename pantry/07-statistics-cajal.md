# CAJAL Figure Intelligence — Chapter 7 — Statistics

Source: chapters/07-statistics.md
Mode: /scan silent
Date: 2026-05-29

## Density Recommendation
4 figure candidates. Mixed density. This chapter pairs conceptual statistical machinery (the p-value as tail probability, the winner's curse) with directly plottable quantities (power curves, multiple-comparison inflation), so it carries both mechanism diagrams and quantitative charts well.

## Figure 1: What a p-value actually says
Priority: Critical
Trigger: VG — a structural claim (the p-value is a tail area under the null distribution) that prose names but cannot itself depict
Figure type: Statistical/quantitative
Concept statement: A p-value is the probability of observing data at least as extreme as the actual data assuming the null hypothesis is true — the shaded tail under the null sampling distribution, not the probability the null is true.
Reader prior knowledge: Has seen "p < .05" reported but likely conflates it with "probability the hypothesis is wrong."
Source anchor: Section: A p-value is not the probability that the null hypothesis is true.

### Block 1 — Illustrae Paste Block
Draw a single symmetric bell-shaped null sampling distribution curve centered on a horizontal axis, drawn as a 1pt black (#000000) stroke. Place a short vertical tick on the axis at the curve's center marking the null value, and a second vertical line further right marking the observed test statistic, drawn in blue (#0072B2). Shade the area under the curve to the right of the observed-statistic line — the upper tail — as a solid fill in orange (#E69F00); this shaded tail is the p-value. Leave the bulk of the distribution to the left unshaded. Add a thin bracket beneath the shaded tail pointing to it, and a separate small empty callout box positioned away from the curve to later hold the misconception contrast. Keep components to six: curve, axis, null tick, observed line, shaded tail, callout box. Render as a flat unannotated vector on a white background, no text or numerals anywhere in the image, clean 1pt strokes, generous whitespace.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook width, 300 DPI, vector, white background, unannotated.
[C - Content] One null sampling distribution (bell curve), a horizontal axis, a central null-value tick, a vertical observed-test-statistic line, a shaded upper tail representing the p-value, and one empty callout box reserved for the misconception contrast.
[O - Organization] Curve centered over the axis; observed-statistic line placed to the right of center; the tail beyond it shaded; bracket beneath the shaded tail; empty callout box set apart in upper area with a thin leader line toward the tail.
[P - Presentation] Flat vector, Okabe-Ito only — curve and axis #000000, observed line #0072B2 (primary), shaded p-value tail #E69F00 (secondary), 1pt strokes, no text in image.
[E - Exclusions] No numerals, no axis tick labels, no probability values, no second curve, no alternative-hypothesis distribution, no legend, no color fills other than the single orange tail.

### Block 3 — Negative Prompt
second overlapping distribution, alternative hypothesis curve, numeric axis values, percentage labels, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 2: Statistical significance versus effect size
Priority: Important
Trigger: VG — the orthogonality of significance and magnitude is a structural relationship prose asserts but cannot show
Figure type: Comparison panels
Concept statement: Statistical significance (signal-to-noise plus sample size) and effect size (actual magnitude) are independent axes — a tiny effect can be highly significant in a large sample, and a large effect can be non-significant in a small one.
Reader prior knowledge: Tends to treat "significant" as a synonym for "large" or "important."
Source anchor: Section: If the p-value doesn't tell you how large the effect is.

### Block 1 — Illustrae Paste Block
Build a two-by-two quadrant grid framed by a thin black (#000000) horizontal axis and vertical axis crossing at the lower-left origin, the horizontal axis running left-to-right and the vertical axis running bottom-to-top. In each of the four quadrants place a single representative marker: in the small-effect/significant quadrant a small filled blue (#0072B2) dot with a very short horizontal error bar; in the large-effect/significant quadrant a large blue dot with a short error bar; in the small-effect/non-significant quadrant a small open gray dot with a wide error bar crossing a thin vertical zero reference line; in the large-effect/non-significant quadrant a large gray dot with a wide error bar also crossing the zero line. Draw the zero reference line as a thin vertical gray dashed line. Keep components to six: two axes, four quadrant markers with their error bars (count as a set). Render as a blank unannotated flat vector on white, no text, 1pt strokes.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] A 2x2 conceptual space with effect size on the horizontal axis and significance on the vertical axis; four marker pairs (dot plus horizontal error bar) showing the four combinations; one vertical zero-effect reference line.
[O - Organization] Two perpendicular axes meeting at lower-left; four quadrants each holding one dot-and-error-bar; significant markers have narrow error bars not crossing zero, non-significant markers have wide error bars crossing the dashed zero line.
[P - Presentation] Flat vector, Okabe-Ito — axes #000000, significant markers #0072B2 (primary), non-significant markers neutral gray, zero line gray dashed, 1pt strokes, no text in image.
[E - Exclusions] No axis labels, no quadrant titles, no numbers, no p-value annotations, no shading fills, no additional gridlines beyond the two axes and the single zero reference line.

### Block 3 — Negative Prompt
quadrant text labels, axis titles, numeric values, p-value annotations, legend, gridlines, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 3: Power curves by effect size
Priority: Critical
Trigger: PQ — power as a function of sample size is inherently a set of plotted curves with a y-axis from zero
Figure type: Statistical/quantitative
Concept statement: Statistical power rises with sample size, and the sample size needed to reach the 0.80 conventional threshold is far larger for small effects than for large ones.
Reader prior knowledge: Knows underpowered studies are bad but underestimates how many participants adequate power requires.
Source anchor: Section: Statistical power is the probability of detecting a real effect.

### Block 1 — Illustrae Paste Block
Draw a standard line chart with a horizontal axis (sample size per group, increasing left to right) and a vertical axis running from zero at the bottom to one at the top, both as 1pt black (#000000) strokes. Plot three smooth monotonically rising S-shaped power curves that all start near the bottom-left and asymptote toward the top: the leftmost-rising, steepest curve in green (#009E73) representing the large effect; a middle curve in blue (#0072B2) for the medium effect; and the slowest-rising rightmost curve in orange (#E69F00) for the small effect. Draw one thin horizontal gray dashed reference line across the chart at the 0.80 power level. At each point where a curve crosses the dashed line, drop a short thin vertical gray tick down to the horizontal axis. Keep components to six: two axes, three curves, one threshold line (ticks belong to the threshold set). Render as a blank unannotated flat vector on white, no text or numerals, clean strokes.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] A power-versus-sample-size line chart: three rising S-curves for large, medium, and small effect sizes; one horizontal 0.80 threshold reference line; vertical drop-ticks where each curve meets the threshold.
[O - Organization] y-axis from zero to one; three curves ordered by steepness (large steepest/leftmost, small shallowest/rightmost); dashed horizontal threshold; drop-ticks from each crossing to the x-axis.
[P - Presentation] Flat vector, Okabe-Ito — axes #000000, large-effect curve #009E73 (active/strong), medium-effect curve #0072B2 (primary), small-effect curve #E69F00 (secondary), threshold and ticks neutral gray, 1pt strokes, no text in image.
[E - Exclusions] No numeric axis labels, no curve legends, no effect-size value annotations, no shaded regions, no additional gridlines, no data point markers other than the threshold-crossing ticks.

### Block 3 — Negative Prompt
numeric axis labels, effect size annotations, legend box, data point dots, shaded confidence bands, gridlines, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Figure 4: Multiple comparisons inflate the false-positive rate
Priority: Important
Trigger: PQ — the rising probability of at least one false positive across many independent tests is a plottable monotone curve
Figure type: Statistical/quantitative
Concept statement: Running many independent tests each at alpha = 0.05 drives the family-wise probability of at least one false positive far above 5% — roughly 64% by twenty tests.
Reader prior knowledge: Knows 0.05 is the conventional threshold but not that it compounds across tests.
Source anchor: Section: Multiple comparisons are the other side of the same problem.

### Block 1 — Illustrae Paste Block
Draw a single rising curve on a chart with a horizontal axis (number of tests, increasing left to right) and a vertical axis from zero at the bottom to one at the top, both 1pt black (#000000). Plot one concave curve in orange (#D55E00) that starts low at the far left (one test) and climbs steeply then flattens as it approaches the top right, representing the cumulative probability of at least one false positive. Draw a thin horizontal gray dashed reference line low near the bottom marking the single-test 0.05 level, so the gap between this baseline and the rising curve is visually obvious. Optionally add evenly spaced short vertical tick marks along the horizontal axis indicating successive test counts. Keep components to five: two axes, one rising curve, one low baseline reference line, one set of axis ticks. Render as a blank unannotated flat vector on white, no text or numerals, clean 1pt strokes, ample whitespace.

### Block 2 — Full SCOPE Prompt
[S - Specification] Single-column 89mm textbook, 300 DPI, vector, white, unannotated.
[C - Content] A monotone rising curve of family-wise false-positive probability versus number of independent tests; a low horizontal reference line at the single-test 0.05 level; evenly spaced x-axis ticks.
[O - Organization] y-axis from zero to one; curve begins low at one test and rises steeply then flattens toward the upper right; dashed baseline near the bottom; the widening gap between baseline and curve is the focal contrast.
[P - Presentation] Flat vector, Okabe-Ito — axes #000000, rising false-positive curve #D55E00 (blocking/danger), baseline reference neutral gray dashed, 1pt strokes, no text in image.
[E - Exclusions] No percentage labels, no numeric tick values, no annotations of "64%" or "5%", no legend, no shaded area fill, no second curve.

### Block 3 — Negative Prompt
percentage labels, numeric values, annotation callouts, legend, shaded fill under curve, second comparison curve, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video Candidate Pass
FIGURE 1 — what a p-value says: STATIC SUFFICIENT — single-state structural depiction — the shaded-tail relationship is grasped in one read; no temporal process.
FIGURE 2 — significance vs effect size: STATIC SUFFICIENT — comparison across a fixed 2x2 space — all four cases coexist and are compared simultaneously, not sequenced.
FIGURE 3 — power curves: VIDEO CANDIDATE — progressive parameter sweep — animating sample size increasing while the three curves climb toward the 0.80 line would make the required-N intuition vivid, though a static multi-curve chart already conveys it.
FIGURE 4 — multiple comparisons: VIDEO CANDIDATE — accumulation over successive tests — incrementing the test count and watching the cumulative false-positive probability climb dramatizes the compounding, though the static curve is adequate.
Recommendation: Generate all four as static figures first; Figures 3 and 4 are the strongest optional video upgrades because both encode an accumulating-over-a-parameter process that animation reinforces.
