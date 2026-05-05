# Project Summary: Dymon Asia AI Enablement Briefing

## Current Output

This project contains a 36-slide HTML briefing deck for Dymon Asia, plus page-by-page speaker notes.

Production URL:

https://dymon-asia-ai-enablement.vercel.app

Speaker notes:

https://dymon-asia-ai-enablement.vercel.app/speaker-notes.md

## Current Goal

The deck is designed for a practical, senior, impatient Dymon Asia audience. It avoids generic AI hype and focuses on a concrete operating question:

How can PMs use AI to capture missed actions, missed opportunities, and missed context, then turn daily work into workflows that compound?

## Current Thesis

AI leverage for PMs begins when daily work stops leaking value.

The model already knows a large amount of public information. The valuable layer is the operating system around the model:

- what work gets captured;
- what action gets delegated;
- what context gets retrieved;
- what artifacts get created;
- what judgment and follow-up persist into future work.

## Narrative Structure

1. **Throughline**
   Daily PM work leaks value through missed actions, missed opportunities, and lost context.

2. **Demo preview**
   Yan will demonstrate one internal onboarding process review transcript turning into execution and memory.

3. **Operating shift**
   Natural language becomes valuable when it dispatches work across tools, not when it merely produces chat answers.

4. **Market signal**
   Cursor, Anthropic/Claude, Goldman Sachs, Shopify, and Block show the shift from tool adoption to workflow and operating-model redesign.

5. **PM translation**
   Investment work moves from information to signal, mechanism, judgment, and action. AI needs context to assist the scarce parts of that chain.

6. **Contrarian judgment**
   The deck keeps the Naval/NFX contrarian framing, but removes the longer efficient-market detour. The point is to sharpen correct contrarian judgment, not to celebrate disagreement.

7. **Onboarding process review demo**
   The old live market-question demo was replaced. The new demo has lower cognitive load and makes the value visible without asking the audience to compare two long reports.

8. **Course architecture**
   The course trains the craft: specify, retrieve, delegate, inspect, package, and rerun. It helps Dymon PMs build similar workflows around their own work.

9. **AI is the new Excel**
   Jay's analogy frames AI as a table-stakes business skill that is learnable, but deep enough to require practice, feedback, and reusable templates.

## Demo Design

The current live demo uses an internal onboarding process review transcript.

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

The new demo lowers cognitive load. The room can see action execution, cross-document handoff, and context capture directly.

## Current Slide Structure

1. Cover
2. Throughline
3. What this session is for
4. Demo preview
5. About Superlinear
6. Narrative map
7. Part I: operating shift
8. The third interface
9. The missing operating model
10. Chat as ceiling
11. Agentic operating model
12. Part II: market signal
13. Cursor / Anysphere
14. Anthropic / Claude
15. Verbs, not nouns
16. Goldman Sachs
17. Copy the right pattern
18. Shopify and Block
19. Part III: PM translation
20. Investment work mechanically
21. Contrarian view
22. Context moves AI up the chain
23. Context architecture
24. Part IV: demo
25. Demo setup
26. Demo beat 1: action to execution
27. Demo beat 2: action to artifact
28. Demo beat 3: work to memory
29. Demo standard
30. Part V: course architecture
31. Course wedge
32. Course design
33. PM AI fluency gaps
34. What Dymon leaves with
35. AI is the new Excel
36. Closing

## Delivery Notes

The speaker notes live in `speaker-notes.md`.

Recommended delivery style:

- direct;
- pragmatic;
- fast-paced;
- light on AI importance arguments;
- explicit about what each example proves;
- careful to distinguish live demo output from mocked accumulated context.

## Archive

The previous version before the onboarding-demo rewrite is archived locally as:

```text
archive/pre-onboarding-demo-20260505
```
