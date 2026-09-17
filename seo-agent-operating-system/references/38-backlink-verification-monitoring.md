# Backlink Verification, Indexing, and Monitoring

## Purpose

Verify that a created backlink or link-bearing off-page activity exists as expected and monitor whether it remains useful over time.

## Initial verification

Load the activity file from [59-offpage-activity-map.md](59-offpage-activity-map.md) so verification matches the expected outcome for that activity.

Check:

- Live page/post/profile/listing URL
- Page loads successfully
- Correct client target URL
- Correct anchor/placement when applicable
- Link is clickable
- Link attribute if relevant
- Page robots directive
- Canonical behavior
- Content/profile/media published as approved or note changes
- Publisher/platform changed or removed content

## Indexation check

Record:

- Indexation status when verifiable
- Check date
- Evidence/source

Do not equate immediate non-indexation with permanent failure. Follow the team-approved recheck schedule.

If no schedule exists, return `NEEDS_HUMAN_RULE` rather than inventing a timing threshold.

## Ongoing monitoring

Track as applicable:

- Link live/lost
- Target URL changed
- Anchor changed
- Page/post/profile removed
- Page redirected
- Domain/platform unavailable
- Link attribute changed
- Page becomes non-indexable
- Publisher becomes paid/restricted
- Major quality/risk change

## Lost-link handling

Classify reason where possible:

- Page deleted
- Link removed
- Domain offline
- Publisher edit
- Site migration
- Target URL issue
- Account/profile removal
- Unknown

Then decide:

- Reclaim/outreach
- Replace opportunity
- Update internal record only
- No action

## Output record

Store:

- Domain/platform
- Activity type
- Live page/post/profile/listing URL
- Target URL
- Anchor when applicable
- Link attribute
- First live date
- Last checked date
- Indexation status
- Live/lost status
- Change detected
- Recommended action

## Handoff

Send quality/execution outcomes to [39-backlink-feedback-learning.md](39-backlink-feedback-learning.md).

For client-page indexing/ranking effects use [53-indexing-monitoring.md](53-indexing-monitoring.md).
