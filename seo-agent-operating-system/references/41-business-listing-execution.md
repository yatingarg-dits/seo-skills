# Business Listing Execution and Maintenance

## Purpose

When a platform requires a business/directory description, generate it through [90-prompt-library-index.md](90-prompt-library-index.md) and the exact [94-prompt-business-directory-descriptions.md](94-prompt-business-directory-descriptions.md) prompt, then adapt only to verified platform field limits at runtime without modifying the stored prompt.

Use [61-business-listing.md](61-business-listing.md) as the end-to-end activity controller.

Create, claim, correct, verify, and maintain approved business listings using property-approved business data.

## Inputs

Load:

- Qualified platform from [40-business-listing-discovery.md](40-business-listing-discovery.md)
- [04-property-context.md](04-property-context.md)

## Prepare listing data

Use approved property data only:

- Business name
- Primary/secondary category
- Description
- Address or service area
- Phone
- Website URL
- Email when approved
- Opening hours
- Logo/images
- Social profiles
- Services/products

If a required field is missing, mark `MISSING_PROPERTY_CONTEXT`.

## Execution modes

Classify:

- Create new listing
- Claim existing listing
- Correct existing listing
- Remove/merge duplicate
- Verify listing
- Update listing
- Paid listing requiring approval

## Submission

Before submit:

- Match business name to approved format.
- Use correct category.
- Use correct canonical website URL.
- Check NAP consistency where applicable.
- Avoid keyword stuffing business name/description.
- Follow platform field limits/rules.
- Store account/credential reference in approved credential system.

## Verification

Record method:

- Email
- Phone/SMS
- Postcard
- Video
- Document
- Manual review
- Other platform method

Do not claim verification is complete until confirmed.

## Post-live checks

Verify listing loads, business details, website link, category, duplicate status, images/profile display, and public URL.

## Maintenance

Track last checked date, listing status, detail changes, platform policy changes, broken website link, and duplicate/new listing appearance.

## Output status

Use:

- CREATED_PENDING_VERIFICATION
- LIVE_VERIFIED
- CLAIM_PENDING
- CORRECTION_PENDING
- DUPLICATE_ACTION_REQUIRED
- PAID_APPROVAL_REQUIRED
- FAILED_WITH_REASON

## Handoff

Send operational feedback to [39-backlink-feedback-learning.md](39-backlink-feedback-learning.md) only when it affects shared source/quality rules; otherwise update listing-specific records and [53-indexing-monitoring.md](53-indexing-monitoring.md) when listing visibility is monitored.
