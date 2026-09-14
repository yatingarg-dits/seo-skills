---
name: seo-monitoring-learning-incidents
description: "Monitor SEO performance, detect anomalies, diagnose incidents, track algorithm updates, run traffic/ranking-drop playbooks, verify analytics, manage SEO experiments, measure outcomes, record change history, and promote validated learnings. Use for monitoring, reporting, alerts, traffic or ranking drops, indexing emergencies, migrations, manual actions, hacked sites, tracking failures, SERP changes, seasonality, experiments, and post-change learning."
---

# SEO Monitoring, Learning, and Incidents

## Mission

Continuously verify whether SEO systems, pages, and campaigns are healthy; detect meaningful changes early; diagnose before acting; measure the impact of changes; and convert validated outcomes into reusable intelligence without confusing correlation with causation.

Use this operating flow:

**Baseline -> monitor -> detect -> confirm -> diagnose -> prioritize -> approve -> fix -> verify -> measure -> learn.**

## Required Inputs

Use or request:

- Website/domain.
- Client SEO Profile and business goals.
- Search Console data.
- Analytics data.
- Conversion/revenue data when available.
- Ranking data when available.
- Crawl/indexing data.
- Backlink data when relevant.
- Deployment/change log.
- Algorithm update log.
- Competitor/market data.
- Seasonality context.
- Approval/escalation owners.

If tracking or data access is incomplete, state the limitation before diagnosing performance.

## 1. Establish a Baseline

Before evaluating changes, capture the current baseline for appropriate metrics:

- Organic clicks.
- Organic impressions.
- Average positions/tracked rankings.
- CTR.
- Organic sessions/users.
- Leads.
- Sales.
- Revenue.
- Bookings/calls.
- Indexed pages.
- Crawl errors.
- Core Web Vitals/technical health where relevant.
- Referring domains/backlinks where relevant.
- Local/GBP metrics where relevant.
- AI-search/citation observations where relevant.

Segment by:

- Page type.
- Directory/template.
- Country.
- Device.
- Brand vs non-brand.
- Search intent.
- Product/category/service.
- New vs existing content.

Do not rely only on whole-site averages.

## 2. Monitoring Cadence

Use cadence based on risk and change rate.

### Daily or Near-Daily for Critical Signals

- Site availability.
- Severe server errors.
- Sitewide noindex/robots blocking.
- Major tracking outages.
- Major redirect failures.
- Security/hack indicators.

### Weekly for Active SEO Operations

- Search Console clicks/impressions.
- Important rankings.
- Key page changes.
- Indexing issues.
- Crawl anomalies.
- New/lost high-value backlinks.
- Local profile/review changes when important.

### Monthly or Strategic Review

- Business outcomes.
- Conversion/revenue trends.
- Content decay.
- Competitor shifts.
- Authority growth.
- Topic/market performance.
- Experiment outcomes.
- Roadmap reprioritization.

Adjust cadence to the client, site size, and risk level.

## 3. Alerting Principles

Trigger investigation based on meaningful deviations rather than every small fluctuation.

Consider:

- Magnitude.
- Duration.
- Business importance.
- Historical volatility.
- Seasonality.
- Data reliability.
- Recent releases.

Avoid panic after a single day's movement unless the event is clearly critical, such as sitewide blocking or downtime.

## 4. Incident Severity

### Critical

Potential sitewide or major business loss.

Examples:

- Entire website noindexed.
- robots.txt blocks the site.
- Main domain misdirected.
- Website down.
- Major migration failure.
- Hacked site.
- Severe tracking loss during a major launch.

Action: immediate escalation and controlled emergency response.

### High

Important business area affected.

Examples:

- Main category/service section noindexed.
- Large ranking/traffic drop on important pages.
- Major redirect errors.
- Serious manual action.

Action: investigate quickly and require approval for corrective changes.

### Medium

Material issue without immediate crisis.

Examples:

- Content decay on an important article.
- Internal-linking gaps.
- Duplicate-content pattern.
- Local profile inconsistency.

Action: prioritize into the task queue.

### Low

Incremental issue or improvement.

Examples:

- Minor metadata opportunity.
- Limited missing alt text.
- Small reporting inconsistency.

Action: fix when practical.

## 5. Traffic Drop Playbook

When organic traffic drops:

1. Confirm the drop is real.
2. Check analytics tracking.
3. Check Search Console clicks/impressions.
4. Identify affected pages/directories.
5. Segment by country/device/brand vs non-brand.
6. Check rankings and SERP changes.
7. Check indexability/noindex/robots/canonicals.
8. Check site availability and server errors.
9. Check recent deployments/migrations.
10. Check algorithm updates.
11. Check competitor changes.
12. Check search demand/seasonality.
13. Check backlink losses when relevant.
14. Recommend action only after evidence.

Never default to "Google update" as the explanation.

## 6. Ranking Drop Playbook

For a ranking decline:

- Confirm the tracking location/device/query is consistent.
- Check whether the ranking URL changed.
- Inspect the actual SERP.
- Check search intent changes.
- Check SERP feature changes.
- Check competitor improvements.
- Check page edits.
- Check technical/indexing issues.
- Check internal-link changes.
- Check backlink loss.
- Check content freshness/accuracy.
- Check algorithm timing.

Treat ranking loss as a symptom, not the diagnosis.

## 7. Impression Drop Without Ranking Drop

Possible causes include:

- Search demand decline.
- Seasonality.
- Query mix changes.
- Market changes.

Separate demand problems from ranking problems before changing pages.

## 8. CTR Drop Without Ranking Drop

Inspect:

- SERP layout changes.
- AI answers/AI Overviews.
- Featured snippets.
- Maps.
- Shopping modules.
- Video/image results.
- Competitor titles/snippets.
- Brand perception.

A stable rank with lower CTR may reflect a different SERP, not weaker relevance.

## 9. Search Console vs Analytics Mismatch

When GSC clicks and analytics organic sessions disagree materially:

Check:

- Date ranges/time zones.
- Tracking deployment.
- Consent/cookie behavior.
- Attribution differences.
- Channel definitions.
- Landing-page filters.
- Bot/internal traffic handling.
- Cross-domain issues.
- Tag Manager/analytics changes.

Do not force the tools to show identical numbers.

## 10. Tracking Failure Playbook

If leads/sessions suddenly collapse:

- Validate whether the business outcome actually changed.
- Test analytics tags.
- Test forms/thank-you pages.
- Check call tracking.
- Check CRM ingestion.
- Check Tag Manager changes.
- Check consent changes.
- Check checkout/booking tracking.

Do not start changing SEO pages if the actual problem is measurement.

## 11. Indexing Emergency Playbook

If an important page/section is unexpectedly noindexed or removed from search:

- Confirm current meta/X-Robots state.
- Confirm canonical.
- Confirm robots access.
- Confirm HTTP status.
- Identify when the change happened.
- Identify deployment responsible if known.
- Assess affected traffic/business value.
- Escalate based on severity.
- Obtain approval for corrective changes.
- Verify live fix.
- Monitor reprocessing/recovery.

## 12. robots.txt Emergency

If robots.txt blocks important areas or the full site:

- Confirm the live file.
- Compare with prior version/change log.
- Identify affected paths.
- Escalate immediately if sitewide/critical.
- Require technical/human approval for edits.
- Verify crawler access after the fix.

## 13. Site Down / Server Error Incident

When the site or important section is unavailable:

- Confirm with independent checks.
- Identify status codes and scope.
- Escalate to development/infrastructure.
- Pause normal SEO recommendations until availability is restored.
- Verify recovery.
- Assess indexing/crawl impact after prolonged incidents.

## 14. Hacked Site Playbook

Indicators may include:

- Casino/pharmacy/spam pages.
- Strange redirects.
- Injected links.
- Fake login pages.
- Unknown indexed URLs.

Actions:

- Escalate to security/development immediately.
- Preserve evidence/logs.
- Identify affected URLs.
- Stop routine SEO changes.
- Clean and secure the site through the proper team.
- Review indexation after cleanup.
- Check Search Console security/manual-action information.
- Monitor recovery.

Security comes before SEO optimization.

## 15. Manual Action Playbook

If a manual action exists:

- Confirm in Search Console.
- Document type/scope.
- Escalate to SEO lead/client owner.
- Audit the relevant issue: links, spam, cloaking, hacked content, etc.
- Build a remediation plan.
- Record changes/removals.
- Submit reconsideration only after reviewed remediation where applicable.

Do not treat a manual action like a routine ranking fluctuation.

## 16. Migration Monitoring

Before migration, save:

- URL inventory.
- Redirect map.
- rankings.
- traffic.
- conversions.
- indexation.
- backlinks to key URLs.

After launch monitor:

- Redirect accuracy.
- 404/5xx errors.
- canonicals.
- robots/noindex.
- sitemaps.
- internal links.
- tracking.
- clicks/impressions.
- rankings.
- conversions.

Use separate migration dashboards/alerts during the high-risk period.

## 17. Redesign Monitoring

Compare pre/post redesign:

- Content amount/usefulness.
- Titles/headings.
- URLs.
- internal links.
- navigation.
- canonicals.
- schema.
- performance.
- tracking.
- conversions.

Do not assume a visual improvement preserves SEO value.

## 18. Algorithm Update Knowledge

Maintain a dated update log.

For each update record:

- Update name.
- Search platform.
- Update type.
- Official start date.
- Official end date when known.
- Official source.
- Date knowledge was checked.
- Client impact analysis.

Prefer official search-engine sources for confirmation.

Do not store rumors as official rules.

## 19. Algorithm Knowledge Classification

Classify claims as:

- **Official:** directly published by the platform.
- **Observed:** repeated pattern seen in market/client data.
- **Tested:** validated through a controlled or well-measured experiment.
- **Unverified:** industry theory, discussion, or rumor.

Always retain the source and date.

## 20. Algorithm Update Response

When an update is confirmed:

1. Record start/end dates.
2. Avoid immediate mass changes.
3. Compare pre/post performance.
4. Segment affected areas.
5. Check unaffected areas.
6. Compare competitors.
7. Check technical/tracking/seasonal alternatives.
8. Identify plausible patterns.
9. Recommend targeted actions with confidence levels.
10. Measure recovery/change over time.

Never blame every drop on an algorithm update.

## 21. Search Demand and Seasonality

For seasonal businesses/content:

- Compare year-over-year or matching-season periods where appropriate.
- Use impressions/search-trend data.
- Account for holidays/events/weather where relevant.
- Avoid calling expected seasonal decline an SEO failure.

## 22. Competitor Movement

If a competitor overtakes the site, check:

- New/updated pages.
- Intent alignment.
- Content quality.
- fresh evidence.
- internal linking.
- backlinks/PR.
- technical changes.
- SERP feature ownership.

Learn from the change without copying blindly.

## 23. High Ranking but Low Leads

Investigate:

- Keyword intent.
- Audience fit.
- Landing-page offer.
- CTA.
- Trust.
- form/checkout usability.
- pricing/qualification.
- tracking accuracy.

Do not call the page successful solely because it ranks well.

## 24. Low Traffic but Strong Revenue

Protect pages that generate strong business value even if traffic volume is modest.

Business performance can outweigh raw traffic volume.

## 25. Content Decay Monitoring

Flag pages when evidence shows:

- Ranking decline.
- Impression decline.
- click decline.
- CTR decline.
- conversion decline.
- outdated facts.
- intent shift.
- competitor improvement.

Do not refresh solely because the publication date is old.

## 26. Backlink Monitoring

Coordinate with off-page SEO for:

- New/lost high-value links.
- Lost referring domains.
- unusual link spikes.
- anchor-pattern changes.
- broken backlink destinations.
- publisher quality changes.

Do not assume a sudden link spike is a negative SEO attack without evidence.

## 27. Local Monitoring

Track where applicable:

- GBP visibility/actions.
- reviews/rating trends.
- local rankings.
- location-page traffic.
- calls/bookings.
- profile-field changes.
- duplicate/suspension issues.

Escalate unauthorized major GBP changes.

## 28. AI Search Monitoring

For defined prompt/query sets, track:

- AI answer presence.
- brand mentions.
- citations.
- competing sources.
- factual accuracy.
- referral traffic when measurable.
- CTR shifts on AI-heavy SERPs.

Store platform and observation date because AI outputs vary.

## 29. Change Log

Record all meaningful SEO changes:

- Date/time.
- URL/scope.
- change description.
- reason/hypothesis.
- owner.
- approval.
- deployment reference.
- baseline metrics.
- expected result.
- rollback plan.

A change log is required for reliable diagnosis and learning.

## 30. SEO Experiment Framework

For material tests, record:

### Hypothesis

What change is expected to produce what result and why?

### Baseline

What was performance before the change?

### Change

Exactly what was implemented?

### Date

When did it go live?

### Measurement Window

How long will the result be observed?

### Primary KPI

Which metric determines success?

### Guardrail Metrics

What should not be harmed?

### External Factors

Algorithm updates, seasonality, competitor changes, campaigns, outages, demand changes.

### Outcome

Positive, negative, neutral, or inconclusive.

Do not call an action a learning until it has been measured.

## 31. Causality Rules

Do not claim a change caused a result merely because it happened earlier.

Before stronger causal claims, consider:

- Algorithm changes.
- seasonality.
- search demand.
- competitor changes.
- paid campaigns.
- backlink changes.
- tracking changes.
- product availability.
- offline promotions.

Use language proportional to the evidence.

## 32. Learning Promotion

Store learnings at the smallest valid level first:

### Client Learning

Observed on one client/site.

### Industry or Geography Learning

Repeated across sufficiently similar clients/markets.

### Validated Reusable Learning

Supported by repeated measurement/testing.

### Candidate Global Learning

Consistently supported across multiple industries/markets and reviewed before promotion.

Never turn one client's outcome into a universal rule.

## 33. Rejected Recommendations

Record rejections and reasons.

Examples:

- Business does not serve proposed location.
- Legal team rejects a claim.
- Product team will not support a page type.
- Technical risk exceeds benefit.

Human rejection is useful governance and learning data.

## 34. Approval Expiry

Re-check high-risk approvals when:

- Implementation is significantly delayed.
- Site architecture changes.
- business priorities change.
- performance changes materially.
- relevant policy/regulation changes.

Do not treat old approval as permanent authorization under changed conditions.

## 35. Reporting

A useful SEO report should explain:

- What changed.
- Why it matters.
- What drove the change when evidence allows.
- Which pages/markets were affected.
- Business outcome.
- Risks/issues.
- Actions completed.
- Actions recommended.
- What will be monitored next.

Avoid reports made only of metric screenshots without interpretation.

## 36. Standard Incident Output

```markdown
### SEO Incident
- Scenario:
- Severity:
- Detection time/date:
- Scope:
- Business impact:
- Evidence:
- Possible causes:
- Causes checked:
- Confirmed finding:
- Recommended action:
- Risk:
- Confidence:
- Human approval:
- Owner/escalation:
- Verification:
- Monitoring window:
- Rollback/recovery plan:
```

## 37. Standard Algorithm Update Output

```markdown
### Search Update Assessment
- Update:
- Search platform:
- Official source:
- Start/end date:
- Client impact:
- Affected areas:
- Unaffected areas:
- Possible connection:
- Confidence:
- Other causes checked:
- Recommended action:
- Human approval:
- Measurement plan:
```

## 38. Standard Experiment Output

```markdown
### SEO Experiment
- Hypothesis:
- Pages/scope:
- Baseline:
- Change:
- Launch date:
- Primary KPI:
- Guardrails:
- Measurement window:
- External factors:
- Result:
- Confidence:
- Learning level:
- Next action:
```

## Non-Negotiable Rules

- Never panic after one day of normal volatility.
- Never blame every drop on an algorithm update.
- Never act on tracking data before verifying tracking when the pattern looks abnormal.
- Never claim causation without sufficient evidence.
- Never ignore seasonality or search-demand changes.
- Never continue routine SEO while a critical security/sitewide incident is active.
- Never call implementation complete until the live state is verified.
- Never call a change successful until its outcome is measured.
- Never promote a one-client observation into a global rule without validation.
- Never hide missing data, conflicting data, or uncertainty.
