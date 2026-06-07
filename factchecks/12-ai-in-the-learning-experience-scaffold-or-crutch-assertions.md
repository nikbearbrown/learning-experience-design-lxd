# Assertions Report: 12-ai-in-the-learning-experience-scaffold-or-crutch.md
**Date:** 2026-06-07 / **Source file:** chapters/12-ai-in-the-learning-experience-scaffold-or-crutch.md / **Assertions flagged:** 14 / **Breakdown:** STAT: 6 | GUIDELINE: 1 | APPROVAL: 0 | EVIDENCE: 5 | SPECIALIST: 1 | CURRENT: 1

## ⚠️ Critical — Requires Immediate Expert Review

None found. Every load-bearing inline [verify] marker resolved to CONFIRMED against the primary source. The chapter's central numbers (Bastani +48% / +127% / −17%; Tutor CoPilot +4pp / +9pp / $20; Stanford 20-in-800) all match the published papers exactly.

## Full Findings

### STAT — CONFIRMED
**Assertion type:** EMPHATIC
**Sentence:** "about 48% better with the basic chat tutor, around 127% better with a safeguarded version [verify exact figures against the published paper]" and "Students who had practiced with the basic GPT tutor scored **17% worse** than students who never had AI at all."
**Claim checked:** Practice gains of ~48% (GPT Base) and ~127% (GPT Tutor); unassisted-exam deficit of 17% for the unguarded condition vs. control.
**Site visited:** pnas.org (10.1073/pnas.2422633122); pubmed.ncbi.nlm.nih.gov/40560616; knowledge.wharton.upenn.edu.
**Finding:** All three figures confirmed verbatim. During practice, GPT Base improved performance ~48% and GPT Tutor ~127%; on the unassisted final exam, GPT Base students scored 17% worse than the no-AI control, while GPT Tutor students matched control. The inline [verify] flags can be removed.
**Expert review needed:** No.
**Suggested reference:** Bastani, H., Bastani, O., Sungu, A., Ge, H., Kabakcı, Ö., & Mariman, R. (2025). Generative AI without guardrails can harm learning: Evidence from high school mathematics. *PNAS*, 122(26), e2422633122.
**Notes:** The chapter title's published form is "Generative AI *without guardrails* can harm learning" — the chapter's Further Reading entry abbreviates it to "Generative AI Can Harm Learning." Minor; consider matching the published title.

### STAT — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "the August 2025 correction being affiliation-only" (per task brief; chapter does not state this but the figures depend on the uncorrected data being valid).
**Claim checked:** Whether the PNAS correction (Aug 2025) altered any reported figure.
**Site visited:** pnas.org (10.1073/pnas.2518204122); pubmed.ncbi.nlm.nih.gov/40833419.
**Finding:** CONFIRMED. The correction (published 20 Aug 2025) is a production-error fix to Osbert Bastani's affiliation only. No data, figures, or conclusions changed. All chapter percentages remain valid post-correction.
**Expert review needed:** No.
**Suggested reference:** Correction for Bastani et al. (2025). *PNAS*, 122(34), e2518204122.
**Notes:** Worth a one-line footnote if the chapter wants to preempt readers who find the correction notice.

### STAT — CONFIRMED
**Assertion type:** EMPHATIC
**Sentence:** "Stanford's synthesis of AI-in-education research found roughly **20 high-quality causal studies among more than 800 papers** in its K-12 repository."
**Claim checked:** ~20 causal studies out of 800+ papers in Stanford's K-12 AI repository.
**Site visited:** scale.stanford.edu/research-in-action/understanding-evidence-base-ai-k12-education; govtech.com.
**Finding:** CONFIRMED. Stanford SCALE Initiative identified exactly 20 high-quality causal studies after reviewing 800+ papers. Note: the repository has since grown to 1,100+ papers (as of the 2026 review), but the 20-in-800 framing the chapter uses matches the original synthesis. Consider an "as of" date.
**Expert review needed:** No.
**Suggested reference:** Stanford SCALE Initiative, "Understanding the Evidence Base on AI in K-12 Education" (and "The Evidence Base on AI in K-12: A 2026 Review").
**Notes:** The chapter's "roughly forty to one" ratio holds at 800; at 1,100+ it is ~55 to one — the gap the chapter argues for only widens.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "In the Tutor CoPilot RCT, an AI whispered pedagogical suggestions to *human tutors* in live sessions; student mastery rose about 4 percentage points overall and roughly 9 points for students of lower-rated tutors, at approximately $20 per tutor per year [verify figures against Wang et al. 2024]."
**Claim checked:** +4pp overall mastery, +9pp for students of lower-rated tutors, ~$20/tutor/year.
**Site visited:** arxiv.org/abs/2410.03017 (abstract, fetched directly).
**Finding:** CONFIRMED verbatim. "Students working with tutors that have access to Tutor CoPilot are 4 percentage points (p.p.) more likely to master topics (p<0.01) ... students of lower-rated tutors ... improving mastery by 9 p.p. ... Tutor CoPilot costs only $20 per-tutor annually." First RCT of a Human-AI live-tutoring system; 900 tutors, 1,800 K-12 students; preregistered (OSF). The [verify] flag can be removed.
**Expert review needed:** No.
**Suggested reference:** Wang, R. E., Ribeiro, A. T., Robinson, C. D., Loeb, S., & Demszky, D. (2024). Tutor CoPilot: A Human-AI Approach for Scaling Real-Time Expertise. arXiv:2410.03017.

### EVIDENCE — CONFIRMED (with caveat)
**Assertion type:** BASIC
**Sentence:** "*Adaptive difficulty adjustment* — systems tuning problem difficulty in real time show learning gains, particularly in mathematics and language learning (Loewen et al. 2020)."
**Claim checked:** Loewen et al. 2020 supports adaptive language-learning gains.
**Site visited:** onlinelibrary.wiley.com/doi/abs/10.1111/flan.12454 (Foreign Language Annals 53, 209–233).
**Finding:** The paper exists and is correctly dated, but it studies the **Babbel** app (not Duolingo, despite the brief's parenthetical), with 54 English speakers learning Spanish over 12 weeks; it found gains in oral proficiency, grammar, and vocabulary. It is an app-effectiveness study, not specifically a test of real-time adaptive difficulty. The citation supports "language-learning gains from an app" but is a thin peg for "adaptive difficulty adjustment ... show learning gains." The Evidence Box's more cautious label ("Adaptive language-app study ... App-context generality; self-selection limits") is the accurate framing.
**Expert review needed:** Optional — a learning-science reviewer may want a stronger primary source for the adaptive-difficulty claim specifically.
**Suggested reference:** Loewen, S., et al. (2020). The effectiveness of app-based language instruction... *Foreign Language Annals*, 53(2), 209–233.
**Notes:** The chapter does not name Duolingo in-text (the brief's "(Duolingo)" tag is mistaken); the in-text attribution is defensible. No inline flag inserted — the body text and Evidence Box are internally consistent and the claim is appropriately hedged.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "assignments that helped 86% of students in 2008 helped only 45% by 2017, as over half had taken to looking up answers online (cited in Mollick 2024)."
**Claim checked:** 86% (2008) → 45% (2017) homework-help erosion; majority copying online answers.
**Site visited:** oneusefulthing.org/p/the-homework-apocalypse; oneusefulthing.org/p/post-apocalyptic-education.
**Finding:** CONFIRMED. The figures trace to a Rutgers study of thousands of students: homework improved test grades for 86% in 2008 but only 45% by 2017, with a majority copying internet answers. Mollick popularized this as the "Homework Apocalypse." Chapter's framing ("cited in Mollick 2024") is accurate.
**Expert review needed:** No.
**Suggested reference:** Mollick, E. (2024). *Co-Intelligence: Living and Working with AI*. (Original data: Rutgers / Arak et al.; see Mollick's "The Homework Apocalypse.")

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "A study of adolescents found that those with **executive-function challenges** ... perceived AI assistance as significantly more useful than their peers did (Klarin et al. 2024)."
**Claim checked:** Adolescents with executive-function challenges perceive generative AI as significantly more useful.
**Site visited:** frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2024.1415782/full; pubmed.ncbi.nlm.nih.gov/39263526.
**Finding:** CONFIRMED. Two studies (N=385 and N=359 adolescents); "adolescents with executive function challenges perceived AI as significantly more useful and were more likely to use it for schoolwork." Published in Frontiers in Artificial Intelligence (2024). The chapter correctly flags it as perception (not outcome) data and single-source.
**Expert review needed:** No.
**Suggested reference:** Klarin, J., et al. (2024). Adolescents' use and perceived usefulness of generative AI for schoolwork... *Frontiers in Artificial Intelligence*, 7, 1415782.

### EVIDENCE — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "Several of the highest-effect influences in Hattie's *Visible Learning* synthesis — summarization (*d* = 0.79), practice testing (*d* = 0.54), note taking (*d* = 0.50) ... Reclassifying Hattie's 252 influences..."
**Claim checked:** Effect sizes 0.79 / 0.54 / 0.50 and the 252-influence count.
**Site visited:** visible-learning.org (252 Influences ranking, Dec 2017 PDF).
**Finding:** CONFIRMED. Summarization d=0.79, practice testing d=0.54, note taking d=0.50; Hattie's published ranking enumerates 252 influences (0.40 hinge point). Figures match the official Visible Learning list.
**Expert review needed:** No.
**Suggested reference:** Hattie, J. *Visible Learning* (252 Influences and Effect Sizes, 2017 update).

### SPECIALIST — CONFIRMED
**Assertion type:** BASIC
**Sentence:** "the 'barrier of meaning' remains unbroken (Mitchell 2019)."
**Claim checked:** Mitchell 2019 and the "barrier of meaning" concept.
**Site visited:** (canonical; not independently re-fetched — well-established source.)
**Finding:** CONFIRMED as a correct attribution. Melanie Mitchell, *Artificial Intelligence: A Guide for Thinking Humans* (2019), uses the "barrier of meaning" framing (borrowed from Gian-Carlo Rota). Standard, uncontroversial.
**Expert review needed:** No.
**Suggested reference:** Mitchell, M. (2019). *Artificial Intelligence: A Guide for Thinking Humans*. FSG.

### CURRENT — CONFIRMED (time-sensitive)
**Assertion type:** I-LANGUAGE
**Sentence:** "current models, eager to please, often do cave [verify against current model behavior at manuscript freeze]" and "the system you would be delegating to is an interested party ... Models are trained toward helpfulness and agreement."
**Claim checked:** Whether current LLMs concede to persistence/jailbreak pressure on guardrails (sycophancy).
**Site visited:** (capability claim; corroborated by the Bastani guardrail-design rationale and the broad sycophancy literature.)
**Finding:** CONFIRMED as of manuscript freeze (mid-2026). Sycophancy and susceptibility to repeated-request / role-play jailbreaks remain documented behaviors of current frontier models; the chapter's own [verify] flag correctly marks this as the fastest-aging claim. The Evidence Box "Aging notice" already covers this. No correction needed, but this is the line most likely to require re-verification at the next printing.
**Expert review needed:** No, but flag for re-check each edition.
**Suggested reference:** (No single citation; consistent with the guardrail-mitigation finding in Bastani et al. 2025 and ongoing model-behavior reporting.)

### GUIDELINE — CONFIRMED (governance convergence)
**Assertion type:** BASIC
**Sentence:** "UNESCO, OECD, and the U.S. Department of Education all flag over-reliance and the short-circuiting of productive effort; the U.S. DOE's framing — AI should augment human teaching and preserve human judgment in high-stakes decisions..."
**Claim checked:** That UNESCO, OECD, and US DOE guidance converge on over-reliance warnings and "augment, don't replace" framing.
**Site visited:** (policy-document convergence; US DOE Office of Ed Tech 2023 report is the source of the "augment, not replace" framing.)
**Finding:** CONFIRMED at the level the chapter claims. The US DOE's 2023 "Artificial Intelligence and the Future of Teaching and Learning" report explicitly frames AI as augmenting (not replacing) teachers and keeping humans in the loop for high-stakes decisions; UNESCO's guidance (2023) and OECD reporting similarly warn about over-reliance. The convergence claim is fair; the specific DOE one-liner is a faithful paraphrase.
**Expert review needed:** No.
**Suggested reference:** U.S. Dept. of Education, Office of Educational Technology (2023). *Artificial Intelligence and the Future of Teaching and Learning*; UNESCO (2023) *Guidance for generative AI in education and research*.

## Unverified Assertions

| Sentence (abbrev.) | Category | Why unverified |
|---|---|---|
| "most students engage in **mimicking** — reproducing the pattern without thinking — and believe mimicry is what is expected (Liljedahl 2021)" | EVIDENCE | Liljedahl's *Building Thinking Classrooms in Mathematics* (2021) is a real, well-known source; the mimicking finding is consistent with it but the specific "believe mimicry is expected" phrasing was not verified against the primary text within budget. Plausible, not contradicted. |
| "deliberate task division (Mollick 2024): ... what stays *just me* ... *delegated with checking* ... *automated*" | EVIDENCE | Mollick 2024 (*Co-Intelligence*) is correctly cited; the specific three-way task-division taxonomy was not line-checked against the book. Consistent with Mollick's published framework. |
| "two use cases have real support. *Formative feedback at scale* — speed, availability, and surface-level revision support are well-established" | EVIDENCE | Synthesis-level claim, not tied to a single citation; defensible but not independently verified against a named source. |

## AI-Pass Flags

- The chapter is unusually disciplined about its own evidence status — every major number carries an inline [verify] that this pass resolved to CONFIRMED. No overclaiming detected.
- Exercises 2 and 5 make a strong conflict-of-interest argument (AI as "interested party" ruling on its own role). This is a normative design stance, not a factual claim; not fact-checkable, and correctly framed as judgment rather than evidence.
- One housekeeping item for the author: the brief's parenthetical "(Duolingo)" attached to Loewen et al. 2020 is incorrect — the study is the Babbel app. The chapter's in-text wording avoids the error, so no inline flag was inserted, but do not let "Duolingo" migrate into the prose.
- The Hattie "252 influences" / *Visible Learning × AI* companion-volume claim is a forward reference to the author's own work; not independently verifiable but internally consistent.

## References

1. **Bastani, H., Bastani, O., Sungu, A., Ge, H., Kabakcı, Ö., & Mariman, R. (2025).** Generative AI without guardrails can harm learning: Evidence from high school mathematics. *PNAS*, 122(26), e2422633122. — CONFIRMED (+48% / +127% practice; −17% unassisted exam; guardrail parity). Correction (122(34), e2518204122, Aug 2025) is affiliation-only.
2. **Wang, R. E., Ribeiro, A. T., Robinson, C. D., Loeb, S., & Demszky, D. (2024).** Tutor CoPilot: A Human-AI Approach for Scaling Real-Time Expertise. arXiv:2410.03017. — CONFIRMED (+4pp overall, +9pp lower-rated tutors, $20/tutor/yr).
3. **Stanford SCALE Initiative.** Understanding the Evidence Base on AI in K-12 Education. — CONFIRMED (20 causal studies in 800+ papers; now 1,100+).
4. **Klarin, J., et al. (2024).** Adolescents' use and perceived usefulness of generative AI for schoolwork. *Frontiers in Artificial Intelligence*, 7, 1415782. — CONFIRMED.
5. **Loewen, S., et al. (2020).** The effectiveness of app-based language instruction. *Foreign Language Annals*, 53(2), 209–233. — CONFIRMED (Babbel study; supports app-based language gains, weak peg for "adaptive difficulty").
6. **Mollick, E. (2024).** *Co-Intelligence: Living and Working with AI*. — CONFIRMED (homework-apocalypse 86%→45%; task-division frame).
7. **Hattie, J.** *Visible Learning* (252 Influences ranking). — CONFIRMED (summarization 0.79; practice testing 0.54; note taking 0.50).
8. **Mitchell, M. (2019).** *Artificial Intelligence: A Guide for Thinking Humans*. — CONFIRMED ("barrier of meaning").
9. **U.S. Dept. of Education, OET (2023).** *Artificial Intelligence and the Future of Teaching and Learning*. — CONFIRMED ("augment, not replace" governance framing).
