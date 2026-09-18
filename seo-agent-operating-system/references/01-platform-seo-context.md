# Platform SEO and Content Context

## Purpose

Store generic platform rules that apply across clients. Do not place client-specific facts here.

## Context hierarchy

Use:

`Platform -> Agency override -> Client -> Property -> Asset/Activity/Publisher`

Lower layers may narrow or override only where the higher-level rule allows it.

## Platform default rule groups

Capture approved defaults for:

- Supported SEO/content/off-page activities
- Approved/free/paid tools and integrations

Centralize approved tool roles and operating processes in [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md). Downstream modules may narrow tool usage but should not redefine the tool's core role without an approved override.
- Keyword data-source priority
- Content research/source reliability
- Content approval and publishing authority
- Content PASS/WARNING/BLOCK validation
- Backlink qualification thresholds
- Backlink commercial classification
- Capacity/benchmark planning
- Human approval points
- Rejection/failure reason taxonomy
- Naming conventions
- Output schemas
- Search/publisher policy boundaries
- Escalation conditions
- Feedback fields

## Current v1 defaults

Use these modules unless an approved lower layer overrides them:

- Content workflow: [54-content-production-workflow.md](54-content-production-workflow.md)
- Content governance: [55-content-rulebook-governance.md](55-content-rulebook-governance.md)
- Content research/source reliability: [57-content-source-research-reliability.md](57-content-source-research-reliability.md)
- Content validation: [87-content-validation-gate.md](87-content-validation-gate.md)
- Human/confidence governance: [89-content-human-confidence-governance.md](89-content-human-confidence-governance.md)
- Keyword source priority: [16-keyword-data-source-priority.md](16-keyword-data-source-priority.md)
- Keyword APIs/integrations: [17-keyword-api-integration.md](17-keyword-api-integration.md)
- Backlink qualification: [32-backlink-qualification.md](32-backlink-qualification.md)
- Commercial/access classification: [42-backlink-commercial-classification.md](42-backlink-commercial-classification.md)
- Capacity benchmarks: [43-backlink-benchmark-capacity.md](43-backlink-benchmark-capacity.md)
- Historical backlink memory: [44-historical-backlink-database.md](44-historical-backlink-database.md)

## Golden-rule summary

Enforce:

- Never fabricate.
- Evidence before recommendation.
- Business relevance and user value before SEO volume/keyword density.
- Retrieve before generating.
- Recommend before executing when judgment is required.
- Human expertise handles ambiguity.
- Important AI decisions must be explainable.
- External actions must be auditable.
- Quality must not be sacrificed for volume.

Use [55-content-rulebook-governance.md](55-content-rulebook-governance.md) for the full content rule set.

## Metric/source rule

For every metric store its source/date because values differ by provider.

Do not compare differently defined metrics as if identical.

## Decision rule format

Represent important rules as :

`IF <condition> THEN <action> DBECAUSE <reason> ELSE <next check>`

## Human control

Keep humans responsible for:

- New thresholds/rules
- Strategy changes
- Exceptions
- Risky/paid link approvals where configured
- Client positioning/claims
- Sensitive publisher relationships
- High-risk content/external actions
- Final publishing when configured
- Global rule changes from feedback

## Handoff

Load client/property context before client-specific recommendations or content generation.
