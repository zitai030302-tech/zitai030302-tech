# Development notes

The priority is to finish the existing projects before starting another benchmark repository. This is a working sequence, not a list of completed features.

## First two weeks

- Publish clean FlexResearch and NPU snapshots as separate repositories; retain the original private archives and team authorship.
- Verify commands from fresh environments and keep the short README entry points.
- Run the BioZ subject-generalization benchmark on the original feature table. Record subject/session groups, feature selection, preprocessing, and missingness. Keep generated-cohort checks separate from real-data metrics.
- Build and run the QuantDesk image on a Docker host. Add an execution example long enough to exercise actual fills and report its data provenance.

## Weeks three and four

- Add a public daily-panel adapter for AlphaResearchLab with adjustment and universe history.
- Record data hashes and available-at timestamps. Reject duplicated rows, missing dates, and undocumented corporate-action handling.
- Freeze a small candidate batch before a fresh holdout run. Compare costs and turnover; preserve failed or redundant ideas.
- Move AlphaResearchLab to its own repository only after the input and ledger interfaces have settled.

## Weeks five and six

- Add a bounded model adapter that produces typed proposal JSON. Save prompts, model settings, responses, validation failures, latency, and cost.
- Compare it against the handwritten baseline under the same frozen data and budget.
- Extend FlexResearch evaluation with a small set of documented failure cases found during actual use. Existing golden cases are a starting point; live-model performance requires its own run.

## Weeks seven and eight

- Write one short technical note per project: a concrete failure, the repair, and a reproducible before/after check.
- Prepare a three-minute demo and a one-page project explanation for interviews.
- Choose the next project based on a measured gap. A separate AgentEvalLab is useful only if the existing evaluation needs justify it.

## Evidence to keep

Use real commits and the CI result from the commit being cited. Do not backdate work or inflate generated-data performance into market, medical, hardware, or platform claims. Project README pages should explain the task and one runnable example before listing implementation details.
