# Content Production and Monitoring Workflow

## Purpose

Before any prompt-library content is briefed or drafted, load [90-prompt-library-index.md](90-prompt-library-index.md), [91-prompt-core-direction.md](91-prompt-core-direction.md), and the exact selected format/stage prompt. Load the long-form framework and multi-brand guardrail only when required by the router. Prompt files `91-120` are immutable source text.

Run content from initial keyword/topic input through research, validation, approval, publishing, verification, indexation, ranking monitoring, and performance review.

Treat this file as the content workflow orchestrator. Load the stage-specific files only when that stage is active. For SEO content load [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md); when AI/LLM visibility is in scope also load [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md).

When a stage needs a tool, load [07-seo-content-tool-stack.md](07-seo-content-tool-stack.md) and follow its approved role/process instead of choosing a tool by convenience alone.


## Contents

- Purpose and supported inputs
- 25-stage sequence
- Critical MVP gates
- Flexible stages
- Stage-specific routing
- Audit trail
## Supported inputs

Accept:

- Keyword
- Keyword cluster
- Topic seed
- Campaign requirement
- Existing-page optimization requirement

For keyword-led SEO content, start with [15-keyword-validation-output.md](15-keyword-validation-output.md).

## Stage sequence

1. Keyword/Input Received -> `KEYWORD_RECEIVED`
2. Keyword Context Check -> `KEYWORD_VALIDATED`
3. Existing Content Check -> `EXISTING_CONTENT_CHECKED`
4. Topic Research -> `TOPIC_OPTIONS_GENERATED`
5. Topic Uniqueness Check -> `TOPIC_DIFFERENTIATION_VALIDATED`
6. Topic Selection -> `TOPIC_APPROVED`
7. SERP Research -> `SERP_RESEARCH_COMPLETE`
8. Source Research -> `RESEARCH_PACK_READY` when factual research is needed
9. Content Layout/Brief -> `LAYOUT_CREATED`
10. Layout Validation -> `LAYOUT_APPROVED`
11. Content Creation -> `DRAFT_CREATED`
12. Content Quality Check -> `CONTENT_VALIDATED`
13. Internal Linking -> `INTERNAL_LINKS_ADDED`
14. External Linking -> `EXTERNAL_SOURCES_ADDED` when needed
15. SEO Validation -> `SEO_VALIDATED` for SEO content
16. Final Content QA -> `READY_FOR_APPROVAL`
17. Approval -> `PENDING_APPROVAL`
18. Revision -> `REVISION_REQUIRED` / `REVISED`
19. Final Approval -> `APPROVED_FOR_PUBLISHING`
20. Publish -> `PUBLISHED`
21. Publication Verification -> `PUBLICATION_VERIFIED`
22. Indexation Check -> `INDEXED` / `NOT_INDEXED` / `PENDING`
23. Ranking Baseline -> `BASELINE_CAPTURED` when available
24. Ranking Monitoring -> `MONITORING_ACTIVE`
25. Performance Review -> `MONITOR` / `OPTIMIZE` / `CLOSE`

## Critical MVP gates

Do not normally move forward when any of these are incomplete:

- Keyword context
- Existing-content check
- Topic research
- Topic selection
- SERP research for SEO content
- Content layout/brief
- Layout validation
- Content creation
- Content validation
- SEO validation for SEO content
- Final QA
- Approval when configured
- Publish
- Publication verification
- Indexation check

A draft with `BLOCK` issues cannot move to approval.

A published item cannot be marked complete before publication verification.

## Flexible stages

Keep these in the workflow but do not make them universal blockers:

- External links
- Number of internal links
- Number of research sources
- Multiple approval rounds
- Client approval when not configured
- Additional expert review
- Metadata review depth
- Ranking frequency
- Ranking-monitoring duration
- Post-publication optimization

## Stage-specific routing

- Prompt selection -> [90-prompt-library-index.md](90-prompt-library-index.md)
Use:

- Topic/context/uniqueness -> [56-content-topic-research-validation.md](56-content-topic-research-validation.md)
- Source research -> [57-content-source-research-reliability.md](57-content-source-research-reliability.md)
- Brief/layout -> [50-seo-content-brief.md](50-seo-content-brief.md)
- Layout validation -> [58-content-layout-validation.md](58-content-layout-validation.md)
- Creation -> [84-content-creation-contract.md](84-content-creation-contract.md)
- Linking -> [85-content-linking.md](85-content-linking.md)
- AI/originality quality -> [86-content-quality-ai-originality.md](86-content-quality-ai-originality.md)
- Validation -> [51-seo-content-review.md](51-seo-content-review.md) and [87-content-validation-gate.md](87-content-validation-gate.md)
- Approval/revision -> [88-content-approval-revision.md](88-content-approval-revision.md)
- Confidence/human control -> [89-content-human-confidence-governance.md](89-content-human-confidence-governance.md)
- Publish/verify -> [52-onpage-implementation-publishing.md](52-onpage-implementation-publishing.md)
- Index/rank/performance -> [53-indexing-monitoring.md](53-indexing-monitoring.md)

## Audit trail

For every stage record:

- Client/property
- Asset/topic/URL
- Selected prompt file(s)/workflow stage when applicable
- Stage
- Status
- Input/evidence
- Decision
- Reason
- Agent/person responsible
- Human review status
- Timestamp/date
- Next handoff
