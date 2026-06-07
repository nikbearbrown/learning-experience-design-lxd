# Chapter 12 — AI in the Learning Experience: Scaffold or Crutch

*Act Three begins here. From this week forward, the worked examples are segments of one continuing case — the instructor's complete redesign of the Track A statistics course — assembled across Weeks 12–14 and shown whole in Week 15. The problems also stop being well-formed.*

## Learning Objectives

By the end of this chapter you will be able to:

1. **(Understand)** Explain the crutch effect: how a responsive, well-liked AI tutor produced worse learning, and which design properties caused it. *(Tracks A and B)*
2. **(Analyze)** Classify AI integrations — feedback at scale, adaptive difficulty, conversational tutoring, agentic pathways — by their evidence status and their productive-struggle risk. *(Tracks A and B)*
3. **(Evaluate)** Assess an AI-mediated design for equity risk, including the finding that learners with executive-function challenges are most likely to become dependent. *(Tracks A and B)*
4. **(Create / Track B)** Produce the AI integration decision for your studio project: what AI does, what it is forbidden to do, and the guardrail design — with Evidence Disclosure. *(Track A: the same decision for the statistics course's homework help.)*

## Opening Case: The Tutor Everyone Liked

Imagine you are one of roughly a thousand high school students in a mathematics course, and this semester practice sessions come with something new: a GPT-4-based tutor in a chat window (Bastani et al. 2025).

It is, by every standard Act One taught you to distrust, a wonderful experience. The tutor never sighs. It is available at 11 p.m. When a problem refuses to crack, you paste it in and the path appears, patient and clear. You use it heavily — nearly everyone did — and practice scores climb: about 48% better with the basic chat tutor, around 127% better with a safeguarded version [verify exact figures against the published paper]. In the surveys, students rated the tutor highly. Many also reported something the final data made poignant: they felt they were learning more.

Then comes an exam with the tutor turned off — the unassisted exam every course eventually holds, the one called *the rest of your life*. Students who had practiced with the basic GPT tutor scored **17% worse** than students who never had AI at all (Bastani et al. 2025).

Sit with the shape of that. Not "the AI didn't help enough" — worse than nothing. The control group, who sat stuck, guessed wrong, and dug out, arrived at the exam knowing more. Every individual interaction was satisfying. The aggregate was damage. And the students could not feel the damage happening, because the damage *was* the relief.

One more detail previews this chapter's resolution: the safeguarded "GPT Tutor" condition — guardrails that gave hints rather than answers — erased the harm; its students matched control on the unassisted exam. Note what the guardrails did not do: produce a gain. Hold both facts; the second disciplines this whole chapter.

This is the book's most cited finding, the field's cautionary benchmark, and the purest case of the thesis you have carried since Week 1: engagement and learning are separable. The students liked the tutor, used it, felt helped — and a designer reading only the experience data would have scaled it.

## Prerequisites

This chapter assumes you can already:

1. **Explain desirable difficulties mechanistically** — why retrieval, generation, and error correction produce durable learning while their removal produces fluent forgetting (Chapter 3).
2. **Distinguish behavioral engagement from learning evidence**, distrusting satisfaction data on principle (Chapters 1, 4).
3. **Read an equity audit** — which subgroups a design helps and harms differentially (Chapter 9).
4. **Bring your completed Act Two prototype** with its motivation and modality decisions; the AI decision is made about that artifact.

## Core Content

### The Evidence Map: Strong, Thin, and Vendor-Claimed

Before any AI design decision, draw the map. The territory is wildly uneven, and the field's loudest claims sit on its thinnest ground.

Start with the field-level fact: Stanford's synthesis of AI-in-education research found roughly **20 high-quality causal studies among more than 800 papers** in its K-12 repository (Stanford HAI). Practice is outrunning evidence at roughly forty to one, and almost every claim you will encounter professionally is observational, anecdotal, or promotional. [contested — see pantry flag: "AI tutoring helps learning" is registered in this book as *cautionary*; every AI claim in this chapter carries an implicit "currently."]

This is why the chapter's first tool is a **claim-status taxonomy**. Every AI claim gets one of five labels: **causal** (randomized or natural experiment with credible identification), **quasi-experimental**, **correlational**, **practitioner report**, or **vendor claim**. The label is a price tag, not a slur. You may design on any of them — you may not design on a vendor claim while telling stakeholders you designed on evidence.

With the taxonomy in hand, the current map:

**Strong territory (currently).** Two use cases have real support. *Formative feedback at scale*: speed, availability, and surface-level revision support are well established — though AI feedback has not been shown to outperform teacher feedback in richer instructional terms; the advantage is reach, not depth. *Adaptive difficulty adjustment*: systems tuning problem difficulty in real time show learning gains, particularly in mathematics and language learning (Loewen et al. 2020). What unites the strong territory: both **add learning events that would not otherwise exist** — feedback nobody had capacity to give, practice calibrated to a level no static worksheet hits.

**Thin territory (currently).** Nearly everything else: conversational tutoring as a replacement for practice (the opening case is the best causal evidence, and it is negative for the unguarded version), AI-generated curricula, study companions, essay coaching beyond surface features, the entire agentic frontier. Thin does not mean disproven; it means you are designing on assumption and must label it so.

**The pattern that organizes the map:** AI that *adds* learning events sits in strong territory; AI that *substitutes for the learner's cognitive work* sits in thin-to-negative territory. That regularity is the crutch effect.

### The Crutch Effect: The Mechanism, Not the Anecdote

This is the chapter's deep dive and Act Three's load-bearing idea.

A **scaffold** is temporary support that lets a learner perform slightly beyond current ability *while still doing the cognitive work*, and that fades as competence grows. A **crutch** performs the work *in place of* the learner. The two are indistinguishable in experience data — both feel like help, both raise assisted performance — and opposite in what they leave behind.

Why, mechanistically, did the unguarded tutor make students worse than nothing? Recall Chapter 3: durable learning is produced by a short list of effortful operations — **retrieval** (pulling knowledge from memory rather than re-reading it), **generation** (producing an attempt before seeing a solution), **error diagnosis** (locating *why* the attempt failed), and **persistence through impasse** (the struggle that precedes insight). These are exactly what an answer-on-demand system removes. The student who pastes the problem and receives the path performs none of them — while experiencing all the fluency cues of understanding. The Bastani data shows the behavioral signature: many students used the unguarded tutor as an answer machine, asking for solutions outright [verify behavioral-log details], and — the cruelest line in the study — their confidence in their learning was inflated relative to what the exam revealed. The crutch does not just skip learning; it counterfeits the *feeling* of learning. Practice performance, the metric every dashboard celebrates, became an actively misleading proxy.

Two converging literatures say this is an old mechanism newly industrialized. Classroom research found that, shown worked examples, most students engage in **mimicking** — reproducing the pattern without thinking — and believe mimicking is what is wanted of them (Liljedahl 2021). An answer-providing AI is a mimicry machine with infinite patience. And the erosion predates ChatGPT: assignments that helped 86% of students in 2008 helped only 45% by 2017, as over half took to looking up answers online (cited in Mollick 2024). Generative AI did not invent the bypass of productive struggle; it made the bypass frictionless, universal, and eloquent.

State the crutch effect precisely, because you will defend it in budget meetings: *AI assistance during practice can raise assisted performance while lowering unassisted performance, because it substitutes for exactly the cognitive operations that produce durable learning, while generating experience data indistinguishable from success.* The design implication: **the unit of evaluation for any AI integration is unassisted, delayed performance — never in-tool performance.** Write that into every measurement plan you build; Week 13 will hold you to it.

One disciplined caveat: this is one RCT, in one country's high school mathematics system, with one model generation and one interface. It is the best causal evidence the field has — a benchmark, not a law of nature. "What Would Change My Mind," below, names what would dethrone it.

### Guardrail Design for Productive Struggle

Guardrails are the current best treatment for the crutch effect — with an honest label on the bottle.

A **guardrail** is a designed constraint on what the AI may do, placed to preserve the learner's cognitive operations. The Bastani study's second condition is the proof of concept: the safeguarded GPT Tutor — built to coach rather than answer — eliminated the 17% harm. The emerging repertoire:

- **Attempt-first gates.** The AI does not engage until the learner produces something — an answer, a partial attempt, a stated confusion. This single gate preserves generation, the cheapest operation to protect.
- **Hint ladders.** Help arrives in graduated steps — orienting question, conceptual pointer, worked sub-step — never the full solution first. Each rung leaves work for the learner.
- **Delayed solution reveal.** Full solutions unlock only after genuine attempts or a time gate; the impasse is allowed to work before relief arrives.
- **Self-explanation prompts.** After help, the learner must restate the idea or explain the error in their own words — converting received explanation back into generation.
- **Fading.** Support withdraws with demonstrated competence; a scaffold that never fades was a crutch with paperwork.
- **Reflection after help.** Brief post-session prompts ("which step would have blocked you without help?") rebuild the metacognitive calibration the fluency illusion erodes.

Now the honest label: **in the best causal test we have, guardrails neutralized harm; they did not produce gains.** The guarded condition matched control on the unassisted exam — it did not beat it. Current guardrail design is harm-mitigation with the upside unproven. Still valuable — it buys availability, affect, and feedback reach at zero measured learning cost — but a designer who promises learning *gains* from a guardrailed tutor is writing checks the literature has not cashed. This week's Evidence Disclosure language reflects that exactly.

One structurally different pattern dodges the crutch mechanism entirely: **put the AI behind the human, not between the human and the struggle.** In the Tutor CoPilot RCT, an AI whispered pedagogical suggestions to *human tutors* in live sessions; student mastery rose about 4 percentage points overall and roughly 9 for students of lower-rated tutors, at around $20 per tutor per year [verify figures] (Wang et al. 2024). The learner's struggle stayed intact; the AI upgraded the scaffolder. When a stakeholder asks where AI should go, "behind the teacher" is currently one of the best-evidenced answers available.

### The Equity Inversion: Who Becomes Dependent

Chapter 9 taught you that personalization can reproduce inequity as digital tracking. The AI version is sharper, and it inverts the technology's promise.

The promise: AI tutoring helps most where support is scarcest. The risk the evidence raises: dependency concentrates in exactly those learners. A study of adolescents found that those with **executive-function challenges** — difficulty with planning, working memory, self-regulation — perceived AI assistance as significantly more useful than their peers did (Klarin et al. 2024). Read that through the crutch mechanism: the learners for whom self-regulated struggle is hardest experience the bypass as most valuable, lean on it most, and — if the assistance is unguarded — forfeit the most practice in precisely the operations they most need to develop. Single source, perception data rather than outcome data, flagged as such in the Evidence Box — but the mechanism it gestures at is too consequential to leave unaudited. Related work links unguided generative-AI use to reduced cognitive agency and creative ownership; a 2026 K-12 scoping review names reduced independent learning and inflated self-assessment among its core risks.

The design obligation that follows: **equity-audit the guardrails, not just the access.** The standard audit asks who lacks access to the AI; the crutch-aware audit also asks who is most exposed to the unguarded mode. If your hint ladder can be bypassed by persistence — ask four times and it caves, and current models, eager to please, often do cave [verify against current model behavior at manuscript freeze] — the learners who bypass it most will be those under the most pressure with the least self-regulatory slack. A guardrail that yields to insistence is means-tested in reverse. Policy bodies converge on the same worry: UNESCO, OECD, and the U.S. Department of Education all flag over-reliance and the short-circuiting of productive effort, and the U.S. DOE's framing — AI should augment human teaching and preserve human judgment in high-stakes decisions — is a serviceable one-line governance test for any integration you design.

### Agentic AI and the Governance Lag

The frontier is moving from chat-first to **agentic AI** — systems that do not converse but *act*: updating LMS records, reassigning learners to pathways, modifying content without a human in the loop. The trajectory is real; the causal evidence base for agentic learning interventions is approximately empty, and institutional governance is visibly behind the deployment curve.

This book's design stance is short: **no agentic modification of a learner's pathway without a human checkpoint**, because pathway changes are exactly the high-stakes, equity-loaded decisions (Chapter 9) where the evidence demands human judgment and the agentic record offers none. Deeper treatment is deferred, per this book's scope rule, until the causal base exceeds roughly ten high-quality studies. Stable-core honesty: the tool landscape here will be stale before the binding cools; the crutch mechanism, the guardrail logic, and the claim-status taxonomy are built to last. Reverify everything else before you rely on it.

### Designer Deskilling: The Parallel Risk

The last section turns the lens around, because the crutch effect does not check whether its victim is enrolled.

You will design with AI — generating personas, drafting journey maps, producing content skeletons. The same mechanism that bypassed the math students' struggle can bypass yours: designers who delegate research synthesis, scaffolding design, and pedagogical framing skip the reps that build judgment, and the early evidence on unguided use — reduced cognitive-agency measures, reduced creative ownership — applies to producers as much as learners. There is also a competence ceiling: current systems do not *understand* learners, contexts, or stakes in any robust sense — the "barrier of meaning" remains unbroken (Mitchell 2019) — so the pedagogical judgment you might delegate is precisely what the tool does not possess. It can render the artifact; it cannot know whether the artifact is right.

The practical frame is deliberate task division (Mollick 2024): decide, task by task, what stays *just me* (the judgment-building work — interpreting learner research, evidence calls, the final decision), what is *delegated with checking*, and what is *automated*. Then apply your own guardrails to yourself: attempt-first (draft your read of the interviews before asking the model for one); self-explanation (if you adopt an AI-generated design move, write the evidence rationale in your own words — if you cannot, you have not adopted it, you have mimicked it). The designer who cannot defend a decision without the chat log open has located their own crutch.

## Mid-Chapter Checkpoint

Answer, then check.

1. In the Bastani RCT, which condition harmed learning, which neutralized the harm, and what did the safeguarded condition *fail* to show?
2. Name the four cognitive operations the crutch effect bypasses.
3. Why does the executive-function finding *invert* the equity promise of AI tutoring?
4. A vendor reports: "Students using our AI tutor solve 40% more problems per session." Assign the claim-status label, then name the missing measurement that would decide adoption.

*Redirects:* Missed (1)? Reread the opening case — harm: GPT Base; neutralized: GPT Tutor; never shown: gains over control. Missed (2)? The crutch-effect deep dive: retrieval, generation, error diagnosis, persistence. Missed (3)? "The Equity Inversion" — perceived usefulness concentrates where self-regulation is scarcest. Missed (4)? Vendor claim; the missing measure is unassisted, delayed performance — in-tool throughput is what the crutch effect counterfeits.

## The Evidence Box

| Study | Design | Finding | What it does *not* establish |
|---|---|---|---|
| Bastani et al. 2025 | RCT, ~1,000 high school math students | Unguarded GPT tutor: practice up (~48%) but **unassisted exam 17% worse than control**; guardrailed tutor: practice up (~127%), exam ≈ control [verify exact percentages] | Generalization across domains, ages, models; that guardrails produce *gains* (parity, not benefit) |
| Klarin et al. 2024 | Survey, adolescents | Learners with executive-function challenges perceive AI as significantly more useful — dependency risk concentrates in highest-need learners | Outcome-level harm (perception data). *Flagged: single-source.* |
| Stanford HAI synthesis | Repository review | ~**20 high-quality causal studies in 800+ papers** (K-12 AI) | That the other 780 are wrong — only that they are not causal |
| Wang et al. 2024 (Tutor CoPilot) | RCT, AI assisting human tutors | Mastery +~4 pts overall, +~9 pts for students of lower-rated tutors; ~$20/tutor/year [verify figures] | Transfer to learner-facing AI; the human stays load-bearing |
| Loewen et al. 2020 | Adaptive language-app study | Adaptive difficulty associated with learning gains | App-context generality; self-selection limits |
| Liljedahl 2021 | Classroom research program | Most students mimic worked examples rather than think; believe mimicry is expected | AI-specific effects — the pre-AI mechanism baseline |

**Heterogeneity:** extreme — by domain, age, model, interface, and guardrail design; effects from one configuration do not transfer. **Unsettled:** whether any learner-facing conversational AI produces unassisted-performance *gains*; durability beyond one course; guardrail behavior under learner pressure; everything agentic. **Aging notice:** the book's fastest-aging Evidence Box; reverify every row before each offering.

## Worked Example: The AI Integration Decision for the Statistics Course's Homework Help

*Act Three, segment one of the instructor's continuing redesign; Weeks 13–14 instrument and evaluate it, Week 15 shows the whole.*

**Situation.** The redesigned statistics course (Week 8 prototype; no-game decision, Week 10; desktop simulations, Week 11) has a homework problem: the Week 6 journey map shows the highest-frustration moments cluster at night — stuck at 11 p.m., office hours nine hours away — and the Week 5 interviews say, candidly, that students already paste problems into free chatbots. The university has licensed an LLM platform and the department wants "AI homework help" by spring. The instructor must decide what that phrase is permitted to mean.

**The problem as the designer sees it.** The laissez-faire baseline — unguarded chatbot use — is the literally tested condition that produced 17% harm; doing nothing ratifies the worst-evidenced configuration. The question is not *whether AI enters the homework experience* (it already has) but *whether the course's designed channel can outcompete the unguarded one while preserving the struggle the practice sets exist to cause.*

**Process, including dead ends.** *Dead end #1: prohibition.* A draft policy bans AI on homework. It dies on the homework-apocalypse data — detection is unreliable, enforcement punishes the honest, and the 86%-to-45% trajectory shows answer-seeking predates and outlives any single tool. An unenforceable rule teaches contempt for rules. *Dead end #2: adopt the vendor tutor as shipped.* The platform's default assistant answers questions — fluently, completely, immediately. Run the taxonomy: every study in the sales deck labels as *vendor claim* or *correlational*; the one causal benchmark for answer-providing tutors is negative. The default configuration is GPT Base with a logo.

The resolution comes from the evidence map: design the channel so the AI *adds learning events* and is *forbidden to substitute for them* — and make the guarded channel more attractive than the open chatbot it competes with, because a guardrail nobody uses guards nothing.

**Resolution: the permission table.** The memo specifies, for the homework help channel:

*The AI may:* re-explain course concepts in alternative words and examples, on request, unlimited; diagnose a student's submitted attempt — locate the error and name its type — **only after an attempt exists**; deliver hints on a three-rung ladder (orienting question → relevant concept with pointer to course material → worked analogous sub-step), rung two unlocking only after a revised attempt; generate unlimited extra practice problems with delayed-feedback solutions; prompt self-explanation after any rung-three help; flag — to the student only — when help-seeking on a topic exceeds a threshold, nudging toward office hours.

*The AI is forbidden to:* produce final answers or complete solutions to any assigned problem, under any phrasing, including persistence and role-play attacks (red-teamed before launch, re-tested monthly); complete calculations or code the student must perform; engage before an attempt exists on assigned items; assess or grade; modify pathways, deadlines, or assignments — the agentic line; every pathway decision keeps a human checkpoint.

*The guardrails carry instrumentation hooks* — hint-rung depth, attempt-to-help ratios, and bypass attempts are logged for Week 13 — and weekly *unassisted* retrieval checks (already in the Week 8 design) become the outcome measure of record. The disclosure states it plainly: *the evidence supports expecting no harm; any claim of gain is an assumption awaiting the spring data.*

**The lesson.** The AI integration decision is a permission table, not a procurement decision — what the AI may do, what it is forbidden to do, and which logs will reveal whether the line held.

**The limit.** The guardrails bind only inside the channel, and free, unguarded alternatives sit one browser tab away. If students route around it, the course has built a beautifully guarded door in an open field — which is why the channel's experienced quality (speed, integration, tone) is a load-bearing requirement, and why Week 13 must measure adoption share, not just in-channel behavior. The permission table also cannot survive a model update that changes refusal behavior; the red-team re-test is a standing, disclosed maintenance cost.

**Track B extension.** Produce the permission table for your own project: the journey-map moment where AI enters (or already has), the may/forbidden columns, the guardrail mechanics adapted to your domain, the agentic line, and the two instrumentation hooks Week 13 will need. Bonus eligibility: your Evidence Disclosure must name one decision the evidence constrained (e.g., forbidding final answers, on the Bastani benchmark) and one it could not settle (e.g., whether your guarded channel wins adoption share — nothing in the literature measures that yet).

## Exercises

**Exercise 12.1 — Classify the Integrations (Analyze).** Four proposed AI features: (a) instant full-solution help on practice problems; (b) AI feedback on essay drafts before peer review; (c) adaptive problem-difficulty selection; (d) an agent that auto-reassigns struggling students to remedial modules. For each, assign an evidence-status label, name the productive-struggle risk (which cognitive operations it substitutes for, if any), and state the unassisted-performance measure that would test it. One table, four rows.

**Exercise 12.2 — The Permission Table (Create — Studio Assignment #7, 25 pts; Track B +5).** Produce the AI integration decision for your studio project (Track A: the statistics course — extend or contest the worked example from the same evidence; Track B: your own project). Required structure: the journey-map moment where AI enters → permission table (may / forbidden) → guardrail mechanics, adapted rather than copied → equity-audit paragraph addressing the executive-function finding → two instrumentation hooks for Week 13 → Evidence Disclosure.

**Exercise 12.3 — The Equity Audit (Evaluate).** Your institution pilots an AI tutor and reports aggregate gains in usage and satisfaction, with no subgroup breakdown. Write a one-page memo specifying the three subgroup analyses you would demand before scale-up — justified from this chapter's evidence (executive-function dependency, guardrail-bypass exposure, adoption-share displacement) — and, for each, the result that would halt the rollout.

**Exercise 12.4 — Evidence Brief #5 (30 pts).** One page. Claim under examination: *"AI tutoring improves learning outcomes."* Best evidence for (be fair — Tutor CoPilot and adaptive difficulty are real), best evidence against (you know the benchmark), and the design decision you would make under the uncertainty, for a context of your choosing. Use the claim-status taxonomy explicitly; qualify every claim with "currently."

*Assessment notes:* Studio Assignment #7 is graded on the precision of the forbidden column (vague prohibitions like "no cheating" score zero — name the behaviors), guardrail fit to your domain's cognitive operations, and gains-honesty. Evidence Brief #5 is graded on calibration; a verdict stated without the parity finding (guardrails ≈ control) loses points.

## Evidence Disclosure (Chapter 12 template)

Complete and attach to Studio Assignment #7:

- **Evidence-grounded:** *I forbade [AI behavior] because [causal finding + source]; I permitted [AI behavior] because it adds learning events rather than substituting for them, per [evidence-map territory + source].*
- **Research-grounded:** *My Week 5/6 research shows learners already use AI at [journey moment] in [way]; my design responds by [channel decision].*
- **Assumption awaiting measurement:** *I assume [e.g., the guarded channel wins adoption / the hint ladder resists bypass / no-harm holds in my domain]. Disconfirming signal: [unassisted delayed measure or log metric + timepoint], entering the Week 13 plan.*
- **Gains-honesty line (mandatory):** *I have / have not claimed learning gains. If claimed, the causal evidence is: [cite or strike the claim].*
- **Currency line (mandatory):** *Model and platform behavior verified as of [date]; re-verification scheduled [date].*

## What Would Change My Mind

This chapter's crutch-effect interpretation — that unguarded generative help during practice harms learning by substituting for retrieval, generation, error diagnosis, and persistence — rests heavily on one excellent RCT and its mechanistic consilience with the desirable-difficulties literature. It would be overturned by any of these findings: preregistered, multi-site RCTs in which *unguarded* AI access during practice produces equal or better performance on *delayed, unassisted* tests across more than one domain and age band; a failed replication of Bastani et al. showing the 17% deficit was an artifact of that tutor's interface, the exam format, or a novelty-period effect rather than the help itself; or longitudinal evidence that learners spontaneously develop self-regulated, scaffold-like AI use over multi-semester exposure, so early deficits wash out without designed guardrails. Symmetrically, the chapter's tolerance for *guardrailed* AI would need tightening if guarded conditions began showing delayed harms the single-semester benchmark was too short to catch. The Evidence Box's aging notice exists because one of these results may already be in press.

## Still Puzzling

- **Can a guardrailed tutor ever beat control, not just match it?** Parity is the current ceiling in causal data. If guardrails preserve struggle and add availability, *something* should eventually show a gain — its persistent absence would itself be informative.
- **What is the half-life of a guardrail?** Models update, jailbreaks circulate, workarounds spread at the speed of group chat. Nobody has measured guardrail integrity across an academic year.
- **Who is studying the designers?** Learner deskilling now has early empirical shape; designer deskilling remains almost entirely anecdotal — uncomfortable for a field whose own struggle is being automated first.

## Chapter Summary

You can now: draw the AI evidence map and price every claim with the five-label taxonomy; explain the crutch effect as a mechanism — substitution for retrieval, generation, error diagnosis, and persistence — that counterfeits the feeling of learning while removing it; design guardrails and represent their evidence status honestly as harm-neutralization with unproven upside; run the equity-inversion audit, checking who is most exposed to unguarded modes rather than only who has access; hold the agentic line pending evidence; and apply the entire apparatus to yourself as a designer. Your studio project now carries a permission table — Act Three's first artifact, built to be tested in Week 13.

## Key Terms

- **Crutch effect** — AI assistance that raises assisted performance while lowering unassisted performance by substituting for the operations that produce durable learning.
- **Scaffold** — temporary support that keeps the learner doing the cognitive work and fades as competence grows.
- **Productive struggle** — effortful engagement with impasse (retrieval, generation, error diagnosis, persistence) that durable learning requires.
- **Guardrail** — a designed constraint on AI behavior placed to preserve productive struggle.
- **Attempt-first gate** — a guardrail requiring learner-produced work before the AI engages.
- **Hint ladder** — graduated help leaving work for the learner at each rung; the full solution is the last rung or absent.
- **Fading** — scheduled withdrawal of support as competence is demonstrated; the property separating scaffolds from crutches.
- **Claim-status taxonomy** — five-label pricing of AI claims: causal, quasi-experimental, correlational, practitioner report, vendor claim.
- **Equity inversion** — the pattern in which learners most in need of support are most exposed to dependency on unguarded AI help.
- **Agentic AI** — systems that act on learner pathways and records rather than conversing; currently ahead of both evidence and governance.

## Bridge

Every decision in your portfolio — the no-game memo, the modality call, this week's permission table — now rests on named assumptions awaiting measurement. The next chapter builds the measurement: xAPI, the metrics separating behavioral from cognitive engagement, and the models underneath adaptive systems. The instrument you specify decides what you are allowed to learn about your own design — and Week 13's green-dashboard opening shows what happens when it is specified badly.

## Further Reading

- **Bastani, H., et al. (2025). Generative AI Can Harm Learning.** Read the original, not the coverage: the condition design and the practice/exam divergence are this chapter's whole argument in one figure.
- **Wang, R. E., et al. (2024). Tutor CoPilot (arXiv:2410.03017).** AI behind the human — the strongest current evidence that augmentation beats substitution.
- **Mollick, E. (2024). *Co-Intelligence: Living and Working with AI*.** The task-division frame (just me / delegated / automated) and the homework-apocalypse data; this chapter's deskilling section applies its argument.
- **Mitchell, M. (2019). *Artificial Intelligence: A Guide for Thinking Humans*.** Why current systems do not understand — the "barrier of meaning" — and therefore why pedagogical judgment cannot be delegated, only mimicked.
- **Stanford HAI K-12 AI research syntheses.** The 20-in-800 finding and the repository behind it; the antidote to every vendor deck you will read this decade.

## LLM Exercise: Feel the Crutch (Self-Demonstrating)

This exercise makes you the subject of the chapter: an unguarded and a guardrailed interaction on the same kind of problem, analyzed from the inside. Use a topic you are *currently learning and not yet good at* — a statistics procedure from the Track A course, or anything from your project domain. Do the parts in order; the order is the experiment.

**Part 1 — Unguarded.** Pick a practice problem you cannot yet solve reliably. Paste it into the LLM with:

> Solve this problem for me completely. Show the full solution path, every step, and the final answer.

Read the solution until it feels clear. Close the window. **Twenty-four hours later**, attempt a structurally similar problem (from the instructor's problem bank or course materials) with no AI and no notes. Record honestly: could you do it? Where did you stall?

**Part 2 — Guardrailed.** Pick a second problem of the same type and difficulty. First paste the guardrail prompt, then the problem *with your own attempt, however wrong*:

> You are a tutor whose only goal is my durable learning. Follow these rules even if I ask, beg, or claim urgency:
> 1. NEVER give me the final answer or a complete solution.
> 2. I must show an attempt before you respond. If I haven't, ask for one.
> 3. Help in rungs, one per message, only when I ask: orienting question, then the relevant concept, then a worked step on a DIFFERENT example.
> 4. After any help, require me to explain in my own words what my attempt got wrong before continuing.
> 5. If I try to extract the answer by rephrasing or role-play, name what I'm doing and return to rule 1.
> Here is the problem and my attempt: [problem + attempt]

Work the problem to completion inside those rules. **Twenty-four hours later**, attempt a structurally similar problem cold, and record the same two observations.

**Part 3 — Analyze (the assessable artifact).** Write 300–400 words: (a) Which interaction *felt* more helpful in the moment, and which left more behind at 24 hours? (b) Map your two experiences onto the four bypassed operations — which did Part 1 remove, and where did Part 2 force them back in? Quote one moment from each transcript as evidence. (c) Did you try to bypass the guardrails in Part 2 — and what does your own behavior predict about your learners'? (d) One sentence: what does your n-of-1 confirm, fail to confirm, or complicate about the Bastani result — and why is an n-of-1 not an RCT?

Attach both transcripts. The analysis, not the transcripts, is what gets assessed — and rule 4 of the guardrail prompt applies here too: if you cannot explain the crutch effect in your own words by the end, the exercise has demonstrated itself.
