# Community and Shared-Sheet Backlink Intake

## Purpose

Process backlink opportunities sourced from Telegram, Slack, Facebook groups, shared spreadsheets, or similar communities.

These sources are discovery inputs, not automatic approvals. Load [46-backlink-community-source-database.md](46-backlink-community-source-database.md) when using a known/researched community.

## Supported intake forms

Examples:

- Telegram channel message/link list
- Slack collaboration/community post
- Facebook/community shared sheet
- Excel/CSV link list
- Manually copied URLs
- Publisher/mediator lists

## Capture source context

For each batch record:

- Community source ID from the source database when available
- Community/platform
- Group/channel name when permitted
- Date received
- Source last-verified date
- Exact post/message URL or message reference when available
- Shared by/source identity when relevant and allowed
- Free/paid claim
- Credential claim
- Notes from the post/sheet

## URL extraction

Extract and normalize:

- Root domain
- Exact URL
- Claimed opportunity type
- Claimed price
- Claimed access/login status
- Claimed contact method

Never treat a claim in a shared sheet, group post, seller message, or channel description as verified fact.

## Initial checks

Flag:

- Duplicate domain
- Previously rejected domain
- Previously classified paid domain
- Website unavailable
- Invalid URL
- Obvious irrelevant niche
- Existing client backlink

## Access classification

Record one:

- DIRECT_SELF_PUBLISH
- LOGIN_AVAILABLE
- LOGIN_REQUIRED
- NEW_ACCOUNT_REQUIRED
- OUTREACH_REQUIRED
- PAID_MEDIATOR
- EXCHANGE_COLLABORATION
- UNKNOWN

Do not store actual passwords in this markdown workflow. Use the organization-approved credential system.

## Community-source controls

Apply the source role from [46-backlink-community-source-database.md](46-backlink-community-source-database.md):

- `DIRECT_OPPORTUNITY`: intake candidates, but still qualify every domain.
- `RELATIONSHIP_NETWORKING`: use for relationships/research; do not assume solicitation is permitted.
- `MARKETPLACE_HIGH_RISK`: manual review is mandatory before outreach, exchange, registration, or payment.
- `RESEARCH_ONLY`: do not route placements to execution; use only for intelligence/risk learning.

If current group rules conflict with the database, current rules win and the database must be updated.

## Paid versus free handling

If the team confirms a site is paid, classify it as paid. Do not permanently blacklist it if paid opportunities may be requested later.

Use separate pools/statuses for:

- Free
- Paid
- Exchange/collaboration
- Unknown

## Security/risk

Do not log into suspicious websites or download unknown files merely because a community shared them. Route suspicious candidates to manual review.

## Output

Produce normalized candidate records and send them to [32-backlink-qualification.md](32-backlink-qualification.md).
