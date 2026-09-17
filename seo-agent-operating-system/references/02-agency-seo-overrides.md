# Agency SEO Overrides

## Purpose

Store agency-level rules that intentionally modify platform defaults across the agency's clients.

## Context hierarchy

`Platform -> Agency -> Client -> Property -> Activity/Publisher`

## Allowed override areas

Capture approved agency rules such as:

- Preferred keyword/SEO data providers
- API/connector priority
- Standard output/report formats
- Backlink DA/PA/SS/traffic thresholds
- Paid/free/exchange policy
- Backlink capacity benchmarks
- Publisher restrictions/allowlists
- Standard author/bio requirements
- Anchor/target-link constraints
- Audit severity definitions
- Human approval points
- Standard feedback taxonomy

## Override record

For each override store:

- Platform rule/module
- Agency replacement/constraint
- Reason
- Approved by
- Effective date
- Review date when applicable
- Scope

## Precedence

If an approved agency override exists, use it before client/property defaults.

If a client/property rule is stricter and allowed, use the stricter lower-level rule.

If precedence is unclear, return `NEEDS_HUMAN_RULE`.

## Benchmark calibration

Agency production data may replace provisional platform capacity ranges in [43-backlink-benchmark-capacity.md](43-backlink-benchmark-capacity.md) after approval.

## Empty state

If no override exists, record `NO_AGENCY_OVERRIDES` and continue with platform defaults.
