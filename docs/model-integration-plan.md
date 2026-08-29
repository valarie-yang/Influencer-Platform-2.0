# Model integration plan

The current public demo uses deterministic Mock AI. A real provider integration should be introduced behind a stable application contract.

## Required controls

- provider and model configuration separated from UI state;
- schema validation for every output object;
- timeout, retry, and fallback behavior;
- content-safety and policy checks;
- user edit and approval before publishing;
- request and response observability without storing unnecessary personal data;
- fixture-based regression evaluation.

## Suggested rollout

1. Keep Mock AI as a deterministic test provider.
2. Add a sandbox provider with synthetic creator data.
3. Compare structured-output validity and edit rates.
4. Run safety and failure-case tests.
5. Only then consider a controlled production pilot.
