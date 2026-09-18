# Technical Crawl and Indexation Audit

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for Screaming Frog, Search Console, Bing Webmaster Tools, Ahrefs/Semrush audit support, and secondary audit-tool roles.

Audit whether search engines can efficiently discover, crawl, canonicalize, and index the correct URLs.

## Inputs

Use [20-audit-intake-baseline.md](20-audit-intake-baseline.md) and approved crawl/index data.

## Crawl capture

Collect at minimum:

- URL
- Status code
- Content type
- Indexability
- Robots directive
- Canonical
- Title
- Meta description
- H1
- Internal inlinks/outlinks
- Crawl depth
- Redirect target
- Response time when available

## Status-code checks

Identify:

- 200 URLs that should not be indexable
- 3xx redirects
- Redirect chains
- Redirect loops
- Internal links to redirects
- 404/410 URLs
- Soft 404 patterns
- 5xx errors
- Broken internal links
- Valuable old URLs with no relevant redirect

## robots.txt

Check:

- File accessibility
- Accidental blocking of important sections
- Unnecessary crawling of low-value sections
- Sitemap declaration when used
- Conflicts with desired crawl behavior

Do not use robots.txt as a substitute for `noindex` logic without validating the intended outcome.

## XML sitemap

Check:

- Accessible sitemap
- Submitted/known in Search Console when available
- Canonical URLs only
- Indexable URLs only
- No broken URLs
- No redirected URLs
- No obvious duplicates
- Correct segmentation for large/multi-type sites

## Indexation checks

Compare where available:

- Crawlable URLs
- Sitemap URLs
- Search Console indexed/not-indexed states
- Canonical selections
- Site-search observations only as supporting evidence

Investigate states such as:

- Crawled, currently not indexed
- Discovered, currently not indexed
- Duplicate/alternate page
- Blocked by robots
- Excluded by noindex
- Soft 404
- Canonical mismatch

## Canonical checks

Flag:

- Missing canonical where required by team standard
- Multiple canonical tags
- Canonical to wrong URL
- Canonical to redirect/error/noindex
- Conflicting canonical signals
- HTTP/HTTPS variants
- WWW/non-WWW variants
- Parameter/facet duplicates
- Cross-domain canonical requiring review

## JavaScript/rendering checks

When relevant verify:

- Important content renders for crawlers
- Links exist in rendered output
- Canonical/meta directives are stable after rendering
- Lazy-loaded content is discoverable
- Client-side routing does not create inaccessibile URLs

## Output

For every issue return:

- Issue type
- Affected URL/template
- Evidence
- SEO impact
- Recommended fix
- Owner
- Severity candidate

Do not finalize severity here. Route findings to [27-audit-prioritization-qa.md](27-audit-prioritization-qa.md).
