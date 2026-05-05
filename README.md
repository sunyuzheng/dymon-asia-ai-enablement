# Dymon Asia AI Enablement Briefing

Working repository for the Dymon Asia AI enablement briefing deck and speaker notes.

Live deck:

- Production: https://dymon-asia-ai-enablement.vercel.app
- Speaker notes: https://dymon-asia-ai-enablement.vercel.app/speaker-notes.md

## What This Is

This project is a static HTML presentation for a Dymon Asia briefing on AI enablement for investment research and portfolio manager workflows.

The current deck argues that the meaningful shift is operational: AI should help PMs capture missed actions, missed opportunities, and missed context, then turn daily work into a compounding context system.

The current deck is `v12 course briefing` and contains 36 slides.

## Audience

The deck is written for Dymon Asia portfolio managers and senior investment professionals. The intended audience is financially sophisticated, practical, and impatient with generic AI hype. The tone is direct, structured, and focused on workflow, judgment, governance, and implementation.

## Core Thesis

AI leverage for PMs begins when daily work stops leaking value.

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

1. Frame the leak: actions, opportunities, and context disappear in ordinary daily work.
2. Explain the operating shift from chat to natural-language dispatch across tools.
3. Show market signals from AI-native firms and governed incumbents.
4. Translate the shift into PM judgment and action.
5. Run Yan's onboarding process review demo in three beats: capture, execute, compound.
6. Explain how the course trains Dymon PMs to build similar workflows.
7. Close with Jay's "AI is the new Excel" learning frame.

## Demo Design

The live demo uses an internal onboarding process review transcript, not a market research question.

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

## Important Files

- `index.html`
  The presentation deck. It is self-contained HTML/CSS/JS with local assets.

- `speaker-notes.md`
  Page-by-page speaker notes for all 36 slides. These are designed for live delivery, not as a transcript.

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

## Deployment

The project is deployed on Vercel:

```bash
vercel deploy --prod --yes
```

The current production alias is:

```text
https://dymon-asia-ai-enablement.vercel.app
```

## Archive

The pre-onboarding-demo version is archived locally as:

```text
archive/pre-onboarding-demo-20260505
```
