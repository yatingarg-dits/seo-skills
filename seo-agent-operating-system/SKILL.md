---
name: seo-agent-operating-system
description: Modular SEO operating system for experienced digital marketing teams. Use when ChatGPT must perform or document SEO keyword research, paid keyword research, website audits, backlink discovery and qualification, off-page SEO activities, backlink content and publishing workflows, business listings, SEO content workflows, indexing, monitoring, or human-feedback learning. Route every task to the smallest relevant module, preserve platform versus client/property context, and never invent missing thresholds or client rules.
---

# SEO Agent Operating System

Use this skill as a router. Load only the modules required for the current task.

## Core operating rules

1. Keep **platform rules**, **agency overrides**, and **client/property context** separate.
2. Treat each materially different source, decision process, or execution path as a separate module.
3. Do not merge business listings into backlinks.
4. Do not merge backlink discovery, qualification, content, execution, verification, and feedback into one step.
5. Do not merge organic keyword difficulty with paid advertising competition.
6. Prefer real team rules and examples over generic SEO assumptions.
7. If a required threshold, credential rule, client preference, or site-specific guideline is missing, return `NEEDS_HUMAN_RULE` instead of inventing it.
8. Record rejection reasons, not only accept/reject outcomes.
9. Keep backlink-quality feedback separate from content-quality feedback.
10. Use human feedback to improve future recommendations; do not silently override approved rules.

## Context layers

Load these first when needed:

- [00-skill-map.md](references/00-skill-map.md) - complete routing map.
- [01-platform-seo-context.md](references/01-platform-seo-context.md) - generic operating rules.
- [02-agency-seo-overrides.md](references/02-agency-seo-overrides.md) - approved agency-level overrides.
- [03-client-context.md](references/03-client-context.md) - client-wide business and brand context.
- [04-property-context.md](references/04-property-context.md) - domain/property-specific SEO context.

## Keyword research route

For organic research:
`10-keyword-intake` -> `11-organic-keyword-research` -> `13-serp-competitor-analysis` -> `14-keyword-clustering-mapping` -> `15-keyword-validation-output`

For paid research:
`10-keyword-intake` -> `12-paid-keyword-research` -> `15-keyword-validation-output`

## Website audit route

`20-audit-intake-baseline` -> `21-technical-crawl-indexation` -> `22-onpage-content-audit` -> `23-architecture-internal-linking` -> `24-performance-mobile-schema` -> optional `25-local-international` -> `26-analytics-tracking` -> `27-audit-prioritization-qa`

## Off-page and backlink route

Start with [59-offpage-activity-map.md](references/59-offpage-activity-map.md) when the requested activity is one of the team's defined off-page activities.

For external opportunities that create or may create a backlink:
`30-backlink-discovery` and/or `31-community-link-intake` -> `32-backlink-qualification` -> `33-backlink-activity-classification` -> relevant activity file `60-83` -> target/content/publisher steps as required -> `37-backlink-outreach-submission` when applicable -> `38-backlink-verification-monitoring` -> `39-backlink-feedback-learning`

Use [60-link-building.md](references/60-link-building.md) for the overall acquisition strategy and [72-backlinks.md](references/72-backlinks.md) for link-level execution/recording.

## Business listing route

Use [61-business-listing.md](references/61-business-listing.md) as the activity controller, then `40-business-listing-discovery` -> `41-business-listing-execution`.

Do not route business listings through generic backlink execution merely because a citation or link may be created.

## Indexing/discovery off-page activities

Use [62-ping-submission.md](references/62-ping-submission.md) and [68-search-engine-submission.md](references/68-search-engine-submission.md) with `53-indexing-monitoring` rather than treating them as backlink-building activities.

## SEO content route

`50-seo-content-brief` -> `51-seo-content-review` -> `52-onpage-implementation-publishing` -> `53-indexing-monitoring`

For backlink-specific content, prefer `35-backlink-content-generation` plus `36-publisher-guidelines`.

## Output discipline

For every module, preserve:

- Input source
- Date checked
- Client/property
- Decision
- Evidence
- Reason
- Action
- Human review status
- Next module/handoff

When a task spans multiple modules, execute them sequentially and keep intermediate outputs traceable.
