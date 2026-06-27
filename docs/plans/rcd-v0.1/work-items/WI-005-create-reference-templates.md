# WI-005 — Create Reference Templates

## Status

Planned

## Purpose

Create lightweight reference templates for RCD Plans and Work Items.

Templates should help teams start quickly without forcing every feature into a large document structure.

## Problem

A methodology without templates is harder to adopt. A methodology with bloated templates becomes paperwork.

RCD needs templates that guide useful thinking while staying small enough to use on normal business application work.

## Output

Create initial files under `templates/`.

Expected starting templates:

- `templates/plan-readme.template.md`
- `templates/work-item.template.md`
- `templates/architecture.template.md`
- `templates/decisions.template.md`

## Scope

This Work Item includes:

- creating the initial Plan README template
- creating the initial Work Item template
- creating optional architecture and decisions templates
- keeping optional templates clearly marked as optional
- aligning templates with the RCD philosophy

## Out of Scope

This Work Item does not include:

- examples
- AI skill instructions
- generated indexes
- metadata schemas
- project management templates

## Acceptance Criteria

- The `templates/` directory exists.
- A Plan README template exists.
- A Work Item template exists.
- Optional templates do not imply mandatory process.
- The templates are short enough to be useful on small business application features.
- The templates reinforce that Plans start small and earn structure as complexity appears.

## Implementation Notes

Default to less structure.

Templates should invite deletion of irrelevant sections. They should not make small work feel heavy.
