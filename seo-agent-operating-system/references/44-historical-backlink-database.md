# Historical Backlink Database

## Purpose

Preserve what the team has already researched, attempted, published, lost, rejected, or paid for so the agent does not repeat work blindly.

## Record level

Maintain both:

- Domain-level publisher record
- Opportunity/page-level record
- Client/property placement record

Do not collapse all history into one "used/not used" field.

## Required fields

Capture when available:

- Root domain
- Opportunity URL
- Source/discovery channel
- First discovered date
- Last checked date
- Activity type
- Niche/category
- Geography/language
- DA/PA/SS/DR/traffic values with source/date
- Commercial status
- Price/currency/date when verified
- Access status
- Contact/editor
- Publisher guideline record
- Client/property
- Target URL
- Anchor text/category
- Content reference
- Submission date
- Live URL
- Live date
- Link attribute
- Indexation status when tracked
- Current status
- Failure/rejection reason
- Lost-link date/reason
- Human feedback

## Core statuses

Use:

- DISCOVERED
- QUALIFIED
- REJECTED
- OUTREACH_PENDING
- OUTREACH_SENT
- RESPONSE_RECEIVED
- SUBMITTED
- PUBLISHED
- LIVE_VERIFIED
- LOST
- PAID_VALID
- UNAVAILABLE
- BLOCKED_FOR_PROPERTY
- NEEDS_REVALIDATION

## Deduplication logic

Before new research/execution:

1. Normalize root domain.
2. Check exact opportunity URL.
3. Check whether this property already has a live link from the domain.
4. Check whether the same activity was attempted previously.
5. Review rejection/failure reason and date.
6. Re-open only when conditions changed or a new valid opportunity exists.

## Reuse rules

Do not automatically reject a previously used domain. Consider:

- Is a new editorial placement strategically justified?
- Is the target page different?
- Is the new page genuinely relevant?
- Is referring-domain diversity a higher priority?

Default to new relevant referring domains when value is otherwise similar.

## Staleness

Historical metrics, price, access, and publishing rules can change. Store dates and revalidate stale operational data before execution.

## Handoff

Use before [32-backlink-qualification.md](32-backlink-qualification.md) and update after [38-backlink-verification-monitoring.md](38-backlink-verification-monitoring.md) and [39-backlink-feedback-learning.md](39-backlink-feedback-learning.md).
