# Performance, Mobile, Images, and Structured Data Audit

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for PageSpeed Insights/Lighthouse, Rich Results Test, Schema.org Validator, schema generators, and supporting crawl tools. The Google Mobile-Friendly Test is retired and must not be used for new work.

Audit technical user-experience signals and implementation quality without reducing SEO to a single tool score. Follow [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md): page experience is not a single algorithm/score. For AI features, [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md) does not require special AI schema.

## Performance evidence

Use available field and lab data. Record source and date.

Check:

- Core Web Vitals status
- LCP
- INP
- CLS
- TTFB when useful
- FCP/TBT when useful for diagnosis
- Render-blocking resources
- JavaScript cost
- CSS cost
- Large images
- Fonts
- Third-party scripts
- Caching/CDN opportunities

Do not recommend changes only from a headline PageSpeed score. Identify the cause/template/resource.

## Mobile checks

Verify:

- Responsive rendering
- Content parity with desktop where expected
- Metadata parity
- Structured-data parity
- Internal-link/navigation parity
- Important lazy-loaded content
- Tap/interaction usability
- Intrusive overlays
- Mobile page performance

## Image checks

Identify:

- Broken images
- Oversized files
- Missing dimensions where causing layout shift
- Compression opportunities
- Modern formats where appropriate
- Descriptive filenames where useful
- Missing/poor alt text for informative images
- Incorrect alt text on decorative images
- Lazy-loading issues

## Structured data

Identify markup actually relevant to visible content and site type.

Check:

- Syntax/validation errors
- Required/important properties
- Markup-content mismatch
- Wrong URLs/entities
- Duplicate/conflicting markup
- Outdated implementation
- Unsupported or misleading markup

Possible types may include Organization, LocalBusiness, Product, Breadcrumb, Article, Video, JobPosting, Event, or other applicable schemas.

Do not add a schema type merely because it exists.

## Output

For each issue return:

- Template/URL
- Evidence
- Root cause
- Recommended fix
- Expected benefit
- Owner

Route to [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).
