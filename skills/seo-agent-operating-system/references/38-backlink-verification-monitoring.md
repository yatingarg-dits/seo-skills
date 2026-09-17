# Backlink Verification, Indexing, and Monitoring

## Purpose

Verify that a created backlink exists as expected and monitor whether it remains useful over time.

## Initial verification

Check:

- Live page URL
- Page loads successfully
- Correct client target URL
- Correct anchor/placement
- Link is clickable
- Link attribute if relevant
- Page robots directive
- Canonical behavior
- Content published as approved or note changes
- Publisher changed/removed content

## Indexation check

Record:

- Indexation status when verifiable
- Check date
- Evidence/source

Do not equate immediate non-indexation with permanent failure. Follow the team-approved recheck schedule.

If no schedule exists, return `NEEDS_HUMAN_RULE` for timing rather than inventing one.

## Ongoing monitoring

Track:

- Link live/lost
- Target URL changed
- Anchor changed
- Page removed
- Page redirected
- Domain expired/offline
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
- Unknown

Then decide:

- Reclaim/outreach
- Replace opportunity
- Update internal record only
- No action

## Output record

Store:

- Domain
- Live page URL
- Target URL
- Anchor
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
