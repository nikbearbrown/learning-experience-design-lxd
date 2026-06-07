# Assertions Report: 97-fundamental-themes.md
**Date:** 2026-06-07 / **Source file:** chapters/97-fundamental-themes.md / **Assertions flagged:** 6 / **Breakdown:** STAT: 2 | GUIDELINE: 0 | APPROVAL: 0 | EVIDENCE: 1 | SPECIALIST: 2 | CURRENT: 1

> **Register note (per chapter's own preamble):** This appendix is deliberately written in manifesto register; its preamble explicitly says its empirical claims are stated with less caution than the body chapters, where the same claims carry full Evidence-Box discipline. Per the fact-check plan, inline flags are inserted ONLY for claims that are factually CONTRADICTED or carry a materially wrong number — NOT for claims that are merely emphatic or broad-brush. The two checkable statistics (Bastani, Kosmyna) both CONFIRMED, so **no inline flags were inserted in this file.** This report documents where manifesto register and the evidence diverge.

## ⚠️ Critical — Requires Immediate Expert Review
None found. The two hard numbers check out; the neurobiological passage is broad-brush but defensible (see SPECIALIST findings); the taxonomy and project URLs are the author's own framework.

## Full Findings

### STAT — CONFIRMED
**Assertion type:** EMPHATIC
**Sentence:** "students who used AI freely during math practice scored 48% higher during practice and 17 percentage points *lower* on the unassisted exam. Not slightly worse. Dramatically worse."
**Claim checked:** Bastani 48% / 17-point figures.
**Site visited:** pnas.org/doi/10.1073/pnas.2422633122 ; papers.ssrn.com/abstract_id=4895486
**Finding:** CONFIRMED. Bastani et al. (2025), *PNAS*. Unguarded "GPT Base" group ~48% higher during assisted practice, ~17% lower than control on the unassisted exam; the guarded tutor mitigated the harm. The numbers and direction are exact. The "Not slightly worse. Dramatically worse" framing is manifesto-register emphasis, not a factual error.
**Expert review needed:** No.
**Suggested reference:** Bastani, H., et al. (2025). *PNAS* 122. doi:10.1073/pnas.2422633122.
**Notes:** The chapter elsewhere (preamble) correctly notes the body treats this with full RCT discipline. One nuance for register honesty: the 48%/17-point harm is specifically the *unguarded* condition — the same paper shows guardrails largely neutralize it. The appendix states this implicitly ("used AI freely") but a careless reader could over-generalize; not an error.

### STAT — CONFIRMED (preprint, n=54)
**Assertion type:** EMPHATIC
**Sentence:** "The Kosmyna EEG study makes this visible: up to 55% reduction in functional brain connectivity during AI-assisted writing vs. brain-only writing."
**Claim checked:** The "up to 55%" connectivity-reduction figure and its source.
**Site visited:** arxiv.org/abs/2506.08872 ; brainonllm.com ; theregister.com/2025/06/18
**Finding:** CONFIRMED with caveats. Kosmyna et al., "Your Brain on ChatGPT" (arXiv:2506.08872, MIT Media Lab). The LLM group showed up to a 55% reduction in total dDTF (directed) connectivity strength in lower-frequency bands (alpha/theta/delta) vs. the brain-only group — the 55% figure matches. CAVEATS the appendix already acknowledges in its preamble and inline ("This book carries that study with a single-source flag"): (1) it is a **non-peer-reviewed preprint** (June 2025); (2) **n = 54** for sessions 1–3, only 18 completing session 4 — small; (3) the paper ran a very large number of ANOVAs, drawing published methodological criticism (e.g., arXiv:2601.00856 commentary). The chapter's framing "makes this visible … (single-source flag — see the note above. The behavioral evidence does not depend on it.)" is an appropriately hedged use of a contested preprint.
**Expert review needed:** No — the chapter already flags it as single-source/preliminary.
**Suggested reference:** Kosmyna, N., et al. (2025). "Your Brain on ChatGPT: Accumulation of Cognitive Debt." arXiv:2506.08872 (preprint, n=54).
**Notes:** No inline flag added (figure is correct; preprint status already disclosed in-text). The "55%" is specifically lower-band dDTF, not all-band global connectivity — the appendix's "functional brain connectivity" is a slight simplification but within manifesto tolerance.

### SPECIALIST — UNVERIFIED (defensible but overdrawn as a strict causal chain)
**Assertion type:** EMPHATIC
**Sentence:** "When the brain encounters material that doesn't fit what it already knows — a prediction error — dopamine fires, BDNF upregulates, synapses strengthen, dendritic spines form. These are the physical events that constitute memory. They are triggered by cognitive friction… Remove the friction and you remove the trigger. No trigger, no consolidation. No consolidation, no durable learning."
**Claim checked:** Whether the dopamine / BDNF / synaptic-consolidation-as-prediction-error-triggered account is defensible or overdrawn.
**Site visited:** No single web source decides this; assessed against established neuroscience (Schultz reward-prediction-error dopamine; activity-dependent BDNF/TrkB plasticity; LTP and structural spine plasticity as memory substrate).
**Finding:** Each component is individually grounded: (a) dopamine encodes reward/prediction error (Schultz et al.) — solid; (b) BDNF upregulates with neural activity and supports plasticity — solid; (c) LTP / synaptic strengthening / dendritic-spine formation underlie memory consolidation — mainstream. **Where it is overdrawn (manifesto register):** the passage welds these into a single deterministic chain in which ALL durable learning is triggered by "cognitive friction / prediction error," and the strict conditional "remove the friction → no trigger → no consolidation → no durable learning" is stronger than the literature licenses. Prediction-error/dopamine learning is best established for *reward* and *reinforcement* learning; extending it as THE universal trigger for all educational consolidation — and equating "cognitive friction" with "prediction error" — is a defensible pedagogical analogy, not an established 1:1 neurobiological identity. Learning also consolidates via spacing, sleep, retrieval, and emotional salience that are not cleanly "friction." Verdict: defensible as broad-brush motivation; **overdrawn if read as a literal exhaustive mechanism.** NOT contradicted — so no inline flag per the file's rule.
**Expert review needed:** Advisory — a neuroscientist reviewer should confirm the author is comfortable with the simplification; the preamble's register disclaimer largely covers it.
**Suggested reference:** Schultz, W. (1998/2016) on dopamine prediction error; Lømo/Bliss LTP literature; for the desirable-difficulties bridge, Bjork & Bjork.
**Notes:** This is the clearest place manifesto register outruns the evidence. The chapter's own preamble pre-licenses exactly this divergence ("stated in the register of a manifesto … treated with full Evidence Box discipline" in the body). Documented here, not flagged inline.

### SPECIALIST — UNVERIFIED (framework claim, broad-brush)
**Assertion type:** EMPHATIC
**Sentence:** "AI is a causal parrot… This is not causal reasoning; it is pattern-matching on causal-sounding text." / "the same weights that produced the output are the weights doing the audit."
**Claim checked:** Whether the Tier-4/Tier-5 characterizations of LLM incapacity are defensible.
**Site visited:** None (conceptual/architectural claim, not a discrete empirical figure).
**Finding:** Defensible as a position widely held in the literature (Pearl's "causal ladder" critique of purely associational systems; documented LLM weaknesses in self-evaluation/calibration). It is a contestable theoretical stance stated as settled fact — appropriate to manifesto register, and the appendix frames it as the book's argument rather than a meta-analytic result. Not a checkable STAT; not contradicted.
**Expert review needed:** No.
**Suggested reference:** Pearl & Mackenzie, *The Book of Why* (2018) for the causal-reasoning frame.
**Notes:** No inline flag.

### EVIDENCE — CONFIRMED (cross-reference integrity)
**Assertion type:** BASIC
**Sentence:** "the hands-on advantage in the touch-tank counterfinding (Chapter 11)" and the various "(Chapter N)" attributions mapping themes to body chapters.
**Claim checked:** That the appendix's internal cross-references restate real claims made in the cited body chapters (touch-tank counterfinding, Bastani in Ch 1/12, desirable difficulties in Ch 3, EEG preprint flagged in Ch 12).
**Site visited:** Internal (consistency with the verified Ch15 Evidence Box and chapter map).
**Finding:** CONFIRMED consistent. The touch-tank, Bastani, desirable-difficulties, and EEG-preprint references all correspond to claims established elsewhere in the book and verified in their source passes. The appendix accurately reports that the EEG study is carried "with a single-source flag" in the body — an honest internal cross-reference.
**Expert review needed:** No.
**Suggested reference:** Internal.
**Notes:** None.

### CURRENT — AI-ONLY (author's own framework; project URLs)
**Assertion type:** COMBINATION
**Sentence:** The seven-tier "Irreducibly Human Taxonomy" (Tiers 1–7) and the Projects table (Frictional / frictional.xyz, Irreducibly Human / irreducibly.xyz, Boondoggling / boondoggling.ai, Brutalist / brutalist.art, Nik Bear Brown / nikbearbrown.com).
**Claim checked:** Per plan: the taxonomy and project URLs are the author's own framework = AI-ONLY, no web check.
**Site visited:** None (per instruction — author's own framework).
**Finding:** Not web-verified by design. These are the author's proprietary framework and project properties, not external factual claims. Note the taxonomy lists Tiers 1, 2, 4, 5, 6, 7 in the body but skips an explicit Tier 3 section (the table header says "Tiers 1, 4–7"); the in-text sections jump from Tier 2 to Tier 4. This is an internal-structure observation, not a factual error — worth an editorial check that the omission of a Tier 3 heading is intentional.
**Expert review needed:** No (editorial only).
**Suggested reference:** None.
**Notes:** AI-ONLY.

## Unverified Assertions

| Sentence (short) | Category | Reason not verified | Risk |
|---|---|---|---|
| Dopamine/BDNF/spine chain as the singular friction-triggered mechanism | SPECIALIST | Broad-brush; defensible components, overdrawn as strict chain | Medium — register, not error; pre-licensed by preamble |
| "AI is a causal parrot" / weights-audit-weights | SPECIALIST | Contestable theoretical stance stated as fact | Low — framed as the book's argument |
| Seven-tier taxonomy; project URLs | CURRENT/AI-ONLY | Author's own framework — no external check by design | n/a |
| Tier 3 section absent from body (table says "1, 4–7") | — | Internal structure | Low — editorial |

## AI-Pass Flags

- **No inline flags inserted in the source file.** Per the special instruction, only CONTRADICTED or materially-wrong-number claims get inline flags in this manifesto-register appendix; both checkable numbers (Bastani 48%/17pt; Kosmyna 55%) CONFIRMED, and the neurobiology is overdrawn-but-not-contradicted.
- **Where manifesto register diverges from evidence (documented, not flagged):** (1) the strict "no friction → no learning" causal chain over-claims a clean mechanism the literature supports only in parts and mostly for reward/reinforcement learning; (2) "functional brain connectivity" simplifies the Kosmyna finding, which is specifically lower-band dDTF in a non-peer-reviewed n=54 preprint; (3) the Tier-4/Tier-5 LLM-incapacity claims are a defensible but contestable stance presented as settled. All three are pre-licensed by the appendix's own register preamble.

## References

1. Bastani, H., et al. (2025). "Generative AI without guardrails can harm learning." *PNAS* 122. doi:10.1073/pnas.2422633122. — CONFIRMED (48% / 17 points; harm is the unguarded condition).
2. Kosmyna, N., et al. (2025). "Your Brain on ChatGPT: Accumulation of Cognitive Debt." arXiv:2506.08872 (MIT Media Lab; preprint, n=54). — CONFIRMED (up to 55% reduction in lower-band dDTF connectivity, LLM vs. brain-only). Preprint status and published methodological criticism noted.
