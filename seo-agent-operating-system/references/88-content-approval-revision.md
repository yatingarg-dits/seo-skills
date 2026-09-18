# Content Approval and Revision

## Purpose

Control approval, requested changes, revision, final approval, and publishing authorization.

## Inputs

Require:

- Draft/version
- [87-content-validation-gate.md](87-content-validation-gate.md) outcome
- Reviewer/approval policy
- Client/stakeholder approval requirement when configured

## Pre-approval rule

Do not send content for approval while any unresolved `BLOCK` issue exists.

`WARNING` items must follow the configured expert-review rule before approval/publishing.

## Approval states

Use:

- READY_FOR_APPROVAL
- PENDING_INTERNAL_APPROVAL
- PENDING_CLIENT_APPROVAL
- CHANGES_REQUESTED
- REVISION_IN_PROGRESS
- REVISED_PENDING_REVIEW
- APPROVED_FOR_PUBLISHING
- REJECTED
- APPROVAL_NOT_REQUIRED_BY_POLICY

## Approval process

1. Record the exact version being reviewed.
2. Identify reviewer/stakeholder.
3. Share validation warnings and unresolved assumptions.
4. Capture requested changes with reason.
5. Route changes back to the responsible writer/content lead/agent.
6. Revalidate changed sections and any affected claims/links/SEO elements.
7. Repeat review only as required by the configured policy.
8. Record final approval with reviewer and date/time.

## Revision rules

When applying feedback:

- Preserve approved facts and claims unless intentionally changed.
- Do not introduce unsupported claims while fixing another issue.
- Recheck source support when factual wording changes.
- Recheck intent/structure when sections are added/removed.
- Recheck links when URLs/sections change.
- Preserve an audit trail of meaningful reviewer changes.

## Publishing authority

Human approval controls publishing when the configured policy requires it.

Do not treat draft completion or validation PASS as publishing authorization.

## Output

Store:

- Asset/version
- Approval state
- Reviewer
- Feedback
- Revision owner
- Revision summary
- Revalidation result
- Final approval status/date
- Publishing authorization

## Handoff

Send only approved/authorized content to [52-onpage-implementation-publishing.md](52-onpage-implementation-publishing.md).
