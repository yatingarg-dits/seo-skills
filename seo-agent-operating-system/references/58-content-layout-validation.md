# Content Layout Validation

## Purpose

Validate the proposed information architecture before drafting so the content covers the user need, business objective, and important information gaps.

## Inputs

Use:

- [50-seo-content-brief.md](50-seo-content-brief.md)
- [56-content-topic-research-validation.md](56-content-topic-research-validation.md)
- [57-content-source-research-reliability.md](57-content-source-research-reliability.md) when research is needed
- SERP observations for SEO content

## Required layout elements

Check where applicable:

- Suggested H1
- H2/H3 structure
- Questions to answer
- Main content direction
- Search intent coverage
- Business objective
- Audience fit
- CTA direction
- Differentiation/information-gain angle
- Evidence/source requirements
- Internal-link opportunities
- Existing-content conflicts

## Validation rules

### Flow

Ensure the sequence is logical for the intended reader and does not exist only to place keywords/headings.

### Intent coverage

Confirm the layout answers the primary need and the expected supporting questions.

### Business relevance

Confirm the asset can support the approved objective without distorting the user need.

### Information gaps

Identify missing concepts, questions, objections, evidence, definitions, or examples needed for a useful asset.

### Differentiation

Confirm the layout contains a defensible contribution beyond copying competitor headings.

### Evidence readiness

Flag any section that requires research not yet supported by the research pack.

### Cannibalization

Stop when the layout creates materially overlapping intent with an existing page unless the approved action is refresh/consolidate/differentiate.

## Outcome

Use:

- LAYOUT_APPROVED
- LAYOUT_APPROVED_WITH_WARNING
- LAYOUT_REVISION_REQUIRED
- BLOCK_MISSING_CONTEXT
- BLOCK_DUPLICATION_RISK
- BLOCK_UNSUPPORTED_RESEARCH_NEED

## Output

Return:

- Layout status
- Passed checks
- Gaps
- Required changes
- Evidence requirements
- Human-review requirement

Do not start drafting when the layout has a `BLOCK` outcome.
