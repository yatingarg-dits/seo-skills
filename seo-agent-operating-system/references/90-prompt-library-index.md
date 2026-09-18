# Global Content Prompt Library Index and Router

## Purpose

Route each content-generation task to the exact prompt file supplied by the team without rewriting, paraphrasing, shortening, merging, or silently changing the stored prompt text.

The prompt files `91-120` are immutable source prompts copied from the approved prompt library. Replace square-bracket placeholders only at execution time using approved task/client/property context. Do not edit the source prompt files to fill placeholders.

## Execution rules

1. Load [91-prompt-core-direction.md](91-prompt-core-direction.md) for every content prompt.
2. Load the exact format-specific prompt listed below.
3. Load [92-prompt-long-form-writing-framework.md](92-prompt-long-form-writing-framework.md) whenever the selected prompt states that the Complete Writing Framework applies, and for newsletter, guest article, listicle, on-site blog, case-study narrative, or long-form LinkedIn article work.
4. Load [120-prompt-multi-brand-guardrail.md](120-prompt-multi-brand-guardrail.md) whenever more than one company/brand is involved or a comparison/listicle includes competitors.
5. Resolve placeholders from approved client/property/campaign context. If a required placeholder cannot be resolved, mark it missing and do not invent a value.
6. Do not change the wording of prompt-library source files. Runtime instructions may add verified context, sources, publisher constraints, or user-requested values around the selected prompt without modifying the stored prompt.
7. Apply platform, agency, client, property, legal/compliance, publisher, and human-approval rules in addition to the prompt. If a conflict exists, do not rewrite the prompt file. Record the conflict and follow the higher-priority applicable rule during execution.
8. Record the selected prompt file(s) and version/commit in the content audit trail.

## Standalone prompt routing

| Content type | Prompt file |
|---|---|
| Google Search Ads | [93-prompt-google-search-ads.md](93-prompt-google-search-ads.md) |
| Business/directory descriptions | [94-prompt-business-directory-descriptions.md](94-prompt-business-directory-descriptions.md) |
| Meta tags | [95-prompt-meta-tags.md](95-prompt-meta-tags.md) |
| AEO/search FAQs | [96-prompt-aeo-search-faqs.md](96-prompt-aeo-search-faqs.md) |
| LinkedIn content promotion | [97-prompt-linkedin-content-promotion.md](97-prompt-linkedin-content-promotion.md) |
| Calls to action | [98-prompt-calls-to-action.md](98-prompt-calls-to-action.md) |
| Image brief | [99-prompt-image-brief.md](99-prompt-image-brief.md) |
| Business insight/newsletter | [100-prompt-business-insight-newsletter.md](100-prompt-business-insight-newsletter.md) |
| Guest article | [101-prompt-guest-article.md](101-prompt-guest-article.md) |
| Research-based article titles | [102-prompt-research-based-article-titles.md](102-prompt-research-based-article-titles.md) |
| Executive case study/event post | [103-prompt-executive-case-study-event-post.md](103-prompt-executive-case-study-event-post.md) |

## Local company listicle workflow

Always load:

- [91-prompt-core-direction.md](91-prompt-core-direction.md)
- [92-prompt-long-form-writing-framework.md](92-prompt-long-form-writing-framework.md)
- [104-prompt-local-company-listicle-workflow-rules.md](104-prompt-local-company-listicle-workflow-rules.md)
- [120-prompt-multi-brand-guardrail.md](120-prompt-multi-brand-guardrail.md)

Then load only the active stage prompt:

1. [105-prompt-local-company-listicle-01-market-outline.md](105-prompt-local-company-listicle-01-market-outline.md)
2. [106-prompt-local-company-listicle-02-brand-profile.md](106-prompt-local-company-listicle-02-brand-profile.md)
3. [107-prompt-local-company-listicle-03-other-profiles-conclusion.md](107-prompt-local-company-listicle-03-other-profiles-conclusion.md)
4. [108-prompt-local-company-listicle-04-linkedin-promotion.md](108-prompt-local-company-listicle-04-linkedin-promotion.md)
5. [109-prompt-local-company-listicle-05-faqs.md](109-prompt-local-company-listicle-05-faqs.md)
6. [110-prompt-local-company-listicle-06-alternative-titles.md](110-prompt-local-company-listicle-06-alternative-titles.md)

Carry forward the approved outline, methodology, sources, company order, keyword usage, and cumulative word count exactly as required by the workflow rules.

## On-site blog workflow

Always load:

- [91-prompt-core-direction.md](91-prompt-core-direction.md)
- [92-prompt-long-form-writing-framework.md](92-prompt-long-form-writing-framework.md)
- [111-prompt-onsite-blog-workflow-rules.md](111-prompt-onsite-blog-workflow-rules.md)

Then load only the active stage prompt:

1. [112-prompt-onsite-blog-01-strategy-outline.md](112-prompt-onsite-blog-01-strategy-outline.md)
2. [113-prompt-onsite-blog-02-whole-article-rules.md](113-prompt-onsite-blog-02-whole-article-rules.md)
3. [114-prompt-onsite-blog-03-first-section-group.md](114-prompt-onsite-blog-03-first-section-group.md)
4. [115-prompt-onsite-blog-04-second-section-group.md](115-prompt-onsite-blog-04-second-section-group.md)
5. [116-prompt-onsite-blog-05-conclusion-engagement-models.md](116-prompt-onsite-blog-05-conclusion-engagement-models.md)
6. [117-prompt-onsite-blog-06-alternative-titles.md](117-prompt-onsite-blog-06-alternative-titles.md)
7. [118-prompt-onsite-blog-07-faqs.md](118-prompt-onsite-blog-07-faqs.md)
8. [119-prompt-onsite-blog-08-metadata-final-audit.md](119-prompt-onsite-blog-08-metadata-final-audit.md)

Carry forward every approved heading, keyword, source, tone requirement, cumulative word count, and editorial decision as required by the workflow rules.

## Prompt selection output

Before content generation record:

- Content type
- Selected prompt file
- Shared prompt files loaded
- Workflow stage when applicable
- Placeholder values resolved
- Missing placeholders
- Client/property/style context loaded
- Research/source requirement
- Human approval requirement

Use `PROMPT_READY` only when the correct prompt and required context are available. Use `PROMPT_BLOCKED_MISSING_CONTEXT` when required placeholders or brand facts cannot be resolved safely.
