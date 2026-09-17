# Backlink Website Qualification

## Purpose

Decide whether a candidate website is suitable for backlink activity using multiple quality signals, not DA alone.

## Inputs

Use candidates from:

- [30-backlink-discovery.md](30-backlink-discovery.md)
- [31-community-link-intake.md](31-community-link-intake.md)

Load [04-property-context.md](04-property-context.md).

## Qualification dimensions

### 1. Topical relevance

Check:

- Same or adjacent niche
- Relevant content category
- Natural contextual fit
- Client topic coverage

Treat relevance as a primary decision signal.

### 2. Audience fit

Check when data is available:

- Audience type
- B2B/B2C fit
- Industry fit
- Country distribution
- Language
- Potential referral relevance

### 3. Geography

Compare publisher geography with property target markets. Do not reject global sites merely because the TLD differs.

### 4. Authority metrics

Record only metrics actually available, with source and date:

- DA
- PA
- DR
- Authority Score
- Other approved authority metric

Do not invent thresholds. Apply only team-approved cutoffs from [01-platform-seo-context.md](01-platform-seo-context.md).

### 5. Spam/risk metrics

Record Spam Score or other approved risk signals with source/date.

Do not make a final decision from Spam Score alone.

### 6. Organic visibility

When available review:

- Estimated organic traffic
- Target-country traffic
- Ranking keyword count
- Relevant ranking topics
- Trend direction
- Sudden collapses/spikes

### 7. Indexation

Check where practical:

- Homepage discoverability/indexation
- Recent article indexation
- Opportunity section indexation
- Existing contributor post indexation
- `noindex`/canonical behavior on target templates

### 8. Manual website quality

Review:

- Real brand/business signals
- About/contact presence
- Realistic authors/editorial identity
- Recent publishing
- Content usefulness
- Navigation/usability
- Excessive unrelated categories
- Obvious link-farm patterns
- Hacked/spam pages
- Adult/casino/pharma contamination where irrelevant/risky
- Excessive sponsored/commercial posts

### 9. Outbound-link behavior

Check for:

- Excessive unrelated external links
- Repetitive commercial anchors
- Obvious sitewide selling patterns
- Network/template footprints

### 10. Existing client relationship/link

Check whether the property already has:

- Live backlink
- Historical backlink
- Failed placement
- Publisher contact
- Paid agreement

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
- NEEDS_HUMAN_RULE

## Mandatory reason

Every non-approved status must include a reason.

Common reasons:

- Irrelevant niche
- Wrong audience/geography
- Poor real traffic/visibility
- Severe decline
- Deindexed/poor indexability
- Link farm/network risk
- Excessive outbound selling
- Low editorial quality
- Hacked/offline
- Already used
- Paid only
- Insufficient evidence
- Other documented reason

## Handoff

Send approved/manual-review candidates to [33-backlink-activity-classification.md](33-backlink-activity-classification.md).
