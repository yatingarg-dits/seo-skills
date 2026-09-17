# Skill Map

Use this map to select the smallest relevant skill file and preserve handoffs.

## Context

| File | Responsibility | Feeds |
|---|---|---|
| `01-platform-seo-context.md` | Global SEO operating rules and boundaries | All modules |
| `02-agency-seo-overrides.md` | Approved agency-level overrides | All client work |
| `03-client-context.md` | Client-wide business, brand, markets, policies | All client properties |
| `04-property-context.md` | Domain-specific audience, pages, keywords, links, signatures, priorities | Keywords, audit, content, backlinks, listings |

## Keyword research

| File | Responsibility | Feeds |
|---|---|---|
| `10-keyword-intake.md` | Define business, market, pages, seed terms, sources | 11 or 12 |
| `11-organic-keyword-research.md` | Build organic keyword universe and core metrics | 13 |
| `12-paid-keyword-research.md` | Build paid keyword universe and PPC metrics | 15 |
| `13-serp-competitor-analysis.md` | Validate intent, SERP pages 1-5, competitors, allintitle | 14 |
| `14-keyword-clustering-mapping.md` | Cluster, map URLs, flag cannibalization, prioritize | 15 |
| `15-keyword-validation-output.md` | Final review and approved/rejected keyword set | Content/Audit |

## Website audit

| File | Responsibility | Feeds |
|---|---|---|
| `20-audit-intake-baseline.md` | Access, business context, baseline | 21-26 |
| `21-technical-crawl-indexation.md` | Crawl, status codes, robots, sitemap, canonicals, indexability | 27 |
| `22-onpage-content-audit.md` | Titles, metas, headings, content, duplication, intent | 27 |
| `23-architecture-internal-linking.md` | URL hierarchy, depth, orphan pages, internal links | 27 |
| `24-performance-mobile-schema.md` | Performance, mobile rendering, images, structured data | 27 |
| `25-local-international.md` | Local SEO and international SEO when applicable | 27 |
| `26-analytics-tracking.md` | GA4/GTM/GSC/conversion tracking validation | 27 |
| `27-audit-prioritization-qa.md` | Prioritize, assign, verify fixes, monitor | 53 |

## Backlink shared workflow

| File | Responsibility | Feeds |
|---|---|---|
| `30-backlink-discovery.md` | Find candidate domains/URLs from approved sources | 32 |
| `31-community-link-intake.md` | Process Telegram/Slack/Facebook/shared-sheet inputs | 32 |
| `32-backlink-qualification.md` | DA/PA/SS, audience, traffic, relevance, quality, risk | 33 |
| `33-backlink-activity-classification.md` | Decide exact off-page/backlink activity | 59/60-83 |
| `34-backlink-target-anchor.md` | Select client target URL and anchor approach | 35/activity |
| `35-backlink-content-generation.md` | Create proposed backlink content from context | 36/37/activity |
| `36-publisher-guidelines.md` | Apply site-specific publishing rules | 35/37/activity |
| `37-backlink-outreach-submission.md` | Execute shared outreach/registration/submission mechanics | 38 |
| `38-backlink-verification-monitoring.md` | Verify live/indexed/link attributes and monitor | 39 |
| `39-backlink-feedback-learning.md` | Capture backlink and content feedback separately | 30-38/activity |

## Business listings

| File | Responsibility | Feeds |
|---|---|---|
| `40-business-listing-discovery.md` | Discover and qualify listing/citation platforms | 41 |
| `41-business-listing-execution.md` | Prepare profile data, submit, verify, maintain | 39/53 |

## SEO content

| File | Responsibility | Feeds |
|---|---|---|
| `50-seo-content-brief.md` | Build content brief from keyword + property context | 51 |
| `51-seo-content-review.md` | Review factual, SEO, intent, tone, link and guideline fit | 52 |
| `52-onpage-implementation-publishing.md` | Implement approved on-page elements and publish | 53 |
| `53-indexing-monitoring.md` | Check indexing, performance, rankings, regressions | Feedback/context |

## Off-page activity controllers

Use [59-offpage-activity-map.md](59-offpage-activity-map.md) to route the exact activity. Each activity keeps its own execution steps while reusing shared modules only when applicable.

| File | Activity | Shared modules commonly used |
|---|---|---|
| `60-link-building.md` | Link Building | 30-39 |
| `61-business-listing.md` | Business Listing | 40-41 |
| `62-ping-submission.md` | Ping Submission | 53 |
| `63-micro-blogging.md` | Micro Blogging | 04, 38 when link exists |
| `64-video-submission.md` | Video Submission | 04, 38 when link exists |
| `65-ppt-submission.md` | PPT Submission | 04, 38 when link exists |
| `66-pdf-submission.md` | PDF Submission | 04, 38 when link exists |
| `67-web-2-0-submission.md` | Web 2.0 Submission | 32, 34-39 |
| `68-search-engine-submission.md` | Search Engine Submission | 21, 53 |
| `69-guest-posting.md` | Guest Posting | 32-39 |
| `70-social-bookmarking.md` | Social Bookmarking | 32, 38-39 when link exists |
| `71-press-release.md` | Press Release | 03-04, 38 when links/mentions tracked |
| `72-backlinks.md` | Backlinks | 30-39 |
| `73-blog-directory-submission.md` | Blog Directory Submission | 32, 38-39 |
| `74-infographics.md` | Infographics | 32, 34, 38-39 |
| `75-podcasts.md` | Podcasts | 03-04, 32, 38 when show-note link exists |
| `76-question-answer.md` | Q&A | 04, 32 when qualification is needed, 38 when link exists |
| `77-article-submission.md` | Article Submission | 32-39 |
| `78-image-sharing.md` | Image Sharing | 04, 38 when link exists |
| `79-profile-creation.md` | Profile Creation | 04, 32, 38-39 |
| `80-guest-blogging.md` | Guest Blogging | 32-39; related to 69 |
| `81-forums.md` | Forums | 04, 32, 38-39 |
| `82-blog-commenting.md` | Blog Commenting | 04, 32, 38-39 |
| `83-forum-participation.md` | Forum Participation | 04, 32, 38-39; related to 81 |

## Routing rule

If a workflow needs a different data source, materially different decision criteria, or materially different execution path, keep it as a separate module rather than adding hidden branches to another module.
