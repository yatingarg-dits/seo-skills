# Backlink Discovery

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for Ahrefs, Semrush, Moz, Bing backlink data, Similarweb supporting research, and GuestPostLinks commercial discovery.

Find candidate backlink opportunities from approved sources without assuming they are suitable.

## Prerequisites

Load:

- [01-platform-seo-context.md](01-platform-seo-context.md)
- [04-property-context.md](04-property-context.md)
- [46-backlink-community-source-database.md](46-backlink-community-source-database.md) when using Telegram/Facebook/Slack sources

## Discovery sources

Use only sources available/approved for the workflow, such as:

- Google search operators and manual search
- Competitor backlink research
- Existing agency backlink database
- Historical client sheets
- Publisher relationship lists
- Guest-post opportunity lists
- Resource-page research
- Industry/community websites
- Direct publisher research
- Community-fed links via [31-community-link-intake.md](31-community-link-intake.md)
- Approved/researched community sources from [46-backlink-community-source-database.md](46-backlink-community-source-database.md)

Record the source of every candidate.

## Discovery queries

Build searches from:

- Client niche
- Service/topic
- Geography
- Guest-post/contributor terms
- Resource/listing terms
- Relevant publication categories
- Competitor referring domains

Do not use one generic query across unrelated clients.

## Candidate capture

Store:

- Domain
- Exact opportunity URL if known
- Discovery source
- Date found
- Niche/category
- Geography/language
- Apparent opportunity type
- Free/paid/unknown
- Login/outreach/unknown
- Community source ID when applicable
- Source post/message URL when available
- Notes

## Duplicate check

Before adding a candidate, check:

- Existing master database
- Existing client backlinks
- Previous rejection history
- Previously paid/blocked classification
- Existing publisher relationship

Do not discard a duplicate blindly. Preserve history and route only if re-evaluation is justified.

## Freshness

Candidate websites can change. Store `date_found` and require revalidation before execution if the last check is stale under the team-approved freshness rule.

If no freshness rule exists, return `NEEDS_HUMAN_RULE` rather than inventing a fixed number of days.

## Output status

Use:

- NEW_CANDIDATE
- ALREADY_KNOWN
- PREVIOUSLY_REJECTED
- PAID_KNOWN
- RELATIONSHIP_KNOWN
- NEEDS_REVALIDATION

## Handoff

Send new/revalidated candidates to [32-backlink-qualification.md](32-backlink-qualification.md).
