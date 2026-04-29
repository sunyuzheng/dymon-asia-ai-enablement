# Dymon Asia AI Enablement Briefing — Speaker Notes

These notes are written for a live briefing. They are not meant to be read verbatim. Use them to keep the narrative tight, make the transitions explicit, and avoid over-explaining each slide.

## Slide 1 — AI Enablement for Investment Research

Open with the promise of the session: this is not a generic AI talk and not a prompt-engineering workshop. The question is how AI changes investment research workflows when it moves from chatbot answers into agentic systems, persistent context, and PM-level judgment.

Set the expectation that the session will be practical. The audience should leave with a mental model for what to build first and why a course can make that change operational.

Transition: start with the core thesis before the examples.

## Slide 2 — Executive Thesis

Frame the main distinction: most people are not underusing AI because the model is weak; they are underusing it because the operating model is wrong.

Explain chatbot mode as a human-in-the-middle workflow: the model answers, the human carries context, executes work, finds problems, and starts over. Agentic mode changes the environment: the AI can work with files, data, browser, code, errors, citations, and persistent artifacts.

Land the claim: the goal is not more summaries. The goal is turning repeated research judgment into reusable workflows.

Transition: clarify what this session should resolve.

## Slide 3 — What This Session Is For

Tell the room that the goal is a precise mental model, not excitement about AI. Walk through the four questions quickly.

Emphasize the last two: PMs do not win by having access to the same information everyone else can retrieve; they win by turning information into differentiated judgment. Dymon should start with individual PM workflows because alpha formation is personal before it becomes team infrastructure.

Transition: make the session concrete with a live question.

## Slide 4 — Demo Kickoff

Ask for one real research question from the room. It can be a company, macro theme, event, market risk, or current uncertainty worth a PM's attention this week.

Explain that you will start two workflows in parallel: a strong off-the-shelf Deep Research run and an agentic research workflow. The point is not to perform a magic trick at the end. The point is to let everyone see the different operating models produce different artifacts.

Transition: while that runs, give the room your background and why this course exists.

## Slide 5 — About Superlinear

Keep this brief. Your credibility is not just audience size or course ratings; it is the intersection of economics, experimentation, growth data science, Statsig, and AI-native building.

Make the key point: Superlinear is not teaching tool names. It is teaching the craft of using AI to build durable work systems. The student examples are proof that non-traditional coders can cross the boundary from AI user to AI builder.

Transition: now map the whole narrative so people know where the talk is going.

## Slide 6 — Narrative Map

Use this as the roadmap. The talk starts with a live question, moves through the paradigm shift, reads the market signals, translates those signals into PM work, returns to the demo, and ends with the course architecture.

Do not dwell on every row. The main purpose is to make the talk easy to follow and show that it is not a collection of AI anecdotes.

Transition: Part I begins with the interface shift.

## Slide 7 — Part I

State the thesis cleanly: AI is not primarily a better chatbot; it is a new interface to compute.

Explain that this distinction matters because if the audience sees AI as only a chat product, they will design shallow workflows. If they see it as an interface to compute, tools, files, and memory, the strategy changes.

Transition: use the Bill Gates example to make the interface point.

## Slide 8 — Paradigm Shift Setup

Ask the room to guess Gates's first revolutionary technology. Let people think briefly. The wrong guesses are useful because they reveal the usual framing: internet, mobile, cloud.

The point is not Bill Gates as an authority. The point is that the first answer was GUI, which changed who could operate compute.

Transition: reveal why GUI is the right comparison.

## Slide 9 — The Reveal

Explain GUI as an access shift. Before GUI, computing was powerful but gated by command-line and programming fluency. GUI made specific computing tasks usable by non-programmers.

Then state the analogy: natural language is the third interface. It lets non-programmers operate more general-purpose compute. That is why AI is not just another SaaS category.

Transition: compare GUI, programming, and natural language.

## Slide 10 — Three Interfaces

Walk through the table. GUI is easy but constrained by what designers expose. Programming is general but hard. Natural language is general and easy to start, but hard to wield well.

Emphasize the last column: natural language still needs context, tools, and verification. This is why the message is not "stop using ChatGPT" as a product; it is "stop using chat as the whole operating model."

Transition: a new interface only matters if work is redesigned around it.

## Slide 11 — The Missing Operating Model

Use the analogies sparingly. The red-flag analogy: if the human must walk in front of the machine, the machine cannot express its speed. The electric motor analogy: factories had to redesign workflows, not merely swap the power source.

Then connect it to chat: if humans still move context, execute work, and bring failures back manually, AI cannot compound.

Transition: define the specific ceiling of chat workflows.

## Slide 12 — Chat As Ceiling

Explain the three failure modes: open feedback loop, repeated context supply, and poor asset retention.

The phrase to land: the human becomes middleware. This is why AI can look intelligent and still fail to change operations.

Transition: contrast that with agentic workflows.

## Slide 13 — Agentic Operating Model

Describe agentic AI as a loop: specify, gather, execute, inspect, persist. This is not a longer prompt; it is a different workflow architecture.

For a PM, the important shift is role change. The human becomes the specifier, reviewer, and judge, not the person manually carrying every step.

Transition: now show that the market is already moving in this direction.

## Slide 14 — Part II

Set up the evidence section carefully. The point is not to tell a success-story highlight reel. The point is to read the pattern across AI-native companies and incumbents.

AI-native firms show the steep curve. Incumbents show the governance and absorption path.

Transition: start with Cursor as the cleanest AI-native workflow example.

## Slide 15 — Cursor / Anysphere

Do not over-index on valuation. Say explicitly that valuation is not the strategic point. The signal is how fast an AI workflow became the daily environment for developers.

The parallel for Dymon: a high-value profession can shift its default work surface quickly once the workflow is redesigned around AI.

Transition: move from market adoption to frontier-company behavior.

## Slide 16 — Anthropic / Claude

Explain that the strongest AI users have moved beyond asking whether AI can code. They are changing the practice of coding: specify the task, let the agent work, review the diff, tighten tests, preserve the learning.

The key takeaway is method, not model access. Weaker users may have the same model but lack the craft of specification, decomposition, inspection, testing, and iteration.

Connect to business users: this is accessible beyond engineers because the bottleneck is increasingly workflow mastery.

Transition: name the broader principle: verbs, not nouns.

## Slide 17 — Verbs, Not Nouns

Use this as a teaching philosophy slide. Nouns are model names, tools, RAG, MCP, agents, benchmarks. They matter, but they do not produce mastery.

Verbs are the craft: specify, decompose, delegate, inspect, test, revise, document, reuse. Investing has the same structure: edge lives in weighing evidence, forming variant views, sizing risk, monitoring catalysts, and revising.

Transition: now show that this is not limited to AI-native software companies.

## Slide 18 — Goldman Sachs

Position Goldman as a regulated-incumbent signal, not a full success story. If a compliance-heavy Wall Street firm is piloting autonomous engineering agents, the conversation has moved from "is this too early?" to "how do we govern it?"

Connect to Dymon: PM workflows also need specification, permissioning, provenance, review, and persistent artifacts.

Transition: synthesize what to copy and what not to copy.

## Slide 19 — What To Copy, What Not To Copy

Make the contrast simple. From AI-native companies, copy workflow speed, tight feedback loops, and reusable artifacts. From finance incumbents, copy governance discipline, review paths, permissioning, and auditability.

The Dymon answer is not "copy Goldman" or "copy Cursor." It is to redesign research workflows with AI-native speed and finance-grade source discipline.

Transition: move from finance to broader organizational adoption signals.

## Slide 20 — Shopify

Use Shopify as an example of AI becoming a management baseline. The key move is not a tool rollout; it is changing resource allocation and performance expectations.

Frame the management question: before adding people or resources, ask what the team should look like if AI teammates were already part of the workflow.

Transition: Block is the more radical version of the same pattern.

## Slide 21 — Block

Be careful not to make this only about layoffs. The deeper signal is organizational redesign: hierarchy as information routing is being replaced by an intelligence layer.

Explain the world-model idea: if the organization has shared company and customer models that AI tools can read and update, coordination changes. Managers become mentors, guides, and domain experts at the edge.

Land the urgency: the risk is treating a paradigm shift like a normal software rollout.

Transition: synthesize the evidence.

## Slide 22 — Synthesis

Walk down the table quickly and avoid retelling each case. The pattern is the point: Cursor shows workflow capture, Anthropic shows frontier-team practice, Goldman shows governed deployment, Shopify shows management expectation, Block shows org-design pressure.

The takeaway is that the gap opens at the speed of workflow and organization redesign, not at the speed of ordinary enterprise software adoption.

Transition: translate the pattern into investment work.

## Slide 23 — Part III

Set up the PM-specific argument. AI must support judgment, not just information retrieval.

The bottleneck for PMs is not getting more text. It is transforming noisy information into differentiated, tradeable judgment.

Transition: break down investment work mechanically.

## Slide 24 — Investment Work, Mechanically

Use the chain: information, signal, mechanism, judgment, position. AI that only summarizes operates at the least scarce part of the chain.

Make the PM implication explicit: the higher-value question is how AI helps with source weighting, causal mechanism, timing, sizing, monitoring, and revision.

Transition: connect this to efficient markets and the meaning of edge.

## Slide 25 — Finance Education Reflection

This is where you can briefly reference your economics/finance background. Keep it modest: the textbook model is useful, but people often misread it.

The practical point is that shared information does not imply identical beliefs, timing, action thresholds, or position sizing. Edge lives in the transformation layer.

Transition: from efficient markets to contrarian thinking.

## Slide 26 — Contrarian View

Lead with the distinction: best practice is the efficient market; you get paid when you are right and consensus is wrong.

Use the Naval framing: contrarian does not mean reflexively disagreeing. It means independent reasoning from first principles under pressure to conform.

Use the NFX image to make the visual point: most best practices sit in the center of the distribution; the rare value is finding the correct tail case and turning it into a tradeable decision.

Transition: define where the edge actually lives.

## Slide 27 — Where The Edge Lives

This slide operationalizes contrarian thinking. It is not disagreement as personality; it is a structured difference in source weighting, mechanism, timing, and action standard.

Connect each row to AI: a generic model tends to flatten sources, list bull/bear stories, and produce balanced prose. PM context tells AI what deserves weight and what action standard matters.

Transition: therefore Deep Research alone is insufficient.

## Slide 28 — Naked Search Is Not Enough

Explain that Deep Research is useful for coverage, but coverage is not judgment. It can produce a comprehensive consensus view and a polished summary, but it usually stays near the information layer.

Tie this back to slide 24: the least scarce part of the chain is information. The more scarce parts are filter, mechanism, decision, and action. Context-aware research AI is different because it operates inside the PM's context architecture: source hierarchy, variant lens, mechanisms, failure modes, and action standards.

The line to land: your context architecture is the competitive edge. It lets AI help with the scarce parts of investment work, not just summarize the least scarce part.

Transition: define that context architecture.

## Slide 29 — Context Architecture

Make clear that context is not a document dump. For a PM, context is the operating system of judgment.

Walk through the four layers: source hierarchy, world model, variant lens, action standard. The output changes only when these layers are explicit enough for the AI to inherit them.

Transition: explain why this should begin with individuals, not a top-down knowledge base.

## Slide 30 — Why Individual First

Contrast the two approaches. Top-down knowledge bases often become expensive document repositories disconnected from desk behavior.

Individual-first starts with one valuable workflow and encodes the PM's actual judgment pattern. Shared infrastructure should emerge from useful work, not precede it as a theoretical architecture.

Transition: show how personal context compounds into team infrastructure.

## Slide 31 — Compounding Path

Walk the path from PM context file to workflow skill, reusable assets, pod defaults, and team layer.

The important claim is sequencing: personal context should prove useful in live work before it is promoted into shared infrastructure.

Transition: return to the live demo.

## Slide 32 — Part IV

Remind the room that the demo has been running in the background. This section is not a performance; it is an inspection.

The question is what each operating model produced after the same head start.

Transition: compare Run A and Run B.

## Slide 33 — Demo Design

Explain Run A and Run B cleanly. Run A tests the best off-the-shelf research assistant mode. Run B tests an agentic workflow with source hierarchy, tools, data, code execution, and a memo spec.

Say what you are not evaluating: prose polish alone. Say what you are evaluating: evidence, calculations, gaps, artifacts, and reuse.

Transition: use explicit evaluation criteria.

## Slide 34 — Evaluation Criteria

Use this as a checklist for the demo output. Ask the room to judge source discipline, variant perception, mechanism, execution, and persistence.

The strongest line: decision usefulness matters more than prose quality. A polished report that does not help decide is not enough.

Transition: connect the demo to the Dymon-specific course.

## Slide 35 — The Dymon Frame

This is the bridge from argument to implementation. The next step is to distill Dymon's investment frame, starting with Jay's judgment patterns, into reusable context.

Explain the before/after: without context, the model is a well-read generalist. With Jay's frame, it inherits source hierarchy, mechanisms, failure modes, and decision criteria. After enablement, each PM can build their own version and contribute reusable pieces.

Transition: now introduce the course as the path to make this habit.

## Slide 36 — Part V

State that the course is not three disconnected workshops. It is one real investment task upgraded three times.

The phrase to land: the course turns the thesis into a desk-level operating habit.

Transition: start with the first wedge before the course.

## Slide 37 — The First Wedge

Explain the pre-course collaboration with Jay. Start with a real task, produce the naked Deep Research version, then inject Jay's frame and iterate.

The result is not just prep work. It creates a classroom proof object: the room can inspect the before/after and see that the difference comes from judgment context, not generic AI enthusiasm.

Transition: show the three-session spiral.

## Slide 38 — Course Design

Explain the spiral: same task, three upgrades. Session 1 does it well once. Session 2 packages it as context and skill. Session 3 turns it into a loop with hypothesis verification and scheduled delegation.

Emphasize intentional repetition. The goal is not to learn nouns; it is to practice the verbs until the method becomes natural.

Transition: define the capability gaps the course closes.

## Slide 39 — PM AI Fluency Gaps

Walk through the five gaps quickly. The difference between average and strong AI use is not a favorite model; it is usable output, quality diagnosis, full-task delegation, compounding memory, and new capability.

For Dymon, the most important gaps are probably 2, 3, and 4: diagnosing failure, delegating full tasks, and making experience compound.

Transition: show what Dymon leaves with.

## Slide 40 — What Dymon Leaves With

Make this concrete. The deliverable is not attendance; it is a first operating layer.

Walk through the six outputs: Dymon Axiom Library, personal PM context files, reusable research skills, periodic execution scaffolding, team context architecture, and three-month support.

The final point is important: the target is not frontier researcher capability. It is everyday AI fluency at the level of strong employees inside first-tier AI organizations.

Transition: now explain Jay's Excel analogy because it makes the learning path intuitive.

## Slide 41 — AI Is The New Excel

Introduce the analogy explicitly: Jay's point is not that AI and Excel look alike. The point is that both are general-purpose work environments that become professional leverage after people learn the craft.

Talk through the three meanings. First, table stakes: AI fluency is becoming a baseline skill. Second, learnable: business people can learn it through real work. Third, deep craft: easy to start does not mean easy to master.

Transition: translate the analogy into PM behavior.

## Slide 42 — What It Means For PMs

Use the table to make the analogy actionable. Everyone can open a sheet, but strong operators model and audit assumptions. Everyone can ask AI questions, but serious PMs specify outcomes, context, evidence standards, and decision criteria.

Training matters because it shortens the path from casual use to operating skill. Ongoing support matters because mastery comes from repeated use, diagnosing failures, and preserving what worked.

Transition: close with the decision question.

## Slide 43 — Closing

Close by reframing the decision. The question is no longer whether Dymon should use AI. That is too broad and already answered.

The real question is which research workflows should become buildable, inspectable, and compounding. This points naturally to the proposed course: start with real PM work, encode judgment, and turn repeated tasks into systems.
