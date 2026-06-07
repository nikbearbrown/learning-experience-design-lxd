# Chapter 10 — Gamification Under Evidence: Motivation Mechanics That Survive the Meta-Analyses
*Why two deployments with identical feature lists can diverge by three years and an entire distribution.*

Consider two deployments of the same gamified curriculum.

The first is documented. A higher-education course was gamified and tracked longitudinally — 1,001 students across three academic years — against a traditional classroom condition and a plain online condition (Lampropoulos & Sidiropoulos 2024). The gamified condition won on every outcome the study measured: success rate, average grade, retention, and — most strikingly — excellence rate, the proportion of students earning top marks. That last detail matters and we will return to it. The biggest gain was at the top of the distribution. Gamification raised the ceiling more than the floor.

The second deployment is an illustrative composite, assembled from the pattern the extrinsic-reward literature predicts and practitioners repeatedly report (Deci, Koestner & Ryan 1999; Hanus & Fox 2015 [verify]). A different program licenses a similar curriculum and applies the same surface checklist: points, badges, a leaderboard, completion streaks. Usage spikes for six weeks. The launch retrospective declares victory. By week twelve, voluntary practice has fallen below the pre-launch baseline. The students who sit atop the leaderboard keep going; the students in the bottom half, who can now see precisely how far behind they are, quietly stop logging in. Satisfaction surveys stay excellent the entire time — you saw this exact signature in Chapter 4, and now you know to distrust it.

Same curriculum. Same nouns on the feature list. One deployment compounds for three years; one collapses after novelty. If "gamification" were a single treatment, this could not happen. The difference is not the badges. It is which psychological needs the mechanics feed — and that is a design property you can analyze before launch, not a mystery you discover after it.

---

The most cited number in this space comes from a meta-analysis in the *British Journal of Educational Technology*: across 22 experimental studies (n = 3,144), gamification produced a moderately positive effect on academic performance, Hedges' *g* = 0.782 (Zeng et al. 2024). Read naively, that is a strong endorsement, comfortably above the conventional moderate threshold. Read the way Chapter 1 trained you: two of those twenty-two studies reported *negative* effects. Gamified learners did worse than controls. The average is not a guarantee; it is the center of a distribution wide enough to contain harm.

This is the actual finding, and it is the one students most reliably skip. Heterogeneity — the technical term for variation in true effects across studies — means a meta-analytic average tells you what happened across many implementations of many designs in many contexts. It cannot tell you what your design will do, because "gamification" is not one treatment. A points-for-completion system and a team-quest system with meaningful choices are as different as two drugs that happen to share a marketing category. The field's research program has accordingly shifted from asking *whether* gamification works to asking *which gamification works, for whom, under what conditions* (Sailer & Homner 2020). You are not entitled to the average. You are entitled to the slice of the distribution your design choices put you in.

Three moderating patterns recur across the recent evidence and are worth knowing before any mechanic is proposed.

**Implementation quality and creativity matter as much as which elements are present.** A PRISMA-based systematic review concluded that gamification significantly influences motivation and skill development, but that creativity and adaptability in implementation matter as much as the presence or absence of game elements (Jaramillo-Mediavilla et al. 2024). The same badge can be a meaningful competence signal or wallpaper, depending on what it is attached to.

**Need-supportive designs sustain; reward-only designs decay.** Gamification designed to satisfy intrinsic psychological needs — autonomy, competence, relatedness — leads to autonomous motivation and long-term retention. Systems relying purely on extrinsic rewards, the points-badges-leaderboards triad, frequently show rapid engagement decline once novelty fades, and can actively undermine intrinsic motivation. This is the moderator that best explains the opening case, and it has independent support: SDT's core claims about need support and motivation quality carry strong meta-analytic backing in education (Wang et al. 2024; Ryan & Deci 2000).

**The largest gains are at the top of the distribution.** The three-year longitudinal study's most important finding is also its least frequently cited: the biggest gain was in excellence rate. If your learning goal is to move the struggling majority — which for most courses it is — a mechanic that primarily energizes the already-successful may produce impressive aggregate numbers while doing little for the learners you built the redesign for. Any mechanic that publicly ranks learners should be interrogated against a specific question: what does this do to the person in the 30th percentile in week six?

---

Here is the chapter's core method. Take any proposed gamified system. Refuse to evaluate "the gamification." Instead, list every individual mechanic and ask of each: which psychological need does this feed — autonomy, competence, relatedness — or is it a pure extrinsic reward? Then ask the darker twin question: which need might it starve?

<!-- → [TABLE: SDT decomposition of seven common mechanics — columns: Mechanic, Can Feed (with conditions), Can Starve (with conditions), Crowding Risk, Population Warning — rows: points for completion, badges, leaderboard, streaks, levels/unlockable paths, team quests, narrative/role framing — designed to serve as the analytical tool for the studio assignment] -->

Two rows deserve extended attention.

Leaderboards are the clearest case of a mechanic with opposite effects on different learners simultaneously. For the top decile, a leaderboard is a competence signal and a competitive environment — it feeds exactly what they came for. For everyone else, it is a precise, public measure of how far behind they are, updated on every login. The review literature finds benefits concentrated among high performers and competitive-orientation learners, with discouragement and disengagement risks for those persistently ranked low [verify — leaderboard systematic review, *Journal of Computer Assisted Learning*]. A leaderboard is not a motivation mechanic. It is a motivation *redistribution* mechanic. What it adds at the top it may subtract from the bottom, and the aggregate can look positive while the effect on the learners who most needed help is negative.

Streaks deserve a different kind of suspicion. The persuasion literature describes commitment and consistency: once people take a small public action, they experience internal and social pressure to behave consistently with it (Cialdini 2009). A streak is a commitment device. It reliably produces *behavior*. Whether it produces *learning* depends entirely on what the streak-preserving behavior is. A streak that can be kept alive with a thirty-second token lesson trains exactly that: the thirty-second token lesson. You met this product category in Chapter 1's EVER finding — beloved, habit-forming, minimal learning value. The streak worked. The learning was optional.

The decomposition method's output is a table, and the table is the argument. When you can show a stakeholder that four of five proposed mechanics are pure extrinsic reward and the fifth starves autonomy, "should we gamify?" stops being a matter of taste.

---

The decomposition identifies *which* mechanics feed which needs. The mechanism that explains *why* reward-only systems collapse rather than merely plateau is worth understanding directly, because it is the piece practitioners most often miss.

**Motivational crowding** — also called the undermining effect — is the phenomenon in which extrinsic rewards displace rather than add to intrinsic motivation. The canonical evidence is a meta-analysis of 128 experiments: tangible rewards that are expected and contingent on doing a task reliably reduced subsequent free-choice engagement in that task (Deci, Koestner & Ryan 1999). People who were paid to do something they previously did for its own sake became less likely to do it once the payment stopped.

The mechanism in plain language: motivation is not a single fuel tank that rewards top up. It is a quality dimension as much as a quantity. When a learner practices statistics because the problems are starting to make sense — competence satisfaction — the activity is self-sustaining. When the same learner practices to earn points, the implicit answer to "why am I doing this?" changes. The reward reframes the activity as the kind of thing one does *for rewards*. Remove the reward — or let it become stale, which novelty decay guarantees — and the reframed activity has no remaining reason. The system did not add motivation. It performed a swap: durable, self-generated motivation out; fragile, externally-maintained motivation in.

This produces the characteristic decay curve from the opening case: spike (novelty plus reward), plateau (reward maintenance), then fall *below baseline* (original intrinsic motivation crowded out, reward no longer compensating). The below-baseline endpoint is the signature that distinguishes crowding from simple boredom. Boredom returns you to where you started. Crowding leaves you worse off than if the mechanic had never launched.

Three design corollaries follow directly.

Rewards are least dangerous where intrinsic motivation is already near zero — there is little to crowd out in a mandatory compliance module with no prior interest. This is why gamification findings from low-interest contexts transfer poorly to contexts where learners arrive curious.

Informational rewards behave differently from controlling rewards. Feedback that says *here is what you can now do* — criterion-referenced badges, mastery progress displays — supports competence. Rewards experienced as *here is your payment for compliance* control behavior and trigger crowding. The same artifact can be either; the framing and contingency structure decide.

Decay risk must be disclosed at design time. A mechanic with a predictable six-week half-life is not necessarily wrong — a six-week onboarding course might happily spend it. A two-semester statistics sequence cannot.

<!-- → [CHART: Three-curve decay chart — x-axis: weeks post-launch, y-axis: voluntary practice rate — curves: reward-only design (spike, plateau, below-baseline fall), need-supportive design (moderate rise, sustained plateau), no-game control (flat baseline) — annotation showing the crowding zone below the baseline and the divergence point at novelty decay] -->

---

The decomposition method has three honest outputs, not two: gamify this way, gamify differently than proposed, and do not gamify. The third is underused because it feels like a non-deliverable. It is not. A documented, evidence-cited decision to decline is the artifact that proves you select for learning rather than engagement.

The "no game" answer is indicated when the decomposition table shows mostly extrinsic-reward rows; when the learner population is far from the leaderboard's top decile; when the content already carries intrinsic interest that crowding would endanger; when the maintenance cost of keeping mechanics fresh exceeds the team's capacity (stale game layers decay fastest); or when a cheaper, better-evidenced intervention serves the same motivational diagnosis.

That last clause is the one to internalize. Gamification proposals are usually a symptom report — learners are not practicing — and the evidence-disciplined move is to treat the diagnosis rather than to accept the prescription that arrived stapled to it. Often the diagnosis is a task-value gap: learners cannot see what the practice buys them. Making the content's utility visible costs nothing, decays slowly, and has stronger evidence support as a predictor of cognitive engagement quality than any mechanic in the decomposition table (Chapter 4). Declining gamification is not refusing to think about motivation. The motivation design obligation remains. You are declining one family of treatments because the evidence prices it honestly.

---

Translate the framework into the case it was built for.

The introductory statistics course's Week 8 prototype redesigned practice around retrieval and spaced problem sets. Completion of optional practice remains low — 38% of enrolled students attempt fewer than half the optional sets. A well-meaning program director, back from a conference, proposes a gamification layer: points per completed problem set, achievement badges, a course-wide leaderboard, and a daily practice streak.

The diagnosis behind the proposal is real: students are not practicing enough. But the proposal is a treatment named before the diagnosis was examined. The actual question: will any of these four mechanics increase durable practice for the students currently not practicing — the bottom 60%, not the top 10% — without crowding out the fragile intrinsic motivation the Week 8 redesign just started building?

Run the SDT decomposition. Points-per-set: pure extrinsic, contingent and expected — the exact reward profile in Deci, Koestner and Ryan (1999). Badges: inert unless criterion-referenced; "completed 10 sets" is a counting badge, not a competence badge. Leaderboard: the course's struggling majority is precisely the population the leaderboard evidence warns about, and the Week 5 learner research found statistics anxiety in nine of twelve interviews — public ranking is close to contraindicated. Streak: would reward daily touches; the problem sets take 25–40 minutes, so the streak-preserving behavior would likely shrink to token engagement.

Two dead ends are worth naming. Spending a day trying to fix the leaderboard — relative-improvement ranking, opt-in, anonymized — produces a mechanic that must be defanged into near-invisibility to be safe. A mechanic that requires defanging is not earning its complexity. Drafting a narrative quest frame — "you are a data detective" — reads as charming for week one and as a seductive detail thereafter; nothing in the learner research suggests the problem is insufficient whimsy.

Re-reading the Week 5 interviews surfaces the actual moderator: students skip optional practice because they cannot see what it buys them. Task-value gap. Not a reward gap.

The memo declines the gamification layer. In its place: a private, criterion-referenced mastery progress map showing which course skills each student has demonstrated and which the next practice set develops — competence-feeding, informational, no ranking; each optional set opens with one sentence connecting it to the exam and to a named real job task; practice sets remain optional, preserving autonomy. Decay risk of the progress map is judged low because it is informational rather than reward-contingent — *this is an assumption awaiting measurement*. Whether map usage and practice persistence hold through week twelve enters the instrumentation plan.

<!-- → [INFOGRAPHIC: Side-by-side comparison of the original gamification proposal vs. the redesign — left column: PBL triad mechanics with SDT decomposition showing starvation risks annotated in red; right column: mastery map plus task-value framing with need-feeding annotations in green — designed to model the accepted/declined format of the gamification decision memo] -->

The gamification decision is not made about gamification. It is made about the diagnosis, the population, and the needs each mechanic feeds. And "no game, but here is what instead" is a complete, defensible design output — arguably more rigorous than a gamification proposal that does not account for the learners it will leave below baseline.

---

## Exercises

**Warm-up**

1. *(Recall — heterogeneity)* A colleague cites *g* = 0.782 from Zeng et al. (2024) as proof that adding badges to your course is evidence-based. Name the two distinct errors in that sentence, and write the two questions you would ask about the meta-analysis before treating the average as a design warrant.

2. *(Recall — crowding mechanism)* In your own words, without consulting the text: explain why a reward-only gamified system lands *below* its pre-launch baseline at week twelve, rather than simply returning to it. What is the mechanism, and what did the reward swap out?

**Application**

3. *(Apply — SDT decomposition)* Choose any gamified learning product you have used. List every mechanic you can identify. For each, classify the psychological need it feeds (autonomy, competence, or relatedness) or mark it as pure extrinsic reward, and identify any need it starves. Produce the table, then write three sentences: which mechanics carry the most decay risk, which are most worth keeping, and what the decomposition reveals about what the product is actually optimized for.

4. *(Apply — population audit)* Take the leaderboard mechanic from Exercise 3 or from the statistics course case. Predict its effect on three specific learner segments: the top 10% by performance, the middle 50%, and the bottom 40%. Write one sentence per segment, naming the mechanism. Then state the single metric at 90 days that would tell you whether the mechanic helped or hurt the segment that needed the most help.

5. *(Apply — informational vs. controlling)* For a learning product you know, identify one mechanic that is currently functioning as a controlling reward and propose a redesign that makes it informational instead. The redesign must leave the mechanic's surface appearance as close to unchanged as possible — the test is whether the framing and contingency structure, not the visual, is what changes.

**Synthesis**

6. *(Synthesize — the decision memo)* Produce a gamification decision memo for a learning experience you are designing or are familiar with. Required structure: diagnosis (what motivation problem the proposal is trying to solve), SDT decomposition table (every proposed mechanic, need fed, need starved), decision (design as proposed / redesign / decline), and a mandatory decay-risk disclosure (the expected decay profile of any mechanic you kept, and whether the experience still functions for learning if that mechanic is ignored). Maximum two pages.

7. *(Synthesize — ceiling vs. floor)* The three-year longitudinal study found gamification's largest gain in excellence rate — the ceiling, not the floor. Your course serves a population where the majority are in the bottom half of prior performance. Construct the argument for adapting rather than rejecting gamification for this population: which mechanics might move the floor, what design changes the leaderboard evidence would require, and what you would measure to know whether the floor actually moved.

**Challenge**

8. *(Challenge — the missing file drawer)* The published gamification literature almost certainly under-samples week-twelve failures — institutions rarely publish collapsed deployments. Design a study that would estimate publication bias in this literature: what you would measure, how you would find unpublished null and negative results, and how a more complete picture of the distribution would change the advice you would give a stakeholder citing *g* = 0.782 as justification for a new leaderboard.

---

## LLM Exercise

*Guardrails: the model generates and critiques; you supply the evidence labels and the final judgment, and nothing the model says substitutes for your own learner research.*

Copy the following into the LLM of your choice, replacing the bracketed material.

---

I am a learning experience design student making a gamification decision. Here is my context: [two sentences: the learning experience, the learner population, the motivation problem your learner research found]. Here is the mechanic I am considering: [one mechanic, described concretely — what the learner sees, when, contingent on what].

Do the following, in order:
1. Argue the strongest case that this mechanic will sustain motivation for THIS population, naming which psychological need — autonomy, competence, or relatedness — it feeds.
2. Argue the strongest case that it will decay or backfire, including the motivational-crowding risk and what it does to learners in the bottom half of the distribution.
3. Propose one redesign of the mechanic that shifts it from controlling to informational.
4. STOP. Do not tell me whether to adopt it. Instead, list the three pieces of evidence or learner data I would need to decide, phrased as questions I must answer myself.

Do not invent study citations. If you reference research, describe the finding generically and I will verify it against my course's Evidence Box.

---

*Deliverable: the transcript, plus a 150-word reflection stating (a) which of the model's arguments survived contact with your actual learner research, (b) one claim the model made that you could not verify, and (c) your decision. The reflection — not the transcript — is what gets assessed.*
