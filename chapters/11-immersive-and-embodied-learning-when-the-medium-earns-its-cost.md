# Chapter 11 — Immersive and Embodied Learning: When the Medium Earns Its Cost

## Learning Objectives

By the end of this chapter you will be able to:

1. **(Understand)** Explain the two mechanisms by which immersion can reduce learning: interface-induced extraneous load and the novelty effect. *(Tracks A and B)*
2. **(Analyze)** Evaluate a proposed XR learning experience against the moderating evidence: immersion level, equipment type, prior XR experience, and adaptive layering. *(Tracks A and B)*
3. **(Evaluate)** Make a defensible modality decision for a specified learning task, including the pre-training requirement when immersion is chosen. *(Tracks A and B)*
4. **(Evaluate / Track B)** Make and disclose the modality decision for your own studio project. *(Track B; Track A students produce the same memo for the statistics course.)*

## Opening Case: The Tank That Beat the Headset

Two groups of students are learning about the same coastal habitat.

The first group files into a room with live touch tanks. Sea stars, urchins, anemones. They reach in. The water is colder than they expect; the urchin's spines move under a fingertip; someone gets splashed. A docent answers questions while students pass a hermit crab around.

The second group puts on headsets and enters a 360° VR rendering of the same habitat — and by every conventional measure of experience design, theirs is the more impressive product. The camera glides where no field trip could go. Production values are high. The students rate it memorable. Several say it was the coolest thing they did that semester.

Then both groups take the same learning assessment, and the touch-tank group outperforms the VR group by **31.1%** (Frontiers in Education, 2026 [verify exact citation before manuscript freeze]). Not a rounding-error difference — roughly a letter grade and a half, in favor of the bucket of seawater over the technology that cost two orders of magnitude more.

The study's mechanism analysis explains exactly why, and the explanation is the chapter: first, navigating the virtual environment itself consumed working memory — the interface generated **extraneous cognitive load** that the tank did not; second, the unfamiliar hardware acted as a **novelty distraction** — learners spent attention on the medium instead of the content. The validating detail: students with prior XR experience scored better. The headset was not neutral packaging for the lesson. For novices, it was a second curriculum, silently enrolled in alongside the first — and the second curriculum ate the first one's attention.

Hold the result carefully. This is one study, in one domain, against an unusually strong physical comparator — live animals are not a strawman control. It does not prove VR fails. It proves that *immersion is a cost the learning must repay*, and this chapter teaches you to compute, before purchase, whether it will. [contested — see pantry flag: "immersion improves learning" is registered in this book as *conditional*, not settled in either direction.]

## Prerequisites

This chapter assumes you can already:

1. **Classify mental effort as intrinsic, extraneous, or germane load** for a specified task (Chapter 3) — the first reduction mechanism is an extraneous-load story, told in a headset.
2. **Distinguish a desirable difficulty from a design flaw** (Chapter 3) — you will need this to see why a hard-to-use interface is never a desirable difficulty.
3. **Bring last week's gamification decision memo** — the modality decision uses the same decompose-then-decide discipline, and this week's memo sits beside it in the portfolio.

## Core Content

### What Immersion Actually Buys

**Immersion** is the degree to which a medium surrounds the learner and substitutes its sensory stream for the room's; **presence** is the resulting feeling of *being there*. Neither is a learning outcome. The evidence-disciplined question is what immersion lets the learner *perceive or do* that a cheaper medium cannot — because that delta is the only thing the cost can buy.

The literature converges on three deltas that are real:

**Spatial knowledge.** Some content is irreducibly three-dimensional — anatomical structure, molecular geometry, architectural space. Meta-analytic work on VR/AR in anatomy education finds genuine gains where the learning target is spatial structure itself [verify — VR/AR anatomy meta-analysis, 2024]. A heart you can orbit teaches its chambers' relations in a way no diagram cleanly can.

**Procedural rehearsal.** When the outcome is *performing a procedure* — a clinical sequence, an equipment operation, an emergency protocol — immersive simulation lets learners rehearse with consequences switched off. Reviews of immersive procedural training find benefits concentrated exactly here, where practicing in reality is dangerous, expensive, or rare (Computers & Education, 2024 [verify]).

**Functionally aligned embodied action.** **Embodied cognition** research holds that thinking is grounded in bodily interaction with the world, and recent meta-analytic work finds overall positive effects of embodied learning designs — *with the critical moderator that the body's action must be functionally aligned with the learning task* (embodied learning meta-analysis, 2024 [verify author/venue]). Tracing a force vector with your arm while learning forces: aligned. Waving at a menu to advance slides: decorative gesture, which adds motor load and buys nothing. The moderator is the finding. Movement is not magic; *task-relevant* movement is mechanism.

Outside these three territories — for declarative knowledge, conceptual relations, verbal reasoning — the honest summary of the immersion literature is *moderate average effects, strong moderators, and real counterfindings*. A systematic review in higher-education science contexts found significant positive impact in 18 of 33 studies (Frontiers in Education, 2024) — which a vendor will read to you as "majority positive" and a designer should read as "a coin flip plus a margin, before you know your moderators." A meta-analysis of immersive technologies in teacher education (52 studies, 22 experimental or quasi-experimental) found a moderate overall effect, Hedges' *g* = 0.524, with **immersion level and equipment type significantly moderating outcomes** (Frontiers in Virtual Reality, 2025) — more immersion was not monotonically better.

### Mechanism One: The Interface Eats the Working Memory

This is the chapter's deep dive, because it converts Chapter 3's most abstract idea into a purchasing decision.

Recall the architecture: working memory is brutally limited; **intrinsic load** is the content's irreducible complexity; **extraneous load** is everything the design wastes capacity on; **germane load** is the productive processing that builds schemas (Sweller). Learning happens in the germane channel, and the channels compete for one fixed budget.

Now put a novice in a headset. Before a single concept arrives, the learner is paying for: locomotion (how do I move?), interaction grammar (which button grips?), viewport management (where am I supposed to look — the freedom to look anywhere is also the obligation to choose), proprioceptive mismatch (my body says standing still, my eyes say gliding forward — for a meaningful fraction of users this escalates to simulator sickness, which is not a side effect but a total capacity loss), and the standing background task of *operating the medium*. Every one of these is extraneous load. None of it exists at the touch tank, where the interface — hands, water, eyes — was installed in infancy at zero marginal cost.

Here is the subtlety students miss: this load is invisible in the experience data. The VR learners in the opening case were not suffering; they were *delighted*. Extraneous load does not feel like waste — it often feels like richness, because attention is fully occupied. This is the seductive-details problem (Chapter 1) at the scale of an entire medium: the experience can be saturated with engagement while the germane channel runs near empty. An effortful interface is also never a desirable difficulty — desirable difficulties (Chapter 3) load the *learning operations* (retrieval, generation, discrimination); interface struggle loads the *delivery*, and difficulty in the delivery channel is pure tax.

The design arithmetic that falls out: immersion is justified only when the germane gain from what the medium uniquely enables (spatial perception, procedural action, aligned embodiment) exceeds the extraneous cost of operating it *for your actual learners at their actual familiarity level*. Both sides of that inequality are estimable before purchase. Most failed XR deployments never wrote the inequality down.

### Mechanism Two: Novelty Is Not Engagement (and It Expires)

The second mechanism is the **novelty effect**: unfamiliar technology commands attention *as technology*. The learner in a headset for the first time is having a headset experience that happens to contain a lesson.

Novelty distorts the evaluation twice. First, it diverts attention — in the touch-tank study, cognitive resources went to the interface rather than the content, and learners with prior XR experience, for whom the novelty had already burned off, scored better. That moderator is the mechanism's fingerprint: if the medium itself were adding learning value, experience with it should matter less, not more. Second, novelty inflates every short-term measure a pilot collects — engagement, satisfaction, time-on-task, recall of *the event* — which means a typical one-session XR pilot is structurally rigged to recommend purchase. The novelty is doing the performing, and novelty is a depreciating asset: by the fourth session it is gone, and the deployment's true, post-novelty effect is what your budget actually bought. Note the symmetry with last week: novelty decay in gamification, novelty distraction in XR — two chapters, one underlying warning about week-one data.

The two mechanisms interact viciously for exactly one population: novices get maximum interface load *and* maximum novelty distraction simultaneously. Which is why the single highest-leverage moderator in the XR literature is prior experience with the equipment — and why the field's most concrete prescription follows directly.

### The Pre-Training Prescription

If the analysis says immersion is warranted, the evidence imposes a precondition: **separate learning the medium from learning the target.**

The touch-tank study's own practical recommendation is pre-training programs that expose learners to low-stakes VR before any educational content arrives (Frontiers in Education, 2026). This is the immersive-scale version of Mayer's **pre-training principle** — people learn better from a lesson when they already know the names and behaviors of its components (Mayer [verify edition]). Applied here: the component the learner must know first is the medium itself.

Concretely, a pre-training block looks like: a short sandbox session (locomotion, grabbing, menus — content-free, playful, deliberately throwaway); a sickness screen with a dignified opt-out path to an equivalent flat-screen version (this is also your Chapter 9 variability obligation — an XR-only design with no alternative pathway fails the accessibility audit before it fails the load analysis); and *scheduling the learning content no earlier than the learner's second session*, so the novelty spike spends itself on the sandbox. Budget honesty: pre-training is a real cost — headset-hours, scheduling, attrition — and it belongs *inside* the modality decision, not discovered after it. If the deployment cannot afford pre-training, it cannot afford VR; running novices cold into content is choosing the opening case's losing condition on purpose.

One more moderator deserves a line: **adaptive layering**. Early evidence suggests AI-VR combinations that adapt difficulty in real time show the strongest results of the current wave — the adaptive layer matters as much as the immersion itself (Springer, 2026 [single source — treat as promising, not established]). The pattern to notice: the value is coming from *responsiveness to the learner*, which is medium-independent, not from the headset. A skeptic could read the adaptive-VR finding as evidence for adaptivity, with VR along for the ride. Until dismantling studies separate the two, that skeptical reading should sit beside the enthusiastic one in your memo.

### The Modality Decision Framework

Assemble the mechanisms and moderators into the decision method — five questions, asked in order, written down:

1. **Is there a spatial or procedural component that flat media cannot represent?** Not "would 3D be nice" — *does the learning outcome itself live in space or in performed action?* If no, stop; the strongest evidence territory is closed and you are shopping for extraneous load.
2. **Will the learner act, or only look?** Functionally aligned action is where embodiment pays. A passive 360° tour is the weakest XR genre and the one the counterfinding directly tested.
3. **What is the learners' prior XR experience, and is pre-training budgeted?** If novices and no pre-training budget: decline, on the opening case's authority.
4. **What does immersion cost — in load, money, time, supervision, sickness exclusion — and what else would that budget buy?** Cost here is a design variable, not a procurement detail. The comparison set must include the boring alternatives: the same dollars spent on retrieval practice, feedback, or worked examples, whose effects are better evidenced and decay-free. "Would VR help?" is the wrong question; "is VR the *best marginal spend* on this learning problem?" is the right one.
5. **Is there an adaptive or instructor layer, or is the medium expected to teach alone?** Unattended immersion is where the 15-of-33 null results live [verify inference — the reviews do not always report this moderator cleanly].

Three honest outputs, as with last week: *adopt with pre-training*, *adopt a cheaper embodiment* (desktop simulation, manipulables, AR-on-tablet — often the quiet winner), or *decline with reasons*. All three are portfolio artifacts.

## Mid-Chapter Checkpoint

Answer, then check.

1. Name the two mechanisms by which immersion reduces learning, and state which one the "prior XR experience predicts better scores" finding validates.
2. A vendor's pilot shows VR learners with higher engagement and higher satisfaction after one session. Why is this almost zero evidence for purchase?
3. Why is a clumsy VR interface *not* a desirable difficulty, even though it makes the lesson harder?
4. Your learning outcome is "interpret confidence intervals." Which framework question closes the XR door, and at which step?

*Redirects:* Missed (1)? Reread both mechanism sections — the moderator fingerprints novelty. Missed (2)? Reread "Novelty Is Not Engagement": one-session pilots measure the novelty spike, which depreciates to zero. Missed (3)? The distinction lives in Chapter 3 and Mechanism One: desirable difficulties load learning operations, interfaces load delivery. Missed (4)? Question 1 — confidence intervals have no spatial or procedural referent; the analysis ends in one line.

## The Evidence Box

| Study | Design | Finding | What it does *not* establish |
|---|---|---|---|
| Frontiers in Education systematic review (2024) | Systematic review, 33 studies, higher-ed sciences | 18/33 showed significant positive learning impact; "transformative potential **when implemented thoughtfully**" | A base rate you can claim — 15/33 did not show it; moderators decide which group you join |
| Teacher-education meta-analysis (Frontiers in VR, 2025) | Meta-analysis, 52 studies (22 experimental/quasi-experimental) | Moderate overall effect, Hedges' *g* = 0.524; **immersion level and equipment type significant moderators** | That more immersion is better — the moderator structure says the opposite is often true |
| Touch-tank counterfinding (Frontiers in Education, 2026) | Comparative study, live habitat vs. 360° VR | Hands-on lesson outscored VR by **31.1%**; mechanisms: interface extraneous load + novelty distraction; prior-XR learners did better; recommends pre-training | **Single source, one domain, strong physical comparator** — a benchmark warning, not a general anti-VR result. *Flagged: single-source.* |
| Adaptive VR finding (Springer, 2026) | Early studies of AI-VR difficulty adaptation | Adaptive VR shows strongest results of current wave; the adaptive layer matters as much as immersion | Whether adaptivity or immersion carries the effect — no dismantling studies yet. *Flagged: single-source.* |
| Embodied learning meta-analysis (2024) [verify author/venue] | Meta-analysis | Positive overall effects, **conditional on functionally aligned action** vs. decorative gesture | That movement per se helps |

**Heterogeneity:** high everywhere; the field's averages are moderate and its moderators are strong, which is precisely the profile where design choices dominate outcomes. **Unsettled:** post-novelty (multi-session) effects are rarely measured; cost-effectiveness against boring alternatives is almost never modeled; simulator-sickness exclusion rates are underreported, which biases samples toward XR-tolerant learners.

## Worked Example: The Modality Decision Memo for the Statistics Course

*Act Two closes here. Method applied to the Track A case: the introductory statistics online course.*

**Situation.** The university has an immersive-learning innovation grant. A vendor demo has circulated: students "walk inside the data," strolling through a 3D scatterplot landscape in headsets. The department chair, genuinely trying to help the redesign, suggests the statistics course apply for the grant. The Week 8 prototype (redesigned practice segments) and the Week 10 no-game decision are on the table; the question is whether the course's medium should now change.

**The problem as the designer sees it.** The grant is free money with a non-free design cost. The actual question is Framework Question 1: *does any learning outcome in introductory statistics have a spatial or procedural component that flat media cannot represent?* — followed honestly by Question 4: even if something could be ported to VR, is it the best marginal spend against this course's documented failure points (statistics anxiety, low practice persistence, sampling-distribution misconceptions — Week 5 research)?

**Process, including dead ends.** The designer inventories the course's outcomes: interpret descriptive statistics, reason about sampling distributions, run and read hypothesis tests, critique study designs. None is spatial in the physical sense — a scatterplot is a *notation*, not a place; making it walkable adds locomotion load to content whose difficulty was never about viewpoint. None is procedural in the embodied sense — the performed procedure is software use, already practiced in its real medium at zero transfer distance.

*Dead end #1:* the designer drafts a justification anyway — "immersion will reduce statistics anxiety by making data playful." Act One vocabulary kills the draft: that is an engagement claim wearing a learning claim's clothes, and the opening case shows exactly how a delightful medium coexists with worse learning. Anxiety appears in the learner research as fear of *being wrong publicly*, which a headset does not address. *Dead end #2:* embodiment enthusiasm. The designer sketches a gesture-based histogram-building activity — physically placing data points feels functionally aligned. Checking the moderator literature deflates it: the aligned action that matters for sampling-distribution reasoning is *manipulating the simulation and predicting its behavior* — drawing samples, watching the distribution build, being surprised. A mouse performs that action at zero interface cost. The gesture version is the same action plus motor overhead: decorative embodiment.

That dead end, however, surfaces the real finding: the course currently has *no* manipulation at all — students watch lecture videos about sampling distributions. The modality problem is real; it is just one rung lower than the grant assumed.

**Resolution.** The memo declines XR for this course and documents why (Questions 1 and 4 both fail). In its place, it adopts **direct-manipulation desktop simulations** for the three highest-misconception topics: students drag sample sizes, draw repeated samples, predict-then-observe the sampling distribution. This captures the active-manipulation benefit the embodiment literature actually supports — functionally aligned action on the concept — at near-zero interface load and no per-seat hardware cost. Grant money is redirected toward a proposal the evidence likes better: building the simulation set and the Week 13 instrumentation. The memo discloses one revisit condition: *if the program later adds a data-collection lab module (a genuinely procedural outcome), the framework runs again and may answer differently.*

**The lesson.** The modality decision is not "is the medium impressive?" but "what does the medium let the learner *do* that this outcome *needs* — and at what load?"

**The limit.** This resolution is local to a conceptual-statistical domain. An anatomy course, a chemistry-lab-safety module, or a clinical-procedure curriculum running the same five questions could legitimately arrive at *adopt with pre-training* — and the method would deserve equal credit there. Declining here is an output of the framework, not a stance against the medium. The framework also cannot price one real thing: recruitment and morale value of visible innovation. If the institution needs a lighthouse project, that is a legitimate institutional goal — it just must not be billed as a learning outcome.

**Track B extension.** Run the five questions on your own project this week, in writing, in order, stopping at the first failed gate. If you adopt immersion, your memo must include the pre-training block and the opt-out path (your Chapter 9 audit applies). If you adopt a cheaper embodiment, name the functionally aligned action precisely — what does the learner's hand *do*, and why is that the concept? Bonus eligibility: disclose one decision the evidence constrained and one it could not settle (post-novelty durability is almost always available for the second).

## Exercises

**Exercise 11.1 — Mechanism Diagnosis (Analyze).** A museum replaces a hands-on circuits bench with a VR circuits room. Visitor dwell time doubles; a quiz at exit shows no change; a delayed quiz two weeks later shows scores *below* the old bench's cohort. Using both mechanisms from this chapter, explain the three numbers — including why dwell time rose. Identify which single piece of additional data would best confirm your account.

**Exercise 11.2 — The Modality Decision Memo (Evaluate — Studio Assignment #6, 25 pts; Track B +5).** Produce the modality decision memo for your studio project (Track A: the statistics course — you may contest the worked example's resolution if you argue from the same framework; Track B: your own project). Required structure: outcome inventory → the five questions, in order, with the failing or passing gate shown → decision (adopt with pre-training / cheaper embodiment / decline) → cost line naming what else the same budget would buy → Evidence Disclosure.

**Exercise 11.3 — Production (Create).** Build the artifact your memo implies: *if adopt* — a one-page pre-training session plan (sandbox tasks, sickness screen, opt-out pathway, session schedule); *if cheaper embodiment* — a paper or clickable sketch of one direct-manipulation activity, annotating the functionally aligned action; *if decline* — the redesigned non-immersive treatment of the topic the XR proposal targeted. Attach to Studio Assignment #6.

**Exercise 11.4 — Counterfinding Defense (Evaluate).** Write a 200-word response to a stakeholder who says: "That touch-tank study is just one paper — the meta-analyses are positive, so we should buy headsets." Your response must use both the heterogeneity discipline from Chapter 10 and at least one moderator from this chapter, and must end with a decision rule rather than a verdict.

*Assessment notes:* Studio Assignment #6 is graded on the order and honesty of the five-question walk-through and on the cost line — a memo that never names the boring alternative spend cannot earn full marks regardless of its decision. As with Week 10, declining with evidence scores as highly as adopting with evidence.

## Evidence Disclosure (Chapter 11 template)

Complete and attach to Studio Assignment #6:

- **Evidence-grounded:** *My modality decision rests on [moderator/mechanism finding], citing [source]; the framework gate that decided it was Question [n].*
- **Research-grounded:** *My Week 5/6 learner research shows [prior XR experience level / anxiety / access constraint], which affects the decision by [effect].*
- **Assumption awaiting measurement:** *I am assuming [e.g., the desktop simulation produces the predict-observe engagement I designed for / post-novelty performance holds]. Disconfirming signal: [metric + timepoint], entering the Week 13 plan.*
- **Counterfinding line (mandatory this chapter):** *The strongest evidence against my decision is [finding], and I proceed anyway because [population/domain/moderator difference — not because the finding is single-source].*

## What Would Change My Mind

This chapter treats immersion as a cost that specific outcome types repay and others do not. That position would need revision if multi-session, preregistered comparative studies — measuring *post-novelty* performance with delayed tests — showed immersive treatments outperforming well-designed flat-media controls on *conceptual, non-spatial* outcomes, in novice populations, without pre-training. The specific signature to watch for: a dismantling study where the adaptive layer is held constant across VR and desktop conditions and the headset still adds learning value for non-spatial content. If that result replicated, the "immersion only pays where perception or action is the outcome" boundary drawn here is too tight, and the framework's Question 1 gate would need loosening.

## Still Puzzling

- **Where are the week-six XR studies?** Nearly the entire evidence base is single-session or single-unit. Post-novelty effectiveness — the only effectiveness a purchased deployment actually delivers — is close to unmeasured.
- **Who gets excluded by sickness, and what does that do to the evidence?** Simulator-sickness dropouts are inconsistently reported; if XR-intolerant learners exit studies early, published effects describe a filtered population.
- **Is adaptivity the active ingredient?** The adaptive-VR finding may be an adaptivity finding wearing a headset. No one has yet run the 2×2.
- **What is the touch tank's secret?** The counterfinding is usually read as "VR failed," but the physical condition's richness — multisensory input, social co-presence, a live docent — is its own unanalyzed bundle. Which ingredient did the learning? The answer would redesign both conditions.

## Chapter Summary

You can now: name the two mechanisms by which immersion reduces learning — interface extraneous load and novelty distraction — and recognize their fingerprints (delighted novices, inflated one-session pilots, prior-experience moderators); identify the three outcome territories where immersion has genuine evidence (spatial knowledge, procedural rehearsal, functionally aligned embodied action) and refuse the medium outside them; impose the pre-training prescription, with its opt-out path, as a precondition of any adoption; run the five-question modality framework in order and stop at the first failed gate; and price immersion against the boring alternatives the same budget would buy. Act Two is complete: your studio project is researched, mapped, co-designed, prototyped, audited, and now carries defended motivation and modality decisions.

## Key Terms

- **Immersion** — the degree to which a medium surrounds the learner and substitutes its sensory stream for the environment's.
- **Presence** — the subjective sense of "being there" that immersion produces; an experience property, not a learning outcome.
- **Interface-induced extraneous load** — working-memory cost of operating the medium (locomotion, controls, viewport management) rather than processing the content.
- **Novelty effect** — attention captured by unfamiliar technology as technology; inflates short-term measures and depreciates to zero with exposure.
- **Functionally aligned action** — bodily action whose form maps onto the concept or skill being learned; the moderator separating embodiment gains from decorative gesture.
- **Pre-training principle** — learners profit more from a lesson when its components are familiar in advance; applied here, the component is the medium itself.
- **Simulator sickness** — motion-conflict discomfort in VR; a capacity and equity issue requiring a screened opt-out path.
- **Adaptive layering** — real-time difficulty adjustment added to an immersive environment; early evidence suggests it may carry much of the observed benefit.
- **Modality decision** — the documented choice of medium for a learning task, made against outcome type, learner moderators, and opportunity cost.

## Bridge

Act Two is complete: a researched, mapped, co-designed, tested, audited prototype with defended motivation and modality decisions. Act Three deploys it into the conditions that decide its fate — and it begins with the decision the field is currently getting wrong at scale. The next chapter's opening study describes a tutor that students loved, used heavily, and rated as helpful. It made them measurably worse. What, exactly, should an AI be allowed to do inside your learning experience?

## Further Reading

- **The touch-tank comparative study (Frontiers in Education, 2026) [verify citation].** The course's sharpest counterfinding; read the mechanism analysis, not just the headline percentage — the prior-experience moderator is the transferable lesson.
- **Teacher-education immersive-technology meta-analysis (Frontiers in Virtual Reality, 2025).** The g = 0.524 estimate with the moderator structure that makes "more immersion" a wrong-direction heuristic; a model of how to read XR averages.
- **Mayer, R. E. *Multimedia Learning* (3rd ed., 2021) [verify edition].** The pre-training principle and its siblings — the flat-media evidence base every XR proposal must beat, not bypass.
- **Sweller, J., et al. — cognitive load theory (recent updates).** The mechanism underneath Mechanism One; rereading it after this chapter turns headset demos into load audits.
- **Peters, D. *Interface Design for Learning* (2014).** The practitioner bridge: how interface decisions become cognitive decisions, written before the headset era and more relevant because of it.

## LLM Exercise: The Modality Red Team

Copy-paste into the LLM of your choice, replacing bracketed material. Guardrails as always: the model argues and stress-tests; you supply evidence labels, learner data, and the verdict. The model must not be allowed to run the framework *for* you — note that step 3 forbids it.

> I am a learning experience design student making a modality decision. Learning outcome: [one sentence — be precise about what the learner must be able to DO]. Learner population: [two facts, including prior XR experience if known]. Proposed medium: [the immersive/embodied proposal on the table].
>
> Do the following, in order:
> 1. Steelman the proposal: what would the medium let this learner perceive or do that flat media cannot, for THIS outcome? If you cannot find a spatial, procedural, or functionally-aligned-action justification, say so plainly.
> 2. Red-team it using two named mechanisms: interface-induced extraneous load and the novelty effect. Describe specifically where each would appear in my deployment, and what each would do to my pilot data.
> 3. Do NOT tell me the decision. Instead, give me: (a) the single cheapest alternative design that captures the benefit you identified in step 1, and (b) the three questions about my learners I must answer from my own research before deciding.
> 4. List what a one-session pilot of this medium would overestimate, and what study design would correct it.
>
> Do not invent citations or effect sizes. Describe findings generically; I will verify against my course's Evidence Box.

**Deliverable:** the transcript plus a 150-word reflection naming (a) whether the model's steelman survived your outcome inventory, (b) the cheapest-alternative it proposed and whether your memo adopts it, and (c) one thing the model asserted that you checked and found unsupported. The reflection is what gets assessed.
