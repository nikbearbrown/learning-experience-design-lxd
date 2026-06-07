# Master Fact-Check Report

**Book folder:** learning-experience-design-lxd (*Experience Design for EdTech — Evidence-Disciplined Learning Experience Design*)
**Date:** 2026-06-07
**Total chapters processed:** 18 files (frontmatter, 15 chapters, fundamental-themes appendix, back matter)
**Total files read:** 18
**Total assertions flagged:** ~190 across the book (per-chapter reports hold the itemized breakdown)
**Breakdown by content category (approx.):** STAT: 36 | GUIDELINE: 21 | APPROVAL: 0 (not an applicable category for this field) | EVIDENCE: 72 | SPECIALIST: 26 | CURRENT: 14
**Breakdown by assertion type:** dominated by BASIC and POSITIVE; a small number of EMPHATIC; several I-LANGUAGE in the appendix; no COMBINATION (emphatic + unhedged) sentences in the body chapters — the book's hedging discipline is itself the reason.

**Field adaptation note:** This is an education / learning-science book, so the biomedical default sources were replaced with PubMed, Google Scholar, ERIC, publisher pages (PNAS, BJET/Wiley, Frontiers, SAGE, Springer, ACM), and the field's standards bodies — CAST (udlguidelines.cast.org) for UDL, W3C/WAI for WCAG, ADL (adlnet.gov) for xAPI/SCORM, and EDUCAUSE for its surveys. The "APPROVAL" category has no analog here; "GUIDELINE" was repurposed for standards-and-current-practice claims (UDL 3.0, WCAG 2.2, xAPI spec, OLC scorecards).

---

## Overall Critical Findings

Sorted by priority. The book is unusually clean — its own `[verify]`/`[contested]` discipline caught most of what a fact-check would otherwise surface. Four items rise to genuine correction; the rest are confirmations or already-flagged caveats.

### 1. Chapter 11 — Touch-tank opening case MISREPRESENTS its source — **CONTRADICTED (CRITICAL)**
**Category:** EVIDENCE / STAT · **Verdict:** CONTRADICTED
**Sentence(s):** the opening narrative that hands-on touch-tank lessons outperformed 360° VR by 31.1%, with a cognitive-load mechanism analysis, a prior-XR-experience moderator, and a pre-training recommendation.
**Finding:** The cited study (Walters et al. 2026, *Frontiers in Education* 11:1774496) is real and correctly placed by venue/year, but it compared an oyster-reef **360° video** to hands-on activities (n=79), found the **video increased** learning, and concluded that **combining** media is best. There is no 31.1% gap, no cognitive-load mechanism analysis, no prior-XR moderator, and no pre-training recommendation in the paper. The chapter's own pre-freeze `[verify]` instinct was correct. **The chapter's underlying argument (immersion must repay its cost; interface load + novelty are the taxes) is independently supported by Sweller, Mayer, and the confirmed VR metas — the fix is surgical re-anchoring of the opener, not a structural rewrite.** Inline flags inserted.
**Resolution note (2026-06-07):** corrections applied — and full-text re-verification found this finding itself partially in error: the 31.1% figure, the prior-XR-use moderator (p = 0.02), the novelty-effect reading, and a pre-training suggestion (citing Howard & Lee 2020) **are** in the paper. What was genuinely wrong in the chapter: "VR rendering" (it was a filmed 360° video in headsets), invented animal details, a "mechanism analysis" the paper does not contain (its own reading is passive-vs-active media plus novelty), and omission of the combined condition and combine-media conclusion (360° video also beat the pre-test, 62.1% vs 43.2%; hands-on 83.6%; combined 79.6% ≈ hands-on). All corrected; see the Chapter 11 assertions file, Resolution section.

### 2. Chapter 4 — Wang et al. 2024 SDT meta-analysis OVERSTATED — **CONTRADICTED**
**Category:** EVIDENCE · **Verdict:** CONTRADICTED
**Sentence:** that the meta-analysis showed SDT-aligned design "reliably improved motivation, engagement, and academic outcomes — with effects that held across school levels and cultures."
**Finding:** The actual paper reports a *partially* significant effect (intrinsic motivation g≈0.58) and a **non-significant relatedness effect (g=0.44, p>0.05)**. Recommend softening — and the honest version actually *reinforces* the chapter's own "relatedness is hardest to support at scale" thesis. Inline flag inserted.

### 3. Chapter 15 (and recurring) — *Transdisciplinary LXD* volume publisher is WRONG — **CONTRADICTED**
**Category:** EVIDENCE · **Verdict:** CONTRADICTED (publisher only)
**Sentence:** Further Reading cites the 2025 *Transdisciplinary Learning Experience Design* volume as "(Purdue University Press, 2025)."
**Finding:** The book is real but published by **Springer** (eds. Schmidt, Earnshaw, Exter, Tawfik, Hokanson; DOI 10.1007/978-3-031-76293-2). Purdue is one editor's institution — the likely source of the slip. This characterization recurs in the TikTOC and pantry synthesis; correct it everywhere. Also: Ch15 Further Reading lists "Westerberg, C." — should be **Tyler J. Westerberg**. Inline flag inserted.

### 4. Chapter 11 — Venue error on the immersive-tech review — **CONTRADICTED (minor)**
**Category:** STAT · **Verdict:** CONTRADICTED
**Sentence:** "18 of 33 studies positive" attributed to "Frontiers in Education, 2024."
**Finding:** That finding belongs to *Emerging Science Journal* (April 2024), not Frontiers in Education. Inline flag inserted.

---

## Confirmed Load-Bearing Claims (the spine held)

Every cornerstone citation verified real and correctly attributed:
- **Bastani et al. 2025 PNAS** — +48% / +127% practice, −17% unassisted exam: exact match. The August 2025 PNAS correction is **affiliation-only** (no figures changed) — confirmed.
- **Zeng et al. 2024 BJET** gamification g = 0.782 across 22 studies — confirmed (the "two negative studies" / n=3,144 sub-detail needs a forest-plot check; flagged UNVERIFIED in Ch1 and Ch10).
- **CAST UDL 3.0** — July 2024, three principles, nine guidelines, 36 considerations: the chapter's "3 × 9 × 36" is exact. **WCAG 2.2** confirmed as current W3C Recommendation (3.0 still a Working Draft).
- **xAPI vs SCORM** (actor-verb-object, LRS, ADL stewardship) — verified against the ADL spec.
- **EDUCAUSE 2025 ROI QuickPoll** 71% / 46% — confirmed (71% = "at least moderately important," n=124).
- **Tutor CoPilot** (Wang et al. 2024, arXiv:2410.03017) +4pp / +9pp / $20-per-tutor — verbatim.
- **Stanford SCALE ~20-in-800** — confirmed (repository has since grown, widening the gap).
- Hirsh-Pasek 2015, Meyer 2021, Soderstrom & Bjork 2015, Fredricks 2004, Mayer 2021, Rey 2012, Cepeda 2006, Roediger & Karpicke 2006, Karpicke & Blunt 2011 (correct direction), Sweller 1988/2019, Kalyuga, Deci/Koestner/Ryan 1999, Lepper/Greene/Nisbett 1973, Hanus & Fox 2015, Kornell & Bjork 2008, Deslauriers et al. 2019, Arnstein 1969, Sanders & Stappers 2008, Druin 2002, Dow et al. 2010, Gould & Lewis 1985, Nielsen & Landauer 1993, Capp 2017, Edyburn 2010, Gernsbacher 2015, O'Neil 2016, Reichheld 2003, Kirkpatrick 1959/2016, Corbett & Anderson 1994, Strathern 1997 (Goodhart) — all confirmed.
- Both Ch3 `[verify]` markers resolved to real papers: **Chen et al. 2018** (*Frontiers in Psychology* 9:1483) and the embodied-learning meta → **Lyu & Deng 2024** (*Learning and Individual Differences* 116:102564, g≈0.52). **King-Sears et al.** UDL meta resolved to *Teaching and Teacher Education* (2023), g = 0.43. **Chang et al. 2025** co-design resolved to *Computers and Education: AI*.

---

## Resolved `[verify]` markers needing prose tightening (not errors, but tighten before freeze)

- **Ch1 / Ch10 — Zeng "two negative studies" + n=3,144:** confirmable headline, unconfirmable sub-details from the abstract — verify against the forest plot or soften.
- **Ch2 — the unnamed "bibliometric review"** of LXD's borrowing-without-consolidation and the unprovable-negative "no direct comparative study exists": both UNVERIFIED; reword or source.
- **Ch4 — the 31/47/57% engagement-variance figures:** trace to a single LXD study that attributes the variance to three traits *jointly*, not task value alone; direction holds, the ranking does not.
- **Ch14 — Alliger et al. 1997:** study and direction confirmed, but the "near zero" correlation is true only of the *affective* reaction subtype (utility reactions correlate more strongly) — the chapter's hedge keeps it accurate; a future editor must NOT tighten it into an unhedged claim.
- **Ch13 — clickstream time-on-task validity:** supported at the synthesis level claimed; anchor one named primary study.

## Watch-outs for future editors (do NOT "correct" these)

- **Ch1 Exercise 5 contains deliberately fabricated citations** ("Hartman and Liu 2019," "Journal of Digital Pedagogy," g = 1.28, an inverted Karpicke & Blunt) — these are planted pedagogical errors with an answer key. They are not real errors and must survive.
- **Ch12 — Loewen et al. 2020 is the Babbel app, not Duolingo.** The chapter prose is correct; don't let "Duolingo" migrate in from notes.
- **Ch97 (appendix)** is deliberately in manifesto register (its own preamble says so). The dopamine/BDNF/dendritic-spine chain is defensible component-by-component but overdrawn as a strict universal "no friction → no learning" mechanism; the Kosmyna "up to 55%" connectivity figure is confirmed but rests on a non-peer-reviewed n=54 preprint with published criticism (already flagged in-book). Per the manifesto-register rule, these were documented here but NOT flagged inline.

---

## Chapter-by-Chapter Summary

| Chapter File | Flagged | Critical | Outdated | Contradicted | Unverified | Confirmed |
|---|---|---|---|---|---|---|
| 00-frontmatter | 0 | 0 | 0 | 0 | 0 | 0 |
| 01-the-engagement-trap | 14 | 0 | 0 | 0 | 1 | 13 |
| 02-discipline-and-borders | 9 | 0 | 0 | 0 | 2 | 7 |
| 03-cognitive-machinery | 14 | 0 | 0 | 0 | 5* | 12 |
| 04-motivation-by-design | 13 | 1 | 0 | 1 | 1 | 11 |
| 05-learner-research | 9 | 0 | 0 | 0 | 5* | 6 |
| 06-journey-mapping | 14 | 0 | 0 | 0 | 8* | 6 |
| 07-co-design | 13 | 0 | 0 | 0 | 5* | 8 |
| 08-prototyping | 12 | 0 | 0 | 0 | 5* | 7 |
| 09-variability-UDL | 18 | 0 | 0 | 0 | 1 | 17 |
| 10-gamification | 14 | 0 | 0 | 0 | 1 | 13 |
| 11-immersive-embodied | ~12 | 2 | 0 | 2 | 1 | 8 |
| 12-AI-scaffold-or-crutch | 14 | 0 | 0 | 0 | 0 | 14 |
| 13-instrumenting | 10 | 0 | 0 | 0 | 1 | 9 |
| 14-evaluating | 9 | 0 | 0 | 0 | 1 | 8 |
| 15-full-redesign | 8 | 1 | 0 | 1 | 1 | 6 |
| 97-fundamental-themes | 6 | 0 | 0 | 0 | 3 | 3 |
| 99-back-matter | 0 | 0 | 0 | 0 | 0 | 0 |

\* "Unverified — not prioritized": low-priority items deliberately deferred under the per-chapter verification budget, not failed checks.

Inline `<!-- FACT-CHECK FLAG -->` comments inserted: Ch1 (1), Ch2 (2), Ch4 (2), Ch10 (1), Ch11 (3), Ch15 (1). `## References` sections appended to all 18 files (CONFIRMED references only; placeholders where none).

---

## Recommended Next Steps

The book is in strong factual shape — a direct consequence of its own evidence discipline, which front-loaded the `[verify]`/`[contested]` markers that this pass then resolved. **The single most urgent item is Chapter 11's opening touch-tank case, which misrepresents its cited study (no 31.1% gap, wrong direction, invented mechanism details); re-anchor the opener to the confirmed VR metas and Sweller/Mayer load theory — the chapter's argument survives intact.** Second, propagate the *Transdisciplinary LXD* publisher correction (Springer, not Purdue UP) and the Westerberg initial across Ch15, the TikTOC, and the pantry synthesis. Third, soften the Chapter 4 Wang et al. 2024 SDT claim to match the paper's partial/non-significant relatedness result — a change that strengthens rather than weakens the chapter. The categories that produced the most flags were EVIDENCE (named-study attributions) and STAT (effect sizes), exactly where a quantitative-evidence textbook concentrates its risk; both held up well. No GUIDELINE/standards claim (UDL, WCAG, xAPI) was outdated. Overall reliability: high — three genuine corrections and a handful of tighten-before-freeze caveats across ~190 assertions, with no fabricated citations found anywhere in the book's own prose.
