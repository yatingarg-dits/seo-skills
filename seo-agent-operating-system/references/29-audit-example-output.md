# Website Audit Example Output

## Purpose

Show the expected level of specificity for audit findings.

These are representative examples only, not evidence from a real client audit.

## Example 1 - indexation blocker

- Issue: Priority service folder blocked in robots.txt
- Scope: `/services/` templates
- Evidence: Crawl blocked; robots rule matches folder
- Business impact: Priority commercial pages may not be crawlable
- Severity: CRITICAL if production pages are intentionally meant to rank
- Recommendation: Remove/adjust blocking rule after staging/parameter exclusions are confirmed
- Owner: Developer + SEO approval
- QA: Re-test robots, crawl URLs, inspect representative URLs

## Example 2 - redirect chain

- Issue: Internal links point to URL A -> 301 B -> 301 C
- Scope: Sitewide navigation/template links
- Impact: Unnecessary crawl path and maintenance complexity
- Severity: MEDIUM unless it affects a large priority section or migration
- Recommendation: Update internal links directly to final canonical URL C; preserve required external redirects
- QA: Crawl template links and verify one-hop destination

## Example 3 - cannibalization

- Issue: Two service pages repeatedly appear for the same primary keyword cluster
- Evidence: Same query set maps to both URLs in Search Console/SERP observations
- Impact: Unclear target ownership; diluted internal/link signals possible
- Severity: HIGH when the affected query is a priority commercial cluster
- Recommendation: Re-map intent; merge, differentiate, redirect, or re-optimize according to the approved URL strategy
- QA: Recheck internal anchors, canonicals, sitemap, and ranking URL after implementation

## Example 4 - high impressions, weak CTR

- Issue: Priority page has high impressions and page-one visibility but weak CTR relative to its own historical baseline
- Evidence: Search Console query/page data
- Impact: Lost traffic without requiring a new ranking position
- Severity: MEDIUM/HIGH depending on business value
- Recommendation: Review title/snippet alignment, SERP intent, brand proposition, rich-result eligibility
- QA: Compare post-change CTR over a meaningful period; do not claim causation from one day of data

## Example 5 - analytics gap

- Issue: Lead form completion is not recorded as a reliable conversion event
- Impact: SEO traffic cannot be tied to qualified lead generation
- Severity: HIGH for lead-generation property
- Recommendation: Implement/repair event and conversion configuration, deduplicate firing, test end-to-end
- Owner: Analytics/Developer
- QA: Controlled test submission + debug/realtime verification

## Required finding schema

Every real audit finding should include:

- Issue
- Affected URL/template
- Evidence/source/date
- Business/SEO impact
- Severity
- Recommendation
- Owner
- Effort
- Dependency
- Status
- QA result
