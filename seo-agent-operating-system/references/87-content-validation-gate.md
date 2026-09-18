# Content Validation Gate

## Purpose

Apply a consistent PASS/WARNING/BLOCK decision before approval or publishing.

The validator must explain why an item passed, warned, or failed. Do not return only a score.


## Contents

- Validation matrix
- Decision rules
- Required validation output
- Handoff
## Validation matrix

### Factual accuracy

- PASS: Supported
- WARNING: Weak evidence
- BLOCK: False or unsupported critical/material claim

### Search intent

- PASS: Strong alignment
- WARNING: Partial alignment
- BLOCK: Wrong intent

### Audience alignment

- PASS: Strong
- WARNING: Too broad/partially defined
- BLOCK: Wrong audience

### Business relevance

- PASS: Clear
- WARNING: Weak
- BLOCK: None for a strategy-led asset

### Brand alignment

- PASS: Correct
- WARNING: Minor deviation
- BLOCK: Contradictory to approved brand/client rules

### Originality

- PASS: Strong contribution
- WARNING: Generic/low information gain
- BLOCK: Duplicative/copied

### Sources

- PASS: Reliable and traceable
- WARNING: Mixed/limited evidence
- BLOCK: Fabricated sources or unsupported material claims

### SEO

- PASS: Natural and intent-aligned
- WARNING: Optimization opportunity
- BLOCK: Manipulative/unacceptable optimization

### Structure

- PASS: Logical
- WARNING: Improvements possible
- BLOCK: Fundamentally poor flow/coverage

### CTA

- PASS: Appropriate
- WARNING: Weak
- BLOCK: Misleading or wrong for intent

### Compliance/risk

- PASS: Clear
- WARNING: Review needed
- BLOCK: Violation or unresolved high-risk issue

## Decision rules

Use overall:

- `PASS` when no blocking issue exists and warnings do not require expert resolution before the next stage.
- `WARNING` when content can proceed only to configured expert/human review.
- `BLOCK` when the asset must return to revision and cannot move to approval.

A single material `BLOCK` controls the overall outcome until resolved.

## Required validation output

Return:

- Overall outcome
- Check/dimension
- Evidence/reference
- Reason
- Required change
- Confidence
- Risk
- Required human action
- Revalidation owner/status

Use [89-content-human-confidence-governance.md](89-content-human-confidence-governance.md) for confidence and escalation.

## Handoff

- BLOCK -> revision through [88-content-approval-revision.md](88-content-approval-revision.md)
- WARNING -> expert/human review
- PASS -> approval through [88-content-approval-revision.md](88-content-approval-revision.md)
