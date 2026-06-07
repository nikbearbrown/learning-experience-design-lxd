# Fact-Check Refresh

**Book:** learning-experience-design-lxd  
**Date:** 2026-06-07  
**Scope:** Checked the current `chapters/` set, existing `factchecks/` reports, inline `[verify]` / `[contested]` markers, and a focused set of live authoritative sources for the highest-risk claims.

## Status

- Chapter files processed: 18
- Existing per-chapter assertion reports: 18
- Existing master report: `factchecks/MASTER_REPORT.md`
- Remaining inline `[verify]` / `[contested]` strings in chapter prose after cleanup: 0
- Freeze-time unresolved items are now centralized in `factchecks/MANUSCRIPT_FREEZE_CHECKS.md`
- Remaining doubled or missing assertion-report pattern problems: none found

The existing fact-check pass is structurally complete: every chapter file has a matching `*-assertions.md` report, and the master report summarizes the book-level findings. A follow-up cleanup pass removed resolved bracketed markers from chapter prose, converted contested items into ordinary prose, and centralized live research questions in `MANUSCRIPT_FREEZE_CHECKS.md`.

## Live Source Rechecks

### Chapter 11 oyster-reef / 360-degree video case

**Verdict:** CONFIRMED with caveats already reflected in the chapter.

The current chapter framing matches the live Frontiers article: Walters et al. report a 360-degree video condition, hands-on condition, and combined condition in an oyster-reef environmental outreach study. The key figures in the chapter are supported: pre-test 43.2%, 360-degree-video-only post-assessment 62.1%, hands-on-only 83.6%, and hands-on scoring 31.1% higher than the 360-degree experience. The source also supports the broader conclusion that combining immersive virtual content with hands-on opportunities is recommended rather than treating the study as a simple "VR fails" result.

**Source:** Walters et al. 2026, *Frontiers in Education*, "Immersive and experiential approaches in environmental outreach: a comparison of 360° video and hands-on learning." https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2026.1774496/full

### Chapter 4 SDT intervention meta-analysis

**Verdict:** CONFIRMED as currently softened in the chapter.

The chapter's current wording accurately avoids the previous overstatement. The live source supports the claim that SDT-based interventions show meaningful effects, including intrinsic motivation around g = 0.58, while relatedness did not reach statistical significance at g = 0.44, p > 0.05. This supports the chapter's point that relatedness is difficult to move at scale.

**Source:** Wang et al. 2024, "A systematic review and meta-analysis of self-determination-theory-based interventions in the education context." https://www.sciencedirect.com/science/article/pii/S0023969024000572

### Chapter 15 / TikTOC publisher for *Transdisciplinary Learning Experience Design*

**Verdict:** CONFIRMED corrected.

The book is published by Springer / Springer Nature, not Purdue University Press. The current chapter further-reading entry uses Springer, and the TikTOC language also uses Springer. The source page lists the DOI and Springer Nature Link record.

**Source:** *Transdisciplinary Learning Experience Design: Futures, Synergies, and Innovation*, Springer Nature Link. https://link.springer.com/book/10.1007/978-3-031-76293-2

### Chapter 10 gamification meta-analysis

**Verdict:** CONFIRMED at the headline level; fine-grained subclaims still require forest-plot-level verification before final freeze.

The Zeng et al. BJET article exists and supports the book's headline claim that a 2024 meta-analysis found positive academic-performance effects for gamification across 22 studies from 2008-2023, with Hedges' g around 0.782. The existing master report's caution still stands: details such as "two negative studies" and exact sample totals should be checked against the full paper/forest plot before removing all local cautions.

**Source:** Zeng et al. 2024, *British Journal of Educational Technology*, "Exploring the impact of gamification on students' academic performance: A comprehensive meta-analysis of studies from the year 2008 to 2023." https://bera-journals.onlinelibrary.wiley.com/doi/full/10.1111/bjet.13471

## Remaining Markers

The former `[verify]` and `[contested]` markers were treated in three groups:

1. **Resolved and cleared from prose:** items whose references now confirm the claim. Examples include several Chapter 11 XR/embodiment references and Chapter 12 Bastani / Tutor CoPilot figures.
2. **Contested by design, converted to prose:** items where the book intentionally teaches evidence uncertainty rather than presenting a settled verdict. Examples include UDL outcome evidence and LXD's disciplinary status.
3. **Still worth freeze-time review, centralized:** items where the fact-check reports advise a more precise source or softened phrasing. Examples include Chapter 13 time-on-task synthesis, Chapter 14 Alliger coefficient precision, and Chapter 10 leaderboard/gamification moderator details.

## Recommended Next Action

Before final manuscript freeze, run only the focused checks listed in `factchecks/MANUSCRIPT_FREEZE_CHECKS.md`.

No new contradiction was found in this refresh beyond the issues already documented in `MASTER_REPORT.md`.
