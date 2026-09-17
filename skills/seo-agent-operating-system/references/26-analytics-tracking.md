# Analytics and Tracking Audit

## Purpose

Verify that SEO outcomes can be measured and that tracking does not create misleading performance conclusions.

## Systems

Check availability/configuration of:

- GA4
- Google Tag Manager
- Google Search Console
- Consent tooling where applicable
- Call tracking when used
- CRM/lead capture integration when available

## Core validation

Check:

- Tracking present on intended pages
- Duplicate tags/events
- Cross-domain behavior when relevant
- Referral exclusions where relevant
- Internal traffic handling if configured
- Form submission events
- Phone-call events
- Purchase/revenue events
- Demo/booking events
- Thank-you-page events
- Key event/conversion definitions
- UTM handling where relevant

## SEO reporting validation

Confirm ability to report:

- Organic traffic
- Organic landing pages
- Organic conversions
- Organic revenue/value when applicable
- Search Console clicks/impressions/CTR/position
- Branded versus non-branded views where methodology exists
- Geography/device where needed

## Data-quality checks

Flag:

- Missing historical periods
- Sudden tracking breaks
- Duplicate conversions
- Event-name changes
- Major discrepancy between systems requiring investigation
- Bot/internal traffic contamination when evident

## Guardrails

- Do not infer business success from traffic alone.
- Do not compare periods without noting major tracking changes.
- Do not claim attribution precision beyond available data.

## Output

Return:

- Tracking item
- Status
- Evidence
- Business impact
- Recommended fix
- Owner

Route to [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).
