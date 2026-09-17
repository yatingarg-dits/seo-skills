# Indexing, Ranking, and SEO Monitoring

## Purpose

Monitor website landing pages/content after publication or SEO implementation and detect indexing, ranking, traffic, or conversion issues.

Backlink-page verification remains in [38-backlink-verification-monitoring.md](38-backlink-verification-monitoring.md).

For explicit submission/discovery actions, use [62-ping-submission.md](62-ping-submission.md) or [68-search-engine-submission.md](68-search-engine-submission.md) before monitoring.

## Inputs

Accept:

- New/updated website URLs
- Audit fixes
- Keyword target map
- Baseline metrics
- Expected conversion actions

## Indexing checks

Track where evidence is available:

- URL crawlability
- `noindex` status
- Canonical
- Sitemap inclusion
- Search Console inspection/indexing state
- Google-selected canonical when available
- Crawl/index exclusion reason

Do not repeatedly request indexing or take action without an approved process.

## Ranking monitoring

Track target clusters rather than one keyword only where possible:

- Primary keyword position
- Supporting keyword positions
- Ranking URL
- Wrong-URL/cannibalization changes
- SERP feature changes
- Geography/device as configured

## Performance monitoring

Track relevant metrics:

- Clicks
- Impressions
- CTR
- Organic sessions
- Conversions/leads/revenue when available
- Landing-page engagement signals used by the team
- Core Web Vitals regressions when relevant

Always store date range and source.

## Change detection

Flag:

- Not indexed after expected review window
- Sudden ranking drop
- Wrong URL starts ranking
- Click/impression decline
- Conversion tracking loss
- Page becomes redirected/error/noindex
- Canonical changes
- Content disappears/changes unexpectedly
- Internal links removed

Use team-approved timing thresholds. If none exist, flag `NEEDS_HUMAN_RULE` rather than inventing a number of days.

## Diagnosis route

- Crawl/index issue -> [21-technical-crawl-indexation.md](21-technical-crawl-indexation.md)
- Content/intent issue -> [22-onpage-content-audit.md](22-onpage-content-audit.md)
- Internal-link issue -> [23-architecture-internal-linking.md](23-architecture-internal-linking.md)
- Performance/mobile issue -> [24-performance-mobile-schema.md](24-performance-mobile-schema.md)
- Tracking issue -> [26-analytics-tracking.md](26-analytics-tracking.md)
- Keyword mapping issue -> [14-keyword-clustering-mapping.md](14-keyword-clustering-mapping.md)

## Output

Return URL, monitoring period, indexing status, ranking summary, traffic/conversion summary, change detected, evidence, diagnosis route, recommended action, and human review status.
