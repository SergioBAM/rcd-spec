# RCD v0.1 Plan

## Status

Draft

## Purpose

This plan defines the first usable version of Repository-Centric Development (RCD).

RCD v0.1 exists to turn the ideas behind RCD into a small, practical specification that can be used on real software projects without requiring extra explanation from the authors.

This plan also dogfoods RCD by using an RCD plan and Work Items to define RCD itself.

## Problem

Implementation knowledge naturally becomes fragmented across documentation systems, project management tools, communication platforms, and individual developer memory.

Over time, this creates knowledge silos. Those silos make handoff difficult, reduce confidence, and force developers to search through stale documents, chat history, ticket comments, and memory to understand why software exists and how it should change.

Knowledge can decay just like code. If implementation knowledge is not kept current, people stop relying on it. Once that happens, teams either duplicate the knowledge elsewhere or avoid deleting obsolete information because nobody knows whether it still matters.

RCD addresses this by making the repository the authoritative source of implementation knowledge.

## Definition of Success

RCD v0.1 is successful when an experienced software developer can read the repository and adopt RCD on a real business application without requiring additional explanation from the authors.

The developer should be able to understand:

- why RCD exists
- where plans live
- what a plan is
- what a Work Item is
- how much structure is appropriate
- what belongs in the repository versus external tools

## Core Philosophy

RCD is built on four core principles:

1. Implementation knowledge should live beside the code.
2. Implementation knowledge should evolve with the code.
3. Implementation knowledge should be easy to discover.
4. Implementation knowledge should remain current.

Everything else in RCD exists to support those principles.

## Golden 5 Rules

1. Every meaningful feature starts with a plan.
2. Plans live beside the code.
3. Work Items are executable specifications.
4. The repository is the authoritative source of implementation knowledge. Project management tools track execution.
5. Plans start small and earn structure as complexity appears.

## Scope

RCD v0.1 includes:

- the philosophy of RCD
- the standard repository layout
- the purpose and structure of plans
- the purpose and structure of Work Items
- lightweight templates
- an initial AI Project Planner skill

## Out of Scope

RCD v0.1 does not define:

- Scrum
- Kanban
- milestones
- sprint planning
- estimation
- story points
- velocity
- team management
- Git branching strategy
- pull request policy
- code style
- CI/CD standards
- release management

Those concerns may exist in a project, but they are not RCD concerns.

RCD is focused on implementation knowledge, not project management.

## Work Items

The following Work Items define the work required for RCD v0.1.

| Work Item | Title | Output |
| --- | --- | --- |
| WI-001 | Define the RCD philosophy | `spec/01-philosophy.md` |
| WI-002 | Define the repository layout | `spec/02-repository-layout.md` |
| WI-003 | Define Plans | `spec/03-plans.md` |
| WI-004 | Define Work Items | `spec/04-work-items.md` |
| WI-005 | Create reference templates | `templates/` |
| WI-006 | Create initial Project Planner skill | `skills/project-planner/SKILL.md` |

## Notes

This plan should remain small. Additional documents should only be added if the plan earns them through real complexity.

If the RCD methodology becomes awkward to use while building RCD itself, the methodology should be changed.
