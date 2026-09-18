# Content Human-in-the-Loop and Confidence Governance

## Purpose

Separate work agents can execute, deterministic checks rules can approve, decisions experts should validate, and actions humans must control.

## Agent can execute

Allow agents to perform repetitive/supporting work such as:

- Topic/SERP research collection
- Source discovery
- Existing-content retrieval
- Clustering/duplicate detection
- Draft briefs/layouts
- Internal-link suggestions
- Preliminary content QA
- Formatting/required-field checks

## Agent + deterministic rules can approve

Allow configured rule-based approval for checks such as:

- Missing required fields
- Broken links
- Duplicate URLs
- Formatting requirements
- Required metadata presence
- Known deterministic publication-verification checks

Do not use deterministic approval for ambiguous strategy or factual judgment.

## Expert should validate

Require expert validation for:

- Strategy
- Business positioning
- Ambiguous evidence
- High-value content
- Brand/marketing claims
- Controversial recommendations
- Sensitive factual interpretation
- Important content differentiation decisions

## Human must control

Keep humans responsible for:

- Final strategic accountability
- High-risk external actions until governance explicitly permits automation
- Publishing when approval policy requires it
- Exception approval
- Changes to platform/agency/client rules

## Confidence format

For every important recommendation return:

`Recommendation + Evidence + Confidence + Reason + Risk + Required Human Action`

Example structure:

- Recommendation: revise a claim or section
- Evidence: supporting source/rule
- Confidence: percentage or configured confidence label
- Reason: why the recommendation follows
- Risk: what could go wrong if ignored
- Required Human Action: none / review / approve / decide

Do not use confidence as a substitute for evidence.

## Escalation triggers

Escalate when:

- Evidence conflicts
- Evidence is insufficient
- Client/brand rule is unclear
- High-risk claim lacks strong support
- Content affects strategic positioning
- Validation has `WARNING` requiring expert judgment
- Execution exceeds configured authority

## Feedback learning

Record expert corrections so future recommendations can improve, but do not convert one reviewer preference into a global rule automatically.

Classify feedback scope as:

- ASSET_EXCEPTION
- PROPERTY_RULE_CANDIDATE
- CLIENT_RULE_CANDIDATE
- AGENCY_RULE_CANDIDATE
- PLATFORM_RULE_CANDIDATE

Require approved governance before promoting feedback into a persistent rule.
