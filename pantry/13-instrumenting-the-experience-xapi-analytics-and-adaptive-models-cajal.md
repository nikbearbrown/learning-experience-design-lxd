# CAJAL Figure Intelligence Report — Chapter 13: Instrumenting the Experience: xAPI, Analytics, and Adaptive Models
*Generated 2026-06-07 · /scan silent · Source: chapters/13-instrumenting-the-experience-xapi-analytics-and-adaptive-models.md*

## Detection summary

| # | Figure | Heuristic | Type | Rank |
|---|--------|-----------|------|------|
| 1 | Two dashboards, one course — SCORM vs. xAPI data visibility | VG | comparison panels | Critical |
| 2 | The three metric classes and the no-impersonation rule | VG | hierarchy-taxonomy | Critical |
| 3 | Anatomy of an xAPI statement and the Learning Record Store | MC | structural schematic | Important |
| 4 | The IRT logistic curve — ability, difficulty, discrimination | PQ | statistical-quantitative | Important |
| 5 | Bayesian at-risk updating with the intervention gate | MC | process flowchart | Important |

Notes on zones scanned and rejected: Hubbard's clarification chain (matters → observable consequences → detectable → measurable) is a four-step verbal chain but each step is a one-clause restatement of the last — prose carries it cleanly; a figure would add ink, not understanding. The Goodhart/time-on-task trap has no chart-grade quantities in the text (the predictive-validity claim is flagged `[verify]`), so a PQ figure would fabricate precision the chapter explicitly withholds. The running-case A1–A5 measurement plan is already tabular in the prose and carries two authorial `<!-- TABLE -->` placeholders; those are tables, not figures, and are correctly specified as tables.

## Density recommendation

The chapter runs roughly 5,400 words of main text across seven sections, with two inline table placeholders already authored. Five figures — approximately one per 1,000 words of expository text — sits at the upper edge of appropriate density for a graduate methods chapter and is justified because four of the five sections introduce a structure the prose can only serialize (a comparison, a taxonomy, a grammar, a curve, an update loop). Recommend placing Figure 1 adjacent to the opening case (it is the chapter's thesis made visible), Figure 2 at the metric-classes section head, Figures 3–5 each within their host section. Do not add a figure to the ethics section or the running case; both are argumentative rather than structural, and a sixth figure would dilute the page-anchor value of the five. Cognitive load check (first-year LXD master's student): all five figures decompose into ≤8 components with single-relation arrow logic; the IRT curve is the highest-load item and is mitigated by restricting it to two curves and one reference line.

## Figures

### Figure 1 — Two dashboards, one course: SCORM vs. xAPI data visibility (rank: Critical; heuristic: VG)
**Concept (one sentence):** The same learners produce a sparse green summary under SCORM's fixed vocabulary and a specific, pattern-revealing event stream under xAPI instrumentation, because each standard can only report what its data model has words for.
**Figure type:** comparison panels
**Cognitive load check:** Two panels, three tiles versus one timeline with three event-pattern callouts — eight components, one comparison relation; well within range for a first-year master's reader who has just read the opening case.

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Draw a two-panel side-by-side comparison of the same online course reported through two data standards, as an unannotated flat vector with no text labels. In the left panel, render a minimal dashboard: three large rounded-rectangle summary tiles stacked vertically, each containing only a single simple glyph — a filled circle for completion, a filled gauge arc for score, a filled clock face for time — all rendered in neutral gray to read as aggregate and inert. In the right panel, render a horizontal event timeline of the same course: a long thin baseline carrying many small tick-mark event dots in primary blue, with three distinct pattern regions emphasized — a dense cluster of repeated dots over one short segment rendered in active green, a small dot positioned before a larger dot to show help requested before any attempt rendered in secondary orange, and a dashed-outline empty segment showing a skipped activity rendered in blocking vermillion outline. Connect the two panels with a single rightward arrow along the bottom indicating the same course republished under richer instrumentation. Keep both panels equal width, aligned tops, 1pt strokes, white background.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89 mm width, 300 DPI minimum, vector output, white background.
- **[C]** Confirmed content only, 7 components: (1) left panel frame, (2) three gray summary tiles with circle/gauge/clock glyphs, (3) right panel frame, (4) event-timeline baseline with small blue event dots, (5) dense repeated-event cluster region, (6) help-before-attempt dot pair, (7) skipped-segment dashed outline. The bottom connecting arrow is an inference (same course, two instrumentations) and is flagged as inference in the art brief, not in the artwork.
- **[O]** Left panel → right panel reading order; bottom arrow left → right; within right panel, timeline flows left → right; the three pattern regions sit on the timeline in sequence, no crossing leader lines.
- **[P]** Flat vector, Okabe-Ito semantic mapping: aggregate SCORM tiles neutral gray (#999999), baseline event dots primary blue #56B4E9, pause-cluster region active #009E73, help-before-attempt pair secondary #E69F00, skipped-segment outline blocking #D55E00, panel frames neutral gray; 1pt strokes throughout; no text labels.
- **[E]** Exclude: any numerals or percentage glyphs inside tiles; bar charts or pie charts inside either panel; more than three pattern regions on the timeline; screenshot-style browser chrome, traffic-light icons, checkmark icons; green fill on the left panel (the "green dashboard" irony is for the caption, not the art); any human figures or avatars; gridlines.

**BLOCK 3 — NEGATIVE PROMPT:**
dashboard screenshot realism, browser chrome, numerals, percentage signs, checkmarks, traffic lights, pie charts, more than two panels, crossing leader lines, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 2 — The three metric classes and the no-impersonation rule (rank: Critical; heuristic: VG)
**Concept (one sentence):** Every metric belongs to exactly one of three classes — behavioral engagement, cognitive engagement proxy, learning evidence — and the discipline is preventing a lower class from answering a higher class's question.
**Figure type:** hierarchy-taxonomy
**Cognitive load check:** One root, three class nodes, three exemplar glyphs, two blocked-substitution marks — eight components; the blocking glyph (⊣) is the only novel notation and is introduced once, consistently.

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Draw a three-tier vertical taxonomy of measurement classes as an unannotated flat vector with no text labels. Place a single small root node at top center in neutral gray. Branch it with 1pt lines to three class nodes arranged in a left-to-right row that also reads bottom-to-top in evidential strength: the leftmost node a plain filled square in secondary orange representing counted participation, the middle node a square with an inner dashed outline in primary blue representing patterned behavior that licenses an inference, the rightmost node a square containing a small clock-delay glyph in active green representing delayed aligned performance. Beneath each class node hang one exemplar glyph on a short stem: a footprint-like dot trail under the left node, an ordered dot-pair under the middle node, a small distance-separated target under the right node. Between the left and right ends of the row, draw two upward-curving arrows that each terminate in a perpendicular blocking bar rather than an arrowhead — one from the orange node toward the green node, one from the blue node toward the green node — rendered in blocking vermillion, showing that lower classes may not substitute upward. White background.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89 mm width, 300 DPI minimum, vector output, white background.
- **[C]** Confirmed content only, 8 components: (1) root node, (2) behavioral-engagement class node, (3) cognitive-proxy class node with dashed inner outline, (4) learning-evidence class node with delay glyph, (5–7) one exemplar glyph per class, (8) two blocked-substitution connectors counted as one notation system. The left-to-right strength ordering is stated in the chapter (proxies license inferences; learning metrics require delayed aligned performance) — not an inference.
- **[O]** Root → three branches, top → bottom; class row reads left → right in increasing evidential strength; blocked substitutions rendered as curved connectors ending in ⊣ bars, never arrowheads, arcing above the class row.
- **[P]** Flat vector, Okabe-Ito semantic mapping: behavioral engagement secondary #E69F00, cognitive proxy primary #56B4E9, learning evidence active #009E73, blocked-substitution connectors #D55E00, root and stems neutral gray; 1pt strokes; no text labels.
- **[E]** Exclude: any fourth class node; arrowheads on the blocking connectors; pyramid or triangle framing (this is a taxonomy, not a hierarchy of value); brain icons, lightbulb icons, graduation-cap icons; size differences among the three class nodes; any downward connectors between classes.

**BLOCK 3 — NEGATIVE PROMPT:**
pyramid shapes, triangle hierarchy, brain icons, lightbulb icons, graduation caps, badge icons, a fourth category node, arrowheads on blocking bars, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 3 — Anatomy of an xAPI statement and the Learning Record Store (rank: Important; heuristic: MC)
**Concept (one sentence):** Every xAPI event is a statement assembled from an actor, a verb, and an object — optionally extended with result and context — and statements from multiple experience sources flow into a Learning Record Store independent of any single LMS.
**Figure type:** structural schematic
**Cognitive load check:** One three-slot statement unit, two optional slots, three source glyphs, one store — the assembly metaphor is read in one pass; optional slots are visually subordinated by dashed outlines so the core triple dominates.

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Draw a structural schematic of an event statement and its storage path as an unannotated flat vector with no text labels. At top center, render the statement as three interlocking rounded rectangles in a horizontal row, joined edge-to-edge like puzzle segments: the first containing a simple person-silhouette-free agent glyph (a filled circle over a trapezoid base) in primary blue, the second containing a rightward action chevron in active green, the third containing a small document-square glyph in primary dark blue. Attach two smaller dashed-outline rectangles hanging beneath the second and third segments in secondary orange, visually optional. Below this statement unit, arrange three small source shapes in a row — a monitor outline, a phone outline, a simple cube — each in neutral gray, each emitting one short downward arrow that converges with the statement unit's own downward arrow into a single database cylinder at bottom center rendered in composite pink with neutral gray detail lines. Keep the cylinder visibly separate from the three sources, centered, with 1pt strokes on a white background, all arrows single-headed and vertically aligned.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89 mm width, 300 DPI minimum, vector output, white background.
- **[C]** Confirmed content only, 8 components: (1) actor slot, (2) verb slot, (3) object slot, (4) optional result slot, (5) optional context slot, (6) three experience-source glyphs counted as one group (LMS monitor, mobile phone, simulation cube — all named in the chapter), (7) convergence arrows, (8) Learning Record Store cylinder. No inferences required; every element is explicit in the text.
- **[O]** Statement reads left → right (actor → verb → object); optional slots hang below on short stems; all flows run top → bottom into the cylinder; arrows converge but never cross.
- **[P]** Flat vector, Okabe-Ito semantic mapping: actor slot primary #56B4E9, verb slot active #009E73, object slot primary #0072B2, optional result/context slots secondary #E69F00 with dashed 1pt outlines, source glyphs neutral gray, LRS cylinder composite #CC79A7; 1pt strokes; no text labels.
- **[E]** Exclude: JSON braces or code-like glyph strings; more than three source devices; any second cylinder or cloud icon; bidirectional arrows between sources and store; company logos; network/wifi iconography; human figures.

**BLOCK 3 — NEGATIVE PROMPT:**
code snippets, JSON braces, curly brackets, cloud icons, wifi symbols, vendor logos, more than one database cylinder, bidirectional flows, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 4 — The IRT logistic curve: ability, difficulty, discrimination (rank: Important; heuristic: PQ)
**Concept (one sentence):** The probability of answering an item correctly rises as a logistic function of the gap between learner ability θ and item difficulty b, crossing 50% where they meet, with the discrimination parameter a setting the curve's steepness.
**Figure type:** statistical-quantitative
**Axis-zero exception logic:** The y-axis is a probability and runs from 0 to 1 with zero shown — Proportional Ink Rule satisfied. The x-axis is the latent θ−b scale, which has no meaningful zero-bottom; it is centered where θ = b, and this is the documented exception: a latent interval scale is anchored at its substantive reference point (the 50% crossing), not at an arbitrary origin. Axis value labels are typeset later by the compositor; the artwork itself remains unannotated.
**Cognitive load check:** Two curves, two axes, one reference crossing — six components; the two-curve contrast (steep vs. shallow a) is the single comparison the reader must extract.

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Draw a single quantitative function plot as an unannotated flat vector with no text labels. Render a horizontal x-axis and a vertical y-axis meeting at the lower left, both in neutral gray with small unlabeled tick marks; the y-axis spans the full probability range from its base to its top, with a faint dashed horizontal reference line at exactly half height running the plot's width in neutral gray. Plot two S-shaped logistic curves rising from near the floor at the left to near the ceiling at the right, both crossing the half-height reference line at the same central x-position: one curve steep, rendered in primary blue, climbing sharply through the crossing; the second curve shallow, rendered in secondary orange, climbing gradually through the same crossing. Mark the shared crossing point with a single small open circle in active green, and drop a faint dashed vertical line from that point to the x-axis in neutral gray. Keep curve strokes slightly heavier than axis strokes for figure-ground separation, 1pt base strokes, white background, no gridlines, no shaded regions, generous margins inside the plot frame.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89 mm width, 300 DPI minimum, vector output, white background.
- **[C]** Confirmed content only, 6 components: (1) x-axis (latent θ−b scale, centered at the θ=b point — exception to zero-origin documented above; an inference-free rendering of the chapter's equation), (2) y-axis spanning probability 0→1 with zero shown, (3) dashed 0.5 reference line, (4) steep high-discrimination curve, (5) shallow low-discrimination curve, (6) shared crossing marker with dashed drop line.
- **[O]** Both curves flow left → right, monotonically rising; reference line horizontal at half height; drop line vertical from crossing to axis; nothing crosses except the two curves at their shared inflection.
- **[P]** Flat vector, Okabe-Ito semantic mapping: high-discrimination curve primary #0072B2, low-discrimination curve secondary #E69F00, crossing marker active #009E73, axes and dashed references neutral gray; 1pt strokes (curves 1.5pt for hierarchy); no text labels, no axis numerals (typeset at composition).
- **[E]** Exclude: more than two curves; any data points or scatter dots; shaded confidence bands; gridlines; arrowheads on axes; curves that fail to plateau (each must visibly asymptote at floor and ceiling); any bar-chart element; a zero label or implication that the latent x-axis starts at zero.

**BLOCK 3 — NEGATIVE PROMPT:**
scatter points, data dots, confidence bands, shaded regions, gridlines, more than two curves, axis arrowheads, bar elements, numerals, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 5 — Bayesian at-risk updating with the intervention gate (rank: Important; heuristic: MC)
**Concept (one sentence):** A Bayesian at-risk model starts from a historical base rate, revises its risk probability as behavioral evidence arrives, and may only emit a flag into the experience if a specified intervention path exists — otherwise the model is cut.
**Figure type:** process flowchart
**Cognitive load check:** A single left-to-right pipeline with one gate and two outcomes — seven components; the partially-filled probability bar is reused at two stages so the reader tracks one object changing, not two objects.

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Draw a left-to-right process flowchart of probabilistic risk updating as an unannotated flat vector with no text labels. Begin at far left with a horizontal probability bar — a rounded-rectangle track partially filled from the left in neutral gray — representing the historical prior. Above the pipeline's midsection, place three small evidence glyphs in secondary orange (a missed-calendar square with a slash-free gap, a jagged error zigzag, a descending three-bar mini-trend), each dropping a short single-headed arrow into the main flow. After the evidence joins, render the same probability bar again, now filled further and tinted primary blue, representing the updated posterior. The posterior bar feeds rightward into a diamond-shaped decision gate outlined in neutral gray. From the gate, draw two exits: a downward-right path ending in a paired-shapes glyph — a small flag pennant beside an open-hand-free support glyph of two linked rounded rectangles — rendered in active green, representing flag plus specified intervention; and a rightward path terminating in a perpendicular blocking bar in vermillion, representing the model cut when no intervention exists. White background, 1pt strokes, all arrows single-headed.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89 mm width, 300 DPI minimum, vector output, white background.
- **[C]** Confirmed content only, 7 components: (1) prior probability bar (historical base rate), (2) three evidence glyphs counted as one group (missed deadlines, error patterns, declining activity — all named in the chapter), (3) evidence-injection arrows, (4) posterior probability bar with greater fill, (5) intervention decision gate, (6) flag-plus-intervention outcome, (7) blocked outcome (model cut). The gate is the chapter's explicit rule ("if the column is empty, cut the model"), not an inference.
- **[O]** Main flow left → right: prior → evidence joins → posterior → gate; evidence drops top → bottom into the flow; gate exits split — accepted path angles down-right ending in →, refused path continues right ending in ⊣.
- **[P]** Flat vector, Okabe-Ito semantic mapping: prior bar neutral gray, evidence glyphs secondary #E69F00, posterior bar primary #56B4E9, flag-plus-intervention outcome active #009E73, blocking terminal #D55E00, gate outline neutral gray; 1pt strokes; no text labels.
- **[E]** Exclude: any percentage numerals on the bars; Bayes' theorem notation or fraction bars; more than three evidence glyphs; a human silhouette as the flagged learner; alarm bells, warning triangles, siren icons; loops back from posterior to prior (the chapter describes forward revision at this grain); red fill on the probability bars.

**BLOCK 3 — NEGATIVE PROMPT:**
mathematical notation, fraction bars, percentage numerals, warning triangles, alarm bells, siren icons, surveillance camera icons, more than three evidence glyphs, feedback loops, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video candidate pass

| Figure | Status | Criterion | Reason |
|--------|--------|-----------|--------|
| 1 — Two dashboards | Not a candidate | Transition mechanism | A static contrast; nothing transforms over time — the comparison is the content. |
| 2 — Metric classes | Not a candidate | State change / process | Taxonomies are timeless structures; animation would add motion without adding mechanism. |
| 3 — xAPI statement anatomy | Weak candidate | Assembly sequence | Statement assembly (actor + verb + object snapping together, flowing to the LRS) has a mild build sequence, but it is a one-beat assembly — a static schematic carries it at lower cost. |
| 4 — IRT curve | Weak candidate | Parameter sweep | Animating *a* steepening and *b* sliding the curve laterally is genuinely mechanistic, but the chapter's pedagogical target is reading a static calibration output, not manipulating parameters. |
| 5 — Bayesian updating | **Candidate — RECOMMENDED** | Transition mechanism over time | The core concept *is* temporal: a probability bar filling as each evidence event lands, the posterior visibly revised event by event, then meeting the intervention gate. |

**Close: 3 candidates (Figures 3, 4, 5); ONE recommended — Figure 5, Bayesian at-risk updating.** Rationale: posterior revision is the only concept in this chapter whose mechanism is literally a sequence of state changes — prior → evidence₁ → revised → evidence₂ → revised — and the chapter's hardest teaching point (a probability is a continuously revised belief, not a diagnosis) is exactly what a static figure flattens. A 20–30 second animation showing the same bar updating three times, then forking at the intervention gate, teaches the "flag without intervention is surveillance" rule as a felt consequence of the flow rather than a slogan. Figures 3 and 4 survive perfectly well as statics.
