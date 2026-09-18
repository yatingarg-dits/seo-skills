# On-Page and Content Audit

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for SEOquake, Yoast, Screaming Frog, Semrush/Ahrefs, SEOptimer/SEOmator-like audit support, and their limitations. Tool findings remain evidence, not automatic priorities.

Audit page-level relevance, search intent, metadata, headings, content quality, duplication, and keyword targeting.

## Inputs

Use:

- [20-audit-intake-baseline.md](20-audit-intake-baseline.md)
- Approved keyword map from [15-keyword-validation-output.md](15-keyword-validation-output.md) when available
- [04-property-context.md](04-property-context.md)

## Title audit

Check:

- Missing titles
- Duplicate titles
- Generic/template-only titles
- Keyword/intent mismatch
- Weak differentiation
- Important page not represented clearly
- Location mismatch where relevant

Do not optimize titles by keyword stuffing.

## Meta description audit

Check:

- Missing
- Duplicate
- Irrelevant
- Weak value proposition
- Weak CTA where a CTA is appropriate
- Intent mismatch

Treat meta descriptions as messaging/CTR assets, not guaranteed ranking text.

## Heading audit

Check:

- Missing or unclear H1
- H1 not matching page purpose
- Repeated template headings that obscure structure
- Illogical H2/H3 hierarchy
- Missing important subtopics

## Content audit

Evaluate:

- Intent match
- Business accuracy
- Original value
- Completeness
- Freshness where relevant
- Thin/empty pages
- Near-duplicate pages
- Duplicate content
- Unhelpful boilerplate dominance
- Missing proof/examples
- Missing FAQs when useful
- Weak CTA/conversion path
- Content that contradicts property context

## Keyword/page checks

Flag:

- Target keyword missing from appropriate page context
- Wrong page ranking
- Multiple pages targeting same intent
- Blog/service cannibalization
- Content gap against validated SERP competitors
- Existing high-impression page with weak CTR

## Page disposition

Recommend one:

- Keep
- Refresh
- Expand
- Re-optimize
- Merge
- Differentiate
- Redirect
- Remove/noindex when justified
- Create supporting content

## Guardrails

- Do not prescribe word count only because competitors are longer.
- Do not add FAQs/schema unless useful and accurate.
- Do not create pages solely to capture keyword variants with the same intent.
- Do not invent client facts.

## Output

Return URL-level findings with evidence, recommendation, and owner. Route to [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).

## Content remediation handoff

When the disposition requires `Refresh`, `Expand`, `Re-optimize`, `Differentiate`, or `Create supporting content`, route the content work through [54-content-production-workflow.md](54-content-production-workflow.md). Re-check topic overlap through [56-content-topic-research-validation.md](56-content-topic-research-validation.md) and quality/originality through [86-content-quality-ai-originality.md](86-content-quality-ai-originality.md).
