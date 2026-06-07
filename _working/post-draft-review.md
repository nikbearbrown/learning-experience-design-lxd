# Post-Draft Review — learning-experience-design-lxd
*Everything executed after the 15 chapter drafts, audited · 2026-06-07*

---

## Headline finding: two versions of this book are interleaved, and it needs your call

While auditing anatomy completeness I found that **ten chapters (1, 2, 4, 5, 7, 8, 10, 11, 13, 14) no longer contain the mandated anatomy sections** — Evidence Box, Mid-Chapter Checkpoint, Worked Example, Evidence Disclosure, What Would Change My Mind, Still Puzzling, Chapter Summary, Key Terms, Bridge, Further Reading. Chapters 3, 6, 9, 12, 15 still have them.

The git history explains it. This is **not** agent damage:

| Time (today) | Event |
|---|---|
| 13:11 | Commit `31fbaf6 "LXD"` — the 15 original drafts, full 17-section anatomy, word counts matching logs/log.csv exactly (e.g. Ch1 = 5,625) |
| 13:17–13:51 | Fifteen per-chapter **"Update NN-…md" commits** — rewritten, heading-light, condensed versions (e.g. Ch1 = 3,503 words; no exercise blocks, no figure refs). These came from your side of the sync (the per-file "Update" commit style suggests GitHub web edits or your own pipeline) |
| after | My later passes (exercise blocks, theme weave, Hattie, figure enrichment, fact-check, corrections) layered onto whatever was on disk — which, mid-stream, became the condensed versions |

So the current chapters = **your condensed bodies + my exercise blocks + figures + anchors + corrections**, and the original full-anatomy bodies survive intact in git at `31fbaf6`. Nothing is lost — but the book is currently a hybrid: five chapters in the original full-anatomy style, ten in the condensed style, all fifteen wearing the later passes.

**Decision needed (yours, not mine):**
1. **Condensed style wins** — accept your revisions as the canonical body; restore selectively only the sections that downstream passes depend on (the Evidence Boxes that fact-check verdicts reference; the Evidence Disclosures the exercise blocks point at); restyle chapters 3/6/9/12/15 to match.
2. **Full anatomy wins** — restore the `31fbaf6` bodies and re-apply your condensations as edits where they tightened prose; everything later (blocks, figures, fact-check) ports cleanly.
3. **Hybrid by design** — keep as is, but then the TikTOC Part 9 anatomy spec and the exercise blocks' internal references ("the chapter's Evidence Disclosure") need reconciling for the ten chapters.

I have not acted on any of these. Every later pass below was verified against the *current* files.

---

## Pass-by-pass audit

### 1. Post-write cleanup — ✅ sound
Stubs in `_working/`, `logs/log.csv` accurate against the original drafts (verified above — its word counts match `31fbaf6` exactly, which is what made the timeline reconstructable). No issues.

### 2. Running-project exercise blocks — ✅ sound, one inconsistency
All 15 five-part blocks present and verified (Exercise 1–5, AI Use Disclosure prompts, standard "tells" verbatim). Old standalone LLM Exercises correctly subsumed — 0 strays. **Found:** the canonical dossier map defines 15 files but chapters reference **16 unique dossier paths** — one agent introduced `dossier/15-core-sections.md` (Ch15's verbatim-only learner sections) beyond the canon. Defensible addition, but it should be added to the Ch15 block's setup checklist as an explicit prerequisite or renamed into the canon. Minor.

### 3. CAJAL scan — ✅ sound
15 reports, 77 figures, refusal discipline held (declined to chart `[verify]`-flagged numbers). The Ch11 report inherited the chapter's source misrepresentation — caught later by the fact-check chain and corrected via addendum. Acceptable: the scan's job was scoping, not verification.

### 4. SVG generation — ✅ sound, two cosmetic items
77/77 SVGs + PNGs, style-guide conformant, honest captions. Items: (a) Ch12 fig-01's "≈0" label collides slightly with the baseline annotation — cosmetic QA sweep candidate; (b) figure numbering follows CAJAL order, not reading order, in Ch3/4/6/11 — fix is renaming assets, offered earlier, still open.

### 5. Theme weave + appendix — ✅ sound
18 anchors verified present; restraint held (Ch2 untouched, Ch15 closing protected). Appendix carries the register note and theme map. One unresolved editorial note from the fact-check: the taxonomy table says "Tiers 1, 4–7" while the body also includes a Tier 2 section — confirm the skip of Tier 3 (and 2's status) is intentional in the source framework.

### 6. Hattie insertions — ✅ sound
Two anchors, both verified accurate against the cluster data (0.79/0.54/0.50 match G27/G20/G34). Cross-reference to *Visible Learning × AI* is real.

### 7. Figure enrichment + build repair — ✅ sound
77/77 referenced exactly once, 0 duplicates, 0 missing files, 25 TABLE placeholders preserved. build.sh upgraded to the QM pattern (this was a genuine latent bug — images silently not embedding). Epub: 78 images, 14.6 MB. **Open:** cover.jpg is my placeholder; ISBN unfilled; **00-frontmatter still contains `[PREFACE PLACEHOLDER]` and 99-back-matter is a 5-placeholder template skeleton** — the front/back-matter authoring pass that the QM books received was never run on this book. That's the largest content gap remaining.

### 8. Fact-check pass — ⚠️ sound process, one humbling lesson
18 reports, ~140 verifications, References sections on all files. **The lesson:** the Ch11 finding was itself one-third wrong — the checking agent worked from the abstract and confidently asserted the paper lacked the 31.1% figure and the moderator, both of which the full text contains. The repair agent caught it only because it fetched the full text before editing. Verdict-level claims need full-text verification, not abstract-level; the master report now documents its own error, which is the right outcome but cost a cycle. The four real corrections (Ch11 specifics, Ch4 Wang, Springer/Westerberg, venue) are applied and verified in the current files. 5 legitimate flags remain open (Zeng forest plot ×2, Ch2 bibliometric ×2, Ch10).

### 9. Corrections — ✅ applied and verified
Re-verified just now: 0 stray "Purdue UP" attributions (the one remaining mention is the correction note itself), Wang sentence softened, Ch11 opener tells the study straight with the regenerated four-condition figure, epub rebuilds clean.

---

## Cross-cutting observations

1. **The mid-session sync is the real process risk.** Twice today, files changed under running passes (your chapter revisions at 13:17–13:51; the AI-for-LXD notes files that "shrank" between passes — almost certainly the same mechanism, not corruption). When you're editing in parallel with a long Cowork session on the same synced folder, passes can layer onto moving targets. Cheap fix: commit before kicking off a multi-agent pass, and tell me when you've pushed revisions mid-session so I re-audit instead of assuming.
2. **TikTOC drift.** The TikTOC still says v1.0 / "Pre-proposal" and its Open Questions (title decision, Track A case choice, UDL reviewer) are unresolved, while reality has moved: project selected (Redesign Dossier), spine confirmed, corrections applied. Tik TOC's own /changelog discipline was never run. Worth one /changelog + /p2 update pass.
3. **metadata.yaml subtitle is empty** while the TikTOC carries one — trivial, but it feeds the epub title page.

## Punch list (priority order)

1. **Decide the chapter-style question** (full anatomy vs condensed vs hybrid) — blocks everything editorial.
2. Author the real 00-frontmatter (preface) and 99-back-matter — the templates are untouched.
3. Ch9 accessibility expert review (Risk 6 — still the proposal blocker).
4. Resolve the 5 open verify flags (Zeng forest plot is the load-bearing one).
5. Real cover; ISBN; metadata subtitle.
6. Optional: figure renumber sweep; Ch12 fig-01 label collision; dossier/15-core-sections canon fix; TikTOC changelog pass.

**Bottom line:** the pipeline after the drafts — exercises, figures, themes, fact-check, corrections, build — is verified internally consistent and the epub ships. The one structural issue is editorial, not mechanical: two versions of the book's body are interleaved because we were both writing it at once, and the choice between them is yours. Everything needed to execute either choice is preserved in git.
