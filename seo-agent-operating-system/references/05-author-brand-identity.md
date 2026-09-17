# Author, Signature, and Brand Identity

## Purpose

Store the approved human/brand identity used in guest posts, articles, profiles, directories, press releases, podcasts, Web 2.0 properties, and other external publishing activities.

Keep identity data separate from publisher-specific rules.

## Context precedence

Use:

`Platform -> Agency -> Client -> Property -> Activity/Publisher`

A publisher may require a different format, but it must not invent or alter client facts.

## Required identity fields

Capture when available:

- Author full name
- Job title/designation
- Company/brand name
- Short author bio
- Long author bio
- Approved profile photo reference
- Approved company logo reference
- Website/homepage URL
- Approved social/profile URLs
- Public contact details if allowed
- Signature text
- Footer text
- Brand boilerplate/company description
- Location/office wording if approved
- Credentials/qualifications that may be claimed
- Topics the author is qualified/approved to discuss
- Restricted claims/topics

## Selection rules

1. Use a real approved author/brand identity.
2. Match the author to the topic where possible.
3. Use property-specific identity before client-wide defaults when both exist.
4. Do not create fake personas, qualifications, job titles, awards, or experience.
5. Do not expose private contact or credential data in public copy.
6. Do not reuse one person's bio for another person.

## Bio variants

Maintain approved variants:

- `BIO_SHORT`: about 40-70 words unless a publisher rule overrides it.
- `BIO_MEDIUM`: about 70-120 words.
- `BIO_LONG`: use only when specifically required.
- `SIGNATURE`: name + role + brand + approved URL/profile fields.

Word ranges are formatting defaults, not client facts.

## Publisher adaptation

When [36-publisher-guidelines.md](36-publisher-guidelines.md) requires a specific author format:

1. Preserve factual identity.
2. Adapt length/format only.
3. Remove fields the publisher forbids.
4. Never add unapproved promotional claims to satisfy a form.

## Output record

Return:

- Identity record ID
- Author/brand used
- Property
- Bio variant
- Signature/footer variant
- Public URLs used
- Publisher/activity
- Approval status
- Last verified date

## Missing data

If author or signature data is required but unavailable, return `MISSING_AUTHOR_IDENTITY`.
