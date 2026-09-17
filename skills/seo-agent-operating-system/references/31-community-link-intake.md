# Community and Shared-Sheet Backlink Intake

## Purpose

Process backlink opportunities sourced from Telegram, Slack, Facebook groups, shared spreadsheets, or similar communities.

These sources are discovery inputs, not automatic approvals.

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

- Community/platform
- Group/channel name when permitted
- Date received
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

Never treat a claim in a shared sheet as verified fact.

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
