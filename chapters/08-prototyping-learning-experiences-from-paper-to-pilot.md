# Chapter 8 — Prototyping Learning Experiences: From Paper to Pilot

*Week 8 · Act Two — Build · **PROTOTYPE CHECKPOINT (100 pts)** · Track-switch decision point*

---

## Learning Objectives

By the end of this chapter you will be able to:

1. **(Apply)** Produce a low-fidelity prototype of one redesigned segment of a learning experience. *Track A: the statistics course segment your Chapter 7 co-design record targets. Track B: the equivalent segment of your own project.*
2. **(Apply)** Run a structured prototype test with real learners, capturing both usability findings AND learning-relevant findings — load, misconception triggers, motivation.
3. **(Analyze)** Separate usability failures from learning-design failures in test results — because the fix is different.
4. **(Evaluate)** Decide what fidelity the next iteration requires, and justify the cost.

---

## Opening Case: Ninety Seconds

*This case is illustrative — a composite of documented high-fidelity-first failures from design practice; the pattern it depicts is the one the prototyping literature exists to prevent (Gould & Lewis 1985; Knapp et al. 2016).*

The team had four months and spent them well, by every visible measure. A branching patient-triage simulation for first-year respiratory therapy students: professionally illustrated, voice-acted, sixty-two decision nodes, an adaptive difficulty curve, a dashboard the dean had already screenshotted for a grant report. The launch review opened with the lead designer saying, honestly, "This is the best thing we've ever built."

Then they watched the first usability recording. A student — bright, motivated, exactly the target learner — opens the simulation. The core mechanic is the *vitals panel*: at each decision node, the patient's oxygen saturation drifts in real time, and the intended lesson is that *waiting is itself a clinical decision* — delay has physiological cost. The student reads the first scenario. She studies the options. She does what every experience of digital learning has trained her to do: she treats the screen as a quiz page. She deliberates carefully — for as long as she likes — believing the scenario is paused while she thinks.

She never notices the saturation number falling. At ninety seconds, the simulated patient codes. The screen shows the outcome; the student's face shows the diagnosis: *"Wait — it was moving? I thought it was like, a question."*

She had not made a clinical error. She had made a perfectly reasonable inference about *what kind of object the simulation was* — and the design had four months of polish answering a question no one had asked: not "is the interface usable?" but "do learners understand what the experience is asking of them?" Nine more recordings, seven more students deliberating over a "paused" screen. The core mechanic — the one carrying the entire learning objective — was invisible to most of its audience.

A paper version of the vitals panel — index cards, one designer flipping the saturation card every ten seconds while a student thinks aloud — would have surfaced the misunderstanding in week one, at the cost of an afternoon. The team got the same finding in month four, at the cost of the budget. The polish was not wasted because polish is bad. It was wasted because it was *premature*: every hour of it answered small questions while the biggest question stood unexamined.

This chapter is about asking the biggest question first, with the cheapest object that can answer it.

---

## Prerequisites

This chapter assumes you can already:

- **Produce an accepted/rejected/deferred co-design record** (Chapter 7): your prototype implements that record's accepted direction — you should know exactly which decisions it embodies and which assumptions it carries.
- **Classify mental effort as intrinsic, extraneous, or germane load** (Chapter 3): the test protocol asks you to spot load problems live.
- **Name your learners' documented misconceptions** (Chapter 5): a learning prototype is, above all, a misconception trap — you must know what you are trapping.

---

## Core Content

### Fidelity Is a Research Decision, Not a Quality Level

A **prototype** is a question made testable: an artifact built to generate evidence about a design decision before the decision becomes expensive. **Fidelity** is how closely the prototype resembles the final experience — in visual finish, in interactivity, in content completeness, in data realness. The opening case's deepest error was treating fidelity as a quality ladder you climb as fast as possible. The discipline this chapter teaches is the opposite: **fidelity is chosen, per test, to match the riskiest unanswered question** — and no higher.

The reasoning has three parts, each with evidence behind it:

*Cost asymmetry.* Changes are cheapest before commitment. Gould and Lewis (1985) made early empirical user testing a founding principle of usability engineering precisely because the cost of a design error grows with everything built on top of it. Four months of voice acting on top of a misunderstood mechanic is the canonical shape of the failure.

*Critique suppression.* Polish changes what testers tell you. Participants shown highly finished artifacts comment on surface details and hesitate to challenge fundamentals — the artifact signals that the big decisions are closed. Rough artifacts license rough feedback; this is a working principle across sketching and prototyping practice (Buxton 2007) and a reason service-design methods deliberately prototype with paper, cardboard, and props (Stickdorn et al. 2018).

*Commitment psychology.* Designers defend what they have invested in. Dow et al. (2010) found that creating multiple prototypes in parallel led to better-rated final designs, more divergent exploration, and — notably — less fixation than refining a single prototype serially. One precious prototype becomes an identity; five cheap ones stay hypotheses.

A practical **fidelity ladder** for learning experiences, bottom to top: *sketch/storyboard* (the experience as a comic strip — tests sequence and framing); *paper prototype* (hand-operated screens or materials — tests interaction logic and comprehension); *Wizard of Oz* (a human secretly simulates the system's intelligence — tests adaptive and AI-like behavior before it exists; Kelley 1984); *clickable mockup* (real navigation, fake content guts — tests flow and orientation); *authoring-tool build* (Storyline/Rise/Genially-class — tests the integrated experience with real content); *pilot module* (real learners, real stakes, instrumented — tests what only deployment can). You will climb this ladder; the discipline is climbing one question at a time.

**Design application.** Before building anything, write one sentence: "The riskiest thing I don't know is ___." Then choose the *lowest* rung that can answer it. If you cannot name the riskiest unknown, you are not ready to prototype — you are decorating.

### Testing Learning Interactions, Not Just Interfaces

Here is where learning experience prototyping departs from the UX prototyping it borrows from — and the departure is the mechanism to understand most deeply this week.

A usability test asks: *can the learner operate the experience?* Can they find the button, follow the flow, complete the task? Necessary — extraneous load from a confusing interface is a genuine learning killer (Chapter 3) — but radically insufficient, because of an uncomfortable asymmetry: **a learning experience can pass every usability test and teach the wrong thing.** Task completion is a usability success criterion and almost meaningless as a learning one. The student in the opening case *completed* her task fluently. So does a learner who breezes through a beautifully usable statistics simulation and exits believing, as before, that bigger samples produce wilder sample means.

A **learning interaction test** therefore probes four channels a standard usability protocol never touches:

1. **The inferred rule.** What does the learner believe the underlying concept or rule *is*, right now? The probe is generative, never recognition-based: "Explain what just happened to the histogram as if to a classmate." "Predict what happens if I double the sample size — then say why." A learner can click correctly while holding the wrong rule; only their *generated explanation* exposes which.
2. **Load signature.** Where does effort spike, and is the spike intrinsic (the concept is hard — keep it), extraneous (the design is hard — kill it), or germane (productive processing — protect it)? Live signals: long silences in think-aloud, re-reading loops, abandoning the task to fight the tool. The Chapter 6 journey map predicted where these should cluster; the test checks the prediction.
3. **Feedback uptake.** When the prototype's feedback fires, what does the learner *do* — revise their thinking (read the explanation, change the prediction), or game the signal (click until green)? Feedback that is received is not the same as feedback that is used.
4. **Motivational read.** Does the learner know why this task is worth doing (task value), and does difficulty read as challenge or as judgment? One probe suffices: "If this weren't required, would you do it — and what would make it feel worth it?"

The protocol that carries all four channels is the **think-aloud with prediction probes**: the learner narrates continuously, and at each conceptually load-bearing moment the facilitator asks for a *prediction before* the system responds and an *explanation after*. Prediction-before is the trap that catches misconceptions in the act — the moment a learner says "the spread will get wider because more data means more spread," you have captured, on tape, exactly the misconception your Chapter 5 research documented, expressing itself against your design.

**Design application.** Build the test sheet with two ruled columns — **usability findings** and **learning findings** — and force every observation into one. The discipline of the second column is the whole method.

### The Sprint, Adapted to Curriculum

The five-day design sprint (Knapp et al. 2016) — map Monday, sketch Tuesday, decide Wednesday, prototype Thursday, test Friday — is the most widely exported rapid-prototyping container in industry, and it adapts to learning design well *if* you respect three differences. Reported applications in engineering and STEAM education and in course-design contexts are encouraging but methodologically thin — case studies, not controlled comparisons [verify — the sprint-in-education literature is small; check current studies before citing effects].

The adaptation:

- **Monday's map already exists.** Your Chapter 6 journey map and Chapter 7 co-design record replace the sprint's mapping day. The "target moment" the sprint picks is your highest-risk journey moment. (You have been running a slow-motion sprint for three weeks.)
- **Friday tests learners, not customers.** The sprint's five-user interview becomes the think-aloud-with-prediction-probes protocol above. Five is a defensible number for *detection* — Nielsen and Landauer's (1993) classic curve suggests small samples surface most frequent usability problems — but treat it as folklore-with-asterisks: five learners can *find* problems; they cannot *measure* prevalence, and rare-but-severe issues (often the equity-relevant ones — Chapter 9) routinely escape small samples.
- **The decider needs an evidence seat.** The sprint's "Decider" votes on judgment and taste. In curriculum sprints, Wednesday's decision must pass the evidence screen first: a sketch that resolves the journey's dropout cliff by deleting the retrieval practice wins the dot-vote and fails the discipline. Put the Evidence Disclosure *inside* the sprint, not after it.

**Design application.** For the studio checkpoint, run a compressed two-day version: half-day to storyboard against the co-design record, half-day to build at chosen fidelity, one day to test with 3–5 learners and write up. The container matters less than its two non-negotiables: a deadline measured in days, and real learners at the end of it.

### Paper, Wizards, and Authoring Tools: Choosing the Medium

The fidelity ladder says *when* to be rough; this section is *how*. Three media cover most learning-prototype situations:

**Paper and cards** excel at interaction *logic* and concept *sequencing* — and they are secretly ideal for dynamic content, because a human operator is an infinitely flexible renderer. The opening case's vitals panel as index cards is not a degraded simulation; it is a *better test instrument* than the real one, because the operator can pause, vary the drift rate between participants, and probe at the exact moment of confusion. Paper's weakness: pacing, timing feel, and anything where the learner's experience depends on the system's real responsiveness.

**Wizard of Oz** (Kelley 1984) puts a hidden human behind the curtain, simulating the system's intelligence — the adaptive hint, the AI tutor reply, the difficulty adjustment — before any of it is built. For learning experiences this is disproportionately valuable right now: Week 12's AI integration decisions can and should be Wizard-of-Oz tested (a human writing "AI" feedback in a chat window) before any model is wired in. You will discover what learners *do* with adaptive feedback at the cost of a colleague's afternoon. The ethical line: deceive about the *system*, never about the *stakes* — and debrief afterward.

**Authoring tools** (Storyline, Rise, Genially-class — taught here tool-agnostically) sit mid-ladder: real interactivity, fast assembly, tempting polish. Use them when the open question genuinely requires system behavior — timing-dependent interactions, branching too complex to hand-operate, integrated flow. Beware their gravitational pull: templates whisper that the lesson should be a click-to-reveal because the tool makes click-to-reveals effortless. The tool's path of least resistance is not a pedagogy.

**Design application.** Choose the medium by the channel you are testing: inferred rule and sequencing → paper; adaptivity and feedback uptake → Wizard of Oz; flow, pacing, and orientation → clickable or authoring-tool build. When in doubt, go one rung lower than feels respectable.

### What a Prototype Cannot Tell You

The last discipline is refusing to overclaim. A prototype session — any fidelity, any protocol — observes a learner for an hour. Some of the most important properties of a learning experience are *invisible at that timescale*, and the chapter's method is honest only if you can list them:

- **Durable retention.** The entire point of the course's thesis — and structurally unmeasurable in a session. Retrieval practice's benefits appear at *delays*; a prototype test happens at *zero delay*, exactly where desirable difficulties look worst and fluent designs look best (Soderstrom & Bjork 2015). A prototype test is, by construction, biased toward the enjoyable side of the enjoyable ≠ effective divide. Never select between a difficulty-rich and a fluency-rich design on prototype-session performance alone.
- **Spacing, decay, and habit effects.** Anything whose mechanism operates across days or weeks: spaced schedules, motivation decay after novelty (Chapter 4's leaderboard collapse happened at week twelve, not minute twelve), dependence formation on supports (Chapter 12's crutch effect emerged on a *delayed, unsupported* exam).
- **Cohort and context effects.** Five learners in a quiet room are not 140 learners in week nine of a hard semester. Social dynamics, instructor variation, and the long tail of life circumstances are pilot-and-instrumentation territory.

This is not a counsel of despair; it is a division of labor. The prototype test answers *comprehension, interaction, load, and immediate misconception* questions now; everything on the list above becomes a named assumption that flows into your Week 13 measurement plan. The Evidence Disclosure's third category — *assumptions awaiting measurement* — exists precisely to carry this handoff. A checkpoint submission that claims its prototype "improved learning" has failed the week's central lesson; one that says "comprehension of the mechanic rose; retention effects unknown, measurement planned" has learned it.

---

## Mid-Chapter Checkpoint

*Ungraded. Answer before reading on.*

In a prototype test of a chemistry tutorial, you observe: (a) two learners cannot find the "next" control and ask the facilitator how to proceed; (b) a learner balances every equation correctly by pattern-matching coefficients from the worked example, and her explanation reveals she believes balancing is "making the numbers symmetrical"; (c) a learner sighs at the third practice problem and says "more of these?"; (d) all five learners rate the session 5/5 and say they'd recommend it.

Classify each observation: usability finding, learning finding, or neither-as-evidence. What is the fix-class for (a) versus (b)?

*Check yourself:* (a) usability — extraneous load; fix the interface, no pedagogy involved. (b) learning finding, and the week's most important kind — task completed, wrong rule inferred; the fix is pedagogical (a contrasting case that breaks "symmetry," a prediction probe), not cosmetic. (c) motivational read — probe task value before deciding whether it signals a design problem or a desirable difficulty doing its job. (d) neither-as-evidence: a smile-sheet rating at zero delay, the exact signal Chapter 1 taught you not to trust. If you classified (b) as a success because she completed the task, reread the learning-interaction section before attempting the checkpoint.

---

## The Evidence Box

**What is well-established:**

- **Early empirical testing with users prevents expensive failure.** Gould & Lewis (1985) — foundational, and confirmed by four decades of usability engineering practice. The principle, not a point estimate, is the finding.
- **Performance during a session dissociates from durable learning.** Soderstrom & Bjork (2015). This is the load-bearing warning for the whole chapter: prototype-session data systematically flatters fluent designs.

**What is moderately supported:**

- **Parallel prototyping beats serial refinement.** Dow et al. (2010), controlled experiment: parallel prototypers produced better-rated outcomes, explored more divergently, fixated less. One strong study plus consistent practice wisdom — robust direction, modest evidence mass.
- **Small-sample testing finds most frequent problems.** Nielsen & Landauer (1993) — the "five users" curve. Contested in scope: holds best for frequent usability defects in homogeneous user groups; explicitly *not* a prevalence estimate, and weak for rare or subgroup-specific failures. Treat as a budgeting heuristic, not a law.

**What is thin or unsettled:**

- **Design sprints in curriculum contexts.** Case-study evidence only (design-summit and sprint-in-STEAM reports; single studies, no controls) [verify]. The sprint container plausibly transfers; nothing yet shows it outperforms slower iteration on learning-relevant outcomes. **Single-source flag** on each individual education-sprint report.
- **Transfer validity of low-fi findings for *learning* (vs usability) failures.** The claim that paper prototypes catch misconception-level failures rests on practice experience and the logic of generative probes, not on a comparative literature quantifying what low-fi tests miss. This book teaches it as strong craft knowledge, honestly labeled as such.

---

## Worked Example: Prototyping the Sampling-Distribution Segment

*Track A continuing case. Chapter 7's co-design record set the direction for Unit 4 of the introductory statistics course: keep the retrieval practice, add an ungraded practice attempt with immediate elaborated feedback, add a simulation-tool sandbox, and redesign the sampling-distribution simulation activity itself — the segment where Chapter 5's research found the misconception that larger samples produce more variable sample means (cf. delMas et al. 2007), and Chapter 6's map found the dropout cliff.*

**Situation.** The designer must produce a tested prototype of the redesigned simulation segment in one week, for the Prototype Checkpoint. The accepted design direction: a *predict–observe–explain* structure — the learner commits to a prediction about what the sampling-distribution histogram will do when sample size increases, runs the simulation, then explains the result — wrapped in the new low-stakes practice-check framing.

**The problem as the designer sees it.** The riskiest unknown, written as the chapter demands: *"I don't know whether the predict–observe–explain activity actually confronts the variability misconception — or whether learners can complete it while the misconception survives intact."* Everything else — tool choice, visual design, even the feedback wording — is downstream of that.

**Process — including the dead ends.**

*Dead end one: starting in the authoring tool.* The designer begins, naturally, in Storyline — the course lives there, so why not prototype there? Two days vanish into slider behavior and histogram animation timing. Worse, the first informal tester comments on the chart colors and the font. The artifact's polish is steering the feedback exactly as Buxton predicts. The build is shelved (not deleted — the slider work will be reused), and the question is demoted down the fidelity ladder.

*The paper version.* One afternoon: nine hand-drawn screens, plus a deck of pre-printed histogram cards showing sampling distributions at n = 5, 25, 100. The designer plays the simulation engine — learner sets a sample size, designer lays down the corresponding card. Prediction probe before each reveal; explanation probe after. Wizard-of-Oz feedback: the designer reads elaborated feedback aloud from a script, varying it to probe what learners do with it.

*The test.* Five learners from the Chapter 7 panel pool, 30 minutes each, think-aloud protocol, two-column test sheet. Findings:

- **Usability column:** two learners couldn't tell which histogram was "the data" and which was "the sample means" — a labeling failure; one wanted to change her prediction after seeing the card (flow gap).
- **Learning column — the one that matters:** *three of five learners made the correct prediction for the wrong reason.* The prompt asked whether the histogram would get "wider or narrower"; learners answered "narrower" while their explanations revealed they were reasoning about the *range of the raw data* ("you'd have fewer weird values with more people"), not the variability of sample means. Task completed; misconception intact; the prototype, as worded, was un-teaching nothing — and a polished build of it would have shipped this failure invisibly.

*Dead end two: the seductive fix.* The designer's first revision instinct is an animated explainer of sampling variability — engaging, beautiful, and a retreat from generation back to presentation (Chapter 3 would call it trading germane processing for fluency). Caught at the Evidence Disclosure stage and dropped.

**Resolution.** The revision forces the misconception into the open instead of explaining it away: the prediction step now presents *two labeled candidate histograms* — one narrower (correct), one wider-but-smoother (the misconception's signature, drawn from the learners' own recorded explanations) — and requires choosing *and typing one sentence of why* before the reveal. Re-test with three fresh learners: the wrong-reason-right-answer pattern now surfaces *visibly in the choice itself*, and the scripted feedback addresses it directly. Fidelity decision for the next iteration, with cost justified: a medium-fidelity interactive build is now warranted — the reveal's pacing and the slider's feel are genuinely open questions paper cannot answer — but voice-over, illustration, and adaptive difficulty remain unjustified spends until the pilot.

**The lesson.** The cheapest prototype that could catch the misconception caught it in week one for the cost of an afternoon — and the most dangerous test result of the week was a completed task.

**The limit.** Eight short sessions established comprehension and trapped a misconception; they established nothing about whether the redesign improves retention, transfer, or Unit 4 completion — those claims now sit, explicitly, in the assumptions-awaiting-measurement register until Week 13 instruments them. And the five-then-three sample was drawn from volunteers; the learners the cliff actually claims were not in the room.

### Track B Extension

Run the same arc on your own project this week: write your riskiest-unknown sentence; choose the lowest fidelity that can answer it (expect, like the worked example, to feel the authoring tool's pull — resist it once, deliberately); build the two-column test sheet with at least two prediction probes targeted at *your* documented misconceptions from Chapter 5; test with 3–5 real learners; revise once and state the fidelity decision for the next iteration with its cost justified. Your Evidence Disclosure must name at least one finding from each column — and if your learning column is empty, the finding is about your protocol, not your design: add generative probes and re-test before submitting.

---

## Exercises

**8.1 — Autopsy the ninety seconds (Analyze).** Reconstruct the opening case as a fidelity-ladder failure: identify the riskiest unknown the team never named, the lowest rung that would have answered it, the channel (inferred rule / load / feedback uptake / motivation) the failure lived in, and the earliest week it was catchable. Then name one thing the four-month build *did* legitimately answer that paper could not have. (~400 words.)

**8.2 — Two columns under pressure (Analyze).** You are given five raw observations from a peer's prototype test (your instructor will provide the set, or trade test sheets with a classmate). Classify each as usability or learning finding, state the fix-class, and flag any observation that is *neither-as-evidence* — fluency or satisfaction data masquerading as a result. Justify the hardest call in two sentences.

**8.3 — PROTOTYPE CHECKPOINT (Create; production milestone — 100 pts).** Submit: **(1) the prototype** — low-fidelity artifact (paper, cards, Wizard-of-Oz script, or clickable mockup) of one redesigned segment, with your riskiest-unknown sentence on its cover page; **(2) the test report** — protocol, participants (n ≥ 3 real learners), the two-column findings sheet, at least one prediction-probe transcript excerpt, and the revision you made; **(3) the Evidence Disclosure** (template below), including the fidelity decision for the next iteration with cost justified. *Track A: the statistics course segment. Track B: your own project's segment (+5 Track B bonus per the studio rule).* **This is the track-switch decision point:** after receiving checkpoint feedback, you may switch tracks once, without penalty — switch to Track A if learner access has proven unreliable (you need learners again in Weeks 9, 13, and 14; decide on your real access, not your hopes), or to Track B if your own project and learner pipeline are now solid. State your track decision and one-sentence rationale on the cover page. *Grading note: the checkpoint rewards the quality of the question asked and the honesty of the findings — a rough prototype that trapped a real misconception outscores a polished one that reports only smooth completions.*

**8.4 — Stretch: the Wizard's rehearsal (Apply).** Before Week 12 makes it graded, Wizard-of-Oz one AI behavior your project might someday include (adaptive hints, tutor-style feedback): script the human-behind-the-curtain rules, run it with one learner, and report what they *did* with the assistance — including any sign of the crutch pattern (help-seeking before attempting). One page.

---

## Evidence Disclosure — Chapter 8 Template

Complete and attach to the Prototype Checkpoint:

1. **The riskiest unknown:** the single sentence, and why this unknown outranked the others.
2. **Fidelity justification:** the rung you chose, the rungs you rejected (one line each on why — too low to answer, or too costly for the question).
3. **Evidence-grounded decisions:** which prototype features implement published evidence (name the finding and citation — e.g., generation over presentation, retrieval framing).
4. **Research-grounded decisions:** which features implement your own learner research or co-design record, with no published evidence either way.
5. **Findings by column:** at least one usability finding and one learning finding, each with its fix-class.
6. **Assumptions awaiting measurement:** every claim your test could *not* establish (durable retention, completion effects, decay), stated as testable assumptions addressed to your Week 13 plan.
7. **Track decision:** stay or switch, and the rationale in one sentence.

---

## What Would Change My Mind

This chapter's core bet is that low-fidelity tests have sufficient transfer validity for learning-relevant failures — that the misconceptions and comprehension breakdowns a paper prototype surfaces are substantially the same ones the built experience would produce. A specific finding would break that bet: a comparative study showing that learning-design failures detected in deployed versions are *systematically absent* from low-fidelity tests of the same designs — for instance, because misconception expression depends on the real system's pacing, feedback timing, and privacy (no facilitator watching) in ways hand-operated prototypes structurally cannot reproduce. If low-fi tests were shown to catch interface problems but reliably miss the inferred-rule failures this chapter claims they catch, the fidelity ladder would need inverting for learning questions — prototype cheap for usability, but go straight to instrumented pilots for pedagogy — and the week's method would be rebuilt around that split.

---

## Still Puzzling

- **The zero-delay bias has no clean correction.** Prototype tests flatter fluency and punish desirable difficulty (Soderstrom & Bjork 2015). We can refuse to *select* designs on session performance — but is there any session-scale signal that *positively predicts* delayed retention? Germane-load signatures? Quality of generated explanations? This would be enormously useful and appears unestablished [verify].
- **Five learners, whose five?** Small-sample detection logic assumed homogeneous users. Learning experiences serve documented variability (Chapter 9 arrives next week) — should the five seats be allocated by misconception profile, by access needs, by risk of dropout? No principled allocation rule exists.
- **When is the Wizard a lie too far?** Wizard-of-Oz testing of AI tutoring blurs into deceiving learners about whether a human is watching their struggle. The HCI consent norms were written for usability labs, not for simulated intimacy with a fake tutor. The ethics here feel one IRB controversy away from being rewritten.

---

## Chapter Summary

You can now: choose prototype fidelity as a research decision matched to a named riskiest unknown, and justify the cost of each rung you climb; build and run a learning-interaction test — think-aloud with prediction probes — that captures inferred rules, load signatures, feedback uptake, and motivational reads, not just task completion; keep a two-column discipline that separates usability failures from learning-design failures, because their fixes differ in kind; adapt the design-sprint container to curriculum, with the evidence screen inside the decision step; deploy paper, Wizard-of-Oz, and authoring-tool media by the channel each tests best; and — the week's hardest capability — state plainly what your prototype cannot show, handing durable-retention and decay questions forward as named assumptions rather than quiet overclaims. You have a tested prototype. It works for the learners who were in the room.

---

## Key Terms

- **Prototype:** an artifact built to generate evidence about a design decision before the decision becomes expensive — a question made testable.
- **Fidelity:** the degree to which a prototype resembles the final experience (visual finish, interactivity, content completeness); chosen per test, not maximized.
- **Fidelity ladder:** the ordered sequence from sketch to pilot; the discipline of climbing one answered question at a time.
- **Riskiest unknown:** the single unanswered question whose wrong answer would be most expensive; the selector for fidelity and medium.
- **Learning interaction test:** a protocol probing inferred rule, load signature, feedback uptake, and motivational read — beyond interface usability.
- **Prediction probe:** asking the learner to commit to a prediction (and a why) before the system responds; the trap that catches misconceptions in the act.
- **Wizard of Oz prototype:** a hidden human simulating system intelligence to test adaptive behavior before it is built (Kelley 1984).
- **Two-column discipline:** recording every test observation as either a usability finding or a learning finding, with different fix-classes.
- **Zero-delay bias:** the structural tendency of prototype sessions to flatter fluent designs and punish desirable difficulties, because they measure performance where learning is invisible.

---

## Bridge

Your prototype works — for the five-or-so learners who were in the room. They were volunteers; they could see the screen, hear the audio, spare the time, and operate the slider; they brought whatever language, prior knowledge, and bandwidth your recruiting happened to select for. The next three weeks stress-test the design against the learners who weren't in the room — beginning with the hardest question in the course: how do you design for the full variability of human learners when accessibility is non-negotiable and the most popular framework for doing it has a contested evidence base?

---

## Further Reading

- **Knapp, J., Zeratsky, J., & Kowitz, B. (2016). *Sprint: How to Solve Big Problems and Test New Ideas in Just Five Days.* Simon & Schuster.** The sprint container in its original form — read it as craft literature, then apply this chapter's three adaptations.
- **Buxton, B. (2007). *Sketching User Experiences.* Morgan Kaufmann.** The deepest argument for roughness as a feature: why sketches invite the critique that polish suppresses.
- **Dow, S. P., et al. (2010). "Parallel prototyping leads to better design results, more divergence, and increased self-efficacy." *ACM TOCHI*, 17(4).** The controlled evidence that holding multiple cheap hypotheses beats refining one precious one.
- **Stickdorn, M., Hormess, M., Lawrence, A., & Schneider, J. (2018). *This Is Service Design Doing.* O'Reilly.** The prototyping methods chapters — desktop walkthroughs, cardboard prototyping, Wizard of Oz variants — are the most complete practical catalog in print.
- **Gould, J. D., & Lewis, C. (1985). "Designing for usability: Key principles and what designers think." *Communications of the ACM*, 28(3).** Forty years old and still the clearest statement of why early user contact is non-negotiable.

---

## LLM Exercise: Stress-Test the Test

*Productive-struggle guardrails: the LLM critiques your protocol; it does not run your test. It must never simulate learner responses, invent findings, or substitute for the n ≥ 3 real learners the checkpoint requires — an LLM roleplaying a confused student tells you about the model's training data, not about your learners' misconceptions.*

After drafting your Prototype Checkpoint test protocol (and before running it), paste your riskiest-unknown sentence, your prototype description, and your full protocol into an LLM with this prompt:

> You are a methods reviewer for a learning-experience prototype test. Here are my riskiest unknown, my prototype description, and my test protocol, including every probe question: [PASTE YOUR OWN ARTIFACTS].
>
> Audit, in order: (1) Can my protocol actually answer my riskiest unknown — or does it only test whether the interface is operable? Point to the specific probes that do learning-channel work (inferred rule, load, feedback uptake, motivation), and name any channel I have left unprobed. (2) Find every probe that is recognition-based where it should be generative, and explain what each will fail to catch — do not rewrite them for me. (3) Identify the one observation my protocol is most likely to misclassify as a success (a completed task hiding a wrong rule). (4) List three claims I might be tempted to make from this test that the zero-delay structure of a prototype session cannot support.
>
> Ask me questions where my protocol is ambiguous rather than assuming answers. Do not generate sample learner responses or findings. If I have pasted no protocol above, refuse and tell me to draft one first.

Submit with your checkpoint: the unprobed channel the LLM identified (or its hardest critique), the probe you rewrote yourself in response, and one sentence on what the audit changed.
