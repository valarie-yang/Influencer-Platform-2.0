# AI-Assisted Influencer Content Operations Platform

A runnable workflow prototype that turns a creator persona into structured content planning, scripts, production tasks, and publishing operations.

**Status:** Runnable prototype with deterministic Mock AI and browser-local persistence. No production model quality or live social-platform integration is claimed.

**Role lens:** AI Product Management · Workflow Design · Rapid Prototyping · Frontend Product Delivery

## Six-step workflow

    Persona
      ↓
    AI Analysis
      ↓
    Monthly Topics
      ↓
    Video Script
      ↓
    Production Plan
      ↓
    Publishing Board

The product closes the gap between “generate some copy” and the operational work required to produce, review, schedule, and publish content.

## What the prototype demonstrates

- persona and audience input;
- structured content pillars and audience analysis;
- four-week topic planning;
- 60–90 second script drafts;
- candidate titles and publishing copy;
- shot list, B-roll, subtitle focus, and editing rhythm;
- publishing board, task completion, and progress calculation;
- loading, empty, disabled, success, and recovery states;
- responsive/mobile navigation;
- browser-local persistence and demo-state recovery.

## AI boundary

The public demo uses deterministic Mock AI responses so the workflow is reproducible and easy to review. It does not claim production LLM quality, real creator-growth results, or live platform publishing.

A future model integration would require a provider abstraction, structured-output validation, retries and fallback, content-safety checks, user editing/approval, and observable failure handling.

## Product decisions

- Make the six-step chain visible so users understand how an idea becomes an executable plan.
- Keep AI outputs structured so each result can be edited and reused by the next step.
- Use deterministic fixtures to validate information architecture and state transitions before model quality is introduced.
- Treat publishing as an operational workflow with tasks and status, not as an automatic side effect.

## Evaluation plan

Current evaluation is based on deterministic fixture walkthroughs and local persistence checks. Production user metrics have not been collected.

Useful future metrics include time from persona input to first usable plan, six-step completion rate, percentage of generated fields requiring edits, script acceptance/edit distance, task completion rate, mobile task success, and persistence recovery success.

## Repository map

- [docs/product-brief.md](docs/product-brief.md) — target users, job to be done, and product scope
- [docs/workflow-and-output-contract.md](docs/workflow-and-output-contract.md) — six-step state model and structured outputs
- [docs/model-integration-plan.md](docs/model-integration-plan.md) — path from Mock AI to a real provider
- [docs/evaluation-and-limitations.md](docs/evaluation-and-limitations.md) — current evidence and non-production boundary

> Public portfolio material should use fictional creator identities, synthetic campaign information, and assets that are owned or licensed for publication.
