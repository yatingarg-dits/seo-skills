# Content Quality, AI-Quality, and Originality Review

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for Grammarly, Hemingway, Copyscape, ZeroGPT, Surfer/Frase, and other QA tools. AI-detection or content-optimization scores are warning/support signals only.

Evaluate whether a draft is useful, defensible, brand-appropriate, clear, and meaningfully differentiated before formal validation. Use [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md) for helpful/original/reliable/spam controls and [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md) for AI citation-worthiness without rewriting solely for machines.

## Core quality dimensions

Check:

- Relevance
- Depth
- Clarity
- Factual correctness
- Repetition
- Brand fit
- Logical progression
- Evidence use
- Reader usefulness
- CTA fit

## AI-quality issues to detect

Flag:

- Generic AI phrasing
- Excessive repetition
- Unsupported claims
- Fake specificity
- Unnatural keyword insertion
- Excessive adjectives
- Repetitive sentence structures
- Unnecessary conclusions
- Excessive headings
- Vague business claims
- Authoritative-sounding statements without evidence

Do not optimize for making AI content merely "look human."

Optimize for content that is:

- Useful
- Defensible
- Brand-appropriate
- Expert-validatable

## Originality/information gain

Define originality as meaningful original contribution, not only plagiarism avoidance.

Ask:

`What does this content add that existing site/SERP content does not?`

Possible contribution types include:

- Original expertise
- Better synthesis
- Proprietary data
- Different framework
- Industry experience
- Examples
- Product knowledge
- Contrarian analysis
- Better explanation
- Unique research

If no meaningful contribution exists, return `WARNING_LOW_INFORMATION_GAIN`.

## Duplication checks

Flag:

- Copied/near-copied text
- Rewritten competitor structure with no added value
- Internal duplication
- Repetitive sections within the draft
- Content substantially overlapping an existing site asset

## Outcome

Use:

- QUALITY_PASS
- QUALITY_PASS_WITH_WARNING
- WARNING_LOW_INFORMATION_GAIN
- WARNING_GENERIC_AI_QUALITY
- REVISION_REQUIRED
- BLOCK_FACTUAL_RISK
- BLOCK_DUPLICATIVE_CONTENT

## Handoff

Send reviewed content to [51-seo-content-review.md](51-seo-content-review.md) and [87-content-validation-gate.md](87-content-validation-gate.md).
