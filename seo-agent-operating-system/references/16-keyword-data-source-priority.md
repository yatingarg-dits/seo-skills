# Keyword Data Source Priority

## Purpose

Use the tool roles and execution processes in [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md). This file decides source precedence when tools disagree.

Define which source to trust for each keyword decision when values differ across Google and third-party SEO tools.

Do not create one universal "best tool". Source priority depends on the metric and decision.

## Source priority by use case

### Existing Google organic performance

Priority:

1. Google Search Console property data
2. Approved rank tracker for controlled/localized tracking
3. Third-party organic estimates

Use Search Console for actual Google clicks, impressions, CTR, average position, query/page/country/device dimensions for the connected property.

### Google Ads keyword demand and advertiser competition

Priority:

1. Google Ads Keyword Planner / Google Ads API KeywordPlanIdeaService
2. Existing Google Ads search-term and keyword performance
3. Approved third-party paid-keyword estimate

Treat Keyword Planner `Competition` as advertiser competition, not organic SEO difficulty.

### Organic keyword difficulty

Use the team's preferred approved SEO provider, but always store:

- Difficulty value
- Provider
- Date
- Geography/database when relevant

Never average Ahrefs/Semrush/Moz/Ubersuggest difficulty values as if they share one formula.

### Search volume

Use priority based on purpose:

- PPC planning: Google Ads historical metrics first.
- Existing-property SEO opportunity: combine Search Console real impressions with an approved search-volume source.
- New-topic SEO research: approved keyword database plus Google Keyword Planner/Trends where available.

When volume values conflict materially, keep both values and label sources instead of silently overwriting one.

### Intent and SERP type

Priority:

1. Current live SERP for the target geography/device context
2. Repeated SERP observations/rank-tracking history
3. Tool-provided intent classification

Manual/live SERP evidence overrides an automated intent label when they conflict.

### Trend and seasonality

Priority:

1. Google Trends for relative trend/seasonality
2. Search Console historical impressions/clicks for the property
3. Approved keyword-provider trend data

## Default tool role matrix

| Need | Primary source | Supporting source |
|---|---|---|
| Existing Google queries | Search Console | Rank tracker |
| Clicks/impressions/CTR | Search Console | Analytics for downstream sessions/conversions |
| PPC avg monthly searches | Keyword Planner/API | Third-party paid tool |
| PPC competition/bid | Keyword Planner/API | Existing Ads performance |
| Organic KD | Approved SEO provider | Live SERP review |
| Search intent | Live SERP | Tool intent label |
| Trend | Google Trends + GSC | SEO provider |
| Competitor keywords | Approved SEO provider | Manual competitor/SERP review |

## Conflict rule

When two sources disagree:

1. Confirm same geography, language, date range, device/network/database.
2. Confirm they measure the same concept.
3. Prefer first-party property data for actual property performance.
4. Preserve provider-specific values for estimates/proprietary metrics.
5. Mark material unresolved conflict as `SOURCE_CONFLICT`.

## Current official basis

Verified 2026-09-17:

- Search Console Performance/Search Analytics exposes clicks, impressions, CTR, position and query/page/country/device dimensions.
- Google Ads Keyword Planner exposes average monthly searches, competition and top-of-page bid ranges; its competition is advertiser competition.

## Handoff

Use with [11-organic-keyword-research.md](11-organic-keyword-research.md), [12-paid-keyword-research.md](12-paid-keyword-research.md), and [17-keyword-api-integration.md](17-keyword-api-integration.md).
