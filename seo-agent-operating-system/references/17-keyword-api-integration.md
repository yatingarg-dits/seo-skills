# Keyword API and Integration Logic

## Purpose

Define the preferred programmatic data path for keyword research while preserving a manual/export fallback.

## Integration priority

### 1. Google Search Console API

Use for connected property performance:

- Queries
- Pages
- Countries
- Devices
- Dates
- Clicks
- Impressions
- CTR
- Average position

Use `searchanalytics.query` with explicit date range and dimensions. Remember the API can be bounded by Search Console's internal row/data limitations; do not assume one query returns every low-volume row.

### 2. Google Ads API KeywordPlanIdeaService

Use for:

- Keyword ideas from keyword seeds
- URL/site seeds
- Geo targeting
- Language targeting
- Search network setting
- Historical keyword metrics

Use this as the preferred programmatic counterpart to Keyword Planner when credentials and account access are available.

### 3. Approved SEO-provider APIs/connectors

Use an agency-approved provider for:

- Organic keyword difficulty
- Competitor keyword sets
- Ranking estimates
- Backlink/authority support data

Store provider name with every proprietary metric.

### 4. Manual UI/export fallback

If API access is unavailable:

- Use the approved UI/export workflow.
- Record `MANUAL_SOURCE`.
- Preserve source, export date, geography, language, and database/network settings.

## Required request context

Before calling any keyword source, resolve:

- Property/client
- Target country/location
- Language
- Organic or paid use case
- Date range for existing performance
- Search network for paid research
- Seed terms/URLs

Do not call a generic global dataset when the task is market-specific unless explicitly requested.

## Metric mapping

Keep these separate:

- `gsc_clicks`
- `gsc_impressions`
- `gsc_ctr`
- `gsc_average_position`
- `ads_avg_monthly_searches`
- `ads_competition`
- `ads_competition_index` when returned
- `ads_top_of_page_bid_low`
- `ads_top_of_page_bid_high`
- `organic_kd_<provider>`
- `third_party_sv_<provider>`

Never map `ads_competition` into `organic_kd`.

## Failure handling

Use:

- `NO_AUTH`
- `NO_PROPERTY_ACCESS`
- `API_QUOTA_OR_LIMIT`
- `SOURCE_UNAVAILABLE`
- `EMPTY_RESULT`
- `SOURCE_CONFLICT`
- `MANUAL_EXPORT_REQUIRED`

Do not invent data when an integration fails.

## Freshness

Store `retrieved_at` with all API data. Re-fetch time-sensitive keyword metrics when the task requires current numbers.

## Handoff

Normalize data according to [16-keyword-data-source-priority.md](16-keyword-data-source-priority.md) before research decisions.
