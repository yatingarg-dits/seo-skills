# Keyword Clustering, URL Mapping, and Prioritization

## Purpose

Turn validated keywords into page-level actions without creating unnecessary duplicate pages.

## Inputs

Load:

- [13-serp-competitor-analysis.md](13-serp-competitor-analysis.md)
- [04-property-context.md](04-property-context.md)

## Clustering rules

Group keywords when they share most of the following:

- Same intent
- Same business objective
- Similar SERP result types
- Significant SERP overlap
- Same topic
- Same suitable page type

Separate keywords when intent or dominant SERP/page type materially differs.

## URL mapping

For each cluster decide:

- Existing page fits
- Existing page needs re-optimization
- Existing page should be merged with another
- New service/product/category page needed
- New location page needed
- New blog/resource needed
- No page should be created

## Cannibalization checks

Flag:

- Multiple pages targeting same intent
- Wrong page ranking
- Blog competing with commercial page
- Similar location pages
- Near-duplicate pages

Recommended action must be one of:

- Keep
- Re-optimize
- Differentiate
- Merge
- Redirect
- Canonicalize where technically appropriate
- Create new page
- Do not target

## Priority logic

Evaluate together:

- Business relevance
- Intent/conversion potential
- Existing ranking proximity
- Current site authority
- SERP competition
- Search demand
- Trend
- Required effort
- Strategic priority from property context

Do not prioritize solely by search volume or difficulty.

## Output fields

Return:

- Primary keyword
- Secondary/supporting keywords
- Cluster
- Intent
- Business relevance
- Existing URL
- Target URL
- Page type
- Cannibalization flag
- Recommended action
- Priority
- Reason

Route to [15-keyword-validation-output.md](15-keyword-validation-output.md).
