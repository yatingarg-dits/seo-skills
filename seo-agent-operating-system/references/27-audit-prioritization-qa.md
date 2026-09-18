# Audit Prioritization and QA

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for tool limitations. Never copy a crawler/audit platform severity or score directly into final business priority.

Turn audit findings into executable work, verify fixes, and prevent tool severity from replacing SEO/business judgment.

## Required issue fields

For every finding capture:

- Issue
- Affected URL/template/scope
- Evidence/source/date
- Business/SEO impact
- Severity
- Recommendation
- Owner
- Effort
- Dependency
- Status
- QA method/result

## Severity defaults

### CRITICAL

Use for issues that can block/seriously damage crawling, indexation, production availability, canonical ownership, or measurement across important sections.

### HIGH

Use for major priority-page/sitewide issues with clear traffic/conversion/ranking risk or major missed opportunity.

### MEDIUM

Use for meaningful but non-blocking issues or growth opportunities.

### LOW

Use for cleanup/minor optimization with limited expected impact.

## Prioritization logic

Prefer:

1. Index/crawl blockers
2. Severe sitewide technical errors
3. Conversion/tracking data loss
4. Canonical/redirect/indexation errors at scale
5. Priority commercial-page issues
6. Architecture/internal-linking issues
7. Performance/mobile/schema issues
8. Growth/content opportunities
9. Low-impact cleanup

Adjust using property business priorities.

## Effort and dependency

Record effort `LOW/MEDIUM/HIGH` and blockers such as developer release, content rewrite, design, analytics access, legal/client approval, or migration dependency.

## QA

After implementation:

- Re-crawl/retest exact issue
- Recheck source/rendered output
- Verify redirects/canonicals/robots as relevant
- Validate schema/performance/mobile as relevant
- Verify internal links
- Verify analytics/conversions
- Inspect important URLs in Search Console when available

## Status values

Use:

- OPEN
- IN_PROGRESS
- BLOCKED
- IMPLEMENTED_PENDING_QA
- QA_PASSED
- QA_FAILED
- REJECTED_WITH_REASON
- DEFERRED_WITH_REASON

## Evidence rule

Do not close from verbal confirmation alone. Keep before/after evidence when practical.

## Example format

Use [29-audit-example-output.md](29-audit-example-output.md) for representative examples only.

## Monitoring handoff

Send implemented priority URLs/metrics to [53-indexing-monitoring.md](53-indexing-monitoring.md).
