# Dymon Asia AI Enablement Briefing

Private working repository for the Dymon Asia AI enablement briefing deck and speaker notes.

Live deck:

- Production: https://dymon-asia-ai-enablement.vercel.app
- Speaker notes: https://dymon-asia-ai-enablement.vercel.app/speaker-notes.md

## What This Is

This project is a static HTML presentation for a Dymon Asia briefing on AI enablement for investment research and portfolio manager workflows.

The deck argues that the meaningful shift is not "better chatbot usage." It is the move from chat-based answers to agentic research workflows, persistent context infrastructure, and PM-level judgment systems.

The final deck is `v11 course briefing` and contains 43 slides.

## Audience

The deck is written for Dymon Asia portfolio managers and senior investment professionals. The intended audience is financially sophisticated, practical, and skeptical of generic AI hype. The tone is therefore structured, direct, and focused on workflow, judgment, governance, and implementation.

## Core Thesis

For PMs, AI leverage begins when judgment becomes infrastructure.

Answers:

- Chat gives a useful response.
- The PM still carries context, verifies claims, and repeats the work next time.

Workflows:

- Agentic AI searches, computes, cites, checks, and leaves behind inspectable artifacts.
- The human becomes specifier, reviewer, and judge.

Context:

- Dymon's source hierarchy, variant lens, and decision standards become reusable operating assets.
- The deck's throughline is the move from AI as a chat product to AI as a research operating system for PM judgment.

## Key Narrative Arc

1. Start a live research question in the room.
2. Explain why AI is a new interface to compute, not merely a better chatbot.
3. Show market evidence from AI-native firms and incumbents.
4. Translate the shift into portfolio manager work.
5. Return to the demo and judge outputs by decision usefulness.
6. Introduce the Dymon-specific course architecture.
7. Close with Jay's "AI is the new Excel" analogy.

## Important Files

- `index.html`  
  The presentation deck. It is self-contained HTML/CSS/JS with local assets.

- `speaker-notes.md`  
  Page-by-page speaker notes for all 43 slides. These are designed for live delivery, not as a transcript.

- `docs/project-summary.md`  
  A summary of the project, deck logic, major decisions, and final conclusions.

- `assets/`  
  Logos and visual assets used by the deck.

- `assets/INDEX.md`  
  Canonical source notes for brand assets. Use this before replacing logos; the Superlinear Academy lockup should come from the 2026 brand identity package, not the retired pre-2026 SVG.

- `vercel.json`  
  Static deployment config.

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

## Confidentiality

This repository should remain private. It contains client-specific positioning, course design, and Dymon-related enablement material.
