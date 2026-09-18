---
name: seo-agent-operating-system
description: Modular SEO and content operating system for experienced digital marketing teams. Use when ChatGPT must perform or document SEO keyword research, paid keyword research, website audits, content research/briefing/creation/validation/approval/publishing/monitoring, backlink discovery and qualification, off-page activities, business listings, indexing, performance monitoring, or human-feedback learning. Route every task to the smallest relevant module, preserve platform, agency, client, property, activity, content, and publisher context, and use configured defaults/overrides rather than inventing missing client facts.
---

# SEO Agent Operating System

Use this skill as a router. Load only the modules required for the current task.

## Core operating rules

1. Keep platform, agency, client, property, activity, content, and publisher rules separate.
2. Treat materially different data sources, decisions, or execution paths as separate modules.
3. Retrieve existing content/context before generating new work.
4. Never fabricate client facts, statistics, customers, capabilities, quotations, results, author identities, publisher rules, credentials, or unsupported claims.
5. Put evidence before recommendation and business relevance/user value before SEO volume or keyword density.
6. Do not merge business listings into backlinks.
7. Keep backlink discovery, history, qualification, commercial/access status, activity classification, target/anchor, content, execution, verification, and feedback traceable.
8. Do not merge organic keyword difficulty with paid advertiser competition.
9. Use v1 platform defaults where defined, then apply approved lower-level overrides.
10. Record evidence, decisions, warnings/blocks, approvals, failure reasons, and human feedback.
11. Recommend before executing when judgment or high-risk external action is required.
12. Automate repetition, not accountability.
13. Use [07-seo-content-tool-stack.md](references/07-seo-content-tool-stack.md) as the central tool-control file; do not invent a different tool role in downstream modules.

## Context route

Load as needed:

- [00-skill-map.md](references/00-skill-map.md)
- [01-platform-seo-context.md](references/01-platform-seo-context.md)
- [02-agency-seo-overrides.md](references/02-agency-seo-overrides.md)
- [03-client-context.md](references/03-client-context.md)
- [04-property-context.md](references/04-property-context.md)
- [05-author-brand-identity.md](references/05-author-brand-identity.md)
- [06-client-content-style-rules.md](references/06-client-content-style-rules.md)
- [07-seo-content-tool-stack.md](references/07-seo-content-tool-stack.md) when a task requires tool selection, tool data, tool-specific execution, or tool limitations

## Keyword research route

Organic:
`10-keyword-intake` -> `16-keyword-data-source-priority` -> optional `17-keyword-api-integration` -> `11-organic-keyword-research` -> `13-serp-competitor-analysis` -> `14-keyword-clustering-mapping` -> `15-keyword-validation-output`

Paid:
`10-keyword-intake` -> `16-keyword-data-source-priority` -> optional `17-keyword-api-integration` -> `12-paid-keyword-research` -> `15-keyword-validation-output`

## Website audit route

`20-audit-intake-baseline` -> `28-audit-operating-sequence` -> `21-26` as applicable -> `27-audit-prioritization-qa` -> `53-indexing-monitoring`

Use `29-audit-example-output` only for output-format examples, never as client evidence.

## Content production route

Use [54-content-production-workflow.md](references/54-content-production-workflow.md) as the content orchestrator.

For SEO/keyword-led content:

`15 keyword validation` -> `54 workflow` -> `56 topic/context/existing-content validation` -> `57 source research` when factual research is needed -> `50 brief/layout` -> `58 layout validation` -> `84 creation contract/draft` -> `86 quality/AI/originality` -> `85 internal/external linking` -> `51 SEO/content review` -> `87 PASS/WARNING/BLOCK gate` -> `88 approval/revision` -> `52 publish/verify` -> `53 index/rank/performance`

Always load [55-content-rulebook-governance.md](references/55-content-rulebook-governance.md) for content work and [89-content-human-confidence-governance.md](references/89-content-human-confidence-governance.md) when expert review, ambiguity, confidence, or escalation is involved.

Do not move a draft to approval while unresolved `BLOCK` issues exist. Do not mark published content complete before publication verification.

## Backlink route

For external link opportunities:

`46 community-source database` when community research is needed -> `30/31 discovery` -> `44 historical backlink check` -> `32 qualification` -> `42 commercial/access classification` -> `33 activity classification` -> relevant activity `60-83` -> `34 target/anchor` and `35/36 content/publisher` as needed -> `37 execution` -> `38 verification` -> `44 history update` -> `39 feedback`

Use `43-backlink-benchmark-capacity` for planning capacity, never as a reason to lower quality.

Use `45-publisher-rule-hackernoon` when HackerNoon is the publisher; revalidate before submission.

## Business listing route

`61-business-listing` -> `40-business-listing-discovery` -> `41-business-listing-execution`.

## Output discipline

Preserve source, date, client/property, asset/activity, decision, evidence, reason, confidence when relevant, risk, action, human-review status, approval state, and handoff.
