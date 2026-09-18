# SEO Content Review

## Purpose

Use [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) for Grammarly, Hemingway, QuillBot, ZeroGPT, Surfer/Frase/Yoast, and other review tools. Their scores/suggestions cannot override factual, brand, intent, or human-review rules.

Review drafted content for factual accuracy, source quality, audience/intent fit, business relevance, brand rules, usefulness, on-page SEO, linking, and publication readiness.

## Inputs

Use:

- [50-seo-content-brief.md](50-seo-content-brief.md)
- [84-content-creation-contract.md](84-content-creation-contract.md)
- [86-content-quality-ai-originality.md](86-content-quality-ai-originality.md)
- [85-content-linking.md](85-content-linking.md) where links are part of the asset
- [06-client-content-style-rules.md](06-client-content-style-rules.md)
- [57-content-source-research-reliability.md](57-content-source-research-reliability.md) when factual research is used

## Review dimensions

### Factual/client accuracy

Check services, products, geography, audience, approved claims, author identity, restricted statements, terminology, statistics, quotations, and capabilities.

### Sources/evidence

Check whether material factual claims are traceable to appropriate evidence and whether conflicting/weak evidence is surfaced.

### Tone/voice

Check formality, technical depth, CTA style, preferred/restricted words, and client positioning.

### Search/user intent

Check the main need/question, expected depth, page/content type, and conversion path where appropriate.

### Topic coverage and structure

Check required sections, gaps, logical progression, repetition, fluff, evidence/examples, and questions from the approved brief.

### On-page SEO

For SEO content check:

- H1/headings
- Natural primary/supporting-topic coverage
- Intent alignment
- Metadata recommendations where required
- URL suggestion/target URL
- Internal links
- External sources
- Image/alt recommendations where applicable

### Cannibalization

If the draft duplicates an existing page intent, route back to [56-content-topic-research-validation.md](56-content-topic-research-validation.md) and keyword clustering/mapping as needed.

## Preliminary outcome

Use:

- REVIEW_PASS
- REVIEW_WARNING
- REVIEW_BLOCK
- FACTUAL_CONTEXT_MISSING
- TONE_OR_CLAIM_VIOLATION
- INTENT_MISMATCH
- CANNIBALIZATION_RISK
- SOURCE_EVIDENCE_GAP
- SEO_REVISION_REQUIRED

Return exact rule-triggered changes, not vague comments such as "make SEO better."

## Handoff

Send the reviewed asset to [87-content-validation-gate.md](87-content-validation-gate.md) for the final PASS/WARNING/BLOCK decision before approval.
