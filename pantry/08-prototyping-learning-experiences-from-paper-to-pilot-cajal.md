# CAJAL Figure Intelligence Report — Chapter 8: Prototyping Learning Experiences — From Paper to Pilot
*Generated 2026-06-07 · /scan silent · Source: chapters/08-prototyping-learning-experiences-from-paper-to-pilot.md*

## Detection summary

| # | Concept | Heuristic | Rank | Figure type |
|---|---------|-----------|------|-------------|
| 1 | The fidelity ladder (six rungs, question-matched) | VG | Critical | Vertical progression / ladder diagram |
| 2 | Four-channel learning interaction test vs usability surface | VG + MC | Critical | Layered conceptual map (probe-depth diagram) |
| 3 | Prototype–test cycle with fidelity demotion/promotion | MC | Important | Cycle diagram |
| 4 | Evaluation-timescale coverage (zero-delay bias) | VG | Important | Coverage matrix |
| 5 | Parallel vs serial prototyping | VG | Supplementary | Two-panel comparison |

Notes on author-embedded placeholders: the chapter's `[DIAGRAM: fidelity ladder]` comment maps directly to Figure 1 and the `[CHART: timeline of what each evaluation type can measure]` comment maps to Figure 4 — both confirmed as genuine figure needs, not tables. The `[TABLE: two-column test sheet template]` is text-bearing tabular content for typesetting; not claimed here. PQ check: the chapter cites Dow et al. (2010), Nielsen & Landauer (1993), and Gould & Lewis (1985) directionally, with no effect sizes or distributions reproduced, so no quantitative chart is licensed; Figure 4 is a categorical coverage matrix, not a data chart, and Figure 5 encodes the Dow finding structurally without fabricated magnitudes. The cost-asymmetry claim was triaged and declined as a standalone figure: drawing a rising cost curve would require inventing a curve shape the chapter never supplies; the asymmetry is instead carried by Figure 1's cost wedge, labeled as ordinal.

## Density recommendation

Five figures for a ~5,200-word chapter is the correct ceiling, and the chapter earns it: this is the book's most mechanism-dense methods chapter, and two of its claims (the ladder, the four channels) are load-bearing for the graded checkpoint. Figures 1 and 2 are non-negotiable. Figure 4 fulfills an explicit author placeholder and guards the checkpoint's most common failure (overclaiming). Figure 3 is the strongest video candidate and could ship as video-only if page budget is tight. Figure 5 is the first cut. Cognitive Load Check (first-year LXD master's student): each figure isolates one discipline — when to be rough (1), what to probe (2), how to iterate (3), what you cannot claim (4), how many to build (5) — so no figure asks the student to integrate two disciplines at once.

## Figures

### Figure 1 — The Fidelity Ladder (rank: Critical; heuristic: VG)
**Concept (one sentence):** Fidelity is a six-rung ladder — sketch/storyboard, paper prototype, Wizard of Oz, clickable mockup, authoring-tool build, pilot module — climbed one question at a time, with cost rising by rung and the entry rung chosen by the riskiest unknown, not by ambition.
**Figure type:** Vertical progression diagram (ladder with cost wedge and entry arrow)

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Create a flat vector ladder diagram on a white background showing six horizontal rounded rectangles stacked vertically with even gaps, all the same width, representing six fidelity rungs from lowest at the bottom to highest at the top. Fill the bottom five rungs in sky blue #56B4E9 and the topmost rung in reddish purple #CC79A7 to mark the pilot rung as a different kind of test involving real stakes. Along the left side of the stack, draw a single neutral gray right-triangle wedge, narrow at the bottom and wide at the top, flush against the rungs, representing build cost rising with fidelity. At the second rung from the bottom, draw one bold horizontal arrow in bluish green #009E73 entering from the right side and stopping at that rung, representing the chosen entry point matched to the riskiest unknown. Above that arrow, draw a small open circle outline in bluish green attached to the arrow's tail, representing the unanswered question that selects the rung. Use 1pt strokes, flat fills, even vertical rhythm, and no text labels anywhere.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89mm width, 300 DPI minimum, vector, white background.
- **[C]** Eight components at the cap: six rungs, one cost wedge, one entry arrow with question marker. Confirmed content: the six rungs and their bottom-to-top order are quoted structure from the chapter. Inferences to label: the cost wedge encodes ordinal direction only (the chapter gives no cost figures), and the entry arrow's position at the second rung is illustrative — the caption must state that the entry rung varies per project.
- **[O]** Vertical, bottom = lowest fidelity, top = highest, matching the chapter's "climb" metaphor. Cost wedge on the left, entry arrow from the right (→ terminating at the rung, never passing through it). No arrows between rungs: the figure must not imply automatic ascent — climbing is a per-question decision, which the single entry arrow carries.
- **[P]** Flat vector. Okabe-Ito mapping: rungs #56B4E9 (primary instrument set), pilot rung #CC79A7 (composite — real learners, real stakes), entry arrow and question marker #009E73 (the active decision), cost wedge neutral gray. 1pt strokes. No text labels.
- **[E]** Exclude: a literal ladder with rails and rungs (clip-art risk); ascending arrows or a climbing figure; numeric cost values, currency symbols, or clock icons on the wedge; quality-star ratings; any seventh rung; tool logos; screenshots or device frames inside the rungs.
- **Cognitive Load Check:** pass — one stack, one wedge, one arrow; the student's only task is mapping the caption's rung names onto six positions.

**BLOCK 3 — NEGATIVE PROMPT:**
literal wooden ladder, climbing figure, staircase, currency symbols, dollar signs, clock icons, star ratings, software logos, device frames, screenshots, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 2 — Four Channels Beneath the Surface: The Learning Interaction Test (rank: Critical; heuristic: VG + MC)
**Concept (one sentence):** A usability test probes only whether the learner can operate the experience, while a learning interaction test sends four deeper probes — inferred rule, load signature, feedback uptake, motivational read — past the operational surface to what the learner actually believes, carries, does with feedback, and values.
**Figure type:** Layered conceptual map (probe-depth diagram)

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Create a flat vector probe-depth diagram on a white background. In the lower half, draw a large target structure of two concentric circles — a thin gray outer ring representing the learner's observable task behavior and a solid deep blue #0072B2 inner core representing the learner's actual understanding. Across the upper third, draw a single thin horizontal gray line representing the operational surface that a standard usability test never penetrates. From above that line, draw five downward probe arrows. The leftmost arrow, in sky blue #56B4E9, stops exactly at the gray outer ring, representing the usability probe reaching only observable operation. The remaining four arrows pass cleanly through the ring and terminate at the inner core, each in its own color: deep blue #0072B2 for the inferred-rule probe, orange #E69F00 for the load-signature probe, bluish green #009E73 for the feedback-uptake probe, and reddish purple #CC79A7 for the motivational-read probe. Space all five arrows evenly, keep them parallel and vertical, and give the four deep probes identical lengths. Use 1pt strokes, flat fills, and no text labels.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89mm width, 300 DPI minimum, vector, white background.
- **[C]** Seven components: surface line, outer ring, inner core, five probe arrows. Confirmed content: the four channels and the claim that usability protocols never touch them are quoted structure ("a learning experience can pass every usability test and teach the wrong thing"). Inference to label: the concentric behavior/understanding geometry is a visual paraphrase of the chapter's completion-vs-comprehension distinction, not a model the chapter draws.
- **[O]** Vertical probe direction, top to bottom (outside → inside the learner's understanding). The usability arrow's stop-short termination is the figure's argument and must be unmistakable: it ends at the ring boundary with clear white space before the core. Four deep arrows pierce the ring at marked crossing points. All arrows →, single-headed, downward.
- **[P]** Flat vector. Okabe-Ito mapping: usability probe #56B4E9 (legitimate but shallow), inferred rule #0072B2 (primary conceptual channel), load #E69F00, feedback uptake #009E73, motivational read #CC79A7; surface and ring neutral gray. 1pt strokes. No text labels.
- **[E]** Exclude: a human head or silhouette as the target (the negative list bars human figures; the abstraction is deliberate); brain imagery; iceberg imagery; magnifying glasses; checkmarks on any probe; ranking of the four deep probes by length or weight (the chapter orders them rhetorically, not by importance); a sixth probe.
- **Cognitive Load Check:** pass — one contrast carried by arrow termination depth; four colors map one-to-one to four caption terms.

**BLOCK 3 — NEGATIVE PROMPT:**
human head silhouette, brain illustration, iceberg, magnifying glass, stethoscope, checkmarks, ranking marks, depth gauge numerals, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 3 — The Prototype–Test Cycle (rank: Important; heuristic: MC)
**Concept (one sentence):** Disciplined prototyping is a loop — name the riskiest unknown, choose the lowest rung that can answer it, build cheap, run the four-channel test, classify findings into usability and learning columns, then revise and re-enter the loop at a rung the new question justifies, including demotion to a lower rung.
**Figure type:** Cycle diagram with one demotion branch

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Create a flat vector cycle diagram on a white background with six nodes arranged clockwise in a circle, connected by single curved arrows. Node one at the top is an open circle outline in bluish green #009E73 representing the riskiest unknown. Node two is a small three-step stair glyph in sky blue #56B4E9 with one step highlighted, representing the choice of the lowest sufficient fidelity rung. Node three is a plain rectangle in sky blue #56B4E9 representing the cheap build. Node four is a circle in deep blue #0072B2 with four short inward tick marks on its rim, representing the four-channel test. Node five is a square split vertically into two halves, gray and deep blue #0072B2, representing the two-column classification of findings. Node six is a rectangle in orange #E69F00 representing the revision. Close the loop from node six back to node one. Add one additional short arrow in vermillion #D55E00 from node five cutting inward across the circle directly to node two, representing demotion back down the fidelity ladder when the build outran the question. Use 1pt strokes, flat fills, even angular spacing, and no text labels.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89mm width, 300 DPI minimum, vector, white background.
- **[C]** Seven components: six cycle nodes plus one demotion chord. Confirmed content: every node is an explicit step in the chapter's method, and the demotion chord is the worked example's documented move (Storyline build shelved, question demoted to paper). Inference: none — the loop closure (revise → new riskiest unknown) is stated in the chapter's iteration sequence (five learners, revision, three fresh learners).
- **[O]** Clockwise flow starting at top (the unknown is the entry point and must read as such — slightly larger than other nodes). All cycle arrows → curved, single-headed. The demotion chord is straight, cuts the interior, and is the only #D55E00 element — it must read as an exceptional but legitimate path, not an error state.
- **[P]** Flat vector. Okabe-Ito mapping: riskiest unknown #009E73 (the active driver), fidelity choice and build #56B4E9 (instruments), test and classification #0072B2 (primary evidence acts), revision #E69F00 (change), demotion chord #D55E00 (costly correction honestly drawn). 1pt strokes. No text labels.
- **[E]** Exclude: a recycling-symbol triangle; gear or cog imagery; numbered badges on nodes (sequence is carried by arrows and caption); any second chord; clock or calendar icons; a happy/sad endpoint — the loop has no exit node, which is the point.
- **Cognitive Load Check:** pass — six stations and one exception path; the student traces it once with the caption's numbered list.

**BLOCK 3 — NEGATIVE PROMPT:**
recycling symbol, gears, cogs, numbered badges, clock icons, calendar icons, finish-line flags, trophy icons, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 4 — What a Session Cannot See: Evaluation-Timescale Coverage (rank: Important; heuristic: VG)
**Concept (one sentence):** Each evaluation method covers only certain timescales — the prototype test occupies the zero-delay column alone, so durable retention, decay, habit, and cohort effects are structurally invisible to it and must be named as assumptions rather than quietly overclaimed.
**Figure type:** Categorical coverage matrix (methods × timescales)

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Create a flat vector coverage matrix on a white background: a grid of four rows and four columns of equal cells with thin gray rules. Rows represent four evaluation methods ordered top to bottom from cheapest to most instrumented — prototype test, pilot module, delayed assessment, instrumented deployment. Columns represent four timescales ordered left to right — session, days, weeks, months. Fill covered cells with solid deep blue #0072B2: row one filled in column one only; row two filled in columns one and two; row three filled in columns two and three; row four filled in columns two, three, and four. Leave all uncovered cells white with their gray borders intact. Around the three empty cells in the top row — the retention, decay, and long-horizon claims a prototype session cannot make — draw one shared rounded-rectangle outline in orange #E69F00, marking them as the named-assumption zone rather than mere absence. Along the bottom edge, draw a single thin gray arrow running left to right beneath the columns representing elapsing time. Use 1pt strokes, flat fills, and no text labels.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89mm width, 300 DPI minimum, vector, white background.
- **[C]** Seven components: the 4×4 grid (one composite element), the filled-cell set, the assumption-zone outline, the time arrow. Confirmed content: the four methods and the prototype test's confinement to the leftmost column follow the chapter's chart placeholder and the zero-delay argument. Inference to label: exact cell fills for the middle rows are reasoned approximations of the chapter's prose ("pilot and instrumentation phase," "delays," "week twelve, not minute twelve") — the caption must mark the middle-row coverage as schematic.
- **[O]** Reading order top-left; time increases rightward only (the time arrow is the sole arrow). The orange outline groups empty cells in the top row — it must enclose emptiness, not fill it; the cells inside stay white. No diagonal elements.
- **[P]** Flat vector. Okabe-Ito mapping: covered cells #0072B2 (primary measurement capacity), named-assumption zone #E69F00 (pending claims), grid and time arrow neutral gray. Deliberately no #D55E00: an unmeasured cell is a limit, not a failure. 1pt strokes. No text labels. Not a data chart — no axis values, and nothing implies magnitude; cells are binary covered/uncovered.
- **[E]** Exclude: numeric axis values; percentage fills or partial fills; heat-map color gradations; calendar or hourglass icons; checkmarks and X marks in cells; a fifth row or column; bar-chart rendering of any row.
- **Cognitive Load Check:** pass — binary fill, one highlighted region; the takeaway (top row is almost empty) is available pre-attentively.

**BLOCK 3 — NEGATIVE PROMPT:**
heat map gradients, partial cell fills, percentage marks, checkmarks, X marks, hourglass icons, calendar icons, numeric values, bar chart rendering, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

### Figure 5 — One Precious Prototype vs Five Cheap Hypotheses (rank: Supplementary; heuristic: VG)
**Concept (one sentence):** Serial refinement of a single prototype breeds commitment to it, while parallel creation of several cheap prototypes keeps them hypotheses and yields more divergent exploration and better-rated final designs (Dow et al. 2010).
**Figure type:** Two-panel comparison

**BLOCK 1 — ILLUSTRAE PASTE BLOCK:**
Create a flat vector two-panel comparison on a white background, panels side by side and equal in size, each reading left to right. In the left panel, draw a single row of three rectangles connected by right-pointing arrows, each rectangle larger and more thickly stroked than the last, all in orange #E69F00, with the final largest rectangle enclosed by a tight second outline hugging its border, representing one prototype refined serially until it accretes commitment and becomes an identity. In the right panel, draw five small rectangles of identical size in sky blue #56B4E9 arranged as a vertical fan on the left side, with five thin arrows converging rightward to a single comparison point drawn as an open diamond outline in bluish green #009E73, from which one arrow continues right to a single medium rectangle in bluish green, representing five cheap parallel prototypes meeting at an evaluative choice that selects one direction. Keep total ink in the two panels visually comparable so neither reads as the elaborate option. Use 1pt strokes, flat fills, and no text labels.

**BLOCK 2 — FULL SCOPE PROMPT:**
- **[S]** Single column, 89mm width, 300 DPI minimum, vector, white background.
- **[C]** Two panels of three component groups each (≤8 total): serial chain with commitment outline; parallel fan, comparison diamond, selected outcome. Confirmed content: the serial-vs-parallel contrast and its direction are Dow et al. (2010) as cited. Inference to label: "five" prototypes echoes the chapter's "five cheap ones stay hypotheses" rhetoric, not a prescribed count — caption should note the number is illustrative.
- **[O]** Both panels flow left to right with → arrows only. The double outline on the serial endpoint is the commitment signature; the open diamond is the decision point. Panels must be the same width so the comparison is structural, not areal.
- **[P]** Flat vector. Okabe-Ito mapping: serial path #E69F00 (seductive but weaker strategy), parallel prototypes #56B4E9 (instruments), comparison point and selected outcome #009E73 (active method). No #D55E00 — serial refinement is suboptimal, not forbidden. 1pt strokes. No text labels.
- **[E]** Exclude: trash icons on unselected parallel prototypes (they are retained hypotheses, not waste); trophy or medal on the outcome; heart or padlock icons literalizing "identity"; numeric ratings; any third panel.
- **Cognitive Load Check:** pass — two familiar gestalts (chain vs fan) carrying one contrast.

**BLOCK 3 — NEGATIVE PROMPT:**
trash can icons, trophy icons, medals, hearts, padlocks, numeric ratings, star ratings, text labels, words, gibberish letters, titles, captions, decorative borders, realistic textures, plastic wrap effects, drop shadows, gradient backgrounds, photographic elements, non-standard arrows, dual-headed arrows, hand-drawn styles, sketch lines, human figures, visual clutter, overlapping unaligned paths, fuzzy borders, watermarks, red-green color combinations, rainbow color scales, 3D perspective distortion

---

## Video candidate pass

| Figure | Status | Criterion | Reason |
|---|---|---|---|
| Fig 1 — Fidelity ladder | Not a candidate | Static structure | The ladder is a decision map consulted, not a process watched; animating ascent would actively undermine the chapter's "do not climb by default" argument. |
| Fig 2 — Four-channel probes | Not a candidate | Simultaneous comparison | Probe depths are compared at a glance; sequencing them in time would falsely imply an order of operations. |
| Fig 3 — Prototype–test cycle | Candidate | Iterative process over time | The loop is inherently temporal, and its hardest teaching — the demotion move, where a built artifact is shelved and the question travels back down the ladder — is a plot event that animation renders as narrative cause-and-effect. |
| Fig 4 — Timescale coverage | Candidate (weak) | Time axis present | Time elapses along the x-axis, but the figure's content is coverage, not change; a static matrix already delivers the empty-cells punchline. |
| Fig 5 — Parallel vs serial | Not a candidate | Categorical comparison | Two strategies compared side by side; no temporal mechanism beyond what the arrows already encode. |

**2 candidates. Recommended for production: Figure 3 — the prototype–test cycle.** Rationale: the cycle is the chapter's procedural core and the worked example already supplies a complete animation script — Storyline build, polish accumulating, tester commenting on chart colors, the shelving, the index cards, the wrong-reason-right-answer catch, the revision, fresh learners. One trip around the loop with the demotion chord firing makes the chapter's least intuitive permission ("going down the ladder is progress") emotionally legible in a way no static cycle diagram achieves. Figure 4's time axis is decorative by comparison; its claim is about absence, which animation cannot show better than an empty cell.
