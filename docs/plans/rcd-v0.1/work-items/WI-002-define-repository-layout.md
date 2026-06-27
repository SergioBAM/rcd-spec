# WI-002 — Define the Repository Layout

## Status

Planned

## Purpose

Define the standard repository layout used by RCD.

The layout should make implementation knowledge easy to find without forcing unnecessary structure onto small projects.

## Problem

If every project stores plans and Work Items differently, RCD loses value. Developers and AI agents need to know where to look first.

At the same time, the layout must stay lightweight. Small features should not be forced to carry the same structure as larger efforts.

## Output

Create `spec/02-repository-layout.md`.

## Scope

This Work Item includes:

- expected location for plans
- expected structure of a plan folder
- required files and folders
- optional files and folders
- naming conventions
- small, medium, and large plan examples

## Out of Scope

This Work Item does not include:

- detailed plan template content
- detailed Work Item template content
- project management structure
- sprint or milestone structure
- Git branching strategy

## Acceptance Criteria

- `spec/02-repository-layout.md` exists.
- The document defines `docs/plans/PLAN-NAME/` as the standard plan location.
- The document states that every plan requires a `README.md`.
- The document states that Work Items live under `work-items/`.
- The document explains that `architecture.md`, `decisions.md`, and `assets/` are optional.
- The document includes examples for small, medium, and large plans.
- The document reinforces that plans start small and earn structure as complexity appears.

## Implementation Notes

Keep the layout boring and predictable.

Prefer simple directory names and Markdown files. Avoid metadata files or generated indexes unless the methodology earns them later.
