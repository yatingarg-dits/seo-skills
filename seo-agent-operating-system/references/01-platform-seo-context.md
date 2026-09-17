# Platform SEO Context

## Purpose

Store generic platform SEO rules that apply across clients. Do not place client-specific facts here.

## Context hierarchy

Use:

`Platform -> Agency override -> Client -> Property -> Activity/Publisher`

Lower layers may narrow or override only where the higher-level rule allows it.

## Platform default rule groups

Capture approved defaults for:

- Supported SEO/off-page activities
- Approved/free/paid tools and integrations
- Keyword data-source priority
- Backlink qualification thresholds
- Backlink commercial classification
- Capacity/benchmark planning
- Human approval points
- Rejection reason taxonomy
- Naming conventions
- Output schemas
- Search/publisher policy boundaries
- Escalation conditions
- Feedback fields

## Current v1 defaults

Use these modules as the current platform defaults unless an approved lower layer overrides them:

- Keyword source priority: [16-keyword-data-source-priority.md](16-keyword-data-source-priority.md)
- Keyword APIs/integrations: [17-keyword-api-integration.md](17-keyword-api-integration.md)
- Backlink qualification: [32-backlink-qualification.md](32-backlink-qualification.md)
- Commercial/access classification: [42-backlink-commercial-classification.md](42-backlink-commercial-classification.md)
- Capacity benchmarks: [43-backlink-benchmark-capacity.md](43-backlink-benchmark-capacity.md)
- Historical backlink memory: [44-historical-backlink-database.md](44-historical-backlink-database.md)

## Metric/source rule

For every metric store its source/date because values differ by provider.

Examples:

- Search volume + source
- Organic difficulty + provider
- Paid competition + Google Ads source
- DA/PA/Spam Score + source
- Organic traffic estimate + provider/date
- Rank + source/date/location/device when relevant

Do not compare differently defined metrics as if identical.

## Decision rule format

Represent important rules as:

`IF <condition> THEN <action> BECAUSE <reason> ELSE <next check>`

## Human control

Keep humans responsible for:

- New thresholds
- Strategy changes
- Exceptions
- Risky/paid link approvals where configured
- Client positioning/claims
- Sensitive publisher relationships
- Global rule changes from feedback

## Handoff

Load client/property context before client-specific recommendations.
