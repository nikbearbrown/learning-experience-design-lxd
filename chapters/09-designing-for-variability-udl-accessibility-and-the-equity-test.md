# Chapter 9 — Designing for Variability: UDL, Accessibility, and the Equity Test
*Holding two true statements at once.*

A middle-school math platform was adopted for the best reasons. Its adaptive engine promised the right problem for every student at the right moment, and it delivered: students scoring below threshold were routed into a remediation track — shorter problems, more repetition, more scaffolding — until accuracy recovered. Students above threshold advanced to extension challenges: open-ended modeling tasks, the creative work the curriculum saved for those who were ready. Teachers loved the dashboard. Remediation-track accuracy rose within weeks. Every individual routing decision, examined alone, was defensible.

A district analyst pulled the cohort data in April. Who was in the remediation track in September? Disproportionately the students who entered with weaker preparation — which, in this district as in most, meant disproportionately lower-income students and students still acquiring English. Who was still there in April? Mostly the same students. The track recovered accuracy on its own short, repetitive items and produced almost no exits, because advancement required performance on the extension-style problems the track never taught. Meanwhile the advanced group had spent seven months practicing modeling, argument, and transfer — the work that compounds. The September gap was a preparation gap. The April gap was a preparation gap *plus seven months of systematically different opportunity to learn*, administered automatically, at scale, with a dashboard certifying progress the whole time.

Note what this case is not. The routing rule used performance, not demographics. Intentions were good throughout. It is the pattern Cathy O'Neil (2016) taught designers to recognize: a proxy-driven model, operating at scale, whose outputs feed back into the conditions that generate its future inputs. The students were sorted by what they hadn't yet been taught, then taught less of it. The personalization worked exactly as designed. The design was the problem.

This chapter is about what it means to design for the *fact* of learner variability — real, universal, and the entire reason personalization is tempting — without building a sorting machine. And it asks you to hold two statements at once: accessibility is non-negotiable, and parts of the UDL evidence base are contested. Most writing on this topic drops one statement or the other. Advocacy treats the framework as settled science; debunking treats contested evidence as license to dismiss the obligations. Both are failures of exactly the discipline this course has been building. This chapter refuses both, which means it will be less comfortable than either.

<!-- → [DIAGRAM: two-path branching illustration — a learner icon at the top; left path labeled "variability-first design" leads to a wide road with multiple lanes, all arriving at the same destination ("full learning objective"); right path labeled "adaptive tracking" forks early into two diverging roads with different endpoints — one labeled "extension: modeling and transfer," one labeled "remediation: accuracy on short items only," the exit from remediation blocked by a gate requiring skills the track never taught. Caption: "Same premise — learners differ. Opposite architectures. Only one holds the destination constant."] -->

---

Start with the premise underneath everything else, the chapter's least contested claim: **learner variability is universal, multidimensional, and poorly described by category labels.** Learners vary in sensory and motor access, language, prior knowledge, working memory, attention, executive function, bandwidth — literal and figurative — cultural reference points, and the circumstances surrounding each session. These dimensions vary *within* the same learner across contexts and weeks. The design tradition this chapter inherits begins from that fact rather than from a mythical average user, and understanding where that tradition comes from matters for evaluating its claims.

The lineage runs through architecture. Ron Mace's **universal design** reframed disability as a property of environments rather than persons: a staircase, not a wheelchair, is what makes a building inaccessible. The tradition's emblem is the **curb cut** — a ramp cut for wheelchair users that turned out to serve parents with strollers, travelers with luggage, cyclists, everyone some of the time. The *curb-cut effect* — designs required by some, beneficial to many — is the field's rhetorical engine, and it is often genuinely true. It is not a law of nature. Some accommodations involve real trade-offs. It is a pattern to check for, not an assumption to design on.

**Universal Design for Learning** is the education-side descendant, developed by CAST from the 1990s onward. If variability is the baseline, design multiple roads into the learning from the start, rather than building for the mythical average and retrofitting accommodations one diagnosis at a time. Retrofit logic is reactive, stigmatizing — the accommodated learner is marked as the exception — and slow. Variability-first logic is proactive and anonymous: the flexible design is just the design.

The current version is **UDL Guidelines 3.0**, released by CAST in July 2024 (CAST 2024): three principles — multiple means of **engagement** (the *why* of learning), of **representation** (the *what*), and of **action and expression** (the *how*) — elaborated into nine guidelines and thirty-six "considerations," renamed from "checkpoints," a deliberate move away from checklist semantics. The 3.0 revision shifted emphasis from individual learner differences toward barriers in the environment, including systemic ones. Read generously, this makes the framework more honest about where barriers live. Read skeptically, it moves the framework further from the operational specificity outcome research can grab onto — a tension treated squarely in a moment.

Used well, the UDL guidelines function as a **structured imagination prosthetic**: a systematic sweep across categories of variability a designer would otherwise sample by autobiography, because designers default to designing for their own perceptual, linguistic, and motivational profile. A framework's first service is interrupting that. Used badly, the guidelines become a compliance checklist where the artifact "has multiple means" of everything and nobody asked what any of it was *for*. The difference is whether each change traces to a named barrier for identifiable learners — which is why this book sequences the audit after learner research, mapping, and prototyping.

---

Here is the mechanism to master in this chapter — the one that separates rigorous from careless thinking about variability, and the one the evidence controversy depends on. Design changes emerging from a variability audit are **not all justified the same way**. Collapsing the three justification logics into one is the root error of both UDL advocacy and UDL debunking.

**The first logic is obligation.** Some changes are owed to learners as a matter of rights, law, and professional ethics, independent of any learning-outcome evidence. Captions. Screen-reader-compatible structure. Keyboard operability. Sufficient contrast. No information carried by color alone. These are codified in the **Web Content Accessibility Guidelines (WCAG 2.2)** — the W3C standard organized under POUR: perceivable, operable, understandable, robust — and carried into law by the ADA and Section 508 in the US and EN 301 549 in the EU. The justification test for an obligation is *access*, not effect size: does this change remove a barrier that excludes someone? Demanding learning-gain evidence before captioning a video is a category error — like demanding evidence that wheelchair ramps improve shopping outcomes. The ramp is owed because the building is public. No study can repeal an obligation, and no contested-evidence finding anywhere in this chapter touches Logic 1. This is what "accessibility is non-negotiable" means, precisely.

**The second logic is evidence.** Some changes a UDL audit surfaces are also supported by specific empirical literatures. Captions again — owed under Logic 1 *and* associated with comprehension benefits for many learners beyond those who require them, a genuine curb-cut effect (Gernsbacher 2015). Worked examples and scaffolding for novices, from Chapter 3's load literature. Making task value visible, from Chapter 4's strongest engagement predictor. When a change is double-justified — owed *and* evidenced — say so. It is the strongest position a design decision can occupy.

**The third logic is a documented bet.** Some changes rest on claims currently contested, under-evidenced, or unestablished — most prominently, that implementing UDL as a whole improves learning outcomes [contested — see pantry flag]. A Logic 3 label is not a prohibition. It is a requirement to decide under documented uncertainty: weigh plausibility, cost, risk, and reversibility, then record the bet. Designers decide under uncertainty constantly. The failure mode is not the uncertainty but the undisclosed confidence.

Three errors, each common, each now nameable. Treating an obligation as if it needed outcome evidence — Logic 1 demoted to Logic 3 — is the debunker's error and the most harmful, because the people it harms are the ones the obligation protects. Treating a contested claim as settled because it shares a framework with obligations — Logic 3 promoted to Logic 1 — is the advocate's error, which spends credibility the obligations need. And treating the whole audit as undifferentiated virtue makes the design indefensible in exactly the budget meeting where it needs defending.

<!-- → [DIAGRAM: three-tier stack labeled "Justification Logics" — top tier: OBLIGATED (cite the standard; justification = access, not effect size; no outcome evidence required); middle tier: EVIDENCE-SUPPORTED (cite the finding; normal evidence-quality rules apply); bottom tier: CONTESTED/UNESTABLISHED (state the bet; document cost, plausibility, reversibility; name the test). Between top and middle, a warning arrow: "demanding outcome evidence here is a category error." Between middle and bottom, a warning arrow: "treating this tier as the top is the credibility drain." Caption: "The three logics are not a hierarchy of confidence — they are different kinds of justification. Mixing them is the chapter's central error."] -->

---

Now the contested middle, with both sides given their strongest form.

**The empirical predicament.** UDL is a meta-framework — a way of generating design decisions — not a single intervention. Implementations bundle many changes at once, vary enormously between studies, and usually arrive alongside other reforms. Isolating "the UDL effect" approaches impossibility. The most-cited meta-analysis by Capp (2017), covering 2013–2016 studies, reported improvements in learning *process* — engagement, access, perceived inclusion — while noting serious heterogeneity in what "UDL" meant across studies and limited, methodologically weak evidence on learning *outcomes*. Later systematic reviews trend positive on some academic outcomes, but across designs of mixed quality with persistent inconsistency in implementation description [verify — check current UDL meta-analyses, including King-Sears and colleagues' work, against the primary papers before citing any effect size].

**The critics' strongest case.** Edyburn (2010) posed the foundational challenge from inside the field: if we cannot say operationally what counts as UDL implementation, we cannot validate it — "would you recognize UDL if you saw it?" The framework's brain-network framing is a loose translation of neuroscience, not a derivation from it; its guidelines mix well-evidenced practices with speculative ones; its institutional success — policy mandates, near-universal presence in teacher preparation — has outrun its outcome evidence, a pattern uncomfortably reminiscent of learning styles [contested — see pantry flag; this critique line is itself disputed]. The critics' point is not that UDL-aligned classrooms harm anyone. It is that a framework can be humane, popular, mandated — and still not have demonstrated that *the framework itself* causes better learning.

**The advocates' strongest case.** Three replies have real force. First, the bundling problem cuts both ways: absence of clean whole-framework evidence is not evidence of absence, and demanding an RCT of a design philosophy may be a category error — you cannot randomize "designing for variability" any more than "user-centered design," and nobody concludes from that gap that user-centered design is bunk. Second, many UDL components are independently evidenced (Logic 2): the framework's value may be precisely as a delivery vehicle that gets evidenced practices implemented systematically. Third, part of UDL's justification was never about test scores — including learners otherwise excluded is a goal whose worth does not wait on outcome data, though advocates who make this correct argument must then accept its discipline and stop also claiming settled outcome superiority.

Where that leaves a designer is a calibration, not a verdict: treat UDL 3.0 as a valuable structured audit instrument whose component recommendations each earn their own label; treat whole-framework outcome claims as currently unestablished in either direction; and treat the obligations traveling alongside the framework as untouched by any of this, because they never rested on outcome evidence. If you feel an urge for a cleaner conclusion, notice it: that urge, gratified, is how fields end up with both uncritical mandates and uncritical backlashes.

---

Return to the opening case, because the variability conversation has a dangerous neighbor wearing its clothes.

**Designing for variability** and **adaptive personalization** begin from the same true premise — learners differ — and diverge structurally. Variability-first design widens the path: multiple means available to all learners, chosen by the learner, with the destination — the full learning objective — held constant. Choice is the learner's; no door closes. Adaptive tracking forks the path: an algorithm assigns different learners different experiences, often with different effective ceilings, based on inferred ability. Choice is the system's; doors close silently, at scale, and the learner rarely knows a fork existed.

The OECD's warning about AI-driven personalization names the risk plainly: layered onto already unequal systems, personalization can reproduce access gaps and unequal support — **digital tracking**, the algorithmic descendant of curricular tracking, which decades of education research found tends to entrench initial differences (OECD 2026). O'Neil (2016) supplies the anatomy the opening case instantiated: proxies stand in for the thing that matters, scale amplifies, opacity prevents appeal, and the feedback loop converts yesterday's gap into tomorrow's training data.

This does not mean adaptivity is forbidden — adaptive difficulty has genuine supporting evidence in some domains, and resist the lazy inversion as firmly as the lazy adoption. It means adaptive proposals must pass an **equity test** before the usual evidence test.

The test has four checks. **Ceiling:** does any group's assigned path foreclose access to the most cognitively rich work? The opening case fails here. **Exit:** does routing create the conditions for leaving the route it assigns — or does the remedial track teach only remedial performance? Fails here too. **Visibility and appeal:** do learners and teachers know routing happened, on what basis, and how to contest it — O'Neil's opacity criterion? **Cohort:** audit outcomes by group over time. The opening case looked fine at every resolution except the one that mattered.

<!-- → [TABLE: equity test checklist — four rows, one per check; columns: Check, Question, Passing condition, Opening-case verdict. Ceiling: "Does any routed path foreclose cognitively rich work?" / "All paths reach the full objective" / FAIL. Exit: "Does the track teach its own exit conditions?" / "Remediation includes skills required to advance" / FAIL. Visibility: "Do learners/teachers know routing happened and how to contest it?" / "Transparent basis, appeal mechanism" / NOT MET. Cohort: "Do outcomes disaggregate equitably over time?" / "No group systematically stranded" / FAIL. Caption: "A feature that passes the normal evidence test can still fail the equity test. Run them in this order."] -->

Two additional lenses extend the equity frame beyond access mechanics — both labeled honestly as value commitments with developing evidence bases rather than settled effect sizes. **Culturally sustaining pedagogy** (Paris 2012) asks whose language practices and ways of knowing the design treats as assets to sustain rather than deficits to remediate. **Trauma-informed design** — per SAMHSA's principles of safety, trustworthiness, choice, collaboration, empowerment — asks whether the experience's pressure points are load-bearing for learning or just ambient threat. And as the constructive alternative to algorithm-first personalization, **human-centered learning analytics** (Buckingham Shum, Ferguson & Martinez-Maldonado 2019) designs the analytic layer with its stakeholders: models interpretable, teachers in the loop on consequential routing, learners visible as agents rather than targets.

---

The audit method itself has a characteristic failure mode worth naming before the worked example. The tempting opening move is comprehensive: a spreadsheet scoring the experience against all thirty-six UDL 3.0 considerations. Two evenings later the spreadsheet is full and nothing has been decided; every row says "could add an option here." This is the checklist trap the framework's own renaming of "checkpoints" warns against. The useful audit is **barrier-first**: walk the experience as documented learner profiles — the phone-bound user, the EAL learner, the screen-reader user, the anxiety-carrying returner — logging the concrete barriers each one hits. Twenty minutes per walk. The considerations function as a prompt set for the walking, not a scoring grid.

The worked example is the *DataWise 101* statistics course, Unit 4's sampling-distribution segment — the prototype from Chapter 8, tested with five sighted, English-fluent volunteers on laptops with time to spare. The 140-person course includes, per the Chapter 5 research, learners on phones during work breaks, learners for whom English is an additional language, screen-reader users in recent cohorts, and a long tail of bandwidth, time, and confidence constraints. The segment survived its first test against a sliver of its audience.

The barrier-first walk as four documented profiles produces eleven concrete barriers. The resulting change table — abridged — looks like this:

The simulation walkthrough video has no captions or transcript. This excludes d/Deaf and hard-of-hearing learners and taxes EAL and phone-in-public learners. **OBLIGATED + EVIDENCE-SUPPORTED**: WCAG 2.2 criterion 1.2.2, and Gernsbacher 2015 for the documented comprehension benefit beyond required users. The double label matters rhetorically: the obligation holds regardless of the evidence; the evidence makes the case easier to fund.

The histogram comparison is encoded by color alone — the color-blind learner cannot see the contrast the misconception probe depends on. **OBLIGATED**: WCAG 1.4.1. Note that fixing this also protects the probe's validity as a research instrument.

The interactive slider is not keyboard-operable and screen-reader users cannot run the core activity at all. **OBLIGATED**: WCAG 2.1.1. The accessible alternative must be an equivalent activity, not a caption on an inaccessible one — the distinction between designed-accessible and genuinely equivalent is exactly where technical compliance fails real users.

Adding a parallel worked-example text path alongside the video walkthrough serves phone and bandwidth learners and learners who process text better than narrated animation. **EVIDENCE-SUPPORTED**: the worked-example effect from Chapter 3, independently justified by representation flexibility.

Framing the practice check's difficulty as designed and recoverable, and making the first attempt ungraded, serves anxious re-enrollers who read graded first attempts as judgment rather than practice. **EVIDENCE-SUPPORTED (motivation) / partially CONTESTED (specific wording)**: SDT competence framing from Chapter 4 supports the principle; the precise reframe wording is a documented bet.

Offering choice of written or audio explanation in the predict-observe-explain step addresses EAL learners taxed by typed English under time pressure. **CONTESTED/UNESTABLISHED**: low cost, reversible, plausible under UDL action/expression logic; the bet is documented and the measurement hook is whether modality choices correlate with probe quality.

The vendor's adaptive-remediation module — offered as a free trial, timed to the design sprint — is **declined**. It fails the ceiling check (the simplified track never reaches the misconception-confronting activity) and the exit check (advancement requires skills the track doesn't teach). This is the opening case sold as a feature. The underlying need is met by a human-in-the-loop instructor flag instead.

<!-- → [TABLE: abridged change table — columns: Change, Barrier addressed, Label, Grounds. Rows as described above, including the decline row for the adaptive module. Caption: "One row per change. One label per change. The decline is the table's most consequential output."] -->

The limit of this audit is worth stating in full: it was performed by one designer using documented profiles without testing with disabled learners or assistive-technology users. Walkthrough-by-proxy finds gross barriers and reliably misses subtle ones, and the data-table slider alternative is exactly the kind of "equivalent" that fails in real screen-reader use. The honest status of the OBLIGATED rows is *designed, not yet verified*. Verification with real AT users and an accessibility expert review is the segment's next gate. And nothing in the table claims the segment now teaches better — every learning claim still routes through Week 13.

---

The chapter opened with a platform that personalized perfectly and sorted inequitably. It ends with a method that finds obligations no evidence debate can touch, surfaces evidence-backed improvements the framework deserves credit for identifying, and labels the rest as bets rather than certainties. The most consequential output from the DataWise 101 audit was a refusal. That is not a failure of the method — it is what the method is for.

What happens next is verification debt: the gap between designed-accessible and verified-accessible with real users. Most "accessible" learning experiences live in that gap permanently, because the design pass happened and the verification pass never did. Closing the gap takes disabled users in the room, assistive-technology expertise, and institutional willingness to treat verification as a production requirement rather than a luxury. The chapter's Still Puzzling section ends on exactly this question, because it is the question the literature has not answered and practice has not solved. It is also, not coincidentally, the question this chapter cannot answer for you.

---

## Evidence Box

<!-- → [TABLE: evidence summary — columns: Claim, Key evidence, Direction & strength, Unsettled.] -->

| Claim | Key evidence | Direction & strength | Unsettled |
|---|---|---|---|
| Learner variability is universal and multidimensional | Foundational premise; not contested | Framework-level; undisputed | Disputes are about frameworks built on it, not the premise itself |
| Accessibility barriers exclude; codified standards remove identifiable barriers | WCAG 2.2; ADA/508/EN 301 549 | Engineering knowledge + rights law; not awaiting pedagogical validation | Whether a specific design is genuinely equivalent requires AT-user testing, not design review |
| Captions benefit comprehension broadly | Gernsbacher 2015 | Positive — single-author review corroborated by underlying studies | Cite the underlying studies for high-stakes claims; single-source flag applies |
| UDL-aligned implementation improves engagement and access measures | Capp 2017 | Positive average, with the author's own caveats about implementation heterogeneity and study quality | Outcome-level evidence mixed; effect sizes not stable across implementations |
| Whole-framework UDL → improved learning outcomes | Current meta-analyses [verify] | Trend positive but contested; implementation heterogeneity prevents clean conclusions | [contested — see pantry flag]; both a verdict-in-favor and a verdict-against are currently defensible |
| Digital tracking reproduces inequity | OECD 2026; O'Neil 2016 (mechanism); curricular-tracking literature | Well-documented pattern; mechanism consistent | Net equity effect of adaptive personalization is moderator-dependent; the moderator map is immature |
| Culturally sustaining pedagogy; trauma-informed design as outcome interventions | Paris 2012; SAMHSA principles | Strong theoretical and ethical grounding | Outcome evidence still developing; taught here as value commitments plus design questions |

---

## What Would Change My Mind

Two findings would force revisions in opposite directions — which is what calibration looks like. If a new generation of component-level studies showed consistent, replicated learning-outcome gains for the framework's currently unestablished recommendations — tested singly, with implementation fidelity reported against UDL reporting criteria — this chapter would promote those rows from Logic 3 to Logic 2 and credit the framework as a validated generator, not just a useful audit prompt. Conversely, consistent well-powered nulls for the framework's distinctive recommendations would shrink UDL's role here to "structured prompt for finding obligations and already-evidenced practices," said plainly. Note what is not on this list: no learning-outcome finding in either direction would change a word of the obligations sections, because those sections never rested on outcome evidence. That is what Logic 1's independence means.

---

## Still Puzzling

- **Can a meta-framework ever be validated?** If "UDL works" is unanswerable in principle — because the bundling problem prevents isolation — while "this UDL-derived change works" never aggregates back to the framework, the field's central empirical question may be permanently ill-posed. It is unclear what honesty requires us to say about mandates in the meantime.
- **The cost of the label, socially.** In institutions that fund only certainty, does labeling a change "documented bet" get equity work defunded? Is that a reason to soften the labels, or precisely the reason they matter?
- **Where does choice itself sit?** Modality choice is UDL bedrock — but Chapter 7 established that learners reliably mis-choose against desirable difficulty. When does multiple-means flexibility become an unguarded menu of fluency? The boundary between honored variability and abandoned guidance is undertheorized.
- **Verification debt.** Most "accessible" learning experiences are designed-accessible, not verified-accessible with real AT users. What would it take, institutionally and economically, to make verification as routine as the design pass?

---

## Exercises

**Warm-up**

1. *(Recall — justification logics)* A colleague proposes making all course videos keyboard-navigable and argues: "We should test whether this improves quiz scores before committing the development time." Identify the error in this argument by name, state the correct justification logic for keyboard operability, and cite the standard that establishes it as an obligation.
*Difficulty: low. Tests: Logic 1 vs. Logic 3 distinction; the category error of demanding outcome evidence for obligations.*

2. *(Recall — curb-cut effect)* The curb-cut effect is described as "a pattern to check for, not an assumption to design on." Explain the difference between those two stances, and give one example of a UDL-style accommodation where the curb-cut framing holds and one where it involves a real trade-off.
*Difficulty: low. Tests: honest vs. rhetorical use of the curb-cut framing.*

3. *(Recall — equity test)* Apply the four-part equity test to the following proposed feature: a platform that routes learners who fail two consecutive quizzes into a "consolidation mode" — shorter, scaffolded problems — with automatic return to the main track when accuracy reaches 80%. Which checks does it pass and which does it fail? What additional information would you need to complete the assessment?
*Difficulty: low. Tests: ceiling, exit, visibility, and cohort checks applied to a new scenario.*

**Application**

4. *(Apply — the three logics)* You are auditing an online professional certification. Label each of the following proposed changes with its justification logic — OBLIGATED, EVIDENCE-SUPPORTED, or CONTESTED/UNESTABLISHED — with one-sentence grounds for each. Flag any double-labeled changes: (a) adding alt-text to all images; (b) allowing learners to choose between a written essay or recorded presentation for the final assessment; (c) replacing a dense reading with a worked example for the first module's core concept; (d) adding a "choose your own order" navigation option for module sequencing.
*Difficulty: moderate. Tests: three-logic sort with real justification chains, including identifying the edge case where (b) and (d) require different treatments.*

5. *(Apply — barrier-first audit)* You are auditing a four-screen mobile learning experience for a professional audience. Describe the four documented learner profiles you would use to walk it barrier-first, the source for each profile (where the documentation comes from), and the specific accessibility and load-related barriers each profile is most likely to surface that a sighted, desktop-based design walkthrough would miss.
*Difficulty: moderate. Tests: barrier-first method, profile documentation discipline, audit coverage gaps.*

6. *(Apply — decline memo)* A product manager proposes adding a feature that automatically routes learners who haven't logged in for five days into a "re-engagement track" with simplified content and lower-stakes activities. Write a one-page decline memo: run the equity test, name which checks it fails and why, and propose an alternative that addresses the re-engagement goal without forking the path.
*Difficulty: moderate. Tests: equity test applied to a novel feature, constructive alternative thinking.*

**Synthesis**

7. *(Synthesize — advocate and skeptic)* The chapter states that both a verdict-in-favor and a verdict-against the whole-framework UDL outcome claim are currently defensible. Write a 200-word version of each, giving each side its strongest evidence-based case. Then write a third 100-word statement that gets the calibration right — acknowledging what is established, what is contested, and what that means for a designer making decisions today.
*Difficulty: moderate-high. Tests: intellectual honesty under genuine uncertainty; three-tier calibration rather than false resolution.*

8. *(Synthesize — double-justified design)* Identify three changes you would make to a hypothetical online statistics course that are double-justified — both obligated and evidence-supported — and three that are single-justified (either obligated only or evidence-supported only). For the double-justified changes, explain why the double label matters rhetorically in a budget conversation. For the single-justified changes, identify the argument you cannot make and why.
*Difficulty: high. Tests: integrated application of all three logics, real rhetorical deployment.*

**Challenge**

9. *(Challenge — verification debt)* The chapter ends on verification debt: the gap between designed-accessible and verified-accessible with real AT users. Propose a minimal verification protocol that a team of three — one learning designer, one developer, one subject-matter expert — could execute for a twenty-module online course without dedicated accessibility expertise on staff. Specify: what you can verify internally, what requires AT-user testing, what requires specialist review, and how you would prioritize the queue if you had budget for only five external verification sessions across all twenty modules.
*Difficulty: high. Tests: practical reasoning about resource constraints, honest limits of proxy methods.*

---

## LLM Exercise: Defend Every Label Twice

*The labels are yours. The model challenges them; it may not assign, change, or originate a label, and it may not be cited as the grounds for one. It cannot tell you whether your design is actually accessible — only testing with real assistive-technology users can. No change table yet? Build it first.*

After completing your change table, paste it — labels, grounds, and all — with this prompt:

---

You are two reviewers in sequence, examining my variability-audit change table: [PASTE YOUR OWN COMPLETED TABLE, WITH LABELS AND GROUNDS].

**Reviewer 1 is a rigorous UDL advocate:** for each row, argue where my labeling understates the case — obligations missed, evidence uncredited, curb-cut effects unanticipated. **Reviewer 2 is a rigorous evidence skeptic:** for each row, argue where my labeling overstates the case — citations that do not support the specific change, contested claims smuggled in as supported, obligations asserted without a named standard. Then, as yourself: (1) identify the single most vulnerable label and ask me the one question that would settle it — do not answer it; (2) identify any row where both reviewers agree I am wrong, since that is where I should look first; (3) list what neither reviewer can know from this table alone — for example, verification with AT users, my learners' actual profiles.

Do not produce a corrected table. Do not assign labels. If no completed table is pasted above, refuse and tell me to do the audit first.

---

*Assessable artifact: the most vulnerable row, your answer to the settling question with any relabeling and why, and one sentence on which reviewer was harder to answer.*

---

## Further Reading

- **CAST (2024). *Universal Design for Learning Guidelines, version 3.0.* udlguidelines.cast.org.** Read the primary source, not summaries — note the considerations' actual wording and the shift toward environmental and systemic barriers.
- **Capp, M. J. (2017). "The effectiveness of universal design for learning: A meta-analysis of literature between 2013 and 2016." *International Journal of Inclusive Education*, 21(8).** The most-cited synthesis — read it for its caveats as much as its means.
- **Edyburn, D. L. (2010). "Would you recognize universal design for learning if you saw it?" *Learning Disability Quarterly*, 33(1).** Still the sharpest framing of the validation problem, from inside the field.
- **Gernsbacher, M. A. (2015). "Video captions benefit everyone." *Policy Insights from the Behavioral and Brain Sciences*, 2(1).** The model citation for a double-justified change — obligation and evidence in one artifact.
- **O'Neil, C. (2016). *Weapons of Math Destruction.* Crown.** The proxy-scale-opacity-feedback anatomy behind the digital-tracking warning; the education chapters make the opening case's mechanism unforgettable.
