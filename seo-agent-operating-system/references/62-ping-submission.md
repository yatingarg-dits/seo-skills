# Ping Submission

## Source activity

Send a notification through an approved pinging service after publishing or materially updating content.

## Purpose

Use ping submission only as a conditional URL/content-discovery activity. Do not treat a ping as proof of crawling or indexing.

## Prerequisites

Require final live URL, successful HTTP response, indexable page unless testing, correct canonical, no accidental `noindex`, and an approved ping service/tool.

For client-owned URLs also use [53-indexing-monitoring.md](53-indexing-monitoring.md).

## Process

1. Confirm the page is live and technically eligible for discovery/indexing.
2. Check whether the team still uses ping submission for this property/platform.
3. Select an approved ping service only if listed/configured through [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) or an approved agency override.
4. Enter only the required URL/feed/site information.
5. Submit once according to the approved cadence.
6. Record service, date, URL, and submission response.
7. Do not repeatedly ping the same URL to force indexing.
8. Monitor discovery/indexing separately through [53-indexing-monitoring.md](53-indexing-monitoring.md).

## Stop/review conditions

Do not submit when the URL is not live, intentionally non-indexable, canonicalized elsewhere unexpectedly, or the ping service is unapproved/unsafe/unavailable.

If the team has no rule for this activity, return `NEEDS_HUMAN_RULE`.

## Success criteria

Success means the approved ping request was submitted and recorded. It does **not** mean the page is indexed or ranked.

## Output record

Store URL, content type, ping service, submission date/time, response, technical eligibility check, follow-up indexing status, and failure reason.
