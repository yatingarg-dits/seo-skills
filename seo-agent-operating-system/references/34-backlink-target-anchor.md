# Backlink Target URL and Anchor Planning

## Purpose

Apply [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md) so anchor selection supports relevance and users without manipulative exact-match/link-spam patterns.

Select the client target page and anchor approach based on relevance, business priority, existing link distribution, and property rules.

## Inputs

Load property context, approved keyword mapping when available, historical backlink data, and activity classification.

## Target-page priority

Use this default sequence unless the property overrides it:

1. Relevant priority commercial/service/product page
2. Relevant high-value informational/resource page
3. Category/hub page when it is the true intent owner
4. Homepage only when brand/homepage intent or publisher context justifies it

Do not default every link to the homepage.

## Target-page checks

Require:

- Strong topical fit with the surrounding external content
- Live `200` destination unless a documented exception exists
- Indexable/canonical target
- Approved external-promotion status
- No conflict with property exclusions
- No unintended staging/parameter URL

## Distribution checks

Before selecting a target:

- Review historical links to the domain/property when available
- Check over-concentration on one page
- Check whether a new referring domain would add more value than another repeat placement
- Consider current business/keyword priority

## Anchor categories

Use:

- BRAND
- NAKED_URL
- GENERIC
- TOPICAL_CONTEXTUAL
- PARTIAL_MATCH
- EXACT_MATCH

Default toward brand, URL, generic, topical, and natural partial-match diversity.

Exact-match anchors require explicit contextual justification and must not be repeated aggressively.

## Anchor decision factors

Consider sentence fit, publisher guidelines, existing anchor distribution, target keyword strategy, activity type, and client restrictions.

## Reject target/anchor when

- Target is non-indexable/redirect/error page
- Link would be irrelevant to surrounding content
- Anchor is misleading or spammy
- Publisher forbids it
- Property excludes the target page
- Historical pattern shows excessive repeated exact-match use

## Output

Return target URL, reason, anchor category/text, historical-distribution check, alternative URL when useful, risks, and approval status.

## Handoff

Send to content generation or execution as required.
