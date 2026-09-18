# Content Creation Contract

## Purpose

Define the complete input contract a writer/content agent must receive before drafting and the rules it must follow during generation.

## Required content contract

Provide:

`Audience + Objective + Intent + Brand Voice + Brief + Evidence + Product/Service Context + CTA + Restrictions`

Do not draft when a missing contract field creates a material risk of incorrect positioning, fabricated claims, or wrong audience/intent.

## Inputs

Load as applicable:

- [03-client-context.md](03-client-context.md)
- [04-property-context.md](04-property-context.md)
- [05-author-brand-identity.md](05-author-brand-identity.md)
- [06-client-content-style-rules.md](06-client-content-style-rules.md)
- [50-seo-content-brief.md](50-seo-content-brief.md)
- [57-content-source-research-reliability.md](57-content-source-research-reliability.md)
- [58-content-layout-validation.md](58-content-layout-validation.md)

## Creation rules

1. Write for the intended reader, not the algorithm.
2. Answer the primary question/need clearly.
3. Avoid unnecessary generic introductions.
4. Remove filler.
5. Do not repeat ideas to increase length.
6. Use specific explanations when evidence supports them.
7. Distinguish fact from recommendation/opinion.
8. Never manufacture client experience.
9. Never manufacture product/service capabilities.
10. Never manufacture results, customers, statistics, quotations, or credentials.
11. Do not overstate expertise.
12. Preserve approved terminology.
13. Maintain logical narrative progression.
14. Explain technical concepts at the level appropriate for the audience.
15. Include evidence where the brief/research requires it.
16. Match the CTA to reader intent and business objective.
17. Do not automatically imitate competitor language, structure, or claims.

## Length/depth rule

Use the depth required to satisfy the user need and business objective. Do not inflate content to match competitor word counts.

## Draft status

Use:

- DRAFT_CREATED
- DRAFT_BLOCKED_MISSING_CONTEXT
- DRAFT_BLOCKED_MISSING_EVIDENCE
- DRAFT_NEEDS_EXPERT_INPUT

## Output record

Store:

- Asset/topic
- Brief/layout version
- Research-pack version
- Draft version
- Author/agent
- Missing inputs
- Known risks
- Next validation stage

## Handoff

Send the draft to [86-content-quality-ai-originality.md](86-content-quality-ai-originality.md), then [85-content-linking.md](85-content-linking.md) and [51-seo-content-review.md](51-seo-content-review.md) as required by the workflow.
