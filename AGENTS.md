# Griddy Prompt Library Agent Guide

## Prompt and Dataset Validation

- Keep prompt-to-dataset links resolvable, CSV fixtures parseable, and referenced columns present. Validate formulas, thresholds, required context, and as-of dates when a prompt's answer depends on them.
- Prefer deterministic structural validators and small oracle cases. Do not add live-model snapshots, provider-response theater, or tests that merely prove a Markdown or CSV file exists.
- A regression check must fail for the broken prompt, link, schema, or computation it claims to protect. Do not silently skip missing datasets or accept unrelated outcomes.
- Avoid duplicate checks at the same boundary and failure mode. Preserve intentional cross-layer coverage when a content validator and an end-to-end prompt evaluation catch different failures.
- When changing a prompt or dataset, update any existing paired validation in the same change; add a deterministic validator when the change introduces or modifies a machine-checkable invariant. Test counts and coverage are not targets.
