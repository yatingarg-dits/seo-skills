# Backlink Website Qualification

## Purpose

Decide whether a candidate website is suitable using relevance, audience, real visibility, risk, authority, indexability, and manual quality—not DA alone.

## Inputs

Use candidates from discovery/community intake and check [44-historical-backlink-database.md](44-historical-backlink-database.md) before rework.

Load property context.

## Platform default v1 thresholds

These are overridable platform defaults, not Google standards.

### Topical relevance

- HIGH: preferred
- MEDIUM/adjacent: acceptable with clear audience/context fit
- LOW: reject unless a documented PR/brand rationale exists

### Audience fit

- HIGH/MEDIUM: continue
- LOW: manual review; reject for link-building-only objective

### Geography

Prefer target-market or genuinely global publishers.

If available audience data shows less than about 10% from the target geography and the site is not globally relevant to the client's audience, mark `MANUAL_REVIEW_GEOGRAPHY` rather than auto-approve.

### Domain Authority (Moz)

- `DA >= 30`: preferred supporting authority signal
- `DA 20-29`: conditional/manual review
- `DA < 20`: normally reject for generic outreach, but allow documented niche/local/institutional exceptions

### Page Authority (Moz)

For an established existing placement page:

- `PA >= 20`: preferred
- `PA 10-19`: conditional
- `PA < 10`: manual review

Do not reject a newly created editorial page solely because PA starts low.

### Spam Score (Moz)

- `0-15%`: preferred
- `16-30%`: manual review
- `>30%`: normally reject unless a strong documented manual exception exists

Never use Spam Score alone.

### Organic visibility

Use estimated traffic and ranking keywords as legitimacy/support signals.

Default traffic interpretation:

- `>=1000 estimated organic visits/month`: strong supporting signal when relevant
- `100-999`: acceptable with relevance/quality
- `1-99`: manual review; can still pass for real niche/local/institutional sites
- `0`: normally reject for generic link building unless the site is new, authoritative offline/institutional, or another documented exception applies

### Traffic trend

Manual review when there is:

- Roughly >50% sustained decline across a comparable 6-12 month period
- Abrupt unexplained spike/drop
- Major keyword/traffic geography shift

### Indexation

Prefer sites where homepage and recent relevant content are indexable/discoverable.

For manual spot checks, review several recent pages; if most recent content appears non-indexed/noindex/canonicalized elsewhere, pause and investigate.

## Manual website quality

Check:

- Real brand/business signals
- About/contact/editorial identity
- Recent useful publishing
- Niche consistency
- Navigation/usability
- Excessive unrelated categories
- Link-farm/network footprints
- Hacked/spam pages
- Adult/casino/pharma contamination when unrelated
- Excessive sponsored/commercial posts
- Outbound-link/anchor patterns

## Existing relationship/link

Check historical database for live/lost/failed/paid placement before recommending a new one.

## Decision statuses

Use:

- APPROVED
- APPROVED_WITH_CONDITIONS
- MANUAL_REVIEW
- PAID_VALID
- OUTREACH_VALID
- REJECTED
- ALREADY_USED
- WEBSITE_UNAVAILABLE
- NEEDS_REVALIDATION

## Mandatory reason

Every non-approved status must state the exact reason/evidence.

## Handoff

Classify commercial/access status with [42-backlink-commercial-classification.md](42-backlink-commercial-classification.md), then activity with [33-backlink-activity-classification.md](33-backlink-activity-classification.md).
