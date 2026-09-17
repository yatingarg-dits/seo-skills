# Paid Keyword Research

## Purpose

Build and qualify search-ad keyword candidates separately from organic SEO difficulty.

## Prerequisites

Load:

- [10-keyword-intake.md](10-keyword-intake.md)
- [04-property-context.md](04-property-context.md)

## Campaign context

Capture:

- Objective
- Conversion action
- Geography
- Language
- Budget if supplied
- Target CPA/ROAS if supplied
- Landing pages
- Brand versus non-brand requirement
- Competitor-term policy

## Sources

Use approved available sources such as:

- Google Keyword Planner
- Existing Google Ads search terms
- Existing Google Ads keyword performance
- Organic keyword research
- Search Console
- Website service/product terms
- Competitor landing pages
- Approved paid-search research tools

## Collect per keyword

Store:

- Keyword
- Avg. monthly searches
- Competition
- Competition index when available
- Top-of-page bid low
- Top-of-page bid high
- CPC where available
- Trend/seasonality
- Location
- Intent
- Conversion relevance
- Landing page
- Brand/non-brand
- Competitor term yes/no
- Negative-keyword candidate yes/no
- Source/date

## Critical rule

Paid `Competition` represents advertiser competition. Do not label it as organic keyword difficulty.

## Segmentation

Classify into:

- Brand
- Core service/product
- High-intent transactional
- Problem/solution
- Location
- Competitor
- Informational/research

## Negative keyword candidates

Flag terms whose intent conflicts with the property goal, such as jobs, salary, free, course, training, DIY, or irrelevant locations only when they are actually irrelevant to this client.

Do not apply a universal negative list blindly.

## Landing-page fit

For every approved keyword identify:

`Keyword -> Intent -> Ad group/theme -> Landing page -> Conversion action`

If no suitable landing page exists, mark `LANDING_PAGE_GAP`.

## Output

Send the candidate set to [15-keyword-validation-output.md](15-keyword-validation-output.md).
