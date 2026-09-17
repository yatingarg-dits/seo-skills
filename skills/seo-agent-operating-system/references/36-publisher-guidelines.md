# Publisher-Specific Guidelines

## Purpose

Store and apply website-specific publishing rules for publishers with unique requirements.

This file defines the schema and decision process. Actual publisher rules should be stored as structured records or separate references linked to the publisher/domain.

## Capture per publisher

Record:

- Domain
- Publisher name
- Last verified date
- Opportunity type
- Allowed topics
- Restricted topics
- Required word count/range if explicitly stated
- Title requirements
- Heading requirements
- Link count limits
- Link/anchor restrictions
- Follow/nofollow/sponsored policy when known
- Image requirements
- Image rights/source requirements
- Author bio requirement
- Author photo requirement
- Reference/citation requirements
- Originality policy
- AI-content policy if stated
- Formatting style
- Submission method
- Review/editorial process
- Turnaround expectation if known
- Contact/editor details when allowed
- Paid/free status
- Other special rules

## Source priority

Prefer rules from:

1. Current official contributor/editorial guidelines
2. Current editor communication
3. Current approved internal record
4. Older historical notes

If rules conflict, use the newest authoritative source and flag the conflict.

## Freshness

Publisher rules change. Store `last_verified_date`.

If the rule is old or the site behavior differs, mark `NEEDS_REVALIDATION`.

## Application

Before generating/submitting content:

1. Match the candidate domain.
2. Load its latest rules.
3. Identify mandatory versus optional requirements.
4. Block submission when a mandatory requirement is unmet.
5. Return the exact unmet rule.

## Missing guidelines

If no site-specific record exists:

- Do not invent requirements.
- Use only publicly visible/current instructions if available.
- Otherwise mark `NO_PUBLISHER_GUIDELINE_RECORD` and use platform defaults only where safe.

## Handoff

Use these rules in:

- [35-backlink-content-generation.md](35-backlink-content-generation.md)
- [37-backlink-outreach-submission.md](37-backlink-outreach-submission.md)
