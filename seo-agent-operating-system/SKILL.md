---
name: seo-agent-operating-system
description: Modular SEO operating system for experienced digital marketing teams. Use when ChatGPT must perform or document SEO keyword research, paid keyword research, website audits, backlink discovery and qualification, backlink content and publishing workflows, business listings, SEO content workflows, indexing, monitoring, or human-feedback learning. Route every task to the smallest relevant module, preserve platform, agency, client, property, activity, and publisher context, and use configured defaults/overrides rather than inventing missing client facts.
---

# SEO Agent Operating System

Use this skill as a router. Load only the modules required for the current task.

## Core operating rules

1. Keep platform, agency, client, property, activity, and publisher rules separate.
2. Treat materially different data sources, decisions, or execution paths as separate modules.
3. Do not merge business listings into backlinks.
4. Keep backlink discovery, historical memory, qualification, commercial/access status, activity classification, target/anchor, content, execution, verification, and feedback traceable.
5. Do not merge organic keyword difficulty with paid advertiser competition.
6. Use the v1 platform defaults where defined, then apply approved lower-level overrides.
7. Never fabricate client facts, author identities, publisher rules, credentials, or unsupported claims.
8. Record rejection/failure reasons and human feedback.

## Context route

Load as needed:

- [00-skill-map.md](references/00-skill-map.md)
- [01-platform-seo-context.md](references/01-platform-seo-context.md)
- [02-agency-seo-overrides.md](references/02-agency-seo-overrides.md)
- [03-client-context.md](references/03-client-context.md)
- [04-property-context.md](references/04-property-context.md)
- [05-author-brand-identity.md](references/05-author-brand-identity.md)
- [06-client-content-style-rules.md](references/06-client-content-style-rules.md)

## Keyword research route

Organic:
`10-keyword-intake` -> `16-keyword-data-source-priority` -> optional `17-keyword-api-integration` -> `11-organic-keyword-research` -> `13-serp-competitor-analysis` -> `14-keyword-clustering-mapping` -> `15-keyword-validation-output`

Paid:
`10-keyword-intake` -> `16-keyword-data-source-priority` -> optional `17-keyword-api-integration` -> `12-paid-keyword-research` -> `15-keyword-validation-output`

## Website audit route

`20-audit-intake-baseline` -> `28-audit-operating-sequence` -> `21-26` as applicable -> `27-audit-prioritization-qa` -> `53-indexing-monitoring`

Use `29-audit-example-output` only for output-format examples, never as client evidence.

## Backlink route

For external link opportunities:

`30/31 discovery` -> `44 historical backlink check` -> `32 qualification` -> `42 commercial/access classification` -> `33 activity classification` -> relevant activity `60-83` -> `34 target/anchor` and `35/36 content/publisher` as needed -> `37 execution` -> `38 verification` -> `44 history update` -> `39 feedback`

Use `43-backlink-benchmark-capacity` for planning capacity, never as a reason to lower quality.

Use `45-publisher-rule-hackernoon` when HackerNoon is the publisher; revalidate before submission.

## Business listing route

`61-business-listing` -> `40-business-listing-discovery` -> `41-business-listing-execution`.

## SEO content route

`50-seo-content-brief` -> `51-seo-content-review` -> `52-onpage-implementation-publishing` -> `53-indexing-monitoring`.

## Output discipline

Preserve source, date, client/property, decision, evidence, reason, action, human-review status, and handoff.
