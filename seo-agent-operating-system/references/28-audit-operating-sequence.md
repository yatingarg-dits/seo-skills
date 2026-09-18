# Website Audit Operating Sequence

## Purpose

When the audit follows a ranking/traffic change, first check [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md). When AI/LLM visibility is part of scope, include [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md) crawler/index/citation checks.

Select and configure audit tools through [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) before running the sequence.

Define the exact experienced-SEO audit order so the agent does not treat a crawler export as the finished audit.

## Sequence

### Phase 1 - Business and property understanding

Load client/property context. Identify priority services, markets, conversions, pages, previous migrations/redesigns, known risks, and competitors.

### Phase 2 - Access and baseline

Collect GSC, GA4, GTM, CMS/crawl access where approved, sitemap/robots, keyword tracking, backlink baseline, previous audits, and recent traffic/ranking history.

### Phase 3 - Crawl and inventory

Crawl the production site and classify URLs, status codes, indexability, canonicals, titles, headings, word/content signals, internal links, images, structured data, and depth.

### Phase 4 - Crawlability and indexation

Check robots, XML sitemaps, `noindex`, canonicalization, redirects, duplicates, Search Console indexing signals, and important URL eligibility.

### Phase 5 - Technical integrity

Check 3xx/4xx/5xx, redirect chains/loops, protocol/host consistency, parameters, pagination/facets, rendering, mobile parity, performance, structured data, and image delivery.

### Phase 6 - Architecture and internal linking

Check hierarchy, crawl depth, orphan pages, dead ends, navigation, breadcrumbs, contextual links, internal anchors, and priority-page authority flow.

### Phase 7 - On-page and content

Review titles, metas, H1/H2 structure, search intent, thin/duplicate/outdated content, E-E-A-T/business evidence where relevant, cannibalization, and content gaps.

### Phase 8 - Local/international

Run only when applicable. Check GBP/citations/local pages or hreflang/language-country architecture.

### Phase 9 - Off-page/backlink health

Review existing referring domains, lost/new links, anchors, relevant referring pages, broken target URLs, suspicious patterns, and competitor link gaps.

### Phase 10 - Analytics and conversion measurement

Validate tracking, key events/conversions, forms/calls/purchases/demos, attribution assumptions, and organic landing-page reporting.

### Phase 11 - Prioritization

For each issue record impact, scope, affected URLs/templates, evidence, recommendation, owner, effort, dependency, severity, and expected outcome.

### Phase 12 - Implementation and QA

After fixes, re-crawl/retest the exact issue. Mark QA pass/fail. Do not close an issue from developer confirmation alone.

### Phase 13 - Monitoring

Track indexation, clicks, impressions, conversions, ranking groups, priority landing pages, crawl errors, CWV/performance, and regression signals.

## Priority order

Use this default order unless property context changes it:

1. Crawl/index blockers
2. Severe sitewide technical errors
3. Tracking/conversion data loss
4. Wrong canonicals/redirects/indexation at scale
5. Priority-page intent/content/on-page issues
6. Architecture/internal-linking issues
7. Performance/mobile/schema issues
8. Content gaps and growth opportunities
9. Low-impact cleanup

## Guardrail

Do not assign `Critical` merely because a tool labels an issue critical. Use [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).

## Example reference

Use [29-audit-example-output.md](29-audit-example-output.md) for formatting examples only. It is not client evidence.
