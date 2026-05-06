# Project Summary: Dymon Asia AI Enablement Briefing

## Current Output

This project contains a 29-slide HTML briefing deck for Dymon Asia, plus page-by-page speaker notes.

Production URL:

https://dymon-asia-ai-enablement.vercel.app

Speaker notes:

https://dymon-asia-ai-enablement.vercel.app/speaker-notes.md

## Current Goal

The deck is designed for a practical, senior, impatient Dymon Asia audience. It avoids generic AI hype and opens with a higher-level frame:

AI is becoming the third interface between humans and compute.

For PMs, the practical skill is learning to use natural language to dispatch compute, tools, context, and follow-through around real investment work.

## Current Thesis

Natural language is becoming a dispatch layer for PM work.

Daily work is the wedge, not the ceiling. The immediate measurable win is fewer missed actions, missed opportunities, and lost context. The deeper skill is learning how to command compute and turn repeated work into compounding systems.

The model already knows a large amount of public information. The valuable layer is the operating system around the model:

- what judgment gets encoded;
- what context gets retrieved;
- what action gets delegated;
- what artifacts get created;
- what follow-up persists into future work.

## Narrative Structure

1. **Gates / GUI opening**
   The deck starts with the Bill Gates question because it engages the room and frames AI as an interface shift, not just another information tool.

2. **Third interface**
   GUI changed who could operate compute. AI changes what can be commanded by natural language.

3. **PM implication**
   For PMs, the new skill is commanding work that used to require manual coordination: judgment, retrieval, drafting, scheduling, notification, artifact creation, and memory.

4. **Daily-work wedge**
   Actions, opportunities, and context are execution-level details, but they are the right training wedge because they repeat every day and make value leakage visible.

5. **Operating model**
   Chat keeps the human as middleware. Agentic workflows require specification, retrieval, action, inspection, and persistence.

6. **Market signal**
   Cursor and Claude Code show the lead-market pattern: production-grade agentic work built around files, tools, tests, and review loops. Goldman Sachs, Shopify, and Block show that incumbents are also turning AI into an operating rule, with governance and supervision.

7. **Course capability**
   The course section now comes immediately after the market signal. It explains the five gaps between chat use and real leverage, the verb-first learning method, and Jay's Excel analogy: AI is table stakes, learnable, and still a deep craft.

8. **PM translation**
   Investment work moves from information to signal, mechanism, judgment, and action. AI needs context to assist the scarce parts of that chain.

9. **Contrarian judgment**
   The deck keeps the Naval/NFX contrarian framing, but removes the longer efficient-market detour. The point is to sharpen correct contrarian judgment, not to celebrate disagreement.

10. **Onboarding process review demo**
   Yan owns the live demo. The deck now uses one overview slide to tell the audience what to watch: language dispatching tools, context changing output, and work leaving memory.

## Demo Design

The current live demo uses an internal onboarding process review transcript. Yan will present the mechanics; the deck keeps only one "what to watch" slide so the main presentation does not duplicate the demo.

### Beat 1: Capture

Yan asks AI to summarize the meeting and identify action items.

This starts with familiar AI behavior: meeting summary and action extraction.

### Beat 2: Execute

Yan gives a one-sentence instruction:

> Action item 1: align with Priya in person. Find a mutual 30-minute slot next week, send the invite, and include the background note.

The agent reads calendars, creates the invite, drafts/sends the background email, and pushes a completion notification.

The point is hands-off execution across tools.

### Beat 3: Artifact

Yan asks for a one-pager for Sarah using the Tom onboarding case, ABC Capital KYC, and SOP 4.2.

The agent retrieves cross-document context, cites source links, creates a Google Doc, shares it with Sarah, sends a short email, and records the artifact.

### Beat 4: Context Ledger

The transcript and generated artifacts become structured context rows:

- people;
- source;
- topic;
- owner;
- linked context IDs;
- derived artifact;
- follow-up status;
- retrieval hints.

The ledger can be opened in Excel/CSV and filtered or pivoted to inspect themes such as China energy or Indonesian coal. The key aha: repeated ideas and missed artifacts become visible.

## Why The Demo Changed

The previous plan compared generic AI output with context-aware AI output on the same live research question.

That created two problems:

- the audience would need to read and evaluate two long reports in real time;
- the comparison depended too much on domain judgment and could invite disagreement about the better answer.

The new demo lowers cognitive load. The room can see action execution, cross-document handoff, and context capture directly. The deck tells the audience to watch for the operating habit: specify, delegate, inspect, persist.

## Current Slide Structure

1. Cover
2. Gates opening question
3. GUI reveal / third-interface frame
4. PM implication
5. About Superlinear
6. Narrative map
7. Part I: dispatch layer
8. Third interface table
9. Missing operating model
10. Daily-work wedge
11. Chat as ceiling
12. Agentic operating model
13. Part II: market signal
14. Cursor / Anysphere
15. Anthropic / Claude
16. Enterprise signal
17. Part III: course capability
18. Five gaps
19. Verbs, not nouns
20. AI is the new Excel
21. Course design
22. Course outcome
23. Part IV: PM translation
24. Investment work mechanically
25. Contrarian view
26. Context moves AI up the chain
27. Context architecture
28. What to watch in Yan's demo
29. Closing

## Delivery Notes

The speaker notes live in `speaker-notes.md`.

Recommended delivery style:

- high-level frame first;
- direct and fast-paced;
- light on generic AI importance arguments;
- explicit about what each example proves;
- practical once the third-interface frame is established;
- careful to distinguish live demo output from mocked accumulated context.

## Archive

The previous version before the onboarding-demo rewrite is archived locally as:

```text
archive/pre-onboarding-demo-20260505
```

The version before the third-interface opening rewrite is in git history at:

```text
861c825 Sharpen Dymon deck narrative
```
