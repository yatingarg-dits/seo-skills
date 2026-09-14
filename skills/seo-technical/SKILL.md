---
name: seo-technical
description: "Audit and govern technical SEO across crawlability, indexability, robots.txt, XML sitemaps, canonicals, redirects, status codes, architecture, faceted navigation, pagination, duplicate URLs, JavaScript rendering, mobile usability, Core Web Vitals, schema, HTTPS, crawl budget, migrations, redesigns, and technical incident prevention. Use for technical audits, implementation guidance, migration QA, and technical SEO troubleshooting."
---

# Technical SEO

## Mission

Ensure important pages can be discovered, crawled, rendered, understood, indexed, and served reliably without introducing unnecessary duplication or technical risk.

Use this order of operations:

**Availability -> crawlability -> renderability -> indexability -> canonicalization -> status/redirects -> architecture -> sitemaps/robots -> performance/mobile -> structured data -> scale controls -> migration/change management -> verification.**

## Required Inputs

Use or request:

- Domain and important subdomains.
- Website platform/CMS/framework.
- Target countries/languages.
- Important page types and templates.
- Crawl data when available.
- Search Console coverage/indexing data.
- XML sitemap(s).
- robots.txt.
- Server/CDN information where relevant.
- Rendering method: server-rendered, static, client-side, hybrid.
- Analytics/deployment history.
- Known migrations/redesigns.
- Approval owner for technical changes.

Missing technical access must be reported explicitly.

## 1. Site Availability

Check whether important pages:

- Load consistently.
- Return expected HTTP status codes.
- Are accessible over HTTPS.
- Avoid persistent server errors.
- Avoid redirect loops.
- Avoid accidental maintenance/login restrictions.

Treat sitewide downtime, mass 5xx errors, incorrect domain redirects, or sitewide blocking as critical incidents.

## 2. Crawlability

Confirm important pages can be reached through:

- Internal links.
- Navigation.
- Sitemaps where appropriate.
- Search-engine crawler access.

Check for:

- robots.txt blocks.
- inaccessible navigation.
- broken links.
- login/session barriers.
- crawl traps.
- endless parameter combinations.
- JavaScript-only links that may not be reliably discoverable.

Do not optimize page content before confirming important pages can be crawled.

## 3. Robots.txt

Understand that robots.txt controls crawling, not guaranteed index removal.

Check:

- User-agent rules.
- Disallow rules.
- Accidental blocking of CSS/JS needed for rendering.
- Accidental blocking of important directories.
- Sitemap declarations.
- Staging/test environment rules.

Never change robots.txt automatically without impact analysis and approval.

Do not use robots.txt as a substitute for noindex when the goal is to prevent indexing of a crawlable page.

## 4. Renderability and JavaScript

For JavaScript-heavy sites, compare:

- Raw HTML.
- Rendered HTML.
- User-visible content.
- Search-engine-visible links and metadata.

Verify important elements exist in a reliably rendered state:

- Main content.
- Internal links.
- Title/meta where framework behavior affects them.
- Canonical.
- Structured data.
- Product/category information.

Do not assume content visible in a browser is automatically easy for search engines to process.

## 5. Indexability

For important pages, check:

- Meta robots.
- X-Robots-Tag.
- Canonical signals.
- HTTP status.
- Duplicate/canonicalized states.
- Search Console indexing status.
- Soft-404 behavior.
- Content quality/indexability intent.

Classify pages as:

- Should be indexed.
- Should not be indexed.
- Needs investigation.

Examples often suitable for indexing:

- Core service pages.
- Product pages with value.
- Category pages.
- Helpful articles.
- Genuine location pages.

Examples often unsuitable for indexing:

- Test pages.
- Internal search results.
- Empty/thin utility pages.
- Low-value filter combinations.
- Duplicate tracking/parameter versions.

Do not remove noindex from pages simply because an audit tool flags it. Confirm intent first.

## 6. Canonicalization

Check:

- Canonical target returns a valid page.
- Canonical points to the preferred version.
- Internal links generally point to the preferred version.
- Sitemap contains the preferred version.
- Canonical signals are not contradictory.
- Cross-domain canonicals are intentional.

Common issues:

- Canonical to a redirected URL.
- Canonical to a 404.
- Canonical loops.
- Important unique page canonicalized elsewhere by mistake.
- Faceted/parameter pages canonicalized inconsistently.

Canonical changes are high risk on important pages and require approval.

## 7. HTTP Status Codes

Interpret status codes in context.

### 2xx

Expected for live indexable pages.

### 3xx

Use redirects intentionally. Distinguish permanent and temporary moves based on actual business intent.

### 4xx

A 404/410 is not automatically an SEO emergency. Prioritize based on:

- Organic traffic.
- Backlinks.
- Internal links.
- Historical value.
- Replacement availability.

### 5xx

Treat sustained server errors on important pages as high priority.

## 8. Redirects

For permanent moves:

- Redirect to the closest relevant replacement.
- Avoid redirecting unrelated deleted pages to the homepage.
- Avoid unnecessary chains.
- Avoid loops.
- Update internal links to the final destination.
- Update sitemaps where relevant.
- Preserve a redirect map for migrations.

Before removing a redirect, check backlinks, traffic, historical URLs, and external references.

Large redirect changes require approval and rollback planning.

## 9. Broken Links

Find and classify:

- Broken internal links.
- Broken image URLs.
- Broken canonical targets.
- Broken hreflang targets.
- Broken external links.
- Redirect chains.

Prioritize broken internal links on high-value pages and broken destinations with backlinks.

## 10. XML Sitemaps

Sitemaps should normally contain URLs the site wants discovered and indexed.

Check for:

- 200-status URLs.
- Canonical URLs.
- Indexable URLs.
- Correct protocol/hostname.
- Reasonable freshness metadata when used.
- Logical segmentation for large sites.

Avoid including:

- Redirects.
- 404/410 URLs.
- noindex URLs.
- Duplicate/non-canonical variants.
- Internal search results.

Do not treat sitemap presence as proof a URL should index.

## 11. Site Architecture

Evaluate:

- Navigation hierarchy.
- Click depth.
- Category/subcategory relationships.
- Orphan pages.
- Internal-link distribution.
- URL consistency.
- Template consistency.
- Whether priority pages are easy to reach.

Important business pages should not be buried behind unnecessary depth.

## 12. Orphan Pages

Identify URLs with no meaningful internal links.

For each orphan page, decide:

- Add relevant internal links.
- Keep intentionally isolated.
- Merge.
- Redirect.
- Remove/noindex with approval when appropriate.

Do not link every orphan page automatically; first confirm the page has value.

## 13. Duplicate Content and Duplicate URLs

Identify duplication from:

- Parameters.
- Tracking codes.
- Sort/filter URLs.
- Print versions.
- HTTP/HTTPS.
- www/non-www.
- trailing-slash variants.
- case differences.
- session IDs.
- copied templates.
- product variants.

Choose a solution based on intent:

- Canonical.
- Redirect.
- noindex.
- parameter control.
- content differentiation.
- keep separate when each version serves distinct value.

Do not use one solution for every duplicate pattern.

## 14. Faceted Navigation and Filters

For ecommerce, marketplaces, directories, and large catalogs:

- Inventory all filter dimensions.
- Estimate URL explosion.
- Identify high-value combinations with genuine search demand.
- Control low-value combinations.
- Prevent crawl traps.
- Align internal links, canonicals, indexation, and sitemaps.

Do not index every filter automatically.

Do not block valuable filtered landing pages merely because they contain parameters.

## 15. Pagination

Check whether:

- Users and crawlers can reach deeper items.
- Pagination links are crawlable.
- Page series does not create unnecessary duplication.
- Important products/articles remain discoverable.
- Infinite scroll has crawlable fallback/navigation where needed.

Do not assume page 2+ should be noindexed by default.

## 16. Crawl Budget and Large Sites

Treat crawl-budget optimization as most relevant to large or frequently changing sites.

Investigate:

- Duplicate URL generation.
- faceted crawl traps.
- infinite calendar/filter spaces.
- low-value crawlable parameters.
- excessive redirects.
- server response efficiency.
- large numbers of obsolete URLs.

At scale, fix patterns and templates instead of editing URLs one by one.

## 17. Mobile Usability

Check important templates on mobile for:

- Readable text.
- Usable controls.
- Navigation.
- Forms.
- Product/service functionality.
- Image sizing.
- layout stability.
- intrusive overlays.
- parity of important content with desktop.

Do not review desktop only.

## 18. Core Web Vitals and Performance

Evaluate user-facing performance such as:

- Largest Contentful Paint.
- Interaction to Next Paint.
- Cumulative Layout Shift.
- Server response behavior.
- image weight.
- JavaScript execution.
- render-blocking resources.
- font loading.
- caching/CDN behavior.

Verify current platform guidance before enforcing numeric thresholds because platform definitions can evolve.

Do not chase a perfect lab score at the expense of content, functionality, or business value.

## 19. Image Delivery

Check:

- Oversized images.
- responsive image delivery.
- modern formats when supported.
- lazy loading where appropriate.
- width/height dimensions.
- broken images.
- unnecessary decorative payload.

Coordinate alt-text/content rules with the on-page/content skill.

## 20. HTTPS and Security Basics

Check:

- HTTP to HTTPS redirects.
- mixed content.
- certificate validity.
- duplicate protocol versions.
- canonical consistency.

Escalate hacked-site or malware issues to security immediately. Security takes priority over routine SEO work.

## 21. Structured Data

Check structured data for:

- Eligibility for the actual page type.
- Match with visible content.
- Required/recommended properties according to current official documentation.
- Accurate prices/availability/reviews where relevant.
- No fabricated ratings, authors, products, FAQs, or events.
- Validation errors and warnings.

Schema is descriptive markup, not a guarantee of rich results.

## 22. International Technical Signals

Coordinate with the local/international skill for:

- hreflang.
- locale URL architecture.
- x-default.
- regional canonicals.
- country/language alternates.

Technical implementation must not create canonicals that contradict hreflang intent.

## 23. Site Search and Internal Search Results

Review internal-search URLs for:

- crawlability.
- indexation risk.
- infinite combinations.
- thin/duplicate pages.

Do not expose unlimited search-result pages to indexing without a deliberate strategy.

## 24. Soft 404s

Identify pages that return 200 but effectively provide no useful content, such as:

- Empty category pages.
- nonexistent product messages.
- placeholder pages.

Choose proper handling based on whether a useful replacement exists.

## 25. Product Availability

For ecommerce:

### Temporarily Out of Stock

Usually keep the page when the product will return. Consider:

- availability status.
- restock notification.
- alternatives.

### Permanently Discontinued

Check:

- traffic.
- rankings.
- backlinks.
- replacement product.
- user demand.

Then decide whether to keep, redirect, or remove.

Never delete only because inventory is zero.

## 26. Website Redesign

Before and after redesign, compare:

- URLs.
- content.
- headings.
- metadata.
- internal links.
- canonicals.
- structured data.
- navigation.
- page speed.
- tracking.

A visual redesign must not silently remove SEO value.

## 27. Website Migration

Treat migration as high/critical risk.

### Pre-Migration

Create:

- complete old URL inventory.
- new URL map.
- redirect map.
- baseline rankings/traffic/conversions.
- important backlink list.
- canonical plan.
- sitemap plan.
- robots/noindex checks.
- analytics/tracking plan.
- rollback/escalation plan.

### Launch

Verify:

- redirects.
- status codes.
- canonicals.
- indexability.
- robots.txt.
- sitemaps.
- internal links.
- tracking.
- HTTPS/domain behavior.

### Post-Launch

Monitor:

- crawl errors.
- indexing.
- rankings.
- clicks/impressions.
- traffic.
- conversions.
- redirect problems.

Do not treat a migration like a normal release.

## 28. Log Analysis

When server logs are available, use them to understand:

- crawler visit frequency.
- wasted crawling.
- important pages not crawled.
- response-code patterns.
- bot behavior after migration.

Do not infer exact indexing decisions from crawl logs alone.

## 29. Technical Priority Model

Prioritize in this order when applicable:

1. Site unavailable or hacked.
2. Sitewide crawl/index blocking.
3. Major migration/redirect failure.
4. Important revenue pages blocked/noindexed/broken.
5. Widespread canonical/indexation errors.
6. Architecture/crawl traps affecting many URLs.
7. Performance/mobile issues with user impact.
8. Structured data and smaller technical improvements.

Do not prioritize by raw error count alone.

## 30. Technical Approval Gates

Human approval is required for:

- robots.txt changes.
- noindex changes on important pages/templates.
- canonical changes.
- large redirect changes.
- URL changes.
- navigation/architecture changes.
- sitemap-generation logic changes when broad.
- large filter/indexation rule changes.
- hreflang restructuring.
- migrations.
- mass removal of URLs.

## Standard Technical Audit Output

```markdown
### Technical Finding
- Area:
- Scope/URLs:
- Current behavior:
- Expected behavior:
- Evidence:
- Business impact:
- SEO impact:
- Severity:
- Risk:
- Confidence:
- Recommended fix:
- Human approval:
- Owner:
- Verification steps:
- Rollback plan:
- Monitoring window:
```

## Non-Negotiable Rules

- Never change robots.txt automatically.
- Never change canonical or noindex state without understanding intent.
- Never redirect every deleted page to the homepage.
- Never delete URLs without checking value.
- Never assume a 404 is an emergency.
- Never assume visible browser content is fully rendered for search engines.
- Never index every facet/filter by default.
- Never chase performance scores without considering real user impact.
- Never treat schema as a ranking shortcut.
- Never launch a migration without a URL map, baseline, verification plan, and approval.
