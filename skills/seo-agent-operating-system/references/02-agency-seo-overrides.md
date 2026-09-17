# Agency SEO Overrides

## Purpose

Store agency-level rules that intentionally modify or narrow platform defaults across the agency's clients.

Keep this layer separate even when no overrides exist yet.

## Context hierarchy

Use:

`Platform -> Agency -> Client -> Property`

The platform layer defines generic operating behavior. The agency layer may override only rules that the platform allows to be overridden.

## Possible agency overrides

Capture only approved rules, such as:

- Preferred tools/data providers
- Standard report/output formats
- Internal approval points
- Agency-wide backlink restrictions
- Agency-wide paid/free opportunity policy
- Standard naming conventions
- Standard severity definitions
- Standard feedback taxonomy
- Standard QA requirements
- Client onboarding requirements

## Conflict handling

For every override record:

- Platform rule being overridden
- Agency rule
- Reason
- Approved by
- Effective date
- Scope

If an override is not explicitly approved, keep the platform rule.

If precedence is unclear, return `NEEDS_HUMAN_RULE`.

## Empty-state behavior

If the agency has no overrides, record `NO_AGENCY_OVERRIDES` and continue with platform rules plus client/property context.

Do not invent agency policy to fill an empty layer.

## Handoff

Load [03-client-context.md](03-client-context.md) and [04-property-context.md](04-property-context.md) for client-specific execution.
