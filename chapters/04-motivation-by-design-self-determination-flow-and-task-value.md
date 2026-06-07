# Chapter 4 — Motivation by Design: Self-Determination, Flow, and Task Value

**Week 4 · Act One — Establish · [MIDTERM: EVIDENCE DIAGNOSTIC]**

---

## Learning Objectives

By the end of this chapter you will be able to:

1. **(Understand)** Explain autonomy, competence, and relatedness as design requirements, with one concrete design expression of each.
2. **(Apply)** Diagnose a provided product's motivation design: which self-determination needs it serves, which it starves.
3. **(Analyze)** Predict from design structure whether a gamified system will sustain motivation or decay after novelty, using the intrinsic/extrinsic distinction.
4. **(Evaluate)** Judge a design against the task-value finding — is the personal or professional utility of the content visible to the learner by design, or merely assumed?

*Track note: there is no Track A/B split this week. The studio tracks diverge starting in Chapter 5, when you begin applying methods to your project. This chapter — and the midterm it carries — is the diagnostic capability both tracks depend on.*

---

## Opening Case: The Leaderboard That Worked Until It Didn't

*Illustrative case. This is a composite built from the documented pattern in the gamification literature — see the Evidence Box — not a single named company. The numbers are representative, not reported.*

The learning platform team at a mid-sized logistics company had a problem most teams would envy: leadership wanted *more* engagement with the compliance and upskilling library, and was willing to fund it. The team shipped a leaderboard. Every completed module earned points; points ranked employees within their region; the top ten names appeared on a dashboard that managers could see.

The launch was everything the vendor's case studies promised. Weekly active users tripled in the first month. Module completions ran 240% above baseline by week five. The post-launch pulse survey came back glowing — "fun," "finally a reason to do these," "love seeing my name up there." The team presented the numbers to leadership in week six and was asked to extend the mechanic to the entire learning catalog.

Then the curve bent. Week eight: completions still above baseline, but falling. Week ten: at baseline. Week twelve: *below* the pre-launch baseline — meaning fewer people were now completing modules than before the leaderboard existed. The same employees who had raced up the rankings in October were, by January, not opening the platform at all. The pulse surveys, notably, stayed positive the whole time. People still *said* they liked the leaderboard. They had simply stopped acting.

The team's first hypothesis was a content problem: maybe the library had been exhausted by the early burst. The data said no — most users had completed fewer than 15% of available modules. The second hypothesis was a novelty problem, which was closer, but it raised the question the team could not answer: novelty of *what*, exactly, had worn off — and why did engagement land *below* where it started, rather than returning to it?

That last detail is the tell, and by the end of this chapter you will be able to read it. A mechanic that merely stops working returns you to baseline. A mechanic that lands you *below* baseline did something to the motivation that was already there. The leaderboard didn't just fail to add fuel. It displaced the fuel the system was running on.

---

## Prerequisites

Before this chapter you should be able to:

- **Distinguish behavioral, cognitive, and affective engagement** and explain why high behavioral engagement is not evidence of learning (Chapter 1).
- **Read a reported effect size** (Hedges' *g*), and state what a meta-analytic average does and does not establish, including heterogeneity (Chapter 1).
- **Classify mental effort** as intrinsic, extraneous, or germane load, and distinguish a desirable difficulty from a design flaw (Chapter 3).

---

## Core Content

### 4.1 Motivation Is a Quality, Not a Quantity

The leaderboard team's mistake begins with a unit error. They treated motivation as a single quantity — a tank you can fill with any fuel — and asked only "how much?" The motivation research of the last four decades says the more important question is "what kind?"

**Self-determination theory (SDT)**, developed by Edward Deci and Richard Ryan, is the most empirically supported framework we have for that question (Deci & Ryan 1985; Ryan & Deci 2000). Its central move is to arrange motivation on a continuum of *quality*: from **amotivation** (no intent to act), through **extrinsic motivation** (acting for a separable consequence — a reward, a ranking, an avoided punishment), to **intrinsic motivation** (acting because the activity is itself satisfying). Crucially, extrinsic motivation is not one thing: it ranges from *external regulation* (I do it for the points) through progressively more **internalized** forms up to *identified* and *integrated* regulation (I do it because it serves who I am becoming). A nursing student grinding through pharmacology flashcards is rarely intrinsically motivated by flashcards — but "this is what a safe nurse does" is internalized extrinsic motivation, durable in a way points are not.

The design relevance is direct: behaviors driven by external regulation persist only while the regulator is present and salient. Behaviors driven by internalized or intrinsic motivation persist on their own. A meta-analysis of SDT-based interventions in education found that interventions supporting students' basic psychological needs reliably improved motivation, engagement, and academic outcomes, with effects that held across school levels and cultures (Wang et al. 2024). The framework is not a loose humanistic preference; it is one of the better-replicated bodies of intervention evidence available to a learning designer.

**Design application.** When you evaluate a motivation mechanic, your first diagnostic question is never "will this increase activity?" Almost anything novel increases activity. The question is: *what kind of motivation does this mechanic recruit, and what happens when the mechanic is removed?* That second clause — the removal test — is the motivational equivalent of Chapter 1's delayed retention test. You will apply it formally in the worked example.

### 4.2 Autonomy, Competence, Relatedness: Needs as Design Requirements

SDT's engine is the claim that intrinsic and well-internalized motivation grow when three basic psychological needs are supported, and wither when they are starved (Ryan & Deci 2000):

**Autonomy** — the experience of volition; acting from choice rather than coercion. Autonomy is not the absence of structure (unstructured experiences often *reduce* felt autonomy by inducing helplessness). It is *meaningful choice within structure*. Design expressions: letting learners choose the order of practice topics, the example domain a problem set draws from, or which of two project briefs to pursue — while the learning outcomes stay fixed. Anti-patterns: forced linear sequences with arbitrary locks; deadlines whose timing communicates institutional convenience rather than pedagogical purpose; "personalization" that makes choices *for* the learner and calls it autonomy.

**Competence** — the experience of growing mastery against optimal challenge. Design expressions: difficulty that adapts to keep success rates in a productive band; feedback that is informational ("here is what your attempt reveals and what to try next") rather than purely evaluative ("7/10"); visible progress tied to *capability* ("you can now interpret a confidence interval") rather than *throughput* ("you completed 12 modules"). Note the connection to Chapter 3: desirable difficulties are competence-compatible precisely because the struggle is followed by genuine, perceptible growth. Difficulty with no growth signal is just frustration.

**Relatedness** — the experience of mattering to others and belonging. The most neglected need in EdTech, because it is the hardest to fake at scale. Design expressions: cohort structures with real interdependence; instructor presence that responds to the learner's actual work; peer review where your feedback visibly helps someone. Anti-pattern: a forum requirement ("post once, reply twice") that simulates the *behaviors* of community while delivering none of the experience of it.

**The diagnostic move.** Take any motivation mechanic and ask of each need: does this design *serve* it, *ignore* it, or *starve* it? A leaderboard, run through this filter, scores worse than intuition suggests. Autonomy: starved — it defines what counts and conscripts everyone into a competition they did not choose. Competence: served for the top decile, starved below it, because rank is a *normative* signal (how you compare) rather than a *mastery* signal (what you can do), and most participants in any ranking are, by construction, not winning. Relatedness: typically starved — rankings frame colleagues as rivals. This is not an argument that leaderboards never work (Chapter 10 treats the moderators seriously). It is the explanation the leaderboard team lacked: a systematic review of leaderboards in education finds effects varying with exactly these design features, with sustained benefit concentrated where mechanics support rather than substitute for the underlying needs [contested — see pantry flag; the gamification evidence is heterogeneous, with negative-effect studies in the meta-analytic pool].

### 4.3 Flow: A Useful Idea You Cannot Yet Measure Well

**Flow** is Mihaly Csikszentmihalyi's name for the state of total absorption that arises when challenge and skill are balanced near the upper edge of ability: time distortion, loss of self-consciousness, intrinsic enjoyment of the activity itself (Csikszentmihalyi 1990). Designers love flow, for good reason — it gives a vocabulary for the felt quality of great learning experiences, and the *challenge-skill balance* idea converges nicely with both desirable difficulties (Chapter 3) and SDT's competence need.

Now the discipline. This book treats flow with two stated caveats, and you should carry both into practice:

**First, flow measurement is inconsistent.** Across the educational literature, "flow" has been operationalized as retrospective surveys of varying construction, experience-sampling pings, behavioral persistence, and physiological proxies — and these measures do not cleanly converge. Reviews of the educational flow literature repeatedly note inconsistent operationalization across studies. Practically: when a vendor or a paper claims a design "produces flow," you usually cannot tell what was measured, and two such claims are usually not comparable. This caveat is stated honestly because the field often doesn't: flow is the weakest-measured construct in this chapter, full stop.

**Second, flow is not evidence of learning.** Absorption can attach to the *interface* rather than the *content* — a slot machine produces flow-like absorption and teaches nothing. This is the seductive-details problem (Chapter 1) wearing a more flattering name. A learner in flow with the game layer of your product may be in flow *around* the learning, not through it.

**Design application.** Use flow as a *design heuristic* — "is the challenge calibrated to the learner's current skill, with immediate feedback?" is an excellent question — and refuse it as an *evaluation claim*. If you find yourself writing "the redesign will increase flow" in a design rationale, replace it with the measurable commitments hiding underneath: success-rate bands, time-to-feedback, voluntary persistence after the required task ends. Those you can instrument (Chapter 13). "Flow" you currently cannot, at least not in a way two reasonable evaluators would agree on.

### 4.4 Task Value: The Strongest Predictor You Are Probably Not Designing For

Here is the finding that should most rearrange your design priorities, and it comes from outside SDT. **Expectancy-value theory** (Eccles et al. 1983; Eccles & Wigfield 2002) holds that effort on a learning task is a joint function of *expectancy* ("can I succeed at this?") and *task value* ("is this worth doing?") — with task value decomposing into **utility value** (it serves my goals), **attainment value** (it matters to my identity), **intrinsic value** (it interests me), and **cost** (what I give up to do it).

In research on online learners' engagement, self-efficacy, task-value beliefs, and self-regulation together explained 31% of the variance in engagement, 47% in critical thinking, and 57% in elaboration strategies — and **task-value beliefs emerged as the strongest single predictor of the cognitive behaviors that produce learning** [verify — single study reported in the course synthesis; the variance percentages should be sourced to the primary paper before manuscript freeze, and they describe correlational, not causal, structure]. Treat the precise numbers as provisional and the direction as well-supported: across the expectancy-value literature, perceived value of the task is consistently among the strongest predictors of the quality — not just quantity — of engagement.

Why does this rearrange priorities? Because most learning products spend their motivation budget on *expectancy* supports (scaffolding, encouragement, progress bars) and on engagement mechanics (Section 4.5), while leaving task value *assumed*. The course catalog says "this module covers hypothesis testing"; nowhere does the experience itself show the learner what hypothesis testing will let *them* do, decide, or avoid. The value exists — the instructor could articulate it in a sentence — but it is not *visible in the design*. The learner is left to supply the "why" themselves, and the learners most likely to disengage are precisely those least equipped to supply it.

**Design application.** Task value is designable. Concretely: open units with an *authentic decision* the skill enables, not a topic announcement ("Here is a real A/B test report; by Friday you'll be able to say whether its conclusion is justified" beats "Unit 6: Significance Testing"). Make future use visible — show where this skill reappears in the learner's stated goal, role, or the course's own later weeks. Build *explicit transfer moments* where the learner applies the skill to material from their own context. And design for **cost**, the forgotten quadrant: every hour of friction, every opaque requirement, is a debit against value, which is one reason Chapter 6's journey mapping tracks friction so obsessively. The persuasion literature would tell you to *claim* value loudly; the evidence here says to make value *experienceable*. The difference between those two is roughly the difference between marketing and design.

### 4.5 Extrinsic Rewards: Decay, Crowding, and the Persuasion Boundary

The leaderboard's below-baseline landing now needs its mechanism. The classic demonstration is Lepper, Greene & Nisbett (1973): preschoolers who enjoyed drawing were promised a certificate for drawing; after the reward phase ended, they drew *less than they had before the reward was introduced* — and less than children never rewarded. The reward had converted "I draw because I like it" into "I draw to get the certificate," and when the certificate stopped, so did the drawing. This **overjustification effect** scaled into a famous meta-analysis: Deci, Koestner & Ryan (1999), synthesizing 128 experiments, found that tangible rewards made contingent on doing, completing, or performing well at an interesting task reliably *undermined* subsequent intrinsic motivation. The economists' name for the same family of phenomena is **motivational crowding-out**: an external incentive can displace, rather than add to, the internal reasons for acting.

Two honest qualifications, because this finding is frequently overclaimed. First, the undermining effect applies to *interesting* tasks — rewards for tasks with no initial intrinsic pull have little to crowd out, and *verbal, informational* feedback tends to enhance rather than undermine. Second, the meta-analysis itself was contested (Cameron and Eisenberger argued the effect was narrower); the field's settled center is that *expected, tangible, contingent* rewards on already-meaningful activity carry real crowding risk, while unexpected rewards and competence-affirming feedback largely do not. In gamification the pattern recurs: a longitudinal classroom study found students in a course gamified with badges, leaderboards, and competition showed *lower* intrinsic motivation and final exam performance than the control by semester's end (Hanus & Fox 2015), and meta-analytic averages — moderately positive overall (*g* = 0.782 in Zeng et al. 2024) — conceal negative-effect studies in the pool [contested — see pantry flag; Chapter 10 treats this heterogeneity as the headline, not a footnote].

It is worth marking a boundary this book will hold throughout: between **motivation design and persuasion engineering**. Cialdini's influence research (Cialdini 2009) catalogs compliance mechanics — commitment and consistency, social proof, scarcity — that demonstrably move behavior. Streaks are commitment devices; leaderboards are social proof; "limited-time" badges are scarcity. These mechanics *work*, in the sense that they produce behavior. But Cialdini's framing is about *compliance*, and compliance is exactly the wrong target for a learning designer: behavior that persists only under the mechanic's pressure, justified by the mechanic rather than the activity. A persuasion mechanic in a learning product is a loan against future motivation. Sometimes the loan is worth taking — to carry a learner over a cold start. But the evidence-disciplined designer takes it knowingly, names the decay risk, and plans the handoff to internalized motivation. The leaderboard team took the loan without knowing it was one.

### 4.6 Motivation as Prerequisite, Not Endpoint

A closing calibration, because this chapter can be misread as "motivation is the goal." It is not, and Act One's whole argument explains why: motivated engagement is *necessary but not sufficient* for learning. Motivation gets the learner to the desirable difficulty and keeps them there; it does not replace it. A design that maximizes motivational comfort can fail exactly the way an engagement-maximizing design fails — by removing the effortful processing that produces learning. (Chapter 12's AI tutor is the canonical case: highly satisfying support that bypassed struggle and produced 17% worse exam performance; Bastani et al. 2025.)

So the design stance this chapter hands you is conditional: *first* secure the learning mechanism (Chapter 3), *then* design the motivational support that keeps learners engaged with it — autonomy-supportive structure, competence-calibrated challenge, genuine relatedness, visible task value — and treat every engagement mechanic beyond those as an empirical claim with a stated decay risk. Motivation by design, not motivation as decoration.

---

## Mid-Chapter Checkpoint

*Ungraded. Answer before reading on.*

A language-learning app introduces a "streak" counter: consecutive days of practice, with a badge at 30 days and a public profile flame. Daily active use rises 40%. Using the vocabulary of this chapter, write two sentences: one predicting what happens to practice behavior if the streak feature were removed after six months, and one naming which construct — external regulation, internalized regulation, or intrinsic motivation — the streak most plausibly recruits, and why.

*If you predicted behavior returns to or below baseline and named external regulation (commitment/consistency pressure with a separable consequence), you have the core mechanism. If you predicted behavior persists, ask yourself what in the streak design would have **internalized** the motivation — and if you can't name the mechanism, revisit Sections 4.1 and 4.5 before the worked example, because the midterm will ask exactly this kind of question.*

---

## The Evidence Box

**What the evidence supports, how strongly, and what remains unsettled.**

| Claim | Key evidence | Direction & strength | Unsettled |
|---|---|---|---|
| Supporting autonomy, competence, relatedness improves motivation and academic outcomes | Wang et al. (2024) meta-analysis of SDT-based educational interventions; Ryan & Deci (2000) | Positive, consistent across levels and cultures; one of the better-replicated intervention literatures | Which need-support components carry the effect; dosage; long-term durability beyond intervention windows |
| Expected tangible rewards contingent on interesting tasks undermine subsequent intrinsic motivation | Deci, Koestner & Ryan (1999), 128 experiments; Lepper, Greene & Nisbett (1973) | Negative effect on free-choice persistence; robust for expected/tangible/contingent rewards | Boundary conditions; the Cameron–Eisenberger dispute narrowed but did not erase the effect; verbal informational feedback is generally enhancing |
| Gamified learning improves academic performance on average | Zeng et al. (2024), 22 studies, n = 3,144, *g* = 0.782; Lampropoulos & Sidiropoulos (2024) longitudinal, n = 1,001 | Moderately positive **average**; heterogeneous — 2 of 22 studies negative; classroom counterevidence (Hanus & Fox 2015) | [contested — see pantry flag] Which mechanics, for whom, for how long; SDT-alignment as candidate moderator (Chapter 10) |
| Task-value beliefs are the strongest predictor of cognitive engagement quality | Expectancy-value research program (Eccles & Wigfield 2002); online-engagement study reporting 31%/47%/57% variance explained | Positive, direction well-supported across the program | [verify — the specific variance figures are single-source in the course synthesis and correlational; confirm primary citation before freeze] |
| Flow states mark optimal learning experience | Csikszentmihalyi (1990); educational flow studies | Conceptually generative; challenge-skill balance converges with competence and desirable-difficulty findings | **Measurement is the problem stated honestly: operationalizations are inconsistent across studies and do not cleanly converge. Flow claims are currently weak evaluation evidence.** Single studies claiming flow→learning links should be read with that flag. |

**Reading note:** the strongest rows here are the SDT intervention row and the reward-undermining row. The weakest is flow. The most *useful* for prediction is arguably the task-value row, even with its [verify] flag, because it points at a design surface (visible utility) that most products leave empty.

---

## Worked Example: Diagnosing the Leaderboard Decay

*Act One worked-example format: this is a diagnostic walk-through, not yet a design method. You are the consultant brought in at week fourteen of the opening case.*

**Situation.** Corporate learning platform; leaderboard launched at week 0; completions +240% by week five; baseline by week ten; *below* baseline at week twelve and still falling. Pulse surveys positive throughout. Leadership is asking whether to "refresh" the leaderboard with new prizes.

**The problem as the designer sees it.** The platform team frames it as an engagement-retention problem: "the mechanic fatigued; we need a stronger mechanic." Note what this framing assumes — that motivation is a quantity, that the leaderboard added some and the addition evaporated. Under that frame, the rational fix is escalation: bigger prizes, seasonal resets, team-based competition.

**Process — including the dead ends.** Walk the evidence-disciplined route:

*Dead end 1: the content-exhaustion hypothesis.* Checked first because it is checkable: completion data shows <15% library coverage per user. Rejected. (Cheap hypotheses first — this is good practice, not wasted time.)

*Dead end 2: the survey reassurance.* The team keeps citing positive pulse surveys as evidence the mechanic "still works." Apply Chapter 1: satisfaction is affective engagement, not behavior and not learning. People can like a leaderboard they no longer act on — liking is cheap. The surveys measure the wrong construct; set them aside.

*Dead end 3: "add a refresh."* Before recommending escalation, run the removal test mentally: if escalation worked, what would week 30 look like? The Deci–Koestner–Ryan mechanism predicts escalation buys another spike with a steeper fall, because each cycle further converts the activity's justification into "for the prize." The team is being offered a second loan to pay interest on the first.

*The diagnostic that lands.* Run the needs audit from Section 4.2 on the actual mechanic. Autonomy: conscripted — employees reported picking *short* modules to farm points, regardless of relevance (the metric became the task). Competence: rank is normative, not mastery-based; 90% of participants spent weeks 6–12 watching themselves lose. Relatedness: regional rivalry, zero collaboration affordances. Then check the *below-baseline* signature against the crowding literature: before launch, a modest population completed modules for internalized reasons (role relevance, manager encouragement). The leaderboard re-priced that activity in points. When the points stopped mattering, the original justification did not automatically return — overjustification predicts exactly this displacement (Lepper et al. 1973; Deci, Koestner & Ryan 1999).

**Resolution.** The recommendation is *not* "never gamify" (the meta-analytic average is positive; the heterogeneity is the point). It is: retire the global leaderboard rather than escalate it; rebuild around the starved needs — learner-chosen learning paths tied to role goals (autonomy), mastery-based progress signals replacing rank (competence), team-level practice with shared artifacts (relatedness); and make task value visible by attaching each module to a decision the employee's actual role requires. Set an explicit measurement plan: the success criterion is voluntary completion rate at +6 months *with no contingent reward in the system*, plus a delayed performance measure — not week-six activity, and not survey sentiment.

**The lesson (one sentence).** A motivation mechanic must be evaluated by what sustains behavior after the mechanic stops paying, because mechanics that recruit only external regulation decay — and can displace the internalized motivation that was already there.

**The limit.** This diagnosis is mechanism-confident but magnitude-uncertain: the needs audit and crowding literature explain the *shape* of the decay (spike, decay, below-baseline landing) but cannot tell you in advance *which* SDT-aligned redesign will recover motivation in this population, or how much of the pre-launch motivation is recoverable at all. That requires learner research — which is precisely why Act Two begins, next week, with researching learners before designing anything. The diagnostic toolkit you now have can read a failure; it cannot yet specify the alternative.

---

## Exercises

**Assessment note (per the course assessment structure):** this week carries the **Midterm Evidence Diagnostic (100 points)** — six unseen design claims; for each, you state the relevant evidence, its strength, and the design decision it warrants — plus **Evidence Brief #3 (30 points)**. Exercises 1–3 below are practice calibrated to the midterm's format; Exercise 4 is the Evidence Brief.

**Exercise 4.1 (Understand → Analyze).** Take a learning product you use. For each SDT need — autonomy, competence, relatedness — identify one design element that serves it or starves it, and classify the product's dominant motivational appeal as external regulation, internalized regulation, or intrinsic motivation. One page. *This is midterm-format practice: claim → evidence → classification.*

**Exercise 4.2 (Analyze — decay prediction).** Below are three mechanics: (a) a public weekly leaderboard reset every Monday; (b) an unlockable "explainer" role where learners who pass a mastery check can answer peers' questions; (c) a completion badge auto-posted to LinkedIn. For each, predict *sustain* or *decay after novelty*, name the mechanism behind your prediction (which needs are fed; what kind of regulation is recruited; what crowding risk exists), and state what data at +90 days would falsify your prediction.

**Exercise 4.3 (Evaluate — the task-value audit; production).** Choose one unit from a real course or product (Track B students: use your studio project; Track A students: use any module of the introductory statistics course shell provided on the course site). Produce a **task-value audit**: for utility, attainment, intrinsic value, and cost, document where in the actual learner-facing experience that value component is *visible by design* — quote or screenshot the element — or mark it ASSUMED. Then redesign the unit's opening (one screen, one paragraph, or one task) to make the strongest missing value component experienceable rather than claimed. Deliverable: audit table + before/after artifact + three-sentence rationale citing this chapter's evidence.

**Exercise 4.4 (Evidence Brief #3, 30 points).** One page, standard format. Claim to examine: **"Adding game elements increases learning."** Best evidence for; best evidence against (you must engage the heterogeneity and at least one negative-effect finding); and the design decision you would make under that uncertainty for a context you specify.

---

## Evidence Disclosure

*Every chapter models the disclosure you attach to studio work. This chapter's version:*

- **One decision the evidence constrained:** the worked example's recommendation to retire rather than refresh the leaderboard is constrained by the reward-undermining meta-analysis (Deci, Koestner & Ryan 1999) and the below-baseline behavioral signature it predicts; escalation was the intuitive move and the evidence overruled it.
- **One decision the evidence could not settle:** *which* SDT-aligned replacement mechanic (mastery paths vs. team practice vs. role-tied value framing) will best restore motivation for this population. The intervention literature supports the family of moves, not the ranking among them. That decision is research-grounded at best — it awaits the learner research methods of Chapter 5 and measurement under Chapter 13.

---

## What Would Change My Mind

This chapter's load-bearing claim is that engagement mechanics recruiting only external regulation decay after novelty and risk crowding out existing motivation. Here is what would force a rewrite: a preregistered, multi-site longitudinal study (12+ months) in authentic learning settings showing that purely points-badges-leaderboard systems — with no autonomy, mastery, or relatedness affordances — sustain voluntary learning behavior at or above baseline after reward withdrawal, with no decrement in free-choice persistence relative to controls. If that result replicated across populations, the "loan against future motivation" framing would be wrong, and this chapter's diagnostic would need to treat extrinsic mechanics as a durable fuel rather than a bridge. The longitudinal gamification evidence we have (Lampropoulos & Sidiropoulos 2024) is *not* that study: its sustained gains came from a multi-mechanic design over three years, and it cannot isolate the pure-extrinsic case.

---

## Still Puzzling

1. **Internalization timing.** We know internalized motivation outlasts external regulation, but the field has weak guidance on the *handoff*: how long can a design lean on extrinsic mechanics before withdrawal, and what does the transfer-of-justification moment look like in instrumented data?
2. **Flow without measurement.** If flow's operationalizations don't converge, is the construct doing any work that "calibrated challenge + immediate feedback + voluntary persistence" doesn't do with better measurement properties? Should the field retire the term for evaluative use?
3. **Task value at scale.** Making utility visible works best when the design knows the learner's goals — but scalable products serve heterogeneous goals. Can task-value design survive scale, or is it inherently a contextualization move that platforms structurally resist?
4. **Cultural moderation.** The SDT meta-analytic evidence spans cultures, but autonomy's *design expressions* are culturally loaded. Which expressions travel and which don't is thinly studied.

---

## Chapter Summary

You can now do four things you could not do four weeks ago, and the midterm will ask you to prove it. You can classify a design's motivational appeal by *quality* — external, internalized, intrinsic — and run the removal test on any engagement mechanic. You can audit a design against the three basic psychological needs and say which it serves, ignores, or starves. You can read the decay signature of extrinsic mechanics — spike, fall, below-baseline landing — and explain it with the overjustification and crowding evidence rather than hand-waving about "novelty." And you can audit a learning experience for task value, the strongest engagement predictor in the evidence and the most neglected surface in practice, distinguishing value *visible by design* from value merely assumed. With Chapter 3's cognitive machinery, this completes Act One's diagnostic kit: you can critique with evidence. You cannot yet design from it. That begins now.

---

## Key Terms

- **Self-determination theory (SDT):** framework holding that motivation quality depends on support for three basic psychological needs — autonomy, competence, relatedness (Deci & Ryan).
- **Intrinsic / extrinsic motivation:** acting because the activity is satisfying in itself, versus acting for a separable consequence; extrinsic motivation varies in how far it is **internalized**.
- **Internalization:** the process by which externally regulated behavior becomes self-endorsed (identified or integrated regulation) — the durable form of extrinsic motivation.
- **Overjustification effect:** the reduction of intrinsic motivation after an expected tangible reward re-prices an already-interesting activity (Lepper, Greene & Nisbett 1973).
- **Motivational crowding-out:** the displacement of internal reasons for acting by external incentives; the economics-literature name for the reward-undermining family.
- **Flow:** absorption arising from challenge-skill balance with immediate feedback (Csikszentmihalyi); useful as a design heuristic, currently weak as a measurement target.
- **Expectancy-value theory:** effort as a joint function of expected success and task value — utility, attainment, intrinsic value, and cost (Eccles & Wigfield).
- **Task value (visible vs. assumed):** the learner-perceived worth of a task; this book's design standard is that value must be *experienceable in the design*, not asserted in the syllabus.
- **Removal test:** the diagnostic question for any mechanic — what behavior remains when the mechanic stops paying?

---

## Bridge

Act One is complete: you can take a design feature — a badge, an animation, an AI hint — and state the evidence-based case for and against it. But every diagnosis in this chapter ended at the same wall: the mechanism explains the failure, and only the learners can specify the fix. Act Two begins with the first design method, and the first rule of evidence-disciplined design: **research the learner before designing anything.** What do the people inside your learning experience actually know, wrongly believe, want, and value — and how would you find out without asking the questions that produce flattering lies?

---

## Further Reading

- **Ryan, R. M., & Deci, E. L. (2000). "Self-determination theory and the facilitation of intrinsic motivation, social development, and well-being." *American Psychologist*, 55(1).** The canonical statement of the needs framework and the internalization continuum — short, readable, and the source most "gamification psychology" decks are silently paraphrasing.
- **Deci, E. L., Koestner, R., & Ryan, R. M. (1999). "A meta-analytic review of experiments examining the effects of extrinsic rewards on intrinsic motivation." *Psychological Bulletin*, 125(6).** The 128-experiment synthesis behind this chapter's decay mechanism; read the boundary conditions, not just the headline.
- **Wang et al. (2024). Meta-analysis of SDT-based interventions in education.** The recent intervention-level support showing need-supportive designs improve motivation and outcomes — the strongest current warrant for treating SDT as a design constraint rather than a preference. [verify exact author list and journal before citation freeze]
- **Eccles, J. S., & Wigfield, A. (2002). "Motivational beliefs, values, and goals." *Annual Review of Psychology*, 53.** The expectancy-value program in review form; the cost component alone will change how you read journey maps in Chapter 6.
- **Cialdini, R. B. (2009). *Influence: Science and Practice* (5th ed.).** Read it as a designer's *boundary document*: every compliance mechanic catalogued here will be pitched to you as an engagement feature someday, and you should recognize the loan terms.

---

## LLM Exercise

*Productive-struggle guardrail: this prompt requires your completed draft diagnosis as input. An LLM given the case cold will produce a fluent, generic SDT essay — and you will learn nothing while feeling helped, which is this course's definition of a crutch. Do the diagnosis first; use the model as a hostile reviewer.*

Complete Exercise 4.2 (the three-mechanic decay prediction) on your own, in writing, before using this prompt. Then paste the following, with your work, into the LLM of your choice:

```
You are a skeptical motivation-science reviewer for a graduate LXD course.
I am pasting MY OWN decay-prediction analysis of three engagement mechanics.
Your job is to stress-test it, not to rewrite it.

Rules:
1. Do NOT produce your own analysis of the mechanics, and do NOT supply
   corrected predictions. Critique only what I wrote.
2. For each of my three predictions, identify: (a) whether my stated
   mechanism actually supports my prediction, or whether I named a
   construct without doing causal work with it; (b) one boundary
   condition from the motivation literature (e.g., reward expectancy,
   task interestingness, verbal vs. tangible feedback) that I ignored
   and that could flip my prediction; (c) whether my falsification
   criterion at +90 days would genuinely distinguish my prediction
   from the rival prediction, and if not, why not.
3. Flag every place I used "engagement," "motivation," or "novelty"
   without specifying WHICH construct (behavioral/cognitive/affective
   engagement; external/internalized/intrinsic regulation) I meant.
4. End with the three hardest questions a midterm examiner could ask
   me about my own analysis — and do not answer them.

Here is my analysis:
[PASTE YOUR COMPLETED EXERCISE 4.2]
```

**Assessable artifact:** submit (1) your original analysis, (2) the LLM's critique, and (3) a half-page revision memo stating which critiques you accepted, which you rejected, and the evidence behind each call. The memo is the graded part: accepting every critique scores no better than rejecting every critique — calibration is the skill.
