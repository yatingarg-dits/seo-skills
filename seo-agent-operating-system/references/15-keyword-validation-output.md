# Keyword Validation and Final Output

## Purpose

Convert raw keyword research into an approved action set with explicit reasons.

## Inputs

Use organic/paid research plus SERP/clustering outputs and property context.

## Validate every keyword/cluster

Check:

- Business/property fit
- Search intent
- Target geography/language
- Demand + source
- Organic difficulty/provider when relevant
- Paid competition/bid when relevant
- Live SERP evidence for organic priorities
- Existing rank/page
- Landing-page fit
- Conversion potential
- Cannibalization risk
- Content/resource requirement
- Google ranking-system/spam-policy risk from [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md)
- AI/LLM visibility objective from [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md) when in scope

## Final statuses

Use:

- APPROVE_EXISTING_PAGE_OPTIMIZATION
- APPROVE_NEW_PAGE
- APPROVE_SUPPORTING_CONTENT
- APPROVE_PAID
- APPROVE_BOTH
- HOLD_FUTURE
- REJECT_IRRELEVANT
- REJECT_INTENT_MISMATCH
- REJECT_CANNIBALIZATION
- REJECT_NO_VALID_LANDING_PAGE
- REJECT_CLIENT_EXCLUSION
- NEEDS_HUMAN_REVIEW

## Priority

Classify High/Medium/Low using business impact and realistic opportunity, not search volume alone.

## Required output columns

- Keyword/cluster
- Organic/Paid/Both/Neither
- Intent
- Business relevance
- Search volume + source
- Organic KD + provider if applicable
- Ads competition/bid if applicable
- Existing rank/URL
- Target URL/action
- Priority
- Reason
- Human approval status

## Source conflicts

Apply [16-keyword-data-source-priority.md](16-keyword-data-source-priority.md). Preserve conflicting provider metrics rather than averaging them.

## Handoff

When the requested output is Google Search Ad copy, use [90-prompt-library-index.md](90-prompt-library-index.md) and [93-prompt-google-search-ads.md](93-prompt-google-search-ads.md).

Approved organic clusters feed content/on-page/audit modules. Approved paid clusters feed the paid campaign workflow outside this skill when available.

## Content handoff

For approved organic/supporting-content clusters, hand off to [54-content-production-workflow.md](54-content-production-workflow.md).

The first content-stage checks are [56-content-topic-research-validation.md](56-content-topic-research-validation.md) for context, existing-content conflict, topic options, uniqueness, and final topic direction.
