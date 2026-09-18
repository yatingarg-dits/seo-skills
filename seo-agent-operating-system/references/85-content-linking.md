# Content Internal and External Linking

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for crawl/internal-link tools, Surfer/Yoast suggestions, and external-source validation support.

Add or recommend links that improve user usefulness, evidence, navigation, and site architecture without forcing links for SEO alone.

## Internal-link evaluation sequence

Evaluate:

`Source relevance -> Destination relevance -> Context -> Anchor quality -> User usefulness -> Existing links`

## Internal-link rules

1. Never insert an irrelevant link only for SEO.
2. Prefer contextually relevant destination pages.
3. Do not repeat identical exact-match anchors unnaturally.
4. Do not link every occurrence of a keyword.
5. Detect orphan pages when site/crawl data is available.
6. Identify important pages with weak internal authority/support.
7. Do not create circular patterns purely for optimization.
8. Validate that destination URLs exist and are appropriate.
9. Flag broken, redirected, or incorrect destinations.
10. Recommend before automatically changing high-value pages when configured human review is required.
11. Keep links useful to the reader in the surrounding sentence/section.

## Internal-link output

For each recommendation store:

- Source URL/asset
- Destination URL
- Link purpose
- Anchor concept
- Placement/context
- Existing link status
- Destination validity
- Human-review requirement

## External-link rules

Add authoritative external references when they materially support:

- Factual claims
- Statistics
- Standards/regulations
- Definitions/documentation
- Research findings
- Important context

Prefer evidence from [57-content-source-research-reliability.md](57-content-source-research-reliability.md).

Do not add an external link simply to reach a link-count target.

## External-link checks

Verify:

- Source supports the claim
- Source reliability tier is appropriate
- Link is current enough for the claim
- Destination is not broken
- Client/publisher rules do not prohibit the link

## Coordination with site architecture

For site-wide internal-link auditing, use [23-architecture-internal-linking.md](23-architecture-internal-linking.md).

This file controls link selection/insertion during content production.

## Status

Use:

- INTERNAL_LINKS_ADDED
- INTERNAL_LINKS_RECOMMENDED
- EXTERNAL_SOURCES_ADDED
- LINK_REVIEW_REQUIRED
- LINK_BLOCKED_INVALID_DESTINATION
- NO_LINK_REQUIRED
