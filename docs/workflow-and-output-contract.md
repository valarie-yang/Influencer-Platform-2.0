# Workflow and output contract

## State model

    PERSONA_CAPTURED
      → ANALYSIS_READY
      → TOPICS_PLANNED
      → SCRIPT_DRAFTED
      → PRODUCTION_PLANNED
      → PUBLISHING_TRACKED

A user may revisit and edit an earlier state. Downstream outputs should be regenerated or marked stale when their inputs change.

## Structured outputs

The workflow should treat AI results as objects rather than an unbounded text blob:

- PersonaAnalysis: audience, positioning, content pillars, tone, constraints.
- TopicPlan: topic, rationale, target week, hook, expected format.
- VideoScript: title, hook, beats, call to action, duration.
- ProductionPlan: shot list, B-roll, subtitle focus, editing rhythm.
- PublishingTask: platform, planned date, status, owner, notes.

## Error and empty states

Every step should define loading, empty, invalid-output, retry, and success states. A failed provider response must not silently overwrite a previously reviewed output.
