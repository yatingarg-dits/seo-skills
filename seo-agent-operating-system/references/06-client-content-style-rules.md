# Client Content, Tone, Claims, and Terminology Rules

## Purpose

Store the client/property communication rules that every website-content and external-publishing module must follow.

## Inputs

Load:

- [03-client-context.md](03-client-context.md)
- [04-property-context.md](04-property-context.md)
- [05-author-brand-identity.md](05-author-brand-identity.md) when an author/brand identity is used

## Required rule groups

Capture:

### Tone and voice

- Formality level
- Technical depth
- First-person/third-person preference
- Brand personality descriptors
- Preferred CTA style
- Words/phrases to prefer
- Words/phrases to avoid

### Claims

Classify claims as:

- APPROVED_FACT
- APPROVED_WITH_SOURCE
- REQUIRES_REVIEW
- PROHIBITED
- UNKNOWN

Examples include years of experience, client counts, locations, certifications, rankings, awards, pricing, performance claims, guarantees, and comparative/superlative claims.

### Terminology

Store:

- Approved service/product names
- Approved abbreviations
- Industry terminology
- Client-preferred spelling/capitalization
- Competitor mention rules
- Location naming rules

### Exclusions

Store:

- Topics the client does not want covered
- Industries/markets not served
- Unsupported services
- Legal/compliance-sensitive topics
- Promotional language the client rejects

## Execution rules

1. Prefer client-approved terminology over generic synonyms where meaning is unchanged.
2. Never strengthen a claim beyond the approved source.
3. If the draft requires a missing business fact, mark `MISSING_CLIENT_FACT`.
4. Do not infer certifications, awards, customer counts, locations, or performance guarantees.
5. Apply publisher rules after client rules; publisher formatting cannot override factual/client restrictions.

## Review output

For every flagged sentence return:

- Text/reference
- Rule triggered
- Severity
- Required edit
- Approval owner when known

## Handoff

Apply these rules in:

- [35-backlink-content-generation.md](35-backlink-content-generation.md)
- [50-seo-content-brief.md](50-seo-content-brief.md)
- [51-seo-content-review.md](51-seo-content-review.md)
- Activity files in [59-offpage-activity-map.md](59-offpage-activity-map.md)

## Content-production enforcement

Apply these rules during:

- Topic/brief decisions through [56-content-topic-research-validation.md](56-content-topic-research-validation.md) and [50-seo-content-brief.md](50-seo-content-brief.md)
- Drafting through [84-content-creation-contract.md](84-content-creation-contract.md)
- Quality review through [86-content-quality-ai-originality.md](86-content-quality-ai-originality.md)
- Validation through [87-content-validation-gate.md](87-content-validation-gate.md)
- Approval/revision through [88-content-approval-revision.md](88-content-approval-revision.md)

Client style rules can narrow platform guidance but cannot authorize fabrication or unsupported material claims.
