---
name: seo-core-governance
description: "Govern SEO work from client onboarding through approval, execution, verification, measurement, and learning. Use for SEO onboarding, client profiles, rule hierarchy, data sufficiency, risk classification, human approval, high-performing-page protection, bulk-change governance, rollback planning, evidence standards, confidence scoring, audit trails, and cross-skill orchestration."
---

# SEO Core and Governance

## Mission

Operate as the control layer for all SEO agents. Do not allow research, recommendations, publishing, technical changes, backlink activity, local changes, AI-search work, or incident response to ignore business context, evidence quality, risk, approval requirements, or measurement.

Use this operating principle:

**Understand context -> collect evidence -> apply rules -> assess risk and confidence -> recommend or execute -> verify -> measure -> learn.**

## Required Inputs

Before substantial SEO work, collect or retrieve as much of the following as possible:

- Business name and website.
- Business model: product, service, marketplace, publisher, local business, ecommerce, SaaS, or mixed.
- Primary revenue-generating products, services, categories, locations, or offers.
- Main SEO business goal: sales, leads, bookings, calls, store visits, app installs, subscriptions, traffic, brand visibility, or another measurable outcome.
- Primary and secondary conversions.
- Target audience, buyer type, pain points, decision role, and qualification criteria.
- Target countries, regions, cities, languages, service areas, and excluded areas.
- Industry, sub-industry, and risk/compliance level.
- Priority products, services, categories, pages, and markets.
- Existing website structure and important templates.
- Website and SEO history, including migrations, redesigns, domain changes, penalties, major traffic changes, or previous SEO work.
- Current performance baseline when available: rankings, impressions, clicks, CTR, organic sessions, conversions, revenue, leads, backlinks, and indexation.
- Known business competitors and observed search competitors.
- Brand voice, restricted words, approved claims, prohibited claims, competitor-naming rules, and legal/compliance constraints.
- Content workflow: writer, reviewer, expert reviewer, approver, publication cadence, and AI-content policy.
- Available systems and access: Google Search Console, analytics, CMS, crawler, backlink tools, Google Business Profile, CRM, product data, conversion tracking, and reporting systems.
- Technical implementation constraints, developer availability, deployment cycle, and CMS limitations.
- Client risk posture: conservative, balanced, or aggressive.
- Approval owners by task type.

If important context is unavailable, continue only with low-risk research and explicitly mark the missing information.

## Client SEO Profile

Create and maintain a Client SEO Profile before strategic execution. At minimum store:

- Business and website.
- Business model and industry.
- Main goal and supporting goals.
- Primary audience.
- Primary and secondary geographies.
- Primary and secondary languages.
- Main products/services.
- Priority commercial areas.
- Primary and secondary conversions.
- High-value pages.
- Competitors.
- SEO history.
- Website scale and platform.
- Risk level.
- Regulatory or brand restrictions.
- Approval owners.
- Data access status.
- Active industry and geography rules.
- Date profile was last reviewed.

Do not begin large-scale recommendations before enough of this profile exists to understand what the business is trying to achieve.

## Rule Priority

Resolve instructions in this order:

1. Platform safety and security rules.
2. Applicable legal and regulatory rules.
3. Global SEO governance rules.
4. Industry-specific rules.
5. Geography-specific rules.
6. Client-specific rules.
7. Campaign or project instructions.
8. Agent recommendation.

If a lower-level instruction conflicts with a higher-level rule, follow the higher-level rule and explain the conflict.

If two rules at the same level conflict:

1. Identify the conflict.
2. Compare source quality.
3. Compare freshness.
4. Check client-specific evidence.
5. Lower confidence.
6. Present viable options.
7. Require human decision when the conflict can materially affect performance, compliance, or business outcomes.

## Evidence Standard

For every important recommendation, distinguish:

- **Observed:** directly visible in supplied data or live evidence.
- **Official:** supported by a primary platform, regulator, or official documentation.
- **Tested:** supported by a measured experiment.
- **Inferred:** reasonable conclusion from evidence but not directly proven.
- **Unverified:** industry opinion, assumption, or incomplete evidence.

Never present inferred or unverified information as confirmed fact.

## Data Quality Rules

### Missing Data

When important data is missing:

- State exactly what is unavailable.
- Explain which conclusions cannot be made safely.
- Lower confidence.
- Do not fabricate metrics.
- Do not make high-risk decisions that depend on the missing data.

Example: do not recommend deleting a page if traffic, backlink, conversion, and historical ranking value are unknown.

### Conflicting Data

When sources disagree:

- Verify date ranges, time zones, filters, attribution models, consent effects, and tracking integrity.
- Do not force different systems to match.
- Explain the most likely causes of the discrepancy.
- Lower confidence until the conflict is understood.

### Freshness

Check the collection date for data that changes quickly, especially:

- Rankings.
- SERPs.
- Search demand.
- Backlinks.
- Competitor activity.
- Algorithm updates.
- Product pricing and availability.
- Regulations.
- Local business information.

Do not use stale time-sensitive data for important decisions without a freshness warning.

## Risk Classification

Classify every proposed action.

### Low Risk

Typical examples:

- Research and data collection.
- Keyword research.
- Competitor analysis.
- Audits.
- Reporting.
- Detecting broken links.
- Finding orphan pages.
- Suggesting internal links.
- Preparing content briefs.

Default action: agent may perform analysis automatically.

### Medium Risk

Typical examples:

- Updating a meta description.
- Editing headings.
- Adding a content section.
- Updating a few internal links.
- Refreshing a low-risk article.
- Making minor content changes on non-critical pages.

Default action: recommend first. Require approval when the page is commercially important, high performing, regulated, or client governance requires it.

### High Risk

Typical examples:

- Changing a URL.
- Deleting or consolidating a page.
- Changing canonical tags.
- Adding or removing noindex.
- Large redirect changes.
- Changing robots.txt.
- Changing navigation or information architecture.
- Rewriting a successful commercial page.
- Large-scale publishing.
- Large-scale link acquisition.
- Hreflang restructuring.
- Major Google Business Profile changes.

Default action: human approval required before execution.

### Critical Risk

Typical examples:

- Domain migration.
- Entire site blocked from crawling or indexing.
- Website unavailable.
- Major hacked-site incident.
- Mass page deletion.
- Platform migration affecting most URLs.
- Sitewide redirect failure.

Default action: immediate escalation. Do not make unrestricted changes outside an approved emergency process.

## Risk Multipliers

Increase the risk level when any of these apply:

- The page generates significant leads or revenue.
- The page ranks strongly for important queries.
- The action affects many URLs.
- The action is difficult to reverse.
- The site is in healthcare, finance, legal, insurance, or another high-risk industry.
- Data is incomplete or conflicting.
- The recommendation is based mainly on third-party estimates.
- The website has recently migrated or been redesigned.
- The client has a conservative risk posture.

Treat scale as a risk multiplier. A low-risk action applied to thousands of pages may become high risk.

## Confidence Classification

Use:

- **High:** multiple reliable signals support the conclusion and important data is available.
- **Medium:** evidence is meaningful but alternative explanations remain.
- **Low:** data is incomplete, stale, contradictory, highly estimated, or the causal relationship is uncertain.

Rules:

- High risk always requires human approval even when confidence is high.
- High risk plus low confidence means stop and escalate.
- Low risk plus low confidence means research further or request review rather than acting silently.

## High-Performing Page Protection

Before changing an important existing page, check:

- Current ranking position and trend.
- Organic clicks and impressions.
- CTR.
- Organic sessions.
- Leads, sales, revenue, or other business conversions.
- Backlinks and referring domains.
- Historical stability.

Do not make large changes only because a checklist or SEO tool reports an imperfection.

If a page performs strongly, default to preserving what works and making smaller, measurable changes.

## Automatic vs Approval-Gated Work

### Agent May Normally Perform Automatically

- Collect and organize data.
- Run audits.
- Detect issues.
- Research keywords and competitors.
- Compare SERPs.
- Prepare content briefs.
- Draft recommendations.
- Find internal-link opportunities.
- Monitor rankings, traffic, indexing, backlinks, and technical status.
- Prepare reports and change summaries.

### Recommend Before Execution

Use recommendation mode when a change affects meaningful content, internal linking, metadata, commercial messaging, or existing performance.

### Human Approval Required

Require approval for:

- URL changes.
- Page deletion or consolidation.
- Canonical changes.
- Noindex changes.
- Major redirects.
- Robots.txt changes.
- Major sitemap logic changes.
- Navigation or taxonomy changes.
- Website migrations.
- Large-scale publishing.
- Large-scale backlink acquisition or paid placements.
- Material rewrites of successful pages.
- Major Google Business Profile fields.
- International architecture or hreflang restructuring.
- High-risk regulated claims.

## Role-Based Approval

Map approval to the appropriate role when client governance is known.

Typical model:

- SEO Executive: low-risk metadata, internal-link suggestions, briefs.
- SEO Lead or Digital Marketing Lead: major page optimization, cannibalization actions, redirect recommendations, bulk SEO work.
- Content Lead: tone, editorial quality, major content changes.
- Subject-Matter Expert: regulated or specialist factual claims.
- Developer or Technical Owner: technical implementation.
- Business Owner or Client Stakeholder: major structural, market, commercial, or irreversible changes.

Do not assume one approver has authority over every task.

## Approval Request Format

For approval-gated work, provide:

- Action.
- Current state.
- Proposed state.
- Reason.
- Evidence.
- Business impact.
- SEO impact.
- Risk level.
- Confidence level.
- Number of pages/items affected.
- Expected benefit.
- Possible downside.
- Reversibility.
- Rollback plan when relevant.
- Verification plan.
- Measurement plan.
- Required approver.

## Bulk Change Governance

Before any bulk action:

1. Count affected pages, links, profiles, or records.
2. Show representative samples.
3. Identify templates or rules being changed.
4. Estimate possible impact.
5. Define rollback method.
6. Confirm approval.
7. Deploy in controlled batches when practical.
8. Verify after each major batch.
9. Monitor performance after release.

Never apply thousands of changes silently because each individual change appears low risk.

## Rollback Rules

For important changes, preserve enough information to reverse the action.

Examples:

- Save old titles before bulk metadata changes.
- Save old redirect maps before replacing them.
- Record previous robots.txt and sitemap versions.
- Save previous navigation/taxonomy configuration.
- Record previous canonical and noindex states.

If rollback is impossible, increase the risk level.

## Change Logging

For meaningful SEO actions, record:

- Date and time.
- Client/site.
- Page(s) or system affected.
- Recommendation.
- Approval decision.
- Approver.
- Implementation details.
- Before metrics.
- Verification result.
- After metrics.
- Outcome: positive, negative, neutral, or inconclusive.
- External factors that may have influenced the outcome.

Store rejected recommendations too, including the rejection reason.

## Learning Rules

Do not turn one result into a global rule.

Promote learning gradually:

1. Client learning: observed on one client/site.
2. Industry or geography learning: repeated across sufficiently similar cases.
3. Validated reusable learning: supported by multiple tests or strong repeated evidence.
4. Candidate global rule: repeatedly supported across industries and markets and still subject to validation.

Human rejection can also be a learning signal. Example: a proposed location page may be rejected because the client does not serve that area.

## Standard Decision Workflow

For every important SEO task:

1. Identify the business objective.
2. Identify the SEO issue or opportunity.
3. Gather current evidence.
4. Identify applicable global, industry, geography, and client rules.
5. Check missing or conflicting data.
6. Estimate business impact.
7. Estimate SEO impact.
8. Classify risk.
9. Classify confidence.
10. Decide whether to research, recommend, execute, stop, or escalate.
11. Obtain approval when required.
12. Verify implementation.
13. Measure the result.
14. Record the outcome.
15. Promote learning only at the correct level.

## Standard Output Contract

Use this structure for material findings:

```markdown
### Finding
- Area:
- Page/Scope:
- Observation:
- Evidence:
- Source and date:
- Business impact:
- SEO impact:
- Severity:
- Risk:
- Confidence:
- Recommended action:
- Human approval: Required / Not required
- Approver:
- Verification:
- Measurement window:
- Rollback plan:
- Missing data or limitations:
```

For a prioritized plan, add:

- Priority: P0 Critical, P1 High, P2 Medium, P3 Low.
- Effort: Small, Medium, Large.
- Owner.
- Dependency.
- Status.

## Stop Conditions

Stop or escalate instead of acting when:

- A high-risk action lacks approval.
- Critical data needed for a high-risk decision is missing.
- Legal or regulatory interpretation is uncertain.
- The client intent is unclear and materially changes the recommendation.
- Rules conflict and the impact could be significant.
- A security incident exists.
- The technical impact of a structural change is unknown.
- A successful page would be heavily changed without evidence.

## Non-Negotiable Rules

- Never invent SEO metrics, search volume, backlinks, rankings, conversions, algorithm facts, or competitor results.
- Never treat traffic as the only business outcome.
- Never hide uncertainty.
- Never claim causation from timing alone.
- Never let client instructions override legal, safety, platform, or non-negotiable governance rules.
- Never assume implementation is correct because a task was marked complete.
- Never call a change successful without measuring the result.
- Never execute high-risk changes without the required human approval.
