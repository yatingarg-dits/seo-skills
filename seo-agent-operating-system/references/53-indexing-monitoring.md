# Indexation, Ranking, and Content Performance Monitoring

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for Search Console, Bing Webmaster Tools, GA4, Clarity, and approved rank/SEO platforms during post-publication monitoring.

Monitor verified website content after publication or SEO implementation and decide whether to monitor, optimize, or close the active review cycle. For ranking-update diagnosis use [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md); for AI/LLM citation/referral monitoring use [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md).

Backlink-page verification remains in [38-backlink-verification-monitoring.md](38-backlink-verification-monitoring.md).

For explicit submission/discovery actions, use [62-ping-submission.md](62-ping-submission.md) or [68-search-engine-submission.md](68-search-engine-submission.md) before monitoring.


## Contents

- Purpose and inputs
- Indexation check
- Ranking baseline and monitoring
- Performance review and change detection
- Performance decision
- Diagnosis route and output
## Inputs

Accept:

- Publication-verified URLs from [52-onpage-implementation-publishing.md](52-onpage-implementation-publishing.md)
- New/updated website URLs
- Audit fixes
- Keyword target map
- Baseline metrics
- Business objective/conversion actions

## Indexation check - mandatory in the content workflow

Track where evidence is available:

- Crawlability
- `noindex` status
- Canonical
- Sitemap inclusion
- Search Console inspection/indexing state
- Search-engine-selected canonical when available
- Crawl/index exclusion reason

Use:

- INDEXED
- NOT_INDEXED
- PENDING
- INDEXATION_ISSUE

Do not repeatedly request indexing without diagnosis or an approved process.

## Ranking baseline

When ranking data becomes available, record:

- First observed position/baseline
- Primary keyword/cluster
- Supporting keyword positions where useful
- Ranking URL
- Geography/device/source/date

Use `BASELINE_CAPTURED` when recorded.

## Ranking monitoring

Monitor primary/supporting clusters and watch for:

- Position direction
- Wrong URL/cannibalization
- SERP feature changes
- Geography/device differences where configured

Monitoring frequency/duration is configurable, not a universal blocker.

## Performance review

Evaluate relevant evidence such as:

- Clicks
- Impressions
- CTR
- Organic sessions
- Conversions/leads/revenue when available
- Landing-page engagement measures used by the team
- Core Web Vitals regression when relevant

Always store date range and source.

## Change detection

Flag:

- Indexation issue
- Sudden ranking drop
- Wrong URL ranking
- Click/impression decline
- Conversion tracking loss
- Redirect/error/noindex/canonical change
- Content disappearance/unapproved change
- Important internal links removed
- Confirmed Google core/spam/Discover update overlaps
- AI/LLM crawler/access change when monitored
- Material AI citation/referral visibility change when monitored

Use team-approved timing thresholds. If none exist, mark `NEEDS_HUMAN_RULE` instead of inventing a number of days.

## Performance decision

Return one:

- MONITOR
- OPTIMIZE
- CONTINUE_MONITORING
- CLOSE_REVIEW_CYCLE
- TECHNICAL_DIAGNOSIS_REQUIRED
- CONTENT_OPTIMIZATION_REQUIRED
- TRACKING_DIAGNOSIS_REQUIRED
- HUMAN_REVIEW_REQUIRED

## Diagnosis route

- Crawl/index issue -> [21-technical-crawl-indexation.md](21-technical-crawl-indexation.md)
- Content/intent issue -> [22-onpage-content-audit.md](22-onpage-content-audit.md) or [56-content-topic-research-validation.md](56-content-topic-research-validation.md)
- Internal-link issue -> [23-architecture-internal-linking.md](23-architecture-internal-linking.md)
- Performance/mobile issue -> [24-performance-mobile-schema.md](24-performance-mobile-schema.md)
- Tracking issue -> [26-analytics-tracking.md](26-analytics-tracking.md)
- Keyword mapping issue -> [14-keyword-clustering-mapping.md](14-keyword-clustering-mapping.md)
- Content-quality/optimization issue -> [86-content-quality-ai-originality.md](86-content-quality-ai-originality.md) and [51-seo-content-review.md](51-seo-content-review.md)

## Output

Return:

- URL/asset
- Monitoring period
- Indexing status
- Ranking baseline/current summary
- Traffic/conversion summary
- Change detected
- Evidence
- Diagnosis route
- Decision: Monitor/Optimize/Continue/Close
- Human review status
