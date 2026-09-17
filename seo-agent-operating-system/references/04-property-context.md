# Property Context

## Purpose

Store domain/property-specific knowledge used for SEO, content, backlink, and listing decisions.

Load [03-client-context.md](03-client-context.md) for client-wide context first.

## Property identity

Capture:

- Property/domain
- Property purpose
- Business unit/brand if different from client
- Primary services/products on this property
- Secondary services/products
- Target audience for this property
- B2B/B2C
- Target industries
- Target countries/cities
- Languages
- Customer problems
- Property-specific USP
- Direct competitors

## SEO context

Capture:

- Priority pages
- Priority services
- Existing keyword targets
- Existing ranking pages
- Content clusters
- Conversion actions
- Local markets
- International markets
- Known SEO limitations
- CMS/technology when relevant

## Backlink/content context

Capture:

- Approved target URLs
- Pages excluded from backlinking
- Property-specific authors
- Property-specific bios/signatures
- Footer text
- Approved property description
- Approved URLs
- Anchor restrictions
- Publisher relationship notes
- Paid-link policy when property-specific

## Publishing context

Store property defaults only. Website-specific publisher requirements belong in [36-publisher-guidelines.md](36-publisher-guidelines.md).

## Missing data behavior

If a task requires a property fact that is absent:

1. Do not fabricate it.
2. Mark `MISSING_PROPERTY_CONTEXT`.
3. Complete only supported parts.
4. Route missing fields for human completion.

## Updates

Record:

- Changed field
- Old value
- New value
- Changed by
- Date
- Reason

## Handoffs

This context can be loaded by keyword, audit, backlink, business-listing, content, and monitoring modules.
