# Chapter 3 — The Cognitive Machinery: Load, Difficulty, and Durable Learning
*Why the lesson that feels easiest to survive is often the hardest to learn from.*

Here is the thing that should bother you about the opening case. A team of talented designers looked at a lesson everyone agreed was a mess — cluttered, demanding, a complaint magnet — and fixed it. They decluttered the screen. They replaced an awkward prediction prompt with a smooth animated walkthrough. They moved a jarring mid-lesson recall question to the end-of-module quiz where it belonged. Every metric they were given to watch went up: completion, satisfaction, time-to-complete down 22%. They wrote a case study. Eight weeks later, the instructor pulled final-exam data and found that students who took the beautiful new version scored *worse* on the transfer items — the questions that asked them to apply sampling-distribution reasoning to a scenario they hadn't seen before. Every instrument the team watched said triumph. The instrument nobody watched said disaster.

This is not a story about bad designers or a careless team. It is a story about a gap between two things that feel like they should be the same thing and aren't: how easy an experience is to get through, and how much learning it produces. The gap has a mechanism. Understanding the mechanism is what this chapter is for.

<!-- → [DIAGRAM: two-axis grid — horizontal axis: ease of experience (low → high), vertical axis: learning produced (low → high). Four quadrants labeled: Q1 lower-left "Hard and useless" (extraneous difficulty), Q2 upper-left "Hard and productive" (desirable difficulty), Q3 lower-right "Easy and empty" (seductive fluency), Q4 upper-right "Well-scaffolded, effective". The Version A and Version B lessons plotted as labeled points. Caption: "The fluency trap lives in Q3. Most engagement dashboards only measure horizontal movement."] -->

---

Working memory is the bottleneck. Everything else in this chapter flows from that sentence, so it is worth sitting with.

When you encounter something genuinely new — a concept you have never seen before, a relationship you are constructing rather than recalling — you hold it in a workspace called working memory while you figure out what to do with it. That workspace is small. Cramped, really. The exact figure depends on the material and how you measure it, but the classic framing — about seven items, plus or minus two — has been refined by decades of subsequent work into something more like: *a handful of novel elements, for a matter of seconds, before they start falling out*. The limit is not a bug or a human failing to be designed around. It is the architecture.

Long-term memory is different. Effectively unlimited, and it stores knowledge not as a list of facts but as *schemas* — organized structures that bundle many elements into one. Your statistics instructor reads `P(A|B)` as a single chunk, the way you read "the" as a single thing rather than three letters. For a novice, that same expression is five or six elements fighting for the same cramped workspace: the P, the parentheses, the vertical bar, what A means, what B means, the conditional relationship between them. Same notation. Utterly different cognitive demand. What counts as "a handful of elements" depends entirely on what the learner already knows, which means the bottleneck is not a fixed property of the material — it is a relationship between the material and the person encountering it.

Cognitive Load Theory, developed by John Sweller and colleagues from the 1980s onward, turns this architectural fact into design guidance by asking a simple question about any learning interaction: *where is the working-memory budget being spent?* (Sweller 1988; Sweller, van Merriënboer & Paas 2019). The answer comes in three categories.

The first is **intrinsic load** — the complexity inherent in the material relative to this learner's prior knowledge. Sweller formalizes this as *element interactivity*: how many things must be held in mind simultaneously because they interact, because understanding any one of them requires having the others. Sampling distributions have high element interactivity for a novice: sample, statistic, the act of repeated sampling, the distribution *of* the statistic across those repetitions — all at once, or no understanding. You cannot sequence your way around intrinsic load; you can only manage it, by pre-training isolated elements before combining them, or by segmenting the material at natural joints. But you cannot eliminate it without changing what is being taught.

<!-- → [DIAGRAM: element-interactivity illustration — two examples side by side. Left: "memorizing vocabulary" — five isolated nodes, no edges, label "low interactivity." Right: "sampling distributions" — five nodes (sample, size n, statistic, repeated sampling, distribution of statistic) all connected by edges, label "high interactivity." Caption: "Interactivity is what makes a concept genuinely hard for a novice — not its unfamiliarity, but how many pieces must be held together simultaneously."] -->

The second is **extraneous load** — workspace consumed not by the material but by the presentation. A cluttered screen. A diagram and its explanation placed six centimeters apart so the learner must hold one in memory while reading the other. Narration that duplicates text already on screen. A decorative animation that runs while the concept is being introduced. This is pure waste. Every unit of working memory spent navigating the container is a unit unavailable for the content. Eliminating extraneous load is the designer's first job, and it is not in conflict with the learner's interest; it is entirely on their side.

The third — and this is where the opening case turns — is **germane processing**: effort devoted to the learning itself. Generating a prediction before seeing the answer. Retrieving a definition from memory rather than looking it up. Explaining in your own words why your initial sketch was wrong. Constructing the schema rather than watching someone else's schema displayed. This processing is what the design exists to provoke, and it costs workspace, and it is supposed to. The design crime is not that it is effortful. The design crime is confusing it with the other two and removing it in the name of polish.

One honest note on the taxonomy: whether germane processing constitutes a distinct category of load or is better understood as *managed intrinsic* load has been debated inside CLT itself, and later formulations fold it into the intrinsic bucket (Sweller, van Merriënboer & Paas 2019). The three-category version is taught here because it directs design attention most clearly. Treat it as a working tool, not a settled ontology.

The design rule in one sentence: minimize extraneous, manage intrinsic by expertise, protect germane. And the professional note for designers in the room: "reduce friction," the prime directive of consumer product design, is not portable to learning design without a load analysis. Friction that is extraneous: remove it. Friction that is germane: removing it is the error. The animated walkthrough in Version B was a correct extraneous-load fix on the cluttered screen; it was a category error on the prediction prompt.

---

The prediction prompt is doing something specific, and the specificity is what matters. It belongs to a family of interventions that Robert Bjork named **desirable difficulties** — conditions that slow apparent performance during learning but improve delayed retention and transfer (Bjork & Bjork 2011). The unifying mechanism: each one forces retrieval or generation rather than passive re-exposure, and effortful retrieval is itself a learning event that strengthens and reorganizes the schema.

Spacing is the schedule version. Distributing practice across sessions — returning to sampling distributions in week six, when the session-four material has had time to partially fade — produces more durable retention than massing the same total practice into a single session (Cepeda et al. 2006). The design lever is the *return*: week-six work that silently requires week-two's concept, retrieved cold. The catch is that it produces more errors during practice and less felt fluency, which means every metric on the engagement dashboard will ding it, and it will be optimized away at the next sprint review unless someone in the room has read the literature.

Retrieval practice is the interaction version. Before showing, ask. Version A's predict-simulate-reconcile cycle is the pattern: generate your expected answer, run the simulation, write two sentences about why you were wrong. The reconciliation — *why was my sketch off?* — is germane processing of the highest grade. It is also the interaction learners most want removed from the experience, because it is uncomfortable and error-prone, and because learners sincerely and measurably mispredict what will help them. When Karpicke and Blunt (2011) had students choose between restudying material and practicing retrieval, students preferred restudy; restudy produced worse retention. The preference is coherent — restudy *feels* like learning, because the material becomes fluent — but the feeling is wrong.

<!-- → [CHART: bar chart with two condition pairs — "immediate recall" and "one-week delayed recall" — each with two bars: "restudy" and "retrieval practice." Retrieval practice slightly lower on immediate, substantially higher on delayed. Source: Roediger & Karpicke 2006 pattern. Caption: "The desirable-difficulty signature: worse during practice, better when it counts. The gap between the bars is where the learning lives."] -->

Interleaving is the sequencing version. Mix problem types so the learner must first decide which approach applies — the discrimination that blocked practice quietly performs for them (Rohrer & Taylor 2007). In the statistics course: confidence-interval, hypothesis-test, and descriptive questions arriving shuffled, because the exam — and life — will not announce the chapter title before presenting a scenario.

Now the conditional. A difficulty is desirable only if the learner can succeed at the processing it induces. This is where the CLT literature and the difficulties literature, which can look like they are arguing, are actually one argument read at two expertise levels.

For novices facing high-element-interactivity material, generation and minimal guidance can overload working memory entirely before any schema forms. The worked-example effect captures this precisely: novices learn more from studying fully worked solutions than from attempting equivalent problems unaided (Sweller & Cooper 1985). Not because being shown things is generally better than doing things — it isn't — but because for a novice, attempting a high-interactivity problem means burning the entire working-memory budget on search and error management rather than on the structure of the solution. The difficulty is real; it is just not doing useful work. It is the right kind of effort aimed at a target the learner does not yet have the machinery to hit.

The flip side is equally important: the **expertise reversal effect** (Kalyuga et al. 2003). The worked example that helps a novice becomes useless and then actively harmful as expertise grows, because the expert now processes the example's guidance as redundant information — which is itself extraneous load. What was scaffolding becomes noise. The optimal design is not a setting; it is a trajectory. Strong guidance and worked examples early; supports progressively withdrawn; retrieval, interleaving, and generation dialed up as schemas solidify. Sweller's term for this arc is *the completion problem* — fading worked examples by progressively removing steps — and it is the mechanism under what good teachers do by craft when they say "I'm not going to tell you this one."

<!-- → [DIAGRAM: the "fade" trajectory — x-axis: learner expertise (novice → expert), y-axis: instructional support level (high → low). Two crossing lines: one declining ("guidance / worked examples"), one rising ("retrieval / generation / interleaving"). Crossover region labeled "the fade zone — schemas forming." Caption: "The expertise reversal predicts a crossover. Designing for one point on this axis and ignoring the trajectory is the most common implementation error."] -->

This synthesis — call it *the fade* — is also the mechanism under the long "discovery learning" controversy. Minimally guided instruction reliably underperforms guided instruction for novices (Kirschner, Sweller & Clark 2006). "Learners construct knowledge, therefore withhold instruction" is the field's most expensive non sequitur. Active cognitive construction — the kind that produces durable learning — is fully compatible with, and for novices demands, strong guidance. What changes as expertise grows is not whether construction is happening; it is where the guidance sits on the fade.

---

There is a diagnostic method in here, and it is the most practically useful thing this chapter can give you. Two pieces of friction can look identical on the surface — learners stall, complain, make errors, abandon — while one is a design flaw and the other is the learning working. Engagement data cannot tell them apart. Mechanism analysis can.

Four questions, run against any point of friction:

**One.** Is the learner effortfully processing the content or the container? Struggling to recall the standard error is content — plausibly germane. Struggling to find where the standard error was defined, to parse a cluttered screen, to fight the input widget: container — extraneous, eliminate it.

**Two.** Does the effort involve retrieval, generation, or discrimination of the target material? If yes, you are probably looking at a desirable difficulty. If the effort is re-orienting, decoding instructions, or managing the tool, no.

**Three.** Can *this* learner succeed at the processing it induces, with feedback? A prediction prompt a novice fails productively — sketch, simulate, reconcile — is desirable. The same prompt with no feedback loop, or aimed at material the learner has no schema for yet, is abandonment dressed as rigor.

**Four.** Would removing it change what is practiced? This is the decisive question. Removing Version B's clutter changed nothing about what learners practiced — extraneous friction, correct to remove. Removing the prediction prompt changed practice from *generating and reconciling a model* to *watching an animation* — that friction was the curriculum.

Priya, the LXD consultant brought in after the Version B disaster, builds her friction ledger by running exactly these questions against every A→B change in the redesign. The process has two dead ends worth naming, because you will hit them too. The first: the team relitigates aesthetics ("A was objectively cluttered!") — true, and useless, because clutter and the prediction prompt are being tried in the same courtroom. The differences must be itemized before they can be judged. The second dead end: she tries to settle the prediction-prompt question with in-course data and almost cannot — quiz scores inside the module favor B, naturally, because B's quiz is open-reference and the practice smoother — and she nearly accepts performance evidence for a learning question. The only data that can adjudicate is delayed and transfer-flavored. She writes in her report: "We are lucky this product sits inside a course with a final exam. Most products aren't that lucky. Build the delayed measure in."

The ledger settles into three piles. *Extraneous, B was right:* the declutter; the integrated diagram-and-explanation (a split-attention fix); the segmented structure; eliminating the six-click path to the formula sheet. *Germane, A was right:* the predict-simulate-reconcile cycle; the mid-lesson closed-book recall of standard deviation versus standard error (relocating it to an open-reference quiz converted retrieval into lookup — the entire point of the exercise removed without anyone noticing). *Seductive, both wrong in different ways:* Tilly the cartoon t-distribution, who delivers charm and extraneous load in equal measure, and who would earn her screen time if she delivered the prediction prompt instead of existing between sections.

Version C ships with B's surfaces and A's demands. Predict-simulate-reconcile restored, now preceded by a pre-training screen that names the three interacting elements before asking the learner to generate — a straight intrinsic-load-management move that keeps the generation inside novices' cognitive capacity without removing the difficulty. Closed-book recall restored mid-lesson with immediate feedback; the open-reference version stays in the end quiz as a spaced second touch. Tilly delivers the prediction prompt or doesn't appear. And two instrumented events — prediction-attempt quality and closed-recall success rate — now feed a delayed follow-up item three weeks later, so the next redesign can argue from learning data instead of forum sentiment.

<!-- → [TABLE: friction ledger — three columns: "A→B change," "Load classification," "Verdict." Rows: declutter (extraneous → remove, correct); animated walkthrough replacing prediction prompt (germane → remove, error); recall relocated to open-reference quiz (germane → remove, error); diagram-explanation integrated (extraneous → remove, correct); Tilly mascot (extraneous → keep with task alignment or remove). Caption: "The ledger forces itemization before judgment. Every whole-version verdict hides a mixture of correct and incorrect moves."] -->

---

Three theoretical traditions organize most LXD conversation, usually as mood music. It is worth reducing each to the design implication that survives the evidence — the only form worth carrying into practice.

Constructivism, the tradition running from Piaget through Vygotsky: knowledge is constructed by the learner through active processing, not transmitted by exposure. The design implication is real and important — *design for what the learner does, not what the content says.* The prediction prompt, the self-explanation, the problem before the lecture: these are constructivist moves that have solid experimental support. What constructivism does *not* imply: withholding guidance. The non sequitur is elegant — "learners construct knowledge, therefore let them construct without support" — but it dissolves immediately on contact with the worked-example evidence. Active cognitive construction is fully compatible with strong guidance; for novices on high-interactivity material, it requires it. Vygotsky's zone of proximal development — the band between what a learner can do alone and with support — is, in the chapter's terms, the load-managed region where difficulty stays desirable.

Situated learning, from Lave and Wenger (1991): learning is bound to the context, community, and authentic activity in which it occurs. The design implication: close the distance between practice environment and performance environment — authentic tasks, real tools, the social fabric designed rather than assumed. The honest limit: a powerful lens with a thinner experimental base than CLT's, and it sits in structural tension with scalable platforms that strip context by design. That tension is not resolved here; it is kept live.

Embodied cognition: cognitive processes are rooted in the body's interaction with the world; movement and gesture can be part of thinking, not decoration around it. The design implication, and the evidence's key moderator: *bodily action helps when it is functionally aligned with the learning task.* Tracing the curve. Enacting the rotation. A 2024 meta-analysis finds positive overall effects exactly under that alignment condition [verify]. Gesture for gesture's sake — tablet interactions designed to feel tactile without connecting to the concept — adds extraneous load. The alignment condition is not a minor qualification; it is the entire finding.

The pattern across all three reductions is the same: each theory earns its place in practice exactly insofar as it survives translation into the load-and-difficulty machinery. That is not theoretical imperialism. It is the discipline of asking every framework the same question: *what does working memory do differently under your design?*

---

One warning, because it is the most common failure mode in practice. The machinery above compresses temptingly into a checklist — *declutter ✓, add retrieval ✓, space the practice ✓* — and a checklist is exactly the wrong container, because every item is a conditional whose truth depends on the learner, the material, and the moment. Retrieval before any schema exists: undesirable difficulty. A worked example handed to an expert: the expertise reversal in action. The checklist preserves the verbs and discards the conditions, and the conditions are the knowledge.

The professional form of this chapter is a habit of argument, not a feature list: *for this learner, at this point in their schema formation, this design choice directs working memory toward the target processing — and here is the evidence status of that claim.* Sat next to a "reduce friction" ticket, the right question is not "does friction increase or decrease?" but "which friction, for whom, and does removing it change what is practiced?"

<!-- → [INFOGRAPHIC: the four-question diagnostic as a decision flowchart — starting node "point of friction identified," branching on Q1 (content / container), Q2 (retrieval / generation / discrimination?), Q3 (can this learner succeed with feedback?), Q4 (does removing it change what is practiced?). Terminal nodes labeled: "extraneous — remove," "desirable difficulty — keep and instrument," "undesirable difficulty — scaffold or fade in." Caption: "Run this before any 'reduce friction' ticket is closed. The output is not always a verdict — sometimes it is a measurement plan."] -->

What load theory cannot tell you is why a learner who *can* keep going *wants* to. The machinery of this chapter is a theory of capacity — of the conditions under which the bottleneck stays clear enough for learning to happen. It says nothing about whether anyone opens the app on day forty. That gap is exactly one chapter wide.

---

## Evidence Box

<!-- → [TABLE: evidence summary — columns: Finding, Source, Direction & size, Heterogeneity/limits. Rows corresponding to each major empirical claim in the chapter.] -->

| Finding | Source | Direction & size | Heterogeneity / limits |
|---|---|---|---|
| Working memory severely limited for novel elements; schemas circumvent the limit | CLT synthesis, Sweller, van Merriënboer & Paas 2019 | Framework-level; massive convergent support | Precise capacity estimates vary by material and measure; design implication is insensitive to exact number |
| Worked-example effect: novices learn more from solutions than unaided solving | Sweller & Cooper 1985; replicated extensively | Positive, moderate-to-large for novices | Reverses with expertise; strongest in well-structured domains |
| Expertise reversal: guidance that helps novices harms experts | Kalyuga et al. 2003 (review) | Crossover interaction | Single most design-relevant moderator in the chapter; requires knowing learner level |
| Multimedia load principles (coherence, signaling, split-attention, redundancy, segmenting, pre-training) | Mayer 2021 | Positive, mostly small-to-moderate per principle | Strongest for novices; boundary conditions actively studied |
| Spacing improves delayed retention | Cepeda et al. 2006 (meta-analysis) | Positive, robust | Optimal gap scales with retention interval |
| Retrieval practice beats restudy; learners mispredict it | Roediger & Karpicke 2006; Karpicke & Blunt 2011 | Positive, moderate-to-large delayed | Transfer gains positive but smaller than retention gains |
| Interleaving beats blocking for discrimination | Rohrer & Taylor 2007 | Positive delayed; *negative during practice* | Domain-dependent; practice-performance dip is the engagement-trap hazard |
| Generation/minimal guidance harms novices on high-element-interactivity material | Chen et al. 2018 [verify]; Kirschner, Sweller & Clark 2006 | Negative for novices under complexity | Boundary literature for the difficulties program; exact thresholds unsettled |
| Embodied action helps when functionally aligned with task | 2024 meta-analysis [verify] | Positive overall, alignment-moderated | Citation to be confirmed before manuscript freeze; treat as provisional |
| Germane load as separate construct | Debated within CLT; Sweller, van Merriënboer & Paas 2019 | — | Working tool, not settled ontology; later formulations fold into intrinsic |

**What remains unsettled:** where the desirable/undesirable boundary sits for a given learner and material (no general formula — hence learner research and instrumentation); how lab-calibrated effects scale into commercial products; whether real-time load measurement will ever be reliable enough to drive adaptive design.

---

## What Would Change My Mind

The chapter's central claim is that working-memory load architecture — minimize extraneous, manage intrinsic by expertise, protect germane processing — is the right primary lens for diagnosing why learning designs succeed or fail. Two findings would force revision. Narrowly: well-powered, preregistered failures to replicate the cornerstone interactions in ecologically valid digital products — particularly the expertise reversal and the worked-example advantage for novices — would collapse the fade prescription this chapter's guidance hangs on. More broadly: if real-time load measurement matures and large instrumented studies find that load indices add *no predictive power* for delayed retention beyond simple time-and-errors telemetry, the load framework stands exposed as redescription rather than mechanism. Neither finding currently exists; the second is the one to watch as instrumentation improves.

---

## Still Puzzling

- **Where is the boundary, numerically?** "Difficulty is desirable when the learner can succeed at the induced processing" is true and unsatisfying — no formula converts prior-knowledge measures into a difficulty setting.
- **Does germane processing exist as a measurable thing?** If germane effort cannot be measured separately from intrinsic load, the chapter's tidiest design rule rests on a distinction instruments cannot see.
- **How much survives the leap from lab to market?** The load effects are mostly lab- and classroom-calibrated. The direction seems robust; the sizes at product scale are genuinely unknown.
- **Whose effort budget are we managing?** Load analysis treats learner effort as a resource to allocate. Learners are also people with finite evenings. The ethics of deliberately designing effortful experiences for tired adults gets surprisingly little attention in a literature built mostly on undergraduates with course credit.

---

## Exercises

**Warm-up**

1. *(Recall — intrinsic/extraneous/germane)* A designer proposes replacing a mid-lesson "explain in your own words" prompt with a multiple-choice comprehension check, on the grounds that the open-response format creates unnecessary frustration. Classify the load each format generates. Which, if either, is extraneous, and which is germane? State the prior-knowledge condition that would change your answer.
*Difficulty: low. Tests: load-category classification.*

2. *(Recall — expertise reversal)* An adaptive platform serves the same fully worked example to all learners regardless of their assessment history. Describe the specific harm this causes for high-expertise learners and the mechanism that produces it.
*Difficulty: low. Tests: expertise reversal, extraneous load.*

3. *(Recall — desirable difficulties taxonomy)* Name three desirable difficulties from the chapter, state the design lever for each (schedule, interaction, or sequencing), and name the dashboard metric most likely to flag each one as a problem.
*Difficulty: low. Tests: difficulties taxonomy and the engagement-trap hazard.*

**Application**

4. *(Apply the fade)* You are redesigning a four-week online module on Bayesian inference for learners ranging from complete novices to practitioners who have used Bayes informally. Sketch the structure of worked-example and generation-prompt use across the four weeks — which weeks lean on examples, which introduce retrieval, at what point interleaving enters. Justify each transition point by naming the schema-formation condition it assumes.
*Difficulty: moderate. Tests: the fade trajectory applied to realistic content.*

5. *(Apply the diagnostic)* A learner forum post reads: "The practice problems are unfair — they ask us to solve things we've never been shown how to do." Run the four-question diagnostic. What facts would you need to collect to determine whether this is an extraneous friction, a desirable difficulty, or an undesirable difficulty? Name the specific measurement for each open question.
*Difficulty: moderate. Tests: four-question diagnostic, prior-knowledge dependence.*

6. *(Apply the friction ledger)* The statistics module described in this chapter had five A→B changes: screen declutter, animated walkthrough replacing the prediction prompt, recall question relocated to open-reference quiz, diagram-explanation integrated, and Tilly the mascot added. Rebuild the friction ledger: load classification, verdict, and the mechanism sentence for each. For at least two rows, name the delayed outcome measure that would let the verdict defend itself empirically.
*Difficulty: moderate. Tests: friction-ledger method across all five changes.*

**Synthesis**

7. *(Synthesize CLT + difficulties + constructivism)* A colleague argues that constructivist pedagogy and cognitive load theory are incompatible — "CLT wants to reduce effort; constructivism wants active struggle." Write a 200-word rebuttal that uses the worked-example effect, the expertise reversal, and Vygotsky's zone of proximal development together to show why the apparent conflict dissolves.
*Difficulty: moderate-high. Tests: theoretical integration across the chapter.*

8. *(Synthesize load + difficulties + the fade)* Design a single retrieval-practice interaction for a novice audience on a high-element-interactivity topic of your choice. Show: (a) how you manage intrinsic load before the retrieval demand; (b) the retrieval structure itself; (c) the feedback mechanism that keeps the difficulty desirable rather than undesirable; and (d) how the interaction would change for an expert audience, citing the expertise reversal.
*Difficulty: high. Tests: integrated application of the chapter's full machinery.*

**Challenge**

9. *(Challenge — open)* The chapter claims the four-question friction diagnostic is itself an unvalidated instrument: it synthesizes the literature but has not been tested as a design tool. Propose a study that would test whether designers trained on the diagnostic classify friction more accurately — and with better learning outcomes — than untrained designers. What is your outcome measure, your comparison condition, and your primary threat to validity? One page maximum.
*Difficulty: high. Tests: research-design thinking, honest engagement with the chapter's own epistemic limits.*

---

## LLM Exercise

*Goal: produce a friction-ledger entry for your studio project (Track A: the statistics course) with an LLM as adversarial reviewer — under the guardrail that the model may attack your classification but never author it.*

Complete your own analysis **first**, then paste:

---

I am a graduate student learning cognitive load analysis for learning experience design. I have classified one point of friction in a real learning experience, and your role is to stress-test my classification — not to produce one for me.

THE INTERACTION (factual description, no judgment): [what the learner sees, must do, and gets as feedback]

THE LEARNER: [who they are; your best evidence about their prior knowledge, and how you know]

MY CLASSIFICATION (written before this conversation):
- Friction type: [extraneous friction / desirable difficulty / undesirable difficulty]
- My answers to the four diagnostic questions: (1) content or container? (2) retrieval, generation, or discrimination of target material? (3) can this learner succeed at it, with what feedback? (4) would removing it change what is practiced? [your four answers]

YOUR TASK, under these rules:
- Attack my weakest answer first: identify which of my four answers rests on the least evidence, and ask one question that exposes the assumption. Wait for my reply.
- Then argue the opposite verdict as strongly as the facts I gave you allow. If you must invent facts to make the case, say "this would only hold if—" and name the missing fact instead of inventing it.
- Ask what data from real learners would settle the classification; refuse to accept "more analytics" without my specifying which metric and why it indexes load or learning rather than behavior.
- Do not classify the friction yourself at any point. Do not soften your critique to be agreeable.
- End by requiring me to write the final ledger entry myself: verdict, the one assumption it still rests on, and the Week 5 research question that would test it.

I will submit: my pre-conversation classification, the transcript, and my final ledger entry.

---

*Assessable artifact: the three-part package. Grading weight: the quality of your four answers and the final ledger entry; the transcript is checked for whether the verdict remained yours.*

---

## Further Reading

- **Sweller, J., van Merriënboer, J., & Paas, F., "Cognitive Architecture and Instructional Design: 20 Years Later," *Educational Psychology Review* (2019)** — the field's own honest stocktaking of CLT, including the germane-load debate.
- **Mayer, R., *Multimedia Learning*, 3rd ed. (2021)** — the experimental principle catalog for screen-based instruction; the most directly design-actionable book on this list.
- **Brown, P., Roediger, H., & McDaniel, M., *Make It Stick* (2014)** — desirable difficulties for the general reader; assign it to stakeholders who need the why without the citations.
- **Kirschner, P., Sweller, J., & Clark, R., "Why Minimal Guidance During Instruction Does Not Work," *Educational Psychologist* (2006)** — the polemic that forced the guidance debate into the open; read it with its rebuttals for the full exchange.
- **Liljedahl, P., *Building Thinking Classrooms in Mathematics* (2021)** — what learners actually do with the tasks we design (mimic, stall, fake, think), from fifteen years of classroom observation.
