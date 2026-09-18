# On-Page Implementation, Publishing, and Publication Verification

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for CMS/Yoast implementation support, Tag Manager measurement changes, schema tests, and publication verification tools.

Publish approved content/SEO changes without introducing technical or content regressions, then verify the live publication before marking the publishing stage complete.

## Inputs

Require:

- Approved/authorized content from [88-content-approval-revision.md](88-content-approval-revision.md), or
- Approved audit changes from [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md)

Do not treat validation PASS as publishing authorization when approval policy requires human approval.

## Pre-publish checklist

Verify:

- Correct property/environment
- Correct target URL/slug
- Approved content version
- Approved title/meta/H1/headings
- Internal links correct
- External links correct
- Images/assets correct
- Alt text appropriate
- CTA/forms correct
- Canonical correct
- Robots directive correct
- Structured data correct when applicable
- Breadcrumb/navigation placement correct when applicable
- Analytics/tracking preserved/configured

## Existing-page changes

Before replacing content:

- Preserve valuable sections unless removal is intentional
- Preserve working links/tracking unless changes are approved
- Note URL changes
- Create redirect plan before changing live URLs

## New-page publishing

Ensure:

- Page is reachable by internal links
- It is not orphaned
- Sitemap inclusion follows site rules
- Canonical points correctly
- Indexing is allowed when intended

## Publication verification - mandatory

After publishing, verify the live URL:

- Expected HTTP status
- Correct content/version
- Formatting/rendering
- Title/meta/H1
- Internal/external links
- Images/assets/alt text
- CTA/forms
- Canonical
- Robots/indexability
- Mobile rendering
- Analytics/tracking
- Structured data when applicable

A published asset cannot be marked complete until publication verification has been performed.

## Status

Use:

- READY_TO_PUBLISH
- PUBLISH_BLOCKED_NO_AUTHORIZATION
- PUBLISHED_PENDING_VERIFICATION
- PUBLICATION_VERIFIED
- VERIFICATION_FAILED
- ROLLBACK_REQUIRED

## Output

Store:

- URL
- Published version
- Publish/update date
- Implementer
- Approval reference
- Verification status
- Evidence/issues found
- Fix/rollback action
- Next monitoring handoff

## Handoff

Send `PUBLICATION_VERIFIED website URLs to [53-indexing-monitoring.md](53-indexing-monitoring.md).
