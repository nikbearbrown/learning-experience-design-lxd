# Chapter 4 — Motivation by Design: Self-Determination, Flow, and Task Value
*Why the leaderboard that worked until it didn't is the most diagnostic experiment your product will ever run.*

The learning platform team at a mid-sized logistics company had a problem most teams would envy: leadership wanted more engagement with the compliance and upskilling library, and was willing to fund it. They shipped a leaderboard. Every completed module earned points; points ranked employees within their region; the top ten names appeared on a dashboard that managers could see.

The launch was everything the vendor's case studies promised. Weekly active users tripled in the first month. Module completions ran 240% above baseline by week five. The pulse survey came back glowing — "fun," "finally a reason to do these," "love seeing my name up there." Leadership asked to extend the mechanic to the entire catalog.

Then the curve bent. Week eight: completions still above baseline, but falling. Week ten: at baseline. Week twelve: *below* the pre-launch baseline — meaning fewer people were completing modules than before the leaderboard had ever existed. The people who had raced up the rankings in October were, by January, not opening the platform at all. The pulse surveys stayed positive the whole time. People still *said* they liked the leaderboard. They had simply stopped acting on it.

The team's first hypothesis was a content problem: the library had been exhausted by the early burst. The data said no — most users had completed fewer than 15% of available modules. The second hypothesis was novelty: the mechanic had grown old. Closer, but it raised a question the team could not answer. If the leaderboard merely stopped working, completions would have returned to baseline. They landed *below* it. A mechanic that stops working returns you to where you started. A mechanic that drops you below where you started did something to the motivation that was already there.

That last detail is the tell, and this chapter is about learning to read it.

---

The mistake the leaderboard team made begins with a unit error. They treated motivation as a single substance — a tank you fill with any available fuel — and asked only "how much?" Four decades of motivation research says the more important question is "what kind?"

Self-determination theory, developed by Edward Deci and Richard Ryan, arranges motivation on a continuum of quality rather than quantity (Deci & Ryan 1985; Ryan & Deci 2000). At one end: amotivation, no intent to act. At the other: intrinsic motivation, acting because the activity is satisfying in itself. In between: extrinsic motivation, acting for a separable consequence. The crucial move is that extrinsic motivation is not one thing. It ranges from *external regulation* — I do it for the points, and when the points stop, I stop — through progressively more internalized forms. A nursing student grinding pharmacology flashcards is rarely intrinsically motivated by flashcards. But "this is what a safe nurse does" is an internalized reason, and it will still be there after the quiz, after the course, after the app is deleted. Points will not.

A meta-analysis of SDT-based interventions in education found that supporting students' basic psychological needs reliably improved motivation, engagement, and academic outcomes — with effects that held across school levels and cultures (Wang et al. 2024). This is one of the better-replicated intervention bodies available to a learning designer, which is worth saying because the framework sometimes reads like humanistic preference. It is not. It is a body of experimental and quasi-experimental evidence that the motivation you build from converges on a prediction: behaviors driven by external regulation persist only while the regulator is present and salient. Behaviors driven by internalized or intrinsic motivation persist on their own.

The practical consequence: when you evaluate a motivation mechanic, the first question is not "will this increase activity?" Almost anything novel increases activity. The question is: *what kind of motivation does this mechanic recruit, and what happens when the mechanic is removed?* That second clause — the removal test — is the motivational equivalent of Chapter 1's delayed retention test. Apply it to every mechanic you are ever tempted to build.

---

SDT proposes three basic psychological needs whose support or starvation determines where on the quality continuum a given design will land.

**Autonomy** is the experience of acting from choice rather than coercion. The common misreading is that autonomy means absence of structure — in practice, unstructured experiences often reduce felt autonomy by inducing helplessness. Autonomy is meaningful choice within structure: which of these three practice domains would you like to draw problems from? Which project brief fits your context? The learning outcomes stay fixed; the path is the learner's. The anti-pattern is a forced linear sequence with arbitrary locks communicating nothing except "the system won't trust you until you've clicked through its requirements." That is coercion with a progress bar.

**Competence** is the experience of growing mastery against challenge calibrated near the upper edge of ability. Design expressions: feedback that is informational rather than merely evaluative — "here is what your attempt reveals and what to try next" rather than "7/10" — and visible progress tied to capability rather than throughput. "You can now interpret a confidence interval" is a competence signal. "You've completed 12 modules" is a throughput signal. One tells the learner what has grown inside them. The other tells them how much of the product they have consumed. These are not the same, and learners who have been saturated with throughput signals while starved of competence signals tend to describe a specific feeling: busy, and somehow not better.

**Relatedness** is the experience of mattering to others and belonging — the most neglected need in EdTech, because it is the hardest to fake at scale. A forum requirement that says "post once, reply twice" simulates the behavioral surface of community while delivering none of its experience. Relatedness requires that your contribution changes something for someone, and that you know it. Real interdependence, real instructor response to your actual work, peer review where you can see that your feedback helped — these are the conditions. The shortcut is to notice them by their absence: a learning product that has no mechanism by which one learner's action matters to another has, by omission, told every learner they are alone.

Run any motivation mechanic through these three. The leaderboard: autonomy starved, because it defined what counted and conscripted everyone into a competition they did not choose. Competence served for the top decile, starved below, because rank is a normative signal — how you compare — rather than a mastery signal — what you can do. In any ranking, most participants are not winning, by construction, and they are receiving a legible signal about it every time they check. Relatedness starved: colleagues as rivals, no collaboration affordances.

<!-- → [TABLE: SDT needs audit applied to four mechanics — columns: Mechanic, Autonomy (serves/ignores/starves), Competence (serves/ignores/starves), Relatedness (serves/ignores/starves), Removal-test prediction — rows: points leaderboard, streak counter, mastery badge, peer review with visible impact] -->

This is not an argument that leaderboards never work. The gamification evidence is heterogeneous — Chapter 10 treats that heterogeneity as the headline — and the moderators include exactly these design features. It is the explanation the leaderboard team was missing: not "it fatigued" but *which psychological needs it starved and which it served only conditionally*, and why the removal prediction therefore reads below baseline rather than back to it.

---

Before the mechanism behind that below-baseline landing, a detour through a concept you will meet constantly, and which deserves honest treatment.

Mihaly Csikszentmihalyi's concept of **flow** — the state of total absorption arising when challenge and skill are balanced near the upper edge of ability, marked by time distortion, loss of self-consciousness, intrinsic enjoyment of the activity — is genuinely useful as a design heuristic (Csikszentmihalyi 1990). The question "is the challenge calibrated to the learner's current skill, with immediate feedback?" is excellent. It converges nicely with SDT's competence need and with the desirable-difficulty reasoning from Chapter 3. Reach for it when you need a vocabulary for the felt quality of a well-calibrated learning experience.

But carry two caveats into every conversation where flow appears.

The first is a measurement problem, and it should be stated plainly: across the educational literature, "flow" has been operationalized as retrospective surveys of varying construction, experience-sampling pings, behavioral persistence, and physiological proxies — and these measures do not cleanly converge. Two studies claiming to show flow effects are usually not comparable, because they measured different things and called them the same name. When a vendor or a paper claims a design "produces flow," you usually cannot tell what was measured. Flow is the weakest-measured construct in this chapter, and the field often doesn't say so.

The second is the absorption-is-not-learning problem. Absorption can attach to the interface rather than the content. A slot machine produces flow-like absorption and teaches nothing. This is the seductive-details pattern from Chapter 1 wearing a more flattering name: a learner in flow with the game layer of your product may be in flow *around* the learning, not through it. Use flow as a heuristic — calibrated challenge, immediate feedback, voluntary persistence after the required session ends — and refuse it as an evaluation claim. Replace "this redesign will increase flow" with the measurable commitments underneath: success-rate bands, time-to-feedback, free-choice continuation rate. Those you can instrument. "Flow" you cannot, not in any way two evaluators would currently agree on.

---

Here is the finding that should most rearrange your design priorities, and it does not come from SDT at all.

Expectancy-value theory holds that effort on a learning task is a function of two things: expectancy ("can I succeed at this?") and task value ("is this worth doing?"). Task value itself decomposes: utility value — it serves my goals; attainment value — it matters to my identity; intrinsic value — it interests me; and cost — what I give up to do it (Eccles et al. 1983; Eccles & Wigfield 2002).

In research on online learners, task-value beliefs emerged as the strongest predictor of the cognitive behaviors that produce learning — stronger than self-efficacy, stronger than self-regulation, strongest predictor of the elaboration and deep processing that separate engagement from genuine comprehension [verify — single-source quantification in this synthesis; the direction is well-supported across the expectancy-value program, but the specific variance percentages need primary-source confirmation before manuscript freeze]. Treat the precise numbers as provisional. The direction is not.

Why does this rearrange priorities? Because most learning products spend their motivation budget on expectancy supports — scaffolding, encouragement, progress bars — and on engagement mechanics, while leaving task value assumed. The course catalog says "this module covers hypothesis testing." Nowhere does the experience show the learner what hypothesis testing will let *them* do, or decide, or avoid. The value exists; an instructor could articulate it in a sentence; but it is not visible in the design. The learner is expected to supply the "why" themselves, and the learners most likely to disengage are exactly those least equipped to supply it.

Task value is designable. Open a unit with an authentic decision the skill enables, not a topic announcement. "Here is a real A/B test report; by Friday you'll be able to say whether its conclusion is justified" does something "Unit 6: Significance Testing" does not. Make future use visible by showing where this skill reappears in the learner's stated goal or in the course's later weeks. And design for *cost* — the forgotten quadrant of expectancy-value — because every hour of friction, every opaque requirement, every dead end in the UX is a debit against the value account. Persuasion would tell you to claim value loudly. The evidence says to make value *experienceable*. The difference between those two is roughly the difference between marketing and design.

<!-- → [INFOGRAPHIC: Expectancy-value model as a design surface — quadrants showing utility, attainment, intrinsic value, and cost, each with one example of "visible by design" vs. "assumed" in a typical learning product — annotation showing where most products spend their motivation budget vs. where the evidence points] -->

---

Now the mechanism behind the below-baseline landing.

The classic demonstration is Lepper, Greene and Nisbett (1973): preschoolers who enjoyed drawing were promised a certificate for drawing. After the reward phase ended, they drew *less than they had before the reward was introduced* — and less than children who had never been rewarded. The reward had converted "I draw because I like it" into "I draw to get the certificate." When the certificate stopped, so did the drawing — and it took the original motivation down with it.

This overjustification effect scaled into a meta-analysis: Deci, Koestner and Ryan (1999), synthesizing 128 experiments, found that tangible rewards made contingent on performing an interesting task reliably undermined subsequent intrinsic motivation. The economists call the same phenomenon motivational crowding-out: an external incentive can displace, rather than add to, the internal reasons for acting.

Two honest qualifications, because this finding is frequently overclaimed. The undermining effect applies to *interesting* tasks — rewards for tasks with no initial intrinsic pull have little to crowd out. And verbal, informational feedback — "your analysis correctly identified the confound" — tends to enhance rather than undermine, because it supports competence rather than replacing intrinsic justification with a separable prize. The field's settled center is that expected, tangible, contingent rewards on already-meaningful activity carry real crowding risk. Unexpected rewards and competence-affirming feedback largely do not.

The logistics platform: before launch, a modest population was completing modules for internalized reasons — role relevance, manager encouragement, professional identity. The leaderboard re-priced that activity in points. Points became the reason. When the points stopped mattering, the original justification did not automatically return. Overjustification predicts exactly this: not a return to baseline but displacement below it, because the internal accounting was overwritten.

<!-- → [CHART: Two-curve chart showing predicted completion behavior with and without overjustification — pre-launch baseline, spike at mechanic launch, decay curve returning to or below baseline — annotation at below-baseline landing with "displacement zone" label] -->

A boundary worth marking here: the distinction between motivation design and persuasion engineering. Cialdini's influence research catalogs compliance mechanics — commitment and consistency, social proof, scarcity — that demonstrably move behavior (Cialdini 2009). Streaks are commitment devices. Leaderboards are social proof. Limited-time badges are scarcity. These mechanics work, in the narrow sense that they produce behavior. But they produce *compliance* — behavior that persists only under the mechanic's pressure and is justified by the mechanic rather than the activity. A compliance mechanic in a learning product is a loan against future motivation. Sometimes the loan is worth taking, to carry a learner over a cold start when the content itself has not yet established its own pull. But the evidence-disciplined designer takes it knowingly, names the decay risk, and plans the handoff to internalized motivation. The leaderboard team took the loan without knowing it was one.

---

A closing calibration, because this chapter can be misread as saying that motivation is the goal. It is not.

Motivated engagement is necessary but not sufficient for learning. Chapter 1's whole argument is that the experience learners prefer and the experience that teaches them are not the same experience. Motivation gets the learner to the desirable difficulty and keeps them there. It does not replace the difficulty. A design that maximizes motivational comfort can fail exactly the way an engagement-maximizing design fails — by removing the effortful processing that produces learning. Chapter 12's AI tutor is the canonical case: highly satisfying support that bypassed struggle and produced 17% worse exam performance on a subsequent unassisted test (Bastani et al. 2025). The learners were motivated. They were also, on the relevant measure, getting worse.

The sequence matters: first secure the learning mechanism, then design the motivational support that keeps learners engaged with it. Autonomy-supportive structure. Competence-calibrated challenge. Genuine relatedness. Visible task value. And treat every engagement mechanic beyond those four as an empirical claim with a stated decay risk — a loan, not a fuel source. Motivation by design, not motivation as decoration.

---

## Exercises

**Warm-up**

1. *(Recall — SDT)* Define autonomy, competence, and relatedness in your own words without looking at the text. For each, give one design expression from a product you use and one anti-pattern you have encountered. Three sentences per need.

2. *(Recall — removal test)* A language-learning app introduces a streak counter: consecutive days of practice, with a badge at 30 days and a public flame on your profile. Daily active use rises 40%. Using the vocabulary of this chapter, write two sentences: one predicting what happens to practice behavior if the streak feature were removed after six months, and one naming which construct — external regulation, internalized regulation, or intrinsic motivation — the streak most plausibly recruits, and why.

**Application**

3. *(Apply — needs audit)* Run the three-need SDT audit on a real mechanic from a product you use. For each need — autonomy, competence, relatedness — classify the mechanic as *serves*, *ignores*, or *starves*, with one sentence of evidence. Then apply the removal test: what does your audit predict about behavior at 90 days without the mechanic? State one piece of observable data that would falsify your prediction.

4. *(Apply — task value audit)* Choose one unit from a real course or product. For each value component — utility, attainment, intrinsic, and cost — document where in the actual learner-facing experience that component is *visible by design* or mark it ASSUMED. Then redesign the unit's opening (one screen, one paragraph, or one task) to make the strongest missing value component experienceable rather than claimed. Deliverable: audit table plus before/after artifact plus a three-sentence rationale citing this chapter's evidence.

5. *(Apply — flow limits)* A colleague argues: "Our redesign improved flow scores by 23% on the post-session survey." Write the two-paragraph response you would give: one paragraph naming what the measurement problem actually is and why two flow operationalizations are typically not comparable, and one paragraph proposing three specific, instrumentable alternatives that would let the team evaluate the same design change more rigorously.

**Synthesis**

6. *(Synthesize — decay prediction)* Three mechanics: (a) a public weekly leaderboard reset every Monday; (b) an unlockable "explainer" role where learners who pass a mastery check can answer peers' questions; (c) a completion badge auto-posted to LinkedIn. For each, predict *sustain* or *decay after novelty*, name the mechanism (which needs are fed, what regulation type is recruited, what crowding risk exists), and state what data at 90 days would falsify your prediction.

7. *(Synthesize — crowding vs. scaffolding)* A corporate learning team is considering adding points and a leaderboard to an onboarding module that survey data shows new hires already find relevant and engaging. Construct the argument against the leaderboard using the crowding literature, with effect sizes and their limits. Then construct the argument for a limited, cold-start extrinsic mechanic that phases out at day 30. Conclude with the design decision you would make and the data you would need to know you were right.

**Challenge**

8. *(Challenge — heterogeneity and design decision)* The Zeng et al. (2024) meta-analysis reports *g* = 0.782 for gamification's effect on academic performance — and two of twenty-two studies found negative effects. The Hanus and Fox (2015) classroom study found lower intrinsic motivation and exam performance in the gamified condition by semester's end. A client wants to gamify a 12-week professional certification course. Write the briefing you would give: what the meta-analytic average supports, what the negative-effect studies reveal about moderating conditions, what design features the SDT evidence would recommend to shift from the negative toward the positive side of the distribution, and what you would measure at 12 weeks to know which side you landed on.

---

## LLM Exercise

*Productive-struggle guardrail: this prompt requires your completed decay-prediction analysis as input. An LLM given the case cold will produce a fluent, generic SDT essay — and you will learn nothing while feeling helped. Complete Exercise 6 first, in writing, then use the model as a hostile reviewer.*

Copy everything between the lines into an LLM, filling in your work before you paste.

---

You are a skeptical motivation-science reviewer for a graduate LXD course. I am pasting MY OWN decay-prediction analysis of three engagement mechanics. Your job is to stress-test it, not to rewrite it.

Rules:
1. Do NOT produce your own analysis of the mechanics, and do NOT supply corrected predictions. Critique only what I wrote.
2. For each of my three predictions, identify: (a) whether my stated mechanism actually supports my prediction, or whether I named a construct without doing causal work with it; (b) one boundary condition from the motivation literature — reward expectancy, task interestingness, verbal vs. tangible feedback — that I ignored and that could flip my prediction; (c) whether my falsification criterion at 90 days would genuinely distinguish my prediction from the rival prediction, and if not, why not.
3. Flag every place I used "engagement," "motivation," or "novelty" without specifying WHICH construct — behavioral/cognitive/affective engagement; external/internalized/intrinsic regulation — I meant.
4. End with the three hardest questions a midterm examiner could ask me about my own analysis — and do not answer them.

Here is my analysis:
[PASTE YOUR COMPLETED EXERCISE 6]

---

*Assessable artifact: submit (1) your original analysis, (2) the LLM's critique, and (3) a half-page revision memo stating which critiques you accepted, which you rejected, and the evidence behind each call. The memo is the graded part: accepting every critique scores no better than rejecting every critique — calibration is the skill.*
