# Chapter 10 — Gamification Under Evidence: Motivation Mechanics That Survive the Meta-Analyses

## Learning Objectives

By the end of this chapter you will be able to:

1. **(Analyze)** Decompose a gamified product into its individual mechanics and classify each as serving autonomy, competence, relatedness, or pure extrinsic reward. *(Tracks A and B)*
2. **(Evaluate)** Judge whether gamification is warranted for a specified learning context, citing the meta-analytic evidence — including its negative-effect studies and the raises-the-ceiling-more-than-the-floor finding. *(Tracks A and B)*
3. **(Create)** Design — or explicitly decline to design — a motivation mechanic for the studio project, with an Evidence Disclosure covering decay risk. *(Track A: the gamification decision memo for the instructor's statistics course. Track B: the same memo for your own project, eligible for the Track B bonus.)*

These objectives sit deliberately high on Bloom's taxonomy. You already learned the motivation machinery in Chapter 4. This week you make a real design decision with it, under evidence that refuses to give you a clean yes or no.

## Opening Case: One Curriculum, Two Fates

Consider two deployments of the same gamified curriculum, three years apart in their outcomes and almost identical on their feature lists.

The first is documented. A higher-education course was gamified and tracked longitudinally — 1,001 students across three academic years — against both a traditional classroom condition and a plain online condition (Lampropoulos & Sidiropoulos 2024). The gamified condition won on every outcome the study measured: success rate, average grade, retention, and — most strikingly — excellence rate, the proportion of students earning top marks. That last detail matters and we will return to it: the biggest gain was at the top of the distribution. Gamification raised the ceiling more than the floor.

The second deployment is an illustrative composite — we label it as such because the institutions that live through this version rarely publish it — assembled from the pattern the extrinsic-reward literature predicts and practitioners repeatedly report (Deci, Koestner & Ryan 1999; Hanus & Fox 2015 [verify]). A different program licenses a similar curriculum and applies the same surface checklist: points, badges, a leaderboard, completion streaks. Usage spikes for six weeks. The launch retrospective declares victory. By week twelve, voluntary practice has fallen below the pre-launch baseline. The students who sit atop the leaderboard keep playing; the students in the bottom half, who can now see precisely how far behind they are, quietly stop logging in. Satisfaction surveys stay excellent the entire time — you saw this exact signature in the Chapter 4 opening case, and now you know to distrust it.

Same curriculum. Same nouns on the feature list. One deployment compounds for three years; one collapses after novelty. If "gamification" were a single treatment, this could not happen. The difference is not the badges. It is which psychological needs the mechanics feed — and that is a design property you can analyze before launch, not a mystery you discover after it.

This chapter teaches you to tell these two deployments apart on paper, before anyone builds anything.

## Prerequisites

This chapter assumes you can already:

1. **Read a meta-analytic effect size critically** — state what a Hedges' *g* does and does not establish, and ask about heterogeneity before accepting an average (Chapter 1).
2. **Explain autonomy, competence, and relatedness as design requirements**, with one design expression of each, and predict extrinsic-reward decay from design structure (Chapter 4).
3. **Bring your Week 8 prototype** — the gamification decision this week is made about a specific artifact, not in the abstract.

If the phrase "the average conceals the distribution" does not immediately raise your suspicion, reread Chapter 1's effect-size section before continuing.

## Core Content

### The Headline Is the Heterogeneity, Not the Average

**Gamification** — the use of game design elements (points, badges, leaderboards, levels, quests, narratives) in non-game contexts — is the most extensively quantified intervention in learning experience design. The most cited current number comes from a meta-analysis in the *British Journal of Educational Technology*: across 22 experimental studies (n = 3,144), gamification produced a moderately positive effect on academic performance, Hedges' *g* = 0.782 (Zeng et al. 2024).

Read naively, that is a strong endorsement — comfortably above the conventional "moderate" threshold. Now read it the way Chapter 1 trained you to. Two of the twenty-two studies in that same meta-analysis reported *negative* effects: gamified learners did worse than controls. The average is not a guarantee; it is the center of a distribution wide enough to contain harm. [contested — see pantry flag: "gamification works" is flagged in this book's contested-claims register as *heterogeneous*, not settled.]

**Heterogeneity** — the technical term for variation in true effects across studies — is the actual finding here, and it is the finding students most reliably skip. A meta-analytic average tells you what happened across many implementations of many designs in many contexts. It cannot tell you what *your* design will do, because "gamification" is not one treatment. A points-for-completion system and a team-quest system with meaningful choices are as different as two drugs that happen to share a marketing category. Earlier meta-analytic work reached the same structural conclusion: effects exist but vary substantially with design and context, and the field's question has shifted from *whether* gamification works to *which* gamification works, for whom, under what conditions (Sailer & Homner 2020).

The design discipline this imposes is simple to state: **you are not entitled to the average.** You are entitled to the slice of the distribution your design choices put you in. The rest of this chapter is about choosing the slice.

### Reading the Moderators: What Separates the Winners

If the effects vary, the next question is *what they vary with*. Three moderating patterns recur across the recent evidence.

**Implementation quality and creativity matter as much as the mechanics themselves.** A PRISMA-based systematic review concluded that gamification significantly influences motivation and skill development — but that creativity and adaptability in implementation matter as much as the presence or absence of game elements (Jaramillo-Mediavilla et al. 2024). The same badge can be a meaningful competence signal or wallpaper, depending on what it is attached to.

**Need-supportive designs sustain; reward-only designs decay.** Across reviews, gamification designed to satisfy intrinsic psychological needs — autonomy, competence, relatedness — leads to deep, autonomous motivation and long-term retention. Systems relying purely on extrinsic rewards (the points-badges-leaderboards triad, often abbreviated **PBL**) frequently show rapid engagement decline once novelty fades, and can actively undermine intrinsic motivation. This is the moderator that best explains our opening case, and it has independent support: self-determination theory's core claims about need support and motivation quality carry strong meta-analytic backing in education (Wang et al. 2024; Ryan & Deci 2000).

**Gamification raises the ceiling more than the floor.** Recall the longitudinal finding: the largest gain was in *excellence rate* (Lampropoulos & Sidiropoulos 2024). The students who benefited most were those positioned to compete for the top. This is a design warning disguised as a success metric. If your learning goal is to move the struggling majority — which, for most courses, it is — a mechanic that primarily energizes the already-successful may produce impressive aggregate numbers while doing little for the learners you built the redesign for. Cross-reference your Chapter 9 equity audit: any mechanic that publicly ranks learners should be tested against the question *what does this do to the person in the 30th percentile in week six?*

A note of calibration: the ceiling-versus-floor finding comes primarily from one longitudinal research program. Treat it as a strong hypothesis with single-program support, not a law. We flag it accordingly in the Evidence Box.

### The SDT Decomposition: Mechanics as Need-Feeding or Need-Starving

Here is the chapter's core method, and the spine of this week's studio assignment. Take any proposed gamified system. Refuse to evaluate "the gamification." Instead, list every individual mechanic and ask of each: *which psychological need does this feed — autonomy, competence, relatedness — or is it a pure extrinsic reward?* Then ask the darker twin question: *which need might it starve?*

| Mechanic | Can feed... | Can starve... |
|---|---|---|
| Points for completion | Competence (if tied to mastery) | Autonomy (if it converts chosen activity into paid work) |
| Badges | Competence (if criterion-referenced and meaningful) | Nothing much — often just inert |
| Leaderboard | Competence + relatedness (for the top decile) | Competence (for everyone who can now see they are losing) |
| Streaks | Competence (habit feedback) | Autonomy (the streak, not the learning, becomes the boss) |
| Levels / unlockable paths | Competence + autonomy (visible progress, choice of route) | Autonomy (if the path is forced) |
| Team quests | Relatedness + autonomy | Relatedness (if teams are ranked against each other punitively) |
| Narrative / role framing | Autonomy (meaning, purpose) | Attention (if it becomes a seductive detail — Chapter 1) |

Two rows deserve special attention.

**Leaderboards** are the clearest case of a mechanic with opposite effects on different learners. The review literature on leaderboards finds benefits concentrated among high performers and competitive-orientation learners, with discouragement and disengagement risks for those persistently ranked low [verify — leaderboard systematic review, *Journal of Computer Assisted Learning*]. A leaderboard is not a motivation mechanic; it is a motivation *redistribution* mechanic.

**Streaks** deserve a designer's suspicion for a different reason. The persuasion literature — which the consumer app industry reads more carefully than the learning literature — describes **commitment and consistency**: once people take a small public action, they experience internal and social pressure to behave consistently with it (Cialdini 2009). A streak is a commitment device. It reliably produces *behavior*. Whether it produces *learning* depends entirely on what the streak-preserving behavior is. A streak that can be kept alive with a thirty-second token lesson trains exactly that: the thirty-second token lesson. You met this product category in Chapter 1's EVER finding (Hirsh-Pasek et al.) — beloved, habit-forming, minimal learning value. The streak worked. The learning was optional.

The decomposition method's output is a table, and the table is the argument. When you can show a stakeholder that four of the five proposed mechanics are pure extrinsic reward and the fifth starves autonomy, "should we gamify?" stops being a matter of taste.

### Motivational Crowding: The Mechanism Behind the Decay Curve

This is the chapter's deep dive — the mechanism that explains *why* reward-only designs collapse after novelty, rather than merely the observation that they do.

**Motivational crowding** (also called the undermining effect) is the phenomenon in which extrinsic rewards displace, rather than add to, intrinsic motivation. The canonical evidence is a meta-analysis of 128 experiments: tangible rewards that are expected and contingent on doing a task reliably *reduced* subsequent free-choice engagement in that task — people who were paid to do something they previously did for its own sake became less likely to do it once the payment stopped (Deci, Koestner & Ryan 1999).

The mechanism, in plain language: motivation is not a single fuel tank that rewards top up. It is a *quality* dimension as much as a quantity. When a learner practices statistics because the problems are starting to make sense — competence satisfaction — the activity is self-sustaining. When the same learner practices to earn points, the implicit answer to "why am I doing this?" changes. The reward reframes the activity as the kind of thing one does *for rewards*. Remove the reward — or let it become stale, which novelty decay guarantees — and the reframed activity has no remaining reason. The system did not add motivation. It performed a swap: durable, self-generated motivation out; fragile, externally-maintained motivation in.

This produces the characteristic decay curve from the opening case: a spike (novelty plus reward), a plateau (reward maintenance), then a fall *below baseline* (the original intrinsic motivation has been crowded out, and the reward no longer compensates). The below-baseline endpoint is the signature that distinguishes crowding from simple boredom — the system ends up worse than if it had never launched.

Three design corollaries:

1. **Rewards are least dangerous where intrinsic motivation is already near zero.** There is little to crowd out in a mandatory compliance module. This is why gamification findings from low-interest contexts transfer poorly to contexts where learners arrive curious.
2. **Informational rewards behave differently from controlling rewards.** Feedback that says *here is what you can now do* (criterion-referenced badges, mastery progress) supports competence. Rewards experienced as *here is your payment for compliance* control behavior and trigger crowding. The same artifact can be either; the framing and contingency structure decide.
3. **Decay risk must be disclosed at design time.** A mechanic with a predictable six-week half-life is not necessarily wrong — a six-week onboarding course might happily spend it. A two-semester statistics sequence cannot. This is why your Evidence Disclosure this week has a mandatory decay-risk line.

### When the Right Answer Is "No Game"

The decomposition method has three honest outputs, not two: *gamify this way*, *gamify differently than proposed*, and *do not gamify*. The third is underused because it feels like a non-deliverable. It is not. A documented, evidence-cited decision to decline is a portfolio artifact — arguably the strongest one this course produces, because it is the artifact that proves you select for learning rather than engagement.

The "no game" answer is indicated when the decomposition table shows mostly extrinsic-reward rows; when the learner population is far from the leaderboard's top decile; when the content already carries intrinsic interest that crowding would endanger; when the maintenance cost of keeping mechanics fresh exceeds the team's capacity (stale game layers decay fastest); or when a cheaper, better-evidenced intervention serves the same motivational diagnosis. That last clause is the one to internalize: gamification proposals are usually a *symptom report* — learners aren't practicing — and the evidence-disciplined move is to treat the diagnosis, not to accept the prescription that arrived stapled to it. Often the diagnosis is a task-value problem (Chapter 4: task-value beliefs are the strongest predictor of cognitive engagement), and the treatment is making the content's utility visible, which costs nothing and decays slowly.

Declining is not refusing to think about motivation. The motivation design obligation remains. You are declining one family of treatments because the evidence prices it honestly.

## Mid-Chapter Checkpoint

Answer without looking back, then check.

1. A colleague says: "Meta-analysis shows gamification has an effect of g = 0.782, so adding badges to our course is evidence-based." Name the two distinct errors in that sentence.
2. Which mechanic in the decomposition table can feed competence for some learners while starving it for others, simultaneously, in the same deployment?
3. Your gamified pilot shows usage *below* the pre-launch baseline at week twelve. Why does "below baseline" point to motivational crowding rather than ordinary novelty wear-off?
4. Name one situation where the crowding risk of extrinsic rewards is low.

*Redirects:* If you missed (1), reread "The Headline Is the Heterogeneity" — the errors are claiming the average for a specific design, and treating "gamification" as one treatment. If you missed (2), revisit the leaderboard row of the decomposition table. If you missed (3) or (4), reread "Motivational Crowding" — below-baseline means motivation was displaced, not merely bored, and crowding needs intrinsic motivation to displace.

## The Evidence Box

| Study | Design | Finding | What it does *not* establish |
|---|---|---|---|
| Zeng et al. 2024 (*BJET*) | Meta-analysis, 22 experimental studies, n = 3,144 | Gamification → academic performance, Hedges' *g* = 0.782; **2 of 22 studies negative** | That any particular mechanic set works; the average spans designs from PBL overlays to full need-supportive systems |
| Lampropoulos & Sidiropoulos 2024 (*Education Sciences*) | Longitudinal, n = 1,001, 3 years, vs. traditional and online conditions | Gamified condition superior on success rate, average grade, retention; **largest gain in excellence rate** (ceiling > floor) | Generalization beyond its context; the ceiling-vs-floor pattern is effectively single-program — *flagged: single-source until replicated* |
| Jaramillo-Mediavilla et al. 2024 | PRISMA systematic review | Significant influence on motivation and skill development; implementation creativity/adaptability matter as much as element presence | A ranking of which mechanics to use |
| Deci, Koestner & Ryan 1999 | Meta-analysis, 128 experiments | Expected, tangible, contingent rewards undermine subsequent intrinsic motivation (the crowding mechanism) | That all rewards harm — informational feedback does not show the undermining pattern |
| Sailer & Homner 2020 | Meta-analysis (earlier wave) | Positive but heterogeneous effects across cognitive, motivational, behavioral outcomes [verify exact effect sizes before manuscript freeze] | Stability of effects over time |

**Heterogeneity:** the central fact of this literature; high in every meta-analysis above. **Unsettled:** long-term effects beyond single courses (the 3-year study is nearly alone); whether SDT-aligned designs *cause* durability or co-occur with better teaching; equity effects of ranking mechanics; publication bias against null gamification deployments (institutions rarely publish their week-twelve collapses).

## Worked Example: The Gamification Decision Memo for the Statistics Course

*Act Two close. Method applied to the Track A case: the introductory statistics online course you have carried since Week 2.*

**Situation.** The Week 8 prototype redesigned the course's practice segment around retrieval and spaced problem sets. Completion of *optional* practice remains low (38% of enrolled students attempt fewer than half the optional sets). A well-meaning stakeholder — the program director, who has seen a conference demo — proposes a gamification layer: points per completed problem set, achievement badges, a course-wide leaderboard, and a daily practice streak.

**The problem as the designer sees it.** The diagnosis behind the proposal is real: students are not practicing enough. But the proposal is a treatment named before the diagnosis was examined. The designer's actual question: *will any of these four mechanics increase durable practice for the students currently not practicing — the bottom 60%, not the top 10% — without crowding out the fragile intrinsic motivation the Week 8 redesign just started building?*

**Process, including dead ends.** The designer runs the SDT decomposition on all four mechanics. Points-per-set: pure extrinsic, contingent and expected — the exact reward profile in Deci, Koestner & Ryan (1999). Badges: inert unless criterion-referenced; "completed 10 sets" is a counting badge, not a competence badge. Leaderboard: the course's struggling majority is precisely the population the leaderboard evidence warns about; the Week 5 learner research (statistics anxiety appeared in 9 of 12 interviews) makes public ranking close to contraindicated. Streak: would reward daily touches; the practice sets take 25–40 minutes, so the streak-preserving behavior would likely shrink to token engagement.

*Dead end #1:* the designer spends a day trying to "fix" the leaderboard — relative-improvement ranking, opt-in, anonymized. Each fix shrinks the mechanic toward invisibility while keeping its maintenance cost. A mechanic that must be defanged into near-invisibility to be safe is not earning its complexity. *Dead end #2:* the designer drafts a narrative quest frame ("you are a data detective"). It reads as charming for week one and as a seductive detail thereafter; nothing in the learner research suggests the problem is insufficient whimsy.

The designer then re-reads the Week 5 interviews and finds the actual moderator: students skip optional practice because they cannot see what it buys them — a task-value gap, not a reward gap.

**Resolution.** The memo declines the gamification layer. In its place: (1) a *mastery progress map* — a private, criterion-referenced display showing which course skills each student has demonstrated and which the next practice set develops (competence-feeding, informational, no ranking); (2) each optional set opens with one sentence connecting it to the exam and to a named real job task (task-value repair, the strongest-evidence lever from Chapter 4); (3) practice sets remain optional (autonomy preserved). The memo discloses: decay risk of the progress map is judged low because it is informational rather than reward-contingent — *this is an assumption awaiting measurement, and the Week 13 instrumentation plan will test it* (does map usage and practice persistence hold through week twelve?).

**The lesson.** The gamification decision is not made about gamification; it is made about the diagnosis, the population, and the needs each mechanic feeds — and "no game, but here is what instead" is a complete, defensible design output.

**The limit.** This method prices motivation mechanics; it cannot rescue a course whose practice tasks are genuinely not worth doing. If the Week 8 prototype's problem sets were busywork, no motivational framing — gamified or not — should make students do more of them, and the honest move is back to Week 8, not forward to Week 10.

**Track B extension.** Run the identical memo on your own project this week: list every motivation mechanic proposed (or already present), decompose by need served and need starved, check the leaderboard/streak rows against *your* Week 5 learner research, and decide. The bonus requires your Evidence Disclosure to name one decision the evidence constrained (e.g., declining a leaderboard against stakeholder preference) and one it could not settle (e.g., whether your progress display decays — almost nothing in the literature tracks informational mechanics past one semester).

## Exercises

**Exercise 10.1 — Diagnose (Analyze).** Return to the opening case's second deployment (the illustrative collapse). Using the decomposition table, identify which need each of its four mechanics (points, badges, leaderboard, streaks) starved, and write three sentences explaining why satisfaction surveys stayed excellent while usage fell below baseline. (Hint: who answers voluntary surveys at week twelve?)

**Exercise 10.2 — The Decision Memo (Apply/Evaluate — Studio Assignment #5, 25 pts; Track B +5).** Produce the gamification decision memo for your studio project (Track A: the statistics course, extending or contesting the worked example — you may reach a different resolution if you argue it from the same evidence; Track B: your own project). Required structure: diagnosis → decomposition table → decision (design / redesign / decline) → decay-risk disclosure → what measurement would falsify the decision. Maximum two pages.

**Exercise 10.3 — Production (Create).** For whichever decision your memo reached, build the artifact: either a paper prototype of the single mechanic you kept (showing the exact moment a learner encounters it, what it displays, and its contingency structure) or, if you declined, the non-game replacement (e.g., the task-value sentence for three real practice tasks plus a sketch of the competence display). This artifact attaches to Studio Assignment #5.

**Exercise 10.4 — Evidence Brief #4 (30 pts).** One page. Claim under examination: *"Leaderboards increase learner motivation."* Best evidence for, best evidence against, and the design decision you would make under that uncertainty for a learner population of your choosing. Cite at least one meta-analysis and name its heterogeneity.

*Assessment notes:* Studio Assignment #5 is graded primarily on the decomposition's honesty (does the table admit what each mechanic starves?) and the decay-risk disclosure — not on whether you gamified. Declining with evidence scores as highly as designing with evidence. Evidence Brief #4 is graded on calibration, not on verdict.

## Evidence Disclosure (Chapter 10 template)

Complete and attach to Studio Assignment #5:

- **Evidence-grounded:** *I adopted/declined [mechanic] because [meta-analytic finding / moderator evidence], citing [source].*
- **Research-grounded:** *My Week 5 learner research showed [finding], which indicates [need / risk] for this population.*
- **Assumption awaiting measurement:** *I am assuming [e.g., the informational progress display will not decay / the task-value framing transfers to my domain]. The signal that would disconfirm this is [metric + timepoint], and it enters my Week 13 measurement plan.*
- **Decay-risk line (mandatory this chapter):** *The mechanic I kept has an expected decay profile of [estimate + reasoning]; the experience still functions for learning if the mechanic is ignored: [yes/no — if no, redesign].*

## What Would Change My Mind

This chapter's position — decompose by psychological need; treat PBL-only designs as decay-prone; treat "no game" as a first-class answer — would need revision if a preregistered, multi-site experimental literature emerged showing that points-badges-leaderboards systems *without* need-supportive design sustain learning gains (not just usage) beyond two semesters across heterogeneous learner populations, including the bottom quartile. The specific finding to watch for: longitudinal replications of Lampropoulos & Sidiropoulos (2024) that decompose *which mechanics* carried the three-year effect — if the durable component turns out to be the reward layer rather than the need-supportive layer, the SDT-alignment moderator story weakens substantially and this chapter's method overweights it.

## Still Puzzling

- **Where do the failed deployments go?** Institutions abandon collapsed gamification layers quietly. The published base almost certainly under-samples week-twelve failures, which means even the heterogeneous picture may be optimistic. No one has measured the file-drawer.
- **Is the ceiling effect a design property or a population property?** Does gamification help top performers because mechanics target them, or because high prior achievers extract value from *any* added structure?
- **Can informational mechanics decay?** The crowding literature covers rewards; almost nothing tracks whether mastery displays and progress maps lose force over time or remain inert-but-harmless.
- **What is the half-life of "creative implementation"?** If implementation quality is the moderator that matters (Jaramillo-Mediavilla et al. 2024), gamification may be less a design pattern than a continuing staffing cost — which changes the budget conversation entirely.

## Chapter Summary

You can now: read a gamification meta-analysis as a distribution rather than a verdict, and refuse the average on behalf of your specific design; decompose any gamified system into mechanics and classify each by the need it feeds and the need it starves; explain motivational crowding as a mechanism — why reward-only systems land below baseline rather than merely flat; identify the populations (struggling majorities, anxiety-prone learners) for whom ranking mechanics carry contraindications; and produce a gamification decision memo whose "decline" output is as rigorous and portfolio-worthy as its "design" output. Your studio project now carries a motivation decision with a disclosed decay risk — an artifact Week 13 will instrument and Week 15 will defend.

## Key Terms

- **Gamification** — the use of game design elements (points, badges, leaderboards, levels, quests, narrative) in non-game contexts.
- **Heterogeneity** — variation in true effects across studies; the reason a meta-analytic average does not transfer to any particular design.
- **Moderator** — a variable (design type, learner population, implementation quality) that changes the size or direction of an effect.
- **PBL triad** — points, badges, leaderboards; the most common and most decay-prone gamification surface.
- **Motivational crowding (undermining effect)** — the displacement of intrinsic motivation by expected, contingent extrinsic rewards, leaving net motivation lower after reward removal.
- **Informational vs. controlling reward** — feedback that communicates competence versus reward experienced as payment for compliance; only the latter shows the crowding signature.
- **Raises-the-ceiling effect** — the finding that gamification's largest gains concentrate among top performers (excellence rate) rather than struggling learners.
- **Commitment device** — a mechanic (e.g., a streak) that leverages consistency pressure to produce behavior; reliably generates engagement, not necessarily learning.
- **Decay risk** — the predicted loss of a mechanic's motivational force after novelty, required as an explicit disclosure line this week.

## Bridge

Gamification changes the *mechanics* of the experience. The next decision changes its *medium* — should the learning be immersive, embodied, three-dimensional? — and the evidence there contains the course's sharpest counterfinding: the week the impressive medium lost to a tank of water by thirty-one percent.

## Further Reading

- **Zeng, J., et al. (2024). Meta-analysis of gamification and academic performance. *British Journal of Educational Technology*.** The current headline number — read it for the forest plot, not the abstract; the two negative studies are the pedagogy.
- **Lampropoulos, G., & Sidiropoulos, A. (2024). Longitudinal gamification study. *Education Sciences*.** The rare three-year deployment; source of the raises-the-ceiling finding and the strongest durability evidence in the literature.
- **Deci, E. L., Koestner, R., & Ryan, R. M. (1999). A meta-analytic review of experiments examining the effects of extrinsic rewards on intrinsic motivation. *Psychological Bulletin*.** The crowding mechanism's evidentiary anchor; fifty years on, still the paper every reward-based design must answer to.
- **Cialdini, R. B. (2009). *Influence: Science and Practice*.** Not a learning text — which is the point. The commitment/consistency and social-proof machinery your competitors' streaks are built from; read it to recognize persuasion wearing learning's clothes.
- **Sailer, M., & Homner, L. (2020). The gamification of learning: a meta-analysis. *Educational Psychology Review*.** The earlier wave's careful moderator analysis; useful as a heterogeneity baseline against Zeng et al.

## LLM Exercise: The Mechanic Stress-Test

Copy-paste the following into the LLM of your choice, replacing the bracketed material. Note the guardrails: the model generates and critiques; *you* supply the evidence labels and the final judgment, and nothing the model says substitutes for your learner research.

> I am a learning experience design student making a gamification decision. Here is my context: [two sentences: the learning experience, the learner population, the motivation problem your Week 5 research found]. Here is the mechanic I am considering: [one mechanic, described concretely — what the learner sees, when, contingent on what].
>
> Do the following, in order:
> 1. Argue the strongest case that this mechanic will sustain motivation for THIS population, naming which psychological need (autonomy, competence, relatedness) it feeds.
> 2. Argue the strongest case that it will decay or backfire, including the motivational-crowding risk and what it does to learners in the bottom half of the distribution.
> 3. Propose one redesign of the mechanic that shifts it from controlling to informational.
> 4. STOP. Do not tell me whether to adopt it. Instead, list the three pieces of evidence or learner data I would need to decide, phrased as questions I must answer myself.
>
> Do not invent study citations. If you reference research, describe the finding generically and I will verify it against my course's Evidence Box.

**Deliverable:** the transcript, plus a 150-word reflection stating (a) which of the model's arguments survived contact with your actual Week 5 learner data, (b) one claim the model made that you could not verify, and (c) your decision. The reflection — not the transcript — is what gets assessed.
