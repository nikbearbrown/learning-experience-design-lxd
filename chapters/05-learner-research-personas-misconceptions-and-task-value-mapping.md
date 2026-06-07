# Chapter 5 — Learner Research: Personas, Misconceptions, and Task-Value Mapping

**Week 5 · Act Two — Build · Studio Assignment #1**

---

## Learning Objectives

By the end of this chapter you will be able to:

1. **(Apply)** Conduct and document learner research using interviews and empathy mapping with 3–5 real learners.
2. **(Analyze)** Extract prior misconceptions — what learners think they know that is wrong — as design inputs, not just knowledge gaps.
3. **(Create)** Produce evidence-based learner personas that encode prior knowledge, misconception, motivation type, and task-value perception (not demographics and stock photos).
4. **(Evaluate / Track B)** Assess which of your project's current design assumptions survive contact with real learners.

*Track note: Act Two begins here, and so does the studio split. Track A students apply this week's method to the instructor's case — the introductory statistics online course — using the provided learner data and interview transcripts. Track B students run the method on their own project with 3–5 real learners. Objectives 1–3 are common; Objective 4 is graded at full depth for Track B (your assumptions are the ones at risk) and in modified form for Track A (you assess the statistics course's stated design assumptions against the provided data).*

---

## Opening Case: Two Brendas

*Illustrative case, built from the standard pattern in persona practice; the persona texts are invented for teaching.*

A workplace-skills platform is preparing to redesign its data-literacy course, and two documents about the same target learner are circulating in the same week.

The first comes from the marketing team, beautifully art-directed. **"Busy Brenda, 34"** smiles from a stock photo beside a tidy grid of attributes: mid-level operations manager, suburban, two kids, podcasts on her commute, "values efficiency and work-life balance," prefers mobile, "wants bite-sized learning that fits her busy life." Designers love it. It is, in the precise sense this course cares about, almost perfectly useless for learning design — and worse than useless, because it *feels* like knowledge. Nothing in it predicts what Brenda will do when she meets a confidence interval.

The second document comes from a learning researcher who spent four hours interviewing five actual operations managers enrolled in the current course. No photo. It says things like: *Holds a coherent wrong model of averages — believes an average is a "typical case" and is robust, so a department mean from six data points feels as trustworthy as one from six hundred. Took one statistics course nine years ago; remembers procedures, not meaning. Motivation is identified-regulation: she wants the analyst on her team to stop being able to end arguments she can't evaluate. Utility value is high but invisible to her in the current course — she described Module 3 as "math I'll never use," yet her own weekly dashboard depends on exactly that math. Cost sensitivity: interruptions every 8–10 minutes at work; evening study competes with childcare; she abandons anything that punishes a three-day gap.*

Six months later the redesigned course launches, and the week-three assessment produces a familiar disaster: learners compute means and standard deviations correctly but make confidently wrong decisions in every scenario question involving sample size. The marketing persona could not have predicted this — nothing about podcasts and busyness touches it. The research persona predicted it almost verbatim: the "averages are robust" model, surfacing exactly where wrong model and assessment collide.

Only one of these documents is a research artifact. The other is demographic decoration. This chapter teaches you to produce the first kind — and to recognize how much of what you currently believe about your own learners is the second.

---

## Prerequisites

Before this chapter you should be able to:

- **Run the motivation diagnostics of Chapter 4:** classify motivational appeals (external / internalized / intrinsic) and audit for task value — this week you will *measure* these in real people rather than infer them from designs.
- **Distinguish a knowledge gap from a desirable difficulty from a design flaw** (Chapter 3) — because misconceptions are a fourth thing, and you need the other three stable to see it.
- **Have your studio project selected** (Week 2 gate). Track B: confirmed access to 3–5 real learners this week. Track A: download the statistics-course learner data package from the course site.

---

## Core Content

### 5.1 Learner Research Is Not Market Research

Market research asks: *who will choose this product, and why?* Learner research asks: *what is in this person's head, and what will happen when our design meets it?* The two overlap in method — both interview, both segment — and differ totally in what counts as a finding. "Prefers mobile" is a market finding. "Believes a p-value is the probability the hypothesis is true" is a learning finding. The first shapes packaging; the second predicts failure at a specific moment in your course.

The distinction matters because LXD inherited the persona from UX, and UX inherited it from market segmentation, and at each inheritance the artifact kept its *format* while losing its *function*. Research on how LX designers make decisions finds practitioners consistently want better access to learner prior knowledge and learner data — and consistently lack it (Schmidt et al.; see also the activity-theoretic persona work in LXD, which argues personas should capture the learner's goals, tools, and context of activity rather than traits [verify — confirm author/year before citation freeze]). The function this chapter restores: **a learner research artifact exists to predict design failure before the design exists.**

Four properties make research learning-relevant, and they become the four sections of everything you produce this week:

1. **Prior knowledge** — what the learner can actually do now (not what their transcript implies).
2. **Misconceptions** — the *wrong models* they hold, which are not absences of knowledge but presences of something else (Section 5.3).
3. **Motivation type** — which needs and regulations are actually in play (Chapter 4's vocabulary, now measured).
4. **Task-value perception** — whether the learner can currently see utility, identity relevance, interest; and what the experience *costs* them.

**Design application.** Before any interview, write down your design's current assumptions in these four categories. You almost certainly have assumptions in all four — every design does, usually inherited and unexamined. The week's real deliverable is finding out which survive contact.

### 5.2 The Learner Interview: Small Numbers, Honest Inference

The reflexive objection to this week's method: "five learners isn't a sample." Correct — and the objection misunderstands what the measurement is for. Hubbard's framing is the right discipline: a measurement is any observation that *reduces uncertainty*, and the first few observations of a genuinely unexamined variable carry the most information per unit effort (Hubbard 2014). If you know nothing about what your learners wrongly believe, the difference between zero interviews and five is enormous; the difference between five and fifty is much smaller, and you will get the fifty later, cheaply, from instrumentation (Chapter 13). Qualitative research at n = 3–5 cannot estimate *prevalence* ("40% of learners hold this misconception") — never report it as if it could. It is excellent at establishing *existence* ("this misconception exists in this population, here is its structure, and here is where it bites").

Craft notes, hard-won and evidence-adjacent:

- **Interview around artifacts and episodes, not opinions.** "Walk me through the last time you used a spreadsheet to decide something" beats "do you feel confident with data?" Self-assessed confidence is among the least trustworthy signals in learning research — learners systematically misjudge their own knowledge, and fluent experiences inflate the misjudgment (the machinery that made Chapter 1's satisfaction ratings worthless as learning evidence).
- **Ask for predictions and explanations, not reports.** "What do you think would happen if…" exposes the model in the learner's head; "do you know about sampling?" exposes only their vocabulary (McTighe & Silver 2020 make the same move pedagogically — prediction and hypothesis tasks surface misconceptions that recall tasks hide).
- **Separate what they say from what they do.** Give a small authentic task during the interview and watch. Five minutes of observed behavior routinely contradicts thirty minutes of self-report.
- **Record and quote; do not paraphrase from memory.** Personas need verbatim evidence. Paraphrase is where wishful thinking enters.

**Ethics is not a footnote:** real learners are giving you data about their own ignorance — the most face-threatening data there is. Anonymize by default, get explicit consent for recording, and never let an excerpt become traceable in critique. (Programs with IRB requirements: confirm coverage with your instructor before recruiting.)

### 5.3 The Misconception Interview: Wrong Models Are Things, Not Holes

The deepest idea this week, and the one that most separates learner research from generic user research: **a misconception is not a missing piece of knowledge. It is a present, coherent, usually hard-won wrong model that actively generates wrong answers** — and it will survive your instruction unless the design engages it directly. Decades of conceptual-change research support this: naive models are stable, self-consistent, and resistant to mere exposition; instruction that ignores them produces students who pass procedural tests while the wrong model sits intact underneath, waiting for a transfer question.

Statistics — our Track A domain — is the best-documented territory for this phenomenon, which is exactly why the instructor chose it. The classics:

- **The law of small numbers:** people believe small samples should resemble the population in detail — so a department average of six observations feels as reliable as one of six hundred (Tversky & Kahneman 1971). This is not innumeracy; it is a coherent (wrong) theory of sampling.
- **The meaning-free p-value:** learners who can execute a hypothesis test flawlessly will tell you the p-value is "the probability the null hypothesis is true" or that significance means *importance* (Spiegelhalter 2019 devotes careful pages to how natural this misreading is; the CAOS instrument documents its prevalence among students who passed statistics courses — delMas et al. 2007).
- **Averages as typical and robust:** the mean is read as "the normal case," outlier-immune, and meaningful without spread — which makes every later concept (variance, sampling distributions, regression to the mean) land on hostile ground.

The interview technique that surfaces wrong models is the **predict–explain–confront** structure:

1. **Predict:** give a concrete scenario and ask for a prediction. *"A hospital records the days when more than 60% of births are boys. Would you expect more such days at a small hospital or a large one?"* (The canonical Kahneman–Tversky item; the wrong model says "same.")
2. **Explain:** whatever they answer, ask *why* — the model lives in the explanation, not the answer. A correct answer with a wrong explanation is a misconception with good camouflage.
3. **Confront (gently):** present a result that contradicts their prediction and ask them to make sense of it. How a learner repairs a contradiction tells you whether the wrong model is shallow (they update) or load-bearing (they explain the evidence away — and they will, fascinatingly, and you must not argue; you are researching, not teaching).

**Design application.** Each documented misconception becomes a *design input* with a location: the wrong model, the journey moment where it will collide with content (mapped formally next week), and the design implication — which is almost never "explain harder." The conceptual-change evidence favors designs that elicit the prediction *first* and make the confrontation an experience rather than a paragraph. A misconception your research has documented is a designable event; one it hasn't is a week-three assessment disaster.

### 5.4 Empathy Mapping and Motivation Typing: Structuring What You Heard

Raw interviews rot into anecdotes unless structured fast. Two complementary structures:

**The empathy map** — adapted from design practice and widely used in teaching-development contexts (the University of Waterloo's instructional resources offer learner-specific templates) — organizes one learner's data into quadrants: *says* (verbatim quotes), *thinks* (inferences you can defend), *does* (observed behavior, including behavior that contradicts the saying), *feels* (affect, named or displayed). Two amendments make the generic tool learning-relevant: a **knows/wrongly-knows** lane (prior knowledge and misconceptions, kept separate) and a **values/costs** lane (task-value perception and the real costs the learner pays). Be honest about its evidence status: empathy mapping is a practitioner sense-making method with essentially no direct learning-outcome evidence — it earns its place by forcing the says/does separation and by making thin spots visible (an empty *does* quadrant means you interviewed opinions). Scaffolding for inference, not a finding.

**Motivation typing** applies Chapter 4 as a coding scheme. For each learner: which regulation style dominates their account of why they're here (external — "my manager requires it"; identified — "I need this to stop being snowed by the analyst"; intrinsic — rare, treasure it)? Which SDT needs does their current experience feed or starve, *in their own telling*? And the task-value map: utility, attainment, interest — each scored *visible to this learner* or *invisible*, with the evidence — plus cost, in their actual units (interrupted attention, evening hours, the face-threat of being seen struggling).

### 5.5 Personas That Encode Evidence — and the AI Shortcut That Doesn't

A **learner persona** is a composite character that compresses your research into a usable design tool. The format earns its keep only under discipline:

- **Every load-bearing attribute traces to evidence.** A defensible persona footnotes its claims to interview moments: *"believes averages are robust (P2, P4; prediction task 3)."* An attribute with no source is decoration or projection — cut it or label it ASSUMED.
- **The four learning-relevant categories are mandatory:** prior knowledge, misconception(s) with their structure, motivation type, task-value perception including cost. Demographics enter *only* where they carry design weight (time poverty, device access, language).
- **A persona is a prediction machine.** The test: a designer who has never met your learners should be able to read it and predict where this learner struggles, disengages, or fails — and be right. The two-Brendas case is this test run on both artifacts.
- **Two or three personas, not six.** Each should represent a genuinely different *design problem* (different misconception structure, different motivation type), not a different demographic. If two personas predict the same failures, merge them.

**Now the shortcut.** It is 2026; you can paste a course description into an LLM and receive, in seconds, three articulate personas with names, goals, frustrations, even plausible-sounding misconceptions. The field genuinely uses this for early-cycle drafting, so this book will not pretend otherwise. Here is the discipline: **an AI-generated persona is a hypothesis document, never a research artifact.** The generator produces the *centroid of the literature* — the misconceptions common in published accounts of learners in general. What it cannot produce is the *situated* finding: that *your* learners hold a specific variant for a specific reason ("our operations managers trust small samples *because their dashboards refresh weekly and have never visibly burned them*"), or the verbatim quote that wins the design argument, or the discovery that surprises you — and the surprising finding is the one that changes the design. The generated persona is fluent, confident, and sourced to nothing: possibly true, evidentially empty. Legitimate uses: drafting interview protocols, generating candidate misconceptions to *probe for* (the interview then confirms or kills them), and stress-testing your real personas for gaps. The illegitimate use is the obvious one, and the Evidence Disclosure on Studio Assignment #1 requires you to state your learner-data source — "generated" is an automatic fail of the research-grounded label.

---

## Mid-Chapter Checkpoint

*Ungraded. Answer before reading on.*

A teammate reports from an interview: *"P3 has a knowledge gap around sampling — she didn't know what a sampling distribution is."* Based on Section 5.3, what crucial thing has this report possibly gotten wrong, and what follow-up would you send the teammate back to do?

*If you said: the report treats a possible misconception as a mere absence — P3 may hold an active wrong model (e.g., "samples resemble the population regardless of size") that the question never probed, and the follow-up is a predict–explain task rather than a definition check — you have the chapter's core distinction. If "gap" and "misconception" still feel interchangeable, reread Section 5.3 before the worked example, because the worked example turns entirely on that difference.*

---

## The Evidence Box

**What the evidence supports, how strongly, and what remains unsettled.**

| Claim | Key evidence | Direction & strength | Unsettled |
|---|---|---|---|
| Learners hold stable, coherent misconceptions that survive instruction unless directly engaged | Conceptual-change literature across science/statistics education; the CAOS instrument (delMas et al. 2007); Tversky & Kahneman (1971) | Strong, replicated across domains; among the most secure findings this book uses | Best *remediation* designs still contested; "elicit-confront" beats exposition, but durability varies by domain and depth of model |
| Task-value perception predicts quality of engagement | Expectancy-value program (Eccles & Wigfield 2002); the variance findings carried from Chapter 4 | Direction well-supported | [verify — the 31/47/57 figures remain single-source; see Chapter 4 Evidence Box] |
| Personas improve design outcomes | Practitioner consensus; LXD decision-making studies (Schmidt et al.) | **Honest status: thin.** A communication and compression tool; direct evidence that persona use improves *learning outcomes* is scarce to nonexistent | Whether the format adds value beyond the underlying research is essentially unstudied |
| Empathy mapping improves research quality | Teaching-practice literature (Waterloo CTE, Northwestern UDL resources) | Practitioner method; no direct outcome evidence — flagged as such | Treat as scaffolding, not finding |
| AI-generated personas can substitute for learner contact | Field practice 2024–2026; AI co-design literature | **Against substitution:** generated personas reproduce literature-typical learners and miss situated misconceptions; no study shows them predicting local design failure | Rapidly aging area [contested — see pantry flag]; AI for protocol drafting and hypothesis generation is plausible but not causally evidenced |

**Reading note:** notice the asymmetry. The *content* of this week's research (misconceptions, task value) rests on strong evidence; the *artifacts* (personas, empathy maps) rest on practitioner consensus. That is not a reason to skip the artifacts — it is a reason to keep the evidence in the research and treat the artifact as packaging. When the persona and the transcripts disagree, the transcripts win.

---

## Worked Example: Researching the Learners of the Track A Statistics Course

**Situation.** The instructor's continuing case: *DataWise 101*, an introductory statistics online course required across several professional master's programs. Eight self-paced modules; video lectures, auto-graded problem sets, a proctored final. Known symptoms (mapped properly next week): ~55% completion, a dropout concentration near week three, and an instructor observation that students "pass the procedures and fail the meaning." Provided to Track A: enrollment analytics, the course shell, and five anonymized learner-interview transcripts with task-based segments.

**The problem as the designer sees it.** The course team's standing diagnosis, recorded in their redesign brief: "students are underprepared and time-poor; we need more review content and shorter videos." Note the shape of this claim — it is a *learner-deficit* hypothesis ("they lack things") with a *content* remedy ("add material"). Both halves are assumptions. Nobody had asked what students *wrongly possess*.

**Process — including the dead ends.**

*Dead end 1: the survey.* The team's first instinct (and probably yours) was a questionnaire: prior coursework, confidence ratings, study hours. It went out to 240 students, got an 18% response, and returned exactly what self-report returns: most respondents "somewhat agree" they are comfortable with basic statistics. Useless twice over — selection bias in who answered, and confidence is not knowledge (Section 5.2). The survey measured the wrong construct cheaply. Kept only as a recruiting funnel for interviews.

*Dead end 2: the AI persona draft.* A team member prompted an LLM with the course description and got three polished personas, including "Returning Professional Raj" who "struggles with mathematical notation." Plausible — and, against the transcripts, wrong in the way that matters: the real interviewed students were mostly *fine* with notation. Their problem was meaning, not symbols. The generated misconceptions were textbook-generic ("confuses correlation and causation" — present, but not what was breaking week three). The draft was kept for one legitimate purpose: its candidate misconceptions became probes in the interview protocol, where most of them died.

*The interviews.* Five students, 45 minutes each: an episode walk-through ("the last assignment you abandoned — open it; walk me through what happened"), then predict–explain tasks built on the course's own week-three content. The hospital-births item went to all five. Four answered "same at both hospitals," and — the research finding of the week — their *explanations* shared a structure: *averages are stable properties; sample size affects effort, not trustworthiness.* One student, confronted with a contradicting simulation, explained it away as "a weird random thing" — the law of small numbers defending itself in real time (Tversky & Kahneman 1971 predicted that conversation fifty years ago). Separately, three of five could execute a full hypothesis test *while* describing the p-value as "the chance you're wrong," and two described the entire course as "math for the final" — utility value invisible — despite each independently telling a work story (a dashboard, a vendor report, an A/B test) where exactly this content decides something they cared about. Motivation typing: one external ("required"), three identified ("I'm tired of nodding along in data meetings"), one intrinsic outlier.

**Resolution.** The research compresses into two personas and a finding sheet. **"Procedural Priya":** can compute anything in the course; holds the stable-averages model and the meaning-free p-value; identified regulation; utility value high in life, invisible in course; cost profile — evening study, abandons after unexplained failure. **"Compliance Carlos":** external regulation, minimal prior knowledge, few active misconceptions; at risk from cost, not confusion. Each attribute footnoted to transcript moments. The team's original brief is then assessed against the research: "underprepared" — *fails* for four of five (they are *mis*-prepared; more review content would feed the wrong model more procedure); "time-poor" — *survives*. One design assumption overruled, one confirmed: that is Objective 4 in practice.

**The lesson (one sentence).** Five structured interviews replaced a deficit hypothesis with a misconception map — changing the redesign target from *more content* to *engineered collisions with two specific wrong models* — which no survey, no analytics dashboard, and no generated persona could have produced.

**The limit.** Existence, not prevalence: five interviews establish that the stable-averages model is real, structured, and active in this population — not whether it afflicts 40% or 90% of the 240, which matters for how much redesign budget it deserves. That estimate needs instrumentation (Chapter 13 builds a detector for exactly this misconception from item-response patterns). And interview research over-samples the articulate and the willing: the students who most need the redesign may be the ones who didn't answer the recruiting email. Carry both limits into your Evidence Disclosure rather than rounding them away.

### Track B Extension: Running This on Your Own Project

You are doing the same five moves on your project this week, with the constraint that you must recruit 3–5 *real* members of your learner population (not classmates role-playing them — the misconceptions you'd harvest from role-play are your own).

1. **Write your assumptions first.** Before any contact: your project's current beliefs about prior knowledge, misconceptions, motivation type, and task value — one page, dated. This is the document the research will judge; submitting it unedited alongside your findings is what makes Objective 4 gradeable.
2. **Build the protocol:** one episode walk-through anchored on a real artifact; two or three predict–explain tasks built *from your project's actual content* where you suspect trouble; the confront move prepared for your highest-stakes suspected misconception. Use an LLM to red-team the protocol (see the LLM Exercise) — not to write it.
3. **Interview 3–5 learners**, recorded with consent, with at least one observed task each.
4. **Structure:** one empathy map per learner, both added lanes; motivation typing with quotes.
5. **Compress:** 2–3 personas, every load-bearing attribute footnoted; finding sheet; assumptions page marked *survived / overruled / untested*.

**Common Track B failure modes,** in descending frequency: interviewing opinions instead of episodes; asking "do you understand X?" instead of predict–explain; recruiting only your most engaged learners (sample the strugglers or say plainly that you couldn't); personas whose attributes trace to nothing. The Track B bonus (+5) requires your Evidence Disclosure to name one design decision your research constrained and one it could not settle — if your research constrained nothing, that is diagnostic too, and worth saying out loud in studio.

---

## Exercises

**Assessment note (per the course assessment structure):** this week is **Studio Assignment #1 — 25 points base, +5 Track B bonus (25/30)**. Exercise 5.3 *is* the studio assignment; 5.1 and 5.2 are formative and feed it.

**Exercise 5.1 (Analyze — the persona autopsy).** Take the "Busy Brenda" marketing persona from the opening case (full text on the course site). For each attribute, classify it: *learning-relevant as stated / learning-relevant if reframed (state the reframe) / decoration.* Then write the three predict–explain interview questions you would need to convert Brenda from decoration into evidence. Half page plus the questions.

**Exercise 5.2 (Apply — protocol draft).** Draft your full interview protocol for Studio Assignment #1: episode walk-through prompt, 2–3 predict–explain tasks built on your actual course content (Track A: weeks 2–4 of the statistics course), one confront move, and your consent script. *Bring this to studio before running any interview — protocol critique happens in section, and the LLM Exercise below is designed to run on this draft.*

**Exercise 5.3 (Create / Evaluate — Studio Assignment #1, 25/30 points; production).** Conduct the learner research and submit: (a) your pre-research assumptions page, dated before first contact; (b) 3–5 empathy maps with the two added lanes; (c) 2–3 evidence-based personas, every load-bearing attribute footnoted; (d) a misconception finding sheet — each wrong model with its structure, supporting quotes, and the journey moment where you predict it bites; (e) the assumptions page marked *survived / overruled / untested*; (f) Evidence Disclosure (template below). Track A works from the provided transcripts and data package, plus optionally one supplementary interview with a current or former statistics student for full marks on (d). Track B: own learners, own project, bonus eligible.

---

## Evidence Disclosure

*Template for Studio Assignment #1 — and this chapter's own disclosure as a model:*

- **One decision the evidence constrained:** in the worked example, the conceptual-change and statistics-misconception literature (delMas et al. 2007; Tversky & Kahneman 1971), combined with four-of-five interview replication, overruled the team's "add review content" plan — exposition aimed at a deficit cannot dislodge an active model, so the redesign target became elicit-and-confront events at the documented collision points.
- **One decision the evidence could not settle:** how much redesign budget the stable-averages misconception deserves relative to the cost/time findings — because n = 5 establishes existence, not prevalence. That allocation is an assumption awaiting measurement, flagged for the Chapter 13 instrumentation plan.
- *(Your version must state, additionally: your learner-data source — recruited population, n, and selection bias you can name. "AI-generated" is not a learner-data source.)*

---

## What Would Change My Mind

This chapter's load-bearing claim is that situated learner research — small-n interviews with predict–explain structure — produces design-critical findings that AI-generated personas and surveys cannot. The finding that would force a rewrite: a credible, replicated study showing that LLM-generated personas, given only course materials and population descriptors, predict the *specific, local* misconceptions and failure points of real cohorts as accurately as interview-based research — validated against actual assessment and dropout data, not expert ratings of plausibility. If generated personas hit the situated findings, the economics of this chapter invert: interviews become the validation step rather than the discovery step, and Section 5.5's division of labor is rewritten in AI's favor. As of this writing, no such validation exists; the claim is rechecked before each course offering because it is exactly the kind the current decade could falsify.

---

## Still Puzzling

1. **The persona format question.** The research inside personas is evidence-based; the format is folklore. Does compressing findings into characters improve design decisions over a plain finding sheet — or does the character invite exactly the projection it was meant to prevent? Essentially unstudied.
2. **Prevalence on a budget.** Between n = 5 interviews and full instrumentation lies a gap: is there a cheap, valid mid-scale method (two-tier diagnostic items? concept inventories in onboarding?) for estimating misconception prevalence before committing redesign budget?
3. **Researching the unreachable.** The learners who ignore recruiting emails are plausibly those with the highest cost profiles and the most design-relevant struggles. What does honest learner research look like for the population that won't talk to you?
4. **Misconceptions about learning itself.** Learners hold wrong models of *how they learn* (massed practice feels better; fluency feels like mastery — Chapter 3). Should personas encode these meta-level misconceptions as a standard lane? This book suspects yes, and knows of no direct evidence either way.

---

## Chapter Summary

You can now run the first method of Act Two end to end: state your design's assumptions in the four learning-relevant categories before researching; conduct small-n interviews that trade opinions for episodes, predictions, and explanations; surface misconceptions as structured wrong models using predict–explain–confront; organize evidence with learning-amended empathy maps; type motivation with Chapter 4's constructs as a coding scheme; compress it into personas whose every load-bearing attribute is footnoted to evidence; use AI for protocol drafting and hypothesis generation without letting it counterfeit learner contact; and report findings at their honest strength — existence, not prevalence. Most importantly, you have run Objective 4's test at least once: holding a design assumption you liked up against real learners and letting the contact decide.

---

## Key Terms

- **Learner research:** investigation of what is in learners' heads — prior knowledge, misconceptions, motivation, task-value perception — to predict design failure; distinct from market research, which predicts adoption.
- **Misconception:** a present, coherent wrong model that actively generates answers — not an absence of knowledge; survives exposition unless directly engaged.
- **Predict–explain–confront:** interview structure that surfaces wrong models by eliciting predictions, probing the explanation beneath them, and observing how the learner handles contradiction.
- **Law of small numbers:** the documented misconception that small samples reliably resemble their population (Tversky & Kahneman 1971).
- **Empathy map:** quadrant tool (says/thinks/does/feels) for structuring one learner's data; amended in this course with knows/wrongly-knows and values/costs lanes.
- **Motivation typing:** coding interview data with SDT constructs — regulation style and need support — rather than inferring motivation from design.
- **Evidence-based persona:** a composite learner character in which every load-bearing attribute traces to research evidence; functions as a prediction machine for design failure.
- **Existence vs. prevalence:** what small-n research can establish (the misconception is real and structured) versus what it cannot (how common it is) — the honesty boundary of this week's method.
- **AI-assisted persona generation:** using LLMs to draft personas or candidate misconceptions; legitimate as hypothesis generation, illegitimate as a substitute for learner contact.

---

## Bridge

Your research describes the learner at a moment: what they know, wrongly know, want, and can afford. But nobody drops out *at a moment in general* — they drop out on a Tuesday in week three, when a tool change, an unscaffolded assignment, and a first assessment land on the same day. Learning happens across time, and your content outline is structurally incapable of showing the experience of moving through it. The next method maps the journey the syllabus can't see. The bridge question: *you now know Priya's wrong model and her cost profile — but where, exactly, in eight weeks of experience, do they detonate?*

---

## Further Reading

- **Tversky, A., & Kahneman, D. (1971). "Belief in the law of small numbers." *Psychological Bulletin*, 76(2).** Three pages that founded fifty years of statistics-misconception research; the hospital problem in this chapter is theirs, and it still works in interviews today.
- **delMas, R., Garfield, J., Ooms, A., & Chance, B. (2007). "Assessing students' conceptual understanding after a first course in statistics." *Statistics Education Research Journal*, 6(2).** The CAOS instrument: documentation that students pass statistics courses with their misconceptions intact — the Track A case's entire premise, with data.
- **Spiegelhalter, D. (2019). *The Art of Statistics*.** The most readable serious account of what statistical concepts actually mean and how they are misread; mine it for predict–explain task material in any data-adjacent project.
- **McTighe, J., & Silver, H. F. (2020). *Teaching for Deeper Learning*.** Chapter-level treatment of prediction and hypothesizing as instructional moves; this week borrows their elicitation logic for research rather than teaching.
- **Hubbard, D. W. (2014). *How to Measure Anything* (3rd ed.).** The measurement-as-uncertainty-reduction framing that justifies small-n research without overclaiming it; the antidote to both "five isn't a sample" dismissal and qualitative overreach.

---

## LLM Exercise

*Productive-struggle guardrail: this prompt requires your drafted interview protocol (Exercise 5.2) as input. Asking an LLM to write your protocol from nothing would hand you literature-typical questions aimed at literature-typical learners — fluent, generic, and aimed at nobody you will actually meet. Draft first; then use the model as the pilot participant you can't burn.*

Complete Exercise 5.2 on your own. Then paste the following, with your draft, into the LLM of your choice:

```
You are playing two roles in sequence for a graduate LXD course.
I am pasting MY OWN draft learner-interview protocol for [one sentence:
your project and learner population]. Do not write new interview
questions for me at any point.

ROLE 1 — Hostile methods reviewer. Flag in my protocol:
(a) every question eliciting opinion or self-assessment where an
episode, prediction, or observed task would carry more evidence;
(b) every question a learner could answer correctly while holding a
wrong model underneath (no explanation probe);
(c) every leading question that telegraphs the answer I want;
(d) anything in my confront move that would make a participant feel
tested rather than researched.
Cite which question you mean each time. Do not rewrite them — state
the failure and the principle, and let me do the rewriting.

ROLE 2 — Pilot participant. Adopt a plausible member of my learner
population who holds ONE coherent misconception relevant to my content
(choose it yourself; do not reveal it in advance). Answer my
predict-explain questions in character, with the evasions, hedges,
and confident wrong explanations real learners produce. Then break
character and tell me: which of my questions surfaced your hidden
misconception, which let you hide it, and what the transcript would
have looked like if I had probed one level deeper.

End with nothing else. No summary advice, no model protocol.
```

**Assessable artifact:** submit (1) your original protocol, (2) the LLM's two-role output, and (3) your revised protocol with margin annotations — for each change, the critique or role-play moment that motivated it; for each rejected critique, why. Graded on the annotations, not the polish: the skill assessed is telling a methods improvement from a fluent suggestion. Then go interview real people; the role-play participant does not count toward your 3–5.
