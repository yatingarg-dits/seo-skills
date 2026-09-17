# On-Page Implementation and Publishing

## Purpose

Implement approved SEO page elements and publish without introducing technical or content regressions.

## Inputs

Require approved content from [51-seo-content-review.md](51-seo-content-review.md) or approved audit changes from [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).

## Pre-publish checklist

Verify:

- Correct property/environment
- Correct target URL/slug
- Title approved
- Meta description approved
- H1/headings correct
- Body content correct
- Internal links correct
- External links correct
- Images/assets correct
- Alt text appropriate
- CTA/forms correct
- Canonical correct
- Robots directive correct
- Structured data correct when applicable
- Breadcrumb/navigation placement correct when applicable

## Existing-page changes

Before replacing content:

- Preserve valuable existing sections unless removal is intentional
- Preserve working links/tracking unless changes are approved
- Note URL changes
- Create redirect plan before changing live URLs

## New-page publishing

Ensure:

- Page is reachable by internal links
- It is not orphaned
- Sitemap inclusion follows platform/site rules
- Canonical points correctly
- Indexing is allowed when intended

## QA immediately after publish

Check live page:

- 200 status when expected
- Rendered title/meta/H1
- Content formatting
- Internal/external links
- Canonical
- Robots
- Mobile rendering
- Forms/CTA
- Analytics/tracking
- Structured data when applicable

## Status

Use:

- READY_TO_PUBLISH
- PUBLISHED_PENDING_QA
- QA_PASSED
- QA_FAILED
- BLOCKED
- ROLLBACK_REQUIRED

## Output

Store:

- URL
- Publish/update date
- Change summary
- Implementer
- QA status
- Issues found
- Next check date/rule

## Handoff

Send published URLs to [53-indexing-monitoring.md](53-indexing-monitoring.md).
