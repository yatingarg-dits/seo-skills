# Publisher-Specific Guidelines

## Purpose

Store and apply website-specific publishing rules for publishers with unique editorial, link, identity, account, and commercial requirements.

## Capture per publisher

Record:

- Domain/publisher
- Last verified date
- Source URL/editor communication
- Opportunity type
- Allowed/restricted topics
- Word-count/range if stated
- Title/heading/format rules
- Link limits
- Anchor restrictions
- Follow/nofollow/sponsored policy when known
- External-source diversity requirements
- Image/rights requirements
- Author bio/photo/profile requirements
- Brand-account requirements
- Reference/citation requirements
- Originality/republishing/canonical policy
- AI-content policy if stated
- Submission method
- Review/editorial process
- Turnaround expectation if stated
- Contact/editor details when allowed
- Free/paid status and last verified price date
- Other special rules

## Source priority

Prefer:

1. Current official contributor/editorial guidelines
2. Current editor communication for the specific submission
3. Current approved internal publisher record
4. Older historical notes

## Conflict handling

If two current official pages conflict:

1. Record both rules and URLs.
2. Mark `PUBLIC_RULE_CONFLICT`.
3. Revalidate through current submission UI/editor communication.
4. Use the stricter safe rule for draft preparation when action cannot wait, but do not claim the conflict is resolved.

## Freshness

Store `last_verified_date`. Revalidate operational items such as price, link limits, account requirements, and submission process before use.

## Application

Before generating/submitting content:

1. Match domain.
2. Load current record.
3. Identify mandatory/optional rules.
4. Load author identity and client content rules.
5. Block submission when a mandatory requirement is unmet.
6. Return the exact unmet/conflicting rule.

## Real example

Use [45-publisher-rule-hackernoon.md](45-publisher-rule-hackernoon.md) as a current public-rule example because HackerNoon was explicitly discussed in the team workflow.

## Missing guidelines

If no record exists, use current public instructions when available. Otherwise mark `NO_PUBLISHER_GUIDELINE_RECORD`; do not invent site-specific requirements.
