# Backlink Commercial and Access Classification

## Purpose

Classify each backlink opportunity as free, paid, exchange, outreach, credential-based, unavailable, or unknown before execution.

Do not use a single "paid = blacklist" rule.

## Commercial status

Use exactly one primary status:

- `FREE_SELF_PUBLISH` - no payment; team can publish with approved access.
- `FREE_EDITORIAL` - no payment; publisher/editor approval required.
- `PAID_SPONSORED` - publisher charges for sponsored/advertising placement.
- `PAID_MEDIATOR` - third party/intermediary charges to obtain placement.
- `EXCHANGE_COLLABORATION` - reciprocal/collaboration arrangement.
- `RELATIONSHIP_BASED` - existing editorial/partner relationship, no standard public route.
- `UNKNOWN_COMMERCIAL_STATUS` - not yet verified.

## Access status

Record separately:

- `CREDENTIALS_AVAILABLE`
- `LOGIN_REQUIRED`
- `NEW_ACCOUNT_REQUIRED`
- `OUTREACH_REQUIRED`
- `INVITE_REQUIRED`
- `SUBMISSION_FORM`
- `NO_ACCESS_PATH`
- `WEBSITE_UNAVAILABLE`

## Rules

1. Keep commercial status separate from website quality.
2. A high-quality paid publisher can remain `PAID_VALID` for paid campaigns.
3. Do not recommend paid opportunities in a free-only task.
4. Do not permanently blacklist a site solely because it became paid.
5. Record price/currency/date only when actually verified.
6. Mark old price data `NEEDS_REVALIDATION`.
7. Never claim credentials exist unless access is confirmed.
8. Store credentials in the approved secret/credential system, not in skill text or public sheets.

## Search-policy guardrail

Paid/sponsored placements must not be acquired with the primary purpose of passing ranking credit. For advertising/sponsorship links, require publisher handling consistent with applicable search-engine policies (for Google, typically `rel="sponsored"` or `nofollow`).

Do not use automated low-quality link creation, excessive exchanges, hidden links, or low-value directory/comment/forum links for ranking manipulation.

## Decision examples

- Good site + fee required -> `PAID_VALID`, not `REJECTED`.
- Good site + no login + editor email found -> `FREE_EDITORIAL` + `OUTREACH_REQUIRED`.
- Community sheet says "free" but site requests payment -> update to paid status based on current evidence.
- Website dead -> `WEBSITE_UNAVAILABLE` regardless of old free/paid label.

## Handoff

Use quality from [32-backlink-qualification.md](32-backlink-qualification.md), then activity classification in [33-backlink-activity-classification.md](33-backlink-activity-classification.md).
