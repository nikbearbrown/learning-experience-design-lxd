# Second-Pass Rewrite — Change Log
*Executed 2026-06-07 from "Experience Design for EdTech — Second Pass Rewrite Notes" (post deep-research evidence audit).*
*All 27 instructions executed. 17 chapter files modified. Repo is git-tracked — `git diff` shows every change.*

## Instruction-by-instruction record

| # | File | Action | Status |
|---|---|---|---|
| 0 | all chapters | Retraction check: Wang & Fan (2025) / *Humanities and Social Sciences Communications* | **CLEAN — no matches anywhere; nothing removed** |
| 1 | 00-frontmatter.md | Replaced `[PREFACE PLACEHOLDER]` with 4-paragraph preface (~640 words): AI-tutor scenario + LearnLM admission; why-now (86% DEC stat); pedagogical-design thesis (Bastani vs. Kestin); evidence standard incl. Wang & Fan retraction as disclosure example | Done |
| 2 | 01 | "Down the hall…" AI-tutor parallel case inserted after opening paragraph | Done |
| 3 | 01 | AI-tutor market-selection sentence appended to clickbait paragraph | Done |
| 4 | 01 | Closing two sentences replaced with "most important person in the room" version | Done |
| 5 | 01 | GLP framing passage inserted | Done — see deviation D1 |
| 6 | 01 | "The Broken Chain" inserted as blockquote callout immediately after the GLP passage | Done |
| 7 | 02 | Fifth brief (AI product manager) added after "Four competent briefs. Four different deliverables. One product." | Done |
| 8 | 02 | AI-native delivery optimization-target paragraph added after the LXD target | Done |
| 9 | 03 | GLP Y1/Y7 bridge added after "What load theory cannot tell you…" closing paragraph | Done |
| 10 | 04 | Relational-levers / lower-ceiling paragraph added after closing calibration | Done |
| 11 | 05 | (a) Y2 error-trajectory paragraph after predict–explain–confront figure; (b) calibration pattern added to mandatory persona attributes | Done — see deviation D2 |
| 12 | 06 | (a) Y5 social-knowledge-texture indicator after reflection lane; (b) fourth triage test "Does this difficulty leave a trace in the data?" added; "Three tests" → "Four tests" | Done — see deviation D3 |
| 13 | 07 | Y5 personal-encounter-texture paragraph added after feedback-matrix / disposition record | Done |
| 14 | 08 | (a) Transfer + calibration probes added after the four channels; (b) "GLP trace hooks" added to Evidence Disclosure template | Done — see deviation D4 |
| 15 | 09 | AI accessibility-fixes note added in Exercise 2 (When NOT to Use AI), after Task 3 | Done |
| 16 | 10 | Teacher-as-amplifier closing paragraph added, with Hattie methodological qualifier inline | Done |
| 17 | 11 | Human-in-the-loop observation added after the modality resolution | Done |
| 18 | 12 | "The Landscape: Who Is Building AI Learning Products" section added before Bastani opening case (LearnLM, DEC 86%/66%, Bellwether) | Done — see flag F1 |
| 19 | 12 | Tutor CoPilot paragraph replaced with full "The Alternative Paradigm: AI Behind the Teacher" section: full numbers + working-paper flag, Kestin with all four caveats, design-is-the-variable resolution, five-row configuration table | Done — see flags F2, F3 |
| 20 | 12 | Three falsification conditions added to "What Would Change My Mind" | Done |
| 21 | 13 | "The GLP Friction Traces" section added after metric classes: seven-component table, Y1 time-on-task contrast, Y3+Y6 minimum-claim rule, Goodhart warning | Done |
| 22 | 14 | Artifact-decoupling framing added before the Forward case | Done — see flag F1 |
| 23 | 14 | Y6 spacing-effect gold-standard paragraph added to layer three | Done |
| 24 | 15 | (a) AI delivery chain added to required portfolio structure; (b) declined-AI-feature note added to peer-review protocol; (c) AI-delivery-chain statement added to final Evidence Disclosure requirements | Done |
| 25 | 97 | Neurobiological mechanism paragraph added after "No trigger, no consolidation," with preprint caveat on magnitudes | Done |
| 26 | 97 | Teacher-as-delivery passage (qualified Hattie + Tutor CoPilot + Kestin + synthesis) | Done — see deviation D5 |

## Deviations from the notes (minor, intentional)

- **D1 (Instr. 5):** Notes said "after the desirable difficulties section, before the closing warning." The effect-size literacy section sits between those two. The GLP passage went immediately after the Bastani/Frictional paragraph and directly before the closing "desirable is conditional" section — satisfying both constraints as nearly as the actual chapter structure allows.
- **D2 (Instr. 11b):** Notes called calibration pattern "a fourth mandatory attribute," but Ch5 already lists four mandatory categories. Added as a **fifth** mandatory attribute; "Y2 signal" rendered as "error-trajectory signal" for consistency with the Y2 paragraph just added.
- **D3 (Instr. 12b):** Changed "Three tests, in order" → "Four tests, in order" for consistency. Two artifacts still say three: **Figure 6.5's caption/image** (needs regeneration) and **Ch6 Exercise 5** ("Run the three triage tests"). Both need a follow-up touch.
- **D4 (Instr. 14b):** Notes said "sixth bullet," but the Ch8 template has seven numbered items. GLP trace hooks inserted as item 6; former items 6–7 renumbered to 7–8.
- **D5 (Instr. 26):** No existing teacher-as-delivery passage exists in 97-fundamental-themes.md, so nothing was replaced — the revised passage was **added** to "The Division of Labor" section (the closest home in the Humans + AI material).

## Flags for your review

- **F1 — Cold opens (Ch12, Ch14, editorial pushback):** Instructions 18 and 22 put new framing sections *before* the chapters' cold opens. Both chapters previously opened mid-scene (second-person Bastani; "You are the analyst, and you have until Friday"), and the book's signature move is the cold open. The insertions are applied as specified, but consider moving the Ch12 landscape section to just after the Bastani case, and the Ch14 decoupling frame to just after the Forward case, to preserve the openings.
- **F2 — Wang citation inconsistency (Ch12):** New section cites "Wang et al. (2025), Annenberg Institute working paper" per the notes; the chapter's Evidence Box row, Further Reading, and Reference #2 still say "Wang et al. 2024, arXiv:2410.03017." Same study, two labels. Pick one canonical citation before freeze.
- **F3 — New citations not yet in References:** Kestin et al. (2025) *Scientific Reports* and Jose et al. (2025) *Frontiers in Psychology* now appear in Ch12 (and Kestin in the Appendix) but have no reference entries. Also unreferenced: Google LearnLM (arXiv:2412.16429), Bellwether (Oct 2025), Digital Education Council survey (2024) — used in Preface, Ch1, Ch2, Ch12. All need entries in the next fact-check pass.
- **F4 — Jose et al. independence check (from the notes themselves):** the 17% figure matches Bastani exactly; verify the studies are independent before the Ch12 table ships citing both as separate confirmation. The table currently cites both.
- **F5 — GLP framework citation:** the GLP framework is now named in Ch1, 3, 5, 7, 8, 12, 13, 14 but never formally cited. If the GLP preprint should be in the references, add it in the fact-check pass.
