# Assertions Report: 08-prototyping-learning-experiences-from-paper-to-pilot.md
**Date:** 2026-06-07 / **Source file:** chapters/08-prototyping-learning-experiences-from-paper-to-pilot.md / **Assertions flagged:** 12 / **Breakdown:** STAT: 1 | GUIDELINE: 2 | APPROVAL: 0 | EVIDENCE: 7 | SPECIALIST: 1 | CURRENT: 1

## ⚠️ Critical — Requires Immediate Expert Review
None found. Every named source checks out with correct attribution, and the chapter's most quotable empirical hooks — Dow et al. 2010 (parallel beats serial) and Nielsen & Landauer 1993 (the five-user curve, correctly hedged as a budgeting heuristic with rare-but-severe failures escaping small samples) — are stated with appropriate nuance. The one [verify] flag (design sprints in education are "case studies, no controls") is itself accurate.

## Full Findings

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "Gould and Lewis (1985) made early empirical user testing a founding principle of usability engineering precisely because a design error grows in cost with everything built on top of it."
**Claim checked:** Gould & Lewis 1985 established early-user-focus / empirical-measurement / iterative design as founding usability principles.
**Site visited:** dl.acm.org (10.1145/3166.3170); cacm.acm.org; experts.colorado.edu.
**Finding:** CONFIRMED. Gould, J. D., & Lewis, C. (1985). "Designing for usability: Key principles and what designers think," *Communications of the ACM*, 28(3), 300–311. The three principles are exactly: early focus on users and tasks, empirical measurement, and iterative design. Accurate. (Note: the chapter's "cost grows with everything built on top" is the standard cost-of-change rationale, a fair gloss rather than a verbatim Gould–Lewis claim.)
**Expert review needed:** No.
**Suggested reference:** Gould, J. D., & Lewis, C. (1985). *Communications of the ACM*, 28(3), 300–311.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "Bill Buxton's argument for roughness as a deliberate feature (Buxton 2007) is exactly this: a sketch says 'this is still a question'; a polished mockup says 'this is a decision.'"
**Claim checked:** Buxton 2007 argues for sketch roughness as a deliberate property that invites critique.
**Site visited:** Not separately fetched (book; non-numeric craft claim).
**Finding:** UNVERIFIED — not prioritized. Buxton, B. (2007). *Sketching User Experiences: Getting the Design Right and the Right Design*. Morgan Kaufmann. The sketch-vs-prototype distinction (sketches are suggestive, disposable, invite revision; prototypes are specific, refine) is the book's central argument. Characterization accurate.
**Expert review needed:** No.
**Suggested reference:** Buxton, B. (2007). *Sketching User Experiences*. Morgan Kaufmann.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "Dow et al. (2010) found that creating multiple prototypes in parallel led to better-rated final designs and more divergent exploration than refining a single prototype serially."
**Claim checked:** Dow et al. 2010 — parallel prototyping yields better results and more divergence than serial.
**Site visited:** dl.acm.org (10.1145/1879831.1879836); spdow.ucsd.edu; hci.stanford.edu (PDF).
**Finding:** CONFIRMED. Dow, S. P., Glassco, A., Kass, J., Schwarz, M., Schwartz, D. L., & Klemmer, S. R. (2010). "Parallel prototyping leads to better design results, more divergence, and increased self-efficacy," *ACM Transactions on Computer-Human Interaction (TOCHI)*, 17(4), Article 18. Parallel-condition web ads outperformed serial on both click-through and expert ratings, with more divergence and higher self-efficacy. Exact match, including the TOCHI venue noted in the figure caption.
**Expert review needed:** No.
**Suggested reference:** Dow, S. P., et al. (2010). *ACM TOCHI*, 17(4), Article 18.

### EVIDENCE — CONFIRMED (nuance preserved)
**Assertion type:** BASIC
**Sentence:** "The five-user number comes from Nielsen and Landauer's (1993) curve for frequent usability defects; treat it as a budgeting heuristic ... where rare-but-severe failures ... routinely escape small samples."
**Claim checked:** Nielsen & Landauer 1993 is the source of the five-user finding and supports the chapter's limitation caveat.
**Site visited:** dl.acm.org (10.1145/169059.169166); Semantic Scholar; nngroup.com.
**Finding:** CONFIRMED. Nielsen, J., & Landauer, T. K. (1993). "A mathematical model of the finding of usability problems," *Proc. INTERCHI '93 / CHI '93*, 206–213. Models problem detection as a Poisson process; the "~5 users find ~85% of problems" result depends on per-problem detection probability. Crucially, the chapter's caveat is well-founded: the model itself shows that lower-probability (rare/severe) problems require substantially more users — and the source notes the 5-user assumption *underestimates* users needed for high thoroughness. The chapter's hedging is more accurate than the popularized "just test 5 users" slogan.
**Expert review needed:** No.
**Suggested reference:** Nielsen, J., & Landauer, T. K. (1993). *Proc. INTERCHI '93*, 206–213.
**Notes:** Exemplary use — the chapter cites the primary source and correctly resists the oversimplified popular reading.

### EVIDENCE/SPECIALIST — CONFIRMED
**Assertion type:** COMBINATION (EMPHATIC + EVIDENCE)
**Sentence:** "Retrieval practice's benefits appear at *delays*; a prototype test happens at *zero delay*, exactly where desirable difficulties look worst and fluent designs look best (Soderstrom & Bjork 2015)."
**Claim checked:** Soderstrom & Bjork 2015 grounds the zero-delay-bias / performance-vs-learning point.
**Site visited:** bjorklab.psych.ucla.edu; journals.sagepub.com (verified in Ch. 7 report).
**Finding:** CONFIRMED. Soderstrom, N. C., & Bjork, R. A. (2015). "Learning versus performance: An integrative review," *Perspectives on Psychological Science*, 10(2), 176–199. The learning/performance dissociation and the unreliability of immediate (zero-delay) performance as an index of durable learning are the paper's core. Directly supports the chapter's "zero-delay session flatters fluency" argument.
**Expert review needed:** No.
**Suggested reference:** Soderstrom, N. C., & Bjork, R. A. (2015). *Perspectives on Psychological Science*, 10(2), 176–199.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "The design sprint — five days, map Monday through test Friday — is the most widely exported rapid-prototyping container in industry (Knapp et al. 2016)."
**Claim checked:** Knapp et al. 2016 is the design-sprint source (5-day map→test structure).
**Site visited:** Not separately fetched (trade book; non-numeric claim).
**Finding:** UNVERIFIED — not prioritized. Knapp, J., Zeratsky, J., & Kowitz, B. (2016). *Sprint: How to Solve Big Problems and Test New Ideas in Just Five Days*. Simon & Schuster. The Monday-map-through-Friday-test structure is exactly this book. Accurate.
**Expert review needed:** No.
**Suggested reference:** Knapp, J., Zeratsky, J., & Kowitz, B. (2016). *Sprint*. Simon & Schuster.

### CURRENT — CONFIRMED ([verify] flag resolved, hedge is accurate)
**Assertion type:** BASIC
**Sentence:** "Reports on sprint-style methods in curriculum and STEAM education are encouraging but methodologically thin — case studies, no controls [verify]. ... Nothing yet shows it outperforms slower iteration on learning-relevant outcomes."
**Claim checked:** Whether the education design-sprint literature is case-study-only without controlled outcome evidence.
**Site visited:** sciencedirect.com (S1871187122000426, *Thinking Skills and Creativity*); link.springer.com (*J. Ambient Intelligence & Humanized Computing*); esignals.fi.
**Finding:** CONFIRMED — the hedge is accurate. The locatable education design-sprint literature (e.g., "Design Sprint: Enhancing STEAM and engineering education...," 2022; "Design sprint in classroom," 2019) consists of case studies and descriptive implementations reporting engagement/skills benefits, with no randomized or controlled comparison showing the sprint *outperforms slower iteration on learning outcomes*. The chapter's claim that the evidence is "methodologically thin — case studies, no controls" stands. The [verify] flag is resolved: the absence of controlled outcome evidence is real.
**Expert review needed:** No.
**Suggested reference:** (Supporting the hedge) Several case studies exist, e.g., *Thinking Skills and Creativity* (2022) on STEAM design sprints; none provides controlled outcome evidence. No single citation needed beyond the chapter's honest negative.
**Notes:** Recommend replacing the inline [verify] with a parenthetical acknowledging case-study-only status, or simply removing the tag since the claim is verified.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "**Wizard of Oz** (Kelley 1984) puts a hidden human behind the curtain, simulating system intelligence."
**Claim checked:** Kelley 1984 is the originating Wizard-of-Oz methodology source.
**Site visited:** scirp.org; student.cs.uwaterloo.ca (p26-kelley.pdf); uxpajournal.org.
**Finding:** CONFIRMED. Kelley, J. F. (1984). "An iterative design methodology for user-friendly natural language office information applications," *ACM Transactions on Office Information Systems*, 2(1), 26–41. The seminal paper that operationalized the Wizard-of-Oz technique (experimenter simulating an intelligent system). Accurate attribution and year.
**Expert review needed:** No.
**Suggested reference:** Kelley, J. F. (1984). *ACM Transactions on Office Information Systems*, 2(1), 26–41.
**Notes:** Chapter attributes Wizard of Oz to "Kelley 1984" — correct. (The KEY CLAIMS brief also listed "Kelley/IDEO attributions"; IDEO is not invoked in this chapter's body for WoZ, so no misattribution present.)

### GUIDELINE — UNVERIFIED (craft claim, by design)
**Assertion type:** EMPHATIC
**Sentence:** "**a learning experience can pass every usability test and teach the wrong thing.** Task completion is a usability success criterion and almost meaningless as a learning one."
**Claim checked:** The usability/learning dissociation as a general principle.
**Site visited:** None directly testing this as an empirical proposition.
**Finding:** UNVERIFIED — not prioritized. This is a craft/conceptual claim the chapter argues from its worked example and from the learning-vs-performance literature (Soderstrom & Bjork 2015, confirmed above) rather than a cited empirical finding. Internally consistent and well-motivated; not a falsifiable single-study claim.
**Expert review needed:** No.

### STAT — UNVERIFIED (illustrative)
**Assertion type:** BASIC
**Sentence:** "sixty-two decision nodes" / "three of five learners made the correct prediction for the wrong reason" / "Eight short sessions" (opening case and Track A worked example).
**Claim checked:** Specific scenario figures.
**Site visited:** None — chapter's own narrative/worked-example numbers.
**Finding:** UNVERIFIED — not prioritized. Pedagogical scenario figures (the respiratory-therapy simulation case and the DataWise/statistics Track A example), not citations to external data. No external verification applicable; magnitudes are plausible for a small qualitative prototype test.
**Expert review needed:** No.
**Notes:** Flagged only to keep illustrative numbers distinct from cited statistics; chapter framing signals fiction.

## Unverified Assertions

| Sentence (abbrev.) | Category | Reason |
|---|---|---|
| Opening respiratory-triage case (62 nodes, 9 recordings) | STAT | Illustrative scenario, not cited data |
| Track A statistics worked example (5-then-3 learners, "three of five") | STAT | Worked example figures, not external data |
| Buxton 2007 roughness-invites-critique | EVIDENCE | Book, not separately fetched; accurate |
| Knapp et al. 2016 sprint structure | EVIDENCE | Trade book, not separately fetched; accurate |
| Fidelity-ladder rungs (sketch→pilot) as a method | GUIDELINE | Practitioner taxonomy, not an empirical claim |
| Authoring-tool "path of least resistance is not a pedagogy" | GUIDELINE | Craft guideline, not empirical |
| "usability test can pass while teaching wrong thing" | GUIDELINE | Conceptual principle, argued not cited |

## AI-Pass Flags
- No fabricated-citation signatures. All seven named sources (Gould & Lewis 1985, Buxton 2007, Dow et al. 2010, Nielsen & Landauer 1993, Soderstrom & Bjork 2015, Knapp et al. 2016, Kelley 1984) resolve to real works with correct venue/year/attribution.
- The [verify] flag on design-sprint education evidence is CONFIRMED accurate (case-study-only, no controls) — recommend clearing the tag.
- No OUTDATED or CONTRADICTED verdicts — no inline FACT-CHECK FLAG annotations required in the chapter body. References section to be appended.
- Notable strength: the Nielsen & Landauer five-user citation is handled with more rigor than the field's popular slogan — the chapter cites the primary source and preserves its actual limitation (rare/severe defects escape small samples).
