# WI-003 — Define Plans

## Status

Planned

## Purpose

Define what a Plan is in RCD.

A Plan describes a meaningful body of implementation work and provides the durable context needed to understand, refine, and execute that work.

## Problem

Teams often spread implementation intent across chat, tickets, meeting notes, and developer memory. This makes it hard to understand what is being built and why.

RCD needs a clear definition of a Plan so teams know what belongs in the repository and what belongs in external tools.

## Output

Create `spec/03-plans.md`.

## Scope

This Work Item includes:

- defining a Plan
- explaining when to create a Plan
- explaining what every Plan must contain
- explaining what is optional
- defining how Plans relate to project management epics
- explaining how Plans stay current
- showing small, medium, and large examples

## Out of Scope

This Work Item does not include:

- detailed Work Item structure
- templates
- AI skill behaviour
- Scrum or Kanban workflow
- milestone planning

## Acceptance Criteria

- `spec/03-plans.md` exists.
- The document defines a Plan as repository-owned implementation knowledge.
- The document states that every Plan has a `README.md`.
- The document explains that a Plan may contain Work Items and optional supporting documents.
- The document explains that a Plan is not the same thing as a project management epic.
- The document explains that Plans should be updated when implementation intent changes.
- The document reinforces that Plans start small and earn structure as complexity appears.

## Implementation Notes

Keep the Plan definition practical.

The document should help a developer decide whether a piece of work needs a Plan without turning every small change into a process exercise.
