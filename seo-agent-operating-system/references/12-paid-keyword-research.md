# Paid Keyword Research

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for Google Keyword Planner, Search Console, Semrush/Ahrefs supporting research, and source limitations.

Build and validate a Google Ads/Search paid-keyword universe based on campaign economics, intent, and landing-page fit.

## Prerequisites

Load:

- [10-keyword-intake.md](10-keyword-intake.md)
- [16-keyword-data-source-priority.md](16-keyword-data-source-priority.md)
- [17-keyword-api-integration.md](17-keyword-api-integration.md) when available
- [04-property-context.md](04-property-context.md)

## Process order

### 1. Define campaign objective

Resolve lead/purchase/demo/call/awareness goal, target geography, language, budget context, conversion action, and landing-page availability.

### 2. Build seeds

Use services/products, organic research, Keyword Planner, existing Ads search terms, Search Console, sales/customer terminology, competitor landing pages, and approved paid research tools.

### 3. Collect Google Ads metrics

Where available store:

- Average monthly searches
- Competitionº- Competition index when available
- Top-of-page bid low/high
- Location/language/network
- Monthly/seasonal trend

Treat `Competition` as advertiser competition, not organic KD.

### 4. Commercial intent

Classify:

- BRAND
- CORE_SERVICE_OR_PRODUCT
- HIGH_INTENT_TRANSACTIONAL
- COMMERCIAL_RESEARCH
- PROBLEM_SOLUTION
- LOCAL
- COMPETITOR
- INFORMATIONAL

### 5. Landing-page fit

Map keyword -> ad group/theme -> intended message -> landing page -> conversion.

Do not activate high-volume terms with weak landing-page relevance merely because volume is high.

### 6. Negative-keyword research

Identify irrelevant intent such as jobs, salary, free, course/training, DIY, definition, template, unsupported location, unrelated industry, or other client-specific negatives.

Do not apply generic negatives that conflict with the client's actual offer.

### 7. Organic/Paid/Both classification

Use:

- `SEO_ONLY`: useful organic topic but poor paid economics/intent.
- `PAID_ONLY`: highly commercial query not suitable as a standalone organic page or strategically reserved for ads.
- `BOTH`: strong business/intent match for SEO and Ads with appropriate landing page.
- `NEITHER`: irrelevant, misleading, prohibited, or uneconomic under supplied campaign constraints.

Do not infer profitability without conversion/cost data.

## Output fields

Store keyword, cluster, intent, monthly searches, competition, bid ranges, source, match-type recommendation when requested, negatives, landing page, organic/paid/both status, priority, and reason.

## Handoff

When approved paid keywords are used to create Google Search Ad assets, route copy generation through [90-prompt-library-index.md](90-prompt-library-index.md) and the exact [93-prompt-google-search-ads.md](93-prompt-google-search-ads.md) prompt.

Use [15-keyword-validation-output.md](15-keyword-validation-output.md).
