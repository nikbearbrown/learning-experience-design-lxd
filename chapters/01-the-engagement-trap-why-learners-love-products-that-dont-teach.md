# Chapter 1 — The Engagement Trap: Why Learners Love Products That Don't Teach
*What the five-star rating actually measured — and why it isn't what you think.*

There is a learning app with a 4.8-star rating and several hundred thousand reviews. The reviews say things like "My daughter asks to practice every day" and "Finally an app that makes learning fun" and "I've kept my streak going for 214 days." The home screen has a chirpy mascot, a progress path through pastel islands, confetti when you finish a lesson. Sessions are short and frictionless. When you get something wrong, the app softens the blow, shows you the answer, and moves on. Retention of users is excellent. Retention of *content* is not measured anywhere in the product.

A design team somewhere is benchmarking this app because their own engagement numbers look anemic beside it. The brief from leadership: make ours feel like theirs. The team catalogs the mechanics — the streaks, the treasure chests, the mascot, the confetti, the micro-lessons — and starts a backlog. Nobody in the room asks the question that this book exists to ask: is there any evidence that the app's users are learning anything?

There is, in fact, evidence. And it is uncomfortable.

When researchers developed evidence-based criteria for what makes an app genuinely educational — active cognitive engagement, meaningful connection to the learner's world, social interaction, a clear learning goal — and then scored the market's most popular "educational" apps against those criteria, most of the top-rated, most-downloaded apps provided minimal learning value, and more than half scored low on basic design quality (Hirsh-Pasek et al. 2015; Meyer et al. 2021 [verify]). The market's star ratings and the evidence-based ratings were measuring different things, and they came apart. The five stars measured how the experience *felt*: polished, rewarding, frictionless, kind. Real properties, all of them. None of them learning.

That would be merely interesting if it were just a gap — pleasant on one axis, neutral on the other. The harder part is that some of the pleasant features are purchased *at the cost* of learning. The app that softens the blow and reveals the answer immediately has just removed exactly the cognitive effort that would have consolidated the memory. The mascot's joke between items sounds harmless; it is a candidate seductive detail, stealing the working-memory bandwidth that the explanation needed. The short, frictionless session feels productive; it may be the enemy of the spacing schedule that actually creates durable knowledge.

None of this is visible in the rating. None of it is visible in the dashboard. The people who built the app may not know it. The learners who love the app certainly don't — they are reporting a feeling, and the feeling is accurate. It just doesn't measure what they think it measures.

---

Here is the distinction the entire book rests on, stated plainly before any apparatus is added to it: **learning is not the same thing as performance**.

Performance is what you can observe during practice — current, situation-supported accuracy. Learning is the relatively permanent change that shows up later, somewhere else. The two dissociate in both directions. Conditions that inflate performance during practice can depress learning afterward. Conditions that depress performance during practice can improve learning. This is not a theoretical possibility — it is one of the most robustly replicated findings in cognitive psychology, documented across hundreds of experiments over more than a century (Soderstrom & Bjork 2015).

The reason it matters so much for this book is that learners' own judgments about whether something is working track performance, not learning. When studying feels effective, it correlates with in-session fluency — and in-session fluency is precisely what desirable difficulty suppresses while it works. So learners who are getting the most out of a spaced retrieval practice routine feel like they are struggling and not retaining. Learners who are getting the least out of massed review and instant-answer reveals feel confident and successful. The five-star rating is structurally set up to reward the second experience over the first.

This is not a story about users being fooled. It is a story about what ratings can and cannot observe.

---

The research literature on engagement is more useful when it is broken into its actual components. The canonical decomposition distinguishes behavioral engagement — participation, time on task, completion, the things a dashboard counts — from affective engagement — interest, enjoyment, belonging, the things a survey captures — from cognitive engagement — the investment of mental effort in understanding, the thing that actually predicts learning, and the hardest of the three to observe (Fredricks, Blumenfeld & Paris 2004). A fourth dimension, academic engagement, covers participation directly tied to achievement-bearing tasks.

For teachers, this maps onto something already legible from the classroom: the difference between a student who is busy and a student who is thinking. For designers, it is the uncomfortable news that your analytics stack measures the first two dimensions almost exclusively. The clickstream cannot see cognitive engagement. Your session-length chart cannot see it. Your completion rate cannot see it.

The features that drive behavioral and affective engagement — streaks, rewards, short frictionless sessions, social pressure, progress bars, immediate positive feedback — are well understood. They work. They reliably increase time-on-task, completion, and user satisfaction. The problem is not that they fail at what they do. The problem is that what they do is not learning.

<!-- → [TABLE: Three-column comparison of behavioral, affective, and cognitive engagement — column headers: Engagement Type, What It Measures, What It Does Not Establish — rows with specific examples from app mechanics (streaks → behavioral, confetti → affective, retrieval effort → cognitive)] -->

And some of what they do actively competes with learning. This is the part that requires more care to explain, because the mechanism is not obvious.

---

A seductive detail is an interesting addition that is not necessary for the learning goal. The dramatic anecdote in the lightning lesson. The cute animation in the fractions app. The trivia sidebar. The mascot's joke between items. The term comes from the multimedia learning literature, where Richard Mayer and colleagues spent two decades demonstrating a result that still surprises designers: adding interesting-but-irrelevant material frequently reduces learning of the target content (Mayer 2021). A meta-analysis by Rey (2012) synthesized dozens of experiments and found a reliable negative effect of seductive details on both retention and transfer.

Why would interesting hurt? Three candidate mechanisms recur. Distraction: the detail captures attention the target content needed. Disruption: the detail breaks the coherence of the explanation, leaving the learner with a fragmented mental model. Diversion: the detail activates the wrong prior knowledge, so the learner organizes the material around the anecdote instead of the principle. The evidence does not yet cleanly distinguish the three. What it establishes is the direction of the effect: interesting, when misaligned with the learning target, costs something.

The design implication is a relevance discipline that runs against most product-design instincts. In consumer UX, delight is nearly free — a smooth animation, a pleasant sound, a witty microcopy moment. In learning design, misplaced delight has a measurable cost, and the learner pays it later, invisibly, on a test the designer never sees.

Delight aimed at the learning target itself — a beautiful visualization of the concept, a narrative that *is* the worked example — is not a seductive detail. It is good design. The question is always functional alignment: is this element directing attention and cognitive effort toward the thing the learner is supposed to be processing, or is it borrowing that attention for something else?

---

Now run the mechanism in reverse, because there is a symmetric problem on the other side of the enjoyment/learning gap, and it is equally counterintuitive.

Robert Bjork named these desirable difficulties — conditions of practice that make learning feel slower and harder in the moment while measurably improving long-term retention and transfer (Bjork 1994; Bjork & Bjork 2011). The word *desirable* is doing a lot of work in that phrase, and it only holds under specific conditions, which is something to come back to. But the basic finding is this: some of what works for learning feels bad.

Spacing: distributing practice over time, rather than massing it into one session, produces reliably better retention when measured later — one of the most robust findings in experimental psychology, replicated across hundreds of studies (Cepeda et al. 2006). Cramming feels productive and tests poorly. Retrieval practice: testing yourself — pulling the answer out of memory rather than reading it again — beats restudy, even when the restudy condition feels far more effective to the learner (Roediger & Karpicke 2006). In a striking demonstration, retrieval practice outperformed elaborate concept-mapping study on a delayed test, while learners predicted the opposite (Karpicke & Blunt 2011). Interleaving: mixing problem types during practice, rather than blocking by type, improves the ability to discriminate which method a problem calls for — and it reliably feels more confusing while it works (Rohrer & Taylor 2007).

The features that the evidence most strongly recommends are precisely the features that engagement metrics punish. A spaced-review schedule means the app surfaces old material when the learner wanted to move forward — friction. Retrieval before reveal means the learner has to struggle before getting the answer — friction. Interleaved practice means the session feels disorganized and harder — friction. In an A/B test optimizing for session length or completion, all three of these evidence-backed designs are likely to lose.

<!-- → [CHART: Two-line chart showing in-session performance vs. delayed retention across massed and spaced practice conditions — x-axis: time, y-axis: accuracy — lines cross to show the desirable difficulty effect visually] -->

This is where the market's selection mechanism closes the trap. Nobody at the company set out to build a product that doesn't teach. The team ran the tests they could run, optimized for the metrics they could see, and shipped what survived. Over enough iterations, the market produces beautifully engaging products whether or not anyone intended to neglect learning — the way click-driven media produces clickbait without any journalist intending to write it. The incentive structure selects for the observable signals, and learning is the signal almost no one in the chain is paid to observe.

---

The evidence behind these claims comes in a form worth understanding directly — because for the rest of this book, and the rest of your career, vendors, papers, and colleagues will hand you numbers dressed as verdicts.

An effect size is a standardized measure of how big a difference is. The one you will meet most often, Hedges' *g*, expresses the difference between two group means in units of standard deviation — roughly, how spread out scores typically are — with a correction that keeps small samples from exaggerating results. A *g* of 0.5 means the average person in the treatment group scored half a standard deviation above the average control person. By a conventional (and often abused) heuristic, 0.2 is small, 0.5 medium, 0.8 large.

What an effect size establishes: the average magnitude and direction of a difference, in the studied populations, under the studied conditions, on the studied measures. What it does not establish: that your product, with your learners, on your outcome, will see that effect — or any effect.

The single most important word for reading meta-analyses — studies that statistically combine many individual studies — is **heterogeneity**: the degree to which those individual studies disagree with each other. An average can be moderately positive while concealing studies that found nothing and studies that found harm. The Zeng et al. (2024) meta-analysis of gamification reports a moderately positive average effect on academic performance (*g* = 0.782 across 22 experimental studies) — *and* two of those 22 studies found negative effects. "Gamification works, *g* = 0.782" and "gamification harmed learning in some studies" are both accurate descriptions of the same meta-analysis. A designer who can only repeat the first sentence is a liability.

Three more habits of effect-size hygiene, from the statistical-literacy literature (Spiegelhalter 2019; Bergstrom & West 2020): ask what was measured and *when* — an effect on an immediate quiz is a performance effect, not a learning effect; ask what the comparison was — "better than nothing" and "better than a well-taught lesson" are different claims with different effect sizes; and be skeptical of numbers that launder weak claims — the polish of a statistic is not evidence of its strength.

<!-- → [TABLE: Evidence summary for Chapter 1's core claims — columns: Finding, Source, Direction and Size, Key Limits — rows: EVER finding, seductive details, spacing, retrieval practice, interleaving, gamification heterogeneity, Bastani AI tutor finding] -->

There is one more data point worth placing here precisely because it is recent and sharp. In 2025, a randomized controlled trial — an experiment where learners are randomly assigned to conditions so outcome differences can be attributed to the intervention — found that students given access to a GPT-based tutor practiced happily with it, then scored roughly 17% worse than unassisted peers on a subsequent exam taken without AI assistance (Bastani et al. 2025). Every individual interaction felt helpful. The aggregate was damage. That is not a reason to dismiss AI tutoring; it is a reason to understand what the AI was doing to the cognitive processing that the exam later required. The chapter that treats this study in full comes later. Here it stands as the sharpest current instance of the pattern this chapter has been describing: the experience learners prefer and the experience that teaches them are not the same experience, and the market cannot tell them apart.

---

The warning that closes this chapter is about the word *desirable* in desirable difficulties, because it is easy to read the preceding argument in a direction that causes its own kind of damage.

*Desirable* is a conditional, not a slogan. The same difficulty that enhances learning in a knowledgeable learner can be a design flaw for a novice. Spacing works when the learner has something in memory to space; introducing it before initial acquisition just produces confusion without consolidation. Retrieval practice requires that the learner can *attempt* retrieval — a complete blank is not a retrieval effort, it is a signal of encoding failure. Interleaving requires enough mastery of individual types that mixing them is the challenge. "It's hard, therefore it's working" is as much an engagement-trap fallacy as "they love it, therefore it's working." The mechanisms are real; applying them requires knowing where the learner actually is, not just knowing that difficulty is sometimes good.

That condition — knowing where the learner actually is — turns out to be the hard problem. The engagement signals tell you where the learner is emotionally and behaviorally. The cognitive-engagement signal, the one that actually predicts learning, is the one almost nobody has figured out how to measure at scale. The instruments exist in the research literature; they are unstandardized and labor-intensive; they have not crossed over into commercial product design in any reliable way. That gap is where much of what follows in this book lives.

For now, the thing to sit with is simpler: that the five stars measured something real, the experience was genuinely pleasant, and pleasant and effective are different axes. A learning product can score high on both. It can score high on one and low on the other. The market, as currently constituted, selects primarily on one axis and is largely blind to the other. A designer who knows this is working with a different instrument than one who doesn't. That is what this chapter was for.

---

## Exercises

**Warm-up**

1. *(Recall — engagement dimensions)* A learning app tracks these metrics: daily active users, average session length, lesson completion rate, in-session quiz accuracy, and Net Promoter Score. For each metric, name which engagement dimension — behavioral, affective, or cognitive — it most directly measures, and explain in one sentence why it is or is not evidence of learning.

2. *(Recall — learning vs. performance)* Define the learning/performance distinction in your own words without using the source text. Then give one concrete example, drawn from your own experience as a learner, of a time when your in-session performance and your later retention came apart in either direction.

**Application**

3. *(Apply — seductive details)* You are designing a module on electrical safety for new technicians. Your content team proposes opening each lesson with a dramatized account of a real workplace accident involving the concept being taught. Apply the seductive details framework: under what conditions would this be a seductive detail, and under what conditions would it be functional delight? What specific design decisions would determine which it becomes?

4. *(Apply — effect size reading)* A vendor's sales deck includes this sentence: "Independent research shows our platform improves learning outcomes with an effect size of *g* = 0.61." Write four questions you would need answered before treating that number as evidence. For each question, name the concept from this chapter it is testing (outcome timing, comparison condition, heterogeneity, or population match).

5. *(Apply — market selection)* Explain, in three to four sentences, why a company could iterate through fifty A/B tests and consistently ship decisions that reduce long-term learning — without anyone on the team intending to, and without the data ever showing it. Use the learning/performance distinction and at least one other concept from this chapter.

**Synthesis**

6. *(Synthesize — EVER evaluation)* Choose one learning app with at least 4.5 stars and a large install base. Evaluate it against the four EVER criteria: active cognitive engagement, meaningful connection to the learner's world, social interaction, and clear learning goal (Hirsh-Pasek et al. 2015). Rate each criterion pass/partial/fail with one concrete observation from the app as your warrant. Then write a two-sentence divergence statement: where does the market rating and the evidence-based rating come apart most sharply, and what does that gap reveal about what the market is selecting for?

7. *(Synthesize — desirable difficulty design)* A colleague proposes removing the "reveal answer" button from your app's flashcard feature and replacing it with forced retrieval — the learner must type a response before seeing the answer. Leadership objects that this will hurt engagement scores. Construct the argument for the change, citing the relevant evidence with effect sizes and their limits, and then honestly describe the conditions under which the colleague's proposal would fail — where forced retrieval is not a desirable difficulty but a design flaw.

**Challenge**

8. *(Challenge — heterogeneity)* The Zeng et al. (2024) meta-analysis reports *g* = 0.782 for gamification's effect on academic performance, but two of twenty-two studies found negative effects. You are advising a team about to gamify an onboarding course for a population and context quite different from the meta-analysis sample. Write the two-paragraph briefing you would give — one paragraph on what the evidence supports, one paragraph on what it cannot tell you — that would let the team make a genuinely informed decision rather than a number-laundered one.

---

## LLM Exercise

*Goal: produce a graded artifact — an effect-size interrogation memo — while practicing the productive-struggle guardrail this book applies to all AI use: the model may challenge and extend your reasoning; it may not replace your first attempt.*

Copy everything between the lines into an LLM, filling in the bracketed sections **before** you paste. If you have not written your own answers in steps 1–2, the exercise is void — that is the point.

---

I am a graduate student learning to read educational effect sizes critically. I have evaluated a claim myself, and I want you to stress-test my reasoning — not replace it.

THE CLAIM: [paste a real quantitative claim from an EdTech product page, press release, or paper — include the number and its source]

MY OWN ANALYSIS (written before this conversation):
1. What I think the number actually measured (outcome, timing, comparison group): [your answer]
2. What I think it does NOT establish, and the heterogeneity/population questions I would ask: [your answer]

YOUR TASK, under these rules:
- First, identify the single weakest point in MY analysis and press me on it with one question. Wait for my reply before continuing.
- After my reply, list any standard effect-size questions I missed (outcome timing, comparison condition, heterogeneity, measure validity, population match) — but for each one, ask it as a question I must answer rather than answering it yourself.
- Do not tell me whether the claim is true. Do not generate a verdict for me.
- End by asking me to write the final two-sentence judgment myself, including one thing the evidence cannot settle.

After the conversation, I will submit: the original claim, my pre-conversation analysis, the transcript, and my final judgment paragraph.

---

*Assessable artifact: the four-part package above. Rubric weight falls on the pre-conversation analysis and the final judgment — the transcript is checked only for whether you let the model do your thinking.*
