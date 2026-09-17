# Audit Prioritization, Implementation QA, and Monitoring

## Purpose

Turn audit findings into an executable backlog, verify implementation, and close the feedback loop.

## Required finding fields

Every finding should contain:

- Issue
- URL/template
- Evidence
- Impact
- Severity
- Recommendation
- Owner
- Effort
- Dependency
- Status
- Date checked
- QA result

## Severity logic

Use platform-approved definitions. If none exist, use these categories qualitatively and flag that thresholds require approval:

- Critical: major crawl/indexing/availability or sitewide failure
- High: material ranking/traffic/conversion risk or opportunity
- Medium: meaningful improvement with lower urgency
- Low: cleanup/minor optimization

Do not assign severity from tool labels alone.

## Prioritization factors

Consider together:

- Business importance
- Number/value of affected pages
- Crawl/indexing impact
- Ranking/traffic impact
- Conversion impact
- Implementation effort
- Dependency/blocker
- Risk of change
- Evidence confidence

## Ownership

Assign where possible:

- SEO
- Developer
- Content
- Design/UX
- Analytics
- Client/business owner

## QA after implementation

Recheck the actual fix:

- Re-crawl affected URLs
- Inspect source/rendered output
- Test redirects
- Test canonicals
- Test robots/noindex
- Validate sitemap changes
- Validate structured data
- Test mobile rendering
- Recheck performance when relevant
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

## Monitoring handoff

For implemented items, send relevant URLs/metrics to [53-indexing-monitoring.md](53-indexing-monitoring.md).

## Feedback rule

When QA fails, record the failure reason and reopen the exact finding. Do not create an untraceable duplicate task.
