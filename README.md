# Dymon Asia AI Enablement Briefing

Working repository for the Dymon Asia AI enablement briefing deck and speaker notes.

Private hosted copy:

- Protected preview: https://dymon-asia-ai-enablement-2zadqsi7g-yuzhengs-projects-9ae1e000.vercel.app
- Speaker notes: append `/speaker-notes.md` to the protected preview URL

This repository and its hosted deck are restricted client materials. A separate contract permits purpose-limited private sharing with an intended counterparty; it does not permit public promotion, indexing, or treating Dymon as public client proof. Create a revocable Vercel Shareable Link for each approved sharing context instead of restoring a public production alias.

## What This Is

This project is a static HTML presentation for a Dymon Asia briefing on AI enablement for investment research and portfolio manager workflows.

The current deck argues that AI is the third interface between humans and compute. For PMs, the practical skill is learning to use natural language to dispatch compute, tools, context, and follow-through around real investment work.

The current deck is `PM AI Fluency Training` and contains 29 slides.

## Audience

The deck is written for Dymon Asia portfolio managers and senior investment professionals. The intended audience is financially sophisticated, practical, and impatient with generic AI hype. The tone is direct, structured, and focused on workflow, judgment, governance, and implementation.

## Core Thesis

Natural language is becoming a new dispatch layer for PM work.

Daily work is the wedge, not the ceiling:

Actions:

- Action items move from transcript to calendar, email, owner, and follow-up.
- The human does not have to be middleware across every tool.

Opportunities:

- Repeated themes across meetings, notes, and calls become visible.
- The system can distinguish a mentioned theme from a derived artifact.

Context:

- Useful work leaves a trace: people, source links, decisions, tags, owners, and reusable patterns.
- Context infrastructure becomes the operating system around PM judgment.

## Key Narrative Arc

1. Use the Gates GUI question to make the interface shift concrete.
2. Define AI as the third interface between humans and compute.
3. Translate the shift into PM work: judgment can now command compute, tools, artifacts, and memory.
4. Explain daily work as the fastest wedge for learning the craft.
5. Show market signals from AI-native teams and governed incumbents.
6. Explain the course capability gap: five gaps, verb-first learning, and Jay's Excel analogy.
7. Translate the trained capability into PM judgment workflow.
8. Set up what to watch in Yan's onboarding process review demo without duplicating his demo walkthrough.
9. Close on operational compounding.

## Demo Design

Yan's live demo uses an internal onboarding process review transcript, not a market research question. The deck only gives the audience one overview slide for what to watch.

The three beats:

- Meeting transcript -> summary and action items.
- One instruction -> calendar invite, background email, and owner notification.
- Follow-up instruction -> cross-document one-pager, Google Doc, share/email, and context ledger.

The demo is judged by captured work, not prose quality:

- fewer missed actions;
- fewer missed opportunities;
- less lost context;
- hands-off execution across tools;
- transferable course method.
- the habit being trained: specify, delegate, inspect, persist.

## Important Files

- `index.html`
  The presentation deck. It is self-contained HTML/CSS/JS with local assets.

- `speaker-notes.md`
  Page-by-page speaker notes for all 29 slides. These are designed for live delivery, not as a transcript.

- `docs/project-summary.md`
  Summary of the project, deck logic, major decisions, and current conclusions.

- `Dymon Asia Pitch Demo_ Context Infrastructure-v2.md`
  Current demo strategy and live-flow design.

- `Dymon Asia Pitch Demo_ Context Infrastructure-artifact-design.md`
  Artifact, transcript, and context ledger design for the demo.

- `assets/INDEX.md`
  Canonical source notes for brand assets. Use this before replacing logos; the Superlinear Academy lockup should come from the 2026 brand identity package.

## Running Locally

The deck can be opened directly in a browser:

```bash
open index.html
```

Or served from the project directory:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

Navigation:

- Arrow keys / PageUp / PageDown
- Home / End
- Click right side to advance
- Click left side to go back
- Touch swipe on mobile
- Press `S` in the main deck to open a separate presenter-notes window
- Use the presenter-notes window for timer, speaker script, and slide controls
- Press `Esc` in the presenter window to close it

## Deployment

The project is hosted as a Vercel Preview protected by Vercel Authentication. Do not deploy it to Production or attach a public custom domain.

```bash
vercel deploy --target=preview --yes
```

Before sharing externally, verify the intended recipient and contract scope, then create a revocable Shareable Link from the protected deployment. Do not send the raw Preview URL: without the bypass link it is accessible only to the Vercel team.

## Archive

The pre-onboarding-demo version is archived locally as:

```text
archive/pre-onboarding-demo-20260505
```
