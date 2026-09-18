# Content Rulebook and Governance

## Purpose

Apply the baseline Phase 1 content rules across research, drafting, validation, approval, publishing, and monitoring.

## Search/AI system rule

Apply [08-google-search-ranking-systems.md](08-google-search-ranking-systems.md) and [09-ai-llm-discovery-visibility.md](09-ai-llm-discovery-visibility.md) where relevant. Do not optimize for guessed algorithms, hidden weights, AI-detector scores, or unverified GEO/AEO hacks.

## Baseline rules

### G-01 Business objective must be known

Identify whether the asset supports traffic, authority, leads, conversion, awareness, or another approved objective.

Use `BLOCK` when the objective is unavailable for strategy-level work.

### G-02 Target audience must be defined

Identify ICP/persona, geography, and search/use context.

Use `WARNING` or `BLOCK` depending on how much the missing audience context affects the task.

### G-03 Brand context must be retrieved

Load approved positioning, services, terminology, messaging, and restrictions from client/property context.

Use `BLOCK` for publication when required brand context is missing.

### G-04 Never fabricate information

Do not invent statistics, customers, capabilities, quotations, results, awards, credentials, or facts.

Use `BLOCK` for fabrication.

### G-05 Claims require evidence

Associate material factual claims with reliable support.

Use `BLOCK` for unsupported material claims.

### G-06 Human approval controls publishing

Allow agents to research, draft, validate, and recommend. Publish only within configured authority.

Use `BLOCK` for unauthorized publication.

### G-07 Maintain auditability

Record sources, decisions, agent actions, validation outcomes, approvals, and publication actions.

### G-08 Avoid blind automation

Escalate ambiguous or high-risk decisions to human review.

### G-09 Quality overrides volume

Do not optimize output count at the expense of usefulness, evidence, brand fit, or correctness.

### G-10 Avoid duplicate work

Retrieve existing content/research before creating a new asset.

Use `WARNING` when duplicate effort is likely.

## Product-level golden rules

Apply these principles across the operating system:

- Never fabricate.
- Never optimize blindly for a metric.
- Put evidence before recommendation.
- Put business relevance before SEO volume.
- Put relevance before backlink authority.
- Put user value before keyword density.
- Retrieve before generating.
- Recommend before executing when judgment is required.
- Use human expertise for ambiguity.
- Make important AI decisions explainable.
- Make external actions auditable.
- Use expert feedback to improve future recommendations.
- Automate repetition, not accountability.
- Never sacrifice quality for output volume.
- Measure whether automation actually saves time.

## Rule precedence

Apply:

`Platform -> Agency -> Client -> Property -> Asset/Activity -> Reviewer decision`

A lower layer may narrow a rule when allowed, but must not weaken non-fabrication, evidence, authorization, or auditability requirements.

## Handoff

Use [87-content-validation-gate.md](87-content-validation-gate.md) to enforce PASS/WARNING/BLOCK outcomes and [89-content-human-confidence-governance.md](89-content-human-confidence-governance.md) for human escalation.
