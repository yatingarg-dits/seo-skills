# Site Architecture and Internal Linking Audit

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for crawl/internal-link sources such as Screaming Frog and approved SEO platforms.

Evaluate whether site structure and internal links guide users and search engines toward important pages.

## Inputs

Use crawl data, property priorities, and keyword/page mapping.

## URL and hierarchy review

Check:

- Logical URL hierarchy
- Unnecessary depth
- Excessive parameters
- Duplicate URL variants
- Upper/lowercase inconsistencies
- Trailing-slash inconsistencies when they create duplicates
- Important pages buried too deeply
- Dead-end pages

## Architecture model

Identify whether important journeys roughly support:

`Home -> Main category/service -> Subcategory/service -> Supporting content`

Do not force this model when the business requires a different valid architecture.

## Orphan and weakly linked pages

Find:

- Crawlable URLs with no internal links
- Sitemap-only pages
- Important pages with very few inlinks
- Pages reachable only through filters/search
- Valuable content not connected to commercial pages

## Internal-link quality

Check:

- Contextual relevance
- Anchor clarity
- Excessive generic anchors
- Repeated exact-match patterns that look unnatural
- Blog-to-service links
- Service-to-supporting-content links
- Breadcrumbs
- Related-content modules
- Navigation/footer dependence
- Links to redirects/errors

## Authority flow

Compare internal-link prominence with property priorities.

Flag when:

- Low-value pages receive disproportionate links
- Priority services receive weak internal support
- Important new pages have no supporting links
- Multiple competing URLs receive conflicting anchor signals

## Recommendation types

Use:

- Add contextual link
- Change destination
- Update anchor
- Remove redundant link
- Fix broken/redirected link
- Add navigation/breadcrumb support
- Consolidate duplicate paths
- Surface orphan page
- De-emphasize low-value page

## Output

Return:

- Source URL/template
- Target URL
- Current issue
- Suggested action
- Suggested anchor concept when useful
- Priority reason

Route to [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).

## Content-production handoff

This file controls site-wide architecture/internal-link auditing. During creation or revision of one content asset, use [85-content-linking.md](85-content-linking.md) for contextual link selection, anchor quality, destination validation, and external-source linking.
