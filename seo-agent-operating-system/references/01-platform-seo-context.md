# Platform SEO Context

## Purpose

Store generic agency/platform SEO rules that apply across clients. Do not place client-specific facts here.

## Required platform rules

Capture approved rules for:

- Supported SEO activities
- Approved/free/paid tools
- Allowed data sources
- Minimum evidence required before a decision
- Metric definitions and source priority
- Human approval points
- Rejection reason taxonomy
- Naming conventions
- Output schemas
- Compliance or link-building boundaries
- Escalation conditions
- Feedback fields

## Context separation

Use this hierarchy:

`Platform -> Agency override -> Client -> Property`

If a lower layer conflicts with a higher layer, do not assume which wins unless an approved override rule exists.

Return `NEEDS_HUMAN_RULE` when conflict resolution is undefined.

## Tool/data rule

For every metric store the source, because values differ by provider.

Examples:

- Search volume + source
- Organic difficulty + source
- Paid competition + source
- DA/PA/Spam Score + source
- Organic traffic estimate + source
- Rank + source/date/location/device when relevant

Do not compare differently defined metrics as if they are identical.

## Decision rule format

Represent important rules as:

`IF <condition> THEN <action> BECAUSE <reason> ELSE <next check>`

Example structure only:

`IF site is irrelevant to client niche THEN reject BECAUSE audience mismatch ELSE continue qualification.`

Do not invent numeric cutoffs that the team has not approved.

## Human control

Keep humans responsible for:

- Strategy changes
- New thresholds
- Exceptions
- Final approval where configured
- Risky link decisions
- Client-positioning changes
- Sensitive publisher relationships

## Handoff

Load [04-property-context.md](04-property-context.md) before producing client-specific recommendations.
