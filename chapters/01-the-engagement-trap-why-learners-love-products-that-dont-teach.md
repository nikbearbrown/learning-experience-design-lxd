# Chapter 1 — The Engagement Trap: Why Learners Love Products That Don't Teach

## Learning Objectives

By the end of this chapter, you will be able to:

1. **(Understand)** Explain the enjoyable ≠ effective problem using the seductive details and desirable difficulties literatures — including the mechanism by which each one separates what learners *like* from what learners *learn*.
2. **(Apply)** Read a reported effect size (Hedges' *g*) and state what it does and does not establish, including heterogeneity — the variation hiding underneath an average.
3. **(Analyze)** Evaluate one top-rated learning app against evidence-based criteria (the EVER routine) and identify where ratings and learning value diverge.

These objectives apply to both tracks. The studio project does not begin until Chapter 2; this chapter builds the evidence literacy every later week depends on.

## Opening Case: What Did the Five Stars Measure?

*The app described below is an illustrative composite, built from the design patterns of top-grossing language and early-learning apps. The research finding it dramatizes is sourced in the text.*

The app has 4.8 stars and several hundred thousand ratings. The reviews are a wall of gratitude: "My daughter asks to practice every day." "Finally an app that makes learning fun." "I've kept my streak going for 214 days." The home screen is a delight — a chirpy mascot, a progress path winding through pastel islands, confetti when you finish a lesson. Sessions are short and frictionless. Nothing is ever hard for long. When you get something wrong, the app softens the blow, shows you the answer, and moves on. Retention of users is superb. Retention of *content* is not measured anywhere in the product.

A design team at a mid-sized EdTech company has been told to benchmark this app, because their own product's engagement numbers look anemic beside it. The brief from leadership: "Make ours feel like theirs." The team catalogs the mechanics — streaks, chests, mascot, confetti, micro-lessons — and starts a backlog. Nobody in the room asks the question this book exists to ask: *is there any evidence that the app's users are learning anything?*

There is, in fact, evidence on exactly this question, and it is uncomfortable. When Kathy Hirsh-Pasek and colleagues developed evidence-based criteria for what makes an app genuinely educational — active cognitive engagement, meaningful connection to the child's world, social interaction, and a clear learning goal — and research teams then scored the market's most popular "educational" apps against those criteria, most of the top-rated, most-downloaded apps provided minimal learning value, and more than half scored low on basic design quality (Hirsh-Pasek et al. 2015; Meyer et al. 2021 [verify]). The book refers to this as the EVER finding, after the Evidence-based EdTech Evaluation Routine the criteria became [verify]. The market's star ratings and the evidence-based ratings were measuring different things — and they came apart.

So what did the five stars measure? How the experience *felt*: polished, rewarding, frictionless, kind. Real properties, none of them learning — and, this is the harder part, some of them may be purchased *at the cost* of learning. The rest of this chapter is about why that trade exists, how to see it, and what evidence would detect it before you ship.

One more data point, because it sets the stakes for the whole course. In 2025, a randomized controlled trial — an experiment where learners are randomly assigned to conditions so outcome differences can be attributed to the design — found that students given a GPT-based tutor practiced happily with it, then scored roughly 17% *worse* than unassisted peers on a later exam taken without the AI (Bastani et al. 2025). Every individual interaction felt helpful. The aggregate was damage. Chapter 12 lives inside that study. For now it stands as the sharpest current instance of the pattern this chapter teaches you to see: the experience learners prefer and the experience that teaches them are not the same experience, and the market cannot tell them apart.

## Prerequisites

You can already:

- Read critically and write at a bachelor's level — you can follow an argument and notice when a claim outruns its support.
- Navigate digital learning products as a *user* — you have used an LMS, a MOOC, or a Duolingo-class app and have opinions about them.
- Bring one of two professional instincts: a design background (you can critique an interface) or a teaching background (you can critique a lesson). This chapter will deliberately unsettle both.

No statistics background is assumed. Effect-size literacy is taught from zero in this chapter, because it is the one prerequisite the rest of the book cannot run without.

## Core Content

### Engagement Is Multidimensional — and Most of It Is Not Learning

Start with the plain-language version: a learner can click often, stay long, enjoy themselves, and learn nothing. "Engagement" as the industry uses the word is a bundle of different things, and only some of them have anything to do with learning.

The research literature unbundles it. The canonical decomposition (Fredricks, Blumenfeld & Paris 2004) distinguishes **behavioral engagement** (participation, time on task, completion — the things a dashboard counts), **affective engagement** (interest, enjoyment, sense of belonging — the things a survey captures), and **cognitive engagement** (the investment of mental effort in understanding — the thing that actually predicts learning, and the hardest of the three to observe). Online-learning research often adds a fourth, **academic engagement**, for participation tied directly to achievement-bearing tasks [verify]. For the teachers in the room: this maps onto something you already know from your classroom — the difference between a student who is busy and a student who is thinking. For the designers in the room: this is the uncomfortable news that your analytics stack measures the first two dimensions almost exclusively, and the one that matters is the one your clickstream cannot see directly.

The evidence that the dimensions come apart is consistent. Time-on-task and completion correlate with learning weakly and inconsistently across studies; cognitive-engagement measures correlate much more strongly. One frequently cited analysis of online learners found that self-efficacy, task-value beliefs, and self-regulation skills together explained 31% of the variance in engagement, 47% in critical thinking, and 57% in elaboration strategies — with **task-value beliefs** (the learner's perception that the material is relevant and useful to them) emerging as the strongest predictor of the deep-processing behaviors [contested — single-source finding; see pantry flag]. We return to task value in Chapter 4, where it becomes a design requirement. Here the point is narrower: the strongest known predictor of cognitively engaged behavior is a *belief about relevance*, not a streak, a mascot, or a confetti burst.

**Design application.** Whenever someone — a stakeholder, a dashboard, your own gut — says "engagement," your first professional move is to ask *which dimension*. Behavioral engagement is necessary (nobody learns from a product they never open) but it is evidence of exposure, not of learning. The discipline this chapter installs: never accept time-on-task, completion, ratings, or streaks as learning proof unless they are tied to delayed performance or transfer — performance on a later occasion, in a new context, without the supports present during practice.

### Seductive Details: When Interesting Subtracts

Here is the first mechanism that actively pries enjoyment apart from learning. A **seductive detail** is an interesting addition that is not necessary for the learning goal — the dramatic anecdote in the lightning lesson, the cute animation in the fractions app, the trivia sidebar, the mascot's joke. The term comes from the multimedia learning literature, where Richard Mayer and colleagues spent two decades demonstrating a result that still surprises designers: adding interesting-but-irrelevant material frequently *reduces* learning of the target content (Mayer 2021). A meta-analysis — a study that statistically combines the results of many individual studies — by Rey (2012) synthesized dozens of experiments and found a reliable negative effect of seductive details on both retention and transfer.

Why would interesting hurt? Three candidate mechanisms recur in the literature. **Distraction**: the detail captures attention the target content needed — working memory, the mental workspace where learning happens, is brutally limited (Chapter 3 makes this precise). **Disruption**: the detail breaks the coherence of the explanation, so the learner builds a fragmented mental model. **Diversion**: the detail activates the wrong prior knowledge, so the learner organizes the material around the anecdote instead of the principle. The evidence does not yet cleanly distinguish the three; what it establishes is the direction of the effect and its design implication.

**Design application: relevance discipline.** Every delightful element must earn its place by supporting the target cognitive processing — attention, effort, and feedback on the right thing. This is *not* an argument for joyless design. Delight aimed at the learning target (a beautiful visualization of the concept itself, a narrative that *is* the worked example) is not a seductive detail; it is good design. The test is functional alignment, not fun. Designers from consumer UX will find this constraint genuinely foreign: in most product design, delight is nearly free. In learning design, misplaced delight has a measurable cost, and the learner pays it — later, invisibly, on a test you never see.

### Desirable Difficulties: When Feeling Worse Works Better

The second mechanism runs the other direction: not only can pleasant features subtract from learning, but some *unpleasant* features add to it. Robert Bjork named these **desirable difficulties** — conditions of practice that make learning feel slower and harder in the moment while measurably improving long-term retention and transfer (Bjork 1994; Bjork & Bjork 2011).

The big three, each with a deep experimental literature behind it:

- **Spacing.** Distributing practice over time beats massing it into one session, for retention measured later — one of the most robust findings in experimental psychology, replicated across hundreds of studies and synthesized meta-analytically (Cepeda et al. 2006). Cramming feels productive and tests poorly.
- **Retrieval practice.** Testing yourself — pulling the answer out of memory — beats restudying the material, even when the restudy condition feels far more effective to the learner (Roediger & Karpicke 2006). In a striking demonstration, retrieval practice outperformed elaborate concept-mapping study on a delayed test, while learners predicted the opposite (Karpicke & Blunt 2011).
- **Interleaving.** Mixing problem types during practice beats blocking them by type, particularly for learning to *discriminate* which method a problem calls for (Rohrer & Taylor 2007) — and it reliably feels more confusing while it works.

The deep reason these results are possible is a distinction this whole book rests on: **learning versus performance** (Soderstrom & Bjork 2015). Performance is what you can observe during practice — current, situation-supported accuracy. Learning is the relatively permanent change that shows up later, somewhere else. The two dissociate in both directions: conditions that inflate practice performance (massing, blocking, immediate hints) can depress learning, and conditions that depress practice performance can enhance it. Learners' own judgments track performance, not learning — which is why the sincere five-star rating is structurally unreliable as learning evidence. They are not lying. They are reporting a feeling that does not measure what they think it measures.

A warning Chapter 3 expands: *desirable* is a conditional, not a slogan. The same friction can be a desirable difficulty for a knowledgeable learner and a design flaw for a novice; difficulty is desirable only when the learner can succeed at the harder processing it induces. "It's hard, therefore it's working" is as much an engagement-trap fallacy as "they love it, therefore it's working."

**Design application.** The features that the evidence most strongly recommends — spaced schedules, retrieval before review, mixed practice — are precisely the features your engagement metrics will punish and your co-design participants (Chapter 7) will vote to remove. An evidence-disciplined designer therefore needs two things this chapter cannot fully supply yet: measurement that captures delayed retention rather than in-session performance (Chapter 13), and motivation design that helps learners tolerate productive struggle (Chapter 4).

### Reading an Effect Size Without Being Fooled by It

Everything above leaned on phrases like "reliable negative effect" and "robust finding." This section gives you the tool to interrogate such phrases yourself, because for the next fourteen weeks — and the rest of your career — vendors, papers, and your own teammates will hand you numbers dressed as verdicts.

An **effect size** is a standardized measure of how big a difference is. The one you will meet most often, **Hedges' *g***, expresses the difference between two group means in units of standard deviation — roughly, how spread out scores typically are — with a correction that keeps small samples from exaggerating. A *g* of 0.5 means the average learner in the treatment group scored half a standard deviation above the average control learner. By a common (and commonly abused) convention, 0.2 is called small, 0.5 medium, 0.8 large; John Hattie's *Visible Learning* synthesis popularized 0.4 as a benchmark "hinge point" for educational interventions, a heuristic that has been both influential and heavily criticized (Hattie 2009).

What an effect size establishes: the average magnitude and direction of a difference, in the studied populations, under the studied conditions, on the studied measures. What it does not establish: that *your* product, with *your* learners, on *your* outcome, will see that effect — or any effect.

The single most important word for reading meta-analyses is **heterogeneity**: the degree to which the individual studies disagree with each other. An average can be moderately positive while concealing studies that found nothing and studies that found harm. The book's standing example, which Chapter 10 treats in full: the Zeng et al. (2024) meta-analysis of gamification reports a moderately positive average effect on academic performance (Hedges' *g* = 0.782 across 22 experimental studies) — *and* two of those 22 studies found negative effects. "Gamification works, *g* = 0.782" and "gamification harmed learning in some studies" are both accurate sentences about the same meta-analysis. A designer who can only repeat the first sentence is a liability.

Three more habits of effect-size hygiene, on loan from the statistical-literacy tradition (Spiegelhalter 2019; Bergstrom & West 2020):

1. **Ask what was measured, and when.** An effect on an immediate quiz is a performance effect; only a delayed or transfer measure speaks to learning. Most EdTech evidence uses immediate measures.
2. **Ask what the comparison was.** "Better than nothing" and "better than a well-taught lesson" are different claims with different effect sizes.
3. **Beware quantitative bullshit.** Numbers can launder weak claims — "clinically important effect size" attached to a non-significant result is a real rhetorical move documented in the wild (Bergstrom & West 2020). The polish of a statistic is not evidence of its strength.

**Design application.** Every Evidence Brief in this course (the first is due this week) uses this skill: a design-relevant claim, the best evidence for it *with effect sizes and their limits*, the best evidence against it, and the decision you would make under that uncertainty. Calibrated uncertainty — "the evidence supports X on immediate measures, is silent on retention, and is heterogeneous across contexts" — is the registered voice of this profession, and it is learnable.

### Why the Market Selects for Engagement

Last mechanism, and it is economic rather than cognitive. None of the above would matter much if the market rewarded learning. It does not, and the reasons are structural.

Consider what each actor in the EdTech market can observe. The *learner* observes how the experience feels — and feelings track performance and pleasantness, not learning. The *buyer* (a parent, an L&D department, a school) observes ratings, dashboards, and the learner's enthusiasm — engagement proxies all the way down. The *app store* observes ratings and downloads; the *investor*, retention curves and revenue. Learning — delayed, transfer-tested, counterfactual — is observable to almost no one, because measuring it requires comparison groups and delayed assessment that no actor in the chain is paid to run. The EVER finding (Hirsh-Pasek et al. 2015; Meyer et al. 2021 [verify]) is exactly what this incentive structure predicts: products optimized for the observable signals, drifting freely on the unobservable one.

This is a selection effect, not a conspiracy. Teams A/B test toward metrics they can see; features that lengthen sessions survive, features that improve three-month retention of content are invisible to the test and die unbuilt. Over enough iterations the market produces beautifully engaging products *whether or not* anyone intended to neglect learning — the way click-driven media produces clickbait without any journalist setting out to write it (Bergstrom & West 2020). And note the trap's second jaw: when effective design genuinely feels worse in the moment, the market does not merely fail to select for learning — it selects *against* some of the designs that teach best.

**Design application.** This is why the book's thesis is a professional obligation rather than an observation: *every learning experience design decision is an empirical claim*, and the designer is frequently the only actor in the system with both the means and the mandate to check it. When you cannot check it — often — the obligation shrinks to honesty: saying which decisions are evidence-grounded and which are assumptions awaiting measurement. That practice has a name in this course, the Evidence Disclosure, and you will perform it in every studio assignment from Week 5 on.

## Mid-Chapter Checkpoint

*Ungraded. Answer before reading on.*

A learning app's dashboard shows: average session length up 22%, 30-day user retention up 9%, lesson completion up 14%, and in-lesson quiz accuracy up 11% after a redesign. A colleague says, "Whatever we changed, learners are learning more." Name the strongest objection to that inference, using the learning/performance distinction.

*If you answered* "the metrics might be wrong" or "correlation isn't causation," *you are circling but not landing — the metrics may be perfectly accurate and causally produced by the redesign. Revisit the Desirable Difficulties section:* all four metrics are in-session behavioral or performance measures; learning is change that persists and transfers, and none of these metrics observes a delayed or transfer outcome. In fact, if the redesign smoothed away retrieval difficulty, in-lesson accuracy could rise *because* durable learning fell.

## The Evidence Box

*The current-state evidence for this chapter's claims. Conventions used throughout the book: effect sizes are Hedges' g unless noted; "delayed" means assessment after a retention interval; single-source findings are flagged.*

| Finding | Source | Direction & size | Heterogeneity / limits |
|---|---|---|---|
| Most top-rated educational apps provide minimal learning value by evidence-based criteria; >50% score low on design quality (the EVER finding) | Hirsh-Pasek et al. 2015; Meyer et al. 2021 [verify] | Descriptive market audit, not an effect size | Children's app market; criteria derived from learning science, applied by raters; generalization to adult products is plausible but untested |
| Seductive details reduce retention and transfer | Rey 2012 (meta-analysis); Mayer 2021 | Negative, small-to-moderate on both outcomes | Effects vary with detail type, placement, and learner prior knowledge; boundary conditions still being mapped |
| Spacing beats massing for delayed retention | Cepeda et al. 2006 (meta-analysis) | Positive, robust | Optimal gap depends on retention interval — a design-relevant moderator |
| Retrieval practice beats restudy; learners predict the reverse | Roediger & Karpicke 2006; Karpicke & Blunt 2011 | Positive, moderate-to-large on delayed tests | Strongest for fact/concept retention; transfer effects positive but smaller; feedback quality matters |
| Interleaving beats blocking for discrimination learning | Rohrer & Taylor 2007 | Positive on delayed tests; practice performance *lower* during interleaving | Domain-dependent; clearest in category and problem-type learning |
| Learning and performance dissociate; learner judgments track performance | Soderstrom & Bjork 2015 (review) | Framework-level synthesis | The book's load-bearing distinction; broad experimental support |
| Gamification: average positive effect concealing negative-effect studies | Zeng et al. 2024 (meta-analysis, 22 studies, n=3,144) | g = 0.782 average; 2/22 studies negative | High heterogeneity — the Chapter 10 case study in reading past an average |
| GPT tutor access → 17% worse on subsequent unassisted exam | Bastani et al. 2025 (RCT) | Negative | One large RCT in one context (secondary mathematics [verify]); the field's cautionary benchmark, treated fully in Chapter 12 |
| Task-value beliefs strongest predictor of cognitive engagement (31%/47%/57% variance pattern) | See pantry synthesis [contested — single-source finding; see pantry flag] | Positive, correlational | One study, self-report measures, no causal design; do not build on it alone |

**What remains unsettled:** whether the enjoyable ≠ effective gap can be closed by measurement (cognitive-engagement instrumentation is promising but unstandardized — Chapters 13–14); the precise mechanism of seductive-detail harm; how desirable-difficulty effects scale outside laboratory and classroom studies into commercial products, where the evidence is thinnest exactly where the products are biggest.

## Worked Example: Diagnosing the Five-Star App

*Act One worked examples are diagnostic: one case, walked from symptom to verdict. This case is an illustrative composite (a vocabulary-learning app of the Duolingo class); the evaluation criteria and findings cited are sourced.*

**Situation.** Lena is three months into her first LXD job. Her company's compliance-adjacent language product has flat engagement, and she has been asked to "benchmark" the category leader — the five-star app from this chapter's opening — and recommend features to copy.

**The problem as the designer sees it.** Initially: an engagement gap. The leader's sessions are shorter, more frequent, more rewarded; hers are longer, rarer, plainer. The obvious move is feature transplantation — streaks, chests, mascot.

**Process, including the dead ends.** Lena starts with the backlog-of-features approach and hits the first dead end two weeks in: she cannot rank the features, because she has no model of what any of them *does* beyond "users seem to like it." Copying without a mechanism is cargo-culting. She finds the evidence-based app-evaluation work (Hirsh-Pasek et al. 2015) and rebuilds the benchmark as a two-column audit: for each prominent feature of the leader, (1) which engagement dimension does it serve, and (2) what does the learning evidence say about its likely effect on retention?

The audit reorganizes everything. Streaks, chests, confetti: behavioral/affective; no retention mechanism; documented decay risk (Chapter 4). The mascot's jokes between items: affective; candidate seductive detail. Short frictionless lessons with immediate answer reveal: the painful row — the app *removes retrieval effort* precisely where the testing-effect literature says effort should be induced. Second dead end: Lena tries to confirm her audit against the leader's outcomes and discovers there is nothing to find — no delayed-retention data exists publicly, for the leader or for her own product. She has been benchmarking against a product whose learning effectiveness is unknown, as far as anyone can tell, *to its own makers*.

**Resolution.** Lena's recommendation memo does three things. It reframes the gap: "They beat us on behavioral and affective engagement; on learning effectiveness, neither product has evidence." It splits the backlog: adopt the leader's onboarding clarity and session structure (engagement features with no learning cost), decline the answer-reveal pattern (directly contradicted by retrieval-practice evidence), and pilot a spaced-review feature *with a delayed vocabulary test* as the success metric, not session length. And it attaches the course's signature artifact, an Evidence Disclosure: which recommendations rest on evidence (retrieval, spacing), which on learner research (none yet — flagged), and which on assumptions awaiting measurement (that users will tolerate the harder review loop — the Chapter 4 problem).

**The lesson.** Benchmarking engagement without an evidence audit copies the market's selection bias straight into your backlog.

**The limit.** This diagnostic approach tells you what the evidence *recommends against* and *recommends for* on average; it cannot tell you what will happen in your product with your learners. Lena's memo earns its credibility precisely by saying so — the pilot with a delayed test, not the audit, is what settles the local question. Where no pilot is possible, the method degrades gracefully into honest labeling, never into certainty.

## Exercises

**1. The dimension sort (Understand).** Take any learning product you use. List ten observable features or metrics it surfaces. Classify each by the engagement dimension it serves or measures — behavioral, affective, cognitive, academic — and mark which, if any, would count as learning evidence under the learning/performance distinction. One paragraph: what does the product's *measurement* design reveal about what it is optimized for?

**2. The five-star autopsy (Analyze — produce something).** Choose one top-rated learning app (4.5+ stars, large install base). Produce a one-page evaluation against the four evidence-based criteria from the EVER tradition: active cognitive engagement, meaningful connection, social interaction, clear learning goal (Hirsh-Pasek et al. 2015). For each criterion: pass/partial/fail, with one concrete observation from the app as your warrant. Conclude with the divergence statement: the two places where the app's market rating and its evidence-based rating come apart most sharply, and your best account of *why* the market rewards each one.

**3. Reading past the average (Apply).** A vendor's deck cites "g = 0.782 (Zeng et al. 2024)" as proof that gamifying your onboarding course will work. Write the four questions you would ask before accepting the inference, each tied to a concept from this chapter (heterogeneity, outcome timing, comparison condition, population match). Then write the two-sentence response you would give the vendor in a meeting — professional, specific, non-dismissive.

**Assessment note.** *Evidence Brief #1 (30 pts) is due this week — the first of five.* One page: one design-relevant claim about a real product (Exercise 2 is a natural source), the best evidence for it, the best evidence against it, and the design decision you would make under that uncertainty. The rubric rewards calibrated language; "the evidence does not settle this, and here is what I would do anyway, and why" is a scoring answer, not a hedge.

## Evidence Disclosure

*Every chapter in this book practices what it grades. One design decision in this chapter the evidence constrained; one it could not settle.*

**Constrained:** This chapter teaches effect-size literacy *before* any design method, and the sequencing was not a stylistic choice. The desirable-difficulties and seductive-details literatures establish that designer and learner intuition reliably mispredict learning outcomes (Soderstrom & Bjork 2015; Karpicke & Blunt 2011); a course that taught design methods first would spend Act Two installing intuitions that Act Three would have to repair.

**Could not settle:** Whether opening with a failure case (the five-star app that doesn't teach) produces better learning of this chapter's concepts than opening with a success case. The failure-first choice rests on the diagnostic-reasoning rationale in the book's case strategy and on the authors' teaching experience — an assumption awaiting measurement, which is exactly what your instructor's course evaluations cannot detect either. Note the recursion, and get used to it.

## What Would Change My Mind

The central claim of this chapter — that engagement evidence and learning evidence are separable, and that the market's rating signals carry little information about learning — would require revision if a large, preregistered study found that app-store ratings or standard behavioral-engagement metrics *predicted delayed, transfer-tested learning outcomes* across products at a useful effect size, after controlling for content coverage and study time. That is a fully runnable study. If five-star products teach reliably better than three-star products on delayed measures, the engagement trap is a smaller problem than this book claims, and the profession owes the market an apology. No such finding currently exists [verify — recheck before each edition; this is the claim most exposed to new evidence].

## Still Puzzling

- **Where does delight stop being seductive?** The functional-alignment test is clean in principle and blurry at the margins — is a beautiful progress animation aligned with motivation (legitimate) or stealing attention (seductive)? The literature does not yet carve this joint.
- **Can a mass-market product survive desirable difficulty?** The evidence says spacing and retrieval work; the market data says friction kills retention curves. Whether any business model can hold both truths at scale is an open question this book raises in Week 1 and cannot fully close by Week 15.
- **Is the learner's pleasure worth something on its own?** This chapter prices enjoyment only as a means or an obstacle to learning. A defensible view holds that learner wellbeing is a legitimate end. How to weigh it against effectiveness when they conflict is a values question the evidence cannot answer — though the evidence can at least make the conflict visible.

## Chapter Summary

You can now do four things you could not reliably do a week ago. Decompose "engagement" into behavioral, affective, cognitive, and academic dimensions and say which a given metric measures. Name and explain the two mechanisms that pry enjoyment apart from learning — seductive details (pleasant additions that subtract) and desirable difficulties (unpleasant additions that add) — and the learning/performance distinction underneath both. Read a Hedges' *g* and interrogate it: outcome timing, comparison condition, heterogeneity, population. And run a first evidence audit on a real product, separating what its ratings measure from what its learners learn. What you cannot yet do: explain *why* working memory makes seductive details costly (Chapter 3), design motivation that survives the removal of confetti (Chapter 4), or measure any of this in a live product (Chapter 13). Those are owed, not skipped.

## Key Terms

- **Behavioral engagement** — observable participation: time on task, clicks, completion. Necessary for learning; not evidence of it.
- **Cognitive engagement** — invested mental effort in understanding; the engagement dimension that predicts learning and the hardest to measure.
- **Task-value beliefs** — a learner's perception that material is relevant and useful to them; a strong (currently single-source-quantified) predictor of deep engagement.
- **Seductive detail** — an interesting addition irrelevant to the learning goal that measurably reduces retention and transfer.
- **Desirable difficulty** — a practice condition (spacing, retrieval, interleaving, generation) that feels harder and slows current performance while improving long-term retention and transfer.
- **Learning vs. performance** — the dissociation between durable, transferable change (learning) and current, supported accuracy (performance); learner self-judgments track performance.
- **Effect size (Hedges' *g*)** — a standardized magnitude of difference between groups, in standard-deviation units, corrected for small samples.
- **Heterogeneity** — the degree to which studies in a meta-analysis disagree; the reason an average effect is the beginning of reading, not the end.
- **Meta-analysis** — a study that statistically combines many studies; powerful, and only as good as the studies and the reader's attention to heterogeneity.
- **Transfer** — applying learning in a context different from the one practiced; with delayed retention, the gold-standard learning evidence.

## Bridge

If the market's most loved products don't teach — and the incentive structure ensures the market can't notice — then everything depends on the discipline whose job is to prevent this. That discipline calls itself Learning Experience Design. What exactly is it, what does it borrow from the older fields it grew out of, what does it uniquely optimize for — and is it actually a discipline yet, or a rebranding with better typography? Chapter 2 takes the question seriously, including the unflattering answer.

## Further Reading

- **Brown, P., Roediger, H., & McDaniel, M., *Make It Stick* (2014)** — the most readable account of desirable difficulties and the learning/performance distinction; the science half of this book's parentage.
- **Soderstrom, N. & Bjork, R., "Learning Versus Performance: An Integrative Review," *Perspectives on Psychological Science* (2015)** — the scholarly statement of this chapter's load-bearing distinction.
- **Rey, G. D., "A review of research and a meta-analysis of the seductive detail effect," *Educational Research Review* (2012)** — the quantitative case that interesting can subtract.
- **Spiegelhalter, D., *The Art of Statistics* (2019)** — effect sizes, framing, and the habit of asking what a number actually measured; the gentlest serious statistics book in print.
- **Bergstrom, C. & West, J., *Calling Bullshit* (2020)** — a field guide to quantitative rhetoric, directly transferable to vendor decks and conference keynotes.

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
