# CAJAL SVG Generator — Run Log

## Run: 2026-06-07T16:30:00 (approx)

Setup notes: metadata.yaml read (title "Experience Design for EdTech", author Nik Bear Brown; book-slug experience-design-for-edtech). node v22.22.0, sharp installed via npm install. `NEU/CLAUDE.md` and `brutalist/CLAUDE.md` do not exist in this book — generation followed the embedded Brutalist D3 SVG Style Guide in the generator prompt. images/ was empty: no collisions, no skips.

### Global deviations from SCOPE blocks (mandated by the style guide, applied uniformly)
1. Okabe-Ito palette in the cajal reports replaced by the Brutalist palette. Red #C8102E used for at most ONE highlighted/positive category per figure; all other categories ink/gray.
2. All negative/blocking/disruptive semantics moved off color onto structure: ⊣ terminator bars, dashed strokes, hollow markers, below-zero positioning, hatching. Red never encodes danger or negative values (several author red/green annotations in the reports were overridden accordingly).
3. The SCOPE blocks' "no text labels" rule targets the unannotated Illustrae pipeline; these SVGs carry visible pedagogical text per the style guide (EB Garamond titles, Inter labels/captions, JetBrains Mono numerics). ALL-CAPS source lines used only for genuine external attribution (Zeng, Bastani, EDUCAUSE, Deci & Ryan, Eccles & Wigfield).
4. No fabricated quantities: figures the reports marked schematic carry "schematic — no measured data" captions and unnumbered axes; charts declined by the reports (31/47/57%, Goodhart time-on-task, Ch9 Evidence Box, g = 0.524 dispersion) were NOT generated.
5. rx="0" squared all "rounded rectangle" requests.

### Per-chapter results

| Chapter file | Figures found | Generated | Skipped |
|---|---|---|---|
| 01-the-engagement-trap-…-cajal.md | 5 | 5 | 0 |
| 02-learning-experience-design-…-cajal.md | 5 | 5 | 0 |
| 03-the-cognitive-machinery-…-cajal.md | 6 | 6 | 0 |
| 04-motivation-by-design-…-cajal.md | 5 | 5 | 0 |
| 05-learner-research-…-cajal.md | 5 | 5 | 0 |
| 06-mapping-the-learning-journey-…-cajal.md | 5 | 5 | 0 |
| 07-co-design-…-cajal.md | 4 | 4 | 0 |
| 08-prototyping-…-cajal.md | 5 | 5 | 0 |
| 09-designing-for-variability-…-cajal.md | 5 | 5 | 0 |
| 10-gamification-under-evidence-…-cajal.md | 5 | 5 | 0 |
| 11-immersive-and-embodied-…-cajal.md | 5 | 5 | 0 |
| 12-ai-in-the-learning-experience-…-cajal.md | 6 | 6 | 0 |
| 13-instrumenting-the-experience-…-cajal.md | 5 | 5 | 0 |
| 14-evaluating-…-cajal.md | 5 | 5 | 0 |
| 15-the-full-redesign-…-cajal.md | 6 | 6 | 0 |

### Figure index (title · type)

Ch1: 01 dissociation crossover (statistical) · 02 three engagement dimensions (comparison) · 03 seductive-detail mechanisms (mechanism) · 04 heterogeneity dot plot g=0.782 (statistical) · 05 market selection loop (cycle)
Ch2: 01 four briefs / optimization targets (comparison 2×2) · 02 intellectual genealogy (timeline) · 03 experience five dimensions (conceptual) · 04 constraint test (flowchart) · 05 portfolio danger zone (quadrant)
Ch3: 01 working-memory budget (mechanism) · 02 desirable-difficulty signature (statistical) · 03 four-question friction diagnostic (flowchart) · 04 the fade / expertise reversal (crossover) · 05 ease/learning quadrant · 06 element interactivity (comparison)
Ch4: 01 overjustification displacement curve (statistical timeline) · 02 motivation quality continuum (spectrum) · 03 three-need leaderboard audit (systems) · 04 expectancy-value surface (quadrant) · 05 removal test (flowchart)
Ch5: 01 two documents one learner (comparison) · 02 predict-explain-confront (flowchart) · 03 amended empathy map (schematic) · 04 procedural-conceptual gap (scatter, qualitative) · 05 Track A research pipeline (flowchart)
Ch6: 01 journey map anatomy — flagship (annotated example, 600h) · 02 outline vs journey (comparison) · 03 budget stacking (schematic mechanism) · 04 line of visibility (cross-section) · 05 friction triage (decision tree)
Ch7: 01 three-layer decision rights (hierarchy) · 02 participation spectrum (comparison) · 03 fluency-learning inversion (conceptual) · 04 matrix→disposition pipeline (flow)
Ch8: 01 fidelity ladder (progression) · 02 four channels beneath the surface (schematic) · 03 prototype-test cycle + demotion chord (cycle) · 04 evaluation-timescale coverage (matrix) · 05 one precious vs five cheap (comparison)
Ch9: 01 three justification logics — equal tiers, ⊣ errors (stack, 480h) · 02 same premise opposite architectures (branching, 540h) · 03 four equity gates (flowchart) · 04 barrier-first audit (flow, 480h) · 05 UDL 3.0 shape (taxonomy, 480h) — Ch9 deliberately near-monochrome per report sobriety note
Ch10: 01 distribution behind the average — 22 studies, negative tail hollow-left of zero (dot plot) · 02 motivational crowding trajectories (line) · 03 leaderboard redistribution (comparison) · 04 SDT decomposition (flowchart) · 05 declined vs adopted (comparison)
Ch11: 01 touch tank vs VR + moderator (dot plot) · 02 two mechanisms one casualty (⊣ mechanism) · 03 working-memory allocation (proportion bars) · 04 five gates fail-fast (flowchart) · 05 pre-training prescription (process)
Ch12: 01 practice vs unassisted divergence, −17 below zero (paired dot) · 02 four bypassed operations (chain + bypass arc) · 03 evidence map + 20-in-800 inset (map) · 04 guardrailed channel, ⊣ blocked answers (systems) · 05 fading band (timeline) · 06 equity inversion (two-path, 480h)
Ch13: 01 two dashboards SCORM/xAPI (comparison, 480h) · 02 metric classes + no-impersonation ⊣ (taxonomy) · 03 xAPI statement anatomy + LRS (schematic, 480h) · 04 IRT logistic curve — documented latent-axis exception (statistical, 480h) · 05 Bayesian at-risk updating + intervention gate (flowchart)
Ch14: 01 three-layer mixed model + no-upward-substitution ⊣ (systems) · 02 one finding two registers (schematic, 480h) · 03 ROI gap 71/46 (bars, EDUCAUSE source line) · 04 confound table before unblinding (flowchart) · 05 satisfaction-learning dissociation — schematic whisker, no fabricated effect (comparison)
Ch15: 01 gallery vs argument (comparison) · 02 decision trace (flowchart) · 03 portfolio anatomy — ochre-bordered "no" trace (schematic, 540h) · 04 defensible "no" anatomy (annotated) · 05 overclaim invitation (flowchart) · 06 the book's arc (conceptual map, 480h)

## Summary
Total cajal.md files processed: 15
Total figures parsed: 77
Total SVGs generated: 77
Total skipped (already exist): 0
PNG conversion: run completed — 77 converted, 0 skipped (node SCRIPTS/svg-to-png.mjs, 300 DPI)
