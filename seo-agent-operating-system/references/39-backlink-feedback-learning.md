# Backlink Feedback and Learning

## Purpose

Capture human feedback in a structured way so future off-page/backlink recommendations improve without mixing website-quality feedback with content-quality feedback.

## Feedback stream 1: backlink/platform recommendation

Use statuses such as:

- GOOD
- BAD
- IRRELEVANT
- SPAM_RISK
- PAID
- WEBSITE_DOWN
- LOGIN_UNAVAILABLE
- OUTREACH_REQUIRED
- ALREADY_USED
- WRONG_ACTIVITY_TYPE
- OTHER

Capture domain/platform/opportunity, activity type, original recommendation, human decision, reason, date, reviewer, and whether a rule should change.

## Feedback stream 2: content recommendation

Use statuses such as:

- GOOD
- MINOR_EDIT
- MAJOR_EDIT
- WRONG_TOPIC
- WRONG_TONE
- WRONG_ANCHOR
- WRONG_TARGET_URL
- GUIDELINES_NOT_FOLLOWED
- FACTUAL_CONTEXT_ERROR
- REJECT

Capture content reference, publisher/platform, activity type, original content type, human decision, edit/rejection reason, date, and reviewer.

## Rule updates

Do not automatically convert one person's one-off feedback into a global platform rule.

Classify feedback as:

- Single-opportunity exception
- Activity-specific rule
- Publisher/platform-specific rule
- Client/property rule
- Agency override
- Platform-wide rule candidate

Require the configured human approval level before updating higher-level context.

## Paid-site handling

If a site is confirmed paid:

- Move/classify it into the paid pool.
- Do not recommend it for free-only tasks.
- Keep it available for future paid requests when otherwise qualified.

Do not permanently blacklist a legitimate paid site merely because a free workflow rejected it.

## Closed-loop handoff

Approved rule changes should update the relevant module/context:

- Discovery source rules -> 30/31
- Qualification rules -> 32
- Activity classification -> 33
- Target/anchor rules -> 34
- Content rules -> 35
- Publisher rules -> 36
- Execution rules -> 37
- Monitoring rules -> 38
- Activity-specific process -> relevant file in [59-offpage-activity-map.md](59-offpage-activity-map.md)
- Property rules -> [04-property-context.md](04-property-context.md)

## Auditability

Keep original recommendation, human feedback, and resulting rule change traceable. Never overwrite history without a record.
