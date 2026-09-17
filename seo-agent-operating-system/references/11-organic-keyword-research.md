# Organic Keyword Research

## Purpose

Run the complete experienced-SEO organic keyword process from existing-property signals through competitor/SERP validation and URL mapping.

## Prerequisites

Load:

- [10-keyword-intake.md](10-keyword-intake.md)
- [16-keyword-data-source-priority.md](16-keyword-data-source-priority.md)
- [17-keyword-api-integration.md](17-keyword-api-integration.md) when programmatic data is available
- [04-property-context.md](04-property-context.md)

## Process order

### 1. Start with the website/property

Extract seeds from homepage, navigation, services/products, categories, existing blogs/resources, FAQs, title/H1 language, sales/customer terminology, and priority services.

### 2. Pull existing Google performance

Use Search Console when available to collect query, page, clicks, impressions, CTR, average position, country, device, and date trend.

Flag:

- Positions 1-3
- 4-10
- 11-20
- 21-50
- High-impression/low-CTR
- Near-page-one opportunities
- Wrong URL ranking
- Multiple URLs for same query
- Declining/improving queries

### 3. Expand seed universe

Use approved sources such as autocomplete, related searches, People Also Ask, Keyword Planner, Google Trends, approved SEO tools, competitor sites, forums/communities, and customer/sales vocabulary.

### 4. Competitor keyword gap

Separate business competitors from SERP competitors.

Collect competitor topics/keywords/pages that are relevant to the client. Reject competitor keywords outside the client's actual offering or planned authority area.

### 5. Collect metrics

For each keyword store:

- Keyword/normalized keyword
- Seed/source
- Topic/cluster candidate
- Geography/language
- Search volume + source
- Organic KD + provider
- CPC as supporting commercial signal
- Trend/seasonality
- Existing rank/URL
- GSC clicks/impressions/CTR when available
- Business relevance
- Conversion potential
- Initial intent

### 6. Business/website vision match

Classify:

- STRONG_BUSINESS_MATCH
- SUPPORTING_MATCH
- TOPICAL_AUTHORITY
- FUTURE_APPROVED_OPPORTUNITY
- WEAK_MATCH
- IRRELEVANT

Do not prioritize high-volume irrelevant terms.

### 7. Live SERP validation

Send important terms to [13-serp-competitor-analysis.md](13-serp-competitor-analysis.md) for pages 1-5 review, intent, page type, competitor strength, SERP features, and `allintitle` support where used.

### 8. Cluster and map

Use [14-keyword-clustering-mapping.md](14-keyword-clustering-mapping.md) to group same-intent terms and map them to existing/new URLs.

### 9. Prioritize

Use business fit, intent, realistic opportunity, conversion potential, existing position, SERP strength, authority/resources, demand, and trend.

## Guardrails

- Search volume alone does not determine priority.
- KD alone does not determine feasibility.
- CPC does not equal organic difficulty.
- `allintitle` is supporting evidence, not a ranking guarantee.
- Preserve source for every metric.
- Reject or downgrade keywords that conflict with property scope.

## Handoff

Use [15-keyword-validation-output.md](15-keyword-validation-output.md) for final approval/rejection.
